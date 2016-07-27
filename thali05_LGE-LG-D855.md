#### Test 78968685da35147_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-27 08:53:42.452  5662  5662 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
07-27 08:53:42.552  5662  5662 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:53:42.553  5662  5662 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 08:53:42.614  5662  5662 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
07-27 08:53:42.638  5662  5662 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-27 08:53:42.639  5662  5662 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-27 08:53:42.658  5662  5662 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-27 08:53:42.658  5662  5662 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
07-27 08:53:42.673  1029  2328 I ActivityManager: Killing 5110:com.google.android.setupwizard/u0a46 (adj 15): empty #17
07-27 08:53:42.707  1029  1989 W libprocessgroup: failed to open /acct/uid_10046/pid_5110/cgroup.procs: No such file or directory
07-27 08:53:42.721  3412  3710 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-27 08:53:42.724  4340  5724 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-27 08:53:42.731  3412  3710 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1df25df0 on behalf of 5662
07-27 08:53:42.751  4938  4993 D InitAlarmsService: Clearing and rescheduling alarms.
07-27 08:53:42.803  1029  2016 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5725 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 08:53:42.815  4650  4665 D CalendarProvider2: Scheduling check of next Alarm
07-27 08:53:42.818  4650  4665 D CalendarProvider2: SCHEDULE_ALARM_REMOVE
07-27 08:53:42.836  5662  5662 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-27 08:53:42.860  5662  5662 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
07-27 08:53:42.978  5725  5725 D DocsApplication: Installing DEX configuration.
07-27 08:53:42.999  5725  5725 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-27 08:53:43.004  5725  5725 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1d85e1b7 com.google.android.apps.docs}
07-27 08:53:43.022  5725  5725 D TAG     : onCreate()
07-27 08:53:43.052  5725  5725 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-27 08:53:43.178  1029  2015 V SIM_STK : Menu title from STK is T-Mobile
,07-27 08:53:43.255  4340  5724 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 529 ms] updated apps [took 528 ms] 
07-27 08:53:43.594  5747  5747 D AndroidRuntime: 
07-27 08:53:43.594  5747  5747 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 08:53:43.598  5747  5747 D AndroidRuntime: CheckJNI is OFF
07-27 08:53:43.801  5747  5747 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 08:53:43.808  1029  1967 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 08:53:43.822  1970  1985 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-27 08:53:43.824  4650  4650 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
07-27 08:53:43.824  4650  4650 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
07-27 08:53:43.826  1029  1967 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-27 08:53:43.829  1029  1967 D ActivityManager: setTaskToReturnTo : TaskRecord{339d363 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 08:53:43.830  1029  1967 D ActivityManager: setTaskToReturnTo : TaskRecord{339d363 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 08:53:43.831  1029  1967 D WindowStateEx: AppWindowTokenEx init.. 
07-27 08:53:43.832   346   369 E GBMv2   : DFP En is all cleared set to be enabled
07-27 08:53:43.876  1029  1967 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5765 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 08:53:43.878  5747  5747 D AndroidRuntime: Shutting down VM
07-27 08:53:43.885  1029  1709 I ActivityManager: Killing 5147:com.lge.clock/u0a10 (adj 15): empty #17
07-27 08:53:43.963  1029  1987 W libprocessgroup: failed to open /acct/uid_10010/pid_5147/cgroup.procs: No such file or directory
07-27 08:53:44.001  1970  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-27 08:53:44.002  1970  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{188befc8 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 08:53:44.003  1970  1986 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-27 08:53:44.003  1970  1986 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13543861 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 08:53:44.042  5765  5765 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,07-27 08:53:44.143  5765  5765 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-27 08:53:44.151  5765  5765 I LibraryLoader: Loading: webviewchromium
07-27 08:53:44.154  5765  5765 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2929-2932)
,07-27 08:53:44.154  5765  5765 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:53:44.170  5765  5765 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {750d889}
,07-27 08:53:44.171  5765  5765 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:53:44.171  5765  5765 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:53:44.180  5765  5765 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 08:53:44.181  5765  5765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 08:53:44.188  5765  5790 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
07-27 08:53:44.195   315  1396 V AudioPolicyService: registerClient() client 0xb1427060, uid 10118
07-27 08:53:44.195  5765  5765 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,07-27 08:53:44.197  5765  5765 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-27 08:53:44.198  5765  5765 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-27 08:53:44.201  1029  1105 D BluetoothManagerService: Message: 20
07-27 08:53:44.201  1029  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e485cd5:true
07-27 08:53:44.202  5765  5794 D BluetoothAdapter: 39592078: getState() :  mService = null. Returning STATE_OFF
07-27 08:53:44.224  5765  5765 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:53:44.224  5765  5765 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:53:44.224  5765  5765 I Adreno-EGL: Build Date: 12/12/14 금
07-27 08:53:44.224  5765  5765 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 08:53:44.224  5765  5765 I Adreno-EGL: Remote Branch: 
07-27 08:53:44.224  5765  5765 I Adreno-EGL: Local Patches: 
07-27 08:53:44.224  5765  5765 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:53:44.256  1838  4493 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,07-27 08:53:44.300  5765  5800 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-27 08:53:44.301  5765  5765 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-27 08:53:44.320  5765  5765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 08:53:44.325  5765  5765 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 08:53:44.328  5765  5765 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 08:53:44.329  1838  4493 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-27 08:53:44.331  5765  5765 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 08:53:44.331  5765  5765 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 08:53:44.346  5765  5765 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-27 08:53:44.353  5765  5765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:53:44.353  5765  5765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 08:53:44.381  5765  5817 D OpenGLRenderer: Render dirty regions requested: true
07-27 08:53:44.381  5765  5817 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 08:53:44.392  1838  4493 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,07-27 08:53:44.402  5765  5817 D OpenGLRenderer: Enabling debug mode 0
07-27 08:53:44.424  5765  5765 D Atlas   : Validating map...
,07-27 08:53:44.428  1029  1709 D SplitWindow: check instance of lgWin Window{1c7ccfa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-27 08:53:44.484  5765  5810 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 08:53:44.484  5765  5810 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 08:53:44.593  1029  1106 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +595ms (total +761ms)
,07-27 08:53:44.594  5765  5765 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d24f8b5 time:83373
07-27 08:53:44.594  1029  1106 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f995b60 u0 com.test.thalitest/.MainActivity t40} time:83373
07-27 08:53:44.774  5765  5765 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:53:44.865  5765  5810 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-27 08:53:44.865  5765  5810 I chromium: 
,07-27 08:53:44.961  5725  5725 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:53:44.961  5725  5725 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 08:53:45.022  5765  5765 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-27 08:53:45.022  5765  5765 I chromium: 
,07-27 08:53:45.029  5765  5832 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
07-27 08:53:45.031   346   375 E GBMv2   : DFP En is all cleared set to be enabled
07-27 08:53:45.032   346   375 E GBMv2   : Set value is all cleared set the max
07-27 08:53:45.032   346   375 I GBMv2   : DFP Enabled. Ignore VFP set
07-27 08:53:45.044  5765  5832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:53:45.044  5765  5832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:53:45.044  5765  5832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:53:45.044  5765  5832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:53:45.044  5765  5832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 08:53:45.044  5765  5832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30714f69 added. We now have 1 listener(s)
,07-27 08:53:45.045  1029  1045 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:53:45.049  5765  5832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-27 08:53:45.052  5765  5832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 08:53:45.053  5765  5832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 08:53:45.053  5765  5832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:53:45.059  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 08:53:45.060  5765  5832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b7691c added. We now have 1 listener(s)
07-27 08:53:45.060  5765  5832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 08:53:45.064  1029  1399 D WifiService: New client listening to asynchronous messages
,07-27 08:53:45.065  5765  5832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:45.066  5765  5832 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-27 08:53:45.069  5765  5832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 08:53:45.069  5765  5832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:53:45.069  5765  5832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:53:45.070  5765  5832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 08:53:45.072  5765  5832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:53:45.073  1029  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:53:45.073  5765  5832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-27 08:53:45.077  5765  5832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:53:45.078  5765  5832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:53:45.078  5765  5832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:45.078  5765  5832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:45.078  5765  5832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:45.078  5765  5832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:45.078  5765  5832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:45.078  5765  5832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:45.078  5765  5832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:45.078  5765  5832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:53:45.078  5765  5832 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:53:45.079  5765  5832 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 08:53:45.123  5765  5765 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:53:45.200  5725  5725 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-27 08:53:45.223  1029  2083 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5849 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-27 08:53:45.334  5849  5849 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-27 08:53:45.353  5849  5849 I LockScreenSettings: New app installed broadcast received ..
,07-27 08:53:45.359  5849  5849 I LockScreenSettings: Number of installed packages  1
07-27 08:53:45.412  1029  2087 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5866 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-27 08:53:45.413  1029  2087 I ActivityManager: Killing 4751:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,07-27 08:53:45.533  1029  1708 W libprocessgroup: failed to open /acct/uid_10085/pid_4751/cgroup.procs: No such file or directory
,07-27 08:53:45.575  5866  5866 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:53:46.142  5765  5837 W jxcore-log: Initializing JXcore engine
07-27 08:53:46.142  5765  5837 W jxcore-log: JXcore engine is ready
,07-27 08:53:46.209  1029  2046 V SIM_STK : Menu title from STK is T-Mobile
,07-27 08:53:46.201  5837  5837 W Thread-647: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8364]" dev="sockfs" ino=8364 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-27 08:53:46.201  5837  5837 W Thread-647: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-27 08:53:46.201  5837  5837 W Thread-647: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7863]" dev="sockfs" ino=7863 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-27 08:53:46.201  5837  5837 W Thread-647: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-27 08:53:46.201  5837  5837 W Thread-647: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[28218]" dev="sockfs" ino=28218 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,07-27 08:53:46.238  5765  5837 W jxcore-log: Starting JXcore engine
,07-27 08:53:46.287  1029  1709 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5903 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 08:53:46.416  5765  5837 W jxcore-log: Platform android
07-27 08:53:46.416  5765  5837 W jxcore-log: 
07-27 08:53:46.416  5765  5837 W jxcore-log: Process ARCH arm
07-27 08:53:46.416  5765  5837 W jxcore-log: 
,07-27 08:53:46.435  1029  2083 I art     : Explicit concurrent mark sweep GC freed 22237(1065KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.569ms total 126.411ms
,07-27 08:53:46.497  5903  5903 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-27 08:53:46.497  5903  5903 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,07-27 08:53:46.503  4885  4885 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-27 08:53:46.532  4938  4938 D AlertReceiver: onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,07-27 08:53:46.538  4938  5921 D AlertService: 0 Action = android.intent.action.PROVIDER_CHANGED
07-27 08:53:46.539  4938  4938 E AgendaWidgetManager: [updateWidgets] 
07-27 08:53:46.541  4938  4938 D MonthWidgetProvider: [onReceive]
07-27 08:53:46.541  4938  4938 D CalendarWidgetProvider: [onReceive]
07-27 08:53:46.541  4938  4938 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
07-27 08:53:46.543  4938  4938 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
07-27 08:53:46.546  4938  4938 D WeekWidgetProvider: [onReceive]
07-27 08:53:46.546  4938  4938 D CalendarWidgetProvider: [onReceive]
07-27 08:53:46.546  4938  4938 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,07-27 08:53:46.549  4938  4938 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
07-27 08:53:46.765  5765  5837 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:53:46.765  5765  5837 I jxcore-log: 
07-27 08:53:46.765  5765  5837 W jxcore-log: JXcore engine is started
,07-27 08:53:46.777  5765  5832 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:53:46.784  5765  5765 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:53:47.821  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{225ec3a1 type 2 when 86583 com.android.providers.calendar} when 86583
,07-27 08:53:47.825  4650  4650 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
07-27 08:53:47.825  4650  4650 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
,07-27 08:53:47.831  4650  4650 D CalendarProvider2: CalendarProviderIntentService.onCreate()
07-27 08:53:47.831  4650  5946 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
07-27 08:53:47.831  4650  5946 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
07-27 08:53:47.832   310  5947 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 08:53:47.833  1029  1103 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 08:53:47.843  4650  5946 D CalendarProvider2: [IntentService] Release Lock
,07-27 08:53:47.851  4650  4650 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
07-27 08:53:49.082  5725  5725 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-27 08:53:49.084  1029  1967 I ActivityManager: Killing 5218:com.google.android.gm/u0a64 (adj 15): empty #17
,07-27 08:53:49.303  1029  2015 W libprocessgroup: failed to open /acct/uid_10064/pid_5218/cgroup.procs: No such file or directory
,07-27 08:53:50.167  5725  5833 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:53:50.422  1838  5522 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-27 08:53:50.427   310  5986 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 08:53:50.428  1029  1103 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 08:53:50.429  1838  5522 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-27 08:53:50.430  1838  1838 I ConfigFetchService: fetch service done; releasing wakelock
07-27 08:53:50.431  1838  1838 I ConfigFetchService: stopping self
07-27 08:53:50.439  2238  2238 I ConfigService: onDestroy
,07-27 08:53:51.272  1029  1987 I ActivityManager: Killing 5261:com.google.android.talk/u0a72 (adj 15): empty #17
,07-27 08:53:51.422  1029  2087 W libprocessgroup: failed to open /acct/uid_10072/pid_5261/cgroup.procs: No such file or directory
,07-27 08:53:51.541  4938  5921 D AlertService: Beginning updateAlertNotification
,07-27 08:53:51.567  4938  5921 D AlertService: No fired or scheduled alerts
,07-27 08:53:51.589  4938  5921 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
07-27 08:53:51.595  4938  5921 D AlarmScheduler: No events found starting within 1 week.
07-27 08:53:51.605  1029  1709 I ActivityManager: Killing 5024:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-27 08:53:51.623  4999  4999 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-27 08:53:51.624  4999  4999 W System.err: android.os.DeadObjectException
07-27 08:53:51.624  4999  4999 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 08:53:51.624  4999  4999 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 08:53:51.624  4999  4999 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-27 08:53:51.624  4999  4999 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-27 08:53:51.624  4999  4999 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 08:53:51.624  4999  4999 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 08:53:51.624  4999  4999 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:53:51.624  4999  4999 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:53:51.624  4999  4999 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:53:51.624  4999  4999 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 08:53:51.624  4999  4999 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:51.624  4999  4999 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:51.624  4999  4999 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 08:53:51.624  4999  4999 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 08:53:51.625  4999  4999 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-27 08:53:51.625  4999  4999 W System.err: android.os.DeadObjectException
07-27 08:53:51.625  4999  4999 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 08:53:51.625  4999  4999 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 08:53:51.625  4999  4999 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-27 08:53:51.625  4999  4999 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-27 08:53:51.625  4999  4999 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 08:53:51.625  4999  4999 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 08:53:51.625  4999  4999 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:53:51.625  4999  4999 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:53:51.625  4999  4999 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:53:51.625  4999  4999 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 08:53:51.626  4999  4999 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:51.626  4999  4999 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:51.626  4999  4999 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 08:53:51.626  4999  4999 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 08:53:51.626  4999  4999 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-27 08:53:51.626  4999  4999 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-27 08:53:51.853  1029  2328 W libprocessgroup: failed to open /acct/uid_1000/pid_5024/cgroup.procs: No such file or directory
07-27 08:53:51.854  1029  2328 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-27 08:53:51.864  4999  4999 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-27 08:53:51.865  4999  4999 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 08:53:51.922  1029  1570 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=5999 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 08:53:51.923  4999  4999 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-27 08:53:51.996  5999  5999 D UEI.SmartControl: Quickset Services start...
07-27 08:53:51.999  5999  5999 I UEI.SmartControl: Manufacture = LGE
07-27 08:53:51.999  5999  5999 D UEI.SmartControl: Id = LGNevo
07-27 08:53:52.000  5999  5999 D UEI.SmartControl: File observer start...
07-27 08:53:52.001  5999  5999 E UEI.SmartControl: IR Port is disabled: false
,07-27 08:53:52.003  5999  5999 D UEI.SmartControl: Starting file observer...
07-27 08:53:52.003  5999  5999 D UEI.SmartControl: Extracting JNI libs...
07-27 08:53:52.003  5999  5999 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 08:53:52.093  5999  5999 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-27 08:53:52.093  5999  5999 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 08:53:52.093  5999  5999 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-27 08:53:52.133  5999  5999 I UEI.SmartControl: --- Selecting new region: 6
07-27 08:53:52.136  5999  5999 I UEI.SmartControl: Model = LG-D855
07-27 08:53:52.137  5999  5999 D UEI.SmartControl: QS Service created
,07-27 08:53:52.155  5999  5999 I UEI.SmartControl: Service initServices...
07-27 08:53:52.159  5999  5999 D UEI.SmartControl: QS start get config
,07-27 08:53:52.222  5999  5999 D UEI.SmartControl: Loading JNI Libs...
,07-27 08:53:52.609  5999  5999 I UEI.SmartControl: Supports setup maps: true
,07-27 08:53:52.617  5999  5999 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 08:53:52.617  5999  5999 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 08:53:52.617  5999  5999 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 08:53:52.618  5999  5999 I UEI.SmartControl: ### init IR Blaster...
07-27 08:53:52.623  5999  5999 D serial_port: Configuring serial port
07-27 08:53:52.628  5999  5999 E UEI.SmartControl: UEIBLaster setting for 616
07-27 08:53:52.628  5999  5999 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 08:53:52.629  5999  5999 I UEI.SmartControl: configuring settings for MAXQ616
07-27 08:53:52.629  5999  5999 I UEI.SmartControl: Get version...
,07-27 08:53:52.646  5999  6017 D UEI.SmartControl: serial port data available: 21
,07-27 08:53:52.674  5999  5999 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-27 08:53:52.674  5999  5999 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 08:53:52.675  5999  5999 I UEI.SmartControl: QS saving settings...
07-27 08:53:52.676  5999  5999 D UEI.SmartControl: IR Blaster version: 25672567
,07-27 08:53:52.694  5999  6017 D UEI.SmartControl: serial port data available: 4
,07-27 08:53:52.726  5999  5999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-27 08:53:52.730  5999  6020 I UEI.SmartControl: Device manager: loading config....
07-27 08:53:52.730  5999  6020 D UEI.SmartControl: ----------- loading internal config...
07-27 08:53:52.738  5999  5999 E UEI.SmartControl: Services init done
07-27 08:53:52.738  5999  5999 D UEI.SmartControl: QS Service init finished
07-27 08:53:52.739  5999  5999 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 08:53:52.739  5999  5999 D UEI.SmartControl: QS Service version code: 201091
,07-27 08:53:52.742  5999  5999 D UEI.SmartControl: Service requested: Control
07-27 08:53:52.745  5999  6020 E UEI.SmartControl: Loading SETTINGS...
07-27 08:53:52.747  5999  5999 D UEI.SmartControl: Request IControl service: devices are loaded...
07-27 08:53:52.750  1029  1044 I ActivityManager: Killing 4999:com.lge.qremote/u0a112 (adj 15): empty #17
,07-27 08:53:52.772  5999  6020 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-27 08:53:52.794  5999  6019 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 08:53:52.794  5999  6019 D UEI.SmartControl: -----service ready thread exits
,07-27 08:53:52.851  1029  2016 W libprocessgroup: failed to open /acct/uid_10112/pid_4999/cgroup.procs: No such file or directory
,07-27 08:53:52.861  5999  5999 D UEI.SmartControl: Internal service binding...
07-27 08:53:53.068   334   334 E ThermalEngine: out low battery limit. 
,07-27 08:53:55.536  1029  1086 I ActivityManager: Waited long enough for: ServiceRecord{2b3c34e9 u0 com.google.android.gms/.wearable.service.WearableService}
,07-27 08:53:57.674  1029  1373 V AlarmManager: RTC_WAKEUP set : Alarm{16def076 type 0 when 1469602437663 com.android.vending} when 1469602437663
,07-27 08:53:57.725  5999  6021 D UEI.SmartControl: Internal timer expired: 1
07-27 08:53:57.725  5999  6021 D UEI.SmartControl: unbind internal service
07-27 08:53:57.728  5999  5999 D UEI.SmartControl: Service.onUnbind: IControl
07-27 08:53:57.728  5999  5999 D UEI.SmartControl: Service.onDestroy
07-27 08:53:57.728  5999  5999 D UEI.SmartControl: Lock is in USE false
07-27 08:53:57.728  5999  5999 D UEI.SmartControl: unbind internal service
07-27 08:53:57.728  5999  5999 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1f657445
07-27 08:53:57.728  5999  5999 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-27 08:53:57.728  5999  5999 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-27 08:53:57.728  5999  5999 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-27 08:53:57.728  5999  5999 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-27 08:53:57.728  5999  5999 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-27 08:53:57.728  5999  5999 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-27 08:53:57.728  5999  5999 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-27 08:53:57.728  5999  5999 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-27 08:53:57.728  5999  5999 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-27 08:53:57.728  5999  5999 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:53:57.728  5999  5999 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 08:53:57.729  5999  5999 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:57.729  5999  5999 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:57.729  5999  5999 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 08:53:57.729  5999  5999 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 08:53:57.729  5999  5999 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1f657445
07-27 08:53:57.729  5999  5999 D serial_port: close(fd = 25)
07-27 08:53:57.732  5999  5999 I UEI.SmartControl: Serial port is closed.
07-27 08:53:57.732  5999  5999 I UEI.SmartControl: Serial port is closed.
07-27 08:53:57.732  5999  5999 D UEI.SmartControl: Blaster closed
07-27 08:53:57.732  5999  5999 D UEI.SmartControl: Shut down QS...
07-27 08:53:57.732  5999  5999 D UEI.SmartControl: Stopping QS lib
07-27 08:53:57.732  5999  5999 D UEI.SmartControl: QS lib stop result = true
07-27 08:53:57.732  5999  5999 D UEI.SmartControl: Stopped QS lib
07-27 08:53:57.732  5999  5999 D UEI.SmartControl: Stopped file observer...
07-27 08:53:57.732  5999  5999 D UEI.SmartControl: QS shutdown complete
07-27 08:53:57.738  1029  1709 V SIM_STK : Menu title from STK is T-Mobile
07-27 08:53:57.832  5662  5662 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-27 08:54:00.051  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 08:54:00.051  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:54:00.051  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 08:54:00.051  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:54:00.056  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:54:00.056  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:54:00.057  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:54:00.058  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:54:02.143   303   303 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
07-27 08:54:02.143   303   303 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
07-27 08:54:02.143   303   303 I rmt_storage: wakelock acquired: 1, error no: 42
,07-27 08:54:02.143   303   908 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
07-27 08:54:02.256   303   908 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
07-27 08:54:02.256   303   908 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
07-27 08:54:02.256   303   908 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
07-27 08:54:02.256   303   908 I rmt_storage: 
,07-27 08:54:02.259   303   303 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,07-27 08:54:02.259   897   906 E Diag_Lib: [IMS_FATAL]| 3347 | 906 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
07-27 08:54:02.383  5765  5837 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:54:02.383  5765  5837 I jxcore-log: 
,07-27 08:54:02.387  5765  5837 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:54:02.387  5765  5837 I jxcore-log: 
07-27 08:54:02.389  5765  5837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:02.389  5765  5837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:54:02.389  5765  5837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:02.389  5765  5837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:54:02.389  5765  5837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:54:02.389  5765  5837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:54:02.389  5765  5837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:02.389  5765  5837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:02.389  5765  5837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:02.389  5765  5837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:02.389  5765  5837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:54:02.392  5765  5837 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:54:02.392  5765  5837 I jxcore-log: 
07-27 08:54:02.394  5765  5837 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 08:54:02.394  5765  5837 I jxcore-log: 
07-27 08:54:02.740  5765  5837 I jxcore-log: Unit Test app is loaded
07-27 08:54:02.740  5765  5837 I jxcore-log: 
,07-27 08:54:02.747  5765  5765 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-27 08:54:02.749  5765  5837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:54:02.749  5765  5837 I jxcore-log: 
07-27 08:54:02.754  1029  2015 D WifiServiceImplEx: setWifiEnabled: true pid=5765, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-27 08:54:02.755  1029  2015 D WifiService: setWifiEnabled: true pid=5765, uid=10118
07-27 08:54:02.755  1029  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 08:54:02.768  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 08:54:02.768  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 08:54:02.768  1029  1029 D Ulp_jni : JNI:system_update. Event-4
07-27 08:54:02.769  1029  1385 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-27 08:54:02.769  1029  1385 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-27 08:54:02.770  1029  1385 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-27 08:54:02.770  1029  1385 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 08:54:02.770  1029  1385 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-27 08:54:02.770  1029  1385 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 08:54:02.770  1029  1385 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-27 08:54:02.770  1029  1385 E WifiHW  : unknown target_country: EU , set to default
07-27 08:54:02.770  1029  1385 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-27 08:54:02.770  1029  1385 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-27 08:54:02.770  1029  1385 I WifiUtil: gEnableBmps=1
07-27 08:54:02.771  1029  1709 D WifiServiceImplEx: disconnect pid=5765, uid=10118, packageName=com.test.thalitest
07-27 08:54:02.771  1029  1045 D WifiServiceImplEx: reconnect pid=5765, uid=10118, packageName=com.test.thalitest
07-27 08:54:02.773  1029  2328 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:02.773  1029  2328 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-27 08:54:02.785  1029  1105 D BluetoothManagerService: Message: 1
07-27 08:54:02.785  1029  1105 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-27 08:54:02.786  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 08:54:02.786  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 08:54:02.787  1029  1029 D Ulp_jni : JNI:system_update. Event-4
07-27 08:54:02.790  5765  5837 I jxcore-log: My device name is: LGE-LG-D855
07-27 08:54:02.790  5765  5837 I jxcore-log: 
07-27 08:54:02.838  1029  1105 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6056 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-27 08:54:02.879  6056  6056 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-27 08:54:02.879  6056  6056 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:02.879  6056  6056 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-27 08:54:02.880  6056  6056 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-27 08:54:02.912  6056  6056 D BluetoothAdapterApp: Loading JNI Library
,07-27 08:54:02.951  6056  6056 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d85e1b7 Instance Count = 1
,07-27 08:54:02.962   310   888 D SoftapController: Softap fwReload - Ok
07-27 08:54:02.963  1029  1105 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 08:54:02.964  1029  1105 D Tethering: InitialState.processMessage what=4
07-27 08:54:02.965   310  6079 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,07-27 08:54:02.972   310   888 D CommandListener: Setting iface cfg
07-27 08:54:02.972   310   888 D CommandListener: Trying to bring down wlan0
07-27 08:54:02.972   310   888 D CommandListener: Clearing all IP addresses on wlan0
07-27 08:54:02.976  1029  1103 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 08:54:02.976  1029  1385 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-27 08:54:02.978  1029  1385 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 08:54:02.978  1029  1385 E WifiStateMachine: useWiFiOffloading() : false
07-27 08:54:02.978  1029  1385 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 08:54:02.971  6080  6080 W wpa_supplicant: type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:02.971  6080  6080 W wpa_supplicant: type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 08:54:03.006  1029  1086 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6081 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 08:54:03.006  1029  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-27 08:54:03.008  6080  6080 I wpa_supplicant: Successfully initialized wpa_supplicant
07-27 08:54:03.009  6056  6056 D BluetoothAdapterApp: onCreate
07-27 08:54:03.012  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-27 08:54:03.013  5765  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:54:03.013  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-27 08:54:03.013  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:03.015  1029  1385 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 08:54:03.015  1029  1385 D WifiMonitor: connecting to supplicant
,07-27 08:54:03.042  6056  6056 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-27 08:54:03.042  6056  6056 D ProfileConfigQcom: Adding HeadsetService
07-27 08:54:03.043  6056  6056 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-27 08:54:03.043  6056  6056 D ProfileConfigQcom: Adding A2dpService
07-27 08:54:03.043  6056  6056 D ProfileConfigQcom: [BTUI] HidService is supported
07-27 08:54:03.043  6056  6056 D ProfileConfigQcom: Adding HidService
07-27 08:54:03.043  6056  6056 D ProfileConfigQcom: [BTUI] HealthService is supported
07-27 08:54:03.043  6056  6056 D ProfileConfigQcom: Adding HealthService
07-27 08:54:03.043  6056  6056 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,07-27 08:54:03.044  6056  6056 D ProfileConfigQcom: [BTUI] PanService is supported
07-27 08:54:03.045  6056  6056 D ProfileConfigQcom: Adding PanService
07-27 08:54:03.045  6056  6056 D ProfileConfigQcom: [BTUI] GattService is supported
07-27 08:54:03.045  6056  6056 D ProfileConfigQcom: Adding GattService
07-27 08:54:03.045  6056  6056 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-27 08:54:03.045  6056  6056 D ProfileConfigQcom: Adding BluetoothMapService
07-27 08:54:03.045  6056  6056 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-27 08:54:03.057  6080  6080 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 08:54:03.057  6080  6080 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-27 08:54:03.066  1029  1105 D BluetoothManagerService: Message: 20
07-27 08:54:03.066  1029  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ef0eb5a:true
07-27 08:54:03.067  6056  6056 D BluetoothAdapterState: make
07-27 08:54:03.070  6056  6056 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-27 08:54:03.070  6056  6056 I bluedroid-qcom: init
,07-27 08:54:03.073  6081  6081 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:03.073  6081  6081 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-27 08:54:03.073  6081  6081 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:03.073  6081  6081 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-27 08:54:03.074  6081  6081 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 08:54:03.074  6081  6081 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-27 08:54:03.075  6056  6104 I BluetoothAdapterState: Entering OffState
07-27 08:54:03.078  6056  6056 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 08:54:03.079  6056  6056 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 08:54:03.079  6056  6056 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 08:54:03.079  6056  6056 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 08:54:03.079  6056  6056 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-27 08:54:03.081  6056  6056 I bluedroid-qcom: get_profile_interface socket
07-27 08:54:03.081  6056  6056 I bluedroid-qcom: get_profile_interface map_client
07-27 08:54:03.082  6056  6108 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-27 08:54:03.084  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-27 08:54:03.084  1029  1105 D BluetoothManagerService: Message: 40
07-27 08:54:03.084  1029  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-27 08:54:03.085  6056  6076 I bluedroid-qcom: config_hci_snoop_log
07-27 08:54:03.086  1029  1105 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-27 08:54:03.086  6056  6108 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 08:54:03.086  1029  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
07-27 08:54:03.071  6107  6107 W bdaddr_loader: type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:03.087  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 08:54:03.088  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 08:54:03.071  6107  6107 W bdaddr_loader: type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:03.089  6056  6108 D BluetoothAdapterProperties: Name is: G3
07-27 08:54:03.091  6107  6107 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-27 08:54:03.091  6107  6107 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-27 08:54:03.091  6107  6107 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-27 08:54:03.093  6056  6075 V LGMDMManagerInternal: Create singleton instance
07-27 08:54:03.093  6107  6107 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,07-27 08:54:03.096  6107  6107 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-27 08:54:03.096  6107  6107 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-27 08:54:03.134  6056  6104 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-27 08:54:03.134  6056  6104 D BluetoothAdapterProperties: Setting state to 11
,07-27 08:54:03.135  6056  6104 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 08:54:03.135  1029  1105 D BluetoothManagerService: Message: 60
07-27 08:54:03.135  1029  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-27 08:54:03.135  1029  1105 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-27 08:54:03.136  6056  6104 I LGBluetoothServiceJni: classInitNative: succeeds
07-27 08:54:03.137  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:03.138  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 08:54:03.140  6056  6104 D BluetoothBondStateMachine: make
07-27 08:54:03.142  6056  6104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.142  6056  6104 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-27 08:54:03.142  6056  6104 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.143  6056  6104 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-27 08:54:03.143  6056  6104 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-27 08:54:03.144  6056  6110 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 08:54:03.150  6056  6104 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 08:54:03.154  6056  6104 E BluetoothAdapterService: File transfer profiles supported!!
07-27 08:54:03.155  1029  1029 D BluetoothHeadset: Proxy object connected
07-27 08:54:03.155  1873  1873 D BluetoothHeadset: Proxy object connected
07-27 08:54:03.156  1873  1873 D BluetoothHeadset: Proxy object connected
07-27 08:54:03.156  1873  1873 D BluetoothHeadset: Proxy object connected
07-27 08:54:03.156  6056  6056 D HeadsetService: Received start request. Starting profile...
07-27 08:54:03.156  6056  6056 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 08:54:03.156  6056  6056 D LGBluetoothHfpAdapter: Version 1.6
07-27 08:54:03.158  6056  6104 E BluetoothAdapterService: File transfer profiles supported!!
07-27 08:54:03.158  6056  6056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 08:54:03.159  6056  6056 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 08:54:03.159  6056  6056 D HeadsetStateMachine: make
07-27 08:54:03.161  6056  6104 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 08:54:03.165  6056  6104 E BluetoothAdapterService: File transfer profiles supported!!
07-27 08:54:03.168  6056  6104 E BluetoothAdapterService: File transfer profiles supported!!
07-27 08:54:03.171  6056  6104 E BluetoothAdapterService: File transfer profiles supported!!
07-27 08:54:03.182  6080  6080 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 08:54:03.183  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 08:54:03.183  6081  6081 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 08:54:03.183  6081  6081 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 08:54:03.183  6081  6081 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 08:54:03.184  6056  6104 V LGMDMManager: Create singleton instance
07-27 08:54:03.184  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-27 08:54:03.185  6056  6104 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-27 08:54:03.186  6056  6056 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:54:03.186  6056  6056 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 08:54:03.189  6056  6056 D HeadsetStateMachine: max_hf_connections = 1
07-27 08:54:03.189  6056  6056 I bluedroid-qcom: get_profile_interface handsfree
07-27 08:54:03.190  6056  6056 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-27 08:54:03.191   315   315 V AudioPolicyService: registerClient() client 0xb54efb20, uid 1002
07-27 08:54:03.191   315  1397 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-27 08:54:03.191   315  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 08:54:03.191   315  1397 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 08:54:03.191  6056  6056 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 08:54:03.192   315  1396 V AudioFlinger: registerClient() client 0xb14331f0, pid 6056
07-27 08:54:03.192   315  1390 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:03.192   315  1390 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:03.192  1599  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:03.192  1599  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:03.192  1873  4133 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:03.192  1873  4133 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:03.192   315  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:03.193   315  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:03.193  2214  2232 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:03.193  2214  2232 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:03.193  1599  1935 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:03.193  1599  1935 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:03.193  2214  2232 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:03.193  2214  2232 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:03.193  1029  1570 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:03.193  1029  1570 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:03.193  1029  1570 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:03.193  1029  1570 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:03.193  6056  6075 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:03.193  1873  1888 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:03.193  1873  1888 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:03.193  6056  6075 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-27 08:54:03.193  6056  6075 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:03.193  6056  6075 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-27 08:54:03.193  6056  6056 V ToneGenerator: Create Track: 0xb4928a80
07-27 08:54:03.193  6056  6056 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-27 08:54:03.193  6056  6056 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-27 08:54:03.193   315  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 08:54:03.193   315  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRat,e 0, format 0, channelMask 3, flags 0
07-27 08:54:03.193   315  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 08:54:03.193   315  1397 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 08:54:03.193   315  1396 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 08:54:03.194  3329  3345 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:03.194  3329  3345 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:03.194  3329  3345 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:03.194  3329  3345 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:03.194   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 08:54:03.194   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-27 08:54:03.194   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 08:54:03.194   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 08:54:03.194  6056  6056 V AudioSystem: getLatency() output 2, latency 50
07-27 08:54:03.194  6056  6056 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 08:54:03.194  6056  6056 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 08:54:03.194   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 08:54:03.194   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 08:54:03.194   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 08:54:03.194   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 08:54:03.194   315  1397 V AudioFlinger: createTrack() lSessionId: 19
07-27 08:54:03.195  6056  6056 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-27 08:54:03.195   315   315 V AudioFlinger: acquiring 19 from 6056, for 6056
07-27 08:54:03.195   315   315 V AudioFlinger:  added new entry for 19
07-27 08:54:03.195  6056  6056 V ToneGenerator: ToneGenerator INIT OK, time: 101975
07-27 08:54:03.196  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.196  6056  6111 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-27 08:54:03.196  6056  6111 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 08:54:03.196  6056  6111 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 08:54:03.196  6056  6111 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-27 08:54:03.197  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.197   315  1397 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6056
07-27 08:54:03.197   315  1397 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-27 08:54:03.197   315  1397 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-27 08:54:03.197   315  1397 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-27 08:54:03.197   315  1397 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 08:54:03.197   315  1397 V voice   : voice_set_parameters: exit with code(0)
07-27 08:54:03.197   315  1397 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-27 08:54:03.197   315  1397 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-27 08:54:03.197   315  1397 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 08:54:03.197   315  1397 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 08:54:03.197   315  1397 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 08:54:03.197   315  1397 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-27 08:54:03.197  6056  6111 V ToneGenerator: ToneGenerator destructor
07-27 08:54:03.197  6056  6111 V ToneGenerator: stopTone
07-27 08:54:03.197  6056  6111 V ToneGenerator: Delete Track: 0xb4928a80
07-27 08:54:03.198  6056  6111 V AudioTrack: ~AudioTrack, releasing session id from 6056 on behalf of 6056
07-27 08:54:03.198   315  1397 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 08:54:03.198   315  1397 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 08:54:03.198   315  1397 V AudioFlinger: PlaybackThread::Track destructor
07-27 08:54:03.198   315   315 V AudioFlinger: releasing 19 from 6056 for 6056
07-27 08:54:03.198   315  1267 V AudioPolicyService: AudioCommandThread() waking up
07-27 08:54:03.198   315  1397 V AudioFlinger: removeClient_l() pid 6056, calling pid 315
07-27 08:54:03.198   315   315 V AudioFlinger:  decremented refcount to 0
07-27 08:54:03.198   315   315 V AudioFlinger: purging stale effects
07-27 08:54:03.198   315  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 08:54:03.198   315  1267 V AudioPolicyManager: releaseOutput() 2
07-27 08:54:03.198   315  1267 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 08:54:03.198  6081  6081 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 08:54:03.199  1029  1029 D BluetoothA2dp: Proxy object connected
07-27 08:54:03.199  6056  6056 D A2dpService: Received start request. Starting profile...
07-27 08:54:03.199  6056  6056 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 08:54:03.200  6056  6056 V Avrcp   : make
07-27 08:54:03.200  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-27 08:54:03.200  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 08:54:03.200  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 08:54:03.200  6081  6081 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 08:54:03.200  6056  6056 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-27 08:54:03.200  6056  6056 I bluedroid-qcom: get_profile_interface avrcp
07-27 08:54:03.200  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-27 08:54:03.201  6081  6081 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 08:54:03.202  1029  1044 I ActivityManager: Killing 5527:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-27 08:54:03.203  1029  2016 W Process : Unable to open /proc/6112/status
,07-27 08:54:03.207  6056  6056 V AudioManager: registerRemoteController: size of Media player list: 0
07-27 08:54:03.211  6056  6056 E AudioManager: No RCC entry present to update
07-27 08:54:03.211  6056  6056 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 08:54:03.213  6056  6056 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-27 08:54:03.213  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-27 08:54:03.213  6056  6056 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-27 08:54:03.252  6080  6080 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-27 08:54:03.256  6080  6080 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-27 08:54:03.256  6080  6080 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-27 08:54:03.258  1029  1385 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-27 08:54:03.259  1029  1385 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-27 08:54:03.259  1029  1385 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-27 08:54:03.259  1029  6116 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-27 08:54:03.259  1029  1385 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-27 08:54:03.259  1029  6116 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 08:54:03.260  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-27 08:54:03.260  1029  1385 E WifiStateMachine:  SupplicantStartingState CMD_DISCONNECT 0 0
07-27 08:54:03.260  1029  1385 E WifiStateMachine:  DefaultState CMD_DISCONNECT 0 0
07-27 08:54:03.260  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-27 08:54:03.260  1029  1385 E WifiStateMachine:  SupplicantStartingState CMD_RECONNECT 0 0
07-27 08:54:03.261  1029  6116 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-27 08:54:03.261  1029  1385 E WifiStateMachine:  DefaultState CMD_RECONNECT 0 0
07-27 08:54:03.262  1029  6116 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-27 08:54:03.262  1029  1385 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:03.263  1029  1385 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:03.263  1029  1385 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:03.264  1029  1385 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:03.264  1029  1385 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,07-27 08:54:03.265  1029  1385 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-27 08:54:03.267  1029  1385 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-27 08:54:03.267  1029  1385 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-27 08:54:03.267  1029  1385 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-27 08:54:03.292  1029  2087 W libprocessgroup: failed to open /acct/uid_10008/pid_5527/cgroup.procs: No such file or directory
,07-27 08:54:03.296  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.296  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.296  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-27 08:54:03.296  1029  1385 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 08:54:03.296  1029  1385 E WifiStateMachine: useWiFiOffloading() : false
07-27 08:54:03.296  1029  1385 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 08:54:03.298  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 08:54:03.298  6081  6081 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 08:54:03.299  6081  6081 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 08:54:03.299  6081  6081 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 08:54:03.300  1029  1385 D WifiNative-wlan0: doBoolean: SET update_config 1
07-27 08:54:03.300  1029  1385 D WifiNative-wlan0: SET update_config 1: returned true
07-27 08:54:03.300  1029  1385 D WifiConfigStore: Loading config and enabling all networks 
07-27 08:54:03.300  1029  1385 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-27 08:54:03.301  1029  1385 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,07-27 08:54:03.302  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:03.304  1970  1970 D WfdService: Waiting for WifiP2p enabling
,07-27 08:54:03.311  1029  1385 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-27 08:54:03.323  1029  1385 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-27 08:54:03.324  1029  1385 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 08:54:03.327  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-27 08:54:03.329  1029  1389 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-27 08:54:03.330  5765  5765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:03.330  5765  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:54:03.330  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:03.330  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:54:03.330  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:54:03.330  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:54:03.330  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:03.330  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:03.330  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:03.331  1029  1385 D WifiStateMachine: enableVerboseLogging : level 2
,07-27 08:54:03.331  1029  1385 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-27 08:54:03.331  1029  1385 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-27 08:54:03.331  1029  1385 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-27 08:54:03.332  5765  5765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:03.332  5765  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:54:03.332  1029  1385 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-27 08:54:03.332  1029  1385 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-27 08:54:03.332  1029  1385 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-27 08:54:03.332  1029  1385 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-27 08:54:03.333  1029  1385 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-27 08:54:03.333  1029  1385 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-27 08:54:03.333  1029  1385 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-27 08:54:03.333  1029  1385 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-27 08:54:03.334  1029  1385 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-27 08:54:03.334  1029  1385 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-27 08:54:03.334  1029  1385 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-27 08:54:03.335  1970  1970 D WfdsService: Supplicant Connection state is changed : true
07-27 08:54:03.335  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 08:54:03.335  1970  2313 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-27 08:54:03.335  1970  2313 D WfdsService: Set the WFDS Monitor: true
07-27 08:54:03.336  1029  1385 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 08:54:03.336  1029  1385 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-27 08:54:03.337  1029  1385 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-27 08:54:03.337  1029  1385 D WifiNative-HAL: Setting external_sim to 1
07-27 08:54:03.337  1029  1385 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-27 08:54:03.337  1029  1385 D WifiNative-wlan0: SET external_sim 1: returned true
07-27 08:54:03.337  1029  1385 I WifiNative-HAL: startHal
07-27 08:54:03.337  1029  1385 E wifi    : getStaticLongField sWifiHalHandle 0x9888a8dc
07-27 08:54:03.337  1029  1385 E WifiHAL : Could not connect handle
07-27 08:54:03.337  1029  1385 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0xa00f1a
07-27 08:54:03.337  1029  1385 I WifiNative-HAL: Could not start hal
07-27 08:54:03.338  1029  1385 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 08:54:03.338  1029  1385 I WifiNative-HAL: startHal
07-27 08:54:03.338  1029  1385 E wifi    : getStaticLongField sWifiHalHandle 0x9888a85c
07-27 08:54:03.338  1029  1385 E WifiHAL : Could not connect handle
07-27 08:54:03.338  1029  1385 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x500df2
07-27 08:54:03.338  1029  1385 I WifiNative-HAL: Could not start hal
07-27 08:54:03.338  1029  1385 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-27 08:54:03.338  1029  1385 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true,
07-27 08:54:03.338  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-27 08:54:03.339  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-27 08:54:03.339  1029  1385 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,07-27 08:54:03.343  1029  1029 D WifiHS20: hidePasspointNotification off =false
07-27 08:54:03.346  1970  2313 D WfdsMonitor: WfdsMonitorThread create
07-27 08:54:03.346  1970  2313 D WfdsMonitor: WFDS Monitor is created and started
07-27 08:54:03.346  1970  2313 D WfdsService: WiFi: Supplicant connection re-established
07-27 08:54:03.349  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.349  1970  6118 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-27 08:54:03.349  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.349  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 08:54:03.349  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 08:54:03.349  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:03.349  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 08:54:03.349  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:03.349  1970  6118 E CtrlSupplicant: Succeed to open control connection
07-27 08:54:03.349  1029  1385 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 08:54:03.349  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-27 08:54:03.349  1970  6118 E CtrlSupplicant: Succeed to open monitor connection
07-27 08:54:03.350  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-27 08:54:03.350  1029  1385 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-27 08:54:03.350  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 08:54:03.350  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 08:54:03.350  1029  1385 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 08:54:03.351  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 08:54:03.351  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:03.351  1970  6118 D WfdsMonitor: Supplicant connection established
07-27 08:54:03.351  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 08:54:03.351  1970  2313 D WfdsService: Connected to the supplicant for wfds
07-27 08:54:03.351  1029  1385 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 08:54:03.351  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-27 08:54:03.351  6080  6080 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-27 08:54:03.352  1029  1385 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-27 08:54:03.352  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 08:54:03.352  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 08:54:03.352  1029  1385 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 08:54:03.353  6081  6081 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 08:54:03.353  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 08:54:03.353  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 08:54:03.353  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 08:54:03.353  6081  6081 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 08:54:03.353  6081  6081 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 08:54:03.353  1029  1385 E WifiNative: : [102,118,305 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransition,s
07-27 08:54:03.353  1029  1385 D WifiNative-wlan0: doBoolean: RECONNECT
,07-27 08:54:03.357  1029  1385 D WifiNative-wlan0: RECONNECT: returned true
07-27 08:54:03.357  1029  1385 D WifiNative-wlan0: doString: [STATUS]
07-27 08:54:03.357  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-27 08:54:03.358  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-27 08:54:03.358  1029  1385 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 08:54:03.358  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 08:54:03.358  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 08:54:03.358  1029  1385 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-27 08:54:03.358  1029  1385 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 08:54:03.359  1029  1385 D WifiNative-wlan0: SET ps 1: returned true
07-27 08:54:03.359  1029  1384 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.361   310   888 D CommandListener: Setting iface cfg
07-27 08:54:03.361   310   888 D CommandListener: Trying to bring up p2p0
07-27 08:54:03.361  1029  1384 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 08:54:03.362  1029  1384 D LGWifiP2pService: P2pEnablingState
07-27 08:54:03.362  1029  1384 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.362  1029  1384 D LGWifiP2pService: P2p socket connection successful
07-27 08:54:03.362  1029  1384 D LGWifiP2pService: P2pEnabledState
07-27 08:54:03.366  1029  1399 D WifiService: New client listening to asynchronous messages
,07-27 08:54:03.373  1029  1987 V SIM_STK : Menu title from STK is T-Mobile
07-27 08:54:03.373  1029  1987 V SIM_STK : Menu title from STK is T-Mobile
07-27 08:54:03.388  1029  2016 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6120 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-27 08:54:03.405   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 303us total 17.005ms
,07-27 08:54:03.412  1029  1384 D LGWifiP2pService: sending p2p connection changed broadcast
07-27 08:54:03.415  1029  1384 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-27 08:54:03.417  1029  1385 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-27 08:54:03.418  1029  1385 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-27 08:54:03.418   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 13.183ms
,07-27 08:54:03.421  1970  1970 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-27 08:54:03.421  1970  1970 D WfdsService: WifiP2pState is changed : true
07-27 08:54:03.422  1029  1708 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-27 08:54:03.424  1970  1970 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-27 08:54:03.425  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 08:54:03.425  1029  1029 D RttService: SCAN_AVAILABLE : 3
07-27 08:54:03.425  1029  1551 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.425  1029  1551 I WifiNative-HAL: startHal
07-27 08:54:03.425  1029  1552 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.427  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-27 08:54:03.427  1970  1970 D WfdsService: isConnected: false
07-27 08:54:03.429  1029  1384 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-27 08:54:03.429  1029  1551 E wifi    : getStaticLongField sWifiHalHandle 0x94c9e99c
07-27 08:54:03.429  1029  1384 D WifiNative-p2p0: doBoolean: SET device_name G3
07-27 08:54:03.429  1029  1551 E WifiHAL : Could not connect handle
07-27 08:54:03.429  1029  1551 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x600d32
07-27 08:54:03.429  1029  1551 I WifiNative-HAL: Could not start hal
07-27 08:54:03.429  1029  1551 E WifiScanningService: could not start HAL
07-27 08:54:03.429  1029  1385 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-27 08:54:03.429  1029  1384 D WifiNative-p2p0: SET device_name G3: returned true
07-27 08:54:03.429  1029  1384 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-27 08:54:03.430  1029  1384 D LGWifiP2pService: before postfix = G3
07-27 08:54:03.430  1029  1384 D WifiServerServiceExt: postfix byte check : 2
07-27 08:54:03.430  1029  1384 D LGWifiP2pService: after postfix = G3
07-27 08:54:03.430  1029  1384 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-27 08:54:03.430  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 08:54:03.430   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 245us total 11.873ms
07-27 08:54:03.430  1970  2313 D WfdsService: Receive the WFDS_ENABLE Method
07-27 08:54:03.431  1970  2313 D WfdsService: Set the WFDS Monitor: true
07-27 08:54:03.431  1970  2313 D WfdsService: Connected to the supplicant for wfds
07-27 08:54:03.431  1970  2313 D WfdsJNI : doCommand: WFDS_SET TRUE
07-27 08:54:03.431  6080  6080 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-27 08:54:03.431  1029  1384 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-27 08:54:03.431  1970  2313 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
07-27 08:54:03.431  1029  1384 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-27 08:54:03.431  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 08:54:03.431  6080  6080 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
07-27 08:54:03.431  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 08:54:03.431  1970  2313 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
07-27 08:54:03.431  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 08:54:03.431  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 08:54:03.431  1970  2313 D WfdsService: selectPreferredScanChannel [36]
07-27 08:54:03.431  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 08:54:03.431  1970  2313 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-27 08:54:03.431  6056  6056 D LGBluetoothAvrcpQ,comAdapter: [BTUI]          displayName: Google Play Music
07-27 08:54:03.431  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 08:54:03.432  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 08:54:03.432  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 08:54:03.432  1029  1385 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-27 08:54:03.432  6056  6056 I BluetoothA2dpServiceJni: classInitNative
07-27 08:54:03.432  1029  1385 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-27 08:54:03.432  6056  6056 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:54:03.432  6056  6056 D A2dpStateMachine: make
07-27 08:54:03.432  1029  1385 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-27 08:54:03.432  1029  1385 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-27 08:54:03.433  1029  1385 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-27 08:54:03.433  6080  6080 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-27 08:54:03.433  1029  1385 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-27 08:54:03.433  1029  1385 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-27 08:54:03.433  1029  1385 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-27 08:54:03.433  1029  1385 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-27 08:54:03.434  6080  6080 E wpa_supplicant: disconnect_rssi_lvl: -100
07-27 08:54:03.434  6056  6056 I bluedroid-qcom: get_profile_interface a2dp
07-27 08:54:03.434  1029  1384 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-27 08:54:03.434  1029  1385 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
07-27 08:54:03.434  1029  1384 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-27 08:54:03.434  1029  1385 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
07-27 08:54:03.434  1029  1384 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-27 08:54:03.434  1029  1385 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
07-27 08:54:03.434  1029  1384 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-27 08:54:03.434  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-27 08:54:03.434  1029  1384 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-27 08:54:03.434  1029  1384 D WifiNative-HAL: p2pGetDeviceAddress
07-27 08:54:03.435  1029  1384 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,07-27 08:54:03.436  1029  1384 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-27 08:54:03.436  1029  1384 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-27 08:54:03.437  1029  1384 D WifiNative-p2p0: P2P_FLUSH: returned true
07-27 08:54:03.437  1029  1384 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-27 08:54:03.437  1029  1384 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-27 08:54:03.438  1029  1384 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-27 08:54:03.438  1029  1384 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-27 08:54:03.438  1029  1384 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-27 08:54:03.438  1970  1970 I WfdStateTracker: handleP2pThisDeviceChanged
07-27 08:54:03.439  1970  1970 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-27 08:54:03.439  1970  1970 D WfdsService: Update P2p Interface State: 3
07-27 08:54:03.439  6056  6137 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 08:54:03.441  6056  6056 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:54:03.441  6056  6056 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 08:54:03.442  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.442  6056  6056 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 08:54:03.444  6056  6135 D A2dpStateMachine: Enter Disconnected: -2
07-27 08:54:03.444  6056  6056 D HidService: Received start request. Starting profile...
07-27 08:54:03.444  6056  6056 I bluedroid-qcom: get_profile_interface hidhost
07-27 08:54:03.444  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.445  6056  6056 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 08:54:03.446  1029  1384 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-27 08:54:03.446  1029  1384 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-27 08:54:03.446  1029  1384 D LGWifiP2pService: InactiveState
07-27 08:54:03.446  1029  1384 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.446  1029  1384 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.447  1029  1384 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-27 08:54:03.447  6056  6056 D HealthService: Received start request. Starting profile...
,07-27 08:54:03.448  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 08:54:03.448  6080  6080 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 08:54:03.449  6080  6080 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 08:54:03.449  6080  6080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.450  6080  6080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.451  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 08:54:03.451  1029  1385 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-27 08:54:03.451  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 08:54:03.451  1029  6116 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 08:54:03.451  1029  6116 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 08:54:03.451  1029  6116 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 08:54:03.451  1029  6116 E WifiMonitor: WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.451  1029  6116 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.451  1029  6116 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.451  1029  6116 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 08:54:03.451  1029  6116 E WifiMonitor: WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.451  1970  6118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 08:54:03.451  1029  6116 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.451  1029  6116 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.451  1970  6118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 08:54:03.451  1029  1385 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-27 08:54:03.451  1029  1385 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-27 08:54:03.451  1029  1385 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-27 08:54:03.452  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-27 08:54:03.452  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 08:54:03.452  6056  6056 I bluedroid-qcom: get_profile_interface health
07-27 08:54:03.452  6080  6080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 08:54:03.452  6056  6056 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-27 08:54:03.452  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.453  6080  6080 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 08:54:03.453  6080  6080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.453  6080  6080 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.454  1970  6118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 08:54:03.454  1970  6118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 08:54:03.454  1970  6118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 08:54:03.454  1029  6116 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 08:54:03.455  1029  6116 E WifiMonitor: WifiMonitor:p2p0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 08:54:03.455  1029  6116 E WifiMonitor,: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 08:54:03.455  1029  6116 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 08:54:03.455  1029  6116 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 08:54:03.455  1029  6116 E WifiMonitor: WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.455  1029  6116 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.455  1029  6116 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.455  1029  6116 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 08:54:03.455  1029  6116 E WifiMonitor: WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.455  1029  6116 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.455  1029  6116 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 08:54:03.455  1029  1384 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-27 08:54:03.456  1029  1384 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.456  1029  1384 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.456  1029  1384 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.456  1029  1384 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.456  1029  1384 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.456  1029  1384 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.457  1970  2313 W WfdsService: DefaultState - msg [9441285] is not handled
07-27 08:54:03.457  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-27 08:54:03.457  6080  6080 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 08:54:03.458  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-27 08:54:03.458  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 08:54:03.458  1029  6116 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 08:54:03.458  1029  6116 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,07-27 08:54:03.459  1029  1385 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-27 08:54:03.459  1029  1385 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-27 08:54:03.460  1029  1385 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-27 08:54:03.460  1029  1385 D WifiNative-wlan0: doBoolean: SCAN
07-27 08:54:03.460  1029  1384 D LGWifiP2pService: InactiveState{ when=-14ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.460  1029  1384 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.460  1029  1384 D LGWifiP2pService: DefaultState{ when=-14ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.461  1029  1385 D WifiNative-wlan0: SCAN: returned false
07-27 08:54:03.461  1029  1385 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=102227  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 08:54:03.462  1029  1385 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=102228  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 08:54:03.463  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:03.463  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:03.463  1029  1385 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 08:54:03.463  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.463  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.463  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 08:54:03.464  1029  1385 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 08:54:03.464  1029  1385 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 08:54:03.464  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:03.465  1029  1384 D LGWifiP2pService: InactiveState{ when=-19ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.465  1029  1384 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.465  1029  1384 D LGWifiP2pService: DefaultState{ when=-19ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.465  1029  1384 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.465  1029  1029 E WifiServerServiceExt: No p2p device connected
07-27 08:54:03.465  1029  1384 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:03.465  1029  1385 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 08:54:03.466  1029  1385 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 08:54:03.467  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:03.467  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 08:54:03.468  6056  6056 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 08:54:03.469  6056  6056 D PanService: Received start request. Starting profile...
07-27 08:54:03.469  6056  6056 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 08:54:03.469  6056  6056 I bluedr,oid-qcom: get_profile_interface pan
07-27 08:54:03.473  6056  6056 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-27 08:54:03.473  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
,07-27 08:54:03.474  6056  6056 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-27 08:54:03.477  6056  6056 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 08:54:03.477  6056  6056 D BtGatt.GattService: Received start request. Starting profile...
07-27 08:54:03.477  6056  6056 D BtGatt.GattService: start()
07-27 08:54:03.477  6056  6056 I bluedroid-qcom: get_profile_interface gatt
07-27 08:54:03.477  6056  6056 D BtGatt.AdvertiseManager: advertise manager created
07-27 08:54:03.482  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.483  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:03.483  6056  6056 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-27 08:54:03.484  6056  6056 V BluetoothMapService: BluetoothMapBinder()
07-27 08:54:03.484  6056  6056 D BluetoothMapService: Received start request. Starting profile...
07-27 08:54:03.484  6056  6056 D BluetoothMapService: start()
,07-27 08:54:03.488  6056  6056 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-27 08:54:03.488  6056  6056 D BluetoothMapEmailAppObserver: createReceiver()
07-27 08:54:03.490  6056  6056 D BluetoothMapEmailAppObserver: initObservers()
07-27 08:54:03.490  6056  6056 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-27 08:54:03.497  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
,07-27 08:54:03.497  6056  6056 D HeadsetStateMachine: Proxy object connected
07-27 08:54:03.497  6056  6056 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-27 08:54:03.498  6056  6056 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-27 08:54:03.498  1873  1873 D BluetoothPhoneService.BluetoothLTECall:  call mBluetoothHeadset.phoneStateChanged()
07-27 08:54:03.499  6056  6111 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:54:03.499  1873  1873 W BluetoothHeadset: Proxy not attached to service
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: java.lang.Throwable
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 08:54:03.499  1873  1873 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 08:54:03.499  6056  6111 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:54:03.499  6056  6111 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:54:03.501  6056  6056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 08:54:03.501  6056  6056 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 08:54:03.502  6056  6056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:03.502  6056  6056 V BluetoothPbapReceiver: ***********state = 11
07-27 08:54:03.508  6056  6056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-27 08:54:03.510  6056  6056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 08:54:03.513  6056  6056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 08:54:03.513  6056  6056 V PanService: [BTUI] SIM Extra State :ABSENT
07-27 08:54:03.515  6056  6056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 08:54:03.517  6056  6056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-27 08:54:03.517  6056  6056 V BluetoothMapService: Handler(): got msg=1
07-27 08:54:03.518  6056  6104 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-27 08:54:03.518  6056  6104 I bluedroid-qcom: enable
07-27 08:54:03.518  6056  6104 I bt_hci_bdroid: init
07-27 08:54:03.519  6056  6149 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 08:54:03.519  6056  6149 I bt-btu  : btu_task pending for preload complete event
07-27 08:54:03.522  1029  1045 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6151 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 08:54:03.525  6056  6104 I bt_vendor: bt-vendor : init
07-27 08:54:03.525  6056  6104 I bt_vendor: bt-vendor : get_bt_soc_type
07-27 08:54:03.525  6056  6104 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-27 08:54:03.525  6056  6104 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-27 08:54:03.525  6056  6104 D bt_userial_mct: userial_init
07-27 08:54:03.525  2238  2238 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 08:54:03.526  6056  6104 D bt_hci_bdroid: set_power 1
07-27 08:54:03.526  6056  6104 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-27 08:54:03.526  6056  6104 I bt_vendor: Starting hciattach daemon
07-27 08:54:03.526  6056  6104 I bt_vendor: try to set true
07-27 08:54:03.511  6161  6161 W sh      : type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:03.511  6161  6161 W sh      : type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:03.539  6164  6164 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-27 08:54:03.541  6120  6147 W FormManager: Network not available. Please check & try again.
07-27 08:54:03.552  1029  1045 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6172 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:03.554  6120  6148 V FormManager: Network unavailable.
07-27 08:54:03.566  6120  6148 V FormManager: Network unavailable.
,07-27 08:54:03.583  1029  1925 I ActivityManager: Killing 5554:com.lge.appbox.client/u0a11 (adj 15): empty #17
07-27 08:54:03.586  6194  6194 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-27 08:54:03.592  6195  6195 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-27 08:54:03.602  6197  6197 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 08:54:03.611  6198  6198 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-27 08:54:03.616  6199  6199 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 08:54:03.619  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 08:54:03.622  6202  6202 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
07-27 08:54:03.639  6204  6204 I libmdmdetect: ESOC framework not supported
,07-27 08:54:03.640  6204  6204 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
07-27 08:54:03.645  6204  6204 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-27 08:54:03.645  6204  6204 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-27 08:54:03.645  6204  6204 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-27 08:54:03.645  6204  6204 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-27 08:54:03.645  6204  6204 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-27 08:54:03.645  6204  6204 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-27 08:54:03.645  6204  6204 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,07-27 08:54:03.655  1029  1570 W libprocessgroup: failed to open /acct/uid_10011/pid_5554/cgroup.procs: No such file or directory
07-27 08:54:03.679  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:54:03.690  1029  1399 D WifiService: New client listening to asynchronous messages
07-27 08:54:03.718  6172  6172 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-27 08:54:03.718  6172  6172 W LG Account v2.2: No ProfileInfo entries
07-27 08:54:03.718  6172  6172 I LG Account v2.2: isEnabled: false
07-27 08:54:03.718  6172  6172 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-27 08:54:03.718  6172  6172 I Feature : [Lifetracker]Country: EU
07-27 08:54:03.718  6172  6172 I Feature : [Lifetracker]Operator: OPEN
07-27 08:54:03.718  6172  6172 I Feature : [Lifetracker]Ranking support: false
07-27 08:54:03.719  6172  6172 I Feature : [Lifetracker]Comfort support: false
07-27 08:54:03.719  6172  6172 I Feature : [Lifetracker]Accessory: true
07-27 08:54:03.719  6172  6172 I Feature : [Lifetracker]Health device: true
07-27 08:54:03.719  6172  6172 I Feature : [Lifetracker]Extra Pedometer: false
07-27 08:54:03.719  6172  6172 I Feature : [Lifetracker]Blood glucose device: false
07-27 08:54:03.719  6172  6172 I Feature : [Lifetracker]Device Number: 3
07-27 08:54:03.720  6081  6081 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:54:03.720  6081  6081 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 08:54:03.728  1029  2328 I ActivityManager: Killing 5576:com.android.contacts/u0a19 (adj 15): empty #17
07-27 08:54:03.728  6081  6081 D WiFiOffLoadUpdatePriority: remove : truetruetrue
07-27 08:54:03.732  1029  1385 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
07-27 08:54:03.733  1029  1385 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,07-27 08:54:03.739  1029  1385 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
07-27 08:54:03.739  1029  1385 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
07-27 08:54:03.739  1029  1385 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 08:54:03.751  1029  1385 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-27 08:54:03.752  6081  6081 D WiFiOffLoadUpdatePriority: remove1
07-27 08:54:03.752  6081  6081 V WiFiOffLoadSharedPrefsUtils: save remove
07-27 08:54:03.758  6081  6081 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
07-27 08:54:03.758  6081  6081 D WiFiOffLoadBroadcast: S: false, R: false
07-27 08:54:03.759  1029  1385 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
07-27 08:54:03.759  1029  1385 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
07-27 08:54:03.759  6081  6081 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
07-27 08:54:03.759  6081  6081 D WiFiOffLoadUpdatePriority: connected SSID: null
07-27 08:54:03.760  6081  6081 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
07-27 08:54:03.761  1029  2329 D WifiServiceImplEx: addOrUpdateNetwork pid=6081, uid=1000, packageName=android.uid.system:1000
07-27 08:54:03.762  1029  2329 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
,07-27 08:54:03.763  1029  1385 E WifiStateMachine:  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
07-27 08:54:03.763  1029  1385 E WifiStateMachine:  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
07-27 08:54:03.763  1029  1385 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
07-27 08:54:03.763  1029  1385 D WifiServerServiceExt: addOrUpdateNetwork: mThisIsFirstEnableing = false
07-27 08:54:03.763  1029  1385 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 ssid 4e47373030
07-27 08:54:03.776  1029  1385 D WifiNative-wlan0: SET_NETWORK 0 ssid 4e47373030: returned true
07-27 08:54:03.776  1029  1385 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,07-27 08:54:03.776  1029  1385 D WifiNative-wlan0: SET_NETWORK 0 key_mgmt WPA-PSK: returned true
07-27 08:54:03.776  1029  1385 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 proto WPA RSN
07-27 08:54:03.777  1029  1385 D WifiNative-wlan0: SET_NETWORK 0 proto WPA RSN: returned true
07-27 08:54:03.777  1029  1385 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
07-27 08:54:03.777  1029  1385 D WifiNative-wlan0: SET_NETWORK 0 pairwise TKIP CCMP: returned true
07-27 08:54:03.777  1029  1385 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
07-27 08:54:03.778  1029  1385 D WifiNative-wlan0: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
07-27 08:54:03.778  1029  1385 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 priority 300
07-27 08:54:03.778  1029  1385 D WifiNative-wlan0: SET_NETWORK 0 priority 300: returned true
07-27 08:54:03.778  1029  1385 E WifiConfigStore: will read network variables netId=0
07-27 08:54:03.782  1029  1385 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
07-27 08:54:03.782  1029  1385 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
07-27 08:54:03.793  1029  1989 W libprocessgroup: failed to open /acct/uid_10019/pid_5576/cgroup.procs: No such file or directory
,07-27 08:54:03.796  6081  6081 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
07-27 08:54:03.796  6081  6081 D WiFiOffLoadUpdatePriority: configuration updated: 0
07-27 08:54:03.796  1029  1385 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
07-27 08:54:03.796  1029  1385 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
07-27 08:54:03.796  1029  1385 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 08:54:03.809  6080  6080 E wpa_supplicant: USIM:  scard_init function
07-27 08:54:03.809  6080  6080 I wpa_supplicant: Trying to associate with SSID 'NG700'
,07-27 08:54:03.810  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-27 08:54:03.810  1029  6116 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-27 08:54:03.811  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-27 08:54:03.811  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
07-27 08:54:03.811  1029  6116 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-27 08:54:03.811  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-27 08:54:03.811  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-27 08:54:03.811  1029  1385 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 08:54:03.811  6081  6081 D WiFiOffLoadUpdatePriority: configuration saved: true
07-27 08:54:03.815  1029  1385 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
07-27 08:54:03.816  1029  1385 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
07-27 08:54:03.817  1029  1385 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
07-27 08:54:03.818  1029  1385 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
07-27 08:54:03.818  1029  1385 I WifiNative-HAL: startHal
07-27 08:54:03.818  1029  1385 E wifi    : getStaticLongField sWifiHalHandle 0x9888a8cc
07-27 08:54:03.819  1029  1385 E WifiHAL : Could not connect handle
07-27 08:54:03.819  1029  1385 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401e76
07-27 08:54:03.819  1029  1385 I WifiNative-HAL: Could not start hal
07-27 08:54:03.819  1029  1385 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-27 08:54:03.822  1029  1385 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=102588  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-27 08:54:03.827  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:03.827  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:03.828  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:03.828  1029  1385 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=102594  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 08:54:03.831  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 08:54:03.831  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.831  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 08:54:03.834  6081  6081 D BluetoothPermissionRequest: onReceive
07-27 08:54:03.834  6081  6081 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-27 08:54:03.835  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.835  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.835  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 08:54:03.838  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:03.838  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,07-27 08:54:03.847  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:03.847  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:03.848  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:03.852  1029  1105 D BluetoothManagerService: Message: 20
07-27 08:54:03.852  1029  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2747bff8:true
,07-27 08:54:03.855  1029  1045 I ActivityManager: Killing 5600:com.lge.email/u0a23 (adj 15): empty #17
07-27 08:54:03.855  6081  6081 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 08:54:03.912  6080  6080 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 08:54:03.917  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-27 08:54:03.917  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-27 08:54:03.917  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-27 08:54:03.917  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-27 08:54:03.918  1029  1385 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=102683  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 08:54:03.918  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 08:54:03.918  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 08:54:03.918  1029  1385 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=102683  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 08:54:03.919  1029  1385 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102684
07-27 08:54:03.919  1029  1385 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102684
07-27 08:54:03.919  1029  1385 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102685
07-27 08:54:03.920  1029  1385 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102685
07-27 08:54:03.920  1029  1385 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102685
07-27 08:54:03.927  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 08:54:03.927  6080  6080 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 08:54:03.927  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,07-27 08:54:03.927  6080  6080 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 08:54:03.927  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-27 08:54:03.927  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 08:54:03.930  1029  6116 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 08:54:03.930  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-27 08:54:03.930  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 08:54:03.930  1029  6116 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 08:54:03.931  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 08:54:03.931  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 08:54:03.933  1029  2015 W libprocessgroup: failed to open /acct/uid_10023/pid_5600/cgroup.procs: No such file or directory
07-27 08:54:03.934  6056  6056 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-27 08:54:03.935  1029  1105 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 08:54:03.935  1029  1385 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=102701  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 08:54:03.936  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:03.936  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-27 08:54:03.939  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:03.940  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 08:54:03.941  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:03.945  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.945  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.945  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 08:54:03.948  1029  1385 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=102713  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 08:54:03.949  1029  1385 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=102714  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 08:54:03.949  1029  1385 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=102715  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 08:54:03.950  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.950  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:03.950  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-27 08:54:03.950  1029  1385 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=102716
07-27 08:54:03.951  1029  1385 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=102716
07-27 08:54:03.952  1029  1385 D WifiNative-wlan0: doString: [STATUS]
,07-27 08:54:03.953  1029  1385 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 08:54:03.953  1029  6116 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 08:54:03.953  1029  6116 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 08:54:03.955  1029  1385 I WifiServiceExtension: setVHTCapabilityType  : false
07-27 08:54:03.965  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:03.965  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 08:54:03.966  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 08:54:03.967  6056  6056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:03.967  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:03.969  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 08:54:03.971  1029  1385 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-27 08:54:03.971  1029  1385 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-27 08:54:03.972  6056  6056 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 08:54:03.972  6056  6056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 08:54:03.972  6056  6056 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 08:54:03.974  6056  6056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:03.974  6056  6056 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,07-27 08:54:03.977  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:03.982  1029  1385 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-27 08:54:03.982  1029  1419 D ConnectivityService: Got NetworkAgent Messenger
07-27 08:54:03.983  1029  1419 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-27 08:54:03.983  1029  1419 D ConnectivityService: NetworkAgent connected
07-27 08:54:03.983  1029  1385 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 08:54:03.983  1029  1385 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 08:54:03.984  1029  1385 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 08:54:03.984  1029  1385 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 08:54:03.991  1029  1385 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 08:54:03.991  1029  1385 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 08:54:03.991  1029  1385 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,07-27 08:54:03.991  1029  1385 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 08:54:03.991  1029  1385 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 08:54:03.996  1029  1385 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 08:54:03.998   310   888 D CommandListener: Setting iface cfg
,07-27 08:54:04.010  1029  1709 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 08:54:04.012  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:04.013  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:04.013  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.013  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.013  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.013  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 08:54:04.016  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.016  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.016  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 08:54:04.019  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:04.019  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:04.019  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.020  1029  6217 D DhcpStateMachine: StoppedState
07-27 08:54:04.020  1029  1385 E WifiStateMachine: Start Dhcp Watchdog 1
07-27 08:54:04.020  1029  6217 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:04.020  1029  6217 D DhcpStateMachine: WaitBeforeStartState
07-27 08:54:04.021  1029  1385 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102786  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 08:54:04.021  1029  1385 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102786  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,07-27 08:54:04.021  1029  1385 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102787  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 08:54:04.022  1029  1385 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:04.022  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:04.023  1029  1385 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:04.023  6120  6214 W FormManager: Network not available. Please check & try again.
07-27 08:54:04.023  1029  1385 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:04.024  1029  1385 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:04.024  1029  1385 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 08:54:04.030  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:04.030  1029  1029 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-27 08:54:04.036  3090  3090 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 08:54:04.036  3090  3090 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 08:54:04.037  3090  3090 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 08:54:04.041  6120  6215 V FormManager: Network unavailable.
07-27 08:54:04.041  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:04.041  1029  1029 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-27 08:54:04.041  3090  3090 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 08:54:04.044  1029  1385 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102809  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 08:54:04.044  6120  6215 V FormManager: Network unavailable.
07-27 08:54:04.044  1029  1385 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102810  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 08:54:04.045  1029  1385 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102810  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 08:54:04.050  1029  1385 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:723628817] from screen [on:0 period:723628817]
07-27 08:54:04.050  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723628818]
07-27 08:54:04.050  1029  1385 I WifiNative-HAL: startHal
07-27 08:54:04.050  1029  1385 E wifi    : getStaticLongField sWifiHalHandle 0x9888a8bc
07-27 08:54:04.050  1029  1385 E WifiHAL : Could not connect handle
07-27 08:54:04.050  1029  1385 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102296
07-27 08:54:04.050  1029  1385 I WifiNative-HAL: Could not start hal
07-27 08:54:04.050  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:04.055  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.056  1029  1385 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.056  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.056  1029  1385 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.056  3090  6235 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 08:54:04.056  1029  1385 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.056  1029  1385 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.057  1029  1385 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.057  1029  1419 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
07-27 08:54:04.057  1029  1419 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-27 08:54:04.058  1029  1385 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
07-27 08:54:04.058  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
07-27 08:54:04.058  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-27 08:54:04.059  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:04.063  3090  6236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 08:54:04.063  3090  6236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-27 08:54:04.064  6151  6151 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 08:54:04.065  6218  6218 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:04.069  6151  6151 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 08:54:04.069  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 08:54:04.071  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:04.081  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-27 08:54:04.081  1029  1385 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-27 08:54:04.081  1029  1385 D WifiNative-wlan0: doBoolean: SET ps 0
07-27 08:54:04.081  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:04.081  1029  1385 D WifiNative-wlan0: SET ps 0: returned true
07-27 08:54:04.081  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-27 08:54:04.082  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-27 08:54:04.082  1029  1385 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-27 08:54:04.082  1029  1385 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-27 08:54:04.082  1029  1385 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 08:54:04.082  1029  1385 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 08:54:04.082  1029  1385 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
07-27 08:54:04.083  1029  1384 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@30e29a58 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:04.083  1029  1384 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@30e29a58 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:04.083  1029  6217 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:04.083  1029  6217 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-27 08:54:04.084  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:04.084  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 08:54:04.128  1029  2329 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6238 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-27 08:54:04.131  1029  2329 I ActivityManager: Killing 5636:com.android.gallery3d/u0a27 (adj 15): empty #17
07-27 08:54:04.181  2778  2778 I MusicWidget: mDelayedStopHandler : unbind
,07-27 08:54:04.244  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:04.244  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,07-27 08:54:04.256  1029  1708 W libprocessgroup: failed to open /acct/uid_10027/pid_5636/cgroup.procs: No such file or directory
07-27 08:54:04.257  2214  2214 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,07-27 08:54:04.259  2214  2214 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
07-27 08:54:04.260  2214  2214 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
07-27 08:54:04.265  2214  2214 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
07-27 08:54:04.265  2214  2214 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
07-27 08:54:04.266  2214  2214 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
07-27 08:54:04.269  2214  2214 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
07-27 08:54:04.270  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,07-27 08:54:04.272  1029  1044 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@da5c39fcom.lge.music.MediaPlaybackService$5@3d28ecec
07-27 08:54:04.273  2214  2214 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
07-27 08:54:04.274  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 08:54:04.275  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 08:54:04.276  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 08:54:04.278  2214  2214 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1f657445
07-27 08:54:04.279  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 08:54:04.281  6238  6238 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:04.281  2214  2214 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
07-27 08:54:04.281  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 08:54:04.282  2214  2214 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
07-27 08:54:04.282  2214  2214 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
07-27 08:54:04.282  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 08:54:04.283  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,07-27 08:54:04.285  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 08:54:04.286  1029  6217 D DhcpStateMachine: DHCPV4 request on wlan0
07-27 08:54:04.286  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-27 08:54:04.287  2214  2214 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,07-27 08:54:04.287  1029  6217 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-27 08:54:04.287  1029  6217 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-27 08:54:04.291  2214  2214 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
07-27 08:54:04.293  2214  2214 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
07-27 08:54:04.293  2214  2214 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
07-27 08:54:04.293  2214  2214 V MediaPlayer[Native]: reset
07-27 08:54:04.299  2214  2214 V MediaPlayer[Native]: setListener
07-27 08:54:04.299  2214  2214 V MediaPlayer[Native]: disconnect
07-27 08:54:04.299  2214  2214 V MediaPlayer[Native]: destructor
07-27 08:54:04.300   315  1397 V AudioFlinger: releasing 16 from 2214 for -1
07-27 08:54:04.300   315  1397 V AudioFlinger:  decremented refcount to 0
07-27 08:54:04.300   315  1397 V AudioFlinger: purging stale effects
,07-27 08:54:04.300  2214  2214 V MediaPlayer[Native]: disconnect
07-27 08:54:04.301  2214  2214 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
07-27 08:54:04.305  2214  2214 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
07-27 08:54:04.307  2214  2214 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
07-27 08:54:04.291  6255  6255 W dhcpcd  : type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:04.291  6255  6255 W dhcpcd  : type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:04.309  6238  6238 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-27 08:54:04.311  2214  2214 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
07-27 08:54:04.311  2214  2214 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
07-27 08:54:04.312  2214  2214 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
07-27 08:54:04.312  2214  2214 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 757397685
07-27 08:54:04.313  2214  2214 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 757397685
,07-27 08:54:04.320  2214  2214 I SmartShareClient: [SmartShareManagerClient] terminate service: 2214/MediaPlaybackService/596435539
07-27 08:54:04.321  6255  6255 I dhcpcd  : version 5.5.6 starting
07-27 08:54:04.323  6255  6255 E dhcpcd  : get_duid: m
07-27 08:54:04.323  6255  6255 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-27 08:54:04.323  6255  6255 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-27 08:54:04.331  2214  2214 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
07-27 08:54:04.331  2214  2214 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@d833b4a
,07-27 08:54:04.334  2214  2214 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
07-27 08:54:04.334  2214  2214 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
07-27 08:54:04.335  2214  2214 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
07-27 08:54:04.335  2214  2214 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
07-27 08:54:04.338  1029  2329 I ActivityManager: Killing 5435:com.android.defcontainer/u0a4 (adj 15): empty #17
07-27 08:54:04.343  6238  6238 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-27 08:54:04.344  6238  6238 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-27 08:54:04.344  6238  6238 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-27 08:54:04.344  6238  6238 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-27 08:54:04.345  6238  6238 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,07-27 08:54:04.346  6238  6238 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-27 08:54:04.347  2214  2214 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
07-27 08:54:04.351  6238  6238 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-27 08:54:04.388  6255  6255 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,07-27 08:54:04.388  6255  6255 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 08:54:04.389  6255  6255 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 08:54:04.396  6255  6255 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-27 08:54:04.396  6255  6255 D dhcpcd  : wlan0: sending REQUEST (xid 0xbc54061d), next in 3.47 seconds
07-27 08:54:04.401  1029  2015 W libprocessgroup: failed to open /acct/uid_10004/pid_5435/cgroup.procs: No such file or directory
,07-27 08:54:04.409  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 08:54:04.413  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:04.465  6255  6255 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-27 08:54:04.479  6238  6238 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 08:54:04.480  6238  6238 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,07-27 08:54:04.482  4885  4885 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 08:54:04.482  4885  4885 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-27 08:54:04.483  4885  4885 V [BNRBootReceiver]: Boot Receiver Return
07-27 08:54:04.484  6238  6238 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-27 08:54:04.487  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:04.491  6255  6255 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-27 08:54:04.491  6255  6255 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-27 08:54:04.491  6255  6255 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-27 08:54:04.491  6255  6255 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,07-27 08:54:04.491  6255  6255 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 08:54:04.492  6255  6255 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 08:54:04.492  6255  6255 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 08:54:04.492  6255  6255 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-27 08:54:04.495  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:04.496  1029  1385 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.496  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.496  1029  1385 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.496  1029  1385 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.497  1029  1385 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.497  1029  1385 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 08:54:04.497  1029  1419 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-27 08:54:04.502  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 08:54:04.509  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 08:54:04.509  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:04.510  6238  6238 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 08:54:04.511  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-27 08:54:04.515  6081  6081 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-27 08:54:04.517  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:04.525  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:04.528  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:04.533  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 08:54:04.534  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:04.535  6238  6238 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 08:54:04.541  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 08:54:04.545  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:04.549  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:04.555  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 08:54:04.555  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:04.556  6238  6238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 08:54:04.558  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 08:54:04.558  6081  6081 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 08:54:04.558  6081  6081 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 08:54:04.558  6081  6081 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 08:54:04.559  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 08:54:04.559  6081  6081 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 08:54:04.559  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-27 08:54:04.559  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 08:54:04.559  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 08:54:04.559  6081  6081 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 08:54:04.559  6081  6081 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-27 08:54:04.559  6081  6081 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 08:54:04.562  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:04.568  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:04.574  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:04.579  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 08:54:04.580  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:04.580  6238  6238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 08:54:04.582  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:04.593  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:04.603  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:04.608  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 08:54:04.608  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:04.608  6238  6238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 08:54:04.610  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:04.614  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:04.618  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 08:54:04.624  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 08:54:04.624  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:04.624  6238  6238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 08:54:04.627  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:04.631  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:04.641  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:04.649  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 08:54:04.650  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:04.651  6238  6238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 08:54:04.654  6238  6238 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-27 08:54:04.655  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-27 08:54:04.655  6238  6238 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-27 08:54:04.662  6204  6205 E QC-QMI  : qmi_client [6204] 13: failed to locate client data
07-27 08:54:04.663   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-27 08:54:04.663   479   479 E QC-QMI  : QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,07-27 08:54:04.666  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
07-27 08:54:04.690  6238  6238 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:54:04.690  6238  6238 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 08:54:04.692  1029  6217 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-27 08:54:04.692  1029  6217 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-27 08:54:04.692  1029  6217 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 08:54:04.693  1029  6217 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-27 08:54:04.693  1029  6217 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-27 08:54:04.693  1029  6217 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 08:54:04.693  1029  6217 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
07-27 08:54:04.693  1029  6217 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-27 08:54:04.693  1029  6217 D DhcpStateMachine: RunningState
07-27 08:54:04.694  1029  1385 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 08:54:04.695  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 08:54:04.696  1029  1384 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:04.696  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 08:54:04.696  1029  1384 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:04.696  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 08:54:04.697  6238  6238 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-27 08:54:04.697  1029  1385 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 08:54:04.697  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 08:54:04.697  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 08:54:04.697  6238  6238 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-27 08:54:04.698  6238  6238 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-27 08:54:04.698  6238  6238 V SoundPool: doLoad: loading sample sampleID=1
07-27 08:54:04.698  6238  6238 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 08:54:04.698  1029  1385 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-27 08:54:04.699  1029  1385 D WifiNative-wlan0: doBoolean: SET ps 1
,07-27 08:54:04.700  6238  6287 V SoundPool: Start decode
07-27 08:54:04.700  6238  6287 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-27 08:54:04.701   315   315 V MediaPlayerService: decode(23, 10857164, 17813)
,07-27 08:54:04.701   315   315 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-27 08:54:04.701   315   315 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-27 08:54:04.701   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,07-27 08:54:04.701   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-27 08:54:04.701   315   315 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-27 08:54:04.701   315   315 V MediaPlayerService: player type = 3
,07-27 08:54:04.701   315   315 V AwesomePlayer: AwesomePlayer create()
07-27 08:54:04.702   315   315 V AwesomePlayer: reset_l() 
07-27 08:54:04.702   315   315 V AwesomePlayer: cancelPlayerEvents
,07-27 08:54:04.702   315   315 V AwesomePlayer: setAudioSink() 
07-27 08:54:04.702   315   315 V AwesomePlayer: reset_l() 
07-27 08:54:04.702   315   315 V AudioCache: notify(0xb0409600, 8, 0, 0)
,07-27 08:54:04.702   315   315 V AudioCache: ignored
07-27 08:54:04.702   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 08:54:04.702   315   315 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
,07-27 08:54:04.702   315   315 V AwesomePlayer: setDataSource_l dataSource
07-27 08:54:04.702   315   315 V LGParserOSAL: SniffLGParser start
07-27 08:54:04.702   315   315 V LGParserOSAL: MainType:5, SubType=0
,07-27 08:54:04.702   315   315 V LGParserOSAL: #### check Mime : application/ogg
07-27 08:54:04.702   315   315 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-27 08:54:04.702   315   315 E MediaExtractor: Use LGExtractor :application/ogg 
,07-27 08:54:04.704  5999  5999 D UEI.SmartControl: QS Service created
,07-27 08:54:04.711  6238  6238 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-27 08:54:04.712  6238  6238 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 08:54:04.713  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,07-27 08:54:04.724  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
07-27 08:54:04.724  5999  5999 I UEI.SmartControl: Service initServices...
07-27 08:54:04.724  5999  5999 D UEI.SmartControl: QS start get config
07-27 08:54:04.724  1029  1385 D WifiNative-wlan0: SET ps 1: returned true
07-27 08:54:04.725  1029  1419 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-27 08:54:04.725  6238  6238 V LGMDMManager: Create singleton instance
07-27 08:54:04.725  1029  1385 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 08:54:04.725  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 08:54:04.725  1029  1385 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 08:54:04.726  1029  1419 D ConnectivityService: ignoring duplicate network state non-change
07-27 08:54:04.729  1029  1419 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 08:54:04.731  1029  1419 D ConnectivityService: Adding iface wlan0 to network 100
07-27 08:54:04.732  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.732  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.732  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,07-27 08:54:04.734  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.734  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.735  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 08:54:04.737  1029  1385 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-27 08:54:04.738  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 08:54:04.740  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.740  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.740  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 08:54:04.741  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 08:54:04.743  1970  1970 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-27 08:54:04.745  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.745  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:04.745  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,07-27 08:54:04.747  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:04.747  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:04.748  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.750  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:04.750  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:04.751  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.753  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:04.756  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 08:54:04.756  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 08:54:04.764   315   315 V LGParserOSAL: supported mime: application/ogg
07-27 08:54:04.764   315   315 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-27 08:54:04.764   315   315 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 08:54:04.764   315   315 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 08:54:04.764   315   315 V AwesomePlayer: AudioTrack Setting
07-27 08:54:04.764   315   315 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-27 08:54:04.764   315   315 V AwesomePlayer: setAudioSource() 
07-27 08:54:04.764   315   315 V MediaPlayerService: prepare
07-27 08:54:04.764   315   315 V AwesomePlayer: prepareAsync_l() 
07-27 08:54:04.764   315   315 V MediaPlayerService: wait for prepare
07-27 08:54:04.764   315  6288 V AwesomePlayer: onPrepareAsyncEvent() 
07-27 08:54:04.764   315  6288 V AwesomePlayer: initAudioDecoder() 
07-27 08:54:04.764   315  6288 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 08:54:04.764   315  6288 V AudioSystem: isOffloadSupported()
07-27 08:54:04.764   315  6288 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 08:54:04.764   315  6288 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 08:54:04.764   315  6288 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 08:54:04.764   315  6288 V AwesomePlayer: getUseOffload() = 0 
07-27 08:54:04.764   315  6288 V OMXCodec: OMXCodec::Create
07-27 08:54:04.764   315  6288 V OMXCodec: findMatchingCodecs()
07-27 08:54:04.764   315  6288 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-27 08:54:04.764   315  6288 V OMXCodec: matchingCodecs.size()=1
07-27 08:54:04.764   315  6288 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-27 08:54:04.769  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:04.770  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 08:54:04.770   315  6288 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-27 08:54:04.770  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.770   315  6288 V LGCodecAdapter: LG Codec Adapter start
07-27 08:54:04.770   315  6288 V OMXCodec: OMXCodec Createtor
07-27 08:54:04.770   315  6288 V OMXCodec: setComponentRole
07-27 08:54:04.770   315  6288 V OMXCodec: configureCodec protected=0
07-27 08:54:04.770   315  6288 V LGCodecAdapter: called getLGCodecSpecificData
07-27 08:54:04.770   315  6288 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-27 08:54:04.770   315  6288 V LGCodecOSAL: Called LGconfigureCodecMETA
07-27 08:54:04.770   315  6288 V LGCodecOSAL: Called LGconfigureCodecMSG
07-27 08:54:04.770   315  6288 V LGCodecOSAL: Not support LGCodec
07-27 08:54:04.770   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 08:54:04.770   315  6288 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-27 08:54:04.770   315  6288 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-27 08:54:04.770   315  6288 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 08:54:04.770   315  6288 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 08:54:04.770   315  6288 V AudioSystem: isOffloadSupported()
07-27 08:54:04.770   3,15  6288 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 08:54:04.770   315  6288 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-27 08:54:04.771   315  6288 V OMXCodec: init()
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-27 08:54:04.771   315  6288 V OMXCodec: allocateBuffers
07-27 08:54:04.771   315  6288 V OMXCodec: allocateBuffersOnPort portIndex=0
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
07-27 08:54:04.771   315  6288 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-27 08:54:04.771   315  6288 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
07-27 08:54:04.771   315  6288 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 08:54:04.772   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 08:54:04.772   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 08:54:04.772   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-27 08:54:04.772   315  6288 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 08:54:04.772   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-27 08:54:04.772   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-27 08:54:04.772   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-27 08:54:04.772   315  6288 V OMXCodec: init() mAsyncCompletion wait free! 
07-27 08:54:04.772   315  6288 V AwesomePlayer: finishAsyncPrepare_l() 
07-27 08:54:04.772   315  6288 V AudioCache: notify(0xb0409600, 5, 0, 0)
07-27 08:54:04.772   315  6288 V AudioCache: ignored
07-27 08:54:04.772   315  6288 V AudioCache: notify(0xb0409600, 1, 0, 0)
,07-27 08:54:04.772   315  6288 V AudioCache: prepared
07-27 08:54:04.772   315   315 V AudioCache: wait - success
,07-27 08:54:04.772   315   315 V MediaPlayerService: start
07-27 08:54:04.772   315   315 V AwesomePlayer: play_l() 
07-27 08:54:04.772   315   315 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-27 08:54:04.772   315   315 V AwesomePlayer: createAudioPlayer_l
07-27 08:54:04.772   315   315 V AwesomePlayer: seekAudioIfNecessary_l() 
07-27 08:54:04.772   315   315 V AwesomePlayer: startAudioPlayer_l() 
07-27 08:54:04.772   315   315 D AudioPlayer: start of Playback, useOffload 0
07-27 08:54:04.772   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 08:54:04.773   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-27 08:54:04.774   315  6290 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on output port
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-27 08:54:04.774   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-27 08:54:04.775   315   315 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-27 08:54:04.784   315   315 V AudioCache: notify(0xb0409600, 6, 0, 0)
07-27 08:54:04.784   315   315 V AudioCache: ignored
07-27 08:54:04.785   315   315 V MediaPlayerService: wait for playback complete
07-27 08:54:04.794   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.794   315  6292 V AudioCache: memcpy(0xaf006000, 0xb17fc000, 4096)
07-27 08:54:04.795   315  6292 V AudioCache: write(0x,b17fc000, 4096)
07-27 08:54:04.795   315  6292 V AudioCache: memcpy(0xaf007000, 0xb17fc000, 4096)
07-27 08:54:04.795   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.795   315  6292 V AudioCache: memcpy(0xaf008000, 0xb17fc000, 4096)
07-27 08:54:04.796   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.796   315  6292 V AudioCache: memcpy(0xaf009000, 0xb17fc000, 4096)
07-27 08:54:04.796   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.796   315  6292 V AudioCache: memcpy(0xaf00a000, 0xb17fc000, 4096)
07-27 08:54:04.796   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.796   315  6292 V AudioCache: memcpy(0xaf00b000, 0xb17fc000, 4096)
07-27 08:54:04.796   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.796   315  6292 V AudioCache: memcpy(0xaf00c000, 0xb17fc000, 4096)
07-27 08:54:04.796  6293  6293 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
07-27 08:54:04.797   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.797   315  6292 V AudioCache: memcpy(0xaf00d000, 0xb17fc000, 4096)
07-27 08:54:04.797   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.797   315  6292 V AudioCache: memcpy(0xaf00e000, 0xb17fc000, 4096)
07-27 08:54:04.797   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.797   315  6292 V AudioCache: memcpy(0xaf00f000, 0xb17fc000, 4096)
07-27 08:54:04.797   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.797   315  6292 V AudioCache: memcpy(0xaf010000, 0xb17fc000, 4096)
,07-27 08:54:04.798   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.798   315  6292 V AudioCache: memcpy(0xaf011000, 0xb17fc000, 4096)
07-27 08:54:04.798   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.798   315  6292 V AudioCache: memcpy(0xaf012000, 0xb17fc000, 4096)
07-27 08:54:04.798   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.798   315  6292 V AudioCache: memcpy(0xaf013000, 0xb17fc000, 4096)
07-27 08:54:04.798   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.798   315  6292 V AudioCache: memcpy(0xaf014000, 0xb17fc000, 4096)
07-27 08:54:04.800   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.800   315  6292 V AudioCache: memcpy(0xaf015000, 0xb17fc000, 4096)
07-27 08:54:04.800   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.800   315  6292 V AudioCache: memcpy(0xaf016000, 0xb17fc000, 4096)
07-27 08:54:04.800   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.800   315  6292 V AudioCache: memcpy(0xaf017000, 0xb17fc000, 4096)
07-27 08:54:04.800   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.800   315  6292 V AudioCache: memcpy(0xaf018000, 0xb17fc000, 4096)
07-27 08:54:04.801  1029  1419 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 08:54:04.801  1029  1419 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
07-27 08:54:04.802  1029  1419 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-27 08:54:04.802   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.802   315  6292 V AudioCache: memcpy(0xaf019000, 0xb17fc000, 4096)
07-27 08:54:04.802  1029  1419 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
07-27 08:54:04.803  1029  1419 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-27 08:54:04.803  1029  1419 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
07-27 08:54:04.803  1029  1419 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
07-27 08:54:04.803   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.803   315  6292 V AudioCache: memcpy(0xaf01a000, 0xb17fc000, 4096)
07-27 08:54:04.804   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.804   315  6292 V AudioCache: memcpy(0xaf01b000, 0xb17fc000, 4096)
07-27 08:54:04.804  1029  1419 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 08:54:04.804  1029  1419 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:04.804  1029  1419 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:04.805  1029  6216 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:04.805  1029  6216 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-27 08:54:04.805  1029  6216 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:04.805   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.805  1029  6216 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 08:54:04.805   315  6292 V AudioCache: memcpy(0xaf01c000, 0xb17fc000, 4096)
,07-27 08:54:04.806  6295  6295 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-27 08:54:04.807   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.807   315  6292 V AudioCache: memcpy(0xaf01d000, 0xb17fc000, 4096)
07-27 08:54:04.808  1029  1419 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-27 08:54:04.808  1029  1419 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:54:04.808  1029  1419 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:04.808  1029  1419 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 08:54:04.808  1029  1419 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.808  1029  1419 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-27 08:54:04.808  1029  1419 D ConnectivityService: currentScore = 0, newScore = 20
07-27 08:54:04.808  1029  1419 D ConnectivityService:    accepting network in place of null
07-27 08:54:04.808  1029  1419 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.809   310  6298 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-27 08:54:04.809  1029  1385 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.809  1029  1385 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:54:04.809  1029  1419 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
07-27 08:54:04.810  1873  1873 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.810  1873  1873 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 08:54:04.811   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.811   315  6292 V AudioCache: memcpy(0xaf01e000, 0xb17fc000, 4096)
,07-27 08:54:04.812   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.812   315  6292 V AudioCache: memcpy(0xaf01f000, 0xb17fc000, 4096)
07-27 08:54:04.813   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.813   315  6292 V AudioCache: memcpy(0xaf020000, 0xb17fc000, 4096)
07-27 08:54:04.813   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.814   315  6292 V AudioCache: memcpy(0xaf021000, 0xb17fc000, 4096)
07-27 08:54:04.814   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.814   315  6292 V AudioCache: memcpy(0xaf022000, 0xb17fc000, 4096)
07-27 08:54:04.814   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.814   315  6292 V AudioCache: memcpy(0xaf023000, 0xb17fc000, 4096)
07-27 08:54:04.815   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.815   315  6292 V AudioCache: memcpy(0xaf024000, 0xb17fc000, 4096)
07-27 08:54:04.815   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.815   315  6292 V AudioCache: memcpy(0xaf025000, 0xb17fc000, 4096)
07-27 08:54:04.816   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.816   315  6292 V AudioCache: memcpy(0xaf026000, 0xb17fc000, 4096)
07-27 08:54:04.816   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.816   315  6292 V AudioCache: memcpy(0xaf027000, 0xb17fc000, 4096)
07-27 08:54:04.817   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.817   315  6292 V AudioCache: memcpy(0xaf028000, 0xb17fc000, 4096)
07-27 08:54:04.817   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.817   315  6292 V AudioCache: memcpy(0xaf029000, 0xb17fc000, 4096)
07-27 08:54:04.818   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.818   315  6292 V AudioCache: memcpy(0xaf02a000, 0xb17fc000, 4096)
07-27 08:54:04.818   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.818   315  6292 V AudioCache: memcpy(0xaf02b000, 0xb17fc000, 4096)
07-27 08:54:04.819   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.819   315  6292 V AudioCache: memcpy(0xaf02c000, 0xb17fc000, 4096)
07-27 08:54:04.819   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.819   315  6292 V AudioCache: memcpy(0xaf02d000, 0xb17fc000, 4096)
07-27 08:54:04.820   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.820   315  6292 V AudioCache: memcpy(0xaf02e000, 0xb17fc000, 4096)
07-27 08:54:04.820   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.820   315  6292 V AudioCache: memcpy(0xaf02f000, 0xb17fc000, 4096)
07-27 08:54:04.821   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.821   315  6292 V AudioCache: memcpy(0xaf030000, 0xb17fc000, 4096)
07-27 08:54:04.821   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.821   315  6292 V AudioCache: memcpy(0xaf031000, 0xb17fc000, 4096)
07-27 08:54:04.822  1029  1419 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 08:54:04.822   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.822   315  6292 V AudioCache: memcpy(0xaf032000, 0xb17fc000, 4096)
07-27 08:54:04.822  1029  1419 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 08:54:04.822   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.822   315,  6292 V AudioCache: memcpy(0xaf033000, 0xb17fc000, 4096)
07-27 08:54:04.822  1029  1419 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-27 08:54:04.823  1029  1419 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:04.823   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.823   315  6292 V AudioCache: memcpy(0xaf034000, 0xb17fc000, 4096)
07-27 08:54:04.823  1029  1419 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-27 08:54:04.823   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.823   315  6292 V AudioCache: memcpy(0xaf035000, 0xb17fc000, 4096)
07-27 08:54:04.824  1029  1029 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-27 08:54:04.824  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 08:54:04.824  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 08:54:04.824  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 08:54:04.824  1029  1029 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
07-27 08:54:04.825   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.825   315  6292 V AudioCache: memcpy(0xaf036000, 0xb17fc000, 4096)
07-27 08:54:04.825   315  6292 V AudioCache: write(0xb17fc000, 4096)
07-27 08:54:04.825   315  6292 V AudioCache: memcpy(0xaf037000, 0xb17fc000, 4096)
07-27 08:54:04.826   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-27 08:54:04.826   315  6292 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 08:54:04.826   315  6292 V AwesomePlayer: postAudioEOS() 
07-27 08:54:04.826   315  6292 V AudioCache: write(0xb17fc000, 280)
07-27 08:54:04.826   315  6292 V AudioCache: memcpy(0xaf038000, 0xb17fc000, 280)
07-27 08:54:04.826  1029  1419 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-27 08:54:04.827   310  6299 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:04.827   310  6299 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
07-27 08:54:04.827   310  6299 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
07-27 08:54:04.827   315  6288 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-27 08:54:04.827   315  6288 V AwesomePlayer: onStreamDone
07-27 08:54:04.827   315  6288 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 08:54:04.827   315  6288 V AudioCache: notify(0xb0409600, 2, 0, 0)
07-27 08:54:04.827   315  6288 V AudioCache: playback complete
07-27 08:54:04.827   315  6288 V AwesomePlayer: pause_l() 
07-27 08:54:04.827   315  6288 V AudioCache: notify(0xb0409600, 7, 0, 0)
07-27 08:54:04.827   315  6288 V AudioCache: ignored
07-27 08:54:04.827   315  6288 V AwesomePlayer: cancelPlayerEvents
07-27 08:54:04.827   315   315 V AudioCache: wait - success
07-27 08:54:04.827   315   315 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-27 08:54:04.827   315  6288 D AudioPlayer: Pause Playback at 1068125
07-27 08:54:04.828  1029  1419 D ConnectivityService: validation of new default Network = false
07-27 08:54:04.828  1029  1419 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-27 08:54:04.828 , 1029  1103 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 08:54:04.828  1029  1419 D DSQN    : enableDataServiceNotify 
07-27 08:54:04.828  1029  1419 D DSQN    : start dsqn bin
07-27 08:54:04.830  6056  6104 I bt_vendor: bluetooth satus is on
07-27 08:54:04.830  6056  6104 D bt_hci_bdroid: preload
07-27 08:54:04.830  6056  6160 D bt_userial_mct: userial_open(port:0)
07-27 08:54:04.830  6056  6160 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-27 08:54:04.830   310  6301 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:04.830   310  6301 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
07-27 08:54:04.830  6056  6160 I bt_vendor: Done intiailizing UART
07-27 08:54:04.830  6056  6160 I bt_vendor: Done intiailizing UART
07-27 08:54:04.831  6056  6160 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-27 08:54:04.831  6056  6160 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-27 08:54:04.831  6056  6302 D bt_userial_mct: Entering userial_read_thread()
07-27 08:54:04.831  6056  6149 I bt-btu  : btu_task received preload complete event
07-27 08:54:04.831  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-27 08:54:04.831  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-27 08:54:04.832  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-27 08:54:04.833  1029  1419 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:04.834  1029  1419 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.834  1029  1419 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:04.834  1029  1419 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:04.821  6303  6303 W dsqn    : type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:04.821  6303  6303 W dsqn    : type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:04.834  1599  1808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_HCI
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 08:54:04.834  6056  6149 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 08:54:04.837  6056  6149 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 08:54:04.837  6056  6149 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 08:54:04.845   315   315 V AwesomePlayer: reset_l() 
07-27 08:54:04.845   315   315 V AudioCache: notify(0xb0409600, 8, 0, 0)
07-27 08:54:04.845   315   315 V AudioCache: ignored
07-27 08:54:04.845   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 08:54:04.845   315   315 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 08:54:04.845   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 08:54:04.845   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-27 08:54:04.845   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-27 08:54:04.845   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 08:54:04.845  6303  6303 E DSQN    : DSQN ssw
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
07-27 08:54:04.845   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 1
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-27 08:54:04.846   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 08:54:04.846   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-27 08:54:04.846   315  6290 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-27 08:54:04.846   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 08:54:04.846   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-27 08:54:04.846   315   315 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-27 08:54:04.846   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-27 08:54:04.847   315   315 D AudioPlayer: AudioPlayer releasing audio source
07-27 08:54:04.847   315   315 D AudioPlayer: AudioPlayer done releasing audio source
07-27 08:54:04.847   315   315 V AwesomePlayer: reset_l() 
07-27 08:54:04.847   31,5   315 V AwesomePlayer: cancelPlayerEvents
07-27 08:54:04.847   315   315 V AwesomePlayer: ~AwesomePlayer call
07-27 08:54:04.848   315   315 V AwesomePlayer: reset_l() 
07-27 08:54:04.848   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 08:54:04.851  6238  6287 V SoundPool: close(31)
07-27 08:54:04.851  6238  6287 V SoundPool: pointer = 0xa002f000, size = 205080, sampleRate = 48000, numChannels = 2
07-27 08:54:04.855  1029  1383 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,07-27 08:54:04.863  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 08:54:04.863  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.864  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.868   310  6298 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-27 08:54:04.871  6056  6149 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-27 08:54:04.871  6056  6149 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa023d061 
07-27 08:54:04.871  6056  6149 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa023d061 
07-27 08:54:04.873  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 08:54:04.874  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-27 08:54:04.875  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2736
07-27 08:54:04.876  6056  6108 E bt-btif : Calling BTA_HhEnable
07-27 08:54:04.876  6056  6108 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-27 08:54:04.876  6056  6108 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 08:54:04.876  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-27 08:54:04.876  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-27 08:54:04.876  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-27 08:54:04.876  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-27 08:54:04.876  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-27 08:54:04.877  6056  6108 D BluetoothAdapterProperties: Name is: G3
07-27 08:54:04.877  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 08:54:04.877  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 08:54:04.878  6056  6108 D BluetoothAdapterProperties: Scan Mode:20
07-27 08:54:04.878  6056  6108 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:54:04.878  6056  6108 D bt_hci_bdroid: postload
07-27 08:54:04.878  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
07-27 08:54:04.878  6056  6160 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 08:54:04.878  6056  6160 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 08:54:04.879  6056  6149 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-27 08:54:04.879  6056  6160 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 08:54:04.879  6056  6160 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 08:54:04.879  6056  6108 D bte_conf: Device ID record 1 : primary
07-27 08:54:04.879  6056  6108 D bte_conf:   vendorId            = 00c4
07-27 08:54:04.879  6056  6108 D bte_conf:   vendorIdSource      = 0001
07-27 08:54:04.879  6056  6108 D bte_conf:   product             = 13a1
07-27 08:54:04.879  6056  6108 D bte_conf:   version             = 1000
07-27 08:54:04.879  6056  6108 D bte_conf:   clientExecutableURL = 
07-27 08:54:04.879  6056  6108 D bte_conf:   serviceDescription  = 
07-27 08:54:04.879  6056  6108 D bte_conf:   documentationURL    = 
07-27 08:54:04.879  6056  6108 D bte_conf: bte_load_did_conf no section named DID2.
,07-27 08:54:04.882  6056  6104 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 08:54:04.882  6056  6104 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:54:04.882  6056  6104 D BluetoothAdapterProperties: State =  11
07-27 08:54:04.883  6056  6104 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-27 08:54:04.883  6056  6104 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-27 08:54:04.883  6056  6104 D BluetoothAdapterProperties: Setting state to 12
07-27 08:54:04.883  6056  6104 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 08:54:04.884  6056  6108 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 08:54:04.884  6056  6149 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 08:54:04.884  6056  6149 W bt-smp  : Plain text(LSB ~ MSB) = 5b b8 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 08:54:04.884  6056  6149 W bt-smp  : Encrypted text(LSB ~ MSB) = 31 f7 ea bb c0 d9 6c 07 9d c6 d4 39 ca cc a2 0b 
07-27 08:54:04.885  6056  6149 W bt-btm  : Stopping oneshot timer
07-27 08:54:04.885  6056  6302 E bt_mct  : hci lib postload completed
07-27 08:54:04.871  6310  6310 W sh      : type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:04.871  6310  6310 W sh      : type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:04.886  6056  6108 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 08:54:04.888  1029  1105 D BluetoothManagerService: Message: 60
07-27 08:54:04.888  1029  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-27 08:54:04.888  1029  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 5 receivers.
,07-27 08:54:04.889  1029  1105 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:04.889   310  6301 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
07-27 08:54:04.893  5765  5765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 08:54:04.893  5765  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:54:04.893  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:04.893  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:54:04.893  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:54:04.893  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:54:04.893  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:54:04.893  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:54:04.893  5765  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 08:54:04.895  1873  2449 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:04.895  6056  6149 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 08:54:04.895  6056  6149 W bt-smp  : Plain text(LSB ~ MSB) = ac 80 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 08:54:04.895  6056  6149 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 1e a6 c1 63 dc 18 b0 f0 2b 9a 2c b4 6b bf d4 
07-27 08:54:04.895  6056  6149 W bt-btm  : Stopping oneshot timer
07-27 08:54:04.895  6056  6104 I BluetoothAdapterState: Entering On State
,07-27 08:54:04.897  6056  6104 D LGBluetoothServiceAdapter: [BTUI] OnState
07-27 08:54:04.897  6056  6104 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-27 08:54:04.897  6056  6104 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-27 08:54:04.897  4249  6307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
07-27 08:54:04.898  1029  1105 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:54:04.898  1873  1889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:04.898  1873  4133 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:04.899  6056  6104 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 08:54:04.899  1029  1105 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-27 08:54:04.899  1029  1105 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-27 08:54:04.900  6056  6108 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:54:04.901  6056  6108 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-27 08:54:04.901  5765  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 08:54:04.902   310  6298 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-27 08:54:04.902  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:04.905  6056  6149 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 08:54:04.905  6056  6149 W bt-smp  : Plain text(LSB ~ MSB) = 9a 42 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 08:54:04.905  6056  6149 W bt-smp  : Encrypted text(LSB ~ MSB) = b5 da 76 8b b9 29 52 bd f6 58 b6 b8 15 94 e0 63 
07-27 08:54:04.905  6056  6149 W bt-btm  : Stopping oneshot timer
07-27 08:54:04.906  1970  1970 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:04.906  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 08:54:04.907  1970  2188 D LGBluetoothAPIService: Message: 1
07-27 08:54:04.908  1970  2188 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,07-27 08:54:04.914  6056  6149 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 08:54:04.914  6056  6149 W bt-smp  : Plain text(LSB ~ MSB) = 98 50 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 08:54:04.914  6056  6149 W bt-smp  : Encrypted text(LSB ~ MSB) = 66 18 75 d3 89 20 6f 24 a8 21 6a 36 20 2b fc c1 
07-27 08:54:04.914  6056  6149 W bt-btm  : Stopping oneshot timer
07-27 08:54:04.915  6319  6319 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-27 08:54:04.917  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-27 08:54:04.917  1029  1105 D BluetoothManagerService: Message: 40
07-27 08:54:04.917  1029  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,07-27 08:54:04.921   310   887 D LGDataListener: argv[0]=dsqncommand
07-27 08:54:04.921   310   887 D LGDataListener: argv[1]=wlan0
07-27 08:54:04.921   310   887 D LGDataListener: argv[2]=1
07-27 08:54:04.921   310   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 08:54:04.923  6056  6149 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 08:54:04.923  6056  6149 W bt-smp  : Plain text(LSB ~ MSB) = c5 88 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 08:54:04.923  6056  6149 W bt-smp  : Encrypted text(LSB ~ MSB) = e2 5e a4 b9 91 22 03 20 80 5a d8 83 01 ad 8a 07 
07-27 08:54:04.923  6056  6149 W bt-btm  : Stopping oneshot timer
07-27 08:54:04.925  6081  6081 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 08:54:04.925  1029  1103 D DSQN    : DSQM DsqnNotification wlan0  1
07-27 08:54:04.925  1029  1103 D DSQN    : start to monitor internet connection
,07-27 08:54:04.927  6056  6056 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:04.927  6056  6056 D BluetoothMapService: STATE_ON
07-27 08:54:04.930  1029  6300 D LocSvc_java: NTP server : europe.pool.ntp.org
07-27 08:54:04.931  1029  6300 D LocSvc_java: NTP server returned: 1469602444431 (Wed Jul 27 08:54:04 GMT+02:00 2016) reference: 103695 certainty: 19 system time offset: -499
07-27 08:54:04.931  1029  6300 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
07-27 08:54:04.938  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:04.938  6056  6056 V BluetoothPbapService: Pbap Service onCreate
07-27 08:54:04.938  6056  6056 V BluetoothPbapService: Starting PBAP service
07-27 08:54:04.939  6056  6056 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,07-27 08:54:04.939  6056  6056 V BluetoothMapService: Handler(): got msg=1
07-27 08:54:04.939  6056  6056 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-27 08:54:04.940  6056  6056 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:04.940  6056  6056 V BluetoothPbapService: state: 12
07-27 08:54:04.940  6056  6056 V BluetoothPbapService: Handler(): got msg=1
07-27 08:54:04.940  6056  6322 D BluetoothMapMasInstance: MAS initSocket()
07-27 08:54:04.940  6056  6322 D BluetoothMapMasInstance:   masId = 00
07-27 08:54:04.940  6056  6322 D BluetoothMapMasInstance:   msgTypes = 0e
07-27 08:54:04.940  6056  6322 D BluetoothMapMasInstance:   masName = SMS/MMS
07-27 08:54:04.940  6056  6322 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-27 08:54:04.942  1029  2329 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:04.945  6056  6056 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-27 08:54:04.945  6056  6322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:54:04.945  6056  6104 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-27 08:54:04.946  6056  6322 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-27 08:54:04.946  6056  6322 V BluetoothMapMasInstance: Succeed to create listening socket 
07-27 08:54:04.946  6056  6322 D BluetoothMapMasInstance: Accepting socket connection...
07-27 08:54:04.946  6056  6056 D LGBluetoothAPIServer: [BTUI] onCreate()
07-27 08:54:04.946  6056  6056 D LGBluetoothAPIServer: [BTUI] onBind()
07-27 08:54:04.947  1970  2188 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-27 08:54:04.947  6056  6108 D BluetoothAdapterProperties: Scan Mode:21
07-27 08:54:04.947  6056  6108 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-27 08:54:04.948  1970  1970 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-27 08:54:04.948  1970  2188 D LGBluetoothAPIService: Message: 100
07-27 08:54:04.948  1970  2188 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-27 08:54:04.948  6056  6323 V BluetoothPbapService: Pbap Service initSocket
07-27 08:54:04.949  1029  2328 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:04.950  6056  6323 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:54:04.950  6056  6323 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-27 08:54:04.950  6056  6323 V BluetoothPbapService: Succeed to create listening socket 
07-27 08:54:04.950  6056  6323 V BluetoothPbapService: Accepting socket connection...
07-27 08:54:04.953  5765  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:54:04.953  1029  6216 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 06:54:04 GMT], X-Android-Received-Millis=[1469602444952], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469602444947]}
07-27 08:54:04.954  6056  6056 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 08:54:04.954  6056  6056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:04.954  1029  6216 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 08:54:04.954  6056  6056 V BluetoothPbapReceiver: ***********state = 12
,07-27 08:54:04.954  1029  6216 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-27 08:54:04.954  1029  1419 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
07-27 08:54:04.954  1029  1419 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-27 08:54:04.954  1029  1419 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:54:04.954  1029  1419 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:04.954  1029  1419 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 08:54:04.955  1029  1419 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
07-27 08:54:04.955  1029  1419 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:04.955  1029  1419 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.955  1029  1419 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:04.955  1029  1419 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:04.955  1029  1419 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.956  1599  1808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 08:54:04.956  1029  1419 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 08:54:04.956  1029  1385 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.956  1873  1873 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:04.956  1029  1385 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:54:04.956  1873  1873 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 08:54:04.959  2238  2238 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 08:54:04.959  2238  2238 D c       : Getting all permits...
07-27 08:54:04.959  2238  2238 D a       : Opening database...
07-27 08:54:04.961  2238  2238 D a       : Opening database auth.proximity.permit_store...
07-27 08:54:04.962  6081  6081 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 08:54:04.962  2238  2238 D a       : Closing database...
,07-27 08:54:04.966  1029  1105 D BluetoothManagerService: Message: 30
07-27 08:54:04.970  6081  6081 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 08:54:04.972  1029  1105 D BluetoothManagerService: Message: 30
07-27 08:54:04.975  1029  1105 D BluetoothManagerService: Message: 30
07-27 08:54:04.978  1029  1105 D BluetoothManagerService: Message: 30
07-27 08:54:04.982  6081  6081 D LocalBluetoothProfileManager: Adding local MAP profile
07-27 08:54:04.983  6081  6081 D BluetoothMap: Create BluetoothMap proxy object
07-27 08:54:04.983  1029  1105 D BluetoothManagerService: Message: 30
,07-27 08:54:04.994  1029  1105 D BluetoothManagerService: Message: 30
07-27 08:54:04.996  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 08:54:04.996  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.997  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 08:54:04.998  6056  6056 V BluetoothPbapService: Pbap Service onBind
07-27 08:54:04.998  6081  6081 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-27 08:54:05.003  6081  6081 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
07-27 08:54:05.007  6081  6081 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-27 08:54:05.012  6081  6081 D DockEventReceiver: finishStartingService: stopping service
07-27 08:54:05.016  6081  6081 D BluetoothA2dp: Proxy object connected
07-27 08:54:05.017  6081  6081 D A2dpProfile: Bluetooth service connected
,07-27 08:54:05.020  6081  6081 D BluetoothHeadset: Proxy object connected
07-27 08:54:05.021  6081  6081 D HeadsetProfile: Bluetooth service connected
07-27 08:54:05.022  6081  6081 D BluetoothInputDevice: Proxy object connected
07-27 08:54:05.023  6081  6081 D HidProfile: Bluetooth service connected
07-27 08:54:05.023  6081  6081 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 08:54:05.024  6081  6081 D PanProfile: Bluetooth service connected
07-27 08:54:05.025  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:05.028  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:05.028  6081  6081 D BluetoothMap: Proxy object connected
07-27 08:54:05.028  6081  6081 D MapProfile: Bluetooth service connected
07-27 08:54:05.029  6081  6081 D BluetoothMap: getConnectedDevices()
07-27 08:54:05.030  6056  6075 V BluetoothMapService: getConnectedDevices()
,07-27 08:54:05.032  6081  6081 D BluetoothPbap: Proxy object connected
07-27 08:54:05.032  6081  6081 D PbapServerProfile: Bluetooth service connected
07-27 08:54:05.032  6081  6081 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-27 08:54:05.033  6081  6081 D BluetoothPermissionRequest: onReceive
07-27 08:54:05.034  6081  6081 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 08:54:05.035  6081  6081 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 08:54:05.036  6056  6056 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-27 08:54:05.037  6081  6081 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 08:54:05.037  6056  6056 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-27 08:54:05.044  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 08:54:05.044  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:05.045  6056  6056 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-27 08:54:05.047  6238  6238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 08:54:05.049  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:05.053  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:05.055  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 08:54:05.060  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 08:54:05.060  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:05.060  6238  6238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 08:54:05.061  6056  6056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 08:54:05.061  6056  6056 V BtOppService: onCreate
07-27 08:54:05.062  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:05.066  6151  6151 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 08:54:05.067  6056  6056 V BluetoothOppNotification: send message
07-27 08:54:05.069  6056  6056 V BtOppService: Starting RfcommListener
,07-27 08:54:05.073  6056  6056 D BluetoothOppPreference: Dumping Names:  
07-27 08:54:05.073  6056  6056 D BluetoothOppPreference: {}
07-27 08:54:05.073  6056  6056 D BluetoothOppPreference: Dumping Channels:  
07-27 08:54:05.073  6056  6056 D BluetoothOppPreference: {}
07-27 08:54:05.073  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 08:54:05.073  6056  6056 V BtOppService: onStartCommand
07-27 08:54:05.076  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:05.076  6056  6333 V BtOppService: Deleted complete outbound shares, number =  0
07-27 08:54:05.077  6056  6333 V BtOppService: Deleted complete inbound failed shares, number = 0
07-27 08:54:05.077  6056  6333 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-27 08:54:05.078  6056  6056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:05.078  6056  6056 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 08:54:05.078  6056  6333 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@238c3638 on behalf of 
07-27 08:54:05.082  6056  6056 V BluetoothOppNotification: new notify threadi!
07-27 08:54:05.082  6056  6056 V BluetoothOppNotification: send delay message
07-27 08:54:05.082  6056  6056 V BtOppService: start RfcommListener
07-27 08:54:05.083  6056  6337 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 08:54:05.084  6056  6056 V BtOppService: RfcommListener started
07-27 08:54:05.084  6056  6056 V BtOppService: ContentObserver received notification
,07-27 08:54:05.091  6056  6338 V BtOppRfcommListener: Starting RFCOMM listener....
07-27 08:54:05.097  1029  2329 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:05.098  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:05.098  6056  6056 V BluetoothFtpService: Ftp Service onCreate
07-27 08:54:05.098  6056  6056 I BluetoothFtpService: Ftp Service onCreate
07-27 08:54:05.098  6056  6338 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:54:05.098  6056  6056 V BluetoothFtpService: Ftp Service onStartCommand
07-27 08:54:05.098  6056  6056 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:05.098  6056  6056 V BluetoothFtpService: Starting Listening on sockets
07-27 08:54:05.098  6056  6056 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 08:54:05.098  6056  6056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 08:54:05.098  6056  6056 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 08:54:05.098  6056  6056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:05.098  6056  6056 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-27 08:54:05.098  6056  6056 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 08:54:05.099  6056  6338 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
07-27 08:54:05.099  6056  6338 V BtOppRfcommListener: Started RFCOMM listener....
07-27 08:54:05.099  6056  6338 I BtOppRfcommListener: Accept thread started.
07-27 08:54:05.099  6056  6338 V BtOppRfcommListener: Accepting connection...
07-27 08:54:05.101  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:05.127  6056  6336 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 08:54:05.128  6056  6336 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,07-27 08:54:05.135  5999  5999 I UEI.SmartControl: Supports setup maps: true
07-27 08:54:05.138  5999  5999 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 08:54:05.138  5999  5999 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 08:54:05.138  5999  5999 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 08:54:05.138  5999  5999 I UEI.SmartControl: ### init IR Blaster...
07-27 08:54:05.141  5999  5999 D serial_port: Configuring serial port
07-27 08:54:05.141  5999  5999 E UEI.SmartControl: UEIBLaster setting for 616
07-27 08:54:05.141  5999  5999 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 08:54:05.141  5999  5999 I UEI.SmartControl: configuring settings for MAXQ616
07-27 08:54:05.141  5999  5999 I UEI.SmartControl: Get version...
07-27 08:54:05.159  5999  6341 D UEI.SmartControl: serial port data available: 21
,07-27 08:54:05.175  1029  1967 I art     : Explicit concurrent mark sweep GC freed 79075(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.252ms total 91.750ms
,07-27 08:54:05.176  6056  6336 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6c0376 on behalf of 
07-27 08:54:05.176  6056  6337 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a4f9d77 on behalf of 
07-27 08:54:05.177  6056  6056 V BtOppService: ContentObserver received notification
07-27 08:54:05.177  6056  6056 V BluetoothFtpService: Handler(): got msg=1
07-27 08:54:05.177  6056  6056 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-27 08:54:05.178  6056  6056 V BluetoothFtpService: Ftp Service initSocket
07-27 08:54:05.180  1029  1708 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:05.180  6056  6056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:54:05.182  6056  6056 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
07-27 08:54:05.182  6056  6056 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-27 08:54:05.183  6056  6342 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-27 08:54:05.185  5999  5999 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-27 08:54:05.185  5999  5999 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 08:54:05.185  5999  5999 I UEI.SmartControl: QS saving settings...
07-27 08:54:05.185  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 08:54:05.185  5999  5999 D UEI.SmartControl: IR Blaster version: 25672567
07-27 08:54:05.185  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:05.186  6056  6337 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 08:54:05.187  6056  6337 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 08:54:05.187  6238  6238 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-27 08:54:05.189  6238  6238 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 08:54:05.190  6238  6238 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 08:54:05.190  6056  6337 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16ea7de4 on behalf of 
07-27 08:54:05.191  6056  6337 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 08:54:05.192  6056  6337 V BluetoothOppNotification: outbound notification was removed.
07-27 08:54:05.193  6056  6337 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 08:54:05.193  6056  6337 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@368b424d on behalf of 
07-27 08:54:05.194  6056  6337 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 08:54:05.194  6056  6336 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 08:54:05.194  6056  6336 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 08:54:05.195  6056  6337 V BluetoothOppNotification: inbound notification was removed.
07-27 08:54:05.195  6056  6337 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 08:54:05.195  6056  6336 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c0ce102 on behalf of 
07-27 08:54:05.196  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 08:54:05.196  6056  6336 V BluetoothOppNotification: update too frequent, put in queue
07-27 08:54:05.199  5999  6341 D UEI.SmartControl: serial port data available: 4
,07-27 08:54:05.200  6056  6336 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-27 08:54:05.201  6056  6337 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7969a13 on behalf of 
07-27 08:54:05.202  6056  6056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25c208e
07-27 08:54:05.202  6056  6056 V BluetoothSapService: Sap Service onCreate
07-27 08:54:05.202  6151  6151 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 08:54:05.204  6056  6056 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:05.204  6056  6056 V BluetoothSapService: state: 12
07-27 08:54:05.204  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 08:54:05.204  6056  6056 V BluetoothSapService: Starting SAP server process
07-27 08:54:05.205  6056  6056 V BluetoothSapService: SAP Service startRfcommListenerThread
07-27 08:54:05.206  6056  6345 V BluetoothSapService: Sap Service initRfcommSocket
07-27 08:54:05.208  1029  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:05.208  6056  6345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:54:05.191  6344  6344 W sapd    : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:05.191  6344  6344 W sapd    : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 08:54:05.211  6081  6081 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:05.215  6344  6344 V BT_SAP  : Event pipe created
07-27 08:54:05.215  6344  6344 V BT_SAP  : create_server_socket qcom.sap.server
07-27 08:54:05.215  6344  6344 V BT_SAP  : created socket fd 6
07-27 08:54:05.220  6056  6345 V BluetoothSapService: Succeed to create listening socket 
07-27 08:54:05.220  6056  6345 V BluetoothSapService: Accepting socket connection...
,07-27 08:54:05.223  6081  6081 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:05.226  5999  5999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-27 08:54:05.227  5999  6347 I UEI.SmartControl: Device manager: loading config....
07-27 08:54:05.227  5999  6347 D UEI.SmartControl: ----------- loading internal config...
07-27 08:54:05.228  5999  5999 E UEI.SmartControl: Services init done
07-27 08:54:05.228  5999  5999 D UEI.SmartControl: QS Service init finished
07-27 08:54:05.228  5999  5999 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 08:54:05.228  5999  5999 D UEI.SmartControl: QS Service version code: 201091
07-27 08:54:05.228  5999  5999 D UEI.SmartControl: Service requested: Control
07-27 08:54:05.229  6238  6238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 08:54:05.229  6238  6238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 08:54:05.230  6238  6238 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 08:54:05.230  5999  6347 E UEI.SmartControl: Loading SETTINGS...
07-27 08:54:05.232  6238  6238 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 08:54:05.232  6238  6238 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 08:54:05.232  5999  6347 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 08:54:05.233  5999  5999 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-27 08:54:05.237  5999  5999 D UEI.SmartControl: Internal service binding...
07-27 08:54:05.237  6238  6238 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-27 08:54:05.238  5999  6014 I UEI.SmartControl: ------ IControl API: 11
07-27 08:54:05.238  5999  6014 D UEI.SmartControl: File observer start...
07-27 08:54:05.238  5999  6014 E UEI.SmartControl: IR Port is disabled: false
07-27 08:54:05.238  5999  6014 D UEI.SmartControl: Starting file observer...
07-27 08:54:05.238  5999  6014 I UEI.SmartControl: Registering callback...
07-27 08:54:05.239  5999  6015 I UEI.SmartControl: ------ IControl API: 19
07-27 08:54:05.239  5999  6015 I UEI.SmartControl: Registering Services Ready callback...
07-27 08:54:05.240  5999  6015 I UEI.SmartControl: Notify client services are ready...
07-27 08:54:05.240  6238  6254 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-27 08:54:05.241  6238  6285 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-27 08:54:05.241  6238  6285 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-27 08:54:05.241  6238  6238 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-27 08:54:05.242  6238  6238 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-27 08:54:05.242  5999  6014 I UEI.SmartControl: ------ IControl API: 8
07-27 08:54:05.243  6238  6238 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-27 08:54:05.243  6238  6238 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-27 08:54:05.243  6238  6238 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-27 08:54:05.243  6238  6238 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-27 08:54:05.245  6238  6238 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,07-27 08:54:05.245  6238  6238 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-27 08:54:05.246  5999  6346 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 08:54:05.247  6238  6253 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-27 08:54:05.247  6238  6285 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-27 08:54:05.248  6238  6285 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-27 08:54:05.248  5999  6346 D UEI.SmartControl: -----service ready thread exits
07-27 08:54:05.248  6238  6238 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-27 08:54:05.249  6238  6238 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-27 08:54:05.250  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-27 08:54:05.250  6238  6238 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 08:54:05.250  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-27 08:54:05.251  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 08:54:05.252  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-27 08:54:05.252  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-27 08:54:05.253  6238  6238 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469602445253]
07-27 08:54:05.255  6238  6238 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
07-27 08:54:05.255  6238  6238 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-27 08:54:05.256  1029  2328 I ActivityManager: Killing 5725:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,07-27 08:54:05.267  6238  6349 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
07-27 08:54:05.412  1029  1967 W libprocessgroup: failed to open /acct/uid_10061/pid_5725/cgroup.procs: No such file or directory
,07-27 08:54:05.421  6238  6238 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-27 08:54:05.425  6238  6238 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 08:54:05.426  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-27 08:54:05.426  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-27 08:54:05.427  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-27 08:54:05.428  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,07-27 08:54:05.429  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,07-27 08:54:05.446  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-27 08:54:05.555  1029  1385 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-27 08:54:05.556  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 08:54:05.557  1029  1385 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 08:54:05.558  1029  1385 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 08:54:05.559  1029  1385 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 08:54:05.561  1029  1385 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 08:54:05.562  1029  1419 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
07-27 08:54:05.563  1029  1419 D ConnectivityService: identical MTU - not setting
07-27 08:54:05.565  1029  1419 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 08:54:05.565  1029  1419 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:05.566  1029  1419 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:05.566  1029  1419 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:05.568  1029  1419 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:05.569  1599  1808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-27 08:54:06.083  6056  6056 V BluetoothOppNotification: new notify threadi!
07-27 08:54:06.084  6056  6056 V BluetoothOppNotification: send delay message
,07-27 08:54:06.101  6056  6359 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-27 08:54:06.142  6056  6359 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1446c46f on behalf of 
07-27 08:54:06.143  6056  6359 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-27 08:54:06.211  6056  6359 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-27 08:54:06.221  6056  6359 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ed5a57c on behalf of 
07-27 08:54:06.222  6056  6359 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 08:54:06.223  6056  6359 V BluetoothOppNotification: outbound notification was removed.
07-27 08:54:06.224  6056  6359 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 08:54:06.224  6056  6359 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@234b6e05 on behalf of 
,07-27 08:54:06.225  6056  6359 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 08:54:06.227  6056  6359 V BluetoothOppNotification: inbound notification was removed.
07-27 08:54:06.227  6056  6359 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 08:54:06.228  6056  6359 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f818e5a on behalf of 
07-27 08:54:07.057  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723631825] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:54:07.058  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723631826] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:54:07.058  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:07.073  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 08:54:07.740  1029  1386 V WifiInternetCheck: Single check msg out of sync, ignoring.
,07-27 08:54:07.826  1029  1419 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:07.837  1029  1105 D Tethering: MasterInitialState.processMessage what=3
07-27 08:54:07.839  5765  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:54:07.844   310  6383 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:07.844   310  6383 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
07-27 08:54:07.848  1029  1085 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:07.852  1029  1085 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 08:54:07.853  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-27 08:54:07.864  5081  5106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 08:54:07.874  5169  5169 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-27 08:54:07.885   310  6383 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
07-27 08:54:07.887  1029  1085 E GpsLocationProvider: No APN found to select.
,07-27 08:54:07.897  1029  1848 D AlarmManagerService: Setting time of day to sec=1469602447
07-27 08:54:07.398  1029  1848 W AlarmManagerService: Unable to set rtc to 1469602447: Invalid argument
,07-27 08:54:07.437  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:54:07.440  1970  1970 I SecureClockService: Intent.ACTION_TIME_CHANGED 
07-27 08:54:07.441  1599  1599 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
07-27 08:54:07.443  1599  1599 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-27 08:54:07.446  2747  2747 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
07-27 08:54:07.447  2747  2747 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-07-27 08:54:07...... Request
07-27 08:54:07.447  2747  2747 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 37, new day : false...... Request
07-27 08:54:07.447  2747  2747 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 37
07-27 08:54:07.447  2747  2747 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 6
07-27 08:54:07.448  2747  2747 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-07-27 08:54:07
,07-27 08:54:07.452  4650  4650 I CalendarProvider2: onReceive() android.intent.action.TIME_SET
07-27 08:54:07.452  4650  4650 D CalendarProvider2: Scheduling check of next Alarm
07-27 08:54:07.453  1029  1708 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
07-27 08:54:07.454  2088  2088 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=27 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
07-27 08:54:07.458  1838  6395 I CheckinService: active receiver: enabled
07-27 08:54:07.459  2088  2088 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 27
,07-27 08:54:07.460  1838  6395 I CheckinService: Preparing to send checkin request
07-27 08:54:07.461  1838  6395 I EventLogService: Accumulating logs since 1469602041123
,07-27 08:54:07.467  2088  2088 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 27
07-27 08:54:07.467  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 08:54:07.481  2238  2238 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:07.486  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
07-27 08:54:07.492   310  6400 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:07.493   310  6400 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,07-27 08:54:07.524   310  6400 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,07-27 08:54:07.528  1838  6395 W EventLogAggregator: Unknown tag: snet_gcore
07-27 08:54:07.528  1838  6395 W EventLogAggregator: Unknown tag: snet_launch_service
07-27 08:54:07.531  1029  2329 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6402 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-27 08:54:07.605  1838  6395 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-27 08:54:07.605  6402  6402 I AppUp4:AppBoxCP: onCreate
07-27 08:54:07.606  6402  6402 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-27 08:54:07.611  1029  1399 D WifiService: New client listening to asynchronous messages
07-27 08:54:07.615  6402  6402 I AppUp4:DB:  setFingerPrint start
07-27 08:54:07.616  6402  6402 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-27 08:54:07.623  6402  6402 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,07-27 08:54:07.623  6402  6402 I AppUp4:DB:  SDK version = 21
07-27 08:54:07.623  6402  6402 I AppUp4:DB:  beforefinger == newfinger no write in DB
,07-27 08:54:07.624  6402  6402 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-27 08:54:07.625  6402  6402 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 08:54:07.625  6402  6402 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:07.627  6402  6402 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 08:54:07.628  6402  6402 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 08:54:07.633  6402  6402 I AppUp4:CustModeStarterReceiver: onReceive
07-27 08:54:07.633  2238  6399 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 08:54:07.687  6402  6402 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 08:54:07.687  6402  6402 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 08:54:07.697  1838  1838 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-27 08:54:07.698  6402  6402 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@750d889
,07-27 08:54:07.698  6402  6402 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 08:54:07.698  6402  6402 D AppUp4:CustFacade: isPhone : true
07-27 08:54:07.700  6402  6402 D AppUp4:CustModeStarterReceiver: begin check event
07-27 08:54:07.700  6402  6402 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-27 08:54:07.700  6402  6402 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-27 08:54:07.704  1838  6425 I ConfigFetchService: running network task: configservice_periodic
07-27 08:54:07.706  1838  6425 I ConfigFetchService: launchTask
07-27 08:54:07.709  2238  2238 I ConfigService: onCreate
07-27 08:54:07.709  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,07-27 08:54:07.715  2238  2238 I ConfigService: onBind returning update interface
07-27 08:54:07.716  1838  1838 I ConfigFetchService: service connected
07-27 08:54:07.716  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 08:54:07.716  2238  2238 I ConfigService: onBind returning config service
07-27 08:54:07.716  1838  1838 I ConfigClient: service connected
07-27 08:54:07.719  6402  6421 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-27 08:54:07.719  6402  6421 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-27 08:54:07.719  6402  6421 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,07-27 08:54:07.723  1029  1987 I ActivityManager: Killing 5849:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,07-27 08:54:07.774  2238  6424 D GCM     : Connected
,07-27 08:54:07.795  3090  3090 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:07.795  3090  3090 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-27 08:54:07.797  1029  1709 W libprocessgroup: failed to open /acct/uid_10080/pid_5849/cgroup.procs: No such file or directory
07-27 08:54:07.802  3090  3090 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 08:54:07.809  3090  3090 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 08:54:07.821  3090  6429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 08:54:07.823  2238  6424 D GCM     : Message class com.google.e.a.a.q
,07-27 08:54:07.825  3412  3412 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:07.825  3090  6429 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
07-27 08:54:07.828  3090  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:07.829  3090  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 08:54:07.836  3412  3412 V DownloadManager: DownloadService onCreate
,07-27 08:54:07.839  3412  6432 I DownloadManager: in removeSpuriousFiles
07-27 08:54:07.840  3412  6432 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
07-27 08:54:07.841  3412  6432 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e8cd28f on behalf of 3412
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
07-27 08:54:07.842  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
07-27 08:54:07.843  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
07-27 08:54:07.843  3412  6432 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
07-27 08:54:07.844  3412  6432 I DownloadManager: in trimDatabase
07-27 08:54:07.844  3412  6432 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
07-27 08:54:07.848  3412  6432 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3ec67925 on behalf of 3412
07-27 08:54:07.878  1029  1708 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6435 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-27 08:54:07.882  3412  3412 V DownloadManager: DownloadService onStartCommand
07-27 08:54:07.883  3412  6433 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
07-27 08:54:07.892  3412  6433 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2b8e08ab on behalf of 3412
07-27 08:54:07.894  3412  6433 V DownloadManager: processing inserted download 1
07-27 08:54:07.895  3412  6433 V DownloadManager: processing inserted download 4
07-27 08:54:07.895  3412  6433 V DownloadManager: processing inserted download 7
07-27 08:54:07.896  3412  6433 V DownloadManager: processing inserted download 8
07-27 08:54:07.897  3412  6433 V DownloadManager: processing inserted download 9
,07-27 08:54:07.900  3412  6433 V DownloadManager: processing inserted download 10
07-27 08:54:07.901  3412  6433 V DownloadManager: processing inserted download 11
07-27 08:54:07.902  3412  6433 V DownloadManager: processing inserted download 12
07-27 08:54:07.904  3412  6433 V DownloadManager: processing inserted download 13
07-27 08:54:07.904  3412  6433 V DownloadManager: processing inserted download 14
07-27 08:54:07.905  3412  6433 V DownloadManager: processing inserted download 16
07-27 08:54:07.916  1029  1925 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6452 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-27 08:54:07.918  3090  6429 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
07-27 08:54:07.924  3412  3412 V DownloadManager: DownloadService onDestroy
07-27 08:54:07.925  3090  3090 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
07-27 08:54:07.928  3090  3090 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
07-27 08:54:07.928  3090  3090 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
07-27 08:54:07.929  3090  3090 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,07-27 08:54:07.933  3090  3090 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
07-27 08:54:07.945  6435  6435 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:07.945  6435  6435 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:07.946  6435  6435 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 08:54:07.947  6435  6435 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 08:54:07.966  6452  6452 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-27 08:54:07.966  6452  6452 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 08:54:07.991  6452  6452 I MultiDex: VM with version 2.1.0 has multidex support
07-27 08:54:07.991  6452  6452 I MultiDex: install
07-27 08:54:07.991  6452  6452 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:54:07.998  6452  6452 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-27 08:54:08.007  6435  6435 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-27 08:54:08.015  6435  6435 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-27 08:54:08.040  6435  6435 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:54:08.060  6435  6435 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:54:08.060  6435  6435 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 08:54:08.131  6435  6435 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 08:54:08.157  6435  6435 I HubEmail: JNI_OnLoad()
07-27 08:54:08.157  6435  6435 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 08:54:08.157  6435  6435 I HubEmail: registerNatives()
07-27 08:54:08.157  6435  6435 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,07-27 08:54:08.157  6435  6435 I HubEmail: registerNativeMethods()
07-27 08:54:08.157  6435  6435 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 08:54:08.157  6435  6435 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,07-27 08:54:08.174  3329  3329 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,07-27 08:54:08.174  3329  3329 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:08.175  6435  6477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:08.176  3329  3329 I LgeMiscReceiver: networkInfo.isConnected() = true
07-27 08:54:08.176  3329  3329 D PhoneState: setPdpRejectCasuse : false
,07-27 08:54:08.210  1029  1925 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6479 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-27 08:54:08.215   310  6489 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:08.215   310  6489 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,07-27 08:54:08.262   310  6489 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,07-27 08:54:08.282  6479  6479 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:54:08.282  6479  6479 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 08:54:08.284  6479  6479 D PhoneMonitor: Register our PhoneStateListener
07-27 08:54:08.295  6479  6479 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-27 08:54:08.296  6479  6479 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 08:54:08.304  6479  6479 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-27 08:54:08.305  6479  6479 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-27 08:54:08.307  6120  6476 V FormManager: There are no updated forms. The schedule will be deleted.
07-27 08:54:08.308  6479  6479 D TelephonyAutoProfiling: [parse] Load xml
,07-27 08:54:08.311  6120  6476 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
07-27 08:54:08.312  6479  6479 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-27 08:54:08.312  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-27 08:54:08.312  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-27 08:54:08.312  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-27 08:54:08.312  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-27 08:54:08.312  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-27 08:54:08.313  6479  6479 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-27 08:54:08.313  6479  6479 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
07-27 08:54:08.317  6479  6479 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-27 08:54:08.324  1029  1987 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6500 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 08:54:08.325  1029  1987 I ActivityManager: Killing 5866:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-27 08:54:08.336  6452  6468 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:54:08.336  6452  6468 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 08:54:08.401  6517  6517 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-27 08:54:08.452   310  6523 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:08.452   310  6523 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,07-27 08:54:08.463  1029  1925 W libprocessgroup: failed to open /acct/uid_10097/pid_5866/cgroup.procs: No such file or directory
07-27 08:54:08.484  6517  6517 I dex2oat : dex2oat took 83.785ms (threads: 4)
07-27 08:54:08.485   310  6523 D libc-netbsd: res_queryN name = www.google.com succeed
,07-27 08:54:08.490   310  6525 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:08.490   310  6525 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-27 08:54:08.490   310  6525 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-27 08:54:08.493  1029  2016 I ActivityManager: Killing 5903:com.lge.eula/1000 (adj 15): empty #17
07-27 08:54:08.501  6452  6468 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:08.501  6452  6468 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:08.501  6452  6468 I Adreno-EGL: Build Date: 12/12/14 금
07-27 08:54:08.501  6452  6468 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 08:54:08.501  6452  6468 I Adreno-EGL: Remote Branch: 
07-27 08:54:08.501  6452  6468 I Adreno-EGL: Local Patches: 
07-27 08:54:08.501  6452  6468 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:08.502  1029  1387 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
07-27 08:54:08.564  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:54:08.564  5765  5837 I jxcore-log: 
,07-27 08:54:08.605  6452  6468 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:08.605  6452  6468 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:08.605  6452  6468 I Adreno-EGL: Build Date: 12/12/14 금
07-27 08:54:08.605  6452  6468 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 08:54:08.605  6452  6468 I Adreno-EGL: Remote Branch: 
07-27 08:54:08.605  6452  6468 I Adreno-EGL: Local Patches: 
07-27 08:54:08.605  6452  6468 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:08.612  1029  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_5903/cgroup.procs: No such file or directory
07-27 08:54:08.647  6452  6468 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:08.647  6452  6468 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:08.647  6452  6468 I Adreno-EGL: Build Date: 12/12/14 금
07-27 08:54:08.647  6452  6468 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 08:54:08.647  6452  6468 I Adreno-EGL: Remote Branch: 
07-27 08:54:08.647  6452  6468 I Adreno-EGL: Local Patches: 
07-27 08:54:08.647  6452  6468 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:08.789  1029  1045 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6531 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-27 08:54:08.790  1029  1045 I ActivityManager: Killing 4938:com.android.calendar/u0a13 (adj 15): empty #17
,07-27 08:54:08.973  1029  1044 W libprocessgroup: failed to open /acct/uid_10013/pid_4938/cgroup.procs: No such file or directory
,07-27 08:54:09.005  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:54:09.005  5765  5837 I jxcore-log: 
,07-27 08:54:09.024  6531  6531 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
07-27 08:54:09.026  6531  6531 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,07-27 08:54:09.030  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:54:09.030  5765  5837 I jxcore-log: 
07-27 08:54:09.032  6531  6531 V DrmService: Service onCreate
07-27 08:54:09.033  6531  6531 D DrmService: Received new request = 2
07-27 08:54:09.034  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:54:09.034  5765  5837 I jxcore-log: 
07-27 08:54:09.038  6531  6552 I DrmSntpClient: Start Sync process
07-27 08:54:09.038  6531  6552 D DrmSntpClient: Server : 0
,07-27 08:54:09.050  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:54:09.050  5765  5837 I jxcore-log: 
,07-27 08:54:09.052   310  6553 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:09.052   310  6553 D libc-netbsd: res_queryN name = pool.ntp.org, class = 1, type = 1
07-27 08:54:09.054  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:54:09.054  5765  5837 I jxcore-log: 
07-27 08:54:09.058   310  6555 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:09.058   310  6555 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-27 08:54:09.073  1029  1967 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6556 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:09.090   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 16.611ms
,07-27 08:54:09.092   310  6553 D libc-netbsd: res_queryN name = pool.ntp.org succeed
07-27 08:54:09.093   310  6555 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-27 08:54:09.100  6531  6552 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
07-27 08:54:09.101   330   899 V ILGDrmService: eDRM_SetDRMTime +++
07-27 08:54:09.101   330   899 I LGDRM   : [DRM] SET TIME : YR=2016, MON=7, DAY=27
07-27 08:54:09.101   330   899 I LGDRM   : [DRM] SET TIME : HR=6, MIN=54, SEC=9
07-27 08:54:09.106   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 331us total 15.401ms
,07-27 08:54:09.114   330   899 V ILGDrmService: eDRM_SetDRMTime ---
07-27 08:54:09.115  6531  6552 I DrmSntpClient: Synched
07-27 08:54:09.116  6531  6531 D DrmService: Completed !! request = 2
07-27 08:54:09.116  6531  6531 D DrmService: Request count = 0
07-27 08:54:09.118  6531  6531 V DrmService: Service onDestroy
07-27 08:54:09.119  1029  2016 I ActivityManager: Killing 4650:com.android.providers.calendar/u0a14 (adj 15): empty #17
,07-27 08:54:09.120  6556  6556 I art     : Almond Protected OAT
,07-27 08:54:09.121   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 282us total 13.457ms
07-27 08:54:09.182  1029  1967 W libprocessgroup: failed to open /acct/uid_10014/pid_4650/cgroup.procs: No such file or directory
,07-27 08:54:09.185  6556  6556 D WeatherApplication: removeAccount
07-27 08:54:09.187  6556  6556 D WeatherApplication: Account.length = 0
07-27 08:54:09.188  6556  6556 E WeatherApplication: OPERATOR:OPEN
07-27 08:54:09.199  6556  6556 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:54:9
,07-27 08:54:09.204  6556  6556 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,07-27 08:54:09.204  6556  6556 D Weather.Utils: 2 : All the weather widget is gone.
07-27 08:54:09.206  6556  6556 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 08:54:09.209  6556  6556 D WeatherAncestor: connectivity changed - connection : true
07-27 08:54:09.210  6556  6556 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-27 08:54:09.221  6556  6556 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 08:54:09.221  6556  6556 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 08:54:09.221  6556  6556 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,07-27 08:54:09.253  6556  6556 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 08:54:09.254  6556  6556 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:54:9
,07-27 08:54:09.303  1029  2083 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6576 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 08:54:09.304  1029  2083 I ActivityManager: Killing 5662:com.android.vending/u0a44 (adj 15): empty #17
,07-27 08:54:09.341  1838  6395 I CheckinTask: Sending checkin request (7931 bytes)
,07-27 08:54:09.446  1029  2016 W libprocessgroup: failed to open /acct/uid_10044/pid_5662/cgroup.procs: No such file or directory
,07-27 08:54:09.559   279   328 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:09.559   279   328 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 08:54:09.559   279   328 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:09.560  6576  6594 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-27 08:54:09.564   279   328 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:09.564   279   328 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 08:54:09.564   279   328 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:09.564  6576  6594 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-27 08:54:09.578   279   328 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:09.578   279   328 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 08:54:09.578   279   328 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:09.578  6576  6596 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-27 08:54:09.580   279   328 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:09.580   279   328 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 08:54:09.580   279   328 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:09.580  6576  6596 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-27 08:54:09.581  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:2505] from screen [on:0 period:723634349] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 08:54:09.582  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723634350] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 08:54:09.582  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:09.661  1838  6395 I art     : Explicit concurrent mark sweep GC freed 28396(1913KB) AllocSpace objects, 15(263KB) LOS objects, 51% free, 29MB/61MB, paused 1.450ms total 54.523ms
,07-27 08:54:09.683  1838  6395 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-27 08:54:09.688  1838  6395 I CheckinService: active receiver: disabled
,07-27 08:54:09.703  1838  6612 I CheckinService: active receiver: disabled
,07-27 08:54:09.760  6576  6576 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-27 08:54:09.766  6576  6576 I LibraryLoader: Loading: webviewchromium
07-27 08:54:09.768  6576  6576 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9044-9047)
07-27 08:54:09.768  6576  6576 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:09.773  6576  6576 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {292debd8}
07-27 08:54:09.774  6576  6576 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:09.775  6576  6576 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:54:09.788  6576  6576 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 08:54:09.789  6576  6576 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:09.799  6576  6576 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 08:54:09.800  6576  6576 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-27 08:54:09.800  6576  6576 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
07-27 08:54:09.801   315  1396 V AudioPolicyService: registerClient() client 0xb54eac60, uid 10093
,07-27 08:54:09.802  6576  6619 W AudioManagerAndroid: Requires BLUETOOTH permission
07-27 08:54:09.814  6576  6576 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:09.814  6576  6576 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:09.814  6576  6576 I Adreno-EGL: Build Date: 12/12/14 금
07-27 08:54:09.814  6576  6576 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 08:54:09.814  6576  6576 I Adreno-EGL: Remote Branch: 
07-27 08:54:09.814  6576  6576 I Adreno-EGL: Local Patches: 
07-27 08:54:09.814  6576  6576 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:09.917  6576  6576 I NSApplication: Starting up...
,07-27 08:54:10.021  1029  2083 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6632 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:10.023  1029  2016 I ActivityManager: Killing 2214:com.lge.music/u0a34 (adj 15): empty #17
,07-27 08:54:10.043   315  1396 V AudioFlinger: 2214 died, releasing its sessions
07-27 08:54:10.043   315  1396 V AudioFlinger:  pid 1873 @ 0
07-27 08:54:10.043   315  1396 V AudioFlinger:  pid 3329 @ 1
07-27 08:54:10.043   315  1396 V AudioFlinger:  pid 3329 @ 2
,07-27 08:54:10.054  5999  6343 D serial_port: close(fd = 24)
,07-27 08:54:10.058  5999  6343 I UEI.SmartControl: Serial port is closed.
07-27 08:54:10.176  1029  1709 W libprocessgroup: failed to open /acct/uid_10034/pid_2214/cgroup.procs: No such file or directory
,07-27 08:54:10.220  6632  6632 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:10.227  5999  6348 D UEI.SmartControl: Internal timer expired: 2
07-27 08:54:10.227  5999  6348 D UEI.SmartControl: unbind internal service
,07-27 08:54:10.435  1029  1989 I art     : Explicit concurrent mark sweep GC freed 20687(1096KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.388ms total 120.639ms
,07-27 08:54:10.544  5081  5081 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,07-27 08:54:10.587  1029  2016 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6665 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-27 08:54:10.590  1838  6661 I CheckinService: active receiver: disabled
,07-27 08:54:10.660  6665  6689 D ALBootInit: ====action==>android.intent.action.TIME_SET
,07-27 08:54:10.663  6665  6689 D ALBootInit: Alarm ALBootInit: TIME_SET
07-27 08:54:10.666  6665  6689 D Alarms  : [setNextAlert] start
07-27 08:54:10.675  6665  6689 D Alarms  : [setNextAlert] (1)
,07-27 08:54:10.678  6665  6689 D Alarms  :  minTime  = 0
07-27 08:54:10.679  6665  6689 D Alarms  :  -- OK multi -- 0
07-27 08:54:10.680  6665  6689 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
07-27 08:54:10.680  6665  6689 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
07-27 08:54:10.697  6665  6689 I CommonUtil: BUILD Country: EU
07-27 08:54:10.698  6665  6689 D Alarms  : broadcastToWidgetProvider : false
,07-27 08:54:10.700  6665  6689 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
07-27 08:54:10.706  1029  2046 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
07-27 08:54:10.708  6665  6665 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
07-27 08:54:10.709  6665  6665 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@25c208e
,07-27 08:54:10.711  6665  6665 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@25c208e
07-27 08:54:10.713  6665  6665 D QuickCoverProvider: onReceiver
07-27 08:54:10.718  1553  1553 I indal   : SmartCoverWidgetContext createApplicationContext
07-27 08:54:10.718  1553  1553 I indal   : SmartCoverWidgetContext createApplicationContext
07-27 08:54:10.726  6556  6556 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:54:10
07-27 08:54:10.727  6556  6556 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 08:54:10.727  6556  6556 D Weather.Utils: 2 : All the weather widget is gone.
,07-27 08:54:10.727  6556  6556 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,07-27 08:54:10.730  6556  6556 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ef950af
07-27 08:54:10.730  6556  6556 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 08:54:10.730  6556  6556 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 08:54:10.730  6556  6556 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 08:54:10.732  6556  6556 D Weather_cast: 2 : set auto-update time : 7/27 11:54
07-27 08:54:10.739  6556  6556 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:54:10
,07-27 08:54:10.776  1029  1570 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6695 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 08:54:10.776  1029  1570 I ActivityManager: Killing 4885:com.lge.bnr/1000 (adj 15): empty #17
,07-27 08:54:10.852  1029  1967 W libprocessgroup: failed to open /acct/uid_1000/pid_4885/cgroup.procs: No such file or directory
,07-27 08:54:10.914  6695  6695 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1469602450914
07-27 08:54:10.914  6695  6695 D         : TimeServiceNative: User Time to be set is 1469602450914
07-27 08:54:10.914  6695  6695 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-27 08:54:10.914  6695  6695 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-27 08:54:10.914  6695  6695 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1469602450914
07-27 08:54:10.914  6695  6695 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-27 08:54:10.914   359  1028 D QC-time-services: Daemon: Connection accepted:time_genoff
07-27 08:54:10.915   359  6712 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1469602450914
07-27 08:54:10.915   359  6712 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1469602450914, operation = 0
,07-27 08:54:10.915   359  6712 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/6/70 1:21:54
07-27 08:54:10.915   359  6712 D QC-time-services: Daemon:Value read from RTC seconds = 3115314000
07-27 08:54:10.915   359  6712 D QC-time-services: Daemon:new time 1469602450914 
07-27 08:54:10.916   359  6712 D QC-time-services: Daemon: delta 1466487136914 genoff 1466487136914 
07-27 08:54:10.916   359  6712 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487136914 to memory
07-27 08:54:10.916   359  6712 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-27 08:54:10.916   359  6712 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
07-27 08:54:10.933   359  6712 D QC-time-services: Updating the TOD offset
07-27 08:54:10.933   359  6712 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487136914 to memory
07-27 08:54:10.933   359  6712 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-27 08:54:10.933   359  6712 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-27 08:54:10.937   359  6712 E QC-time-services: Daemon:Update to modem bit set
07-27 08:54:10.937   359  6712 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-27 08:54:10.937   359  6712 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522336914
,07-27 08:54:10.938  6695  6695 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
07-27 08:54:10.940   359  1026 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
07-27 08:54:10.940   359  1028 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-27 08:54:11.017  1029  2083 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6713 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-27 08:54:11.019  1029  2083 I ActivityManager: Killing 6218:com.lge.settings.easy/1000 (adj 15): empty #17
,07-27 08:54:11.153  1029  1989 W libprocessgroup: failed to open /acct/uid_1000/pid_6218/cgroup.procs: No such file or directory
,07-27 08:54:11.182  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:54:11.182  5765  5837 I jxcore-log: 
,07-27 08:54:11.194  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:54:11.194  5765  5837 I jxcore-log: 
07-27 08:54:11.202  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:54:11.202  5765  5837 I jxcore-log: 
,07-27 08:54:11.236  6713  6713 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,07-27 08:54:11.244  6713  6713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
07-27 08:54:11.247  1599  1599 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-27 08:54:11.247  1599  1599 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-27 08:54:11.247  1599  1599 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,07-27 08:54:11.252  6713  6713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
07-27 08:54:11.253  6713  6713 V [BNRBootReceiver]: Boot Receiver Return
07-27 08:54:11.254  6713  6713 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 08:54:11.323  1029  1709 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6735 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,07-27 08:54:11.329  1029  1709 I ActivityManager: Killing 6151:com.lge.sync/1000 (adj 15): empty #17
07-27 08:54:11.363  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:54:11.363  5765  5837 I jxcore-log: 
,07-27 08:54:11.483  1029  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_6151/cgroup.procs: No such file or directory
,07-27 08:54:11.525  6735  6735 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:11.555  6735  6735 D CalendarApplication: CalendarApplication.onCreate()
,07-27 08:54:11.571  6735  6735 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
07-27 08:54:11.572  6735  6735 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3d5bc08d, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@eca2242, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@238ce253, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2f23d790, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@750d889, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@25c208e, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@ef950af, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2d16dcbc, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1f657445, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@39fdb79a, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1a1448cb, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@20d308a8, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@206e0fc1, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@7efb366, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@109ca6a7, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@19a40754, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@240ae6fd, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@fb39ff2, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@11630643, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2de444c0, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3a3f5f9, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3957c93e, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@da5c39f, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3d28ecec, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2d24f8b5, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@d833b4a, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@222cfabb, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@292debd8, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@7796b31, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@641c216, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@26268797, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3181ed84, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@22c8896d, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@208fe9a2, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@bc20633, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1df25df0, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@30714f69, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3aa6fdee, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2e8cd28f, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@23b7691c, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Prefer,enceKey$KeyData@3ec67925, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@b090afa, l
07-27 08:54:11.579  6735  6735 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,07-27 08:54:11.598  6735  6735 D Config  : [init]
,07-27 08:54:11.600  6735  6735 I Config  : LGCalendar ver.4.40.16
07-27 08:54:11.601  6735  6735 I Config  : start check model
07-27 08:54:11.601  6735  6735 I Config  : start check native_ca
07-27 08:54:11.602  6735  6735 I Config  : Config Operator=OPEN, Country=EU
07-27 08:54:11.602  6735  6735 D Config  : [setDefaultValuesToPref]
07-27 08:54:11.602  6735  6735 D Config  : [parseProfiles]
07-27 08:54:11.607  6735  6735 D ProfilesParser: [debug_displayParseInfos] profile.country = null
07-27 08:54:11.607  6735  6735 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
07-27 08:54:11.607  6735  6735 D Config  : [updateProfiletoCountryInfo]
07-27 08:54:11.608  6735  6735 D GeneralPreference: [checkAndMigrateOldPreference]
07-27 08:54:11.619  6735  6735 E AgendaWidgetManager: [updateWidgets] 
,07-27 08:54:11.734  6735  6754 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,07-27 08:54:11.738  6735  6754 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,07-27 08:54:11.748  6735  6735 D MonthWidgetProvider: [onReceive]
07-27 08:54:11.748  6735  6735 D CalendarWidgetProvider: [onReceive]
07-27 08:54:11.748  6735  6735 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,07-27 08:54:11.752  6735  6755 W HolidayIntentService: onHandleIntent
07-27 08:54:11.752  6735  6735 D CalendarTypeController: [onUpdateAndInitCalendarTime]
07-27 08:54:11.754  6735  6755 D HolidayDataLoader: readJsonAsset : holiday.json
07-27 08:54:11.766  6735  6735 D WeekWidgetProvider: [onReceive]
07-27 08:54:11.767  6735  6735 D CalendarWidgetProvider: [onReceive]
07-27 08:54:11.767  6735  6735 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,07-27 08:54:11.771  6735  6735 D CalendarTypeController: [onUpdateAndInitCalendarTime]
07-27 08:54:11.775  2238  2238 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-27 08:54:11.782  6735  6754 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,07-27 08:54:11.784  2238  2238 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-27 08:54:11.785  2238  2238 D c       : Getting all permits...
07-27 08:54:11.785  2238  2238 D a       : Opening database...
07-27 08:54:11.786  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
07-27 08:54:11.789  2238  2238 D a       : Opening database auth.proximity.permit_store...
07-27 08:54:11.790  2238  2238 D a       : Closing database...
07-27 08:54:11.790  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
07-27 08:54:11.805  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,07-27 08:54:11.812  2238  2238 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-27 08:54:11.818  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,07-27 08:54:11.823  6735  6755 E HolidayIntentService: onHandleIntent:holiday data empty
07-27 08:54:11.824  2238  2238 I GCM     : GCM config loaded
07-27 08:54:11.825  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
07-27 08:54:11.830  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
07-27 08:54:11.833  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,07-27 08:54:11.836  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
07-27 08:54:11.840  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
07-27 08:54:11.842  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
07-27 08:54:11.843  6479  6479 V SetupWizard: Connected to Gservices successfully
07-27 08:54:11.848  2238  2238 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-27 08:54:11.849  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,07-27 08:54:11.857  6665  6665 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
07-27 08:54:11.857  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
07-27 08:54:11.860  6556  6556 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:54:11
,07-27 08:54:11.862  6556  6556 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 08:54:11.862  6556  6556 D Weather.Utils: 2 : All the weather widget is gone.
07-27 08:54:11.862  6556  6556 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 08:54:11.863  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
07-27 08:54:11.863  6556  6556 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
,07-27 08:54:11.864  6556  6556 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:54:11
07-27 08:54:11.866  2088  2088 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
07-27 08:54:11.868  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
07-27 08:54:11.868  2088  2821 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
07-27 08:54:11.869  2088  2821 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-27 08:54:11.869  2088  2821 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
07-27 08:54:11.869  2088  2821 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
07-27 08:54:11.869  2088  2821 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
07-27 08:54:11.870  6735  6754 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
07-27 08:54:11.870  6735  6754 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
07-27 08:54:11.871  6713  6713 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
07-27 08:54:11.871  6713  6713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
07-27 08:54:11.873  1599  1599 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-27 08:54:11.873  1599  1599 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-27 08:54:11.873  1599  1599 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
07-27 08:54:11.873  6713  6713 V [BNRBootReceiver]: Boot Receiver Return
,07-27 08:54:11.876  2088  2088 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,07-27 08:54:11.876  6735  6754 I AlertUtils: set default noti to content://media/internal/audio/media/41
07-27 08:54:11.877  2088  5203 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
07-27 08:54:11.878  2088  5203 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-27 08:54:11.878  2088  5203 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
07-27 08:54:11.878  2088  5203 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
07-27 08:54:11.879  2088  5203 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
07-27 08:54:11.881  6735  6754 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
07-27 08:54:11.882  1029  1709 I ActivityManager: Killing 6081:com.android.settings/1000 (adj 15): empty #17
07-27 08:54:11.892  1029  1399 D WifiService: Client connection lost with reason: 4
,07-27 08:54:11.954  1029  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6081/cgroup.procs: No such file or directory
,07-27 08:54:12.388  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:54:12.388  5765  5837 I jxcore-log: ,
,07-27 08:54:12.459  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{335e94c6 type 2 when 111721 com.android.providers.calendar} when 111721
,07-27 08:54:12.474  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:54:12.474  5765  5837 I jxcore-log: 
07-27 08:54:12.500  1029  1086 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6777 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,07-27 08:54:12.506  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:54:12.506  5765  5837 I jxcore-log: 
,07-27 08:54:12.579  6777  6777 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-27 08:54:12.589  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=24.6, 0.0, 0.0  rx=20.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723637357] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 08:54:12.590  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=24.6, 0.0, 0.0  rx=20.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723637358] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 08:54:12.590  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:54:12.616  6777  6777 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1d85e1b7
,07-27 08:54:12.627  1599  1599 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 08:54:12.627  1599  1599 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 08:54:12.632  6777  6777 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
,07-27 08:54:12.633  1970  2145 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 08:54:12.633  1970  2145 D LEDHandler: Battery Level Remaining: 100%
07-27 08:54:12.633  1970  2145 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
07-27 08:54:12.635  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:12.635  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:12.635  6056  6111 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:54:12.635  1029  1399 D WifiController: battery changed pluggedType: 2
07-27 08:54:12.635  6713  6713 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 08:54:12.635  6777  6777 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2f23d790(com.android.providers.calendar.CalendarProvider2@1d85e1b7)
07-27 08:54:12.636  1599  1599 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
07-27 08:54:12.636  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:54:12.637  1599  1599 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:54:12.639  6777  6777 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
07-27 08:54:12.640  6777  6777 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
07-27 08:54:12.647  6238  6238 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-27 08:54:12.647  6238  6238 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2736
,07-27 08:54:12.651  6777  6777 D CalendarProvider2: CalendarProviderIntentService.onCreate()
07-27 08:54:12.652  6777  6807 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
07-27 08:54:12.653  6777  6807 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
07-27 08:54:12.657  6777  6807 E SQLiteLog: (284) automatic index on view_events(_id)
07-27 08:54:12.671  6777  6807 D CalendarProvider2: [IntentService] Release Lock
,07-27 08:54:12.674  6777  6777 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
,07-27 08:54:12.675  1029  2328 I ActivityManager: Killing 6172:com.lge.lifetracker/u0a37 (adj 15): empty #17
07-27 08:54:12.750  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:54:12.750  5765  5837 I jxcore-log: 
,07-27 08:54:12.772  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:54:12.772  5765  5837 I jxcore-log: 
,07-27 08:54:12.777  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:54:12.777  5765  5837 I jxcore-log: 
,07-27 08:54:12.783  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:54:12.783  5765  5837 I jxcore-log: 
,07-27 08:54:12.793  1029  2083 W libprocessgroup: failed to open /acct/uid_10037/pid_6172/cgroup.procs: No such file or directory
,07-27 08:54:12.799  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:54:12.799  5765  5837 I jxcore-log: 
,07-27 08:54:12.818  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
07-27 08:54:12.818  5765  5837 I jxcore-log: 
,07-27 08:54:12.902  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:54:12.902  5765  5837 I jxcore-log: 
,07-27 08:54:12.908  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:54:12.908  5765  5837 I jxcore-log: 
,07-27 08:54:12.943  5765  5837 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:54:12.943  5765  5837 I jxcore-log: 
,07-27 08:54:12.954  5765  5837 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-27 08:54:12.956  5765  5837 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-27 08:54:12.956  5765  5837 I jxcore-log: 
07-27 08:54:13.006  5765  5837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 08:54:13.006  5765  5837 I jxcore-log: 
,07-27 08:54:13.007  5765  5837 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 08:54:13.007  5765  5837 I jxcore-log: 
07-27 08:54:14.018  1029  2329 I ActivityManager: Killing 6402:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-27 08:54:14.049  1029  1987 W libprocessgroup: failed to open /acct/uid_10011/pid_6402/cgroup.procs: No such file or directory
,07-27 08:54:14.625  6576  6597 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:54:15.563  1029  1989 I ActivityManager: Killing 6120:com.lge.formmanager/u0a26 (adj 15): empty #17
,07-27 08:54:15.604  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=12.8, 0.0, 0.0  rx=10.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723640372] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 08:54:15.605  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=12.8, 0.0, 0.0  rx=10.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723640373] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 08:54:15.605  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:15.609  1029  1987 W libprocessgroup: failed to open /acct/uid_10026/pid_6120/cgroup.procs: No such file or directory
,07-27 08:54:17.764  1029  1925 V SIM_STK : Menu title from STK is T-Mobile
,07-27 08:54:17.779  1838  6427 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-27 08:54:17.787   310  6819 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-27 08:54:17.787   310  6819 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-27 08:54:17.787   310  6819 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-27 08:54:18.007  1838  6427 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-27 08:54:18.024  1838  1838 I ConfigFetchService: fetch service done; releasing wakelock
07-27 08:54:18.027  1838  1838 I ConfigFetchService: stopping self
,07-27 08:54:18.069  2238  2238 I ConfigService: onDestroy
,07-27 08:54:18.620  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=7.9, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723643388] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 08:54:18.630  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=7.9, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:723643397] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 08:54:18.630  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:54:19.756  1599  1599 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-27 08:54:19.796  1029  1375 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 08:54:19.849  2088  2088 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 08:54:19.877  1029  1086 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6820 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 08:54:19.911  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,07-27 08:54:19.914  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-27 08:54:19.915  1029  1029 D administrator: Handling package changes for user 0
07-27 08:54:19.931  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 08:54:19.968  6820  6820 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 08:54:20.029  1029  1029 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-27 08:54:20.029  1029  1029 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 08:54:20.071  1029  1085 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:20.077  1029  1085 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-27 08:54:20.085  2459  2459 V GmsNetworkLocationProvi: DISABLE
07-27 08:54:20.085  2088  2088 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-27 08:54:20.086  6820  6820 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:54:20.086  6820  6820 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 08:54:20.122  2459  2459 E GCoreFlp: Bound FusedProviderService with LocationManager
07-27 08:54:20.123  1029  1085 D LocationProviderProxy: applying state to connected service
07-27 08:54:20.148  2238  2267 I art     : Explicit concurrent mark sweep GC freed 8176(477KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 1.007ms total 26.856ms
,07-27 08:54:20.195  6820  6865 I Babel   : MmsConfig: mnc/mcc: 0/0
,07-27 08:54:20.195  6820  6865 I Babel   : MmsConfig.loadMmsSettings
07-27 08:54:20.199  6820  6865 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-27 08:54:20.199  6820  6865 I Babel   : MmsConfig.loadFromDatabase
,07-27 08:54:20.210  6820  6865 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-27 08:54:20.211  6820  6865 I Babel   : MmsConfig.loadFromResources
07-27 08:54:20.213  6820  6865 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-27 08:54:20.214  6820  6865 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-27 08:54:20.227  6820  6820 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:20.233  6820  6863 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 08:54:20.234  6820  6863 W AudioCapabilities: Unsupported mime audio/qcelp
07-27 08:54:20.236  6820  6863 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 08:54:20.244  6820  6863 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-27 08:54:20.245  6820  6863 W AudioCapabilities: Unsupported mime audio/qcelp
,07-27 08:54:20.246  6820  6863 W AudioCapabilities: Unsupported mime audio/evrc
07-27 08:54:20.255  1838  6867 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-27 08:54:20.255  1838  6867 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-27 08:54:20.275  6820  6863 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-27 08:54:20.278  6820  6863 W VideoCapabilities: Unsupported mime video/divx
07-27 08:54:20.282  6820  6863 W VideoCapabilities: Unsupported mime video/divx311
07-27 08:54:20.286  6820  6863 W VideoCapabilities: Unsupported mime video/divx4
,07-27 08:54:20.287  1029  1708 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6870 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-27 08:54:20.297  1838  4493 I Icing   : updateResources: need to parse e{com.google.android.gms}
,07-27 08:54:20.299  6820  6863 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-27 08:54:20.310  1029  2329 I ActivityManager: Killing 6500:com.android.chrome/u0a57 (adj 15): empty #17
,07-27 08:54:20.321  6820  6863 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-27 08:54:20.325  6820  6863 W AudioCapabilities: Unsupported mime audio/eac3
,07-27 08:54:20.327  6820  6863 W AudioCapabilities: Unsupported mime audio/ac3
07-27 08:54:20.328  6820  6863 W AudioCapabilities: Unsupported mime audio/g726
07-27 08:54:20.341  6820  6863 W AudioCapabilities: Unsupported mime audio/wma-voice
,07-27 08:54:20.343  6820  6863 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-27 08:54:20.352  6820  6863 W AudioCapabilities: Unsupported mime audio/adpcm
07-27 08:54:20.362  1029  1925 W libprocessgroup: failed to open /acct/uid_10057/pid_6500/cgroup.procs: No such file or directory
,07-27 08:54:20.366  6820  6863 W VideoCapabilities: Unsupported mime video/theora
07-27 08:54:20.368  6820  6863 W VideoCapabilities: Unsupported mime video/mjpg
07-27 08:54:20.401  6870  6870 I AppUp4:AppBoxCP: onCreate
07-27 08:54:20.401  6870  6870 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-27 08:54:20.406  6870  6870 I AppUp4:DB:  setFingerPrint start
07-27 08:54:20.407  6870  6870 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-27 08:54:20.411  6870  6870 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-27 08:54:20.411  6870  6870 I AppUp4:DB:  SDK version = 21
07-27 08:54:20.411  6870  6870 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-27 08:54:20.413  6870  6870 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-27 08:54:20.418  6870  6870 I AppUp4:CustModeStarterReceiver: onReceive
,07-27 08:54:20.451  6870  6870 D LgDataFeature: LgDataFeature() Constructor: none
07-27 08:54:20.451  6870  6870 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 08:54:20.458  6870  6870 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@eca2242
07-27 08:54:20.458  6870  6870 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 08:54:20.458  6870  6870 D AppUp4:CustFacade: isPhone : true
07-27 08:54:20.458  6870  6870 D AppUp4:CustModeStarterReceiver: begin check event
07-27 08:54:20.458  6870  6870 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-27 08:54:20.494  1029  1709 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6891 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-27 08:54:20.494  1029  1709 I ActivityManager: Killing 6531:com.lge.drmservice/u0a62 (adj 15): empty #17
07-27 08:54:20.593  1029  2087 W libprocessgroup: failed to open /acct/uid_10062/pid_6531/cgroup.procs: No such file or directory
,07-27 08:54:20.746  1029  2328 I art     : Explicit concurrent mark sweep GC freed 23093(1160KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.185ms total 143.893ms
,07-27 08:54:20.772  6891  6891 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:20.772  6891  6891 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:20.773  6891  6891 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,07-27 08:54:20.774  6891  6891 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-27 08:54:20.775  6891  6891 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 08:54:20.885  6891  6891 I SystemConfig: BUILD Country: EU
07-27 08:54:20.885  6891  6891 I SystemConfig: BUILD Operator: OPEN
,07-27 08:54:20.951  1029  2087 I ActivityManager: Killing 6576:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,07-27 08:54:21.068  1029  2328 W libprocessgroup: failed to open /acct/uid_10093/pid_6576/cgroup.procs: No such file or directory
,07-27 08:54:21.134  1029  2087 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6913 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-27 08:54:21.144  6891  6911 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-27 08:54:21.145  6891  6911 I SystemConfig: existFile = false
07-27 08:54:21.145  6891  6911 I SystemConfig: canReadFile = false
07-27 08:54:21.145  6891  6911 I SystemConfig: systemFeature RCS result false
07-27 08:54:21.145  6891  6911 D SystemConfig: refreshRcsSupport() :false
07-27 08:54:21.156   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 22.596ms
,07-27 08:54:21.176   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 19.538ms
07-27 08:54:21.198   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 20.590ms
07-27 08:54:21.198  6913  6913 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:21.199  6913  6913 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 08:54:21.199  6913  6913 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-27 08:54:21.199  6913  6913 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-27 08:54:21.297  6913  6913 I AppConfig: Total System Memory = 2995761152
,07-27 08:54:21.308  6913  6913 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-27 08:54:21.419  1029  1925 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6932 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 08:54:21.419  1029  1925 I ActivityManager: Killing 6632:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-27 08:54:21.472  1029  1987 W libprocessgroup: failed to open /acct/uid_10097/pid_6632/cgroup.procs: No such file or directory
,07-27 08:54:21.652  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=9.0, 0.0, 0.0  rx=6.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723646420] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 08:54:21.653  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=9.0, 0.0, 0.0  rx=6.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723646421] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 08:54:21.653  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:21.662  6932  6932 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
07-27 08:54:21.781  6932  6932 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 08:54:21.781  6932  6932 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 08:54:21.849  6932  6932 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-27 08:54:21.870  6932  6932 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:54:21.871  6932  6932 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-27 08:54:21.887  6932  6932 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,07-27 08:54:21.888  6932  6932 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
07-27 08:54:21.922  1029  1967 I ActivityManager: Killing 6435:com.lge.email/u0a23 (adj 15): empty #17
,07-27 08:54:21.954  1029  1709 W libprocessgroup: failed to open /acct/uid_10023/pid_6435/cgroup.procs: No such file or directory
,07-27 08:54:21.959  3412  3428 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-27 08:54:21.960  3412  3428 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3c4cdcc6 on behalf of 6932
07-27 08:54:21.969  4340  6972 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-27 08:54:22.039  1029  1708 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6973 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:22.064  6932  6932 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-27 08:54:22.108  6932  6932 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-27 08:54:22.161  6973  6973 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-27 08:54:22.193  6973  6973 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-27 08:54:22.193  6973  6973 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-27 08:54:22.193  6973  6973 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-27 08:54:22.193  6973  6973 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-27 08:54:22.193  6973  6973 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,07-27 08:54:22.193  6973  6973 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
07-27 08:54:22.252  1029  1044 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7003 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:22.253  1029  1044 I ActivityManager: Killing 5081:com.wsandroid.suite.lge/1000 (adj 15): empty #17
07-27 08:54:22.309  1029  1987 W libprocessgroup: failed to open /acct/uid_1000/pid_5081/cgroup.procs: No such file or directory
,07-27 08:54:22.376  7003  7003 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:22.472  1029  2015 V SIM_STK : Menu title from STK is T-Mobile
,07-27 08:54:22.504  4340  6972 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 535 ms] updated apps [took 535 ms] 
,07-27 08:54:23.079  1029  1086 W ProcessCpuTracker: Skipping unknown process pid 6827
,07-27 08:54:23.083  1029  1086 W ProcessCpuTracker: Skipping unknown process pid 6828
07-27 08:54:23.083  1029  1086 W ProcessCpuTracker: Skipping unknown process pid 6841
07-27 08:54:23.084  1029  1086 W ProcessCpuTracker: Skipping unknown process pid 6852
07-27 08:54:23.087  1029  1086 W ProcessCpuTracker: Skipping unknown process pid 7041
07-27 08:54:24.671  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:723649438] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:24.677  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:723649445] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:54:24.677  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:54:27.685  1029  2016 I ActivityManager: Killing 6695:com.qualcomm.timeservice/1000 (adj 15): empty #17
,07-27 08:54:27.694  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723652462] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:54:27.695  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723652463] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:54:27.696  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:54:27.723  1029  2015 W libprocessgroup: failed to open /acct/uid_1000/pid_6695/cgroup.procs: No such file or directory
,07-27 08:54:30.709  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723655477] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:30.720  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723655487] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:30.720  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:33.740  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723658508] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:33.754  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:723658522] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:33.755  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:36.775  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723661543] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:36.778  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723661546] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:36.778  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,07-27 08:54:39.801  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:723664568] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:39.812  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:723664579] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:39.812  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:42.829  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723667597] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:42.841  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:723667609] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:42.842  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:43.533  1029  1385 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,07-27 08:54:43.535  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-27 08:54:43.536  1029  1385 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-27 08:54:43.537  1029  1385 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,07-27 08:54:43.538  1029  1385 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
,07-27 08:54:43.540  1029  1385 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,07-27 08:54:45.863  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723670631] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:45.866  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723670634] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:45.866  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:48.085  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3ce72c1e type 2 when 147338 com.google.android.gms} when 147338
,07-27 08:54:48.137  1838  1838 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-27 08:54:48.143  2238  2238 I ConfigService: onCreate
07-27 08:54:48.144  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 08:54:48.145  1838  7045 I ConfigFetchService: running network task: configservice_periodic
07-27 08:54:48.147  1838  7045 I ConfigFetchService: launchTask
07-27 08:54:48.154  2238  2238 I ConfigService: onBind returning update interface
,07-27 08:54:48.158  1838  1838 I ConfigFetchService: service connected
07-27 08:54:48.158  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 08:54:48.158  2238  2238 I ConfigService: onBind returning config service
07-27 08:54:48.160  1838  1838 I ConfigClient: service connected
07-27 08:54:48.226  1029  2046 V SIM_STK : Menu title from STK is T-Mobile
,07-27 08:54:48.254  1838  2364 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-27 08:54:48.272   310  7052 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:54:48.272   310  7052 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-27 08:54:48.272   310  7052 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-27 08:54:48.487  1838  2364 W ConfigFetchTask: bad response from server: 401 Unauthorized
07-27 08:54:48.490  1838  1838 I ConfigFetchService: fetch service done; releasing wakelock
,07-27 08:54:48.496  1838  1838 I ConfigFetchService: stopping self
07-27 08:54:48.531  2238  2238 I ConfigService: onDestroy
,07-27 08:54:48.895  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723673663] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:48.897  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:723673665] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:48.898  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:51.921  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:723676689] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 08:54:51.924  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723676692] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 08:54:51.925  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:54.947  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723679715] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:54.951  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723679718] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:54.951  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:57.977  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723682745] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:57.980  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723682748] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:54:57.980  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:54:59.543  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 08:54:59.543  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:54:59.543  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 08:54:59.544  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:54:59.558  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 08:54:59.558  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:54:59.561  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:54:59.564  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:55:00.054  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 08:55:00.054  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:55:00.055  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 08:55:00.055  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:55:00.070  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:55:00.070  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:55:00.082  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:55:00.083  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:55:01.000  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723685768] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:01.017  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:723685784] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:01.017  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:55:04.040  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723688807] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:04.052  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:723688820] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:04.052  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:07.073  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723691840] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:07.076  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723691843] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:07.076  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:10.098  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723694866] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:10.107  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723694869] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:10.108  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:55:13.126  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723697894] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:13.129  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723697897] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:13.130  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:16.155  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723700923] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:16.158  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723700926] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:16.158  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:19.179  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723703947] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:19.188  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:723703956] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:19.188  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:22.213  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:723706981] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:22.216  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723706984] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:22.216  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:25.238  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723710006] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:25.239  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723710007] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:25.239  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:28.256  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723713024] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:28.260  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723713027] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:28.260  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:29.075  1599  1599 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 08:55:29.075  1599  1599 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 08:55:29.087  1029  1399 D WifiController: battery changed pluggedType: 2
,07-27 08:55:29.091  1970  2145 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 08:55:29.091  1970  2145 D LEDHandler: Battery Level Remaining: 100%
07-27 08:55:29.091  1970  2145 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
07-27 08:55:29.092  1599  1599 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
07-27 08:55:29.092  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:55:29.096  6056  6111 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:55:29.097  1599  1599 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:55:29.098  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:55:29.099  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 08:55:29.102  6713  6713 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 08:55:31.283  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723716050] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:31.286  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723716053] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:31.286  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:34.308  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723719076] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:34.311  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723719079] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:34.318  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:37.338  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723722106] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:37.349  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723722109] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:37.349  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:55:40.367  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:723725135] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:40.368  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723725136] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:40.368  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:43.388  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723728156] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:43.396  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723728159] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:43.396  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:55:46.417  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723731185] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:46.420  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723731188] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:55:46.420  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:48.508  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 08:55:48.533  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{290449c9 type 2 when 207770 com.google.android.gms} when 207770
,07-27 08:55:48.592  1838  1838 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-27 08:55:48.608  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 08:55:48.622  2238  2238 I ConfigService: onCreate
,07-27 08:55:48.624  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 08:55:48.638  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 08:55:48.643  1838  7057 I ConfigFetchService: running network task: configservice_periodic
07-27 08:55:48.648  1838  7057 I ConfigFetchService: launchTask
07-27 08:55:48.653  2238  2238 I ConfigService: onBind returning update interface
,07-27 08:55:48.656  1838  1838 I ConfigFetchService: service connected
07-27 08:55:48.656  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 08:55:48.656  2238  2238 I ConfigService: onBind returning config service
07-27 08:55:48.658  1838  1838 I ConfigClient: service connected
07-27 08:55:48.724  1029  1570 V SIM_STK : Menu title from STK is T-Mobile
,07-27 08:55:48.735  1838  2367 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-27 08:55:48.738   310  7077 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:55:48.738   310  7077 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-27 08:55:48.740   310  7077 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-27 08:55:48.953  1838  2367 W ConfigFetchTask: bad response from server: 401 Unauthorized
07-27 08:55:48.956  1838  1838 I ConfigFetchService: fetch service done; releasing wakelock
,07-27 08:55:48.958  1838  1838 I ConfigFetchService: stopping self
07-27 08:55:49.018  2238  2238 I ConfigService: onDestroy
07-27 08:55:49.018  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{393dc300 type 2 when 201777 android} when 201777
,07-27 08:55:49.446  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723734213] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:49.449  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723734216] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:49.449  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:52.472  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723737240] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 08:55:52.475  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723737243] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 08:55:52.475  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:55.505  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:723740273] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:55.508  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723740276] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:55.508  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:55:58.528  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723743296] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:58.538  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:723743305] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:55:58.539  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:56:00.062  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 08:56:00.062  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:56:00.063  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 08:56:00.063  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:56:00.078  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 08:56:00.078  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:56:00.081  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:56:00.084  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:56:01.560  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723746328] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:01.570  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723746338] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:01.571  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:56:04.173  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 08:56:04.242  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 08:56:04.269  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 08:56:04.595  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:723749363] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:04.598  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723749366] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:04.598  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:07.624  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:723752392] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:07.625  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723752393] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:07.625  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:10.646  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:723755413] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:10.648  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723755416] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:10.649  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:13.668  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723758436] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:13.677  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:723758444] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:13.678  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:56:16.698  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723761465] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:16.701  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723761468] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:16.701  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:19.727  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723764495] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:19.730  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723764498] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:19.730  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:22.756  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723767523] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:22.766  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:723767534] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:22.766  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:25.786  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723770554] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:25.789  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723770557] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:25.790  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:28.809  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723773577] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:28.820  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723773587] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:28.820  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:31.842  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723776609] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:31.845  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723776612] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:31.845  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:34.868  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723779635] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:34.871  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723779638] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:34.871  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:37.893  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723782661] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:37.896  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723782664] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:37.896  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:40.921  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723785688] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:40.931  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723785698] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:40.931  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:56:43.953  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723788721] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:43.956  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723788724] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:43.956  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:46.982  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723791750] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:46.985  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723791753] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:46.985  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:50.009  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723794777] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:50.019  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:723794786] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:50.019  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:56:53.040  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723797808] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:53.053  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:723797821] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:53.053  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:56.075  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723800842] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:56:56.078  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:723800846] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:56.078  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:56:59.101  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723803868] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:59.110  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723803878] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:56:59.110  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:57:00.056  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 08:57:00.056  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:57:00.056  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 08:57:00.057  1599  1599 I [SystemUI]Clock: called onTimeUpdated(),
,07-27 08:57:00.073  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 08:57:00.073  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 08:57:00.075  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:57:00.077  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:57:02.132  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723806900] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:02.135  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723806903] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-27 08:57:02.135  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:05.159  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723809926] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:05.168  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723809936] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:05.169  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:57:08.191  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723812958] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:08.203  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:723812970] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:08.203  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:57:11.228  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:723815995] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:11.231  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723815998] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:11.231  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:14.259  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723819027] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:14.269  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723819037] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:14.269  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:57:17.287  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:723822055] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:17.288  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:723822056] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:17.288  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:20.307  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723825074] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:20.310  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:723825078] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:20.310  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:23.335  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723828103] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:23.338  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723828106] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:23.339  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:26.363  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723831130] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:26.366  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:723831134] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:26.366  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:29.393  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723834161] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:29.396  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723834164] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:29.396  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:32.420  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723837188] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:32.430  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723837198] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:32.431  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:35.452  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723840220] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:35.455  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723840223] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:35.455  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:38.480  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723843248] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:38.490  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723843258] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:38.491  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:41.512  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723846279] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:41.514  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723846282] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:41.515  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:44.537  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723849305] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:44.540  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723849308] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:44.540  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:47.567  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723852335] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:47.570  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723852338] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:47.570  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:48.978  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 08:57:49.002  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2b63739 type 2 when 328240 com.google.android.gms} when 328240
,07-27 08:57:49.069  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 08:57:49.076  1838  1838 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-27 08:57:49.091  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 08:57:49.097  2238  2238 I ConfigService: onCreate
07-27 08:57:49.098  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 08:57:49.102  1838  7095 I ConfigFetchService: running network task: configservice_periodic
07-27 08:57:49.104  1838  7095 I ConfigFetchService: launchTask
,07-27 08:57:49.110  2238  2238 I ConfigService: onBind returning update interface
07-27 08:57:49.114  1838  1838 I ConfigFetchService: service connected
07-27 08:57:49.115  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 08:57:49.115  2238  2238 I ConfigService: onBind returning config service
07-27 08:57:49.116  1838  1838 I ConfigClient: service connected
,07-27 08:57:49.204  1029  1045 V SIM_STK : Menu title from STK is T-Mobile
,07-27 08:57:49.219  1838  3834 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-27 08:57:49.226   310  7113 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 08:57:49.226   310  7113 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-27 08:57:49.264   310  7113 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-27 08:57:49.537  1838  3834 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-27 08:57:49.547  1838  1838 I ConfigFetchService: fetch service done; releasing wakelock
,07-27 08:57:49.550  1838  1838 I ConfigFetchService: stopping self
07-27 08:57:49.603  2238  2238 I ConfigService: onDestroy
,07-27 08:57:50.594  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723855361] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:50.597  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723855364] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:50.597  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:53.623  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723858391] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 08:57:53.626  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723858394] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 08:57:53.626  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:55.158  1029  3452 I LocationManagerService: remove 1ea348c4
,07-27 08:57:55.159  1029  3452 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,07-27 08:57:55.159  1029  3452 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 08:57:55.160  1029  3452 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:57:55.173  1029  3452 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-27 08:57:55.175  1029  3452 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-27 08:57:56.652  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723861420] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:56.656  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723861423] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:57:56.656  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:57:59.684  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723864452] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,07-27 08:57:59.687  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723864455] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:57:59.687  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:00.055  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 08:58:00.055  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:58:00.056  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 08:58:00.056  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:58:00.070  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:58:00.070  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:58:00.074  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 08:58:00.083  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:58:02.713  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723867480] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:58:02.716  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723867483] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:58:02.716  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:04.169  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 08:58:04.236  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 08:58:04.269  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 08:58:05.739  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723870507] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:05.750  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:723870518] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:05.751  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:08.773  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723873541] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:58:08.776  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723873544] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:08.776  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:11.799  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723876567] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:11.810  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723876577] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:11.810  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:58:14.830  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723879598] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:14.842  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:723879610] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:14.842  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:58:17.864  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:723882632] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:17.867  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723882635] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:58:17.867  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:20.890  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723885658] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:20.900  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723885668] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:20.900  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:58:23.920  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723888688] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:23.933  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:723888700] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:23.933  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:26.952  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723891720] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:58:26.955  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723891723] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:26.955  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:29.982  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723894750] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:29.985  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723894753] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:29.985  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:33.011  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723897779] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:33.021  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723897789] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:33.022  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:36.042  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723900809] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:58:36.045  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:723900813] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:36.045  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:39.072  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723903839] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:39.075  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:723903843] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:39.075  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:42.101  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723906868] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:42.111  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:723906879] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:42.112  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:45.132  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723909899] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:45.135  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723909902] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:58:45.135  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:48.155  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723912923] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:48.158  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723912926] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:48.158  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:51.183  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723915951] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:51.186  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723915954] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:51.186  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:54.216  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723918983] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:54.218  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723918986] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:54.219  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:58:57.242  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723922009] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:57.245  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:723922013] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:58:57.245  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:00.061  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 08:59:00.062  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:59:00.062  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 08:59:00.063  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:59:00.077  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:59:00.077  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:59:00.079  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:59:00.083  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:59:00.274  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723925042] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:00.277  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723925045] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:00.278  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:03.304  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723928072] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:03.307  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723928075] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:59:03.308  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:06.333  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723931101] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:06.336  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723931104] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:06.336  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:09.362  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723934130] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:09.365  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723934133] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:09.366  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:12.391  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723937158] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:12.401  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723937168] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:12.401  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:59:15.422  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723940189] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:15.425  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723940192] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:59:15.425  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:18.450  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723943218] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:18.462  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:723943229] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:18.463  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:59:21.483  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723946251] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:21.486  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723946254] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:59:21.486  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:24.512  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723949280] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:24.515  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723949283] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:59:24.515  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:27.542  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723952309] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:27.545  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:723952313] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:27.545  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:30.571  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723955339] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:30.582  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:723955350] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:30.582  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:33.604  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723958371] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:59:33.607  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723958374] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:59:33.607  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:36.632  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723961400] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:36.635  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723961403] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:36.635  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:39.668  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723964435] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:39.671  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:723964439] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:59:39.671  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:42.698  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723967466] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:42.708  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723967469] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:42.708  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:59:45.729  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723970497] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:45.740  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:723970508] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:45.740  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:48.762  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723973530] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 08:59:48.765  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723973533] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:48.765  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:51.787  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723976555] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:51.790  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723976558] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:51.791  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 08:59:54.809  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723979577] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:54.820  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723979587] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:54.820  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 08:59:57.840  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723982608] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:57.852  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:723982620] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 08:59:57.852  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:00:00.053  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:00:00.053  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:00:00.053  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:00:00.054  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:00:00.069  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:00:00.069  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:00:00.072  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:00:00.078  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:00:00.875  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723985643] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:00.878  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723985646] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:00.878  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:01.713  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 09:00:01.743  6665  6665 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-27 09:00:01.749  6665  6665 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@25c208e
07-27 09:00:01.789  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:00:01.824  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 09:00:03.900  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723988668] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:03.910  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:723988678] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:03.910  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:00:06.931  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:723991698] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:06.942  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:723991709] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:06.942  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:09.962  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:723994730] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:09.965  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:723994733] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:09.966  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:12.991  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:723997759] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:13.000  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:723997768] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:13.001  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:00:16.021  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724000789] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:16.034  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:724000802] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:16.035  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:19.055  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724003823] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:19.068  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:724003836] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:19.069  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:00:22.089  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724006857] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:22.106  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:724006873] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:22.106  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:25.126  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724009894] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:25.129  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724009897] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:25.130  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:28.152  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724012920] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:28.155  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724012923] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:28.156  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:31.176  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724015944] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:31.179  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724015947] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:31.180  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:34.204  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2997] from screen [on:0 period:724018972] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:34.207  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724018975] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:34.208  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:37.234  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724022001] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:37.237  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724022005] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:37.237  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:40.263  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724025031] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:40.266  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724025034] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:40.266  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:43.291  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724028058] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:43.301  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724028069] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:43.301  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:46.322  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724031090] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:46.326  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724031093] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:46.326  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:49.352  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724034119] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:49.355  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724034123] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:49.355  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:52.381  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724037148] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:52.391  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724037158] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:52.391  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:00:55.414  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724040181] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:55.417  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724040185] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:00:55.417  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:00:58.445  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724043213] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:58.448  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724043216] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:00:58.448  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:00.059  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:01:00.059  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:01:00.059  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:01:00.060  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:01:00.074  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:01:00.074  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:01:00.077  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:01:00.079  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:01:01.468  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724046236] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:01.481  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724046239] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:01.481  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:04.503  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724049270] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:04.506  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724049274] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:04.506  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:07.530  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:724052297] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:07.540  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724052308] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:07.541  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:10.564  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724055332] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:10.567  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724055335] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:10.567  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:13.592  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724058359] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:13.595  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724058363] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-27 09:01:13.595  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:16.622  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724061390] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:16.625  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724061393] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:16.625  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:19.650  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724064417] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:19.660  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724064427] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:19.660  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:01:22.679  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724067447] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:22.691  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724067459] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:22.691  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:01:25.710  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724070478] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:25.722  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724070490] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:25.722  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:28.742  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724073510] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:28.745  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724073513] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:28.745  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:31.768  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724076536] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:31.778  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724076545] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:31.778  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:01:34.800  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724079568] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:34.812  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724079580] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:34.813  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:37.834  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724082602] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:37.849  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:724082616] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:37.849  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:01:40.868  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:724085635] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:40.871  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724085638] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:40.871  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:43.895  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724088663] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:43.898  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724088666] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:43.898  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:46.924  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724091692] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:46.928  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724091695] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:46.928  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:01:49.569  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 09:01:49.585  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{26c7ec30 type 2 when 568831 com.google.android.gms} when 568831
,07-27 09:01:49.652  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:01:49.684  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 09:01:49.883  1029  1967 I art     : Explicit concurrent mark sweep GC freed 135376(6MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.989ms total 189.375ms
,07-27 09:01:49.887  2238  2238 I ConfigService: onCreate
07-27 09:01:49.890  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 09:01:49.890  1838  1838 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-27 09:01:49.899  1838  7152 I ConfigFetchService: running network task: configservice_periodic
07-27 09:01:49.900  1838  7152 I ConfigFetchService: launchTask
,07-27 09:01:49.905  2238  2238 I ConfigService: onBind returning update interface
07-27 09:01:49.906  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 09:01:49.906  2238  2238 I ConfigService: onBind returning config service
07-27 09:01:49.906  1838  1838 I ConfigFetchService: service connected
07-27 09:01:49.907  1838  1838 I ConfigClient: service connected
07-27 09:01:49.947  1029  2328 V SIM_STK : Menu title from STK is T-Mobile
,07-27 09:01:49.953  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724094721] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:49.954  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:724094722] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:49.954  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:01:49.958  1838  5522 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-27 09:01:49.961   310  7155 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 09:01:49.962   310  7155 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-27 09:01:50.001   310  7155 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-27 09:01:50.300  1838  5522 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-27 09:01:50.309  1838  1838 I ConfigFetchService: fetch service done; releasing wakelock
07-27 09:01:50.313  1838  1838 I ConfigFetchService: stopping self
07-27 09:01:50.355  2238  2238 I ConfigService: onDestroy
,07-27 09:01:52.970  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724097738] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:52.980  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724097748] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:01:52.980  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:01:56.001  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=7.2, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724100768] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 09:01:56.013  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=7.2, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:724100781] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 09:01:56.013  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:01:59.035  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724103802] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:59.038  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724103806] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:01:59.038  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:00.053  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:02:00.053  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:02:00.054  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:02:00.054  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:02:00.068  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:02:00.068  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:02:00.071  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:02:00.074  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:02:02.058  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:724106826] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:02.059  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:724106827] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:02.059  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:05.077  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724109844] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:05.080  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724109848] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:05.080  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:08.102  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724112870] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:08.105  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724112873] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:08.106  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:11.129  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724115896] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:11.137  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724115905] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:11.138  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:02:14.158  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724118926] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:14.161  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724118929] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:14.171  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:17.191  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724121959] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:17.202  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724121969] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:17.202  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:20.224  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724124991] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:20.227  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724124995] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:20.227  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:23.248  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724128015] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:23.251  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724128019] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:23.251  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:26.277  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724131045] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:26.280  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724131048] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:26.280  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:29.307  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724134074] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:29.310  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724134077] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:29.310  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:32.329  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724137097] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:32.339  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724137106] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:32.339  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:02:35.358  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:724140126] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:35.370  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724140137] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:35.371  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:02:38.390  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724143158] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:38.402  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724143170] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:38.403  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:41.425  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724146192] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:41.428  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724146195] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:41.428  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:44.452  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724149220] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:44.455  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724149223] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:44.455  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:47.480  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724152248] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:47.489  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724152257] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:47.489  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:02:50.509  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724155277] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:50.521  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724155289] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:50.521  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:02:53.542  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724158310] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:53.545  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724158313] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:02:53.546  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,07-27 09:02:56.569  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:724161337] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:56.579  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724161347] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:56.580  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:02:59.600  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724164368] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:59.613  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724164380] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:02:59.613  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:00.054  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:03:00.055  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:03:00.055  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:03:00.055  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:03:00.069  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:03:00.070  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:03:00.073  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:03:00.083  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:03:02.635  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724167403] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:03:02.638  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724167406] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:02.638  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:04.172  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 09:03:04.240  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:03:04.271  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 09:03:05.660  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724170428] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:05.670  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724170438] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:05.671  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:08.692  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724173460] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:03:08.695  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724173463] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:08.695  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:10.783  1029  1967 I ActivityManager: Killing 6735:com.android.calendar/u0a13 (adj 15): empty #17
,07-27 09:03:10.822  1029  1925 W libprocessgroup: failed to open /acct/uid_10013/pid_6735/cgroup.procs: No such file or directory
,07-27 09:03:11.721  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724176489] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:11.730  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:724176497] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:11.730  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:03:14.750  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724179518] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:14.763  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:724179531] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:14.763  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:17.785  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724182553] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:03:17.788  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724182556] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:17.788  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:20.809  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724185577] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:20.818  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724185586] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:20.819  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:03:23.839  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724188607] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:23.851  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724188618] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:23.851  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:03:26.870  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724191638] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:26.882  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724191649] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:26.882  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:29.903  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724194671] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:03:29.906  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724194674] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:29.906  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:32.927  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724197695] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:32.930  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724197698] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:03:32.930  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:35.954  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724200722] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:03:35.957  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724200725] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:03:35.958  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:38.982  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724203749] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:38.984  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724203752] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:38.985  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:42.009  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724206776] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:42.018  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724206785] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:42.018  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:03:45.040  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724209808] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:45.053  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724209820] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:45.053  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:03:48.074  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724212841] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:48.077  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724212844] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:03:48.077  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:51.102  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724215870] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:51.105  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724215873] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:51.105  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:54.129  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724218897] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:54.139  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724218907] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:54.139  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:03:57.158  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724221926] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:57.169  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724221929] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:03:57.170  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:00.063  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:04:00.063  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:04:00.063  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:04:00.064  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:04:00.079  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:04:00.080  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:04:00.084  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:04:00.086  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:04:00.191  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724224958] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:00.202  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724224970] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:00.203  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:03.223  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724227991] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:03.225  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:724227993] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:04:03.225  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:06.249  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724231017] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:06.258  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:724231025] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:06.258  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:04:09.278  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724234046] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:09.281  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724234049] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:09.290  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:12.312  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724237080] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:12.315  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724237083] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:12.315  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:15.342  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724240110] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:15.346  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724240113] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:15.346  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:18.370  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724243138] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:18.380  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724243148] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:18.381  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:04:21.400  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724246168] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:21.412  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724246180] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:21.413  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:04:24.434  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724249202] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:24.437  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724249205] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:04:24.437  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:27.464  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724252232] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:27.467  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724252235] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:27.467  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:30.502  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3012] from screen [on:0 period:724255270] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:30.505  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724255273] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:30.506  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:33.526  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724258294] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:33.529  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724258297] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:33.529  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:36.549  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724261317] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:36.559  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724261327] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:36.559  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:04:39.579  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724264347] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:39.591  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724264358] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:39.591  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:04:42.611  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724267379] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:42.622  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724267390] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:42.623  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:45.644  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724270412] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:04:45.647  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724270415] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:45.647  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:48.673  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:724273441] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:48.676  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724273444] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:48.676  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:51.704  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724276472] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:51.707  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724276475] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:51.708  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:54.733  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724279501] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:54.736  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724279504] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:54.736  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:04:57.760  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724282527] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:57.769  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724282537] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:04:57.769  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:00.057  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:05:00.057  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:05:00.057  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:05:00.058  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:05:00.074  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:05:00.075  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:05:00.077  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:05:00.087  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:05:00.790  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724285558] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:00.808  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:18] from screen [on:0 period:724285576] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:00.808  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:05:03.828  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724288596] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:03.831  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724288599] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:03.840  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:06.863  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724291631] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:06.866  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724291634] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:05:06.866  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:09.893  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724294660] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:09.896  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724294663] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:09.896  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:12.921  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724297689] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:12.930  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724297698] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:12.930  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:05:15.950  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724300718] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:15.963  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724300730] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:15.963  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:18.983  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724303751] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:05:18.986  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724303754] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:18.986  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:22.014  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724306781] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:22.017  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724306784] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:22.017  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:25.040  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724309808] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:25.051  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724309818] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:25.051  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:28.074  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724312841] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:05:28.077  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724312844] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:28.077  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:31.102  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724315870] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:05:31.105  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724315873] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:05:31.105  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:34.129  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724318897] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:34.139  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724318907] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:34.140  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:05:37.160  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724321928] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:37.172  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724321939] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:37.172  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:40.193  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724324961] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:05:40.196  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724324964] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:40.197  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:43.222  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:724327990] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:43.225  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724327993] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:43.225  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:46.250  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724331018] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:46.261  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724331028] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:46.261  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:49.283  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724334051] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:05:49.286  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724334054] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:49.286  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:52.313  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724337081] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:52.316  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724337084] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:05:52.317  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:55.340  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724340108] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:55.350  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724340118] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:55.350  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:05:58.371  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724343139] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:58.385  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:724343152] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:05:58.385  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:00.063  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:06:00.063  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:06:00.063  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:06:00.064  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:06:00.080  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:06:00.080  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:06:00.082  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:06:00.084  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:06:01.401  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724346169] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:01.405  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724346173] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:01.405  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:04.430  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724349198] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:04.440  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724349208] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:04.441  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:07.462  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724352229] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:07.464  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724352232] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:07.465  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:10.490  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724355257] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:10.500  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724355268] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:10.500  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:13.521  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724358289] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:13.525  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724358293] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:13.525  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:16.550  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724361318] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:16.560  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724361328] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:16.561  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:19.582  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724364350] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:19.585  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724364353] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:19.585  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:22.610  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724367378] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:22.620  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724367388] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:22.620  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:25.642  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724370410] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:25.645  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724370413] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:25.646  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:28.672  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724373440] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:28.675  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724373443] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:28.675  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:31.700  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724376468] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:31.711  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724376479] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:31.711  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:06:34.732  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724379499] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:34.735  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724379503] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:34.735  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:37.760  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724382528] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:37.770  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724382538] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:37.771  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:40.791  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:724385558] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:40.808  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:18] from screen [on:0 period:724385576] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:40.811  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:06:43.829  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724388596] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:43.840  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724388608] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:43.841  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:06:46.860  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724391628] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:46.872  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724391640] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:46.873  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:06:49.894  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724394662] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:49.897  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724394665] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:49.898  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:52.922  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724397689] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:52.925  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724397693] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:52.925  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:55.950  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724400718] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:55.961  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724400728] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:55.962  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:06:58.984  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724403751] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:06:58.987  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724403754] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:06:58.987  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:00.061  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:07:00.067  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:07:00.067  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:07:00.068  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
07-27 09:07:00.075  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:07:00.075  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:07:00.077  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:07:00.079  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:07:02.014  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724406781] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:07:02.017  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724406784] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:02.017  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,07-27 09:07:05.040  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724409808] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:05.050  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724409818] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:05.051  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:08.072  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724412840] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:07:08.075  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724412843] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:08.075  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:11.099  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724415867] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:11.112  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724415879] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:11.112  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:07:14.132  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724418900] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:14.135  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724418903] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:07:14.135  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:17.161  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724421929] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:17.171  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724421939] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:17.171  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:07:20.190  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724424958] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:20.202  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724424970] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:20.202  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:07:23.223  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724427991] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:23.226  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724427994] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:07:23.226  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:26.252  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724431019] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:26.255  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724431022] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:26.255  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:29.278  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724434046] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:29.281  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724434049] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:29.288  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:32.318  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724437085] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:07:32.321  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724437089] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:32.321  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:35.349  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724440117] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:35.359  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724440127] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:35.360  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:07:38.379  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724443147] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:38.390  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724443157] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:38.390  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:07:41.413  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724446180] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:41.416  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724446183] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:07:41.416  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:44.439  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724449206] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:44.449  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724449216] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:44.449  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:07:47.468  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724452236] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:47.471  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724452239] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:07:47.471  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:50.499  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724455267] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:50.510  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724455277] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:50.510  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:07:53.531  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724458298] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:53.542  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724458310] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,07-27 09:07:53.543  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:07:56.564  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724461332] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:07:56.567  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724461335] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:56.568  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:07:59.595  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724464362] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:59.598  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724464366] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:07:59.598  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:00.096  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:08:00.097  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:08:00.097  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:08:00.097  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:08:00.110  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:08:00.110  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:08:00.114  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:08:00.120  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:08:02.619  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724467387] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:02.631  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724467398] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:02.631  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:08:05.654  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724470421] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:05.666  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:724470434] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:05.667  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:08:06.582   495  1021 I Sensors : sns_pwr.c(273):acquiring wakelock
,07-27 09:08:06.589  1029  1054 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 33, msg Id 5, txn Id 0
,07-27 09:08:06.589  1029  1054 D sensors_hal_KnockOnProx: processInd: SNS_SAM_KNOCK_REPORT_IND_V01
,07-27 09:08:06.590  1029  1054 D sensors_hal_KnockOnProx: processInd: handle 70, count=1
07-27 09:08:06.590  1029  1054 I sensors_hal_KnockOnProx: processInd : knock-on state changed - NEAR
07-27 09:08:06.591  1029  1083 D sensors_hal_Ctx: poll:polldata:1, sensor:70, type:499898103, x:0.000000 y:-0.000007 z:0.000000
07-27 09:08:06.592  1029  1083 D sensors_hal_Ctx: poll: count: 36
07-27 09:08:06.592  1029  1083 D sensors_hal_Util: waitForResponse: timeout=0
,07-27 09:08:06.593  1029  1115 D KnockOnPowerController: proximity onSensorChanged : proximity = 0,
07-27 09:08:06.593  1029  1115 I KnockOnPowerController: current mode = 0  value = 1 0
07-27 09:08:06.595  1029  1115 I KnockOnPowerController: [setLPWGmode2] current mode = 0  value = 9 0 0 0 0
,07-27 09:08:06.833  1029  1054 I sensors_hal_KnockOnProx: processInd : knock-on state changed - FAR
,07-27 09:08:06.846  1029  1115 D KnockOnPowerController: proximity onSensorChanged : proximity = 1
,07-27 09:08:06.847  1029  1115 I KnockOnPowerController: current mode = 1  value = 1 1
07-27 09:08:06.849  1029  1115 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,07-27 09:08:08.333   495   511 I Sensors : sns_pwr.c(301):releasing wakelock
,07-27 09:08:08.684  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724473452] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:08.687  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724473455] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:08.687  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:11.713  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724476481] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:11.716  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724476484] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:11.716  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:14.742  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724479510] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:14.745  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724479513] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:14.746  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:17.770  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724482538] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:17.788  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:18] from screen [on:0 period:724482556] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:17.789  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:20.807  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724485575] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:20.810  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724485578] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:20.811  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:23.833  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724488601] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:23.836  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724488604] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:23.836  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:26.862  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724491630] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:26.865  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724491633] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:26.865  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:29.894  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724494662] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:29.897  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724494665] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:29.897  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:32.923  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724497691] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:32.926  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724497694] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:32.926  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:35.950  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724500718] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:35.960  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724500728] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:35.960  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:08:38.980  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724503748] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:38.992  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724503760] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:38.992  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:42.014  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724506781] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:42.017  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724506785] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:42.017  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:45.040  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724509808] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:45.050  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724509818] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:45.051  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:48.072  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724512840] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:48.075  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724512843] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:48.075  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:08:51.099  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724515867] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:51.108  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724515876] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:51.109  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:08:54.130  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724518898] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:54.142  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724518910] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:54.142  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:08:57.162  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724521929] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:08:57.165  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724521933] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:08:57.165  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:00.057  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:09:00.057  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:09:00.058  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:09:00.058  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:09:00.073  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:09:00.073  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:09:00.079  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:09:00.087  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:09:00.189  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724524957] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:00.200  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724524968] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:00.200  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:09:03.220  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724527988] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:03.232  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724528000] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:03.232  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:04.339  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 09:09:04.366  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{851163 type 2 when 1003602 com.android.bluetooth} when 1003602
,07-27 09:09:04.373  6056  6149 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 09:09:04.373  6056  6149 W bt-smp  : Plain text(LSB ~ MSB) = a1 64 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 09:09:04.373  6056  6149 W bt-smp  : Encrypted text(LSB ~ MSB) = 52 95 e4 c9 2c 2f d2 1e 67 ae 2f f8 b7 56 59 c8 
07-27 09:09:04.374  6056  6149 W bt-btm  : Stopping oneshot timer
07-27 09:09:04.426  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:09:04.457  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 09:09:06.252  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724531019] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:06.255  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724531023] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:06.255  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:09.281  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724534048] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:09.290  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724534058] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:09.291  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:09:12.311  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724537078] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:12.322  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724537090] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:12.323  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:15.343  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724540111] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:09:15.346  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724540114] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:15.347  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:18.369  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724543137] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:18.377  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:724543145] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:18.378  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:21.397  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724546165] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:09:21.400  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724546168] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:21.400  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:24.423  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724549191] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:24.426  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724549194] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:09:24.426  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:27.452  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724552219] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:27.455  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724552223] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:09:27.455  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:30.479  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724555247] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:30.490  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724555257] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:30.490  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:33.514  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724558282] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:33.517  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724558285] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:09:33.517  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:36.542  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724561310] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:36.545  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724561313] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:36.545  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:38.358  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1986c160 type 2 when 1007093 com.google.android.gms} when 1007093
,07-27 09:09:38.426  2238  6424 D GCM     : Message class com.google.e.a.a.h
,07-27 09:09:39.570  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724564338] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:39.582  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724564349] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:39.582  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:09:42.604  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724567371] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:42.607  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724567374] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:09:42.607  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:45.635  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724570403] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:45.638  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724570406] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:09:45.638  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:48.663  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724573431] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:48.666  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724573434] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:09:48.666  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:51.693  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724576461] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:51.696  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724576464] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:51.696  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:54.722  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724579489] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:54.725  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724579493] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:54.725  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:09:57.752  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724582519] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:57.755  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724582523] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:09:57.756  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:00.064  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:10:00.064  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:10:00.064  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:10:00.065  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:10:00.078  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:10:00.078  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:10:00.080  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:10:00.083  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:10:00.776  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724585544] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:00.779  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724585547] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:00.779  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:03.800  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724588568] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:03.810  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724588577] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:03.810  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:10:06.829  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724591597] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:06.842  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724591609] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:06.842  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:08.439  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 09:10:08.459  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d8bc619 type 2 when 1067702 com.google.android.gms} when 1067702
,07-27 09:10:08.523  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:10:08.551  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 09:10:08.567  2238  2238 I ConfigService: onCreate
,07-27 09:10:08.573  1838  1838 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-27 09:10:08.574  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 09:10:08.578  1838  7167 I ConfigFetchService: running network task: configservice_periodic
07-27 09:10:08.580  1838  7167 I ConfigFetchService: launchTask
,07-27 09:10:08.588  2238  2238 I ConfigService: onBind returning update interface
07-27 09:10:08.590  1838  1838 I ConfigFetchService: service connected
07-27 09:10:08.590  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 09:10:08.590  2238  2238 I ConfigService: onBind returning config service
07-27 09:10:08.592  1838  1838 I ConfigClient: service connected
,07-27 09:10:09.863  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724594631] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:09.866  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724594634] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:09.867  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:12.893  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724597661] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:12.896  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724597664] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:12.896  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:15.920  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724600688] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:15.931  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724600698] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:15.931  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:10:18.660  1029  2087 V SIM_STK : Menu title from STK is T-Mobile
,07-27 09:10:18.677  1838  6427 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-27 09:10:18.685   310  7169 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-27 09:10:18.685   310  7169 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-27 09:10:18.726   310  7169 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-27 09:10:18.949  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:724603717] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:10:18.951  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:724603719] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:10:18.951  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:19.026  1838  6427 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-27 09:10:19.034  1838  1838 I ConfigFetchService: fetch service done; releasing wakelock
07-27 09:10:19.038  1838  1838 I ConfigFetchService: stopping self
07-27 09:10:19.081  2238  2238 I ConfigService: onDestroy
,07-27 09:10:21.963  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724606730] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 09:10:21.966  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724606734] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 09:10:21.966  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:24.989  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724609757] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:24.999  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724609767] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:24.999  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:10:28.019  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724612787] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:28.031  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724612799] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:28.032  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:10:31.054  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724615822] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:31.057  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724615825] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:31.057  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:34.085  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724618853] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:10:34.088  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724618856] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:34.089  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:37.113  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:724621881] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:10:37.117  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724621884] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:10:37.117  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:40.139  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724624907] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:40.149  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724624916] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:40.149  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:43.168  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724627936] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:43.180  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724627939] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:43.180  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:10:46.201  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724630969] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:46.213  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724630980] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:46.213  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:10:49.233  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724634001] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:49.236  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724634004] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:10:49.237  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:52.262  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724637030] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:52.265  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724637033] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:52.265  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:10:55.289  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724640057] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:55.298  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724640066] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:55.298  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:10:58.318  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724643085] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:10:58.321  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724643088] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:10:58.321  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:00.052  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:11:00.053  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:11:00.053  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:11:00.053  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:11:00.067  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:11:00.067  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:11:00.069  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:11:00.073  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:11:01.350  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724646117] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:01.360  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724646128] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:01.361  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:11:04.379  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724649147] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:04.389  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724649157] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:04.390  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:11:07.411  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724652179] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:07.423  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724652190] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:07.423  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:11:10.445  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724655213] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:10.448  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724655216] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:10.448  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:13.474  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724658242] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:13.477  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724658245] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:13.477  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:16.503  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724661271] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:16.506  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724661274] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:16.507  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:19.534  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724664302] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:19.537  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724664305] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:19.537  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:22.562  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724667329] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:22.565  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724667333] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:22.565  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:25.593  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724670361] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:25.594  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:724670362] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:25.594  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:28.614  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724673381] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:28.616  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724673384] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:28.617  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:31.639  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724676407] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:31.649  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724676417] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:31.650  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:11:34.669  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724679437] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:34.681  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724679448] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:34.681  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:11:37.700  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724682468] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:37.713  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724682480] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:37.713  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:11:40.730  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:724685498] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:40.734  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724685502] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:40.734  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:11:43.752  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:724688520] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:43.755  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724688523] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:43.756  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:46.776  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724691543] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:46.779  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724691546] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:46.779  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:49.799  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724694567] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:49.808  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:724694575] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:49.808  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:11:52.829  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724697597] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:52.841  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724697608] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:52.841  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:55.863  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724700630] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:11:55.866  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724700633] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:55.866  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:11:58.888  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724703656] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:58.896  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724703659] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:11:58.897  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:00.054  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:12:00.054  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:12:00.055  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:12:00.055  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:12:00.069  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:12:00.069  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:12:00.074  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:12:00.080  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:12:01.919  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724706686] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:01.933  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:724706700] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:01.933  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:12:04.953  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724709721] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:04.956  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724709724] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:04.957  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:07.985  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724712752] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:07.995  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724712763] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:07.996  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:11.018  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724715785] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:11.021  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724715788] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:11.021  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:14.041  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724718809] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:14.044  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724718812] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:14.045  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:17.069  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724721836] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:17.079  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724721846] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:17.079  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:12:20.100  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724724867] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:20.111  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724724879] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:20.112  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:23.132  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724727900] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:23.135  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724727903] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:23.135  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:26.161  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724730928] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:26.171  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724730938] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:26.171  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:12:29.193  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724733961] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:29.196  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724733964] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:29.196  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:32.222  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724736990] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:32.226  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724736993] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:32.226  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:35.251  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724740019] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:35.261  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724740029] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:35.261  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:38.282  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724743050] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:38.285  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724743053] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:38.285  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:40.819  1029  1085 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:12:41.313  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724746081] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:41.316  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724746084] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:41.316  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:44.339  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724749106] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:44.348  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724749116] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:44.348  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:12:47.369  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724752137] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:47.382  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724752149] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:47.382  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:50.402  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724755170] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:50.405  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724755173] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:50.405  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:53.432  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724758200] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:53.436  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724758203] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:53.436  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:56.462  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724761230] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:56.466  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724761233] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:12:56.466  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:12:59.491  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724764258] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:59.500  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724764268] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:12:59.500  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:13:00.059  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:13:00.060  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:13:00.060  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:13:00.060  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:13:00.074  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:13:00.074  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:13:00.080  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:13:00.087  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:13:02.517  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724767285] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:02.521  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724767288] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:02.521  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:05.546  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724770314] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:05.549  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724770317] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:05.549  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:08.575  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724773342] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,07-27 09:13:08.578  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724773346] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:08.578  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:11.597  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724776365] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:11.601  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724776368] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:11.601  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:14.628  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724779396] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:14.637  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724779405] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:14.638  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:17.658  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724782426] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:17.670  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724782438] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:17.672  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:13:20.690  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724785458] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:20.703  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:724785471] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,07-27 09:13:20.704  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:13:23.725  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724788492] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:23.728  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724788496] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:23.728  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:26.749  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724791517] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:26.760  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724791527] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:26.760  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:13:29.780  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724794548] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:29.792  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724794559] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:29.792  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:13:32.814  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724797582] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:32.817  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724797585] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:32.817  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:35.842  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724800610] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:35.845  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724800613] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:35.846  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:38.871  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724803638] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:38.880  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724803648] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:38.881  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:13:41.902  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724806669] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:41.905  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724806673] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:41.905  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:44.930  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724809698] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:44.940  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:724809707] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:44.940  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:13:47.960  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724812728] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:47.973  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724812740] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:47.973  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:13:51.003  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3011] from screen [on:0 period:724815770] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:51.014  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724815782] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:51.014  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:54.029  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724818797] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:54.042  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:724818810] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:13:54.042  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:13:57.063  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724821831] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:57.066  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724821834] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:13:57.066  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:00.092  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:14:00.092  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:14:00.092  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:14:00.093  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:14:00.107  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:14:00.107  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:14:00.109  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:14:00.111  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:14:00.113  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3023] from screen [on:0 period:724824881] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:00.114  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:724824882] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:00.114  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:03.132  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724827900] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:03.136  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724827903] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:03.136  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:06.163  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724830931] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:06.166  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724830934] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:06.166  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:09.192  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724833959] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:09.195  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724833963] gl rssi=-49 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:09.195  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:12.220  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724836988] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:12.231  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724836998] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:12.231  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:14:15.253  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724840021] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:15.256  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724840024] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:15.256  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:18.282  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724843050] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:18.285  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724843053] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:18.286  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:21.310  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724846078] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:21.321  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:724846089] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:21.322  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:14:24.343  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724849111] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:24.346  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724849114] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:24.346  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:27.367  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724852135] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:27.370  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724852138] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:27.370  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:30.395  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724855162] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:30.398  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724855166] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:30.398  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:33.423  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724858191] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:33.427  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724858194] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:33.427  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:36.453  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724861221] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:36.456  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724861224] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:36.456  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:39.481  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724864248] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:39.491  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724864258] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:39.491  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:14:42.512  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724867280] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:42.515  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724867283] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:42.516  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:45.540  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:724870307] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:45.549  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:724870317] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:45.549  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:14:48.569  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724873337] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:48.582  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:724873349] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:48.582  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:14:51.603  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724876371] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:51.607  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724876374] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:51.607  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:54.634  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724879401] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:54.637  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724879405] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:54.637  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:14:57.662  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724882430] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:14:57.665  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724882433] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:14:57.665  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:00.053  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:15:00.054  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:15:00.054  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 09:15:00.054  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:15:00.067  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:15:00.067  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:15:00.069  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:15:00.073  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:15:00.687  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:724885455] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:00.688  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:724885456] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:00.688  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:01.749  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 09:15:01.772  6665  6665 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-27 09:15:01.782  6665  6665 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@25c208e
07-27 09:15:01.839  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:15:01.866  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 09:15:03.708  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724888475] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:03.711  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724888478] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:03.711  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:06.738  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724891505] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:06.741  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724891509] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:06.741  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:06.958  1029  1115 D KnockOnPowerController: LPWG WAKEUP isScreenOn = false, TimeAfterSleep = 1324306
,07-27 09:15:06.965  1599  1599 D KeyguardModel: mReceiver, received action: com.lge.android.intent.action.ACTION_KNOCK_ON, sendingUserId:-1
07-27 09:15:06.965  1599  1599 D KeyguardModel: LGIntent.ACTION_KNOCK_ON
07-27 09:15:06.967  1970  2145 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-27 09:15:06.969  1029  1115 I PowerManagerService: Waking up from sleep (uid 1000)...
07-27 09:15:06.970  1029  1115 D KnockOnPowerController: [updateScreenState] screen on = true
07-27 09:15:06.970  1029  1115 D KnockOnPowerController: disable proximity sensor
07-27 09:15:06.970  1029  1029 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@dfd4290)
07-27 09:15:06.970  1029  1115 I SensorManager: removeAllSensors() [Sensor: LGE Knock-on Proximity Sensor] bycom.android.server.power.ProximitySensorListener.disable():117
07-27 09:15:06.970  1029  1029 V SmartCoverServiceDelegate: onScreenTurnedOn()
07-27 09:15:06.970  1029  1115 I sensors_hal_Ctx: activate: handle is 70, disable
07-27 09:15:06.970  1029  1115 V sensors_hal_Ctx: activate sensors is 0
07-27 09:15:06.970  1029  1115 D sensors_hal_KnockOnProx: enable: handle=70
07-27 09:15:06.970  1029  1115 D sensors_hal_KnockOnProx: enable: Disabling sensor handle=70
07-27 09:15:06.970  1029  1115 I sensors_hal_SAM: sendCancel:sensor() Sending cancel to svc no:33
07-27 09:15:06.971  1553  1569 D SmartCoverViewMediator: onScreenTurnedOn, seq = 0
07-27 09:15:06.971  1553  1569 D SmartCoverViewMediator: notifyScreenOnLocked
07-27 09:15:06.971  1553  1553 D SmartCoverViewMediator: handleNotifyScreenOn
07-27 09:15:06.971  1553  1553 I QuickCircle: onScreenTurnedOn
07-27 09:15:06.973  1029  1115 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,07-27 09:15:06.976  1029  1054 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 0, txn Id 69
07-27 09:15:06.976  1029  1054 D sensors_hal_KnockOnProx: processResp: Received SNS_SAM_KNOCK_DISABLE/CANCEL_RESP_V01
07-27 09:15:06.980  1029  1385 E WifiStateMachine:  ConnectedState CMD_SCREEN_STATE_CHANGED 1 0
07-27 09:15:06.980  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_SCREEN_STATE_CHANGED 1 0
07-27 09:15:06.980  1029  1385 E WifiStateMachine:  ConnectModeState CMD_SCREEN_STATE_CHANGED 1 0
07-27 09:15:06.981  1029  1385 E WifiStateMachine:  DriverStartedState CMD_SCREEN_STATE_CHANGED 1 0
07-27 09:15:06.982  1029  1029 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
07-27 09:15:06.982  1553  1553 D QuickCircleViewManager: applyCoverState:0
07-27 09:15:06.982  1599  1618 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
07-27 09:15:06.982  1599  1618 D KeyguardViewMediator: notifyScreenOnLocked
07-27 09:15:06.982  1599  1599 D KeyguardViewMediator: handleNotifyScreenOn
07-27 09:15:06.982  1599  1599 D KeyguardViewBase: screen on, instance 30b033d0
07-27 09:15:06.983  1599  1599 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-27 09:15:06.983  1599  1599 D KeyguardSecurityView: showSecurityScreen(None)
07-27 09:15:06.983  1599  1599 D quilt lockscreen LightParticleRenderer: resume()
07-27 09:15:06.983  1599  1599 D quilt lockscreen LightParticleRenderer: initRenderer()
07-27 09:15:06.983   315  1397 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 1029
07-27 09:15:06.983   315  1397 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-27 09:15:06.983   315  1397 V voice   : voice_set_parameters: enter: screen_state=on
07-27 09:15:06.983   315  1397 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-27 09:15:06.983   315  1397 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 09:15:06.983   315  1397 V voice   : voice_set_parameters: exit with code(0)
07-27 09:15:06.983   315  1397 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-27 09:15:06.983   315  1397 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-27 09:15:06.983   315  1397 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 09:15:06.983   315  1397 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 09:15:06.983   315  1397 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-27 09:15:06.984   315  1397 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 09:15:06.984   315  1397 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-27 09:15:06.985  1029  1385 E WifiStateMachine:  SupplicantStartedState CMD_SCREEN_STATE_CHANGED 1 0
07-27 09:15:06.985  1029  1385 E WifiStateMachine:  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
07-27 09:15:06.986  1029  1385 E WifiStateMachine:  ConnectedState !what:132097 0 0
07-27 09:15:06.986  1029  1385 E WifiStateMachine:  L2ConnectedState !what:132097 0 0
07-27 09:15:06.986  1029  1385 E WifiStateMachine:  ConnectModeState !what:132097 0 0
07-27 09:15:06.987  1029  1385 E WifiStateMachine:  DriverStartedState !what:132097 0 0
07-27 09:15:06.987  1029  1385 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
,07-27 09:15:06.992  1970  2145 V LEDService: startInternal : pkg=KnockOn, recordId=0 : LGLedRecord{2d29299 flags=2 patternId=2 color=0 priority=2 recordId=0 pkg=KnockOn mExceptional=false mNativeNotification=false whichLedPlay=1 patternFilePath=null}
07-27 09:15:06.992  1970  2145 D qdlights: set_light_notifications: 3,0,0,0,3
07-27 09:15:06.992  1970  2145 D qdlights: [pattern_id] = 0
07-27 09:15:06.994  1029  1385 E WifiStateMachine:  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-27 09:15:06.994  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-27 09:15:06.994  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:15:06.994  1029  1115 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=10000 (1356273 ms ago)
07-27 09:15:06.994  1029  1115 D KnockOnPowerController: disable proximity sensor
07-27 09:15:06.995  1599  1599 D LgeKeyguardWallpaperContainer: queryReferenceOfBackground isPortrait : true ,queryObject : com.lge.lockscreen.widget.draglayer.EffectBridgeImpl@57378d7
07-27 09:15:06.995  1599  1599 D KeyguardModel: cache file exits
07-27 09:15:06.995  1599  1599 D ScreenTurnOffBySensor: registerProximitySensor
07-27 09:15:06.995  1599  1599 I SensorManager: registerListenerImpl() [Sensor: LGE Knock-on Proximity Sensor, Rate: 200000, SensorEventListener: com.lge.lockscreen.model.ScreenTurnOffBySensor@5c71054] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.registerProximitySensor():54
07-27 09:15:06.996  1029  2046 I sensors_hal_Ctx: batch: handle:70 flags:0x0 period_ns 200000000, timeout 0
07-27 09:15:06.996  1029  2046 D sensors_hal_SAM: batch:sensor() handle:70 flags:0x0 period_ns:200000000 timeout:0
07-27 09:15:06.996  1029  2046 D sensors_hal_SAM: batch:sensor() handle:70 freq:1 report_rate:1 max:1.000000 min:1.000000
07-27 09:15:06.996  1029  2046 I sensors_hal_Ctx: activate: handle is 70, enable
07-27 09:15:06.997  1029  1050 D sensors_hal_Time: time_service_sensor1_cb: msg_type 1
07-27 09:15:06.997  1029  1050 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 2, txn Id 1
07-27 09:15:06.997  1029  2046 D sensors_hal_Util: waitForResponse: timeout=1000
07-27 09:15:06.997  1029  1050 D sensors_hal_Time: tsOffsetIs: Apps: 1366275468389; DSPS: 44911555; Offset : -4330005321
07-27 09:15:06.997  1029  2046 V sensors_hal_Ctx: activate sensors is 0
07-27 09:15:06.997  1029  2046 D sensors_hal_KnockOnProx: enable: handle=70
07-27 09:15:06.997  1029  2046 I sensors_hal_SAM: sendEnableReq:sensor() Sending enable to svc no:33
07-27 09:15:06.997  1029  2046 D sensors_hal_Util: waitForResponse: timeout=1000
07-27 09:15:06.997  1029  1115 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-27 09:15:06.998  1970  2145 I LEDService: getCurrentHighestLGLedRecord : size = 2
07-27 09:15:06.998  1970  2145 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:15:06.998  1029  1115 I SensorManager: registerListenerImpl() [Sensor: Motion Accel, Rate: 66667, SensorEventListener: com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1a4e52c3] bycom.android.internal.policy.impl.WindowOrientationListener.enable():147
07-27 09:15:06.999  1970  2145 I LEDService: updateLightsLocked : turn on led
07-27 09:15:06.999  1029  1054 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 2, txn Id 0
07-27 09:15:06.999  1029  1054 D sensors_hal_KnockOnProx: processResp: Received SNS_SAM_KNOCK_ENABLE_RESP_V01
07-27 09:15:06.999  1029  2046 D sensors_hal_KnockOnProx: enable: Received response: 0
07-27 09:15:06.999  1599  1599 I SensorManager: registerListenerImpl() [Sensor: LGE Light, Rate: 200000, SensorEventListener: com.lge.lockscreen.model.ScreenTurnOffBySensor@5c71054] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.registerProximitySensor():55
07-27 09:15:07.000  1029  1045 I sensors_hal_Ctx: batch: handle:1 flags:0x0 period_ns 200000000, timeout 0
07-27 09:15:07.000  1029  1045 D sensors_hal_SMGR: batch:sensor(android.sen,sor.light) handle:1 flags:0x0 period_ns 200000000
07-27 09:15:07.000  1029  1045 D sensors_hal_SMGR: batch:sensor(android.sensor.light) sample_rate=20Hz report_rate_f=0.000000Hz curr sample rate:20 cur rpt rate:0 max:20.000000 min:1.000000
07-27 09:15:07.000  1029  1045 D sensors_hal_SMGR: batch: current sample rate, report rate & buffering are equal to requested (0.000000,0.000000,0)
07-27 09:15:07.000  1029  1045 I sensors_hal_Ctx: activate: handle is 1, enable
07-27 09:15:07.000  1029  1045 V sensors_hal_Ctx: activate sensors is 2
07-27 09:15:07.000  1029  1045 D sensors_hal_SMGR: enable:sensor(android.sensor.light) handle 1, freq=20 report_rate=0 batched=0
07-27 09:15:07.000  1029  1045 I sensors_hal_SMGR: SMGRReportAdd:sensor(android.sensor.light) handle=1, sample_rate=20 report_rate=0 buffer=0
07-27 09:15:07.000  1029  1045 D sensors_hal_SMGR: SMGRPrepareAddMsg:sensor android.sensor.light 
07-27 09:15:07.000  1029  1045 D sensors_hal_Util: waitForResponse: timeout=1000
07-27 09:15:07.001  1970  2145 I LEDService: getCurrentHighestLGLedRecord() start. size = 2
,07-27 09:15:07.003  1970  7200 D qdlights: set_light_notifications: 2,ff00ffff,500,0,1
07-27 09:15:07.003  1970  7200 D qdlights: [Current] = 255, R = 0, G = 255, B = 255
07-27 09:15:07.006  1599  3116 D quilt lockscreen LockScreenRenderer: onSurfaceCreated()
07-27 09:15:07.007  1029  1385 E WifiStateMachine:  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-27 09:15:07.007  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-27 09:15:07.007  1029  1385 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
07-27 09:15:07.008  1029  1385 E WifiStateMachine:  ConnectedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-27 09:15:07.008  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-27 09:15:07.008  1029  1385 E WifiStateMachine:  ConnectModeState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-27 09:15:07.008  1029  1385 E WifiStateMachine:  DriverStartedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-27 09:15:07.008  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-27 09:15:07.010  1029  1051 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 1, Sn 0, msg Id 33, txn Id 1
07-27 09:15:07.011  1029  1051 D sensors_hal_SMGR: processResp: 33
07-27 09:15:07.011  1029  1051 I sensors_hal_SMGR: processBufferingResp: Id: 1 Resp: 1 txn id 1
07-27 09:15:07.011  1029  1045 D sensors_hal_SMGR: SMGRReportAdd: Received Response: 0
07-27 09:15:07.011  1029  1115 I sensors_hal_Ctx: batch: handle:46 flags:0x0 period_ns 66667000, timeout 0
07-27 09:15:07.011  1029  1115 D sensors_hal_SAM: batch:sensor(com.qti.sensor.motion_accel) handle:46 flags:0x0 period_ns:66667000 timeout:0
07-27 09:15:07.011  1029  1115 D sensors_hal_SAM: batch:sensor(com.qti.sensor.motion_accel) handle:46 freq:1 report_rate:1 max:1.000000 min:0.000000
07-27 09:15:07.011  1029  1115 I sensors_hal_Ctx: activate: handle is 46, enable
07-27 09:15:07.011  1029  1115 V sensors_hal_Ctx: activate sensors is 400000000002
07-27 09:15:07.011  1029  1115 D sensors_hal_LP2: enable: handle=46
07-27 09:15:07.011  1029  1115 I sensors_hal_SAM: sendEnableReq:sensor(com.qti.sensor.motion_accel) Sending enable to svc no:49
07-27 09:15:07.011  1599  1599 V KeyguardStatusView: Enable transport text marquee
07-27 09:15:07.012   495   917 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
07-27 09:15:07.012  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:15:07.012  1029  2329 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-27 09:15:07.012   495   917 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req f54afd3e
,07-27 09:15:07.014  1029  1080 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 2, txn Id 0
07-27 09:15:07.014  1029  1080 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_ENABLE_RESP_V01
07-27 09:15:07.014  1029  1115 D sensors_hal_Util: waitForResponse: timeout=1000
07-27 09:15:07.014  1029  1115 D sensors_hal_LP2: enable: Received response: 0
07-27 09:15:07.014  1029  1115 D KnockOnPowerController: sendResult : 1
07-27 09:15:07.015  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
07-27 09:15:07.016  1029  1571 I QCOM PowerHAL: Got set_interactive hint
07-27 09:15:07.017  1029  1085 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-27 09:15:07.017   280   280 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6082000
07-27 09:15:07.017   280   280 D qdhwcomposer: hwc_blank: Unblanking display: 0
07-27 09:15:07.022   346   369 E GBMv2   : Set value is all cleared set the max
07-27 09:15:07.023   346   369 I GBMv2   : VFP is [12]
07-27 09:15:07.024  1599  3116 D lockscreen_weather: lock_settings_weather_animation = 1
,07-27 09:15:07.030  1599  3116 D lockscreen_weather: R.bool.weather_service_default_auto_update = true
07-27 09:15:07.030  1599  3116 D lockscreen_weather: weather RefreshPeriod = 3
07-27 09:15:07.030  1599  3116 D lockscreen_weather: com.lge.sizechangable.weather_preferences = true
07-27 09:15:07.030  1599  3116 D lockscreen_weather: getCurrentWeather returns, { city=null weatherText=null weatherCode=0 temperature=null weatherIconResID=-1 }
07-27 09:15:07.030  1599  3116 D quilt lockscreen LockScreenRenderer: onSurfaceChanged() : width = 1440, height = 2560
07-27 09:15:07.030  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-27 09:15:07.031  1029  1385 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-27 09:15:07.031  1029  1385 E WifiStateMachine:  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-27 09:15:07.034  1029  1106 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-27 09:15:07.032  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-27 09:15:07.035  1029  1385 E WifiStateMachine:  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
07-27 09:15:07.035  1029  1385 D WifiNative-wlan0: doBoolean: BLACKLIST clear
07-27 09:15:07.035  1029  1029 V ActivityManager: Display changed displayId=0
07-27 09:15:07.035  1029  1385 D WifiNative-wlan0: BLACKLIST clear: returned true
,07-27 09:15:07.046  1873  1873 D DSDPConnection: Display #0 changed.
07-27 09:15:07.050  1599  3116 W Adreno-ES20: <__load_uniform_float:825>: GL_INVALID_OPERATION
,07-27 09:15:07.070  1873  1873 D PhoneInterfaceManager: [PhoneIntfMgr] mSigLevel = 3
,07-27 09:15:07.074   312   504 E QMI_FW  : [LGE_VSS_QCCI][AP] Enter qcci_qmi_lge_vss_send_cmd().....
07-27 09:15:07.074   312   504 E QMI_FW  : [LGE_VSS_QCCI][AP] Common sendind MSG = 0x60a
07-27 09:15:07.075  1873  1873 V TelephonyAutoProfiling: [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
07-27 09:15:07.078   312   504 E QMI_FW  : [LGE_VSS_QCCI][AP] Enter qcci_qmi_lge_vss_send_cmd().....
07-27 09:15:07.078   312   504 E QMI_FW  : [LGE_VSS_QCCI][AP] Common sendind MSG = 0x60a
07-27 09:15:07.079   495  1021 I Sensors : sns_pwr.c(273):acquiring wakelock
07-27 09:15:07.079  1029  1054 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 33, msg Id 5, txn Id 0
07-27 09:15:07.079  1029  1054 D sensors_hal_KnockOnProx: processInd: SNS_SAM_KNOCK_REPORT_IND_V01
07-27 09:15:07.079  1029  1054 D sensors_hal_KnockOnProx: processInd: handle 70, count=1
07-27 09:15:07.079  1029  1054 I sensors_hal_KnockOnProx: processInd : knock-on state changed - FAR
07-27 09:15:07.079  1029  1083 D sensors_hal_Ctx: poll:polldata:1, sensor:70, type:499898103, x:5.000000 y:-0.000007 z:0.000000
07-27 09:15:07.079  1029  1083 D sensors_hal_Ctx: poll: count: 36
07-27 09:15:07.079  1029  1083 D sensors_hal_Util: waitForResponse: timeout=0
,07-27 09:15:07.112  1873  1873 D PhoneInterfaceManager: [PhoneIntfMgr] handleMessage : 2
,07-27 09:15:07.122  1873  1873 D PhoneInterfaceManager: [PhoneIntfMgr] handleMessage : 3
07-27 09:15:07.130  1599  1599 I [SystemUI]StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 8 0 -98 -80 -120 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0 level=3
07-27 09:15:07.130  1599  1599 D TelephonyIcons: updateDataType sub=0, type=0, inetCondition=1 showAtLeast3G=false show4GforLte=true hspaDistinguishable=false
07-27 09:15:07.130  1599  1599 D TelephonyIcons: data type item name: array/telephony_data_type_sim1
07-27 09:15:07.130  1599  1599 D TelephonyIcons: data type item id: 2131623942
07-27 09:15:07.130  1970  2145 I LEDService: getCurrentHighestLGLedRecord() start. size = 2
07-27 09:15:07.130  1599  1599 D TelephonyIcons: updateDataType mSelectedDataTypeIcon[0]=0, mSelectedDataActivityIndex=0
07-27 09:15:07.130  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 09:15:07.132  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:07.134  1970  1970 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
07-27 09:15:07.134  1970  1970 D Cliptray Service: lockStatus = 1
07-27 09:15:07.135  1029  1029 D Ulp_jni : JNI:system_update. Event-0
07-27 09:15:07.142  1949  1949 D LNfcService: action : android.intent.action.SCREEN_ON
,07-27 09:15:07.144  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 09:15:07.144  1599  1599 D KeyguardViewMediator: handleKeyguardDoneDrawing
07-27 09:15:07.146  1873  1873 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
07-27 09:15:07.147   280   792 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
07-27 09:15:07.147  1949  7221 D NfcServiceNXP: mScreenState : 2
07-27 09:15:07.167  1029  1115 I DisplayPowerController: Unblocked screen on after 172 ms
07-27 09:15:07.168  1029  1115 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-27 09:15:07.169  1599  1599 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
,07-27 09:15:07.186  1949  2744 E NxpNfcJni: getReconnectState = 0x0
,07-27 09:15:07.191  1599  1599 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-27 09:15:07.217   280   280 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-27 09:15:07.218  1029  1571 D SurfaceControl: Excessive delay in setPowerMode(): 200ms
07-27 09:15:07.221  1949  7221 D LNfcService: isRequireNfcCRouting() return true
07-27 09:15:07.221  1949  7221 D LNfcService: isHCERoutingtoHost() return true
07-27 09:15:07.221  1949  7221 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: 0
07-27 09:15:07.221  1949  7221 D NfcService: mEnableLPD: true
07-27 09:15:07.221  1949  7221 D NfcService: mEnableReader: false
07-27 09:15:07.221  1949  7221 D NfcService: mEnableHostRouting: true
07-27 09:15:07.221  1949  7221 D NfcService: newParams.techmask= mTechMask: 0
07-27 09:15:07.221  1949  7221 D NfcService: mEnableLPD: true
07-27 09:15:07.221  1949  7221 D NfcService: mEnableReader: false
07-27 09:15:07.221  1949  7221 D NfcService: mEnableHostRouting: true
07-27 09:15:07.221  1949  7221 D NfcService: screenState= 2
07-27 09:15:07.221  1949  7221 D NfcService: Discovery configuration equal, not updating.
07-27 09:15:07.236  2747  2747 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]ACTION_SCREEN_ON !!!
,07-27 09:15:07.241  4733  4733 D AppCleanupService: android.intent.action.SCREEN_ON
07-27 09:15:07.244  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:15:07.244  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:15:07.245  1029  1029 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
07-27 09:15:07.373  1029  1051 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
07-27 09:15:07.374  1029  1051 D sensors_hal_SMGR: processBufferingInd: Samples_len=1 Items=1 max_reports_per_index=1
07-27 09:15:07.374  1029  1051 V sensors_hal_SMGR: processReportInd: St: 0 ReportId: 1 Rate: 0, Len: 1
07-27 09:15:07.374  1029  1051 V sensors_hal_SMGR: processReportInd: Id: PROX_LIGHT_DATA: Ty: 1 Q: 0
07-27 09:15:07.374  1029  1051 V sensors_hal_Light: processReportInd:sensor android.sensor.light 
,07-27 09:15:07.374  1029  1051 V sensors_hal_Light: processReportInd: 130000 19.000000
,07-27 09:15:07.374  1029  1051 D sensors_hal_SMGR: processReportInd: handle:1 SMGR TS:44923686 HAL TS:1366632091846 elapsedRealtimeNano:1366639027714
07-27 09:15:07.374  1029  1083 D sensors_hal_Ctx: poll:polldata:1, sensor:1, type:5, x:19.000000 y:0.000000 z:0.000000
07-27 09:15:07.374  1029  1083 D sensors_hal_Ctx: poll: count: 36
07-27 09:15:07.374  1029  1083 D sensors_hal_Util: waitForResponse: timeout=0
07-27 09:15:07.385  1029  1080 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
07-27 09:15:07.385  1029  1080 D sensors_hal_LP2: processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
07-27 09:15:07.385  1029  1080 D sensors_hal_LP2: processInd: Samples_len=1 Items=1 max_reports_per_index=1
07-27 09:15:07.385  1029  1080 V sensors_hal_LP2: processInd: X: -0.181519 Y: 0.483276 Z: 9.734512 
07-27 09:15:07.385  1029  1083 D sensors_hal_Ctx: poll:polldata:1, sensor:46, type:499898101, x:-0.181519 y:0.483276 z:9.734512
,07-27 09:15:07.385  1029  1083 D sensors_hal_Ctx: poll: count: 36
,07-27 09:15:07.385  1029  1083 D sensors_hal_Util: waitForResponse: timeout=0
07-27 09:15:07.435  1029  1080 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
07-27 09:15:07.435  1029  1080 D sensors_hal_LP2: processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
07-27 09:15:07.435  1029  1080 D sensors_hal_LP2: processInd: Samples_len=1 Items=1 max_reports_per_index=1
07-27 09:15:07.435  1029  1080 V sensors_hal_LP2: processInd: X: -0.177048 Y: 0.483917 Z: 9.719147 
,07-27 09:15:07.435  1029  1083 D sensors_hal_Ctx: poll:polldata:1, sensor:46, type:499898101, x:-0.177048 y:0.483917 z:9.719147
07-27 09:15:07.435  1029  1083 D sensors_hal_Ctx: poll: count: 36
07-27 09:15:07.435  1029  1083 D sensors_hal_Util: waitForResponse: timeout=0
07-27 09:15:07.510  1970  7200 D qdlights: set_light_notifications: 2,f700f7f7,10,0,1
07-27 09:15:07.510  1970  7200 D qdlights: [Current] = 247, R = 0, G = 247, B = 247
,07-27 09:15:07.521  1970  7200 D qdlights: set_light_notifications: 2,ef00efef,10,0,1
,07-27 09:15:07.521  1970  7200 D qdlights: [Current] = 239, R = 0, G = 239, B = 239
07-27 09:15:07.533  1970  7200 D qdlights: set_light_notifications: 2,e700e7e7,10,0,1
07-27 09:15:07.533  1970  7200 D qdlights: [Current] = 231, R = 0, G = 231, B = 231
,07-27 09:15:07.544  1970  7200 D qdlights: set_light_notifications: 2,df00dfdf,10,0,1
07-27 09:15:07.544  1970  7200 D qdlights: [Current] = 223, R = 0, G = 223, B = 223
07-27 09:15:07.556  1970  7200 D qdlights: set_light_notifications: 2,d700d7d7,10,0,1
07-27 09:15:07.556  1970  7200 D qdlights: [Current] = 215, R = 0, G = 215, B = 215
,07-27 09:15:07.568  1970  7200 D qdlights: set_light_notifications: 2,cf00cfcf,10,0,1
,07-27 09:15:07.568  1970  7200 D qdlights: [Current] = 207, R = 0, G = 207, B = 207
,07-27 09:15:07.580  1970  7200 D qdlights: set_light_notifications: 2,c700c7c7,10,0,1
07-27 09:15:07.580  1970  7200 D qdlights: [Current] = 199, R = 0, G = 199, B = 199
,07-27 09:15:07.591  1970  7200 D qdlights: set_light_notifications: 2,bf00bfbf,10,0,1
07-27 09:15:07.591  1970  7200 D qdlights: [Current] = 191, R = 0, G = 191, B = 191
,07-27 09:15:07.603  1970  7200 D qdlights: set_light_notifications: 2,b700b7b7,10,0,1
,07-27 09:15:07.603  1970  7200 D qdlights: [Current] = 183, R = 0, G = 183, B = 183
,07-27 09:15:07.614  1970  7200 D qdlights: set_light_notifications: 2,af00afaf,10,0,1
,07-27 09:15:07.614  1970  7200 D qdlights: [Current] = 175, R = 0, G = 175, B = 175
,07-27 09:15:07.626  1970  7200 D qdlights: set_light_notifications: 2,a200a2a2,10,0,1
,07-27 09:15:07.626  1970  7200 D qdlights: [Current] = 162, R = 0, G = 162, B = 162
07-27 09:15:07.637  1970  7200 D qdlights: set_light_notifications: 2,97009797,10,0,1
07-27 09:15:07.637  1970  7200 D qdlights: [Current] = 151, R = 0, G = 151, B = 151
,07-27 09:15:07.648  1970  7200 D qdlights: set_light_notifications: 2,8c008c8c,10,0,1
07-27 09:15:07.648  1970  7200 D qdlights: [Current] = 140, R = 0, G = 140, B = 140
,07-27 09:15:07.660  1970  7200 D qdlights: set_light_notifications: 2,81008181,10,0,1
,07-27 09:15:07.660  1970  7200 D qdlights: [Current] = 129, R = 0, G = 129, B = 129
07-27 09:15:07.671  1970  7200 D qdlights: set_light_notifications: 2,76007676,10,0,1
,07-27 09:15:07.671  1970  7200 D qdlights: [Current] = 118, R = 0, G = 118, B = 118
,07-27 09:15:07.682  1970  7200 D qdlights: set_light_notifications: 2,6b006b6b,10,0,1
07-27 09:15:07.682  1970  7200 D qdlights: [Current] = 107, R = 0, G = 107, B = 107
,07-27 09:15:07.694  1970  7200 D qdlights: set_light_notifications: 2,60006060,10,0,1
,07-27 09:15:07.694  1970  7200 D qdlights: [Current] = 96, R = 0, G = 96, B = 96
,07-27 09:15:07.706  1970  7200 D qdlights: set_light_notifications: 2,55005555,10,0,1
,07-27 09:15:07.706  1970  7200 D qdlights: [Current] = 85, R = 0, G = 85, B = 85
,07-27 09:15:07.717  1970  7200 D qdlights: set_light_notifications: 2,4a004a4a,10,0,1
,07-27 09:15:07.717  1970  7200 D qdlights: [Current] = 74, R = 0, G = 74, B = 74
,07-27 09:15:07.728  1970  7200 D qdlights: set_light_notifications: 2,3f003f3f,10,0,1
,07-27 09:15:07.728  1970  7200 D qdlights: [Current] = 63, R = 0, G = 63, B = 63
,07-27 09:15:07.740  1970  7200 D qdlights: set_light_notifications: 2,35003636,10,0,1
07-27 09:15:07.740  1970  7200 D qdlights: [Current] = 53, R = 0, G = 54, B = 54
,07-27 09:15:07.751  1970  7200 D qdlights: set_light_notifications: 2,30003131,10,0,1
07-27 09:15:07.751  1970  7200 D qdlights: [Current] = 48, R = 0, G = 49, B = 49
,07-27 09:15:07.763  1970  7200 D qdlights: set_light_notifications: 2,2b002c2c,10,0,1
07-27 09:15:07.763  1970  7200 D qdlights: [Current] = 43, R = 0, G = 44, B = 44
,07-27 09:15:07.774  1970  7200 D qdlights: set_light_notifications: 2,26002727,10,0,1
07-27 09:15:07.774  1970  7200 D qdlights: [Current] = 38, R = 0, G = 39, B = 39
,07-27 09:15:07.786  1970  7200 D qdlights: set_light_notifications: 2,21002222,10,0,1
07-27 09:15:07.786  1970  7200 D qdlights: [Current] = 33, R = 0, G = 34, B = 34
,07-27 09:15:07.798  1970  7200 D qdlights: set_light_notifications: 2,1c001d1d,10,0,1
,07-27 09:15:07.798  1970  7200 D qdlights: [Current] = 28, R = 0, G = 29, B = 29
,07-27 09:15:07.810  1970  7200 D qdlights: set_light_notifications: 2,17001818,10,0,1
07-27 09:15:07.810  1970  7200 D qdlights: [Current] = 23, R = 0, G = 24, B = 24
,07-27 09:15:07.822  1970  7200 D qdlights: set_light_notifications: 2,12001313,10,0,1
,07-27 09:15:07.822  1970  7200 D qdlights: [Current] = 18, R = 0, G = 19, B = 19
07-27 09:15:07.833  1970  7200 D qdlights: set_light_notifications: 2,d000e0e,10,0,1
07-27 09:15:07.833  1970  7200 D qdlights: [Current] = 13, R = 0, G = 14, B = 14
,07-27 09:15:07.845  1970  7200 D qdlights: set_light_notifications: 2,8000909,10,0,1
07-27 09:15:07.845  1970  7200 D qdlights: [Current] = 8, R = 0, G = 9, B = 9
,07-27 09:15:07.858  1970  2145 D LEDHandler: handleMessage() repeat = false, whichLed = 1
07-27 09:15:07.859  1970  2145 D qdlights: set_light_notifications: 0,0,0,0,1
,07-27 09:15:07.860  1970  2145 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-27 09:15:07.860  1970  2145 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:15:07.861  1970  2145 I LEDService: updateLightsLocked : turn off led
07-27 09:15:07.861  1970  2145 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:15:07.982  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:08.134   495   917 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
,07-27 09:15:08.456  1029  1375 D InputDispatcher: notifyMotion - action=ACTION_DOWN, eventTime=1367734614000, downTime=1367734614000
,07-27 09:15:08.457  1029  1374 D InputTransport: channel '2d09dc60 StatusBar (server)' : action=ACTION_DOWN, downTime=1367734614000, eventTime=1367734614000, pointerCount=1
,07-27 09:15:08.457  1599  1599 I ViewRootImpl: ViewRoot's Touch Event : ACTION_DOWN
07-27 09:15:08.458  1029  1374 D InputTransport: channel 'WindowManager (server)' : action=ACTION_DOWN, downTime=1367734614000, eventTime=1367734614000, pointerCount=1
07-27 09:15:08.462  1029  1967 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=10000 (1357741 ms ago)
07-27 09:15:08.464  1599  1599 D LockDragLayerEffect: ACTION_DOWN - mActivePointerId:  0 (819.43097, 2175.1504)
07-27 09:15:08.466  1599  3116 V SoundPool: play sampleID=1, leftVolume=1.000000, rightVolume=1.000000, priority=0, loop=0, rate=1.000000
07-27 09:15:08.466  1599  3116 V SoundPool: mState = 0 mChannelID=0, mNumChannels=1, mPos = 0, mPriority=-1, mLoop=0
07-27 09:15:08.466  1599  3116 V SoundPool: Allocated active channel
07-27 09:15:08.466  1599  3116 V SoundPool: play channel 0x99ab5ac8 state = 0
07-27 09:15:08.466  1599  3116 V SoundPool: SoundChannel::play 0x99ab5ac8: sampleID=1, channelID=1, leftVolume=1.000000, rightVolume=1.000000, priority=0, loop=0, rate=1.000000
07-27 09:15:08.466   315   315 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10020
07-27 09:15:08.466   315  1396 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 3, flags 0
07-27 09:15:08.467   315  1396 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 09:15:08.467   315  1396 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 09:15:08.467  1599  3116 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 09:15:08.467   315  1397 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 3, flags 0
07-27 09:15:08.467   315  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 09:15:08.467   315  1397 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 09:15:08.467  1599  3116 V AudioTrack: set(): streamType 1, sampleRate 48000, format 0x1, channelMask 0x3, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 0
07-27 09:15:08.467  1599  3116 V AudioTrack: sharedBuffer: 0x9a467000, size: 152872
07-27 09:15:08.467  1599  3116 V AudioTrack: set() streamType 1, sampleRate 48000, format 1, frameCount 0, flags 0004
07-27 09:15:08.467   315   315 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 09:15:08.467   315  1396 V AudioPolicyManager: getOutputForAttr() usage=13, content=4, tag=####$$$$%%%%&&&&''''(((())))****++++,,,,----....////0000111122223333444455556666777788889999::::;;;;<<<<====>>>>????@@@@AAAABBBBCCCCDDDDEEEEHHHHGGGGIIIIFFFFJJJJKKKKMMMMLLLLNNNNOOOOPPPPQQQQRRRRSSSSTTTTUUUUVVVVWWWWXXXXYYYYZZZZ[[[[]]]]^^^^____````bbbbaaaa\\\\ flags=00000000
07-27 09:15:08.467   315  1396 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 3, flags 4
07-27 09:15:08.467   315  1396 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 09:15:08.467   315  1396 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 09:15:08.467  1599  3116 V AudioSystem: getLatency() output 2, latency 50
07-27 09:15:08.467  1599  3116 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 09:15:08.467  1599  3116 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 09:15:08.468   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 09:15:08.468   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 09:15:08.468   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 09:15:08.468   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 09:15:08.468   315  1397 V AudioFlinger: createTrack() lSessionId: 20
07-27 09:15:08.468   315  1397 V AudioFlinger: sharedBuffer: 0xaf300000, size: 152872
07-27 09:15:08.470  1599  3116 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 38218
07-27 09:15:08.470   31,5  1396 V AudioFlinger: acquiring 20 from 1599, for 1599
07-27 09:15:08.470   315  1396 V AudioFlinger:  added new entry for 20
07-27 09:15:08.470  1599  3116 V SoundPool: setVolume 0xaf44c480
07-27 09:15:08.471   315  1397 V AudioFlinger: start(4099), calling pid 1599 session 20
07-27 09:15:08.471   315  1397 V AudioFlinger: ? => ACTIVE (4099) on thread 0xb5497b00
07-27 09:15:08.471   315  1397 V AudioPolicyManagerEx: startOutput() output 2, stream 1, session 20
,07-27 09:15:08.471   315  1397 V AudioPolicyManager: changeRefCount() stream 1, count 1
07-27 09:15:08.471   315  1397 V AudioPolicyManagerEx: getNewOutputDevice() selected device 2
07-27 09:15:08.471   315  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx::setOutputDevice
07-27 09:15:08.471   315  1397 V AudioPolicyManager: setOutputDevice() output 2 device 0002 delayMs 0
,07-27 09:15:08.471   315  1397 V AudioPolicyManager: setOutputDevice() prevDevice 0002
07-27 09:15:08.471   315  1397 V AudioPolicyManager: setOutputDevice() setting same device 0002 or null device for output 2
07-27 09:15:08.471  1599  3116 V SoundPool: delete oldTrack 0x0
07-27 09:15:08.479  1029  2015 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=10000 (1357758 ms ago)
07-27 09:15:08.482   315  1271 D audio_hw_primary: start_output_stream: enter: stream(0xb547f240)usecase(1: low-latency-playback) devices(0x2)
07-27 09:15:08.482   315  1271 V lge_audio_hifi: setup24BitPlayback
07-27 09:15:08.482   315  1271 W lge_audio_hifi: setup24BitPlayback: Format is not 24 bit
,07-27 09:15:08.482   315  1271 E audio_hw_primary: select_devices: enter and usecase(1)
07-27 09:15:08.482   315  1271 V msm8974_platform_lge: LGE_platform_get_output_snd_device: enter(0:2)
07-27 09:15:08.482   315  1271 V msm8974_platform: platform_get_output_snd_device: enter: output devices(0x2)
07-27 09:15:08.482   315  1271 V msm8974_platform: platform_get_output_snd_device: exit: snd_device(speaker)
,07-27 09:15:08.482   315  1271 V msm8974_platform_lge: LGE_platform_get_output_snd_device: exit: out_snd_device(speaker)
07-27 09:15:08.482   315  1271 V audio_hw_lge_primary: LGE_exeption_scenario: enter and out: 2, in: 0
07-27 09:15:08.482   315  1271 V msm8974_platform_lge: LGE_platform_get_output_snd_device: enter(0:2)
07-27 09:15:08.482   315  1271 V msm8974_platform: platform_get_output_snd_device: enter: output devices(0x2)
07-27 09:15:08.482   315  1271 V msm8974_platform: platform_get_output_snd_device: exit: snd_device(speaker)
07-27 09:15:08.482   315  1271 V msm8974_platform_lge: LGE_platform_get_output_snd_device: exit: out_snd_device(speaker)
07-27 09:15:08.482   315  1271 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: )
07-27 09:15:08.482   315  1271 V lge_audio_hifi: platform_check_force_routing: id = 1
07-27 09:15:08.482   315  1271 V lge_audio_hifi: platform_check_force_routing: not offload
07-27 09:15:08.482   315  1271 D lge_audio_hifi: platform_check_force_routing: force route: 0
,07-27 09:15:08.482   315  1271 E audio_hw_primary: enable_snd_device: enter  2
07-27 09:15:08.482   315  1271 D hardware_info: hw_info_append_hw_type : device_name = speaker
07-27 09:15:08.482   315  1271 V audio_hw_fb_prot: audio_extn_spk_fb_protect_enable: Entry
07-27 09:15:08.482   315  1271 V audio_hw_primary: enable_audio_route: enter: usecase(29)
07-27 09:15:08.482   315  1271 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 0
07-27 09:15:08.482   315  1271 V audio_hw_primary: enable_audio_route: apply mixer and update path: fb-protection
07-27 09:15:08.482   315  1271 E audio_route: Path: fb-protection, length: 4
07-27 09:15:08.482   315  1271 E audio_route:   id=0: ctl=IMON ADC Switch
,07-27 09:15:08.482   315  1271 E audio_route:     id=0 value=1
07-27 09:15:08.482   315  1271 E audio_route:   id=1: ctl=VMON ADC Switch
07-27 09:15:08.482   315  1271 E audio_route:     id=0 value=1
07-27 09:15:08.482   315  1271 E audio_route:   id=2: ctl=Monitor Select
07-27 09:15:08.482   315  1271 E audio_route:     id=0 value=1
07-27 09:15:08.482   315  1271 E audio_route:   id=3: ctl=Speaker Protection
07-27 09:15:08.482   315  1271 E audio_route:     id=0 value=1
07-27 09:15:08.485   315  1271 V audio_hw_primary: enable_audio_route: exit
07-27 09:15:08.494   315  1271 V audio_hw_fb_prot: audio_extn_spk_fb_protect_enable: Exit
07-27 09:15:08.494   315  1271 V audio_hw_primary: enable_snd_device: snd_device(2: speaker)
07-27 09:15:08.494   315  1271 V msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(14)
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 14, path =  0
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> send_adm_topology
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> send_asm_topology
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> send_audtable
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
,07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> send_audvoltable
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> send_afe_cal
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AFE_COMMON_TABLE
07-27 09:15:08.494   315  1271 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
07-27 09:15:08.494   315  1271 E audio_route: Path: speaker, length: 10
07-27 09:15:08.494   315  1271 E audio_route:   id=0: ctl=SLIM RX1 MUX
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=1
07-27 09:15:08.494   315  1271 E audio_route:   id=1: ctl=SLIM_0_RX Channels
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=0
,07-27 09:15:08.494   315  1271 E audio_route:   id=2: ctl=RX3 MIX1 INP1
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=5
07-27 09:15:08.494   315  1271 E audio_route:   id=3: ctl=RX3 Digital Volume
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=60
07-27 09:15:08.494   315  1271 E audio_route:   id=4: ctl=RX4 Digital Volume
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=60
07-27 09:15:08.494   315  1271 E audio_route:   id=5: ctl=RDAC5 MUX
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=1
07-27 09:15:08.494   315  1271 E audio_route:   id=6: ctl=LINEOUT1 Volume
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=16
07-27 09:15:08.494   315  1271 E audio_route:   id=7: ctl=LINEOUT3 Volume
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=16
07-27 09:15:08.494   315  1271 E audio_route:   id=8: ctl=RX3 HPF cut off
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=2
07-27 09:15:08.494   315  1271 E audio_route:   id=9: ctl=SPK Amp Volume
07-27 09:15:08.494   315  1271 E audio_route:     id=0 value=3
07-27 09:15:08.499   315  1271 V audio_hw_primary: enable_audio_route: enter: usecase(1),
07-27 09:15:08.499   315  1271 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 2
07-27 09:15:08.499   315  1271 V audio_hw_primary: enable_audio_route: apply mixer and update path: low-latency-playback
07-27 09:15:08.499   315  1271 E audio_route: Path: low-latency-playback, length: 1
07-27 09:15:08.499   315  1271 E audio_route:   id=0: ctl=SLIMBUS_0_RX Audio Mixer MultiMedia5
07-27 09:15:08.500   315  1271 E audio_route:     id=0 value=1
07-27 09:15:08.501   315  1271 V audio_hw_primary: enable_audio_route: exit
07-27 09:15:08.501   315  1271 D audio_hw_primary: select_devices: done
07-27 09:15:08.501   315  1271 V audio_hw_primary: start_output_stream: Opening PCM device card_id(0) device_id(15)
,07-27 09:15:08.516   315  1271 V audio_hw_primary: start_output_stream: exit
07-27 09:15:08.579   495   511 I Sensors : sns_pwr.c(301):releasing wakelock
,07-27 09:15:08.586  1599  1599 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,07-27 09:15:08.586  1599  1599 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:15:08.606  1970  2145 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:15:08.606  1970  2145 D LEDHandler: Battery Level Remaining: 100%
07-27 09:15:08.606  1970  2145 D LEDHandler: Battery Temp: 279, mChargingStatus=5, mChargingStop=false
,07-27 09:15:08.610  1029  1399 D WifiController: battery changed pluggedType: 2
07-27 09:15:08.611  1599  1599 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
07-27 09:15:08.611  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:15:08.614  1599  1599 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:15:08.617  6056  6111 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:15:08.617  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:15:08.617  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:15:08.620  6713  6713 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 09:15:08.700  1029  1375 D InputDispatcher: notifyMotion - action=ACTION_UP, eventTime=1367979044000, downTime=1367734614000
,07-27 09:15:08.700  1029  1374 D InputTransport: channel '2d09dc60 StatusBar (server)' : action=ACTION_UP, downTime=1367734614000, eventTime=1367979044000, pointerCount=1
,07-27 09:15:08.701  1029  1374 D InputTransport: channel 'WindowManager (server)' : action=ACTION_UP, downTime=1367734614000, eventTime=1367979044000, pointerCount=1
07-27 09:15:08.702  1599  1599 I ViewRootImpl: ViewRoot's Touch Event : ACTION_UP
07-27 09:15:08.703  1599  1599 D LockDragLayerEffect: ACTION_UP - pointerId:  0 (826.4261, 1416.4467)
07-27 09:15:08.705  1029  2329 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=10000 (1357983 ms ago)
07-27 09:15:08.705  1599  1599 D LockDragLayerEffect: handleUp()- mActivePointerId:  0
07-27 09:15:08.713  1599  3116 D quilt lockscreen LightParticleRenderer: up() : UNLOCK, drag distance = 758.73596
07-27 09:15:08.714  1599  3116 V SoundPool: play sampleID=2, leftVolume=1.000000, rightVolume=1.000000, priority=0, loop=0, rate=1.000000
07-27 09:15:08.714  1599  3116 V SoundPool: mState = 4 mChannelID=1, mNumChannels=2, mPos = 0, mPriority=0, mLoop=0
07-27 09:15:08.714  1599  3116 V SoundPool: Allocated active channel
07-27 09:15:08.714  1599  3116 V SoundPool: play channel 0x99ab5ac8 state = 4
07-27 09:15:08.714  1599  3116 V SoundPool: SoundChannel::play 0x99ab5ac8: sampleID=2, channelID=2, leftVolume=1.000000, rightVolume=1.000000, priority=0, loop=0, rate=1.000000
07-27 09:15:08.714  1599  3116 V SoundPool: channel 1 stolen - event queued for channel 2
07-27 09:15:08.715  1599  3116 V SoundPool: stop
07-27 09:15:08.715   315   315 V AudioFlinger: stop(4099), calling pid 1599
07-27 09:15:08.715   315   315 V AudioFlinger: not stopping/stopped => stopping/stopped (4099) on thread 0xb56b5000
07-27 09:15:08.715  1599  3116 V SoundPool: done_l(1)
07-27 09:15:08.715  1599  3116 V SoundPool: add to restart list
,07-27 09:15:08.715  1599  3113 V SoundPool: awake
,07-27 09:15:08.715  1599  3113 V SoundPool: Getting channel from list
07-27 09:15:08.715  1599  3113 V SoundPool: Starting stolen channel 1 -> 2
07-27 09:15:08.715  1599  3113 V SoundPool: SoundChannel::play 0x99ab5ac8: sampleID=2, channelID=2, leftVolume=1.000000, rightVolume=1.000000, priority=0, loop=0, rate=1.000000
,07-27 09:15:08.715   315  1396 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 3, flags 0
07-27 09:15:08.715   315  1396 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 09:15:08.715   315  1396 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 09:15:08.715  1599  3113 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 09:15:08.716   315  1397 V AudioPolicyManager: getOutput() device 2, stream 1, samplingRate 0, format 0, channelMask 3, flags 0
07-27 09:15:08.716   315  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 09:15:08.716   315  1397 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 09:15:08.716  1599  3113 V AudioTrack: set(): streamType 1, sampleRate 48000, format 0x1, channelMask 0x3, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 0
07-27 09:15:08.716  1599  3113 V AudioTrack: sharedBuffer: 0x9a367000, size: 231044
07-27 09:15:08.716  1599  3113 V AudioTrack: set() streamType 1, sampleRate 48000, format 1, frameCount 0, flags 0004
07-27 09:15:08.717   315   315 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 09:15:08.717   315  1396 V AudioPolicyManager: getOutputForAttr() usage=13, content=4, tag=�š� flags=00000000
07-27 09:15:08.717   315  1396 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 3, flags 4
07-27 09:15:08.717   315  1396 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 09:15:08.717   315  1396 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 09:15:08.718  1599  3113 V AudioSystem: getLatency() output 2, latency 50
07-27 09:15:08.718  1599  3113 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 09:15:08.718  1599  3113 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 09:15:08.718   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 09:15:08.718   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 09:15:08.718   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 09:15:08.718   315  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 09:15:08.718   315  1397 V AudioFlinger: createTrack() lSessionId: 21
07-27 09:15:08.718   315  1397 V AudioFlinger: sharedBuffer: 0xaf100000, size: 231044
07-27 09:15:08.719  1599  3113 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 57761
07-27 09:15:08.719   315   315 V AudioFlinger: acquiring 21 from 1599, for 1599
07-27 09:15:08.719   315   315 V AudioFlinger:  added new entry for 21
,07-27 09:15:08.719  1599  3113 V SoundPool: setVolume 0x9d7bb200
07-27 09:15:08.719   315  1396 V AudioFlinger: start(4100), calling pid 1599 session 21
07-27 09:15:08.720   315  1396 V AudioFlinger: ? => ACTIVE (4100) on thread 0xb5497800
07-27 09:15:08.720   315  1396 V AudioPolicyManagerEx: startOutput() output 2, stream 1, session 21
07-27 09:15:08.720   315  1396 V AudioPolicyManager: changeRefCount() stream 1, count 2
07-27 09:15:08.720  1599  3113 V SoundPool: delete oldTrack 0xaf44c480
07-27 09:15:08.720  1599  3113 V AudioTrack: ~AudioTrack, releasing session id from 1599 on behalf of 1599
07-27 09:15:08.721   315   315 V AudioFlinger: releasing 20 from 1599 for 1599
,07-27 09:15:08.721   315   315 V AudioFlinger:  decremented refcount to 0
07-27 09:15:08.721   315   315 V AudioFlinger: purging stale effects
07-27 09:15:08.748   315  1390 V AudioFlinger: presentationComplete() mPresentationCompleteFrames 0 framesWritten 6720
07-27 09:15:08.748   315  1390 V AudioFlinger: presentationComplete() reset: mPresentationCompleteFrames 7200 audioHalFrames 480
,07-27 09:15:08.771   315  1390 V AudioFlinger: presentationComplete() mPresentationCompleteFrames 7200 framesWritten 7680
,07-27 09:15:08.791   315  1390 V AudioPolicyService: AudioCommandThread() adding stop output 2
07-27 09:15:08.791   315  1390 V AudioPolicyService: inserting command: 5 at index 0, num commands 0
,07-27 09:15:08.791   315  1390 V AudioPolicyService: AudioCommandThread() adding release output 2
,07-27 09:15:08.791   315  1267 V AudioPolicyService: AudioCommandThread() waking up
,07-27 09:15:08.791   315  1267 V AudioPolicyService: AudioCommandThread() processing stop output 2
07-27 09:15:08.791   315  1390 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 09:15:08.791   315  1390 V AudioFlinger: PlaybackThread::Track destructor
07-27 09:15:08.791   315  1267 V AudioPolicyManagerEx: stopOutput() output 2, stream 1, session 20
,07-27 09:15:08.791   315  1267 V AudioPolicyManager: changeRefCount() stream 1, count 1
07-27 09:15:08.791   315  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 09:15:08.792   315  1267 V AudioPolicyManager: releaseOutput() 2
07-27 09:15:08.792   315  1267 V AudioPolicyService: AudioCommandThread() going to sleep,
07-27 09:15:08.989  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:09.058  1029  2016 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:09.060  1029  2015 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
07-27 09:15:09.251  1599  3116 D quilt lockscreen LockScreenRenderer: onAnimFinished() : UNLOCK
,07-27 09:15:09.255  1599  1599 D LgeKeyguardSwipeView: dismiss() 
07-27 09:15:09.256  1599  1599 D KeyguardSecurityView: showNextSecurityScreenOrFinish(false)
,07-27 09:15:09.256  1599  1599 D KeyguardViewMediator: keyguardDone(true)
07-27 09:15:09.256  1599  1599 D KeyguardViewMediator: handleKeyguardDone
07-27 09:15:09.257  1599  1599 D KeyguardUpdateMonitor: clearFailedUnlockAttempts, user: 0
07-27 09:15:09.257  1599  1599 D KeyguardViewMediator: handleHide
07-27 09:15:09.278  1599  1599 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO BACK HOME RECENT clock SEARCH >
,07-27 09:15:09.295  1599  1599 D KeyguardBackground: updateKeyguardState mState ? 0 ,goingToFullShade ? false ,fromShadeLocked ? false
07-27 09:15:09.297  1599  1599 D KeyguardBackground: Backdrop animation start. dest Alpha : 0 ,duration : 0 ,mKeyguardFadingAway : true
07-27 09:15:09.297  1599  1599 D KeyguardBackground: Backdrop animation end. BackDrop Alpha : 0.0
07-27 09:15:09.298  1599  1599 D LgeKeyguardWallpaperContainer: releaseReferenceOfBackground queriedDrawable : android.graphics.drawable.BitmapDrawable@3af47736 ,referencingObject : com.android.systemui.statusbar.phone.PhoneStatusBar@1d40714a
07-27 09:15:09.298  1599  1599 D LgeKeyguardWallpaperContainer: PortraitDrawableQueryList : com.lge.lockscreen.widget.draglayer.EffectBridgeImpl@57378d7
,07-27 09:15:09.300  1599  1599 D ScreenTurnOffBySensor: unregisterProximitySensor
07-27 09:15:09.301  1599  1599 I SensorManager: removeAllSensors() [Sensor: LGE Light] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.unregisterProximitySensor():63
07-27 09:15:09.301  1029  1987 I sensors_hal_Ctx: activate: handle is 1, disable
07-27 09:15:09.301  1029  1987 V sensors_hal_Ctx: activate sensors is 400000000000
07-27 09:15:09.301  1029  1987 D sensors_hal_SMGR: enable:sensor(android.sensor.light) Deactivating sensor handle=1
07-27 09:15:09.301  1029  1987 I sensors_hal_SMGR: SMGRReportDelete:sensor(android.sensor.light) handle=1
07-27 09:15:09.301  1029  1987 D sensors_hal_Util: waitForResponse: timeout=1000
07-27 09:15:09.304  1029  1051 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 1, Sn 0, msg Id 33, txn Id 1
07-27 09:15:09.304  1029  1051 D sensors_hal_SMGR: processResp: 33
07-27 09:15:09.304  1029  1051 I sensors_hal_SMGR: processBufferingResp: Id: 1 Resp: 0 txn id 1
07-27 09:15:09.305  1029  1987 D sensors_hal_SMGR: SMGRReportDelete: Rcvd success response from request
07-27 09:15:09.305  1599  1599 I SensorManager: removeAllSensors() [Sensor: LGE Knock-on Proximity Sensor] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.unregisterProximitySensor():63
,07-27 09:15:09.309  1029  1045 I sensors_hal_Ctx: activate: handle is 70, disable
07-27 09:15:09.309  1029  1045 V sensors_hal_Ctx: activate sensors is 400000000000
07-27 09:15:09.309  1029  1045 D sensors_hal_KnockOnProx: enable: handle=70
07-27 09:15:09.309  1029  1045 D sensors_hal_KnockOnProx: enable: Disabling sensor handle=70
07-27 09:15:09.309  1029  1045 I sensors_hal_SAM: sendCancel:sensor() Sending cancel to svc no:33
07-27 09:15:09.313  1029  1054 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 0, txn Id 69
07-27 09:15:09.313  1599  1599 V LockDragLayerEffect: reset() : resets state to STATE_RESET_LOCK
07-27 09:15:09.313  1029  1054 D sensors_hal_KnockOnProx: processResp: Received SNS_SAM_KNOCK_DISABLE/CANCEL_RESP_V01
07-27 09:15:09.313  1599  1599 D quilt lockscreen LightParticleRenderer: pause()
07-27 09:15:09.313  1599  1599 D quilt lockscreen LightParticleRenderer: initRenderer()
07-27 09:15:09.364  1599  1599 D LockDragLayerEffect: cleanUp!
07-27 09:15:09.364  1599  1599 V SoundPool: SoundPool destructor
,07-27 09:15:09.365  1599  3113 V SoundPool: awake
07-27 09:15:09.365  1599  3113 V SoundPool: goodbye
07-27 09:15:09.366  1599  1599 V SoundPool: return from quit
07-27 09:15:09.366  1599  1599 V SoundPool: SoundChannel destructor 0x99ab5ac8
07-27 09:15:09.366  1599  1599 V SoundPool: stop
07-27 09:15:09.367   315   315 V AudioFlinger: stop(4100), calling pid 1599
07-27 09:15:09.367   315   315 V AudioFlinger: not stopping/stopped => stopping/stopped (4100) on thread 0xb56b5000
07-27 09:15:09.374  1599  1599 V AudioTrack: ~AudioTrack, releasing session id from 1599 on behalf of 1599
07-27 09:15:09.374   315  1397 V AudioFlinger: releasing 21 from 1599 for 1599
07-27 09:15:09.374   315  1397 V AudioFlinger:  decremented refcount to 0
07-27 09:15:09.374   315  1397 V AudioFlinger: purging stale effects
07-27 09:15:09.374  1599  1599 V SoundPool: clear samples
07-27 09:15:09.374  1599  1599 V SoundPool: Sample::destructor sampleID=1, fd=-1
07-27 09:15:09.375  1599  1599 V SoundPool: Sample::destructor sampleID=2, fd=-1
07-27 09:15:09.382  1599  1599 D LgeKeyguardWallpaperContainer: releaseReferenceOfBackground queriedDrawable : android.graphics.drawable.BitmapDrawable@3af47736 ,referencingObject : com.lge.lockscreen.widget.draglayer.EffectBridgeImpl@57378d7
07-27 09:15:09.382  1599  1599 D LgeKeyguardWallpaperContainer: PortraitDrawableQueryList is empty.
07-27 09:15:09.382  1599  1599 D quilt lockscreen LightParticleRenderer: pause()
,07-27 09:15:09.391  1599  1599 D KeyguardSimpleHostView: onDetachedFromWindow()
07-27 09:15:09.391  1599  1599 V KeyguardDisplayManager: hide
07-27 09:15:09.393  1599  1599 D StatusBarKeyguardViewManager: LockScreen status : 0 (Lock released)
07-27 09:15:09.394  1599  1599 D StatusBarKeyguardViewManager: KnockCode status : 0
,07-27 09:15:09.396  1599  1599 D StatusBarKeyguardViewManager: adjustCameraSliderVisibility: shouldVisible = false, mGlanceViewNow = false
07-27 09:15:09.396  1599  1599 D KeyguardUpdateMonitor: sendKeyguardVisibilityChanged(false)
07-27 09:15:09.410  1029  1029 V ActivityManager: Display changed displayId=0
07-27 09:15:09.411   315  1390 V AudioFlinger: presentationComplete() mPresentationCompleteFrames 0 framesWritten 38400
07-27 09:15:09.411   315  1390 V AudioFlinger: presentationComplete() reset: mPresentationCompleteFrames 38880 audioHalFrames 480
,07-27 09:15:09.414  1873  1873 D DSDPConnection: Display #0 changed.
07-27 09:15:09.431   315  1390 V AudioFlinger: presentationComplete() mPresentationCompleteFrames 38880 framesWritten 39360
,07-27 09:15:09.438  1599  1599 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=false mOccluded=false isSecure=false --> flags=0x0 --> lgNaviBtnFlag=0x0
07-27 09:15:09.440  1029  2087 I SystemUI[Framework]: ==>disabled() what=0x0, token=android.os.BinderProxy@1662d740,  pkg=com.android.systemui
07-27 09:15:09.440  1029  2087 I SystemUI[Framework]: StatusBar disabled: mDisabled=0x600000,  mDisableRecords.size=1
,07-27 09:15:09.440  1029  2087 I SystemUI[Framework]: StatusBar disabled: [0] userId=0, what=0x600000, pkg=WindowManager.LayoutParams, token=android.os.Binder@3a6a45a
07-27 09:15:09.440  5765  5765 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-27 09:15:09.440  5765  5765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-27 09:15:09.440  1029  1708 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=com.android.systemui
07-27 09:15:09.440  1029  1708 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.BinderProxy@1662d740,  pkg=com.android.systemui
07-27 09:15:09.440  1029  1708 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-27 09:15:09.440  5765  5765 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-27 09:15:09.440  5765  5765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-27 09:15:09.440  1970  1986 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-27 09:15:09.441  1970  1986 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17a9395e co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 09:15:09.444   315  1390 V AudioPolicyService: AudioCommandThread() adding stop output 2
07-27 09:15:09.444   315  1390 V AudioPolicyService: inserting command: 5 at index 0, num commands 0
07-27 09:15:09.444   315  1390 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 09:15:09.444   315  1390 V AudioPolicyService: inserting command: 6 at index 1, num commands 1
07-27 09:15:09.444   315  1390 V AudioFlinger: PlaybackThread::Track destructor
07-27 09:15:09.444   315  1390 V AudioFlinger: removeClient_l() pid 1599, calling pid 315
07-27 09:15:09.445   315  1267 V AudioPolicyService: AudioCommandThread() waking up
07-27 09:15:09.445   315  1267 V AudioPolicyService: AudioCommandThread() processing stop output 2
07-27 09:15:09.445   315  1267 V AudioPolicyManagerEx: stopOutput() output 2, stream 1, session 21
07-27 09:15:09.445   315  1267 V AudioPolicyManager: changeRefCount() stream 1, count 0
07-27 09:15:09.445   315  1267 V AudioPolicyManagerEx: getNewOutputDevice() selected device 0
07-27 09:15:09.445   315  1267 V AudioPolicyManagerEx: AudioPolicyManagerEx::setOutputDevice
07-27 09:15:09.445   315  1267 V AudioPolicyManager: setOutputDevice() output 2 device 0000 delayMs 100
07-27 09:15:09.445   315  1267 V AudioPolicyManager: setOutputDevice() prevDevice 0002
07-27 09:15:09.445   315  1267 V AudioPolicyManager: setOutputDevice() setting same device 0000 or null device for output 2
07-27 09:15:09.445   315  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 09:15:09.445   315  1267 V AudioPolicyManager: releaseOutput() 2
07-27 09:15:09.445   315  1267 V AudioPolicyService: AudioCommandThread() going to sleep
,07-27 09:15:09.449  1970  1970 V SplitWindowPolicy: receive broadcasted action: android.intent.action.USER_PRESENT, isFull? false, isPrevLock? false
07-27 09:15:09.450  1599  1599 D PhoneStatusBar: disable: < expand icons* alerts system_info* BACK HOME RECENT clock SEARCH >
07-27 09:15:09.452  1949  1949 D LNfcService: action : android.intent.action.USER_PRESENT
07-27 09:15:09.452  2747  2747 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]ACTION_USER_PRESENT
07-27 09:15:09.453  2747  4176 D LIA_MrGDBLogger_LoggerThread: [dreamwood]App Usage Logging
07-27 09:15:09.456  1029  1104 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,07-27 09:15:09.457  1029  1104 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
07-27 09:15:09.458  1949  2440 D NfcServiceNXP: mScreenState : 3
07-27 09:15:09.461  5765  5765 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d24f8b5 time:1368739
07-27 09:15:09.462  1029  1104 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-27 09:15:09.462  1029  1104 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-27 09:15:09.462  1029  1104 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 09:15:09.462  1029  1104 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a6a45a,  pkg=WindowManager.LayoutParams
07-27 09:15:09.462  1029  1104 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-27 09:15:09.468  1029  1709 D InputDispatcher: Focus left window: Window{2d09dc60 u0 StatusBar}
07-27 09:15:09.468  1029  1709 D InputDispatcher: Focus entered window: Window{1c7ccfa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:15:09.469  1029  1709 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=30000 (1338747 ms ago)
,07-27 09:15:09.472  1029  1029 I WifiServerServiceExt: ACTION_USER_PRESENT
07-27 09:15:09.473  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RELOAD_TLS_AND_RECONNECT 0 0
07-27 09:15:09.473  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RELOAD_TLS_AND_RECONNECT 0 0
07-27 09:15:09.474  1029  1385 E WifiStateMachine:  ConnectModeState !CMD_RELOAD_TLS_AND_RECONNECT 0 0
07-27 09:15:09.474  2238  2238 V UserPresentBroadcastReceiver: Recieved ACTION_USER_PRESENT.
07-27 09:15:09.479  2238  2238 D d       : Notifying listener(s): onUserPresent()...
07-27 09:15:09.480  1029  1044 D InputMethodManagerService: setImestate : 0
07-27 09:15:09.480  1029  1029 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 09:15:09.480  1029  1029 W PackageManager: Failure retrieving resources for com.google.android.gms: Resource ID #0x0
07-27 09:15:09.480  2238  2238 D c       : Starting periodic check for user presence.
,07-27 09:15:09.487  2238  2238 D c       : Stoping periodic check for user presence.
07-27 09:15:09.496  1949  2744 E NxpNfcJni: getReconnectState = 0x0
,07-27 09:15:09.514  2238  2238 I Coffee - GoogleTrustAgent: GoogleTrustAgent created.
,07-27 09:15:09.522  1599  1599 D PhoneStatusBar: disableNaviBtn: < menu sim_switch* notification* qmemo* qslide* dual_window* >
07-27 09:15:09.524  1029  1105 D BluetoothManagerService: Message: 20
07-27 09:15:09.524  1029  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e042884:true
07-27 09:15:09.529  1949  2440 D LNfcService: isRequireNfcCRouting() return true
07-27 09:15:09.529  1949  2440 D LNfcService: isHCERoutingtoHost() return true
07-27 09:15:09.529  1949  2440 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: 0
07-27 09:15:09.529  1949  2440 D NfcService: mEnableLPD: true
07-27 09:15:09.529  1949  2440 D NfcService: mEnableReader: false
07-27 09:15:09.529  1949  2440 D NfcService: mEnableHostRouting: true
,07-27 09:15:09.530  2238  2238 I Coffee - Trustlet: Trustlet com.google.android.gms.auth.trustagent.trustlet.d enabled state changed to: true
07-27 09:15:09.530  2238  2238 I Coffee - TrustletManager: Trustlet registered com.google.android.gms.auth.trustagent.trustlet.d enabled: true
07-27 09:15:09.531  1949  2440 D NfcService: newParams.techmask= mTechMask: default
07-27 09:15:09.531  1949  2440 D NfcService: mEnableLPD: true
07-27 09:15:09.531  1949  2440 D NfcService: mEnableReader: false
07-27 09:15:09.531  1949  2440 D NfcService: mEnableHostRouting: true
07-27 09:15:09.531  1949  2440 D NfcService: screenState= 3
07-27 09:15:09.539  2238  2238 I Coffee - Trustlet: Trustlet com.google.android.gms.auth.trustagent.trustlet.u enabled state changed to: true
07-27 09:15:09.539  2238  2238 W Coffee - OneTimeAuthTrustlet: Registering broadcast receiver more than once.
07-27 09:15:09.539  2238  2238 I Coffee - TrustletManager: Trustlet registered com.google.android.gms.auth.trustagent.trustlet.u enabled: true
07-27 09:15:09.546  2238  2238 I Coffee - Trustlet: Trustlet com.google.android.gms.auth.trustagent.trustlet.ab enabled state changed to: true
,07-27 09:15:09.548  1599  1599 D PhoneStatusBar: disable: < expand icons alerts system_info back* home* recent* clock search* >
07-27 09:15:09.551  2238  2238 I Coffee - TrustletManager: Trustlet registered com.google.android.gms.auth.trustagent.trustlet.ab enabled: true
07-27 09:15:09.552  1949  2744 E NxpNfcJni: getReconnectState = 0x0
07-27 09:15:09.552  1949  2440 E NxpNfcJni: nfcManager_enableDiscovery:UICC_LISTEN_MASK=0x0199;
07-27 09:15:09.553  2238  2238 I Coffee - Trustlet: Trustlet com.google.android.gms.auth.trustagent.trustlet.f enabled state changed to: true
07-27 09:15:09.553  2238  2238 W Coffee - OneTimeAuthTrustlet: Registering broadcast receiver more than once.
07-27 09:15:09.553  2238  2238 I Coffee - TrustletManager: Trustlet registered com.google.android.gms.auth.trustagent.trustlet.f enabled: true
07-27 09:15:09.553  2238  2238 W Coffee - Trustlet: Trustlet com.google.android.gms.auth.trustagent.trustlet.d enabled state called with same state (true), ignored.
07-27 09:15:09.553  1949  2744 E NxpNfcJni: nfaDeviceManagementCallback: NFA_DM_GET_CONFIG failed
07-27 09:15:09.554  1949  2440 E NxpNfcJni: enableDisableLptd: Config TLV length 0 returned is too short
07-27 09:15:09.554  2238  2238 W Coffee - Trustlet: Trustlet com.google.android.gms.auth.trustagent.trustlet.u enabled state called with same state (true), ignored.
07-27 09:15:09.554  2238  2238 I Coffee - Trustlet: Trustlet com.google.android.gms.auth.trustagent.trustlet.ab enabled state changed to: false
07-27 09:15:09.555  2238  2238 W Coffee - Trustlet: Trustlet com.google.android.gms.auth.trustagent.trustlet.f enabled state called with same state (true), ignored.
07-27 09:15:09.555  2238  2238 I Coffee - GoogleTrustAgent: Providing trust state change: true
07-27 09:15:09.558  1029  2328 D SplitWindow: check instance of lgWin Window{4d0b495 u0 SearchPanel}
,07-27 09:15:09.562  1599  1599 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
07-27 09:15:09.562  1838  1838 I Kids    : [CommonUtils] disabled. skipping.
07-27 09:15:09.562  1599  1599 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
07-27 09:15:09.562  1599  1599 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-27 09:15:09.562  1599  1599 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-27 09:15:09.564  1599  1599 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=608600 newVal=8600 diff=600000
07-27 09:15:09.564  6556  6556 D WeatherAncestor: 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 9:15:9
07-27 09:15:09.565  6556  6556 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 09:15:09.565  6556  6556 D Weather.Utils: 2 : All the weather widget is gone.
07-27 09:15:09.565  6556  6556 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 09:15:09.566  6556  6556 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 9:15:9
07-27 09:15:09.571  2238  2238 D PeriodicCheckReceiver: Received intent: Intent { flg=0x14 cmp=com.google.android.gms/.auth.be.proximity.authorization.userpresence.PeriodicCheckReceiver (has extras) }.
,07-27 09:15:09.579  2238  7261 D UserPresenceService: Received onHandleIntent() with intent: Intent { cmp=com.google.android.gms/.auth.be.proximity.authorization.userpresence.UserPresenceService (has extras) }.
,07-27 09:15:09.581  2238  7261 D d       : Handling user-presence detection with detection type: PERIODIC_CHECK.
07-27 09:15:09.582  2238  7261 D d       : Notifying listener(s): onUserPresent()...
07-27 09:15:09.584  1599  1599 D LGKeyguardUnlockMethodController: onTrustChanged with userId : 0 , getUserTrustIsManaged : true ,getUserHasTrust : false
07-27 09:15:09.620  1599  2478 D NativeBitmapDiskPool: cache wallpaper. cacheKey is bg_portrait
,07-27 09:15:09.718   346   375 E GBMv2   : DFP En is all cleared set to be enabled
,07-27 09:15:09.718   346   375 E GBMv2   : Set value is all cleared set the max
07-27 09:15:09.718   346   375 I GBMv2   : DFP Enabled. Ignore VFP set
,07-27 09:15:09.776  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2995] from screen [on:0 period:724894544] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:09.777  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:724894545] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:09.999  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:10.007  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:230] from screen [on:0 period:724894775] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:10.008  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:724894776] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:10.008  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:15:10.344   334   428 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-27 09:15:11.011  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:11.058  1029  2015 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:11.063   315  1396 V AudioPolicyService: registerClient() client 0xb54efba0, uid 10003
,07-27 09:15:12.424   315  1390 D audio_hw_primary: out_standby: enter: stream (0xb547f240) usecase(1: low-latency-playback)
,07-27 09:15:12.499   315  1390 V audio_hw_primary: stop_output_stream: enter: usecase(1: low-latency-playback)
,07-27 09:15:12.499   315  1390 V audio_hw_primary: out->usecase 1, out->format = 1
07-27 09:15:12.499   315  1390 V audio_hw_primary: disable_audio_route: enter: usecase(1)
07-27 09:15:12.499   315  1390 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 2
07-27 09:15:12.499   315  1390 V audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback
07-27 09:15:12.503   315  1390 V audio_hw_primary: disable_audio_route: exit
07-27 09:15:12.503   315  1390 E audio_hw_primary: disable_snd_device: enter 2
07-27 09:15:12.503   315  1390 D hardware_info: hw_info_append_hw_type : device_name = speaker
07-27 09:15:12.503   315  1390 V audio_hw_primary: disable_snd_device: snd_device(2: speaker)
07-27 09:15:12.503   315  1390 V audio_hw_fb_prot: audio_extn_spk_fb_protect_disable: Entry
,07-27 09:15:12.510   315  1390 V audio_hw_primary: disable_audio_route: enter: usecase(29)
,07-27 09:15:12.510   315  1390 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 0
07-27 09:15:12.510   315  1390 V audio_hw_primary: disable_audio_route: reset and update mixer path: fb-protection
07-27 09:15:12.518   315  1390 V audio_hw_primary: disable_audio_route: exit
07-27 09:15:12.518   315  1390 V audio_hw_fb_prot: audio_extn_spk_fb_protect_disable: Exit
,07-27 09:15:12.525   315  1390 V audio_hw_primary: stop_output_stream: exit: status(0)
07-27 09:15:12.525   315  1390 V lge_audio_dummyloopback: AUX: LGEAux_setDummyLoopback_outStandby: jack_on:0, usb_on:0, standby for usecase : 1
,07-27 09:15:12.525   315  1390 V audio_hw_primary: out_standby: exit
07-27 09:15:13.023  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724897791] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:13.027  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724897794] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:13.027  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:13.060  1029  2016 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:14.349   334   428 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-27 09:15:15.058  1029  1709 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:16.046  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:724900813] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:16.049  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724900817] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:16.049  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:17.058  1029  1989 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:18.353   334   428 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-27 09:15:19.058  1029  2046 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:19.071  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724903838] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:19.074  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724903841] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:19.074  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:20.043  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:21.056  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:21.064  1029  1967 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
07-27 09:15:22.095  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:724906863] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:22.098  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724906866] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:22.098  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:22.357   334   428 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-27 09:15:23.058  1029  1045 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:23.072  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 09:15:24.084  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:25.058  1029  2329 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:25.121  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:724909888] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:25.126  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:724909894] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:25.126  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:15:26.361   334   428 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-27 09:15:26.999  1029  1050 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
,07-27 09:15:26.999  1029  1050 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:15:26.999  1029  1050 D sensors_hal_Time: tsOffsetIs: Apps: 1386276863120; DSPS: 45566960; Offset : -4329981825
,07-27 09:15:27.058  1029  1967 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:27.096  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:28.145  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724912912] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:28.150  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:724912918] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:28.150  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:15:29.058  1029  2087 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:30.115  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 09:15:30.365   334   428 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-27 09:15:31.058  1029  2328 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:31.169  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:724915937] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:31.175  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724915941] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:31.176  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 09:15:32.723  1029  1115 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=30000 (1362001 ms ago)
,07-27 09:15:33.058  1029  1967 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:34.196  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:724918964] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:34.200  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:724918968] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:34.200  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:34.369   334   428 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-27 09:15:35.058  1029  2015 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:37.058  1029  1570 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:37.222  1029  1385 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:724921990] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:37.225  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724921993] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:37.226  1029  1385 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-27 09:15:38.372   334   428 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-27 09:15:38.706  1029  1115 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=30000 (1367985 ms ago)
07-27 09:15:38.707  1029  1115 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-27 09:15:38.707  1029  1115 D KnockOnPowerController: [updateScreenState] screen on = false
07-27 09:15:38.707  1029  1115 D KnockOnPowerController: disable proximity sensor
07-27 09:15:38.707  1029  1115 D KnockOnPowerController: enable proximity sensor
07-27 09:15:38.708  1029  1115 I SensorManager: registerListenerImpl() [Sensor: LGE Knock-on Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2cbf71c3] bycom.android.server.power.ProximitySensorListener.enable():107
,07-27 09:15:38.711  1029  1115 I sensors_hal_Ctx: batch: handle:70 flags:0x0 period_ns 200000000, timeout 0
,07-27 09:15:38.711  1029  1115 D sensors_hal_SAM: batch:sensor() handle:70 flags:0x0 period_ns:200000000 timeout:0
,07-27 09:15:38.712  1029  1115 D sensors_hal_SAM: batch:sensor() handle:70 freq:1 report_rate:1 max:1.000000 min:1.000000
07-27 09:15:38.712  1029  1115 I sensors_hal_Ctx: activate: handle is 70, enable
07-27 09:15:38.712  1029  1115 V sensors_hal_Ctx: activate sensors is 400000000000
07-27 09:15:38.712  1029  1115 D sensors_hal_KnockOnProx: enable: handle=70
07-27 09:15:38.712  1029  1115 I sensors_hal_SAM: sendEnableReq:sensor() Sending enable to svc no:33
,07-27 09:15:38.713  1029  1115 D sensors_hal_Util: waitForResponse: timeout=1000
,07-27 09:15:38.715  1029  1054 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 2, txn Id 0
07-27 09:15:38.715  1029  1054 D sensors_hal_KnockOnProx: processResp: Received SNS_SAM_KNOCK_ENABLE_RESP_V01
07-27 09:15:38.716  1029  1115 D sensors_hal_KnockOnProx: enable: Received response: 0
07-27 09:15:38.717  1029  1115 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
07-27 09:15:38.734  1029  1115 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=30000 (1368013 ms ago)
07-27 09:15:38.736  1029  1029 I SensorManager: removeAllSensors() [Sensor: Motion Accel] bycom.android.internal.policy.impl.WindowOrientationListener.disable():166
07-27 09:15:38.737  1029  1029 I sensors_hal_Ctx: activate: handle is 46, disable
07-27 09:15:38.737  1029  1029 V sensors_hal_Ctx: All sensors stop, stop the time_service.
,07-27 09:15:38.737  1029  1029 D sensors_hal_Time: send stop time_service command
,07-27 09:15:38.743  1029  1029 D sensors_hal_Util: waitForResponse: timeout=1000
,07-27 09:15:38.744  1029  1115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.power.PowerManagerServiceEx$3.run:1231 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,07-27 09:15:38.747  1029  1115 I PowerManagerService: Sleeping (uid 1000)...
07-27 09:15:38.747  1029  1115 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=30000 (1368026 ms ago)
07-27 09:15:38.747  1029  1050 D sensors_hal_Time: time_service_sensor1_cb: msg_type 1
07-27 09:15:38.747  1029  1050 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 0, txn Id 1
07-27 09:15:38.748  1029  1029 V sensors_hal_Ctx: activate sensors is 0
07-27 09:15:38.749  1029  1029 D sensors_hal_LP2: enable: handle=46
07-27 09:15:38.749  1029  1029 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-27 09:15:38.749  1029  1029 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
07-27 09:15:38.753  1553  1615 D SmartCoverViewMediator: onScreenTurnedOff(3)
07-27 09:15:38.753  1553  1615 D SmartCoverViewMediator: notifyScreenOffLocked
07-27 09:15:38.756  5765  5765 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-27 09:15:38.756  5765  5765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-27 09:15:38.760  1970  7220 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
,07-27 09:15:38.760  1970  7220 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1f3c413f co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 09:15:38.762  1599  1616 D KeyguardViewMediator: onScreenTurnedOff(3)
07-27 09:15:38.763  1599  1616 D KeyguardViewMediator: notifyScreenOffLocked
07-27 09:15:38.763  1553  1553 D SmartCoverViewMediator: handleNotifyScreenOFF
07-27 09:15:38.763  1553  1553 I QuickCircle: onScreenTurnedOff
07-27 09:15:38.764  1553  1553 D LgeQuickCoverOverlayWindow: updateVisibility:hideSmartLighting
07-27 09:15:38.764  1553  1553 D LgeQuickCoverOverlayWindow: updateVisibility:hideNotification
07-27 09:15:38.764  1553  1553 D QuickCircleViewManager: applyCoverState:1
07-27 09:15:38.764  1553  1553 D QuickCircleViewManager: getState: 0
07-27 09:15:38.764  1553  1553 D QuickCircleViewManager: applyCoverState:LCD Off -> go to lock
07-27 09:15:38.764  1553  1553 D QuickCircleViewManager: getState: 0
07-27 09:15:38.792  1029  1080 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-27 09:15:38.792  1029  1080 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,07-27 09:15:38.822  5765  5765 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2de444c0 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@342a5a9b, 16908290=android.view.AbsSavedState$1@342a5a9b}, android:focusedViewId=100}]}]
07-27 09:15:38.822  5765  5765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-27 09:15:38.822  5765  5765 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 09:15:38.822  5765  5765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-27 09:15:38.832  1599  1616 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2, timeout = 5000
07-27 09:15:38.834  1599  1599 D KeyguardViewMediator: handleNotifyScreenOff
07-27 09:15:38.834  1599  1599 D ScreenTurnOffBySensor: unregisterProximitySensor
07-27 09:15:38.834  1599  1599 D StatusBarWindowView: onScreenTurnedOff why = 3
,07-27 09:15:38.834  1599  1599 V KeyguardStatusView: Disable transport text marquee
07-27 09:15:38.837  1029  1385 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
07-27 09:15:38.837  1029  1385 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
07-27 09:15:38.838  1029  1385 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
07-27 09:15:38.838   315  1396 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 1029
07-27 09:15:38.838  1029  1385 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-27 09:15:38.839   315  1396 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-27 09:15:38.839   315  1396 V voice   : voice_set_parameters: enter: screen_state=off
07-27 09:15:38.839   315  1396 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-27 09:15:38.839   315  1396 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 09:15:38.839  1029  1385 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-27 09:15:38.839   315  1396 V voice   : voice_set_parameters: exit with code(0)
07-27 09:15:38.839   315  1396 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-27 09:15:38.839   315  1396 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-27 09:15:38.839   315  1396 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 09:15:38.839   315  1396 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 09:15:38.839   315  1396 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 09:15:38.839   315  1396 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-27 09:15:38.839  1029  1385 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
07-27 09:15:38.840  1029  1385 E WifiStateMachine:  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-27 09:15:38.841  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-27 09:15:38.841  1029  1385 E WifiStateMachine:  ConnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-27 09:15:38.842  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-27 09:15:38.842  1029  1385 E WifiStateMachine:  ConnectModeState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-27 09:15:38.842  1029  1385 E WifiStateMachine:  DriverStartedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-27 09:15:38.843  1029  1385 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 09:15:38.846  1029  1399 D WifiController: CMD_SCREEN_OFF 
07-27 09:15:38.846  1029  1399 D WifiController: shouldWifiStayAwake TRUE
07-27 09:15:38.850   495  1021 I Sensors : sns_pwr.c(273):acquiring wakelock
07-27 09:15:38.851  1029  1054 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 33, msg Id 5, txn Id 0
07-27 09:15:38.851  1029  1054 D sensors_hal_KnockOnProx: processInd: SNS_SAM_KNOCK_REPORT_IND_V01
07-27 09:15:38.851  1029  1054 D sensors_hal_KnockOnProx: processInd: handle 70, count=1
07-27 09:15:38.851  1029  1054 I sensors_hal_KnockOnProx: processInd : knock-on state changed - FAR
07-27 09:15:38.851  1029  1083 D sensors_hal_Ctx: poll:polldata:1, sensor:70, type:499898103, x:5.000000 y:-0.000007 z:0.000000
07-27 09:15:38.851  1029  1083 D sensors_hal_Ctx: poll: count: 36
07-27 09:15:38.851  1029  1083 D sensors_hal_Util: waitForResponse: timeout=0
07-27 09:15:38.851  1029  1115 D KnockOnPowerController: proximity onSensorChanged : proximity = 1
07-27 09:15:38.852  1029  1115 I KnockOnPowerController: current mode = 1  value = 1 1
07-27 09:15:38.852  1029  1115 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,07-27 09:15:38.856  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
07-27 09:15:38.868  6080  6080 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 09:15:38.869  1029  1385 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,07-27 09:15:39.058  1029  2087 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-27 09:15:39.220   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
07-27 09:15:39.220   280   280 D qdhwcomposer: hwc_blank: Blanking display: 0
07-27 09:15:39.220  1029  1106 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-27 09:15:39.221  1029  1029 V ActivityManager: Display changed displayId=0
,07-27 09:15:39.232  1873  1873 D DSDPConnection: Display #0 changed.
,07-27 09:15:39.373   334   428 E ThermalEngine: [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 578000000
,07-27 09:15:39.375  1029  1085 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-27 09:15:39.380  1970  2145 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,07-27 09:15:39.380  1970  2145 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:15:39.381  1970  1970 D VolumeVibrator: clear
07-27 09:15:39.382  1970  2145 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-27 09:15:39.382  1970  2145 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 09:15:39.383  1970  2145 I LEDService: updateLightsLocked : turn on led
07-27 09:15:39.383  1970  2145 D qdlights: set_light_notifications: 3,4,0,0,1
07-27 09:15:39.383  1970  2145 D qdlights: [pattern_id] = 4
07-27 09:15:39.384  1970  2145 D LEDHandler: RESTART MSG
07-27 09:15:39.385  1970  1970 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-27 09:15:39.389  1949  1949 D LNfcService: action : android.intent.action.SCREEN_OFF
,07-27 09:15:39.392  1949  2734 D NfcServiceNXP: mScreenState : 1
07-27 09:15:39.395  1873  1873 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
07-27 09:15:39.399  2088  2088 I [LGHome]EVENT: [Launcher.java:1836:onReceive()]Screen Off
07-27 09:15:39.410  2747  2747 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]ACTION_SCREEN_OFF !!!
07-27 09:15:39.410  2747  2747 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]case 9 : com.test.thalitest
,07-27 09:15:39.427  2747  4176 D LIA_MrGDBLogger_LoggerThread: [dreamwood]App Usage Logging
,07-27 09:15:39.428  2747  2747 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]scheduledExecutorService is stopped
07-27 09:15:39.430  1949  2744 E NxpNfcJni: getReconnectState = 0x0
07-27 09:15:39.433  4733  4733 D AppCleanupService: android.intent.action.SCREEN_OFF
07-27 09:15:39.435  4733  7296 D AppCleanupService: AppUsageStatsSaveTask
07-27 09:15:39.437  1990  1990 E LibSecureUISvc: svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
07-27 09:15:39.438  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:15:39.438  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:15:39.438  1029  1029 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
,07-27 09:15:39.463  1949  2734 D LNfcService: isRequireNfcCRouting() return true
07-27 09:15:39.463  1949  2734 D LNfcService: isHCERoutingtoHost() return true
07-27 09:15:39.463  1949  2734 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-27 09:15:39.463  1949  2734 D NfcService: mEnableLPD: true
07-27 09:15:39.463  1949  2734 D NfcService: mEnableReader: false
07-27 09:15:39.463  1949  2734 D NfcService: mEnableHostRouting: true
07-27 09:15:39.463  1949  2734 D NfcService: newParams.techmask= mTechMask: 0
07-27 09:15:39.463  1949  2734 D NfcService: mEnableLPD: true
07-27 09:15:39.463  1949  2734 D NfcService: mEnableReader: false
07-27 09:15:39.463  1949  2734 D NfcService: mEnableHostRouting: true
07-27 09:15:39.463  1949  2734 D NfcService: screenState= 1
07-27 09:15:39.484  1949  2744 E NxpNfcJni: getReconnectState = 0x0
,07-27 09:15:39.485  1949  2734 E NxpNfcJni: nfcManager_enableDiscovery:UICC_LISTEN_MASK=0x0199;
07-27 09:15:39.490   280   792 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-27 09:15:39.490   280   280 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-27 09:15:39.491  1029  1571 D SurfaceControl: Excessive delay in setPowerMode(): 271ms
07-27 09:15:39.491  1029  1571 I QCOM PowerHAL: Got set_interactive hint
07-27 09:15:39.722  1599  1599 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:15:39.723  1599  1599 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:15:39.738  1970  2145 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:15:39.738  1970  2145 D LEDHandler: Battery Level Remaining: 100%
07-27 09:15:39.738  1970  2145 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
,07-27 09:15:39.739  1599  1599 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,07-27 09:15:39.740  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 09:15:39.741  1029  1399 D WifiController: battery changed pluggedType: 2
,07-27 09:15:39.742  1599  1599 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 09:15:39.743  6056  6111 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:15:39.743  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
07-27 09:15:39.744  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:15:39.744  6713  6713 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 09:15:40.244  1029  1385 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:724925012] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 09:15:40.247  1029  1385 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:724925015] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-27 09:15:40.350   495   511 I Sensors : sns_pwr.c(301):releasing wakelock
,07-27 09:15:43.772  1599  1599 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,07-27 09:15:43.784  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3ff24138 type 2 when 1403032 com.android.systemui} when 1403032
,07-27 09:15:43.800  1599  1599 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
07-27 09:15:43.803  1599  1599 D KeyguardViewMediator: doKeyguard: showing the lock screen
07-27 09:15:43.803  1599  1599 D KeyguardViewMediator: showLocked
07-27 09:15:43.806  1599  1599 D KeyguardViewMediator: handleShow
07-27 09:15:43.810  1599  1599 D KnockOffHandler: knockOffView: com.android.keyguard.KeyguardSimpleHostView{1469ee58 V.E..... ......I. 0,0-0,0 #7f0d00d5 app:id/keyguard_host_view}
07-27 09:15:43.810  1599  1599 D KnockOffGestureDetector: doubleTapSlopInMM 10, doubleTapSlop = 212
07-27 09:15:43.810  1599  1599 D KnockOffGestureDetector: LONGPRESS_TIMEOUT = 500
07-27 09:15:43.810  1599  1599 D KnockOffGestureDetector: TAP_TIMEOUT = 180
07-27 09:15:43.810  1599  1599 D KnockOffGestureDetector: DOUBLE_TAP_TIMEOUT = 300
,07-27 09:15:43.818  1599  1599 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-27 09:15:43.818  1599  1599 D KeyguardSecurityView: showSecurityScreen(None)
07-27 09:15:43.819  1599  1599 D KeyguardSecurityView: MDM isLockOutNow: false
07-27 09:15:43.819  1599  1599 D KeyguardModel: MDM enableLockOutNow(false)
07-27 09:15:43.820  1599  1599 V KeyguardSecurityView: inflating id = 2130968659
07-27 09:15:43.827  1599  1599 D KeyguardMessageArea: updateCmasInfofalse
07-27 09:15:43.827  1599  1599 D KeyguardMessageArea: MDM onMdmLockoutModeChanged
,07-27 09:15:43.838  1599  1599 D UpdateKeyguardStatusFactory: Country= EU Carrier= OPEN
07-27 09:15:43.841  1599  1599 D KeyguardMessageArea: updateCmasInfofalse
07-27 09:15:43.841  1599  1599 D KeyguardMessageArea: MDM onMdmLockoutModeChanged
07-27 09:15:43.843  1599  1599 D KeyguardMessageArea: updateCmasInfofalse
07-27 09:15:43.844  1599  1599 D KeyguardMessageArea: MDM onMdmLockoutModeChanged
,07-27 09:15:43.848  1599  1599 D KeyguardMessageArea: updateCmasInfofalse
07-27 09:15:43.849  1599  1599 D KeyguardMessageArea: MDM onMdmLockoutModeChanged
07-27 09:15:43.882  1599  1599 D EmergencyButton: updateEmergencyCallButton(phoneState: 0
07-27 09:15:43.883  1599  1599 D EmergencyButton: MDM updateEmergencyCallButton() - isLockoutMode: false
,07-27 09:15:43.896  1599  1599 D LgeKeyguardSwipeView: LgeKeyguardDragView.hideBouncer.  mIsBouncing: false
,07-27 09:15:43.901  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-27 09:15:43.951  1599  1599 D KeyguardSimpleHostView: onAttachedToWindow()
,07-27 09:15:43.954  1599  1599 D LgeKeyguardSwipeView: onSimStateChangedUsingSubId: ABSENT, subId=-1
07-27 09:15:43.954  1599  1599 D CarrierText: updateCarrierText, simState=ABSENT plmn=Emergency calls only spn=null subId=-1
07-27 09:15:43.954  1599  1599 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:15:43.955  1599  1599 D CarrierText: updateCarrierText, simState=ABSENT plmn=Emergency calls only spn=null subId=-1
07-27 09:15:43.955  1599  1599 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:15:43.956  1599  1599 D KnockOffHandler: knockOffView: android.widget.FrameLayout{1852b056 G.E..... ......ID 52,960-1388,2560 #7f0d01d4 app:id/keyguard_hostview_holder}
07-27 09:15:43.956  1599  1599 D KnockOffGestureDetector: doubleTapSlopInMM 10, doubleTapSlop = 212
07-27 09:15:43.956  1599  1599 D KnockOffGestureDetector: LONGPRESS_TIMEOUT = 500
07-27 09:15:43.956  1599  1599 D KnockOffGestureDetector: TAP_TIMEOUT = 180
07-27 09:15:43.956  1599  1599 D KnockOffGestureDetector: DOUBLE_TAP_TIMEOUT = 300
07-27 09:15:43.957  1599  1599 D StatusBarKeyguardViewManager: adjustCameraSliderVisibility: shouldVisible = false, mGlanceViewNow = false
07-27 09:15:43.957  1599  1599 D KeyguardUpdateMonitor: sendKeyguardVisibilityChanged(true)
07-27 09:15:43.958  1599  1599 V SoundPool: SoundPool constructor: maxChannels=1, attr.usage=13, attr.flags=0x0, attr.tags=
07-27 09:15:43.959  1599  1599 V SoundPool: load: fd=68, offset=0, length=35098, priority=1
07-27 09:15:43.959  1599  1599 V SoundPool: create sampleID=1, fd=81, offset=35098 length=0
07-27 09:15:43.959  1599  1599 V SoundPool: doLoad: loading sample sampleID=1
07-27 09:15:43.959  1599  1599 V SoundPool: load: fd=68, offset=0, length=59341, priority=1
07-27 09:15:43.960  1599  1599 V SoundPool: create sampleID=2, fd=109, offset=59341 length=0
07-27 09:15:43.960  1599  1599 V SoundPool: doLoad: loading sample sampleID=2
07-27 09:15:43.960  1599  1599 D quilt lockscreen LightParticleRenderer: LightParticleRenderer created
07-27 09:15:43.960  1599  1599 E quilt LockScreenSurfaceView: android.view.SurfaceView.setLockScreenFlag() method is not supported.
07-27 09:15:43.961  1599  1599 D LockDragLayerEffect: LCD is off when effect is initailized! Call effect onPause()
07-27 09:15:43.961  1599  1599 D quilt lockscreen LightParticleRenderer: pause()
07-27 09:15:43.961  1599  1599 D quilt lockscreen LightParticleRenderer: initRenderer()
07-27 09:15:43.964  1599  1599 D LgeKeyguardWallpaperContainer: queryReferenceOfBackground isPortrait : true ,queryObject : com.lge.lockscreen.widget.draglayer.EffectBridgeImpl@3d0f49f6
,07-27 09:15:43.970  1599  7307 V SoundPool: Start decode
07-27 09:15:43.970  1599  7307 V MediaPlayer[Native]: decode(81, 0, 35098)
07-27 09:15:43.971   315  1396 V MediaPlayerService: decode(23, 0, 35098)
07-27 09:15:43.971   315  1396 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-27 09:15:43.971   315  1396 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-27 09:15:43.971   315  1396 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-27 09:15:43.971   315  1396 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-27 09:15:43.971   315  1396 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-27 09:15:43.971   315  1396 V MediaPlayerService: player type = 3
07-27 09:15:43.971   315  1396 V AwesomePlayer: AwesomePlayer create()
07-27 09:15:43.972   315  1396 V AwesomePlayer: reset_l() 
07-27 09:15:43.972   315  1396 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:43.972   315  1396 V AwesomePlayer: setAudioSink() 
07-27 09:15:43.972   315  1396 V AwesomePlayer: reset_l() 
07-27 09:15:43.972   315  1396 V AudioCache: notify(0xb04095c0, 8, 0, 0)
07-27 09:15:43.972   315  1396 V AudioCache: ignored
07-27 09:15:43.972   315  1396 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:43.972   315  1396 D Utils   : printFileName fd(24) -> /system/media/audio/ui/light_touchdown.ogg
07-27 09:15:43.972   315  1396 V AwesomePlayer: setDataSource_l dataSource
07-27 09:15:43.972   315  1396 V LGParserOSAL: SniffLGParser start
07-27 09:15:43.972   315  1396 V LGParserOSAL: MainType:5, SubType=0
07-27 09:15:43.972   315  1396 V LGParserOSAL: #### check Mime : application/ogg
07-27 09:15:43.973   315  1396 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-27 09:15:43.973   315  1396 E MediaExtractor: Use LGExtractor :application/ogg 
07-27 09:15:43.981   315  1396 V LGParserOSAL: supported mime: application/ogg
07-27 09:15:43.981   315  1396 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-27 09:15:43.981   315  1396 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 09:15:43.981   315  1396 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 09:15:43.981   315  1396 V AwesomePlayer: AudioTrack Setting
07-27 09:15:43.981   315  1396 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-27 09:15:43.981   315  1396 V AwesomePlayer: setAudioSource() 
07-27 09:15:43.981   315  1396 V MediaPlayerService: prepare
07-27 09:15:43.981   315  1396 V AwesomePlayer: prepareAsync_l() 
07-27 09:15:43.981   315  1396 V MediaPlayerService: wait for prepare
,07-27 09:15:43.993   315  7309 V AwesomePlayer: onPrepareAsyncEvent() 
07-27 09:15:43.993   315  7309 V AwesomePlayer: initAudioDecoder() 
07-27 09:15:43.993   315  7309 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 09:15:43.993   315  7309 V AudioSystem: isOffloadSupported()
07-27 09:15:43.993   315  7309 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=796208 us, has_video=0
07-27 09:15:43.993   315  7309 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 09:15:43.993   315  7309 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 09:15:43.993   315  7309 V AwesomePlayer: getUseOffload() = 0 
07-27 09:15:43.993   315  7309 V OMXCodec: OMXCodec::Create
07-27 09:15:43.993   315  7309 V OMXCodec: findMatchingCodecs()
07-27 09:15:43.993   315  7309 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-27 09:15:43.993   315  7309 V OMXCodec: matchingCodecs.size()=1
07-27 09:15:43.993   315  7309 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-27 09:15:43.996   315  7309 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-27 09:15:43.996   315  7309 V LGCodecAdapter: LG Codec Adapter start
07-27 09:15:43.996   315  7309 V OMXCodec: OMXCodec Createtor
07-27 09:15:43.996   315  7309 V OMXCodec: setComponentRole
07-27 09:15:43.996   315  7309 V OMXCodec: configureCodec protected=0
,07-27 09:15:43.999   315  7309 V LGCodecAdapter: called getLGCodecSpecificData
07-27 09:15:43.999   315  7309 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-27 09:15:43.999   315  7309 V LGCodecOSAL: Called LGconfigureCodecMETA
07-27 09:15:43.999   315  7309 V LGCodecOSAL: Called LGconfigureCodecMSG
07-27 09:15:43.999   315  7309 V LGCodecOSAL: Not support LGCodec
07-27 09:15:43.999   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 09:15:43.999   315  7309 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-27 09:15:43.999   315  7309 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-27 09:15:43.999   315  7309 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 09:15:43.999   315  7309 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 09:15:43.999   315  7309 V AudioSystem: isOffloadSupported()
07-27 09:15:43.999   315  7309 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=796208 us, has_video=0
07-27 09:15:43.999   315  7309 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 09:15:43.999   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-27 09:15:43.999   315  7309 V OMXCodec: init()
07-27 09:15:44.002   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-27 09:15:44.002   315  7309 V OMXCodec: allocateBuffers
07-27 09:15:44.002   315  7309 V OMXCodec: allocateBuffersOnPort portIndex=0
07-27 09:15:44.002   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 09:15:44.002   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
07-27 09:15:44.002   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
07-27 09:15:44.002   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
07-27 09:15:44.003   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
07-27 09:15:44.003   315  7309 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 09:15:44.003   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 09:15:44.003   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 09:15:44.003   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-27 09:15:44.003   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-27 09:15:44.003   315  7309 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be1f0 on output port
07-27 09:15:44.003   315  7309 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 09:15:44.004   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 09:15:44.004   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 09:15:44.005   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-27 09:15:44.005   315  7309 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 09:15:44.005   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-27 09:15:44.005   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-27 09:15:44.005   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-27 09:15:44.005   315  7309 V OMXCodec: init() mAsyncCompletion wait free! 
07-27 09:15:44.005   315  7309 V AwesomePlayer: finishAsyncPrepare_l() 
07-27 09:15:44.005   315  7309 V AudioCache: notify(0xb04095c0, 5, 0, 0)
07-27 09:15:44.005   315  7309 V AudioCache: ignored
07-27 09:15:,44.005   315  7309 V AudioCache: notify(0xb04095c0, 1, 0, 0)
07-27 09:15:44.005   315  7309 V AudioCache: prepared
07-27 09:15:44.005   315  1396 V AudioCache: wait - success
07-27 09:15:44.005   315  1396 V MediaPlayerService: start
07-27 09:15:44.005   315  1396 V AwesomePlayer: play_l() 
07-27 09:15:44.005   315  1396 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-27 09:15:44.005   315  1396 V AwesomePlayer: createAudioPlayer_l
07-27 09:15:44.005   315  1396 V AwesomePlayer: seekAudioIfNecessary_l() 
07-27 09:15:44.005   315  1396 V AwesomePlayer: startAudioPlayer_l() 
07-27 09:15:44.005   315  1396 D AudioPlayer: start of Playback, useOffload 0
07-27 09:15:44.005   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 09:15:44.006   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 09:15:44.008   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-27 09:15:44.008   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-27 09:15:44.008   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,07-27 09:15:44.013   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-27 09:15:44.013   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-27 09:15:44.013   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 09:15:44.013   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
07-27 09:15:44.013   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044794864
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-27 09:15:44.014   315  7311 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 09:15:44.014   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be650 on output port
07-27 09:15:44.016   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-27 09:15:44.016   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-27 09:15:44.017   315  1396 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-27 09:15:44.017   315  1396 V AudioCache: notify(0xb04095c0, 6, 0, 0)
07-27 09:15:44.017   315  1396 V AudioCache: ignored
07-27 09:15:44.018   315  1396 V MediaPlayerService: wait for playback complete
07-27 09:15:44.020   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.020   315  7312 V AudioCache: memcpy(0xaf006000, 0xb1495000, 4096)
07-27 09:15:44.020   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.020   315  7312 V AudioCache: memcpy(0xaf007000, 0xb1495000, 4096)
,07-27 09:15:44.025   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.025   315  7312 V AudioCache: memcpy(0xaf008000, 0xb1495000, 4096)
07-27 09:15:44.027   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.027   315  7312 V AudioCache: memcpy(0xaf009000, 0xb1495000, 4096)
07-27 09:15:44.028   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.028   315  7312 V AudioCache: memcpy(0xaf00a000, 0xb1495000, 4096)
07-27 09:15:44.028   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.028   315  7312 V AudioCache: memcpy(0xaf00b000, 0xb1495000, 4096)
07-27 09:15:44.029   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.029   315  7312 V AudioCache: memcpy(0xaf00c000, 0xb1495000, 4096)
07-27 09:15:44.030   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.031   315  7312 V AudioCache: memcpy(0xaf00d000, 0xb1495000, 4096)
07-27 09:15:44.035   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.035   315  7312 V AudioCache: memcpy(0xaf00e000, 0xb1495000, 4096)
,07-27 09:15:44.038   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.038   315  7312 V AudioCache: memcpy(0xaf00f000, 0xb1495000, 4096)
07-27 09:15:44.040   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.040   315  7312 V AudioCache: memcpy(0xaf010000, 0xb1495000, 4096)
07-27 09:15:44.040   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.040   315  7312 V AudioCache: memcpy(0xaf011000, 0xb1495000, 4096)
07-27 09:15:44.041   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.041   315  7312 V AudioCache: memcpy(0xaf012000, 0xb1495000, 4096)
07-27 09:15:44.042   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.042   315  7312 V AudioCache: memcpy(0xaf013000, 0xb1495000, 4096)
07-27 09:15:44.043   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.043   315  7312 V AudioCache: memcpy(0xaf014000, 0xb1495000, 4096)
07-27 09:15:44.043   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.043   315  7312 V AudioCache: memcpy(0xaf015000, 0xb1495000, 4096)
07-27 09:15:44.044   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.044   315  7312 V AudioCache: memcpy(0xaf016000, 0xb1495000, 4096)
07-27 09:15:44.044   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.044   315  7312 V AudioCache: memcpy(0xaf017000, 0xb1495000, 4096)
07-27 09:15:44.045   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.045   315  7312 V AudioCache: memcpy(0xaf018000, 0xb1495000, 4096)
07-27 09:15:44.046   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.046   315  7312 V AudioCache: memcpy(0xaf019000, 0xb1495000, 4096)
07-27 09:15:44.046   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.046   315  7312 V AudioCache: memcpy(0xaf01a000, 0xb1495000, 4096)
,07-27 09:15:44.049   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.049   315  7312 V AudioCache: memcpy(0xaf01b000, 0xb1495000, 4096)
07-27 09:15:44.050   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.050   315  7312 V AudioCache: memcpy(0xaf01c000, 0xb1495000, 4096)
07-27 09:15:44.051   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.051   315  7312 V AudioCache: memcpy(0xaf01d000, 0xb1495000, 4096)
07-27 09:15:44.052   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.052   315  7312 V AudioCache: memcpy(0xaf01e000, 0xb1495000, 4096)
07-27 09:15:44.052   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.052   315  7312 V AudioCache: memcpy(0xaf01f000, 0xb1495000, 4096)
07-27 09:15:44.053   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.053   315  7312 V AudioCache: memcpy(0xaf020000, 0xb1495000, 4096)
07-27 09:15:44.054   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.054   315  7312 V AudioCache: memcpy(0xaf021000, 0xb1495000, 4096)
07-27 09:15:44.054   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.054   315  7312 V AudioCache: memcpy(0xaf022000, 0xb1495000, 4096)
07-27 09:15:44.055   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.055   315  7312 V AudioCache: memcpy(0xaf023000, 0xb1495000, 4096)
07-27 09:15:44.055   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.056   315  7312 V AudioCache: memcpy(0xaf024000, 0xb1495000, 4096)
07-27 09:15:44.056   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.056   315  7312 V AudioCache: memcpy(0xaf025000, 0xb1495000, 4096)
07-27 09:15:44.057   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.057   315  7312 V AudioCache: memcpy(0xaf026000, 0xb1495000, 4096)
07-27 09:15:44.057   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.057   315  7312 V AudioCache: memcpy(0xaf027000, 0xb1495000, 4096)
,07-27 09:15:44.060   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.060   315  7312 V AudioCache: memcpy(0xaf028000, 0xb1495000, 4096)
07-27 09:15:44.061   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.061   315  7312 V AudioCache: memcpy(0xaf029000, 0xb1495000, 4096)
07-27 09:15:44.062   315  7312 V AudioCache: write(0xb1495000, 4096)
07-27 09:15:44.062   315  7312 V AudioCache: memcpy(0xaf02a000, 0xb1495000, 4096)
07-27 09:15:44.062   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-27 09:15:44.062   315  7312 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,07-27 09:15:44.062   315  7312 V AwesomePlayer: postAudioEOS() 
07-27 09:15:44.062   315  7312 V AudioCache: write(0xb1495000, 1320)
07-27 09:15:44.062   315  7312 V AudioCache: memcpy(0xaf02b000, 0xb1495000, 1320)
07-27 09:15:44.073   315  7309 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-27 09:15:44.073   315  7309 V AwesomePlayer: onStreamDone
07-27 09:15:44.073   315  7309 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 09:15:44.073   315  7309 V AudioCache: notify(0xb04095c0, 2, 0, 0)
07-27 09:15:44.073   315  7309 V AudioCache: playback complete
07-27 09:15:44.073   315  7309 V AwesomePlayer: pause_l() 
07-27 09:15:44.073   315  7309 V AudioCache: notify(0xb04095c0, 7, 0, 0)
07-27 09:15:44.073   315  7309 V AudioCache: ignored
07-27 09:15:44.073   315  7309 V AwesomePlayer: cancelPlayerEvents
,07-27 09:15:44.073   315  1396 V AudioCache: wait - success
07-27 09:15:44.073   315  1396 V MediaPlayerService: return size 152872, sampleRate=48000, channelCount = 2, format = 1
07-27 09:15:44.073   315  7309 D AudioPlayer: Pause Playback at 796208
07-27 09:15:44.074   315  1396 V AwesomePlayer: reset_l() 
07-27 09:15:44.074   315  1396 V AudioCache: notify(0xb04095c0, 8, 0, 0)
07-27 09:15:44.074   315  1396 V AudioCache: ignored
07-27 09:15:44.074   315  1396 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.074   315  1396 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 09:15:44.074   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 09:15:44.074   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-27 09:15:44.074   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-27 09:15:44.074   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
,07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
07-27 09:15:44.074   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57be650 on port 1
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
,07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.075   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-27 09:15:44.076   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 09:15:44.076   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 09:15:44.076   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-27 09:15:44.076   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-27 09:15:44.076   315  7311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-27 09:15:44.076   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 09:15:44.076   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-27 09:15:44.076   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-27 09:15:44.077   315  1396 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-27 09:15:44.077   315  1396 D AudioPlayer: AudioPlayer releasing audio source
07-27 09:15:44.077   315  1396 D AudioPlayer: AudioPlayer done releasing audio source
07-27 09:15:44.077   315  1396 V AwesomePlayer: reset_l() 
07-27 09:15:44.077   315  1396 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.077   315  1396 V AwesomePlayer: ~AwesomePlayer call
07-27 09:15:44.077   315  1396 V AwesomePlayer: reset_l() 
07-27 09:15:44.077   315  1396 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.078  1599  7307 V SoundPool: close(81)
07-27 09:15:44.078  1599  7307 V SoundPool: pointer = 0x97455000, size = 152872, sampleRate = 48000, numChannels = 2
07-27 09:15:44.078  1599  7307 V SoundPool: Start decode
07-27 09:15:44.078  1599  7307 V MediaPlayer[Native]: decode(109, 0, 59341)
07-27 09:15:44.080   315   315 V MediaPlayerService: decode(23, 0, 59341)
07-27 09:15:44.080   315   315 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-27 09:15:44.080   315   315 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-27 09:15:44.080   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-27 09:15:44.080   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-27 09:15:44.080   315   315 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-27 09:15:44.080   315   315 V MediaPlayerService: player type = 3
07-27 09:15:44.080   315   315 V AwesomePlayer: AwesomePlayer create()
07-27 09:15:44.081   315   315 V AwesomePlayer: reset_l() 
07-27 09:15:44.081   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.081   315   315 V AwesomePlayer: setAudioSink() 
07-27 09:15:44.081   315   315 V AwesomePlayer: reset_l() 
07-27 09:15:44.081   315   315 V AudioCache: notify(0xb0409640, 8, 0, 0)
07-27 09:15:44.081   315   315 V AudioCache: ignored
07-27 09:15:44.081   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.081   315   315 D Utils   : printFileName fd(24) -> /system/media/audio/ui/light_unlock.ogg
07-27 09:15:44.081   315   315 V AwesomePlayer: setDataSource_l dataSource
07-27 09:15:44.081   315   315 V LGParserOSAL: SniffLGParser start
07-27 09:15:44.081   315   315 V LGParserOSAL: MainType:5, SubType=0
07-27 09:15:44.081   315   315 V LGParserOSAL: #### check Mime : application/ogg
07-27 09:15:44.081   315   315 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-27 09:15:44.081   315   315 E MediaExtractor: Use LGExtractor :application/ogg 
07-27 09:15:44.124   315   315 V LGParserOSAL: supported mime: application/ogg
07-27 09:15:44.125   315   315 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-27 09:15:44.125   315   315 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 09:,15:44.125   315   315 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 09:15:44.125   315   315 V AwesomePlayer: AudioTrack Setting
07-27 09:15:44.125   315   315 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-27 09:15:44.125   315   315 V AwesomePlayer: setAudioSource() 
07-27 09:15:44.125   315   315 V MediaPlayerService: prepare
07-27 09:15:44.125   315   315 V AwesomePlayer: prepareAsync_l() 
07-27 09:15:44.127   315   315 V MediaPlayerService: wait for prepare
07-27 09:15:44.127   315  7328 V AwesomePlayer: onPrepareAsyncEvent() 
07-27 09:15:44.127   315  7328 V AwesomePlayer: initAudioDecoder() 
07-27 09:15:44.127   315  7328 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 09:15:44.127   315  7328 V AudioSystem: isOffloadSupported()
07-27 09:15:44.128   315  7328 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1203354 us, has_video=0
07-27 09:15:44.128   315  7328 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 09:15:44.128   315  7328 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 09:15:44.128   315  7328 V AwesomePlayer: getUseOffload() = 0 
07-27 09:15:44.128   315  7328 V OMXCodec: OMXCodec::Create
07-27 09:15:44.128   315  7328 V OMXCodec: findMatchingCodecs()
07-27 09:15:44.128   315  7328 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-27 09:15:44.128   315  7328 V OMXCodec: matchingCodecs.size()=1
07-27 09:15:44.128   315  7328 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-27 09:15:44.134   315  7328 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-27 09:15:44.134   315  7328 V LGCodecAdapter: LG Codec Adapter start
07-27 09:15:44.134   315  7328 V OMXCodec: OMXCodec Createtor
07-27 09:15:44.134   315  7328 V OMXCodec: setComponentRole
07-27 09:15:44.134   315  7328 V OMXCodec: configureCodec protected=0
07-27 09:15:44.134   315  7328 V LGCodecAdapter: called getLGCodecSpecificData
07-27 09:15:44.134   315  7328 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-27 09:15:44.134   315  7328 V LGCodecOSAL: Called LGconfigureCodecMETA
07-27 09:15:44.134   315  7328 V LGCodecOSAL: Called LGconfigureCodecMSG
07-27 09:15:44.134   315  7328 V LGCodecOSAL: Not support LGCodec
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 09:15:44.135   315  7328 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-27 09:15:44.135   315  7328 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-27 09:15:44.135   315  7328 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 09:15:44.135   315  7328 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 09:15:44.135   315  7328 V AudioSystem: isOffloadSupported()
07-27 09:15:44.135   315  7328 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1203354 us, has_video=0
07-27 09:15:44.135   315  7328 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-27 09:15:44.135   315  7328 V OMXCodec: init()
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-27 09:15:44.135   315  7328 V OMXCodec: allocateBuffers
07-27 09:15:44.135   315  7328 V OMXCodec: allocateBuffersOnPort portIndex=0
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
07-27 09:15:44.135   315  7328 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 09:15:44.135   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 09:15:44.136   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-27 09:15:44.136   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-27 09:15:44.136   315  7328 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be2e0 on output port
07-27 09:15:44.136   315  7328 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 09:15:44.136   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 09:15:44.136   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 09:15:44.136   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-27 09:15:44.136   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-27 09:15:44.136   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-27 09:15:44.136   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
07-27 09:15:44.136   315  7328 V OMXCodec: init() mAsyncCompletion wait free! 
07-27 09:15:44.136   315  7328 V AwesomePlayer: finishAsyncPrepare_l() 
07-27 09:15:44.136   315  7328 V AudioCache: notify(0xb0409640, 5, 0, 0)
07-27 09:15:44.136   315  7328 V AudioCache: ignored
07-27 09:15:44.136   315  7328 V AudioCache: notify(0xb0409640, 1, 0, 0)
07-27 09:15:44.136   315  7328 V AudioCache: prepared
07-27 09:15:44.136   315   315 V AudioCache: wait - success
07-27 09:15:44.136   315   315 V MediaPlayerService: start
07-27 09:15:44.136   315   315 V AwesomePlayer: play_l() 
07-27 09:15:44.136   315   315 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-27 09:15:44.136   315   315 V AwesomePlayer: createAudioPlayer_l
07-27 09:15:44.136   315   315 V AwesomePlayer: seekAudioIfNecessary_l() 
07-27 09:15:44.136   315   315 V AwesomePlayer: startAudioPlayer_l() 
07-27 09:15:44.136   315   315 D AudioPlayer: start of Playback, useOffload 0
07-27 09:15:44.136   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 09:15:44.136   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 09:15:44.139   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-27 09:15:44.139   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-27 09:15:44.139   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044795104
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-27 09:15:44.140   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-27 09:15:44.141   315  7330 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 09:15:44.141   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 09:15:44.141   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-27 09:15:44.141   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-27 09:15:44.141   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
07-27 09:15:44.141   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on output port
07-27 09:15:44.141   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-27 09:15:44.141   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-27 09:15:4,4.142   315   315 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-27 09:15:44.142   315   315 V AudioCache: notify(0xb0409640, 6, 0, 0)
07-27 09:15:44.142   315   315 V AudioCache: ignored
07-27 09:15:44.142   315   315 V MediaPlayerService: wait for playback complete
07-27 09:15:44.143   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.143   315  7332 V AudioCache: memcpy(0xaf006000, 0xb16ea000, 4096)
07-27 09:15:44.143   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.143   315  7332 V AudioCache: memcpy(0xaf007000, 0xb16ea000, 4096)
07-27 09:15:44.143   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.143   315  7332 V AudioCache: memcpy(0xaf008000, 0xb16ea000, 4096)
07-27 09:15:44.144   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.144   315  7332 V AudioCache: memcpy(0xaf009000, 0xb16ea000, 4096)
07-27 09:15:44.144   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.144   315  7332 V AudioCache: memcpy(0xaf00a000, 0xb16ea000, 4096)
07-27 09:15:44.145   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.145   315  7332 V AudioCache: memcpy(0xaf00b000, 0xb16ea000, 4096)
07-27 09:15:44.149   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.149   315  7332 V AudioCache: memcpy(0xaf00c000, 0xb16ea000, 4096)
07-27 09:15:44.149   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.149   315  7332 V AudioCache: memcpy(0xaf00d000, 0xb16ea000, 4096)
07-27 09:15:44.150  1599  1599 D LgeKeyguardWallpaperContainer: image cache, cache hit : image from cache
07-27 09:15:44.150  1599  1599 D KeyguardModel: cache file exits
07-27 09:15:44.150   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.150   315  7332 V AudioCache: memcpy(0xaf00e000, 0xb16ea000, 4096)
07-27 09:15:44.151  1599  1599 D quilt lockscreen LightParticleRenderer: initRenderer()
07-27 09:15:44.151  1599  1599 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
07-27 09:15:44.151  1599  1599 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-27 09:15:44.151  1599  1599 I [SystemUI]NavigationThemeResource: , Keyguard show=true, IME shown=false, Panel expanded=false
07-27 09:15:44.151   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.151   315  7332 V AudioCache: memcpy(0xaf00f000, 0xb16ea000, 4096)
07-27 09:15:44.152   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.152   315  7332 V AudioCache: memcpy(0xaf010000, 0xb16ea000, 4096)
07-27 09:15:44.152   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.152   315  7332 V AudioCache: memcpy(0xaf011000, 0xb16ea000, 4096)
07-27 09:15:44.153   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.153   315  7332 V AudioCache: memcpy(0xaf012000, 0xb16ea000, 4096)
07-27 09:15:44.153   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.153   315  7332 V AudioCache: memcpy(0xaf013000, 0xb16ea000, 4096)
07-27 09:15:44.153  1599  1599 D KeyguardBackground: Backdrop animation start. dest Alpha : 1
07-27 09:15:44.153  1599  1599 D KeyguardBackground: setKeyguardBackground isPortrait ? true
07-27 09:15:44.153  1599  1599 D LgeKeyguardWallpaperContainer: queryReferenceOfBackground isPortrait : true ,queryObject : com.android.systemui.statusbar.phone.PhoneStatusBar@1d40714a
07-27 09:15:44.153  1599  1599 D KeyguardModel: cache file exits
07-27 09:15:44.154   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.154   315  7332 V AudioCache: memcpy(0xaf014000, 0xb16ea000, 4096)
07-27 09:15:44.154   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.154   315  7332 V AudioCache: memcpy(0xaf015000, 0xb16ea000, 4096)
07-27 09:15:44.155  1029  1708 V NotificationVibrator: cancel()
07-27 09:15:44.155  1029  1708 I VolumeVibratorManager: cancel()
07-27 09:15:44.155  1970  2175 D VolumeVibrator: clear
07-27 09:15:44.155  1029  2083 I LGImmersionVibrator: Vibrator off
07-27 09:15:44.156   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.156   315  7332 V AudioCache: memcpy(0xaf016000, 0xb16ea000, 4096)
07-27 09:15:44.156  1599  1599 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search >
07-27 09:15:44.156   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.156   315  7332 V AudioCache: memcpy(0xaf017000, 0xb16ea000, 4096)
07-27 09:15:44.156   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.156   315  7332 V AudioCache: memcpy(0xaf018000, 0xb16ea000, 4096)
07-27 09:15:44.157   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.157   315  7332 V AudioCache: memcpy(0xaf019000, 0xb16ea000, 4096)
07-27 09:15:44.158   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.158   315  7332 V AudioCache: memcpy(0xaf01a000, 0xb16ea000, 4096)
07-27 09:15:44.158   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.158   315  7332 V AudioCache: memcpy(0xaf01b000, 0xb16ea000, 4096)
07-27 09:15:44.159   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.159   315  7332 V AudioCache: memcpy(0xaf01c000, 0xb16ea000, 4096)
07-27 09:15:44.160   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.160   315  7332 V AudioCache: memcpy(0xaf01d000, 0xb16ea000, 4096)
07-27 09:15:44.160  1599  1599 D KeyguardBackground: updateKeyguardState mState ? 1 ,goingToFullShade ? false ,fromShadeLocked ? false
07-27 09:15:44.160  1599  1599 D KeyguardBackground: Backdrop animation start. dest Alpha : 1
07-27 09:15:44.160  1599  1599 D KeyguardBackground: setKeyguardBackground isPortrait ? true
07-27 09:15:44.161   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.161   315  7332 V AudioCache: memcpy(0xaf01e000, 0xb16ea000, 4096)
07-27 09:15:44.162   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.162   315  7332 V AudioCache: memcpy(0xaf01f000, 0xb16ea000, 4096)
07-27 09:15:44.162   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.162   315  7332 V AudioCache: memcpy(0xaf020000, 0xb16ea000, 4096)
07-27 09:15:44.163  1599  1599 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back home recent clock search >
07-27 09:15:44.163  1599  1599 D StatusBarKeyguardViewManager: adjustCameraSliderVisibility: shouldVisible = false, mGlanceViewNow = false
07-27 09:15:44.163   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.163   315  7332 V AudioCache: memcpy(0xaf021000, 0xb16ea000, 4096)
07-27 09:15:44.164   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.164   315  7332 V AudioCache: memcpy(0xaf022000, 0xb16ea000, 4096)
07-27 09:15:44.164  1599  1599 D StatusBarKeyguardViewManager: LockScreen status : 1 (Normal Lock)
07-27 09:15:44.165  1599  1599 D KeyguardViewMediator: adjustStatusBarLocked: mShowing=true mOccluded=false isSecure=false --> flags=0x3200000 --> lgNaviBtnFlag=0x70006
07-27 09:15:44.165   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.165   315  7332 V AudioCache: memcpy(0xaf023000, 0xb16ea000, 4096)
07-27 09:15:44.165  1029  2329 I SystemUI[Framework]: ==>disabled() what=0x3200000, token=android.os.BinderProxy@1662d740,  pkg=com.android.systemui
07-27 09:15:44.165  1029  2329 I SystemUI[Framework]: StatusBar disabled: mDisabled=0x3200000,  mDisableRecords.size=1
07-27 09:15:44.165  1029  2329 I SystemUI[Framework]: StatusBar disabled: [0] userId=0, what=0x3200000, pkg=com.android.systemui, token=android.os.BinderProxy@1662d740
07-27 09:15:44.165  1029  2087 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x70006 pkg=com.android.systemui
07-27 09:15:44.165   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.165   315  7332 V AudioCache: memcpy(0xaf024000, 0xb16ea000, 4096)
07-27 09:15:44.165  1029  2087 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x70006, token=android.os.BinderProxy@1662d740,  pkg=com.android.systemui
07-27 09:15:44.165  1029  2087 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x70006,  mDisableRecords.size=1
07-27 09:15:44.165  1029  2087 I SystemUI[Framework]:   [0] userId=0, what=0x70006, pkg=com.android.systemui, token=android.os.BinderProxy@1662d740
07-27 09:15:44.166   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.166   315  7332 V AudioCache: memcpy(0xaf025000, 0xb16ea000, 4096)
07-27 09:15:44.167  1599  1599 V KeyguardDisplayManager: show
07-27 09:15:44.167   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.167   315  7332 V AudioCache: memcpy(0xaf026000, 0xb16ea000, 4096)
07-27 09:15:44.167   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.167   315  7332 V AudioCache: memcpy(0xaf027000, 0xb16ea000, 4096)
07-27 09:15:44.168   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.168   315  7332 V AudioCache: memcpy(0xaf028000, 0xb16ea000, 4096)
07-27 09:15:44.169   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.169   315  7332 V AudioCache: memcpy(0xaf029000, 0xb16ea000, 4096)
07-27 09:15:44.169   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.170   315  7332 V AudioCache: memcpy(0xaf02a000, 0xb16ea000, 4096)
07-27 09:15:44.170   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.170   315  7332 V AudioCache: memcpy(0xaf02b000, 0xb16ea000, 4096)
07-27 09:15:44.171   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.171   315  7332 V AudioCache: memcpy(0xaf02c000, 0xb16ea000, 4096)
07-27 09:15:44.172   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.172   315  7332 V AudioCache: memcpy(0xaf02d000, 0xb16ea000, 4096)
07-27 09:15:44.173   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.173   315  7332 V AudioCache: memcpy(0xaf02e000, 0xb16ea000, 4096)
07-27 09:15:44.174   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.174   315  7332 V AudioCache: memcpy(0xaf02f000, 0xb16ea000, 4096)
07-27 09:15:44.175   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.175   315  7332 V AudioCache: memcpy(0xaf030000, 0xb16ea000, 4096)
07-27 09:15:44.175   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.176   315  7332 V AudioCache: memcpy(0xaf031000, 0xb16ea000, 4096)
07-27 09:15:44.176   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.176   315  7332 V AudioCache: memcpy(0xaf032000, 0xb16ea000, 4096)
07-27 09:15:44.177   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.177   315  7332 V AudioCache: memcpy(0xaf033000, 0xb16ea000, 4096)
07-27 09:15:44.178   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.178   315  7332 V AudioCache: memcpy(0xaf034000, 0xb16ea000, 4096)
07-27 09:15:44.178   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.178   315  7332 V AudioCache: memcpy(0xaf035000, 0xb16ea000, 4096)
07-27 09:15:44.179   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.179   315  7332 V AudioCache: memcpy(0xaf036000, 0xb16ea000, 4096)
07-27 09:15:44.180   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.180   315  7332 V AudioCache: memcpy(0xaf037000, 0xb16ea000, 4096)
07-27 09:15:44.180   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.180   315  7332 V AudioCache: memcpy(0xaf038000, 0xb16ea000, 4096)
07-27 09:15:44.181   315  7332 V AudioCache: write(0xb16ea000, 4096)
,07-27 09:15:44.181   315  7332 V AudioCache: memcpy(0xaf039000, 0xb16ea000, 4096)
07-27 09:15:44.182   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.182   315  7332 V AudioCache: memcpy(0xaf03a000, 0xb16ea000, 4096)
07-27 09:15:44.182   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.182   315  7332 V AudioCache: memcpy(0xaf03b000, 0xb16ea000, 4096)
07-27 09:15:44.183   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.183   315  7332 V AudioCache: memcpy(0xaf03c000, 0xb16ea000, 4096)
07-27 09:15:44.183   315  7332 V AudioCache: write(0xb16ea000, 4096)
07-27 09:15:44.183   315  7332 V AudioCache: memcpy(0xaf03d000, 0xb16ea000, 4096)
07-27 09:15:44.184   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-27 09:15:44.184   315  7332 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 09:15:44.184   315  7332 V AwesomePlayer: postAudioEOS() 
07-27 09:15:44.184   315  7332 V AudioCache: write(0xb16ea000, 1668)
07-27 09:15:44.184   315  7332 V AudioCache: memcpy(0xaf03e000, 0xb16ea000, 1668)
07-27 09:15:44.192   315  7328 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-27 09:15:44.193   315  7328 V AwesomePlayer: onStreamDone
07-27 09:15:44.193   315  7328 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 09:15:44.193   315  7328 V AudioCache: notify(0xb0409640, 2, 0, 0)
07-27 09:15:44.193   315  7328 V AudioCache: playback complete
07-27 09:15:44.193   315  7328 V AwesomePlayer: pause_l() 
07-27 09:15:44.193   315  7328 V AudioCache: notify(0xb0409640, 7, 0, 0)
07-27 09:15:44.193   315  7328 V AudioCache: ignored
07-27 09:15:44.193   315  7328 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.193   315   315 V AudioCache: wait - success
07-27 09:15:44.193   315   315 V MediaPlayerService: return size 231044, sampleRate=48000, channelCount = 2, format = 1
07-27 09:15:44.193   315  7328 D AudioPlayer: Pause Playback at 1203354
07-27 09:15:44.193   315   315 V AwesomePlayer: reset_l() 
07-27 09:15:44.193   315   315 V AudioCache: notify(0xb0409640, 8, 0, 0)
07-27 09:15:44.193   315   315 V AudioCache: ignored
07-27 09:15:44.193   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.193   315   315 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 09:15:44.193   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 09:15:44.193   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-27 09:15:44.193   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-27 09:15:44.193   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 1
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 09:15:44.194   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-27 09:15:44.194   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 09:15:44.194   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 09:15:44.195   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-27 09:15:44.195   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-27 09:15:44.195   315  7330 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-27 09:15:44.195   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 09:15:44.195   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-27 09:15:44.195   315   315 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-27 09:15:44.195   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-27 09:15:44.195   315   315 D AudioPlayer: AudioPlayer releasing audio source
07-27 09:15:44.195   315   315 D AudioPlayer: AudioPlayer done releasing audio source
07-27 09:15:44.195   315   315 V AwesomePlayer: reset_l() 
07-27 09:15:44.195   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.195   315   315 V AwesomePlayer: ~AwesomePlayer call
07-27 09:15:44.196  1029  1104 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x608600, pkg=com.android.systemui
07-27 09:15:44.196   315   315 V AwesomePlayer: reset_l() 
07-27 09:15:44.196   315   315 V AwesomePlayer: cancelPlayerEvents
07-27 09:15:44.196  1599  7307 V SoundPool: close(109)
07-27 09:15:44.196  1599  7307 V SoundPool: pointer = 0x97355000, size = 231044, sampleRate = 48000, numChannels = 2
07-27 09:15:44.196  1029  1104 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-27 09:15:44.196  1029  1104 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-27 09:15:44.196  1029  1104 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 09:15:44.196  1029  1104 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a6a45a,  pkg=WindowManager.LayoutParams
07-27 09:15:44.196  1029  1104 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x70006,  mDisableRecords.size=1
07-27 09:15:44.196  1029  1104 I SystemUI[Framework]:   [0] userId=0, what=0x70006, pkg=com.android.systemui, token=android.os.BinderProxy@1662d740
07-27 09:15:44.211  1029  1570 D InputDispatcher: Focus left window: Window{1c7ccfa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:15:44.211  1029  1570 D InputDispatcher: Focus entered window: Window{2d09dc60 u0 StatusBar}
07-27 09:15:44.211  1029  1570 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=10000 (1393489 ms ago)
,07-27 09:15:44.250  1029  1925 D SplitWindow: check instance of lgWin Window{18f3e14d u0 SurfaceView}
,07-27 09:15:44.267   346   369 E GBMv2   : Set value is all cleared set the max
07-27 09:15:44.267   346   369 I GBMv2   : VFP is [12]
,07-27 09:15:44.284  1599  1599 D EmergencyButton: updateEmergencyCallButton(phoneState: 0
07-27 09:15:44.284  1599  1599 D EmergencyButton: MDM updateEmergencyCallButton() - isLockoutMode: false
,07-27 09:15:44.291  1599  1599 D EmergencyButton: updateEmergencyCallButton(phoneState: 0
07-27 09:15:44.291  1599  1599 D EmergencyButton: MDM updateEmergencyCallButton() - isLockoutMode: false
07-27 09:15:44.293  1599  1599 D EmergencyButton: updateEmergencyCallButton(phoneState: 0
,07-27 09:15:44.293  1599  1599 D EmergencyButton: MDM updateEmergencyCallButton() - isLockoutMode: false
07-27 09:15:44.296  1599  1599 V KeyguardStatusView: refresh statusview showing:true
07-27 09:15:44.297  1599  1599 D PhoneStatusBar: disableNaviBtn: < menu SIM_SWITCH* NOTIFICATION* QMEMO* QSLIDE* DUAL_WINDOW* >
,07-27 09:15:44.316  1599  1599 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO BACK* HOME* RECENT* clock SEARCH* >
,07-27 09:15:44.330  1599  1599 D PhoneStatusBar: setSystemUiVisibility vis=608600 mask=ffffffff oldVal=8600 newVal=608600 diff=600000
,07-27 09:15:44.479  1029  1044 D InputDispatcher: Window went away: Window{4d0b495 u0 SearchPanel}
,07-27 09:15:44.482  1599  1599 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-27 09:15:45.725   346   375 E GBMv2   : DFP En is all cleared set to be enabled
,07-27 09:15:45.725   346   375 E GBMv2   : Set value is all cleared set the max
,07-27 09:15:45.725   346   375 I GBMv2   : DFP Enabled. Ignore VFP set
,07-27 09:16:00.055  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:16:00.055  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:16:00.055  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:16:00.056  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:16:00.071  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 09:16:00.071  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:16:00.074  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
,07-27 09:16:00.075  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:16:31.833  1029  1373 D PowerManagerServiceEx: acquireWakeLockInternal: lock=141172205, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,07-27 09:16:31.861  1029  1373 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d0a9402 type 2 when 1428672 com.google.android.gms} when 1428672
,07-27 09:16:31.920  2665  2665 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 09:16:31.952  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=141172205 [*alarm*], flags=0x0
,07-27 09:17:00.054  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-27 09:17:00.055  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 09:17:00.055  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-27 09:17:00.055  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms),07-27 09:17:00.071  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:17:00.071  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:17:00.073  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:17:00.075  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:17:13.948  7344  7344 D AndroidRuntime: 
07-27 09:17:13.948  7344  7344 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 09:17:13.953  7344  7344 D AndroidRuntime: CheckJNI is OFF
07-27 09:17:14.150  7344  7344 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-27 09:17:14.171  1029  1086 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-27 09:17:14.172  1029  1086 I ActivityManager: Killing 5765:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
07-27 09:17:14.223  1029  1925 I WindowState: WIN DEATH: Window{1c7ccfa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:17:14.225  1029  1399 D WifiService: Client connection lost with reason: 4
07-27 09:17:14.228  1029  1925 D InputDispatcher: Window went away: Window{1c7ccfa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:17:14.392  1029  1086 I ActivityManager:   Force finishing activity ActivityRecord{1f995b60 u0 com.test.thalitest/.MainActivity t40}
07-27 09:17:14.418  1029  1029 V ActivityManager: Display changed displayId=0
07-27 09:17:14.423  1873  1873 D DSDPConnection: Display #0 changed.
07-27 09:17:14.448   346   369 E GBMv2   : DFP En is all cleared set to be enabled
07-27 09:17:14.453  1029  1967 W ActivityManager: Spurious death for ProcessRecord{3225d113 5765:com.test.thalitest/u0a118}, curProc for 5765: null
07-27 09:17:14.454  1970  1986 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
07-27 09:17:14.455  1970  1986 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e432a0c co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-27 09:17:14.455  1029  1118 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-27 09:17:14.457  1029  1118 I ActivityManager:   Force finishing activity ActivityRecord{1f995b60 u0 com.test.thalitest/.MainActivity t40 f}
07-27 09:17:14.457  1029  1118 W ActivityManager: Duplicate finish request for ActivityRecord{1f995b60 u0 com.test.thalitest/.MainActivity t40 f}
07-27 09:17:14.464  1970  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-27 09:17:14.465  1970  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ab0bf55 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-27 09:17:14.504  2088  2088 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-27 09:17:14.506  2088  2088 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-27 09:17:14.507  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-27 09:17:14.514  1029  1375 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-27 09:17:14.522  2747  2747 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
07-27 09:17:14.524  2034  2034 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-27 09:17:14.526  2459  2600 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 09:17:14.528  6056  6056 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-27 09:17:14.529  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-27 09:17:14.531  4249  4249 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-27 09:17:14.554  1029  1086 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7369 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 09:17:14.555  2088  2088 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-27 09:17:14.555  4249  4249 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-27 09:17:14.555  4249  4249 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-27 09:17:14.555  4249  4249 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-27 09:17:14.556  4249  4249 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 09:17:14.556  4249  4249 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 09:17:14.556  4249  4249 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:14.556  4249  4249 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 09:17:14.556  4249  4249 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:17:14.556  4249  4249 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 09:17:14.556  4249  4249 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 09:17:14.556  4249  4249 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 09:17:14.556  2088  2179 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-27 09:17:14.563  2088  2088 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-27 09:17:14.564  2088  2088 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-27 09:17:14.564  2088  2088 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-27 09:17:14.566  1924  1924 D ActionManagerService: notifyUserLog: 1000003
07-27 09:17:14.567  2747  4187 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-27 09:17:14.567  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-27 09:17:14.571  2088  2088 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-27 09:17:14.574  1599  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 09:17:14.574  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.575  1599  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 09:17:14.575  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.582  1924  1924 D ActionManagerService: notifyUserLog: 1000004
07-27 09:17:14.582  2747  4187 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-27 09:17:14.583  2088  2088 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
07-27 09:17:14.584  2747  2762 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , create_time: 1430832262123
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , expire_time: 0
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , display: false
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , animation: false }
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , create_time: 1430832262287
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , expire_time: 0
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , display: false
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , animation: false }
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , create_time: 1469186101943
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , expire_time: 0
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , display: false
07-27 09:17:14.587  2088  2088 I GBoardWebViewUtils: , animation: false }
07-27 09:17:14.596  1599  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-27 09:17:14.596  1599  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 09:17:14.597  1599  1647 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-27 09:17:14.597  1599  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 09:17:14.603  2088  7382 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
07-27 09:17:14.608  4340  4340 I art     : Explicit concurrent mark sweep GC freed 7948(463KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 340us total 127.491ms
07-27 09:17:14.613  1599  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 09:17:14.613  1599  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 09:17:14.614  1599  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 09:17:14.614  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.617  1029  2046 V SIM_STK : Menu title from STK is T-Mobile
07-27 09:17:14.617  1029  2046 V SIM_STK : Menu title from STK is T-Mobile
07-27 09:17:14.618  1599  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-27 09:17:14.619  1599  1647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 09:17:14.620  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-27 09:17:14.623  1599  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 09:17:14.623  1599  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 09:17:14.626  1599  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 09:17:14.626  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.627  2088  2088 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 09:17:14.628  2088  2088 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
07-27 09:17:14.630  1599  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 09:17:14.630  1599  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 09:17:14.630  1599  1647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-27 09:17:14.630  1599  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 09:17:14.631  1599  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 09:17:14.632  1599  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 09:17:14.647  1029  1987 V SIM_STK : Menu title from STK is T-Mobile
07-27 09:17:14.650  1599  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 09:17:14.650  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.663  1599  1599 D KeyguardModel: handleShortcutListChanged...
07-27 09:17:14.663  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-27 09:17:14.677  1029  2046 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-27 09:17:14.679  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 09:17:14.680  6056  6056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 09:17:14.708  2088  2088 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-27 09:17:14.715  1890  1890 D SplitUIManager: split_name #11 / not available #0
07-27 09:17:14.715  1890  1890 D SplitUIService: removed split : 
07-27 09:17:14.718  7369  7369 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 09:17:14.733  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-27 09:17:14.740  1599  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 09:17:14.740  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.744  1599  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 09:17:14.744  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.746  1599  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 09:17:14.746  1599  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 09:17:14.747  1890  1890 D SplitUIManager: split_name #11 / not available #0
07-27 09:17:14.747  1890  1890 I SplitUIService: split app #11
07-27 09:17:14.748  1029  1029 I art     : Explicit concurrent mark sweep GC freed 246453(11MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 44MB/66MB, paused 2.525ms total 272.792ms
07-27 09:17:14.751  1029  1118 I art     : WaitForGcToComplete blocked for 73.593ms for cause Explicit
07-27 09:17:14.777  1599  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 09:17:14.777  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.779  2088  2088 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
07-27 09:17:14.779  1599  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 09:17:14.779  1599  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 09:17:14.782  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 09:17:14.783  1599  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 09:17:14.783  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.784  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-27 09:17:14.784  1599  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 09:17:14.784  1599  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 09:17:14.785  1599  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 09:17:14.785  1599  1647 D KeyguardModel: createShortcutInfo...
07-27 09:17:14.785  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-27 09:17:14.787  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-27 09:17:14.788  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-27 09:17:14.790  7369  7369 D PluginManager: init()
07-27 09:17:14.801  1029  1029 D administrator: Handling package changes for user 0
07-27 09:17:14.804  1029  1106 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{dc3d170 u0 com.lge.launcher2/.Launcher t39} time:1494083
07-27 09:17:14.810  1029  1709 V SIM_STK : Menu title from STK is T-Mobile
07-27 09:17:14.810  2088  2088 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-27 09:17:14.810  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 09:17:14.811  2088  2248 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-27 09:17:14.811  2088  2248 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
07-27 09:17:14.815  1599  1599 D KeyguardModel: handleShortcutListChanged...
07-27 09:17:14.815  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-27 09:17:14.832  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-27 09:17:14.832  2088  2088 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-27 09:17:14.833  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 09:17:14.840  2088  2088 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
07-27 09:17:14.843  2665  2665 D [Concierge]Service: onStartCommand(). Type : 8
07-27 09:17:14.843  2665  2665 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-27 09:17:14.844  2665  2665 D [Concierge]Service: Update widget ID : 11
07-27 09:17:14.846  2088  2088 D [Concierge]WidgetView: change position of spinner
07-27 09:17:14.847  2088  2088 I [Concierge]WidgetView: initWebView(). Time : 1469603834847
07-27 09:17:14.847  2665  2665 D [Concierge]Service: onStartCommand(). Type : 0
07-27 09:17:14.874  2088  2088 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 875515940
07-27 09:17:14.874  2088  2088 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-27 09:17:14.874  2088  2088 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-27 09:17:14.877  2088  2088 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@ff8e136
07-27 09:17:14.877  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-27 09:17:14.878  2088  2088 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-27 09:17:14.879  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 09:17:14.885  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-27 09:17:14.885  2088  2088 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-27 09:17:14.886  2088  2088 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469602369176, New one : 1469603834847
07-27 09:17:14.886  2088  2088 D [Concierge]WidgetView: Unregister all receivers
07-27 09:17:14.887  2088  2088 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-27 09:17:14.887  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 09:17:14.889  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-27 09:17:14.890  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-27 09:17:14.891  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-27 09:17:14.892  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-27 09:17:14.893  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-27 09:17:14.896  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 09:17:14.896  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 09:17:14.913  1029  1029 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-27 09:17:14.913  1029  1029 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 09:17:14.913  1029  1029 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 09:17:14.918  1029  1574 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
07-27 09:17:14.938  2088  2088 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-27 09:17:14.946  2088  2088 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-27 09:17:14.946  2088  2088 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-27 09:17:14.970  2088  2088 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-27 09:17:14.971  2088  2088 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 09:17:14.982  1029  1118 I art     : Explicit concurrent mark sweep GC freed 15665(1008KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.420ms total 224.534ms
07-27 09:17:14.986   334   426 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-27 09:17:14.986  3162  7398 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-27 09:17:14.989  2088  2088 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@22bcc3b9 time:1494268
07-27 09:17:15.025  7344  7344 D AndroidRuntime: Shutting down VM
07-27 09:17:15.055  1029  1118 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7399 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-27 09:17:15.091  7369  7369 W ExternalStrings: load override strings
07-27 09:17:15.091  7369  7369 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 09:17:15.091  7369  7369 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 09:17:15.091  1029  2328 I ActivityManager: Killing 6479:com.google.android.setupwizard/u0a46 (adj 15): empty #17
07-27 09:17:15.092  7369  7369 D StatusProvider: onCreate
07-27 09:17:15.099  2088  2088 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
07-27 09:17:15.133  1029  1925 W libprocessgroup: failed to open /acct/uid_10046/pid_6479/cgroup.procs: No such file or directory
07-27 09:17:15.134  2088  2890 I GBoardtInterface: onReloaded()
07-27 09:17:15.135  2088  2088 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-27 09:17:15.136  2747  2774 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 09:17:15.138  2747  2775 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 09:17:15.144  1924  1924 D ActionManagerService: notifyUserLog: 1000001
07-27 09:17:15.145  2747  4187 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-27 09:17:15.145  2747  4187 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-27 09:17:15.147  1924  1924 D ActionManagerService: notifyUserLog: 1000001
07-27 09:17:15.148  2747  4187 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-27 09:17:15.148  2747  4187 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-27 09:17:15.148  2747  4187 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-27 09:17:15.148  2747  4187 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-27 09:17:15.149  2747  2775 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 09:17:15.151  2088  2088 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
07-27 09:17:15.151  2088  2088 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-27 09:17:15.153  2088  2088 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-27 09:17:15.153  2088  2088 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-27 09:17:15.154  2088  2088 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-27 09:17:15.154  2088  2088 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-27 09:17:15.172  7369  7369 V Signer  : override build config not found
07-27 09:17:15.173  7369  7369 D Signer  : value of property debug is false
07-27 09:17:15.193  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
07-27 09:17:15.193  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
07-27 09:17:15.193  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-27 09:17:15.193  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-27 09:17:15.194  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-27 09:17:15.194  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-27 09:17:15.194  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-27 09:17:15.194  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-27 09:17:15.195  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-27 09:17:15.195  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-27 09:17:15.195  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-27 09:17:15.195  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-27 09:17:15.195  7369  7369 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
07-27 09:17:15.202  7369  7369 V LGMDMManager: Create singleton instance
07-27 09:17:15.237  7369  7369 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
07-27 09:17:15.265  7369  7369 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-27 09:17:15.266  7369  7419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 09:17:15.268  1838  1838 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-27 09:17:15.273  2238  2238 I ConfigService: onCreate
07-27 09:17:15.273  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 09:17:15.275  1838  1838 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-27 09:17:15.277  2238  2238 I ConfigService: onBind returning update interface
07-27 09:17:15.278  2238  2238 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 09:17:15.278  2238  2238 I ConfigService: onBind returning config service
07-27 09:17:15.319  1029  1085 W InputMethodInfo: Duplicated subtype definition found: , voice
07-27 09:17:15.319  2238  2238 I ConfigService: onDestroy
07-27 09:17:15.331  1838  7425 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-27 09:17:15.338  6870  6870 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: Error inserting package=com.test.thalitest
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 09:17:15.339  6870  6870 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 09:17:15.348  2148  7428 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-27 09:17:15.365  2148  2266 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-27 09:17:15.372  2148  7428 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
07-27 09:17:15.372  2148  7428 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-27 09:17:15.372  2148  7428 E AndroidRuntime: Process: android.process.acore, PID: 2148
07-27 09:17:15.372  2148  7428 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.372  2148  7428 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.376  2148  2266 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:17:15.377  1029  2329 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7429 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-27 09:17:15.380  7369  7418 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-27 09:17:15.385  2148  7428 I Process : Sending signal. PID: 2148 SIG: 9
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: Can't write: system_app_crash
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 09:17:15.391  1029  7438 E DropBoxManagerService: 	... 5 more
07-27 09:17:15.400  5329  7451 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
07-27 09:17:15.412  2088  2890 I GBoardtInterface: exportHTML()
07-27 09:17:15.423  1838  7453 I PeopleContactsSync: CP2 sync disabled
07-27 09:17:15.423  1838  4493 I Icing   : doRemovePackageData com.test.thalitest
07-27 09:17:15.440  1838  4493 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
07-27 09:17:15.440  1838  4493 E Icing   : Could not init tag ds.tag.corpusid-1
07-27 09:17:15.440  1838  4493 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
07-27 09:17:15.440  1838  4493 E Icing   : Could not init tag ds.tag.corpusid-13
07-27 09:17:15.440  1838  4493 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
07-27 09:17:15.440  1838  4493 E Icing   : Could not init tag ds.tag.corpusid-7
07-27 09:17:15.441  1838  4493 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
07-27 09:17:15.441  1838  4493 E Icing   : Could not init tag ds.tag.corpusid-8
07-27 09:17:15.442  2088  2890 I GBoardtInterface: exportHTML()
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.445  1838  7445 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.445  1838  7445 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:17:15.446  1838  7445 W SQLiteOpenHelper: Opened metrics.db in read-only mode
07-27 09:17:15.447  1838  7445 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
07-27 09:17:15.447  1838  7445 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
07-27 09:17:15.447  1838  7445 E AndroidRuntime: Process: com.google.android.gms, PID: 1838
07-27 09:17:15.447  1838  7445 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.447  1838  7445 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:17:15.449  7429  7429 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 09:17:15.449  7429  7429 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 09:17:15.450  7429  7429 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 09:17:15.450  7429  7429 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 09:17:15.452  1838  4493 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
07-27 09:17:15.452  1838  4493 E Icing   : Could not init tag ds.tag.corpusid-9
07-27 09:17:15.452  1838  4493 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
07-27 09:17:15.452  1838  4493 E Icing   : Could not init tag ds.tag.deleted
07-27 09:17:15.452  1838  4493 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
07-27 09:17:15.452  1838  4493 E Icing   : Writing status failed
07-27 09:17:15.468  2088  2890 I GBoardtInterface: exportHTML()
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.g.b.a(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:17:15.470  7369  7418 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.b(SourceFile:502)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:496)
07-27 09:17:15.474  1838  7456 E SQLiteDatabase: 	at com.google.android.gms.drive.database.l.run(SourceFile:519)
07-27 09:17:15.474  1838  7456 I Process : Sending signal. PID: 1838 SIG: 9
07-27 09:17:15.488  1029  1399 D WifiService: Client connection lost with reason: 4
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.a.a(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.d.d(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.d.<init>(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.d.a(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.modes.adapt.a.a(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.h.<init>(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.f.<init>(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.f.a(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafe,e.applock.AppLockComponent.a(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:17:15.488  7369  7418 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: Couldn't open lockedapplications for writing (will try read-only):
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.a.a(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.d.d(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.d.<init>(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.d.a(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.modes.adapt.a.a(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.h.<init>(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.f.<init>(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.f.a(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.c.b.b(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.framework.b.a(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.app.t.run(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.d.f.run(Unknown Source)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:17:15.489  7369  7418 E SQLiteOpenHelper: 	at com.mcafee.d.c.run(Unknown Source)
07-27 09:17:15.492  7369  7418 W SQLiteOpenHelper: Opened lockedapplications in read-only mode
07-27 09:17:15.492  1029  1709 I ActivityManager: Process android.process.acore (pid 2148) has died
07-27 09:17:15.492  1029  1709 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
07-27 09:17:15.492  1029  1709 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
07-27 09:17:15.494   277   277 E lowmemorykiller: Error writing /proc/1838/oom_score_adj; errno=22
07-27 09:17:15.495  1029  1044 W ActivityManager: Exception when destroying service com.google.android.gms/.icing.service.IndexWorkerService
07-27 09:17:15.495  1029  1044 W ActivityManager: android.os.DeadObjectException
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1681)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1593)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at com.android.server.am.ActiveServices.stopServiceLocked(ActiveServices.java:451)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at com.android.server.am.ActiveServices.stopServiceLocked(ActiveServices.java:474)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at com.android.server.am.ActivityManagerService.stopService(ActivityManagerService.java:15217)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:910)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
07-27 09:17:15.495  1029  1044 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
07-27 09:17:15.495   277   277 E lowmemorykiller: Error writing /proc/1838/oom_score_adj; errno=22
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 09:17:15.500  7429  7429 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 09:17:15.500  7429  7429 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 09:17:15.501  7429  7429 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 09:17:15.501  7429  7429 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 09:17:15.501  7429  7429 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:17:15.501  7429  7429 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 09:17:15.501  7429  7429 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 09:17:15.501  7429  7429 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.notificationtray.e.a(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:17:15.502  7369  7418 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)

```
