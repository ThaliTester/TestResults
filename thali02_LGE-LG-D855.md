#### Test 79763830e2067e4_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 14:17:06.057  1803  4640 I art     : Explicit concurrent mark sweep GC freed 24326(1591KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 1.254ms total 71.258ms
08-26 14:17:06.092  4584  6528 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 336 ms] updated apps [took 335 ms] 
08-26 14:17:06.092  6529  6529 D DocsApplication: Installing DEX configuration.
08-26 14:17:06.109  6529  6529 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 14:17:06.116  6529  6529 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{d8bb4f5 com.google.android.apps.docs}
08-26 14:17:06.134  6529  6529 D TAG     : onCreate()
08-26 14:17:06.157  6529  6529 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-26 14:17:07.098  1803  4714 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-26 14:17:07.185  6561  6561 D AndroidRuntime: 
08-26 14:17:07.185  6561  6561 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 14:17:07.188  6561  6561 D AndroidRuntime: CheckJNI is OFF
08-26 14:17:07.240  1803  4714 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 14:17:07.297  6561  6561 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 14:17:07.301  1035  1952 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 14:17:07.318  1953  2558 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 14:17:07.322  1035  1952 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 14:17:07.323  1035  1952 D ActivityManager: setTaskToReturnTo : TaskRecord{207b368 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 14:17:07.323  1035  1952 D ActivityManager: setTaskToReturnTo : TaskRecord{207b368 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 14:17:07.325  1035  1952 D WindowStateEx: AppWindowTokenEx init.. 
08-26 14:17:07.325   345   375 E GBMv2   : DFP En is all cleared set to be enabled
08-26 14:17:07.357  1035  1952 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6586 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 14:17:07.358  6561  6561 D AndroidRuntime: Shutting down VM
08-26 14:17:07.364  6529  6529 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:07.364  6529  6529 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 14:17:07.405  1803  4714 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-26 14:17:07.427  1953  1970 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 14:17:07.427  1953  1970 D SplitWindowPolicy: topRunningActivity=ActivityInfo{360fab81 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 14:17:07.428  1953  1968 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 14:17:07.428  1953  1968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{31b38426 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 14:17:07.481  6586  6586 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 14:17:07.552  6586  6586 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-26 14:17:07.561  6586  6586 I LibraryLoader: Loading: webviewchromium
08-26 14:17:07.567  6586  6586 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 4132-4139)
08-26 14:17:07.568  6586  6586 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 14:17:07.571  6103  6103 I LockScreenSettings: New app installed broadcast received ..
08-26 14:17:07.577  6103  6103 I LockScreenSettings: Number of installed packages  1
08-26 14:17:07.580  6529  6529 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 14:17:07.591  6586  6586 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b0d61d7}
,08-26 14:17:07.593  6586  6586 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 14:17:07.593  6586  6586 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 14:17:07.604  6586  6586 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 14:17:07.605  6586  6586 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:17:07.613  1035  1583 V SIM_STK : Menu title from STK is T-Mobile
08-26 14:17:07.616   321  1381 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
,08-26 14:17:07.617  6586  6586 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 14:17:07.618  6586  6586 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 14:17:07.619  6586  6586 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 14:17:07.621  1035  1117 D BluetoothManagerService: Message: 20
08-26 14:17:07.621  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cccf55f:true
08-26 14:17:07.633  6586  6586 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 14:17:07.633  6586  6586 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 14:17:07.633  6586  6586 I Adreno-EGL: Build Date: 12/12/14 금
08-26 14:17:07.633  6586  6586 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 14:17:07.633  6586  6586 I Adreno-EGL: Remote Branch: 
08-26 14:17:07.633  6586  6586 I Adreno-EGL: Local Patches: 
08-26 14:17:07.633  6586  6586 I Adreno-EGL: Reconstruct Branch: 
,08-26 14:17:07.663  1035  1769 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6631 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 14:17:07.712  6586  6629 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 14:17:07.713  6586  6586 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 14:17:07.728  6586  6586 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:17:07.732  6586  6586 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 14:17:07.735  6586  6586 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 14:17:07.738  6586  6586 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 14:17:07.738  6586  6586 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 14:17:07.739  6631  6631 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 14:17:07.739  6631  6631 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-26 14:17:07.751  6586  6586 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-26 14:17:07.800  1035  1051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6654 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-26 14:17:07.802  1035  1051 I ActivityManager: Killing 5460:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-26 14:17:07.885  6586  6586 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:17:07.885  6586  6586 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:17:07.890  1035  2347 W libprocessgroup: failed to open /acct/uid_10005/pid_5460/cgroup.procs: No such file or directory
,08-26 14:17:07.925  6586  6675 D OpenGLRenderer: Render dirty regions requested: true
08-26 14:17:07.925  6586  6675 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 14:17:07.926  1035  1109 W ActivityManager: Activity pause timeout for ActivityRecord{20614381 u0 com.test.thalitest/.MainActivity t6}
08-26 14:17:07.932  6586  6675 D OpenGLRenderer: Enabling debug mode 0
,08-26 14:17:07.952  6586  6586 D Atlas   : Validating map...
,08-26 14:17:07.962  1035  2006 D SplitWindow: check instance of lgWin Window{3aa29661 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 14:17:07.990  6654  6654 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-26 14:17:08.006  6654  6654 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 14:17:08.006  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 14:17:08.031  6586  6673 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 14:17:08.031  6586  6673 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 14:17:08.041  1035  1952 I ActivityManager: Killing 5840:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 14:17:08.089  1035  2347 W libprocessgroup: failed to open /acct/uid_10072/pid_5840/cgroup.procs: No such file or directory
,08-26 14:17:08.109  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +683ms (total +783ms)
08-26 14:17:08.109  6586  6586 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@397b9e92 time:104682
08-26 14:17:08.110  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{20614381 u0 com.test.thalitest/.MainActivity t6} time:104682
,08-26 14:17:08.228  6586  6586 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 14:17:08.228  6586  6586 I chromium: 
,08-26 14:17:08.289  6586  6586 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 14:17:08.450  6586  6692 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-26 14:17:08.465  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 14:17:08.465  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 14:17:08.465  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 14:17:08.465  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 14:17:08.465  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 14:17:08.465  6586  6692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f277eb6 added. We now have 1 listener(s)
08-26 14:17:08.471  1035  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:08.474  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 14:17:08.478  6586  6692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-26 14:17:08.483  6586  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:08.483  6586  6692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 14:17:08.494  6586  6692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ddc668d added. We now have 1 listener(s)
08-26 14:17:08.494  6586  6692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:08.500  1035  1425 D WifiService: New client listening to asynchronous messages
08-26 14:17:08.504  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:08.504  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 14:17:08.506  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 14:17:08.507  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-26 14:17:08.507  6586  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 14:17:08.513  6586  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:08.514  1035  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 14:17:08.515  6586  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 14:17:08.524  6586  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 14:17:08.525  6586  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:08.525  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:08.525  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:08.525  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:08.525  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:08.525  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:08.525  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:08.525  6586  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:08.525  6586  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 14:17:08.525  6586  6692 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:08.530  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:08.532  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:08.533  6586  6692 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 14:17:08.576  6586  6673 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 14:17:08.576  6586  6673 I chromium: 
,08-26 14:17:08.641  6586  6586 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 14:17:09.189   345   377 E GBMv2   : DFP En is all cleared set to be enabled
08-26 14:17:09.189   345   377 E GBMv2   : Set value is all cleared set the max
08-26 14:17:09.189   345   377 I GBMv2   : DFP Enabled. Ignore VFP set
08-26 14:17:09.190  2773  2773 I MusicWidget: mDelayedStopHandler : unbind
,08-26 14:17:09.192  2210  2210 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 14:17:09.192  2210  2210 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 14:17:09.193  2210  2210 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-26 14:17:09.194  2210  2210 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 14:17:09.194  2210  2210 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 14:17:09.195  2210  2210 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-26 14:17:09.196  2210  2210 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 14:17:09.196  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-26 14:17:09.198  1035  1583 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@16ddfcf4com.lge.music.MediaPlaybackService$5@384f3c1d
08-26 14:17:09.199  2210  2210 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 14:17:09.199  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.200  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.201  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.202  2210  2210 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@32dc4473
08-26 14:17:09.202  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.203  2210  2210 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 14:17:09.203  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.204  2210  2210 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 14:17:09.204  2210  2210 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 14:17:09.205  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.206  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 14:17:09.209  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.209  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.210  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 14:17:09.212  2210  2210 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 14:17:09.216  2210  2210 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 14:17:09.216  2210  2210 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 14:17:09.216  2210  2210 V MediaPlayer[Native]: reset
08-26 14:17:09.225  2210  2210 V MediaPlayer[Native]: setListener
08-26 14:17:09.225  2210  2210 V MediaPlayer[Native]: disconnect
08-26 14:17:09.225  2210  2210 V MediaPlayer[Native]: destructor
08-26 14:17:09.226   321  1381 V AudioFlinger: releasing 16 from 2210 for -1
08-26 14:17:09.226   321  1381 V AudioFlinger:  decremented refcount to 0
08-26 14:17:09.226   321  1381 V AudioFlinger: purging stale effects
08-26 14:17:09.226  2210  2210 V MediaPlayer[Native]: disconnect
,08-26 14:17:09.227  2210  2210 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-26 14:17:09.233  2210  2210 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 14:17:09.233  2210  2210 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 14:17:09.240  2210  2210 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
,08-26 14:17:09.240  2210  2210 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 14:17:09.241  2210  2210 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 14:17:09.241  2210  2210 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 964402834
08-26 14:17:09.241  2210  2210 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 964402834
08-26 14:17:09.254  2210  2210 I SmartShareClient: [SmartShareManagerClient] terminate service: 2210/MediaPlaybackService/254782321
08-26 14:17:09.258  2210  2210 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
,08-26 14:17:09.258  2210  2210 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1adf3063
08-26 14:17:09.262  2210  2210 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 14:17:09.262  2210  2210 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 14:17:09.262  2210  2210 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 14:17:09.263  2210  2210 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 14:17:09.268  1035  1931 I ActivityManager: Killing 5635:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 14:17:09.278  2210  2210 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29985
08-26 14:17:09.285  5609  5609 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 14:17:09.285  5609  5609 W System.err: android.os.DeadObjectException
08-26 14:17:09.285  5609  5609 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 14:17:09.285  5609  5609 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 14:17:09.285  5609  5609 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 14:17:09.285  5609  5609 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 14:17:09.285  5609  5609 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 14:17:09.285  5609  5609 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 14:17:09.285  5609  5609 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:09.286  5609  5609 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:09.286  5609  5609 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:09.286  5609  5609 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:09.286  5609  5609 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:09.286  5609  5609 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:09.286  5609  5609 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:09.286  5609  5609 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:09.286  5609  5609 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 14:17:09.286  5609  5609 W System.err: android.os.DeadObjectException
08-26 14:17:09.286  5609  5609 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-26 14:17:09.286  5609  5609 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 14:17:09.286  5609  5609 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 14:17:09.287  5609  5609 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 14:17:09.287  5609  5609 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 14:17:09.287  5609  5609 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 14:17:09.287  5609  5609 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:09.287  5609  5609 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:09.287  5609  5609 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-26 14:17:09.287  5609  5609 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:09.287  5609  5609 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:09.287  5609  5609 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372),
08-26 14:17:09.287  5609  5609 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:09.287  5609  5609 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:09.287  5609  5609 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 14:17:09.287  5609  5609 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 14:17:09.349  6586  6695 W jxcore-log: Initializing JXcore engine
08-26 14:17:09.349  6586  6695 W jxcore-log: JXcore engine is ready
,08-26 14:17:09.425  6695  6695 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7909]" dev="sockfs" ino=7909 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 14:17:09.425  6695  6695 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 14:17:09.425  6695  6695 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8043]" dev="sockfs" ino=8043 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 14:17:09.425  6695  6695 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 14:17:09.425  6695  6695 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31061]" dev="sockfs" ino=31061 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-26 14:17:09.451  6586  6695 W jxcore-log: Starting JXcore engine
,08-26 14:17:09.518  1035  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_5635/cgroup.procs: No such file or directory
,08-26 14:17:09.519  1035  1050 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-26 14:17:09.523  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=751743850, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-26 14:17:09.523  5609  5609 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 14:17:09.523  5609  5609 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 14:17:09.579  1035  1952 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6700 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 14:17:09.580  5609  5609 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 14:17:09.596  2564  2564 D [Concierge]Service: onStartCommand(). Type : 9
,08-26 14:17:09.635  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=751743850 [*alarm*], flags=0x0
08-26 14:17:09.642  4475  6713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 14:17:09.670  6700  6700 D UEI.SmartControl: Quickset Services start...
08-26 14:17:09.672  6700  6700 I UEI.SmartControl: Manufacture = LGE
,08-26 14:17:09.673  6700  6700 D UEI.SmartControl: Id = LGNevo
08-26 14:17:09.674  6700  6700 D UEI.SmartControl: File observer start...
08-26 14:17:09.675  6700  6700 E UEI.SmartControl: IR Port is disabled: false
08-26 14:17:09.675  6700  6700 D UEI.SmartControl: Starting file observer...
08-26 14:17:09.675  6700  6700 D UEI.SmartControl: Extracting JNI libs...
08-26 14:17:09.675  6700  6700 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 14:17:09.682  6586  6695 W jxcore-log: Platform android
08-26 14:17:09.682  6586  6695 W jxcore-log: 
08-26 14:17:09.682  6586  6695 W jxcore-log: Process ARCH arm
08-26 14:17:09.682  6586  6695 W jxcore-log: 
08-26 14:17:09.739  6700  6700 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 14:17:09.739  6700  6700 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 14:17:09.739  6700  6700 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 14:17:09.761  6700  6700 I UEI.SmartControl: --- Selecting new region: 6
08-26 14:17:09.761  1035  1109 W ProcessCpuTracker: Skipping unknown process pid 6729
,08-26 14:17:09.762  6700  6700 I UEI.SmartControl: Model = LG-D855
08-26 14:17:09.763  6700  6700 D UEI.SmartControl: QS Service created
08-26 14:17:09.772  6700  6700 I UEI.SmartControl: Service initServices...
08-26 14:17:09.774  6700  6700 D UEI.SmartControl: QS start get config
,08-26 14:17:09.800  6700  6700 D UEI.SmartControl: Loading JNI Libs...
,08-26 14:17:09.916  6586  6695 I jxcore-log: JXcore Cordova bridge is ready!
08-26 14:17:09.916  6586  6695 I jxcore-log: 
,08-26 14:17:09.917  6586  6695 W jxcore-log: JXcore engine is started
,08-26 14:17:09.930  6586  6692 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 14:17:09.939  6586  6586 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 14:17:10.021  6700  6700 I UEI.SmartControl: Supports setup maps: true
,08-26 14:17:10.024  6700  6700 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 14:17:10.024  6700  6700 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 14:17:10.024  6700  6700 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 14:17:10.024  6700  6700 I UEI.SmartControl: ### init IR Blaster...
08-26 14:17:10.029  6700  6700 D serial_port: Configuring serial port
08-26 14:17:10.032  6700  6700 E UEI.SmartControl: UEIBLaster setting for 616
08-26 14:17:10.033  6700  6700 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 14:17:10.033  6700  6700 I UEI.SmartControl: configuring settings for MAXQ616
08-26 14:17:10.033  6700  6700 I UEI.SmartControl: Get version...
08-26 14:17:10.049  6700  6734 D UEI.SmartControl: serial port data available: 21
,08-26 14:17:10.081  6700  6700 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 14:17:10.082  6700  6700 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 14:17:10.082  6700  6700 I UEI.SmartControl: QS saving settings...
,08-26 14:17:10.084  6700  6700 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 14:17:10.100  6700  6734 D UEI.SmartControl: serial port data available: 4
,08-26 14:17:10.134  6700  6740 I UEI.SmartControl: Device manager: loading config....
,08-26 14:17:10.137  6700  6700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 14:17:10.138  6700  6740 D UEI.SmartControl: ----------- loading internal config...
08-26 14:17:10.147  6700  6700 E UEI.SmartControl: Services init done
08-26 14:17:10.147  6700  6700 D UEI.SmartControl: QS Service init finished
,08-26 14:17:10.150  6700  6700 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 14:17:10.150  6700  6700 D UEI.SmartControl: QS Service version code: 201091
08-26 14:17:10.155  6700  6700 D UEI.SmartControl: Service requested: Control
08-26 14:17:10.168  6700  6740 E UEI.SmartControl: Loading SETTINGS...
08-26 14:17:10.171  6700  6700 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 14:17:10.174  1035  1934 I ActivityManager: Killing 5609:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 14:17:10.180  6700  6740 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 14:17:10.198  6700  6739 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 14:17:10.198  6700  6739 D UEI.SmartControl: -----service ready thread exits
,08-26 14:17:10.273  1035  2006 W libprocessgroup: failed to open /acct/uid_10112/pid_5609/cgroup.procs: No such file or directory
,08-26 14:17:10.275  6700  6700 D UEI.SmartControl: Internal service binding...
08-26 14:17:11.590  6529  6529 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 14:17:11.635  1035  2051 I ActivityManager: Killing 6223:com.android.calendar/u0a13 (adj 15): empty #17
,08-26 14:17:11.790  1035  1769 W libprocessgroup: failed to open /acct/uid_10013/pid_6223/cgroup.procs: No such file or directory
,08-26 14:17:12.482  6529  6605 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 14:17:15.136  6700  6741 D UEI.SmartControl: Internal timer expired: 1
,08-26 14:17:15.136  6700  6741 D UEI.SmartControl: unbind internal service
,08-26 14:17:15.152  6700  6700 D UEI.SmartControl: Service.onUnbind: IControl
,08-26 14:17:15.156  6700  6700 D UEI.SmartControl: Service.onDestroy
,08-26 14:17:15.157  6700  6700 D UEI.SmartControl: Lock is in USE false
08-26 14:17:15.157  6700  6700 D UEI.SmartControl: unbind internal service
08-26 14:17:15.160  6700  6700 D serial_port: close(fd = 25)
08-26 14:17:15.164  6700  6700 I UEI.SmartControl: Serial port is closed.
,08-26 14:17:15.169  6700  6700 I UEI.SmartControl: Serial port is closed.
,08-26 14:17:15.169  6700  6700 D UEI.SmartControl: Blaster closed
08-26 14:17:15.169  6700  6700 D UEI.SmartControl: Shut down QS...
08-26 14:17:15.169  6700  6700 D UEI.SmartControl: Stopping QS lib
08-26 14:17:15.169  6700  6700 D UEI.SmartControl: QS lib stop result = true
08-26 14:17:15.169  6700  6700 D UEI.SmartControl: Stopped QS lib
08-26 14:17:15.170  6700  6700 D UEI.SmartControl: Stopped file observer...
08-26 14:17:15.170  6700  6700 D UEI.SmartControl: QS shutdown complete
,08-26 14:17:19.284  2210  2210 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,08-26 14:17:20.175  1035  1109 I ActivityManager: Waited long enough for: ServiceRecord{359cf725 u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 14:17:20.471  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 14:17:20.471  6586  6695 I jxcore-log: 
,08-26 14:17:20.474  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 14:17:20.474  6586  6695 I jxcore-log: 
,08-26 14:17:20.480  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:20.480  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:20.480  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:20.480  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:20.480  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:20.480  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:20.480  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:20.480  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:20.482  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:20.484  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 14:17:20.484  6586  6695 I jxcore-log: 
08-26 14:17:20.485  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 14:17:20.485  6586  6695 I jxcore-log: 
08-26 14:17:20.996  6586  6695 D executeNativeTests: Running unit tests
,08-26 14:17:21.077  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:21.077  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 added. We now have 2 listener(s)
,08-26 14:17:21.082  1035  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 14:17:21.083  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:21.084  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:21.084  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:21.084  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.084  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 added. We now have 2 listener(s)
,08-26 14:17:21.084  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 14:17:21.084  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-26 14:17:21.087  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.090  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
,08-26 14:17:21.090  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.090  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.090  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-26 14:17:21.090  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-26 14:17:21.090  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.090  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.090  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:21.091  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-26 14:17:21.091  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:21.094  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 14:17:21.096  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:21.096  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:21.099  6586  6695 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 14:17:21.100  6586  6695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 14:17:21.100  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-26 14:17:21.100  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:21.100  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:21.101  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.101  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:21.101  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.101  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.101  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.102  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.102  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:21.102  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 removed from the list
08-26 14:17:21.102  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.102  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 removed from the list
08-26 14:17:21.105  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.107  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.108  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.108  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.109  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.109  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.109  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.110  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.110  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.110  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.111  6586  6695 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 14:17:21.112  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.112  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.112  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.112  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.112  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.112  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.112  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.112  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.112  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.112  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.112  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.112  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.112  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.112  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.113  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.113  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.113  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.113  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 14,:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 14:17:21.117  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 14:17:21.118  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 14:17:21.118  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 14:17:21.118  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 14:17:21.118  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 14:17:21.118  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 14:17:21.118  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 14:17:21.118  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 14:17:21.118  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.118  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.118  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.119  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.119  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.119  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.119  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.119  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.119  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.119  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.119  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.119  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.119  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.119  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.120  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.120  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.120  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.120  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.120  6586  6695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 14:17:21.122  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.123  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.123  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.123  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.123  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.123  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.123  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.123  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.123  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:21.124  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.124  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:21.125  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:21.125  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:21.125  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:21.125  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.125  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:21.127  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.128  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.129  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:21.130  1035  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:21.133  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:21.137  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 14:17:21.139  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 14:17:21.140  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:21.140  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.141  6586  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 14:17:21.141  6586  6695 I io.jxcore.node.ConnectionHelper: start: OK
08-26 14:17:21.143  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.143  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.143  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.143  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.143  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.143  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.144  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.144  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.144  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.144  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.144  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.144  6586  6695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 14:17:21.145  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.147  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.147  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.147  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.147  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.147  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.147  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.147  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.147  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:21.148  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.148  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:21.150  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.151  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.151  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:21.151  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:21.151  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:21.151  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.151  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:21.154  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:21.154  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.155  6586  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 14:17:21.155  6586  6695 I io.jxcore.node.ConnectionHelper: start: OK
08-26 14:17:21.156  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.156  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.156  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.156  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.156  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.156  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.157  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.157  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.157  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.157  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.157  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.157  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.157  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.158  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.158  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.159  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.159  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.159  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.159  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.159  6586  6695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 14:17:21.161  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.163  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.163  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.163  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.163  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.163  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.163  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.163  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.163  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:21.164  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.164  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:21.165  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:21.165  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:21.165  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:21.165  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.165  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:21.165  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.168  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.169  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:21.169  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.170  6586  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 14:17:21.170  6586  6695 I io.jxcore.node.ConnectionHelper: start: OK
08-26 14:17:21.170  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.170  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.170  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.171  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.171  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.171  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.171  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.171  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.171  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.172  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.172  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.172  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.172  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.172  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.172  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.172  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.173  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.173  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.173  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.173  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.173  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.173  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.174  6586  6695 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 14:17:21.174  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.174  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.175  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.175  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.175  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.175  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.175  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.175  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.175  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.175  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.175  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.175  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.175  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.175  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.176  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.176  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.176  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.176  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.176  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.176  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.177  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 14:17:21.177  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.177  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.177  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.178  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.178  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.178  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.178  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.178  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.178  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.178  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.178  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.178  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.178  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.178  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.179  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.179  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.180  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.180  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.180  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.180  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.180  6586  6695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 14:17:21.181  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.181  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.181  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.181  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.181  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.181  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.181  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.181  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.181  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.181  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.181  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.181  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.181  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.181  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.182  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.182  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.182  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.182  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.182  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.182  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.183  6586  6695 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 14:17:21.183  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.183  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.183  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.183  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.183  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.183  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.183  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.183  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.183  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.183  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.183  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.183  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.183  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.183  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.184  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.184  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.184  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.184  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.184  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.184  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.185  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:21.188  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:21.188  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:21.188  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:21.188  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:21.188  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:21.188  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.188  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.188  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.188  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.188  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.188  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.188  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.188  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.188  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.188  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.188  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.188  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.188  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.188  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.189  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.189  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.190  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.190  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.190  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.190  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.190  6586  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.191  6586  6695 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 14:17:21.191  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 14:17:21.192  6586  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.193  6586  6695 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 14:17:21.194  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 14:17:21.195  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 14:17:21.195  6586  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 14:17:21.195  6586  6695 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:21.195  6586  6695 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 14:17:21.195  6586  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.195  6586  6695 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:21.195  6586  6695 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 14:17:21.195  6586  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.195  6586  6695 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:21.195  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 14:17:21.199  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 14:17:21.201  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 14:17:21.201  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 14:17:21.202  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 14:17:21.202  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 14:17:21.202  6586  6695 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 14:17:21.203  6586  6695 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.203  6586  6695 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 14:17:21.203  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.203  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.203  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.203  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.203  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.203  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.203  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 14:17:21.204  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.204  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.204  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.204  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.204  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.204  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.204  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.204  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.205  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.205  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.205  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.205  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.205  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.205  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.205  6586  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-26 14:17:21.206  6586  6695 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 14:17:21.206  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.206  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.206  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.206  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.206  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.206  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.206  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.206  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.206  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.206  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.207  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.207  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.207  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.207  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.207  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.207  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.208  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.208  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.208  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.208  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.210  6586  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 14:17:21.210  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.210  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.210  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.210  6586  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-26 14:17:21.211  6586  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-26 14:17:21.212  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.212  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.212  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.212  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.212  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.212  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.212  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.212  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.212  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.212  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.212  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.214  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.214  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.214  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.214  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.214  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.214  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.215  6586  6695 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 14:17:21.215  6586  6695 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 14:17:21.215  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:21.215  6586  6695 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 14:17:21.215  6586  6695 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 14:17:21.215  6586  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 14:17:21.215  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:21.215  6586  6695 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 14:17:21.215  6586  6695 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 14:17:21.215  6586  6695 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 14:17:21.215  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:21.215  6586  6695 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 14:17:21.215  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.215  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.215  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.216  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21,.216  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.216  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.216  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.216  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.216  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.216  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.216  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.216  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.216  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.216  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.217  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.217  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.218  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.218  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.218  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.218  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.218  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.218  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.218  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.218  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.218  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.218  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.218  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.218  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.218  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.218  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.218  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.219  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.219  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.219  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.219  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.219  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.219  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.219  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.219  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.219  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.219  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.219  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.219  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.219  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.219  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.219  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.219  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.219  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.219  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.220  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.220  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.221  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.221  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.221  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.221  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.222  6586  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 14:17:21.222  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.222  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 14:17:21.223  6586  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 14:17:21.223  6586  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 14:17:21.224  6586  6586 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 14:17:21.225  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 14:17:21.225  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:21.226  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.226  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 14:17:21.226  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 14:17:21.226  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 14:17:21.226  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.226  6586  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 14:17:21.227  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:21.228  6586  6806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:21.229  3877  3898 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-26 14:17:21.229  6586  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 14:17:21.229  6586  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 14:17:21.229  6586  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 14:17:21.230  6586  6586 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 14:17:21.230  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.230  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.230  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:21.230  6586  6695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:21.230  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:21.231  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:21.231  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:21.231  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.231  6586  6695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:21.231  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.232  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.233  6586  6695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:21.233  6586  6586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:21.233  6586  6586 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 14:17:21.233  6586  6586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:21.233  6586  6586 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:21.233  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.233  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.233  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.233  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.233  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.233  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.234  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.234  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.234  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.234  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.234  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.234  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.234  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.234  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.234  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.234  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.234  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.234  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.234  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.235  6586  6695 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 14:17:21.236  6586  6695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 14:17:21.236  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:21.238  6586  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:21.238  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.238  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.239  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.239  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.239  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.239  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.239  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.239  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.239  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.239  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.239  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.239  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.239  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.239  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.240  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.240  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.240  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.240  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.241  1035  1583 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:21.241  1035  1770 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:21.242  1035  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:21.242  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.242  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.242  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.243  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.243  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.243  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.243  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.243  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.243  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.243  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.243  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.243  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.243  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.243  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.243  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.243  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.244  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.244  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.244  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.244  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.244  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.245  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.245  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.245  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.245  6586  6695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc3c06 not in the list
08-26 14:17:21.245  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.245  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.245  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.245  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.245  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.245  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.245  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.245  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.245  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.245  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.245  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30e392c7 not in the list
08-26 14:17:21.246  6586  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 14:17:21.246  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:21.247  6586  6695 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 14:17:21.247  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:21.247  6586  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 14:17:21.247  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:21.248  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 14:17:21.248  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 14:17:21.249  6586  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 14:17:21.249  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 14:17:21.249  6586  6695 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 14:17:21.249  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 14:17:21.249  6586  6695 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 14:17:21.249  6586  6695 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 14:17:21.250  6586  6695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 14:17:21.250  6586  6695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 14:17:21.250  6586  6695 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 14:17:21.250  6586  6695 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 14:17:21.250  6586  6695 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 14:17:21.250  6586  6695 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 14:17:21.251  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.251  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fd8ca8c added. We now have 2 listener(s)
08-26 14:17:21.251  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:21.253  6586  6695 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 14:17:21.254  1035  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6586, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 14:17:21.254  1035  1050 D WifiService: setWifiEnabled: true pid=6586, uid=10118
08-26 14:17:21.254  1035  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 14:17:21.255  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.255  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@314d15d5 added. We now have 3 listener(s)
08-26 14:17:21.255  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:21.258  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.258  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@323761ea added. We now have 4 listener(s)
08-26 14:17:21.258  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:21.260  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.260  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26662cdb added. We now have 5 listener(s)
08-26 14:17:21.260  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:21.261  1035  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6586, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 14:17:21.261  1035  1051 D WifiService: setWifiEnabled: false pid=6586, uid=10118
08-26 14:17:21.261  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 14:17:21.272  1035  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:21.272  1035  2006 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@23eb8a35 mBinding = false
08-26 14:17:21.273  1035  1374 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-26 14:17:21.274  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:21.275  1035  1374 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:21.275  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 14:17:21.276  1035  1374 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:21.276  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 14:17:21.276  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 14:17:21.276  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:21.276  1035  1374 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 14:17:21.276  1035  1374 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 14:17:21.276  1035  1374 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 14:17:21.277  1035  1374 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 14:17:21.277  1035  1374 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 14:17:21.280  1035  1117 D BluetoothManagerService: Message: 2
08-26 14:17:21.281  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 14:17:21.281  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 14:17:21.281  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 14:17:21.281  1035  1117 D BluetoothManagerService: Sending off request.
08-26 14:17:21.282  1035  1374 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 14:17:21.282  3877  3970 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 14:17:21.282  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.282  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.282  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 14:17:21.282  3877  3949 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 14:17:21.282  3877  3949 D BluetoothAdapterProperties: Setting state to 13
08-26 14:17:21.282  3877  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 14:17:21.282  2727  2727 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 14:17:21.283  3877  3949 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 14:17:21.283  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 14:17:21.283  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 14:17:21.283  3877  3949 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 14:17:21.283  1035  1374 D WifiNative-wlan0: SET ps 1: returned true
08-26 14:17:21.283  1035  2849 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:21.286  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.286  3877  3954 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:21.287  3877  3949 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 14:17:21.288  3877  4220 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 14:17:21.288  3877  4220 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:21.288  3877  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 14:17:21.288  3877  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 14:17:21.288  3877  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 14:17:21.288  3877  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 14:17:21.288  3877  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 14:17:21.288  3877  4220 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 14:17:21.288  3877  3949 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 14:17:21.288  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 14:17:21.288  3877  4224 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:21.288  3877  4038 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 14:17:21.289   317   904 D CommandListener: Clearing all IP addresses on wlan0
08-26 14:17:21.294  3877  4279 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:21.294  3877  4282 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:21.294  3877  4277 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 14:17:21.295  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 14:17:21.295  3877  4038 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 14:17:21.302  1035  1117 D BluetoothManagerService: Message: 60
08-26 14:17:21.302  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 14:17:21.302  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 14:17:21.303  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.303  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.303  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.303  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.303  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.303  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:21.303  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.303  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.303  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:21.303  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.303  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.303  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:21.304  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.305  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.307  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.307  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:21.307  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.307  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.307  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.307  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:21.307  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14,:17:21.307  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.307  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:21.307  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.307  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.308  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.326  1035  1109 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6814 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:21.337  1035  1429 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 14:17:21.338  1035  1429 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-26 14:17:21.399  1035  1429 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 14:17:21.399  1035  1429 D DSQN    : disableDataServiceNotify
08-26 14:17:21.399  1035  1429 D DSQN    : stop dsqn bin
,08-26 14:17:21.407  1035  1429 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 14:17:21.407  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:21.407  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:21.408  1035  1429 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:21.408  1035  1429 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 14:17:21.408  1035  2847 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.408  1035  2847 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.408  1035  2847 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 14:17:21.409  1035  1429 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 14:17:21.409  1035  1429 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 14:17:21.409  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 14:17:21.410  1586  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 14:17:21.449  1035  1362 I art     : Explicit concurrent mark sweep GC freed 27835(1471KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.135ms total 119.499ms
,08-26 14:17:21.452  1035  1362 V AlarmManager: RTC_WAKEUP set : Alarm{2dfe6d96 type 0 when 1472213840729 com.android.vending} when 1472213840729
08-26 14:17:21.455  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.458  3877  3877 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.458  3877  3877 D BluetoothMapService: STATE_TURNING_OFF
08-26 14:17:21.458  3877  3877 V BluetoothMapService: Handler(): got msg=4
08-26 14:17:21.458  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 14:17:21.458  3877  3877 D BluetoothMapService: MAP Service closeService in
08-26 14:17:21.458  3877  3877 D BluetoothMapMasInstance: MAP Service shutdown
08-26 14:17:21.459  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 14:17:21.459  3877  3877 V BluetoothMapService: MAP Service closeService out
08-26 14:17:21.460  3877  3877 V BtOppService: Receiver DISABLED_ACTION 
08-26 14:17:21.460  3877  3877 I BtOppRfcommListener: stopping Accept Thread
08-26 14:17:21.460  3877  3877 V BtOppRfcommListener: close mBtServerSocket
08-26 14:17:21.461  3877  3877 V BtOppRfcommListener: waiting for thread to terminate
08-26 14:17:21.461  3877  4277 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 14:17:21.462  3877  3877 V BtOppRfcommListener: done waiting for thread to terminate
08-26 14:17:21.509  1035  2849 D DhcpStateMachine: StoppedState
,08-26 14:17:21.517  1035  1109 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6837 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 14:17:21.522  1035  1429 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:21.522  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 14:17:21.522  1035  1429 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:21.523  1035  1429 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:21.523  1035  1429 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:21.523  1035  1429 D NetworkManagementService: Removing idletimer
08-26 14:17:21.523  1035  1429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:21.523  1861  1861 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:21.523  1861  1861 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 14:17:21.524  1035  1429 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 14:17:21.525  3877  3877 V BtOppService: onDestroy
08-26 14:17:21.526  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 14:17:21.527  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.527  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:21.527  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.527  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.527  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.527  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:21.527  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:21.527  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:21.527  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:21.528  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.528  1953  1953 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 14:17:21.528  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:21.528  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:21.528  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:21.528  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 14:17:21.528  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 14:17:21.528  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 14:17:21.529  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: D,ISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 14:17:21.529  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 14:17:21.530  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.530  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:21.530  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.530  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.530  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.530  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:21.530  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:21.530  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:21.530  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:21.531  1035  1372 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 14:17:21.531  1035  1372 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 14:17:21.531  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 14:17:21.531  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 14:17:21.531  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 14:17:21.531  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 14:17:21.531  1035  2051 V SIM_STK : Menu title from STK is T-Mobile
,08-26 14:17:21.539  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.539  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:21.540  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:21.540  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:21.542  3877  3877 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 14:17:21.543  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:21.543  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.543  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.543  1035  1373 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3699e4d
08-26 14:17:21.543  1035  1374 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.544  1035  1373 D LGWifiP2pService: P2pDisablingState
08-26 14:17:21.544  1035  1373 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.544  1035  1373 D LGWifiP2pService: p2p socket connection lost
08-26 14:17:21.544  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.544  1035  1373 D LGWifiP2pService: P2pDisabledState
08-26 14:17:21.544  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.544  1035  1374 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 14:17:21.545  1035  1374 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.545  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.546  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.547  1035  1374 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.548  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 14:17:21.549  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:21.549  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:21.549  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 14:17:21.549  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 14:17:21.549  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-26 14:17:21.550  1035  1539 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.550  1035  1540 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.551  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.551  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 14:17:21.551  1953  1953 D WfdsService: WifiP2pState is changed : false
08-26 14:17:21.551  1953  2310 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 14:17:21.551  1953  2310 D WfdsService: Set the WFDS Monitor: false
08-26 14:17:21.551  1035  1374 E WifiStateMachine:  D,efaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:21.552  1035  1374 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:21.552  1035  1374 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:21.552  1953  2310 D WfdsMonitor: WFDS Monitor is stopped
08-26 14:17:21.552  1953  2310 D WfdsService: STATE : WfdsDisabledState - enter
08-26 14:17:21.552  1953  2755 D CtrlSupplicant: Received on exit socket, terminate
08-26 14:17:21.552  1035  1374 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 14:17:21.552  1953  2755 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 14:17:21.552  1953  2755 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 14:17:21.552  1953  2755 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 14:17:21.552  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 14:17:21.552  2727  2727 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 14:17:21.553  1953  2312 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 14:17:21.553  1953  2310 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 14:17:21.553  1035  1373 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.553  1035  1373 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.553  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 14:17:21.553  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 14:17:21.554  1035  1374 D WifiNative-wlan0: SET ps 1: returned true
08-26 14:17:21.554  1035  2849 D DhcpStateMachine: StoppedState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:21.554   317   904 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:21.563  1035  1374 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 14:17:21.565  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 14:17:21.566  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:21.566  1035  1374 D WifiNative-p2p0: TERMINATE: returned true
08-26 14:17:21.566  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:21.566  1035  1374 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 14:17:21.566  1035  1374 E WifiStateMachine: useWiFiOffloading() : false
08-26 14:17:21.566  1035  1374 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 14:17:21.566  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 14:17:21.567  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-26 14:17:21.569  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.569  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:21.569  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.569  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.569  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:21.569  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:21.569  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:21.569  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:21.569  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:21.570  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:21.570  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:21.575  1035  1374 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 14:17:21.575  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.575  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:21.575  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.575  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:21.575  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:21.575  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:21.575  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:21.575  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:21.575  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:21.575  1035  1374 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 14:17:21.575  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 14:17:21.576  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:21.576  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 14:17:21.576  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.576  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:21.589  6837  6837 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:21.589  6837  6837 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-26 14:17:21.589  6837  6837 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 14:17:21.590  6837  6837 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 14:17:21.591  6837  6837 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 14:17:21.591  6837  6837 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 14:17:21.592  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 14:17:21.593  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:21.594  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 14:17:21.620  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 14:17:21.621  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:21.621  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:21.625  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:21.625  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:21.626  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:21.638  6814  6814 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 14:17:21.638  6814  6814 W LG Account v2.2: No ProfileInfo entries
,08-26 14:17:21.638  6814  6814 I LG Account v2.2: isEnabled: false
08-26 14:17:21.638  6814  6814 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 14:17:21.638  6814  6814 I Feature : [Lifetracker]Country: EU
08-26 14:17:21.638  6814  6814 I Feature : [Lifetracker]Operator: OPEN
08-26 14:17:21.638  6814  6814 I Feature : [Lifetracker]Ranking support: false
08-26 14:17:21.639  6814  6814 I Feature : [Lifetracker]Comfort support: false
08-26 14:17:21.639  6814  6814 I Feature : [Lifetracker]Accessory: true
08-26 14:17:21.639  6814  6814 I Feature : [Lifetracker]Health device: true
08-26 14:17:21.639  6814  6814 I Feature : [Lifetracker]Extra Pedometer: false
08-26 14:17:21.639  6814  6814 I Feature : [Lifetracker]Blood glucose device: false
08-26 14:17:21.639  6814  6814 I Feature : [Lifetracker]Device Number: 3
08-26 14:17:21.644  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:21.653  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 14:17:21.653  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 14:17:21.657  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:21.658  2727  2727 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 14:17:21.659  2727  2727 I wpa_supplicant: monitor socket send errors count : 1
08-26 14:17:21.659  2727  2727 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1953-2\x00 that cannot receive messages
08-26 14:17:21.659  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:21.660  1035  2753 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 14:17:21.660  1035  2753 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 14:17:21.680  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 14:17:21.689  1035  1988 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6856 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 14:17:21.693  3877  3877 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 14:17:21.693  3877  3877 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.693  3877  3877 V BluetoothPbapReceiver: ***********state = 13
,08-26 14:17:21.694  3877  3877 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 14:17:21.695  3877  3877 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.695  3877  3877 V BluetoothPbapService: state: 13
08-26 14:17:21.695  3877  3877 V BluetoothPbapService: Pbap Service closeService in
08-26 14:17:21.696  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:21.698  2727  2727 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 14:17:21.699  2727  2727 W wpa_supplicant: USIM:  scard_deinit function
08-26 14:17:21.699  1035  2753 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 14:17:21.699  1035  2753 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 14:17:21.699  1035  2753 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 14:17:21.699  3877  3877 V BluetoothPbapService: successfully stopped pbap service
08-26 14:17:21.699  1035  2753 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 14:17:21.699  3877  3877 V BluetoothPbapService: Pbap Service closeService out
08-26 14:17:21.699  1035  2753 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:21.699  3877  3877 V BluetoothPbapService: Pbap Service onDestroy
08-26 14:17:21.699  1035  1117 D BluetoothManagerService: Message: 20
08-26 14:17:21.699  1035  2753 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:21.699  3877  3877 V BluetoothPbapService: Pbap Service closeService in
08-26 14:17:21.699  3877  3877 V BluetoothPbapService: Pbap Service closeService out
08-26 14:17:21.699  3877  3877 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 14:17:21.699  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@69fcaed:true
08-26 14:17:21.700  1035  1374 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118257
08-26 14:17:21.700  1035  1374 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118258
08-26 14:17:21.701  1035  1117 D Tethering: InitialState.processMessage what=4
08-26 14:17:21.702  1035  1374 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118260  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 14:17:21.702  1035  1374 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118260  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 14:17:21.703  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:21.704  1035  1374 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:21.704  1035  1374 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-26 14:17:21.715  1035  1117 D BluetoothManagerService: Message: 30
08-26 14:17:21.718  1035  1117 D BluetoothManagerService: Message: 30
,08-26 14:17:21.720  6837  6837 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 14:17:21.721  6837  6837 D BluetoothMap: Create BluetoothMap proxy object
08-26 14:17:21.722  1035  1117 D BluetoothManagerService: Message: 30
08-26 14:17:21.725  1035  1117 D BluetoothManagerService: Message: 30
08-26 14:17:21.726  6837  6837 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 14:17:21.727  6837  6837 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-26 14:17:21.734  6586  6586 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 14:17:21.737  6837  6837 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-26 14:17:21.740  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 14:17:21.746  6837  6837 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:21.755  6837  6837 D BluetoothInputDevice: Proxy object connected
08-26 14:17:21.756  6837  6837 D HidProfile: Bluetooth service connected
08-26 14:17:21.757  6837  6837 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 14:17:21.757  6837  6837 D PanProfile: Bluetooth service connected
,08-26 14:17:21.758  6837  6837 D BluetoothMap: Proxy object connected
08-26 14:17:21.758  6837  6837 D MapProfile: Bluetooth service connected
08-26 14:17:21.758  6837  6837 D BluetoothMap: getConnectedDevices()
08-26 14:17:21.759  6837  6837 D BluetoothMap: Bluetooth is Not enabled
08-26 14:17:21.759  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 14:17:21.760  6837  6837 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 14:17:21.763  6837  6837 D BluetoothPermissionRequest: onReceive
08-26 14:17:21.765  6837  6837 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 14:17:21.766  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 14:17:21.768  2727  2727 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 14:17:21.769  1035  2753 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 14:17:21.769  1035  2753 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 14:17:21.769  1035  2753 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-26 14:17:21.771  1035  1374 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 14:17:21.772  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 14:17:21.773  1035  2056 I ActivityManager: Killing 6186:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-26 14:17:21.777  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 14:17:21.778  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:21.783  6065  6065 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 14:17:21.799  3877  3877 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 14:17:21.799  3877  3877 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 14:17:21.799  1035  1931 W libprocessgroup: failed to open /acct/uid_10014/pid_6186/cgroup.procs: No such file or directory
08-26 14:17:21.800  3877  3877 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-26 14:17:21.803  1035  2056 I ActivityManager: Killing 6296:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 14:17:21.812  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:21.855  6837  6837 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:21.856  6837  6837 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 14:17:21.867  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:21.872  1035  1050 W libprocessgroup: failed to open /acct/uid_10004/pid_6296/cgroup.procs: No such file or directory
,08-26 14:17:21.876  3877  3877 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.877  1035  1374 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 14:17:21.877  1035  1374 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 14:17:21.877  1035  1374 E WifiStateMachine: useWiFiOffloading() : false
08-26 14:17:21.877  1035  1374 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 14:17:21.877  3877  3877 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 14:17:21.879  1953  1953 D WfdsService: Supplicant Connection state is changed : false
08-26 14:17:21.879  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 14:17:21.881  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:21.882  1953  2310 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 14:17:21.882  1953  2310 D WfdsService: Set the WFDS Monitor: false
08-26 14:17:21.882  1953  2310 D WfdsMonitor: WFDS Monitor is stopped
08-26 14:17:21.884  2468  2468 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:21.886  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.888  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.964  1035  1988 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6885 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 14:17:21.966  3877  3877 V BluetoothFtpService: Ftp Service onStartCommand
08-26 14:17:21.966  3877  3877 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.967  1035  1988 I ActivityManager: Killing 6439:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-26 14:17:21.968  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 14:17:21.967  3877  3877 V BluetoothFtpService: Ftp Service closeService
08-26 14:17:21.968  3877  3877 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 14:17:21.968  1035  1386 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 14:17:21.969  1035  1386 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 14:17:21.987   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 24.484ms
,08-26 14:17:22.007   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 17.390ms
,08-26 14:17:22.024   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 341us total 16.082ms
,08-26 14:17:22.111  3877  3877 V BluetoothFtpService: successfully stopped ftp service
08-26 14:17:22.111  1035  1934 W libprocessgroup: failed to open /acct/uid_10008/pid_6439/cgroup.procs: No such file or directory
08-26 14:17:22.112  3877  3877 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 14:17:22.112  3877  3877 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 14:17:22.112  3877  3877 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 14:17:22.113  3877  3877 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:22.113  3877  3877 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 14:17:22.113  3877  3877 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-26 14:17:22.120  3877  3877 V BluetoothFtpService: Ftp Service onDestroy
08-26 14:17:22.120  3877  3877 V BluetoothFtpService: Ftp Service closeService
,08-26 14:17:22.156  6885  6885 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 14:17:22.179  1035  2030 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6902 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 14:17:22.179  3877  3877 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:22.179  3877  3877 V BluetoothSapService: state: 13
08-26 14:17:22.180  3877  3877 V BluetoothSapService: Stopping SAP server process
,08-26 14:17:22.181  3877  3877 V BluetoothSapService: Sap Service closeSapService in
08-26 14:17:22.182  3877  3877 V BluetoothSapService: Close listen Socket : 
08-26 14:17:22.182  3877  3877 V BluetoothSapService: Close rfcomm Socket : 
08-26 14:17:22.182  3877  3877 V BluetoothSapService: Close sapd  Socket : 
08-26 14:17:22.183  3877  3877 V BluetoothSapService: Sap Service closeSapService out
08-26 14:17:22.183  3877  3877 V BluetoothSapService: Sap Service onDestroy
08-26 14:17:22.183  3877  3877 V BluetoothSapService: Sap Service closeSapService in
08-26 14:17:22.183  3877  3877 V BluetoothSapService: Close listen Socket : 
08-26 14:17:22.183  3877  3877 V BluetoothSapService: Close rfcomm Socket : 
08-26 14:17:22.183  3877  3877 V BluetoothSapService: Close sapd  Socket : 
08-26 14:17:22.184  3877  3877 V BluetoothSapService: Sap Service closeSapService out
08-26 14:17:22.197  6885  6885 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 14:17:22.234  6885  6885 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 14:17:22.235  6885  6885 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 14:17:22.235  6885  6885 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-26 14:17:22.236  6885  6885 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 14:17:22.236  6885  6885 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 14:17:22.239  6885  6885 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 14:17:22.249  6885  6885 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 14:17:22.264  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 14:17:22.265  6902  6902 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 14:17:22.270  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:22.280  1035  2030 I ActivityManager: Killing 5995:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 14:17:22.298  3877  3954 D bt_hci_bdroid: cleanup
08-26 14:17:22.298  3877  4038 W bt-btif : ag scb idx 1 not allocated
08-26 14:17:22.298  3877  4038 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:22.298  3877  4040 I bt_lpm  : LPM is already off!!!
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:22.298  3877  4212 I bt_userial_mct: exiting userial_read_thread
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:22.298  3877  4212 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:22.298  3877  3954 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:22.298  3877  4040 I bt_vendor: hw_epilog_process
08-26 14:17:22.298  3877  4038 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:22.298  3877  4038 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 14:17:22.299  3877  3954 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 14:17:22.299  3877  3954 D bt_userial_mct: userial_close
08-26 14:17:22.299  3877  3954 E bt_userial_mct: pthread_join() FAILED result:3
,08-26 14:17:22.299  3877  3954 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 14:17:22.371  1035  1934 W libprocessgroup: failed to open /acct/uid_10011/pid_5995/cgroup.procs: No such file or directory
08-26 14:17:22.372  6885  6885 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 14:17:22.380  6885  6885 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-26 14:17:22.388  6885  6885 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-26 14:17:22.391  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:22.404  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 14:17:22.404  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 14:17:22.404  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:22.410  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:22.416  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:22.425  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:22.426  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 14:17:22.429  6885  6885 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:22.430  3877  3954 D bt_hci_bdroid: set_power 0
08-26 14:17:22.430  3877  3954 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 14:17:22.430  3877  3954 I bt_vendor: bluetooth satus is on
08-26 14:17:22.430  3877  3954 I bt_vendor: bt-vendor : resetting BT status
08-26 14:17:22.430  3877  3954 I bt_vendor: Starting hciattach daemon
08-26 14:17:22.430  3877  3954 I bt_vendor: try to set false
08-26 14:17:22.431  3877  3954 I bt_vendor: Starting hciattach daemon
08-26 14:17:22.431  3877  3954 I bt_vendor: try to set false
08-26 14:17:22.432  3877  3954 I bt_vendor: cleanup
08-26 14:17:22.433  3877  4038 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 14:17:22.433  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:22.434  3877  3954 I GKI_LINUX: GKI_exit_task 0 done
08-26 14:17:22.434  3877  3954 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 14:17:22.436  3877  3949 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 14:17:22.440  3877  3877 D HeadsetService: Received stop request...Stopping profile...
,08-26 14:17:22.441  3877  3877 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 14:17:22.441  3877  3877 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:22.441  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bcc5ac4
08-26 14:17:22.441  3877  3969 D HeadsetStateMachine: Exit Disconnected: -1
08-26 14:17:22.443  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 14:17:22.443  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 14:17:22.443  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:22.445  1861  1861 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:22.445  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:22.445  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 14:17:22.445  1861  1861 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:22.445  1861  1861 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:22.446  3877  3877 D A2dpService: Received stop request...Stopping profile...
08-26 14:17:22.447  3877  4002 D A2dpStateMachine: Exit Disconnected: -1
08-26 14:17:22.447  3877  3877 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 14:17:22.450  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:22.452  3877  3877 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 14:17:22.452  3877  3877 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:22.452  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bcc5ac4
08-26 14:17:22.453  3877  3949 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-26 14:17:22.457  3877  3877 D HidService: Received stop request...Stopping profile...
08-26 14:17:22.457  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bcc5ac4
08-26 14:17:22.458  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:22.458  3877  3877 D HeadsetStateMachine: Unbinding service...
08-26 14:17:22.458  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 14:17:22.459  3877  3877 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 14:17:22.459  3877  3877 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 14:17:22.459  3877  3877 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 14:17:22.459  3877  3877 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 14:17:22.460  3877  3877 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 14:17:22.460  3877  3877 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:22.460  3877  3877 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 14:17:22.460  3877  3877 D HealthService: Received stop request...Stopping profile...
08-26 14:17:22.460  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bcc5ac4
08-26 14:17:22.461  3877  3877 D PanService: Received stop request...Stopping profile...
08-26 14:17:22.462  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bcc5ac4
08-26 14:17:22.463  3877  3877 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 14:17:22.463  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:22.463  3877  3877 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 14:17:22.463  3877  3877 D BtGatt.GattService: stop()
08-26 14:17:22.463  6837  6837 D BluetoothInputDevice: Proxy object disconnected
08-26 14:17:22.463  3877  3877 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 14:17:22.463  6837  6837 D HidProfile: Bluetooth service disconnected
08-26 14:17:22.464  6837  6837 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 14:17:22.464  6837  6837 D PanProfile: Bluetooth service disconnected
08-26 14:17:22.466  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bcc5ac4
,08-26 14:17:22.467  3877  3877 D BluetoothMapService: Received stop request...Stopping profile...
08-26 14:17:22.467  3877  3877 D BluetoothMapService: stop()
08-26 14:17:22.468  3877  3877 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 14:17:22.468  3877  3877 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 14:17:22.469  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bcc5ac4
08-26 14:17:22.470  3877  3877 I BluetoothA2dpServiceJni: cleanupNative
08-26 14:17:22.470  3877  4003 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 14:17:22.470  3877  3877 I GKI_LINUX: GKI_exit_task 2 done
08-26 14:17:22.471  3877  3877 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 14:17:22.471  3877  3877 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 14:17:22.471  3877  3877 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 14:17:22.471  3877  3877 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 14:17:22.471  3877  3877 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 14:17:22.471  3877  3877 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 14:17:22.472  3877  3877 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 14:17:22.472  3877  3877 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 14:17:22.473  3877  3877 V BluetoothMapService: Handler(): got msg=4
08-26 14:17:22.473  3877  3877 D BluetoothMapService: MAP Service closeService in
08-26 14:17:22.473  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 14:17:22.473  3877  3877 V BluetoothMapService: MAP Service closeService out
08-26 14:17:22.473  3877  3877 D BluetoothMapService: cleanup()
08-26 14:17:22.473  3877  3877 D BluetoothMapService: MAP Service closeService in
08-26 14:17:22.473  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 14:17:22.473  3877  3877 V BluetoothMapService: MAP Service closeService out
08-26 14:17:22.473  3877  3949 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 14:17:22.473  3877  3949 D BluetoothAdapterProperties: Setting state to 10
08-26 14:17:22.473  3877  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 14:17:22.474  1035  1117 D BluetoothManagerService: Message: 60
08-26 14:17:22.474  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 14:17:22.474  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 14:17:22.474  1861  1876 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:22.474  3877  3949 I BluetoothAdapterState: Entering OffState
08-26 14:17:22.477  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:22.477  6837  6852 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 14:17:22.479  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:22.479  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:22.480  1861  1877 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:22.481  6837  6853 D BluetoothPan: onBluetoothStateChange on: false
08-26 14:17:22.481  6885  6885 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:22.481  6837  6852 D BluetoothMap: onBluetoothStateChange: up=false
08-26 14:17:22.481  6837  6837 D BluetoothMap: Proxy object disconnected
08-26 14:17:22.482  6837  6837 D MapProfile: Bluetooth service disconnected
08-26 14:17:22.482  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:22.542  1035  2347 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6927 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 14:17:22.542  1861  2443 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 14:17:22.547  6837  6853 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 14:17:22.549  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 14:17:22.549  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 14:17:22.555  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 14:17:22.555  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 14:17:22.556  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@23eb8a35 mBinding = false
,08-26 14:17:22.557  1035  1117 D BluetoothManagerService: Sending unbind request.
08-26 14:17:22.559  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 14:17:22.561  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:22.561  1953  2141 D LGBluetoothAPIService: Message: 2
08-26 14:17:22.561  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 14:17:22.562  1953  2141 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@37170867 mBinding = false
08-26 14:17:22.562  1953  2141 D LGBluetoothAPIService: Sending unbind request.
08-26 14:17:22.569  3877  3954 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 14:17:22.569  3877  3877 I GKI_LINUX: GKI_exit_task 1 done
08-26 14:17:22.569  3877  3877 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 14:17:22.570  3877  3877 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 14:17:22.570  3877  3877 I art     : --- WEIRD: removing null entry 246
08-26 14:17:22.570  3877  3877 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 14:17:22.570  3877  3877 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 14:17:22.573  6837  6837 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 14:17:22.574  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 14:17:22.574  6837  6837 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 14:17:22.576  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.577  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.577  3877  3877 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 14:17:22.578  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 14:17:22.580  3877  3877 I art     : System.exit called, status: 0
08-26 14:17:22.580  3877  3877 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 14:17:22.587  1586  1586 D BluetoothAdapter: 955810222: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:22.587  1586  1586 D BluetoothAdapter: 955810222: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:22.593  6837  6837 D DockEventReceiver: finishStartingService: stopping service
08-26 14:17:22.603   321   321 V AudioFlinger: 3877 died, releasing its sessions
08-26 14:17:22.603   321   321 V AudioFlinger:  pid 1861 @ 0
08-26 14:17:22.603   321   321 V AudioFlinger:  pid 3459 @ 1
08-26 14:17:22.603   321   321 V AudioFlinger:  pid 3459 @ 2
,08-26 14:17:22.603  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 14:17:22.627  1035  2051 I ActivityManager: Process com.android.bluetooth (pid 3877) has died
08-26 14:17:22.628  1035  2051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-26 14:17:22.637  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:22.650  6837  6837 D BluetoothPermissionRequest: onReceive
,08-26 14:17:22.654  6837  6837 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 14:17:22.655  6837  6837 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 14:17:22.658  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 14:17:22.713  1035  2051 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6946 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 14:17:22.727  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:22.732  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:22.737  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 14:17:22.756  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:22.756  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 14:17:22.756  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 14:17:22.756  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 14:17:22.762  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 14:17:22.775  6946  6946 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 14:17:22.775  6946  6946 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 14:17:22.776  6946  6946 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 14:17:22.776  6946  6946 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 14:17:22.777  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 14:17:22.777  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 14:17:22.778  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 14:17:22.778  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 14:17:22.778  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-26 14:17:22.778  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 14:17:22.779  6927  6965 W FormManager: Network not available. Please check & try again.
08-26 14:17:22.785  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 14:17:22.786  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 14:17:22.788  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:22.790  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:22.796  6927  6966 V FormManager: Network unavailable.
,08-26 14:17:22.797  6946  6946 D BluetoothAdapterApp: Loading JNI Library
08-26 14:17:22.798  4285  6969 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 14:17:22.801  6927  6966 V FormManager: Network unavailable.
08-26 14:17:22.805  4285  6970 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 14:17:22.805  4285  6970 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 14:17:22.812  6856  6856 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 14:17:22.812  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 14:17:22.812  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:22.817  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:22.824  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 14:17:22.834  6946  6946 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d8bb4f5 Instance Count = 1
08-26 14:17:22.842  6946  6946 D BluetoothAdapterApp: onCreate
,08-26 14:17:22.843  6885  6885 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 14:17:22.844  6927  6976 W FormManager: Network not available. Please check & try again.
08-26 14:17:22.844  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 14:17:22.845  6885  6885 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 14:17:22.845  6927  6977 V FormManager: Network unavailable.
08-26 14:17:22.847  6927  6977 V FormManager: Network unavailable.
08-26 14:17:22.852  1035  1934 I ActivityManager: Killing 6018:com.android.contacts/u0a19 (adj 15): empty #17
08-26 14:17:22.864  6946  6946 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-26 14:17:22.864  6946  6946 D ProfileConfigQcom: Adding HeadsetService
08-26 14:17:22.864  6946  6946 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 14:17:22.865  6946  6946 D ProfileConfigQcom: Adding A2dpService
08-26 14:17:22.865  6946  6946 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 14:17:22.865  6946  6946 D ProfileConfigQcom: Adding HidService
08-26 14:17:22.865  6946  6946 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 14:17:22.865  6946  6946 D ProfileConfigQcom: Adding HealthService
08-26 14:17:22.866  6946  6946 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 14:17:22.867  6946  6946 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 14:17:22.867  6946  6946 D ProfileConfigQcom: Adding PanService
08-26 14:17:22.867  6946  6946 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 14:17:22.867  6946  6946 D ProfileConfigQcom: Adding GattService
08-26 14:17:22.868  6946  6946 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 14:17:22.868  6946  6946 D ProfileConfigQcom: Adding BluetoothMapService
08-26 14:17:22.868  6946  6946 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 14:17:22.870  6946  6946 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 14:17:22.882  6885  6885 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 14:17:22.882  6885  6885 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 14:17:22.889  6885  6885 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 14:17:22.890  6885  6885 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 14:17:22.890  6885  6885 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-26 14:17:22.890  6885  6885 V SoundPool: doLoad: loading sample sampleID=1
08-26 14:17:22.891  6885  6885 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 14:17:22.891  6885  6982 V SoundPool: Start decode
08-26 14:17:22.892  6885  6982 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-26 14:17:22.892   321  1381 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 14:17:22.892   321  1381 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 14:17:22.892   321  1381 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 14:17:22.892   321  1381 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 14:17:22.892   321  1381 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 14:17:22.892   321  1381 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 14:17:22.892   321  1381 V MediaPlayerService: player type = 3
08-26 14:17:22.892   321  1381 V AwesomePlayer: AwesomePlayer create()
08-26 14:17:22.893   321  1381 V AwesomePlayer: reset_l() 
08-26 14:17:22.893   321  1381 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:22.893   321  1381 V AwesomePlayer: setAudioSink() 
08-26 14:17:22.893   321  1381 V AwesomePlayer: reset_l() 
08-26 14:17:22.893   321  1381 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-26 14:17:22.893   321  1381 V AudioCache: ignored
08-26 14:17:22.893   321  1381 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:22.893   321  1381 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 14:17:22.893   321  1381 V AwesomePlayer: setDataSource_l dataSource
08-26 14:17:22.893   321  1381 V LGParserOSAL: SniffLGParser start
08-26 14:17:22.893   321  1381 V LGParserOSAL: MainType:5, SubType=0
08-26 14:17:22.893   321  1381 V LGParserOSAL: #### check Mime : application/ogg
08-26 14:17:22.893   321  1381 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 14:17:22.893   321  1381 E MediaExtractor: Use LGExtractor :application/ogg 
,08-26 14:17:22.922  1035  2006 W libprocessgroup: failed to open /acct/uid_10019/pid_6018/cgroup.procs: No such file or directory
,08-26 14:17:22.923  6700  6700 D UEI.SmartControl: QS Service created
08-26 14:17:22.929  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 14:17:22.934  6946  6946 V LGMDMManagerInternal: Create singleton instance
08-26 14:17:22.937  6885  6885 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 14:17:22.940   321  1381 V LGParserOSAL: supported mime: application/ogg
08-26 14:17:22.940   321  1381 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 14:17:22.940   321  1381 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 14:17:22.940   321  1381 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 14:17:22.940   321  1381 V AwesomePlayer: AudioTrack Setting
08-26 14:17:22.940   321  1381 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 14:17:22.940   321  1381 V AwesomePlayer: setAudioSource() 
08-26 14:17:22.940   321  1381 V MediaPlayerService: prepare
08-26 14:17:22.940   321  1381 V AwesomePlayer: prepareAsync_l() 
,08-26 14:17:22.940   321  1381 V MediaPlayerService: wait for prepare
08-26 14:17:22.941   321  6983 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 14:17:22.941   321  6983 V AwesomePlayer: initAudioDecoder() 
08-26 14:17:22.941   321  6983 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 14:17:22.941   321  6983 V AudioSystem: isOffloadSupported()
08-26 14:17:22.941   321  6983 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 14:17:22.941   321  6983 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 14:17:22.941   321  6983 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 14:17:22.941   321  6983 V AwesomePlayer: getUseOffload() = 0 
08-26 14:17:22.941   321  6983 V OMXCodec: OMXCodec::Create
08-26 14:17:22.941   321  6983 V OMXCodec: findMatchingCodecs()
08-26 14:17:22.941   321  6983 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 14:17:22.941   321  6983 V OMXCodec: matchingCodecs.size()=1
08-26 14:17:22.941   321  6983 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 14:17:22.943   321  6983 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 14:17:22.943   321  6983 V LGCodecAdapter: LG Codec Adapter start
08-26 14:17:22.943   321  6983 V OMXCodec: OMXCodec Createtor
08-26 14:17:22.944   321  6983 V OMXCodec: setComponentRole
08-26 14:17:22.944   321  6983 V OMXCodec: configureCodec protected=0
08-26 14:17:22.944   321  6983 V LGCodecAdapter: called getLGCodecSpecificData
08-26 14:17:22.944   321  6983 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
,08-26 14:17:22.944   321  6983 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 14:17:22.944   321  6983 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 14:17:22.944   321  6983 V LGCodecOSAL: Not support LGCodec
08-26 14:17:22.944   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 14:17:22.944   321  6983 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 14:17:22.944   321  6983 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 14:17:22.944   321  6983 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 14:17:22.944   321  6983 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 14:17:22.944   321  6983 V AudioSystem: isOffloadSupported()
08-26 14:17:22.944   321  6983 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,08-26 14:17:22.944   321  6983 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 14:17:22.944   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 14:17:22.944   321  6983 V OMXCodec: init()
08-26 14:17:22.944   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 14:17:22.944   321  6983 V OMXCodec: allocateBuffers
08-26 14:17:22.944   321  6983 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 14:17:22.944   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
,08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-26 14:17:22.945   321  6983 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-26 14:17:22.945   321  6983 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
,08-26 14:17:22.945   321  6983 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 14:17:22.945   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 14:17:22.945   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 14:17:22.946  6885  6885 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 14:17:22.946   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 14:17:22.946   321  6983 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 14:17:22.946  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 14:17:22.947   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 14:17:22.947   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 14:17:22.947   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 14:17:22.947   321  6983 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 14:17:22.947   321  6983 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 14:17:22.948   321  6983 V AudioCache: notify(0xb5474a80, 5, 0, 0)
08-26 14:17:22.948   321  6983 V AudioCache: ignored
08-26 14:17:22.948   321  6983 V AudioCache: notify(0xb5474a80, 1, 0, 0)
08-26 14:17:22.948   321  6983 V AudioCache: prepared
08-26 14:17:22.948   321  1381 V AudioCache: wait - success
08-26 14:17:22.948   321  1381 V MediaPlayerService: start
08-26 14:17:22.948   321  1381 V AwesomePlayer: play_l() 
08-26 14:17:22.948   321  1381 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 14:17:22.948   321  1381 V AwesomePlayer: createAudioPlayer_l
08-26 14:17:22.948   321  1381 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 14:17:22.948   321  1381 V AwesomePlayer: startAudioPlayer_l() 
08-26 14:17:22.948   321  1381 D AudioPlayer: start of Playback, useOffload 0
08-26 14:17:22.948   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 14:17:22.948   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 14:17:22.956   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 14:17:22.957   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 14:17:22.957   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 14:17:22.957   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 14:17:22.957   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 14:17:22.957   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 14:17:22.957   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
08-26 14:17:22.957   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1,
,08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 14:17:22.958   321  6985 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-26 14:17:22.958   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc90 on output port
08-26 14:17:22.959  6885  6885 V LGMDMManager: Create singleton instance
08-26 14:17:22.962   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 14:17:22.962   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 14:17:22.963   321  1381 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 14:17:22.963   321  1381 V AudioCache: notify(0xb5474a80, 6, 0, 0)
08-26 14:17:22.963   321  1381 V AudioCache: ignored
08-26 14:17:22.964   321  1381 V MediaPlayerService: wait for playback complete
08-26 14:17:22.964   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.964   321  6986 V AudioCache: memcpy(0xaf006000, 0xb57c6000, 4096)
08-26 14:17:22.966   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.966   321  6986 V AudioCache: memcpy(0xaf007000, 0xb57c6000, 4096)
08-26 14:17:22.967   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.967   321  6986 V AudioCache: memcpy(0xaf008000, 0xb57c6000, 4096)
08-26 14:17:22.968   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.968   321  6986 V AudioCache: memcpy(0xaf009000, 0xb57c6000, 4096)
08-26 14:17:22.968   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.968   321  6986 V AudioCache: memcpy(0xaf00a000, 0xb57c6000, 4096)
08-26 14:17:22.969   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.969   321  6986 V AudioCache: memcpy(0xaf00b000, 0xb57c6000, 4096)
08-26 14:17:22.969   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.969   321  6986 V AudioCache: memcpy(0xaf00c000, 0xb57c6000, 4096)
08-26 14:17:22.970   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.970   321  6986 V AudioCache: memcpy(0xaf00d000, 0xb57c6000, 4096)
08-26 14:17:22.973   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.973   321  6986 V AudioCache: memcpy(0xaf00e000, 0xb57c6000, 4096)
08-26 14:17:22.973  6700  6700 I UEI.SmartControl: Service initServices...
08-26 14:17:22.974   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.974   321  6986 V AudioCache: memcpy(0xaf00f000, 0xb57c6000, 4096)
08-26 14:17:22.974  6700  6700 D UEI.SmartControl: QS start get config
08-26 14:17:22.975   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.975   321  6986 V AudioCache: memcpy(0xaf010000, 0xb57c6000, 4096)
08-26 14:17:22.976   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.976   321  6986 V AudioCache: memcpy(0xaf011000, 0xb57c6000, 4096)
08-26 14:17:22.976   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.976   321  6986 V AudioCache: memcpy(0xaf012000, 0xb57c6000, 4096)
08-26 14:17:22.977   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.977   321  6986 V AudioCache: memcpy(0xaf013000, 0xb57c6000, 4096)
08-26 14:17:22.978   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.978   321  6986 V AudioCache: memcpy(0xaf014000, 0xb57c6000, 4096)
08-26 14:17:22.979   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.979   321  6986 V AudioCache: memcpy(0xaf015000, 0xb57c6000, 4096)
08-26 14:17:22.980   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.980   321  6986 V AudioCache: memcpy(0xaf016000, 0xb57c6000, 4096)
08-26 14:17:22.980   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.980   321  6986 V AudioCache: memcpy(0xaf017000, 0xb57c6000, 4096)
08-26 14:17:22.981   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.981   321  6986 V AudioCache: memcpy(0xaf018000, 0xb57c6000, 4096)
08-26 14:17:22.981   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.981   321  6986 V AudioCache: memcpy(0xaf019000, 0xb57c6000, 4096)
08-26 14:17:22.982   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.982   321  6986 V AudioCache: memcpy(0xaf01a000, 0xb57c6000, 4096)
08-26 14:17:22.982   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.982   321  6986 V AudioCache: memcpy(0xaf01b000, 0xb57c6000, 4096)
08-26 14:17:22.984   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.984   321  6986 V AudioCache: memcpy(0xaf01c000, 0xb57c6000, 4096)
08-26 14:17:22.985   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.985   321  6986 V AudioCache: memcpy(0xaf01d000, 0xb57c6000, 4096)
08-26 14:17:22.985   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.985   321  6986 V AudioCache: memcpy(0xaf01e000, 0xb57c6000, 4096)
08-26 14:17:22.986   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.986   321  6986 V AudioCache: memcpy(0xaf01f000, 0xb57c6000, 4096)
08-26 14:17:22.987   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.987   321  6986 V AudioCache: memcpy(0xaf020000, 0xb57c6000, 4096)
08-26 14:17:22.987   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.988   321  6986 V AudioCache: memcpy(0xaf021000, 0xb57c6000, 4096)
08-26 14:17:22.988   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.988   321  6986 V AudioCache: memcpy(0xaf022000, 0xb57c6000, 4096)
,08-26 14:17:22.989   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.989   321  6986 V AudioCache: memcpy(0xaf023000, 0xb57c6000, 4096)
08-26 14:17:22.990   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.990   321  6986 V AudioCache: memcpy(0xaf024000, 0xb57c6000, 4096)
08-26 14:17:22.990   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.990   321  6986 V AudioCache: memcpy(0xaf025000, 0xb57c6000, 4096)
08-26 14:17:22.991   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.991   321  6986 V AudioCache: memcpy(0xaf026000, 0xb57c6000, 4096)
08-26 14:17:22.991   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.992   321  6986 V AudioCache: memcpy(0xaf027000, 0xb57c6000, 4096)
08-26 14:17:22.992   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.992   321  6986 V AudioCache: memcpy(0xaf028000, 0xb57c6000, 4096)
08-26 14:17:22.993   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.993   321  6986 V AudioCache: memcpy(0xaf029000, 0xb57c6000, 4096)
08-26 14:17:22.993   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.993   321  6986 V AudioCache: memcpy(0xaf02a000, 0xb57c6000, 4096)
08-26 14:17:22.994   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.994   321  6986 V AudioCache: memcpy(0xaf02b000, 0xb57c6000, 4096)
08-26 14:17:22.996   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.996   321  6986 V AudioCache: memcpy(0xaf02c000, 0xb57c6000, 4096)
08-26 14:17:22.997   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.997   321  6986 V AudioCache: memcpy(0xaf02d000, 0xb57c6000, 4096)
08-26 14:17:22.997   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.997   321  6986 V AudioCache: memcpy(0xaf02e000, 0xb57c6000, 4096)
08-26 14:17:22.998   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.998   321  6986 V AudioCache: memcpy(0xaf02f000, 0xb57c6000, 4096)
08-26 14:17:22.999   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.999   321  6986 V AudioCache: memcpy(0xaf030000, 0xb57c6000, 4096)
08-26 14:17:22.999   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:22.999   321  6986 V AudioCache: memcpy(0xaf031000, 0xb57c6000, 4096)
08-26 14:17:23.000   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:23.000   321  6986 V AudioCache: memcpy(0xaf032000, 0xb57c6000, 4096)
08-26 14:17:23.001   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:23.001   321  6986 V AudioCache: memcpy(0xaf033000, 0xb57c6000, 4096)
08-26 14:17:23.001   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:23.001   321  6986 V AudioCache: memcpy(0xaf034000, 0xb57c6000, 4096)
08-26 14:17:23.002   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:23.002   321  6986 V AudioCache: memcpy(0xaf035000, 0xb57c6000, 4096)
08-26 14:17:23.002   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:23.002   321  6986 V AudioCache: memcpy(0xaf036000, 0xb57c6000, 4096)
08-26 14:17:23.003   321  6986 V AudioCache: write(0xb57c6000, 4096)
08-26 14:17:23.003   321  6986 V AudioCache: memcpy(0xaf037000, 0xb57c6000, 4096)
08-26 14:17:23.003   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 14:17:23.003   321  6986 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 14:17:23.003   321  6986 V AwesomePlayer: postAudioEOS() 
08-26 14:17:23.003   321  6986 V AudioCache: write(0xb57c6000, 280)
08-26 14:17:23.003   321  6986 V AudioCache: memcpy(0xaf038000, 0xb57c6000, 280)
08-26 14:17:23.007   321  6983 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 14:17:23.007   321  6983 V AwesomePlayer: onStreamDone
08-26 14:17:23.007   321  6983 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 14:17:23.007   321  6983 V AudioCache: notify(0xb5474a80, 2, 0, 0)
08-26 14:17:23.007   321  6983 V AudioCache: playback complete
08-26 14:17:23.007   321  6983 V AwesomePlayer: pause_l() 
08-26 14:1,7:23.007   321  6983 V AudioCache: notify(0xb5474a80, 7, 0, 0)
08-26 14:17:23.007   321  6983 V AudioCache: ignored
08-26 14:17:23.007   321  6983 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:23.007   321  1381 V AudioCache: wait - success
08-26 14:17:23.007   321  1381 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 14:17:23.008   321  6983 D AudioPlayer: Pause Playback at 1068125
08-26 14:17:23.008   321  1381 V AwesomePlayer: reset_l() 
08-26 14:17:23.008   321  1381 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-26 14:17:23.008   321  1381 V AudioCache: ignored
08-26 14:17:23.008   321  1381 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:23.008   321  1381 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 14:17:23.008   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 14:17:23.008   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 14:17:23.008   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 14:17:23.008   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-26 14:17:23.008   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fc90 on port 1
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:23.009   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 14:17:23.009   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 14:17:23.009   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 14:17:23.010   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 14:17:23.010   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 14:17:23.010   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 14:17:23.010   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 14:17:23.010   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 14:17:23.010   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 14:17:23.011   321  1381 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 14:17:23.011   321  1381 D AudioPlayer: AudioPlayer releasing audio source
08-26 14:17:23.011   321  1381 D AudioPlayer: AudioPlayer done releasing audio source
08-26 14:17:23.011   321  1381 V AwesomePlayer: reset_l() 
08-26 14:17:23.011   321  1381 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:23.011   321  1381 V AwesomePlayer: ~AwesomePlayer call
08-26 14:17:23.012   321  1381 V AwesomePlayer: reset_l() 
08-26 14:17:23.012   321  1381 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:23.012  6885  6982 V SoundPool: close(32)
08-26 14:17:23.012  6885  6982 V SoundPool: pointer = 0xa0009000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 14:17:23.030  6946  6946 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:23.033  6946  6946 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 14:17:23.033  6946  6946 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 14:17:23.033  6946  6946 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 14:17:23.034  6946  6946 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:23.034  6946  6946 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 14:17:23.041  6902  6902 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 14:17:23.046  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 14:17:23.047  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-26 14:17:23.049  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8265
08-26 14:17:23.252  6700  6700 I UEI.SmartControl: Supports setup maps: true
,08-26 14:17:23.255  6700  6700 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 14:17:23.255  6700  6700 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 14:17:23.255  6700  6700 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 14:17:23.255  6700  6700 I UEI.SmartControl: ### init IR Blaster...
08-26 14:17:23.258  6700  6700 D serial_port: Configuring serial port
08-26 14:17:23.258  6700  6700 E UEI.SmartControl: UEIBLaster setting for 616
08-26 14:17:23.258  6700  6700 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 14:17:23.258  6700  6700 I UEI.SmartControl: configuring settings for MAXQ616
08-26 14:17:23.258  6700  6700 I UEI.SmartControl: Get version...
08-26 14:17:23.277  6700  6990 D UEI.SmartControl: serial port data available: 21
,08-26 14:17:23.303  6700  6700 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 14:17:23.304  6700  6700 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-26 14:17:23.304  6700  6700 I UEI.SmartControl: QS saving settings...,
,08-26 14:17:23.306  6700  6700 D UEI.SmartControl: IR Blaster version: 25672567,
,08-26 14:17:23.325  6700  6990 D UEI.SmartControl: serial port data available: 4
,08-26 14:17:23.355  6700  6996 I UEI.SmartControl: Device manager: loading config....
,08-26 14:17:23.358  6700  6996 D UEI.SmartControl: ----------- loading internal config...
08-26 14:17:23.358  6700  6700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 14:17:23.361  6700  6700 E UEI.SmartControl: Services init done
08-26 14:17:23.361  6700  6700 D UEI.SmartControl: QS Service init finished
08-26 14:17:23.362  6700  6700 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 14:17:23.363  6700  6700 D UEI.SmartControl: QS Service version code: 201091
08-26 14:17:23.364  6700  6700 D UEI.SmartControl: Service requested: Control
08-26 14:17:23.365  6700  6996 E UEI.SmartControl: Loading SETTINGS...
08-26 14:17:23.370  6700  6700 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 14:17:23.373  6885  6885 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 14:17:23.376  6700  6722 I UEI.SmartControl: ------ IControl API: 11
08-26 14:17:23.377  6700  6722 D UEI.SmartControl: File observer start...
08-26 14:17:23.377  6700  6700 D UEI.SmartControl: Internal service binding...
08-26 14:17:23.378  6700  6722 E UEI.SmartControl: IR Port is disabled: false
08-26 14:17:23.378  6700  6722 D UEI.SmartControl: Starting file observer...
08-26 14:17:23.380  6700  6722 I UEI.SmartControl: Registering callback...
08-26 14:17:23.381  6700  6723 I UEI.SmartControl: ------ IControl API: 19
08-26 14:17:23.382  6700  6996 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 14:17:23.382  6700  6723 I UEI.SmartControl: Registering Services Ready callback...
,08-26 14:17:23.397  6700  6995 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 14:17:23.397  6885  6901 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 14:17:23.398  6700  6995 D UEI.SmartControl: -----service ready thread exits
08-26 14:17:23.398  6885  6979 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 14:17:23.398  6885  6979 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 14:17:23.399  6885  6885 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 14:17:23.399  6885  6885 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 14:17:23.399  6700  6722 I UEI.SmartControl: ------ IControl API: 8
08-26 14:17:23.402  6885  6885 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 14:17:23.402  6885  6885 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 14:17:23.402  6885  6885 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 14:17:23.403  6885  6885 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 14:17:23.404  6885  6885 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 14:17:23.404  6885  6885 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 14:17:23.406  6885  6885 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 14:17:23.409  6885  6885 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 14:17:23.409  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 14:17:23.410  6885  6885 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 14:17:23.411  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 14:17:23.412  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 14:17:23.413  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-26 14:17:23.414  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 14:17:23.415  6885  6885 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472213843414]
08-26 14:17:23.417  6885  6885 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 14:17:23.423  1035  2030 I ActivityManager: Killing 6038:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-26 14:17:23.439  6885  6998 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 14:17:23.482  1035  2030 I ActivityManager: Killing 6481:com.lge.email/u0a23 (adj 15): empty #18
,08-26 14:17:23.514  1035  1050 W libprocessgroup: failed to open /acct/uid_10027/pid_6038/cgroup.procs: No such file or directory
,08-26 14:17:23.521  1035  2006 W libprocessgroup: failed to open /acct/uid_10023/pid_6481/cgroup.procs: No such file or directory
08-26 14:17:23.533  6885  6885 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-26 14:17:23.535  6885  6885 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 14:17:23.536  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 14:17:23.538  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 14:17:23.539  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 14:17:23.540  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 14:17:23.541  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 14:17:23.562  6885  6885 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 14:17:24.314  1035  1988 D WifiServiceImplEx: setWifiEnabled: true pid=6586, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 14:17:24.315  1035  1988 D WifiService: setWifiEnabled: true pid=6586, uid=10118
,08-26 14:17:24.315  1035  1988 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 14:17:24.349  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 14:17:24.349  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 14:17:24.349  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 14:17:24.351  1035  1374 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 14:17:24.351  1035  1374 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 14:17:24.353  1035  1374 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 14:17:24.353  1035  1374 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 14:17:24.354  1035  1374 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 14:17:24.354  1035  1374 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 14:17:24.354  1035  1374 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 14:17:24.354  1035  1374 E WifiHW  : unknown target_country: EU , set to default
08-26 14:17:24.354  1035  1374 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 14:17:24.354  1035  1374 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 14:17:24.354  1035  1374 I WifiUtil: gEnableBmps=1
08-26 14:17:24.526  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:24.531  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:24.533  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-26 14:17:24.544  1035  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:24.550  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:24.551  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:24.552  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-26 14:17:24.560  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:24.564  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:24.569  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 14:17:24.572  6392  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 14:17:24.586  5752  5752 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 14:17:24.594  5752  5752 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 14:17:24.611  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:24.640  1035  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:24.688  1035  1934 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7006 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-26 14:17:24.694  1035  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 14:17:24.694  1035  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 14:17:24.766  7006  7006 I AppUp4:AppBoxCP: onCreate
08-26 14:17:24.767  7006  7006 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 14:17:24.777  7006  7006 I AppUp4:DB:  setFingerPrint start
08-26 14:17:24.778  7006  7006 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 14:17:24.787  7006  7006 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 14:17:24.787  7006  7006 I AppUp4:DB:  SDK version = 21
08-26 14:17:24.787  7006  7006 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-26 14:17:24.790  7006  7006 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-26 14:17:24.792  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 14:17:24.792  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:24.795  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 14:17:24.795  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 14:17:24.801  7006  7006 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 14:17:24.844  7006  7006 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:24.844  7006  7006 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 14:17:24.852  7006  7006 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1b0d61d7
08-26 14:17:24.852  7006  7006 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 14:17:24.853  7006  7006 D AppUp4:CustFacade: isPhone : true
08-26 14:17:24.853  7006  7006 D AppUp4:CustModeStarterReceiver: begin check event
08-26 14:17:24.854  7006  7006 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 14:17:24.855  7006  7006 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 14:17:24.857  7006  7046 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 14:17:24.857  7006  7046 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,08-26 14:17:24.858  7006  7046 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-26 14:17:24.860  1035  1051 I ActivityManager: Killing 6103:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 14:17:24.976  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:24.977  1035  1769 W libprocessgroup: failed to open /acct/uid_10080/pid_6103/cgroup.procs: No such file or directory
08-26 14:17:24.979  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 14:17:24.984  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 14:17:24.984  1035  1117 D Tethering: InitialState.processMessage what=4
08-26 14:17:24.987  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:24.990   317   904 D SoftapController: Softap fwReload - Ok
08-26 14:17:24.990  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:24.991  1035  1374 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (629ms)
08-26 14:17:24.996  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:24.997   317   904 D CommandListener: Setting iface cfg
,08-26 14:17:24.997   317   904 D CommandListener: Trying to bring down wlan0
08-26 14:17:24.998   317   904 D CommandListener: Clearing all IP addresses on wlan0
08-26 14:17:25.001  1035  1374 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 14:17:25.006  4285  7050 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 14:17:24.995  7051  7051 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:24.995  7051  7051 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:25.010  4285  7052 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:25.010  4285  7052 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 14:17:25.028  7051  7051 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 14:17:25.049  1035  2006 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7053 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 14:17:25.060  7051  7051 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 14:17:25.060  7051  7051 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 14:17:25.096  7053  7053 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:25.097  7053  7053 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 14:17:25.099  7053  7053 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 14:17:25.099  7053  7053 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 14:17:25.101  1035  1374 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 14:17:25.101  1035  1374 E WifiStateMachine: useWiFiOffloading() : false
08-26 14:17:25.101  1035  1374 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 14:17:25.102  1035  1374 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 14:17:25.102  1035  1374 D WifiMonitor: connecting to supplicant
08-26 14:17:25.102  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 14:17:25.103  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 14:17:25.104  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:25.104  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:25.105  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:25.136  7051  7051 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 14:17:25.165  7053  7053 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 14:17:25.175  7053  7053 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-26 14:17:25.203  7053  7053 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 14:17:25.205  7051  7051 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-26 14:17:25.220  7051  7051 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 14:17:25.220  7051  7051 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-26 14:17:25.221  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 14:17:25.221  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 14:17:25.222  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 14:17:25.222  1035  1374 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 14:17:25.222  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:25.223  1035  1374 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:25.223  1035  7071 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 14:17:25.223  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:25.223  1035  7071 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-26 14:17:25.223  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 14:17:25.224  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 14:17:25.224  1035  1374 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:25.224  1035  7071 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 14:17:25.224  1035  7071 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 14:17:25.224  1035  1374 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 14:17:25.224  1035  1374 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 14:17:25.224  7053  7053 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:25.225  7053  7053 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 14:17:25.225  1035  1374 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 14:17:25.225  1035  1374 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 14:17:25.225  1035  1374 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 14:17:25.226  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:25.226  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:25.226  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:25.226  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:25.226  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 14:17:25.226  1035  1374 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 14:17:25.226  1035  1374 E WifiStateMachine: useWiFiOffloading() : false
08-26 14:17:25.226  1035  1374 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 14:17:25.228  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 14:17:25.228  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:25.228  1953  1953 D WfdService: Waiting for WifiP2p enabling
08-26 14:17:25.228  1035  1386 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 14:17:25.228  1035  1374 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 14:17:25.229  1035  1374 D WifiNative-wlan0: SET update_config 1: returned true
08-26 14:17:25.229  1035  1374 D WifiConfigStore: Loading config and enabling all networks 
08-26 14:17:25.229  1035  1374 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 14:17:25.230  1035  1374 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 14:17:25.232  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:25.232  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:25.232  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:25.232  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:25.232  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:25.232  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:25.232  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:25.232  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:25.232  6586  6586 V io.jxcore,.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:25.233  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:25.233  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:25.235  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:25.235  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:25.235  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:25.235  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:25.235  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:25.235  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:25.235  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:25.235  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:25.235  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:25.235  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:25.235  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:25.236  1035  1374 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 14:17:25.244  1035  1374 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 14:17:25.244  1035  1374 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 14:17:25.245  1035  1374 D WifiStateMachine: enableVerboseLogging : level 2
,08-26 14:17:25.245  1035  1374 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 14:17:25.246  1035  1374 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 14:17:25.246  1035  1374 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 14:17:25.246  1035  1374 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 14:17:25.246  1035  1374 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 14:17:25.246  1035  1374 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 14:17:25.246  1035  1374 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 14:17:25.247  1035  1374 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 14:17:25.247  1035  1374 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 14:17:25.247  1035  1374 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 14:17:25.247  1035  1374 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-26 14:17:25.247  1035  1374 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 14:17:25.247  1035  1374 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 14:17:25.248  1035  1374 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 14:17:25.248  1035  1374 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 14:17:25.248  1035  1374 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 14:17:25.249  1953  1953 D WfdsService: Supplicant Connection state is changed : true
08-26 14:17:25.249  1035  1374 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 14:17:25.249  1035  1374 D WifiNative-HAL: Setting external_sim to 1
08-26 14:17:25.249  1035  1374 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 14:17:25.249  1953  2310 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 14:17:25.249  1953  2310 D WfdsService: Set the WFDS Monitor: true
08-26 14:17:25.249  1953  2310 D WfdsMonitor: WfdsMonitorThread create
08-26 14:17:25.249  1953  2310 D WfdsMonitor: WFDS Monitor is created and started
08-26 14:17:25.249  1953  2310 D WfdsService: WiFi: Supplicant connection re-established
08-26 14:17:25.249  1035  1374 D WifiNative-wlan0: SET external_sim 1: returned true
,08-26 14:17:25.249  1035  1374 I WifiNative-HAL: startHal
08-26 14:17:25.249  1035  1374 D wifi    : setting scan oui 0xaf6057c0
08-26 14:17:25.250  1953  7074 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 14:17:25.250  1035  1374 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 14:17:25.250  1035  1374 I WifiNative-HAL: startHal
08-26 14:17:25.250  1035  1374 D wifi    : setting scan oui 0xaf6057c0
08-26 14:17:25.250  1953  7074 E CtrlSupplicant: Succeed to open control connection
08-26 14:17:25.250  1035  1374 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 14:17:25.250  1953  7074 E CtrlSupplicant: Succeed to open monitor connection
08-26 14:17:25.250  1953  7074 D WfdsMonitor: Supplicant connection established
08-26 14:17:25.250  1953  2310 D WfdsService: Connected to the supplicant for wfds
08-26 14:17:25.250  1035  1374 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 14:17:25.250  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 14:17:25.250  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 14:17:25.251  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 14:17:25.251  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 14:17:25.251  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 14:17:25.251  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 14:17:25.251  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 14:17:25.251  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 14:17:25.252  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 14:17:25.252  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 14:17:25.252  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 14:17:25.252  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 14:17:25.252  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 14:17:25.252  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 14:17:25.252  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 14:17:25.252  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 14:17:25.252  7051  7051 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 14:17:25.253  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 14:17:25.253  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 14:17:25.253  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 14:17:25.253  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 14:17:25.254  1035  1374 E WifiNative: : [121,811,328 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 14:17:25.254  1035  1374 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 14:17:25.254  1035  1374 D WifiNative-wlan0: RECONNECT: returned true
08-26 14:17:25.254  1035  1374 D WifiNative-wlan0: doString: [STATUS]
08-26 14:17:25.254  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 14:17:25.255  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 14:17:25.255  1035  1374 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 14:17:25.255  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 14:17:25.255  1035  1374 D WifiNative-wlan0: SET ps 1: returned true
08-26 14:17:25.255  1035  1373 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.256  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 14:17:25.256  1035,  1035 D RttService: SCAN_AVAILABLE : 3
08-26 14:17:25.256  1035  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.256  1035  1539 I WifiNative-HAL: startHal
08-26 14:17:25.256  1035  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf6057c0
08-26 14:17:25.256  1035  1539 D wifi    : failed to get capabilities : -3
08-26 14:17:25.256  1035  1539 E WifiScanningService: could not get scan capabilities
08-26 14:17:25.256  1035  1540 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.256  1035  1374 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 14:17:25.257  1035  1374 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 14:17:25.257  1035  1374 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 14:17:25.258  1035  1374 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 14:17:25.258  1035  1374 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 14:17:25.258  1035  1374 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 14:17:25.258   317   904 D CommandListener: Setting iface cfg
08-26 14:17:25.258   317   904 D CommandListener: Trying to bring up p2p0
08-26 14:17:25.259  1035  1374 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 14:17:25.259  1035  1373 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 14:17:25.259  1035  1374 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 14:17:25.259  1035  1373 D LGWifiP2pService: P2pEnablingState
,08-26 14:17:25.259  1035  1373 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.259  1035  1373 D LGWifiP2pService: P2p socket connection successful
08-26 14:17:25.259  7051  7051 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 14:17:25.259  1035  1373 D LGWifiP2pService: P2pEnabledState
08-26 14:17:25.259  1035  1373 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 14:17:25.259  1035  1374 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 14:17:25.260  1035  1374 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 14:17:25.260  1035  1374 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 14:17:25.260  1035  1374 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 14:17:25.260  7051  7051 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 14:17:25.261  1035  1374 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 14:17:25.261  1035  1374 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 14:17:25.262  1035  1374 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 14:17:25.262  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 14:17:25.262  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 14:17:25.263  7051  7051 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:25.263  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 14:17:25.263  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:25.263  1035  7071 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:25.263  1035  7071 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:25.263  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 14:17:25.263  7051  7051 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 14:17:25.263  1953  1953 D WfdsService: WifiP2pState is changed : true
08-26 14:17:25.263  7051  7051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.263  1953  2310 D WfdsService: Receive the WFDS_ENABLE Method
08-26 14:17:25.263  1953  2310 D WfdsService: Set the WFDS Monitor: true
08-26 14:17:25.263  1953  2310 D WfdsService: Connected to the supplicant for wfds
08-26 14:17:25.263  1953  2310 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 14:17:25.264  1953  7074 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:25.264  1035  7071 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:25.264  1035  7071 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.264  1035  7071 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.264  1035  7071 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.264  1035  1374 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 14:17:25.264  7051  7051 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 14:17:25.264  7051  7051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.264  1035  1374 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 14:17:25.264  1035  1374 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 14:17:25.264  1035  1374 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 14:17:25.264  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 14:17:25.265  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 14:17:25.265  7051  7051 I wpa_supplic,ant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 14:17:25.265  1953  2310 D WfdsService: selectPreferredScanChannel [36]
08-26 14:17:25.265  1953  2310 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 14:17:25.265  1953  7074 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:25.265  1035  7071 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:25.265  1035  7071 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.265  1035  7071 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.265  1035  7071 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.265  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 14:17:25.265  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 14:17:25.265  1035  7071 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 14:17:25.265  1035  7071 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 14:17:25.265  1035  1374 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 14:17:25.265  1035  1374 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 14:17:25.265  1035  1374 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 14:17:25.265  1035  1374 D WifiNative-wlan0: doBoolean: SCAN
08-26 14:17:25.266  1035  1373 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 14:17:25.266  1035  1374 D WifiNative-wlan0: SCAN: returned false
08-26 14:17:25.266  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=121824  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 14:17:25.266  1035  1373 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 14:17:25.266  1035  1373 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 14:17:25.266  1035  1373 D WifiNative-p2p0: SET device_name G3: returned true
08-26 14:17:25.267  1035  1373 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 14:17:25.267  1035  1373 D LGWifiP2pService: before postfix = G3
08-26 14:17:25.267  1035  1373 D WifiServerServiceExt: postfix byte check : 2
08-26 14:17:25.267  1035  1373 D LGWifiP2pService: after postfix = G3
08-26 14:17:25.267  1035  1373 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 14:17:25.267  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=121825  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 14:17:25.267  1953  1953 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 14:17:25.267  1035  1374 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 14:17:25.268  1035  1374 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 14:17:25.268  1953  1953 D WfdsService: isConnected: false
08-26 14:17:25.268  1035  1374 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 14:17:25.268  1035  1374 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 14:17:25.269  1035  1373 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 14:17:25.269  1035  1373 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 14:17:25.269  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:25.269  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:25.270  1035  1374 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UN,KNOWN/IDLE
08-26 14:17:25.270  1035  1373 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 14:17:25.270  1035  1373 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 14:17:25.270  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:25.270  1035  1373 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 14:17:25.270  1035  1373 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 14:17:25.272  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:25.272  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:25.272  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 14:17:25.273  1035  1373 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 14:17:25.274  1035  1373 D WifiNative-HAL: p2pGetDeviceAddress
08-26 14:17:25.274  1035  1373 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 14:17:25.274  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:25.274  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 14:17:25.274  1035  1373 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 14:17:25.274  1035  1373 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 14:17:25.275  1953  1953 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 14:17:25.275  1035  1373 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 14:17:25.275  1035  1373 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 14:17:25.275  1953  1953 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 14:17:25.275  1953  1953 D WfdsService: Update P2p Interface State: 3
08-26 14:17:25.275  1035  1373 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 14:17:25.275  1035  1373 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 14:17:25.275  1035  1373 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 14:17:25.275  1035  1373 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 14:17:25.284  1035  1373 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 14:17:25.284  1035  1373 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 14:17:25.284  1035  1373 D LGWifiP2pService: InactiveState
08-26 14:17:25.284  1035  1373 D LGWifiP2pService: InactiveState{ when=-21ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.284  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.284  1035  1373 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 14:17:25.284  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-26 14:17:25.285  7051  7051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:25.286  1035  7071 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-26 14:17:25.286  1035  7071 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:25.286  1035  7071 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:25.286  1035  7071 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:25.286  7051  7051 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 14:17:25.286  1953  7074 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 14:17:25.286  7051  7051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.286  1953  7074 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:25.286  1035  7071 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:25.286  1035  7071 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.286  1035  7071 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.286  1035  7071 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.286  1035  1373 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  7051  7051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.287  1035  1373 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.288  1035  7071 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:25.288  1953  2310 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 14:17:25.288  1035  7071 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.288  1035  7071 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.288  1035  7071 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:25.288  1953  7074 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:25.288  1035  1373 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.288  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.andro,id.internal.util.StateMachine$SmHandler }
08-26 14:17:25.288  1035  1373 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:25.288  1035  1035 E WifiServerServiceExt: No p2p device connected
08-26 14:17:25.315  7053  7053 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 14:17:25.347  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 14:17:25.347  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:25.347  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 14:17:25.348  7053  7053 I HubEmail: JNI_OnLoad()
08-26 14:17:25.348  7053  7053 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-26 14:17:25.348  7053  7053 I HubEmail: registerNatives()
08-26 14:17:25.348  7053  7053 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 14:17:25.348  7053  7053 I HubEmail: registerNativeMethods()
08-26 14:17:25.348  7053  7053 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 14:17:25.348  7053  7053 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-26 14:17:25.352  6927  7078 W FormManager: Network not available. Please check & try again.
08-26 14:17:25.353  7053  7080 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:25.410  1035  1583 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7081 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 14:17:25.425  6927  7079 V FormManager: Network unavailable.
,08-26 14:17:25.429  6927  7079 V FormManager: Network unavailable.
08-26 14:17:25.440  1035  2347 I ActivityManager: Killing 6529:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-26 14:17:25.478  1035  1934 W libprocessgroup: failed to open /acct/uid_10061/pid_6529/cgroup.procs: No such file or directory
08-26 14:17:25.561  7081  7081 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:25.561  7081  7081 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 14:17:25.565  7081  7081 D PhoneMonitor: Register our PhoneStateListener
,08-26 14:17:25.590  7081  7081 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 14:17:25.592  7081  7081 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 14:17:25.607  7081  7081 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-26 14:17:25.609  7081  7081 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 14:17:25.610  7081  7081 D TelephonyAutoProfiling: [parse] Load xml
08-26 14:17:25.619  7081  7081 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 14:17:25.619  7081  7081 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 14:17:25.619  7081  7081 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 14:17:25.628  7081  7081 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-26 14:17:25.655  1035  1051 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7104 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:25.658  1035  1051 I ActivityManager: Killing 6133:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-26 14:17:25.723  1035  1714 W libprocessgroup: failed to open /acct/uid_10097/pid_6133/cgroup.procs: No such file or directory
08-26 14:17:25.913  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 14:17:25.913  1035  7071 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-26 14:17:25.915  7051  7051 E wpa_supplicant: USIM:  scard_init function
,08-26 14:17:25.916  7051  7051 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 14:17:25.924  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-26 14:17:25.924  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 14:17:25.924  1035  7071 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 14:17:25.925  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 14:17:25.925  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 14:17:25.925  1035  1374 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-26 14:17:25.932  1035  1931 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7125 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-26 14:17:25.940  1035  1374 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 14:17:25.941  1035  1374 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 14:17:25.941  1035  1374 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 14:17:25.941  1035  1374 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 14:17:25.943  1035  1931 I ActivityManager: Killing 6631:com.lge.eula/1000 (adj 15): empty #17
08-26 14:17:26.019  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122577  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 14:17:26.021  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122579  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 14:17:26.025  1035  1952 W libprocessgroup: failed to open /acct/uid_1000/pid_6631/cgroup.procs: No such file or directory
08-26 14:17:26.032  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.032  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:26.033  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.033  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.033  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 14:17:26.034  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.035  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.035  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-26 14:17:26.036  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.039  7051  7051 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 14:17:26.039  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:26.039  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 14:17:26.041  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 14:17:26.041  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 14:17:26.042  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 14:17:26.042  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 14:17:26.042  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:26.042  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:26.044  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.044  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:26.045  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122602  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 14:17:26.045  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.046  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122604  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 14:17:26.048  1035  1374 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122606
08-26 14:17:26.049  1035  1374 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122607
08-26 14:17:26.049  1035  1374 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122607
08-26 14:17:26.050  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122607
08-26 14:17:26.050  1035  1374 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122608
08-26 14:17:26.051  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=122608  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 14:17:26.051  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 14:17:26.056  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:26.056  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:26.056  7051  7051 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 14:17:26.056  7051  7051 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 14:17:26.056  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 14:17:26.056  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 14:17:26.056  1035  7071 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 14:17:26.056  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 14:17:26.056  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 14:17:26.057  1035  7071 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 14:17:26.057  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:26.057  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:26.061  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.061  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.061  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 14:17:26.063  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=122620  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 14:17:26.067  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.068  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.068  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.069  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:26.069  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 14:17:26.069  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.070  1035  1374 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:26.070  1035  1374 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:26.071  1035  1374 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:26.071  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:26.072  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.072  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:26.072  1035  1374 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:26.072  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122630  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 14:17:26.073  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.073  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:26.073  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 14:17:26.074  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122631  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 14:17:26.074  1035  1374 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122632
08-26 14:17:26.075  1035  1374 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122633
08-26 14:17:26.075  1035  1374 D WifiNative-wlan0: doString: [STATUS]
08-26 14:17:26.076  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:26.076  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:26.076  1035  1374 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 14:17:26.078  1035  1374 I WifiServiceExtension: setVHTCapabilityType  : false
,08-26 14:17:26.085  1035  1374 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 14:17:26.085  1035  1374 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-26 14:17:26.090  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.090  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:26.091  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.092  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.092  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 14:17:26.093  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.093  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.093  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 14:17:26.093  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.096  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.096  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:26.096  1035  1374 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 14:17:26.096  1035  1429 D ConnectivityService: Got NetworkAgent Messenger
08-26 14:17:26.096  1035  1374 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 14:17:26.096  1035  1374 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 14:17:26.096  1035  1429 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 14:17:26.096  1035  1429 D ConnectivityService: NetworkAgent connected
08-26 14:17:26.097  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.097  1035  1374 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 14:17:26.097  1035  1374 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 14:17:26.105  1035  1374 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 14:17:26.105  1035  1374 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 14:17:26.105  1035  1374 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-26 14:17:26.106  1035  1374 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 14:17:26.106  1035  1374 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 14:17:26.109  1035  1374 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 14:17:26.111   317   904 D CommandListener: Setting iface cfg
08-26 14:17:26.154  1035  1051 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7156 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:26.155  1035  1051 I ActivityManager: Killing 6654:com.lge.bnr/1000 (adj 15): empty #17
08-26 14:17:26.208  1035  2056 W libprocessgroup: failed to open /acct/uid_1000/pid_6654/cgroup.procs: No such file or directory
,08-26 14:17:26.226  1035  1374 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 14:17:26.226  1035  7155 D DhcpStateMachine: StoppedState
08-26 14:17:26.226  1035  7155 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.226  1035  7155 D DhcpStateMachine: WaitBeforeStartState
08-26 14:17:26.228  1035  1374 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122785  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:26.228  1035  1374 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122786  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:26.229  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122786  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:26.230  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:26.230  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 14:17:26.231  1035  1374 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122789  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:26.232  1035  1374 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122790  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:26.233  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122790  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:26.235  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77683] from screen [on:0 period:-959936294] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 14:17:26.236  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-959936292] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 14:17:26.236  1035  1374 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 14:17:26.240  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 14:17:26.246  1035  1429 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 14:17:26.248  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.249  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.250  1035  1374 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.252  1035  1374 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.253  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.254  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.255  1035  1429 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-26 14:17:26.256  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-26 14:17:26.258  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-26 14:17:26.258  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 14:17:26.259  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 14:17:26.260  1035  1374 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 14:17:26.260  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 14:17:26.261  7156  7156 I art     : Almond Protected OAT
08-26 14:17:26.261  1035  1374 D WifiNative-wlan0: SET ps 0: returned true
08-26 14:17:26.261  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 14:17:26.262  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 14:17:26.263  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 14:17:26.263  1035  1374 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 14:17:26.263  1035  1374 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 14:17:26.263  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16935945 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.263  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16935945 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.263  1035  7155 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.263  1035  1374 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 14:17:26.263  1035  7155 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 14:17:26.266   317   904 D CommandListener: Setting iface cfg
08-26 14:17:26.266   317   904 D CommandListener: Trying to bring up wlan0
,08-26 14:17:26.268  1035  1374 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds,
08-26 14:17:26.269  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:26.269  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 14:17:26.270  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0,
08-26 14:17:26.270  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:26.270  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-26 14:17:26.270  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.270  1035  1374 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.271  1035  1374 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.271  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:26.272  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 14:17:26.273  1035  1429 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 14:17:26.274  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 14:17:26.274  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-26 14:17:26.274  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 14:17:26.274  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.274  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.274  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 14:17:26.275  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-26 14:17:26.275  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 14:17:26.275  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 14:17:26.275  1035  1374 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-26 14:17:26.276  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 14:17:26.292  1035  1374 D WifiNative-wlan0: SET ps 1: returned true
08-26 14:17:26.293  1035  1429 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-26 14:17:26.293  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 14:17:26.294  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 14:17:26.294  1035  1374 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 14:17:26.294  1035  1429 D ConnectivityService: ignoring duplicate network state non-change
,08-26 14:17:26.296  1035  1429 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 14:17:26.297  1035  1429 D ConnectivityService: Adding iface wlan0 to network 101
08-26 14:17:26.301  1035  1374 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 14:17:26.330  1035  1429 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 14:17:26.330  1035  1429 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 14:17:26.331  1035  1429 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 14:17:26.332   317   904 E Netd    : netlink response contains error (File exists)
08-26 14:17:26.332  1035  1429 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 14:17:26.333  1035  1429 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 14:17:26.333  1035  1429 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 14:17:26.333  1035  1429 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 14:17:26.334  1035  1429 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 14:17:26.335  1035  1429 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 14:17:26.335  1035  1429 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 14:17:26.335  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.335  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 14:17:26.335  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.335  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 14:17:26.337  1035  1429 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 14:17:26.337  1035  1429 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:26.337  1035  1429 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:26.337  1035  1429 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 14:17:26.337  1035  1429 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.337  1035  1429 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 14:17:26.337  1035  1429 D ConnectivityService: currentScore = 0, newScore = 20
08-26 14:17:26.337  1035  1429 D ConnectivityService:    accepting network in place of null
08-26 14:17:26.337  1035  1429 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.338  1035  1374 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.338  1035  1374 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:26.338  1861  1861 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.338  1861  1861 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 14:17:26.338   317  7176 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 14:17:26.340  1035  1429 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [,fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 14:17:26.340  1035  1429 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 14:17:26.340  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 14:17:26.340  1035  1429 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:26.340  1035  1429 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 14:17:26.341  1035  1429 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 14:17:26.342  1035  1429 D ConnectivityService: validation of new default Network = false
08-26 14:17:26.342  1035  1429 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 14:17:26.342  1035  1429 D DSQN    : enableDataServiceNotify 
08-26 14:17:26.342  1035  1429 D DSQN    : start dsqn bin
08-26 14:17:26.346  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.346  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:26.351  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.352  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.352  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.352  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 14:17:26.345  7177  7177 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:26.354  1035  1429 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 14:17:26.345  7177  7177 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:26.354  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.354  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:26.356  1035  1429 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:26.357  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.357  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.357  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 14:17:26.358  1586  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 14:17:26.360  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 14:17:26.363  1953  1953 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 14:17:26.364  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.364  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.364  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 14:17:26.365  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 14:17:26.372  7177  7177 E DSQN    : DSQN ssw
08-26 14:17:26.373  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.373  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:26.373  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 14:17:26.373  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.373  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:26.374  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.375  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 14:17:26.376  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 14:17:26.376  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 14:17:26.376  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 14:17:26.378  7156  7156 D WeatherApplication: removeAccount
08-26 14:17:26.379  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.380  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 14:17:26.380  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.383  7156  7156 D WeatherApplication: Account.length = 0
08-26 14:17:26.383  7156  7156 E WeatherApplication: OPERATOR:OPEN
,08-26 14:17:26.391  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:26.391  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 14:17:26.392  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.394  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:26
08-26 14:17:26.394   317  7176 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 14:17:26.397  1035  1372 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 14:17:26.397  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 14:17:26.397  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-26 14:17:26.400  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 14:17:26.401  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-26 14:17:26.402  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-26 14:17:26.412  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 14:17:26.412  1803  7181 I CheckinService: active receiver: enabled
08-26 14:17:26.412  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 14:17:26.412  7156  7156 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-26 14:17:26.422  1803  7181 I CheckinService: Preparing to send checkin request
08-26 14:17:26.422  1803  7181 I EventLogService: Accumulating logs since 1472213781032
08-26 14:17:26.427   317  7176 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 14:17:26.428  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 14:17:26.429  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.430  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.433  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 14:17:26.433  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:26
08-26 14:17:26.460   317   903 D LGDataListener: argv[0]=dsqncommand
,08-26 14:17:26.460   317   903 D LGDataListener: argv[1]=wlan0
08-26 14:17:26.460   317   903 D LGDataListener: argv[2]=1
08-26 14:17:26.460   317   903 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 14:17:26.460  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 14:17:26.460  1035  1115 D DSQN    : start to monitor internet connection
08-26 14:17:26.466  1035  7155 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 14:17:26.468  1035  7155 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 14:17:26.468  1035  7155 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 14:17:26.465  7187  7187 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:26.465  7187  7187 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 14:17:26.480  1035  2030 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7186 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:26.482  7187  7187 I dhcpcd  : version 5.5.6 starting
08-26 14:17:26.482  1035  2030 I ActivityManager: Killing 2210:com.lge.music/u0a34 (adj 15): empty #17
08-26 14:17:26.483  7187  7187 E dhcpcd  : get_duid: m
08-26 14:17:26.484  7187  7187 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 14:17:26.484  7187  7187 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 14:17:26.491  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 12:17:26 GMT], X-Android-Received-Millis=[1472213846491], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472213846459]}
08-26 14:17:26.491  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 14:17:26.491  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-26 14:17:26.493  1035  1429 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 14:17:26.493  1035  1429 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 14:17:26.493  1035  1429 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:26.493  1035  1429 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:26.493  1035  1429 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 14:17:26.493  1035  1429 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 14:17:26.493  1035  1429 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 14:17:26.493  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.493  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:26.494  1035  1429 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:26.494  1035  1429 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.494  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 14:17:26.495  1035  1374 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.495  1035  1374 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:26.495  1861  1861 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:26.495  1586  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 14:17:26.495  1861  1861 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 14:17:26.504   321  1380 V AudioFlinger: 2210 died, releasing its sessions
08-26 14:17:26.504   321  1380 V AudioFlinger:  pid 1861 @ 0
08-26 14:17:26.504   321  1380 V AudioFlinger:  pid 3459 @ 1
08-26 14:17:26.504   321  1380 V AudioFlinger:  pid 3459 @ 2
,08-26 14:17:26.544  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.544  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:26.544  1035  1373 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:26.545  1803  7181 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-26 14:17:26.555  7187  7187 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 14:17:26.556  7187  7187 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 14:17:26.556  7187  7187 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 14:17:26.556  7187  7187 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 14:17:26.556  7187  7187 D dhcpcd  : wlan0: sending REQUEST (xid 0x5f3b9da1), next in 4.35 seconds
,08-26 14:17:26.559  1035  1050 W libprocessgroup: failed to open /acct/uid_10034/pid_2210/cgroup.procs: No such file or directory
08-26 14:17:26.566  1035  1374 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 14:17:26.567  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 14:17:26.568  1035  1374 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 14:17:26.568  1035  1374 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 14:17:26.569  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-26 14:17:26.570  1035  1374 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-26 14:17:26.586  7187  7187 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 14:17:26.599  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 14:17:26.600  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 14:17:26.601  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:26.607  7187  7187 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 14:17:26.607  7187  7187 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 14:17:26.608  7187  7187 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 14:17:26.608  7187  7187 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 14:17:26.608  7187  7187 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 14:17:26.608  7187  7187 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 14:17:26.609  7187  7187 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 14:17:26.609  7187  7187 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 14:17:26.694   278   336 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 14:17:26.695   278   336 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 14:17:26.695   278   336 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:26.698  7186  7219 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 14:17:26.708   278   336 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 14:17:26.708   278   336 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 14:17:26.708   278   336 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 14:17:26.708  7186  7219 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 14:17:26.717   278   336 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 14:17:26.717   278   336 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 14:17:26.717   278   336 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 14:17:26.717  7186  7225 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 14:17:26.720   278   336 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 14:17:26.720   278   336 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 14:17:26.720   278   336 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 14:17:26.720  7186  7225 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 14:17:26.724  1035  2051 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7227 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-26 14:17:26.746   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 22.635ms
,08-26 14:17:26.769   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 21.687ms
,08-26 14:17:26.790   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 20.397ms
,08-26 14:17:26.798  7227  7227 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 14:17:26.798  7227  7227 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 14:17:26.819  7227  7227 I MultiDex: VM with version 2.1.0 has multidex support
08-26 14:17:26.819  7227  7227 I MultiDex: install
08-26 14:17:26.819  7227  7227 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 14:17:26.825  7227  7227 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-26 14:17:26.874  1035  7155 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-26 14:17:26.875  1035  7155 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 14:17:26.875  1035  7155 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 14:17:26.875  1035  7155 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 14:17:26.875  1035  7155 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 14:17:26.875  1035  7155 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 14:17:26.875  1035  7155 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 14:17:26.875  1035  7155 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 14:17:26.875  1035  7155 D DhcpStateMachine: RunningState
08-26 14:17:26.920  7186  7186 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 14:17:26.931  7186  7186 I LibraryLoader: Loading: webviewchromium
,08-26 14:17:26.935  7186  7186 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3503-3508)
08-26 14:17:26.935  7186  7186 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 14:17:26.944  7186  7186 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2eb111de}
,08-26 14:17:26.948  7186  7186 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 14:17:26.949  7186  7186 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 14:17:26.972  7186  7186 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 14:17:26.973  7186  7186 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:17:26.991  7186  7186 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 14:17:26.992  7186  7186 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
08-26 14:17:26.992  7186  7186 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
,08-26 14:17:27.005   321  1715 V AudioPolicyService: registerClient() client 0xb0410080, uid 10093
,08-26 14:17:27.008  7186  7274 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 14:17:27.013  7186  7186 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 14:17:27.013  7186  7186 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 14:17:27.013  7186  7186 I Adreno-EGL: Build Date: 12/12/14 금
08-26 14:17:27.013  7186  7186 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 14:17:27.013  7186  7186 I Adreno-EGL: Remote Branch: 
08-26 14:17:27.013  7186  7186 I Adreno-EGL: Local Patches: 
08-26 14:17:27.013  7186  7186 I Adreno-EGL: Reconstruct Branch: 
08-26 14:17:27.093  7282  7282 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 14:17:27.124  7186  7186 I NSApplication: Starting up...
,08-26 14:17:27.176  7282  7282 I dex2oat : dex2oat took 82.496ms (threads: 4)
,08-26 14:17:27.192  7227  7248 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 14:17:27.192  7227  7248 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 14:17:27.192  7227  7248 I Adreno-EGL: Build Date: 12/12/14 금
08-26 14:17:27.192  7227  7248 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 14:17:27.192  7227  7248 I Adreno-EGL: Remote Branch: 
08-26 14:17:27.192  7227  7248 I Adreno-EGL: Local Patches: 
08-26 14:17:27.192  7227  7248 I Adreno-EGL: Reconstruct Branch: 
08-26 14:17:27.194  1035  1769 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7296 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:27.195  1035  1769 I ActivityManager: Killing 6065:com.android.vending/u0a44 (adj 15): empty #17
08-26 14:17:27.200  1035  1374 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:27.200  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:27.201  1035  1374 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:27.201  1035  1374 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:27.202  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:27.202  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 14:17:27.203  1035  1429 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-26 14:17:27.203  1035  1429 D ConnectivityService: identical MTU - not setting
08-26 14:17:27.203  1035  1429 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 14:17:27.203  1035  1429 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 14:17:27.203  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:27.203  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:27.203  1035  1429 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:27.204  1586  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 14:17:27.312  1035  1050 W libprocessgroup: failed to open /acct/uid_10044/pid_6065/cgroup.procs: No such file or directory
,08-26 14:17:27.341  7227  7248 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 14:17:27.341  7227  7248 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 14:17:27.341  7227  7248 I Adreno-EGL: Build Date: 12/12/14 금
08-26 14:17:27.341  7227  7248 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 14:17:27.341  7227  7248 I Adreno-EGL: Remote Branch: 
08-26 14:17:27.341  7227  7248 I Adreno-EGL: Local Patches: 
08-26 14:17:27.341  7227  7248 I Adreno-EGL: Reconstruct Branch: 
,08-26 14:17:27.354  1035  1429 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 14:17:27.354  1035  2006 D WifiServiceImplEx: setWifiEnabled: false pid=6586, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 14:17:27.354  1035  2006 D WifiService: setWifiEnabled: false pid=6586, uid=10118
08-26 14:17:27.354  1035  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 14:17:27.365  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 14:17:27.365  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 14:17:27.365  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 14:17:27.367  1035  1374 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:27.367  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:27.368  1035  1374 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:27.368  1035  1374 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:27.368  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 14:17:27.369  1035  1374 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 14:17:27.369  1035  1374 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 14:17:27.369  1035  1374 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 14:17:27.369  1035  1374 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 14:17:27.369  1035  1374 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 14:17:27.376  1035  1374 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 14:17:27.377  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 14:17:27.377  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.377  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 14:17:27.377  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.377  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 14:17:27.377  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 14:17:27.377  1035  1374 D WifiNative-wlan0: SET ps 1: returned true
08-26 14:17:27.378  1035  7155 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.378   317   904 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:27.390  7296  7296 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:17:27.408  1035  1429 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 14:17:27.408  1035  1429 D ConnectivityService: ignoring duplicate network state non-change
08-26 14:17:27.408  1035  1429 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-26 14:17:27.410  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:27.410  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:27.411  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 14:17:27.411  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:27.412  1953  1953 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 14:17:27.413  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.413  1035  1374 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:27.413  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.413  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 14:17:27.414  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:27.414  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:27.414  1035  1374 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:27.414  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:27.414  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:27.415  1035  1374 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 14:17:27.415  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.415  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.415  1035  1373 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3699e4d
08-26 14:17:27.415  1035  1373 D LGWifiP2pService: P2pDisablingState
08-26 14:17:27.415  1035  1373 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.415  1035  1373 D LGWifiP2pService: p2p socket connection lost
08-26 14:17:27.415  1035  1373 D LGWifiP2pService: P2pDisabledState
08-26 14:17:27.416  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 14:17:27.418  1035  1374 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 14:17:27.418  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-26 14:17:27.418  7051  7051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 14:17:27.418  1035  1373 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.418  1035  1373 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.419  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 14:17:27.419  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 14:17:27.420  1035  1374 D WifiNative-wlan0: SET ps 1: returned true
08-26 14:17:27.421  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.421  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.421  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 14:17:27.421  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 14:17:27.421  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-26 14:17:27.422  1035  1539 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.422  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 14:17:27.422  1953  1953 D WfdsService: WifiP2pState is changed : false
08-26 14:17:27.422  1953  2310 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 14:17:27.423  1953  2310 D WfdsService: Set the WFDS Monitor: false
08-26 14:17:27.423  1953  2310 D WfdsMonitor: WFDS Monitor is stopped
08-26 14:17:27.423  1953  2310 D WfdsService: STATE : WfdsDisabledState - enter
08-26 14:17:27.423  1953  7074 D CtrlSupplicant: Received on exit socket, terminate
08-26 14:17:27.423  1953  7074 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 14:17:27.423  1953  7074 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 14:17:27.423  1953  7074 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 14:17:27.423  1953  2312 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 14:17:27.423  1035  1540 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.424  1953  2310 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 14:17:27.434  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:27.434  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:27.438  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 14:17:27.464   317   904 D CommandListener: Clearing all IP addresses on wlan0
08-26 14:17:27.464  1035  1429 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 14:17:27.464  1035  1429 D DSQN    : disableDataServiceNotify
08-26 14:17:27.464  1035  1429 D DSQN    : stop dsqn bin
,08-26 14:17:27.470  1035  1429 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 14:17:27.470  1035  1374 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 14:17:27.470  1035  1374 D WifiNative-p2p0: TERMINATE: returned true
08-26 14:17:27.470  1035  1374 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 14:17:27.470  1035  1374 E WifiStateMachine: useWiFiOffloading() : false
08-26 14:17:27.470  1035  1374 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 14:17:27.471  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 14:17:27.471  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:27.471  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:27.471  1035  1429 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:27.471  1035  1429 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 14:17:27.472  1035  1429 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
,08-26 14:17:27.472  1035  1429 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 14:17:27.472  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 14:17:27.472  1586  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 14:17:27.472  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.472  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.472  1035  7153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 14:17:27.474  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.474  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 14:17:27.474  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:27.474  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.474  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 14:17:27.478  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-26 14:17:27.481  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 14:17:27.481  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:27.481  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 14:17:27.481  1035  1429 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:27.481  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 14:17:27.482  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.482  1035  1429 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:27.482  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:27.482  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:27.482  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:27.482  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:27.482  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:27.482  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:27.482  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:27.482  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:27.482  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.482  1035  1429 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:27.482  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:27.482  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:27.482  1035  1429 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:27.482  1035  1429 D NetworkManagementService: Removing idletimer
08-26 14:17:27.482  1035  1429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.482  1035  1374 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:27.482  1035  1374 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:27.483  1035  1372 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 14:17:27.483  1861  1861 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:27.483  1861  1861 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 14:17:27.483  1035  1372 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 14:17:27.483  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for ,multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.483  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:27.483  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:27.483  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:27.483  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:27.483  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:27.483  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:27.483  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:27.483  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:27.483  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.483  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:27.484  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:27.484  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 14:17:27.485  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 14:17:27.485  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 14:17:27.485  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 14:17:27.485  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 14:17:27.485  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 14:17:27.485  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 14:17:27.485  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-26 14:17:27.515  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 14:17:27.516  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:27.516  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 14:17:27.529  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 14:17:27.531  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:27.531  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:27.578  7051  7051 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 14:17:27.578  7051  7051 I wpa_supplicant: monitor socket send errors count : 1
08-26 14:17:27.578  1035  1952 I art     : Explicit concurrent mark sweep GC freed 125674(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.159ms total 114.369ms
08-26 14:17:27.578  7051  7051 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1953-4\x00 that cannot receive messages
,08-26 14:17:27.581  1035  7071 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 14:17:27.581  1035  7071 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 14:17:27.590  1035  7155 D DhcpStateMachine: StoppedState
08-26 14:17:27.590  1035  7155 D DhcpStateMachine: StoppedState{ when=-170ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:27.592  1035  1374 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 14:17:27.592  1035  1374 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 14:17:27.601  7051  7051 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 14:17:27.602  7051  7051 W wpa_supplicant: USIM:  scard_deinit function
08-26 14:17:27.603  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 14:17:27.603  7227  7248 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 14:17:27.603  7227  7248 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 14:17:27.603  7227  7248 I Adreno-EGL: Build Date: 12/12/14 금
08-26 14:17:27.603  7227  7248 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 14:17:27.603  7227  7248 I Adreno-EGL: Remote Branch: 
08-26 14:17:27.603  7227  7248 I Adreno-EGL: Local Patches: 
08-26 14:17:27.603  7227  7248 I Adreno-EGL: Reconstruct Branch: 
08-26 14:17:27.603  1035  1117 D Tethering: InitialState.processMessage what=4
,08-26 14:17:27.603  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 14:17:27.603  1035  7071 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 14:17:27.603  1035  7071 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 14:17:27.603  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:27.603  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:27.604  1035  1374 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124162
08-26 14:17:27.605  1035  1374 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124162
08-26 14:17:27.605  1035  1374 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124163  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 14:17:27.606  1035  1374 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124164  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 14:17:27.607  1035  1374 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:27.607  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:27.609  1035  1374 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:27.800  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 14:17:27.802  6392  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 14:17:27.817  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:27.818  7051  7051 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 14:17:27.818  1035  7071 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 14:17:27.818  1035  7071 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 14:17:27.818  1035  7071 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 14:17:27.819  1035  1374 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-26 14:17:27.828  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 14:17:27.828  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:27.828  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 14:17:27.828  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 14:17:27.830  7006  7006 I AppUp4:CustModeStarterReceiver: onReceive
08-26 14:17:27.834  7006  7006 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1b0d61d7
08-26 14:17:27.834  7006  7006 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 14:17:27.834  7006  7006 D AppUp4:CustFacade: isPhone : true
08-26 14:17:27.835  7006  7006 D AppUp4:CustModeStarterReceiver: begin check event
08-26 14:17:27.835  7006  7006 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 14:17:27.838  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:27.838  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 14:17:27.840  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:27.842  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 14:17:27.846  4285  7334 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 14:17:27.848  7053  7053 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 14:17:27.853  4285  7335 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:27.853  4285  7335 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 14:17:27.873  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 14:17:27.873  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:27.873  7053  7336 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.873  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 14:17:27.875  7081  7081 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 14:17:27.875  7081  7081 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 14:17:27.879  6927  7338 W FormManager: Network not available. Please check & try again.
08-26 14:17:27.882  6927  7340 V FormManager: Network unavailable.
08-26 14:17:27.885  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:27
08-26 14:17:27.886  6927  7340 V FormManager: Network unavailable.
,08-26 14:17:27.887  7227  7248 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:27.887  7227  7248 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 14:17:27.887  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 14:17:27.887  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-26 14:17:27.888  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 14:17:27.888  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-26 14:17:27.888  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11428dad
,08-26 14:17:27.889  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 14:17:27.889  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 14:17:27.889  7156  7156 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 14:17:27.889  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 14:17:27.889  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:27
08-26 14:17:27.913  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:27.913  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 14:17:27.913  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 14:17:27.914  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 14:17:27.917  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 14:17:27.917  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 14:17:27.917  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 14:17:27.917  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 14:17:27.917  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 14:17:27.917  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 14:17:27.917  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 14:17:27.924  1953  1953 D WfdsService: Supplicant Connection state is changed : false
08-26 14:17:27.924  1953  2310 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 14:17:27.924  1953  2310 D WfdsService: Set the WFDS Monitor: false
08-26 14:17:27.924  1953  2310 D WfdsMonitor: WFDS Monitor is stopped
08-26 14:17:27.924  1035  1374 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 14:17:27.924  1035  1374 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 14:17:27.924  1035  1374 E WifiStateMachine: useWiFiOffloading() : false
08-26 14:17:27.924  1035  1374 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 14:17:27.927  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 14:17:27.927  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 14:17:27.928  2468  2468 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.929  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.929  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:27.929  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:27.929  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:27.929  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:27.929  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:27.929  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:27.929  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:27.929  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:27.930  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 14:17:27.930  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.930  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:27.930  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:27.930  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:27.930  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:27.930  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:27.930  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:27.930  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:27.930  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:27.931  1035  1386 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 14:17:27.931  1035  1386 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 14:17:27.931  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:27.935  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:27.941  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:27.942  6927  7347 W FormManager: Network not available. Please check & try again.
08-26 14:17:27.944  6927  7348 V FormManager: Network unavailable.
08-26 14:17:27.948   317  7350 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 14:17:27.949  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 14:17:27.949  1803  7181 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-26 14:17:27.952  6927  7348 V FormManager: Network unavailable.
,08-26 14:17:27.956  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:27.959  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:27.960  1803  7181 I CheckinService: active receiver: disabled
,08-26 14:17:27.969  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:27.976  6927  7351 W FormManager: Network not available. Please check & try again.
08-26 14:17:27.980  6927  7352 V FormManager: Network unavailable.
,08-26 14:17:27.983  6927  7352 V FormManager: Network unavailable.
08-26 14:17:27.985  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 14:17:27.985  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 14:17:27.987  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:27.988  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:27.992  4285  7353 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 14:17:27.994  4285  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 14:17:27.994  4285  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 14:17:28.048  1035  1583 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7355 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 14:17:28.165  7355  7355 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 14:17:28.165  7355  7355 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-26 14:17:28.182  7355  7355 V [BNRBootReceiver]: Boot Receiver Return
,08-26 14:17:28.183  7355  7355 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 14:17:28.190  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:28.202  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.211  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.230  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.231  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 14:17:28.234  6885  6885 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:28.241  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-26 14:17:28.250  6837  6837 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 14:17:28.255  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:28.267  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.282  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.296  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 14:17:28.297  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.302  6885  6885 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:28.310  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:28.329  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.340  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.355  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.356  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.356  6700  6997 D UEI.SmartControl: Internal timer expired: 2
08-26 14:17:28.356  6700  6997 D UEI.SmartControl: unbind internal service
,08-26 14:17:28.357  6885  6885 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 14:17:28.366  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:28.376  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.385  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 14:17:28.396  6700  6991 D serial_port: close(fd = 24)
,08-26 14:17:28.397  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.398  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.399  6885  6885 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:28.406  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:28.406  6700  6991 I UEI.SmartControl: Serial port is closed.
08-26 14:17:28.415  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.421  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.430  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 14:17:28.431  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.431  6885  6885 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:28.437  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:28.455  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.464  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.475  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 14:17:28.476  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.476  6885  6885 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 14:17:28.487  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:28.494  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.502  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 14:17:28.509  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.510  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.510  6885  6885 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 14:17:28.523  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:28.536  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.543  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.552  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.553  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 14:17:28.559  6885  6885 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:28.567  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:28.582  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.593  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.605  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.606  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.607  6885  6885 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 14:17:28.615  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:28.625  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 14:17:28.641  1035  1425 D WifiService: New client listening to asynchronous messages
,08-26 14:17:28.643  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:28.654  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.667  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.682  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.683  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.685  6885  6885 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 14:17:28.688  6885  6885 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 14:17:28.689  6885  6885 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 14:17:28.705  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:28.723  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 14:17:28.730  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:28.738  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:28.744  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 14:17:28.758  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.759  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.761  6885  6885 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 14:17:28.763  6885  6885 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 14:17:28.764  6885  6885 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 14:17:28.771  1035  1050 I ActivityManager: Killing 6814:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-26 14:17:28.881  1035  1988 W libprocessgroup: failed to open /acct/uid_10037/pid_6814/cgroup.procs: No such file or directory
,08-26 14:17:28.899  2227  2227 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-26 14:17:28.915  2227  2227 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-26 14:17:28.915  2227  2227 D c       : Getting all permits...
08-26 14:17:28.915  2227  2227 D a       : Opening database...
,08-26 14:17:28.921  2227  2227 D a       : Opening database auth.proximity.permit_store...
08-26 14:17:28.922  2227  2227 D a       : Closing database...
08-26 14:17:28.933  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:28.940  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 14:17:28.940  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 14:17:28.940  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:28.944  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:28.951  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 14:17:28.960  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.960  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:28.962  6885  6885 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:28.965  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:28.969  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 14:17:28.969  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 14:17:28.969  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:28.974  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:28.981  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:28.992  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:28.992  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 14:17:28.996  6885  6885 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:29.002  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:29.009  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 14:17:29.009  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 14:17:29.009  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:29.016  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:29.025  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:29.032  6885  6885 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 14:17:29.033  6885  6885 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:29.036  6885  6885 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:29.046  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:29.051  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:29.058  6927  7387 W FormManager: Network not available. Please check & try again.
08-26 14:17:29.059  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:29.068  6927  7388 V FormManager: Network unavailable.
,08-26 14:17:29.077  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 14:17:29.078  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 14:17:29.079  6927  7388 V FormManager: Network unavailable.
08-26 14:17:29.080  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:29.082  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 14:17:29.090  4285  7389 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 14:17:29.093  4285  7390 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 14:17:29.094  4285  7390 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 14:17:29.101  6856  6856 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 14:17:29.101  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 14:17:29.102  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:29.110  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:29.121  6927  7392 W FormManager: Network not available. Please check & try again.
08-26 14:17:29.123  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:29.137  6927  7393 V FormManager: Network unavailable.
,08-26 14:17:29.141  6927  7393 V FormManager: Network unavailable.
08-26 14:17:29.154  2227  2227 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-26 14:17:29.246  1035  1374 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-959933282] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 14:17:29.249  1035  1374 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-959933279] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 14:17:29.346  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:29.353  1035  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:29.359  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-26 14:17:29.362  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:29.363  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:29.366  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 14:17:29.368  6392  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 14:17:29.372  5752  5752 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 14:17:29.382  1035  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 14:17:29.393  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:29.405  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 14:17:29.405  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:29.405  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 14:17:29.405  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 14:17:29.409  7006  7006 I AppUp4:CustModeStarterReceiver: onReceive
08-26 14:17:29.412  7006  7006 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1b0d61d7
08-26 14:17:29.412  7006  7006 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 14:17:29.412  7006  7006 D AppUp4:CustFacade: isPhone : true
08-26 14:17:29.413  7006  7006 D AppUp4:CustModeStarterReceiver: begin check event
08-26 14:17:29.413  7006  7006 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 14:17:29.416  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:29.417  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 14:17:29.419  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 14:17:29.421  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:29.429  7053  7053 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 14:17:29.430  4285  7398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 14:17:29.443  4285  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:29.443  4285  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 14:17:29.458  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 14:17:29.458  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:29.458  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 14:17:29.458  3459  3459 D PhoneState: setPdpRejectCasuse : false
,08-26 14:17:29.465  7053  7401 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:29.468  6927  7407 W FormManager: Network not available. Please check & try again.
08-26 14:17:29.471  7081  7081 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 14:17:29.472  7081  7081 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 14:17:29.475  6927  7408 V FormManager: Network unavailable.
08-26 14:17:29.492  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:29
,08-26 14:17:29.493  6927  7408 V FormManager: Network unavailable.
08-26 14:17:29.495  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 14:17:29.495  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-26 14:17:29.496  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 14:17:29.496  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-26 14:17:29.496  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11428dad
08-26 14:17:29.497  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 14:17:29.497  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 14:17:29.497  7156  7156 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 14:17:29.500  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 14:17:29.500  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:29
08-26 14:17:30.370  1035  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:30.376  1035  1769 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 14:17:30.393  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 14:17:30.393  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 14:17:30.393  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-26 14:17:30.397  1035  1117 D BluetoothManagerService: Message: 1
08-26 14:17:30.397  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 14:17:30.428  1035  1117 D BluetoothManagerService: Message: 20
08-26 14:17:30.428  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d665305:true
,08-26 14:17:30.433  6946  6946 D BluetoothAdapterState: make
08-26 14:17:30.437  6946  6946 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 14:17:30.438  6946  6946 I bluedroid-qcom: init
08-26 14:17:30.439  6946  7426 I BluetoothAdapterState: Entering OffState
08-26 14:17:30.439  6946  6946 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 14:17:30.440  6946  6946 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 14:17:30.440  6946  6946 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 14:17:30.440  6946  6946 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 14:17:30.440  6946  6946 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 14:17:30.442  6946  6946 I bluedroid-qcom: get_profile_interface socket
08-26 14:17:30.442  6946  6946 I bluedroid-qcom: get_profile_interface map_client
,08-26 14:17:30.446  6946  7430 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 14:17:30.450  6946  7430 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 14:17:30.445  7429  7429 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:30.445  7429  7429 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:30.460  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-26 14:17:30.462  1035  1117 D BluetoothManagerService: Message: 40
08-26 14:17:30.463  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 14:17:30.466  7429  7429 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 14:17:30.466  7429  7429 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 14:17:30.466  7429  7429 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 14:17:30.467  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 14:17:30.468  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 14:17:30.468  6946  6961 I bluedroid-qcom: config_hci_snoop_log
08-26 14:17:30.470  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 14:17:30.470  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 14:17:30.471  7429  7429 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 14:17:30.476  7429  7429 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 14:17:30.476  7429  7429 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-26 14:17:30.483  6946  7426 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 14:17:30.483  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.494  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:30.497  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.506  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-26 14:17:30.506  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-26 14:17:30.509  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:30.510  6946  7430 D BluetoothAdapterProperties: Name is: G3
08-26 14:17:30.511  6946  7426 D BluetoothAdapterProperties: Setting state to 11
08-26 14:17:30.511  6946  7426 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 14:17:30.512  1035  1117 D BluetoothManagerService: Message: 60
08-26 14:17:30.512  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 14:17:30.512  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 14:17:30.513  6946  7426 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 14:17:30.519  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:30.522  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:30.524  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:30.525  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-26 14:17:30.534  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:30.537  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:30.549  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 14:17:30.553  6946  7426 D BluetoothBondStateMachine: make
,08-26 14:17:30.558  1035  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.559  6946  7446 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 14:17:30.559  6946  7426 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.559  6946  7426 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 14:17:30.559  6946  7426 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.560  6946  7426 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 14:17:30.560  6946  7426 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 14:17:30.562  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 14:17:30.565  6946  6946 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 14:17:30.565  6392  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 14:17:30.565  6946  6946 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:30.566  6946  6946 V BluetoothPbapReceiver: ***********state = 11
08-26 14:17:30.566  6946  7426 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 14:17:30.573  5752  5752 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 14:17:30.578  6946  6946 D HeadsetService: Received start request. Starting profile...
08-26 14:17:30.579  6946  6946 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 14:17:30.579  6946  6946 D LGBluetoothHfpAdapter: Version 1.6
08-26 14:17:30.582  6946  6946 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 14:17:30.582  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:30.583  6946  7426 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:30.584  6946  6946 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 14:17:30.584  6946  6946 D HeadsetStateMachine: make
,08-26 14:17:30.628  6946  6946 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:30.628  6946  6946 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 14:17:30.632  1035  1934 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7451 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 14:17:30.635  1035  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.636  6946  6946 D HeadsetStateMachine: max_hf_connections = 1
08-26 14:17:30.636  6946  6946 I bluedroid-qcom: get_profile_interface handsfree
08-26 14:17:30.638  5752  5752 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 14:17:30.639  6946  6946 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 14:17:30.639  6946  7426 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:30.640  1035  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:30.640  1035  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:30.640   321  1380 V AudioPolicyService: registerClient() client 0xb04107a0, uid 1002
08-26 14:17:30.641   321  1715 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 14:17:30.641   321  1715 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 14:17:30.641   321  1715 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 14:17:30.641  6946  6946 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 14:17:30.641   321   321 V AudioFlinger: registerClient() client 0xb1433190, pid 6946
,08-26 14:17:30.642  6946  6946 V ToneGenerator: Create Track: 0xb4928a80
08-26 14:17:30.642  6946  6946 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 14:17:30.642  6946  6946 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 14:17:30.642   321  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:30.642   321  1376 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:30.642   321  1380 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 14:17:30.642   321  1380 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 14:17:30.642   321  1380 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 14:17:30.642   321  1380 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 14:17:30.643  1035  1988 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:30.643  1035  1988 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:30.643  1586  1923 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:30.643  1586  1923 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:30.643  1861  7210 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:30.643  1861  7210 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:30.644  3459  3478 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:30.644  3459  3478 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:30.644  6946  6946 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 14:17:30.644   321  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:30.644   321  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:30.644  6946  6962 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:30.644  6946  6962 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 14:17:30.644  1035  1714 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:30.644  1035  1714 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:30.644  1586  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:30.644  1586  1606 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:30.645  1861  1877 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:30.645  1861  1877 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:30.645  3459  3477 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:30.645  3459  3477 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:30.645   321  1380 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 14:17:30.646   321  1715 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 14:17:30.646  6946  6962 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:30.646   321  1715 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 14:17:30.646  6946  6962 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 14:17:30.646   321  1715 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 14:17:30.646   321  1715 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 14:17:30.646  6946  6946 V AudioSystem: getLatency() output 2, latency 50
08-26 14:17:30.646  6946  6946 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 14:17:30.646  6946  6946 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 14:17:30.646  6946  7426 E BluetoothAdapterService: File transfer profiles supported!!
08-,26 14:17:30.646   321  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 14:17:30.647   321  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 14:17:30.647   321  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 14:17:30.647   321  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 14:17:30.647   321  1381 V AudioFlinger: createTrack() lSessionId: 20
08-26 14:17:30.648  6946  6946 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 14:17:30.648   321  1715 V AudioFlinger: acquiring 20 from 6946, for 6946
08-26 14:17:30.648   321  1715 V AudioFlinger:  added new entry for 20
08-26 14:17:30.648  6946  6946 V ToneGenerator: ToneGenerator INIT OK, time: 127221
08-26 14:17:30.648  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.649  6946  7448 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 14:17:30.649  6946  7448 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 14:17:30.649  6946  7448 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 14:17:30.649  6946  7448 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 14:17:30.649   321  1381 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6946
08-26 14:17:30.650   321  1381 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 14:17:30.650   321  1381 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 14:17:30.650   321  1381 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 14:17:30.650   321  1381 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 14:17:30.650   321  1381 V voice   : voice_set_parameters: exit with code(0)
08-26 14:17:30.650   321  1381 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 14:17:30.650   321  1381 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 14:17:30.650   321  1381 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 14:17:30.650   321  1381 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 14:17:30.650   321  1381 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 14:17:30.650   321  1381 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 14:17:30.650  6946  7448 V ToneGenerator: ToneGenerator destructor
08-26 14:17:30.650  6946  7448 V ToneGenerator: stopTone
08-26 14:17:30.650  6946  7448 V ToneGenerator: Delete Track: 0xb4928a80
08-26 14:17:30.651  6946  7448 V AudioTrack: ~AudioTrack, releasing session id from 6946 on behalf of 6946
08-26 14:17:30.651   321   321 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 14:17:30.651   321   321 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 14:17:30.651   321  1260 V AudioPolicyService: AudioCommandThread() waking up
08-26 14:17:30.651   321  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 14:17:30.651   321  1260 V AudioPolicyManager: releaseOutput() 2
08-26 14:17:30.651   321  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 14:17:30.651   321  1380 V AudioFlinger: releasing 20 from 6946 for 6946
08-26 14:17:30.651   321  1380 V AudioFlinger:  decremented refcount to 0
08-26 14:17:30.651   321  1380 V AudioFlinger: purging stale effects
08-26 14:17:30.651  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.651  6946  6946 D HeadsetStateMachine: Proxy object connected
08-26 14:17:30.652   321   321 V AudioFlinger: PlaybackThread::Track destructor
08-26 14:17:30.652   321   321 V AudioFlinger: remove,Client_l() pid 6946, calling pid 321
08-26 14:17:30.653  6946  6946 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 14:17:30.653  6946  6946 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 14:17:30.658  1035  1770 W Process : Unable to open /proc/7464/status
08-26 14:17:30.659  6946  7426 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:30.661  6946  6946 D A2dpService: Received start request. Starting profile...
08-26 14:17:30.662  6946  6946 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 14:17:30.663  6946  6946 V Avrcp   : make
08-26 14:17:30.663  6946  6946 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 14:17:30.663  6946  6946 I bluedroid-qcom: get_profile_interface avrcp
08-26 14:17:30.670  6946  7426 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:30.674  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.677  6946  6946 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 14:17:30.678  6946  6946 E AudioManager: No RCC entry present to update
08-26 14:17:30.678  6946  6946 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 14:17:30.680  6946  7426 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 14:17:30.682  6946  6946 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 14:17:30.683  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 14:17:30.683  6946  6946 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 14:17:30.687  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 14:17:30.688  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.688  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 14:17:30.688  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 14:17:30.688  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 14:17:30.689  7006  7006 I AppUp4:CustModeStarterReceiver: onReceive
08-26 14:17:30.694  6946  7426 V LGMDMManager: Create singleton instance
08-26 14:17:30.696  6946  7426 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 14:17:30.699  7006  7006 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1b0d61d7
08-26 14:17:30.699  7006  7006 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 14:17:30.699  7006  7006 D AppUp4:CustFacade: isPhone : true
08-26 14:17:30.738  7006  7006 D AppUp4:CustModeStarterReceiver: begin check event
08-26 14:17:30.739  7006  7006 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-26 14:17:30.747  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.748  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 14:17:30.753  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:30.758  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:30.775  7053  7053 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 14:17:30.776  4285  7472 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 14:17:30.782  4285  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.782  4285  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 14:17:30.802  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 14:17:30.803  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.803  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 14:17:30.803  7451  7451 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-26 14:17:30.804  7451  7451 W LG Account v2.2: No ProfileInfo entries
08-26 14:17:30.804  7451  7451 I LG Account v2.2: isEnabled: false
08-26 14:17:30.804  7451  7451 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 14:17:30.804  7451  7451 I Feature : [Lifetracker]Country: EU
08-26 14:17:30.804  7451  7451 I Feature : [Lifetracker]Operator: OPEN
08-26 14:17:30.804  7451  7451 I Feature : [Lifetracker]Ranking support: false
08-26 14:17:30.805  7451  7451 I Feature : [Lifetracker]Comfort support: false
08-26 14:17:30.805  7451  7451 I Feature : [Lifetracker]Accessory: true
08-26 14:17:30.805  7451  7451 I Feature : [Lifetracker]Health device: true
08-26 14:17:30.805  7451  7451 I Feature : [Lifetracker]Extra Pedometer: false
08-26 14:17:30.805  7451  7451 I Feature : [Lifetracker]Blood glucose device: false
08-26 14:17:30.805  7451  7451 I Feature : [Lifetracker]Device Number: 3
08-26 14:17:30.807  7081  7081 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 14:17:30.807  7081  7081 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 14:17:30.807  7053  7476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:30.814  6927  7479 W FormManager: Network not available. Please check & try again.
08-26 14:17:30.819  6927  7480 V FormManager: Network unavailable.
,08-26 14:17:30.824  6927  7480 V FormManager: Network unavailable.
08-26 14:17:30.825  6837  6837 D BluetoothPermissionRequest: onReceive
08-26 14:17:30.828  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:30
08-26 14:17:30.829  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 14:17:30.829  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-26 14:17:30.830  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 14:17:30.830  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-26 14:17:30.830  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11428dad
08-26 14:17:30.831  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 14:17:30.831  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 14:17:30.831  7156  7156 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 14:17:30.831  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 14:17:30.831  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:30
,08-26 14:17:30.833  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 14:17:30.836  1035  2051 V SIM_STK : Menu title from STK is T-Mobile
08-26 14:17:30.836  1035  2051 V SIM_STK : Menu title from STK is T-Mobile
08-26 14:17:30.856  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 14:17:30.857  6392  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 14:17:30.869  2227  2227 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:30.877  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 14:17:30.877  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.877  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 14:17:30.877  7006  7006 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 14:17:30.879  7006  7006 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 14:17:30.881  7006  7006 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1b0d61d7
08-26 14:17:30.881  7006  7006 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 14:17:30.881  7006  7006 D AppUp4:CustFacade: isPhone : true
08-26 14:17:30.881  7006  7006 D AppUp4:CustModeStarterReceiver: begin check event
08-26 14:17:30.882  7006  7006 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 14:17:30.885  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.885  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 14:17:30.886  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:30.888  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 14:17:30.893  7053  7053 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 14:17:30.895  4285  7481 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 14:17:30.900  4285  7482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.900  4285  7482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 14:17:30.909  7053  7483 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:30.912  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 14:17:30.912  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:30.912  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 14:17:30.915  7081  7081 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 14:17:30.915  7081  7081 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 14:17:30.921  6927  7486 V FormManager: Network unavailable.
,08-26 14:17:30.925  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:30
08-26 14:17:30.926  1035  1952 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 14:17:30.926  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 14:17:30.926  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-26 14:17:30.927  6927  7485 W FormManager: Network not available. Please check & try again.
08-26 14:17:30.927  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 14:17:30.927  6927  7486 V FormManager: Network unavailable.
08-26 14:17:30.927  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-26 14:17:30.927  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11428dad
08-26 14:17:30.928  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 14:17:30.928  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 14:17:30.928  7156  7156 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 14:17:30.928  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 14:17:30.929  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:30
08-26 14:17:30.932  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 14:17:30.937  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 14:17:30.938  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 14:17:30.938  6946  6946 I BluetoothA2dpServiceJni: classInitNative
08-26 14:17:30.939  6946  6946 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 14:17:30.939  6946  6946 D A2dpStateMachine: make
08-26 14:17:30.940  6946  6946 I bluedroid-qcom: get_profile_interface a2dp
08-26 14:17:30.940  6946  7489 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 14:17:30.942  6946  6946 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 14:17:30.942  6946  6946 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 14:17:30.943  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.943  6946  7488 D A2dpStateMachine: Enter Disconnected: -2
08-26 14:17:30.944  6946  6946 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 14:17:30.945  6946  6946 D HidService: Received start request. Starting profile...
08-26 14:17:30.945  6946  6946 I bluedroid-qcom: get_profile_interface hidhost
08-26 14:17:30.945  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.946  6946  6946 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 14:17:30.950  6946  6946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 14:17:30.950  6946  6946 D HealthService: Received start request. Starting profile...
08-26 14:17:30.951  6946  6946 I bluedroid-qcom: get_profile_interface health
08-26 14:17:30.951  6946  6946 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 14:17:30.951  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.952  6946  6946 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 14:17:30.953  6946  7448 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 14:17:30.953  6946  7448 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 14:17:30.954  6946  6946 D PanService: Received start request. Starting profile...
08-26 14:17:30.954  6946  7448 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 14:17:30.954  6946  6946 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 14:17:30.954  6946  6946 I bluedroid-qcom: get_profile_interface pan
08-26 14:17:30.958  6946  6946 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 14:17:30.959  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.959  6946  6946 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-26 14:17:30.963  6946  6946 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 14:17:30.964  6946  6946 D BtGatt.GattService: Received start request. Starting profile...
08-26 14:17:30.964  6946  6946 D BtGatt.GattService: start()
08-26 14:17:30.964  6946  6946 I bluedroid-qcom: get_profile_interface gatt
08-26 14:17:30.964  6946  6946 D BtGatt.AdvertiseManager: advertise manager created
08-26 14:17:30.969  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.970  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.970  6946  6946 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 14:17:30.971  6946  6946 V BluetoothMapService: BluetoothMapBinder()
,08-26 14:17:30.971  6946  6946 D BluetoothMapService: Received start request. Starting profile...
08-26 14:17:30.971  6946  6946 D BluetoothMapService: start()
08-26 14:17:30.974  6946  6946 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 14:17:30.974  6946  6946 D BluetoothMapEmailAppObserver: createReceiver()
08-26 14:17:30.975  6946  6946 D BluetoothMapEmailAppObserver: initObservers()
08-26 14:17:30.975  6946  6946 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 14:17:30.981  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:30.984  6946  6946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 14:17:30.986  6946  6946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 14:17:30.989  6946  6946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 14:17:30.989  6946  6946 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 14:17:30.991  6946  6946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 14:17:30.993  6946  6946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 14:17:30.993  6946  6946 V BluetoothMapService: Handler(): got msg=1
08-26 14:17:30.994  6946  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 14:17:30.994  6946  7426 I bluedroid-qcom: enable
08-26 14:17:30.994  6946  7426 I bt_hci_bdroid: init
08-26 14:17:30.996  6946  7426 I bt_vendor: bt-vendor : init
08-26 14:17:30.996  6946  7426 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 14:17:30.996  6946  7426 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 14:17:30.996  6946  7426 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 14:17:30.996  6946  7426 D bt_userial_mct: userial_init
08-26 14:17:30.996  6946  7496 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 14:17:30.996  6946  7426 D bt_hci_bdroid: set_power 1
08-26 14:17:30.996  6946  7426 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 14:17:30.996  6946  7426 I bt_vendor: Starting hciattach daemon
08-26 14:17:30.996  6946  7426 I bt_vendor: try to set true
08-26 14:17:30.996  6946  7496 I bt-btu  : btu_task pending for preload complete event
08-26 14:17:30.997  6946  6946 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:30.998  6946  6946 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-26 14:17:30.998  6946  6946 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 14:17:30.998  6946  6946 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 14:17:30.999  6946  6946 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:30.999  6946  6946 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 14:17:30.995  7499  7499 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:30.995  7499  7499 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:31.021  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 14:17:31.145  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 14:17:31.168  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 14:17:31.208  7512  7512 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 14:17:31.221  7513  7513 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-26 14:17:31.250  7514  7514 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 14:17:31.266  7518  7518 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 14:17:31.289  7520  7520 I libmdmdetect: ESOC framework not supported
08-26 14:17:31.289  7520  7520 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 14:17:31.299  7520  7520 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 14:17:31.299  7520  7520 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 14:17:31.299  7520  7520 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 14:17:31.299  7520  7520 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 14:17:31.299  7520  7520 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 14:17:31.299  7520  7520 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 14:17:31.299  7520  7520 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 14:17:31.333  7520  7521 E QC-QMI  : qmi_client [7520] 14: failed to locate client data
,08-26 14:17:31.336   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 14:17:31.336   478   478 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-26 14:17:31.366  7522  7522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 14:17:31.389  7523  7523 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 14:17:31.416  1035  1109 W ProcessCpuTracker: Skipping unknown process pid 7499
08-26 14:17:31.417  1035  1109 W ProcessCpuTracker: Skipping unknown process pid 7523
,08-26 14:17:31.448  6946  7426 I bt_vendor: bluetooth satus is on
08-26 14:17:31.448  6946  7426 D bt_hci_bdroid: preload
08-26 14:17:31.448  6946  7498 D bt_userial_mct: userial_open(port:0)
,08-26 14:17:31.448  6946  7498 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 14:17:31.452  6946  7498 I bt_vendor: Done intiailizing UART
08-26 14:17:31.453  6946  7498 I bt_vendor: Done intiailizing UART
08-26 14:17:31.453  6946  7498 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 14:17:31.453  6946  7498 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 14:17:31.453  6946  7496 I bt-btu  : btu_task received preload complete event
08-26 14:17:31.453  6946  7525 D bt_userial_mct: Entering userial_read_thread()
08-26 14:17:31.454  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 14:17:31.454  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 14:17:31.459  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 14:17:31.469  6946  7496 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 14:17:31.470  6946  7496 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 14:17:31.470  6946  7496 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 14:17:31.534  6946  7496 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 14:17:31.535  6946  7496 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0217061 
08-26 14:17:31.535  6946  7496 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0217061 
,08-26 14:17:31.586  6946  7430 E bt-btif : Calling BTA_HhEnable
,08-26 14:17:31.586  6946  7430 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 14:17:31.587  6946  7430 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 14:17:31.587  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-26 14:17:31.587  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 14:17:31.587  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 14:17:31.587  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-26 14:17:31.588  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 14:17:31.589  6946  7430 D BluetoothAdapterProperties: Name is: G3
,08-26 14:17:31.590  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 14:17:31.591  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 14:17:31.592  6946  7430 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:31.593  6946  7430 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 14:17:31.593  6946  7430 D bt_hci_bdroid: postload
,08-26 14:17:31.594  6946  7498 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 14:17:31.596  6946  7430 D bte_conf: Device ID record 1 : primary
08-26 14:17:31.596  6946  7430 D bte_conf:   vendorId            = 00c4
08-26 14:17:31.597  6946  7430 D bte_conf:   vendorIdSource      = 0001
08-26 14:17:31.597  6946  7430 D bte_conf:   product             = 13a1
08-26 14:17:31.597  6946  7430 D bte_conf:   version             = 1000
08-26 14:17:31.597  6946  7430 D bte_conf:   clientExecutableURL = 
08-26 14:17:31.597  6946  7430 D bte_conf:   serviceDescription  = 
08-26 14:17:31.597  6946  7430 D bte_conf:   documentationURL    = 
08-26 14:17:31.597  6946  7430 D bte_conf: bte_load_did_conf no section named DID2.
08-26 14:17:31.598  6946  7498 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 14:17:31.602  6946  7498 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 14:17:31.595  7527  7527 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:31.595  7527  7527 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:31.608  6946  7525 E bt_mct  : hci lib postload completed
08-26 14:17:31.619  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:31.623  6946  7496 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 14:17:31.623  6946  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 14:17:31.623  6946  7426 D BluetoothAdapterProperties: ScanMode =  20
08-26 14:17:31.623  6946  7426 D BluetoothAdapterProperties: State =  11
08-26 14:17:31.623  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:31.624  6946  7426 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 14:17:31.624  6946  7426 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 14:17:31.624  6946  7426 D BluetoothAdapterProperties: Setting state to 12
08-26 14:17:31.624  6946  7426 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 14:17:31.624  6946  7430 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 14:17:31.625  6946  7430 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 14:17:31.626  1035  1117 D BluetoothManagerService: Message: 60
08-26 14:17:31.626  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 14:17:31.627  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 14:17:31.628  6946  7426 I BluetoothAdapterState: Entering On State
08-26 14:17:31.631  6946  7426 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 14:17:31.631  6946  7426 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 14:17:31.632  6946  7426 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 14:17:31.632  6946  7426 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-26 14:17:31.634  1861  7210 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:31.640  6946  7496 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:31.640  6946  7496 W bt-smp  : Plain text(LSB ~ MSB) = 86 2f 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:31.640  6946  7496 W bt-smp  : Encrypted text(LSB ~ MSB) = f8 ee e9 7c 2a c2 64 ff 95 66 a2 af dd 02 d3 2e 
08-26 14:17:31.641  6946  7496 W bt-btm  : Stopping oneshot timer
08-26 14:17:31.652  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:31.654  6946  7430 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 14:17:31.654  6946  7430 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 14:17:31.658  6837  6926 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 14:17:31.661  1861  1877 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:31.663  6946  7496 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:31.663  6946  7496 W bt-smp  : Plain text(LSB ~ MSB) = 73 2a 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:31.663  6946  7496 W bt-smp  : Encrypted text(LSB ~ MSB) = 41 46 5a 5b fc 35 7c cc e4 01 f2 c8 c7 92 f6 41 
08-26 14:17:31.663  6946  7496 W bt-btm  : Stopping oneshot timer
08-26 14:17:31.674  1861  1861 D BluetoothHeadset: Proxy object connected
,08-26 14:17:31.676  1035  1035 D BluetoothA2dp: Proxy object connected
,08-26 14:17:31.679  1861  1861 D BluetoothHeadset: Proxy object connected
08-26 14:17:31.679  6837  6853 D BluetoothPan: onBluetoothStateChange on: true
08-26 14:17:31.679  6837  6853 D BluetoothPan: onBluetoothStateChange call bindService
08-26 14:17:31.680  6946  7426 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 14:17:31.681  6837  6837 D BluetoothInputDevice: Proxy object connected
08-26 14:17:31.681  6837  6837 D HidProfile: Bluetooth service connected
08-26 14:17:31.683  6837  6926 D BluetoothMap: onBluetoothStateChange: up=true
08-26 14:17:31.685  7540  7540 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 14:17:31.685  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 14:17:31.687  1035  1035 D BluetoothHeadset: Proxy object connected
08-26 14:17:31.688  6837  6837 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 14:17:31.688  6837  6837 D PanProfile: Bluetooth service connected
08-26 14:17:31.688  1861  7210 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:31.688  6946  7496 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:31.688  6946  7496 W bt-smp  : Plain text(LSB ~ MSB) = 81 b3 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:31.688  6946  7496 W bt-smp  : Encrypted text(LSB ~ MSB) = 20 59 c9 6f de 69 37 07 8e f9 4e 3a ea d6 74 fb 
08-26 14:17:31.688  6946  7496 W bt-btm  : Stopping oneshot timer
08-26 14:17:31.692  1861  1861 D BluetoothHeadset: Proxy object connected
08-26 14:17:31.692  6837  6853 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 14:17:31.693  6837  6837 D BluetoothMap: Proxy object connected
08-26 14:17:31.693  6837  6837 D MapProfile: Bluetooth service connected
08-26 14:17:31.693  6837  6837 D BluetoothMap: getConnectedDevices()
08-26 14:17:31.694  6946  7466 V BluetoothMapService: getConnectedDevices()
08-26 14:17:31.695  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 14:17:31.695  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 14:17:31.696  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 14:17:31.696  1035  1117 D BluetoothManagerService: Message: 40
08-26 14:17:31.696  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 14:17:31.696  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.697  1953  2141 D LGBluetoothAPIService: Message: 1
08-26 14:17:31.697  1953  2141 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 14:17:31.697  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 14:17:31.700  6946  7496 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:31.700  6946  7496 W bt-smp  : Plain text(LSB ~ MSB) = f3 33 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:31.700  6946  7496 W bt-smp  : Encrypted text(LSB ~ MSB) = 32 11 0e aa 99 42 35 50 b3 48 fc 1b 1b 75 0e 2a 
08-26 14:17:31.700  6946  7496 W bt-btm  : Stopping oneshot timer
,08-26 14:17:31.708  1953  2141 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 14:17:31.709  6586  6586 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 14:17:31.710  6946  6946 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.710  6946  6946 D BluetoothMapService: STATE_ON
08-26 14:17:31.711  6837  6837 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 14:17:31.712  6946  6946 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 14:17:31.712  6946  6946 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 14:17:31.713  1953  1953 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 14:17:31.716  1035  1117 D BluetoothManagerService: Message: 30
08-26 14:17:31.716  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:31.716  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:31.716  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:31.716  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:31.716  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:31.716  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:31.716  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:31.716  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:31.717  1953  2141 D LGBluetoothAPIService: Message: 100
08-26 14:17:31.717  1953  2141 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-26 14:17:31.719  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:31.719  6837  6837 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 14:17:31.722  6946  7496 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:31.722  6946  7496 W bt-smp  : Plain text(LSB ~ MSB) = 48 d5 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:31.722  6946  7496 W bt-smp  : Encrypted text(LSB ~ MSB) = 3f 43 51 6b c1 a7 29 11 f4 14 9e 3d b6 9a e6 c4 
08-26 14:17:31.722  6946  7496 W bt-btm  : Stopping oneshot timer
08-26 14:17:31.724  7186  7223 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-26 14:17:31.725  1035  1117 D BluetoothManagerService: Message: 30
08-26 14:17:31.727  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:31.727  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:31.727  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:31.727  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:31.727  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:31.727  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:31.727  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:31.727  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:31.729  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:31.735  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:31.735  6946  6946 V BluetoothPbapService: Pbap Service onCreate
08-26 14:17:31.736  6946  6946 V BluetoothPbapService: Starting PBAP service
08-26 14:17:31.736  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 14:17:31.737  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 14:17:31.738  6946  6946 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 14:17:31.738  6946  6946 V BluetoothPbapService: Pbap Service onBind
08-26 14:17:31.742  6946  6946 V BluetoothMapService: Handler(): got msg=1
08-26 14:17:31.742  6837  6837 D BluetoothA2dp: Proxy object connected
08-26 14:17:31.742  6946  6946 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 14:17:31.743  6946  6946 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.743  6837  6837 D A2dpProfile: Bluetooth service connected
08-26 14:17:31.743  6946  6946 V BluetoothPbapService: state: 12
08-26 14:17:31.743  6946  6946 V BluetoothPbapService: Handler(): got msg=1
08-26 14:17:31.744  6946  6946 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 14:17:31.745  6837  6837 D BluetoothHeadset: Proxy object connected
08-26 14:17:31.745  6946  6946 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 14:17:31.745  6946  6946 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.745  6946  6946 V BluetoothPbapReceiver: ***********state = 12
08-26 14:17:31.746  6946  7547 V BluetoothPbapService: Pbap Service initSocket
08-26 14:17:31.746  6837  6837 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:31.747  6946  7546 D BluetoothMapMasInstance: MAS initSocket()
08-26 14:17:31.747  6946  7546 D BluetoothMapMasInstance:   masId = 00
08-26 14:17:31.747  6946  7546 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 14:17:31.747  6946  7546 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 14:17:31.747  6946  7546 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 14:17:31.749  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:31.749  1035  1931 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:31.749  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:31.750  2227  2227 D c       : Getting all permits...
08-26 14:17:31.750  2227  2227 D a       : Opening database...
08-26 14:17:31.751  6946  7547 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:31.752  6946  7547 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 14:17:31.752  6946  7547 V BluetoothPbapService: Succeed to create listening socket 
08-26 14:17:31.752  6946  7547 V BluetoothPbapService: Accepting socket connection...
08-26 14:17:31.753  6946  7430 D BluetoothAdapterProperties: Scan Mode:21
08-26 14:17:31.753  6946  7430 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 14:17:31.754  6946  7546 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:31.754  2227  2227 D a       : Opening database auth.proximity.permit_store...
08-26 14:17:31.754  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:31.755  2227  2227 D a       : Closing database...
08-26 14:17:31.757  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:31.757  6946  7546 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 14:17:31.757  6946  7546 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 14:17:31.758  6946  7546 D BluetoothMapMasInstance: Accepting socket connection...
,08-26 14:17:31.761  6837  6837 D DockEventReceiver: finishStartingService: stopping service
08-26 14:17:31.762  6837  6837 D BluetoothPbap: Proxy object connected
08-26 14:17:31.763  6837  6837 D PbapServerProfile: Bluetooth service connected
08-26 14:17:31.768  6837  6837 D BluetoothPermissionRequest: onReceive
,08-26 14:17:31.770  6837  6837 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 14:17:31.772  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 14:17:31.775  6946  6946 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 14:17:31.776  6946  6946 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 14:17:31.784  6946  6946 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 14:17:31.810  6946  6946 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 14:17:31.810  6946  6946 V BtOppService: onCreate
08-26 14:17:31.815  6946  6946 V BluetoothOppNotification: send message
08-26 14:17:31.821  6946  6946 V BtOppService: Starting RfcommListener
08-26 14:17:31.831  6946  6946 D BluetoothOppPreference: Dumping Names:  
08-26 14:17:31.831  6946  6946 D BluetoothOppPreference: {}
,08-26 14:17:31.832  6946  6946 D BluetoothOppPreference: Dumping Channels:  
08-26 14:17:31.832  6946  6946 D BluetoothOppPreference: {}
08-26 14:17:31.834  6946  6946 V BtOppService: onStartCommand
08-26 14:17:31.835  6946  7556 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 14:17:31.838  6946  7556 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 14:17:31.839  6946  7553 V BtOppService: Deleted complete outbound shares, number =  0
08-26 14:17:31.841  6946  6946 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.842  6946  7553 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 14:17:31.842  6946  6946 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 14:17:31.842  6946  7553 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 14:17:31.843  6946  7556 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@aed73e on behalf of 
,08-26 14:17:31.844  6946  7556 V BluetoothOppNotification: update too frequent, put in queue
08-26 14:17:31.844  6946  7553 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7fab99f on behalf of 
08-26 14:17:31.846  6946  7556 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 14:17:31.847  6946  7556 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 14:17:31.852  6946  7556 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a49aaec on behalf of 
08-26 14:17:31.853  6946  6946 V BluetoothOppNotification: new notify threadi!
08-26 14:17:31.854  6946  6946 V BluetoothOppNotification: send delay message
08-26 14:17:31.854  6946  7556 V BluetoothOppNotification: update too frequent, put in queue
08-26 14:17:31.854  6946  6946 V BtOppService: start RfcommListener
08-26 14:17:31.856  6946  7556 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-26 14:17:31.858  6946  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 14:17:31.859  6946  6946 V BtOppService: RfcommListener started
08-26 14:17:31.859  6946  6946 V BtOppService: ContentObserver received notification
08-26 14:17:31.862  6946  6946 V BtOppService: ContentObserver received notification
08-26 14:17:31.862  6946  7558 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 14:17:31.863  1035  1770 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:31.865  6946  7558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:31.865  6946  7559 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 14:17:31.865  6946  7559 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 14:17:31.868  6946  7559 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21f9deb5 on behalf of 
08-26 14:17:31.869  6946  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e3d294a on behalf of 
,08-26 14:17:31.870  6946  7558 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-26 14:17:31.870  6946  7558 V BtOppRfcommListener: Started RFCOMM listener....
08-26 14:17:31.870  6946  7558 I BtOppRfcommListener: Accept thread started.
08-26 14:17:31.870  6946  7558 V BtOppRfcommListener: Accepting connection...
08-26 14:17:31.873  6946  7557 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 14:17:31.874  6946  7559 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 14:17:31.875  6946  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 14:17:31.878  6946  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bdb50bb on behalf of 
08-26 14:17:31.879  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:31.880  6946  7557 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 14:17:31.880  6946  6946 V BluetoothFtpService: Ftp Service onCreate
08-26 14:17:31.880  6946  6946 I BluetoothFtpService: Ftp Service onCreate
08-26 14:17:31.880  6946  6946 V BluetoothFtpService: Ftp Service onStartCommand
08-26 14:17:31.880  6946  6946 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:31.880  6946  6946 V BluetoothFtpService: Starting Listening on sockets
08-26 14:17:31.881  6946  6946 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 14:17:31.881  6946  6946 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 14:17:31.881  6946  6946 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 14:17:31.881  6946  6946 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.881  6946  6946 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 14:17:31.881  6946  6946 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 14:17:31.883  6946  6946 V BluetoothFtpService: Handler(): got msg=1
08-26 14:17:31.884  6946  6946 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 14:17:31.885  6946  6946 V BluetoothFtpService: Ftp Service initSocket
08-26 14:17:31.885  6946  7557 V BluetoothOppNotification: outbound notification was removed.
08-26 14:17:31.885  6946  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 14:17:31.886  6946  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bb6b131 on behalf of 
08-26 14:17:31.887  6946  7557 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 14:17:31.888  6946  7557 V BluetoothOppNotification: inbound notification was removed.
08-26 14:17:31.889  6946  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 14:17:31.889  1035  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:31.890  6946  6946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:31.891  6946  6946 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-26 14:17:31.892  6946  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23ac9016 on behalf of 
08-26 14:17:31.893  6946  7560 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 14:17:31.907  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:31.907  6946  6946 V BluetoothSapService: Sap Service onCreate
,08-26 14:17:31.909  6946  6946 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.909  6946  6946 V BluetoothSapService: state: 12
08-26 14:17:31.909  6946  6946 V BluetoothSapService: Starting SAP server process
08-26 14:17:31.911  6946  6946 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 14:17:31.912  6946  7562 V BluetoothSapService: Sap Service initRfcommSocket
08-26 14:17:31.905  7561  7561 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:31.913  1035  1931 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:31.905  7561  7561 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:31.914  6946  7562 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:31.915  6946  7562 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 14:17:31.915  6946  7562 V BluetoothSapService: Succeed to create listening socket 
08-26 14:17:31.915  6946  7562 V BluetoothSapService: Accepting socket connection...
08-26 14:17:31.925  7561  7561 V BT_SAP  : Event pipe created
08-26 14:17:31.925  7561  7561 V BT_SAP  : create_server_socket qcom.sap.server
08-26 14:17:31.925  7561  7561 V BT_SAP  : created socket fd 6
,08-26 14:17:32.420  1035  1373 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:32.421  1035  1373 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:32.473  1035  1374 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 14:17:32.474  1035  1374 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 14:17:32.812  1035  2030 I ActivityManager: Killing 7355:com.lge.bnr/1000 (adj 15): empty #17
,08-26 14:17:32.843  1035  1769 W libprocessgroup: failed to open /acct/uid_1000/pid_7355/cgroup.procs: No such file or directory
,08-26 14:17:32.854  6946  6946 V BluetoothOppNotification: new notify threadi!
08-26 14:17:32.855  6946  6946 V BluetoothOppNotification: send delay message
08-26 14:17:32.856  6946  7572 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 14:17:32.860  6946  7572 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24d997a2 on behalf of 
08-26 14:17:32.860  6946  7572 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 14:17:32.862  6946  7572 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 14:17:32.863  6946  7572 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26251c33 on behalf of 
08-26 14:17:32.863  6946  7572 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 14:17:32.865  6946  7572 V BluetoothOppNotification: outbound notification was removed.
08-26 14:17:32.865  6946  7572 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 14:17:32.866  6946  7572 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ed6bbf0 on behalf of 
08-26 14:17:32.866  6946  7572 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 14:17:32.871  6946  7572 V BluetoothOppNotification: inbound notification was removed.
,08-26 14:17:32.871  6946  7572 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 14:17:32.874  6946  7572 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a515569 on behalf of 
,08-26 14:17:32.933  1035  2030 I ActivityManager: Killing 6700:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 14:17:32.965  6885  6885 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-26 14:17:32.965  6885  6885 W System.err: android.os.DeadObjectException
08-26 14:17:32.966  6885  6885 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 14:17:32.966  6885  6885 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-26 14:17:32.966  6885  6885 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 14:17:32.966  6885  6885 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 14:17:32.966  6885  6885 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 14:17:32.966  6885  6885 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 14:17:32.966  6885  6885 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:32.966  6885  6885 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:32.966  6885  6885 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:32.966  6885  6885 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:32.966  6885  6885 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:32.966  6885  6885 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:32.966  6885  6885 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:32.966  6885  6885 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:32.967  6885  6885 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 14:17:32.967  6885  6885 W System.err: android.os.DeadObjectException
,08-26 14:17:32.974  6885  6885 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 14:17:32.974  6885  6885 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 14:17:32.974  6885  6885 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 14:17:32.974  6885  6885 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 14:17:32.974  6885  6885 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 14:17:32.974  6885  6885 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 14:17:32.974  6885  6885 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:32.974  6885  6885 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:32.974  6885  6885 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:32.974  6885  6885 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:32.974  6885  6885 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:32.974  6885  6885 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:32.974  6885  6885 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:32.975  6885  6885 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:32.975  6885  6885 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 14:17:32.975  6885  6885 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 14:17:33.000  1035  1769 W libprocessgroup: failed to open /acct/uid_1000/pid_6700/cgroup.procs: No such file or directory
08-26 14:17:33.001  1035  1769 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 14:17:33.009  6885  6885 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 14:17:33.010  6885  6885 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 14:17:33.052  1035  1714 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7573 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 14:17:33.077  6885  6885 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 14:17:33.140  7573  7573 D UEI.SmartControl: Quickset Services start...
,08-26 14:17:33.145  7573  7573 I UEI.SmartControl: Manufacture = LGE
,08-26 14:17:33.145  7573  7573 D UEI.SmartControl: Id = LGNevo
,08-26 14:17:33.146  7573  7573 D UEI.SmartControl: File observer start...
08-26 14:17:33.148  7573  7573 E UEI.SmartControl: IR Port is disabled: false
,08-26 14:17:33.149  7573  7573 D UEI.SmartControl: Starting file observer...
08-26 14:17:33.149  7573  7573 D UEI.SmartControl: Extracting JNI libs...
,08-26 14:17:33.149  7573  7573 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-26 14:17:33.255  7573  7573 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-26 14:17:33.255  7573  7573 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-26 14:17:33.255  7573  7573 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 14:17:33.296  7573  7573 I UEI.SmartControl: --- Selecting new region: 6
,08-26 14:17:33.298  7573  7573 I UEI.SmartControl: Model = LG-D855
,08-26 14:17:33.301  7573  7573 D UEI.SmartControl: QS Service created
,08-26 14:17:33.317  7573  7573 I UEI.SmartControl: Service initServices...
,08-26 14:17:33.322  7573  7573 D UEI.SmartControl: QS start get config
,08-26 14:17:33.362  7573  7573 D UEI.SmartControl: Loading JNI Libs...
,08-26 14:17:33.411  1035  1770 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 14:17:33.411  1035  1770 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@17107a34 mBinding = false
,08-26 14:17:33.437  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 14:17:33.438  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 14:17:33.438  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 14:17:33.438  1035  1117 D BluetoothManagerService: Message: 2
08-26 14:17:33.439  1035  1117 D BluetoothManagerService: Sending off request.
08-26 14:17:33.439  6946  6962 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 14:17:33.440  6946  7426 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 14:17:33.440  6946  7426 D BluetoothAdapterProperties: Setting state to 13
08-26 14:17:33.440  6946  7426 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 14:17:33.440  1035  1117 D BluetoothManagerService: Message: 60
08-26 14:17:33.440  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 14:17:33.440  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 14:17:33.441  6946  7426 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 14:17:33.441  6946  7426 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 14:17:33.442  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 14:17:33.444  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.444  6946  6946 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.444  6946  6946 D BluetoothMapService: STATE_TURNING_OFF
08-26 14:17:33.445  6946  6946 V BtOppService: Receiver DISABLED_ACTION 
08-26 14:17:33.445  6946  6946 V BluetoothMapService: Handler(): got msg=4
08-26 14:17:33.445  6946  6946 D BluetoothMapService: MAP Service closeService in
08-26 14:17:33.445  6946  6946 D BluetoothMapMasInstance: MAP Service shutdown
,08-26 14:17:33.447  6946  7546 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 14:17:33.447  6946  7546 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:33.447  6946  7546 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 14:17:33.447  6946  7546 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 14:17:33.447  6946  7546 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 14:17:33.447  6946  7546 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 14:17:33.447  6946  7546 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 14:17:33.447  6946  7546 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 14:17:33.448  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:33.448  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:33.448  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:33.448  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:33.448  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:33.448  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:33.448  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:33.448  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:33.448  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:33.448  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:33.448  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:33.449  6946  6946 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 14:17:33.449  6946  6946 V BluetoothMapService: MAP Service closeService out
08-26 14:17:33.450  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:33.450  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:33.450  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:33.450  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:33.450  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:33.450  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:33.450  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:33.450  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:33.450  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:33.450  6946  6946 I BtOppRfcommListener: stopping Accept Thread
08-26 14:17:33.450  6946  6946 V BtOppRfcommListener: close mBtServerSocket
08-26 14:17:33.450  6946  7,558 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:33.451  6946  7558 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 14:17:33.451  6946  6946 V BtOppRfcommListener: waiting for thread to terminate
08-26 14:17:33.451  6946  6946 V BtOppRfcommListener: done waiting for thread to terminate
08-26 14:17:33.452  6586  6586 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:33.452  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:33.455  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-26 14:17:33.458  6946  7430 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:33.458  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 14:17:33.458  6946  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 14:17:33.459  6946  7426 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 14:17:33.460  6946  7547 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:33.461  6946  7562 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:33.462  6946  7560 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:33.462  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 14:17:33.463  6946  7496 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 14:17:33.466  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 14:17:33.466  6946  7496 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 14:17:33.472  6946  6946 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 14:17:33.472  6946  6946 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.472  6946  6946 V BluetoothPbapReceiver: ***********state = 13
,08-26 14:17:33.474  6946  6946 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 14:17:33.475  6946  6946 V BtOppService: onDestroy
08-26 14:17:33.476  6946  6946 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 14:17:33.476  6946  6946 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.476  6946  6946 V BluetoothPbapService: state: 13
08-26 14:17:33.476  6946  6946 V BluetoothPbapService: Pbap Service closeService in
08-26 14:17:33.477  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:33.478  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:33.479  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:33.481  6946  6946 V BluetoothPbapService: successfully stopped pbap service
08-26 14:17:33.481  6946  6946 V BluetoothPbapService: Pbap Service closeService out
08-26 14:17:33.481  6837  6837 D DockEventReceiver: finishStartingService: stopping service
08-26 14:17:33.481  6946  6946 V BluetoothPbapService: Pbap Service onDestroy
08-26 14:17:33.481  6946  6946 V BluetoothPbapService: Pbap Service closeService in
08-26 14:17:33.481  6946  6946 V BluetoothPbapService: Pbap Service closeService out
08-26 14:17:33.481  6946  6946 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 14:17:33.482  6837  6837 D BluetoothPbap: Proxy object disconnected
08-26 14:17:33.482  6837  6837 D PbapServerProfile: Bluetooth service disconnected
08-26 14:17:33.499  6837  6837 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 14:17:33.504  6837  6837 D BluetoothPermissionRequest: onReceive
08-26 14:17:33.504  6837  6837 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 14:17:33.509  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 14:17:33.510  6946  6946 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 14:17:33.510  6946  6946 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 14:17:33.511  6946  6946 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-26 14:17:33.518  6946  6946 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.518  6946  6946 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 14:17:33.519  6946  6946 V BluetoothFtpService: Ftp Service onStartCommand
08-26 14:17:33.519  6946  6946 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.519  6946  6946 V BluetoothFtpService: Ftp Service closeService
08-26 14:17:33.519  6946  6946 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 14:17:33.519  6946  6946 V BluetoothFtpService: successfully stopped ftp service
08-26 14:17:33.520  6946  6946 V BluetoothFtpService: Ftp Service onDestroy
08-26 14:17:33.520  6946  6946 V BluetoothFtpService: Ftp Service closeService
08-26 14:17:33.522  6946  6946 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 14:17:33.522  6946  6946 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 14:17:33.522  6946  6946 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 14:17:33.522  6946  6946 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.522  6946  6946 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 14:17:33.522  6946  6946 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 14:17:33.523  6946  6946 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.523  6946  6946 V BluetoothSapService: state: 13
08-26 14:17:33.523  6946  6946 V BluetoothSapService: Stopping SAP server process
,08-26 14:17:33.525  6946  6946 V BluetoothSapService: Sap Service closeSapService in
08-26 14:17:33.525  6946  6946 V BluetoothSapService: Close listen Socket : 
08-26 14:17:33.525  6946  6946 V BluetoothSapService: Close rfcomm Socket : 
08-26 14:17:33.525  6946  6946 V BluetoothSapService: Close sapd  Socket : 
08-26 14:17:33.527  6946  6946 V BluetoothSapService: Sap Service closeSapService out
08-26 14:17:33.528  6946  6946 V BluetoothSapService: Sap Service onDestroy
08-26 14:17:33.528  6946  6946 V BluetoothSapService: Sap Service closeSapService in
08-26 14:17:33.528  6946  6946 V BluetoothSapService: Close listen Socket : 
08-26 14:17:33.528  6946  6946 V BluetoothSapService: Close rfcomm Socket : 
08-26 14:17:33.528  6946  6946 V BluetoothSapService: Close sapd  Socket : 
08-26 14:17:33.529  6946  6946 V BluetoothSapService: Sap Service closeSapService out
08-26 14:17:33.707  7573  7573 I UEI.SmartControl: Supports setup maps: true
,08-26 14:17:33.711  7573  7573 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 14:17:33.711  7573  7573 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 14:17:33.711  7573  7573 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 14:17:33.711  7573  7573 I UEI.SmartControl: ### init IR Blaster...
08-26 14:17:33.717  7573  7573 D serial_port: Configuring serial port
08-26 14:17:33.721  7573  7573 E UEI.SmartControl: UEIBLaster setting for 616
08-26 14:17:33.721  7573  7573 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 14:17:33.722  7573  7573 I UEI.SmartControl: configuring settings for MAXQ616
08-26 14:17:33.722  7573  7573 I UEI.SmartControl: Get version...
08-26 14:17:33.739  7573  7610 D UEI.SmartControl: serial port data available: 21
,08-26 14:17:33.769  7573  7573 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 14:17:33.769  7573  7573 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-26 14:17:33.770  7573  7573 I UEI.SmartControl: QS saving settings...
,08-26 14:17:33.772  7573  7573 D UEI.SmartControl: IR Blaster version: 25672567
08-26 14:17:33.790  7573  7610 D UEI.SmartControl: serial port data available: 4
,08-26 14:17:33.832  7573  7613 I UEI.SmartControl: Device manager: loading config....
,08-26 14:17:33.833  7573  7613 D UEI.SmartControl: ----------- loading internal config...
,08-26 14:17:33.838  7573  7573 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 14:17:33.861  7573  7613 E UEI.SmartControl: Loading SETTINGS...
,08-26 14:17:33.874  7573  7613 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 14:17:33.889  7573  7612 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 14:17:33.889  7573  7612 D UEI.SmartControl: -----service ready thread exits
,08-26 14:17:34.011  1035  1934 I art     : Explicit concurrent mark sweep GC freed 72242(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.616ms total 164.052ms
,08-26 14:17:34.011  7573  7573 E UEI.SmartControl: Services init done
,08-26 14:17:34.011  7573  7573 D UEI.SmartControl: QS Service init finished
08-26 14:17:34.012  7573  7573 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 14:17:34.012  7573  7573 D UEI.SmartControl: QS Service version code: 201091
08-26 14:17:34.012  7573  7573 D UEI.SmartControl: Service requested: Control
08-26 14:17:34.017  6885  6885 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 14:17:34.018  7573  7589 I UEI.SmartControl: ------ IControl API: 11
08-26 14:17:34.020  7573  7589 I UEI.SmartControl: Registering callback...
08-26 14:17:34.020  1035  1583 I ActivityManager: Killing 6885:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 14:17:34.052  1035  1769 W libprocessgroup: failed to open /acct/uid_10112/pid_6885/cgroup.procs: No such file or directory
,08-26 14:17:34.052  7573  7573 D UEI.SmartControl: Internal service binding...
,08-26 14:17:34.370  6946  7430 D bt_hci_bdroid: cleanup
,08-26 14:17:34.379  6946  7498 I bt_lpm  : LPM is already off!!!
08-26 14:17:34.379  6946  7525 I bt_userial_mct: exiting userial_read_thread
08-26 14:17:34.379  6946  7525 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 14:17:34.380  6946  7496 W bt-btif : ag scb idx 1 not allocated
08-26 14:17:34.381  6946  7496 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:34.381  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 14:17:34.382  6946  7496 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:34.382  6946  7496 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 14:17:34.382  6946  7496 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:34.382  6946  7496 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 14:17:34.385  6946  7430 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 14:17:34.385  6946  7498 I bt_vendor: hw_epilog_process
08-26 14:17:34.386  6946  7430 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 14:17:34.386  6946  7430 D bt_userial_mct: userial_close
08-26 14:17:34.386  6946  7430 E bt_userial_mct: pthread_join() FAILED result:3
08-26 14:17:34.386  6946  7430 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 14:17:34.398  6946  7430 D bt_hci_bdroid: set_power 0
08-26 14:17:34.398  6946  7430 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 14:17:34.399  6946  7430 I bt_vendor: bluetooth satus is on
08-26 14:17:34.399  6946  7430 I bt_vendor: bt-vendor : resetting BT status
08-26 14:17:34.399  6946  7430 I bt_vendor: Starting hciattach daemon
08-26 14:17:34.399  6946  7430 I bt_vendor: try to set false
08-26 14:17:34.401  6946  7430 I bt_vendor: Starting hciattach daemon
08-26 14:17:34.402  6946  7430 I bt_vendor: try to set false
,08-26 14:17:34.404  6946  7430 I bt_vendor: cleanup
08-26 14:17:34.405  6946  7496 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 14:17:34.405  6946  7430 I GKI_LINUX: GKI_exit_task 0 done
08-26 14:17:34.406  6946  7430 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 14:17:34.410  6946  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 14:17:34.417  6946  7426 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-26 14:17:34.421  6946  6946 D HeadsetService: Received stop request...Stopping profile...
08-26 14:17:34.422  6946  6946 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 14:17:34.422  6946  6946 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:34.422  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:34.423  6946  7448 D HeadsetStateMachine: Exit Disconnected: -1
08-26 14:17:34.425  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:34.425  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 14:17:34.426  1861  1861 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:34.426  1861  1861 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:34.426  1861  1861 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:34.428  6946  6946 D A2dpService: Received stop request...Stopping profile...
08-26 14:17:34.428  6946  7488 D A2dpStateMachine: Exit Disconnected: -1
08-26 14:17:34.429  6946  6946 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-26 14:17:34.434  6946  6946 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 14:17:34.434  6946  6946 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:34.434  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:34.436  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:34.436  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 14:17:34.437  6946  6946 D HidService: Received stop request...Stopping profile...
08-26 14:17:34.438  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:34.440  6946  6946 D HealthService: Received stop request...Stopping profile...
08-26 14:17:34.440  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:34.442  6946  6946 D PanService: Received stop request...Stopping profile...
,08-26 14:17:34.445  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:34.449  6946  6946 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 14:17:34.449  6946  6946 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 14:17:34.449  6946  6946 D BtGatt.GattService: stop()
08-26 14:17:34.449  6946  6946 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 14:17:34.450  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:34.452  6946  6946 D BluetoothMapService: Received stop request...Stopping profile...
08-26 14:17:34.452  6946  6946 D BluetoothMapService: stop()
08-26 14:17:34.452  6946  6946 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 14:17:34.452  6946  6946 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 14:17:34.453  6946  6946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:34.454  6946  6946 V BluetoothMapService: Handler(): got msg=4
08-26 14:17:34.454  6946  6946 D BluetoothMapService: MAP Service closeService in
08-26 14:17:34.454  6946  6946 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 14:17:34.454  6946  6946 V BluetoothMapService: MAP Service closeService out
,08-26 14:17:34.457  6946  7426 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 14:17:34.458  6946  7426 D BluetoothAdapterProperties: Setting state to 10
08-26 14:17:34.458  6946  7426 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 14:17:34.459  1035  1117 D BluetoothManagerService: Message: 60
08-26 14:17:34.459  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 14:17:34.459  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 14:17:34.459  6946  7426 I BluetoothAdapterState: Entering OffState
08-26 14:17:34.460  1861  7210 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:34.460  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:34.461  6837  6853 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 14:17:34.461  1861  1876 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:34.462  6837  6852 D BluetoothPan: onBluetoothStateChange on: false
08-26 14:17:34.462  6837  6853 D BluetoothMap: onBluetoothStateChange: up=false
08-26 14:17:34.463  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:34.463  6837  6852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:34.465  1861  1877 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:34.465  6946  6946 D HeadsetStateMachine: Unbinding service...
08-26 14:17:34.466  6946  6946 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 14:17:34.466  6946  6946 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 14:17:34.466  6946  6946 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 14:17:34.466  6946  6946 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 14:17:34.466  6946  6946 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 14:17:34.466  6946  6946 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:34.466  6946  6946 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-26 14:17:34.472  6837  6853 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:34.475  6946  6946 I BluetoothA2dpServiceJni: cleanupNative
08-26 14:17:34.475  6946  7489 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 14:17:34.475  6946  6946 I GKI_LINUX: GKI_exit_task 2 done
08-26 14:17:34.475  6946  6946 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 14:17:34.476  6837  6852 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 14:17:34.477  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 14:17:34.477  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 14:17:34.479  6946  6946 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 14:17:34.479  6946  6946 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 14:17:34.482  6946  6946 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 14:17:34.482  6946  6946 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 14:17:34.482  6946  6946 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 14:17:34.484  6946  6946 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 14:17:34.484  6946  6946 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 14:17:34.487  6946  6946 D BluetoothMapService: cleanup()
08-26 14:17:34.487  6946  6946 D BluetoothMapService: MAP Service closeService in
08-26 14:17:34.487  6946  6946 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 14:17:34.487  6946  6946 V BluetoothMapService: MAP Service closeService out
08-26 14:17:34.489  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 14:17:34.489  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 14:17:34.489  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@17107a34 mBinding = false
08-26 14:17:34.490  1035  1117 D BluetoothManagerService: Sending unbind request.
08-26 14:17:34.494  6946  7430 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 14:17:34.496  6946  6946 I GKI_LINUX: GKI_exit_task 1 done
08-26 14:17:34.496  6946  6946 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 14:17:34.497  6946  6946 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 14:17:34.498  6946  6946 I art     : --- WEIRD: removing null entry 248
08-26 14:17:34.499  6946  6946 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 14:17:34.499  6946  6946 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 14:17:34.499  6946  6946 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 14:17:34.501  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 14:17:34.504  6946  6946 I art     : System.exit called, status: 0
08-26 14:17:34.504  6946  6946 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 14:17:34.510  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:34.514  1953  2141 D LGBluetoothAPIService: Message: 2
08-26 14:17:34.514  1953  2141 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@20082614 mBinding = false
08-26 14:17:34.514  1953  2141 D LGBluetoothAPIService: Sending unbind request.
08-26 14:17:34.515  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:34.516  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:34.516  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 14:17:34.518  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 14:17:34.518  6837  6837 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 14:17:34.529  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 14:17:34.555  1586  1586 D BluetoothAdapter: 955810222: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:34.555  1586  1586 D BluetoothAdapter: 955810222: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:34.560   321  1380 V AudioFlinger: 6946 died, releasing its sessions
08-26 14:17:34.560   321  1380 V AudioFlinger:  pid 1861 @ 0
08-26 14:17:34.560   321  1380 V AudioFlinger:  pid 3459 @ 1
08-26 14:17:34.561   321  1380 V AudioFlinger:  pid 3459 @ 2
08-26 14:17:34.656  1035  1051 I ActivityManager: Process com.android.bluetooth (pid 6946) has died
08-26 14:17:34.657  1035  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-26 14:17:34.667  6837  6837 D DockEventReceiver: finishStartingService: stopping service
08-26 14:17:34.669  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:34.671  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 14:17:34.686  6837  6837 D BluetoothPermissionRequest: onReceive
08-26 14:17:34.689  6837  6837 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 14:17:34.689  6837  6837 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-26 14:17:34.692  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 14:17:34.754  1035  1770 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7645 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 14:17:34.833  7645  7645 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 14:17:34.834  7645  7645 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 14:17:34.834  7645  7645 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 14:17:34.835  7645  7645 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:34.856  7645  7645 D BluetoothAdapterApp: Loading JNI Library
,08-26 14:17:34.892  7645  7645 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@d8bb4f5 Instance Count = 1
,08-26 14:17:34.900  7645  7645 D BluetoothAdapterApp: onCreate
,08-26 14:17:34.934  7645  7645 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 14:17:34.934  7645  7645 D ProfileConfigQcom: Adding HeadsetService
,08-26 14:17:34.934  7645  7645 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 14:17:34.934  7645  7645 D ProfileConfigQcom: Adding A2dpService
08-26 14:17:34.935  7645  7645 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 14:17:34.935  7645  7645 D ProfileConfigQcom: Adding HidService
08-26 14:17:34.935  7645  7645 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 14:17:34.935  7645  7645 D ProfileConfigQcom: Adding HealthService
08-26 14:17:34.936  7645  7645 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 14:17:34.937  7645  7645 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 14:17:34.937  7645  7645 D ProfileConfigQcom: Adding PanService
08-26 14:17:34.937  7645  7645 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 14:17:34.938  7645  7645 D ProfileConfigQcom: Adding GattService
08-26 14:17:34.938  7645  7645 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 14:17:34.938  7645  7645 D ProfileConfigQcom: Adding BluetoothMapService
08-26 14:17:34.938  7645  7645 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 14:17:34.940  7645  7645 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 14:17:34.947  6837  6837 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-26 14:17:34.949  7645  7645 V LGMDMManagerInternal: Create singleton instance
,08-26 14:17:35.036  7645  7645 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:35.041  7645  7645 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-26 14:17:35.041  7645  7645 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 14:17:35.041  7645  7645 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 14:17:35.043  7645  7645 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:35.043  7645  7645 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 14:17:35.052  6902  6902 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 14:17:35.057  1035  1769 I ActivityManager: Killing 6856:com.lge.sync/1000 (adj 15): empty #17
08-26 14:17:35.082  1035  1425 D WifiService: Client connection lost with reason: 4
,08-26 14:17:35.099  1035  2056 W libprocessgroup: failed to open /acct/uid_1000/pid_6856/cgroup.procs: No such file or directory
,08-26 14:17:36.439  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:36.439  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-26 14:17:36.537  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 14:17:36.625  1035  1035 D administrator: Handling package changes for user 0
,08-26 14:17:36.640  1035  1109 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7673 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 14:17:36.646  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 14:17:36.650  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-26 14:17:36.663  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 14:17:36.678  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{19eccffc type 2 when 133235 com.google.android.gms} when 133235
,08-26 14:17:36.684  1035  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 14:17:36.702  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 14:17:36.732  7673  7673 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 14:17:36.791  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 14:17:36.791  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 14:17:36.833  7673  7673 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:36.834  7673  7673 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 14:17:36.852  1035  1107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:17:36.865  1035  1107 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 14:17:36.890  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 14:17:36.890  2468  2468 V GmsNetworkLocationProvi: DISABLE
,08-26 14:17:36.925  1035  1107 D LocationProviderProxy: applying state to connected service
,08-26 14:17:36.927  2468  2468 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-26 14:17:37.016  7673  7718 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-26 14:17:37.016  7673  7718 I Babel   : MmsConfig.loadMmsSettings
,08-26 14:17:37.022  7673  7718 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 14:17:37.022  7673  7718 I Babel   : MmsConfig.loadFromDatabase
,08-26 14:17:37.042  7673  7718 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 14:17:37.042  7673  7718 I Babel   : MmsConfig.loadFromResources
08-26 14:17:37.045  7673  7718 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 14:17:37.046  7673  7718 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-26 14:17:37.087  7673  7673 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:37.096  7673  7716 W AudioCapabilities: Unsupported mime audio/evrc
08-26 14:17:37.097  7673  7716 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 14:17:37.099  7673  7716 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 14:17:37.118  7673  7716 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-26 14:17:37.119  7673  7716 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 14:17:37.121  7673  7716 W AudioCapabilities: Unsupported mime audio/evrc
08-26 14:17:37.125  1803  7719 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 14:17:37.125  1803  7719 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-26 14:17:37.130  7006  7006 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 14:17:37.134  7006  7006 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1b0d61d7
08-26 14:17:37.134  7006  7006 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 14:17:37.134  7006  7006 D AppUp4:CustFacade: isPhone : true
08-26 14:17:37.135  7006  7006 D AppUp4:CustModeStarterReceiver: begin check event
08-26 14:17:37.135  7006  7006 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 14:17:37.138  7673  7716 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-26 14:17:37.139  1803  4714 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 14:17:37.143  7673  7716 W VideoCapabilities: Unsupported mime video/divx
,08-26 14:17:37.153  7673  7716 W VideoCapabilities: Unsupported mime video/divx311
08-26 14:17:37.155  7673  7716 W VideoCapabilities: Unsupported mime video/divx4
08-26 14:17:37.163  7673  7716 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 14:17:37.179  1035  1770 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7723 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-26 14:17:37.183  1035  1770 I ActivityManager: Killing 7053:com.lge.email/u0a23 (adj 15): empty #17
,08-26 14:17:37.193  7673  7716 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-26 14:17:37.197  7673  7716 W AudioCapabilities: Unsupported mime audio/eac3
,08-26 14:17:37.198  7673  7716 W AudioCapabilities: Unsupported mime audio/ac3
08-26 14:17:37.200  7673  7716 W AudioCapabilities: Unsupported mime audio/g726
08-26 14:17:37.201  7673  7716 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 14:17:37.202  7673  7716 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 14:17:37.203  7673  7716 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 14:17:37.205  7673  7716 W VideoCapabilities: Unsupported mime video/theora
08-26 14:17:37.206  7673  7716 W VideoCapabilities: Unsupported mime video/mjpg
08-26 14:17:37.309  1035  1769 W libprocessgroup: failed to open /acct/uid_10023/pid_7053/cgroup.procs: No such file or directory
,08-26 14:17:37.358  7723  7723 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:37.359  7723  7723 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 14:17:37.359  7723  7723 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 14:17:37.360  7723  7723 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 14:17:37.360  7723  7723 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 14:17:37.465  7723  7723 I SystemConfig: BUILD Country: EU
08-26 14:17:37.466  7723  7723 I SystemConfig: BUILD Operator: OPEN
,08-26 14:17:37.487  1035  1429 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-26 14:17:37.556  1035  1934 I ActivityManager: Killing 6927:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-26 14:17:37.619  1035  1583 W libprocessgroup: failed to open /acct/uid_10026/pid_6927/cgroup.procs: No such file or directory
,08-26 14:17:37.632  7723  7745 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 14:17:37.632  7723  7745 I SystemConfig: existFile = false
08-26 14:17:37.632  7723  7745 I SystemConfig: canReadFile = false
,08-26 14:17:37.633  7723  7745 I SystemConfig: systemFeature RCS result false
,08-26 14:17:37.633  7723  7745 D SystemConfig: refreshRcsSupport() :false
,08-26 14:17:37.706  1035  1934 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7751 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 14:17:37.801  7751  7751 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:37.801  7751  7751 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 14:17:37.801  7751  7751 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 14:17:37.802  7751  7751 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 14:17:37.936  7751  7751 I AppConfig: Total System Memory = 2995761152
,08-26 14:17:37.949  7751  7751 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-26 14:17:38.014  1035  1769 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7775 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:38.016  1035  1769 I ActivityManager: Killing 6392:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-26 14:17:38.078  1035  1770 W libprocessgroup: failed to open /acct/uid_1000/pid_6392/cgroup.procs: No such file or directory
,08-26 14:17:38.303  7775  7775 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 14:17:38.444  7775  7775 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 14:17:38.445  7775  7775 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 14:17:38.501  7775  7775 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 14:17:38.523  7775  7775 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 14:17:38.526  7775  7775 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 14:17:38.541  7775  7775 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 14:17:38.541  7775  7775 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 14:17:38.560  1035  1714 I ActivityManager: Killing 7081:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 14:17:38.593  1035  1934 W libprocessgroup: failed to open /acct/uid_10046/pid_7081/cgroup.procs: No such file or directory
,08-26 14:17:38.638  4584  7817 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-26 14:17:38.667  1035  1931 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7824 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-26 14:17:38.703  2826  2843 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-26 14:17:38.707  2826  2843 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@33e11ecb on behalf of 7775
,08-26 14:17:38.739  7775  7775 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 14:17:38.753  7775  7775 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-26 14:17:38.759  7824  7824 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 14:17:38.785  7824  7824 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-26 14:17:38.785  7824  7824 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-26 14:17:38.785  7824  7824 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 14:17:38.785  7824  7824 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-26 14:17:38.785  7824  7824 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 14:17:38.785  7824  7824 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 14:17:38.798   317  7858 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-26 14:17:38.799  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 14:17:38.831  7573  7614 D UEI.SmartControl: Internal timer expired: 1
08-26 14:17:38.831  7573  7614 D UEI.SmartControl: unbind internal service
,08-26 14:17:38.853  1035  1583 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7860 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 14:17:38.866  7573  7573 D UEI.SmartControl: Service.onUnbind: IControl
08-26 14:17:38.867  7573  7573 D UEI.SmartControl: Service.onDestroy
08-26 14:17:38.867  7573  7573 D UEI.SmartControl: Lock is in USE false
,08-26 14:17:38.867  7573  7573 D UEI.SmartControl: unbind internal service
08-26 14:17:38.867  7573  7573 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@32dc4473
08-26 14:17:38.868  7573  7573 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 14:17:38.868  7573  7573 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 14:17:38.868  7573  7573 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 14:17:38.868  7573  7573 W System.err: 	at com.uei.control.Service.c(Unknown Source)
,08-26 14:17:38.868  7573  7573 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 14:17:38.868  7573  7573 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 14:17:38.868  7573  7573 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 14:17:38.868  7573  7573 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 14:17:38.868  7573  7573 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:38.868  7573  7573 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:38.868  7573  7573 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:38.868  7573  7573 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:38.868  7573  7573 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:38.868  7573  7573 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:38.869  7573  7573 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:38.869  7573  7573 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@32dc4473
08-26 14:17:38.871  7573  7573 D serial_port: close(fd = 25)
,08-26 14:17:38.876   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 21.398ms
08-26 14:17:38.878  7573  7573 I UEI.SmartControl: Serial port is closed.
08-26 14:17:38.878  7573  7573 I UEI.SmartControl: Serial port is closed.
08-26 14:17:38.878  7573  7573 D UEI.SmartControl: Blaster closed
08-26 14:17:38.878  7573  7573 D UEI.SmartControl: Shut down QS...
08-26 14:17:38.879  7573  7573 D UEI.SmartControl: Stopping QS lib
08-26 14:17:38.880  7573  7573 D UEI.SmartControl: QS lib stop result = true
08-26 14:17:38.882  7573  7573 D UEI.SmartControl: Stopped QS lib
08-26 14:17:38.884  7573  7573 D UEI.SmartControl: Stopped file observer...
08-26 14:17:38.884  7573  7573 D UEI.SmartControl: QS shutdown complete
08-26 14:17:38.886  1035  2006 I ActivityManager: Killing 7104:com.android.chrome/u0a57 (adj 15): empty #17
08-26 14:17:38.900   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 20.283ms
,08-26 14:17:38.923   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 21.946ms
,08-26 14:17:38.999  1035  1583 W libprocessgroup: failed to open /acct/uid_10057/pid_7104/cgroup.procs: No such file or directory
,08-26 14:17:39.063  7860  7860 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 14:17:39.087  7860  7860 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 14:17:39.109  1035  1769 V SIM_STK : Menu title from STK is T-Mobile
,08-26 14:17:39.121  7860  7860 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 14:17:39.121  7860  7860 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 14:17:39.122  7860  7860 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 14:17:39.122  7860  7860 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 14:17:39.122  7860  7860 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 14:17:39.124  7860  7860 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 14:17:39.129  7860  7860 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-26 14:17:39.132  4584  7817 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 494 ms] updated apps [took 494 ms] 
,08-26 14:17:39.136  7860  7860 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-26 14:17:39.137  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8265
08-26 14:17:39.139  7860  7860 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 14:17:39.141  7860  7860 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 14:17:39.142  7860  7860 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 14:17:39.142  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 14:17:39.143  7860  7860 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-26 14:17:39.172  7860  7860 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 14:17:39.172  7860  7860 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 14:17:39.180  7860  7860 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 14:17:39.181  7860  7860 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 14:17:39.181  7860  7860 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 14:17:39.181  7860  7860 V SoundPool: doLoad: loading sample sampleID=1
08-26 14:17:39.181  7860  7860 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 14:17:39.186  7860  7881 V SoundPool: Start decode
08-26 14:17:39.187  7860  7881 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 14:17:39.189  7860  7860 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 14:17:39.189  7573  7573 D UEI.SmartControl: QS Service created
,08-26 14:17:39.191   321  1715 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 14:17:39.191   321  1715 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 14:17:39.191   321  1715 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 14:17:39.191   321  1715 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 14:17:39.192   321  1715 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 14:17:39.192   321  1715 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 14:17:39.192   321  1715 V MediaPlayerService: player type = 3
08-26 14:17:39.192   321  1715 V AwesomePlayer: AwesomePlayer create()
08-26 14:17:39.193   321  1715 V AwesomePlayer: reset_l() 
08-26 14:17:39.193   321  1715 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:39.193   321  1715 V AwesomePlayer: setAudioSink() 
08-26 14:17:39.193   321  1715 V AwesomePlayer: reset_l() 
08-26 14:17:39.193   321  1715 V AudioCache: notify(0xb54745c0, 8, 0, 0)
08-26 14:17:39.193   321  1715 V AudioCache: ignored
08-26 14:17:39.193   321  1715 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:39.194   321  1715 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 14:17:39.194   321  1715 V AwesomePlayer: setDataSource_l dataSource
08-26 14:17:39.194  7860  7860 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 14:17:39.194   321  1715 V LGParserOSAL: SniffLGParser start
08-26 14:17:39.194   321  1715 V LGParserOSAL: MainType:5, SubType=0
08-26 14:17:39.194   321  1715 V LGParserOSAL: #### check Mime : application/ogg
08-26 14:17:39.194   321  1715 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 14:17:39.194   321  1715 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 14:17:39.195  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 14:17:39.215  7860  7860 V LGMDMManager: Create singleton instance
,08-26 14:17:39.229  7573  7573 I UEI.SmartControl: Service initServices...
,08-26 14:17:39.230  7573  7573 D UEI.SmartControl: QS start get config
08-26 14:17:39.251   321  1715 V LGParserOSAL: supported mime: application/ogg
08-26 14:17:39.251   321  1715 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 14:17:39.251   321  1715 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 14:17:39.251   321  1715 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 14:17:39.251   321  1715 V AwesomePlayer: AudioTrack Setting
08-26 14:17:39.251   321  1715 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 14:17:39.251   321  1715 V AwesomePlayer: setAudioSource() 
08-26 14:17:39.251   321  1715 V MediaPlayerService: prepare
08-26 14:17:39.251   321  1715 V AwesomePlayer: prepareAsync_l() 
08-26 14:17:39.251   321  1715 V MediaPlayerService: wait for prepare
08-26 14:17:39.252   321  7882 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 14:17:39.252   321  7882 V AwesomePlayer: initAudioDecoder() 
08-26 14:17:39.252   321  7882 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 14:17:39.252   321  7882 V AudioSystem: isOffloadSupported()
08-26 14:17:39.252   321  7882 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 14:17:39.252   321  7882 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 14:17:39.252   321  7882 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 14:17:39.252   321  7882 V AwesomePlayer: getUseOffload() = 0 
,08-26 14:17:39.252   321  7882 V OMXCodec: OMXCodec::Create
08-26 14:17:39.252   321  7882 V OMXCodec: findMatchingCodecs()
08-26 14:17:39.252   321  7882 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 14:17:39.253   321  7882 V OMXCodec: matchingCodecs.size()=1
08-26 14:17:39.253   321  7882 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 14:17:39.257   321  7882 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,08-26 14:17:39.257   321  7882 V LGCodecAdapter: LG Codec Adapter start
08-26 14:17:39.257   321  7882 V OMXCodec: OMXCodec Createtor
08-26 14:17:39.257   321  7882 V OMXCodec: setComponentRole
08-26 14:17:39.257   321  7882 V OMXCodec: configureCodec protected=0
08-26 14:17:39.257   321  7882 V LGCodecAdapter: called getLGCodecSpecificData
08-26 14:17:39.257   321  7882 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 14:17:39.257   321  7882 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 14:17:39.258   321  7882 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 14:17:39.258   321  7882 V LGCodecOSAL: Not support LGCodec
08-26 14:17:39.258   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 14:17:39.258   321  7882 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 14:17:39.258   321  7882 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 14:17:39.258   321  7882 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 14:17:39.258   321  7882 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 14:17:39.258   321  7882 V AudioSystem: isOffloadSupported()
08-26 14:17:39.258   321  7882 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 14:17:39.258   321  7882 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 14:17:39.258   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 14:17:39.258   321  7882 V OMXCodec: init()
08-26 14:17:39.259   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 14:17:39.259   321  7882 V OMXCodec: allocateBuffers
08-26 14:17:39.259   321  7882 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 14:17:39.259   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 14:17:39.259   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
08-26 14:17:39.259   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
08-26 14:17:39.260   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-26 14:17:39.260   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-26 14:17:39.260   321  7882 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 14:17:39.260   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 14:17:39.260   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-26 14:17:39.260   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-26 14:17:39.260   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-26 14:17:39.260   321  7882 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-26 14:17:39.261   321  7882 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 14:17:39.261   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 14:17:39.261   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 14:17:39.261   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 14:17:39.261   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 14:17:39.261   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 14:17:39.261   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 14:17:39.261   321  7882 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 14:17:39.261   ,321  7882 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 14:17:39.261   321  7882 V AudioCache: notify(0xb54745c0, 5, 0, 0)
08-26 14:17:39.261   321  7882 V AudioCache: ignored
08-26 14:17:39.261   321  7882 V AudioCache: notify(0xb54745c0, 1, 0, 0)
08-26 14:17:39.261   321  7882 V AudioCache: prepared
08-26 14:17:39.261   321  1715 V AudioCache: wait - success
08-26 14:17:39.261   321  1715 V MediaPlayerService: start
08-26 14:17:39.261   321  1715 V AwesomePlayer: play_l() 
08-26 14:17:39.261   321  1715 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 14:17:39.261   321  1715 V AwesomePlayer: createAudioPlayer_l
08-26 14:17:39.261   321  1715 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 14:17:39.261   321  1715 V AwesomePlayer: startAudioPlayer_l() 
08-26 14:17:39.261   321  1715 D AudioPlayer: start of Playback, useOffload 0
08-26 14:17:39.261   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 14:17:39.261   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 14:17:39.264   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 14:17:39.264   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 14:17:39.264   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 14:17:39.264   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 14:17:39.264   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 14:17:39.264   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 14:17:39.265   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 14:17:39.266   321  7884 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 14:17:39.266   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 14:17:39.266   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-26 14:17:39.266   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-26 14:17:39.266   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-26 14:17:39.266   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 14:17:39.266   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 14:17:39.266   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 14:17:39.269   321  1715 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 14:17:39.269   321  1715 V AudioCache: notify(0xb54745c0, 6, 0, 0)
08-26 14:17:39.269   321  1715 V AudioCache: ignored
08-26 14:17:39.269   321  1715 V MediaPlayerService: wait for playback complete
08-26 14:17:39.278   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.278   321  7885 V AudioCache: memcpy(0xaf006000, 0xb57bf000, 4096)
08-26 14:17:39.280   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.280   321  7885 V AudioCache: memcpy(0xaf007000, 0xb57bf000, 4096)
08-26 14:17:39.281   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.281   321  7885 V AudioCache: memcpy(0xaf008000, 0xb57bf000, 4096)
08-26 14:17:39.282   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.282   321  7885 V AudioCache: memcpy(0xaf009000, 0xb57bf000, 4096)
08-26 14:17:39.283   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.283   321  7885 V AudioCache: memcpy(0xaf00a000, 0xb57bf000, 4096)
08-26 14:17:39.283   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.283   321  7885 V AudioCache: memcpy(0xaf00b000, 0xb57bf000, 4096)
08-26 14:17:39.284   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.284   321  7885 V AudioCache: memcpy(0xaf00c000, 0xb57bf000, 4096)
08-26 14:17:39.285   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.285   321  7885 V AudioCache: memcpy(0xaf00d000, 0xb57bf000, 4096)
08-26 14:17:39.285   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.285   321  7885 V AudioCache: memcpy(0xaf00e000, 0xb57bf000, 4096)
08-26 14:17:39.286   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.286   321  7885 V AudioCache: memcpy(0xaf00f000, 0xb57bf000, 4096)
08-26 14:17:39.287   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.287   321  7885 V AudioCache: memcpy(0xaf010000, 0xb57bf000, 4096)
08-26 14:17:39.288   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.288   321  7885 V AudioCache: memcpy(0xaf011000, 0xb57bf000, 4096)
08-26 14:17:39.288   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.288   321  7885 V AudioCache: memcpy(0xaf012000, 0xb57bf000, 4096)
08-26 14:17:39.289   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.289   321  7885 V AudioCache: memcpy(0xaf013000, 0xb57bf000, 4096)
08-26 14:17:39.289   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.290   321  7885 V AudioCache: memcpy(0xaf014000, 0xb57bf000, 4096)
08-26 14:17:39.290   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.290   321  7885 V AudioCache: memcpy(0xaf015000, 0xb57bf000, 4096)
08-26 14:17:39.291   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.291   321  7885 V AudioCache: memcpy(0xaf016000, 0xb57bf000, 4096)
08-26 14:17:39.291   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.291   321  7885 V AudioCache: memcpy(0xaf017000, 0xb57bf000, 4096)
08-26 14:17:39.292   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.292   321  7885 V AudioCache: memcpy(0xaf018000, 0xb57bf000, 4096)
08-26 14:17:39.292   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.292   321  7885 V AudioCache: memcpy(0xaf019000, 0xb57bf000, 4096)
08-26 14:17:39.293   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.293   321  7885 V AudioCache: memcpy(0xaf01a000, 0xb57bf000, 4096)
08-26 14:17:39.293   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.293   321  7885 V AudioCache: memcpy(0xaf01b000, 0xb57bf000, 4096)
08-26 14:17:39.294   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.294   321  7885 V AudioCache: memcpy(0xaf01c000, 0xb57bf000, 4096)
08-26 14:17:39.295   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.295   321  7885 V AudioCache: memcpy(0xaf01d000, 0xb57bf000, 4096)
08-26 14:17:39.295   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.295   321  7885 V AudioCache: memcpy(0xaf01e000, 0xb57bf000, 4096)
08-26 14:17:39.296   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.296   321  7885 V AudioCache: memcpy(0xaf01f000, 0xb57bf000, 4096)
08-26 14:17:39.296   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.296   321  7885 V AudioCache: memcpy(0xaf020000, 0xb57bf000, 4096)
08-26 14:17:39.297   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.297   321  7885 V AudioCache: memcpy(0xaf021000, 0xb57bf000, 4096)
08-26 14:17:39.297   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.297   321  7885 V AudioCache: memcpy(0xaf022000, 0xb57bf000, 4096)
08-26 14:17:39.298   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.298   321  7885 V AudioCache: memcpy(0xaf023000, 0xb57bf000, 4096)
08-26 14:17:39.299   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.299   321  7885 V AudioCache: memcpy(0xaf024000, 0xb57bf000, 4096)
08-26 14:17:39.299   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.299   321  7885 V AudioCache: memcpy(0xaf025000, 0xb57bf000, 4096)
08-26 14:17:39.300   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.300   321  7885 V AudioCache: memcpy(0xaf026000, 0xb57bf000, 4096)
08-26 14:17:39.300   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.300   321  7885 V AudioCache: memcpy(0xaf027000, 0xb57bf000, 4096)
08-26 14:17:39.300  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 14:17:39.301   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.301   321  7885 V AudioCache: memcpy(0xaf028000, 0xb57bf000, 4096)
08-26 14:17:39.301  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 14:17:39.302   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.302   321  7885 V AudioCache: memcpy(0xaf029000, 0xb57bf000, 4096)
08-26 14:17:39.303   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.303   321  7885 V AudioCache: memcpy(0xaf02a000, 0xb57bf000, 4096)
08-26 14:17:39.303   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.303   321  7885 V AudioCache: memcpy(0xaf02b000, 0xb57bf000, 4096)
08-26 14:17:39.303  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4903
08-26 14:17:39.304   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.304   321  7885 V AudioCache: memcpy(0xaf02c000, 0xb57bf000, 4096)
08-26 14:17:39.305   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.305   321  7885 V AudioCache: memcpy(0xaf02d000, 0xb57bf000, 4096)
,08-26 14:17:39.306   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.306   321  7885 V AudioCache: memcpy(0xaf02e000, 0xb57bf000, 4096)
08-26 14:17:39.306   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.306   321  7885 V AudioCache: memcpy(0xaf02f000, 0xb57bf000, 4096)
08-26 14:17:39.306   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.306   321  7885 V AudioCache: memcpy(0xaf030000, 0xb57bf000, 4096)
08-26 14:17:39.306   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.306   321  7885 V AudioCache: memcpy(0xaf031000, 0xb57bf000, 4096)
08-26 14:17:39.308   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.308   321  7885 V AudioCache: memcpy(0xaf032000, 0xb57bf000, 4096)
08-26 14:17:39.308   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.308   321  7885 V AudioCache: memcpy(0xaf033000, 0xb57bf000, 4096)
08-26 14:17:39.308   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.308   321  7885 V AudioCache: memcpy(0xaf034000, 0xb57bf000, 4096)
08-26 14:17:39.308   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.308   321  7885 V AudioCache: memcpy(0xaf035000, 0xb57bf000, 4096)
08-26 14:17:39.310   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 14:17:39.310   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.310   321  7885 V AudioCache: memcpy(0xaf036000, 0xb57bf000, 4096)
08-26 14:17:39.310   321  7885 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 14:17:39.310   321  7885 V AudioCache: write(0xb57bf000, 4096)
08-26 14:17:39.310   321  7885 V AudioCache: memcpy(0xaf037000, 0xb57bf000, 4096)
08-26 14:17:39.310   321  7885 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 14:17:39.310   321  7885 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 14:17:39.310   321  7885 V AwesomePlayer: postAudioEOS() 
08-26 14:17:39.310   321  7885 V AudioCache: write(0xb57bf000, 280)
08-26 14:17:39.310   321  7885 V AudioCache: memcpy(0xaf038000, 0xb57bf000, 280)
08-26 14:17:39.312   321  7882 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 14:17:39.312   321  7882 V AwesomePlayer: onStreamDone
08-26 14:17:39.312   321  7882 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 14:17:39.312   321  7882 V AudioCache: notify(0xb54745c0, 2, 0, 0)
08-26 14:17:39.312   321  7882 V AudioCache: playback complete
08-26 14:17:39.312   321  7882 V AwesomePlayer: pause_l() 
08-26 14:17:39.312   321  1715 V AudioCache: wait - success
08-26 14:17:39.312   321  7882 V AudioCache: notify(0xb54745c0, 7, 0, 0)
08-26 14:17:39.312   321  1715 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 14:17:39.312   321  7882 V AudioCache: ignored
08-26 14:17:39.312   321  7882 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:39.312   321  7882 D AudioPlayer: Pause Playback at 1068125
08-26 14:17:39.312   321  1715 V AwesomePlayer: reset_l() 
08-26 14:17:39.312   321  1715 V AudioCache: notify(0xb54745c0, 8, 0, 0)
08-26 14:17:39.312   321  1715 V AudioCache: ignored
08-26 14:17:39.312   321  1715 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:39.313   321  1715 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 14:17:39.313   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 14:17:39.313   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 14:17:39.313   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 14:17:39.313   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.goog,le.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 14:17:39.313   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
,08-26 14:17:39.314   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 14:17:39.314   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 14:17:39.314   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 14:17:39.314   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 14:17:39.314   321  7884 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
,08-26 14:17:39.314   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 14:17:39.314   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 14:17:39.314   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 14:17:39.315   321  1715 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-26 14:17:39.315   321  1715 D AudioPlayer: AudioPlayer releasing audio source
08-26 14:17:39.315   321  1715 D AudioPlayer: AudioPlayer done releasing audio source
08-26 14:17:39.315   321  1715 V AwesomePlayer: reset_l() 
08-26 14:17:39.315   321  1715 V AwesomePlayer: cancelPlayerEvents
,08-26 14:17:39.315   321  1715 V AwesomePlayer: ~AwesomePlayer call
08-26 14:17:39.315   321  1715 V AwesomePlayer: reset_l() 
08-26 14:17:39.315   321  1715 V AwesomePlayer: cancelPlayerEvents
08-26 14:17:39.315  7860  7881 V SoundPool: close(31)
,08-26 14:17:39.315  7860  7881 V SoundPool: pointer = 0xa0009000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 14:17:39.453  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:39.454  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23563a51 added. We now have 6 listener(s)
08-26 14:17:39.454  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-26 14:17:39.457  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:39.461  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d21b2b6 added. We now have 7 listener(s)
08-26 14:17:39.461  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:39.462  6586  6695 I System.out: IsBluetoothEnabled
,08-26 14:17:39.464  1035  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:39.464  1035  2051 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-26 14:17:39.464  1035  1117 D BluetoothManagerService: Message: 2
08-26 14:17:39.473  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:39.474  1035  1770 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 14:17:39.475  1035  1770 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 14:17:39.492  1035  1117 D BluetoothManagerService: Message: 1
08-26 14:17:39.492  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 14:17:39.494  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 14:17:39.495  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 14:17:39.495  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 14:17:39.504  1035  1117 D BluetoothManagerService: Message: 20
08-26 14:17:39.504  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@106782aa:true
08-26 14:17:39.505  7645  7645 D BluetoothAdapterState: make
08-26 14:17:39.510  7645  7645 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 14:17:39.510  7645  7645 I bluedroid-qcom: init
08-26 14:17:39.511  7645  7889 I BluetoothAdapterState: Entering OffState
08-26 14:17:39.511  7645  7645 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 14:17:39.511  7645  7645 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 14:17:39.511  7645  7645 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 14:17:39.511  7645  7645 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 14:17:39.511  7645  7645 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 14:17:39.512  7645  7645 I bluedroid-qcom: get_profile_interface socket
08-26 14:17:39.512  7645  7645 I bluedroid-qcom: get_profile_interface map_client
08-26 14:17:39.512  7645  7893 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 14:17:39.505  7892  7892 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:39.505  7892  7892 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:39.515  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 14:17:39.516  1035  1117 D BluetoothManagerService: Message: 40
08-26 14:17:39.516  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 14:17:39.519  7645  7661 I bluedroid-qcom: config_hci_snoop_log
08-26 14:17:39.520  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
,08-26 14:17:39.521  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 14:17:39.521  7645  7893 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 14:17:39.523  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 14:17:39.523  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 14:17:39.523  7645  7893 D BluetoothAdapterProperties: Name is: G3
,08-26 14:17:39.525  7645  7889 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 14:17:39.525  7645  7889 D BluetoothAdapterProperties: Setting state to 11
08-26 14:17:39.525  7645  7889 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 14:17:39.526  1035  1117 D BluetoothManagerService: Message: 60
08-26 14:17:39.526  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 14:17:39.526  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 14:17:39.528  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 14:17:39.528  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:39.530  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 14:17:39.531  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:39.531  7892  7892 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 14:17:39.531  7892  7892 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 14:17:39.531  7892  7892 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 14:17:39.531  7645  7889 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 14:17:39.534  7892  7892 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 14:17:39.539  7892  7892 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 14:17:39.539  7892  7892 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 14:17:39.539  7645  7645 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 14:17:39.540  7645  7645 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:39.540  7645  7645 V BluetoothPbapReceiver: ***********state = 11
,08-26 14:17:39.542  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:39.547  7645  7889 D BluetoothBondStateMachine: make
08-26 14:17:39.549  7645  7889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:39.550  7645  7889 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 14:17:39.550  7645  7889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:39.550  7645  7889 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 14:17:39.550  7645  7889 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 14:17:39.550  7645  7894 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 14:17:39.552  6837  6837 D BluetoothPermissionRequest: onReceive
,08-26 14:17:39.554  7645  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:39.555  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 14:17:39.559  7645  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:39.562  7645  7645 D HeadsetService: Received start request. Starting profile...
08-26 14:17:39.562  7645  7645 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 14:17:39.562  7645  7645 D LGBluetoothHfpAdapter: Version 1.6
08-26 14:17:39.565  7645  7645 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 14:17:39.566  7645  7645 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 14:17:39.566  7645  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:39.567  7645  7645 D HeadsetStateMachine: make
08-26 14:17:39.570  7645  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:39.574  7645  7889 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 14:17:39.579  7645  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:39.582  7645  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-26 14:17:39.604  7645  7645 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:39.605  7645  7645 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 14:17:39.607  7573  7573 I UEI.SmartControl: Supports setup maps: true
08-26 14:17:39.609  7645  7889 V LGMDMManager: Create singleton instance
08-26 14:17:39.610  7645  7889 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 14:17:39.611  7645  7645 D HeadsetStateMachine: max_hf_connections = 1
08-26 14:17:39.612  7645  7645 I bluedroid-qcom: get_profile_interface handsfree
08-26 14:17:39.613  7573  7573 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 14:17:39.613  7573  7573 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 14:17:39.613  7573  7573 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 14:17:39.613  7573  7573 I UEI.SmartControl: ### init IR Blaster...
08-26 14:17:39.614  7645  7645 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 14:17:39.615   321   321 V AudioPolicyService: registerClient() client 0xb0410600, uid 1002
08-26 14:17:39.615   321  1380 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 14:17:39.615   321  1380 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 14:17:39.615   321  1380 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 14:17:39.616  7645  7645 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 14:17:39.616   321  1381 V AudioFlinger: registerClient() client 0xb55816e8, pid 7645
08-26 14:17:39.616  7573  7573 D serial_port: Configuring serial port
08-26 14:17:39.616  7573  7573 E UEI.SmartControl: UEIBLaster setting for 616
08-26 14:17:39.616  7573  7573 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 14:17:39.616  7573  7573 I UEI.SmartControl: configuring settings for MAXQ616
08-26 14:17:39.617  7573  7573 I UEI.SmartControl: Get version...
,08-26 14:17:39.617   321  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:39.617   321  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:39.617  1586  2525 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:39.617  1586  2525 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:39.617  3459  3478 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:39.617  3459  3478 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:39.617  1035  1583 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:39.617  1035  1583 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:39.617   321  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:39.617  7645  7662 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:39.617  7645  7645 V ToneGenerator: Create Track: 0xb4928a80
08-26 14:17:39.617   321  1376 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:39.617  7645  7662 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 14:17:39.617  7645  7645 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 14:17:39.617  1035  1931 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:39.617  7645  7645 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 14:17:39.617  1035  1931 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:39.618  1586  1923 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:39.618  1586  1923 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:39.618  3459  3477 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:39.618   321  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 14:17:39.618  3459  3477 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:39.618   321  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 14:17:39.618   321  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 14:17:39.618  7645  7661 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:39.618  7645  7661 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 14:17:39.618   321  1381 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 14:17:39.618  1861  2443 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 14:17:39.618  1861  2443 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 14:17:39.618  1861  2443 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 14:17:39.618  1861  2443 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 14:17:39.618   321  1380 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 14:17:39.618   321   321 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 14:17:39.618   321   321 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 14:17:39.618   321   321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 14:17:39.618   321   321 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 14:17:39.619  7645  7645 V AudioSystem: getLatency() output 2, latency 50
08-26 14:17:39.619  7645  7645 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 14:17:39.619  7645  7645 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 14:17:39.619   321  1715 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 14:17:39.619   321  1715 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), ,curLvl = 31 
08-26 14:17:39.619   321  1715 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 14:17:39.619   321  1715 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 14:17:39.619   321  1715 V AudioFlinger: createTrack() lSessionId: 21
08-26 14:17:39.620  7645  7645 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,08-26 14:17:39.621   321  1381 V AudioFlinger: acquiring 21 from 7645, for 7645
,08-26 14:17:39.621   321  1381 V AudioFlinger:  added new entry for 21
08-26 14:17:39.621  7645  7645 V ToneGenerator: ToneGenerator INIT OK, time: 136194
08-26 14:17:39.621  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:39.622  7645  7895 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 14:17:39.623  7645  7895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 14:17:39.623  7645  7895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 14:17:39.623  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:39.623  7645  7895 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 14:17:39.623   321  1380 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7645
08-26 14:17:39.624   321  1380 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 14:17:39.624   321  1380 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 14:17:39.624   321  1380 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 14:17:39.624   321  1380 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 14:17:39.624   321  1380 V voice   : voice_set_parameters: exit with code(0)
08-26 14:17:39.624   321  1380 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 14:17:39.624   321  1380 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 14:17:39.624   321  1380 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 14:17:39.624   321  1380 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 14:17:39.624   321  1380 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 14:17:39.624   321  1380 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 14:17:39.624  7645  7895 V ToneGenerator: ToneGenerator destructor
08-26 14:17:39.624  7645  7895 V ToneGenerator: stopTone
08-26 14:17:39.624  7645  7895 V ToneGenerator: Delete Track: 0xb4928a80
08-26 14:17:39.625  7645  7645 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:39.627  7645  7895 V AudioTrack: ~AudioTrack, releasing session id from 7645 on behalf of 7645
08-26 14:17:39.627   321  1715 V AudioFlinger: releasing 21 from 7645 for 7645
08-26 14:17:39.627   321  1715 V AudioFlinger:  decremented refcount to 0
08-26 14:17:39.627   321  1715 V AudioFlinger: purging stale effects
08-26 14:17:39.627   321  1715 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 14:17:39.627   321  1715 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 14:17:39.627   321  1260 V AudioPolicyService: AudioCommandThread() waking up
08-26 14:17:39.627   321  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 14:17:39.628  1035  1714 W Process : Unable to open /proc/7897/status
08-26 14:17:39.628   321  1260 V AudioPolicyManager: releaseOutput() 2
08-26 14:17:39.628   321  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 14:17:39.628   321  1715 V AudioFlinger: PlaybackThread::Track destructor
08-26 14:17:39.628   321  1715 V AudioFlinger: removeClient_l() pid 7645, calling pid 321
08-26 14:17:39.628  7645  7645 D A2dpService: Received start request. Starting profile...
08-26 14:17:39.629  7645  7645 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 14:17:39.630  7645  7645 V Avrcp   : make
08-26 14:17:39.630  7645  7645 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 14:17:39.630  7645  7645 I bluedroid-qcom: get_profile_interface avrcp
,08-26 14:17:39.634  7573  7896 D UEI.SmartControl: serial port data available: 21
08-26 14:17:39.640  7645  7645 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 14:17:39.641  7645  7645 E AudioManager: No RCC entry present to update
08-26 14:17:39.641  7645  7645 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 14:17:39.645  7645  7645 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-26 14:17:39.646  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 14:17:39.646  7645  7645 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 14:17:39.650  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 14:17:39.660  7573  7573 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 14:17:39.660  7573  7573 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 14:17:39.660  7573  7573 I UEI.SmartControl: QS saving settings...
,08-26 14:17:39.661  7573  7573 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 14:17:39.677  7573  7896 D UEI.SmartControl: serial port data available: 4
,08-26 14:17:39.708  7573  7573 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 14:17:39.709  7573  7902 I UEI.SmartControl: Device manager: loading config....
08-26 14:17:39.710  7573  7902 D UEI.SmartControl: ----------- loading internal config...
08-26 14:17:39.713  7573  7573 E UEI.SmartControl: Services init done
08-26 14:17:39.713  7573  7573 D UEI.SmartControl: QS Service init finished
08-26 14:17:39.714  7573  7573 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 14:17:39.715  7573  7573 D UEI.SmartControl: QS Service version code: 201091
08-26 14:17:39.715  7573  7573 D UEI.SmartControl: Service requested: Control
08-26 14:17:39.721  7573  7573 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 14:17:39.721  7573  7902 E UEI.SmartControl: Loading SETTINGS...
,08-26 14:17:39.725  7860  7860 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-26 14:17:39.726  7573  7573 D UEI.SmartControl: Internal service binding...
08-26 14:17:39.727  7573  7589 I UEI.SmartControl: ------ IControl API: 11
08-26 14:17:39.729  7573  7589 D UEI.SmartControl: File observer start...
08-26 14:17:39.729  7573  7589 E UEI.SmartControl: IR Port is disabled: false
08-26 14:17:39.730  7573  7589 D UEI.SmartControl: Starting file observer...
08-26 14:17:39.730  7573  7589 I UEI.SmartControl: Registering callback...
08-26 14:17:39.730  7573  7902 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 14:17:39.738  7573  7588 I UEI.SmartControl: ------ IControl API: 19
,08-26 14:17:39.745  7573  7588 I UEI.SmartControl: Registering Services Ready callback...
,08-26 14:17:39.745  7573  7588 I UEI.SmartControl: Notify client services are ready...
08-26 14:17:39.747  7573  7901 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 14:17:39.747  7573  7901 D UEI.SmartControl: -----service ready thread exits
08-26 14:17:39.747  7860  7876 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 14:17:39.748  7860  7879 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 14:17:39.748  7860  7876 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 14:17:39.748  7860  7879 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 14:17:39.748  7860  7879 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 14:17:39.748  7860  7879 D QRemote : [RemoteControlManager.java:391:handleMessage()] oooooo 140510:Retrieve msg remove
,08-26 14:17:39.749  7860  7879 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 14:17:39.749  7860  7860 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 14:17:39.750  7860  7860 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 14:17:39.750  7573  7616 I UEI.SmartControl: ------ IControl API: 8
08-26 14:17:39.753  7860  7860 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 14:17:39.754  7860  7860 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,08-26 14:17:39.756  7860  7860 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 14:17:39.758  7860  7860 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 14:17:39.760  7860  7860 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 14:17:39.761  7860  7860 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 14:17:39.762  7860  7860 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 14:17:39.767  7860  7860 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-26 14:17:39.769  7860  7860 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 14:17:39.771  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 14:17:39.773  7860  7860 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 14:17:39.773  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 14:17:39.773  1035  1770 V SIM_STK : Menu title from STK is T-Mobile
08-26 14:17:39.774  1035  1770 V SIM_STK : Menu title from STK is T-Mobile
08-26 14:17:39.775  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 14:17:39.778  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 14:17:39.779  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 14:17:39.783  7860  7860 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472213859781]
,08-26 14:17:39.790  7860  7860 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 14:17:39.821  7860  7904 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 14:17:39.825  7860  7860 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-26 14:17:39.826  7860  7860 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 14:17:39.826  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 14:17:39.827  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 14:17:39.827  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 14:17:39.827  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 14:17:39.828  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 14:17:39.837  7860  7860 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 14:17:39.883  1035  2056 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 14:17:39.901  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 14:17:39.906  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 14:17:39.907  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 14:17:39.908  7645  7645 I BluetoothA2dpServiceJni: classInitNative
08-26 14:17:39.908  7645  7645 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 14:17:39.908  7645  7645 D A2dpStateMachine: make
08-26 14:17:39.910  7645  7645 I bluedroid-qcom: get_profile_interface a2dp
,08-26 14:17:39.910  7645  7909 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 14:17:39.912  7645  7645 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 14:17:39.912  7645  7645 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 14:17:39.913  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:39.914  7645  7908 D A2dpStateMachine: Enter Disconnected: -2
08-26 14:17:39.914  7645  7645 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 14:17:39.916  7645  7645 D HidService: Received start request. Starting profile...
08-26 14:17:39.916  7645  7645 I bluedroid-qcom: get_profile_interface hidhost
08-26 14:17:39.916  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:39.917  7645  7645 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 14:17:39.918  7645  7645 D HealthService: Received start request. Starting profile...
,08-26 14:17:39.920  7645  7645 I bluedroid-qcom: get_profile_interface health
08-26 14:17:39.920  7645  7645 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 14:17:39.920  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:39.921  7645  7645 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 14:17:39.923  7645  7645 D PanService: Received start request. Starting profile...
08-26 14:17:39.923  7645  7645 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 14:17:39.923  7645  7645 I bluedroid-qcom: get_profile_interface pan
08-26 14:17:39.930  7645  7645 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 14:17:39.930  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
,08-26 14:17:39.931  7645  7645 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 14:17:39.935  7645  7645 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 14:17:39.936  7645  7645 D BtGatt.GattService: Received start request. Starting profile...
08-26 14:17:39.936  7645  7645 D BtGatt.GattService: start()
08-26 14:17:39.936  7645  7645 I bluedroid-qcom: get_profile_interface gatt
08-26 14:17:39.936  7645  7645 D BtGatt.AdvertiseManager: advertise manager created
08-26 14:17:39.946  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
,08-26 14:17:39.950  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
,08-26 14:17:39.951  7645  7645 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 14:17:39.952  7645  7645 V BluetoothMapService: BluetoothMapBinder()
08-26 14:17:39.953  7645  7645 D BluetoothMapService: Received start request. Starting profile...
08-26 14:17:39.953  7645  7645 D BluetoothMapService: start()
08-26 14:17:39.955  7645  7645 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 14:17:39.956  7645  7645 D BluetoothMapEmailAppObserver: createReceiver()
08-26 14:17:39.957  7645  7645 D BluetoothMapEmailAppObserver: initObservers()
08-26 14:17:39.957  7645  7645 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 14:17:39.965  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
,08-26 14:17:39.966  7645  7645 D HeadsetStateMachine: Proxy object connected
,08-26 14:17:39.967  7645  7645 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 14:17:39.967  7645  7645 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 14:17:39.973  7645  7645 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 14:17:39.974  7645  7895 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 14:17:39.974  7645  7895 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 14:17:39.975  7645  7895 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 14:17:39.975  7645  7645 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 14:17:39.975  7645  7645 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 14:17:39.975  7645  7645 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 14:17:39.975  7645  7645 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:39.975  7645  7645 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 14:17:39.984  7645  7645 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 14:17:39.989  7645  7645 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 14:17:39.993  7645  7645 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 14:17:39.997  7645  7645 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 14:17:39.997  7645  7645 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 14:17:40.001  7645  7645 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 14:17:40.001  7645  7645 V BluetoothMapService: Handler(): got msg=1
,08-26 14:17:40.004  7645  7889 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 14:17:40.004  7645  7889 I bluedroid-qcom: enable
08-26 14:17:40.004  7645  7889 I bt_hci_bdroid: init
,08-26 14:17:40.005  7645  7916 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 14:17:40.005  7645  7916 I bt-btu  : btu_task pending for preload complete event
08-26 14:17:40.006  7645  7889 I bt_vendor: bt-vendor : init
08-26 14:17:40.006  7645  7889 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 14:17:40.006  7645  7889 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 14:17:40.006  7645  7889 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 14:17:40.006  7645  7889 D bt_userial_mct: userial_init
08-26 14:17:40.006  7645  7889 D bt_hci_bdroid: set_power 1
08-26 14:17:40.006  7645  7889 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 14:17:40.006  7645  7889 I bt_vendor: Starting hciattach daemon
08-26 14:17:40.006  7645  7889 I bt_vendor: try to set true
08-26 14:17:40.005  7919  7919 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:40.005  7919  7919 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:40.034  7920  7920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 14:17:40.139  7926  7926 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 14:17:40.165  7927  7927 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 14:17:40.195  7929  7929 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 14:17:40.209  7930  7930 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 14:17:40.222  7931  7931 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 14:17:40.244  7932  7932 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 14:17:40.270  7937  7937 I libmdmdetect: ESOC framework not supported
,08-26 14:17:40.277  7937  7937 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-26 14:17:40.288  7937  7937 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 14:17:40.288  7937  7937 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 14:17:40.288  7937  7937 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 14:17:40.288  7937  7937 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 14:17:40.288  7937  7937 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 14:17:40.288  7937  7937 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 14:17:40.289  7937  7937 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-26 14:17:40.338  7937  7938 E QC-QMI  : qmi_client [7937] 15: failed to locate client data
,08-26 14:17:40.339   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-26 14:17:40.339   478   478 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-26 14:17:40.414  7942  7942 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 14:17:40.436  7943  7943 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 14:17:40.470  7645  7889 I bt_vendor: bluetooth satus is on
,08-26 14:17:40.470  7645  7889 D bt_hci_bdroid: preload
,08-26 14:17:40.473  7645  7918 D bt_userial_mct: userial_open(port:0)
08-26 14:17:40.473  7645  7918 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 14:17:40.478  7645  7918 I bt_vendor: Done intiailizing UART
08-26 14:17:40.479  7645  7918 I bt_vendor: Done intiailizing UART
08-26 14:17:40.479  7645  7918 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 14:17:40.479  7645  7918 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 14:17:40.482  7645  7916 I bt-btu  : btu_task received preload complete event
08-26 14:17:40.483  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 14:17:40.483  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-26 14:17:40.491  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-26 14:17:40.494  7645  7945 D bt_userial_mct: Entering userial_read_thread()
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 14:17:40.496  7645  7916 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 14:17:40.497  7645  7916 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 14:17:40.497  7645  7916 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 14:17:40.497  7645  7916 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 14:17:40.497  7645  7916 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 14:17:40.566  7645  7916 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 14:17:40.566  7645  7916 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0217061 
,08-26 14:17:40.566  7645  7916 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0217061 
08-26 14:17:40.602  7645  7893 E bt-btif : Calling BTA_HhEnable
08-26 14:17:40.603  7645  7893 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-26 14:17:40.609  7645  7893 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 14:17:40.611  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 14:17:40.611  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-26 14:17:40.611  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-26 14:17:40.612  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 14:17:40.612  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-26 14:17:40.613  7645  7893 D BluetoothAdapterProperties: Name is: G3
08-26 14:17:40.614  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3,
08-26 14:17:40.615  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 14:17:40.618  7645  7893 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:40.619  7645  7893 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 14:17:40.619  7645  7893 D bt_hci_bdroid: postload
,08-26 14:17:40.628  7645  7918 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 14:17:40.629  7645  7916 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 14:17:40.630  7645  7893 D bte_conf: Device ID record 1 : primary
08-26 14:17:40.630  7645  7893 D bte_conf:   vendorId            = 00c4
08-26 14:17:40.630  7645  7893 D bte_conf:   vendorIdSource      = 0001
08-26 14:17:40.630  7645  7893 D bte_conf:   product             = 13a1
08-26 14:17:40.630  7645  7893 D bte_conf:   version             = 1000
08-26 14:17:40.630  7645  7893 D bte_conf:   clientExecutableURL = 
08-26 14:17:40.630  7645  7893 D bte_conf:   serviceDescription  = 
08-26 14:17:40.630  7645  7893 D bte_conf:   documentationURL    = 
08-26 14:17:40.630  7645  7893 D bte_conf: bte_load_did_conf no section named DID2.
08-26 14:17:40.631  7645  7918 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 14:17:40.634  7645  7889 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 14:17:40.634  7645  7889 D BluetoothAdapterProperties: ScanMode =  20
08-26 14:17:40.634  7645  7889 D BluetoothAdapterProperties: State =  11
08-26 14:17:40.637  7645  7889 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 14:17:40.638  7645  7889 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 14:17:40.638  7645  7889 D BluetoothAdapterProperties: Setting state to 12
08-26 14:17:40.638  7645  7889 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 14:17:40.641  7645  7893 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 14:17:40.635  7947  7947 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:40.644  1035  1117 D BluetoothManagerService: Message: 60
08-26 14:17:40.644  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 14:17:40.644  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 14:17:40.644  7645  7889 I BluetoothAdapterState: Entering On State
08-26 14:17:40.635  7947  7947 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:40.648  7645  7918 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 14:17:40.650  7645  7893 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 14:17:40.667  7645  7916 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:40.667  7645  7916 W bt-smp  : Plain text(LSB ~ MSB) = fe b3 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:40.667  7645  7916 W bt-smp  : Encrypted text(LSB ~ MSB) = 2b 78 f7 1e 76 3c 06 ed 3e 29 27 89 cf d5 3e 8d 
,08-26 14:17:40.670  7645  7918 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 14:17:40.670  7645  7916 W bt-btm  : Stopping oneshot timer
08-26 14:17:40.671  7645  7945 E bt_mct  : hci lib postload completed
08-26 14:17:40.673  7645  7889 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 14:17:40.673  7645  7889 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 14:17:40.674  7645  7889 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 14:17:40.674  7645  7889 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 14:17:40.691  7645  7916 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:40.691  7645  7916 W bt-smp  : Plain text(LSB ~ MSB) = 10 5e 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:40.691  7645  7916 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 83 a4 55 1d cf 22 ca 91 f5 cf e8 90 74 1e a5 
,08-26 14:17:40.694  7645  7916 W bt-btm  : Stopping oneshot timer
08-26 14:17:40.697  7645  7889 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 14:17:40.706  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:40.706  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:40.706  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:40.706  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:40.706  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:40.706  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:40.706  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:40.706  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:40.709  1861  1876 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:40.714  7645  7916 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:40.714  7645  7916 W bt-smp  : Plain text(LSB ~ MSB) = a2 6b 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:40.714  7645  7916 W bt-smp  : Encrypted text(LSB ~ MSB) = be c4 d9 e4 7c 20 64 91 5d 30 e6 4e 45 0f 26 54 
08-26 14:17:40.714  7645  7916 W bt-btm  : Stopping oneshot timer
08-26 14:17:40.717  7645  7893 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 14:17:40.717  7645  7893 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 14:17:40.721  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:40.726  7645  7916 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:40.726  7645  7916 W bt-smp  : Plain text(LSB ~ MSB) = 1d 3c 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:40.726  7645  7916 W bt-smp  : Encrypted text(LSB ~ MSB) = 00 f9 44 08 8f 36 ea 26 3c 2a 02 b1 9c a4 b5 ce 
08-26 14:17:40.726  7645  7916 W bt-btm  : Stopping oneshot timer
08-26 14:17:40.736  1861  1861 D BluetoothHeadset: Proxy object connected
,08-26 14:17:40.739  7645  7916 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 14:17:40.740  7645  7916 W bt-smp  : Plain text(LSB ~ MSB) = d3 18 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 14:17:40.742  7645  7916 W bt-smp  : Encrypted text(LSB ~ MSB) = f6 ce b8 70 65 3e dc 69 62 fc 6d 10 de 0e 3d c8 
08-26 14:17:40.742  7645  7916 W bt-btm  : Stopping oneshot timer
08-26 14:17:40.742  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:40.749  1035  1035 D BluetoothA2dp: Proxy object connected
,08-26 14:17:40.767  6837  6926 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 14:17:40.786  7952  7952 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-26 14:17:40.804  6837  6837 D BluetoothInputDevice: Proxy object connected
08-26 14:17:40.804  6837  6837 D HidProfile: Bluetooth service connected
08-26 14:17:40.804  1861  2443 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 14:17:40.809  6837  6853 D BluetoothPan: onBluetoothStateChange on: true
08-26 14:17:40.809  6837  6853 D BluetoothPan: onBluetoothStateChange call bindService
08-26 14:17:40.809  1861  1861 D BluetoothHeadset: Proxy object connected
08-26 14:17:40.811  6837  6926 D BluetoothMap: onBluetoothStateChange: up=true
08-26 14:17:40.812  6837  6837 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 14:17:40.812  6837  6837 D PanProfile: Bluetooth service connected
08-26 14:17:40.814  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:40.815  1035  1035 D BluetoothHeadset: Proxy object connected
08-26 14:17:40.815  6837  6852 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:40.818  1861  1876 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 14:17:40.822  1861  1861 D BluetoothHeadset: Proxy object connected
08-26 14:17:40.822  6837  6837 D BluetoothMap: Proxy object connected
08-26 14:17:40.822  6837  6837 D MapProfile: Bluetooth service connected
08-26 14:17:40.822  6837  6837 D BluetoothMap: getConnectedDevices()
08-26 14:17:40.822  6837  6853 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:40.823  7645  7662 V BluetoothMapService: getConnectedDevices()
08-26 14:17:40.824  6837  6837 D BluetoothHeadset: Proxy object connected
08-26 14:17:40.824  6837  6837 D HeadsetProfile: Bluetooth service connected
08-26 14:17:40.825  6837  6852 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 14:17:40.827  6837  6837 D BluetoothA2dp: Proxy object connected
08-26 14:17:40.827  6837  6837 D A2dpProfile: Bluetooth service connected
08-26 14:17:40.828  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 14:17:40.828  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 14:17:40.829  1953  1953 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:40.830  1953  2141 D LGBluetoothAPIService: Message: 1
08-26 14:17:40.830  1953  2141 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-26 14:17:40.832  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 14:17:40.840  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 14:17:40.840  1035  1117 D BluetoothManagerService: Message: 40
08-26 14:17:40.840  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 14:17:40.842  1953  2141 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-26 14:17:40.849  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:40.957  1035  1714 I art     : Explicit concurrent mark sweep GC freed 24963(1226KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.850ms total 115.330ms
,08-26 14:17:40.958  7645  7645 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:40.958  7645  7645 D BluetoothMapService: STATE_ON
08-26 14:17:40.958  6837  6837 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 14:17:40.960  6837  6837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 14:17:40.963  7645  7645 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 14:17:40.964  7645  7645 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 14:17:40.965  7645  7645 V BluetoothMapService: Handler(): got msg=1
08-26 14:17:40.966  1953  1953 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 14:17:40.966  1953  2141 D LGBluetoothAPIService: Message: 100
08-26 14:17:40.966  1953  2141 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 14:17:40.967  7645  7645 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 14:17:40.969  7645  7973 D BluetoothMapMasInstance: MAS initSocket()
08-26 14:17:40.969  7645  7973 D BluetoothMapMasInstance:   masId = 00
08-26 14:17:40.969  7645  7973 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 14:17:40.969  7645  7973 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 14:17:40.969  7645  7973 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 14:17:40.970  6837  6837 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:40.979  1035  1988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:40.980  7645  7973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:40.981  7645  7973 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 14:17:40.982  7645  7893 D BluetoothAdapterProperties: Scan Mode:21
,08-26 14:17:40.982  7645  7973 V BluetoothMapMasInstance: Succeed to create listening socket 
,08-26 14:17:40.982  7645  7893 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 14:17:40.985  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:40.985  7645  7973 D BluetoothMapMasInstance: Accepting socket connection...
08-26 14:17:41.000  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:41.000  7645  7645 V BluetoothPbapService: Pbap Service onCreate
08-26 14:17:41.000  7645  7645 V BluetoothPbapService: Starting PBAP service
,08-26 14:17:41.002  7645  7645 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 14:17:41.002  7645  7645 V BluetoothPbapService: Pbap Service onBind
08-26 14:17:41.003  6837  6837 D BluetoothPbap: Proxy object connected
,08-26 14:17:41.003  6837  6837 D PbapServerProfile: Bluetooth service connected
08-26 14:17:41.003  7645  7645 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:41.003  7645  7645 V BluetoothPbapService: state: 12
08-26 14:17:41.003  7645  7645 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 14:17:41.004  7645  7645 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:41.004  7645  7645 V BluetoothPbapReceiver: ***********state = 12
08-26 14:17:41.005  7645  7645 V BluetoothPbapService: Handler(): got msg=1
08-26 14:17:41.005  7645  7645 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 14:17:41.007  2227  2227 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:41.007  2227  2227 D c       : Getting all permits...
08-26 14:17:41.007  2227  2227 D a       : Opening database...
08-26 14:17:41.007  7645  7974 V BluetoothPbapService: Pbap Service initSocket
08-26 14:17:41.008  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:41.008  7645  7974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:41.009  7645  7974 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 14:17:41.009  7645  7974 V BluetoothPbapService: Succeed to create listening socket 
08-26 14:17:41.009  7645  7974 V BluetoothPbapService: Accepting socket connection...
08-26 14:17:41.011  2227  2227 D a       : Opening database auth.proximity.permit_store...
08-26 14:17:41.011  2227  2227 D a       : Closing database...
,08-26 14:17:41.021  6837  6837 D BluetoothPermissionRequest: onReceive
08-26 14:17:41.024  6837  6837 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 14:17:41.025  6837  6837 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 14:17:41.029  7645  7645 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-26 14:17:41.030  7645  7645 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 14:17:41.037  7645  7645 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 14:17:41.060  7645  7645 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 14:17:41.061  7645  7645 V BtOppService: onCreate
,08-26 14:17:41.065  7645  7645 V BluetoothOppNotification: send message
,08-26 14:17:41.069  7645  7645 V BtOppService: Starting RfcommListener
08-26 14:17:41.075  7645  7645 D BluetoothOppPreference: Dumping Names:  
08-26 14:17:41.075  7645  7645 D BluetoothOppPreference: {}
08-26 14:17:41.075  7645  7645 D BluetoothOppPreference: Dumping Channels:  
08-26 14:17:41.075  7645  7645 D BluetoothOppPreference: {}
08-26 14:17:41.078  7645  7645 V BtOppService: onStartCommand
,08-26 14:17:41.083  7645  7981 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 14:17:41.083  7645  7645 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:41.084  7645  7645 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 14:17:41.093  7645  7645 V BluetoothOppNotification: new notify threadi!
08-26 14:17:41.093  7645  7978 V BtOppService: Deleted complete outbound shares, number =  0
08-26 14:17:41.094  7645  7645 V BluetoothOppNotification: send delay message
08-26 14:17:41.095  7645  7645 V BtOppService: start RfcommListener
08-26 14:17:41.096  7645  7981 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-26 14:17:41.098  7645  7645 V BtOppService: RfcommListener started
08-26 14:17:41.100  7645  7978 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 14:17:41.101  7645  7981 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@aed73e on behalf of 
08-26 14:17:41.114  7645  7978 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-26 14:17:41.115  7645  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7fab99f on behalf of 
08-26 14:17:41.117  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
08-26 14:17:41.118  7645  7645 V BluetoothFtpService: Ftp Service onCreate
08-26 14:17:41.118  7645  7645 I BluetoothFtpService: Ftp Service onCreate
08-26 14:17:41.120  7645  7645 V BtOppService: ContentObserver received notification
08-26 14:17:41.120  7645  7645 V BluetoothFtpService: Ftp Service onStartCommand
08-26 14:17:41.121  7645  7981 V BluetoothOppNotification: update too frequent, put in queue
08-26 14:17:41.122  7645  7645 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:41.122  7645  7981 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 14:17:41.122  7645  7981 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 14:17:41.122  7645  7645 V BluetoothFtpService: Starting Listening on sockets
08-26 14:17:41.122  7645  7645 V BtOppService: ContentObserver received notification
08-26 14:17:41.123  7645  7645 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 14:17:41.123  7645  7645 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 14:17:41.123  7645  7645 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 14:17:41.123  7645  7981 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21f9deb5 on behalf of 
08-26 14:17:41.124  7645  7645 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:41.124  7645  7645 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 14:17:41.124  7645  7645 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 14:17:41.125  7645  7986 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 14:17:41.126  7645  7985 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 14:17:41.128  7645  7985 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e3d294a on behalf of 
08-26 14:17:41.128  7645  7981 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 14:17:41.129  7645  7981 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 14:17:41.129  7645  7985 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 14:17:41.129  1035  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:41.130  7645  7645 V BluetoothFtpService: Handler(): got msg=1
,08-26 14:17:41.135  7645  7645 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 14:17:41.136  7645  7645 V BluetoothFtpService: Ftp Service initSocket
08-26 14:17:41.137  7645  7986 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:41.138  7645  7986 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 14:17:41.139  7645  7986 V BtOppRfcommListener: Started RFCOMM listener....
08-26 14:17:41.139  7645  7986 I BtOppRfcommListener: Accept thread started.
08-26 14:17:41.139  7645  7986 V BtOppRfcommListener: Accepting connection...
08-26 14:17:41.139  7645  7981 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bdb50bb on behalf of 
08-26 14:17:41.140  1035  2056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:41.140  7645  7645 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:41.140  7645  7981 V BluetoothOppNotification: update too frequent, put in queue
08-26 14:17:41.140  7645  7985 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 14:17:41.141  7645  7645 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-26 14:17:41.142  7645  7645 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 14:17:41.143  7645  7981 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 14:17:41.145  7645  7987 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-26 14:17:41.148  7645  7985 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a9c89d8 on behalf of 
08-26 14:17:41.148  7645  7985 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 14:17:41.150  7645  7985 V BluetoothOppNotification: outbound notification was removed.
08-26 14:17:41.150  7645  7985 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 14:17:41.151  7645  7985 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bb6b131 on behalf of 
08-26 14:17:41.152  7645  7985 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 14:17:41.153  7645  7985 V BluetoothOppNotification: inbound notification was removed.
08-26 14:17:41.153  7645  7985 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 14:17:41.154  7645  7985 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23ac9016 on behalf of 
08-26 14:17:41.162  7645  7645 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11428dad
,08-26 14:17:41.162  7645  7645 V BluetoothSapService: Sap Service onCreate
08-26 14:17:41.164  7645  7645 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:41.164  7645  7645 V BluetoothSapService: state: 12
08-26 14:17:41.164  7645  7645 V BluetoothSapService: Starting SAP server process
,08-26 14:17:41.166  7645  7645 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 14:17:41.155  7988  7988 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:41.155  7988  7988 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:41.167  7645  7989 V BluetoothSapService: Sap Service initRfcommSocket
08-26 14:17:41.168  1035  1770 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:41.169  7645  7989 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:41.170  7645  7989 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-26 14:17:41.170  7645  7989 V BluetoothSapService: Succeed to create listening socket 
08-26 14:17:41.170  7645  7989 V BluetoothSapService: Accepting socket connection...
08-26 14:17:41.179  7988  7988 V BT_SAP  : Event pipe created
08-26 14:17:41.179  7988  7988 V BT_SAP  : create_server_socket qcom.sap.server
08-26 14:17:41.179  7988  7988 V BT_SAP  : created socket fd 6
,08-26 14:17:41.509  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:41.509  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:41.509  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:41.509  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:41.509  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:41.509  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:41.509  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:41.509  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:41.514  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:41.516  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:41.516  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a90bbb7 added. We now have 8 listener(s)
08-26 14:17:41.516  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:41.520  1035  2347 D WifiServiceImplEx: setWifiEnabled: false pid=6586, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 14:17:41.520  1035  2347 D WifiService: setWifiEnabled: false pid=6586, uid=10118
08-26 14:17:41.520  1035  2347 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 14:17:41.525  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:41.530  1035  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6586, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 14:17:41.530  1035  1050 D WifiService: setWifiEnabled: true pid=6586, uid=10118
08-26 14:17:41.530  1035  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 14:17:41.544  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-26 14:17:41.547  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-26 14:17:41.547  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-26 14:17:41.549  1035  1374 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-26 14:17:41.549  1035  1374 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 14:17:41.551  1035  1374 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 14:17:41.551  1035  1374 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
08-26 14:17:41.552  1035  1374 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 14:17:41.552  1035  1374 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 14:17:41.552  1035  1374 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-26 14:17:41.552  1035  1374 E WifiHW  : unknown target_country: EU , set to default
08-26 14:17:41.552  1035  1374 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 14:17:41.552  1035  1374 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 14:17:41.552  1035  1374 I WifiUtil: gEnableBmps=1
08-26 14:17:42.097  7645  7645 V BluetoothOppNotification: new notify threadi!,
08-26 14:17:42.098  7645  7645 V BluetoothOppNotification: send delay message
,08-26 14:17:42.141  7645  8005 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 14:17:42.152  7645  8005 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24d997a2 on behalf of 
08-26 14:17:42.153  7645  8005 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 14:17:42.154  7645  8005 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 14:17:42.155  7645  8005 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26251c33 on behalf of 
08-26 14:17:42.156  7645  8005 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-26 14:17:42.160  7645  8005 V BluetoothOppNotification: outbound notification was removed.
,08-26 14:17:42.160  7645  8005 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 14:17:42.162  7645  8005 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ed6bbf0 on behalf of 
08-26 14:17:42.162  7645  8005 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 14:17:42.164  7645  8005 V BluetoothOppNotification: inbound notification was removed.
08-26 14:17:42.164  7645  8005 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 14:17:42.165  7645  8005 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a515569 on behalf of 
08-26 14:17:42.217   317   904 D SoftapController: Softap fwReload - Ok
,08-26 14:17:42.228  1035  1374 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (672ms)
08-26 14:17:42.239   317   904 D CommandListener: Setting iface cfg
08-26 14:17:42.239   317   904 D CommandListener: Trying to bring down wlan0
,08-26 14:17:42.248   317   904 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:42.282  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 14:17:42.283  1035  1374 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 14:17:42.295  8007  8007 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 14:17:42.305  8007  8007 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 14:17:42.313  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:42.313  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 14:17:42.313  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 14:17:42.313  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 14:17:42.317  1035  1374 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 14:17:42.317  1035  1374 E WifiStateMachine: useWiFiOffloading() : false
08-26 14:17:42.317  1035  1374 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 14:17:42.326  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 14:17:42.330  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:42.330  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 14:17:42.330  1035  1374 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 14:17:42.330  1035  1374 D WifiMonitor: connecting to supplicant
08-26 14:17:42.346  8007  8007 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 14:17:42.347  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:42.359  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 14:17:42.361  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 14:17:42.361  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 14:17:42.361  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 14:17:42.361  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 14:17:42.361  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-26 14:17:42.362  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 14:17:42.362  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 14:17:42.395  8007  8007 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 14:17:42.396  8007  8007 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 14:17:42.399  1035  1117 D Tethering: InitialState.processMessage what=4
08-26 14:17:42.417  1035  2030 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8025 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 14:17:42.418  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 14:17:42.469  8007  8007 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 14:17:42.516  8007  8007 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 14:17:42.532  8007  8007 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-26 14:17:42.533  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 14:17:42.534  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 14:17:42.534  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 14:17:42.535  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 14:17:42.535  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-26 14:17:42.535  1035  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,08-26 14:17:42.535  1035  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 14:17:42.535  1035  1374 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 14:17:42.536  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:42.536  1035  1050 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8047 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 14:17:42.536  1035  1374 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:42.536  1035  1374 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:42.537  1035  1374 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:42.537  1035  1374 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 14:17:42.537  1035  1374 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 14:17:42.538  1035  1374 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 14:17:42.538  1035  1374 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 14:17:42.538  1035  1374 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 14:17:42.541  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:42.541  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:42.541  1035  1374 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 14:17:42.541  1035  1374 E WifiStateMachine: useWiFiOffloading() : false
08-26 14:17:42.541  1035  1374 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 14:17:42.541  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:42.541  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:42.541  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 14:17:42.543  1953  1953 D WfdService: Waiting for WifiP2p enabling
08-26 14:17:42.544  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 14:17:42.544  1035  1386 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-26 14:17:42.545  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:42.549  1035  1374 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 14:17:42.549  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:42.549  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:42.549  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:42.549  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:42.549  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:42.549  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:42.549  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:42.549  6586  6586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:42.549  1035  1374 D WifiNative-wlan0: SET update_config 1: returned true
08-26 14:17:42.549  1035  1374 D WifiConfigStore: Loading config and enabling all networks 
08-26 14:17:42.549  1035  1374 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 14:17:42.549  1035  1374 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 14:17:42.551  6586  6586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:42.556  1035  1374 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 14:17:42.559  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:42.559  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:42.559  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:42.559  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:42.559  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:42.559  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:42.559  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:42.559  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:42.564  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:42.565  1035  1374 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 14:17:42.566  1035  1374 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 14:17:42.568  1035  1374 D WifiStateMachine: enableVerboseLogging : level 2
08-26 14:17:42.568  1035  1374 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 14:17:42.568  1035  1374 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 14:17:42.568  1035  1374 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 14:17:42.569  1035  1374 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 14:17:42.569  1035  1374 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 14:17:42.569  1035  1374 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 14:17:42.569  1035  1374 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 14:17:42.569  1035  1374 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 14:17:42.570  1035  1374 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 14:17:42.570  6586  6695 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 14:17:42.570  1035  1374 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 14:17:42.570  1035  1374 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 14:17:42.570  1035  1374 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 14:17:42.570  1035  1374 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 14:17:42.570  6586  6695 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 14:17:42.571  1035  1374 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 14:17:42.572  1953  1953 D WfdsService: Supplicant Connection state is changed : true
08-26 14:17:42.572  1953  2310 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 14:17:42.572  1953  2310 D WfdsService: Set the WFDS Monitor: true
08-26 14:17:42.572  1953  2310 D WfdsMonitor: WfdsMonitorThread create
08-26 14:17:42.572  1035  1374 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 14:17:42.572  1035  1374 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 14:17:42.572  1953  2310 D WfdsMonitor: WFDS Monitor is created and started
08-26 14:17:42.572  1953  2310 D WfdsService: WiFi: Supplicant connection re-established
08-26 14:17:42.572  6586  6695 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@137152e1 Bundle[{}]
08-26 14:17:42.572  1035  1374 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 14:17:42.572  1035  1374 D WifiNative-HAL: Setting external_sim to 1
08-26 14:17:42.572  1035  1374 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 14:17:42.573  8025  8044 W FormManager: Network not available. Please check & try again.
08-26 14:17:42.573  1035  1374 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 14:17:42.573  1035  1374 I WifiNative-HAL: startHal
08-26 14:17:42.573  1035  1374 D wifi    : setting scan oui 0xaf6057c0
08-26 14:17:42.573  6586  6695 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 14:17:42.573  6586  6695 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 14:17:42.573  1035  1374 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 14:17:42.573  1035  1374 I WifiNative-HAL: startHal
08-26 14:17:42.573  1035  1374 D wifi    : setting scan oui 0xaf6057c0
08-26 14:17:42.574  1035  1374 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 14:17:42.574  1035  1374 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 14:17:42.574  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 14:17:42.574  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 14:17:42.575  1953  8066 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 14:17:42.575  1953  8066 E CtrlSupplicant: Succeed to open control connection
08-26 14:17:42.575  6586  6695 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 14:17:42.575  1953  8066 E CtrlSupplicant: Succeed to open monitor connection
08-26 14:17:42.576  6586  6695 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 14:17:42.576  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 14:17:42.577  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 14:17:42.577  6586  6695 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 14:17:42.577  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 14:17:42.578  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 14:17:42.578  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 14:17:42.578  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 14:17:42.578  1953  8066 D WfdsMonitor: Supplicant connection established
08-26 14:17:42.578  1953  2310 D WfdsService: Connected to the supplicant for wfds
08-26 14:17:42.578  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 14:17:42.578  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 14:17:42.578  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 14:17:42.579  6586  6695 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 14:17:42.579  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 14:17:42.579  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 14:17:42.579  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 14:17:42.580  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 14:17:42.580  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 14:17:42.580  8007  8007 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 14:17:42.580  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 14:17:42.580  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 14:17:42.580  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 14:17:42.581  7673  7673 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:42.581  1035  1374 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 14:17:42.581  8025  8045 V FormManager: Network unavailable.
08-26 14:17:42.582  1035  1374 E WifiNative: : [139,139,159 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 14:17:42.582  1035  1374 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 14:17:42.582  1035  1374 D WifiNative-wlan0: RECONNECT: returned true
08-26 14:17:42.582  1035  1374 D WifiNative-wlan0: doString: [STATUS]
08-26 14:17:42.583  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 14:17:42.583  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 14:17:42.583  1035  1374 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d add,ress=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 14:17:42.583  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 14:17:42.584  8025  8045 V FormManager: Network unavailable.
08-26 14:17:42.584  1035  1374 D WifiNative-wlan0: SET ps 1: returned true
08-26 14:17:42.584  1035  1373 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.584  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 14:17:42.584  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-26 14:17:42.584  1035  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.584  1035  1539 I WifiNative-HAL: startHal
08-26 14:17:42.585  1035  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf6057c0
08-26 14:17:42.585  1035  1539 D wifi    : failed to get capabilities : -3
08-26 14:17:42.585  1035  1539 E WifiScanningService: could not get scan capabilities
08-26 14:17:42.585  1035  1540 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.585  1035  1374 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 14:17:42.585  1035  1374 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 14:17:42.585   317   904 D CommandListener: Setting iface cfg
08-26 14:17:42.585   317   904 D CommandListener: Trying to bring up p2p0
08-26 14:17:42.586  1035  1374 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 14:17:42.586  1035  1373 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 14:17:42.586  1035  1373 D LGWifiP2pService: P2pEnablingState
08-26 14:17:42.586  1035  1373 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler },
08-26 14:17:42.586  1035  1373 D LGWifiP2pService: P2p socket connection successful
08-26 14:17:42.586  1035  1373 D LGWifiP2pService: P2pEnabledState
08-26 14:17:42.586  1035  1374 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 14:17:42.586  1035  1373 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 14:17:42.586  1035  1374 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 14:17:42.587  1035  1374 E WifiStateMachine:  ConnectModeState what:132106 1 0
,08-26 14:17:42.587  1035  1373 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 14:17:42.588  1953  1953 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 14:17:42.588  1035  1373 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 14:17:42.588  1953  1953 D WfdsService: WifiP2pState is changed : true
08-26 14:17:42.588  1953  2310 D WfdsService: Receive the WFDS_ENABLE Method
08-26 14:17:42.588  1035  1373 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 14:17:42.588  1953  2310 D WfdsService: Set the WFDS Monitor: true
08-26 14:17:42.588  1953  2310 D WfdsService: Connected to the supplicant for wfds
08-26 14:17:42.588  1953  2310 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 14:17:42.588  8007  8007 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 14:17:42.588  1035  1374 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 14:17:42.588  1035  1374 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 14:17:42.588  8007  8007 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 14:17:42.588  1035  1373 D WifiNative-p2p0: SET device_name G3: returned true
08-26 14:17:42.588  1035  1373 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 14:17:42.589  1035  1373 D LGWifiP2pService: before postfix = G3
08-26 14:17:42.589  1035  1373 D WifiServerServiceExt: postfix byte check : 2
08-26 14:17:42.589  1035  1373 D LGWifiP2pService: after postfix = G3
08-26 14:17:42.589  1035  1373 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 14:17:42.589  6586  6695 I System.out: Running OutgoingSocketThread
,08-26 14:17:42.589  1035  1373 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 14:17:42.589  1035  1373 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 14:17:42.589  1035  1373 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 14:17:42.589  1035  1373 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 14:17:42.590  1035  1373 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 14:17:42.590  1035  1373 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-26 14:17:42.590  1035  1373 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 14:17:42.590  1035  1373 D WifiNative-HAL: p2pGetDeviceAddress
08-26 14:17:42.590  1035  1373 D WifiNative-HAL: p2pGetDeviceAddress returning 
,08-26 14:17:42.590  1035  1373 D LGWifiP2pService: DeviceAddress: 
08-26 14:17:42.590  1035  1373 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 14:17:42.591  1953  2310 D WfdsService: selectPreferredScanChannel [36]
08-26 14:17:42.591  1953  2310 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 14:17:42.591  1035  1373 D WifiNative-p2p0: P2P_FLUSH: returned false
08-26 14:17:42.591  1035  1373 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 14:17:42.591  1953  1953 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 14:17:42.591  1035  1373 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-26 14:17:42.591  1035  1373 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 14:17:42.591  1953  1953 D WfdsService: isConnected: false
08-26 14:17:42.592  1035  1373 D WifiNative-p2p0:    returned OK
08-26 14:17:42.592  1035  1373 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 14:17:42.592  1035  1373 D WifiNative-p2p0: SAVE_CONFIG: returned false
08-26 14:17:42.592  1035  1373 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 14:17:42.593  1035  1373 D LGWifiP2pService: InactiveState
08-26 14:17:42.593  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.593  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.593  1035  1373 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 14:17:42.593  1953  1953 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 14:17:42.593  1953  1953 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 14:17:42.593  1953  1953 D WfdsService: Update P2p Interface State: 3
08-26 14:17:42.594  6586  8067 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
08-26 14:17:42.596  6586  8067 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 51531
08-26 14:17:42.596  6586  8067 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 14:17:42.600  1035  2347 I ActivityManager: Killing 7125:com.lge.drmservice/u0a62 (adj 15): empty #17
08-26 14:17:42.603  1035  1373 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.603  8007  8007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:42.603  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.604  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.604  1035  1373 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.604  8007  8007 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 14:17:42.604  1035  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 14:17:42.604  8007  8007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.604  1035  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:42.604  1035  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:42.604  1035  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:42.604  1035  1035 E WifiServerServiceExt: No p2p device connected
08-26 14:17:42.605  1953  2310 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 14:17:42.605  1035  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:42.605  1035  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.605  8007  8007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.605  1035  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.605  1035  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.605  1035  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:42.605  1035  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 14:17:42.605  1035  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.605  1035  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.606  1953  8066 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 14:17:42.606  1953  8066 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:42.606  1953  8066 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:42.606  1035  1374 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 14:17:42.607  1035  1374 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 14:17:42.607  1035  1374 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,08-26 14:17:42.607  1035  1374 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 14:17:42.608  8007  8007 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 14:17:42.608  1035  1374 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 14:17:42.609  1035  1374 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 14:17:42.609  1035  1374 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 14:17:42.609  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 14:17:42.609  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 14:17:42.610  8007  8007 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:42.610  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 14:17:42.610  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:42.610  1035  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:42.610  1035  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 14:17:42.610  8007  8007 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 14:17:42.610  8007  8007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.611  1035  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:42.611  1035  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.611  1035  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.611  1035  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.611  8007  8007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.611  1035  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:42.611  1035  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.611  1035  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.611  1035  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 14:17:42.612  1953  8066 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:42.612  1953  8066 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 14:17:42.613  1035  1374 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 14:17:42.613  1035  1373 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.613  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:42.613  1035  1374 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 14:17:42.614  1035  1374 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 14:17:42.614  1035  1374 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 14:17:42.614  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 14:17:42.614  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 14:17:42.614  8007  8007 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 14:17:42.614  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 14:17:42.614  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 14:17:42.614  1035  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 ,14:17:42.615  1035  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 14:17:42.615  1035  1374 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 14:17:42.615  1035  1374 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 14:17:42.615  1035  1374 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 14:17:42.615  1035  1374 D WifiNative-wlan0: doBoolean: SCAN
08-26 14:17:42.616  1035  1374 D WifiNative-wlan0: SCAN: returned false
08-26 14:17:42.616  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=139174  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 14:17:42.627  8047  8047 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 14:17:42.649  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=139207  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-26 14:17:42.649  1035  1374 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 14:17:42.650  1035  1374 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 14:17:42.650  1035  1374 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-26 14:17:42.650  1035  2030 W libprocessgroup: failed to open /acct/uid_10062/pid_7125/cgroup.procs: No such file or directory
08-26 14:17:42.650  1035  1374 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 14:17:42.651  1035  1374 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 14:17:42.652  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:42.652  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:42.652  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:42.653  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:42.653  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 14:17:42.653  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:42.654  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:42.655  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:42.655  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-26 14:17:42.661  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:42.662  1035  1988 I ActivityManager: Killing 7156:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 14:17:42.692  1035  1051 W libprocessgroup: failed to open /acct/uid_10085/pid_7156/cgroup.procs: No such file or directory
,08-26 14:17:42.701  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:42.701  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 14:17:42.702  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 14:17:42.702  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 14:17:42.702  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 14:17:42.703  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 14:17:42.703  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-26 14:17:42.703  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 14:17:42.703  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 14:17:42.703  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 14:17:42.703  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 14:17:42.711  8047  8047 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:42.717  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:42.720  8025  8071 W FormManager: Network not available. Please check & try again.
08-26 14:17:42.726  8025  8072 V FormManager: Network unavailable.
08-26 14:17:42.727  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:42.733  8025  8072 V FormManager: Network unavailable.
,08-26 14:17:42.756  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 14:17:42.757  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 14:17:42.759  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 14:17:42.761  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 ,
08-26 14:17:42.768  4285  8073 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 14:17:42.773  4285  8074 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 14:17:42.773  4285  8074 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 14:17:42.817  1035  1931 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8075 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 14:17:42.951  8075  8075 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 14:17:42.952  8075  8075 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-26 14:17:42.961  8075  8075 V [BNRBootReceiver]: Boot Receiver Return
08-26 14:17:42.963  8075  8075 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 14:17:43.039  1035  1952 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8096 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 14:17:43.042  1035  1952 I ActivityManager: Killing 7186:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-26 14:17:43.179  8007  8007 E wpa_supplicant: USIM:  scard_init function
,08-26 14:17:43.180  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 14:17:43.180  8007  8007 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 14:17:43.180  1035  8055 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 14:17:43.181  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 14:17:43.181  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-26 14:17:43.181  1035  8055 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 14:17:43.181  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 14:17:43.181  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 14:17:43.183  1035  1374 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 14:17:43.184  1035  1374 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 14:17:43.186  1035  1374 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,08-26 14:17:43.188  1035  1374 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 14:17:43.188  1035  1374 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 14:17:43.262  1035  1770 W libprocessgroup: failed to open /acct/uid_10093/pid_7186/cgroup.procs: No such file or directory
,08-26 14:17:43.288  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=139845  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 14:17:43.293  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.293  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:43.297  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.297  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.297  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 14:17:43.297  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.308  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.308  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.308  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 14:17:43.309  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=139859  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 14:17:43.310  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:43.310  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-26 14:17:43.319  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.319  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:43.321  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.326  8096  8096 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 14:17:43.326  8007  8007 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 14:17:43.327  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 14:17:43.327  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 14:17:43.327  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 14:17:43.327  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 14:17:43.328  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=139886  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 14:17:43.329  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=139886  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 14:17:43.329  1035  1374 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139887
08-26 14:17:43.330  1035  1374 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139887
,08-26 14:17:43.331  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 14:17:43.331  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:43.331  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:43.332  1035  1374 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139890
,08-26 14:17:43.332  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139890
08-26 14:17:43.333  1035  1374 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139891
08-26 14:17:43.335  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:43.335  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 14:17:43.336  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=139893  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 14:17:43.340  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:43.340  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.340  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 14:17:43.342  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.342  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:43.343  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=139900  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 14:17:43.343  1035  1374 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:43.343  1035  1374 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:43.344  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.344  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.344  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-26 14:17:43.346  8007  8007 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 14:17:43.346  8007  8007 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 14:17:43.348  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:43.348  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:43.348  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 14:17:43.348  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 14:17:43.348  1035  8055 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 14:17:43.348  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 14:17:43.348  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 14:17:43.348  1035  8055 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 14:17:43.348  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:43.348  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 14:17:43.349  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.350  1035  1374 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:43.350  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:43.351  1035  1374 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 14:17:43.351  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.351  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:43.351  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:43.351  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 14:17:43.351  1035  1374 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139909  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 14:17:43.352  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139910  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 14:17:43.353  1035  1374 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139911
08-26 14:17:43.353  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.353  1035  1374 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139911
08-26 14:17:43.354  1035  1374 D WifiNative-wlan0: doString: [STATUS]
08-26 14:17:43.355  1035  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 14:17:43.355  1035  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 14:17:43.355  1035  1374 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 14:17:43.357  1035  1374 I WifiServiceExtension: setVHTCapabilityType  : false
,08-26 14:17:43.370  1035  1374 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 14:17:43.370  1035  1374 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 14:17:43.376  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.376  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.377  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 14:17:43.377  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.377  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:43.378  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.383  8096  8096 D PluginManager: init()
08-26 14:17:43.389  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.389  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.389  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-26 14:17:43.390  1035  1374 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 14:17:43.390  1035  1374 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 14:17:43.390  1035  1374 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 14:17:43.390  1035  1429 D ConnectivityService: Got NetworkAgent Messenger
08-26 14:17:43.390  1035  1429 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 14:17:43.390  1035  1429 D ConnectivityService: NetworkAgent connected
08-26 14:17:43.390  1035  1374 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 14:17:43.390  1035  1374 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 14:17:43.395  1035  1374 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 14:17:43.395  1035  1374 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 14:17:43.395  1035  1374 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 14:17:43.396  1035  1374 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 14:17:43.396  1035  1374 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 14:17:43.400  1035  1374 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 14:17:43.401  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.401  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:43.402   317   904 D CommandListener: Setting iface cfg
08-26 14:17:43.402  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.407  1035  1374 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 14:17:43.407  1035  8120 D DhcpStateMachine: StoppedState
08-26 14:17:43.407  1035  8120 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.407  1035  8120 D DhcpStateMachine: WaitBeforeStartState
08-26 14:17:43.407  1035  1374 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139965  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:43.408  1035  1374 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139966  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:43.408  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139966  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:43.409  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:43.409  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 14:17:43.409  1035  1374 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:43.410  1035  1374 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139968  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:43.410  1035  1374 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139968  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 14:17:43.412  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:,3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14161] from screen [on:0 period:-959919117] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 14:17:43.413  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-959919116] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 14:17:43.413  1035  1374 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-26 14:17:43.419  1035  1429 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 14:17:43.419  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.419  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.420  1035  1374 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.420  1035  1374 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.420  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.421  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.421  1035  1429 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 14:17:43.421  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=162,0,0
08-26 14:17:43.422  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=162,0,0
08-26 14:17:43.422  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 14:17:43.422  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 14:17:43.422  1035  1374 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 14:17:43.423  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 14:17:43.423  1035  1374 D WifiNative-wlan0: SET ps 0: returned true
08-26 14:17:43.423  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 14:17:43.423  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 14:17:43.423  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 14:17:43.423  1035  1374 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 14:17:43.424  1035  1374 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 14:17:43.424  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e6ebecc target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.424  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e6ebecc target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.424  1035  8120 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.424  1035  8120 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 14:17:43.425  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.424  1035  1374 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 14:17:43.425   317   904 D CommandListener: Setting iface cfg
,08-26 14:17:43.426   317   904 D CommandListener: Trying to bring up wlan0
08-26 14:17:43.428  1035  1374 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 14:17:43.428  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:43.429  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 14:17:43.430  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 14:17:43.430  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 14:17:43.431  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.431  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.432  1035  1374 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.432  1035  1374 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.433  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.433  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 14:17:43.433  1035  1429 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 14:17:43.434  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 14:17:43.434  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 14:17:43.434  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 14:17:43.434  1035  1373 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.434  1035  1373 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.434  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 14:17:43.435  1035  1374 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 14:17:43.435  1035  1374 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 14:17:43.435  8007  8007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 14:17:43.435  1035  1374 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 14:17:43.435  1035  1374 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 14:17:43.451  1035  1374 D WifiNative-wlan0: SET ps 1: returned true
,08-26 14:17:43.451  1035  1429 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 14:17:43.452  1035  1374 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 14:17:43.452  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 14:17:43.452  1035  1374 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 14:17:43.453  1035  1429 D ConnectivityService: ignoring duplicate network state non-change
08-26 14:17:43.457  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.458  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.458  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 14:17:43.458  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.458  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:43.460  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.462  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.462  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.462  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 14:17:43.463  1035  1429 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 14:17:43.463  1035  1429 D ConnectivityService: Adding iface wlan0 to network 102
08-26 14:17:43.464  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.464  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 14:17:43.464  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 14:17:43.466  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 14:17:43.467  1953  1953 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 14:17:43.472  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.472  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.472  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 14:17:43.474  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 14:17:43.478  1035  1374 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 14:17:43.480  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:43.480  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.480  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 14:17:43.482  1035  1429 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 14:17:43.482  1035  1429 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 14:17:43.483  1035  1429 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 14:17:43.483   317   904 E Netd    : netlink response contains error (File exists)
08-26 14:17:43.484  1035  1429 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 14:17:43.484  1035  1429 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 14:17:43.484  1035  1429 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 14:17:43.484  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.484  1035  1429 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 14:17:43.484  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 14:17:43.485  1035  1429 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 14:17:43.485  1035  1429 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.485  1035  1429 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.485  1035  1429 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.485  1035  1429 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:43.485  1035  1429 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:43.485  1035  1429 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 14:17:43.485  1035  1429 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.486  1035  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.486  1035  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 14:17:43.486  1035  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.486  1035  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 14:17:43.487  1035  1429 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 14:17:43.487  1035  1429 D ConnectivityService: currentScore = 0, newScore = 20
08-26 14:17:43.487  1035  1429 D ConnectivityService:    accepting network in place of null
08-26 14:17:43.487  1035  1429 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.489  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.489  1035  1374 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.489  1035  1374 D WIFI   , :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:43.489  1035  1429 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 14:17:43.490  1035  1429 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 14:17:43.490  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 14:17:43.490   317  8124 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 14:17:43.491  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.491  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 14:17:43.491  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.492  1861  1861 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.492  1861  1861 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 14:17:43.493  1035  1429 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:43.493  1035  1429 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 14:17:43.493  1035  1429 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-26 14:17:43.493  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 14:17:43.493  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 14:17:43.493  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 14:17:43.494  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 14:17:43.494  1035  1429 D ConnectivityService: validation of new default Network = false
08-26 14:17:43.494  1035  1429 D ConnectivityService: Default network via Wi-Fi connected. start DSQN,
08-26 14:17:43.494  1035  1429 D DSQN    : enableDataServiceNotify 
08-26 14:17:43.494  1035  1429 D DSQN    : start dsqn bin
08-26 14:17:43.495  8125  8125 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:43.495  8125  8125 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 14:17:43.499  1035  1429 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.499  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.499  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:43.499  1035  1429 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:43.500  1586  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 14:17:43.511  1035  1372 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 14:17:43.511  8125  8125 E DSQN    : DSQN ssw
,08-26 14:17:43.523  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 14:17:43.524  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.525  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 14:17:43.544   317  8124 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 14:17:43.581   317  8124 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 14:17:43.591  6586  6695 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
08-26 14:17:43.592  6586  6695 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
08-26 14:17:43.600  6586  6695 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
,08-26 14:17:43.601  6586  6695 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 14:17:43.602  6586  6695 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
08-26 14:17:43.607  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 14:17:43.607  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f5bdf24 added. We now have 2 listener(s)
08-26 14:17:43.608  1035  2347 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.613  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.613  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.613  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.614  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.614  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f32a8d added. We now have 9 listener(s)
08-26 14:17:43.614  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.614   317   903 D LGDataListener: argv[0]=dsqncommand
08-26 14:17:43.614   317   903 D LGDataListener: argv[1]=wlan0
08-26 14:17:43.614   317   903 D LGDataListener: argv[2]=1
08-26 14:17:43.614   317   903 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-26 14:17:43.615  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
,08-26 14:17:43.615  1035  1115 D DSQN    : start to monitor internet connection
,08-26 14:17:43.615  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:43.622  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:43.626  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:43.626  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.626  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:43.626  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.626  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.626  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.626  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:43.626  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:43.626  1035  8120 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 14:17:43.627  1035  8120 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 14:17:43.627  1035  8120 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-26 14:17:43.629  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-26 14:17:43.630  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:43.625  8131  8131 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:43.625  8131  8131 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=7437 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 14:17:43.635  8131  8131 I dhcpcd  : version 5.5.6 starting
08-26 14:17:43.636  8131  8131 E dhcpcd  : get_duid: m
08-26 14:17:43.636  8131  8131 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 14:17:43.636  8131  8131 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 14:17:43.641  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.641  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.641  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6b5c53 added. We now have 3 listener(s)
08-26 14:17:43.641  1035  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.643  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.643  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.643  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.643  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.643  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@209c990 added. We now have 10 listener(s)
08-26 14:17:43.643  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.643  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:43.643  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:43.643  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:43.643  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.643  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.643  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:43.643  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.643  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f5bdf24 removed from the list
08-26 14:17:43.643  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.643  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager,@21f32a8d removed from the list
08-26 14:17:43.644  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.645  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop,
,08-26 14:17:43.645  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.645  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.645  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 14:17:43.645  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.645  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.645  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.646  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f32a8d not in the list
08-26 14:17:43.646  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.646  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-26 14:17:43.646  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.646  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.646  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.646  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@209c990 removed from the list
08-26 14:17:43.646  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.647  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.647  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.647  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.647  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6b5c53 removed from the list
08-26 14:17:43.647  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.647  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef4e289 added. We now have 2 listener(s)
08-26 14:17:43.647  1035  2347 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.649  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.649  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.649  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.649  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.649  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a40628e added. We now have 9 listener(s)
08-26 14:17:43.649  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.649  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:43.650  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:43.654  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:43.654  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.654  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:43.654  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.654  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.654  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.654  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:43.654  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:43.654  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.655  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:43.656  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.657  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.657  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.657  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d69eebc added. We now have 3 listener(s)
08-26 14:17:43.657  1035  1931 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.659  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.659  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.659  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.659  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.659  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e401e45 added. We now have 10 listener(s)
08-26 14:17:43.659  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.659  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:43.659  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 14:17:43.659  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:43.659  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:43.659  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:43.661  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:43.661  1035  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.664  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:43.666  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 14:17:43.666  1035  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 12:17:43 GMT], X-Android-Received-Millis=[1472213863666], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472213863613]}
08-26 14:17:43.666  1035  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 14:17:43.666  1035  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 14:17:43.667  1035  1429 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.667  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:43.667  1035  1429 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.667  1035  1429 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:43.667  1035  1429 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:43.667  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:43.667  1035  1429 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 14:17:43.667  1035  1429 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 14:17:43.667  1035  1429 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.667  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.667  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:43.668  1035  1429 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:43.668  6586  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 14:17:43.668  1035  1429 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.668  1586  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 14:17:43.668  1035  1429 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 14:17:43.669  1035  1374 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.669  1035  1374 D WIFI    :   my score=60, my filter,=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:43.669  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:43.669  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:43.670  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:43.670  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:43.670  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:43.671  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.671  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.671  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:43.671  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.671  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef4e289 removed from the list
08-26 14:17:43.671  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.671  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a40628e removed from the list
08-26 14:17:43.671  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:43.671  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.671  1861  1861 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:43.671  1861  1861 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-26 14:17:43.672  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.672  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.673  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.673  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.673  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.673  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a40628e not in the list
08-26 14:17:43.673  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.673  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.674  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.676  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:43.676  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:43.676  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.676  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.676  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e401e45 removed from the list
08-26 14:17:43.676  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.676  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.676  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.676  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.676  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d69eebc removed from the list
08-26 14:17:43.676  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.676  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8453aa8 added. We now have 2 listener(s)
08-26 14:17:43.676  1035  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.679  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.679  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.679  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.679  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.679  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@234959c1 added. We now have 9 listener(s)
08-26 14:17:43.679  6586  6695 D org.thaliproject.p2p.btconnectorlib.ut,ils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.680  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:43.682  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:43.687  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:43.687  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.687  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:43.687  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.687  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.687  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.687  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:43.687  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:43.688  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 14:17:43.688  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.689  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:43.689  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.689  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.689  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1200a7 added. We now have 3 listener(s)
08-26 14:17:43.690  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 14:17:43.690  1035  1931 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.691  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.693  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.694  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.695  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:43.695  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.695  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.695  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b075954 added. We now have 10 listener(s)
08-26 14:17:43.695  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.695  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:43.696  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:43.696  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:43.696  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:43.696  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:43.696  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:43.698  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:43.699  1035  2056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.702  8131  8131 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 14:17:43.702  8131  8131 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 14:17:43.702  8131  8131 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 14:17:43.702  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:43.702  8131  8131 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 14:17:43.702  8131  8131 D dhcpcd  : wlan0: sending REQUEST (xid 0x893996e2), next in 3.31 seconds
08-26 14:17:43.702  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:43.704  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:43.704  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:43.705  6586  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 14:17:43.705  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:43.706  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:43.706  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:43.706  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.706  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.706  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:43.706  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.706  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8453aa8 removed from the list
08-26 14:17:43.706  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.706  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@234959c1 removed from the list
08-26 14:17:43.706  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:43.706  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.706  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.706  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.707  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.707  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.707  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.707  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@234959c1 not in the list
08-26 14:17:43.707  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.707  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.708  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.708  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:43.708  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:43.708  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.708  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.708  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b075954 removed from the list
08-26 14:17:43.708  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.708  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.708  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.708  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.708  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1200a7 removed from the list
08-26 14:17:43.709  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.709  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36d40043 added. We now have 2 listener(s)
08-26 14:17:43.709  1035  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.710  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the ,following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.710  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.710  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.711  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.711  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@272ab6c0 added. We now have 9 listener(s)
08-26 14:17:43.711  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.711  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:43.712  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:43.714  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:43.714  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.714  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:43.714  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.714  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.714  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.714  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:43.714  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:43.715  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.715  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:43.715  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.715  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bd08b3e added. We now have 3 listener(s)
08-26 14:17:43.715  1035  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.717  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.717  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.717  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.717  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.717  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322c5d9f added. We now have 10 listener(s)
08-26 14:17:43.717  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.717  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: fal,se, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:43.717  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:43.717  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:43.717  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:43.717  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:43.721  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.722  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:43.722  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.723  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.725  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:43.726  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 14:17:43.727  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:43.728  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:43.730  6586  6695 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 14:17:43.732  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:43.732  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:43.732  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:43.732  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.732  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.732  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:43.732  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.732  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36d40043 removed from the list
08-26 14:17:43.732  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.732  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@272ab6c0 removed from the list
08-26 14:17:43.732  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:43.732  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.732  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.732  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.737  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.737  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.737  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.738  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@272ab6c0 not in the list
08-26 14:17:43.738  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.738  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.738  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.739  6586  6695 D BluetoothLeScanner: could not find callback wrapper
08-26 14:17:43.739  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:43.739  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.739  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.739  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322c5d9f removed from the list
08-26 14:17:43.739  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.739  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.739  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.739  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.739  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bd08b3e removed from the list
08-26 14:17:43.740  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.740  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc61d4a added. We now have 2 listener(s)
08-26 14:17:43.740  1035  2056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.742  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.742  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.742  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.742  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.742  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318334bb added. We now have 9 listener(s)
08-26 14:17:43.742  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.743  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:43.745  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:43.747  6586  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:43.747  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.747  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:17:43.747  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.747  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.747  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.747  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:43.747  6586  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:43.748  6586  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:43.749  6586  6695 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:43.750  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.751  6586  6586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.751  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.751  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24bb3531 added. We now have 3 listener(s)
08-26 14:17:43.752  1035  1583 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:17:43.753  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 14:17:43.754  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.754  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.754  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.754  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d0c416 added. We now have 10 listener(s)
08-26 14:17:43.754  6586  6695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.754  6586  6695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:43.754  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:43.754  6586  6695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:43.755  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.755  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.755  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:43.755  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.755  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc61d4a removed from the list
08-26 14:17:43.755  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.755  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318334bb removed from the list
08-26 14:17:43.755  6586  6695 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:43.755  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.755  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.755  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.756  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.756  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.756  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.756  6586  6695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318334bb not in the list
08-26 14:17:43.756  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.756  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.758  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.758  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.758  6586  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.758  6586  6695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d0c416 removed from the list
08-26 14:17:43.758  6586  6695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.758  6586  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.758  6586  6695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.758  6586  6695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.758  6586  6695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24bb3531 removed from the list
08-26 14:17:43.759  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 14:17:43.759  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 14:17:43.759  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 14:17:43.760  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:43.760  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 14:17:43.760  6586  6695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:43.772  6586  8138 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
08-26 14:17:43.772  6586  8138 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
08-26 14:17:43.772  6586  8138 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 14:17:43.775  6586  8139 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
08-26 14:17:43.775  6586  8139 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
08-26 14:17:43.775  6586  8139 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 14:17:43.779  6586  6695 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 14:17:43.779  6586  6695 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 14:17:43.779  6586  6695 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 14:17:43.779  6586  6695 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 14:17:43.779  6586  6695 D com.test.thalitest.ThaliTestRunner: Total duration: 22704 ms
08-26 14:17:43.780  6586  6695 I jxcore-log: *Native tests were executed*
08-26 14:17:43.780  6586  6695 I jxcore-log: 
08-26 14:17:43.781  6586  6695 I jxcore-log: Total number of executed tests:  80
08-26 14:17:43.781  6586  6695 I jxcore-log: 
08-26 14:17:43.781  6586  6695 I jxcore-log: Number of passed tests:  80
08-26 14:17:43.781  6586  6695 I jxcore-log: 
08-26 14:17:43.781  6586  6695 I jxcore-log: Number of failed tests:  0
08-26 14:17:43.781  6586  6695 I jxcore-log: 
08-26 14:17:43.781  6586  6695 I jxcore-log: Number of ignored tests:  0
08-26 14:17:43.781  6586  6695 I jxcore-log: 
08-26 14:17:43.782  6586  6695 I jxcore-log: Total duration:  22704
08-26 14:17:43.782  6586  6695 I jxcore-log: 
,08-26 14:17:43.782  6586  6695 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 14:17:43.782  6586  6695 I jxcore-log: 
08-26 14:17:43.791  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.791  6586  6695 I jxcore-log: 
08-26 14:17:43.793  8131  8131 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-26 14:17:43.796  6586  6586 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 14:17:43.798  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.798  6586  6695 I jxcore-log: 
08-26 14:17:43.800  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.800  6586  6695 I jxcore-log: 
08-26 14:17:43.801  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.801  6586  6695 I jxcore-log: 
08-26 14:17:43.802  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.802  6586  6695 I jxcore-log: 
08-26 14:17:43.803  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.803  6586  6695 I jxcore-log: 
08-26 14:17:43.806  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.806  6586  6695 I jxcore-log: 
08-26 14:17:43.808  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:43.808  6586  6695 I jxcore-log: 
08-26 14:17:43.809  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:43.809  6586  6695 I jxcore-log: 
08-26 14:17:43.810  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.810  6586  6695 I jxcore-log: 
08-26 14:17:43.811  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.811  6586  6695 I jxcore-log: 
08-26 14:17:43.813  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:43.813  6586  6695 I jxcore-log: 
08-26 14:17:43.814  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:43.814  6586  6695 I jxcore-log: 
08-26 14:17:43.814  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:43.814  6586  6695 I jxcore-log: 
08-26 14:17:43.815  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.815  6586  6695 I jxcore-log: 
08-26 14:17:43.816  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.816  6586  6695 I jxcore-log: 
08-26 14:17:43.817  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.817  6586  6695 I jxcore-log: 
08-26 14:17:43.818  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.818  6586  6695 I jxcore-log: 
08-26 14:17:43.818  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.818  6586  6695 I jxcore-log: 
08-26 14:17:43.819  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.819  6586  6695 I jxcore-log: 
08-26 14:17:43.820  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.820  6586  6695 I jxcore-log: 
08-26 14:17:43.821  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:43.821  6586  6695 I jxcore-log: 
08-26 14:17:43.821  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:43.821  6586  6695 I jxcore-log: 
08-26 14:17:43.822  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:43.822  6586  6695 I jxcore-log: 
,08-26 14:17:43.823  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.823  6586  6695 I jxcore-log: 
08-26 14:17:43.824  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.824  6586  6695 I jxcore-log: 
08-26 14:17:43.825  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.825  6586  6695 I jxcore-log: 
08-26 14:17:43.825  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.825  6586  6695 I jxcore-log: 
08-26 14:17:43.826  6586  6695 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:43.826  6586  6695 I jxcore-log: 
08-26 14:17:43.829  8096  8096 W ExternalStrings: load override strings
08-26 14:17:43.829  8096  8096 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:43.829  8096  8096 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:43.830  8096  8096 D StatusProvider: onCreate
,08-26 14:17:43.837  8131  8131 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 14:17:43.837  8131  8131 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-26 14:17:43.837  8131  8131 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 14:17:43.837  8131  8131 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 14:17:43.838  8131  8131 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 14:17:43.838  8131  8131 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 14:17:43.838  8131  8131 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 14:17:43.838  8131  8131 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 14:17:43.866  8096  8096 V Signer  : override build config not found
08-26 14:17:43.866  8096  8096 D Signer  : value of property debug is false
,08-26 14:17:43.911  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-26 14:17:43.912  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-26 14:17:43.912  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 14:17:43.912  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 14:17:43.912  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 14:17:43.913  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 14:17:43.913  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 14:17:43.913  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 14:17:43.913  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 14:17:43.914  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 14:17:43.914  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 14:17:43.914  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 14:17:43.915  8096  8096 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-26 14:17:43.928  8096  8096 V LGMDMManager: Create singleton instance
,08-26 14:17:43.988  8096  8096 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 14:17:44.041  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:44.043  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.056  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:44.069  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.069  8146  8146 D AndroidRuntime: 
08-26 14:17:44.069  8146  8146 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 14:17:44.071  8146  8146 D AndroidRuntime: CheckJNI is OFF
08-26 14:17:44.084  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 14:17:44.088  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.092  7860  7860 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:44.094  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-26 14:17:44.096  6837  6837 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 14:17:44.100  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.100  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.103  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:44.109  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.114  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:44.115  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.116  7860  7860 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 14:17:44.118  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.118  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.123  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:44.131  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.144  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 14:17:44.144  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.146  7860  7860 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:44.148  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:44.148  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 14:17:44.148  6837  6837 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 14:17:44.148  6837  6837 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 14:17:44.149  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 14:17:44.149  6837  6837 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 14:17:44.149  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 14:17:44.149  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 14:17:44.149  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 14:17:44.149  6837  6837 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 14:17:44.149  6837  6837 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 14:17:44.149  6837  6837 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 14:17:44.183  8146  8146 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 14:17:44.197  1035  1109 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-26 14:17:44.198  1035  1109 I ActivityManager: Killing 6586:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-26 14:17:44.229  1035  8120 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 14:17:44.229  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.229  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.231  1035  8120 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 14:17:44.231  1035  8120 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 14:17:44.231  1035  8120 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 14:17:44.231  1035  8120 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-26 14:17:44.231  1035  8120 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 14:17:44.231  1035  8120 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 14:17:44.231  1035  8120 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 14:17:44.231  1035  8120 D DhcpStateMachine: RunningState
08-26 14:17:44.232  8096  8162 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 14:17:44.265  1035  1050 I WindowState: WIN DEATH: Window{3aa29661 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 14:17:44.265  1035  1425 D WifiService: Client connection lost with reason: 4
08-26 14:17:44.273  1035  1050 D InputDispatcher: Window went away: Window{3aa29661 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 14:17:44.407  1035  1109 E libprocessgroup: failed to kill 1 processes for processgroup 6586
,08-26 14:17:44.413  1035  1109 I ActivityManager:   Force finishing activity ActivityRecord{20614381 u0 com.test.thalitest/.MainActivity t6}
,08-26 14:17:44.447   345   375 E GBMv2   : DFP En is all cleared set to be enabled
,08-26 14:17:44.468  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-26 14:17:44.473  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{20614381 u0 com.test.thalitest/.MainActivity t6 f}
08-26 14:17:44.474  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{20614381 u0 com.test.thalitest/.MainActivity t6 f}
,08-26 14:17:44.503  1035  1952 W ActivityManager: Spurious death for ProcessRecord{35042b39 6586:com.test.thalitest/u0a118}, curProc for 6586: null
,08-26 14:17:44.510  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-26 14:17:44.516  3802  3802 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-26 14:17:44.528  2007  2007 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 14:17:44.529  2468  2661 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 14:17:44.531  7645  7645 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
,08-26 14:17:44.531  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 14:17:44.532  4475  4475 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 14:17:44.533  4475  4475 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 14:17:44.533  4475  4475 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 14:17:44.533  4475  4475 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 14:17:44.533  4475  4475 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:44.533  4475  4475 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:44.534  4475  4475 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:44.534  4475  4475 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:44.534  4475  4475 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:44.534  4475  4475 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:44.534  4475  4475 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:44.534  1035  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 14:17:44.534  4475  4475 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:44.556  4584  4584 I art     : Explicit concurrent mark sweep GC freed 8193(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 762us total 71.106ms
08-26 14:17:44.556  1035  1107 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-26 14:17:44.574  1035  1952 V SIM_STK : Menu title from STK is T-Mobile
,08-26 14:17:44.610  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:44.615  1953  2558 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 14:17:44.615  1953  2558 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2081c403 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 14:17:44.616  2061  2061 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-26 14:17:44.617  1953  1970 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 14:17:44.618  2061  2061 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 14:17:44.618  1953  1970 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3e4b8f80 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-26 14:17:44.627  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.629  1035  1035 D administrator: Handling package changes for user 0
08-26 14:17:44.633  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 14:17:44.633  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-26 14:17:44.635  2061  2139 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-26 14:17:44.650  1915  1915 D ActionManagerService: notifyUserLog: 1000003
08-26 14:17:44.652  2061  2061 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 14:17:44.652  3802  4443 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-26 14:17:44.654  1586  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 14:17:44.654  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.654  2061  2061 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-26 14:17:44.658  2061  2061 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-26 14:17:44.659  1586  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 14:17:44.659  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.664  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 14:17:44.664  1586  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:44.664  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 14:17:44.666  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 14:17:44.673  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 14:17:44.673  1586  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 14:17:44.678  1586  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-26 14:17:44.678  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.684  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 14:17:44.684  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 14:17:44.686  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:44.686  2061  2061 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 14:17:44.688  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 14:17:44.688  1586  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 14:17:44.688  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.688  7860  7860 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:44.692  1586  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,08-26 14:17:44.692  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.700  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.701  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.703  1586  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:44.703  1586  1635 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 14:17:44.704  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 14:17:44.704  1586  1635 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 14:17:44.705  1915  1915 D ActionManagerService: notifyUserLog: 1000004
08-26 14:17:44.705  2061  2061 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-26 14:17:44.705  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 14:17:44.705  3802  4443 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 14:17:44.705  1586  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 14:17:44.707  3802  4436 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 14:17:44.710  1586  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 14:17:44.710  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.710  7573  7903 D UEI.SmartControl: Internal timer expired: 2
08-26 14:17:44.710  7573  7903 D UEI.SmartControl: unbind internal service
,08-26 14:17:44.712  1035  1769 V SIM_STK : Menu title from STK is T-Mobile
08-26 14:17:44.712  1035  1769 V SIM_STK : Menu title from STK is T-Mobile
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , expire_time: 0
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , display: false
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , animation: false }
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , expire_time: 0
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , display: false
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , animation: false }
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , create_time: 1471602816196
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , expire_time: 0
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , display: false
08-26 14:17:44.713  2061  2061 I GBoardWebViewUtils: , animation: false }
08-26 14:17:44.718  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 14:17:44.718  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 14:17:44.738  2061  8198 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-26 14:17:44.744  1586  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 14:17:44.744  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.746  1586  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 14:17:44.746  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.747  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 14:17:44.747  1586  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 14:17:44.748  1586  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 14:17:44.748  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.750  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 14:17:44.750  1586  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-26 14:17:44.751  1586  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 14:17:44.751  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.751  1881  1881 D SplitUIManager: split_name #11 / not available #0
08-26 14:17:44.752  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 14:17:44.752  1881  1881 D SplitUIService: removed split : 
08-26 14:17:44.752  1586  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 14:17:44.753  1586  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 14:17:44.753  1586  1635 D KeyguardModel: createShortcutInfo...
08-26 14:17:44.755  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-26 14:17:44.755  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 14:17:44.762  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 14:17:44.763  2061  2061 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 14:17:44.770  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:44.772  1881  1881 D SplitUIManager: split_name #11 / not available #0
08-26 14:17:44.772  1881  1881 I SplitUIService: split app #11
,08-26 14:17:44.778  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 14:17:44.778  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 14:17:44.779  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 14:17:44.779  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 14:17:44.779  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 14:17:44.779  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 14:17:44.779  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 14:17:44.779  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 14:17:44.779  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 14:17:44.780  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 14:17:44.780  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 14:17:44.780  7645  7645 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 14:17:44.783  1035  2347 V SIM_STK : Menu title from STK is T-Mobile
08-26 14:17:44.795  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 14:17:44.795  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 14:17:44.795  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 14:17:44.797  1035  1559 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 14:17:44.802  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.807  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:44.807  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 14:17:44.807  7860  7860 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:44.812  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.813  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.821  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-26 14:17:44.821  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-26 14:17:44.831  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:44.832  8096  8162 D LgDataFeature: LgDataFeature() Constructor: none
08-26 14:17:44.833  8096  8162 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 14:17:44.833  2061  2061 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-26 14:17:44.843  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.847  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:44.847  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.847  7860  7860 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:44.860  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 14:17:44.860  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.878  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:44.886  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.889  1035  1374 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:44.889  1035  1374 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:44.890  1035  1374 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:44.890  1035  1374 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 14:17:44.892  1035  1123 I art     : Explicit concurrent mark sweep GC freed 80825(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.457ms total 194.521ms
08-26 14:17:44.892  1035  1374 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:44.893  1035  1374 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 14:17:44.893  1035  1429 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 14:17:44.893  1035  1429 D ConnectivityService: identical MTU - not setting
08-26 14:17:44.893  1035  1429 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 14:17:44.893  1035  1429 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 14:17:44.893  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:44.893  1035  1429 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:44.895  1035  1429 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 14:17:44.895  1586  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 14:17:44.897  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:44.900  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.900  7860  7860 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:44.908  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.908  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 14:17:44.912  2061  2061 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-26 14:17:44.914  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 14:17:44.916  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 14:17:44.917  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 14:17:44.918  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:44.918  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 14:17:44.919  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-26 14:17:44.925  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.931  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:44.931  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.936  2061  2061 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 14:17:44.936  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 14:17:44.936  2061  2188 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 14:17:44.936  2061  2188 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-26 14:17:44.937  7860  7860 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:44.940  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{305efc0d u0 com.lge.launcher2/.Launcher t5} time:141512
,08-26 14:17:44.946  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.946  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.950  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-26 14:17:44.951  2061  2061 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 14:17:44.951  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 14:17:44.953  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:44.957  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.958  2061  2061 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-26 14:17:44.959  2564  2564 D [Concierge]Service: onStartCommand(). Type : 8
08-26 14:17:44.959  2564  2564 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 14:17:44.961  2564  2564 D [Concierge]Service: Update widget ID : 11
08-26 14:17:44.961  2061  2061 D [Concierge]WidgetView: change position of spinner
08-26 14:17:44.964  2061  2061 I [Concierge]WidgetView: initWebView(). Time : 1472213864964
08-26 14:17:44.964  2564  2564 D [Concierge]Service: onStartCommand(). Type : 0
,08-26 14:17:44.965  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:44.965  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.966  7860  7860 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 14:17:44.969  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.969  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 14:17:44.971  8047  8047 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 14:17:44.974  8047  8047 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:44.976  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 14:17:44.978  2061  2061 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 834305418
08-26 14:17:44.978  2061  2061 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 14:17:44.978  2061  2061 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-26 14:17:44.981  2061  2061 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1f25cb0a
08-26 14:17:44.981  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 14:17:44.982  8096  8162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-26 14:17:44.982  2061  2061 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 14:17:44.982  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 14:17:44.982  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:44.988  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-26 14:17:44.990  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:44.990  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:44.991  7860  7860 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 14:17:44.991  2061  2061 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 14:17:44.991  7860  7860 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 14:17:44.991  2061  2061 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 14:17:44.991  7860  7860 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 14:17:44.992  2061  2061 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472213751206, New one : 1472213864964
08-26 14:17:44.992  2061  2061 D [Concierge]WidgetView: Unregister all receivers
08-26 14:17:44.992  2061  2061 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 14:17:44.995  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 14:17:44.995  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 14:17:44.997  8047  8047 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 14:17:44.997  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 14:17:44.998  8047  8047 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 14:17:44.998  8096  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-26 14:17:44.999  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 14:17:45.000  6837  6837 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 14:17:45.000  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-26 14:17:45.002  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 14:17:45.003  8096  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 14:17:45.003  6837  6837 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 14:17:45.003  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 14:17:45.003  8096  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 14:17:45.004  8096  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 14:17:45.004  8096  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 14:17:45.005  8096  8162 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 14:17:45.005  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 14:17:45.006  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 14:17:45.006  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 14:17:45.010  7860  7860 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 14:17:45.010  7860  7860 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 14:17:45.010  7860  7860 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 14:17:45.011  7860  7860 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 14:17:45.011  7860  7860 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 14:17:45.012  8096  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-26 14:17:45.013  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 14:17:45.014  8096  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-26 14:17:45.015  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 14:17:45.016  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 14:17:45.017  8096  8096 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-26 14:17:45.017  8096  8163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 14:17:45.018  1035  1051 I ActivityManager: Killing 7227:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-26 14:17:45.056  1035  1107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:45.060  1035  1107 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 14:17:45.066  2061  2061 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 14:17:45.074  8146  8146 D AndroidRuntime: Shutting down VM
08-26 14:17:45.077  2061  2061 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 14:17:45.077  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-26 14:17:45.079  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 14:17:45.098  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-26 14:17:45.100  2061  2061 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2239ba87 time:141673
08-26 14:17:45.100  1035  2030 W libprocessgroup: failed to open /acct/uid_10005/pid_7227/cgroup.procs: No such file or directory
08-26 14:17:45.105  2227  2227 I ConfigService: onCreate
08-26 14:17:45.105  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 14:17:45.105  2227  2227 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-26 14:17:45.110  2227  2227 I ConfigService: onBind returning update interface
08-26 14:17:45.140  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8207 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 14:17:45.142  2227  2227 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 14:17:45.142  2227  2227 I ConfigService: onBind returning config service
08-26 14:17:45.143  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 14:17:45.148  7573  7900 D serial_port: close(fd = 24)
08-26 14:17:45.150  1803  1803 I ConfigFetchService: service connected
08-26 14:17:45.150  1803  1803 I ConfigClient: service connected
08-26 14:17:45.153  7573  7900 I UEI.SmartControl: Serial port is closed.
,08-26 14:17:45.156  2227  2227 I ConfigService: onDestroy
08-26 14:17:45.159  1803  8222 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
,08-26 14:17:45.207  5922  8233 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-26 14:17:45.214  1803  8234 I PeopleContactsSync: CP2 sync disabled
08-26 14:17:45.217  1803  4714 I Icing   : doRemovePackageData com.test.thalitest
08-26 14:17:45.234  1803  8232 W GmsApplication: Using Auth Proxy for data requests.
,08-26 14:17:45.239  1803  8232 W GmsApplication: Using Auth Proxy for data requests.
,08-26 14:17:45.257  7006  7006 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-26 14:17:45.257  2061  2061 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-26 14:17:45.268  1035  1934 I ActivityManager: Killing 7673:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 14:17:45.279  2227  2245 I art     : Explicit concurrent mark sweep GC freed 7741(435KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 737us total 28.846ms
,08-26 14:17:45.301  2061  2879 I GBoardtInterface: onReloaded()
,08-26 14:17:45.303  2061  2061 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 14:17:45.361  1035  2347 W libprocessgroup: failed to open /acct/uid_10072/pid_7673/cgroup.procs: No such file or directory
,08-26 14:17:45.369  3802  4436 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 14:17:45.374  2191  8238 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 14:17:45.409  2191  8238 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
,--------- beginning of crash
08-26 14:17:45.410  2191  8238 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 14:17:45.410  2191  8238 E AndroidRuntime: Process: android.process.acore, PID: 2191
08-26 14:17:45.410  2191  8238 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailStatusTable.delete(VoicemailStatusTable.java:100)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:45.410  2191  8238 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:45.423  1035  2056 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8240 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 14:17:45.429  2191  8238 I Process : Sending signal. PID: 2191 SIG: 9
08-26 14:17:45.430  3802  3818 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 14:17:45.468  1035  1050 I ActivityManager: Process android.process.acore (pid 2191) has died
08-26 14:17:45.468  1035  1050 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
08-26 14:17:45.468  1035  1050 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
,08-26 14:17:45.495  1803  8226 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-26 14:17:45.495  1803  8226 E DriveAsyncService: disk I/O error (code 3850)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:45.495  1803  8226 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: Can't write: system_app_crash
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 14:17:45.498  1035  8250 E DropBoxManagerService: 	... 5 more
08-26 14:17:45.499  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-26 14:17:45.500  3802  4443 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 14:17:45.500  3802  4443 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 14:17:45.504  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-26 14:17:45.505  3802  4443 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 14:17:45.505  3802  4443 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED,
08-26 14:17:45.505  3802  4443 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-26 14:17:45.505  3802  4443 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-26 14:17:45.506  3802  4436 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 14:17:45.508  8240  8240 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:45.508  8240  8240 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 14:17:45.509  2061  2061 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-26 14:17:45.509  2061  2061 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-26 14:17:45.509  8240  8240 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 14:17:45.509  8240  8240 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 14:17:45.511  2061  2061 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-26 14:17:45.511  2061  2061 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 14:17:45.514  2061  2061 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-26 14:17:45.514  2061  2061 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread$,H.handleMessage(ActivityThread.java:1344)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:45.628  8240  8240 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:45.630  8240  8240 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.630  8240  8240 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 14:17:45.631  8240  8240 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 14:17:45.632  8240  8240 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 14:17:45.632  8240  8240 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.632  8240  8240 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.632  8240  8240 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-26 14:17:45.632  8240  8240 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-26 14:17:45.632  8240  8240 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
,08-26 14:17:45.632  8240  8240 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-26 14:17:45.632  8240  8240 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 14:17:45.632  8240  8240 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
,08-26 14:17:45.633  8240  8240 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 14:17:45.633  8240  8240 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 14:17:45.633  8240  8240 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-26 14:17:45.633  8240  8240 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:45.633  8240  8240 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:45.633  8240  8240 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-26 14:17:45.634  8240  8240 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-26 14:17:45.634  8240  8240 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-26 14:17:45.634  8240  8240 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:45.650  8240  8240 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:45.651  8240  8240 D AndroidRuntime: Shutting down VM
08-26 14:17:45.653  8240  8240 E AndroidRuntime: FATAL EXCEPTION: main
08-26 14:17:45.653  8240  8240 E AndroidRuntime: Process: com.lge.email, PID: 8240
08-26, 14:17:45.653  8240  8240 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-26 14:17:45.653  8240  8240 E AndroidRuntime: 	... 11 more
,08-26 14:17:45.663  8240  8240 I Process : Sending signal. PID: 8240 SIG: 9
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: Can't write: system_app_crash
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 14:17:45.666  1035  8260 E DropBoxManagerService: 	... 5 more
,08-26 14:17:45.777  1035  1770 I ActivityManager: Process com.lge.email (pid 8240) has died

```
