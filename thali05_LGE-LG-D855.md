#### Test 72145431744cc2c_thali05_LGE-LG-D855 Logs


```
--------- beginning of system
07-12 11:36:18.342  1031  1972 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5652 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
--------- beginning of main
07-12 11:36:18.369   348   348 I art     : Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 427us total 24.610ms
07-12 11:36:18.390   348   348 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 19.461ms
,07-12 11:36:18.414   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 23.785ms
07-12 11:36:18.566  5652  5652 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
07-12 11:36:18.659  5652  5652 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:18.660  5652  5652 D LgDataFeature: LgDataFeature() Constructor Done, null
07-12 11:36:18.734  5652  5652 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
07-12 11:36:18.751  5687  5687 D AndroidRuntime: 
07-12 11:36:18.751  5687  5687 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-12 11:36:18.755  5687  5687 D AndroidRuntime: CheckJNI is OFF
07-12 11:36:18.757  5652  5652 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-12 11:36:18.758  5652  5652 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-12 11:36:18.775  5652  5652 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-12 11:36:18.775  5652  5652 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
07-12 11:36:18.786  1031  1917 I ActivityManager: Killing 5042:com.google.android.setupwizard/u0a46 (adj 15): empty #17
07-12 11:36:18.841  1031  1992 W libprocessgroup: failed to open /acct/uid_10046/pid_5042/cgroup.procs: No such file or directory
07-12 11:36:18.862  4258  5718 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-12 11:36:18.914  1031  1052 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5719 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-12 11:36:18.923  2804  2820 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-12 11:36:18.924  2804  2820 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@a241986 on behalf of 5652
07-12 11:36:18.950  5652  5652 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-12 11:36:18.966  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
07-12 11:36:18.966  1031  1364 W ActivityManager: Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
07-12 11:36:18.968  1031  1364 V AlarmManager: RTC_WAKEUP set : Alarm{5a50c84 type 0 when 1468229721922 com.android.providers.contacts} when 1468229721922
07-12 11:36:18.969  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{232ebc6d type 2 when 46557 com.google.android.talk} when 46557
07-12 11:36:18.970  1031  1364 V AlarmManager: RTC_WAKEUP set : Alarm{219da0a2 type 0 when 1468316145387 com.lge.ia.task.mrgdblogger} when 1468316145387
07-12 11:36:18.970  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{365af133 type 2 when 76155 com.google.android.gms} when 76155
07-12 11:36:18.980  5687  5687 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 11:36:18.994  5652  5652 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
07-12 11:36:18.995  1031  1921 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 11:36:19.013  1922  1938 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-12 11:36:19.019  1031  1921 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-12 11:36:19.021  1031  1921 D ActivityManager: setTaskToReturnTo : TaskRecord{173f681c #38 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-12 11:36:19.021  1031  1921 D ActivityManager: setTaskToReturnTo : TaskRecord{173f681c #38 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-12 11:36:19.022  1031  1921 D WindowStateEx: AppWindowTokenEx init.. 
07-12 11:36:19.023   344   397 E GBMv2   : DFP En is all cleared set to be enabled
07-12 11:36:19.069  1031  1921 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5748 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-12 11:36:19.070  5687  5687 D AndroidRuntime: Shutting down VM
07-12 11:36:19.079  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
07-12 11:36:19.092  5719  5719 D DocsApplication: Installing DEX configuration.
07-12 11:36:19.110  5719  5719 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-12 11:36:19.114  5719  5719 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{246a4f7c com.google.android.apps.docs}
07-12 11:36:19.128  5719  5719 D TAG     : onCreate()
07-12 11:36:19.134  1922  1938 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-12 11:36:19.134  1922  1938 D SplitWindowPolicy: topRunningActivity=ActivityInfo{284ec259 co.....MainActivity}, taskId=38, activityType=0, bIsSplit=false
07-12 11:36:19.135  1922  1937 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-12 11:36:19.136  1922  1937 D SplitWindowPolicy: topRunningActivity=ActivityInfo{12960e1e co.....MainActivity}, taskId=38, activityType=0, bIsSplit=false
07-12 11:36:19.145  5719  5719 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-12 11:36:19.188  5748  5748 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-12 11:36:19.280  5748  5748 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-12 11:36:19.286  5748  5748 I LibraryLoader: Loading: webviewchromium
07-12 11:36:19.289  5748  5748 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5659-5662)
07-12 11:36:19.289  5748  5748 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:19.307  5748  5748 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11199026}
07-12 11:36:19.308  5748  5748 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:19.308  5748  5748 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 11:36:19.317  5748  5748 I BrowserStartupController: Initializing chromium process, renderers=0
07-12 11:36:19.318  5748  5748 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:19.323  5748  5767 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
07-12 11:36:19.328  1031  1629 V SIM_STK : Menu title from STK is T-Mobile
07-12 11:36:19.330  5748  5748 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-12 11:36:19.331  5748  5748 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-12 11:36:19.331  5748  5748 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-12 11:36:19.337   315  1765 V AudioPolicyService: registerClient() client 0xb557c120, uid 10118
07-12 11:36:19.342  1031  1111 D BluetoothManagerService: Message: 20
07-12 11:36:19.342  1031  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@324ea59e:true
07-12 11:36:19.343  5748  5771 D BluetoothAdapter: 892478567: getState() :  mService = null. Returning STATE_OFF
07-12 11:36:19.343  5748  5748 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:36:19.343  5748  5748 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:36:19.343  5748  5748 I Adreno-EGL: Build Date: 12/12/14 금
07-12 11:36:19.343  5748  5748 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-12 11:36:19.343  5748  5748 I Adreno-EGL: Remote Branch: 
07-12 11:36:19.343  5748  5748 I Adreno-EGL: Local Patches: 
07-12 11:36:19.343  5748  5748 I Adreno-EGL: Reconstruct Branch: 
07-12 11:36:19.385  4258  5718 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 522 ms] updated apps [took 521 ms] 
07-12 11:36:19.435  5748  5777 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-12 11:36:19.437  5748  5748 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-12 11:36:19.450  5748  5748 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:19.453  5748  5748 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-12 11:36:19.455  5748  5748 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-12 11:36:19.458  5748  5748 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-12 11:36:19.458  5748  5748 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-12 11:36:19.470  5748  5748 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-12 11:36:19.476  5748  5748 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:19.476  5748  5748 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:19.516  5748  5790 D OpenGLRenderer: Render dirty regions requested: true
07-12 11:36:19.517  5748  5790 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 11:36:19.538  5748  5790 D OpenGLRenderer: Enabling debug mode 0
07-12 11:36:19.552  5748  5748 D Atlas   : Validating map...
07-12 11:36:19.557  1031  2012 D SplitWindow: check instance of lgWin Window{85f8714 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 11:36:19.600  5748  5788 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:19.600  5748  5788 D LgDataFeature: LgDataFeature() Constructor Done, null
07-12 11:36:19.679  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{205ca4ac type 2 when 86038 com.android.providers.calendar} when 86038
07-12 11:36:19.694  5748  5748 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@21468262 time:86068
07-12 11:36:19.696  1031  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +560ms (total +669ms)
07-12 11:36:19.697  1031  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19600c25 u0 com.test.thalitest/.MainActivity t38} time:86070
07-12 11:36:19.805  5748  5748 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-12 11:36:19.805  5748  5748 I chromium: 
07-12 11:36:19.855  5748  5748 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-12 11:36:19.945  5748  5788 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-12 11:36:19.945  5748  5788 I chromium: 
07-12 11:36:20.093  5748  5808 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
07-12 11:36:20.108  5748  5808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:36:20.108  5748  5808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:36:20.108  5748  5808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:36:20.108  5748  5808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:36:20.108  5748  5808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 11:36:20.109  5748  5808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a241986 added. We now have 1 listener(s)
07-12 11:36:20.110  1031  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:20.120  5748  5808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-12 11:36:20.122  5748  5808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-12 11:36:20.126  5748  5808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:36:20.127  5748  5808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 11:36:20.138  5748  5808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb69b9d added. We now have 1 listener(s)
07-12 11:36:20.138  5748  5808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 11:36:20.142  1031  1523 D WifiService: New client listening to asynchronous messages
07-12 11:36:20.142  5748  5808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:20.143  5748  5808 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 11:36:20.146  5748  5808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:36:20.146  5748  5808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:36:20.146  5748  5808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:36:20.147  5748  5808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 11:36:20.149  5748  5808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 11:36:20.149  1031  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:20.149  5748  5808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-12 11:36:20.153  5748  5808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:20.153  5748  5808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:20.153  5748  5808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:20.153  5748  5808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:20.153  5748  5808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:20.153  5748  5808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:20.153  5748  5808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:20.153  5748  5808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:20.153  5748  5808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:20.153  5748  5808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:36:20.153  5748  5808 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:36:20.154  5748  5808 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 11:36:20.192  5748  5748 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:20.385  1797  4426 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,07-12 11:36:20.467  1797  4426 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,07-12 11:36:20.488   344   399 E GBMv2   : DFP En is all cleared set to be enabled
07-12 11:36:20.488   344   399 E GBMv2   : Set value is all cleared set the max
07-12 11:36:20.488   344   399 I GBMv2   : DFP Enabled. Ignore VFP set
,07-12 11:36:20.567  1797  4426 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,07-12 11:36:20.721  4862  5493 D AlertService: Beginning updateAlertNotification
,07-12 11:36:20.782  4862  5493 D AlertService: No fired or scheduled alerts
,07-12 11:36:20.794  4862  5493 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,07-12 11:36:20.815  4862  5493 D AlarmScheduler: No events found starting within 1 week.
,07-12 11:36:20.826  1031  1992 I ActivityManager: Killing 5085:com.lge.clock/u0a10 (adj 15): empty #17
,07-12 11:36:20.898  1031  1917 W libprocessgroup: failed to open /acct/uid_10010/pid_5085/cgroup.procs: No such file or directory
,07-12 11:36:21.176  5719  5719 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:21.176  5719  5719 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-12 11:36:21.242  5748  5811 W jxcore-log: Initializing JXcore engine
07-12 11:36:21.242  5748  5811 W jxcore-log: JXcore engine is ready
,07-12 11:36:21.311  5811  5811 W Thread-637: type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[7466]" dev="sockfs" ino=7466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-12 11:36:21.311  5811  5811 W Thread-637: type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-12 11:36:21.311  5811  5811 W Thread-637: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9451]" dev="sockfs" ino=9451 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-12 11:36:21.311  5811  5811 W Thread-637: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-12 11:36:21.311  5811  5811 W Thread-637: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[28024]" dev="sockfs" ino=28024 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,07-12 11:36:21.334  5748  5811 W jxcore-log: Starting JXcore engine
,07-12 11:36:21.415  5719  5719 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:36:21.454  1031  1629 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5830 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:21.532  5748  5811 W jxcore-log: Platform android
07-12 11:36:21.532  5748  5811 W jxcore-log: 
07-12 11:36:21.533  5748  5811 W jxcore-log: Process ARCH arm
07-12 11:36:21.533  5748  5811 W jxcore-log: 
,07-12 11:36:21.535  5830  5830 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
07-12 11:36:21.550  5830  5830 I LockScreenSettings: New app installed broadcast received ..
07-12 11:36:21.553  5830  5830 I LockScreenSettings: Number of installed packages  1
,07-12 11:36:21.611  1031  1698 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5847 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:21.613  1031  1698 I ActivityManager: Killing 4673:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
07-12 11:36:21.688  1031  1921 W libprocessgroup: failed to open /acct/uid_10085/pid_4673/cgroup.procs: No such file or directory
,07-12 11:36:21.724  5847  5847 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:21.964  5748  5811 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:36:21.964  5748  5811 I jxcore-log: 
07-12 11:36:21.965  5748  5811 W jxcore-log: JXcore engine is started
,07-12 11:36:21.975  5748  5808 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-12 11:36:21.981  5748  5748 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:36:22.374  1031  1917 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:36:22.433  1031  1901 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5881 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-12 11:36:22.513  5881  5881 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-12 11:36:22.513  5881  5881 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,07-12 11:36:22.518  4824  4824 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-12 11:36:22.534  1031  1921 I ActivityManager: Killing 5218:com.google.android.talk/u0a72 (adj 15): empty #17
,07-12 11:36:22.535   310  5900 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-12 11:36:22.536  1031  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-12 11:36:22.598  1031  1955 I art     : Explicit concurrent mark sweep GC freed 24692(1185KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.943ms total 126.113ms
,07-12 11:36:22.664  1031  1031 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver}
07-12 11:36:22.664  1031  1031 W BroadcastQueue: android.os.DeadObjectException
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.sendFinished(BroadcastReceiver.java:419)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.finish(BroadcastReceiver.java:395)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:973)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at com.android.server.SystemServer.run(SystemServer.java:288)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at com.android.server.SystemServer.main(SystemServer.java:189)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-12 11:36:22.664  1031  1031 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,07-12 11:36:22.664  1031  1031 W libprocessgroup: failed to open /acct/uid_10072/pid_5218/cgroup.procs: No such file or directory
07-12 11:36:22.713  1031  1031 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5901 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-12 11:36:22.715  1031  1920 W ActivityManager: Spurious death for ProcessRecord{3cf5060c 5901:com.google.android.talk/u0a72}, curProc for 5218: null
,07-12 11:36:22.788  5901  5901 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-12 11:36:22.901  5901  5901 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:22.901  5901  5901 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-12 11:36:23.034  5901  5931 I Babel   : MmsConfig: mnc/mcc: 0/0
07-12 11:36:23.034  5901  5931 I Babel   : MmsConfig.loadMmsSettings
,07-12 11:36:23.050  5901  5931 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-12 11:36:23.050  5901  5931 I Babel   : MmsConfig.loadFromDatabase
,07-12 11:36:23.069  5901  5931 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-12 11:36:23.069  5901  5931 I Babel   : MmsConfig.loadFromResources
07-12 11:36:23.071  5901  5931 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-12 11:36:23.072  5901  5931 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-12 11:36:23.103  5901  5901 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:36:23.108  5901  5929 W AudioCapabilities: Unsupported mime audio/evrc
07-12 11:36:23.112  5901  5929 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 11:36:23.114  5901  5929 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 11:36:23.128  2711  2711 D LIA_MrGDBLogger_MrGIntentReceiverDBCleaning: [dreamwood]onReceive
07-12 11:36:23.129  2711  2711 D LIA_MrGDBLogger_MrGDBCleaner: [dreamwood]onReceive
07-12 11:36:23.132  5901  5929 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-12 11:36:23.132  2711  5938 D LIA_MrGDBLogger_MrGDBManager: [dreamwood]dbFileSize : 57344
07-12 11:36:23.132  4584  4584 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
07-12 11:36:23.132  4584  4584 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
,07-12 11:36:23.135  2711  5938 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]cleanOldRecord : APP_USAGE
07-12 11:36:23.137  2711  5938 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]LimitedDate : 2016-06-12 11:36:23, count : 0
07-12 11:36:23.137  2711  5938 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]cleanOldRecord : CONCIERGE_BOARD
07-12 11:36:23.138  4584  4584 D CalendarProvider2: CalendarProviderIntentService.onCreate()
07-12 11:36:23.138  4584  5940 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
07-12 11:36:23.138  4584  5940 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
07-12 11:36:23.139  2711  5938 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]LimitedDate : 2016-06-12 11:36:23, count : 0
07-12 11:36:23.139  2711  5938 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]cleanOldRecord : INFORMANT_FEATURE_STATUS_INFO
07-12 11:36:23.140  2711  5938 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]LimitedDate : 2016-06-12 11:36:23, count : 0
07-12 11:36:23.140  2711  5938 D LIA_MrGDBLogger_MrGDBManager: [dreamwood]dbFileSize : 57344
07-12 11:36:23.141  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
07-12 11:36:23.141  5901  5929 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 11:36:23.146  5901  5929 W AudioCapabilities: Unsupported mime audio/evrc
,07-12 11:36:23.156  4584  5940 D CalendarProvider2: [IntentService] Release Lock
07-12 11:36:23.157  4584  4584 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
07-12 11:36:23.158  1031  1051 I ActivityManager: Killing 5176:com.google.android.gm/u0a64 (adj 15): empty #17
07-12 11:36:23.160  5901  5929 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-12 11:36:23.162  5901  5929 W VideoCapabilities: Unsupported mime video/divx
,07-12 11:36:23.163  5901  5929 W VideoCapabilities: Unsupported mime video/divx311
07-12 11:36:23.165  5901  5929 W VideoCapabilities: Unsupported mime video/divx4
07-12 11:36:23.169  5901  5929 W VideoCapabilities: Unsupported mime video/mp4v-esdp
07-12 11:36:23.181  5901  5929 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-12 11:36:23.183  5901  5929 W AudioCapabilities: Unsupported mime audio/eac3
,07-12 11:36:23.184  5901  5929 W AudioCapabilities: Unsupported mime audio/ac3
07-12 11:36:23.185  5901  5929 W AudioCapabilities: Unsupported mime audio/g726
07-12 11:36:23.185  5901  5929 W AudioCapabilities: Unsupported mime audio/wma-voice
07-12 11:36:23.186  5901  5929 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-12 11:36:23.188  5901  5929 W AudioCapabilities: Unsupported mime audio/adpcm
07-12 11:36:23.189  5901  5929 W VideoCapabilities: Unsupported mime video/theora
07-12 11:36:23.191  5901  5929 W VideoCapabilities: Unsupported mime video/mjpg
07-12 11:36:23.268  1031  1917 W libprocessgroup: failed to open /acct/uid_10064/pid_5176/cgroup.procs: No such file or directory
,07-12 11:36:25.319  5719  5719 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-12 11:36:25.326  1031  1972 I ActivityManager: Killing 4941:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-12 11:36:25.343  4914  4914 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,07-12 11:36:25.344  4914  4914 W System.err: android.os.DeadObjectException
07-12 11:36:25.344  4914  4914 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-12 11:36:25.344  4914  4914 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-12 11:36:25.344  4914  4914 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-12 11:36:25.344  4914  4914 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-12 11:36:25.344  4914  4914 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-12 11:36:25.344  4914  4914 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-12 11:36:25.344  4914  4914 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:25.344  4914  4914 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:25.344  4914  4914 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:25.346  4914  4914 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-12 11:36:25.346  4914  4914 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:25.347  4914  4914 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:25.347  4914  4914 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-12 11:36:25.347  4914  4914 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-12 11:36:25.347  4914  4914 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-12 11:36:25.347  4914  4914 W System.err: android.os.DeadObjectException
07-12 11:36:25.347  4914  4914 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-12 11:36:25.347  4914  4914 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-12 11:36:25.347  4914  4914 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-12 11:36:25.347  4914  4914 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-12 11:36:25.347  4914  4914 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-12 11:36:25.347  4914  4914 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-12 11:36:25.347  4914  4914 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:25.348  4914  4914 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:25.348  4914  4914 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:25.348  4914  4914 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-12 11:36:25.348  4914  4914 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:25.348  4914  4914 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:25.348  4914  4914 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-12 11:36:25.348  4914  4914 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-12 11:36:25.348  4914  4914 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-12 11:36:25.348  4914  4914 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-12 11:36:25.560  1031  1992 W libprocessgroup: failed to open /acct/uid_1000/pid_4941/cgroup.procs: No such file or directory
07-12 11:36:25.560  1031  1992 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-12 11:36:25.580  4914  4914 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-12 11:36:25.580  4914  4914 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,07-12 11:36:25.624  1031  1920 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=5960 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-12 11:36:25.627  4914  4914 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-12 11:36:25.714  5960  5960 D UEI.SmartControl: Quickset Services start...
07-12 11:36:25.716  5960  5960 I UEI.SmartControl: Manufacture = LGE
07-12 11:36:25.717  5960  5960 D UEI.SmartControl: Id = LGNevo
,07-12 11:36:25.718  5960  5960 D UEI.SmartControl: File observer start...
07-12 11:36:25.718  5960  5960 E UEI.SmartControl: IR Port is disabled: false
07-12 11:36:25.719  5960  5960 D UEI.SmartControl: Starting file observer...
07-12 11:36:25.719  5960  5960 D UEI.SmartControl: Extracting JNI libs...
07-12 11:36:25.719  5960  5960 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-12 11:36:25.804  5960  5960 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-12 11:36:25.804  5960  5960 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-12 11:36:25.804  5960  5960 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-12 11:36:25.841  5960  5960 I UEI.SmartControl: --- Selecting new region: 6
,07-12 11:36:25.844  5960  5960 I UEI.SmartControl: Model = LG-D855
,07-12 11:36:25.846  5960  5960 D UEI.SmartControl: QS Service created
07-12 11:36:25.863  5960  5960 I UEI.SmartControl: Service initServices...
,07-12 11:36:25.869  5960  5960 D UEI.SmartControl: QS start get config
,07-12 11:36:25.941  5960  5960 D UEI.SmartControl: Loading JNI Libs...
,07-12 11:36:26.331  5719  5822 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:36:26.368  1797  5514 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-12 11:36:26.372   310  6002 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-12 11:36:26.372  1031  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-12 11:36:26.373  1797  5514 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-12 11:36:26.374  1797  1797 I ConfigFetchService: fetch service done; releasing wakelock
07-12 11:36:26.375  1797  1797 I ConfigFetchService: stopping self
07-12 11:36:26.378  2054  2054 I ConfigService: onDestroy
07-12 11:36:26.403  5960  5960 I UEI.SmartControl: Supports setup maps: true
07-12 11:36:26.409  5960  5960 D UEI.SmartControl: QS start statue = true Error code = 0
07-12 11:36:26.409  5960  5960 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-12 11:36:26.409  5960  5960 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-12 11:36:26.409  5960  5960 I UEI.SmartControl: ### init IR Blaster...
,07-12 11:36:26.415  5960  5960 D serial_port: Configuring serial port
07-12 11:36:26.420  5960  5960 E UEI.SmartControl: UEIBLaster setting for 616
07-12 11:36:26.420  5960  5960 I UEI.SmartControl: Setting serial record hearder size = 2
07-12 11:36:26.421  5960  5960 I UEI.SmartControl: configuring settings for MAXQ616
07-12 11:36:26.421  5960  5960 I UEI.SmartControl: Get version...
07-12 11:36:26.438  5960  6008 D UEI.SmartControl: serial port data available: 21
,07-12 11:36:26.465  5960  5960 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-12 11:36:26.465  5960  5960 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-12 11:36:26.465  5960  5960 I UEI.SmartControl: QS saving settings...
,07-12 11:36:26.466  5960  5960 D UEI.SmartControl: IR Blaster version: 25672567
,07-12 11:36:26.484  5960  6008 D UEI.SmartControl: serial port data available: 4
,07-12 11:36:26.489   334   334 E ThermalEngine: out low battery limit. 
07-12 11:36:26.523  5960  5960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-12 11:36:26.525  5960  6012 I UEI.SmartControl: Device manager: loading config....
07-12 11:36:26.526  5960  6012 D UEI.SmartControl: ----------- loading internal config...
07-12 11:36:26.529  5960  5960 E UEI.SmartControl: Services init done
07-12 11:36:26.529  5960  5960 D UEI.SmartControl: QS Service init finished
07-12 11:36:26.537  5960  5960 D UEI.SmartControl: QS Service version name: 2.1.91
07-12 11:36:26.537  5960  5960 D UEI.SmartControl: QS Service version code: 201091
07-12 11:36:26.538  5960  5960 D UEI.SmartControl: Service requested: Control
,07-12 11:36:26.540  5960  6012 E UEI.SmartControl: Loading SETTINGS...
07-12 11:36:26.543  5960  5960 D UEI.SmartControl: Request IControl service: devices are loaded...
07-12 11:36:26.545  4914  4914 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-12 11:36:26.546  5960  5975 I UEI.SmartControl: ------ IControl API: 11
07-12 11:36:26.546  1031  1698 I ActivityManager: Killing 4914:com.lge.qremote/u0a112 (adj 15): empty #17
07-12 11:36:26.547  5960  5975 I UEI.SmartControl: Registering callback...
07-12 11:36:26.551  5960  6012 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-12 11:36:26.558  5960  6011 I UEI.SmartControl: Notify AllClients services are ready: 0
07-12 11:36:26.559  5960  6011 D UEI.SmartControl: -----service ready thread exits
07-12 11:36:26.628  1031  1901 W libprocessgroup: failed to open /acct/uid_10112/pid_4914/cgroup.procs: No such file or directory
07-12 11:36:26.629  5960  5960 D UEI.SmartControl: Internal service binding...
,07-12 11:36:27.479  1031  1554 I ActivityManager: Killing 4862:com.android.calendar/u0a13 (adj 15): empty #17
,07-12 11:36:27.618  1031  1698 W libprocessgroup: failed to open /acct/uid_10013/pid_4862/cgroup.procs: No such file or directory
,07-12 11:36:31.415  1031  1092 I ActivityManager: Waited long enough for: ServiceRecord{37c66871 u0 com.google.android.gms/.wearable.service.WearableService}
,07-12 11:36:31.522  5960  6013 D UEI.SmartControl: Internal timer expired: 1
07-12 11:36:31.522  5960  6013 D UEI.SmartControl: unbind internal service
,07-12 11:36:31.535  5960  5960 D UEI.SmartControl: Service.onUnbind: IControl
,07-12 11:36:31.538  5960  5960 D UEI.SmartControl: Service.onDestroy
07-12 11:36:31.538  5960  5960 D UEI.SmartControl: Lock is in USE false
07-12 11:36:31.538  5960  5960 D UEI.SmartControl: unbind internal service
07-12 11:36:31.538  5960  5960 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1c7e88b2
07-12 11:36:31.538  5960  5960 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-12 11:36:31.538  5960  5960 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-12 11:36:31.538  5960  5960 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-12 11:36:31.538  5960  5960 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-12 11:36:31.539  5960  5960 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-12 11:36:31.539  5960  5960 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-12 11:36:31.539  5960  5960 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-12 11:36:31.539  5960  5960 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-12 11:36:31.539  5960  5960 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:31.539  5960  5960 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:31.539  5960  5960 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-12 11:36:31.539  5960  5960 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:31.539  5960  5960 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:31.539  5960  5960 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-12 11:36:31.539  5960  5960 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-12 11:36:31.539  5960  5960 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1c7e88b2
,07-12 11:36:31.541  5960  5960 D serial_port: close(fd = 25)
07-12 11:36:31.579  5960  5960 I UEI.SmartControl: Serial port is closed.
07-12 11:36:31.579  5960  5960 I UEI.SmartControl: Serial port is closed.
,07-12 11:36:31.584  5960  5960 D UEI.SmartControl: Blaster closed
07-12 11:36:31.584  5960  5960 D UEI.SmartControl: Shut down QS...
07-12 11:36:31.584  5960  5960 D UEI.SmartControl: Stopping QS lib
07-12 11:36:31.597  5960  5960 D UEI.SmartControl: QS lib stop result = true
07-12 11:36:31.597  5960  5960 D UEI.SmartControl: Stopped QS lib
,07-12 11:36:31.599  5960  5960 D UEI.SmartControl: Stopped file observer...
,07-12 11:36:31.599  5960  5960 D UEI.SmartControl: QS shutdown complete
,07-12 11:36:33.908   307   307 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,07-12 11:36:33.908   307   307 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
,07-12 11:36:33.909   307   307 I rmt_storage: wakelock acquired: 1, error no: 42
,07-12 11:36:33.909   307   907 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,07-12 11:36:34.023   307   907 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
07-12 11:36:34.023   307   907 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
07-12 11:36:34.023   307   907 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
07-12 11:36:34.023   307   907 I rmt_storage: 
,07-12 11:36:34.026   307   307 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,07-12 11:36:34.027   897   905 E Diag_Lib: [IMS_FATAL]| 3347 | 905 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,07-12 11:36:34.842  5748  5811 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:36:34.842  5748  5811 I jxcore-log: 
07-12 11:36:34.844  5748  5811 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:36:34.844  5748  5811 I jxcore-log: 
,07-12 11:36:34.847  5748  5811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:34.847  5748  5811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:34.847  5748  5811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:34.847  5748  5811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:34.847  5748  5811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:34.847  5748  5811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:34.847  5748  5811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:34.847  5748  5811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:34.847  5748  5811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:34.847  5748  5811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:34.847  5748  5811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:36:34.849  5748  5811 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:36:34.849  5748  5811 I jxcore-log: 
07-12 11:36:34.851  5748  5811 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 11:36:34.851  5748  5811 I jxcore-log: 
,07-12 11:36:35.186  5748  5811 I jxcore-log: Unit Test app is loaded
07-12 11:36:35.186  5748  5811 I jxcore-log: 
,07-12 11:36:35.191  5748  5811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:36:35.191  5748  5811 I jxcore-log: 
07-12 11:36:35.199  1031  1051 D WifiServiceImplEx: setWifiEnabled: true pid=5748, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-12 11:36:35.201  1031  1051 D WifiService: setWifiEnabled: true pid=5748, uid=10118
07-12 11:36:35.201  1031  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 11:36:35.204  5748  5748 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 11:36:35.226  1031  1051 D WifiServiceImplEx: disconnect pid=5748, uid=10118, packageName=com.test.thalitest
07-12 11:36:35.227  1031  1554 D WifiServiceImplEx: reconnect pid=5748, uid=10118, packageName=com.test.thalitest
07-12 11:36:35.228  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-12 11:36:35.228  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-12 11:36:35.229  1031  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:35.229  1031  1031 D Ulp_jni : JNI:system_update. Event-4
07-12 11:36:35.229  1031  1517 E WifiStateMachine:  InitialState CMD_DISCONNECT 0 0
07-12 11:36:35.230  1031  1517 E WifiStateMachine:  DefaultState CMD_DISCONNECT 0 0
07-12 11:36:35.230  1031  1517 E WifiStateMachine:  InitialState CMD_RECONNECT 0 0
07-12 11:36:35.230  1031  1517 E WifiStateMachine:  DefaultState CMD_RECONNECT 0 0
07-12 11:36:35.230  1031  1517 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-12 11:36:35.230  1031  1517 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-12 11:36:35.231  1031  1051 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-12 11:36:35.232  1031  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-12 11:36:35.232  1031  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-12 11:36:35.233  1031  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-12 11:36:35.233  1031  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-12 11:36:35.233  1031  1517 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-12 11:36:35.233  1031  1517 E WifiHW  : unknown target_country: EU , set to default
07-12 11:36:35.233  1031  1517 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-12 11:36:35.233  1031  1517 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-12 11:36:35.233  1031  1517 I WifiUtil: gEnableBmps=1
,07-12 11:36:35.249  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-12 11:36:35.249  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-12 11:36:35.250  1031  1031 D Ulp_jni : JNI:system_update. Event-4
07-12 11:36:35.250  1031  1111 D BluetoothManagerService: Message: 1
07-12 11:36:35.251  1031  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-12 11:36:35.258  5748  5811 I jxcore-log: My device name is: LGE-LG-D855
07-12 11:36:35.258  5748  5811 I jxcore-log: 
07-12 11:36:35.260  5748  5811 I jxcore-log: WARN testUtils: myNameCallback not set!
07-12 11:36:35.260  5748  5811 I jxcore-log: 
,07-12 11:36:35.306  1031  1111 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6046 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-12 11:36:35.366  6046  6046 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-12 11:36:35.366  6046  6046 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-12 11:36:35.367  6046  6046 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-12 11:36:35.367  6046  6046 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-12 11:36:35.419  1031  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-12 11:36:35.424  1031  1111 D Tethering: InitialState.processMessage what=4
07-12 11:36:35.425   310   883 D SoftapController: Softap fwReload - Ok
07-12 11:36:35.427   310  6069 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-12 11:36:35.429   310   883 D CommandListener: Setting iface cfg
07-12 11:36:35.430   310   883 D CommandListener: Trying to bring down wlan0
07-12 11:36:35.430   310   883 D CommandListener: Clearing all IP addresses on wlan0
07-12 11:36:35.431  1031  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-12 11:36:35.432  6046  6046 D BluetoothAdapterApp: Loading JNI Library
,07-12 11:36:35.449  1031  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6071 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-12 11:36:35.450  1031  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-12 11:36:35.458  1031  1517 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-12 11:36:35.461  1031  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-12 11:36:35.461  1031  1517 E WifiStateMachine: useWiFiOffloading() : false
07-12 11:36:35.461  1031  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-12 11:36:35.465  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,07-12 11:36:35.467  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:35.468  1031  1517 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-12 11:36:35.469  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-12 11:36:35.470  5748  5748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:36:35.473  1031  1517 D WifiMonitor: connecting to supplicant
,07-12 11:36:35.501  6081  6081 W wpa_supplicant: type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:35.501  6081  6081 W wpa_supplicant: type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:35.529  6081  6081 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 11:36:35.532  6046  6046 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@246a4f7c Instance Count = 1
07-12 11:36:35.545  6081  6081 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-12 11:36:35.545  6081  6081 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-12 11:36:35.557  6046  6046 D BluetoothAdapterApp: onCreate
,07-12 11:36:35.577  6046  6046 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-12 11:36:35.578  6046  6046 D ProfileConfigQcom: Adding HeadsetService
07-12 11:36:35.578  6046  6046 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-12 11:36:35.578  6046  6046 D ProfileConfigQcom: Adding A2dpService
07-12 11:36:35.578  6046  6046 D ProfileConfigQcom: [BTUI] HidService is supported
07-12 11:36:35.578  6046  6046 D ProfileConfigQcom: Adding HidService
,07-12 11:36:35.578  6046  6046 D ProfileConfigQcom: [BTUI] HealthService is supported
,07-12 11:36:35.578  6046  6046 D ProfileConfigQcom: Adding HealthService
07-12 11:36:35.578  6046  6046 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-12 11:36:35.579  6046  6046 D ProfileConfigQcom: [BTUI] PanService is supported
07-12 11:36:35.579  6046  6046 D ProfileConfigQcom: Adding PanService
07-12 11:36:35.579  6046  6046 D ProfileConfigQcom: [BTUI] GattService is supported
07-12 11:36:35.580  6046  6046 D ProfileConfigQcom: Adding GattService
07-12 11:36:35.580  6046  6046 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-12 11:36:35.580  6046  6046 D ProfileConfigQcom: Adding BluetoothMapService
07-12 11:36:35.580  6046  6046 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-12 11:36:35.594  6071  6071 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:36:35.594  6071  6071 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-12 11:36:35.595  6071  6071 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-12 11:36:35.595  6071  6071 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-12 11:36:35.596  6071  6071 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-12 11:36:35.597  6071  6071 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-12 11:36:35.598  1031  1111 D BluetoothManagerService: Message: 20
07-12 11:36:35.598  1031  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24155d0e:true
07-12 11:36:35.598  6046  6046 D BluetoothAdapterState: make
07-12 11:36:35.602  6046  6046 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-12 11:36:35.603  6046  6095 I BluetoothAdapterState: Entering OffState
07-12 11:36:35.603  6046  6046 I bluedroid-qcom: init
07-12 11:36:35.605  6046  6046 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-12 11:36:35.606  6046  6046 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-12 11:36:35.606  6046  6046 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-12 11:36:35.606  6046  6046 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 11:36:35.606  6046  6046 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-12 11:36:35.606  6046  6046 I bluedroid-qcom: get_profile_interface socket
07-12 11:36:35.606  6046  6046 I bluedroid-qcom: get_profile_interface map_client
07-12 11:36:35.607  6046  6098 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-12 11:36:35.609  6046  6098 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-12 11:36:35.610  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-12 11:36:35.610  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,07-12 11:36:35.611  6081  6081 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-12 11:36:35.615  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-12 11:36:35.615  1031  1111 D BluetoothManagerService: Message: 40
07-12 11:36:35.615  1031  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-12 11:36:35.601  6099  6099 W bdaddr_loader: type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:35.601  6099  6099 W bdaddr_loader: type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:35.617  6099  6099 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-12 11:36:35.617  6099  6099 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-12 11:36:35.617  6099  6099 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-12 11:36:35.618  6099  6099 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-12 11:36:35.618  6046  6067 I bluedroid-qcom: config_hci_snoop_log
07-12 11:36:35.619  1031  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-12 11:36:35.619  1031  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
07-12 11:36:35.621  6046  6098 D BluetoothAdapterProperties: Name is: G3
07-12 11:36:35.625  6099  6099 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-12 11:36:35.625  6099  6099 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,07-12 11:36:35.627  6046  6066 V LGMDMManagerInternal: Create singleton instance
07-12 11:36:35.682  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-12 11:36:35.683  6071  6071 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-12 11:36:35.683  6071  6071 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-12 11:36:35.683  6071  6071 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-12 11:36:35.683  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-12 11:36:35.689  6081  6081 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-12 11:36:35.690  6046  6095 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-12 11:36:35.690  6046  6095 D BluetoothAdapterProperties: Setting state to 11
07-12 11:36:35.691  6046  6095 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-12 11:36:35.691  1031  1111 D BluetoothManagerService: Message: 60
07-12 11:36:35.691  1031  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-12 11:36:35.691  1031  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-12 11:36:35.692  6081  6081 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-12 11:36:35.692  6081  6081 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-12 11:36:35.692  6046  6095 I LGBluetoothServiceJni: classInitNative: succeeds
07-12 11:36:35.696  6071  6071 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-12 11:36:35.696  1031  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-12 11:36:35.696  1031  1517 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-12 11:36:35.696  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-12 11:36:35.696  1031  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-12 11:36:35.697  1031  1517 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-12 11:36:35.697  1031  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:35.697  1031  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:35.697  1031  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:35.698  1031  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:35.698  1031  1517 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-12 11:36:35.698  1031  1517 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-12 11:36:35.698  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-12 11:36:35.699  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:36:35.699  1031  1517 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-12 11:36:35.699  1031  1517 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-12 11:36:35.699  1031  1517 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-12 11:36:35.699  1031  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-12 11:36:35.699  1031  1517 E WifiStateMachine: useWiFiOffloading() : false
07-12 11:36:35.699  1031  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-12 11:36:35.700  1031  1517 D WifiNative-wlan0: doBoolean: SET update_config 1
07-12 11:36:35.700  1031  1517 D WifiNative-wlan0: SET update_config 1: returned true
07-12 11:36:35.700  1031  1517 D WifiConfigStore: Loading config and enabling all networks 
07-12 11:36:35.700  1031  1517 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-12 11:36:35.701  1031  1517 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-12 11:36:35.702  1922  1922 D WfdService: Waiting for WifiP2p enabling
07-12 11:36:35.702  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:35.702  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:35.703  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-12 11:36:35.703  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-12 11:36:35.703  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-12 11:36:35.703  6071  6071 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-12 11:36:35.703  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-12 11:36:35.705  6071  6071 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-12 11:36:35.705  6046  6095 D BluetoothBondStateMachine: make
07-12 11:36:35.706  1031  1917 I ActivityManager: Killing 5518:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-12 11:36:35.708  6046  6095 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:35.708  6046  6095 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-12 11:36:35.708  6046  6095 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:35.708  6046  6095 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-12 11:36:35.709  6046  6095 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-12 11:36:35.709  5748  5748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:35.709  5748  5748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:35.709  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:35.709  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:35.709  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:35.709  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:35.709  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:35.709  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:35.709  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:35.709  5748  5748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the che,ck when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:35.709  5748  5748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:36:35.710  6046  6103 I BluetoothBondStateMachine: StableState(): Entering Off State
07-12 11:36:35.710  1031  1522 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-12 11:36:35.711  1031  6102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-12 11:36:35.711  1031  6102 D WifiMonitor: Dropping event because (p2p0) is stopped
07-12 11:36:35.711  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-12 11:36:35.711  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-12 11:36:35.711  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-12 11:36:35.711  1031  1517 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-12 11:36:35.714  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-12 11:36:35.716  1031  1517 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-12 11:36:35.716  6046  6095 E BluetoothAdapterService: File transfer profiles supported!!
07-12 11:36:35.717  1031  1517 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-12 11:36:35.739  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:36:35.829  6046  6046 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-12 11:36:35.831  6046  6046 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:35.831  6046  6046 V BluetoothPbapReceiver: ***********state = 11
,07-12 11:36:35.836  1031  1955 W libprocessgroup: failed to open /acct/uid_10008/pid_5518/cgroup.procs: No such file or directory
07-12 11:36:35.842  1031  1517 D WifiStateMachine: enableVerboseLogging : level 2
07-12 11:36:35.843  1031  1517 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-12 11:36:35.844  1031  1031 D BluetoothHeadset: Proxy object connected
,07-12 11:36:35.845  6046  6046 D HeadsetService: Received start request. Starting profile...
07-12 11:36:35.846  6046  6046 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-12 11:36:35.844  1031  1517 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-12 11:36:35.846  1031  1517 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-12 11:36:35.846  6046  6046 D LGBluetoothHfpAdapter: Version 1.6
07-12 11:36:35.847  1031  1517 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-12 11:36:35.847  1031  1517 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-12 11:36:35.847  6046  6095 E BluetoothAdapterService: File transfer profiles supported!!
,07-12 11:36:35.848  1031  1517 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-12 11:36:35.848  1031  1517 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-12 11:36:35.848  1832  1832 D BluetoothHeadset: Proxy object connected
07-12 11:36:35.848  1031  1517 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-12 11:36:35.848  1031  1517 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,07-12 11:36:35.849  1031  1517 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
,07-12 11:36:35.849  1031  1517 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,07-12 11:36:35.849  1832  1832 D BluetoothHeadset: Proxy object connected
,07-12 11:36:35.849  1832  1832 D BluetoothHeadset: Proxy object connected
07-12 11:36:35.849  1031  1517 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true,
07-12 11:36:35.849  1031  1517 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5,
,07-12 11:36:35.849  1031  1517 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true,
07-12 11:36:35.850  1922  1922 D WfdsService: Supplicant Connection state is changed : true
07-12 11:36:35.850  1922  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-12 11:36:35.850  1922  2260 D WfdsService: Set the WFDS Monitor: true
07-12 11:36:35.851  1922  2260 D WfdsMonitor: WfdsMonitorThread create,
07-12 11:36:35.851  1922  2260 D WfdsMonitor: WFDS Monitor is created and started
07-12 11:36:35.851  1922  2260 D WfdsService: WiFi: Supplicant connection re-established
07-12 11:36:35.852  1031  1517 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:36:35.852  1031  1517 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,07-12 11:36:35.854  5901  5901 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:35.854  1031  1517 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-12 11:36:35.854  1031  1517 D WifiNative-HAL: Setting external_sim to 1
07-12 11:36:35.855  1031  1517 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-12 11:36:35.855  1031  1517 D WifiNative-wlan0: SET external_sim 1: returned true,
07-12 11:36:35.855  1031  1517 I WifiNative-HAL: startHal
07-12 11:36:35.855  1031  1517 E wifi    : getStaticLongField sWifiHalHandle 0x9879a8dc
07-12 11:36:35.855  1031  1517 E WifiHAL : Could not connect handle
07-12 11:36:35.855  1031  1517 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401f0a
,07-12 11:36:35.855  1031  1517 I WifiNative-HAL: Could not start hal
07-12 11:36:35.855  1031  1517 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:36:35.855  1031  1517 I WifiNative-HAL: startHal
07-12 11:36:35.855  1031  1517 E wifi    : getStaticLongField sWifiHalHandle 0x9879a85c
,07-12 11:36:35.856  1031  1517 E WifiHAL : Could not connect handle
07-12 11:36:35.856  1031  1517 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301f06
07-12 11:36:35.856  1031  1517 I WifiNative-HAL: Could not start hal
07-12 11:36:35.856  1031  1517 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,07-12 11:36:35.857  1922  6105 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-12 11:36:35.857  1922  6105 E CtrlSupplicant: Succeed to open control connection
07-12 11:36:35.858  1922  6105 E CtrlSupplicant: Succeed to open monitor connection
07-12 11:36:35.858  1031  1517 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-12 11:36:35.858  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,07-12 11:36:35.858  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-12 11:36:35.859  6046  6046 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-12 11:36:35.859  1031  1517 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-12 11:36:35.860  6046  6095 E BluetoothAdapterService: File transfer profiles supported!!
07-12 11:36:35.862  6046  6046 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 11:36:35.863  6046  6046 D HeadsetStateMachine: make
07-12 11:36:35.863  2054  2054 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 11:36:35.864  1922  6105 D WfdsMonitor: Supplicant connection established
07-12 11:36:35.865  1922  2260 D WfdsService: Connected to the supplicant for wfds
,07-12 11:36:35.873  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
07-12 11:36:35.873  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:35.875  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-12 11:36:35.876  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-12 11:36:35.877  1031  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-12 11:36:35.877  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3,
07-12 11:36:35.877  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-12 11:36:35.879  1031  1031 D WifiHS20: hidePasspointNotification off =false
07-12 11:36:35.881  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:35.881  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
07-12 11:36:35.881  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-12 11:36:35.882  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:36:35.887  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-12 11:36:35.887  6071  6071 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-12 11:36:35.887  6071  6071 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-12 11:36:35.887  6071  6071 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-12 11:36:35.888  1031  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-12 11:36:35.888  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-12 11:36:35.888  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-12 11:36:35.892  1031  1523 D WifiService: New client listening to asynchronous messages
07-12 11:36:35.892  1031  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-12 11:36:35.893  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-12 11:36:35.893  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-12 11:36:35.893  1031  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-12 11:36:35.893  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-12 11:36:35.893  6081  6081 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-12 11:36:35.893  1031  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-12 11:36:35.893  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-12 11:36:35.894  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-12 11:36:35.894  1031  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-12 11:36:35.895  1031  1517 E WifiNative: : [102,253,346 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-12 11:36:35.895  1031  1517 D WifiNative-wlan0: doBoolean: RECONNECT
07-12 11:36:35.896  1031  1517 D WifiNative-wlan0: RECONNECT: returned true
07-12 11:36:35.896  1031  1517 D WifiNative-wlan0: doString: [STATUS]
07-12 11:36:35.896  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-12 11:36:35.897  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-12 11:36:35.898  1031  1517 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-12 11:36:35.898  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-12 11:36:35.898  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-12 11:36:35.899  1031  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-12 11:36:35.899  1031  1517 D WifiNative-wlan0: doBoolean: SET ps 1
07-12 11:36:35.899  1031  1517 D WifiNative-wlan0: SET ps 1: returned true
07-12 11:36:35.900  1031  1516 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:35.901   310   883 D CommandListener: Setting iface cfg
07-12 11:36:35.901   310   883 D CommandListener: Trying to bring up p2p0
,07-12 11:36:35.901  1031  1516 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-12 11:36:35.901  1031  1516 D LGWifiP2pService: P2pEnablingState
07-12 11:36:35.901  1031  1516 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:35.901  1031  1516 D LGWifiP2pService: P2p socket connection successful
07-12 11:36:35.901  1031  1516 D LGWifiP2pService: P2pEnabledState
07-12 11:36:35.907  6046  6046 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:35.907  6046  6046 D LgDataFeature: LgDataFeature() Constructor Done, null
07-12 11:36:35.913  1031  1698 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6108 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:35.915  1031  1517 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-12 11:36:35.916  1031  1517 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-12 11:36:35.916  1031  1517 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-12 11:36:35.917  1031  1517 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-12 11:36:35.917  1031  1517 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-12 11:36:35.917  6046  6046 D HeadsetStateMachine: max_hf_connections = 1
07-12 11:36:35.918  6046  6046 I bluedroid-qcom: get_profile_interface handsfree
07-12 11:36:35.919  1031  1517 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-12 11:36:35.919  1031  1517 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-12 11:36:35.919  1031  1517 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-12 11:36:35.920  6081  6081 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-12 11:36:35.920  6046  6046 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-12 11:36:35.920  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-12 11:36:35.920   315  1362 V AudioPolicyService: registerClient() client 0xb558a960, uid 1002
07-12 11:36:35.920  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
07-12 11:36:35.921  1031  1031 D RttService: SCAN_AVAILABLE : 3
07-12 11:36:35.921  1031  1535 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:35.921  1031  1535 I WifiNative-HAL: startHal
07-12 11:36:35.921  1031  1535 E wifi    : getStaticLongField sWifiHalHandle 0x94b8799c
07-12 11:36:35.921  1031  1535 E WifiHAL : Could not connect handle
07-12 11:36:35.921  1031  1535 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501c46
07-12 11:36:35.921  1031  1535 I WifiNative-HAL: Could not start hal
07-12 11:36:35.921  1031  1535 E WifiScanningService: could not start HAL
07-12 11:36:35.921  1031  1536 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:35.921   315  1766 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-12 11:36:35.921   315  1766 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-12 11:36:35.921  1031  1516 D LGWifiP2pService: sending p2p connection changed broadcast
07-12 11:36:35.921   315  1766 V AudioPolicyManagerEx: getOutput() returns output 2
07-12 11:36:35.921  6046  6046 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-12 11:36:35.922  1031  1517 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-12 11:36:35.922  1031  1517 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-12 11:36:35.922   315  1363 V AudioFlinger: registerClient() client 0xb55815c8, pid 6046
07-12 11:36:35.922  1031  1517 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-12 11:36:35.922  1031  1517 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-12 11:36:35.922  6081  6081 E wpa_supplicant: disconnect_rssi_lvl: -100
07-12 11:36:35.923   315  1357 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:35.923   315  1357 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:35.923  1922  1922 D WfdsService: WifiP2pState is changed : true
,07-12 11:36:35.923  1031  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:35.923  1031  1052 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:35.923  1031  1516 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-12 11:36:35.924  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-12 11:36:35.924  1922  2260 D WfdsService: Receive the WFDS_ENABLE Method
07-12 11:36:35.924  1922  2260 D WfdsService: Set the WFDS Monitor: true
07-12 11:36:35.924  1031  1517 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
07-12 11:36:35.924  1922  2260 D WfdsService: Connected to the supplicant for wfds
07-12 11:36:35.924  1922  2260 D WfdsJNI : doCommand: WFDS_SET TRUE
07-12 11:36:35.924  6081  6081 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-12 11:36:35.924  1031  1517 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
07-12 11:36:35.924  1031  1517 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
07-12 11:36:35.924  6046  6067 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,07-12 11:36:35.924  6046  6067 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-12 11:36:35.925  1922  2260 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
07-12 11:36:35.925  3112  3128 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:35.925  3112  3128 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:35.925  6081  6081 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
07-12 11:36:35.925  1832  4014 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:35.925  1832  4014 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:35.925  1031  1516 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-12 11:36:35.925  1031  1516 D WifiNative-p2p0: doBoolean: SET device_name G3
,07-12 11:36:35.925  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-12 11:36:35.925  2127  4104 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:35.925  6046  6095 E BluetoothAdapterService: File transfer profiles supported!!
,07-12 11:36:35.925  2127  4104 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:35.925  1581  1599 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:35.925  1581  1599 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:35.925   315  1358 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:35.925   315  1358 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:35.926  1031  1921 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:35.926  1031  1921 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:35.926  1581  3132 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:35.926  1581  3132 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:35.926  1832  2432 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:35.926  1832  2432 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:35.926  2127  2159 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:35.926  2127  2159 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:35.926  3112  3127 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:35.926  3112  3127 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:35.926  6046  6104 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:35.926  6046  6104 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-12 11:36:35.926  6046  6046 V ToneGenerator: Create Track: 0xb4928080
07-12 11:36:35.926  6046  6046 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-12 11:36:35.926  6046  6046 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-12 11:36:35.926   315  1765 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-12 11:36:35.926   315  1765 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-12 11:36:35.926   315  1765 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-12 11:36:35.926   315  1765 V AudioPolicyManagerEx: getOutput() returns output 2
07-12 11:36:35.927   315  1362 I AudioFlinger: isAudioPlaybackHookOn() false
07-12 11:36:35.931  6071  6071 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-12 11:36:35.931   315  1362 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-12 11:36:35.931   315  1362 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-12 11:36:35.931   315  1362 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-12 11:36:35.931   315  1362 V AudioPolicyManagerEx: getOutput() returns output 2
07-12 11:36:35.931  6046  6046 V AudioSystem: getLatency() output 2, latency 50
07-12 11:36:35.931  6046  6046 V AudioSystem: getFrameCount() output 2, frameCount 960
07-12 11:36:35.931  6046  6046 V AudioTrack: createTrack_l() output 2 afLatency 50
07-12 11:36:35.932   315  1766 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-12 11:36:35.932   315  1766 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-12 11:36:35.932   315  1766 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-12 11:36:35.932   315  1766 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-12 11:36:35.932   315  1766 V AudioFlinger: createTrack() lSessionId: 21
07-12 11:36:35.932  6046  6095 E BluetoothAdapterService: File transfer profiles supported!!
07-12 11:36:35.933  6046  6046 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-12 11:36:35.933   315  1363 V AudioFlinger: acquiring 21 from 6046, for 6046
0,7-12 11:36:35.933   315  1363 V AudioFlinger:  added new entry for 21
07-12 11:36:35.933  6046  6046 V ToneGenerator: ToneGenerator INIT OK, time: 102307
07-12 11:36:35.933  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:35.934  6046  6106 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-12 11:36:35.935  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:35.935  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-12 11:36:35.935  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-12 11:36:35.935  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-12 11:36:35.935  6071  6071 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-12 11:36:35.935  6071  6071 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-12 11:36:35.937  6046  6106 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-12 11:36:35.937  6046  6106 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-12 11:36:35.937  6046  6106 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-12 11:36:35.937   315  1765 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6046
07-12 11:36:35.937  1922  2260 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
07-12 11:36:35.937   315  1765 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-12 11:36:35.937   315  1765 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-12 11:36:35.937   315  1765 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-12 11:36:35.937  1922  2260 D WfdsService: selectPreferredScanChannel [36]
07-12 11:36:35.937   315  1765 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-12 11:36:35.937   315  1765 V voice   : voice_set_parameters: exit with code(0)
07-12 11:36:35.938   315  1765 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-12 11:36:35.938  1922  2260 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-12 11:36:35.938   315  1765 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-12 11:36:35.938   315  1765 V msm8974_platform: platform_set_parameters: exit with code(0)
07-12 11:36:35.938   315  1765 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-12 11:36:35.938   315  1765 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-12 11:36:35.938   315  1765 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-12 11:36:35.938  1031  1516 D WifiNative-p2p0: SET device_name G3: returned true
07-12 11:36:35.938  1031  1516 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-12 11:36:35.938  1031  1516 D LGWifiP2pService: before postfix = G3
07-12 11:36:35.938  1031  1516 D WifiServerServiceExt: postfix byte check : 2
07-12 11:36:35.938  1031  1516 D LGWifiP2pService: after postfix = G3
07-12 11:36:35.938  1031  1516 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-12 11:36:35.939  6046  6106 V ToneGenerator: ToneGenerator destructor
07-12 11:36:35.939  6046  6106 V ToneGenerator: stopTone
07-12 11:36:35.939  6046  6106 V ToneGenerator: Delete Track: 0xb4928080
07-12 11:36:35.939  1031  1516 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-12 11:36:35.939  1031  1516 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-12 11:36:35.939  1031  1516 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-12 11:36:35.940  1031  1516 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-12 11:36:35.940  1031  1516 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-12 11:36:35.940  1031  1516 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-12 11:36:35.940  1031  1516 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-12 11:36:35.940  1031  1516 D WifiNative-HAL: p2pGetDeviceAddress
07-12 11:36:35.941  1031  1516 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-12 11:36:35.942  1922  1922 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-12 11:36:35.943  6046  6106 V AudioTrack: ~AudioTrack, releasing session id from 6046 on behalf of 6046
07-12 11:36:35.943   315   315 V AudioFlinger: releasing 21 from 6046 for 6046
07-12 11:36:35.943   315   315 V AudioFlinger:  decremented refcount to 0
07-12 11:36:35.943   315   315 V AudioFlinger: purging stale effects
07-12 11:36:35.943   315   315 V AudioPolicyService: AudioCommandThread() adding release output 2
07-12 11:36:35.943   315   315 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-12 11:36:35.944   315  1260 V AudioPolicyService: AudioCommandThread() waking up
07-12 11:36:35.944   315  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
07-12 11:36:35.944   315  1260 V AudioPolicyManager: releaseOutput() 2
07-12 11:36:35.944   315  1260 V AudioPolicyService: AudioCommandThread() going to sleep
07-12 11:36:35.944   315   315 V AudioFlinger: PlaybackThread::Track destructor
07-12 11:36:35.944   315   315 V AudioFlinger: removeClient_l() pid 6046, calling pid 315
07-12 11:36:35.946  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-12 11:36:35.946  6081  6081 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-12 11:36:35.947  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-12 11:36:35.947  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-12 11:36:35.947  6081  6081 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-12 11:36:35.947  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-12 11:36:35.947  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-12 11:36:35.947  6081  6081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:35.947  1031  1517 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-12 11:36:35.947  6081  6081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:35.947  1031  1517 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-12 11:36:35.948  1031  1517 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-12 11:36:35.948  1922  1922 D WfdsService: isConnected: false
07-12 11:36:35.948  1031  1517 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-12 11:36:35.948  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-12 11:36:35.948  1922  6105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-12 11:36:35.948  1922  6105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-12 11:36:35.948  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-12 11:36:35.949  6081  6081 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-12 11:36:35.949  6046  6095 E BluetoothAdapterService: File transfer profiles supported!!
07-12 11:36:35.949  1031  6102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-12 11:36:35.949  1031  6102 E WifiMonitor: WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:35.949  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:35.949  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:35.949  1031  6102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-12 11:36:35.949  1031  6102 E WifiMonitor: WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:35.949  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:35.949  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:35.949  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-12 11:36:35.949  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-12 11:36:35.950  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-12 11:36:35.950  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-12 11:36:35.950  1031  1517 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-12 11:36:35.950  1031  1517 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-12 11:36:35.950  1031  1517 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-12 11:36:35.950  1031  1517 D WifiNative-wlan0: doBoolean: SCAN
07-12 11:36:35.951  1031  1517 D WifiNative-wlan0: SCAN: returned false
07-12 11:36:35.951  1031  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=102310  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-12 11:36:35.952  2754  2754 I MusicWidget: mDelayedStopHandler : unbind
07-12 11:36:35.977  1031  1992 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6126 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-12 11:36:35.977  6046  6046 D A2dpService: Received start request. Starting profile...
07-12 11:36:35.977  1031  1516 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-12 11:36:35.977  1031  1516 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-12 11:36:35.978  6046  6046 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 11:36:35.978  1031  1516 D WifiNative-p2p0: P2P_FLUSH: returned true
07-12 11:36:35.978  1031  1516 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-12 11:36:35.978  1031  1516 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-12 11:36:35.978  6046  6046 V Avrcp   : make
07-12 11:36:35.978  1031  1516 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-12 11:36:35.979  6046  6046 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-12 11:36:35.979  6046  6046 I bluedroid-qcom: get_profile_interface avrcp
07-12 11:36:35.979  1031  1516 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-12 11:36:35.979  1031  1516 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-12 11:36:35.979  1031  1031 D BluetoothA2dp: Proxy object connected
07-12 11:36:35.981  1031  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=102340  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-12 11:36:35.983  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
07-12 11:36:35.983  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
07-12 11:36:35.983  6046  6095 E BluetoothAdapterService: File transfer profiles supported!!
07-12 11:36:35.983  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
07-12 11:36:35.985  1031  1517 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-12 11:36:35.985  1031  1517 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-12 11:36:35.986  1031  1517 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-12 11:36:35.986  1031  1516 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-12 11:36:35.987  1031  1516 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-12 11:36:35.987  1031  1517 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-12 11:36:35.987  1031  1517 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-12 11:36:35.989   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 236us total 12.563ms
07-12 11:36:35.996  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:35.996  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:35.996  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-12 11:36:36.000   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 230us total 10.719ms
07-12 11:36:36.002  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.002  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:36.003  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:36.005  1922  1922 I WfdStateTracker: handleP2pThisDeviceChanged
07-12 11:36:36.005  1922  1922 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-12 11:36:36.005  1922  1922 D WfdsService: Update P2p Interface State: 3
07-12 11:36:36.011   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 10.147ms
07-12 11:36:36.011  6046  6046 V AudioManager: registerRemoteController: size of Media player list: 0
,07-12 11:36:36.012  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:36.013  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
07-12 11:36:36.013  1031  1516 D LGWifiP2pService: InactiveState
07-12 11:36:36.013  1031  1516 D LGWifiP2pService: InactiveState{ when=-66ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,07-12 11:36:36.013  1031  1516 D LGWifiP2pService: P2pEnabledState{ when=-67ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.013  1031  1516 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-12 11:36:36.014  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-12 11:36:36.014  6081  6081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-12 11:36:36.014  6081  6081 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-12 11:36:36.014  6081  6081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:36.015  6081  6081 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:36.017  1031  1516 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-12 11:36:36.017  1031  6102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-12 11:36:36.017  1031  6102 E WifiMonitor: WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-12 11:36:36.017  1922  6105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-12 11:36:36.017  1031  1516 D LGWifiP2pService: InactiveState{ when=-38ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.017  1922  6105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-12 11:36:36.017  1031  1516 D LGWifiP2pService: P2pEnabledState{ when=-38ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.017  1922  6105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-12 11:36:36.017  1031  1516 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.017  1031  1516 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.017  1031  1516 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.017  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-12 11:36:36.017  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-12 11:36:36.017  1031  6102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,07-12 11:36:36.017  1031  6102 E WifiMonitor: WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:36.017  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-12 11:36:36.017  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:36.017  1031  6102 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-12 11:36:36.017  1031  6102 E WifiMonitor: WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:36.017  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:36.018  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-12 11:36:36.020  1031  1516 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.020  1031  1516 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.020  1031  1516 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.020  1922  2260 W WfdsService: DefaultState - msg [9441285] is not handled
07-12 11:36:36.022  6046  6046 E AudioManager: No RCC entry present to update
07-12 11:36:36.022  6046  6046 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-12 11:36:36.023  1031  1516 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.023  1031  1516 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.023  1031  1516 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.023  1031  1516 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.023  1031  1516 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.023  1031  1516 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.024  1031  1031 E WifiServerServiceExt: No p2p device connected
07-12 11:36:36.025  6046  6046 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-12 11:36:36.025  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-12 11:36:36.025  6046  6046 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-12 11:36:36.026  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
07-12 11:36:36.027  6046  6095 V LGMDMManager: Create singleton instance
,07-12 11:36:36.032  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
07-12 11:36:36.035  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-12 11:36:36.033  2127  2127 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
07-12 11:36:36.039  2127  2127 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
07-12 11:36:36.039  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
07-12 11:36:36.039  6046  6095 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-12 11:36:36.039  1031  1866 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@14f6f557com.lge.music.MediaPlaybackService$5@4312844
07-12 11:36:36.040  2127  2127 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
07-12 11:36:36.040  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.041  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.041  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.041  2127  2127 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1c7e88b2
07-12 11:36:36.042  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.042  2127  2127 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
07-12 11:36:36.042  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.043  2127  2127 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
07-12 11:36:36.043  2127  2127 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
07-12 11:36:36.043  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,07-12 11:36:36.044  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.044  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.045  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.045  2127  2127 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
07-12 11:36:36.079  2127  2127 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
07-12 11:36:36.080  2127  2127 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
07-12 11:36:36.080  2127  2127 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
07-12 11:36:36.080  2127  2127 V MediaPlayer[Native]: reset
07-12 11:36:36.084  2127  2127 V MediaPlayer[Native]: setListener
07-12 11:36:36.084  2127  2127 V MediaPlayer[Native]: disconnect
07-12 11:36:36.084  2127  2127 V MediaPlayer[Native]: destructor
07-12 11:36:36.084   315  1765 V AudioFlinger: releasing 18 from 2127 for -1
07-12 11:36:36.084   315  1765 V AudioFlinger:  decremented refcount to 0
07-12 11:36:36.084   315  1765 V AudioFlinger: purging stale effects
,07-12 11:36:36.086  2127  2127 V MediaPlayer[Native]: disconnect
07-12 11:36:36.087  2127  2127 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,07-12 11:36:36.088  2127  2127 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
07-12 11:36:36.088  2127  2127 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
07-12 11:36:36.089  2127  2127 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
07-12 11:36:36.089  2127  2127 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
07-12 11:36:36.089  2127  2127 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
07-12 11:36:36.090  2127  2127 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 734727469
07-12 11:36:36.090  2127  2127 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 734727469
07-12 11:36:36.096  6108  6108 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-12 11:36:36.096  6108  6108 W LG Account v2.2: No ProfileInfo entries
07-12 11:36:36.096  6108  6108 I LG Account v2.2: isEnabled: false
07-12 11:36:36.096  6108  6108 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-12 11:36:36.096  6108  6108 I Feature : [Lifetracker]Country: EU
07-12 11:36:36.096  6108  6108 I Feature : [Lifetracker]Operator: OPEN
07-12 11:36:36.097  6108  6108 I Feature : [Lifetracker]Ranking support: false
07-12 11:36:36.097  6108  6108 I Feature : [Lifetracker]Comfort support: false
07-12 11:36:36.097  6108  6108 I Feature : [Lifetracker]Accessory: true
07-12 11:36:36.097  6108  6108 I Feature : [Lifetracker]Health device: true
07-12 11:36:36.097  6108  6108 I Feature : [Lifetracker]Extra Pedometer: false
07-12 11:36:36.097  6108  6108 I Feature : [Lifetracker]Blood glucose device: false
07-12 11:36:36.097  6108  6108 I Feature : [Lifetracker]Device Number: 3
07-12 11:36:36.099  2127  2127 I SmartShareClient: [SmartShareManagerClient] terminate service: 2127/MediaPlaybackService/600500072
,07-12 11:36:36.102  2127  2127 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
07-12 11:36:36.102  2127  2127 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@21468262
07-12 11:36:36.119  1031  1920 V SIM_STK : Menu title from STK is T-Mobile
07-12 11:36:36.119  1031  1920 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:36:36.134  1031  1866 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6151 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-12 11:36:36.140  2127  2127 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
07-12 11:36:36.140  6126  6149 W FormManager: Network not available. Please check & try again.
07-12 11:36:36.140  2127  2127 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
07-12 11:36:36.141  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
07-12 11:36:36.141  2127  2127 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
07-12 11:36:36.142  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
07-12 11:36:36.142  1031  1698 I ActivityManager: Killing 5550:com.lge.appbox.client/u0a11 (adj 15): empty #17
07-12 11:36:36.198  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-12 11:36:36.198  6081  6081 E wpa_supplicant: USIM:  scard_init function
07-12 11:36:36.198  1031  6102 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-12 11:36:36.198  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-12 11:36:36.198  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
07-12 11:36:36.198  6081  6081 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-12 11:36:36.198  1031  6102 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-12 11:36:36.199  1031  1517 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
,07-12 11:36:36.200  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-12 11:36:36.200  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-12 11:36:36.200  1031  1517 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
07-12 11:36:36.200  1031  1517 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
07-12 11:36:36.201  1031  1517 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
07-12 11:36:36.201  1031  1517 I WifiNative-HAL: startHal
07-12 11:36:36.201  1031  1517 E wifi    : getStaticLongField sWifiHalHandle 0x9879a8cc
07-12 11:36:36.201  1031  1517 E WifiHAL : Could not connect handle
07-12 11:36:36.201  1031  1517 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301b1a
07-12 11:36:36.201  1031  1517 I WifiNative-HAL: Could not start hal
07-12 11:36:36.201  1031  1517 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,07-12 11:36:36.270  1031  1992 W libprocessgroup: failed to open /acct/uid_10011/pid_5550/cgroup.procs: No such file or directory
07-12 11:36:36.276  1031  2032 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-12 11:36:36.280  1031  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=102639  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-12 11:36:36.284  6071  6071 D BluetoothPermissionRequest: onReceive
07-12 11:36:36.289  6071  6071 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,07-12 11:36:36.293  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.293  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:36.293  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.293  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:36.293  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.293  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-12 11:36:36.294  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-12 11:36:36.296  1031  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=102655  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-12 11:36:36.297  6126  6150 V FormManager: Network unavailable.
07-12 11:36:36.297  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.297  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.297  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-12 11:36:36.297  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:36.297  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-12 11:36:36.298  6126  6150 V FormManager: Network unavailable.
07-12 11:36:36.299  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-12 11:36:36.299  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-12 11:36:36.299  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-12 11:36:36.299  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-12 11:36:36.299  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-12 11:36:36.300  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-12 11:36:36.300  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-12 11:36:36.300  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-12 11:36:36.300  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-12 11:36:36.300  6046  6046 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-12 11:36:36.300  6046  6046 I BluetoothA2dpServiceJni: classInitNative
07-12 11:36:36.300  6046  6046 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:36:36.300  6046  6046 D A2dpStateMachine: make
07-12 11:36:36.301  6046  6046 I bluedroid-qcom: get_profile_interface a2dp
07-12 11:36:36.301  6046  6170 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-12 11:36:36.304  6046  6046 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:36:36.304  6046  6046 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-12 11:36:36.305  6046  6169 D A2dpStateMachine: Enter Disconnected: -2
07-12 11:36:36.305  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:36.306  6046  6046 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 11:36:36.309  6046  6046 D HidService: Received start request. Starting profile...
07-12 11:36:36.309  6046  6046 I bluedroid-qcom: get_profile_interface hidhost
07-12 11:36:36.309  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:36.309  6046  6046 D HeadsetStateMachine: Proxy object connected
07-12 11:36:36.310  6046  6046 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-12 11:36:36.310  6046  6046 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-12 11:36:36.311  1031  1992 I ActivityManager: Killing 5393:com.android.defcontainer/u0a4 (adj 15): empty #17
07-12 11:36:36.314  6046  6046 I BluetoothHealthServiceJni: classInitNative: succeeds
07-12 11:36:36.314  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.314  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:36.314  1832  1832 D BluetoothPhoneService.BluetoothLTECall:  call mBluetoothHeadset.phoneStateChanged()
07-12 11:36:36.315  1832  1832 W BluetoothHeadset: Proxy not attached to service
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: java.lang.Throwable
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-12 11:36:36.315  1832  1832 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-12 11:36:36.316  6046  6046 D HealthService: Received start request. Starting profile...
07-12 11:36:36.317  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:36:36.321  6046  6046 I bluedroid-qcom: get_profile_interface health
07-12 11:36:36.321  6046  6046 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-12 11:36:36.321  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:36.323  6081  6081 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-12 11:36:36.325  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-12 11:36:36.325  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-12 11:36:36.325  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-12 11:36:36.325  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-12 11:36:36.326  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-12 11:36:36.326  1031  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=102684  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-12 11:36:36.326  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-12 11:36:36.326  1031  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=102685  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-12 11:36:36.327  1031  1517 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102685
07-12 11:36:36.326  6046  6046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-12 11:36:36.327  1031  1517 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102686
07-12 11:36:36.327  1031  1517 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102686
07-12 11:36:36.327  1031  1517 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102686
07-12 11:36:36.327  6046  6046 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 11:36:36.327  1031  1517 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=102686
07-12 11:36:36.328  1031  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=102686  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-12 11:36:36.329  6046  6046 D PanService: Received start request. Starting profile...
07-12 11:36:36.329  6046  6046 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 11:36:36.329  6046  6046 I bluedroid-qcom: get_profile_interface pan
07-12 11:36:36.330  6081  6081 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-12 11:36:36.331  6081  6081 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-12 11:36:36.333  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-12 11:36:36.333  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-12 11:36:36.333  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-12 11:36:36.333  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-12 11:36:36.333  1031  6102 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-12 11:36:36.333  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-12 11:36:36.333  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-12 11:36:36.333  1031  6102 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-12 11:36:36.337  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-12 11:36:36.337  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-12 11:36:36.341  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-12 11:36:36.369  1031  1554 W libprocessgroup: failed to open /acct/uid_10004/pid_5393/cgroup.procs: No such file or directory
,07-12 11:36:36.371  1031  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-12 11:36:36.371  6046  6046 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-12 11:36:36.371  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:36.372  6046  6046 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-12 11:36:36.374  1031  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=102733  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-12 11:36:36.375  1031  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=102733  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-12 11:36:36.375  1031  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=102734  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-12 11:36:36.375  6046  6106 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-12 11:36:36.376  1031  1517 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=102734
07-12 11:36:36.376  1031  1517 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=102735
07-12 11:36:36.376  6046  6106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 11:36:36.377  6046  6106 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-12 11:36:36.377  6046  6046 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 11:36:36.377  6046  6046 D BtGatt.GattService: Received start request. Starting profile...
07-12 11:36:36.377  6046  6046 D BtGatt.GattService: start()
07-12 11:36:36.377  6046  6046 I bluedroid-qcom: get_profile_interface gatt
07-12 11:36:36.377  6046  6046 D BtGatt.AdvertiseManager: advertise manager created
07-12 11:36:36.380  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.380  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-12 11:36:36.381  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:36.381  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.381  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.381  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-12 11:36:36.382  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.382  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.382  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-12 11:36:36.382  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:36.382  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-12 11:36:36.384  1031  1517 D WifiNative-wlan0: doString: [STATUS]
07-12 11:36:36.384  1031  1992 I ActivityManager: Killing 5567:com.android.contacts/u0a19 (adj 15): empty #17
07-12 11:36:36.384  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-12 11:36:36.384  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-12 11:36:36.384  1031  1517 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-12 11:36:36.386  1031  1517 I WifiServiceExtension: setVHTCapabilityType  : false
07-12 11:36:36.387  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.387  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:36.388  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:36.390  1031  1111 D BluetoothManagerService: Message: 20
07-12 11:36:36.390  1031  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7dad3d2:true
07-12 11:36:36.522  1031  1517 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-12 11:36:36.523  1031  1517 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,07-12 11:36:36.526  1031  1920 W libprocessgroup: failed to open /acct/uid_10019/pid_5567/cgroup.procs: No such file or directory
07-12 11:36:36.533  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.533  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.533  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-12 11:36:36.535  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.535  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:36.538  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:36:36.542  1031  1364 V AlarmManager: RTC_WAKEUP set : Alarm{1eed4ba0 type 0 when 1468316193779 com.android.vending} when 1468316193779
07-12 11:36:36.545  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:36.546  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:36.546  6046  6046 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-12 11:36:36.547  6046  6046 V BluetoothMapService: BluetoothMapBinder()
07-12 11:36:36.556  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.556  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-12 11:36:36.558  1031  1364 V AlarmManager: RTC_WAKEUP set : Alarm{226b81cc type 0 when 1468316196115 android} when 1468316196115
07-12 11:36:36.558  6046  6046 D BluetoothMapService: Received start request. Starting profile...
07-12 11:36:36.558  6046  6046 D BluetoothMapService: start()
07-12 11:36:36.559  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:36:36.559  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.559  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:36.559  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-12 11:36:36.561  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-12 11:36:36.561  6046  6046 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-12 11:36:36.561  6046  6046 D BluetoothMapEmailAppObserver: createReceiver()
07-12 11:36:36.562  6046  6046 D BluetoothMapEmailAppObserver: initObservers()
07-12 11:36:36.563  6046  6046 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-12 11:36:36.568  1031  1523 D WifiService: New client listening to asynchronous messages
07-12 11:36:36.571  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
,07-12 11:36:36.574  6046  6046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-12 11:36:36.576  6046  6046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-12 11:36:36.587  6046  6046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-12 11:36:36.588  1031  1517 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-12 11:36:36.589  1031  1524 D ConnectivityService: Got NetworkAgent Messenger
07-12 11:36:36.589  1031  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-12 11:36:36.589  1031  1524 D ConnectivityService: NetworkAgent connected
07-12 11:36:36.589  1031  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 11:36:36.589  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-12 11:36:36.590  6046  6046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-12 11:36:36.590  6046  6046 V PanService: [BTUI] SIM Extra State :ABSENT
07-12 11:36:36.593  6046  6046 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-12 11:36:36.593  6046  6046 V BluetoothMapService: Handler(): got msg=1
07-12 11:36:36.593  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-12 11:36:36.593  1031  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-12 11:36:36.593  6046  6095 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-12 11:36:36.593  6046  6095 I bluedroid-qcom: enable
07-12 11:36:36.594  6046  6095 I bt_hci_bdroid: init
07-12 11:36:36.597  6071  6071 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:36.597  6071  6071 D LgDataFeature: LgDataFeature() Constructor Done, null
07-12 11:36:36.599  6046  6183 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-12 11:36:36.599  6046  6183 I bt-btu  : btu_task pending for preload complete event
,07-12 11:36:36.602  6046  6095 I bt_vendor: bt-vendor : init
07-12 11:36:36.602  6046  6095 I bt_vendor: bt-vendor : get_bt_soc_type
07-12 11:36:36.602  6046  6095 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-12 11:36:36.602  6046  6095 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-12 11:36:36.602  6046  6095 D bt_userial_mct: userial_init
07-12 11:36:36.603  6046  6095 D bt_hci_bdroid: set_power 1
07-12 11:36:36.603  6046  6095 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-12 11:36:36.603  6046  6095 I bt_vendor: Starting hciattach daemon
07-12 11:36:36.603  6046  6095 I bt_vendor: try to set true
07-12 11:36:36.591  6186  6186 W sh      : type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:36.591  6186  6186 W sh      : type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:36.609  6071  6071 D WiFiOffLoadUpdatePriority: remove : truetruetrue
07-12 11:36:36.612  1031  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-12 11:36:36.616  1031  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 11:36:36.616  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-12 11:36:36.616  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-12 11:36:36.616  1031  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-12 11:36:36.621  6188  6188 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
07-12 11:36:36.625  1031  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-12 11:36:36.625  1031  2032 V SIM_STK : Menu title from STK is T-Mobile
07-12 11:36:36.625   310   883 D CommandListener: Setting iface cfg
07-12 11:36:36.629  1031  1517 E WifiStateMachine: Start Dhcp Watchdog 1
,07-12 11:36:36.629  1031  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102988  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-12 11:36:36.629  1031  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102988  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-12 11:36:36.630  1031  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=102989  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-12 11:36:36.630  1031  6190 D DhcpStateMachine: StoppedState
07-12 11:36:36.630  1031  6190 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.630  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:36.630  1031  6190 D DhcpStateMachine: WaitBeforeStartState
07-12 11:36:36.630  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:36.631  1031  1517 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:36.631  1031  1517 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:36.631  1031  1517 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:36.631  1031  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-12 11:36:36.632  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:36.632  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-12 11:36:36.632  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:36.632  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-12 11:36:36.633  1031  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102992  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-12 11:36:36.633  1031  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102992  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-12 11:36:36.634  1031  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=102992  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-12 11:36:36.635  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-562618597] from screen [on:0 period:-562618597]
07-12 11:36:36.636  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-562618596]
07-12 11:36:36.636  1031  1517 I WifiNative-HAL: startHal
07-12 11:36:36.636  1031  1517 E wifi    : getStaticLongField sWifiHalHandle 0x9879a8bc
07-12 11:36:36.636  1031  1517 E WifiHAL : Could not connect handle
07-12 11:36:36.636  1031  1517 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x80119e
07-12 11:36:36.636  1031  1517 I WifiNative-HAL: Could not start hal
07-12 11:36:36.636  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:36:36.640  1031  1524 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
07-12 11:36:36.640  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,07-12 11:36:36.641  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
07-12 11:36:36.641  1031  1517 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
07-12 11:36:36.642  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:36.642  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:36.642  1031  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:36.642  1031  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:36.643  1031  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:36.643  1031  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:36.643  1031  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-12 11:36:36.645  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:36.645  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:36.646  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-12 11:36:36.647  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
07-12 11:36:36.647  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
07-12 11:36:36.647  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-12 11:36:36.664  6195  6195 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-12 11:36:36.671  6196  6196 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-12 11:36:36.684  6198  6198 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-12 11:36:36.690  6199  6199 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-12 11:36:36.691  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,07-12 11:36:36.691  1031  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-12 11:36:36.691  1031  1517 D WifiNative-wlan0: doBoolean: SET ps 0
07-12 11:36:36.692  1031  1517 D WifiNative-wlan0: SET ps 0: returned true
07-12 11:36:36.692  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-12 11:36:36.692  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-12 11:36:36.692  1031  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-12 11:36:36.692  1031  1517 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-12 11:36:36.692  1031  1517 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-12 11:36:36.692  1031  1517 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-12 11:36:36.692  1031  1517 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
07-12 11:36:36.693  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
07-12 11:36:36.693  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
07-12 11:36:36.693  1031  1517 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
07-12 11:36:36.694  1031  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-12 11:36:36.694  1031  1516 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c9c07e target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.694  1031  1516 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c9c07e target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.695  1031  6190 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:36.695  1031  6190 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-12 11:36:36.696  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:36.696  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,07-12 11:36:36.697  6200  6200 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
07-12 11:36:36.705  6201  6201 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
07-12 11:36:36.706  1031  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-12 11:36:36.707  6071  6071 D WiFiOffLoadUpdatePriority: remove1
,07-12 11:36:36.707  6071  6071 V WiFiOffLoadSharedPrefsUtils: save remove
07-12 11:36:36.722  6071  6071 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
07-12 11:36:36.722  6071  6071 D WiFiOffLoadBroadcast: S: false, R: false
,07-12 11:36:36.723  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
07-12 11:36:36.723  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
07-12 11:36:36.723  1031  1517 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
07-12 11:36:36.724  6071  6071 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
07-12 11:36:36.724  6071  6071 D WiFiOffLoadUpdatePriority: connected SSID: null
07-12 11:36:36.724  6071  6071 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
07-12 11:36:36.724  6203  6203 I libmdmdetect: ESOC framework not supported
07-12 11:36:36.725  6203  6203 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
07-12 11:36:36.726  1031  1992 D WifiServiceImplEx: addOrUpdateNetwork pid=6071, uid=1000, packageName=android.uid.system:1000
07-12 11:36:36.726  1031  1992 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
07-12 11:36:36.727  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
07-12 11:36:36.727  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
07-12 11:36:36.727  1031  1517 E WifiStateMachine:  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
07-12 11:36:36.728  1031  1517 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
07-12 11:36:36.728  1031  1517 D WifiServerServiceExt: addOrUpdateNetwork: mThisIsFirstEnableing = false
07-12 11:36:36.728  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 ssid 4e47373030
07-12 11:36:36.729  6203  6203 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-12 11:36:36.729  6203  6203 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-12 11:36:36.729  6203  6203 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-12 11:36:36.729  6203  6203 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-12 11:36:36.729  6203  6203 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-12 11:36:36.729  6203  6203 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-12 11:36:36.729  6203  6203 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-12 11:36:36.743  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 ssid 4e47373030: returned true
07-12 11:36:36.743  1031  1517 E WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
07-12 11:36:36.743  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-12 11:36:36.744  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-12 11:36:36.744  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,07-12 11:36:36.744  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 key_mgmt WPA-PSK: returned true
07-12 11:36:36.744  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 proto WPA RSN
07-12 11:36:36.744  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 proto WPA RSN: returned true
07-12 11:36:36.744  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
07-12 11:36:36.745  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 pairwise TKIP CCMP: returned true
07-12 11:36:36.745  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
07-12 11:36:36.745  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
07-12 11:36:36.745  1031  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 priority 300
07-12 11:36:36.745  1031  1517 D WifiNative-wlan0: SET_NETWORK 0 priority 300: returned true
07-12 11:36:36.746  1031  1517 E WifiConfigStore: will read network variables netId=0
07-12 11:36:36.749  1031  1517 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
07-12 11:36:36.750  1031  1517 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
07-12 11:36:36.751  6071  6071 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
07-12 11:36:36.751  6071  6071 D WiFiOffLoadUpdatePriority: configuration updated: 0
07-12 11:36:36.751  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
07-12 11:36:36.751  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
07-12 11:36:36.751  1031  1517 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
07-12 11:36:36.751  1031  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-12 11:36:36.764  1031  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-12 11:36:36.765  6071  6071 D WiFiOffLoadUpdatePriority: configuration saved: true
07-12 11:36:36.768  6046  6046 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-12 11:36:36.768  6071  6071 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-12 11:36:36.774  6046  6046 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:36.776  6046  6046 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-12 11:36:36.776  6046  6046 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-12 11:36:36.776  6046  6046 V BluetoothSapReceiver: SapReceiver onReceive 
,07-12 11:36:36.777  6046  6046 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:36.777  6046  6046 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-12 11:36:36.794  5652  5652 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-12 11:36:36.822  1031  1554 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6210 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-12 11:36:36.826  6126  6207 W FormManager: Network not available. Please check & try again.
07-12 11:36:36.830  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-12 11:36:36.833  6126  6208 V FormManager: Network unavailable.
,07-12 11:36:36.843  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-12 11:36:36.845  6126  6208 V FormManager: Network unavailable.
,07-12 11:36:36.849  6210  6210 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-12 11:36:36.850  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:36.851  1031  2011 I ActivityManager: Killing 5594:com.lge.email/u0a23 (adj 15): empty #17
07-12 11:36:36.897  1031  6190 D DhcpStateMachine: DHCPV4 request on wlan0
07-12 11:36:36.897  1031  6190 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,07-12 11:36:36.897  1031  6190 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,07-12 11:36:36.901  6227  6227 W dhcpcd  : type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:36.901  6227  6227 W dhcpcd  : type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-12 11:36:36.928  6227  6227 I dhcpcd  : version 5.5.6 starting
07-12 11:36:36.930  6227  6227 E dhcpcd  : get_duid: m
07-12 11:36:36.930  6227  6227 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-12 11:36:36.930  6227  6227 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,07-12 11:36:36.949  1031  1866 W libprocessgroup: failed to open /acct/uid_10023/pid_5594/cgroup.procs: No such file or directory
,07-12 11:36:36.960  1031  2011 I ActivityManager: Killing 5627:com.android.gallery3d/u0a27 (adj 15): empty #17
07-12 11:36:37.061  6227  6227 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,07-12 11:36:37.061  6227  6227 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-12 11:36:37.061  6227  6227 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-12 11:36:37.069  6227  6227 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-12 11:36:37.069  1031  1920 W libprocessgroup: failed to open /acct/uid_10027/pid_5627/cgroup.procs: No such file or directory
07-12 11:36:37.069  6227  6227 D dhcpcd  : wlan0: sending REQUEST (xid 0xe1f0db6c), next in 4.30 seconds
07-12 11:36:37.088  3072  3072 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-12 11:36:37.088  3072  3072 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-12 11:36:37.090  3072  3072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-12 11:36:37.094  3072  3072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-12 11:36:37.101  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.109  6151  6151 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,07-12 11:36:37.111  3072  6234 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-12 11:36:37.117  6151  6151 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-12 11:36:37.117  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-12 11:36:37.119  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:36:37.120  3072  6236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-12 11:36:37.121  3072  6236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-12 11:36:37.125  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.130  6227  6227 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
07-12 11:36:37.162  1031  1554 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6237 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-12 11:36:37.166  6227  6227 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-12 11:36:37.166  6227  6227 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-12 11:36:37.167  6227  6227 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-12 11:36:37.167  6227  6227 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-12 11:36:37.167  6227  6227 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-12 11:36:37.167  6227  6227 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-12 11:36:37.167  6227  6227 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-12 11:36:37.167  6227  6227 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-12 11:36:37.169  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:37.169  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:37.169  1031  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:37.169  1031  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:37.169  1031  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:37.170  1031  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-12 11:36:37.170  1031  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,07-12 11:36:37.207  6237  6237 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-12 11:36:37.222  6237  6237 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,07-12 11:36:37.244  6237  6237 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-12 11:36:37.244  6237  6237 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-12 11:36:37.244  6237  6237 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-12 11:36:37.245  6237  6237 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-12 11:36:37.245  6237  6237 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,07-12 11:36:37.252  6237  6237 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-12 11:36:37.256  6237  6237 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-12 11:36:37.260  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-12 11:36:37.264  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.291  6237  6237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-12 11:36:37.292  4824  4824 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-12 11:36:37.293  4824  4824 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-12 11:36:37.294  4824  4824 V [BNRBootReceiver]: Boot Receiver Return
07-12 11:36:37.294  6237  6237 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-12 11:36:37.298  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.299  6237  6237 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-12 11:36:37.302  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.317  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.325  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-12 11:36:37.325  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.327  6237  6237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-12 11:36:37.329  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-12 11:36:37.331  6071  6071 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-12 11:36:37.338  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.344  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.348  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.354  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-12 11:36:37.354  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.354  6237  6237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-12 11:36:37.357  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-12 11:36:37.361  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:36:37.366  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.372  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-12 11:36:37.372  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.372  6237  6237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-12 11:36:37.373  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-12 11:36:37.373  6071  6071 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-12 11:36:37.373  6071  6071 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-12 11:36:37.374  6071  6071 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-12 11:36:37.374  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-12 11:36:37.374  6071  6071 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-12 11:36:37.374  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-12 11:36:37.374  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-12 11:36:37.374  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-12 11:36:37.374  6071  6071 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-12 11:36:37.374  6071  6071 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-12 11:36:37.375  6071  6071 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-12 11:36:37.377  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.383  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.390  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.395  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-12 11:36:37.395  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-12 11:36:37.395  6237  6237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-12 11:36:37.398  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.404  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.408  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.414  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-12 11:36:37.414  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.414  6237  6237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-12 11:36:37.417  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-12 11:36:37.423  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:36:37.428  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.434  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-12 11:36:37.435  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.435  6237  6237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-12 11:36:37.438  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.445  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.450  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.459  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-12 11:36:37.459  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.459  6237  6237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-12 11:36:37.464  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:824] from screen [on:0 period:-562617768]
07-12 11:36:37.471  6237  6237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-12 11:36:37.472  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-12 11:36:37.472  6237  6237 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,07-12 11:36:37.498  4170  6277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,07-12 11:36:37.501  1031  6190 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-12 11:36:37.503  1031  6190 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-12 11:36:37.503  1031  6190 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-12 11:36:37.504  1031  6190 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-12 11:36:37.504  1031  6190 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-12 11:36:37.504  1031  6190 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-12 11:36:37.504  1031  6190 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
07-12 11:36:37.505  1031  6190 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-12 11:36:37.505  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-12 11:36:37.505  1031  6190 D DhcpStateMachine: RunningState
07-12 11:36:37.506  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-12 11:36:37.506  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-12 11:36:37.506  1031  1516 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:37.506  1031  1516 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:37.507  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-12 11:36:37.507  1031  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-12 11:36:37.507  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-12 11:36:37.508  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-12 11:36:37.508  1031  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-12 11:36:37.508  1031  1517 D WifiNative-wlan0: doBoolean: SET ps 1
,07-12 11:36:37.523  6237  6237 D LgDataFeature: LgDataFeature() Constructor: none,
07-12 11:36:37.524  6237  6237 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-12 11:36:37.528  1031  1517 D WifiNative-wlan0: SET ps 1: returned true
07-12 11:36:37.528  1031  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-12 11:36:37.529  1031  1517 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-12 11:36:37.529  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-12 11:36:37.529  1031  1517 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-12 11:36:37.529  1031  1524 D ConnectivityService: ignoring duplicate network state non-change
07-12 11:36:37.533  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:37.533  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:37.533  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-12 11:36:37.535  1031  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-12 11:36:37.536  1031  1524 D ConnectivityService: Adding iface wlan0 to network 100
,07-12 11:36:37.537  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:37.537  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:37.539  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:37.542  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:37.542  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:37.542  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-12 11:36:37.544  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-12 11:36:37.545  1031  1517 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-12 11:36:37.546  1922  1922 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-12 11:36:37.549  1031  1524 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-12 11:36:37.549  1031  1524 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-12 11:36:37.549  1031  1517 E WifiStateMachine:  ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):87 rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:85] from screen [on:0 period:-562617683]
07-12 11:36:37.550  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):88 rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-562617682]
07-12 11:36:37.552  1031  1517 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.50 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-39
07-12 11:36:37.552  1031  1517 D WifiNative-wlan0: doBoolean: SCAN TYPE=ONLY
07-12 11:36:37.553  6081  6081 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-12 11:36:37.553  1031  1524 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-12 11:36:37.554  1031  6102 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-12 11:36:37.554  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-12 11:36:37.554  1031  1524 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
07-12 11:36:37.554  1031  6102 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-12 11:36:37.554  1031  6102 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-12 11:36:37.554  1031  1524 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-12 11:36:37.554  1031  1524 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
07-12 11:36:37.554  1031  1517 D WifiNative-wlan0: SCAN TYPE=ONLY: returned true
07-12 11:36:37.554  1031  1524 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
07-12 11:36:37.558  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:37.558  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:37.559  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:37.559  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:37.559  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-12 11:36:37.559  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-12 11:36:37.561  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:37.562  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.563  1031  1524 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-12 11:36:37.563  1031  1524 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:37.563  1031  1524 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:37.563  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:37.563  1031  1524 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-12 11:36:37.563  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-12 11:36:37.564  1031  1524 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:36:37.564  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:37.564  1031  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:37.564  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-12 11:36:37.566  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:37.566  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:37.566  1031  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-12 11:36:37.566  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-12 11:36:37.566  1031  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:37.566  1031  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-12 11:36:37.566  1031  1524 D ConnectivityService: currentScore = 0, newScore = 20
07-12 11:36:37.566  1031  1524 D ConnectivityService:    accepting network in place of null
07-12 11:36:37.566  1031  1524 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:37.567   310  6287 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-12 11:36:37.567  1031  1517 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:37.567  1031  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:36:37.567  1581  1581 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-12 11:36:37.567  1031  1524 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
07-12 11:36:37.568  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:37.569  1832  1832 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:37.570  1832  1832 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-12 11:36:37.578  1031  1524 E ConnectivityService: [lg_data] Adding agent Netw,orkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-12 11:36:37.578  1031  1524 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-12 11:36:37.579  1031  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-12 11:36:37.581  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-12 11:36:37.582   310  6288 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:36:37.582  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-12 11:36:37.582   310  6288 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
07-12 11:36:37.582  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-12 11:36:37.582  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-12 11:36:37.582  1031  1031 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
07-12 11:36:37.582   310  6288 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
07-12 11:36:37.583  1031  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-12 11:36:37.583  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:37.583  1581  1581 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-12 11:36:37.583  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:37.584  1031  1524 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:37.584  1031  1524 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-12 11:36:37.585  1031  1524 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-12 11:36:37.586  1031  1524 D ConnectivityService: validation of new default Network = false
07-12 11:36:37.586  1031  1524 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-12 11:36:37.586  1031  1524 D DSQN    : enableDataServiceNotify 
07-12 11:36:37.586  1031  1524 D DSQN    : start dsqn bin
07-12 11:36:37.589  6237  6237 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-12 11:36:37.590  6237  6237 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-12 11:36:37.590  6237  6237 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-12 11:36:37.590  6237  6237 V SoundPool: doLoad: loading sample sampleID=1
07-12 11:36:37.590  1031  1515 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-12 11:36:37.591  6237  6237 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,07-12 11:36:37.594   310  6292 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:36:37.594   310  6292 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
07-12 11:36:37.595  1031  1524 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:37.595  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:37.595  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:37.595  6237  6291 V SoundPool: Start decode
07-12 11:36:37.596  6237  6291 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-12 11:36:37.596  1031  1524 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:37.596  1581  2087 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-12 11:36:37.591  6293  6293 W dsqn    : type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:37.591  6293  6293 W dsqn    : type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:37.596   315  1766 V MediaPlayerService: decode(23, 10857164, 17813)
07-12 11:36:37.599   315  1766 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-12 11:36:37.599   315  1766 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-12 11:36:37.599   315  1766 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-12 11:36:37.599   315  1766 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-12 11:36:37.599   315  1766 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-12 11:36:37.599   315  1766 V MediaPlayerService: player type = 3
07-12 11:36:37.599   315  1766 V AwesomePlayer: AwesomePlayer create()
07-12 11:36:37.599   315  1766 V AwesomePlayer: reset_l() 
07-12 11:36:37.599   315  1766 V AwesomePlayer: cancelPlayerEvents
07-12 11:36:37.599   315  1766 V AwesomePlayer: setAudioSink() 
07-12 11:36:37.599   315  1766 V AwesomePlayer: reset_l() 
07-12 11:36:37.599   315  1766 V AudioCache: notify(0xb1432180, 8, 0, 0)
07-12 11:36:37.599   315  1766 V AudioCache: ignored
07-12 11:36:37.599   315  1766 V AwesomePlayer: cancelPlayerEvents
07-12 11:36:37.599   315  1766 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-12 11:36:37.599   315  1766 V AwesomePlayer: setDataSource_l dataSource
07-12 11:36:37.599   315  1766 V LGParserOSAL: SniffLGParser start
07-12 11:36:37.599   315  1766 V LGParserOSAL: MainType:5, SubType=0
07-12 11:36:37.599   315  1766 V LGParserOSAL: #### check Mime : application/ogg
07-12 11:36:37.599   315  1766 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-12 11:36:37.599   315  1766 E MediaExtractor: Use LGExtractor :application/ogg 
07-12 11:36:37.602  6237  6237 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-12 11:36:37.603  6237  6237 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-12 11:36:37.603  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,07-12 11:36:37.610  6293  6293 E DSQN    : DSQN ssw
07-12 11:36:37.616  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-12 11:36:37.617  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:37.618  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:37.626  6237  6237 V LGMDMManager: Create singleton instance
07-12 11:36:37.627  5960  5960 D UEI.SmartControl: QS Service created
07-12 11:36:37.631   315  1766 V LGParserOSAL: supported mime: application/ogg
07-12 11:36:37.631   315  1766 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-12 11:36:37.631   315  1766 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-12 11:36:37.631   315  1766 V AwesomePlayer: mBitrate = -1 bits/sec
07-12 11:36:37.631   315  1766 V AwesomePlayer: AudioTrack Setting
07-12 11:36:37.631   315  1766 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-12 11:36:37.631   315  1766 V AwesomePlayer: setAudioSource() 
07-12 11:36:37.631   315  1766 V MediaPlayerService: prepare
07-12 11:36:37.631   315  1766 V AwesomePlayer: prepareAsync_l() 
07-12 11:36:37.631   315  1766 V MediaPlayerService: wait for prepare
07-12 11:36:37.631   315  6298 V AwesomePlayer: onPrepareAsyncEvent() 
07-12 11:36:37.631   315  6298 V AwesomePlayer: initAudioDecoder() 
07-12 11:36:37.631   315  6298 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-12 11:36:37.631   315  6298 V AudioSystem: isOffloadSupported()
07-12 11:36:37.631   315  6298 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-12 11:36:37.631   315  6298 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-12 11:36:37.631   315  6298 I AudioFlinger: isAudioPlaybackHookOn() false
07-12 11:36:37.631   315  6298 V AwesomePlayer: getUseOffload() = 0 
07-12 11:36:37.631   315  6298 V OMXCodec: OMXCodec::Create
07-12 11:36:37.631   315  6298 V OMXCodec: findMatchingCodecs()
07-12 11:36:37.631   315  6298 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-12 11:36:37.631   315  6298 V OMXCodec: matchingCodecs.size()=1
07-12 11:36:37.631   315  6298 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-12 11:36:37.632   315  6298 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-12 11:36:37.632   315  6298 V LGCodecAdapter: LG Codec Adapter start
07-12 11:36:37.632   315  6298 V OMXCodec: OMXCodec Createtor
07-12 11:36:37.632   315  6298 V OMXCodec: setComponentRole
07-12 11:36:37.632   315  6298 V OMXCodec: configureCodec protected=0
07-12 11:36:37.632   315  6298 V LGCodecAdapter: called getLGCodecSpecificData
07-12 11:36:37.632   315  6298 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-12 11:36:37.632   315  6298 V LGCodecOSAL: Called LGconfigureCodecMETA
07-12 11:36:37.632   315  6298 V LGCodecOSAL: Called LGconfigureCodecMSG
07-12 11:36:37.632   315  6298 V LGCodecOSAL: Not support LGCodec
07-12 11:36:37.632   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-12 11:36:37.632   315  6298 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-12 11:36:37.632   315  6298 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-12 11:36:37.632   315  6298 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-12 11:36:37.632   315  6298 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-12 11:36:37.632   315  6298 V AudioSystem: isOffloadSupported()
07-12 11:36:37.632   315  6298 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-12 11:36:37.632   315  6298 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-12 11:36:37.632   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
,07-12 11:36:37.632   315  6298 V OMXCodec: init()
07-12 11:36:37.632   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-12 11:36:37.632   315  6298 V OMXCodec: allocateBuffers
07-12 11:36:37.632   315  6298 V OMXCodec: allocateBuffersOnPort portIndex=0
07-12 11:36:37.632   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
07-12 11:36:37.633   315  6298 V OMXCodec: allocateBuffersOnPort portIndex=1
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
07-12 11:36:37.633   315  6298 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
07-12 11:36:37.633   315  6298 V OMXCodec: init() mAsyncCompletion wait!!! 
07-12 11:36:37.634   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-12 11:36:37.634   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-12 11:36:37.634   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-12 11:36:37.634   315  6298 V OMXCodec: init() mAsyncCompletion wait!!! 
07-12 11:36:37.634   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
,07-12 11:36:37.634   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-12 11:36:37.634   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-12 11:36:37.634   315  6298 V OMXCodec: init() mAsyncCompletion wait free! 
07-12 11:36:37.634   315  6298 V AwesomePlayer: finishAsyncPrepare_l() 
07-12 11:36:37.634   315  6298 V AudioCache: notify(0xb1432180, 5, 0, 0)
07-12 11:36:37.634   315  6298 V AudioCache: ignored
07-12 11:36:37.634   315  6298 V AudioCache: notify(0xb1432180, 1, 0, 0)
07-12 11:36:37.634   315  6298 V AudioCache: prepared
07-12 11:36:37.634   315  1766 V AudioCache: wait - success
07-12 11:36:37.634   315  1766 V MediaPlayerService: start
07-12 11:36:37.634   315  1766 V AwesomePlayer: play_l() 
07-12 11:36:37.634   315  1766 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-12 11:36:37.634   315  1766 V AwesomePlayer: createAudioPlayer_l
07-12 11:36:37.634   315  1766 V AwesomePlayer: seekAudioIfNecessary_l() 
07-12 11:36:37.634   315  1766 V AwesomePlayer: startAudioPlayer_l() 
07-12 11:36:37.634   315  1766 D AudioPlayer: start of Playback, useOffload 0
07-12 11:36:37.634   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-12 11:36:37.634   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-12 11:36:37.636   315  6300 V OMXCodec: allocateBuffersOnPort portIndex=1
07-12 11:36:37.636   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-12 11:36:37.637   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
07-12 11:36:37.637   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
07-12 11:36:37.637   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-12 11:36:37.637   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
07-12 11:36:37.63,7   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-12 11:36:37.637   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-12 11:36:37.637   315  1766 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-12 11:36:37.638   315  1766 V AudioCache: notify(0xb1432180, 6, 0, 0)
07-12 11:36:37.638   315  1766 V AudioCache: ignored
07-12 11:36:37.638   315  1766 V MediaPlayerService: wait for playback complete
07-12 11:36:37.638   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.638   315  6301 V AudioCache: memcpy(0xac102000, 0xb17f9000, 4096)
07-12 11:36:37.639   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.639   315  6301 V AudioCache: memcpy(0xac103000, 0xb17f9000, 4096)
07-12 11:36:37.639   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.639   315  6301 V AudioCache: memcpy(0xac104000, 0xb17f9000, 4096)
07-12 11:36:37.639  5960  5960 I UEI.SmartControl: Service initServices...
07-12 11:36:37.639   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.639   315  6301 V AudioCache: memcpy(0xac105000, 0xb17f9000, 4096)
07-12 11:36:37.639  5960  5960 D UEI.SmartControl: QS start get config
07-12 11:36:37.640   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.640   315  6301 V AudioCache: memcpy(0xac106000, 0xb17f9000, 4096)
07-12 11:36:37.642   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.642   315  6301 V AudioCache: memcpy(0xac107000, 0xb17f9000, 4096)
07-12 11:36:37.643   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.643   315  6301 V AudioCache: memcpy(0xac108000, 0xb17f9000, 4096)
07-12 11:36:37.644   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.644   315  6301 V AudioCache: memcpy(0xac109000, 0xb17f9000, 4096)
07-12 11:36:37.644   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.644   315  6301 V AudioCache: memcpy(0xac10a000, 0xb17f9000, 4096)
07-12 11:36:37.644   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.644   315  6301 V AudioCache: memcpy(0xac10b000, 0xb17f9000, 4096)
07-12 11:36:37.645   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.645   315  6301 V AudioCache: memcpy(0xac10c000, 0xb17f9000, 4096)
07-12 11:36:37.645   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.645   315  6301 V AudioCache: memcpy(0xac10d000, 0xb17f9000, 4096)
07-12 11:36:37.646   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.646   315  6301 V AudioCache: memcpy(0xac10e000, 0xb17f9000, 4096)
07-12 11:36:37.647   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.647   315  6301 V AudioCache: memcpy(0xac10f000, 0xb17f9000, 4096)
07-12 11:36:37.647   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.647   315  6301 V AudioCache: memcpy(0xac110000, 0xb17f9000, 4096)
07-12 11:36:37.648   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.648   315  6301 V AudioCache: memcpy(0xac111000, 0xb17f9000, 4096)
07-12 11:36:37.648   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.648   315  6301 V AudioCache: memcpy(0xac112000, 0xb17f9000, 4096)
07-12 11:36:37.648   315  6301 V AudioCache: write(0xb17f9000, 4096)
,07-12 11:36:37.648   315  6301 V AudioCache: memcpy(0xac113000, 0xb17f9000, 4096)
07-12 11:36:37.649   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.649   315  6301 V AudioCache: memcpy(0xac114000, 0xb17f9000, 4096)
07-12 11:36:37.649   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.649   315  6301 V AudioCache: memcpy(0xac115000, 0xb17f9000, 4096)
07-12 11:36:37.649   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.649   315  6301 V AudioCache: memcpy(0xac116000, 0xb17f9000, 4096)
07-12 11:36:37.649   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.649   315  6301 V AudioCache: memcpy(0xac117000, 0xb17f9000, 4096)
07-12 11:36:37.650   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.650   315  6301 V AudioCache: memcpy(0xac118000, 0xb17f9000, 4096)
07-12 11:36:37.650   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.650   315  6301 V AudioCache: memcpy(0xac119000, 0xb17f9000, 4096)
07-12 11:36:37.650   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.650   315  6301 V AudioCache: memcpy(0xac11a000, 0xb17f9000, 4096)
07-12 11:36:37.650   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.650   315  6301 V AudioCache: memcpy(0xac11b000, 0xb17f9000, 4096)
07-12 11:36:37.651   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.651   315  6301 V AudioCache: memcpy(0xac11c000, 0xb17f9000, 4096)
07-12 11:36:37.652   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.652   315  6301 V AudioCache: memcpy(0xac11d000, 0xb17f9000, 4096)
07-12 11:36:37.652   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.652   315  6301 V AudioCache: memcpy(0xac11e000, 0xb17f9000, 4096)
07-12 11:36:37.653   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.653   315  6301 V AudioCache: memcpy(0xac11f000, 0xb17f9000, 4096)
07-12 11:36:37.653   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.653   315  6301 V AudioCache: memcpy(0xac120000, 0xb17f9000, 4096)
07-12 11:36:37.653   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.653   315  6301 V AudioCache: memcpy(0xac121000, 0xb17f9000, 4096)
07-12 11:36:37.654   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.654   315  6301 V AudioCache: memcpy(0xac122000, 0xb17f9000, 4096)
07-12 11:36:37.654   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.654   315  6301 V AudioCache: memcpy(0xac123000, 0xb17f9000, 4096)
07-12 11:36:37.654   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.654   315  6301 V AudioCache: memcpy(0xac124000, 0xb17f9000, 4096)
07-12 11:36:37.654   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.654   315  6301 V AudioCache: memcpy(0xac125000, 0xb17f9000, 4096)
07-12 11:36:37.655   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.655   315  6301 V AudioCache: memcpy(0xac126000, 0xb17f9000, 4096)
07-12 11:36:37.656   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.656   315  6301 V AudioCache: memcpy(0xac127000, 0xb17f9000, 4096)
07-12 11:36:37.656   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.656   315  6301 V AudioCache: memcpy(0xac128000, 0xb17f9000, 4096)
07-12 11:36:37.656   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.656   315  6301 V AudioCache: memcpy(0xac129000, 0xb17f9000, 4096)
07-12 11:36:37.656   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.656   315  6301 V AudioCache: memcpy(0xac12a000, 0xb17f9000, 4096)
07-12 11:36:37.657   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.657   315  6301 V AudioCache: memcpy(0xac12b000, 0xb17f9000, 4096)
07-12 11:36:37.658   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.658   315  6301 V AudioCache: memcpy(0xac12c000, 0xb17f9000, 4096)
07-12 11:36:37.658   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.658   315  6301 V AudioCache: memcpy(0xac12d000, 0xb17f9000, 4096)
07-12 11:36:37.658   315  6301 V Au,dioCache: write(0xb17f9000, 4096)
07-12 11:36:37.658   315  6301 V AudioCache: memcpy(0xac12e000, 0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: memcpy(0xac12f000, 0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: memcpy(0xac130000, 0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: memcpy(0xac131000, 0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: memcpy(0xac132000, 0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: write(0xb17f9000, 4096)
07-12 11:36:37.659   315  6301 V AudioCache: memcpy(0xac133000, 0xb17f9000, 4096)
07-12 11:36:37.660   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-12 11:36:37.660   315  6301 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-12 11:36:37.660   315  6301 V AwesomePlayer: postAudioEOS() 
07-12 11:36:37.660   315  6301 V AudioCache: write(0xb17f9000, 280)
07-12 11:36:37.660   315  6301 V AudioCache: memcpy(0xac134000, 0xb17f9000, 280)
07-12 11:36:37.661   315  6298 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-12 11:36:37.661   315  6298 V AwesomePlayer: onStreamDone
07-12 11:36:37.661   315  6298 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-12 11:36:37.661   315  6298 V AudioCache: notify(0xb1432180, 2, 0, 0)
07-12 11:36:37.661   315  6298 V AudioCache: playback complete
07-12 11:36:37.661   315  6298 V AwesomePlayer: pause_l() 
07-12 11:36:37.661   315  6298 V AudioCache: notify(0xb1432180, 7, 0, 0)
07-12 11:36:37.661   315  6298 V AudioCache: ignored
07-12 11:36:37.661   315  6298 V AwesomePlayer: cancelPlayerEvents
07-12 11:36:37.661   315  1766 V AudioCache: wait - success
07-12 11:36:37.661   315  1766 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-12 11:36:37.661   315  6298 D AudioPlayer: Pause Playback at 1068125
07-12 11:36:37.671   315  1766 V AwesomePlayer: reset_l() 
07-12 11:36:37.671   315  1766 V AudioCache: notify(0xb1432180, 8, 0, 0)
07-12 11:36:37.671   315  1766 V AudioCache: ignored
07-12 11:36:37.671   315  1766 V AwesomePlayer: cancelPlayerEvents
07-12 11:36:37.671   315  1766 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-12 11:36:37.671   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-12 11:36:37.671   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-12 11:36:37.671   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-12 11:36:37.671   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-12 11:36:37.671   31,5  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
07-12 11:36:37.671   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-12 11:36:37.672   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-12 11:36:37.672   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-12 11:36:37.672   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-12 11:36:37.672   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-12 11:36:37.672   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-12 11:36:37.672   315  6300 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-12 11:36:37.672   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-12 11:36:37.672   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-12 11:36:37.672   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-12 11:36:37.673   315  1766 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-12 11:36:37.673   315  1766 D AudioPlayer: AudioPlayer releasing audio source
07-12 11:36:37.673   315  1766 D AudioPlayer: AudioPlayer done releasing audio source
07-12 11:36:37.673   315  1766 V AwesomePlayer: reset_l() 
07-12 11:36:37.673   315  1766 V AwesomePlayer: cancelPlayerEvents
07-12 11:36:37.673   315  1766 V AwesomePlayer: ~AwesomePlayer call
07-12 11:36:37.673   315  1766 V AwesomePlayer: reset_l() 
07-12 11:36:37.673   315  1766 V AwesomePlayer: cancelPlayerEvents
07-12 11:36:37.673  6237  6291 V SoundPool: close(31)
07-12 11:36:37.673  6237  6291 V SoundPool: pointer = 0x9fe3f000, size = 205080, sampleRate = 48000, numChannels = 2
07-12 11:36:37.674  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-12 11:36:37.674  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-12 11:36:37.676  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:541
07-12 11:36:37.681  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.690  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:36:37.695  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.699  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-12 11:36:37.699  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.703  6237  6237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-12 11:36:37.704  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-12 11:36:37.709  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.712  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.716  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-12 11:36:37.716  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.717  6237  6237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-12 11:36:37.719  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.721  6151  6151 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-12 11:36:37.724  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-12 11:36:37.725  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.731   310  6287 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-12 11:36:37.738  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-12 11:36:37.741  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-12 11:36:37.742  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.742  6237  6237 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-12 11:36:37.742  6237  6237 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-12 11:36:37.743  6237  6237 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-12 11:36:37.745  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-12 11:36:37.746  6203  6204 E QC-QMI  : qmi_client [6203] 13: failed to locate client data
07-12 11:36:37.747  6151  6151 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-12 11:36:37.747  1031  1517 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-12 11:36:37.747   456   456 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-12 11:36:37.747   456   456 E QC-QMI  : QMUX qmux_client_id=13 not found in qmux client list, unable to remove
07-12 11:36:37.747  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-12 11:36:37.748  1031  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-12 11:36:37.748  1031  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-12 11:36:37.748  1031  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-12 11:36:37.748  1031  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-12 11:36:37.749  6151  6151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-12 11:36:37.749  1031  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
07-12 11:36:37.749  1031  1524 D ConnectivityService: identical MTU - not setting
07-12 11:36:37.749  1031  1524 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-12 11:36:37.749  1031  1524 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:37.749  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:37.749  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:37.750  1031  1524 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:37.750  1581  2087 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-12 11:36:37.750  6071  6071 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.753   310  6292 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
07-12 11:36:37.759  6071  6071 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:37.763  6237  6237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-12 11:36:37.763  6237  6237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-12 11:36:37.764  6237  6237 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-12 11:36:37.764  6237  6237 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-12 11:36:37.764  6237  6237 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,07-12 11:36:37.773   310  6287 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-12 11:36:37.878  6302  6302 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-12 11:36:37.892  5960  5960 I UEI.SmartControl: Supports setup maps: true
07-12 11:36:37.895  5960  5960 D UEI.SmartControl: QS start statue = true Error code = 0
07-12 11:36:37.895  5960  5960 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-12 11:36:37.895  5960  5960 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-12 11:36:37.895  5960  5960 I UEI.SmartControl: ### init IR Blaster...
07-12 11:36:37.895  6303  6303 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-12 11:36:37.903  5960  5960 D serial_port: Configuring serial port
07-12 11:36:37.904  5960  5960 E UEI.SmartControl: UEIBLaster setting for 616
07-12 11:36:37.904  5960  5960 I UEI.SmartControl: Setting serial record hearder size = 2
07-12 11:36:37.904  5960  5960 I UEI.SmartControl: configuring settings for MAXQ616
07-12 11:36:37.904  5960  5960 I UEI.SmartControl: Get version...
,07-12 11:36:37.908  6046  6095 I bt_vendor: bluetooth satus is on
07-12 11:36:37.908  6046  6095 D bt_hci_bdroid: preload
07-12 11:36:37.908  6046  6185 D bt_userial_mct: userial_open(port:0)
07-12 11:36:37.908  6046  6185 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-12 11:36:37.912  6046  6185 I bt_vendor: Done intiailizing UART
07-12 11:36:37.913  6046  6185 I bt_vendor: Done intiailizing UART
07-12 11:36:37.913  6046  6185 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-12 11:36:37.913  6046  6185 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-12 11:36:37.913  6046  6183 I bt-btu  : btu_task received preload complete event
07-12 11:36:37.914  6046  6306 D bt_userial_mct: Entering userial_read_thread()
07-12 11:36:37.914  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-12 11:36:37.914  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-12 11:36:37.915  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_HCI
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_BNEP
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 11:36:37.918  6046  6183 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 11:36:37.920  5960  6305 D UEI.SmartControl: serial port data available: 21
07-12 11:36:37.945  6046  6183 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-12 11:36:37.945  6046  6183 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014b061 
07-12 11:36:37.945  6046  6183 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014b061 
,07-12 11:36:37.947  5960  5960 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-12 11:36:37.947  5960  5960 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-12 11:36:37.947  5960  5960 I UEI.SmartControl: QS saving settings...
07-12 11:36:37.947  5960  5960 D UEI.SmartControl: IR Blaster version: 25672567
07-12 11:36:37.964  5960  6305 D UEI.SmartControl: serial port data available: 4
,07-12 11:36:37.974  6046  6098 E bt-btif : Calling BTA_HhEnable
07-12 11:36:37.974  6046  6098 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-12 11:36:37.974  6046  6098 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-12 11:36:37.974  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-12 11:36:37.974  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-12 11:36:37.974  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-12 11:36:37.975  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-12 11:36:37.975  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-12 11:36:37.976  6046  6098 D BluetoothAdapterProperties: Name is: G3
07-12 11:36:37.976  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-12 11:36:37.976  6046  6098 D BluetoothAdapterProperties: Scan Mode:20
07-12 11:36:37.976  6046  6098 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:36:37.976  6046  6098 D bt_hci_bdroid: postload
,07-12 11:36:37.977  6046  6183 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-12 11:36:37.977  6046  6185 D bt_hci_bdroid: Used up Tx Cmd credits
07-12 11:36:37.977  6046  6185 D bt_hci_bdroid: Used up Tx Cmd credits
07-12 11:36:37.977  6046  6185 D bt_hci_bdroid: Used up Tx Cmd credits
07-12 11:36:37.982  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
07-12 11:36:37.983  6046  6183 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-12 11:36:37.983  6046  6183 W bt-smp  : Plain text(LSB ~ MSB) = b0 da 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-12 11:36:37.983  6046  6183 W bt-smp  : Encrypted text(LSB ~ MSB) = ed 7b a8 a7 9e ae a6 68 32 35 6d fd cd e0 b6 7b 
07-12 11:36:37.983  6046  6183 W bt-btm  : Stopping oneshot timer
07-12 11:36:37.983  6046  6185 D bt_hci_bdroid: Used up Tx Cmd credits
07-12 11:36:37.984  6046  6185 D bt_hci_bdroid: Used up Tx Cmd credits
07-12 11:36:37.984  6046  6185 D bt_hci_bdroid: Used up Tx Cmd credits
07-12 11:36:37.984  6046  6098 D bte_conf: Device ID record 1 : primary
07-12 11:36:37.984  6046  6098 D bte_conf:   vendorId            = 00c4
07-12 11:36:37.984  6046  6098 D bte_conf:   vendorIdSource      = 0001
07-12 11:36:37.984  6046  6098 D bte_conf:   product             = 13a1
07-12 11:36:37.984  6046  6098 D bte_conf:   version             = 1000
07-12 11:36:37.984  6046  6098 D bte_conf:   clientExecutableURL = 
07-12 11:36:37.984  6046  6098 D bte_conf:   serviceDescription  = 
07-12 11:36:37.984  6046  6098 D bte_conf:   documentationURL    = 
,07-12 11:36:37.984  6046  6098 D bte_conf: bte_load_did_conf no section named DID2.
07-12 11:36:37.985  6046  6185 D bt_hci_bdroid: Used up Tx Cmd credits
07-12 11:36:37.985  6046  6306 E bt_mct  : hci lib postload completed
07-12 11:36:37.986  6046  6098 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 11:36:37.986  6046  6095 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-12 11:36:37.986  6046  6095 D BluetoothAdapterProperties: ScanMode =  20
07-12 11:36:37.986  6046  6095 D BluetoothAdapterProperties: State =  11
07-12 11:36:37.986  6046  6095 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-12 11:36:37.987  6046  6095 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-12 11:36:37.987  6046  6095 D BluetoothAdapterProperties: Setting state to 12
07-12 11:36:37.987  6046  6095 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 11:36:37.987  6046  6098 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-12 11:36:37.988  1031  1111 D BluetoothManagerService: Message: 60
07-12 11:36:37.988  1031  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,07-12 11:36:37.988  1031  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 5 receivers.
07-12 11:36:37.989  6046  6095 I BluetoothAdapterState: Entering On State
07-12 11:36:37.981  6309  6309 W sh      : type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:37.981  6309  6309 W sh      : type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-12 11:36:37.997  1832  4029 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:37.997  1031  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:37.998  1832  4014 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:37.998  1832  2432 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:37.998  1031  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:36:38.002  1031  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-12 11:36:38.002  1031  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-12 11:36:38.004  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:38.005  1922  2104 D LGBluetoothAPIService: Message: 1
07-12 11:36:38.005  1922  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-12 11:36:38.005  6046  6183 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-12 11:36:38.005  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-12 11:36:38.005  6046  6183 W bt-smp  : Plain text(LSB ~ MSB) = 1b 74 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-12 11:36:38.005  6046  6183 W bt-smp  : Encrypted text(LSB ~ MSB) = ff c0 22 1a 41 6d cf e5 26 60 1e 37 07 29 35 88 
07-12 11:36:38.005  6046  6183 W bt-btm  : Stopping oneshot timer
,07-12 11:36:38.007  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-12 11:36:38.008  1031  1111 D BluetoothManagerService: Message: 40
07-12 11:36:38.008  1031  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-12 11:36:38.010  5748  5748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-12 11:36:38.010  5748  5748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:38.010  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:38.010  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:38.010  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:38.010  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:38.010  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:36:38.010  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:36:38.010  5748  5748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 11:36:38.010  6046  6095 D LGBluetoothServiceAdapter: [BTUI] OnState
07-12 11:36:38.010  6046  6095 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-12 11:36:38.011  6046  6095 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-12 11:36:38.011  6046  6095 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-12 11:36:38.012  1922  2104 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-12 11:36:38.012  6046  6046 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:38.012  6046  6046 D BluetoothMapService: STATE_ON
07-12 11:36:38.013  6046  6046 V BluetoothMapService: Handler(): got msg=1
07-12 11:36:38.013  6046  6046 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-12 11:36:38.013  5748  5748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 11:36:38.017  6046  6314 D BluetoothMapMasInstance: MAS initSocket()
,07-12 11:36:38.021  6046  6183 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-12 11:36:38.021  6046  6183 W bt-smp  : Plain text(LSB ~ MSB) = f8 00 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-12 11:36:38.021  6046  6183 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 5e c8 91 c6 cc cf 57 e7 6c 6c f7 de 2c e5 c2 
07-12 11:36:38.021  6046  6183 W bt-btm  : Stopping oneshot timer
07-12 11:36:38.023  6046  6314 D BluetoothMapMasInstance:   masId = 00
07-12 11:36:38.023  6046  6314 D BluetoothMapMasInstance:   msgTypes = 0e
07-12 11:36:38.023  6046  6314 D BluetoothMapMasInstance:   masName = SMS/MMS
07-12 11:36:38.023  6046  6314 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-12 11:36:38.023  5960  6312 I UEI.SmartControl: Device manager: loading config....
07-12 11:36:38.024  5960  6312 D UEI.SmartControl: ----------- loading internal config...
07-12 11:36:38.024  1031  1629 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-12 11:36:38.025  6046  6314 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:38.027  6046  6314 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-12 11:36:38.027  6046  6314 V BluetoothMapMasInstance: Succeed to create listening socket 
07-12 11:36:38.027  6046  6314 D BluetoothMapMasInstance: Accepting socket connection...
,07-12 11:36:38.028  5960  6312 E UEI.SmartControl: Loading SETTINGS...
07-12 11:36:38.030  6046  6183 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-12 11:36:38.030  6046  6183 W bt-smp  : Plain text(LSB ~ MSB) = 63 9b 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-12 11:36:38.030  6046  6183 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f 81 c7 02 3a ed 0e 7a a1 d7 f5 a4 cb e8 e4 a0 
07-12 11:36:38.030  6046  6183 W bt-btm  : Stopping oneshot timer
,07-12 11:36:38.031  5960  5960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-12 11:36:38.032  5960  5960 E UEI.SmartControl: Services init done
07-12 11:36:38.032  5960  5960 D UEI.SmartControl: QS Service init finished
07-12 11:36:38.033  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:38.033  6046  6046 V BluetoothPbapService: Pbap Service onCreate
07-12 11:36:38.033  6046  6046 V BluetoothPbapService: Starting PBAP service
07-12 11:36:38.034  6046  6046 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-12 11:36:38.034  5960  5960 D UEI.SmartControl: QS Service version name: 2.1.91
07-12 11:36:38.034  5960  5960 D UEI.SmartControl: QS Service version code: 201091
07-12 11:36:38.034  6046  6046 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:38.035  6046  6046 V BluetoothPbapService: state: 12
07-12 11:36:38.035  5960  5960 D UEI.SmartControl: Service requested: Control
07-12 11:36:38.036  6071  6071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-12 11:36:38.036  6046  6046 D LGBluetoothAPIServer: [BTUI] onCreate()
07-12 11:36:38.037  6046  6046 D LGBluetoothAPIServer: [BTUI] onBind()
07-12 11:36:38.038  6237  6237 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-12 11:36:38.038  5960  5975 I UEI.SmartControl: ------ IControl API: 11
07-12 11:36:38.038  5960  5960 D UEI.SmartControl: Internal service binding...
07-12 11:36:38.038  5960  5975 D UEI.SmartControl: File observer start...
07-12 11:36:38.039  5960  5975 E UEI.SmartControl: IR Port is disabled: false
07-12 11:36:38.039  5960  5975 D UEI.SmartControl: Starting file observer...
07-12 11:36:38.039  5960  5975 I UEI.SmartControl: Registering callback...
07-12 11:36:38.039  1922  1922 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-12 11:36:38.039  6046  6046 V BluetoothPbapService: Handler(): got msg=1
07-12 11:36:38.039  1922  2104 D LGBluetoothAPIService: Message: 100
07-12 11:36:38.039  1922  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-12 11:36:38.040  6046  6095 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-12 11:36:38.040  6046  6183 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-12 11:36:38.040  6046  6183 W bt-smp  : Plain text(LSB ~ MSB) = 90 65 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-12 11:36:38.040  6046  6183 W bt-smp  : Encrypted text(LSB ~ MSB) = cb ec b2 d5 2c 3c 2e 62 ee 5f 20 f3 ae e4 1f fb 
07-12 11:36:38.040  6046  6183 W bt-btm  : Stopping oneshot timer
07-12 11:36:38.041  6046  6046 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,07-12 11:36:38.041  5960  5976 I UEI.SmartControl: ------ IControl API: 19
07-12 11:36:38.042  5960  5976 I UEI.SmartControl: Registering Services Ready callback...
07-12 11:36:38.042  6046  6046 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-12 11:36:38.043  6046  6046 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:38.043  6046  6046 V BluetoothPbapReceiver: ***********state = 12
07-12 11:36:38.044  6046  6317 V BluetoothPbapService: Pbap Service initSocket
07-12 11:36:38.044  1031  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-12 11:36:38.045  2054  2054 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 11:36:38.045  2054  2054 D c       : Getting all permits...
07-12 11:36:38.045  2054  2054 D a       : Opening database...
07-12 11:36:38.049  2054  2054 D a       : Opening database auth.proximity.permit_store...
07-12 11:36:38.050  2054  2054 D a       : Closing database...
07-12 11:36:38.056  6046  6317 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:38.059  6046  6317 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-12 11:36:38.059  6046  6317 V BluetoothPbapService: Succeed to create listening socket 
07-12 11:36:38.059  6046  6317 V BluetoothPbapService: Accepting socket connection...
07-12 11:36:38.059  6071  6071 D LocalBluetoothProfileManager: Adding local A2DP profile
07-12 11:36:38.061  1031  1111 D BluetoothManagerService: Message: 30
07-12 11:36:38.062  6071  6071 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-12 11:36:38.064  1031  1111 D BluetoothManagerService: Message: 30
07-12 11:36:38.068  1031  1111 D BluetoothManagerService: Message: 30
,07-12 11:36:38.071  1031  1111 D BluetoothManagerService: Message: 30
07-12 11:36:38.073  6071  6071 D LocalBluetoothProfileManager: Adding local MAP profile
07-12 11:36:38.074  6071  6071 D BluetoothMap: Create BluetoothMap proxy object
07-12 11:36:38.075  1031  1111 D BluetoothManagerService: Message: 30
07-12 11:36:38.079  1031  1111 D BluetoothManagerService: Message: 30
07-12 11:36:38.080  6071  6071 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-12 11:36:38.080  6046  6046 V BluetoothPbapService: Pbap Service onBind
,07-12 11:36:38.082  6321  6321 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-12 11:36:38.084  6071  6071 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
07-12 11:36:38.086  6071  6071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-12 11:36:38.092  6071  6071 D DockEventReceiver: finishStartingService: stopping service
07-12 11:36:38.095  6071  6071 D BluetoothA2dp: Proxy object connected
07-12 11:36:38.095  6071  6071 D A2dpProfile: Bluetooth service connected
,07-12 11:36:38.128  6071  6071 D BluetoothHeadset: Proxy object connected
07-12 11:36:38.129  6071  6071 D HeadsetProfile: Bluetooth service connected
,07-12 11:36:38.131  6071  6071 D BluetoothInputDevice: Proxy object connected
07-12 11:36:38.131  6071  6071 D HidProfile: Bluetooth service connected
07-12 11:36:38.132  6071  6071 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 11:36:38.133  6071  6071 D PanProfile: Bluetooth service connected
07-12 11:36:38.134  6071  6071 D BluetoothMap: Proxy object connected
07-12 11:36:38.134  6071  6071 D MapProfile: Bluetooth service connected
07-12 11:36:38.134  6071  6071 D BluetoothMap: getConnectedDevices()
07-12 11:36:38.135  6046  6104 V BluetoothMapService: getConnectedDevices()
07-12 11:36:38.135  6071  6071 D BluetoothPbap: Proxy object connected
07-12 11:36:38.136  6071  6071 D PbapServerProfile: Bluetooth service connected
07-12 11:36:38.136  6071  6071 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-12 11:36:38.138  6071  6071 D BluetoothPermissionRequest: onReceive
07-12 11:36:38.140  6071  6071 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-12 11:36:38.141  5960  6312 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-12 11:36:38.142  6071  6071 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-12 11:36:38.143  6071  6071 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-12 11:36:38.145  6046  6046 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-12 11:36:38.146  6046  6046 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-12 11:36:38.151  6046  6046 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-12 11:36:38.151  6046  6098 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:36:38.152  6046  6098 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,07-12 11:36:38.154  6046  6098 D BluetoothAdapterProperties: Scan Mode:21
07-12 11:36:38.154  6046  6098 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-12 11:36:38.155  5960  6311 I UEI.SmartControl: Notify AllClients services are ready: 0
07-12 11:36:38.156  5960  6311 D UEI.SmartControl: -----service ready thread exits
07-12 11:36:38.156  6237  6255 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-12 11:36:38.156  6237  6285 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-12 11:36:38.161  6237  6285 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-12 11:36:38.161  6237  6237 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-12 11:36:38.162  6046  6046 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-12 11:36:38.162  6237  6237 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-12 11:36:38.162  6046  6046 V BtOppService: onCreate
07-12 11:36:38.162  5960  5975 I UEI.SmartControl: ------ IControl API: 8
07-12 11:36:38.163  5748  5748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:36:38.164  6237  6237 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-12 11:36:38.164  6237  6237 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-12 11:36:38.164  6237  6237 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-12 11:36:38.164  6237  6237 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-12 11:36:38.164  6046  6046 V BluetoothOppNotification: send message
,07-12 11:36:38.166  6237  6237 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-12 11:36:38.166  6046  6046 V BtOppService: Starting RfcommListener
07-12 11:36:38.167  6237  6237 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-12 11:36:38.172  6046  6046 D BluetoothOppPreference: Dumping Names:  
,07-12 11:36:38.172  6046  6046 D BluetoothOppPreference: {}
07-12 11:36:38.172  6046  6046 D BluetoothOppPreference: Dumping Channels:  
07-12 11:36:38.172  6046  6046 D BluetoothOppPreference: {}
07-12 11:36:38.172  6237  6237 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-12 11:36:38.173  6237  6237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-12 11:36:38.174  6046  6046 V BtOppService: onStartCommand
07-12 11:36:38.174  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-12 11:36:38.174  6237  6237 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-12 11:36:38.174  6046  6328 V BtOppService: Deleted complete outbound shares, number =  0
07-12 11:36:38.175  6046  6331 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-12 11:36:38.175  6046  6331 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-12 11:36:38.176  6046  6328 V BtOppService: Deleted complete inbound failed shares, number = 0
07-12 11:36:38.176  6046  6328 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-12 11:36:38.176  6046  6046 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:38.177  6046  6046 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-12 11:36:38.177  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-12 11:36:38.177  6046  6328 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22589609 on behalf of 
07-12 11:36:38.177  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-12 11:36:38.179  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,07-12 11:36:38.179  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-12 11:36:38.179  6046  6046 V BluetoothOppNotification: new notify threadi!
07-12 11:36:38.179  6046  6046 V BluetoothOppNotification: send delay message
07-12 11:36:38.180  6237  6237 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1468316198179]
07-12 11:36:38.180  6046  6046 V BtOppService: start RfcommListener
07-12 11:36:38.180  6046  6332 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-12 11:36:38.181  6046  6332 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3164d00e on behalf of 
07-12 11:36:38.181  6046  6331 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38250a2f on behalf of 
07-12 11:36:38.181  6046  6046 V BtOppService: RfcommListener started
07-12 11:36:38.181  6046  6046 V BtOppService: ContentObserver received notification
07-12 11:36:38.182  6046  6046 V BtOppService: ContentObserver received notification
07-12 11:36:38.183  6046  6334 V BtOppRfcommListener: Starting RFCOMM listener....
07-12 11:36:38.183  1031  1972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:38.184  6046  6334 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:38.184  6237  6237 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-12 11:36:38.185  1031  2012 I ActivityManager: Killing 5719:com.google.android.apps.docs/u0a61 (adj 15): empty #17
07-12 11:36:38.185  6046  6334 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
07-12 11:36:38.186  6046  6334 V BtOppRfcommListener: Started RFCOMM listener....
07-12 11:36:38.186  6046  6334 I BtOppRfcommListener: Accept thread started.
07-12 11:36:38.186  6046  6334 V BtOppRfcommListener: Accepting connection...
07-12 11:36:38.186  6046  6331 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-12 11:36:38.187  6046  6331 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-12 11:36:38.187  6046  6331 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39d83c on behalf of 
07-12 11:36:38.188  6046  6331 V BluetoothOppNotification: update too frequent, put in queue
07-12 11:36:38.188  6046  6331 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-12 11:36:38.190  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
07-12 11:36:38.190  6046  6046 V BluetoothFtpService: Ftp Service onCreate
07-12 11:36:38.190  6046  6046 I BluetoothFtpService: Ftp Service onCreate
07-12 11:36:38.190  6046  6046 V BluetoothFtpService: Ftp Service onStartCommand
07-12 11:36:38.190  6046  6046 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:38.190  6046  6046 V BluetoothFtpService: Starting Listening on sockets
07-12 11:36:38.190  6046  6046 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-12 11:36:38.191  6046  6046 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-12 11:36:38.191  6046  6046 V BluetoothSapReceiver: SapReceiver onReceive 
07-12 11:36:38.191  6046  6046 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:38.191  6046  6046 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-12 11:36:38.191  6046  6046 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-12 11:36:38.191  6046  6332 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-12 11:36:38.192  6046  6332 V BluetoothOppPro,vider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-12 11:36:38.192  6046  6332 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5a1df1a on behalf of 
07-12 11:36:38.193  6046  6332 V BluetoothOppNotification: outbound: succ-0  fail-0
07-12 11:36:38.194  6046  6332 V BluetoothOppNotification: outbound notification was removed.
07-12 11:36:38.194  6046  6332 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-12 11:36:38.195  6046  6332 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20021a4b on behalf of 
07-12 11:36:38.195  6046  6332 V BluetoothOppNotification: inbound: succ-0  fail-0
07-12 11:36:38.201  6046  6332 V BluetoothOppNotification: inbound notification was removed.
,07-12 11:36:38.201  6046  6332 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-12 11:36:38.275  1031  2011 I art     : Explicit concurrent mark sweep GC freed 78128(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.456ms total 70.838ms
,07-12 11:36:38.278  6237  6333 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
07-12 11:36:38.279  6046  6332 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25ea3c28 on behalf of 
07-12 11:36:38.300  6046  6046 V BluetoothFtpService: Handler(): got msg=1
,07-12 11:36:38.301  1031  2032 W libprocessgroup: failed to open /acct/uid_10061/pid_5719/cgroup.procs: No such file or directory
07-12 11:36:38.301  6046  6046 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-12 11:36:38.301  6046  6046 V BluetoothFtpService: Ftp Service initSocket
07-12 11:36:38.315  1031  1629 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:38.316  6046  6046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:38.317  6046  6046 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-12 11:36:38.318  6237  6237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-12 11:36:38.319  6046  6335 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-12 11:36:38.319  6237  6237 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-12 11:36:38.323  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-12 11:36:38.323  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-12 11:36:38.323  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-12 11:36:38.323  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-12 11:36:38.324  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-12 11:36:38.332  6046  6046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35322467
,07-12 11:36:38.332  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
07-12 11:36:38.333  6046  6046 V BluetoothSapService: Sap Service onCreate
07-12 11:36:38.337  6046  6046 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:38.337  6046  6046 V BluetoothSapService: state: 12
07-12 11:36:38.337  6046  6046 V BluetoothSapService: Starting SAP server process
07-12 11:36:38.338  6046  6046 V BluetoothSapService: SAP Service startRfcommListenerThread
07-12 11:36:38.339   310   882 D LGDataListener: argv[0]=dsqncommand
07-12 11:36:38.339   310   882 D LGDataListener: argv[1]=wlan0
07-12 11:36:38.339   310   882 D LGDataListener: argv[2]=1
07-12 11:36:38.339  1031  6289 D LocSvc_java: NTP server : europe.pool.ntp.org
07-12 11:36:38.339   310   882 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-12 11:36:38.340  1031  6289 D LocSvc_java: NTP server returned: 1468316198442 (Tue Jul 12 11:36:38 GMT+02:00 2016) reference: 104698 certainty: 292 system time offset: 103
07-12 11:36:38.340  1031  6289 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
07-12 11:36:38.340  6046  6338 V BluetoothSapService: Sap Service initRfcommSocket
07-12 11:36:38.341  1031  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:38.341  1031  1109 D DSQN    : DSQM DsqnNotification wlan0  1
07-12 11:36:38.341  1031  1109 D DSQN    : start to monitor internet connection
07-12 11:36:38.331  6336  6336 W sapd    : type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:38.342  6046  6338 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:38.331  6336  6336 W sapd    : type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-12 11:36:38.342  6046  6338 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-12 11:36:38.343  6046  6338 V BluetoothSapService: Succeed to create listening socket 
07-12 11:36:38.343  6046  6338 V BluetoothSapService: Accepting socket connection...
07-12 11:36:38.347  6336  6336 V BT_SAP  : Event pipe created
07-12 11:36:38.348  6336  6336 V BT_SAP  : create_server_socket qcom.sap.server
07-12 11:36:38.348  6336  6336 V BT_SAP  : created socket fd 6
,07-12 11:36:38.367  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:36:38 GMT], X-Android-Received-Millis=[1468316198367], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1468316198339]}
07-12 11:36:38.367  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-12 11:36:38.367  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,07-12 11:36:38.367  1031  1524 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:38.368  1031  1524 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-12 11:36:38.368  1031  1524 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:36:38.368  1031  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:38.368  1031  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-12 11:36:38.368  1031  1524 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
07-12 11:36:38.368  1031  1524 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:38.368  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:38.368  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:38.369  1031  1524 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:38.369  1031  1524 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:38.369  1031  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-12 11:36:38.369  1031  1517 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:38.369  1031  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:36:38.370  1832  1832 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:38.371  1832  1832 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-12 11:36:38.371  1581  2087 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-12 11:36:38.386  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-12 11:36:38.386  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:36:38.387  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:36:39.181  6046  6046 V BluetoothOppNotification: new notify threadi!
07-12 11:36:39.182  6046  6046 V BluetoothOppNotification: send delay message
,07-12 11:36:39.185  6046  6346 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-12 11:36:39.188  6046  6346 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27baf2d4 on behalf of 
07-12 11:36:39.190  6046  6346 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-12 11:36:39.192  6046  6346 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-12 11:36:39.193  6046  6346 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@48e2c7d on behalf of 
07-12 11:36:39.194  6046  6346 V BluetoothOppNotification: outbound: succ-0  fail-0
07-12 11:36:39.198  6046  6346 V BluetoothOppNotification: outbound notification was removed.
,07-12 11:36:39.198  6046  6346 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-12 11:36:39.200  6046  6346 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27c53772 on behalf of 
07-12 11:36:39.203  6046  6346 V BluetoothOppNotification: inbound: succ-0  fail-0
07-12 11:36:39.204  6046  6346 V BluetoothOppNotification: inbound notification was removed.
07-12 11:36:39.204  6046  6346 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-12 11:36:39.217  6046  6346 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a0987c3 on behalf of 
,07-12 11:36:39.338  1581  1581 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-12 11:36:39.338  1581  1581 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-12 11:36:39.644  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2088] from screen [on:0 period:-562615588] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:36:39.652  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:-562615581] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:36:39.652  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:36:39.695  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:36:40.269  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:36:40.269  5748  5811 I jxcore-log: 
,07-12 11:36:40.547  1031  1519 V WifiInternetCheck: Single check msg out of sync, ignoring.
,07-12 11:36:40.586  1031  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:36:40.592  1031  1111 D Tethering: MasterInitialState.processMessage what=3
07-12 11:36:40.592  5748  5748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:36:40.598   310  6347 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:36:40.598   310  6347 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,07-12 11:36:40.601  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:40.610  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-12 11:36:40.616  5017  5038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-12 11:36:40.622  5113  5113 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-12 11:36:40.663   310  6347 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
,07-12 11:36:40.684  1031  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.686  2054  2054 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:40.689  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:36:40.689  5748  5811 I jxcore-log: 
07-12 11:36:40.690  1031  1806 D AlarmManagerService: Setting time of day to sec=1468316201
07-12 11:36:41.069  1031  1806 W AlarmManagerService: Unable to set rtc to 1468316201: Invalid argument
07-12 11:36:41.077   310  6363 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:36:41.077   310  6363 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,07-12 11:36:41.080  1031  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
07-12 11:36:41.080  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:41.080  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:41.080  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-12 11:36:41.080  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:41.081  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,07-12 11:36:41.097  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:36:41.097  5748  5811 I jxcore-log: 
07-12 11:36:41.100  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:36:41.100  5748  5811 I jxcore-log: 
07-12 11:36:41.116  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:36:41.116  5748  5811 I jxcore-log: 
07-12 11:36:41.116  1031  2011 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6365 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-12 11:36:41.122  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:36:41.122  1581  1581 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
07-12 11:36:41.123  1581  1581 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-12 11:36:41.123  1031  1091 E GpsLocationProvider: No APN found to select.
07-12 11:36:41.124  4584  4584 I CalendarProvider2: onReceive() android.intent.action.TIME_SET
07-12 11:36:41.124  4584  4584 D CalendarProvider2: Scheduling check of next Alarm
07-12 11:36:41.125  1922  1922 I SecureClockService: Intent.ACTION_TIME_CHANGED 
07-12 11:36:41.125  2711  2711 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
07-12 11:36:41.126  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:36:41.126  5748  5811 I jxcore-log: 
07-12 11:36:41.126  2711  2711 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-07-12 11:36:41...... Request
07-12 11:36:41.126  2711  2711 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 22, new day : false...... Request
07-12 11:36:41.126  2711  2711 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 22
07-12 11:36:41.126  2711  2711 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 2
07-12 11:36:41.127  2711  2711 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-07-12 11:36:41
07-12 11:36:41.130  1031  1992 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
07-12 11:36:41.135  2013  2013 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=12 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
07-12 11:36:41.138  2013  2013 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 12
07-12 11:36:41.139  2013  2013 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 12
07-12 11:36:41.140  2013  2013 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-12 11:36:41.155  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:36:41.196  6365  6365 I AppUp4:AppBoxCP: onCreate
07-12 11:36:41.197  6365  6365 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-12 11:36:41.206  6365  6365 I AppUp4:DB:  setFingerPrint start
,07-12 11:36:41.206  6365  6365 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-12 11:36:41.214  6365  6365 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-12 11:36:41.214  6365  6365 I AppUp4:DB:  SDK version = 21
07-12 11:36:41.214  6365  6365 I AppUp4:DB:  beforefinger == newfinger no write in DB
,07-12 11:36:41.216  6365  6365 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-12 11:36:41.217  6365  6365 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-12 11:36:41.217  6365  6365 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:41.219  6365  6365 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-12 11:36:41.219  6365  6365 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-12 11:36:41.227  6365  6365 I AppUp4:CustModeStarterReceiver: onReceive
,07-12 11:36:41.278  6365  6365 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:41.278  6365  6365 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-12 11:36:41.284  6365  6365 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@11199026
07-12 11:36:41.284  6365  6365 D AppUp4:CustFacade: isCustomizationCompleted : false
07-12 11:36:41.285  6365  6365 D AppUp4:CustFacade: isPhone : true
07-12 11:36:41.285  6365  6365 D AppUp4:CustModeStarterReceiver: begin check event
07-12 11:36:41.285  6365  6365 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-12 11:36:41.285  6365  6365 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-12 11:36:41.293  6365  6382 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,07-12 11:36:41.293  6365  6382 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-12 11:36:41.293  6365  6382 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-12 11:36:41.294  1031  1629 I ActivityManager: Killing 5830:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
07-12 11:36:41.326  1031  6102 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,07-12 11:36:41.326  1031  6102 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-12 11:36:41.328  1031  1517 E WifiStateMachine:  ConnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
07-12 11:36:41.329  1031  1517 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
,07-12 11:36:41.330  1031  1517 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
07-12 11:36:41.331  1031  1517 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
07-12 11:36:41.332  1031  1517 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
07-12 11:36:41.333  1031  1517 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-12 11:36:41.429  3072  3072 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:41.430  3072  3072 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-12 11:36:41.431  1031  1052 W libprocessgroup: failed to open /acct/uid_10080/pid_5830/cgroup.procs: No such file or directory
07-12 11:36:41.433  3072  3072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-12 11:36:41.444  3072  3072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-12 11:36:41.451  2804  2804 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:41.453  3072  6384 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-12 11:36:41.456  3072  6384 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
07-12 11:36:41.456  3072  6385 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:41.456  3072  6385 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-12 11:36:41.458  2804  2804 V DownloadManager: DownloadService onCreate
07-12 11:36:41.460  2804  6386 I DownloadManager: in removeSpuriousFiles
,07-12 11:36:41.460  2804  6386 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
07-12 11:36:41.461  2804  6386 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@bb69b9d on behalf of 2804
07-12 11:36:41.461  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
07-12 11:36:41.461  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
07-12 11:36:41.461  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
07-12 11:36:41.461  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
07-12 11:36:41.461  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
07-12 11:36:41.462  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
07-12 11:36:41.462  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
07-12 11:36:41.462  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
07-12 11:36:41.462  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
07-12 11:36:41.462  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
07-12 11:36:41.462  2804  6386 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,07-12 11:36:41.462  2804  6386 I DownloadManager: in trimDatabase
07-12 11:36:41.463  2804  6386 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
07-12 11:36:41.465  2804  6386 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@18984812 on behalf of 2804
07-12 11:36:41.499   310  6363 D libc-netbsd: res_queryN name = mtalk.google.com succeed
07-12 11:36:41.500  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:36:41 GMT], X-Android-Received-Millis=[1468316201498], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1468316201082]}
07-12 11:36:41.500  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-12 11:36:41.500  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-12 11:36:41.503  1031  2012 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6390 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-12 11:36:41.505  2804  2804 V DownloadManager: DownloadService onStartCommand
,07-12 11:36:41.507  2804  6387 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
07-12 11:36:41.508  1031  1524 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
07-12 11:36:41.508  1031  1524 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-12 11:36:41.508  1031  1524 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:36:41.508  1031  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:41.508  1031  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-12 11:36:41.508  1031  1524 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
07-12 11:36:41.509  1031  1524 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:41.509  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:41.508  2804  6387 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@10665499 on behalf of 2804
07-12 11:36:41.510  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:41.510  3072  6384 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
07-12 11:36:41.511  1031  1524 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:41.511  2804  6387 V DownloadManager: processing inserted download 1
07-12 11:36:41.513  1581  2087 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-12 11:36:41.513  2804  6387 V DownloadManager: processing inserted download 4
07-12 11:36:41.514  2804  6387 V DownloadManager: processing inserted download 7
07-12 11:36:41.515  2804  6387 V DownloadManager: processing inserted download 8
07-12 11:36:41.517  3072  3072 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,07-12 11:36:41.519  2804  6387 V DownloadManager: processing inserted download 9
07-12 11:36:41.521  3072  3072 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
07-12 11:36:41.521  2804  6387 V DownloadManager: processing inserted download 10
07-12 11:36:41.521  3072  3072 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
07-12 11:36:41.524  3072  3072 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
07-12 11:36:41.525  2804  6387 V DownloadManager: processing inserted download 11
07-12 11:36:41.526  2804  6387 V DownloadManager: processing inserted download 12
07-12 11:36:41.528  2804  6387 V DownloadManager: processing inserted download 13
07-12 11:36:41.529  2804  6387 V DownloadManager: processing inserted download 14
07-12 11:36:41.530  2804  6387 V DownloadManager: processing inserted download 16
07-12 11:36:41.532  2804  2804 V DownloadManager: DownloadService onDestroy
,07-12 11:36:41.536  3072  3072 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,07-12 11:36:41.565  6390  6390 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:41.565  6390  6390 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-12 11:36:41.566  6390  6390 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-12 11:36:41.566  6390  6390 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-12 11:36:41.609  2054  6362 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-12 11:36:41.619  6390  6390 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-12 11:36:41.629  6390  6390 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-12 11:36:41.658  6390  6390 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:36:41.680  6390  6390 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:41.680  6390  6390 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-12 11:36:41.804  6390  6390 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-12 11:36:41.852  6390  6390 I HubEmail: JNI_OnLoad()
,07-12 11:36:41.852  6390  6390 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-12 11:36:41.852  6390  6390 I HubEmail: registerNatives()
07-12 11:36:41.852  6390  6390 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-12 11:36:41.852  6390  6390 I HubEmail: registerNativeMethods()
07-12 11:36:41.852  6390  6390 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-12 11:36:41.853  6390  6390 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,07-12 11:36:41.859  3112  3112 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-12 11:36:41.859  3112  3112 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:41.861  3112  3112 I LgeMiscReceiver: networkInfo.isConnected() = true
07-12 11:36:41.861  3112  3112 D PhoneState: setPdpRejectCasuse : false
07-12 11:36:41.908  1031  1051 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6421 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-12 11:36:41.916  6390  6420 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:36:41.958   310  6439 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-12 11:36:41.958   310  6439 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
07-12 11:36:41.988  6421  6421 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:41.988  6421  6421 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-12 11:36:41.990  6421  6421 D PhoneMonitor: Register our PhoneStateListener
07-12 11:36:42.000  6421  6421 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-12 11:36:42.001  6421  6421 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-12 11:36:42.006   310  6439 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,07-12 11:36:42.048  1031  1698 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6442 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:42.049  1031  1092 I ActivityManager: Killing 5847:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-12 11:36:42.078  6126  6419 V FormManager: There are no updated forms. The schedule will be deleted.
,07-12 11:36:42.084  6421  6421 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-12 11:36:42.084  6421  6421 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-12 11:36:42.085  6421  6421 D TelephonyAutoProfiling: [parse] Load xml
07-12 11:36:42.087  6126  6419 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
07-12 11:36:42.087  6421  6421 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-12 11:36:42.087  6421  6421 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-12 11:36:42.088  6421  6421 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
07-12 11:36:42.095  6421  6421 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,07-12 11:36:42.147   310  6460 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-12 11:36:42.148   310  6460 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,07-12 11:36:42.179   310  6460 D libc-netbsd: res_queryN name = www.google.com succeed
07-12 11:36:42.191   310  6462 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:36:42.191   310  6462 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-12 11:36:42.191   310  6462 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-12 11:36:42.196  1031  2012 W libprocessgroup: failed to open /acct/uid_10097/pid_5847/cgroup.procs: No such file or directory
07-12 11:36:42.221  1031  1052 I ActivityManager: Killing 5881:com.lge.eula/1000 (adj 15): empty #17
,07-12 11:36:42.245  1031  1520 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
07-12 11:36:42.296  1031  1901 W libprocessgroup: failed to open /acct/uid_1000/pid_5881/cgroup.procs: No such file or directory
07-12 11:36:42.296  1797  6463 I CheckinService: active receiver: enabled
,07-12 11:36:42.349  1797  6463 I CheckinService: Preparing to send checkin request
07-12 11:36:42.349  1797  6463 I EventLogService: Accumulating logs since 1468316132027
07-12 11:36:42.401  1797  6463 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-12 11:36:42.412  1031  1523 D WifiService: New client listening to asynchronous messages
,07-12 11:36:42.533  1031  1917 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6473 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-12 11:36:42.584  6473  6473 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 11:36:42.585  6473  6473 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-12 11:36:42.603  6473  6473 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:36:42.603  6473  6473 I MultiDex: install
07-12 11:36:42.603  6473  6473 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:36:42.640  1031  1920 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6491 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-12 11:36:42.641  1031  1920 I ActivityManager: Killing 5901:com.google.android.talk/u0a72 (adj 15): empty #17
,07-12 11:36:42.777  1031  1554 W libprocessgroup: failed to open /acct/uid_10072/pid_5901/cgroup.procs: No such file or directory
,07-12 11:36:42.805  6473  6473 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-12 11:36:42.879  6491  6491 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,07-12 11:36:42.881  6491  6491 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
07-12 11:36:42.888  6491  6491 V DrmService: Service onCreate
07-12 11:36:42.888  6491  6491 D DrmService: Received new request = 2
07-12 11:36:42.893  6491  6509 I DrmSntpClient: Start Sync process
07-12 11:36:42.893  6491  6509 D DrmSntpClient: Server : 0
,07-12 11:36:42.898   310  6510 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:36:42.898   310  6510 D libc-netbsd: res_queryN name = pool.ntp.org, class = 1, type = 1
,07-12 11:36:42.931  1031  1554 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6511 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-12 11:36:42.938   310  6510 D libc-netbsd: res_queryN name = pool.ntp.org succeed
07-12 11:36:42.957  6491  6509 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
,07-12 11:36:42.959   322   888 V ILGDrmService: eDRM_SetDRMTime +++
07-12 11:36:42.959   322   888 I LGDRM   : [DRM] SET TIME : YR=2016, MON=7, DAY=12
07-12 11:36:42.959   322   888 I LGDRM   : [DRM] SET TIME : HR=9, MIN=36, SEC=42
07-12 11:36:42.966   322   888 V ILGDrmService: eDRM_SetDRMTime ---
07-12 11:36:42.967  6491  6509 I DrmSntpClient: Synched
07-12 11:36:42.970  6491  6491 D DrmService: Completed !! request = 2
07-12 11:36:42.970  6491  6491 D DrmService: Request count = 0
,07-12 11:36:42.973  6491  6491 V DrmService: Service onDestroy
07-12 11:36:42.974  1031  1917 I ActivityManager: Killing 4584:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-12 11:36:42.997  6511  6511 I art     : Almond Protected OAT
,07-12 11:36:43.086  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3380] from screen [on:0 period:-562612147] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:36:43.088  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562612144] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:36:43.088  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:36:43.096  1031  1051 W libprocessgroup: failed to open /acct/uid_10014/pid_4584/cgroup.procs: No such file or directory
07-12 11:36:43.102  6511  6511 D WeatherApplication: removeAccount
,07-12 11:36:43.106  6511  6511 D WeatherApplication: Account.length = 0
07-12 11:36:43.107  6511  6511 E WeatherApplication: OPERATOR:OPEN
07-12 11:36:43.118  6511  6511 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:36:43
,07-12 11:36:43.124  6511  6511 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-12 11:36:43.125  6511  6511 D Weather.Utils: 2 : All the weather widget is gone.
07-12 11:36:43.128  6511  6511 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,07-12 11:36:43.131  6473  6488 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:43.132  6473  6488 D LgDataFeature: LgDataFeature() Constructor Done, null
07-12 11:36:43.132  6511  6511 D WeatherAncestor: connectivity changed - connection : true
,07-12 11:36:43.135  6511  6511 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-12 11:36:43.147  6511  6511 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-12 11:36:43.147  6511  6511 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-12 11:36:43.147  6511  6511 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,07-12 11:36:43.171  6511  6511 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-12 11:36:43.171  6511  6511 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:36:43
,07-12 11:36:43.178  6529  6529 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
07-12 11:36:43.217  6529  6529 I dex2oat : dex2oat took 38.729ms (threads: 4)
,07-12 11:36:43.230  6473  6488 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:36:43.230  6473  6488 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:36:43.230  6473  6488 I Adreno-EGL: Build Date: 12/12/14 금
07-12 11:36:43.230  6473  6488 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-12 11:36:43.230  6473  6488 I Adreno-EGL: Remote Branch: 
07-12 11:36:43.230  6473  6488 I Adreno-EGL: Local Patches: 
07-12 11:36:43.230  6473  6488 I Adreno-EGL: Reconstruct Branch: 
07-12 11:36:43.235  1031  1955 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6535 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:43.235  1031  1955 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
07-12 11:36:43.248   348   348 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 20.526ms
,07-12 11:36:43.251   315  1362 V AudioFlinger: 2127 died, releasing its sessions
07-12 11:36:43.251   315  1362 V AudioFlinger:  pid 1832 @ 0
07-12 11:36:43.251   315  1362 V AudioFlinger:  pid 3112 @ 1
07-12 11:36:43.251   315  1362 V AudioFlinger:  pid 3112 @ 2
07-12 11:36:43.270   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 20.029ms
,07-12 11:36:43.288   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 346us total 16.412ms
,07-12 11:36:43.298  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:36:43.298  5748  5811 I jxcore-log: 
07-12 11:36:43.308  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:36:43.308  5748  5811 I jxcore-log: 
,07-12 11:36:43.316  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:36:43.316  5748  5811 I jxcore-log: 
,07-12 11:36:43.335  1031  1554 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
,07-12 11:36:43.395  5960  6307 D serial_port: close(fd = 24)
07-12 11:36:43.397   278   427 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:36:43.397   278   427 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-12 11:36:43.397   278   427 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:36:43.398  6535  6555 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-12 11:36:43.398  5960  6307 I UEI.SmartControl: Serial port is closed.
07-12 11:36:43.399   278   427 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:36:43.399   278   427 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-12 11:36:43.399   278   427 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:36:43.400  6535  6555 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,07-12 11:36:43.410  5960  6315 D UEI.SmartControl: Internal timer expired: 2
07-12 11:36:43.410  5960  6315 D UEI.SmartControl: unbind internal service
07-12 11:36:43.424   278   427 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:36:43.424   278   427 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-12 11:36:43.424   278   427 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:36:43.426  6535  6560 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-12 11:36:43.429   278   427 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:36:43.429   278   427 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-12 11:36:43.429   278   427 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:36:43.435  6535  6560 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-12 11:36:43.481  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:36:43.481  5748  5811 I jxcore-log: 
,07-12 11:36:43.529  6473  6488 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:36:43.529  6473  6488 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:36:43.529  6473  6488 I Adreno-EGL: Build Date: 12/12/14 금
07-12 11:36:43.529  6473  6488 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-12 11:36:43.529  6473  6488 I Adreno-EGL: Remote Branch: 
07-12 11:36:43.529  6473  6488 I Adreno-EGL: Local Patches: 
07-12 11:36:43.529  6473  6488 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:36:43.550  6535  6535 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-12 11:36:43.556  6535  6535 I LibraryLoader: Loading: webviewchromium
07-12 11:36:43.558  6535  6535 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9551-9553)
07-12 11:36:43.558  6535  6535 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:43.561  6535  6535 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1f784f29}
07-12 11:36:43.562  6535  6535 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:43.562  6535  6535 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:36:43.569  6535  6535 I BrowserStartupController: Initializing chromium process, renderers=0
07-12 11:36:43.570  6535  6535 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:43.574  6473  6488 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:36:43.574  6473  6488 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:36:43.574  6473  6488 I Adreno-EGL: Build Date: 12/12/14 금
07-12 11:36:43.574  6473  6488 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-12 11:36:43.574  6473  6488 I Adreno-EGL: Remote Branch: 
07-12 11:36:43.574  6473  6488 I Adreno-EGL: Local Patches: 
07-12 11:36:43.574  6473  6488 I Adreno-EGL: Reconstruct Branch: 
07-12 11:36:43.579  6535  6535 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,07-12 11:36:43.579  6535  6535 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-12 11:36:43.580  6535  6535 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
07-12 11:36:43.585   315   315 V AudioPolicyService: registerClient() client 0xb1026fe0, uid 10093
07-12 11:36:43.586  6535  6579 W AudioManagerAndroid: Requires BLUETOOTH permission
07-12 11:36:43.590  6535  6535 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:36:43.590  6535  6535 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:36:43.590  6535  6535 I Adreno-EGL: Build Date: 12/12/14 금
07-12 11:36:43.590  6535  6535 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-12 11:36:43.590  6535  6535 I Adreno-EGL: Remote Branch: 
07-12 11:36:43.590  6535  6535 I Adreno-EGL: Local Patches: 
07-12 11:36:43.590  6535  6535 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:36:43.633  6535  6535 I NSApplication: Starting up...
,07-12 11:36:43.682  1031  1972 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6592 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:43.685  1031  1972 I ActivityManager: Killing 5652:com.android.vending/u0a44 (adj 15): empty #17
07-12 11:36:43.889  1031  1866 W libprocessgroup: failed to open /acct/uid_10044/pid_5652/cgroup.procs: No such file or directory
,07-12 11:36:43.934   310  6613 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-12 11:36:43.934   310  6613 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-12 11:36:43.939  6592  6592 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:36:43.974   310  6613 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-12 11:36:44.192  5017  5017 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,07-12 11:36:44.208  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:36:44.208  5748  5811 I jxcore-log: 
,07-12 11:36:44.223  1797  6463 I CheckinTask: Sending checkin request (7873 bytes)
07-12 11:36:44.257  1031  1901 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6626 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-12 11:36:44.265  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:36:44.265  5748  5811 I jxcore-log: 
,07-12 11:36:44.271  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:36:44.271  5748  5811 I jxcore-log: 
,07-12 11:36:44.422  1031  1052 I art     : Explicit concurrent mark sweep GC freed 27272(1424KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.999ms total 110.991ms
,07-12 11:36:44.440  1797  6463 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-12 11:36:44.447  1797  6463 I CheckinService: active receiver: disabled
,07-12 11:36:44.471  1797  6650 I CheckinService: active receiver: disabled
07-12 11:36:44.478  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:36:44.478  5748  5811 I jxcore-log: 
,07-12 11:36:44.482  6626  6651 D ALBootInit: ====action==>android.intent.action.TIME_SET
07-12 11:36:44.486  6626  6651 D ALBootInit: Alarm ALBootInit: TIME_SET
07-12 11:36:44.487  6626  6651 D Alarms  : [setNextAlert] start
07-12 11:36:44.494  6626  6651 D Alarms  : [setNextAlert] (1)
,07-12 11:36:44.496  6626  6651 D Alarms  :  minTime  = 0
,07-12 11:36:44.497  6626  6651 D Alarms  :  -- OK multi -- 0
07-12 11:36:44.498  6626  6651 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
07-12 11:36:44.498  6626  6651 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
07-12 11:36:44.500  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:36:44.500  5748  5811 I jxcore-log: 
07-12 11:36:44.504  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:36:44.504  5748  5811 I jxcore-log: 
07-12 11:36:44.509  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:36:44.509  5748  5811 I jxcore-log: 
,07-12 11:36:44.511  6626  6651 I CommonUtil: BUILD Country: EU
07-12 11:36:44.512  6626  6651 D Alarms  : broadcastToWidgetProvider : false
07-12 11:36:44.518  6626  6651 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
07-12 11:36:44.524  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:36:44.524  5748  5811 I jxcore-log: 
,07-12 11:36:44.542  1031  1554 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,07-12 11:36:44.543  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 11:36:44.543  5748  5811 I jxcore-log: 
07-12 11:36:44.547  6626  6626 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
07-12 11:36:44.548  6626  6626 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@35322467
07-12 11:36:44.550  6626  6626 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@35322467
,07-12 11:36:44.553  6626  6626 D QuickCoverProvider: onReceiver
07-12 11:36:44.558  1537  1537 I indal   : SmartCoverWidgetContext createApplicationContext
07-12 11:36:44.558  1537  1537 I indal   : SmartCoverWidgetContext createApplicationContext
,07-12 11:36:44.578  6511  6511 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:36:44
,07-12 11:36:44.580  6511  6511 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-12 11:36:44.580  6511  6511 D Weather.Utils: 2 : All the weather widget is gone.
07-12 11:36:44.580  6511  6511 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-12 11:36:44.585  6511  6511 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c1b1214
07-12 11:36:44.585  6511  6511 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-12 11:36:44.585  6511  6511 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-12 11:36:44.585  6511  6511 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-12 11:36:44.587  6511  6511 D Weather_cast: 2 : set auto-update time : 7/12 14:36
07-12 11:36:44.593  6511  6511 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:36:44
,07-12 11:36:44.630  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 11:36:44.630  5748  5811 I jxcore-log: 
,07-12 11:36:44.635  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 11:36:44.635  5748  5811 I jxcore-log: 
07-12 11:36:44.660  5748  5811 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 11:36:44.660  5748  5811 I jxcore-log: 
07-12 11:36:44.660  1031  1992 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6656 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-12 11:36:44.662  1031  1992 I ActivityManager: Killing 4824:com.lge.bnr/1000 (adj 15): empty #17
,07-12 11:36:44.671  5748  5811 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-12 11:36:44.672  5748  5811 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-12 11:36:44.672  5748  5811 I jxcore-log: 
07-12 11:36:44.723  5748  5811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 11:36:44.723  5748  5811 I jxcore-log: 
,07-12 11:36:44.724  5748  5811 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:36:44.724  5748  5811 I jxcore-log: 
07-12 11:36:44.746  1031  2011 W libprocessgroup: failed to open /acct/uid_1000/pid_4824/cgroup.procs: No such file or directory
,07-12 11:36:44.802  6656  6656 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1468316204802
,07-12 11:36:44.804  6656  6656 D         : TimeServiceNative: User Time to be set is 1468316204802
07-12 11:36:44.804  6656  6656 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-12 11:36:44.804  6656  6656 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-12 11:36:44.804  6656  6656 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1468316204802
07-12 11:36:44.805   394  1027 D QC-time-services: Daemon: Connection accepted:time_genoff
07-12 11:36:44.805  6656  6656 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-12 11:36:44.805   394  6676 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1468316204802
07-12 11:36:44.806   394  6676 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1468316204802, operation = 0
07-12 11:36:44.806   394  6676 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/22/70 4:4:34
07-12 11:36:44.806   394  6676 D QC-time-services: Daemon:Value read from RTC seconds = 1829074000
07-12 11:36:44.806   394  6676 D QC-time-services: Daemon:new time 1468316204802 
07-12 11:36:44.806   394  6676 D QC-time-services: Daemon: delta 1466487130802 genoff 1466487130802 
07-12 11:36:44.806   394  6676 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487130802 to memory
07-12 11:36:44.806   394  6676 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-12 11:36:44.806   394  6676 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
07-12 11:36:44.819   394  6676 D QC-time-services: Updating the TOD offset
07-12 11:36:44.819   394  6676 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487130802 to memory
07-12 11:36:44.819   394  6676 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-12 11:36:44.819   394  6676 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:36:44.824   394  6676 E QC-time-services: Daemon:Update to modem bit set
07-12 11:36:44.824   394  6676 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-12 11:36:44.824   394  6676 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522330802
07-12 11:36:44.825  6656  6656 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
07-12 11:36:44.827   394  1025 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
07-12 11:36:44.827   394  1027 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-12 11:36:44.899  1031  1052 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6677 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-12 11:36:44.902  1031  1052 I ActivityManager: Killing 6151:com.lge.sync/1000 (adj 15): empty #17
07-12 11:36:44.966  1031  1866 W libprocessgroup: failed to open /acct/uid_1000/pid_6151/cgroup.procs: No such file or directory
07-12 11:36:44.966  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e5e47b type 2 when 110878 com.google.android.gms} when 110878
,07-12 11:36:45.040  6677  6677 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,07-12 11:36:45.047  6677  6677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
07-12 11:36:45.048  1581  1581 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-12 11:36:45.048  1581  1581 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-12 11:36:45.049  1581  1581 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
07-12 11:36:45.055  6677  6677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
07-12 11:36:45.056  6677  6677 V [BNRBootReceiver]: Boot Receiver Return
,07-12 11:36:45.058  6677  6677 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-12 11:36:45.115  1031  1629 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6696 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
07-12 11:36:45.116  1031  1629 I ActivityManager: Killing 6071:com.android.settings/1000 (adj 15): empty #17
,07-12 11:36:45.137  1031  1523 D WifiService: Client connection lost with reason: 4
,07-12 11:36:45.176  1031  1920 W libprocessgroup: failed to open /acct/uid_1000/pid_6071/cgroup.procs: No such file or directory
,07-12 11:36:45.211  6696  6696 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:45.244  6696  6696 D CalendarApplication: CalendarApplication.onCreate()
,07-12 11:36:45.255  6696  6696 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
07-12 11:36:45.259  6696  6696 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3bbf485a, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@8196a8b, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@23cae768, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@32566781, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@11199026, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@35322467, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3c1b1214, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2680fabd, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1c7e88b2, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1b32a003, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@6a13b80, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@37c785b9, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@30c87dfe, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@c35395f, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@289e8fac, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2651c475, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@222a7c0a, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@379e0c7b, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@383afa98, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@130732f1, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@22fc4ed6, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@14f6f557, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@4312844, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2bcb0d2d, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@21468262, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@208b8ff3, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2a3a84b0, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1f784f29, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@310e62ae, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@5c5384f, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@283b3bdc, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@159db4e5, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@f61fbba, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@13470a6b, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@142e39c8, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@25f9ba61, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@a241986, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@14c9e247, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@26d12a74, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@bb69b9d, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Pr,eferenceKey$KeyData@18984812, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2eb85b
07-12 11:36:45.266  6696  6696 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
07-12 11:36:45.276  6696  6696 D Config  : [init]
,07-12 11:36:45.277  6696  6696 I Config  : LGCalendar ver.4.40.16
07-12 11:36:45.277  6696  6696 I Config  : start check model
07-12 11:36:45.277  6696  6696 I Config  : start check native_ca
07-12 11:36:45.278  6696  6696 I Config  : Config Operator=OPEN, Country=EU
07-12 11:36:45.279  6696  6696 D Config  : [setDefaultValuesToPref]
07-12 11:36:45.279  6696  6696 D Config  : [parseProfiles]
07-12 11:36:45.284  6696  6696 D ProfilesParser: [debug_displayParseInfos] profile.country = null
07-12 11:36:45.284  6696  6696 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
07-12 11:36:45.284  6696  6696 D Config  : [updateProfiletoCountryInfo]
07-12 11:36:45.285  6696  6696 D GeneralPreference: [checkAndMigrateOldPreference]
07-12 11:36:45.300  6696  6696 E AgendaWidgetManager: [updateWidgets] 
,07-12 11:36:45.307  6696  6718 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
07-12 11:36:45.313  6696  6718 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,07-12 11:36:45.336  6696  6718 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,07-12 11:36:45.342  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
07-12 11:36:45.346  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
07-12 11:36:45.350  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,07-12 11:36:45.354  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
07-12 11:36:45.358  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
07-12 11:36:45.362  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
07-12 11:36:45.367  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,07-12 11:36:45.370  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
07-12 11:36:45.374  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
07-12 11:36:45.379  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,07-12 11:36:45.384  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
07-12 11:36:45.389  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
07-12 11:36:45.394  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,07-12 11:36:45.399  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
07-12 11:36:45.403  6696  6718 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
07-12 11:36:45.403  6696  6718 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
07-12 11:36:45.406  6696  6718 I AlertUtils: set default noti to content://media/internal/audio/media/41
07-12 11:36:45.413  6696  6718 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,07-12 11:36:45.481  6696  6726 W HolidayIntentService: onHandleIntent
,07-12 11:36:45.482  6696  6696 D MonthWidgetProvider: [onReceive]
07-12 11:36:45.482  6696  6696 D CalendarWidgetProvider: [onReceive]
07-12 11:36:45.482  6696  6696 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,07-12 11:36:45.486  6696  6726 D HolidayDataLoader: readJsonAsset : holiday.json
07-12 11:36:45.490  6696  6696 D CalendarTypeController: [onUpdateAndInitCalendarTime]
07-12 11:36:45.499  6696  6696 D WeekWidgetProvider: [onReceive]
07-12 11:36:45.499  6696  6696 D CalendarWidgetProvider: [onReceive]
07-12 11:36:45.499  6696  6696 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
07-12 11:36:45.500  6696  6696 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,07-12 11:36:45.561  6696  6726 E HolidayIntentService: onHandleIntent:holiday data empty
,07-12 11:36:45.586  1031  2011 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6727 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-12 11:36:45.593  1031  1052 I ActivityManager: Killing 6108:com.lge.lifetracker/u0a37 (adj 15): empty #17
,07-12 11:36:45.661  1031  1917 W libprocessgroup: failed to open /acct/uid_10037/pid_6108/cgroup.procs: No such file or directory
,07-12 11:36:45.687  6727  6727 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:36:45.687  6727  6727 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,07-12 11:36:45.688  6727  6727 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-12 11:36:45.689  6727  6727 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,07-12 11:36:45.691  6727  6727 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-12 11:36:45.692  6727  6727 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-12 11:36:45.900  6727  6727 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-12 11:36:45.938  6727  6727 D LgDataFeature: LgDataFeature() Constructor: none
,07-12 11:36:45.938  6727  6727 D LgDataFeature: LgDataFeature() Constructor Done, null,
,07-12 11:36:45.948  6727  6727 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-12 11:36:45.953  1031  2012 I ActivityManager: Killing 5960:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-12 11:36:45.983  6237  6237 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,07-12 11:36:45.983  6237  6237 W System.err: android.os.DeadObjectException
,07-12 11:36:45.984  6237  6237 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-12 11:36:45.984  6237  6237 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-12 11:36:45.984  6237  6237 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-12 11:36:45.984  6237  6237 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,07-12 11:36:45.984  6237  6237 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-12 11:36:45.984  6237  6237 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-12 11:36:45.984  6237  6237 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:45.984  6237  6237 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,07-12 11:36:45.984  6237  6237 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:45.984  6237  6237 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-12 11:36:45.984  6237  6237 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:45.984  6237  6237 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:45.985  6237  6237 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-12 11:36:45.985  6237  6237 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-12 11:36:45.985  6237  6237 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-12 11:36:45.985  6237  6237 W System.err: android.os.DeadObjectException
07-12 11:36:45.986  6237  6237 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-12 11:36:45.986  6237  6237 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-12 11:36:45.986  6237  6237 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-12 11:36:45.986  6237  6237 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-12 11:36:45.986  6237  6237 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-12 11:36:45.986  6237  6237 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-12 11:36:45.986  6237  6237 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:45.986  6237  6237 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:45.986  6237  6237 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:45.986  6237  6237 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-12 11:36:45.986  6237  6237 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:45.986  6237  6237 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:45.986  6237  6237 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-12 11:36:45.986  6237  6237 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-12 11:36:45.986  6237  6237 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-12 11:36:45.987  6237  6237 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-12 11:36:46.069   276   276 E lowmemorykiller: Error opening /proc/5960/oom_score_adj; errno=2
,07-12 11:36:46.078  1031  1629 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
07-12 11:36:46.078  1031  1629 W ActivityManager: android.os.DeadObjectException
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
07-12 11:36:46.078  1031  1629 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
07-12 11:36:46.082  1031  1955 W libprocessgroup: failed to open /acct/uid_1000/pid_5960/cgroup.procs: No such file or directory
07-12 11:36:46.093  2054  2054 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-12 11:36:46.098  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=15.4, 0.0, 0.0  rx=12.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-562609134] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:36:46.099  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=15.4, 0.0, 0.0  rx=12.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-562609133] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:36:46.099  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:36:46.102  6237  6237 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-12 11:36:46.103  6237  6237 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-12 11:36:46.108  2054  2054 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-12 11:36:46.108  2054  2054 D c       : Getting all permits...
07-12 11:36:46.108  2054  2054 D a       : Opening database...
07-12 11:36:46.114  2054  2054 D a       : Opening database auth.proximity.permit_store...
07-12 11:36:46.115  2054  2054 D a       : Closing database...
,07-12 11:36:46.177  1031  1629 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6753 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-12 11:36:46.181  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{15887cb0 type 2 when 112109 com.android.providers.calendar} when 112109
07-12 11:36:46.190  6237  6237 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-12 11:36:46.199  2054  2054 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-12 11:36:46.217  2054  2054 I GCM     : GCM config loaded
,07-12 11:36:46.227   310  6774 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:36:46.228   310  6774 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
07-12 11:36:46.228   310  6774 D libc-netbsd: res_queryN name = mtalk.google.com succeed
07-12 11:36:46.240  6421  6421 V SetupWizard: Connected to Gservices successfully
,07-12 11:36:46.245  6626  6626 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
07-12 11:36:46.253  6511  6511 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 11:36:46
,07-12 11:36:46.257  6511  6511 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-12 11:36:46.257  6511  6511 D Weather.Utils: 2 : All the weather widget is gone.
07-12 11:36:46.257  6511  6511 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-12 11:36:46.258  6511  6511 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
07-12 11:36:46.258  6511  6511 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 11:36:46
07-12 11:36:46.265  6237  6237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-12 11:36:46.265  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:541
07-12 11:36:46.269  2013  2013 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,07-12 11:36:46.270  2013  2799 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
07-12 11:36:46.270  2013  2799 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-12 11:36:46.271  2013  2799 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
07-12 11:36:46.272  2013  2799 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
07-12 11:36:46.272  2013  2799 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
07-12 11:36:46.278  6677  6677 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
07-12 11:36:46.279  6677  6677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
07-12 11:36:46.280  1581  1581 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-12 11:36:46.280  1581  1581 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-12 11:36:46.280  1581  1581 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,07-12 11:36:46.283  6677  6677 V [BNRBootReceiver]: Boot Receiver Return
07-12 11:36:46.307  6753  6753 D UEI.SmartControl: Quickset Services start...
,07-12 11:36:46.310  6753  6753 I UEI.SmartControl: Manufacture = LGE
07-12 11:36:46.310  6753  6753 D UEI.SmartControl: Id = LGNevo
07-12 11:36:46.312  6753  6753 D UEI.SmartControl: File observer start...
07-12 11:36:46.312  6753  6753 E UEI.SmartControl: IR Port is disabled: false
07-12 11:36:46.313  6753  6753 D UEI.SmartControl: Starting file observer...
07-12 11:36:46.313  6753  6753 D UEI.SmartControl: Extracting JNI libs...
07-12 11:36:46.313  6753  6753 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-12 11:36:46.338  1031  1866 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6785 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,07-12 11:36:46.389  1581  1581 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-12 11:36:46.390  1581  1581 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-12 11:36:46.410  1797  1797 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-12 11:36:46.413  6785  6785 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-12 11:36:46.415  1797  6804 I ConfigFetchService: running network task: configservice_periodic
07-12 11:36:46.416  1797  6804 I ConfigFetchService: launchTask
07-12 11:36:46.419  6753  6753 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-12 11:36:46.419  6753  6753 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-12 11:36:46.419  6753  6753 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-12 11:36:46.426  2054  2054 I ConfigService: onCreate
07-12 11:36:46.426  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,07-12 11:36:46.434  2054  2054 I ConfigService: onBind returning update interface
07-12 11:36:46.435  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-12 11:36:46.435  2054  2054 I ConfigService: onBind returning config service
07-12 11:36:46.435  1797  1797 I ConfigFetchService: service connected
07-12 11:36:46.435  1797  1797 I ConfigClient: service connected
07-12 11:36:46.448  6753  6753 I UEI.SmartControl: --- Selecting new region: 6
,07-12 11:36:46.450  6753  6753 I UEI.SmartControl: Model = LG-D855
,07-12 11:36:46.451  6785  6785 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@246a4f7c
07-12 11:36:46.451  6753  6753 D UEI.SmartControl: QS Service created
07-12 11:36:46.461  6753  6753 I UEI.SmartControl: Service initServices...
,07-12 11:36:46.463  6785  6785 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
07-12 11:36:46.464  6753  6753 D UEI.SmartControl: QS start get config
07-12 11:36:46.465  6785  6785 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@32566781(com.android.providers.calendar.CalendarProvider2@246a4f7c)
07-12 11:36:46.468  6785  6785 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,07-12 11:36:46.468  6785  6785 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
07-12 11:36:46.474  2013  2013 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,07-12 11:36:46.478  2013  5154 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
07-12 11:36:46.478  2013  5154 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-12 11:36:46.479  2013  5154 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
07-12 11:36:46.479  6785  6785 D CalendarProvider2: CalendarProviderIntentService.onCreate()
07-12 11:36:46.480  2013  5154 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
07-12 11:36:46.480  6785  6808 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
07-12 11:36:46.480  6785  6808 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
07-12 11:36:46.481  2013  5154 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
07-12 11:36:46.481  2054  6802 D GCM     : Connected
07-12 11:36:46.482  6785  6808 E SQLiteLog: (284) automatic index on view_events(_id)
07-12 11:36:46.494  6753  6753 D UEI.SmartControl: Loading JNI Libs...
,07-12 11:36:46.503  6785  6808 D CalendarProvider2: [IntentService] Release Lock
07-12 11:36:46.504  6785  6785 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
07-12 11:36:46.505  1031  1866 I ActivityManager: Killing 6210:com.lge.settings.easy/1000 (adj 15): empty #17
07-12 11:36:46.513  2054  6802 D GCM     : Message class com.google.e.a.a.q
,07-12 11:36:46.589  1031  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_6210/cgroup.procs: No such file or directory
,07-12 11:36:46.715  6753  6753 I UEI.SmartControl: Supports setup maps: true
,07-12 11:36:46.718  6753  6753 D UEI.SmartControl: QS start statue = true Error code = 0
,07-12 11:36:46.718  6753  6753 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-12 11:36:46.719  6753  6753 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-12 11:36:46.719  6753  6753 I UEI.SmartControl: ### init IR Blaster...
07-12 11:36:46.725  6753  6753 D serial_port: Configuring serial port
07-12 11:36:46.736  6753  6753 E UEI.SmartControl: UEIBLaster setting for 616
07-12 11:36:46.736  6753  6753 I UEI.SmartControl: Setting serial record hearder size = 2
07-12 11:36:46.737  6753  6753 I UEI.SmartControl: configuring settings for MAXQ616
07-12 11:36:46.738  6753  6753 I UEI.SmartControl: Get version...
,07-12 11:36:46.756  6753  6811 D UEI.SmartControl: serial port data available: 21
,07-12 11:36:46.785  6753  6753 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-12 11:36:46.786  6753  6753 I UEI.SmartControl: IR Blaster version: 256702256704300002
,07-12 11:36:46.787  6753  6753 I UEI.SmartControl: QS saving settings...
07-12 11:36:46.789  6753  6753 D UEI.SmartControl: IR Blaster version: 25672567
07-12 11:36:46.805  6753  6811 D UEI.SmartControl: serial port data available: 4
,07-12 11:36:46.842  6753  6817 I UEI.SmartControl: Device manager: loading config....
,07-12 11:36:46.843  6753  6817 D UEI.SmartControl: ----------- loading internal config...
,07-12 11:36:46.845  6753  6753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-12 11:36:46.848  6753  6753 E UEI.SmartControl: Services init done
07-12 11:36:46.848  6753  6753 D UEI.SmartControl: QS Service init finished
07-12 11:36:46.851  6753  6753 D UEI.SmartControl: QS Service version name: 2.1.91
07-12 11:36:46.851  6753  6753 D UEI.SmartControl: QS Service version code: 201091
07-12 11:36:46.852  6753  6753 D UEI.SmartControl: Service requested: Control
07-12 11:36:46.856  6753  6817 E UEI.SmartControl: Loading SETTINGS...
,07-12 11:36:46.858  6753  6753 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-12 11:36:46.865  6753  6817 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-12 11:36:46.867  6237  6237 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-12 11:36:46.867  6753  6771 I UEI.SmartControl: ------ IControl API: 11
,07-12 11:36:46.869  6753  6771 I UEI.SmartControl: Registering callback...
07-12 11:36:46.875  6753  6770 I UEI.SmartControl: ------ IControl API: 19
07-12 11:36:46.878  6753  6770 I UEI.SmartControl: Registering Services Ready callback...
,07-12 11:36:46.883  1031  1955 I ActivityManager: Killing 6365:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-12 11:36:46.907  6753  6816 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-12 11:36:46.908  6237  6254 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-12 11:36:46.909  6237  6285 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-12 11:36:46.909  6237  6285 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-12 11:36:46.910  6237  6237 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-12 11:36:46.910  6237  6237 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-12 11:36:46.910  6753  6816 D UEI.SmartControl: -----service ready thread exits
07-12 11:36:46.911  6753  6771 I UEI.SmartControl: ------ IControl API: 8
07-12 11:36:46.912  6237  6237 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-12 11:36:46.913  6237  6237 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-12 11:36:46.913  6237  6237 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-12 11:36:46.913  6237  6237 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-12 11:36:46.914  6237  6237 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-12 11:36:46.916  6237  6237 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-12 11:36:46.927  1031  1992 W libprocessgroup: failed to open /acct/uid_10011/pid_6365/cgroup.procs: No such file or directory
07-12 11:36:46.927  6753  6753 D UEI.SmartControl: Internal service binding...
,07-12 11:36:46.932  6237  6237 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-12 11:36:46.936  6237  6237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-12 11:36:46.936  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-12 11:36:46.938  6237  6237 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-12 11:36:46.938  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-12 11:36:46.939  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-12 11:36:46.940  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-12 11:36:46.941  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,07-12 11:36:46.941  6237  6237 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1468316206941]
07-12 11:36:46.955  6237  6822 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-12 11:36:46.960  6237  6237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-12 11:36:46.961  6237  6237 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-12 11:36:46.961  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-12 11:36:46.961  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-12 11:36:46.961  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-12 11:36:46.962  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-12 11:36:46.962  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-12 11:36:46.964  6237  6237 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
07-12 11:36:48.453  6535  6557 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:36:48.659  1031  2012 I ActivityManager: Killing 6126:com.lge.formmanager/u0a26 (adj 15): empty #17
,07-12 11:36:48.695  1031  1901 W libprocessgroup: failed to open /acct/uid_10026/pid_6126/cgroup.procs: No such file or directory
,07-12 11:36:49.109  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=16.7, 0.0, 0.0  rx=13.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-562606123] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:36:49.119  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=16.7, 0.0, 0.0  rx=13.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-562606113] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:36:49.119  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:36:49.208  1031  1866 I ActivityManager: Killing 6442:com.android.chrome/u0a57 (adj 15): empty #17
,07-12 11:36:49.246  1031  1972 W libprocessgroup: failed to open /acct/uid_10057/pid_6442/cgroup.procs: No such file or directory
,07-12 11:36:51.844  6753  6818 D UEI.SmartControl: Internal timer expired: 1
,07-12 11:36:51.851  6753  6818 D UEI.SmartControl: unbind internal service
,07-12 11:36:51.909  6753  6812 D serial_port: close(fd = 25)
,07-12 11:36:51.921  6753  6812 I UEI.SmartControl: Serial port is closed.
,07-12 11:36:52.137  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=13.8, 0.0, 0.0  rx=11.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-562603095] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:36:52.140  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=13.8, 0.0, 0.0  rx=11.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562603092] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:36:52.140  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:36:52.391  1581  1581 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-12 11:36:52.417  1031  1426 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-12 11:36:52.486  1031  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6828 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-12 11:36:52.497  1581  1581 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-12 11:36:52.499  1581  1581 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-12 11:36:52.510  2013  2013 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-12 11:36:52.536  2013  2013 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-12 11:36:52.549  1031  1031 D administrator: Handling package changes for user 0
,07-12 11:36:52.577  6828  6828 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-12 11:36:52.667  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-12 11:36:52.668  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-12 11:36:52.674  6828  6828 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:52.674  6828  6828 D LgDataFeature: LgDataFeature() Constructor Done, null
07-12 11:36:52.720  1031  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:52.726  1031  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-12 11:36:52.732  2013  2013 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-12 11:36:52.734  2449  2449 V GmsNetworkLocationProvi: DISABLE
,07-12 11:36:52.789  6828  6872 I Babel   : MmsConfig: mnc/mcc: 0/0
07-12 11:36:52.789  6828  6872 I Babel   : MmsConfig.loadMmsSettings
,07-12 11:36:52.792  6828  6872 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-12 11:36:52.793  6828  6872 I Babel   : MmsConfig.loadFromDatabase
07-12 11:36:52.796  2054  2272 I art     : Explicit concurrent mark sweep GC freed 7594(494KB) AllocSpace objects, 8(128KB) LOS objects, 52% free, 29MB/61MB, paused 853us total 55.922ms
,07-12 11:36:52.816  6828  6872 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-12 11:36:52.816  6828  6872 I Babel   : MmsConfig.loadFromResources
07-12 11:36:52.818  6828  6872 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-12 11:36:52.820  2449  2449 E GCoreFlp: Bound FusedProviderService with LocationManager
,07-12 11:36:52.837  6828  6871 W AudioCapabilities: Unsupported mime audio/evrc
07-12 11:36:52.837  6828  6872 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-12 11:36:52.838  6828  6871 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 11:36:52.840  6828  6828 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:52.844  6828  6871 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 11:36:52.855  6828  6871 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-12 11:36:52.858  6828  6871 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 11:36:52.861  1797  6876 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-12 11:36:52.861  6828  6871 W AudioCapabilities: Unsupported mime audio/evrc
07-12 11:36:52.861  1797  6876 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
07-12 11:36:52.875  6828  6871 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-12 11:36:52.893  1031  1052 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6878 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-12 11:36:52.895  6828  6871 W VideoCapabilities: Unsupported mime video/divx
07-12 11:36:52.899  6828  6871 W VideoCapabilities: Unsupported mime video/divx311
07-12 11:36:52.901  1797  4426 I Icing   : updateResources: need to parse e{com.google.android.gms}
07-12 11:36:52.902  6828  6871 W VideoCapabilities: Unsupported mime video/divx4
07-12 11:36:52.906  1031  2012 I ActivityManager: Killing 6491:com.lge.drmservice/u0a62 (adj 15): empty #17
,07-12 11:36:52.907  6828  6871 W VideoCapabilities: Unsupported mime video/mp4v-esdp
07-12 11:36:52.918  6828  6871 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-12 11:36:52.920  6828  6871 W AudioCapabilities: Unsupported mime audio/eac3
07-12 11:36:52.920  6828  6871 W AudioCapabilities: Unsupported mime audio/ac3
,07-12 11:36:52.921  6828  6871 W AudioCapabilities: Unsupported mime audio/g726
07-12 11:36:52.922  6828  6871 W AudioCapabilities: Unsupported mime audio/wma-voice
07-12 11:36:52.922  6828  6871 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-12 11:36:52.923  6828  6871 W AudioCapabilities: Unsupported mime audio/adpcm
07-12 11:36:52.925  6828  6871 W VideoCapabilities: Unsupported mime video/theora
07-12 11:36:52.927  6828  6871 W VideoCapabilities: Unsupported mime video/mjpg
07-12 11:36:52.975  1031  1920 W libprocessgroup: failed to open /acct/uid_10062/pid_6491/cgroup.procs: No such file or directory
,07-12 11:36:52.980  1031  1091 D LocationProviderProxy: applying state to connected service
07-12 11:36:53.027  6878  6878 I AppUp4:AppBoxCP: onCreate
,07-12 11:36:53.028  6878  6878 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-12 11:36:53.035  6878  6878 I AppUp4:DB:  setFingerPrint start
,07-12 11:36:53.035  6878  6878 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-12 11:36:53.040  6878  6878 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-12 11:36:53.041  6878  6878 I AppUp4:DB:  SDK version = 21
07-12 11:36:53.041  6878  6878 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-12 11:36:53.042  6878  6878 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-12 11:36:53.051  6878  6878 I AppUp4:CustModeStarterReceiver: onReceive
07-12 11:36:53.076  6878  6878 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:53.077  6878  6878 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-12 11:36:53.082  6878  6878 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@8196a8b
07-12 11:36:53.082  6878  6878 D AppUp4:CustFacade: isCustomizationCompleted : false
07-12 11:36:53.082  6878  6878 D AppUp4:CustFacade: isPhone : true
07-12 11:36:53.083  6878  6878 D AppUp4:CustModeStarterReceiver: begin check event
07-12 11:36:53.083  6878  6878 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-12 11:36:53.151  1031  1921 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6899 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
07-12 11:36:53.154  1031  1921 I ActivityManager: Killing 6535:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,07-12 11:36:53.175   348   348 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 23.762ms
,07-12 11:36:53.192   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 350us total 16.172ms
,07-12 11:36:53.207   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 14.109ms
,07-12 11:36:53.368  1031  1917 W libprocessgroup: failed to open /acct/uid_10093/pid_6535/cgroup.procs: No such file or directory
,07-12 11:36:53.420  6899  6899 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:53.421  6899  6899 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-12 11:36:53.421  6899  6899 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-12 11:36:53.423  6899  6899 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-12 11:36:53.423  6899  6899 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-12 11:36:53.517  6899  6899 I SystemConfig: BUILD Country: EU
07-12 11:36:53.518  6899  6899 I SystemConfig: BUILD Operator: OPEN
,07-12 11:36:53.712  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{146b018a type 2 when 119692 com.google.android.gms} when 119692
,07-12 11:36:53.734  1031  1921 I art     : Explicit concurrent mark sweep GC freed 20577(1073KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.839ms total 159.738ms
,07-12 11:36:53.745  1031  1917 I ActivityManager: Killing 6592:com.google.android.apps.plus/u0a97 (adj 15): empty #17
07-12 11:36:53.807  1031  1698 W libprocessgroup: failed to open /acct/uid_10097/pid_6592/cgroup.procs: No such file or directory
,07-12 11:36:53.814  6899  6922 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-12 11:36:53.814  6899  6922 I SystemConfig: existFile = false
07-12 11:36:53.815  6899  6922 I SystemConfig: canReadFile = false
07-12 11:36:53.815  6899  6922 I SystemConfig: systemFeature RCS result false
07-12 11:36:53.816  6899  6922 D SystemConfig: refreshRcsSupport() :false
07-12 11:36:53.852  1031  1917 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6925 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-12 11:36:53.900  6925  6925 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:36:53.901  6925  6925 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-12 11:36:53.901  6925  6925 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-12 11:36:53.901  6925  6925 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-12 11:36:53.986  6925  6925 I AppConfig: Total System Memory = 2995761152
,07-12 11:36:53.998  6925  6925 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-12 11:36:54.083  1031  1955 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6944 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:54.089  1031  1955 I ActivityManager: Killing 6390:com.lge.email/u0a23 (adj 15): empty #17
07-12 11:36:54.146  1031  1554 W libprocessgroup: failed to open /acct/uid_10023/pid_6390/cgroup.procs: No such file or directory
,07-12 11:36:54.341  6944  6944 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-12 11:36:54.425  6944  6944 D LgDataFeature: LgDataFeature() Constructor: none
07-12 11:36:54.425  6944  6944 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-12 11:36:54.480  6944  6944 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-12 11:36:54.502  6944  6944 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:36:54.503  6944  6944 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:36:54.520  6944  6944 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-12 11:36:54.520  6944  6944 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-12 11:36:54.550  1031  1955 I ActivityManager: Killing 5017:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,07-12 11:36:54.580  1031  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_5017/cgroup.procs: No such file or directory
,07-12 11:36:54.585  2804  2819 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,07-12 11:36:54.587  2804  2819 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@178ad33f on behalf of 6944
07-12 11:36:54.592  4258  6981 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-12 11:36:54.647  1031  2012 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6986 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:54.659  6944  6944 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-12 11:36:54.698  6944  6944 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-12 11:36:54.738  1797  3139 I art     : Explicit concurrent mark sweep GC freed 33548(2MB) AllocSpace objects, 19(327KB) LOS objects, 51% free, 29MB/61MB, paused 2.082ms total 76.189ms
,07-12 11:36:54.745  6986  6986 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
07-12 11:36:54.795  6986  6986 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-12 11:36:54.796  6986  6986 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,07-12 11:36:54.796  6986  6986 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-12 11:36:54.796  6986  6986 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-12 11:36:54.796  6986  6986 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-12 11:36:54.796  6986  6986 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
07-12 11:36:54.861  1031  2032 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7013 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:54.865  1031  2032 I ActivityManager: Killing 6656:com.qualcomm.timeservice/1000 (adj 15): empty #17
,07-12 11:36:54.916  1031  1698 W libprocessgroup: failed to open /acct/uid_1000/pid_6656/cgroup.procs: No such file or directory
,07-12 11:36:54.975  7013  7013 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:55.167  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562600065] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:36:55.168  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-562600064] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:36:55.168  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:36:55.189  1031  1921 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:36:55.213  4258  6981 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 621 ms] updated apps [took 621 ms] 
,07-12 11:36:56.512  1031  1554 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:36:56.539  1797  2311 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-12 11:36:56.548   310  7054 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-12 11:36:56.549   310  7054 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-12 11:36:56.549   310  7054 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-12 11:36:56.779  1797  2311 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-12 11:36:56.793  1797  1797 I ConfigFetchService: fetch service done; releasing wakelock
07-12 11:36:56.797  1797  1797 I ConfigFetchService: stopping self
07-12 11:36:56.841  2054  2054 I ConfigService: onDestroy
,07-12 11:36:58.182  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562597050] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:36:58.183  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-562597049] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:36:58.183  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:00.306  1031  1051 I ActivityManager: Killing 6696:com.android.calendar/u0a13 (adj 15): empty #17
,07-12 11:37:00.339  1031  1955 W libprocessgroup: failed to open /acct/uid_10013/pid_6696/cgroup.procs: No such file or directory
,07-12 11:37:00.421  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:37:00.421  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:37:00.421  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:37:00.422  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:37:00.435  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:37:00.436  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:37:00.438  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:37:00.440  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:37:01.200  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=6.7, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562594032] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:37:01.203  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=6.7, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562594029] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:37:01.203  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:01.697  1031  1972 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,07-12 11:37:01.700  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:01.700  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:01.700  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-12 11:37:01.700  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:01.700  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-12 11:37:01.739  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:37:01 GMT], X-Android-Received-Millis=[1468316221738], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1468316221710]}
,07-12 11:37:01.742  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,07-12 11:37:01.742  1031  6182 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,07-12 11:37:01.743  1031  1524 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
,07-12 11:37:01.743  1031  1524 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,07-12 11:37:01.743  1031  1524 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:01.743  1031  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:01.743  1031  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-12 11:37:01.743  1031  1524 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
07-12 11:37:01.744  1031  1524 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-12 11:37:01.744  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:01.744  1031  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:01.744  1031  1524 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:01.746  1581  2087 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-12 11:37:04.230  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562591002] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:37:04.233  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562590999] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:37:04.233  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:04.700  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:37:04.720  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3f020cea type 2 when 130678 com.google.android.gms} when 130678
,07-12 11:37:04.732   310  7057 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:37:04.733   310  7057 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
07-12 11:37:04.733   310  7057 D libc-netbsd: res_queryN name = mtalk.google.com succeed
07-12 11:37:04.760  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:37:04.808  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:37:05.019  2054  7058 D GCM     : Connected
,07-12 11:37:05.064  2054  7058 D GCM     : Message class com.google.e.a.a.q
,07-12 11:37:07.254  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562587979] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:07.264  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-562587968] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:07.265  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:10.290  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562584943] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:37:10.293  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-562584939] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:37:10.293  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:13.313  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562581920] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:13.323  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-562581910] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:13.323  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:16.344  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562578888] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:16.354  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-562578878] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:16.354  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:17.009  1031  1517 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,07-12 11:37:17.010  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-12 11:37:17.012  1031  1517 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-12 11:37:17.013  1031  1517 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-12 11:37:17.014  1031  1517 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,07-12 11:37:17.028  1031  1517 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,07-12 11:37:19.375  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562575857] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:19.378  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562575854] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:19.379  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:22.400  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562572832] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:22.403  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562572829] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:22.404  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:25.429  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562569803] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:37:25.432  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562569800] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:37:25.433  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:28.453  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562566779] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:28.464  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-562566768] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:28.464  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:31.485  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562563747] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:37:31.488  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562563744] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:31.488  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:34.511  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562560721] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:34.521  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562560718] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:34.521  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:37:35.092  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1acafbdb type 2 when 161057 com.google.android.gms} when 161057
,07-12 11:37:35.138  1797  1797 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-12 11:37:35.144  2054  2054 I ConfigService: onCreate
07-12 11:37:35.145  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-12 11:37:35.147  1797  7068 I ConfigFetchService: running network task: configservice_periodic
07-12 11:37:35.150  1797  7068 I ConfigFetchService: launchTask
,07-12 11:37:35.158  2054  2054 I ConfigService: onBind returning update interface
07-12 11:37:35.160  1797  1797 I ConfigFetchService: service connected
07-12 11:37:35.160  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-12 11:37:35.160  2054  2054 I ConfigService: onBind returning config service
07-12 11:37:35.162  1797  1797 I ConfigClient: service connected
,07-12 11:37:35.237  1031  2011 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:37:35.259  1797  2320 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-12 11:37:35.276   310  7074 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-12 11:37:35.278   310  7074 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-12 11:37:35.278   310  7074 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-12 11:37:35.488  1797  2320 W ConfigFetchTask: bad response from server: 401 Unauthorized
07-12 11:37:35.491  1797  1797 I ConfigFetchService: fetch service done; releasing wakelock
,07-12 11:37:35.497  1797  1797 I ConfigFetchService: stopping self
07-12 11:37:35.541  2054  2054 I ConfigService: onDestroy
,07-12 11:37:37.541  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562557691] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:37.544  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562557688] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:37:37.544  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:40.573  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562554659] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:37:40.584  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-562554648] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:37:40.584  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:37:43.607  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562551625] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:43.610  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562551622] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:37:43.610  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:46.636  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562548596] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:46.639  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562548593] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:46.639  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:49.665  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562545567] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:49.668  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562545564] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:49.668  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:37:52.692  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562542540] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:52.702  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-562542530] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:52.702  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:37:55.723  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562539510] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:55.735  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-562539497] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:55.735  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:37:58.757  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562536475] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:37:58.760  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-562536473] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:37:58.760  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:00.052  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:38:00.053  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:38:00.053  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:38:00.053  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:38:00.069  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:38:00.069  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:38:00.071  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:38:00.073  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:38:01.784  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562533449] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:01.794  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-562533438] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:38:01.794  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:38:02.367  1581  1581 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-12 11:38:02.367  1581  1581 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-12 11:38:02.383  1031  1523 D WifiController: battery changed pluggedType: 2
,07-12 11:38:02.387  1581  1581 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
07-12 11:38:02.387  1581  1581 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-12 11:38:02.389  1922  2063 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-12 11:38:02.389  1922  2063 D LEDHandler: Battery Level Remaining: 100%
07-12 11:38:02.389  1922  2063 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
07-12 11:38:02.392  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:38:02.392  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:38:02.394  6046  6106 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-12 11:38:02.395  1581  1581 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-12 11:38:02.400  6677  6677 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-12 11:38:04.816  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562530417] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:04.819  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562530414] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:38:04.819  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:07.845  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562527387] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:07.848  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562527384] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:07.849  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:10.875  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562524357] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:10.878  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562524354] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:10.887  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:13.908  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562521324] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:13.911  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562521321] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:38:13.912  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:16.936  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-562518296] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:16.939  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562518293] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:16.939  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:19.965  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562515267] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:19.977  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-562515256] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:19.977  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:38:22.997  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562512235] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:23.000  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562512232] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:38:23.000  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:26.027  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562509205] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:26.030  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562509202] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:26.030  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:29.054  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562506178] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:29.064  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-562506169] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:29.064  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:32.086  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562503146] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:38:32.089  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562503143] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:32.089  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:35.111  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562500121] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:35.121  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562500118] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:35.121  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:38:35.513  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:38:35.530  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1f2f849a type 2 when 221491 com.google.android.gms} when 221491
07-12 11:38:35.571  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:38:35.604  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:38:35.636  1797  1797 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-12 11:38:35.641  2054  2054 I ConfigService: onCreate
07-12 11:38:35.642  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-12 11:38:35.643  1797  7080 I ConfigFetchService: running network task: configservice_periodic
07-12 11:38:35.646  1797  7080 I ConfigFetchService: launchTask
07-12 11:38:35.652  2054  2054 I ConfigService: onBind returning update interface
,07-12 11:38:35.656  1797  1797 I ConfigFetchService: service connected
07-12 11:38:35.656  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-12 11:38:35.656  2054  2054 I ConfigService: onBind returning config service
07-12 11:38:35.658  1797  1797 I ConfigClient: service connected
07-12 11:38:35.740  1031  1052 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:38:35.752  1797  3706 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-12 11:38:35.755   310  7098 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-12 11:38:35.755   310  7098 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-12 11:38:35.755   310  7098 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-12 11:38:35.951  1797  3706 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-12 11:38:35.954  1797  1797 I ConfigFetchService: fetch service done; releasing wakelock
,07-12 11:38:35.958  1797  1797 I ConfigFetchService: stopping self
07-12 11:38:36.013  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{397419b5 type 2 when 205293 android} when 205293
07-12 11:38:36.015  2054  2054 I ConfigService: onDestroy
,07-12 11:38:38.138  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562497095] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:38.141  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-562497091] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:38.141  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:41.161  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562494071] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-12 11:38:41.164  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562494068] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-12 11:38:41.164  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:44.190  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562491043] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:44.192  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562491040] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:38:44.193  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:47.218  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-562488014] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:47.222  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562488011] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:47.222  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:50.242  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562484990] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:50.253  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-562484980] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:50.253  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:38:53.271  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562481961] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:38:53.274  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562481958] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:53.274  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:56.306  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562478926] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:56.309  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562478923] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:56.309  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:38:59.334  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562475898] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:59.344  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-562475888] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:38:59.345  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:00.002  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:39:00.057  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:39:00.075  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:39:00.079  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:39:00.079  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:39:00.079  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
07-12 11:39:00.081  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:39:00.081  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:39:00.082  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:39:00.085  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:39:00.139  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:39:02.366  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562472866] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:02.369  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562472863] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:02.370  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:05.397  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562469836] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:05.399  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562469833] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:05.400  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:08.422  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562466810] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:08.431  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-562466801] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-12 11:39:08.431  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:39:11.451  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562463781] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:11.454  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562463778] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:11.464  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:14.485  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562460747] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:14.489  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562460744] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:14.489  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:17.517  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562457716] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:17.520  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-562457712] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:17.520  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:20.546  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562454687] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:20.549  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-562454683] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:20.549  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:23.576  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562451656] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:23.580  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562451653] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:39:23.580  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:26.607  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562448626] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:26.610  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562448623] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:26.610  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:29.633  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562445599] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:29.643  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-562445589] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:29.643  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:32.663  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562442570] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:32.677  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-562442555] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:39:32.677  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:39:35.698  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562439534] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:39:35.701  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562439531] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-12 11:39:35.701  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:38.722  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-562436510] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:38.732  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-562436501] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:38.732  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:39:41.751  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562433481] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:39:41.754  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562433478] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:41.754  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:44.784  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562430448] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:44.794  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-562430438] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:44.794  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:39:47.814  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-562427419] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:47.827  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-562427405] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:47.828  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:50.848  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562424384] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:39:50.851  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562424381] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:50.851  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:51.484  1031  1114 D KnockOnPowerController: LPWG WAKEUP isScreenOn = false, TimeAfterSleep = 253994
,07-12 11:39:51.493  1581  1581 D KeyguardModel: mReceiver, received action: com.lge.android.intent.action.ACTION_KNOCK_ON, sendingUserId:-1
07-12 11:39:51.494  1581  1581 D KeyguardModel: LGIntent.ACTION_KNOCK_ON
07-12 11:39:51.495  1031  1114 I PowerManagerService: Waking up from sleep (uid 1000)...
07-12 11:39:51.496  1031  1114 D KnockOnPowerController: [updateScreenState] screen on = true
07-12 11:39:51.496  1031  1114 D KnockOnPowerController: disable proximity sensor
07-12 11:39:51.496  1031  1031 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2d42484a)
07-12 11:39:51.496  1031  1114 I SensorManager: removeAllSensors() [Sensor: LGE Knock-on Proximity Sensor] bycom.android.server.power.ProximitySensorListener.disable():117
07-12 11:39:51.496  1031  1114 I sensors_hal_Ctx: activate: handle is 70, disable
07-12 11:39:51.496  1031  1114 V sensors_hal_Ctx: activate sensors is 0
07-12 11:39:51.496  1031  1114 D sensors_hal_KnockOnProx: enable: handle=70
07-12 11:39:51.496  1031  1114 D sensors_hal_KnockOnProx: enable: Disabling sensor handle=70
07-12 11:39:51.496  1031  1114 I sensors_hal_SAM: sendCancel:sensor() Sending cancel to svc no:33
07-12 11:39:51.497  1031  1114 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-12 11:39:51.499  1031  1060 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 0, txn Id 69
07-12 11:39:51.499  1031  1060 D sensors_hal_KnockOnProx: processResp: Received SNS_SAM_KNOCK_DISABLE/CANCEL_RESP_V01
,07-12 11:39:51.500  1031  1031 V SmartCoverServiceDelegate: onScreenTurnedOn()
07-12 11:39:51.500  1537  1553 D SmartCoverViewMediator: onScreenTurnedOn, seq = 0
07-12 11:39:51.500  1537  1553 D SmartCoverViewMediator: notifyScreenOnLocked
07-12 11:39:51.501  1537  1537 D SmartCoverViewMediator: handleNotifyScreenOn
07-12 11:39:51.501  1537  1537 I QuickCircle: onScreenTurnedOn
07-12 11:39:51.501  1581  1599 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
07-12 11:39:51.501  1581  1599 D KeyguardViewMediator: notifyScreenOnLocked
07-12 11:39:51.503  1537  1537 D QuickCircleViewManager: applyCoverState:0
07-12 11:39:51.503  1581  1581 D KeyguardViewMediator: handleNotifyScreenOn
07-12 11:39:51.503  1581  1581 D KeyguardViewBase: screen on, instance 1fbacba8
07-12 11:39:51.503  1581  1581 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-12 11:39:51.503  1581  1581 D KeyguardSecurityView: showSecurityScreen(None)
07-12 11:39:51.503  1581  1581 D quilt lockscreen LightParticleRenderer: resume()
07-12 11:39:51.503  1581  1581 D quilt lockscreen LightParticleRenderer: initRenderer()
07-12 11:39:51.508  1031  1517 E WifiStateMachine:  ConnectedState CMD_SCREEN_STATE_CHANGED 1 0
07-12 11:39:51.508  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_SCREEN_STATE_CHANGED 1 0
07-12 11:39:51.508  1031  1517 E WifiStateMachine:  ConnectModeState CMD_SCREEN_STATE_CHANGED 1 0
07-12 11:39:51.509  1031  1517 E WifiStateMachine:  DriverStartedState CMD_SCREEN_STATE_CHANGED 1 0
07-12 11:39:51.509  1031  1517 E WifiStateMachine:  SupplicantStartedState CMD_SCREEN_STATE_CHANGED 1 0
07-12 11:39:51.509  1031  1517 E WifiStateMachine:  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
07-12 11:39:51.510  1031  1517 E WifiStateMachine:  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-12 11:39:51.510  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-12 11:39:51.510  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:39:51.511  1031  1031 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,07-12 11:39:51.514   315  1363 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 1031
07-12 11:39:51.514   315  1363 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-12 11:39:51.514   315  1363 V voice   : voice_set_parameters: enter: screen_state=on
07-12 11:39:51.514   315  1363 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-12 11:39:51.514   315  1363 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-12 11:39:51.514   315  1363 V voice   : voice_set_parameters: exit with code(0)
07-12 11:39:51.514   315  1363 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-12 11:39:51.514   315  1363 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-12 11:39:51.515   315  1363 V msm8974_platform: platform_set_parameters: exit with code(0)
07-12 11:39:51.515   315  1363 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-12 11:39:51.515   315  1363 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-12 11:39:51.515   315  1363 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-12 11:39:51.515   315  1363 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-12 11:39:51.518  1581  1581 D LgeKeyguardWallpaperContainer: queryReferenceOfBackground isPortrait : true ,queryObject : com.lge.lockscreen.widget.draglayer.EffectBridgeImpl@2c68518f
07-12 11:39:51.518  1581  1581 D KeyguardModel: cache file exits
07-12 11:39:51.518  1581  1581 D ScreenTurnOffBySensor: registerProximitySensor
07-12 11:39:51.518  1581  1581 I SensorManager: registerListenerImpl() [Sensor: LGE Knock-on Proximity Sensor, Rate: 200000, SensorEventListener: com.lge.lockscreen.model.ScreenTurnOffBySensor@2d82b8ac] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.registerProximitySensor():54
07-12 11:39:51.519  1031  1917 I sensors_hal_Ctx: batch: handle:70 flags:0x0 period_ns 200000000, timeout 0
07-12 11:39:51.519  1031  1917 D sensors_hal_SAM: batch:sensor() handle:70 flags:0x0 period_ns:200000000 timeout:0
07-12 11:39:51.519  1031  1917 D sensors_hal_SAM: batch:sensor() handle:70 freq:1 report_rate:1 max:1.000000 min:1.000000
07-12 11:39:51.519  1031  1917 I sensors_hal_Ctx: activate: handle is 70, enable
07-12 11:39:51.519  1031  1917 D sensors_hal_Util: waitForResponse: timeout=1000
07-12 11:39:51.520  1031  1056 D sensors_hal_Time: time_service_sensor1_cb: msg_type 1
07-12 11:39:51.520  1031  1056 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 2, txn Id 1
07-12 11:39:51.520  1031  1056 D sensors_hal_Time: tsOffsetIs: Apps: 297514936973; DSPS: 9889601; Offset : -4306101251
07-12 11:39:51.520  1031  1917 V sensors_hal_Ctx: activate sensors is 0
07-12 11:39:51.520  1031  1917 D sensors_hal_KnockOnProx: enable: handle=70
07-12 11:39:51.520  1031  1917 I sensors_hal_SAM: sendEnableReq:sensor() Sending enable to svc no:33
07-12 11:39:51.520  1031  1917 D sensors_hal_Util: waitForResponse: timeout=1000
07-12 11:39:51.521  1031  1517 E WifiStateMachine:  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-12 11:39:51.521  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-12 11:39:51.521  1031  1517 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
07-12 11:39:51.522  1031  1060 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 33, msg Id 2, txn Id 0
07-12 11:39:51.522  1031  1517 E WifiStateMachine:  ConnectedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-12 11:39:51.522  1031  1060 D sensors_hal_KnockOnProx: processResp: Received SNS_SAM_KNOCK_ENABLE_RESP_V01
07-12 11:39:51.522  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-12 11:39:51.522  1031  1517 E WifiStateMachine:  ConnectModeState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-12 11:39:51.523  1031  1517 E WifiStateMachine:  DriverStartedState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
07-12 11:39:51.523  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,07-12 11:39:51.524  1031  1917 D sensors_hal_KnockOnProx: enable: Received response: 0
07-12 11:39:51.528  1581  1581 I SensorManager: registerListenerImpl() [Sensor: LGE Light, Rate: 200000, SensorEventListener: com.lge.lockscreen.model.ScreenTurnOffBySensor@2d82b8ac] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.registerProximitySensor():55
07-12 11:39:51.529  1031  1955 I sensors_hal_Ctx: batch: handle:1 flags:0x0 period_ns 200000000, timeout 0
07-12 11:39:51.529  1031  1955 D sensors_hal_SMGR: batch:sensor(android.sensor.light) handle:1 flags:0x0 period_ns 200000000
07-12 11:39:51.530  1031  1955 D sensors_hal_SMGR: batch:sensor(android.sensor.light) sample_rate=20Hz report_rate_f=0.000000Hz curr sample rate:20 cur rpt rate:0 max:20.000000 min:1.000000
07-12 11:39:51.530  1031  1955 D sensors_hal_SMGR: batch: current sample rate, report rate & buffering are equal to requested (0.000000,0.000000,0)
07-12 11:39:51.530  1031  1955 I sensors_hal_Ctx: activate: handle is 1, enable
07-12 11:39:51.530  1031  1955 V sensors_hal_Ctx: activate sensors is 2
07-12 11:39:51.530  1031  1955 D sensors_hal_SMGR: enable:sensor(android.sensor.light) handle 1, freq=20 report_rate=0 batched=0
07-12 11:39:51.530  1031  1955 I sensors_hal_SMGR: SMGRReportAdd:sensor(android.sensor.light) handle=1, sample_rate=20 report_rate=0 buffer=0
07-12 11:39:51.530  1031  1955 D sensors_hal_SMGR: SMGRPrepareAddMsg:sensor android.sensor.light 
07-12 11:39:51.531  1031  1955 D sensors_hal_Util: waitForResponse: timeout=1000
07-12 11:39:51.532  1581  3171 D quilt lockscreen LockScreenRenderer: onSurfaceCreated()
07-12 11:39:51.533  1031  1057 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 1, Sn 0, msg Id 33, txn Id 1
07-12 11:39:51.533  1031  1057 D sensors_hal_SMGR: processResp: 33
07-12 11:39:51.533  1031  1057 I sensors_hal_SMGR: processBufferingResp: Id: 1 Resp: 1 txn id 1
07-12 11:39:51.533  1031  1955 D sensors_hal_SMGR: SMGRReportAdd: Received Response: 0
07-12 11:39:51.534  1581  1581 V KeyguardStatusView: Enable transport text marquee
07-12 11:39:51.534  1031  2012 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-12 11:39:51.534  1031  1114 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=10000 (287529 ms ago)
07-12 11:39:51.535  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-12 11:39:51.535  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:39:51.536  1922  2063 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,07-12 11:39:51.538  1581  1581 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
07-12 11:39:51.539  1031  1114 D KnockOnPowerController: disable proximity sensor
07-12 11:39:51.540  1922  2063 V LEDService: startInternal : pkg=KnockOn, recordId=0 : LGLedRecord{1aa7c2f6 flags=2 patternId=2 color=0 priority=2 recordId=0 pkg=KnockOn mExceptional=false mNativeNotification=false whichLedPlay=1 patternFilePath=null}
07-12 11:39:51.540  1922  2063 D qdlights: set_light_notifications: 3,0,0,0,3
07-12 11:39:51.540  1922  2063 D qdlights: [pattern_id] = 0
07-12 11:39:51.542  1031  1114 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-12 11:39:51.543  1031  1114 I SensorManager: registerListenerImpl() [Sensor: Motion Accel, Rate: 66667, SensorEventListener: com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@19f87519] bycom.android.internal.policy.impl.WindowOrientationListener.enable():147
07-12 11:39:51.544  1922  2063 I LEDService: getCurrentHighestLGLedRecord : size = 2
07-12 11:39:51.544  1922  2063 D qdlights: set_light_notifications: 0,0,0,0,3
07-12 11:39:51.544  1031  1114 I sensors_hal_Ctx: batch: handle:46 flags:0x0 period_ns 66667000, timeout 0
07-12 11:39:51.544  1031  1114 D sensors_hal_SAM: batch:sensor(com.qti.sensor.motion_accel) handle:46 flags:0x0 period_ns:66667000 timeout:0
07-12 11:39:51.545  1031  1114 D sensors_hal_SAM: batch:sensor(com.qti.sensor.motion_accel) handle:46 freq:1 report_rate:1 max:1.000000 min:0.000000
07-12 11:39:51.545  1031  1114 I sensors_hal_Ctx: activate: handle is 46, enable
07-12 11:39:51.545  1031  1114 V sensors_hal_Ctx: activate sensors is 400000000002
07-12 11:39:51.545  1031  1114 D sensors_hal_LP2: enable: handle=46
07-12 11:39:51.545  1031  1114 I sensors_hal_SAM: sendEnableReq:sensor(com.qti.sensor.motion_accel) Sending enable to svc no:49
07-12 11:39:51.545  1922  2063 I LEDService: updateLightsLocked : turn on led
07-12 11:39:51.546  1031  1114 D sensors_hal_Util: waitForResponse: timeout=1000
07-12 11:39:51.546   493   915 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
07-12 11:39:51.546   493   915 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req f54afd3e
07-12 11:39:51.547  1031  1086 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 2, txn Id 0
07-12 11:39:51.547  1031  1086 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_ENABLE_RESP_V01
07-12 11:39:51.547   344   397 E GBMv2   : Set value is all cleared set the max
07-12 11:39:51.547   344   397 I GBMv2   : VFP is [12]
07-12 11:39:51.547  1031  1114 D sensors_hal_LP2: enable: Received response: 0
07-12 11:39:51.549  1031  1114 D KnockOnPowerController: sendResult : 1
,07-12 11:39:51.550  1031  1555 I QCOM PowerHAL: Got set_interactive hint
07-12 11:39:51.552  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-12 11:39:51.552   279   279 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6082000
07-12 11:39:51.552   279   279 D qdhwcomposer: hwc_blank: Unblanking display: 0
07-12 11:39:51.553  1031  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-12 11:39:51.555  1031  1517 E WifiStateMachine:  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-12 11:39:51.555  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-12 11:39:51.556  1031  1517 E WifiStateMachine:  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
07-12 11:39:51.557  1031  1517 D WifiNative-wlan0: doBoolean: BLACKLIST clear
07-12 11:39:51.558  1581  3171 D lockscreen_weather: lock_settings_weather_animation = 1
07-12 11:39:51.559  1031  1517 D WifiNative-wlan0: BLACKLIST clear: returned true
07-12 11:39:51.560  1031  1517 E WifiStateMachine:  ConnectedState !what:132097 0 0
07-12 11:39:51.560  1031  1517 E WifiStateMachine:  L2ConnectedState !what:132097 0 0
07-12 11:39:51.560  1922  2063 I LEDService: getCurrentHighestLGLedRecord() start. size = 2
07-12 11:39:51.560  1922  2063 I LEDService: getCurrentHighestLGLedRecord() start. size = 2
07-12 11:39:51.560  1031  1517 E WifiStateMachine:  ConnectModeState !what:132097 0 0
07-12 11:39:51.560  1031  1517 E WifiStateMachine:  DriverStartedState !what:132097 0 0
07-12 11:39:51.560  1031  1517 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
,07-12 11:39:51.563  1922  1922 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,07-12 11:39:51.563  1922  1922 D Cliptray Service: lockStatus = 1
07-12 11:39:51.565  1031  1112 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-12 11:39:51.565  1031  1031 V ActivityManager: Display changed displayId=0
07-12 11:39:51.566  1902  1902 D LNfcService: action : android.intent.action.SCREEN_ON
07-12 11:39:51.566  1922  7133 D qdlights: set_light_notifications: 2,ff00ffff,500,0,1
07-12 11:39:51.566  1922  7133 D qdlights: [Current] = 255, R = 0, G = 255, B = 255
07-12 11:39:51.571  1581  3171 D lockscreen_weather: R.bool.weather_service_default_auto_update = true
07-12 11:39:51.571  1581  3171 D lockscreen_weather: weather RefreshPeriod = 3
07-12 11:39:51.571  1581  3171 D lockscreen_weather: com.lge.sizechangable.weather_preferences = true
07-12 11:39:51.571  1581  3171 D lockscreen_weather: getCurrentWeather returns, { city=null weatherText=null weatherCode=0 temperature=null weatherIconResID=-1 }
07-12 11:39:51.572  1581  3171 D quilt lockscreen LockScreenRenderer: onSurfaceChanged() : width = 1440, height = 2560
,07-12 11:39:51.576  1832  1832 D DSDPConnection: Display #0 changed.
07-12 11:39:51.577  1902  7134 D NfcServiceNXP: mScreenState : 2
,07-12 11:39:51.595  1031  1031 D Ulp_jni : JNI:system_update. Event-0
07-12 11:39:51.598  1581  3171 W Adreno-ES20: <__load_uniform_float:825>: GL_INVALID_OPERATION
07-12 11:39:51.602   493  1020 I Sensors : sns_pwr.c(273):acquiring wakelock
07-12 11:39:51.602  1031  1060 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 33, msg Id 5, txn Id 0
07-12 11:39:51.603  1031  1060 D sensors_hal_KnockOnProx: processInd: SNS_SAM_KNOCK_REPORT_IND_V01
07-12 11:39:51.603  1031  1060 D sensors_hal_KnockOnProx: processInd: handle 70, count=1
07-12 11:39:51.603  1031  1060 I sensors_hal_KnockOnProx: processInd : knock-on state changed - FAR
07-12 11:39:51.603  1031  1089 D sensors_hal_Ctx: poll:polldata:1, sensor:70, type:499898103, x:5.000000 y:-0.000007 z:0.000000
07-12 11:39:51.603  1031  1089 D sensors_hal_Ctx: poll: count: 36
07-12 11:39:51.603  1031  1089 D sensors_hal_Util: waitForResponse: timeout=0
,07-12 11:39:51.604  1832  1832 D PhoneInterfaceManager: [PhoneIntfMgr] mSigLevel = 2
07-12 11:39:51.606   313   516 E QMI_FW  : [LGE_VSS_QCCI][AP] Enter qcci_qmi_lge_vss_send_cmd().....
07-12 11:39:51.606   313   516 E QMI_FW  : [LGE_VSS_QCCI][AP] Common sendind MSG = 0x60a
07-12 11:39:51.606  1832  1832 V TelephonyAutoProfiling: [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
07-12 11:39:51.609   313   516 E QMI_FW  : [LGE_VSS_QCCI][AP] Enter qcci_qmi_lge_vss_send_cmd().....
07-12 11:39:51.609   313   516 E QMI_FW  : [LGE_VSS_QCCI][AP] Common sendind MSG = 0x60a
07-12 11:39:51.622  1902  2741 E NxpNfcJni: getReconnectState = 0x0
,07-12 11:39:51.639  1581  1581 I [SystemUI]StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 6 0 -102 -115 -120 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0 level=2
,07-12 11:39:51.639  1581  1581 D TelephonyIcons: updateDataType sub=0, type=0, inetCondition=1 showAtLeast3G=false show4GforLte=true hspaDistinguishable=false
07-12 11:39:51.639  1581  1581 D TelephonyIcons: data type item name: array/telephony_data_type_sim1
07-12 11:39:51.640  1581  1581 D TelephonyIcons: data type item id: 2131623942
07-12 11:39:51.640  1581  1581 D TelephonyIcons: updateDataType mSelectedDataTypeIcon[0]=0, mSelectedDataActivityIndex=0
07-12 11:39:51.640  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-12 11:39:51.640  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:39:51.642  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-12 11:39:51.647  1832  1832 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
07-12 11:39:51.653  1581  1581 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-12 11:39:51.667  1902  7134 D LNfcService: isRequireNfcCRouting() return true
,07-12 11:39:51.667  1902  7134 D LNfcService: isHCERoutingtoHost() return true
07-12 11:39:51.667  1902  7134 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: 0
07-12 11:39:51.667  1902  7134 D NfcService: mEnableLPD: true
07-12 11:39:51.667  1902  7134 D NfcService: mEnableReader: false
07-12 11:39:51.667  1902  7134 D NfcService: mEnableHostRouting: true
07-12 11:39:51.667  1902  7134 D NfcService: newParams.techmask= mTechMask: 0
07-12 11:39:51.667  1902  7134 D NfcService: mEnableLPD: true
07-12 11:39:51.667  1902  7134 D NfcService: mEnableReader: false
07-12 11:39:51.667  1902  7134 D NfcService: mEnableHostRouting: true
07-12 11:39:51.668  1902  7134 D NfcService: screenState= 2
07-12 11:39:51.668  1902  7134 D NfcService: Discovery configuration equal, not updating.
07-12 11:39:51.670  1031  1114 I DisplayPowerController: Unblocked screen on after 127 ms
07-12 11:39:51.670  1031  1114 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-12 11:39:51.675   279   804 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
07-12 11:39:51.683  1581  1581 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
,07-12 11:39:51.703  1581  1581 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-12 11:39:51.747  2711  2711 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]ACTION_SCREEN_ON !!!
,07-12 11:39:51.748  2711  2711 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]scheduledExecutorService is running
07-12 11:39:51.749  1031  2012 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
07-12 11:39:51.749  1031  1052 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
07-12 11:39:51.751  4655  4655 D AppCleanupService: android.intent.action.SCREEN_ON
07-12 11:39:51.752   279   279 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-12 11:39:51.753  1031  1555 D SurfaceControl: Excessive delay in setPowerMode(): 201ms
07-12 11:39:51.754  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:39:51.754  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:39:51.754  1031  1031 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
07-12 11:39:51.901  1031  1057 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
07-12 11:39:51.901  1031  1057 D sensors_hal_SMGR: processBufferingInd: Samples_len=1 Items=1 max_reports_per_index=1
,07-12 11:39:51.901  1031  1057 V sensors_hal_SMGR: processReportInd: St: 0 ReportId: 1 Rate: 0, Len: 1
07-12 11:39:51.901  1031  1057 V sensors_hal_SMGR: processReportInd: Id: PROX_LIGHT_DATA: Ty: 1 Q: 0
07-12 11:39:51.901  1031  1057 V sensors_hal_Light: processReportInd:sensor android.sensor.light 
07-12 11:39:51.901  1031  1057 V sensors_hal_Light: processReportInd: 140000 20.000000
07-12 11:39:51.901  1031  1057 D sensors_hal_SMGR: processReportInd: handle:1 SMGR TS:9901863 HAL TS:297874776434 elapsedRealtimeNano:297882076766
07-12 11:39:51.901  1031  1089 D sensors_hal_Ctx: poll:polldata:1, sensor:1, type:5, x:20.000000 y:0.000000 z:0.000000
07-12 11:39:51.901  1031  1089 D sensors_hal_Ctx: poll: count: 36
07-12 11:39:51.901  1031  1089 D sensors_hal_Util: waitForResponse: timeout=0
,07-12 11:39:51.968  1031  1086 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
,07-12 11:39:51.969  1031  1086 D sensors_hal_LP2: processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
07-12 11:39:51.969  1031  1086 D sensors_hal_LP2: processInd: Samples_len=1 Items=1 max_reports_per_index=1
07-12 11:39:51.969  1031  1086 V sensors_hal_LP2: processInd: X: -0.293549 Y: 0.502548 Z: 9.702652 
07-12 11:39:51.969  1031  1089 D sensors_hal_Ctx: poll:polldata:1, sensor:46, type:499898101, x:-0.293549 y:0.502548 z:9.702652
07-12 11:39:51.969  1031  1089 D sensors_hal_Ctx: poll: count: 36
07-12 11:39:51.969  1031  1089 D sensors_hal_Util: waitForResponse: timeout=0
,07-12 11:39:52.018  1031  1086 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 49, msg Id 5, txn Id 0
07-12 11:39:52.018  1031  1086 D sensors_hal_LP2: processInd: SNS_SAM_EVENT_GATED_SENSOR_REPORT_IND_V01
07-12 11:39:52.018  1031  1086 D sensors_hal_LP2: processInd: Samples_len=1 Items=1 max_reports_per_index=1
07-12 11:39:52.018  1031  1086 V sensors_hal_LP2: processInd: X: -0.286896 Y: 0.497406 Z: 9.704056 
,07-12 11:39:52.018  1031  1089 D sensors_hal_Ctx: poll:polldata:1, sensor:46, type:499898101, x:-0.286896 y:0.497406 z:9.704056
,07-12 11:39:52.019  1031  1089 D sensors_hal_Ctx: poll: count: 36
07-12 11:39:52.019  1031  1089 D sensors_hal_Util: waitForResponse: timeout=0
07-12 11:39:52.070  1922  7133 D qdlights: set_light_notifications: 2,f700f7f7,10,0,1
07-12 11:39:52.070  1922  7133 D qdlights: [Current] = 247, R = 0, G = 247, B = 247
,07-12 11:39:52.082  1922  7133 D qdlights: set_light_notifications: 2,ef00efef,10,0,1
07-12 11:39:52.082  1922  7133 D qdlights: [Current] = 239, R = 0, G = 239, B = 239
,07-12 11:39:52.095  1922  7133 D qdlights: set_light_notifications: 2,e700e7e7,10,0,1
07-12 11:39:52.095  1922  7133 D qdlights: [Current] = 231, R = 0, G = 231, B = 231
,07-12 11:39:52.106  1922  7133 D qdlights: set_light_notifications: 2,df00dfdf,10,0,1
07-12 11:39:52.106  1922  7133 D qdlights: [Current] = 223, R = 0, G = 223, B = 223
,07-12 11:39:52.117  1922  7133 D qdlights: set_light_notifications: 2,d700d7d7,10,0,1
07-12 11:39:52.117  1922  7133 D qdlights: [Current] = 215, R = 0, G = 215, B = 215
,07-12 11:39:52.129  1922  7133 D qdlights: set_light_notifications: 2,cf00cfcf,10,0,1
07-12 11:39:52.129  1922  7133 D qdlights: [Current] = 207, R = 0, G = 207, B = 207
,07-12 11:39:52.140  1922  7133 D qdlights: set_light_notifications: 2,c700c7c7,10,0,1
07-12 11:39:52.140  1922  7133 D qdlights: [Current] = 199, R = 0, G = 199, B = 199
07-12 11:39:52.151  1922  7133 D qdlights: set_light_notifications: 2,bf00bfbf,10,0,1
07-12 11:39:52.151  1922  7133 D qdlights: [Current] = 191, R = 0, G = 191, B = 191
,07-12 11:39:52.162  1922  7133 D qdlights: set_light_notifications: 2,b700b7b7,10,0,1
07-12 11:39:52.162  1922  7133 D qdlights: [Current] = 183, R = 0, G = 183, B = 183
,07-12 11:39:52.174  1922  7133 D qdlights: set_light_notifications: 2,af00afaf,10,0,1
07-12 11:39:52.174  1922  7133 D qdlights: [Current] = 175, R = 0, G = 175, B = 175
,07-12 11:39:52.185  1922  7133 D qdlights: set_light_notifications: 2,a200a2a2,10,0,1
07-12 11:39:52.185  1922  7133 D qdlights: [Current] = 162, R = 0, G = 162, B = 162
07-12 11:39:52.196  1922  7133 D qdlights: set_light_notifications: 2,97009797,10,0,1
07-12 11:39:52.196  1922  7133 D qdlights: [Current] = 151, R = 0, G = 151, B = 151
,07-12 11:39:52.207  1922  7133 D qdlights: set_light_notifications: 2,8c008c8c,10,0,1
07-12 11:39:52.208  1922  7133 D qdlights: [Current] = 140, R = 0, G = 140, B = 140
07-12 11:39:52.219  1922  7133 D qdlights: set_light_notifications: 2,81008181,10,0,1
07-12 11:39:52.219  1922  7133 D qdlights: [Current] = 129, R = 0, G = 129, B = 129
,07-12 11:39:52.230  1922  7133 D qdlights: set_light_notifications: 2,76007676,10,0,1
07-12 11:39:52.230  1922  7133 D qdlights: [Current] = 118, R = 0, G = 118, B = 118
,07-12 11:39:52.241  1922  7133 D qdlights: set_light_notifications: 2,6b006b6b,10,0,1
07-12 11:39:52.241  1922  7133 D qdlights: [Current] = 107, R = 0, G = 107, B = 107
,07-12 11:39:52.252  1922  7133 D qdlights: set_light_notifications: 2,60006060,10,0,1
07-12 11:39:52.253  1922  7133 D qdlights: [Current] = 96, R = 0, G = 96, B = 96
,07-12 11:39:52.264  1922  7133 D qdlights: set_light_notifications: 2,55005555,10,0,1
07-12 11:39:52.264  1922  7133 D qdlights: [Current] = 85, R = 0, G = 85, B = 85
,07-12 11:39:52.275  1922  7133 D qdlights: set_light_notifications: 2,4a004a4a,10,0,1
07-12 11:39:52.275  1922  7133 D qdlights: [Current] = 74, R = 0, G = 74, B = 74
,07-12 11:39:52.286  1922  7133 D qdlights: set_light_notifications: 2,3f003f3f,10,0,1
,07-12 11:39:52.286  1922  7133 D qdlights: [Current] = 63, R = 0, G = 63, B = 63
07-12 11:39:52.298  1922  7133 D qdlights: set_light_notifications: 2,35003636,10,0,1
,07-12 11:39:52.298  1922  7133 D qdlights: [Current] = 53, R = 0, G = 54, B = 54
07-12 11:39:52.309  1922  7133 D qdlights: set_light_notifications: 2,30003131,10,0,1
,07-12 11:39:52.309  1922  7133 D qdlights: [Current] = 48, R = 0, G = 49, B = 49
07-12 11:39:52.320  1922  7133 D qdlights: set_light_notifications: 2,2b002c2c,10,0,1
07-12 11:39:52.320  1922  7133 D qdlights: [Current] = 43, R = 0, G = 44, B = 44
,07-12 11:39:52.331  1922  7133 D qdlights: set_light_notifications: 2,26002727,10,0,1
,07-12 11:39:52.331  1922  7133 D qdlights: [Current] = 38, R = 0, G = 39, B = 39
07-12 11:39:52.343  1922  7133 D qdlights: set_light_notifications: 2,21002222,10,0,1
07-12 11:39:52.343  1922  7133 D qdlights: [Current] = 33, R = 0, G = 34, B = 34
,07-12 11:39:52.354  1922  7133 D qdlights: set_light_notifications: 2,1c001d1d,10,0,1
07-12 11:39:52.354  1922  7133 D qdlights: [Current] = 28, R = 0, G = 29, B = 29
,07-12 11:39:52.365  1922  7133 D qdlights: set_light_notifications: 2,17001818,10,0,1
,07-12 11:39:52.365  1922  7133 D qdlights: [Current] = 23, R = 0, G = 24, B = 24
,07-12 11:39:52.377  1922  7133 D qdlights: set_light_notifications: 2,12001313,10,0,1
,07-12 11:39:52.377  1922  7133 D qdlights: [Current] = 18, R = 0, G = 19, B = 19
,07-12 11:39:52.388  1922  7133 D qdlights: set_light_notifications: 2,d000e0e,10,0,1
,07-12 11:39:52.388  1922  7133 D qdlights: [Current] = 13, R = 0, G = 14, B = 14
,07-12 11:39:52.400  1922  7133 D qdlights: set_light_notifications: 2,8000909,10,0,1
07-12 11:39:52.400  1922  7133 D qdlights: [Current] = 8, R = 0, G = 9, B = 9
,07-12 11:39:52.412  1922  2063 D LEDHandler: handleMessage() repeat = false, whichLed = 1
07-12 11:39:52.412  1922  2063 D qdlights: set_light_notifications: 0,0,0,0,1
,07-12 11:39:52.413  1922  2063 I LEDService: getCurrentHighestLGLedRecord : size = 1
,07-12 11:39:52.413  1922  2063 D qdlights: set_light_notifications: 0,0,0,0,3
07-12 11:39:52.415  1922  2063 I LEDService: updateLightsLocked : turn off led
07-12 11:39:52.415  1922  2063 D qdlights: set_light_notifications: 0,0,0,0,3
07-12 11:39:52.509  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:39:52.717   493   915 I Sensors : sns_sam_dep.c(465):Algo b76018ca Generating dependent req 83777081
,07-12 11:39:52.899   344   399 E GBMv2   : DFP En is all cleared set to be enabled
,07-12 11:39:52.900   344   399 E GBMv2   : Set value is all cleared set the max
07-12 11:39:52.900   344   399 I GBMv2   : DFP Enabled. Ignore VFP set
,07-12 11:39:53.102   493   504 I Sensors : sns_pwr.c(301):releasing wakelock
,07-12 11:39:53.514  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:39:53.691  1581  1581 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-12 11:39:53.691  1581  1581 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-12 11:39:53.699  1031  1523 D WifiController: battery changed pluggedType: 2
07-12 11:39:53.703  1581  1581 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
07-12 11:39:53.703  1581  1581 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-12 11:39:53.704  1922  2063 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-12 11:39:53.704  1922  2063 D LEDHandler: Battery Level Remaining: 100%
07-12 11:39:53.704  1922  2063 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
07-12 11:39:53.708  1581  1581 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-12 11:39:53.710  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:39:53.711  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:39:53.712  6046  6106 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-12 11:39:53.712  6677  6677 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-12 11:39:53.748  1031  1920 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-12 11:39:53.879  1031  1517 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562421353] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:53.882  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562421350] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:54.526  1031  1517 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:642] from screen [on:0 period:-562420706] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:54.529  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562420703] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:54.531  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:39:55.026   334   415 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-12 11:39:55.748  1031  1955 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-12 11:39:57.549  1031  1517 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-562417683] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:57.552  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562417680] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:39:57.552  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-12 11:39:57.748  1031  2032 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-12 11:39:59.030   334   415 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,07-12 11:39:59.501  1031  1114 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=10000 (295496 ms ago)
,07-12 11:39:59.748  1031  1629 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,07-12 11:40:00.001  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:40:00.041  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:40:00.041  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:40:00.041  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:40:00.044  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:40:00.046  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:40:00.046  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:40:00.047  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:40:00.048  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:40:00.051  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
07-12 11:40:00.100  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:40:00.575  1031  1517 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562414658] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:40:00.578  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562414655] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-12 11:40:00.578  1031  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-12 11:40:01.496  1031  1114 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=10000 (297492 ms ago)
,07-12 11:40:01.497  1031  1114 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-12 11:40:01.497  1031  1114 D KnockOnPowerController: [updateScreenState] screen on = false
07-12 11:40:01.497  1031  1114 D KnockOnPowerController: disable proximity sensor
07-12 11:40:01.497  1031  1114 D KnockOnPowerController: enable proximity sensor
07-12 11:40:01.498  1031  1114 I SensorManager: registerListenerImpl() [Sensor: LGE Knock-on Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@30505f1] bycom.android.server.power.ProximitySensorListener.enable():107
07-12 11:40:01.502  1031  1114 I sensors_hal_Ctx: flush: handle is 70
07-12 11:40:01.502  1031  1114 I sensors_hal_SAM: flush:sensor() handle:70
,07-12 11:40:01.505  1031  1114 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
07-12 11:40:01.524  1031  1114 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=10000 (297519 ms ago)
07-12 11:40:01.526  1031  1031 I SensorManager: removeAllSensors() [Sensor: Motion Accel] bycom.android.internal.policy.impl.WindowOrientationListener.disable():166
07-12 11:40:01.526  1031  1031 I sensors_hal_Ctx: activate: handle is 46, disable
07-12 11:40:01.526  1031  1031 V sensors_hal_Ctx: activate sensors is 2
07-12 11:40:01.526  1031  1031 D sensors_hal_LP2: enable: handle=46
07-12 11:40:01.526  1031  1031 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-12 11:40:01.526  1031  1031 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,07-12 11:40:01.532  1031  1114 D KnockOnPowerController: proximity onSensorChanged : proximity = 1
,07-12 11:40:01.532  1031  1114 I KnockOnPowerController: current mode = 1  value = 1 1
07-12 11:40:01.533  1581  2161 D KeyguardViewMediator: onScreenTurnedOff(3)
07-12 11:40:01.533  1581  2161 D KeyguardViewMediator: notifyScreenOffLocked
07-12 11:40:01.533  1581  2161 E KeyguardViewMediator: resetStateLocked
07-12 11:40:01.534  1581  1581 D KeyguardViewMediator: handleNotifyScreenOff
07-12 11:40:01.534  1031  1114 I KnockOnPowerController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
07-12 11:40:01.534  1581  1581 D KeyguardViewBase: screen off, instance 1fbacba8 at 307529
07-12 11:40:01.534  1581  1581 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=true)
07-12 11:40:01.534  1581  1581 D KeyguardSecurityView: showSecurityScreen(None)
07-12 11:40:01.535  1581  1581 V LockDragLayerEffect: reset() : resets state to STATE_RESET_LOCK
07-12 11:40:01.536  1581  1581 D quilt lockscreen LightParticleRenderer: pause()
07-12 11:40:01.537  1581  1581 D quilt lockscreen LightParticleRenderer: initRenderer()
07-12 11:40:01.538  1537  1552 D SmartCoverViewMediator: onScreenTurnedOff(3)
07-12 11:40:01.538  1537  1552 D SmartCoverViewMediator: notifyScreenOffLocked
07-12 11:40:01.538  1537  1537 D SmartCoverViewMediator: handleNotifyScreenOFF
07-12 11:40:01.538  1537  1537 I QuickCircle: onScreenTurnedOff
07-12 11:40:01.539  1537  1537 D LgeQuickCoverOverlayWindow: updateVisibility:hideSmartLighting
,07-12 11:40:01.539  1537  1537 D LgeQuickCoverOverlayWindow: updateVisibility:hideNotification
07-12 11:40:01.539  1537  1537 D QuickCircleViewManager: applyCoverState:1
07-12 11:40:01.539  1537  1537 D QuickCircleViewManager: getState: 0
07-12 11:40:01.539  1537  1537 D QuickCircleViewManager: applyCoverState:LCD Off -> go to lock
07-12 11:40:01.539  1537  1537 D QuickCircleViewManager: getState: 0
,07-12 11:40:01.553  1031  1517 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
07-12 11:40:01.554  1031  1517 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
07-12 11:40:01.554  1031  1517 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
07-12 11:40:01.556  1031  1517 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-12 11:40:01.556  1031  1517 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-12 11:40:01.557  1031  1517 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
07-12 11:40:01.559  1031  1114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.power.PowerManagerServiceEx$3.run:1231 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,07-12 11:40:01.560  1031  1517 E WifiStateMachine:  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-12 11:40:01.560  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-12 11:40:01.560  1031  1517 E WifiStateMachine:  ConnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-12 11:40:01.562  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
,07-12 11:40:01.562  1031  1517 E WifiStateMachine:  ConnectModeState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-12 11:40:01.563  1031  1517 E WifiStateMachine:  DriverStartedState CMD_SET_SUSPEND_OPT_ENABLED 1 0
07-12 11:40:01.563  1031  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-12 11:40:01.564   315  1363 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 1031
07-12 11:40:01.564   315  1363 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-12 11:40:01.564   315  1363 V voice   : voice_set_parameters: enter: screen_state=off
07-12 11:40:01.564   315  1363 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-12 11:40:01.564   315  1363 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-12 11:40:01.564   315  1363 V voice   : voice_set_parameters: exit with code(0)
07-12 11:40:01.564   315  1363 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-12 11:40:01.564   315  1363 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-12 11:40:01.565   315  1363 V msm8974_platform: platform_set_parameters: exit with code(0)
07-12 11:40:01.565   315  1363 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-12 11:40:01.565   315  1363 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-12 11:40:01.565   315  1363 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-12 11:40:01.566  1031  1114 I PowerManagerService: Sleeping (uid 1000)...
07-12 11:40:01.566  1031  1114 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=10000 (297561 ms ago)
07-12 11:40:01.573  1031  1523 D WifiController: CMD_SCREEN_OFF 
07-12 11:40:01.573  1031  1523 D WifiController: shouldWifiStayAwake TRUE
07-12 11:40:01.576  1031  1091 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-12 11:40:01.581  1581  1581 D ScreenTurnOffBySensor: unregisterProximitySensor
07-12 11:40:01.581  1581  1581 I SensorManager: removeAllSensors() [Sensor: LGE Light] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.unregisterProximitySensor():63
07-12 11:40:01.582  1031  1955 I sensors_hal_Ctx: activate: handle is 1, disable
07-12 11:40:01.582  1031  1955 V sensors_hal_Ctx: All sensors stop, stop the time_service.
07-12 11:40:01.582  1031  1955 D sensors_hal_Time: send stop time_service command
07-12 11:40:01.582  1031  1955 D sensors_hal_Util: waitForResponse: timeout=1000
07-12 11:40:01.583  1031  1056 D sensors_hal_Time: time_service_sensor1_cb: msg_type 1
07-12 11:40:01.583  1031  1056 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 0, txn Id 1
07-12 11:40:01.583  1031  1955 V sensors_hal_Ctx: activate sensors is 0
07-12 11:40:01.583  1031  1955 D sensors_hal_SMGR: enable:sensor(android.sensor.light) Deactivating sensor handle=1
07-12 11:40:01.583  1031  1955 I sensors_hal_SMGR: SMGRReportDelete:sensor(android.sensor.light) handle=1
07-12 11:40:01.583  1031  1955 D sensors_hal_Util: waitForResponse: timeout=1000
07-12 11:40:01.585  1031  1057 V sensors_hal_SMGR: SMGRSensor_sensor1_cb: msg_type 1, Sn 0, msg Id 33, txn Id 1
07-12 11:40:01.585  1031  1057 D sensors_hal_SMGR: processResp: 33
07-12 11:40:01.585  1031  1057 I sensors_hal_SMGR: processBufferingResp: Id: 1 Resp: 0 txn id 1
07-12 11:40:01.585  1031  1955 D sensors_hal_SMGR: SMGRReportDelete: Rcvd success response from request
07-12 11:40:01.585  1581  1581 I SensorManager: removeAllSensors() [Sensor: LGE Knock-on Proximity Sensor] bycom.lge.lockscreen.model.ScreenTurnOffBySensor.unregisterProximitySensor():63
07-12 11:40:01.586  1031  2032 I sensors_hal_Ctx: batch: handle:70 flags:0x0 period_ns 200000000, timeout 0
07-12 11:40:01.586  1031  2032 D sensors_hal_SAM: batch:sensor() handle:70 flags:0x0 period_ns:200000000 timeout:0
07-12 11:40:01.586  1031  2032 D sensors_hal_SAM: batch:sensor() handle:70 freq:1 report_rate:1 max:1.000000 min:1.000000
07-12 11:40:01.586  1581  1581 D KeyguardViewMediator: handleReset
07-12 11:40:01.587  6081  6081 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-12 11:40:01.588  1031  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,07-12 11:40:01.611  1581  1581 D KeyguardBackground: updateKeyguardState mState ? 1 ,goingToFullShade ? false ,fromShadeLocked ? false
07-12 11:40:01.611  1581  1581 D KeyguardBackground: Backdrop animation start. dest Alpha : 1
,07-12 11:40:01.611  1581  1581 D KeyguardBackground: setKeyguardBackground isPortrait ? true
,07-12 11:40:01.615  1031  1086 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-12 11:40:01.615  1031  1086 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
07-12 11:40:01.623  1581  1581 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO BACK HOME RECENT clock SEARCH >
07-12 11:40:01.623  1581  1581 D StatusBarKeyguardViewManager: adjustCameraSliderVisibility: shouldVisible = false, mGlanceViewNow = false
07-12 11:40:01.623  1581  1581 D StatusBarWindowView: onScreenTurnedOff why = 3
07-12 11:40:01.623  1581  1581 V KeyguardStatusView: Disable transport text marquee
,07-12 11:40:01.642  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-12 11:40:01.653  1581  1581 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
07-12 11:40:01.656  1922  2063 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-12 11:40:01.656  1922  2063 D qdlights: set_light_notifications: 0,0,0,0,3
,07-12 11:40:01.658  1922  1922 D VolumeVibrator: clear
07-12 11:40:01.660  1922  1922 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-12 11:40:01.660  1922  2063 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-12 11:40:01.660  1922  2063 D qdlights: set_light_notifications: 0,0,0,0,3
07-12 11:40:01.661  1922  2063 I LEDService: updateLightsLocked : turn on led
07-12 11:40:01.661  1922  2063 D qdlights: set_light_notifications: 3,4,0,0,1
07-12 11:40:01.661  1922  2063 D qdlights: [pattern_id] = 4
07-12 11:40:01.663  1902  1902 D LNfcService: action : android.intent.action.SCREEN_OFF
07-12 11:40:01.663  1922  2063 D LEDHandler: RESTART MSG
07-12 11:40:01.665  1902  2412 D NfcServiceNXP: mScreenState : 1
,07-12 11:40:01.677  2013  2013 I [LGHome]EVENT: [Launcher.java:1836:onReceive()]Screen Off
07-12 11:40:01.678  1832  1832 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
07-12 11:40:01.691  2711  2711 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]ACTION_SCREEN_OFF !!!
07-12 11:40:01.691  2711  2711 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]case 9 : com.test.thalitest
,07-12 11:40:01.703  1902  2741 E NxpNfcJni: getReconnectState = 0x0
,07-12 11:40:01.728  2711  4078 D LIA_MrGDBLogger_LoggerThread: [dreamwood]App Usage Logging
07-12 11:40:01.730  2711  2711 D LIA_MrGDBLogger_AppUsageDetector: [dreamwood]scheduledExecutorService is stopped
,07-12 11:40:01.737  4655  4655 D AppCleanupService: android.intent.action.SCREEN_OFF
,07-12 11:40:01.737  1902  2412 D LNfcService: isRequireNfcCRouting() return true
07-12 11:40:01.737  1902  2412 D LNfcService: isHCERoutingtoHost() return true
07-12 11:40:01.737  1902  2412 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: 0
07-12 11:40:01.737  1902  2412 D NfcService: mEnableLPD: true
07-12 11:40:01.737  1902  2412 D NfcService: mEnableReader: false
07-12 11:40:01.737  1902  2412 D NfcService: mEnableHostRouting: true
07-12 11:40:01.737  1902  2412 D NfcService: newParams.techmask= mTechMask: 0
07-12 11:40:01.737  1902  2412 D NfcService: mEnableLPD: true
07-12 11:40:01.737  1902  2412 D NfcService: mEnableReader: false
07-12 11:40:01.737  1902  2412 D NfcService: mEnableHostRouting: true
07-12 11:40:01.737  1902  2412 D NfcService: screenState= 1
07-12 11:40:01.737  1902  2412 D NfcService: Discovery configuration equal, not updating.
07-12 11:40:01.739  1939  1939 E LibSecureUISvc: svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
07-12 11:40:01.740  4655  7184 D AppCleanupService: AppUsageStatsSaveTask
07-12 11:40:01.741  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:40:01.741  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:40:01.742  1031  1031 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
,07-12 11:40:02.053  1031  1112 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-12 11:40:02.053  1031  1031 V ActivityManager: Display changed displayId=0
,07-12 11:40:02.055   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
07-12 11:40:02.055   279   279 D qdhwcomposer: hwc_blank: Blanking display: 0
07-12 11:40:02.061  1832  1832 D DSDPConnection: Display #0 changed.
07-12 11:40:02.332   279   804 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-12 11:40:02.334   279   279 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-12 11:40:02.338  1031  1555 D SurfaceControl: Excessive delay in setPowerMode(): 285ms
,07-12 11:40:02.339  1031  1555 I QCOM PowerHAL: Got set_interactive hint
07-12 11:40:03.033   334   415 E ThermalEngine: [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 578000000
,07-12 11:40:03.596  1031  1517 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-562411637] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:40:03.599  1031  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-562411634] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-12 11:40:27.527  1031  3299 I LocationManagerService: remove d33719f
,07-12 11:40:27.536  1031  3299 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-12 11:40:27.536  1031  3299 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-12 11:40:27.538  1031  3299 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-12 11:40:27.540  1031  3299 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-12 11:40:27.542  1031  3299 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-12 11:40:35.990  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{165c40d8 type 2 when 341951 com.google.android.gms} when 341951
,07-12 11:40:36.047  1797  1797 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-12 11:40:36.054  2054  2054 I ConfigService: onCreate
07-12 11:40:36.055  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-12 11:40:36.058  1797  7194 I ConfigFetchService: running network task: configservice_periodic
07-12 11:40:36.061  1797  7194 I ConfigFetchService: launchTask
,07-12 11:40:36.069  2054  2054 I ConfigService: onBind returning update interface
07-12 11:40:36.071  1797  1797 I ConfigFetchService: service connected
07-12 11:40:36.071  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-12 11:40:36.071  2054  2054 I ConfigService: onBind returning config service
07-12 11:40:36.073  1797  1797 I ConfigClient: service connected
,07-12 11:40:36.265  1031  1917 I art     : Explicit concurrent mark sweep GC freed 82658(3MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 43MB/65MB, paused 2.678ms total 175.506ms
,07-12 11:40:36.296  1031  1921 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:40:36.307  1797  3759 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-12 11:40:36.309   310  7203 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:40:36.310   310  7203 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,07-12 11:40:36.353   310  7203 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-12 11:40:36.596  1797  3759 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-12 11:40:36.606  1797  1797 I ConfigFetchService: fetch service done; releasing wakelock
07-12 11:40:36.609  1797  1797 I ConfigFetchService: stopping self
07-12 11:40:36.658  2054  2054 I ConfigService: onDestroy
,07-12 11:41:00.003  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:41:00.057  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:41:00.068  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-12 11:41:00.068  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:41:00.069  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:41:00.069  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
07-12 11:41:00.072  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:41:00.072  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:41:00.076  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:41:00.082  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:41:00.115  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:42:00.100  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:42:00.100  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:42:00.100  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:42:00.101  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:42:00.116  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:42:00.116  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:42:00.118  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:42:00.120  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:43:00.054  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:43:00.055  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated(),
07-12 11:43:00.055  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
07-12 11:43:00.055  1581  1581 I [SystemUI]Clock: called onTimeUpdated(),
,07-12 11:43:00.076  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:43:00.076  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:43:00.077  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:43:00.078  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:44:00.058  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:44:00.058  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated(),
07-12 11:44:00.059  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
07-12 11:44:00.059  1581  1581 I [SystemUI]Clock: called onTimeUpdated(),
,07-12 11:44:00.080  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:44:00.080  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:44:00.082  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:44:00.083  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:44:03.325  1581  1581 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-12 11:44:03.326  1581  1581 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-12 11:44:03.340  1581  1581 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,07-12 11:44:03.342  1031  1523 D WifiController: battery changed pluggedType: 2
07-12 11:44:03.343  1581  1581 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-12 11:44:03.344  1581  1581 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-12 11:44:03.345  1922  2063 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-12 11:44:03.345  1922  2063 D LEDHandler: Battery Level Remaining: 100%
07-12 11:44:03.345  1922  2063 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
07-12 11:44:03.351  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:44:03.351  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:44:03.352  6046  6106 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:44:03.356  6677  6677 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-12 11:44:36.622  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:44:36.649  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d10d1ab type 2 when 582600 com.google.android.gms} when 582600
,07-12 11:44:36.703  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:44:36.732  1797  1797 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-12 11:44:36.738  2054  2054 I ConfigService: onCreate
07-12 11:44:36.738  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-12 11:44:36.747  1797  7213 I ConfigFetchService: running network task: configservice_periodic
,07-12 11:44:36.760  1797  7213 I ConfigFetchService: launchTask
,07-12 11:44:36.765  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
07-12 11:44:36.770  2054  2054 I ConfigService: onBind returning update interface
07-12 11:44:36.772  1797  1797 I ConfigFetchService: service connected
,07-12 11:44:36.774  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-12 11:44:36.774  2054  2054 I ConfigService: onBind returning config service
07-12 11:44:36.776  1797  1797 I ConfigClient: service connected
07-12 11:44:36.851  1031  1920 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:44:36.865  1797  5514 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-12 11:44:36.875   310  7231 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-12 11:44:36.876   310  7231 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-12 11:44:36.876   310  7231 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-12 11:44:37.059  1797  5514 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-12 11:44:37.061  1797  1797 I ConfigFetchService: fetch service done; releasing wakelock
,07-12 11:44:37.068  1797  1797 I ConfigFetchService: stopping self
,07-12 11:44:37.113  2054  2054 I ConfigService: onDestroy
,07-12 11:45:00.058  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:45:00.059  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:45:00.059  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:45:00.060  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:45:00.074  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:45:00.075  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:45:00.077  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:45:00.079  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:45:01.551  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:45:01.577  6626  6626 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-12 11:45:01.582  6626  6626 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@35322467
07-12 11:45:01.604  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:45:01.635  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:45:26.554  1031  1051 I ActivityManager: Killing 6727:com.android.settings/1000 (adj 15): empty #17
,07-12 11:45:26.589  1031  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_6727/cgroup.procs: No such file or directory
,07-12 11:46:00.002  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:46:00.055  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:46:00.072  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-12 11:46:00.072  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:46:00.072  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:46:00.075  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
07-12 11:46:00.077  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:46:00.077  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:46:00.078  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:46:00.080  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:46:00.126  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:47:00.051  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:47:00.051  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:47:00.051  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:47:00.052  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:47:00.066  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:47:00.066  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:47:00.073  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:47:00.077  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:48:00.060  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:48:00.060  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:48:00.060  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:48:00.061  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:48:00.077  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:48:00.077  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:48:00.080  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:48:00.081  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:49:00.069  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-12 11:49:00.069  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:49:00.069  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:49:00.070  1581  1581 I [SystemUI]Clock: called onTimeUpdated(),
,07-12 11:49:00.089  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:49:00.089  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:49:00.092  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:49:00.094  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:50:00.077  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:50:00.077  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:50:00.078  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:50:00.078  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:50:00.093  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:50:00.093  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:50:00.097  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:50:00.099  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:51:00.086  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:51:00.086  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:51:00.087  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:51:00.087  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:51:00.103  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:51:00.104  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:51:00.106  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:51:00.108  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:51:38.299  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:51:38.305  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b83b3aa type 2 when 1004279 com.android.bluetooth} when 1004279
07-12 11:51:38.322  6046  6183 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-12 11:51:38.322  6046  6183 W bt-smp  : Plain text(LSB ~ MSB) = a3 1c 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-12 11:51:38.322  6046  6183 W bt-smp  : Encrypted text(LSB ~ MSB) = 06 c7 3f 64 02 bd c2 20 07 1c a1 fd c9 ca c7 50 
07-12 11:51:38.322  6046  6183 W bt-btm  : Stopping oneshot timer
,07-12 11:51:38.346  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:51:38.374  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:52:00.057  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:52:00.057  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:52:00.057  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:52:00.058  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:52:00.073  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:52:00.073  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:52:00.077  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:52:00.078  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:52:16.098  1031  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1014416023, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,07-12 11:52:16.117  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{274d7b9b type 2 when 1031055 com.google.android.gms} when 1031055
,07-12 11:52:16.156  2568  2568 D [Concierge]Service: onStartCommand(). Type : 9
,07-12 11:52:16.187  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1014416023 [*alarm*], flags=0x0
,07-12 11:52:16.204  2054  7058 D GCM     : Message class com.google.e.a.a.h
,07-12 11:52:46.227  1031  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{c890b38 type 2 when 1072195 com.google.android.gms} when 1072195
,07-12 11:52:46.293  1797  1797 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-12 11:52:46.300  2054  2054 I ConfigService: onCreate
07-12 11:52:46.302  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-12 11:52:46.305  1797  7247 I ConfigFetchService: running network task: configservice_periodic
07-12 11:52:46.308  1797  7247 I ConfigFetchService: launchTask
,07-12 11:52:46.317  2054  2054 I ConfigService: onBind returning update interface
07-12 11:52:46.319  1797  1797 I ConfigFetchService: service connected
07-12 11:52:46.319  2054  2054 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-12 11:52:46.319  2054  2054 I ConfigService: onBind returning config service
07-12 11:52:46.320  1797  1797 I ConfigClient: service connected
,07-12 11:52:46.394  1031  1917 V SIM_STK : Menu title from STK is T-Mobile
,07-12 11:52:46.429  1797  2311 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-12 11:52:46.434   310  7259 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-12 11:52:46.435   310  7259 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-12 11:52:46.473   310  7259 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-12 11:52:46.740  1797  2311 W ConfigFetchTask: bad response from server: 401 Unauthorized
,07-12 11:52:46.743  1797  1797 I ConfigFetchService: fetch service done; releasing wakelock
,07-12 11:52:46.743  1797  1797 I ConfigFetchService: stopping self
,07-12 11:52:46.771  2054  2054 I ConfigService: onDestroy
,07-12 11:53:00.056  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:53:00.056  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:53:00.056  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:53:00.057  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:53:00.072  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:53:00.073  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:53:00.077  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:53:00.078  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:54:00.113  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:54:00.113  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:54:00.113  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:54:00.114  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:54:00.131  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:54:00.131  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:54:00.134  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:54:00.137  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:55:00.059  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:55:00.059  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:55:00.059  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:55:00.060  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:55:00.076  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
,07-12 11:55:00.076  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:55:00.079  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
,07-12 11:55:00.081  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:55:14.124  1031  1091 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 11:56:00.056  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:56:00.056  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:56:00.056  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-12 11:56:00.057  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:56:00.072  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:56:00.072  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:56:00.074  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:56:00.077  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:57:00.056  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:57:00.056  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:57:00.056  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:57:00.057  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:57:00.070  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:57:00.071  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:57:00.073  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:57:00.077  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:58:00.056  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:58:00.056  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:58:00.056  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:58:00.057  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,07-12 11:58:00.071  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:58:00.071  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:58:00.073  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:58:00.077  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:59:00.065  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-12 11:59:00.065  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-12 11:59:00.065  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-12 11:59:00.066  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
