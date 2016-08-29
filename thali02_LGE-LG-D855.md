#### Test 829140738625595_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 11:06:34.132  6503  6503 D DocsApplication: Installing DEX configuration.
08-29 11:06:34.154  6503  6503 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-29 11:06:34.159  6503  6503 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{8030cd3 com.google.android.apps.docs}
08-29 11:06:34.176  6503  6503 D TAG     : onCreate()
08-29 11:06:34.204  6503  6503 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-29 11:06:34.666   327   438 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-29 11:06:34.670  3206  6532 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 11:06:34.966  1800  4643 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-29 11:06:35.131  1800  4643 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-29 11:06:35.185  1800  4643 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-29 11:06:35.224  6533  6533 D AndroidRuntime: 
08-29 11:06:35.224  6533  6533 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 11:06:35.226  6533  6533 D AndroidRuntime: CheckJNI is OFF
08-29 11:06:35.369  6533  6533 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 11:06:35.375  1043  1924 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 11:06:35.403  1925  2721 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 11:06:35.408  1043  1924 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 11:06:35.409  1043  1924 D ActivityManager: setTaskToReturnTo : TaskRecord{1d87d1c1 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 11:06:35.410  1043  1924 D ActivityManager: setTaskToReturnTo : TaskRecord{1d87d1c1 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 11:06:35.411  1043  1924 D WindowStateEx: AppWindowTokenEx init.. 
08-29 11:06:35.412   333   362 E GBMv2   : DFP En is all cleared set to be enabled
08-29 11:06:35.448  1043  1924 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6564 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 11:06:35.450  6533  6533 D AndroidRuntime: Shutting down VM
08-29 11:06:35.495  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 11:06:35.496  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1245f3bf co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 11:06:35.496  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 11:06:35.496  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1cc72a8c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 11:06:35.529  6564  6564 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 11:06:35.603  6564  6564 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-29 11:06:35.610  6564  6564 I LibraryLoader: Loading: webviewchromium
08-29 11:06:35.612  6564  6564 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5883-5886)
08-29 11:06:35.613  6564  6564 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:06:35.642  6564  6564 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4c64ac5}
08-29 11:06:35.643  6564  6564 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:06:35.644  6564  6564 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 11:06:35.655  6564  6564 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 11:06:35.656  6564  6564 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 11:06:35.668  6564  6564 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-29 11:06:35.668  6564  6564 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 11:06:35.669  6564  6564 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 11:06:35.676   318  1368 V AudioPolicyService: registerClient() client 0xb0410820, uid 10118
08-29 11:06:35.683  1043  1119 D BluetoothManagerService: Message: 20
,08-29 11:06:35.683  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@385eb843:true
08-29 11:06:35.690  6564  6564 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:06:35.690  6564  6564 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:06:35.690  6564  6564 I Adreno-EGL: Build Date: 12/12/14 금
,08-29 11:06:35.690  6564  6564 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:06:35.690  6564  6564 I Adreno-EGL: Remote Branch: 
08-29 11:06:35.690  6564  6564 I Adreno-EGL: Local Patches: 
08-29 11:06:35.690  6564  6564 I Adreno-EGL: Reconstruct Branch: 
08-29 11:06:35.712  6503  6503 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:06:35.712  6503  6503 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:06:35.768  6564  6597 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 11:06:35.769  6564  6564 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 11:06:35.779  6564  6564 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:06:35.783  6564  6564 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 11:06:35.785  6564  6564 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 11:06:35.787  6564  6564 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 11:06:35.787  6564  6564 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-29 11:06:35.796  6564  6564 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-29 11:06:35.801  6564  6564 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 11:06:35.801  6564  6564 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:06:35.819  6564  6611 D OpenGLRenderer: Render dirty regions requested: true
08-29 11:06:35.819  6564  6611 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 11:06:35.823  6564  6611 D OpenGLRenderer: Enabling debug mode 0
08-29 11:06:35.827  6564  6564 D Atlas   : Validating map...
,08-29 11:06:35.830  1043  1960 D SplitWindow: check instance of lgWin Window{13e11b25 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 11:06:35.871  6089  6089 I LockScreenSettings: New app installed broadcast received ..
,08-29 11:06:35.874  6089  6089 I LockScreenSettings: Number of installed packages  1
08-29 11:06:35.883  6564  6609 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 11:06:35.883  6564  6609 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:06:35.891  6564  6564 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39a6b458 time:106165
08-29 11:06:35.896  6503  6503 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-29 11:06:35.914  1043  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +421ms (total +502ms)
08-29 11:06:35.914  1043  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{31034d66 u0 com.test.thalitest/.MainActivity t6} time:106188
08-29 11:06:35.947  1043  1997 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:06:35.997  1043  1996 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6631 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:06:36.027  6564  6564 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 11:06:36.027  6564  6564 I chromium: 
,08-29 11:06:36.050  6564  6564 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 11:06:36.070  6631  6631 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 11:06:36.071  6631  6631 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 11:06:36.124  1043  1924 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6648 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 11:06:36.125  1043  1924 I ActivityManager: Killing 5813:com.google.android.gm/u0a64 (adj 15): empty #17
,08-29 11:06:36.132  6564  6609 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 11:06:36.132  6564  6609 I chromium: 
08-29 11:06:36.217  1043  1870 W libprocessgroup: failed to open /acct/uid_10064/pid_5813/cgroup.procs: No such file or directory
,08-29 11:06:36.265  6564  6665 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-29 11:06:36.279  6564  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 11:06:36.279  6564  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 11:06:36.279  6564  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 11:06:36.279  6564  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 11:06:36.279  6564  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 11:06:36.280  6564  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21edc99c added. We now have 1 listener(s)
08-29 11:06:36.285  1043  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:36.288  6564  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 11:06:36.295  6564  6665 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-29 11:06:36.301  6564  6665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:06:36.302  6564  6665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 11:06:36.312  6564  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@355e432b added. We now have 1 listener(s)
,08-29 11:06:36.313  6564  6665 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:36.314  6648  6648 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-29 11:06:36.318  1043  1526 D WifiService: New client listening to asynchronous messages
08-29 11:06:36.321  6564  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:06:36.322  6564  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 11:06:36.323  6564  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 11:06:36.324  6564  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 11:06:36.324  6564  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 11:06:36.330  6564  6665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:36.331  1043  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:36.332  6564  6665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 11:06:36.341  6564  6665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 11:06:36.341  6564  6665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:36.341  6564  6665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:36.341  6564  6665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:36.341  6564  6665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:36.341  6564  6665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:36.341  6564  6665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:36.341  6564  6665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:36.341  6564  6665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:36.341  6564  6665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 11:06:36.341  6564  6665 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:06:36.344  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:36.344  6564  6665 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 11:06:36.345  6648  6648 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 11:06:36.345  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 11:06:36.345  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:36.381  6564  6564 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 11:06:36.386  6378  6378 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 11:06:36.388  1043  1942 I ActivityManager: Killing 5870:com.google.android.talk/u0a72 (adj 15): empty #17
08-29 11:06:36.468  2783  2783 I MusicWidget: mDelayedStopHandler : unbind
,08-29 11:06:36.479  1043  1729 W libprocessgroup: failed to open /acct/uid_10072/pid_5870/cgroup.procs: No such file or directory
08-29 11:06:36.486  2132  2132 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 11:06:36.487  2132  2132 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
,08-29 11:06:36.489  2132  2132 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 11:06:36.494  2132  2132 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 11:06:36.495  2132  2132 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 11:06:36.496  2132  2132 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 11:06:36.502  2132  2132 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
,08-29 11:06:36.502  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-29 11:06:36.505  1043  1906 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2697afcacom.lge.music.MediaPlaybackService$5@2661953b
08-29 11:06:36.507  2132  2132 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 11:06:36.509  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.512  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.513  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.514  2132  2132 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2d45ce41
08-29 11:06:36.514  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-29 11:06:36.518  2132  2132 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 11:06:36.518  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.519  2132  2132 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 11:06:36.519  2132  2132 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 11:06:36.519  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.520  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.521  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.521  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.522  2132  2132 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 11:06:36.523  2132  2132 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-29 11:06:36.524  2132  2132 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 11:06:36.525  2132  2132 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 11:06:36.525  2132  2132 V MediaPlayer[Native]: reset
08-29 11:06:36.532  2132  2132 V MediaPlayer[Native]: setListener
08-29 11:06:36.532  2132  2132 V MediaPlayer[Native]: disconnect
08-29 11:06:36.532  2132  2132 V MediaPlayer[Native]: destructor
08-29 11:06:36.532   318  1368 V AudioFlinger: releasing 18 from 2132 for -1
08-29 11:06:36.532   318  1368 V AudioFlinger:  decremented refcount to 0
08-29 11:06:36.532   318  1368 V AudioFlinger: purging stale effects
08-29 11:06:36.532  2132  2132 V MediaPlayer[Native]: disconnect
08-29 11:06:36.534  2132  2132 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-29 11:06:36.535   333   364 E GBMv2   : DFP En is all cleared set to be enabled
08-29 11:06:36.535   333   364 E GBMv2   : Set value is all cleared set the max
08-29 11:06:36.535   333   364 I GBMv2   : DFP Enabled. Ignore VFP set
08-29 11:06:36.537  2132  2132 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 11:06:36.538  2132  2132 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 11:06:36.539  2132  2132 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 11:06:36.540  2132  2132 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 11:06:36.540  2132  2132 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 11:06:36.540  2132  2132 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 967226456
08-29 11:06:36.540  2132  2132 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 967226456
08-29 11:06:36.550  2132  2132 I SmartShareClient: [SmartShareManagerClient] terminate service: 2132/MediaPlaybackService/417833775
08-29 11:06:36.554  2132  2132 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 11:06:36.554  2132  2132 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@2afdc9b1
,08-29 11:06:36.557  2132  2132 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 11:06:36.557  2132  2132 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 11:06:36.558  2132  2132 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 11:06:36.559  2132  2132 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 11:06:36.566  2132  2132 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
08-29 11:06:36.567  1043  1729 I ActivityManager: Killing 5633:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-29 11:06:36.586  5606  5606 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-29 11:06:36.586  5606  5606 W System.err: android.os.DeadObjectException
08-29 11:06:36.587  5606  5606 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 11:06:36.587  5606  5606 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 11:06:36.587  5606  5606 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 11:06:36.587  5606  5606 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 11:06:36.587  5606  5606 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 11:06:36.587  5606  5606 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 11:06:36.587  5606  5606 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:06:36.587  5606  5606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:06:36.587  5606  5606 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:06:36.588  5606  5606 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:06:36.588  5606  5606 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:36.588  5606  5606 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:06:36.588  5606  5606 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:06:36.588  5606  5606 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:06:36.589  5606  5606 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 11:06:36.589  5606  5606 W System.err: android.os.DeadObjectException
08-29 11:06:36.589  5606  5606 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 11:06:36.589  5606  5606 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 11:06:36.589  5606  5606 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 11:06:36.589  5606  5606 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 11:06:36.589  5606  5606 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 11:06:36.589  5606  5606 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 11:06:36.589  5606  5606 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:06:36.590  5606  5606 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-29 11:06:36.590  5606  5606 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:06:36.590  5606  5606 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:06:36.590  5606  5606 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:36.590  5606  5606 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-29 11:06:36.590  5606  5606 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:06:36.590  5606  5606 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:06:36.590  5606  5606 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,08-29 11:06:36.590  5606  5606 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 11:06:36.798  1043  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_5633/cgroup.procs: No such file or directory
08-29 11:06:36.799  1043  1906 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 11:06:36.814  5606  5606 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 11:06:36.815  5606  5606 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-29 11:06:36.868  1043  1639 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6671 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 11:06:36.868  5606  5606 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 11:06:36.942  6671  6671 D UEI.SmartControl: Quickset Services start...
,08-29 11:06:36.944  6671  6671 I UEI.SmartControl: Manufacture = LGE
08-29 11:06:36.944  6671  6671 D UEI.SmartControl: Id = LGNevo
08-29 11:06:36.945  6671  6671 D UEI.SmartControl: File observer start...
08-29 11:06:36.946  6671  6671 E UEI.SmartControl: IR Port is disabled: false
08-29 11:06:36.946  6671  6671 D UEI.SmartControl: Starting file observer...
08-29 11:06:36.946  6671  6671 D UEI.SmartControl: Extracting JNI libs...
08-29 11:06:36.947  6671  6671 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 11:06:37.026  6671  6671 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 11:06:37.027  6671  6671 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 11:06:37.027  6671  6671 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 11:06:37.054  6671  6671 I UEI.SmartControl: --- Selecting new region: 6
08-29 11:06:37.055  6671  6671 I UEI.SmartControl: Model = LG-D855
,08-29 11:06:37.057  6671  6671 D UEI.SmartControl: QS Service created
08-29 11:06:37.069  6671  6671 I UEI.SmartControl: Service initServices...
,08-29 11:06:37.072  6671  6671 D UEI.SmartControl: QS start get config
08-29 11:06:37.118  6671  6671 D UEI.SmartControl: Loading JNI Libs...
,08-29 11:06:37.330  6564  6668 W jxcore-log: Initializing JXcore engine
08-29 11:06:37.330  6564  6668 W jxcore-log: JXcore engine is ready
,08-29 11:06:37.338  6671  6671 I UEI.SmartControl: Supports setup maps: true
08-29 11:06:37.341  6671  6671 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 11:06:37.341  6671  6671 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 11:06:37.341  6671  6671 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 11:06:37.341  6671  6671 I UEI.SmartControl: ### init IR Blaster...
08-29 11:06:37.346  6671  6671 D serial_port: Configuring serial port
08-29 11:06:37.349  6671  6671 E UEI.SmartControl: UEIBLaster setting for 616
08-29 11:06:37.349  6671  6671 I UEI.SmartControl: Setting serial record hearder size = 2
,08-29 11:06:37.352  6671  6671 I UEI.SmartControl: configuring settings for MAXQ616
08-29 11:06:37.352  6671  6671 I UEI.SmartControl: Get version...
08-29 11:06:37.368  6671  6689 D UEI.SmartControl: serial port data available: 21
,08-29 11:06:37.394  6671  6671 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 11:06:37.394  6671  6671 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 11:06:37.395  6671  6671 I UEI.SmartControl: QS saving settings...
08-29 11:06:37.395  6671  6671 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 11:06:37.414  6671  6689 D UEI.SmartControl: serial port data available: 4
,08-29 11:06:37.413  6668  6668 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8413]" dev="sockfs" ino=8413 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 11:06:37.413  6668  6668 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 11:06:37.413  6668  6668 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8454]" dev="sockfs" ino=8454 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 11:06:37.413  6668  6668 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 11:06:37.413  6668  6668 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31410]" dev="sockfs" ino=31410 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-29 11:06:37.435  6564  6668 W jxcore-log: Starting JXcore engine
,08-29 11:06:37.447  6671  6692 I UEI.SmartControl: Device manager: loading config....
08-29 11:06:37.447  6671  6692 D UEI.SmartControl: ----------- loading internal config...
,08-29 11:06:37.451  6671  6671 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 11:06:37.453  6671  6671 E UEI.SmartControl: Services init done
08-29 11:06:37.453  6671  6671 D UEI.SmartControl: QS Service init finished
08-29 11:06:37.455  6671  6671 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 11:06:37.455  6671  6671 D UEI.SmartControl: QS Service version code: 201091
08-29 11:06:37.457  6671  6692 E UEI.SmartControl: Loading SETTINGS...
08-29 11:06:37.457  6671  6671 D UEI.SmartControl: Service requested: Control
08-29 11:06:37.459  5606  5606 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 11:06:37.460  6671  6686 I UEI.SmartControl: ------ IControl API: 11
08-29 11:06:37.460  1043  1558 I ActivityManager: Killing 5606:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 11:06:37.461  6671  6686 I UEI.SmartControl: Registering callback...
,08-29 11:06:37.469  6671  6692 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 11:06:37.486  6671  6691 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 11:06:37.487  6671  6691 D UEI.SmartControl: -----service ready thread exits
,08-29 11:06:37.561  6564  6668 W jxcore-log: Platform android
08-29 11:06:37.561  6564  6668 W jxcore-log: 
08-29 11:06:37.561  6564  6668 W jxcore-log: Process ARCH arm
08-29 11:06:37.561  6564  6668 W jxcore-log: 
,08-29 11:06:37.592  1043  1852 W libprocessgroup: failed to open /acct/uid_10112/pid_5606/cgroup.procs: No such file or directory
,08-29 11:06:37.592  6671  6671 D UEI.SmartControl: Internal service binding...
,08-29 11:06:37.753  6564  6668 I jxcore-log: JXcore Cordova bridge is ready!
08-29 11:06:37.753  6564  6668 I jxcore-log: 
08-29 11:06:37.753  6564  6668 W jxcore-log: JXcore engine is started
,08-29 11:06:37.766  6564  6665 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 11:06:37.774  6564  6564 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-29 11:06:39.799  6503  6503 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-29 11:06:39.802  1043  1996 I ActivityManager: Killing 6210:com.android.calendar/u0a13 (adj 15): empty #17
,08-29 11:06:39.888  1043  1888 W libprocessgroup: failed to open /acct/uid_10013/pid_6210/cgroup.procs: No such file or directory
,08-29 11:06:40.783  6503  6599 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 11:06:42.451  6671  6693 D UEI.SmartControl: Internal timer expired: 1
,08-29 11:06:42.451  6671  6693 D UEI.SmartControl: unbind internal service
,08-29 11:06:42.465  6671  6671 D UEI.SmartControl: Service.onUnbind: IControl
,08-29 11:06:42.468  6671  6671 D UEI.SmartControl: Service.onDestroy
08-29 11:06:42.468  6671  6671 D UEI.SmartControl: Lock is in USE false
08-29 11:06:42.468  6671  6671 D UEI.SmartControl: unbind internal service
08-29 11:06:42.469  6671  6671 D serial_port: close(fd = 25)
08-29 11:06:42.472  6671  6671 I UEI.SmartControl: Serial port is closed.
,08-29 11:06:42.472  6671  6671 I UEI.SmartControl: Serial port is closed.
08-29 11:06:42.472  6671  6671 D UEI.SmartControl: Blaster closed
08-29 11:06:42.473  6671  6671 D UEI.SmartControl: Shut down QS...
08-29 11:06:42.473  6671  6671 D UEI.SmartControl: Stopping QS lib
08-29 11:06:42.473  6671  6671 D UEI.SmartControl: QS lib stop result = true
08-29 11:06:42.473  6671  6671 D UEI.SmartControl: Stopped QS lib
08-29 11:06:42.474  6671  6671 D UEI.SmartControl: Stopped file observer...
08-29 11:06:42.474  6671  6671 D UEI.SmartControl: QS shutdown complete
08-29 11:06:43.182  1800  6411 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-29 11:06:43.187   314  6725 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-29 11:06:43.187   314  6725 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-29 11:06:43.188   314  6725 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-29 11:06:43.404  1800  1800 I ConfigFetchService: fetch service done; releasing wakelock
,08-29 11:06:43.412  1800  1800 I ConfigFetchService: stopping self
08-29 11:06:43.421  2176  2176 I ConfigService: onDestroy
,08-29 11:06:46.578  2132  2132 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19981
,08-29 11:06:47.689  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 11:06:47.689  6564  6668 I jxcore-log: 
,08-29 11:06:47.692  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 11:06:47.692  6564  6668 I jxcore-log: 
08-29 11:06:47.697  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:47.697  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:47.697  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:47.697  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:47.697  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:47.697  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:47.697  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:47.697  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:47.699  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:47.702  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 11:06:47.702  6564  6668 I jxcore-log: 
08-29 11:06:47.703  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 11:06:47.703  6564  6668 I jxcore-log: 
,08-29 11:06:48.210  6564  6668 D executeNativeTests: Running unit tests
,08-29 11:06:48.290  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:06:48.290  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c added. We now have 2 listener(s)
,08-29 11:06:48.291  1043  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:06:48.292  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-29 11:06:48.292  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:06:48.292  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:06:48.292  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 11:06:48.292  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 added. We now have 2 listener(s),
08-29 11:06:48.292  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-29 11:06:48.293  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:06:48.295  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:06:48.296  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 11:06:48.296  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.296  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.296  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:48.296  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:48.296  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.296  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-29 11:06:48.296  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.297  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.298  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:06:48.299  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:48.299  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:48.302  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:06:48.304  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:06:48.304  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 11:06:48.306  6564  6668 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
08-29 11:06:48.307  1043  1115 I ActivityManager: Waited long enough for: ServiceRecord{2abfd3a9 u0 com.google.android.gms/.wearable.service.WearableService}
08-29 11:06:48.308  6564  6668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:06:48.308  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 11:06:48.308  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:06:48.308  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 11:06:48.308  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.309  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.309  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.309  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:48.309  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.310  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:48.310  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:06:48.310  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c removed from the list
08-29 11:06:48.310  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.310  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 removed from the list
08-29 11:06:48.310  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.310  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:48.310  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.311  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.311  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.311  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:06:48.311  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.311  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.313  6564  6668 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 11:06:48.313  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.313  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:06:48.313  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.314  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.314  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.314  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.314  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
,08-29 11:06:48.314  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.314  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.314  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.314  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:48.314  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.314  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.314  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.315  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:06:48.315  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.315  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.315  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
,08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 11:06:48.320  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:06:48.321  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-29 11:06:48.321  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:06:48.321  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 11:06:48.321  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:06:48.321  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 11:06:48.321  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-29 11:06:48.321  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 11:06:48.321  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.322  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.322  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.322  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 11:06:48.322  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.322  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.322  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.322  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:48.322  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.322  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.322  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.323  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.323  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 11:06:48.323  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.324  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.324  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.324  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:48.324  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.324  6564  6668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:06:48.326  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:48.328  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:48.328  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.328  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.328  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-29 11:06:48.328  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:48.328  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.328  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:48.328  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.329  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.329  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:06:48.330  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 11:06:48.331  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 11:06:48.331  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:06:48.331  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:06:48.331  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:06:48.331  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:06:48.331  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:06:48.334  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:06:48.334  1043  1639 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:48.338  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:06:48.341  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:06:48.342  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
08-29 11:06:48.344  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:06:48.344  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:48.345  6564  6668 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:06:48.345  6564  6668 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 11:06:48.347  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.347  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.347  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:48.347  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.347  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.347  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:48.347  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.347  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 11:06:48.347  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.347  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.347  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:48.348  6564  6668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:06:48.349  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:48.351  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:48.351  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.351  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.351  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:48.351  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:48.351  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-29 11:06:48.351  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:48.351  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.352  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.352  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:06:48.353  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:48.354  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 11:06:48.354  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:06:48.354  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:06:48.354  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:06:48.354  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:06:48.354  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:06:48.357  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:06:48.357  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:48.358  6564  6668 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:06:48.358  6564  6668 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 11:06:48.359  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.359  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:06:48.359  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.360  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.360  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:48.360  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:48.360  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.360  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:48.360  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.360  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.360  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:48.360  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.360  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.361  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:06:48.361  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.362  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.362  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 11:06:48.362  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.362  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.362  6564  6668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 11:06:48.364  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:06:48.366  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 11:06:48.366  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.366  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.366  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:48.366  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-29 11:06:48.366  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.366  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:48.366  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.366  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.367  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-29 11:06:48.368  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:48.368  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:48.369  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:06:48.369  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:06:48.369  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 11:06:48.369  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:48.369  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:06:48.371  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:06:48.372  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-29 11:06:48.372  6564  6668 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:06:48.372  6564  6668 I io.jxcore.node.ConnectionHelper: start: OK
08-29 11:06:48.372  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 11:06:48.372  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.372  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:48.373  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.373  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.373  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.373  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 11:06:48.373  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.373  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:48.373  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list,
08-29 11:06:48.373  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.373  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.373  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:06:48.373  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.374  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.374  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:48.374  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:06:48.374  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.375  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.375  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 11:06:48.375  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.375  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.375  6564  6668 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 11:06:48.375  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.375  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.375  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:48.375  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.375  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.375  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.375  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
,08-29 11:06:48.375  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.375  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.376  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:06:48.376  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.376  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.376  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.376  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:48.376  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.376  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:06:48.377  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.377  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.377  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.377  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
,08-29 11:06:48.378  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 11:06:48.378  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.378  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:06:48.378  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-29 11:06:48.378  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.378  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.378  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.378  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.378  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.378  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
,08-29 11:06:48.378  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.378  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.378  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.378  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.378  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:48.379  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.379  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.379  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.379  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.379  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.379  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
,08-29 11:06:48.380  6564  6668 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 11:06:48.380  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.380  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.380  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.380  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:48.380  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.380  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.380  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.380  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.380  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
,08-29 11:06:48.380  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.380  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.380  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.380  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.380  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:48.381  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.381  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.381  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.381  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.381  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:48.381  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.382  6564  6668 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 11:06:48.382  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.382  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.382  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:48.382  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.382  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.382  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.382  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.382  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.382  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
,08-29 11:06:48.382  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.382  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.382  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.382  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-29 11:06:48.382  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.383  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.383  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.383  6564  6668 D BluetoothLeScanner: could not find callback wrapper
,08-29 11:06:48.383  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.383  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.383  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
,08-29 11:06:48.384  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:06:48.385  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:06:48.385  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:06:48.385  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:06:48.385  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 11:06:48.385  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:06:48.385  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.385  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.385  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.385  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.385  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:48.385  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.385  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.385  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.385  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.385  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.385  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 11:06:48.386  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.386  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.386  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.386  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.386  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:06:48.387  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.387  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.387  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.387  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.387  6564  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:48.387  6564  6668 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:06:48.387  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 11:06:48.389  6564  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:48.389  6564  6668 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010],
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:06:48.389  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 11:06:48.390  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:06:48.390  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 11:06:48.390  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:06:48.390  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 11:06:48.390  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:06:48.390  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-29 11:06:48.390  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:06:48.390  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 11:06:48.390  6564  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 11:06:48.390  6564  6668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:06:48.390  6564  6668 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 11:06:48.390  6564  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:48.390  6564  6668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:06:48.390  6564  6668 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 11:06:48.390  6564  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:48.390  6564  6668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:06:48.390  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 11:06:48.392  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 11:06:48.393  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 11:06:48.393  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 11:06:48.394  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 11:06:48.394  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 11:06:48.394  6564  6668 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 11:06:48.394  6564  6668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:48.394  6564  6668 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 11:06:48.394  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.394  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.394  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.395  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.395  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.395  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.395  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 11:06:48.395  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.395  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.395  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.395  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.395  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.395  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.395  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.395  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.396  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.396  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.397  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.397  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.397  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.397  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.401  6564  6668 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 11:06:48.402  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.402  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.402  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.402  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.402  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.402  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.403  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.403  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.403  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.403  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.403  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.403  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.403  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.403  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.404  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.404  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.404  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.404  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.404  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.404  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.405  6564  6668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 11:06:48.408  6564  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-29 11:06:48.409  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.409  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.409  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.409  6564  6726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-29 11:06:48.410  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.410  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.410  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.410  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.410  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.410  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.410  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.410  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.410  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.410  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.410  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.410  6564  6726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-29 11:06:48.419  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.419  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.426  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.426  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.426  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.426  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.427  6564  6668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 11:06:48.427  6564  6668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 11:06:48.427  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:06:48.427  6564  6668 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 11:06:48.427  6564  6668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:06:48.427  6564  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 11:06:48.427  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:06:48.428  6564  6668 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 11:06:48.428  6564  6668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:06:48.428  6564  6668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:06:48.428  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:06:48.428  6564  6668 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 11:06:48.428  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.428  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.428  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.428  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.428  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.428  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.428  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.428  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.428  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.428  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.428  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.429  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.429  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.429  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.429  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.429  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.430  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.430  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.430  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.430  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.430  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.430  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.430  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.430  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.430  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.430  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.430  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.430  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.430  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.430  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.430  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.430  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.430  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.430  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.430  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.430  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.430  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.431  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.431  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.431  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.431  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.431  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.431  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.431  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.431  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.431  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.431  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.431  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.431  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.433  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.433  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.433  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.433  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.433  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.433  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.434  6564  6668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 11:06:48.435  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:48.435  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 11:06:48.436  6564  6668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 11:06:48.436  6564  6668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 11:06:48.436  6564  6564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 11:06:48.436  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 11:06:48.436  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:06:48.437  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.437  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 11:06:48.437  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 11:06:48.437  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 11:06:48.437  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.437  6564  6668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 11:06:48.438  6564  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 11:06:48.438  6564  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 11:06:48.438  6564  6564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 11:06:48.439  6564  6564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 11:06:48.439  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.439  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.439  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:06:48.439  6564  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:06:48.439  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:06:48.440  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:06:48.440  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:06:48.440  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:48.440  6564  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:06:48.441  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.441  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.441  6564  6668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:06:48.441  6564  6564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:06:48.441  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.441  6564  6564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:06:48.442  6564  6564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:06:48.442  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.442  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.442  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.442  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.442  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.442  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.442  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.442  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.442  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.442  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.442  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.442  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.442  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.442  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.443  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.443  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.443  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:48.443  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.444  6564  6668 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 11:06:48.444  6564  6668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:06:48.444  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:06:48.446  6564  6668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:06:48.447  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.447  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.447  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.447  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.447  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.447  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.447  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.447  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.447  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.447  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.447  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.447  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.447  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.447  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.448  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.448  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.448  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.448  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.448  1043  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:48.449  1043  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:48.449  1043  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:48.450  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.450  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.450  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.450  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.450  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.450  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.450  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.450  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.450  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.450  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.450  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.450  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.450  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.450  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.450  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.451  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.451  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.451  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.451  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:48.451  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:48.451  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:48.451  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:48.451  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.451  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.451  6564  6668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b41016c not in the list
08-29 11:06:48.451  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.451  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.451  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:48.451  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.451  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.451  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:48.451  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:48.452  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:48.452  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:48.452  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:48.452  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea4b335 not in the list
08-29 11:06:48.453  6564  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 11:06:48.453  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:06:48.453  6564  6668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 11:06:48.453  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:06:48.453  6564  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 11:06:48.453  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:06:48.455  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 11:06:48.455  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 11:06:48.455  6564  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 11:06:48.455  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:06:48.456  6564  6668 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 11:06:48.456  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:06:48.456  6564  6668 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 11:06:48.456  6564  6668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 11:06:48.456  6564  6668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 11:06:48.457  6564  6668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 11:06:48.457  6564  6668 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 11:06:48.457  6564  6668 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 11:06:48.457  6564  6668 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 11:06:48.457  6564  6668 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 11:06:48.458  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:48.458  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10f9e222 added. We now have 2 listener(s)
08-29 11:06:48.458  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:48.459  6564  6668 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 11:06:48.460  1043  1852 D WifiServiceImplEx: setWifiEnabled: true pid=6564, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:06:48.460  1043  1852 D WifiService: setWifiEnabled: true pid=6564, uid=10118
08-29 11:06:48.460  1043  1852 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:06:48.461  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:48.461  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2597d4b3 added. We now have 3 listener(s)
08-29 11:06:48.461  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:48.464  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:48.464  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39e64a70 added. We now have 4 listener(s)
08-29 11:06:48.464  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:48.465  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:48.465  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@145c01e9 added. We now have 5 listener(s)
08-29 11:06:48.465  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:48.466  1043  1558 D WifiServiceImplEx: setWifiEnabled: false pid=6564, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:06:48.466  1043  1558 D WifiService: setWifiEnabled: false pid=6564, uid=10118
08-29 11:06:48.466  1043  1558 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:06:48.478  1043  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:48.478  1043  1924 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@eea8ed6 mBinding = false
,08-29 11:06:48.478  1043  1520 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:48.480  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:48.480  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:06:48.481  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:06:48.481  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 11:06:48.481  1043  1520 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:48.482  1043  1520 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:48.482  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:48.482  1043  1520 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 11:06:48.482  1043  1520 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:06:48.482  1043  1520 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:06:48.483  1043  1520 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:06:48.483  1043  1520 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 11:06:48.490  1043  1119 D BluetoothManagerService: Message: 2
08-29 11:06:48.490  1043  1119 D BluetoothManagerService: Sending off request.
08-29 11:06:48.490  3877  3893 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 11:06:48.491  1043  1520 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:06:48.491  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:06:48.491  2625  2625 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:06:48.491  1043  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.491  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:06:48.491  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.491  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:06:48.491  3877  3960 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 11:06:48.491  3877  3960 D BluetoothAdapterProperties: Setting state to 13
08-29 11:06:48.492  3877  3960 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 11:06:48.492  1043  1520 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:06:48.492  1043  2778 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.492   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:06:48.492  3877  3960 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 11:06:48.492  3877  3960 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 11:06:48.493  3877  3967 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:06:48.494  3877  3960 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 11:06:48.495  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:48.496  3877  3960 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:06:48.496  3877  4176 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:06:48.497  3877  4174 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 11:06:48.497  3877  4174 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:06:48.497  3877  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 11:06:48.497  3877  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 11:06:48.497  3877  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 11:06:48.497  3877  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 11:06:48.497  3877  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 11:06:48.497  3877  4174 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 11:06:48.497  3877  4223 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:06:48.497  3877  4219 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:06:48.498  3877  4218 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:06:48.499  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for mul,tiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.499  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:48.499  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.499  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.499  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:48.499  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:48.499  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.499  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:48.499  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.499  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.499  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.500  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:06:48.501  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:48.501  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:06:48.502  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:48.502  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 ,
08-29 11:06:48.502  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 11:06:48.503  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.503  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:48.503  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.503  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.503  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:48.503  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:48.503  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.503  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:48.503  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.503  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.503  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:48.504  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:48.515  1043  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 11:06:48.515  1043  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-29 11:06:48.535  1043  1115 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6738 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-29 11:06:48.537  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 11:06:48.538  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:48.538  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:48.538  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:06:48.539  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:48.539  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:48.539  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 11:06:48.540  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:48.541  1043  1119 D BluetoothManagerService: Message: 60
08-29 11:06:48.541  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 11:06:48.542  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 11:06:48.543  3877  3877 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:48.543  3877  3877 D BluetoothMapService: STATE_TURNING_OFF
08-29 11:06:48.543  3877  3877 V BluetoothMapService: Handler(): got msg=4
08-29 11:06:48.544  3877  3877 D BluetoothMapService: MAP Service closeService in
08-29 11:06:48.544  3877  3877 D BluetoothMapMasInstance: MAP Service shutdown
08-29 11:06:48.544  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:06:48.544  3877  3877 V BluetoothMapService: MAP Service closeService out
08-29 11:06:48.544  3877  3877 V BtOppService: Receiver DISABLED_ACTION 
08-29 11:06:48.544  3877  3877 I BtOppRfcommListener: stopping Accept Thread
08-29 11:06:48.544  3877  3877 V BtOppRfcommListener: close mBtServerSocket
08-29 11:06:48.544  3877  3877 V BtOppRfcommListener: waiting for thread to terminate
08-29 11:06:48.545  3877  4218 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:06:48.545  3877  3877 V BtOppRfcommListener: done waiting for thread to terminate
08-29 11:06:48.545  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.545  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:48.545  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.545  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.545  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:48.545  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:48.545  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:48.545  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:48.545  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:06:48.548  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.548  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:48.549  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:48.550  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.550  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:48.550  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.550  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.550  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:48.550  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:48.550  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:48.550  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:48.550  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.551  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.551  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:48.559  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 11:06:48.581  1043  1115 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6762 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:06:48.583  1043  1520 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.583  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.584  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.584  1043  1520 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 11:06:48.584  1043  1520 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.584  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.584  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.585  1043  1520 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.585  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.585  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:48.586  1043  1519 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.586  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.586  1043  1519 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2473f8eb
08-29 11:06:48.586  3877  3877 V BtOppService: onDestroy
08-29 11:06:48.594  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 11:06:48.595  3877  3877 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 11:06:48.595  1043  1519 D LGWifiP2pService: P2pDisablingState
08-29 11:06:48.595  1043  1519 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.595  1043  1519 D LGWifiP2pService: p2p socket connection lost
08-29 11:06:48.595  1043  1519 D LGWifiP2pService: P2pDisabledState
,08-29 11:06:48.596  1043  1520 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 11:06:48.596  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:06:48.596  2625  2625 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:06:48.599  1043  1519 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.599  1043  1519 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.600  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:06:48.600  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:06:48.601  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 11:06:48.601  1925  1925 D WfdsService: WifiP2pState is changed : false
08-29 11:06:48.601  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:48.601  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:48.601  1925  2285 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 11:06:48.601  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:06:48.601  1925  2285 D WfdsService: Set the WFDS Monitor: false
08-29 11:06:48.601  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 11:06:48.601  1043  1043 D RttService: SCAN_AVAILABLE : 1
08-29 11:06:48.601  1925  2285 D WfdsMonitor: WFDS Monitor is stopped
08-29 11:06:48.601  1043  1539 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.602  1925  2285 D WfdsService: STATE : WfdsDisabledState - enter
08-29 11:06:48.602  1925  2708 D CtrlSupplicant: Received on exit socket, terminate
08-29 11:06:48.602  1925  2708 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 11:06:48.602  1925  2708 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 11:06:48.602  1925  2708 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 11:06:48.602  1043  1520 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:06:48.602  1925  2294 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 11:06:48.602  1925  2285 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 11:06:48.603  1043  1540 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.608   314   900 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:06:48.608  1043  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 11:06:48.608  1043  1527 D DSQN    : disableDataServiceNotify
08-29 11:06:48.608  1043  1527 D DSQN    : stop dsqn bin
08-29 11:06:48.610  1043  1520 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 11:06:48.611  1043  1520 D WifiNative-p2p0: TERMINATE: returned true
08-29 11:06:48.611  1043  1520 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:06:48.611  1043  1520 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:06:48.611  1043  1520 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:06:48.611  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 11:06:48.612  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:48.612  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:48.612  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:06:48.614  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 11:06:48.615  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 11:06:48.615  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:48.615  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:48.615  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:48.615  1043  1043 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 11:06:48.618  1043  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 11:06:48.618  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:48.618  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:48.619  1043  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:48.619  1043  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 11:06:48.619  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.619  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:48.619  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.619  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.619  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:48.619  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:48.619  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:48.619  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:48.619  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.619  1043  2775 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.619  1043  2775 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.619  1043  2775 D NetworkMo,nitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 11:06:48.620  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.620  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:48.620  1043  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 11:06:48.620  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 11:06:48.620  1043  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 11:06:48.620  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 11:06:48.622  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:48.623  1043  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:48.623  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:06:48.623  1043  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:48.623  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 11:06:48.624  1043  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:48.624  1043  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:48.624  1043  1518 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 11:06:48.624  1043  1520 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:48.624  1043  1520 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:06:48.624  1043  1527 D NetworkManagementService: Removing idletimer
08-29 11:06:48.625  1043  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:48.625  1043  1518 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 11:06:48.625  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.625  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:48.625  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.625  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.625  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:48.625  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:48.625  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:48.625  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:48.625  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:48.625  1835  1835 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:48.625  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.625  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 11:06:48.625  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:06:48.649  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 11:06:48.649  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:48.650  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:48.653  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:06:48.660  1043  1942 I art     : Explicit concurrent mark sweep GC freed 29416(1415KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.383ms total 155.644ms
08-29 11:06:48.661  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 11:06:48.661  3877  4049 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 11:06:48.662  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 11:06:48.662  3877  4049 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 11:06:48.662  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 11:06:48.662  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 11:06:48.662  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:06:48.662  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:06:48.662  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 11:06:48.662  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:06:48.662  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:06:48.664  1043  1527 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 11:06:48.668  6762  6762 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:06:48.668  6762  6762 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-29 11:06:48.668  6762  6762 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 11:06:48.669  6762  6762 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 11:06:48.670  6762  6762 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 11:06:48.674  6762  6762 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 11:06:48.679  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:06:48.679  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:48.680  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:06:48.713  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-29 11:06:48.714  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:48.714  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:48.717  6738  6738 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 11:06:48.717  6738  6738 W LG Account v2.2: No ProfileInfo entries
08-29 11:06:48.717  6738  6738 I LG Account v2.2: isEnabled: false
08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]Country: EU
08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]Operator: OPEN
08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]Ranking support: false
08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]Comfort support: false
08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]Accessory: true
08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]Health device: true
08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]Extra Pedometer: false
,08-29 11:06:48.717  6738  6738 I Feature : [Lifetracker]Blood glucose device: false
08-29 11:06:48.718  6738  6738 I Feature : [Lifetracker]Device Number: 3
08-29 11:06:48.720  1043  2778 D DhcpStateMachine: StoppedState
08-29 11:06:48.720  1043  2778 D DhcpStateMachine: StoppedState{ when=-118ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:48.721  1043  1520 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 11:06:48.721  1043  1520 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 11:06:48.727  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:48.727  2625  2625 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 11:06:48.727  2625  2625 I wpa_supplicant: monitor socket send errors count : 1
08-29 11:06:48.727  2625  2625 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
08-29 11:06:48.728  1043  2701 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 11:06:48.728  1043  2701 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 11:06:48.765  1043  1906 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6784 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:06:48.766  2625  2625 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:06:48.767  2625  2625 W wpa_supplicant: USIM:  scard_deinit function
08-29 11:06:48.767  1043  2701 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 11:06:48.767  1043  2701 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:06:48.767  1043  2701 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:06:48.767  1043  2701 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 11:06:48.767  1043  2701 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:06:48.767  1043  2701 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:06:48.767  1043  1119 D Tethering: InitialState.processMessage what=4
08-29 11:06:48.768  1043  1520 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=119031
08-29 11:06:48.768  1043  1520 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=119031
08-29 11:06:48.768  1043  1520 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=119031  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 11:06:48.769  1043  1520 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=119031  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 11:06:48.769  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:06:48.770  1043  1906 I ActivityManager: Killing 6173:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 11:06:48.772  1043  1520 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:48.773  1043  1520 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 11:06:48.818  6762  6762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 11:06:48.866  1043  1997 W libprocessgroup: failed to open /acct/uid_10014/pid_6173/cgroup.procs: No such file or directory
,08-29 11:06:48.869  2625  2625 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 11:06:48.870  1043  2701 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 11:06:48.870  1043  2701 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 11:06:48.871  1043  2701 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 11:06:48.872  1043  1520 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-29 11:06:48.887  3877  3877 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:06:48.887  3877  3877 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:48.887  3877  3877 V BluetoothPbapReceiver: ***********state = 13
,08-29 11:06:48.894  1043  1119 D BluetoothManagerService: Message: 20
08-29 11:06:48.894  3877  3877 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 11:06:48.894  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cb6c4b0:true
08-29 11:06:48.895  3877  3877 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:48.895  3877  3877 V BluetoothPbapService: state: 13
08-29 11:06:48.896  3877  3877 V BluetoothPbapService: Pbap Service closeService in
08-29 11:06:48.899  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:06:48.901  3877  3877 V BluetoothPbapService: successfully stopped pbap service
08-29 11:06:48.901  3877  3877 V BluetoothPbapService: Pbap Service closeService out
08-29 11:06:48.901  3877  3877 V BluetoothPbapService: Pbap Service onDestroy
08-29 11:06:48.901  3877  3877 V BluetoothPbapService: Pbap Service closeService in
08-29 11:06:48.901  3877  3877 V BluetoothPbapService: Pbap Service closeService out
08-29 11:06:48.901  3877  3877 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-29 11:06:48.905  1043  1360 V AlarmManager: RTC_WAKEUP set : Alarm{2484a2ae type 0 when 1472461608782 com.android.vending} when 1472461608782
08-29 11:06:48.927  1043  1119 D BluetoothManagerService: Message: 30
,08-29 11:06:48.935  1043  1119 D BluetoothManagerService: Message: 30
08-29 11:06:48.939  6762  6762 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 11:06:48.941  6762  6762 D BluetoothMap: Create BluetoothMap proxy object
08-29 11:06:48.942  1043  1119 D BluetoothManagerService: Message: 30
08-29 11:06:48.942  6564  6564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 11:06:48.947  1043  1119 D BluetoothManagerService: Message: 30
08-29 11:06:48.949  6762  6762 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 11:06:48.950  6762  6762 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 11:06:48.968  6762  6762 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-29 11:06:48.968  6784  6784 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 11:06:48.971  6762  6762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-29 11:06:48.973  6784  6784 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:06:48.974  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:06:48.982  1043  1520 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 11:06:48.982  1043  1520 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:06:48.982  1043  1520 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:06:48.982  1043  1520 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:06:48.983  6762  6762 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:06:48.986  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-29 11:06:48.986  1925  2285 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 11:06:48.986  1925  2285 D WfdsService: Set the WFDS Monitor: false
08-29 11:06:48.986  1925  2285 D WfdsMonitor: WFDS Monitor is stopped
08-29 11:06:48.988  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:48.988  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 11:06:48.991  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 11:06:48.991  1043  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 11:06:48.991  1043  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 11:06:48.992  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.992  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:48.992  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.992  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.992  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:48.992  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:48.992  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:48.992  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:48.992  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:48.994  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:48.994  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:48.994  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:48.994  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:48.994  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:48.994  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:48.994  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:48.994  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:48.994  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:48.996  2474  2474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:06:48.997  1043  1558 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:06:48.999  6762  6762 D BluetoothInputDevice: Proxy object connected
08-29 11:06:49.000  6762  6762 D HidProfile: Bluetooth service connected
08-29 11:06:49.001  6762  6762 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:06:49.002  6762  6762 D PanProfile: Bluetooth service connected
08-29 11:06:49.003  6762  6762 D BluetoothMap: Proxy object connected
08-29 11:06:49.003  6762  6762 D MapProfile: Bluetooth service connected
08-29 11:06:49.004  6762  6762 D BluetoothMap: getConnectedDevices()
08-29 11:06:49.004  6762  6762 D BluetoothMap: Bluetooth is Not enabled
08-29 11:06:49.016  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:49.048  6762  6762 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:06:49.048  6762  6762 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:06:49.056  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:49.056  6762  6762 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 11:06:49.058  6762  6762 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 11:06:49.064  6762  6762 D BluetoothPermissionRequest: onReceive
08-29 11:06:49.067  6762  6762 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 11:06:49.073  1043  1888 I ActivityManager: Killing 6275:com.android.defcontainer/u0a4 (adj 15): empty #17
08-29 11:06:49.073  6762  6762 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 11:06:49.119  3877  3877 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-29 11:06:49.119  3877  3877 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-29 11:06:49.120  3877  3877 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 11:06:49.121  1043  1059 W libprocessgroup: failed to open /acct/uid_10004/pid_6275/cgroup.procs: No such file or directory
08-29 11:06:49.197  5774  5774 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-29 11:06:49.225  1043  1888 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6813 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-29 11:06:49.228  3877  3877 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:49.228  3877  3877 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 11:06:49.229  3877  3877 V BluetoothFtpService: Ftp Service onStartCommand
08-29 11:06:49.229  3877  3877 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:49.229  3877  3877 V BluetoothFtpService: Ftp Service closeService
08-29 11:06:49.229  3877  3877 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 11:06:49.230  3877  3877 V BluetoothFtpService: successfully stopped ftp service
08-29 11:06:49.231  3877  3877 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:06:49.231  3877  3877 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:06:49.231  3877  3877 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:06:49.231  3877  3877 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:49.231  3877  3877 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 11:06:49.231  3877  3877 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 11:06:49.232  1043  1870 I ActivityManager: Killing 6419:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-29 11:06:49.250   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 479us total 22.122ms
,08-29 11:06:49.273   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 19.432ms
,08-29 11:06:49.299   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 486us total 24.828ms
,08-29 11:06:49.318  1043  1639 W libprocessgroup: failed to open /acct/uid_10008/pid_6419/cgroup.procs: No such file or directory
,08-29 11:06:49.319  3877  3877 V BluetoothFtpService: Ftp Service onDestroy
08-29 11:06:49.319  3877  3877 V BluetoothFtpService: Ftp Service closeService
08-29 11:06:49.330  3877  3877 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:49.330  3877  3877 V BluetoothSapService: state: 13
08-29 11:06:49.330  3877  3877 V BluetoothSapService: Stopping SAP server process
,08-29 11:06:49.331  3877  3877 V BluetoothSapService: Sap Service closeSapService in
08-29 11:06:49.331  3877  3877 V BluetoothSapService: Close listen Socket : 
08-29 11:06:49.332  3877  3877 V BluetoothSapService: Close rfcomm Socket : 
08-29 11:06:49.332  3877  3877 V BluetoothSapService: Close sapd  Socket : 
08-29 11:06:49.333  3877  3877 V BluetoothSapService: Sap Service closeSapService out
08-29 11:06:49.333  3877  3877 V BluetoothSapService: Sap Service onDestroy
08-29 11:06:49.333  3877  3877 V BluetoothSapService: Sap Service closeSapService in
08-29 11:06:49.333  3877  3877 V BluetoothSapService: Close listen Socket : 
08-29 11:06:49.333  3877  3877 V BluetoothSapService: Close rfcomm Socket : 
08-29 11:06:49.333  3877  3877 V BluetoothSapService: Close sapd  Socket : 
08-29 11:06:49.354  6813  6813 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 11:06:49.403  1043  1870 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6833 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 11:06:49.405  3877  3877 V BluetoothSapService: Sap Service closeSapService out
08-29 11:06:49.408  6813  6813 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-29 11:06:49.448  6813  6813 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-29 11:06:49.449  6813  6813 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 11:06:49.449  6813  6813 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 11:06:49.450  6813  6813 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 11:06:49.450  6813  6813 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-29 11:06:49.453  6813  6813 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 11:06:49.458  6813  6813 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 11:06:49.459  6833  6833 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:06:49.466  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:06:49.468  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:49.475  1043  1639 I ActivityManager: Killing 6014:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-29 11:06:49.509  1043  1729 W libprocessgroup: failed to open /acct/uid_10011/pid_6014/cgroup.procs: No such file or directory
,08-29 11:06:49.510  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:06:49.514  6813  6813 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 11:06:49.517  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:49.522  6813  6813 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-29 11:06:49.525  6784  6784 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:06:49.525  6784  6784 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:06:49.525  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:06:49.532  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:49.541  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:06:49.552  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:49.553  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:49.555  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 11:06:49.561  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:06:49.571  6784  6784 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:06:49.571  6784  6784 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:06:49.571  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:06:49.578  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:49.586  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:49.593  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:49.594  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:49.596  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 11:06:49.660  1043  1924 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6853 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 11:06:49.665  3877  4049 W bt-btif : ag scb idx 1 not allocated
08-29 11:06:49.665  3877  4049 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 11:06:49.665  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:06:49.665  3877  4049 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:06:49.665  3877  3967 D bt_hci_bdroid: cleanup
08-29 11:06:49.665  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:06:49.665  3877  4049 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:06:49.666  3877  4049 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:06:49.666  3877  4049 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 11:06:49.666  3877  4053 I bt_lpm  : LPM is already off!!!
08-29 11:06:49.666  3877  4148 I bt_userial_mct: exiting userial_read_thread
08-29 11:06:49.666  3877  4148 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 11:06:49.667  3877  3967 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 11:06:49.667  3877  4053 I bt_vendor: hw_epilog_process
08-29 11:06:49.668  3877  3967 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 11:06:49.668  3877  3967 D bt_userial_mct: userial_close
08-29 11:06:49.668  3877  3967 E bt_userial_mct: pthread_join() FAILED result:3
08-29 11:06:49.668  3877  3967 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 11:06:49.766  3877  3967 D bt_hci_bdroid: set_power 0
08-29 11:06:49.766  3877  3967 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 11:06:49.767  3877  3967 I bt_vendor: bluetooth satus is on
08-29 11:06:49.767  3877  3967 I bt_vendor: bt-vendor : resetting BT status
08-29 11:06:49.767  3877  3967 I bt_vendor: Starting hciattach daemon
08-29 11:06:49.767  3877  3967 I bt_vendor: try to set false
08-29 11:06:49.767  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:06:49.768  3877  3967 I bt_vendor: Starting hciattach daemon
08-29 11:06:49.769  3877  3967 I bt_vendor: try to set false
08-29 11:06:49.771  3877  3967 I bt_vendor: cleanup
08-29 11:06:49.772  3877  4049 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 11:06:49.773  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 11:06:49.783  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:49.787  3877  3967 I GKI_LINUX: GKI_exit_task 0 done
08-29 11:06:49.787  3877  3967 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 11:06:49.790  3877  3960 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 11:06:49.794  3877  3877 D HeadsetService: Received stop request...Stopping profile...
08-29 11:06:49.795  3877  3877 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 11:06:49.795  3877  3877 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:06:49.795  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c940c1a
08-29 11:06:49.796  3877  3996 D HeadsetStateMachine: Exit Disconnected: -1
08-29 11:06:49.797  1043  1043 D BluetoothHeadset: Proxy object disconnected
08-29 11:06:49.797  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 11:06:49.797  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-29 11:06:49.798  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-29 11:06:49.798  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-29 11:06:49.799  3877  3877 D A2dpService: Received stop request...Stopping profile...
08-29 11:06:49.799  3877  4026 D A2dpStateMachine: Exit Disconnected: -1
08-29 11:06:49.804  3877  3877 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 11:06:49.804  3877  3960 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-29 11:06:49.807  3877  3877 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 11:06:49.807  3877  3877 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:06:49.807  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c940c1a
08-29 11:06:49.809  1043  1043 D BluetoothA2dp: Proxy object disconnected
08-29 11:06:49.809  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 11:06:49.809  3877  3877 D HeadsetStateMachine: Unbinding service...
08-29 11:06:49.810  3877  3877 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:06:49.810  3877  3877 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:06:49.810  3877  3877 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:06:49.810  3877  3877 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:06:49.810  3877  3877 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 11:06:49.810  3877  3877 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:06:49.810  3877  3877 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 11:06:49.811  3877  3877 D HidService: Received stop request...Stopping profile...
08-29 11:06:49.811  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c940c1a
08-29 11:06:49.812  3877  3877 D HealthService: Received stop request...Stopping profile...
08-29 11:06:49.812  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c940c1a
08-29 11:06:49.814  6762  6762 D BluetoothInputDevice: Proxy object disconnected
08-29 11:06:49.814  6762  6762 D HidProfile: Bluetooth service disconnected
08-29 11:06:49.814  3877  3877 D PanService: Received stop request...Stopping profile...
08-29 11:06:49.819  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c940c1a
,08-29 11:06:49.820  3877  3877 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:06:49.820  3877  3877 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 11:06:49.820  3877  3877 D BtGatt.GattService: stop()
08-29 11:06:49.820  3877  3877 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 11:06:49.821  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c940c1a
08-29 11:06:49.822  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:06:49.822  3877  3877 D BluetoothMapService: Received stop request...Stopping profile...
08-29 11:06:49.823  3877  3877 D BluetoothMapService: stop()
08-29 11:06:49.823  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:06:49.823  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:06:49.823  6762  6762 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:06:49.823  3877  3877 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 11:06:49.823  3877  3877 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 11:06:49.824  3877  3877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c940c1a
08-29 11:06:49.824  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:06:49.825  3877  3877 I BluetoothA2dpServiceJni: cleanupNative
08-29 11:06:49.825  3877  4028 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 11:06:49.825  3877  3877 I GKI_LINUX: GKI_exit_task 2 done
08-29 11:06:49.825  3877  3877 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 11:06:49.826  3877  3877 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:06:49.826  3877  3877 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 11:06:49.826  3877  3877 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:06:49.826  3877  3877 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:06:49.826  3877  3877 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:06:49.827  3877  3877 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 11:06:49.827  3877  3877 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 11:06:49.828  3877  3877 V BluetoothMapService: Handler(): got msg=4
08-29 11:06:49.828  3877  3877 D BluetoothMapService: MAP Service closeService in
08-29 11:06:49.828  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:06:49.828  3877  3877 V BluetoothMapService: MAP Service closeService out
08-29 11:06:49.828  3877  3960 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 11:06:49.828  3877  3960 D BluetoothAdapterProperties: Setting state to 10
08-29 11:06:49.828  3877  3960 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 11:06:49.829  3877  3877 D BluetoothMapService: cleanup()
08-29 11:06:49.829  3877  3877 D BluetoothMapService: MAP Service closeService in
08-29 11:06:49.829  3877  3877 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:06:49.829  3877  3877 V BluetoothMapService: MAP Service closeService out
08-29 11:06:49.829  1043  1119 D BluetoothManagerService: Message: 60
08-29 11:06:49.829  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 11:06:49.829  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 11:06:49.829  3877  3960 I BluetoothAdapterState: Entering OffState
08-29 11:06:49.829  1835  1850 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:06:49.830  1835  2421 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:06:49.830  1043  1119 D BluetoothHeadset: onBluetoothStateChange: u,p=false
08-29 11:06:49.831  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:06:49.831  6762  6779 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 11:06:49.832  6762  6780 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:06:49.832  6762  6874 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:06:49.833  1835  3995 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:06:49.834  6762  6779 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:06:49.835  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 11:06:49.835  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 11:06:49.836  6853  6873 W FormManager: Network not available. Please check & try again.
08-29 11:06:49.837  6853  6875 V FormManager: Network unavailable.
08-29 11:06:49.838  1043  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 11:06:49.838  1043  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 11:06:49.839  1043  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@eea8ed6 mBinding = false
08-29 11:06:49.839  1043  1119 D BluetoothManagerService: Sending unbind request.
08-29 11:06:49.840  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 11:06:49.844  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:49.845  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:06:49.848  1925  2104 D LGBluetoothAPIService: Message: 2
,08-29 11:06:49.848  1925  2104 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@240bf5d5 mBinding = false
08-29 11:06:49.848  1925  2104 D LGBluetoothAPIService: Sending unbind request.
08-29 11:06:49.850  3877  3967 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 11:06:49.850  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:49.851  3877  3877 I GKI_LINUX: GKI_exit_task 1 done
08-29 11:06:49.851  3877  3877 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 11:06:49.851  3877  3877 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 11:06:49.851  3877  3877 I art     : --- WEIRD: removing null entry 246
08-29 11:06:49.851  3877  3877 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 11:06:49.851  3877  3877 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 11:06:49.851  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:49.852  3877  3877 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 11:06:49.853  1586  1586 D BluetoothAdapter: 499244274: getState() :  mService = null. Returning STATE_OFF
08-29 11:06:49.853  1586  1586 D BluetoothAdapter: 499244274: getState() :  mService = null. Returning STATE_OFF
08-29 11:06:49.853  6853  6875 V FormManager: Network unavailable.
08-29 11:06:49.854  3877  3877 I art     : System.exit called, status: 0
08-29 11:06:49.854  3877  3877 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 11:06:49.859  6762  6762 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:06:49.859  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:06:49.859  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:06:49.859  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:06:49.859  6762  6762 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:06:49.860  6762  6762 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:06:49.861  6762  6762 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 11:06:49.862  6762  6762 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 11:06:49.862  6762  6762 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 11:06:49.864  6762  6762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:06:49.872  6762  6762 D DockEventReceiver: finishStartingService: stopping service
08-29 11:06:49.872  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:06:49.872  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 11:06:49.874  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:49.879  1043  1906 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-29 11:06:49.881  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:49.884   318  1368 V AudioFlinger: 3877 died, releasing its sessions
08-29 11:06:49.884   318  1368 V AudioFlinger:  pid 1835 @ 0
08-29 11:06:49.884   318  1368 V AudioFlinger:  pid 3411 @ 1
08-29 11:06:49.884   318  1368 V AudioFlinger:  pid 3411 @ 2
08-29 11:06:49.884  6762  6762 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 11:06:49.887  4318  6882 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:06:49.891  4318  6883 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:06:49.891  4318  6883 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:06:49.922  4466  6880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 11:06:49.976  1043  1060 I ActivityManager: Process com.android.bluetooth (pid 3877) has died
,08-29 11:06:49.977  1043  1060 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-29 11:06:49.997  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:06:50.003  6784  6784 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 11:06:50.003  6784  6784 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:06:50.003  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:06:50.019  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:06:50.021  6853  6893 W FormManager: Network not available. Please check & try again.
08-29 11:06:50.026  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:50.033  6762  6762 D BluetoothPermissionRequest: onReceive
,08-29 11:06:50.035  6762  6762 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 11:06:50.036  6762  6762 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 11:06:50.043  6853  6894 V FormManager: Network unavailable.
08-29 11:06:50.043  6762  6762 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:06:50.117  1043  1729 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6899 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 11:06:50.127  6853  6894 V FormManager: Network unavailable.
08-29 11:06:50.137  1043  1059 I ActivityManager: Killing 6034:com.android.contacts/u0a19 (adj 15): empty #17
,08-29 11:06:50.188  1043  1558 W libprocessgroup: failed to open /acct/uid_10019/pid_6034/cgroup.procs: No such file or directory
,08-29 11:06:50.208  6813  6813 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-29 11:06:50.211  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 11:06:50.212  6813  6813 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 11:06:50.220  6899  6899 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 11:06:50.220  6899  6899 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:06:50.221  6899  6899 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-29 11:06:50.222  6899  6899 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 11:06:50.244  6899  6899 D BluetoothAdapterApp: Loading JNI Library
,08-29 11:06:50.257  6813  6813 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:06:50.257  6813  6813 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:06:50.266  6813  6813 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 11:06:50.269  6813  6813 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 11:06:50.269  6813  6813 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 11:06:50.269  6813  6813 V SoundPool: doLoad: loading sample sampleID=1
08-29 11:06:50.270  6813  6918 V SoundPool: Start decode
,08-29 11:06:50.270  6813  6918 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-29 11:06:50.271  6813  6813 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 11:06:50.275   318  1369 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 11:06:50.275   318  1369 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 11:06:50.275   318  1369 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 11:06:50.275   318  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 11:06:50.275   318  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 11:06:50.275   318  1369 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 11:06:50.275   318  1369 V MediaPlayerService: player type = 3
08-29 11:06:50.275   318  1369 V AwesomePlayer: AwesomePlayer create()
08-29 11:06:50.275   318  1369 V AwesomePlayer: reset_l() 
08-29 11:06:50.276   318  1369 V AwesomePlayer: cancelPlayerEvents
08-29 11:06:50.276   318  1369 V AwesomePlayer: setAudioSink() 
08-29 11:06:50.276   318  1369 V AwesomePlayer: reset_l() 
08-29 11:06:50.276   318  1369 V AudioCache: notify(0xb54747c0, 8, 0, 0)
08-29 11:06:50.276   318  1369 V AudioCache: ignored
08-29 11:06:50.276   318  1369 V AwesomePlayer: cancelPlayerEvents
08-29 11:06:50.276   318  1369 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 11:06:50.276   318  1369 V AwesomePlayer: setDataSource_l dataSource
08-29 11:06:50.276   318  1369 V LGParserOSAL: SniffLGParser start
08-29 11:06:50.276   318  1369 V LGParserOSAL: MainType:5, SubType=0
08-29 11:06:50.276   318  1369 V LGParserOSAL: #### check Mime : application/ogg
08-29 11:06:50.276   318  1369 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 11:06:50.276   318  1369 E MediaExtractor: Use LGExtractor :application/ogg 
,08-29 11:06:50.285  6899  6899 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@8030cd3 Instance Count = 1
08-29 11:06:50.290  6671  6671 D UEI.SmartControl: QS Service created
08-29 11:06:50.292  6899  6899 D BluetoothAdapterApp: onCreate
08-29 11:06:50.295  6813  6813 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 11:06:50.303  6813  6813 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 11:06:50.304  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 11:06:50.326  6813  6813 V LGMDMManager: Create singleton instance
,08-29 11:06:50.327   318  1369 V LGParserOSAL: supported mime: application/ogg
08-29 11:06:50.327   318  1369 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 11:06:50.327   318  1369 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 11:06:50.327   318  1369 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 11:06:50.327   318  1369 V AwesomePlayer: AudioTrack Setting
08-29 11:06:50.327   318  1369 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 11:06:50.327   318  1369 V AwesomePlayer: setAudioSource() 
08-29 11:06:50.327   318  1369 V MediaPlayerService: prepare
08-29 11:06:50.327   318  1369 V AwesomePlayer: prepareAsync_l() 
08-29 11:06:50.327   318  1369 V MediaPlayerService: wait for prepare
08-29 11:06:50.328   318  6920 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 11:06:50.328   318  6920 V AwesomePlayer: initAudioDecoder() 
08-29 11:06:50.328   318  6920 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 11:06:50.328   318  6920 V AudioSystem: isOffloadSupported()
08-29 11:06:50.328   318  6920 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 11:06:50.328   318  6920 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 11:06:50.328   318  6920 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 11:06:50.328   318  6920 V AwesomePlayer: getUseOffload() = 0 
08-29 11:06:50.328   318  6920 V OMXCodec: OMXCodec::Create
08-29 11:06:50.328   318  6920 V OMXCodec: findMatchingCodecs()
08-29 11:06:50.328   318  6920 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 11:06:50.328   318  6920 V OMXCodec: matchingCodecs.size()=1
08-29 11:06:50.328   318  6920 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 11:06:50.330   318  6920 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 11:06:50.330   318  6920 V LGCodecAdapter: LG Codec Adapter start
08-29 11:06:50.330   318  6920 V OMXCodec: OMXCodec Createtor
08-29 11:06:50.330   318  6920 V OMXCodec: setComponentRole
08-29 11:06:50.330   318  6920 V OMXCodec: configureCodec protected=0
08-29 11:06:50.330   318  6920 V LGCodecAdapter: called getLGCodecSpecificData
08-29 11:06:50.330   318  6920 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 11:06:50.330   318  6920 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 11:06:50.330   318  6920 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 11:06:50.330   318  6920 V LGCodecOSAL: Not support LGCodec
08-29 11:06:50.330   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 11:06:50.330   318  6920 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 11:06:50.330   318  6920 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 11:06:50.331   318  6920 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 11:06:50.331   318  6920 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 11:06:50.331   318  6920 V AudioSystem: isOffloadSupported()
08-29 11:06:50.331   318  6920 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 11:06:50.331   318  6920 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 11:06:50.331   318  6920 V OMXCodec: init()
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-29 11:06:50.331   318  6920 V OMXCodec: allocateBuffers
08-29 11:06:50.331   318  6920 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-29 11:06:50.331   318  6920 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
08-29 11:06:50.331   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-29 11:06:50.332   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-29 11:06:50.332   318  6920 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc90 on output port
08-29 11:06:50.332   318  6920 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 11:06:50.332  6671  6671 I UEI.SmartControl: Service initServices...
08-29 11:06:50.332  6671  6671 D UEI.SmartControl: QS start get config
08-29 11:06:50.336   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 11:06:50.336   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 11:06:50.336   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 11:06:50.336   318  6920 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 11:06:50.336   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 11:06:50.336   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 11:06:50.336   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 11:06:50.336   318  6920 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 11:06:50.336   318  6920 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 11:06:50.336   318  6920 V AudioCache: notify(0xb54747c0, 5, 0, 0)
08-29 11:06:50.336   318  6920 V AudioCache: ignored
08-29 11:06:50.336   318  6920 V AudioCache: notify(0xb54747c0, 1, 0, 0)
08-29 11:06:50.336   318  6920 V AudioCache: prepared
08-29 11:06:50.336   318  1369 V AudioCache: wait - success
08-29 11:06:50.337   318  1369 V MediaPlayerService: start
08-29 11:06:50.337   318  1369 V AwesomePlayer: play_l() 
08-29 11:06:50.337   318  1369 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 11:06:50.337   318  1369 V AwesomePlayer: createAudioPlayer_l
,08-29 11:06:50.337   318  1369 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 11:06:50.337   318  1369 V AwesomePlayer: startAudioPlayer_l() ,
,08-29 11:06:50.337   318  1369 D AudioPlayer: start of Playback, useOffload 0
08-29 11:06:50.337   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 11:06:50.337   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 11:06:50.337  6899  6899 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-29 11:06:50.337  6899  6899 D ProfileConfigQcom: Adding HeadsetService
08-29 11:06:50.338  6899  6899 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 11:06:50.338  6899  6899 D ProfileConfigQcom: Adding A2dpService
08-29 11:06:50.338  6899  6899 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 11:06:50.338  6899  6899 D ProfileConfigQcom: Adding HidService
08-29 11:06:50.338  6899  6899 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 11:06:50.339  6899  6899 D ProfileConfigQcom: Adding HealthService
08-29 11:06:50.339  6899  6899 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 11:06:50.340  6899  6899 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 11:06:50.340  6899  6899 D ProfileConfigQcom: Adding PanService
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 11:06:50.340  6899  6899 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 11:06:50.340  6899  6899 D ProfileConfigQcom: Adding GattService
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048976
08-29 11:06:50.340   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 11:06:50.341  6899  6899 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 11:06:50.341  6899  6899 D ProfileConfigQcom: Adding BluetoothMapService
08-29 11:06:50.341   318  6922 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15462e0 on output port
08-29 11:06:50.341  6899  6899 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 11:06:50.341   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=,4
08-29 11:06:50.343  6899  6899 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 11:06:50.343   318  1369 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 11:06:50.347   318  1369 V AudioCache: notify(0xb54747c0, 6, 0, 0)
08-29 11:06:50.347   318  1369 V AudioCache: ignored
08-29 11:06:50.347   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.347   318  6923 V AudioCache: memcpy(0xac300000, 0xb57d7000, 4096)
08-29 11:06:50.350   318  1369 V MediaPlayerService: wait for playback complete
,08-29 11:06:50.350  6762  6762 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 11:06:50.352   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.353   318  6923 V AudioCache: memcpy(0xac301000, 0xb57d7000, 4096)
08-29 11:06:50.353   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.353   318  6923 V AudioCache: memcpy(0xac302000, 0xb57d7000, 4096)
08-29 11:06:50.354   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.354   318  6923 V AudioCache: memcpy(0xac303000, 0xb57d7000, 4096)
08-29 11:06:50.355   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.355   318  6923 V AudioCache: memcpy(0xac304000, 0xb57d7000, 4096)
08-29 11:06:50.355  6899  6899 V LGMDMManagerInternal: Create singleton instance
08-29 11:06:50.356   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.356   318  6923 V AudioCache: memcpy(0xac305000, 0xb57d7000, 4096)
08-29 11:06:50.357   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.357   318  6923 V AudioCache: memcpy(0xac306000, 0xb57d7000, 4096)
08-29 11:06:50.358   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.358   318  6923 V AudioCache: memcpy(0xac307000, 0xb57d7000, 4096)
08-29 11:06:50.359   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.359   318  6923 V AudioCache: memcpy(0xac308000, 0xb57d7000, 4096)
08-29 11:06:50.360   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.360   318  6923 V AudioCache: memcpy(0xac309000, 0xb57d7000, 4096)
08-29 11:06:50.361   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.361   318  6923 V AudioCache: memcpy(0xac30a000, 0xb57d7000, 4096)
08-29 11:06:50.361   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.361   318  6923 V AudioCache: memcpy(0xac30b000, 0xb57d7000, 4096)
08-29 11:06:50.362   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.362   318  6923 V AudioCache: memcpy(0xac30c000, 0xb57d7000, 4096)
,08-29 11:06:50.364   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.364   318  6923 V AudioCache: memcpy(0xac30d000, 0xb57d7000, 4096)
08-29 11:06:50.365   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.365   318  6923 V AudioCache: memcpy(0xac30e000, 0xb57d7000, 4096)
08-29 11:06:50.366   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.366   318  6923 V AudioCache: memcpy(0xac30f000, 0xb57d7000, 4096)
08-29 11:06:50.366   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.367   318  6923 V AudioCache: memcpy(0xac310000, 0xb57d7000, 4096)
08-29 11:06:50.367   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.367   318  6923 V AudioCache: memcpy(0xac311000, 0xb57d7000, 4096)
08-29 11:06:50.368   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.368   318  6923 V AudioCache: memcpy(0xac312000, 0xb57d7000, 4096)
08-29 11:06:50.369   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.369   318  6923 V AudioCache: memcpy(0xac313000, 0xb57d7000, 4096)
08-29 11:06:50.370   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.370   318  6923 V AudioCache: memcpy(0xac314000, 0xb57d7000, 4096)
08-29 11:06:50.371   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.371   318  6923 V AudioCache: memcpy(0xac315000, 0xb57d7000, 4096)
08-29 11:06:50.371   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.371   318  6923 V AudioCache: memcpy(0xac316000, 0xb57d7000, 4096)
08-29 11:06:50.372   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.372   318  6923 V AudioCache: memcpy(0xac317000, 0xb57d7000, 4096)
08-29 11:06:50.373   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.373   318  6923 V AudioCache: memcpy(0xac318000, 0xb57d7000, 4096)
08-29 11:06:50.374   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.374   318  6923 V AudioCache: memcpy(0xac319000, 0xb57d7000, 4096)
,08-29 11:06:50.376   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.376   318  6923 V AudioCache: memcpy(0xac31a000, 0xb57d7000, 4096)
08-29 11:06:50.377   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.377   318  6923 V AudioCache: memcpy(0xac31b000, 0xb57d7000, 4096)
08-29 11:06:50.377   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.377   318  6923 V AudioCache: memcpy(0xac31c000, 0xb57d7000, 4096)
08-29 11:06:50.378   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.378   318  6923 V AudioCache: memcpy(0xac31d000, 0xb57d7000, 4096)
08-29 11:06:50.378   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.378   318  6923 V AudioCache: memcpy(0xac31e000, 0xb57d7000, 4096)
08-29 11:06:50.378   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.378   318  6923 V AudioCache: memcpy(0xac31f000, 0xb57d7000, 4096)
08-29 11:06:50.379   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.379   318  6923 V AudioCache: memcpy(0xac320000, 0xb57d7000, 4096)
08-29 11:06:50.380   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.380   318  6923 V AudioCache: memcpy(0xac321000, 0xb57d7000, 4096)
08-29 11:06:50.380   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.380   318  6923 V AudioCache: memcpy(0xac322000, 0xb57d7000, 4096)
08-29 11:06:50.381   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.381   318  6923 V AudioCache: memcpy(0xac323000, 0xb57d7000, 4096)
08-29 11:06:50.381   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.381   318  6923 V AudioCache: memcpy(0xac324000, 0xb57d7000, 4096)
08-29 11:06:50.382   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.382   318  6923 V AudioCache: memcpy(0xac325000, 0xb57d7000, 4096)
08-29 11:06:50.382   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.382   318  6923 V AudioCache: memcpy(0xac326000, 0xb57d7000, 4096)
08-29 11:06:50.383   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.383   318  6923 V AudioCache: memcpy(0xac327000, 0xb57d7000, 4096)
08-29 11:06:50.383   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.383   318  6923 V AudioCache: memcpy(0xac328000, 0xb57d7000, 4096)
08-29 11:06:50.384   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.384   318  6923 V AudioCache: memcpy(0xac329000, 0xb57d7000, 4096)
08-29 11:06:50.385   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.385   318  6923 V AudioCache: memcpy(0xac32a000, 0xb57d7000, 4096)
08-29 11:06:50.385   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.385   318  6923 V AudioCache: memcpy(0xac32b000, 0xb57d7000, 4096)
,08-29 11:06:50.387   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.387   318  6923 V AudioCache: memcpy(0xac32c000, 0xb57d7000, 4096)
08-29 11:06:50.388   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.388   318  6923 V AudioCache: memcpy(0xac32d000, 0xb57d7000, 4096)
08-29 11:06:50.388   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.388   318  6923 V AudioCache: memcpy(0xac32e000, 0xb57d7000, 4096)
08-29 11:06:50.389   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.389   318  6923 V AudioCache: memcpy(0xac32f000, 0xb57d7000, 4096)
08-29 11:06:50.390   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.390   318  6923 V AudioCache: memcpy(0xac330000, 0xb57d7000, 4096)
08-29 11:06:50.390   318  6923 V AudioCache: write(0xb57d7000, 4096)
08-29 11:06:50.390   318  6923 V AudioCache: memcpy(0xac331000, 0xb57d7000, 4096)
08-29 11:06:50.391   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 11:06:50.391   318  6923 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 11:06:50.391   318  6923 V AwesomePlayer: postAudioEOS() 
08-29 11:06:50.391   318  6923 V AudioCache: write(0xb57d7000, 280)
08-29 11:06:50.391   318  6923 V AudioCache: memcpy(0xac332000, 0xb57d7000, 280)
08-29 11:06:50.392   318  6920 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 11:06:50.392   318  6920 V AwesomePlayer: onStreamDone
08-29 11:06:50.392   318  6920 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 11:06:50.393   318  6920 V AudioCache: notify(0xb54747c0, 2, 0, 0)
08-29 11:06:50.393   318  6920 V AudioCache: playback complete
08-29 11:06:50.393   318  6920 V AwesomePlayer: pause_l() 
08-29 11:06:50.393   318  1369 V AudioCache: wait - success
08-29 11:06:50.393   318  6920 V AudioCache: notify(0xb54747c0, 7, 0, 0)
08-29 11:06:50.393   318  6920 V AudioCache: ignored
08-29 11:06:50.393   318  1369 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 11:06:50.393   318  6920 V AwesomePlayer: cancelPlayerEvents
08-29 11:06:50.393   318  6920 D AudioPlayer: Pause Playback at 1068125
08-29 11:06:50.393   318  1369 V AwesomePlayer: reset_l() 
08-29 11:06:50.393   318  1369 V AudioCache: notify(0xb54747c0, 8, 0, 0)
08-29 11:06:50.393   318  1369 V AudioCache: ignored
08-29 11:06:50.393   318  1369 V AwesomePlayer: cancelPlayerEvents
08-29 11:06:50.393   318  1369 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 11:06:50.393   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 11:06:50.393   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 11:06:50.393   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 11:06:50.393   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,,bufIndex=0
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15462e0 on port 1
08-29 11:06:50.394   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 11:06:50.395   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
08-29 11:06:50.395   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 11:06:50.395   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-29 11:06:50.395   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 11:06:50.395   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
08-29 11:06:50.395   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 11:06:50.395   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 11:06:50.395   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 11:06:50.395   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 11:06:50.396   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 11:06:50.396   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 11:06:50.396   318  6922 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 11:06:50.396   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 11:06:50.396   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 11:06:50.396   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 11:06:50.408   318  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 11:06:50.408   318  1369 D AudioPlayer: AudioPlayer releasing audio source
08-29 11:06:50.408   318  1369 D AudioPlayer: AudioPlayer done releasing audio source
08-29 11:06:50.408   318  1369 V AwesomePlayer: reset_l() 
08-29 11:06:50.408   318  1369 V AwesomePlayer: cancelPlayerEvents
08-29 11:06:50.408   318  1369 V AwesomePlayer: ~AwesomePlayer call
08-29 11:06:50.408   318  1369 V AwesomePlayer: reset_l() 
08-29 11:06:50.408   318  1369 V AwesomePlayer: cancelPlayerEvents
,08-29 11:06:50.409  6813  6918 V SoundPool: close(31)
08-29 11:06:50.409  6813  6918 V SoundPool: pointer = 0x9fe88000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 11:06:50.428  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-29 11:06:50.429  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 11:06:50.432  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9596
08-29 11:06:50.443  6899  6899 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:06:50.446  6899  6899 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:06:50.446  6899  6899 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:06:50.447  6899  6899 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:06:50.448  6899  6899 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:50.448  6899  6899 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 11:06:50.458  6833  6833 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 11:06:50.625  6671  6671 I UEI.SmartControl: Supports setup maps: true
,08-29 11:06:50.628  6671  6671 D UEI.SmartControl: QS start statue = true Error code = 0
,08-29 11:06:50.628  6671  6671 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 11:06:50.628  6671  6671 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 11:06:50.628  6671  6671 I UEI.SmartControl: ### init IR Blaster...
08-29 11:06:50.631  6671  6671 D serial_port: Configuring serial port
08-29 11:06:50.632  6671  6671 E UEI.SmartControl: UEIBLaster setting for 616
08-29 11:06:50.632  6671  6671 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 11:06:50.632  6671  6671 I UEI.SmartControl: configuring settings for MAXQ616
08-29 11:06:50.632  6671  6671 I UEI.SmartControl: Get version...
08-29 11:06:50.650  6671  6925 D UEI.SmartControl: serial port data available: 21
,08-29 11:06:50.677  6671  6671 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 11:06:50.677  6671  6671 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 11:06:50.677  6671  6671 I UEI.SmartControl: QS saving settings...
08-29 11:06:50.679  6671  6671 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 11:06:50.697  6671  6925 D UEI.SmartControl: serial port data available: 4
,08-29 11:06:50.730  6671  6931 I UEI.SmartControl: Device manager: loading config....
,08-29 11:06:50.732  6671  6671 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 11:06:50.736  6671  6931 D UEI.SmartControl: ----------- loading internal config...
08-29 11:06:50.738  6671  6671 E UEI.SmartControl: Services init done
08-29 11:06:50.738  6671  6671 D UEI.SmartControl: QS Service init finished
08-29 11:06:50.739  6671  6671 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 11:06:50.739  6671  6671 D UEI.SmartControl: QS Service version code: 201091
08-29 11:06:50.740  6671  6671 D UEI.SmartControl: Service requested: Control
08-29 11:06:50.747  6671  6931 E UEI.SmartControl: Loading SETTINGS...
,08-29 11:06:50.751  6671  6671 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 11:06:50.756  6671  6671 D UEI.SmartControl: Internal service binding...
08-29 11:06:50.756  6813  6813 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 11:06:50.759  6671  6687 I UEI.SmartControl: ------ IControl API: 11
08-29 11:06:50.760  6671  6687 D UEI.SmartControl: File observer start...
08-29 11:06:50.761  6671  6687 E UEI.SmartControl: IR Port is disabled: false
,08-29 11:06:50.761  6671  6687 D UEI.SmartControl: Starting file observer...
08-29 11:06:50.761  6671  6687 I UEI.SmartControl: Registering callback...
08-29 11:06:50.762  6671  6931 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 11:06:50.762  6671  6686 I UEI.SmartControl: ------ IControl API: 19
,08-29 11:06:50.765  6671  6686 I UEI.SmartControl: Registering Services Ready callback...
08-29 11:06:50.788  6671  6930 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 11:06:50.788  6671  6930 D UEI.SmartControl: -----service ready thread exits
,08-29 11:06:50.789  6813  6828 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-29 11:06:50.790  6813  6916 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 11:06:50.791  6813  6916 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 11:06:50.792  6813  6813 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 11:06:50.793  6813  6813 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 11:06:50.794  6671  6687 I UEI.SmartControl: ------ IControl API: 8
08-29 11:06:50.798  6813  6813 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 11:06:50.798  6813  6813 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 11:06:50.799  6813  6813 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 11:06:50.800  6813  6813 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-29 11:06:50.802  6813  6813 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-29 11:06:50.803  6813  6813 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-29 11:06:50.806  6813  6813 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 11:06:50.817  6813  6813 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-29 11:06:50.829  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 11:06:50.831  6813  6813 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 11:06:50.832  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 11:06:50.833  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 11:06:50.834  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 11:06:50.835  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 11:06:50.836  6813  6813 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472461610836]
08-29 11:06:50.838  6813  6813 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-29 11:06:50.845  1043  1997 I ActivityManager: Killing 6062:com.android.gallery3d/u0a27 (adj 15): empty #17
08-29 11:06:50.869  6813  6936 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 11:06:50.876  1043  1997 I ActivityManager: Killing 6468:com.lge.email/u0a23 (adj 15): empty #18
08-29 11:06:50.906  1043  1558 W libprocessgroup: failed to open /acct/uid_10027/pid_6062/cgroup.procs: No such file or directory
,08-29 11:06:50.921  1043  1888 W libprocessgroup: failed to open /acct/uid_10023/pid_6468/cgroup.procs: No such file or directory
,08-29 11:06:50.927  6813  6813 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-29 11:06:50.929  6813  6813 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 11:06:50.929  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 11:06:50.930  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 11:06:50.930  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 11:06:50.931  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 11:06:50.931  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 11:06:50.941  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 11:06:51.511  1043  1924 D WifiServiceImplEx: setWifiEnabled: true pid=6564, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 11:06:51.512  1043  1924 D WifiService: setWifiEnabled: true pid=6564, uid=10118
08-29 11:06:51.512  1043  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:06:51.546  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 11:06:51.547  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:06:51.547  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 11:06:51.548  1043  1520 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 11:06:51.548  1043  1520 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 11:06:51.551  1043  1520 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 11:06:51.551  1043  1520 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 11:06:51.551  1043  1520 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 11:06:51.551  1043  1520 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 11:06:51.551  1043  1520 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 11:06:51.551  1043  1520 E WifiHW  : unknown target_country: EU , set to default
08-29 11:06:51.551  1043  1520 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 11:06:51.551  1043  1520 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 11:06:51.551  1043  1520 I WifiUtil: gEnableBmps=1
08-29 11:06:51.626  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:51.637  1043  1119 D Tethering: MasterInitialState.processMessage what=3
08-29 11:06:51.651  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:51.655  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:51.657  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.664  1043  1119 D Tethering: MasterInitialState.processMessage what=3
,08-29 11:06:51.673  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 11:06:51.675  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:51.678  6378  6406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 11:06:51.688  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.689  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.705  5740  5740 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 11:06:51.712  5740  5740 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 11:06:51.730  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:51.782  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:51.809  1043  1060 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6955 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-29 11:06:51.815  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:51.815  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 11:06:51.905  6955  6955 I AppUp4:AppBoxCP: onCreate
,08-29 11:06:51.906  6955  6955 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 11:06:51.917  6955  6955 I AppUp4:DB:  setFingerPrint start
,08-29 11:06:51.917  6955  6955 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-29 11:06:51.926  6955  6955 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-29 11:06:51.926  6955  6955 I AppUp4:DB:  SDK version = 21
,08-29 11:06:51.926  6955  6955 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 11:06:51.929  6955  6955 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-29 11:06:51.930  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 11:06:51.930  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:51.933  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 11:06:51.933  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 11:06:51.942  6955  6955 I AppUp4:CustModeStarterReceiver: onReceive
08-29 11:06:51.986  6955  6955 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:06:51.986  6955  6955 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:06:51.996  6955  6955 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4c64ac5
08-29 11:06:51.996  6955  6955 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:06:51.996  6955  6955 D AppUp4:CustFacade: isPhone : true
08-29 11:06:51.996  6955  6955 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:06:51.997  6955  6955 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 11:06:51.997  6955  6955 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-29 11:06:51.998  6955  6974 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-29 11:06:51.998  6955  6974 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 11:06:51.999  6955  6974 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 11:06:52.003  1043  1852 I ActivityManager: Killing 6089:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-29 11:06:52.037  1043  1729 W libprocessgroup: failed to open /acct/uid_10080/pid_6089/cgroup.procs: No such file or directory
,08-29 11:06:52.042  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:52.042  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:06:52.044  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:52.048  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:52.055  4318  6978 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:06:52.063  4318  6979 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:52.063  4318  6979 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:06:52.118  1043  1558 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6986 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 11:06:52.195  6986  6986 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:06:52.196  6986  6986 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:06:52.198  6986  6986 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 11:06:52.198  6986  6986 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 11:06:52.259  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:06:52.259  1043  1119 D Tethering: InitialState.processMessage what=4
08-29 11:06:52.259  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 11:06:52.270   314   900 D SoftapController: Softap fwReload - Ok
08-29 11:06:52.274  1043  1520 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (711ms)
,08-29 11:06:52.280   314   900 D CommandListener: Setting iface cfg
08-29 11:06:52.281   314   900 D CommandListener: Trying to bring down wlan0
08-29 11:06:52.287   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:06:52.289  1043  1520 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-29 11:06:52.283  7007  7007 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:52.283  7007  7007 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:52.311  6986  6986 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 11:06:52.316  7007  7007 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 11:06:52.324  6986  6986 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 11:06:52.353  7007  7007 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 11:06:52.353  7007  7007 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 11:06:52.357  6986  6986 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:06:52.383  6986  6986 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:06:52.383  6986  6986 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:06:52.390  1043  1520 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:06:52.390  1043  1520 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:06:52.390  1043  1520 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:06:52.390  1043  1520 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 11:06:52.390  1043  1520 D WifiMonitor: connecting to supplicant
08-29 11:06:52.392  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 11:06:52.393  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 11:06:52.394  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:52.395  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:52.396  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:52.436  7007  7007 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 11:06:52.485  7007  7007 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 11:06:52.503  1043  1520 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-29 11:06:52.504  1043  1520 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 11:06:52.504  7007  7007 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-29 11:06:52.505  7007  7007 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 11:06:52.506  1043  1520 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-29 11:06:52.506  1043  7018 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 11:06:52.506  1043  7018 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 11:06:52.506  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-29 11:06:52.506  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 11:06:52.506  1043  7018 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 11:06:52.506  1043  7018 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 11:06:52.506  1043  1520 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 11:06:52.507  1043  1520 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:52.507  1043  1520 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:52.508  1043  1520 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 11:06:52.508  1043  1520 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 11:06:52.508  1043  1520 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 11:06:52.509  1043  1520 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 11:06:52.509  1043  1520 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 11:06:52.509  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:52.509  1043  1520 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:06:52.509  1043  1520 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:06:52.509  1043  1520 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:06:52.510  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:52.510  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:52.510  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:52.510  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:06:52.511  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:52.512  1043  1520 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 11:06:52.512  1043  1520 D WifiNative-wlan0: SET update_config 1: returned true
08-29 11:06:52.513  1043  1520 D WifiConfigStore: Loading config and enabling all networks 
08-29 11:06:52.513  1043  1520 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 11:06:52.513  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-29 11:06:52.513  1043  1520 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 11:06:52.514  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:06:52.514  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:52.514  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:52.514  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:52.514  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:52.514  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:52.514  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:52.514  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:52.514  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:52.514  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:52.514  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:52.514  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 11:06:52.516  1043  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 11:06:52.516  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:52.516  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:52.516  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:52.516  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:52.516  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:52.516  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:52.516  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:52.516  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:52.516  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:52.516  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:52.516  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:52.520  1043  1520 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 11:06:52.529  6986  6986 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 11:06:52.530  1043  1520 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 11:06:52.530  1043  1520 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 11:06:52.532  1043  1520 D WifiStateMachine: enableVerboseLogging : level 2,
08-29 11:06:52.532  1043  1520 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 11:06:52.533  1043  1520 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 11:06:52.533  1043  1520 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 11:06:52.533  1043  1520 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 11:06:52.533  1043  1520 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 11:06:52.533  1043  1520 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 11:06:52.533  1043  1520 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 11:06:52.534  1043  1520 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 11:06:52.534  1043  1520 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-29 11:06:52.534  1043  1520 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 11:06:52.534  1043  1520 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 11:06:52.535  1043  1520 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 11:06:52.535  1043  1520 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 11:06:52.536  1043  1520 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 11:06:52.547  1043  1520 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:06:52.547  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-29 11:06:52.547  1043  1520 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 11:06:52.547  1925  2285 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 11:06:52.547  1925  2285 D WfdsService: Set the WFDS Monitor: true
,08-29 11:06:52.547  1925  2285 D WfdsMonitor: WfdsMonitorThread create
08-29 11:06:52.547  1925  2285 D WfdsMonitor: WFDS Monitor is created and started
08-29 11:06:52.547  1925  2285 D WfdsService: WiFi: Supplicant connection re-established
08-29 11:06:52.547  1043  1520 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 11:06:52.547  1043  1520 D WifiNative-HAL: Setting external_sim to 1
08-29 11:06:52.547  1043  1520 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 11:06:52.548  1043  1520 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 11:06:52.548  1043  1520 I WifiNative-HAL: startHal
08-29 11:06:52.548  1043  1520 D wifi    : setting scan oui 0xaf6b51e0
08-29 11:06:52.548  1925  7019 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-29 11:06:52.548  1043  1520 D WifiStateMachine: Setting OUI to DA-A1-19
,08-29 11:06:52.549  1043  1520 I WifiNative-HAL: startHal
08-29 11:06:52.549  1043  1520 D wifi    : setting scan oui 0xaf6b51e0
08-29 11:06:52.549  1925  7019 E CtrlSupplicant: Succeed to open control connection
08-29 11:06:52.549  1925  7019 E CtrlSupplicant: Succeed to open monitor connection
08-29 11:06:52.549  1043  1520 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 11:06:52.549  1043  1520 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 11:06:52.549  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 11:06:52.549  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 11:06:52.550  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 11:06:52.550  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 11:06:52.550  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 11:06:52.550  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 11:06:52.550  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 11:06:52.550  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 11:06:52.551  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 11:06:52.551  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 11:06:52.551  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 11:06:52.551  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 11:06:52.551  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 11:06:52.551  1925  7019 D WfdsMonitor: Supplicant connection established
08-29 11:06:52.551  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 11:06:52.552  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 11:06:52.552  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 11:06:52.552  7007  7007 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 11:06:52.552  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 11:06:52.552  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 11:06:52.552  1925  2285 D WfdsService: Connected to the supplicant for wfds
08-29 11:06:52.552  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 11:06:52.552  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 11:06:52.553  1043  1520 E WifiNative: : [122,815,793 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 11:06:52.553  1043  1520 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 11:06:52.554  1043  1520 D WifiNative-wlan0: RECONNECT: returned true
08-29 11:06:52.554  1043  1520 D WifiNative-wlan0: doString: [STATUS]
08-29 11:06:52.554  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:06:52.555  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 11:06:52.555  1043  1520 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 11:06:52.555  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:06:52.555  1043  1520 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:06:52.555  1043  1519 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.556  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 11:06:52.556  1043  1043 D RttService: SCAN_AVAILABLE : 3
08-29 11:06:52.556  1043  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.556  1043  1539 I WifiNative-HAL: startHal
08-29 11:06:52.556  1043  1539 D wifi ,   : getting scan capabilities on interface[1] = 0xaf6b51e0
08-29 11:06:52.556  1043  1539 D wifi    : failed to get capabilities : -3
08-29 11:06:52.556  1043  1539 E WifiScanningService: could not get scan capabilities
08-29 11:06:52.556  1043  1540 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.557  1043  1520 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 11:06:52.557  1043  1520 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 11:06:52.558   314   900 D CommandListener: Setting iface cfg
08-29 11:06:52.558  1043  1520 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 11:06:52.558   314   900 D CommandListener: Trying to bring up p2p0
08-29 11:06:52.558  1043  1520 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 11:06:52.558  1043  1519 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 11:06:52.558  1043  1519 D LGWifiP2pService: P2pEnablingState
08-29 11:06:52.559  1043  1519 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.559  1043  1519 D LGWifiP2pService: P2p socket connection successful
08-29 11:06:52.559  1043  1520 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 11:06:52.559  1043  1519 D LGWifiP2pService: P2pEnabledState,
08-29 11:06:52.559  1043  1520 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 11:06:52.559  1043  1520 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 11:06:52.559  1043  1520 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 11:06:52.560  7007  7007 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 11:06:52.560  1043  1520 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 11:06:52.560  1043  1520 E WifiStateMachine:  ConnectModeState what:132096 -100 0,
08-29 11:06:52.561  1043  1520 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 11:06:52.561  1043  1520 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 11:06:52.561  7007  7007 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 11:06:52.561  1043  1519 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 11:06:52.562  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 11:06:52.562  1925  1925 D WfdsService: WifiP2pState is changed : true
08-29 11:06:52.562  1925  2285 D WfdsService: Receive the WFDS_ENABLE Method
08-29 11:06:52.562  1925  2285 D WfdsService: Set the WFDS Monitor: true
,08-29 11:06:52.563  1925  2285 D WfdsService: Connected to the supplicant for wfds
08-29 11:06:52.563  1925  2285 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 11:06:52.563  7007  7007 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 11:06:52.563  1925  2285 D WfdsService: selectPreferredScanChannel [36]
08-29 11:06:52.563  1925  2285 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 11:06:52.563  1043  1520 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 11:06:52.564  1043  1520 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 11:06:52.564  1043  1520 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 11:06:52.564  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 11:06:52.565  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 11:06:52.565  7007  7007 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:06:52.565  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:06:52.566  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:06:52.566  1043  7018 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:06:52.566  1043  7018 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:06:52.566  7007  7007 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 11:06:52.566  7007  7007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.566  1925  7019 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:06:52.566  1043  7018 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:06:52.566  1043  7018 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.566  1043  7018 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.566  1043  7018 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.566  1043  1520 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 11:06:52.567  1043  1520 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:06:52.567  7007  7007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.567  1043  1520 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:06:52.567  1043  7018 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:06:52.567  1043  7018 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.567  1043  7018 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.568  1043  7018 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.568  1043  1520 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:06:52.568  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 11:06:52.568  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 11:06:52.568  7007  7007 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:06:52.568  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 11:06:52.568  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN,
08-29 11:06:52.568  1043  7018 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:06:52.568  1043  7018 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:06:52.568  1925  7019 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:06:52.569  1043  1520 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 11:06:52.569  1043  1520 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 11:06:52.570  1043  1520 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 11:06:52.570  1043  1520 D WifiNative-wlan0: doBoolean: SCAN
08-29 11:06:52.570  1043  1520 D WifiNative-wlan0: SCAN: returned false
,08-29 11:06:52.570  1043  1519 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 11:06:52.571  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122834  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:06:52.571  1043  1519 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 11:06:52.571  1043  1519 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 11:06:52.571  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 11:06:52.572  1925  1925 D WfdsService: isConnected: false
,08-29 11:06:52.572  1043  1519 D WifiNative-p2p0: SET device_name G3: returned true
08-29 11:06:52.572  1043  1519 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 11:06:52.572  1043  1519 D LGWifiP2pService: before postfix = G3
08-29 11:06:52.572  1043  1519 D WifiServerServiceExt: postfix byte check : 2
08-29 11:06:52.572  1043  1519 D LGWifiP2pService: after postfix = G3
08-29 11:06:52.573  1043  1519 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,08-29 11:06:52.573  1043  1519 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 11:06:52.573  1043  1519 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 11:06:52.573  1043  1519 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 11:06:52.573  1043  1519 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 11:06:52.574  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122837  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-29 11:06:52.574  1043  1520 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:06:52.575  1043  1520 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:06:52.575  1043  1520 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:06:52.575  1043  1520 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:06:52.576  1043  1520 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:06:52.577  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:52.577  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:52.577  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 11:06:52.577  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:52.577  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:52.578  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:52.579  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:52.579  1043  1043 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 11:06:52.581  1043  1519 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 11:06:52.581  1043  1519 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 11:06:52.581  1043  1519 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 11:06:52.581  1043  1519 D WifiNative-HAL: p2pGetDeviceAddress
08-29 11:06:52.582  1043  1519 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 11:06:52.582  1043  1519 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 11:06:52.582  1043  1519 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 11:06:52.583  1043  1519 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 11:06:52.583  1043  1519 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 11:06:52.583  1043  1519 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 11:06:52.583  1043  1519 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 11:06:52.583  1043  1519 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 11:06:52.583  1043  1519 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 11:06:52.583  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 11:06:52.583  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 11:06:52.583  1925  1925 D WfdsService: Update P2p Interface State: 3
08-29 11:06:52.587  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 11:06:52.587  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:52.587  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 11:06:52.589  6986  6986 I HubEmail: JNI_OnLoad()
,08-29 11:06:52.589  6986  6986 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 11:06:52.589  6986  6986 I HubEmail: registerNatives()
08-29 11:06:52.589  6986  6986 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 11:06:52.589  6986  6986 I HubEmail: registerNativeMethods()
08-29 11:06:52.589  6986  6986 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 11:06:52.589  6986  6986 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-29 11:06:52.599  1043  1519 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 11:06:52.599  1043  1519 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 11:06:52.617  1043  1924 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7025 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 11:06:52.618  1043  1519 D LGWifiP2pService: InactiveState
08-29 11:06:52.619  1043  1519 D LGWifiP2pService: InactiveState{ when=-52ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.619  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-52ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.619  1043  1519 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 11:06:52.619  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 11:06:52.620  7007  7007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:06:52.620  1043  7018 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:06:52.620  1043  7018 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:06:52.620  1043  7018 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:06:52.620  1043  7018 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:06:52.620  7007  7007 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 11:06:52.620  7007  7007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.621  1043  7018 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:06:52.621  1043  7018 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.621  1043  7018 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.621  1043  7018 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.621  7007  7007 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.621  1043  7018 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:06:52.621  1043  7018 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.621  1043  7018 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.621  1043  7018 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:06:52.622  1925  7019 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:06:52.622  1925  7019 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:06:52.622  1925  7019 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:06:52.622  1043  1519 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 11:06:52.622  1043  1519 D LGWifiP2pService: InactiveState{ when=-39ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.622  6853  7021 W FormManager: Network not available. Please check & try again.
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-39ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=,139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1925  2285 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 11:06:52.623  1043  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:52.623  1043  1043 E WifiServerServiceExt: No p2p device connected
08-29 11:06:52.624  6853  7022 V FormManager: Network unavailable.
08-29 11:06:52.624  6986  7024 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:52.626  6853  7022 V FormManager: Network unavailable.
08-29 11:06:52.637  1043  1558 I ActivityManager: Killing 6503:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 11:06:52.673  1043  1852 W libprocessgroup: failed to open /acct/uid_10061/pid_6503/cgroup.procs: No such file or directory
08-29 11:06:52.757  7025  7025 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:06:52.757  7025  7025 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:06:52.761  7025  7025 D PhoneMonitor: Register our PhoneStateListener
08-29 11:06:52.781  7025  7025 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-29 11:06:52.783  7025  7025 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 11:06:52.810  7025  7025 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 11:06:52.811  7025  7025 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 11:06:52.812  7025  7025 D TelephonyAutoProfiling: [parse] Load xml
,08-29 11:06:52.820  7025  7025 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 11:06:52.820  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 11:06:52.821  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 11:06:52.821  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 11:06:52.821  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 11:06:52.821  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 11:06:52.821  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 11:06:52.821  7025  7025 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 11:06:52.821  7025  7025 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-29 11:06:52.842  1043  1852 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7045 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:06:52.843  7025  7025 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-29 11:06:52.845  1043  1852 I ActivityManager: Killing 6109:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-29 11:06:52.897  1043  1997 W libprocessgroup: failed to open /acct/uid_10097/pid_6109/cgroup.procs: No such file or directory
,08-29 11:06:53.152  1043  1960 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7066 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 11:06:53.161  1043  1960 I ActivityManager: Killing 6631:com.lge.eula/1000 (adj 15): empty #17
08-29 11:06:53.188  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 11:06:53.188  1043  7018 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 11:06:53.189  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 11:06:53.189  7007  7007 E wpa_supplicant: USIM:  scard_init function
08-29 11:06:53.189  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-29 11:06:53.189  1043  7018 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 11:06:53.189  7007  7007 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-29 11:06:53.192  1043  1520 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 11:06:53.193  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:06:53.193  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 11:06:53.193  1043  1520 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 11:06:53.193  1043  1520 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 11:06:53.194  1043  1520 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 11:06:53.194  1043  1520 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 11:06:53.207  1043  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_6631/cgroup.procs: No such file or directory
,08-29 11:06:53.211  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123474  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 11:06:53.217  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123480  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 11:06:53.228  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.229  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.229  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 11:06:53.229  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.229  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:53.229  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.229  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.229  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 11:06:53.229  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:53.229  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 11:06:53.230  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.232  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.232  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:53.234  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.305  7007  7007 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-29 11:06:53.305  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 11:06:53.305  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 11:06:53.305  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,08-29 11:06:53.305  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 11:06:53.306  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:06:53.306  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:06:53.311  1043  1060 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7095 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:06:53.313  1043  1060 I ActivityManager: Killing 6648:com.lge.bnr/1000 (adj 15): empty #17
08-29 11:06:53.314  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123574  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 11:06:53.315  7007  7007 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:06:53.315  7007  7007 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:06:53.316  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:06:53.316  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:06:53.317  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 11:06:53.317  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:06:53.317  1043  7018 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:06:53.317  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 11:06:53.317  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:06:53.317  1043  7018 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:06:53.317  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:06:53.317  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:06:53.318  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123578  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 11:06:53.319  1043  1520 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123582
08-29 11:06:53.319  1043  1520 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123582
,08-29 11:06:53.319  1043  1520 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123582
08-29 11:06:53.320  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123583
08-29 11:06:53.320  1043  1520 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123583
08-29 11:06:53.321  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123584  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 11:06:53.399  1043  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 11:06:53.404  1043  1924 W libprocessgroup: failed to open /acct/uid_1000/pid_6648/cgroup.procs: No such file or directory,
,08-29 11:06:53.432  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=123694  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 11:06:53.432  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.432  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:53.433  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123695  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-29 11:06:53.433  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=123696  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 11:06:53.434  1043  1520 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123697
08-29 11:06:53.434  1043  1520 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123697
08-29 11:06:53.435  1043  1520 D WifiNative-wlan0: doString: [STATUS]
08-29 11:06:53.436  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:06:53.436  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:06:53.437  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.437  1043  1520 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 11:06:53.437  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.437  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-29 11:06:53.439  1043  1520 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 11:06:53.440  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.442  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.442  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.442  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 11:06:53.447  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.447  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:53.451  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:06:53.458  1043  1520 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 11:06:53.458  1043  1520 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 11:06:53.461  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.461  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.461  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 11:06:53.463  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.463  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:53.465  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:06:53.468  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.468  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.468  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 11:06:53.471  7095  7095 I art     : Almond Protected OAT
08-29 11:06:53.472  1043  1520 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 11:06:53.472  1043  1527 D ConnectivityService: Got NetworkAgent Messenger
08-29 11:06:53.472  1043  1520 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:06:53.472  1043  1520 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:06:53.472  1043  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 11:06:53.472  1043  1527 D ConnectivityService: NetworkAgent connected
08-29 11:06:53.472  1043  1520 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:06:53.472  1043  1520 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:06:53.479  1043  1520 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:06:53.479  1043  1520 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:06:53.479  1043  1520 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-29 11:06:53.480  1043  1520 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:06:53.480  1043  1520 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:06:53.486  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.486  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:53.486  1043  1520 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:06:53.488   314   900 D CommandListener: Setting iface cfg
08-29 11:06:53.488  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:06:53.490  1043  1520 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 11:06:53.490  1043  7116 D DhcpStateMachine: StoppedState
08-29 11:06:53.490  1043  7116 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.490  1043  7116 D DhcpStateMachine: WaitBeforeStartState
08-29 11:06:53.491  1043  1520 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123754  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:06:53.491  1043  1520 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123754  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:06:53.492  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=123754  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:06:53.493  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:53.493  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-29 11:06:53.494  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:53.494  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:53.495  1043  1520 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:53.495  1043  1520 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:53.495  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:53.496  1043  1520 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:53.496  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:53.496  1043  1043 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 11:06:53.497  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:53.497  1043  1043 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 11:06:53.498  1043  1520 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123761  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:06:53.499  1043  1520 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:06:53.499  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=123762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:06:53.501  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77887] from screen [on:0 period:-712169027] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 11:06:53.502  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-712169027] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 11:06:53.502  1043  1520 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 11:06:53.506  1043  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 11:06:53.506  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.507  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.507  1043  1520 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.507  1043  1520 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.508  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.508  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.509  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.509  1043  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 11:06:53.509  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=139,0,0
08-29 11:06:53.510  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=139,0,0
08-29 11:06:53.510  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 11:06:53.510  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 11:06:53.510  1043  1520 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 11:06:53.511  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 11:06:53.511  1043  1520 D WifiNative-wlan0: SET ps 0: returned true
08-29 11:06:53.511  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 11:06:53.511  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 11:06:53.512  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 11:06:53.512  1043  1520 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 11:06:53.512  1043  1520 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 11:06:53.512  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20ccfbe7 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.512  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20ccfbe7 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.512  1043  1520 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 11:06:53.512  1043  7116 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.512  1043  7116 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 11:06:53.513   314   900 D CommandListener: Setting iface cfg
08-29 11:06:53.513   314   900 D CommandListener: Trying to bring up wlan0
08-29 11:06:53.513  1043  1520 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 11:06:53.514  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:53.514  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 11:06:53.515  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:53.515  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 11:06:53.516  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.516  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.517  1043  1520 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 11:06:53.517  1043  1520 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.518  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.518  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:53.518  1043  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 11:06:53.519  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 11:06:53.519  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 11:06:53.520  1043  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.520  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.520  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:06:53.520  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:06:53.521  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:06:53.521  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 11:06:53.521  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-29 11:06:53.521  1043  1520 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-29 11:06:53.522  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:06:53.532  7095  7095 D WeatherApplication: removeAccount
08-29 11:06:53.533  7095  7095 D WeatherApplication: Account.length = 0
,08-29 11:06:53.533  7095  7095 E WeatherApplication: OPERATOR:OPEN
08-29 11:06:53.537  1043  1520 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:06:53.538  1043  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 11:06:53.538  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 11:06:53.539  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 11:06:53.539  7095  7095 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:53
08-29 11:06:53.539  1043  1520 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 11:06:53.539  1043  1527 D ConnectivityService: ignoring duplicate network state non-change
08-29 11:06:53.542  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.542  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:53.542  7095  7095 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 11:06:53.542  7095  7095 D Weather.Utils: 2 : All the weather widget is gone.
08-29 11:06:53.543  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.543  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.543  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.543  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 11:06:53.545  7095  7095 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 11:06:53.546  1043  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 11:06:53.547  1043  1527 D ConnectivityService: Adding iface wlan0 to network 101
08-29 11:06:53.549  7095  7095 D WeatherAncestor: connectivity changed - connection : true
08-29 11:06:53.551  7095  7095 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-29 11:06:53.555  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.555  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.555  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 11:06:53.556  1043  1520 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 11:06:53.559  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 11:06:53.565  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 11:06:53.565  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.565  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:53.566  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.567  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.567  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.567  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:53.567  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 11:06:53.567  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 11:06:53.568  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:06:53.569  7095  7095 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 11:06:53.569  7095  7095 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 11:06:53.569  7095  7095 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-29 11:06:53.570  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 11:06:53.576  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.576  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:53.577  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 11:06:53.586  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 11:06:53.586  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 11:06:53.586  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.595  1043  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 11:06:53.595  1043  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 11:06:53.596  1043  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 11:06:53.596  1043  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.596  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.596  1043  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.596   314   900 E Netd    : netlink response contains error (File exists)
08-29 11:06:53.596  1043  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 11:06:53.597  1043  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 11:06:53.597  1043  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 11:06:53.597  1043  1527 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-29 11:06:53.598  1043  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-29 11:06:53.598  1043  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 11:06:53.598  1043  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 11:06:53.598  1043  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 11:06:53.598  1043  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:06:53.598  1043  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:53.598  1043  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 11:06:53.598  1043  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.598  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.598  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 11:06:53.598  1043  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 11:06:53.598  1043  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-29 11:06:53.598  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:53.598  1043  1527 D ConnectivityService:    accepting network in place of null
08-29 11:06:53.598  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 11:06:53.598  1043  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.599  1043  1520 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.599  1043  1520 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:06:53.599  1835  1835 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.599  1043  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 11:06:53.599  1043  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 11:06:53.599  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 11:06:53.600  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:06:53.600   314  7121 D libc-netbsd: res_queryN name = clients3.goog,le.com, class = 1, type = 28
08-29 11:06:53.602  7095  7095 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 11:06:53.602  7095  7095 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:53
08-29 11:06:53.604  1043  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:53.604  1043  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 11:06:53.604  1043  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 11:06:53.605  1043  1043 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 11:06:53.605  1043  1527 D ConnectivityService: validation of new default Network = false
08-29 11:06:53.605  1043  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 11:06:53.605  1043  1527 D DSQN    : enableDataServiceNotify 
08-29 11:06:53.605  1043  1527 D DSQN    : start dsqn bin
08-29 11:06:53.606  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 11:06:53.606  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:06:53.606  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-29 11:06:53.611  1043  1520 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:06:53.611  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:06:53.612  1043  1520 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:06:53.612  1043  1520 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:06:53.612  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:06:53.613  1043  1520 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 11:06:53.637  1043  1639 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7122 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:06:53.638  1043  1639 I ActivityManager: Killing 2132:com.lge.music/u0a34 (adj 15): empty #17
08-29 11:06:53.638  1043  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 11:06:53.638  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.638  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 11:06:53.639  1043  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:53.639  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 11:06:53.633  7131  7131 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:53.633  7131  7131 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:53.650  7131  7131 E DSQN    : DSQN ssw
,08-29 11:06:53.652   314  7121 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 11:06:53.661   318   318 V AudioFlinger: 2132 died, releasing its sessions
08-29 11:06:53.661   318   318 V AudioFlinger:  pid 1835 @ 0
,08-29 11:06:53.661   318   318 V AudioFlinger:  pid 3411 @ 1
,08-29 11:06:53.661   318   318 V AudioFlinger:  pid 3411 @ 2
08-29 11:06:53.677  1043  1060 W libprocessgroup: failed to open /acct/uid_10034/pid_2132/cgroup.procs: No such file or directory
,08-29 11:06:53.685   314  7121 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-29 11:06:53.688  1043  1518 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-29 11:06:53.695  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:06:53.696  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.697  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.714  1043  7116 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 11:06:53.714  1043  7116 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 11:06:53.714  1043  7116 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-29 11:06:53.713  7143  7143 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:53.713  7143  7143 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:53.717   314   899 D LGDataListener: argv[0]=dsqncommand
08-29 11:06:53.717   314   899 D LGDataListener: argv[1]=wlan0
08-29 11:06:53.717   314   899 D LGDataListener: argv[2]=1
08-29 11:06:53.717   314   899 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 11:06:53.718  1043  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 11:06:53.718  1043  1117 D DSQN    : start to monitor internet connection
08-29 11:06:53.721  7143  7143 I dhcpcd  : version 5.5.6 starting
08-29 11:06:53.723  7143  7143 E dhcpcd  : get_duid: m
08-29 11:06:53.723  7143  7143 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 11:06:53.723  7143  7143 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-29 11:06:53.731  1800  7147 I CheckinService: active receiver: enabled
08-29 11:06:53.745  1800  7147 I CheckinService: Preparing to send checkin request
,08-29 11:06:53.745  1800  7147 I EventLogService: Accumulating logs since 1472461548261
08-29 11:06:53.749  1043  1360 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e636f83 type 2 when 124012 com.google.android.gms} when 124012
08-29 11:06:53.753  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 09:06:53 GMT], X-Android-Received-Millis=[1472461613752], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472461613717]}
08-29 11:06:53.753  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 11:06:53.753  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 11:06:53.756  1043  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-29 11:06:53.756  1043  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 11:06:53.756  1043  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:06:53.756  1043  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 11:06:53.756  1043  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 11:06:53.756  1043  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-29 11:06:53.756  1043  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 11:06:53.756  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.756  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:53.756  1043  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:53.756  1043  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.757  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 11:06:53.757  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 11:06:53.757  1043  1520 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.758  1835  1835 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:53.758  1043  1520 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:06:53.758  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 11:06:53.767  7143  7143 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 11:06:53.767  7143  7143 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 11:06:53.767  7143  7143 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 11:06:53.767  7143  7143 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 11:06:53.767  7143  7143 D dhcpcd  : wlan0: sending REQUEST (xid 0x6df6db74), next in 3.19 seconds
08-29 11:06:53.768   278   447 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 11:06:53.768   278   447 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 11:06:53.768   278   447 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 11:06:53.768  7122  7154 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 11:06:53.770   278   447 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 11:06:53.770   278   447 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 11:06:53.770   278   447 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:06:53.772  7122  7154 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 11:06:53.773  1800  7147 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-29 11:06:53.774  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:06:53.775  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.776  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:53.777   278   447 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 11:06:53.777   278   447 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 11:06:53.777   278   447 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 11:06:53.778  7122  7159 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 11:06:53.779   278   447 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 11:06:53.779   278   447 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 11:06:53.779   278   447 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 11:06:53.779  7122  7159 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-29 11:06:53.807  7143  7143 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 11:06:53.826  7143  7143 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 11:06:53.826  7143  7143 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-29 11:06:53.826  7143  7143 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 11:06:53.826  7143  7143 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 11:06:53.827  7143  7143 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 11:06:53.827  7143  7143 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 11:06:53.827  7143  7143 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 11:06:53.827  7143  7143 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 11:06:53.856  1043  1870 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7163 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-29 11:06:53.862   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.165ms total 13.220ms
08-29 11:06:53.874   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 244us total 11.086ms
08-29 11:06:53.886   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 240us total 10.689ms
,08-29 11:06:53.908  7163  7163 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 11:06:53.908  7163  7163 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 11:06:53.934  7163  7163 I MultiDex: VM with version 2.1.0 has multidex support
08-29 11:06:53.934  7163  7163 I MultiDex: install
08-29 11:06:53.934  7163  7163 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 11:06:53.949  7163  7163 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-29 11:06:54.047  7122  7122 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 11:06:54.058  7122  7122 I LibraryLoader: Loading: webviewchromium
08-29 11:06:54.062  7122  7122 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4330-4336)
,08-29 11:06:54.062  7122  7122 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:06:54.073  7122  7122 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27febe04}
08-29 11:06:54.077  7122  7122 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:06:54.078  7122  7122 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 11:06:54.094  7122  7122 I BrowserStartupController: Initializing chromium process, renderers=0
,08-29 11:06:54.095  7122  7122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:06:54.106  7122  7122 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-29 11:06:54.107  7122  7122 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-29 11:06:54.107  7122  7122 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-29 11:06:54.109   318  2152 V AudioPolicyService: registerClient() client 0xb0410220, uid 10093
08-29 11:06:54.110  7122  7219 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 11:06:54.117  1043  7116 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 11:06:54.118  1043  7116 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 11:06:54.118  1043  7116 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 11:06:54.118  1043  7116 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 11:06:54.118  1043  7116 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 11:06:54.118  1043  7116 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 11:06:54.118  1043  7116 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 11:06:54.118  1043  7116 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 11:06:54.118  1043  7116 D DhcpStateMachine: RunningState
,08-29 11:06:54.131  7122  7122 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:06:54.131  7122  7122 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:06:54.131  7122  7122 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:06:54.131  7122  7122 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:06:54.131  7122  7122 I Adreno-EGL: Remote Branch: 
08-29 11:06:54.131  7122  7122 I Adreno-EGL: Local Patches: 
08-29 11:06:54.131  7122  7122 I Adreno-EGL: Reconstruct Branch: 
,08-29 11:06:54.232  7122  7122 I NSApplication: Starting up...
,08-29 11:06:54.310  1043  1059 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7235 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 11:06:54.310  7163  7180 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:06:54.310  7163  7180 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:06:54.311  1043  1059 I ActivityManager: Killing 5774:com.android.vending/u0a44 (adj 15): empty #17
,08-29 11:06:54.378  1043  1888 W libprocessgroup: failed to open /acct/uid_10044/pid_5774/cgroup.procs: No such file or directory
,08-29 11:06:54.416  7235  7235 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:06:54.487  7258  7258 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 11:06:54.527  1043  1520 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:06:54.527  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:06:54.528  1043  1520 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:06:54.528  1043  1520 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:06:54.529  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-29 11:06:54.529  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:06:54.529  1043  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-29 11:06:54.530  1043  1527 D ConnectivityService: identical MTU - not setting
08-29 11:06:54.530  1043  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 11:06:54.530  1043  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 11:06:54.530  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:54.530  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:54.531  1043  1527 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:54.532  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 11:06:54.549  7258  7258 I dex2oat : dex2oat took 61.202ms (threads: 4)
08-29 11:06:54.550  1043  1870 D WifiServiceImplEx: setWifiEnabled: false pid=6564, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:06:54.550  1043  1870 D WifiService: setWifiEnabled: false pid=6564, uid=10118
08-29 11:06:54.550  1043  1870 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:06:54.560  7163  7180 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:06:54.560  7163  7180 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:06:54.560  7163  7180 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:06:54.560  7163  7180 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:06:54.560  7163  7180 I Adreno-EGL: Remote Branch: 
08-29 11:06:54.560  7163  7180 I Adreno-EGL: Local Patches: 
08-29 11:06:54.560  7163  7180 I Adreno-EGL: Reconstruct Branch: 
08-29 11:06:54.560  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:06:54.560  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:06:54.560  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 11:06:54.561  1043  1520 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:54.562  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:54.562  1043  1520 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:54.563  1043  1520 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,08-29 11:06:54.564  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 11:06:54.565  1043  1520 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 11:06:54.565  1043  1520 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:06:54.565  1043  1520 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:06:54.566  1043  1520 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:06:54.566  1043  1520 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:06:54.573  1043  1520 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:06:54.573  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:06:54.573  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.573  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.573  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:06:54.574  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:06:54.574  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:06:54.574  1043  1520 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:06:54.574  1043  7116 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.575   314   900 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:06:54.593  1043  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 11:06:54.593  1043  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-29 11:06:54.595  1043  1520 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:54.595  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:54.596  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.596  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.596  1043  1519 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2473f8eb
08-29 11:06:54.596  1043  1519 D LGWifiP2pService: P2pDisablingState
08-29 11:06:54.596  1043  1519 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.596  1043  1519 D LGWifiP2pService: p2p socket connection lost
08-29 11:06:54.596  1043  1519 D LGWifiP2pService: P2pDisabledState
08-29 11:06:54.600  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 11:06:54.595  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:54.601  1043  1520 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:54.602  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:54.602  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:06:54.602  1043  1520 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 11:06:54.602  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:54.602  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:54.602  1043  1520 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 11:06:54.602  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 11:06:54.602  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:06:54.603  7007  7007 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:06:54.603  1043  1519 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.603  1043  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.603  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:06:54.603  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:06:54.603  1043  1520 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:06:54.603  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:54.603  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:54.603  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:06:54.604  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:54.605  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 11:06:54.609  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:54.609  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:54.609  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_ST,ATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:06:54.609  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 11:06:54.609  1043  1043 D RttService: SCAN_AVAILABLE : 1
,08-29 11:06:54.610  1043  1540 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.616  1043  1539 D WifiScanningService: DefaultState got{ when=-7ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.616  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 11:06:54.616  1925  1925 D WfdsService: WifiP2pState is changed : false
08-29 11:06:54.617  1925  2285 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 11:06:54.617  1925  2285 D WfdsService: Set the WFDS Monitor: false
08-29 11:06:54.617  1925  2285 D WfdsMonitor: WFDS Monitor is stopped
08-29 11:06:54.617  1925  2285 D WfdsService: STATE : WfdsDisabledState - enter
08-29 11:06:54.617  1925  7019 D CtrlSupplicant: Received on exit socket, terminate
08-29 11:06:54.617  1925  7019 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 11:06:54.617  1925  7019 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 11:06:54.618  1925  7019 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 11:06:54.618  1925  2294 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 11:06:54.618  1925  2285 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 11:06:54.627  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:54.627  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 11:06:54.628  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:54.629   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:06:54.629  1043  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 11:06:54.629  1043  1527 D DSQN    : disableDataServiceNotify
08-29 11:06:54.629  1043  1527 D DSQN    : stop dsqn bin
08-29 11:06:54.630  1043  1520 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 11:06:54.631  1043  1520 D WifiNative-p2p0: TERMINATE: returned true
08-29 11:06:54.631  1043  1520 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:06:54.631  1043  1520 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:06:54.631  1043  1520 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:06:54.631  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 11:06:54.636  1043  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 11:06:54.636  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:54.636  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:54.636  1043  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:06:54.636  1043  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 11:06:54.636  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:54.636  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.636  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:54.636  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.636  1043  7115 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 11:06:54.636  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:06:54.637  1043  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 11:06:54.637  1043  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 11:06:54.637  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:06:54.637  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 11:06:54.638  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 11:06:54.638  1043  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:54.638  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.co,nn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:06:54.638  1043  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:54.638  1043  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:54.638  1043  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:54.639  1043  1527 D NetworkManagementService: Removing idletimer
08-29 11:06:54.639  1043  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:54.639  1043  1527 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 11:06:54.639  1835  1835 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:54.639  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 11:06:54.639  1043  1527 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-29 11:06:54.639  1043  1520 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:06:54.639  1043  1520 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:06:54.639  1043  1518 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 11:06:54.640  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:54.640  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:54.640  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:54.640  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SU,PPORTED
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:54.640  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:54.640  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:54.640  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:54.641  1043  1518 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 11:06:54.643  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 11:06:54.643  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:06:54.643  1043  1043 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 11:06:54.643  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 11:06:54.643  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 11:06:54.643  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 11:06:54.643  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:06:54.643  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:06:54.643  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 11:06:54.643  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:06:54.643  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:06:54.648  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 11:06:54.648  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:06:54.658  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:54.659  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:54.674  7163  7180 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:06:54.674  7163  7180 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:06:54.674  7163  7180 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:06:54.674  7163  7180 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:06:54.674  7163  7180 I Adreno-EGL: Remote Branch: 
08-29 11:06:54.674  7163  7180 I Adreno-EGL: Local Patches: 
08-29 11:06:54.674  7163  7180 I Adreno-EGL: Reconstruct Branch: 
,08-29 11:06:54.680  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:06:54.681  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:54.682  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:06:54.701  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:06:54.703  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:54.703  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:54.714  1043  1906 I art     : Explicit concurrent mark sweep GC freed 116581(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.240ms total 182.826ms
08-29 11:06:54.737  7163  7180 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 11:06:54.737  7163  7180 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 11:06:54.737  7163  7180 I Adreno-EGL: Build Date: 12/12/14 금
08-29 11:06:54.737  7163  7180 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 11:06:54.737  7163  7180 I Adreno-EGL: Remote Branch: 
08-29 11:06:54.737  7163  7180 I Adreno-EGL: Local Patches: 
08-29 11:06:54.737  7163  7180 I Adreno-EGL: Reconstruct Branch: 
,08-29 11:06:54.749  7007  7007 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 11:06:54.749  7007  7007 I wpa_supplicant: monitor socket send errors count : 1
08-29 11:06:54.749  7007  7007 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
08-29 11:06:54.752  1043  7018 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 11:06:54.753  1043  7018 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-29 11:06:54.774  7007  7007 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 11:06:54.776  1043  1119 D Tethering: InitialState.processMessage what=4
08-29 11:06:54.777  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 11:06:54.777  7007  7007 W wpa_supplicant: USIM:  scard_deinit function
08-29 11:06:54.777  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:06:54.777  1043  7018 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 11:06:54.777  1043  7018 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 11:06:54.778  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:06:54.778  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:06:54.778  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:06:54.780  1043  1520 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=125043
,08-29 11:06:54.781  1043  1520 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=125044
08-29 11:06:54.783  1043  1520 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=125046  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 11:06:54.783  1043  7116 D DhcpStateMachine: StoppedState
08-29 11:06:54.783  1043  7116 D DhcpStateMachine: StoppedState{ when=-180ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:06:54.784  1043  1520 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=125047  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 11:06:54.786  1043  1520 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:54.787  1043  1520 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:06:54.789  1043  1520 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 11:06:54.790  1043  1520 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 11:06:54.906  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 11:06:54.909  6378  6406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 11:06:54.928  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:54.930  7007  7007 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 11:06:54.931  1043  7018 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 11:06:54.931  1043  7018 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 11:06:54.931  1043  7018 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 11:06:54.931  1043  1520 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-29 11:06:54.942  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-29 11:06:54.942  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:54.942  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 11:06:54.942  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 11:06:54.944  6955  6955 I AppUp4:CustModeStarterReceiver: onReceive
08-29 11:06:54.948  6955  6955 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4c64ac5
08-29 11:06:54.948  6955  6955 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:06:54.948  6955  6955 D AppUp4:CustFacade: isPhone : true
08-29 11:06:54.949  6955  6955 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:06:54.949  6955  6955 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 11:06:54.950  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:54.951  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:06:54.952  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:54.953  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:54.958  4318  7279 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:06:54.961   314  7281 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 11:06:54.962  1800  7147 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-29 11:06:54.962  1043  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 11:06:54.963  6986  6986 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 11:06:54.965  4318  7282 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:54.965  4318  7282 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:06:54.970  1800  7147 I CheckinService: active receiver: disabled
,08-29 11:06:54.988  6986  7284 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:06:54.991  6853  7287 W FormManager: Network not available. Please check & try again.
08-29 11:06:54.995  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 11:06:54.995  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:54.995  6853  7288 V FormManager: Network unavailable.
08-29 11:06:54.995  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 11:06:54.999  7025  7025 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 11:06:54.999  7025  7025 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 11:06:55.010  6853  7288 V FormManager: Network unavailable.
,08-29 11:06:55.013  7095  7095 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:55
,08-29 11:06:55.015  7095  7095 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 11:06:55.015  7095  7095 D Weather.Utils: 2 : All the weather widget is gone.
08-29 11:06:55.015  7095  7095 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 11:06:55.015  7095  7095 D WeatherAncestor: connectivity changed - connection : true
08-29 11:06:55.015  7095  7095 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2cd5434b
08-29 11:06:55.016  7095  7095 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 11:06:55.016  7095  7095 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 11:06:55.016  7095  7095 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 11:06:55.016  7095  7095 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 11:06:55.016  7095  7095 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:55
08-29 11:06:55.033  1925  1925 D WfdsService: Supplicant Connection state is changed : false
,08-29 11:06:55.033  1925  2285 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 11:06:55.033  1925  2285 D WfdsService: Set the WFDS Monitor: false
08-29 11:06:55.033  1925  2285 D WfdsMonitor: WFDS Monitor is stopped
08-29 11:06:55.034  1043  1520 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 11:06:55.034  1043  1520 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:06:55.034  1043  1520 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:06:55.034  1043  1520 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:06:55.036  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 11:06:55.037  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:06:55.038  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 11:06:55.038  1043  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 11:06:55.038  1043  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 11:06:55.038  2474  2474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:55.041  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:55.041  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:55.041  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:55.041  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:55.041  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:55.041  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:55.041  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:55.041  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:55.041  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:55.042  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:55.042  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:06:55.043  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:06:55.043  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:06:55.043  6762  6762 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:06:55.043  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:06:55.044  6762  6762 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-29 11:06:55.044  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:06:55.045  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:06:55.045  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:06:55.045  6762  6762 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:06:55.045  6762  6762 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:06:55.053  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:06:55.057  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:06:55.060  6853  7292 W FormManager: Network not available. Please check & try again.
08-29 11:06:55.065  6853  7293 V FormManager: Network unavailable.
,08-29 11:06:55.067  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.067  6853  7293 V FormManager: Network unavailable.
08-29 11:06:55.085  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:06:55.089  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 11:06:55.093  6853  7295 W FormManager: Network not available. Please check & try again.
08-29 11:06:55.097  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.097  6853  7296 V FormManager: Network unavailable.
,08-29 11:06:55.103  6853  7296 V FormManager: Network unavailable.
08-29 11:06:55.114  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:06:55.115  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:06:55.116  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 11:06:55.118  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:55.123  4318  7297 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 11:06:55.125  4318  7298 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:06:55.126  4318  7298 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:06:55.182  1043  1060 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7299 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 11:06:55.328  7299  7299 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 11:06:55.328  7299  7299 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 11:06:55.334  7299  7299 V [BNRBootReceiver]: Boot Receiver Return
,08-29 11:06:55.336  7299  7299 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 11:06:55.339  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:55.350  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.357  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:06:55.371  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:55.372  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:55.375  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 11:06:55.379  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-29 11:06:55.383  6762  6762 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 11:06:55.388  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:06:55.403  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.412  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.427  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:06:55.427  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:55.430  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:06:55.438  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:55.458  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.469  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.478  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:55.479  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:55.481  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:06:55.487  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:06:55.496  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.505  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.517  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:55.518  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:55.519  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:06:55.523  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:55.534  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.542  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:06:55.552  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:55.553  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:06:55.553  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:06:55.558  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:55.571  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.579  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:06:55.587  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:06:55.588  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:55.589  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:06:55.593  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:06:55.602  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.612  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:06:55.620  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:06:55.621  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:55.622  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:06:55.635  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:06:55.666  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.679  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.695  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:06:55.696  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:55.707  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:06:55.713  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:06:55.728  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.731  6671  6932 D UEI.SmartControl: Internal timer expired: 2
08-29 11:06:55.731  6671  6932 D UEI.SmartControl: unbind internal service
08-29 11:06:55.738  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.747  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:55.748  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:06:55.751  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:06:55.758  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:55.764  6784  6784 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-29 11:06:55.776  1043  1526 D WifiService: New client listening to asynchronous messages
08-29 11:06:55.777  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:06:55.782  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.796  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.801  6671  6926 D serial_port: close(fd = 24)
08-29 11:06:55.805  6671  6926 I UEI.SmartControl: Serial port is closed.
08-29 11:06:55.810  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:55.811  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:06:55.814  6813  6813 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 11:06:55.816  6813  6813 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 11:06:55.817  6813  6813 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 11:06:55.827  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:06:55.838  6784  6784 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 11:06:55.840  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:06:55.848  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:55.860  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:55.872  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:06:55.874  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:06:55.876  6813  6813 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 11:06:55.878  6813  6813 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 11:06:55.879  6813  6813 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 11:06:55.886  1043  1639 I ActivityManager: Killing 6738:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-29 11:06:55.891   314  7322 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-29 11:06:55.894  1043  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-29 11:06:55.944  1043  1906 W libprocessgroup: failed to open /acct/uid_10037/pid_6738/cgroup.procs: No such file or directory
,08-29 11:06:55.956  2176  2176 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-29 11:06:55.972  2176  2176 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-29 11:06:55.973  2176  2176 D c       : Getting all permits...
08-29 11:06:55.973  2176  2176 D a       : Opening database...
,08-29 11:06:55.982  2176  2176 D a       : Opening database auth.proximity.permit_store...
,08-29 11:06:55.983  2176  2176 D a       : Closing database...
08-29 11:06:56.000  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:06:56.007  6784  6784 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 11:06:56.007  6784  6784 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:06:56.007  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:06:56.014  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:56.021  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:56.035  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:06:56.035  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:56.039  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:06:56.047  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:56.055  6784  6784 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:06:56.055  6784  6784 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:06:56.055  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:06:56.066  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:56.079  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:56.091  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:06:56.091  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:06:56.093  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 11:06:56.099  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:06:56.105  6784  6784 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 11:06:56.105  6784  6784 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:06:56.105  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:06:56.110  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:06:56.116  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:56.125  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:06:56.126  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:06:56.129  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:06:56.149  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:06:56.157  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:06:56.169  6853  7326 W FormManager: Network not available. Please check & try again.
08-29 11:06:56.174  6853  7327 V FormManager: Network unavailable.
08-29 11:06:56.175  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:56.194  6853  7327 V FormManager: Network unavailable.
,08-29 11:06:56.203  2176  2176 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-29 11:06:56.226  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:06:56.227  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 11:06:56.230  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 11:06:56.235  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:56.250  4318  7328 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:06:56.255  6784  6784 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-29 11:06:56.255  6784  6784 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 11:06:56.255  6784  6784 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:06:56.263  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:06:56.274  4318  7330 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:06:56.275  4318  7330 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:06:56.277  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:06:56.294  6853  7332 V FormManager: Network unavailable.
08-29 11:06:56.297  6853  7332 V FormManager: Network unavailable.
,08-29 11:06:56.298  6853  7331 W FormManager: Network not available. Please check & try again.
,08-29 11:06:56.518  1043  1520 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-712166019] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 11:06:56.519  1043  1520 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-712166009] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 11:06:56.609  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:56.622  1043  1119 D Tethering: MasterInitialState.processMessage what=3
08-29 11:06:56.634  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:56.638  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:56.641  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:56.644  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 11:06:56.645  6378  6406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 11:06:56.655  5740  5740 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 11:06:56.675  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:56.696  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 11:06:56.696  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:56.696  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 11:06:56.696  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 11:06:56.701  6955  6955 I AppUp4:CustModeStarterReceiver: onReceive
08-29 11:06:56.707  6955  6955 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4c64ac5
08-29 11:06:56.707  6955  6955 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:06:56.707  6955  6955 D AppUp4:CustFacade: isPhone : true
,08-29 11:06:56.711  6955  6955 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:06:56.711  6955  6955 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 11:06:56.755  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:56.755  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 11:06:56.764  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:56.773  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 11:06:56.779  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:56.780  4318  7354 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 11:06:56.783  6986  6986 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 11:06:56.785  4318  7355 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:56.785  4318  7355 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:06:56.801  6986  7357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:06:56.808  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-29 11:06:56.808  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:56.808  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 11:06:56.808  3411  3411 D PhoneState: setPdpRejectCasuse : false
08-29 11:06:56.811  7025  7025 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 11:06:56.811  7025  7025 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 11:06:56.814  6853  7360 W FormManager: Network not available. Please check & try again.
,08-29 11:06:56.822  6853  7361 V FormManager: Network unavailable.
08-29 11:06:56.825  7095  7095 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:56
,08-29 11:06:56.829  7095  7095 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-29 11:06:56.829  7095  7095 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 11:06:56.829  7095  7095 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 11:06:56.830  7095  7095 D WeatherAncestor: connectivity changed - connection : true
,08-29 11:06:56.830  7095  7095 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2cd5434b
08-29 11:06:56.831  7095  7095 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 11:06:56.831  7095  7095 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 11:06:56.831  7095  7095 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 11:06:56.831  7095  7095 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 11:06:56.831  7095  7095 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:56
08-29 11:06:56.832  6853  7361 V FormManager: Network unavailable.
08-29 11:06:57.562  1043  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:57.562  1043  1729 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 11:06:57.594  1043  1119 D BluetoothManagerService: Message: 1
08-29 11:06:57.594  1043  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-29 11:06:57.599  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:06:57.600  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:06:57.600  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,08-29 11:06:57.628  1043  1119 D BluetoothManagerService: Message: 20
08-29 11:06:57.628  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1830ffd:true
08-29 11:06:57.629  6899  6899 D BluetoothAdapterState: make
08-29 11:06:57.634  6899  6899 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 11:06:57.634  6899  6899 I bluedroid-qcom: init
,08-29 11:06:57.638  6899  7374 I BluetoothAdapterState: Entering OffState
08-29 11:06:57.638  6899  6899 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 11:06:57.639  6899  6899 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 11:06:57.639  6899  6899 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:06:57.639  6899  6899 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 11:06:57.639  6899  6899 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 11:06:57.639  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:57.643  1043  1119 D Tethering: MasterInitialState.processMessage what=3
08-29 11:06:57.648  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:57.651  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:57.654  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:57.654  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:57.659  6899  6899 I bluedroid-qcom: get_profile_interface socket
08-29 11:06:57.659  6899  6899 I bluedroid-qcom: get_profile_interface map_client
08-29 11:06:57.661  6899  7378 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 11:06:57.663  6899  7378 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 11:06:57.663  7377  7377 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:57.663  7377  7377 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:57.676  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-29 11:06:57.680  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 11:06:57.681  1043  1119 D Tethering: MasterInitialState.processMessage what=3
08-29 11:06:57.685  7377  7377 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 11:06:57.685  7377  7377 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 11:06:57.685  7377  7377 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 11:06:57.686  6899  7378 D BluetoothAdapterProperties: Name is: G3
08-29 11:06:57.688  7377  7377 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-29 11:06:57.698  7377  7377 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 11:06:57.698  7377  7377 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 11:06:57.700  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:57.703  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:57.705  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 11:06:57.706  1043  1119 D BluetoothManagerService: Message: 40
08-29 11:06:57.706  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 11:06:57.707  6899  6914 I bluedroid-qcom: config_hci_snoop_log
08-29 11:06:57.708  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 11:06:57.708  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 11:06:57.714  6899  7374 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 11:06:57.714  6899  7374 D BluetoothAdapterProperties: Setting state to 11
08-29 11:06:57.714  6899  7374 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 11:06:57.721  6899  7374 I LGBluetoothServiceJni: classInitNative: succeeds
,08-29 11:06:57.736  1043  1119 D BluetoothManagerService: Message: 60
08-29 11:06:57.736  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 11:06:57.737  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 11:06:57.737  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 11:06:57.738  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:57.742  6378  6406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 11:06:57.746  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:57.749  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:06:57.751  6762  6762 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 11:06:57.753  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:57.755  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:57.764  5740  5740 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 11:06:57.765  6899  7374 D BluetoothBondStateMachine: make
08-29 11:06:57.769  6899  7374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:57.769  6899  7374 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 11:06:57.769  6899  7374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:57.769  6899  7374 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 11:06:57.770  6899  7374 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 11:06:57.770  5740  5740 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 11:06:57.771  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:57.771  6899  7396 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 11:06:57.771  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:06:57.772  6899  6899 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:06:57.772  6899  6899 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:57.773  6899  6899 V BluetoothPbapReceiver: ***********state = 11
08-29 11:06:57.782  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:06:57.786  6899  7374 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:06:57.821  1043  1942 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7398 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-29 11:06:57.825  6899  7374 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:06:57.827  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:57.831  6899  6899 D HeadsetService: Received start request. Starting profile...
08-29 11:06:57.832  6899  6899 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:06:57.833  6899  6899 D LGBluetoothHfpAdapter: Version 1.6
08-29 11:06:57.836  6899  7374 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 11:06:57.840  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 11:06:57.840  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:57.840  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-29 11:06:57.840  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 11:06:57.841  6899  6899 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 11:06:57.843  6955  6955 I AppUp4:CustModeStarterReceiver: onReceive
08-29 11:06:57.844  6899  6899 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:06:57.845  6899  6899 D HeadsetStateMachine: make
08-29 11:06:57.847  6899  7374 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:06:57.849  6955  6955 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4c64ac5
08-29 11:06:57.850  6955  6955 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:06:57.850  6955  6955 D AppUp4:CustFacade: isPhone : true
08-29 11:06:57.851  6955  6955 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:06:57.852  6899  7374 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:06:57.852  6955  6955 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-29 11:06:57.856  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:57.857  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:06:57.858  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:57.860  6899  7374 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:06:57.860  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:57.865  6899  7374 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:06:57.869  6986  6986 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 11:06:57.879  4318  7416 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:06:57.882  6899  7374 V LGMDMManager: Create singleton instance
,08-29 11:06:57.885  6899  6899 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:06:57.885  6899  6899 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:06:57.888  6899  7374 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 11:06:57.889  4318  7417 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:57.890  4318  7417 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:06:57.895  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 11:06:57.895  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:57.897  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 11:06:57.898  6899  6899 D HeadsetStateMachine: max_hf_connections = 1
,08-29 11:06:57.898  6899  6899 I bluedroid-qcom: get_profile_interface handsfree
08-29 11:06:57.899  6899  6899 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 11:06:57.900  6986  7418 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:57.900   318   318 V AudioPolicyService: registerClient() client 0xb558aa60, uid 1002
08-29 11:06:57.900   318  2152 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 11:06:57.900   318  2152 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:06:57.900   318  2152 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:06:57.901  6899  6899 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 11:06:57.901   318  1368 V AudioFlinger: registerClient() client 0xb5581970, pid 6899
08-29 11:06:57.902   318  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:06:57.902   318  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:06:57.902  6899  6899 V ToneGenerator: Create Track: 0xb4928a80
08-29 11:06:57.902  6899  6899 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 11:06:57.902  6899  6899 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 11:06:57.902  1586  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:06:57.902  1586  1610 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:06:57.902  1835  1850 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:06:57.902  1835  1850 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:06:57.902   318  2152 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 11:06:57.902   318  2152 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 11:06:57.902   318  2152 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:06:57.902   318  2152 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:06:57.902  6899  6899 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 11:06:57.902  6899  6915 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:06:57.902  6899  6915 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 11:06:57.902  1043  1942 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:06:57.902  1043  1942 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:06:57.903  3411  3427 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:06:57.903  3411  3427 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:06:57.903   318  1368 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 11:06:57.903   318  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:06:57.903   318  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:06:57.903  1586  1609 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:06:57.903  1835  2421 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:06:57.903  1586  1609 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:06:57.903  1835  2421 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:06:57.903  6899  6915 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:06:57.903  6899  6915 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 11:06:57.903   318  2152 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 11:06:57.904   318  2152 V AudioPolic,yManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 11:06:57.904   318  2152 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:06:57.904   318  2152 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:06:57.904  6899  6899 V AudioSystem: getLatency() output 2, latency 50
08-29 11:06:57.904  6899  6899 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 11:06:57.904  6899  6899 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 11:06:57.904  1043  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:06:57.904  1043  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:06:57.904  3411  3426 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:06:57.904  3411  3426 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:06:57.904   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 11:06:57.904   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 11:06:57.904   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 11:06:57.904   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 11:06:57.904   318   318 V AudioFlinger: createTrack() lSessionId: 22
08-29 11:06:57.905  6853  7423 V FormManager: Network unavailable.
08-29 11:06:57.905  6853  7422 W FormManager: Network not available. Please check & try again.
08-29 11:06:57.906  6899  6899 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 11:06:57.906  7025  7025 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 11:06:57.907  7025  7025 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 11:06:57.907   318  1369 V AudioFlinger: acquiring 22 from 6899, for 6899
08-29 11:06:57.907   318  1369 V AudioFlinger:  added new entry for 22
08-29 11:06:57.907  6899  6899 V ToneGenerator: ToneGenerator INIT OK, time: 128181
08-29 11:06:57.907  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:57.908  6899  7415 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 11:06:57.908  6899  7415 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:06:57.908  6899  7415 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:06:57.908  6899  7415 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 11:06:57.910  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:57.912  6899  6899 D A2dpService: Received start request. Starting profile...
08-29 11:06:57.912   318  2152 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6899
08-29 11:06:57.913   318  2152 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 11:06:57.913   318  2152 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 11:06:57.913   318  2152 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 11:06:57.913   318  2152 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 11:06:57.913   318  2152 V voice   : voice_set_parameters: exit with code(0)
08-29 11:06:57.913  6899  6899 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 11:06:57.913   318  2152 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 11:06:57.913   318  2152 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 11:06:57.913   318  2152 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 11:06:57.913   318  2152 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 11:06:57.913   318  2152 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 11:06:57.913   318  2152 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 11:06:57.913  6899  7415 V ToneGenerator: ToneGenerator destructor
08-29 11:06:57.913  6899  7415 V ToneGenerator: stopTone
08-29 11:06:57.913  6899  7415 V ToneGenerator: Delete Track: 0xb4928a80
08-29 11:06:57.914  6899  6899 V Avrcp   : make
08-29 11:06:57.914  6899  7415 V AudioTrack: ~AudioTrack, releasing session id from 6899 on behalf of 6899
08-29 11:06:57.914   318  2152 V AudioFlinger: releasing 22 from 6899 for 6899
08-29 11:06:57.914   318  2152 V AudioFlinger:  decremented refcount to 0
08-29 11:06:57.914   318  2152 V AudioFlinger: purging stale effects
08-29 11:06:57.914  6899  6899 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 11:06:57.915  6899  6899 I bluedroid-qcom: get_profile_interface avrcp
08-29 11:06:57.916  6853  7423 V FormManager: Network unavailable.
08-29 11:06:57.916   318   318 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 11:06:57.916   318   318 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 11:06:57.916   318  1273 V AudioPolicyService: AudioCommandThread() waking up
08-29 11:06:57.916   318  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 11:06:57.916   318  1273 V AudioPolicyManager: releaseOutput() 2
08-29 11:06:57.916   318  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 11:06:57.916   318   318 V AudioFlinger: PlaybackThread::Track destructor
08-29 11:06:57.916   318   318 V AudioFlinger: removeClient_l() pid 6899, calling pid 318
08-29 11:06:57.922  6899  6899 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 11:06:57.923  6899  6899 E AudioManager: No RCC entry present to update
08-29 11:06:57.923  6899  6899 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 11:06:57.926  6899  6899 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 11:06:57.927  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 11:06:57.927  6899  6899 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 11:06:57.939  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 11:06:57.943  7095  7095 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:57
08-29 11:06:57.990  7095  7095 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 11:06:57.990  7095  7095 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 11:06:57.991  7095  7095 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 11:06:57.992  7095  7095 D WeatherAncestor: connectivity changed - connection : true
,08-29 11:06:57.992  7095  7095 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2cd5434b
08-29 11:06:57.995  7398  7398 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 11:06:57.996  7095  7095 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 11:06:57.996  7095  7095 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 11:06:57.996  7095  7095 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 11:06:57.996  7095  7095 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 11:06:57.996  7095  7095 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:57
08-29 11:06:57.997  7398  7398 W LG Account v2.2: No ProfileInfo entries
08-29 11:06:57.997  7398  7398 I LG Account v2.2: isEnabled: false
,08-29 11:06:57.998  7398  7398 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 11:06:57.998  7398  7398 I Feature : [Lifetracker]Country: EU
08-29 11:06:57.998  7398  7398 I Feature : [Lifetracker]Operator: OPEN
08-29 11:06:57.998  7398  7398 I Feature : [Lifetracker]Ranking support: false
08-29 11:06:57.999  7398  7398 I Feature : [Lifetracker]Comfort support: false
,08-29 11:06:57.999  7398  7398 I Feature : [Lifetracker]Accessory: true
08-29 11:06:57.999  7398  7398 I Feature : [Lifetracker]Health device: true
08-29 11:06:57.999  7398  7398 I Feature : [Lifetracker]Extra Pedometer: false
08-29 11:06:57.999  7398  7398 I Feature : [Lifetracker]Blood glucose device: false
08-29 11:06:58.000  7398  7398 I Feature : [Lifetracker]Device Number: 3
,08-29 11:06:58.036  6762  6762 D BluetoothPermissionRequest: onReceive
,08-29 11:06:58.050  6762  6762 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 11:06:58.064  6378  6378 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 11:06:58.067  6378  6406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 11:06:58.085  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:58.089  1043  1870 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:06:58.089  1043  1870 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:06:58.097  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 11:06:58.097  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:58.097  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 11:06:58.097  6955  6955 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 11:06:58.103  6955  6955 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 11:06:58.108  6955  6955 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4c64ac5
08-29 11:06:58.108  6955  6955 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:06:58.108  6955  6955 D AppUp4:CustFacade: isPhone : true
08-29 11:06:58.108  6955  6955 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:06:58.109  6955  6955 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 11:06:58.112  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:58.113  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 11:06:58.115  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:06:58.117  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 11:06:58.125  4318  7429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 11:06:58.127  6986  6986 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 11:06:58.128  4318  7430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:58.129  4318  7430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:06:58.144  6986  7431 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:06:58.152  3411  3411 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 11:06:58.152  3411  3411 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 11:06:58.152  3411  3411 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 11:06:58.156  7025  7025 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 11:06:58.156  7025  7025 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 11:06:58.158  6853  7433 W FormManager: Network not available. Please check & try again.
,08-29 11:06:58.169  7095  7095 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:58
08-29 11:06:58.172  6853  7435 V FormManager: Network unavailable.
,08-29 11:06:58.173  7095  7095 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 11:06:58.173  7095  7095 D Weather.Utils: 2 : All the weather widget is gone.
08-29 11:06:58.173  7095  7095 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 11:06:58.173  1043  1960 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 11:06:58.173  7095  7095 D WeatherAncestor: connectivity changed - connection : true
08-29 11:06:58.173  7095  7095 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2cd5434b
08-29 11:06:58.174  7095  7095 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 11:06:58.174  7095  7095 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 11:06:58.174  7095  7095 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 11:06:58.174  7095  7095 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 11:06:58.174  7095  7095 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:6:58
08-29 11:06:58.179  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 11:06:58.179  6853  7435 V FormManager: Network unavailable.
08-29 11:06:58.182  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:06:58.183  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 11:06:58.183  6899  6899 I BluetoothA2dpServiceJni: classInitNative
08-29 11:06:58.183  6899  6899 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:06:58.183  6899  6899 D A2dpStateMachine: make
,08-29 11:06:58.187  6899  6899 I bluedroid-qcom: get_profile_interface a2dp
08-29 11:06:58.187  6899  7437 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 11:06:58.189  6899  6899 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:06:58.189  6899  6899 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 11:06:58.190  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:58.190  6899  7436 D A2dpStateMachine: Enter Disconnected: -2
08-29 11:06:58.191  6899  6899 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 11:06:58.193  6899  6899 D HidService: Received start request. Starting profile...
08-29 11:06:58.193  6899  6899 I bluedroid-qcom: get_profile_interface hidhost
08-29 11:06:58.193  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:58.194  6899  6899 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 11:06:58.195  6899  6899 D HealthService: Received start request. Starting profile...
,08-29 11:06:58.197  6899  6899 I bluedroid-qcom: get_profile_interface health
08-29 11:06:58.197  6899  6899 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 11:06:58.198  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:58.198  6899  6899 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 11:06:58.200  6899  6899 D PanService: Received start request. Starting profile...
08-29 11:06:58.200  6899  6899 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:06:58.200  6899  6899 I bluedroid-qcom: get_profile_interface pan
08-29 11:06:58.206  6899  6899 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 11:06:58.207  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:58.208  6899  6899 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-29 11:06:58.213  6899  6899 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:06:58.213  6899  6899 D BtGatt.GattService: Received start request. Starting profile...
08-29 11:06:58.213  6899  6899 D BtGatt.GattService: start()
08-29 11:06:58.213  6899  6899 I bluedroid-qcom: get_profile_interface gatt
08-29 11:06:58.214  6899  6899 D BtGatt.AdvertiseManager: advertise manager created
08-29 11:06:58.220  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:58.221  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:58.221  6899  6899 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 11:06:58.222  6899  6899 V BluetoothMapService: BluetoothMapBinder()
,08-29 11:06:58.223  6899  6899 D BluetoothMapService: Received start request. Starting profile...
08-29 11:06:58.223  6899  6899 D BluetoothMapService: start()
08-29 11:06:58.226  6899  6899 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 11:06:58.226  6899  6899 D BluetoothMapEmailAppObserver: createReceiver()
08-29 11:06:58.227  6899  6899 D BluetoothMapEmailAppObserver: initObservers()
08-29 11:06:58.227  6899  6899 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 11:06:58.238  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:58.239  6899  6899 D HeadsetStateMachine: Proxy object connected
08-29 11:06:58.239  6899  6899 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 11:06:58.240  6899  6899 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-29 11:06:58.241  6899  7415 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-29 11:06:58.242  6899  7415 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 11:06:58.243  6899  7415 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 11:06:58.245  6899  6899 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:06:58.252  6899  6899 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 11:06:58.258  6899  6899 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:06:58.262  6899  6899 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:06:58.263  6899  6899 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 11:06:58.268  6899  6899 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 11:06:58.274  6899  6899 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 11:06:58.275  6899  6899 V BluetoothMapService: Handler(): got msg=1
08-29 11:06:58.276  6899  7374 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 11:06:58.276  6899  7374 I bluedroid-qcom: enable
,08-29 11:06:58.277  6899  7444 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 11:06:58.278  6899  7444 I bt-btu  : btu_task pending for preload complete event
08-29 11:06:58.278  6899  7374 I bt_hci_bdroid: init
08-29 11:06:58.279  6899  7374 I bt_vendor: bt-vendor : init
08-29 11:06:58.279  6899  7374 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 11:06:58.279  6899  7374 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 11:06:58.279  6899  7374 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 11:06:58.279  6899  7374 D bt_userial_mct: userial_init
08-29 11:06:58.280  6899  6899 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:58.280  6899  7374 D bt_hci_bdroid: set_power 1
08-29 11:06:58.280  6899  7374 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 11:06:58.280  6899  7374 I bt_vendor: Starting hciattach daemon
08-29 11:06:58.280  6899  7374 I bt_vendor: try to set true
08-29 11:06:58.282  6899  6899 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:06:58.283  6899  6899 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:06:58.283  6899  6899 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:06:58.273  7447  7447 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:58.273  7447  7447 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:06:58.283  6899  6899 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 11:06:58.310  7448  7448 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 11:06:58.463  7454  7454 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 11:06:58.480  7455  7455 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-29 11:06:58.503  7460  7460 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 11:06:58.517  7461  7461 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 11:06:58.530  7462  7462 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 11:06:58.548  7463  7463 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 11:06:58.580  7465  7465 I libmdmdetect: ESOC framework not supported
,08-29 11:06:58.581  7465  7465 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 11:06:58.590  7465  7465 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 11:06:58.590  7465  7465 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-29 11:06:58.590  7465  7465 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 11:06:58.590  7465  7465 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-29 11:06:58.590  7465  7465 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 11:06:58.590  7465  7465 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 11:06:58.590  7465  7465 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 11:06:58.631  7465  7466 E QC-QMI  : qmi_client [7465] 14: failed to locate client data
08-29 11:06:58.633   454   454 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 11:06:58.633   454   454 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-29 11:06:58.674  7467  7467 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 11:06:58.704  7468  7468 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:06:58.735  6899  7374 I bt_vendor: bluetooth satus is on
,08-29 11:06:58.735  6899  7374 D bt_hci_bdroid: preload
08-29 11:06:58.735  6899  7446 D bt_userial_mct: userial_open(port:0)
08-29 11:06:58.735  6899  7446 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 11:06:58.738  6899  7446 I bt_vendor: Done intiailizing UART
08-29 11:06:58.741  6899  7446 I bt_vendor: Done intiailizing UART
08-29 11:06:58.741  6899  7446 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 11:06:58.741  6899  7446 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-29 11:06:58.742  6899  7444 I bt-btu  : btu_task received preload complete event
08-29 11:06:58.742  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 11:06:58.742  6899  7470 D bt_userial_mct: Entering userial_read_thread()
08-29 11:06:58.742  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 11:06:58.744  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 11:06:58.747  6899  7444 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 11:06:58.747  6899  7444 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 11:06:58.747  6899  7444 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 11:06:58.747  6899  7444 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 11:06:58.747  6899  7444 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:06:58.748  6899  7444 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 11:06:58.752  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7447
08-29 11:06:58.752  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7468
08-29 11:06:58.790  7122  7157 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-29 11:06:58.835  6899  7444 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 11:06:58.835  6899  7444 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa019a061 
08-29 11:06:58.835  6899  7444 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019a061 
,08-29 11:06:58.883  6899  7378 E bt-btif : Calling BTA_HhEnable
,08-29 11:06:58.884  6899  7378 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 11:06:58.884  6899  7378 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 11:06:58.889  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 11:06:58.889  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 11:06:58.889  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 11:06:58.889  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 11:06:58.889  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 11:06:58.890  6899  7378 D BluetoothAdapterProperties: Name is: G3
08-29 11:06:58.891  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 11:06:58.892  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 11:06:58.894  6899  7378 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:06:58.895  6899  7378 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:06:58.897  6899  7378 D bt_hci_bdroid: postload
08-29 11:06:58.898  6899  7446 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:06:58.899  6899  7444 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 11:06:58.899  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:58.900  6899  7378 D bte_conf: Device ID record 1 : primary
08-29 11:06:58.900  6899  7378 D bte_conf:   vendorId            = 00c4
08-29 11:06:58.900  6899  7378 D bte_conf:   vendorIdSource      = 0001
08-29 11:06:58.900  6899  7378 D bte_conf:   product             = 13a1
08-29 11:06:58.900  6899  7378 D bte_conf:   version             = 1000
08-29 11:06:58.901  6899  7378 D bte_conf:   clientExecutableURL = 
08-29 11:06:58.901  6899  7378 D bte_conf:   serviceDescription  = 
,08-29 11:06:58.901  6899  7378 D bte_conf:   documentationURL    = 
08-29 11:06:58.901  6899  7378 D bte_conf: bte_load_did_conf no section named DID2.
08-29 11:06:58.905  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:58.907  6899  7444 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:06:58.907  6899  7444 W bt-smp  : Plain text(LSB ~ MSB) = 1b b8 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:06:58.907  6899  7444 W bt-smp  : Encrypted text(LSB ~ MSB) = f8 94 2d a1 0d 46 8f 04 19 a0 6b 6d f5 ae 0f c5 
08-29 11:06:58.907  6899  7444 W bt-btm  : Stopping oneshot timer
08-29 11:06:58.907  6899  7446 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:06:58.910  6899  7374 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 11:06:58.910  6899  7374 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:06:58.910  6899  7374 D BluetoothAdapterProperties: State =  11
08-29 11:06:58.910  6899  7374 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 11:06:58.910  6899  7374 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 11:06:58.911  6899  7374 D BluetoothAdapterProperties: Setting state to 12
08-29 11:06:58.911  6899  7374 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 11:06:58.911  1043  1119 D BluetoothManagerService: Message: 60
08-29 11:06:58.911  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 11:06:58.911  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-29 11:06:58.912  6899  7374 I BluetoothAdapterState: Entering On State
08-29 11:06:58.903  7474  7474 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:58.913  6899  7378 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 11:06:58.913  6899  7378 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:06:58.903  7474  7474 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:58.915  1835  2421 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:06:58.917  6899  7446 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:06:58.918  6899  7446 D bt_hci_bdroid: Used up Tx Cmd credits
,08-29 11:06:58.921  6899  7374 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 11:06:58.921  6899  7374 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 11:06:58.921  6899  7374 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 11:06:58.922  6899  7374 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 11:06:58.924  6899  7446 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:06:58.924  6899  7446 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:06:58.926  1835  3995 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:06:58.927  1835  1835 D BluetoothHeadset: Proxy object connected
08-29 11:06:58.928  6899  7470 E bt_mct  : hci lib postload completed
08-29 11:06:58.929  1835  1835 D BluetoothHeadset: Proxy object connected
08-29 11:06:58.930  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:06:58.931  1043  1043 D BluetoothHeadset: Proxy object connected
,08-29 11:06:58.933  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:06:58.934  6899  7378 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:06:58.934  6899  7378 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 11:06:58.936  6762  6874 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:06:58.936  1043  1043 D BluetoothA2dp: Proxy object connected
08-29 11:06:58.946  6899  7444 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:06:58.946  6899  7444 W bt-smp  : Plain text(LSB ~ MSB) = 4b 9a 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:06:58.946  6899  7444 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 05 c1 70 e1 d1 69 70 bb 42 b6 bf 3c e2 21 9b 
08-29 11:06:58.946  6899  7444 W bt-btm  : Stopping oneshot timer
,08-29 11:06:58.951  6762  6762 D BluetoothInputDevice: Proxy object connected
08-29 11:06:58.951  6762  6762 D HidProfile: Bluetooth service connected
08-29 11:06:58.951  6762  6780 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:06:58.951  6762  6780 D BluetoothPan: onBluetoothStateChange call bindService
08-29 11:06:58.955  6762  6874 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:06:58.957  6762  6762 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:06:58.957  6762  6762 D PanProfile: Bluetooth service connected
08-29 11:06:58.957  1835  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:06:58.958  6899  7444 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:06:58.958  6899  7444 W bt-smp  : Plain text(LSB ~ MSB) = 36 6d 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:06:58.958  6899  7444 W bt-smp  : Encrypted text(LSB ~ MSB) = 75 da 40 a1 79 8a be e4 ae a1 c3 71 fd 62 1b 21 
08-29 11:06:58.958  6899  7444 W bt-btm  : Stopping oneshot timer
,08-29 11:06:58.962  1835  1835 D BluetoothHeadset: Proxy object connected
08-29 11:06:58.963  6762  6780 D BluetoothMap: onBluetoothStateChange: up=true
08-29 11:06:58.965  6899  7374 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 11:06:58.966  6762  6762 D BluetoothMap: Proxy object connected
08-29 11:06:58.966  6762  6762 D MapProfile: Bluetooth service connected
08-29 11:06:58.966  6762  6762 D BluetoothMap: getConnectedDevices()
08-29 11:06:58.968  1043  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 11:06:58.968  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 11:06:58.969  6899  7444 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:06:58.969  6899  7444 W bt-smp  : Plain text(LSB ~ MSB) = 8c 26 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:06:58.969  6899  7444 W bt-smp  : Encrypted text(LSB ~ MSB) = 0d e1 33 77 1d 90 1f f5 33 1d ad 6d 80 7a ae 6d 
08-29 11:06:58.969  6899  7444 W bt-btm  : Stopping oneshot timer
08-29 11:06:58.969  6899  6915 V BluetoothMapService: getConnectedDevices()
08-29 11:06:58.971  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:06:58.975  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:06:58.977  1925  2104 D LGBluetoothAPIService: Message: 1
08-29 11:06:58.977  1925  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 11:06:58.980  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 11:06:58.981  7479  7479 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 11:06:58.984  1043  1119 D BluetoothManagerService: Message: 40
08-29 11:06:58.984  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 11:06:58.985  1925  2104 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 11:06:58.987  6564  6564 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-29 11:06:58.988  6899  7444 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:06:58.988  6899  7444 W bt-smp  : Plain text(LSB ~ MSB) = b7 ac 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:06:58.988  6899  7444 W bt-smp  : Encrypted text(LSB ~ MSB) = 12 4b a5 a5 94 f3 c7 58 87 fa 1b f7 24 8e c8 bc 
08-29 11:06:58.988  6899  7444 W bt-btm  : Stopping oneshot timer
08-29 11:06:58.991  6899  6899 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:58.991  6899  6899 D BluetoothMapService: STATE_ON
08-29 11:06:58.993  6899  6899 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 11:06:58.993  6899  6899 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 11:06:58.995  6762  6762 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 11:06:58.997  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 11:06:58.997  1925  2104 D LGBluetoothAPIService: Message: 100
08-29 11:06:58.997  1925  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 11:06:58.999  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:58.999  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:58.999  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:58.999  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:58.999  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:58.999  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:58.999  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:58.999  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:06:59.002  1043  1119 D BluetoothManagerService: Message: 30
08-29 11:06:59.006  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:59.009  6762  6762 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 11:06:59.011  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:59.011  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:59.011  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:06:59.011  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:59.011  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:59.011  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:59.011  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:59.011  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:59.013  1043  1119 D BluetoothManagerService: Message: 30
,08-29 11:06:59.015  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:59.017  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:59.017  6899  6899 V BluetoothPbapService: Pbap Service onCreate
08-29 11:06:59.017  6899  6899 V BluetoothPbapService: Starting PBAP service
08-29 11:06:59.018  6762  6762 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 11:06:59.019  6899  6899 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 11:06:59.019  6899  6899 V BluetoothMapService: Handler(): got msg=1
08-29 11:06:59.019  6899  6899 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 11:06:59.020  6899  6899 V BluetoothPbapService: Pbap Service onBind
08-29 11:06:59.021  6762  6762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:06:59.021  6899  7486 D BluetoothMapMasInstance: MAS initSocket()
08-29 11:06:59.021  6899  6899 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:59.021  6899  6899 V BluetoothPbapService: state: 12
08-29 11:06:59.021  6899  6899 V BluetoothPbapService: Handler(): got msg=1
08-29 11:06:59.021  6899  7486 D BluetoothMapMasInstance:   masId = 00
08-29 11:06:59.021  6899  7486 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 11:06:59.021  6899  7486 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 11:06:59.021  6899  7486 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 11:06:59.022  6899  6899 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 11:06:59.023  6899  7487 V BluetoothPbapService: Pbap Service initSocket
08-29 11:06:59.024  6762  6762 D BluetoothA2dp: Proxy object connected
08-29 11:06:59.024  1043  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:59.024  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:59.025  6762  6762 D A2dpProfile: Bluetooth service connected
,08-29 11:06:59.026  6899  6899 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:06:59.026  6899  6899 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:59.026  6899  6899 V BluetoothPbapReceiver: ***********state = 12
08-29 11:06:59.027  6762  6762 D BluetoothHeadset: Proxy object connected
08-29 11:06:59.028  6762  6762 D HeadsetProfile: Bluetooth service connected
08-29 11:06:59.029  6899  7487 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:06:59.029  6899  7486 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:06:59.030  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:06:59.031  2176  2176 D c       : Getting all permits...
08-29 11:06:59.031  2176  2176 D a       : Opening database...
08-29 11:06:59.032  6899  7486 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 11:06:59.033  6899  7486 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 11:06:59.033  6899  7486 D BluetoothMapMasInstance: Accepting socket connection...
08-29 11:06:59.033  6899  7378 D BluetoothAdapterProperties: Scan Mode:21
,08-29 11:06:59.033  6899  7378 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 11:06:59.033  6899  7487 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 11:06:59.033  6899  7487 V BluetoothPbapService: Succeed to create listening socket 
08-29 11:06:59.033  6899  7487 V BluetoothPbapService: Accepting socket connection...
08-29 11:06:59.035  6762  6762 D BluetoothPbap: Proxy object connected
08-29 11:06:59.036  6762  6762 D PbapServerProfile: Bluetooth service connected
08-29 11:06:59.039  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:59.040  2176  2176 D a       : Opening database auth.proximity.permit_store...
08-29 11:06:59.041  2176  2176 D a       : Closing database...
,08-29 11:06:59.041  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:59.045  6762  6762 D DockEventReceiver: finishStartingService: stopping service
08-29 11:06:59.054  6762  6762 D BluetoothPermissionRequest: onReceive
,08-29 11:06:59.056  6762  6762 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 11:06:59.059  6762  6762 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:06:59.062  6899  6899 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 11:06:59.064  6899  6899 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 11:06:59.072  6899  6899 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 11:06:59.097  6899  6899 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 11:06:59.098  6899  6899 V BtOppService: onCreate
08-29 11:06:59.102  6899  6899 V BluetoothOppNotification: send message
08-29 11:06:59.107  6899  6899 V BtOppService: Starting RfcommListener
08-29 11:06:59.123  6899  6899 D BluetoothOppPreference: Dumping Names:  
08-29 11:06:59.123  6899  6899 D BluetoothOppPreference: {}
,08-29 11:06:59.123  6899  6899 D BluetoothOppPreference: Dumping Channels:  
08-29 11:06:59.123  6899  6899 D BluetoothOppPreference: {}
08-29 11:06:59.125  6899  6899 V BtOppService: onStartCommand
08-29 11:06:59.128  6899  7495 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:06:59.132  6899  6899 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:59.132  6899  6899 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 11:06:59.134  6899  7495 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:06:59.134  6899  7492 V BtOppService: Deleted complete outbound shares, number =  0
08-29 11:06:59.137  6899  7495 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3198e64 on behalf of 
08-29 11:06:59.137  6899  6899 V BluetoothOppNotification: new notify threadi!
08-29 11:06:59.138  6899  6899 V BluetoothOppNotification: send delay message
,08-29 11:06:59.139  6899  7495 V BluetoothOppNotification: update too frequent, put in queue
,08-29 11:06:59.141  6899  7492 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 11:06:59.142  6899  7492 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 11:06:59.142  6899  6899 V BtOppService: start RfcommListener
08-29 11:06:59.143  6899  7496 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 11:06:59.144  6899  7492 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@209c48cd on behalf of 
08-29 11:06:59.147  6899  7495 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-29 11:06:59.147  6899  7495 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:06:59.149  6899  7496 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c47a582 on behalf of 
08-29 11:06:59.149  6899  7495 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@237b4493 on behalf of 
08-29 11:06:59.150  6899  6899 V BtOppService: RfcommListener started
08-29 11:06:59.151  6899  6899 V BtOppService: ContentObserver received notification
08-29 11:06:59.153  6899  7496 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 11:06:59.153  6899  7497 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 11:06:59.153  6899  7495 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:06:59.153  1043  1852 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:59.153  6899  7495 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:06:59.154  6899  7496 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 11:06:59.157  6899  7497 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:06:59.158  6899  7497 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-29 11:06:59.159  6899  7497 V BtOppRfcommListener: Started RFCOMM listener....
08-29 11:06:59.159  6899  7497 I BtOppRfcommListener: Accept thread started.
08-29 11:06:59.159  6899  7497 V BtOppRfcommListener: Accepting connection...
08-29 11:06:59.160  6899  7495 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7132cd0 on behalf of 
08-29 11:06:59.160  6899  7496 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13b1a4c9 on behalf of 
08-29 11:06:59.161  6899  7496 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 11:06:59.162  6899  7495 V BluetoothOppNotification: update too frequent, put in queue
08-29 11:06:59.163  6899  7496 V BluetoothOppNotification: outbound notification was removed.
08-29 11:06:59.163  6899  7496 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 11:06:59.164  6899  7495 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 11:06:59.165  6899  7496 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f4e97ce on behalf of 
08-29 11:06:59.166  6899  7496 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 11:06:59.168  6899  7496 V BluetoothOppNotification: inbound notification was removed.
08-29 11:06:59.168  6899  7496 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 11:06:59.168  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:59.169  6899  6899 V BluetoothFtpService: Ftp Service onCreate
08-29 11:06:59.169  6899  6899 I BluetoothFtpService: Ftp Service onCreate
08-29 11:06:59.169  6899  6899 V BluetoothFtpService: Ftp Service onStartCommand
08-29 11:06:59.169  6899  6899 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:59.169  6899  6899 V BluetoothFtpService: Starting Listening on sockets
08-29 11:06:59.169  6899  6899 V BtOppService: ContentObserver received notification
08-29 11:06:59.170  6899  7496 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ec645fc on behalf of 
08-29 11:06:59.170  6899  6899 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:06:59.170  6899  6899 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:06:59.170  6899  6899 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:06:59.170  6899  6899 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:59.170  6899  6899 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 11:06:59.170  6899  6899 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 11:06:59.172  6899  6899 V BluetoothFtpService: Handler(): got msg=1
08-29 11:06:59.173  6899  6899 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,08-29 11:06:59.173  6899  6899 V BluetoothFtpService: Ftp Service initSocket
08-29 11:06:59.174  6899  7498 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:06:59.174  6899  7498 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:06:59.175  6899  7498 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a6c485 on behalf of 
08-29 11:06:59.176  6899  7498 V BluetoothOppNotification: update too frequent, put in queue
08-29 11:06:59.178  6899  7498 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 11:06:59.180  1043  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:59.181  6899  6899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:06:59.183  6899  6899 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-29 11:06:59.183  6899  6899 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 11:06:59.185  6899  7499 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 11:06:59.211  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:06:59.211  6899  6899 V BluetoothSapService: Sap Service onCreate
,08-29 11:06:59.214  6899  6899 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:59.214  6899  6899 V BluetoothSapService: state: 12
08-29 11:06:59.214  6899  6899 V BluetoothSapService: Starting SAP server process
08-29 11:06:59.217  6899  6899 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 11:06:59.213  7500  7500 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:59.213  7500  7500 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:06:59.220  6899  7501 V BluetoothSapService: Sap Service initRfcommSocket
08-29 11:06:59.221  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:06:59.222  6899  7501 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:06:59.225  6899  7501 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 11:06:59.226  6899  7501 V BluetoothSapService: Succeed to create listening socket 
08-29 11:06:59.227  6899  7501 V BluetoothSapService: Accepting socket connection...
,08-29 11:06:59.237  7500  7500 V BT_SAP  : Event pipe created
08-29 11:06:59.237  7500  7500 V BT_SAP  : create_server_socket qcom.sap.server
,08-29 11:06:59.237  7500  7500 V BT_SAP  : created socket fd 6
,08-29 11:06:59.601  1043  1519 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:06:59.602  1043  1519 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:06:59.633  1043  1520 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 11:06:59.634  1043  1520 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 11:06:59.928  1043  1996 I ActivityManager: Killing 7299:com.lge.bnr/1000 (adj 15): empty #17
,08-29 11:06:59.959  1043  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_7299/cgroup.procs: No such file or directory
,08-29 11:06:59.970  1043  1997 I ActivityManager: Killing 6671:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 11:06:59.989  6813  6813 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 11:06:59.989  6813  6813 W System.err: android.os.DeadObjectException
08-29 11:06:59.990  6813  6813 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 11:06:59.990  6813  6813 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 11:06:59.990  6813  6813 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 11:06:59.990  6813  6813 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 11:06:59.990  6813  6813 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 11:06:59.990  6813  6813 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 11:06:59.990  6813  6813 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:06:59.990  6813  6813 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:06:59.990  6813  6813 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:06:59.990  6813  6813 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:06:59.990  6813  6813 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:59.990  6813  6813 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:06:59.990  6813  6813 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:06:59.990  6813  6813 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:06:59.991  6813  6813 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 11:06:59.991  6813  6813 W System.err: android.os.DeadObjectException
08-29 11:06:59.991  6813  6813 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 11:06:59.991  6813  6813 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 11:06:59.991  6813  6813 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 11:06:59.991  6813  6813 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 11:06:59.991  6813  6813 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 11:06:59.991  6813  6813 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 11:06:59.991  6813  6813 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:06:59.991  6813  6813 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:06:59.991  6813  6813 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:06:59.991  6813  6813 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:06:59.991  6813  6813 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:59.991  6813  6813 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:06:59.992  6813  6813 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:06:59.992  6813  6813 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:06:59.992  6813  6813 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 11:06:59.992  6813  6813 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-29 11:07:00.027  1043  1059 W libprocessgroup: failed to open /acct/uid_1000/pid_6671/cgroup.procs: No such file or directory
08-29 11:07:00.027  1043  1059 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 11:07:00.033  1043  1360 D PowerManagerServiceEx: acquireWakeLockInternal: lock=383609739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1043
08-29 11:07:00.037  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-29 11:07:00.037  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-29 11:07:00.037  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-29 11:07:00.037  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-29 11:07:00.039  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-29 11:07:00.039  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
,08-29 11:07:00.043  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-29 11:07:00.044  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
08-29 11:07:00.047  6813  6813 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 11:07:00.047  6813  6813 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 11:07:00.103  1043  1060 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7511 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:07:00.118  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-29 11:07:00.139  6899  6899 V BluetoothOppNotification: new notify threadi!
08-29 11:07:00.140  6899  6899 V BluetoothOppNotification: send delay message
,08-29 11:07:00.165  6899  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 11:07:00.169  6813  6813 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 11:07:00.170  6813  6813 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-29 11:07:00.171  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9596
08-29 11:07:00.172  1043  1043 D PowerManagerServiceEx: releaseWakeLockInternal: lock=383609739 [*alarm*], flags=0x0
08-29 11:07:00.176  6899  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e142401 on behalf of 
08-29 11:07:00.177  6899  7520 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 11:07:00.178  6899  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 11:07:00.179  6899  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b51d2a6 on behalf of 
08-29 11:07:00.180  6899  7520 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-29 11:07:00.181  6899  7520 V BluetoothOppNotification: outbound notification was removed.
08-29 11:07:00.181  6899  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 11:07:00.183  6899  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@126974e7 on behalf of 
08-29 11:07:00.184  6899  7520 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 11:07:00.186  6899  7520 V BluetoothOppNotification: inbound notification was removed.
08-29 11:07:00.186  6899  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 11:07:00.188  6899  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a2f5894 on behalf of 
,08-29 11:07:00.325  1043  1997 I art     : Explicit concurrent mark sweep GC freed 75219(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.974ms total 109.773ms
,08-29 11:07:00.354  7511  7511 D UEI.SmartControl: Quickset Services start...
,08-29 11:07:00.355  7511  7511 I UEI.SmartControl: Manufacture = LGE
08-29 11:07:00.356  7511  7511 D UEI.SmartControl: Id = LGNevo
08-29 11:07:00.359  7511  7511 D UEI.SmartControl: File observer start...
08-29 11:07:00.360  7511  7511 E UEI.SmartControl: IR Port is disabled: false
08-29 11:07:00.361  7511  7511 D UEI.SmartControl: Starting file observer...
08-29 11:07:00.361  7511  7511 D UEI.SmartControl: Extracting JNI libs...
,08-29 11:07:00.361  7511  7511 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 11:07:00.469  7511  7511 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 11:07:00.469  7511  7511 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 11:07:00.469  7511  7511 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 11:07:00.495  7511  7511 I UEI.SmartControl: --- Selecting new region: 6
,08-29 11:07:00.497  7511  7511 I UEI.SmartControl: Model = LG-D855
,08-29 11:07:00.499  7511  7511 D UEI.SmartControl: QS Service created
08-29 11:07:00.511  7511  7511 I UEI.SmartControl: Service initServices...
08-29 11:07:00.514  7511  7511 D UEI.SmartControl: QS start get config
,08-29 11:07:00.557  7511  7511 D UEI.SmartControl: Loading JNI Libs...
,08-29 11:07:00.625  1043  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:07:00.625  1043  1729 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3566770c mBinding = false
,08-29 11:07:00.642  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 11:07:00.643  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 11:07:00.646  1043  1119 D BluetoothManagerService: Message: 2
08-29 11:07:00.647  1043  1119 D BluetoothManagerService: Sending off request.
08-29 11:07:00.647  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 11:07:00.647  6899  7484 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 11:07:00.648  6899  7374 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 11:07:00.648  6899  7374 D BluetoothAdapterProperties: Setting state to 13
08-29 11:07:00.648  6899  7374 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 11:07:00.648  1043  1119 D BluetoothManagerService: Message: 60
08-29 11:07:00.648  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 11:07:00.648  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 11:07:00.649  6899  7374 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 11:07:00.649  6899  7374 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 11:07:00.650  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:00.652  6899  6899 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:00.652  6899  6899 D BluetoothMapService: STATE_TURNING_OFF
08-29 11:07:00.652  6899  6899 V BluetoothMapService: Handler(): got msg=4
08-29 11:07:00.652  6899  6899 D BluetoothMapService: MAP Service closeService in
08-29 11:07:00.652  6899  6899 D BluetoothMapMasInstance: MAP Service shutdown
08-29 11:07:00.654  6899  7486 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 11:07:00.654  6899  7486 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:07:00.654  6899  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 11:07:00.654  6899  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 11:07:00.654  6899  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 11:07:00.654  6899  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 11:07:00.654  6899  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 11:07:00.654  6899  7486 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 11:07:00.655  6899  6899 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:07:00.655  6899  6899 V BluetoothMapService: MAP Service closeService out
08-29 11:07:00.655  6899  6899 V BtOppService: Receiver DISABLED_ACTION 
08-29 11:07:00.655  6899  6899 I BtOppRfcommListener: stopping Accept Thread
08-29 11:07:00.656  6899  6899 V BtOppRfcommListener: close mBtServerSocket
08-29 11:07:00.656  6899  7497 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:07:00.656  6899  6899 V BtOppRfcommListener: waiting for thread to terminate
08-29 11:07:00.656  6899  7497 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:07:00.657  6899  6899 V BtOppRfcommListener: done waiting for thread to terminate
08-29 11:07:00.658  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:07:00.662  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:07:00.662  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:00.662  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - i,s Wi-Fi Direct supported: true
08-29 11:07:00.662  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:00.662  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:00.662  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:07:00.662  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:00.662  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:00.662  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:07:00.662  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:07:00.663  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:07:00.664  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:07:00.664  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:00.664  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:00.664  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:00.664  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:00.664  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:07:00.664  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:00.664  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:00.664  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:00.665  6564  6564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:07:00.665  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:07:00.672  6762  6762 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 11:07:00.679  6762  6762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:07:00.681  6899  7378 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:07:00.683  6899  7374 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true,
08-29 11:07:00.683  6899  7499 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:07:00.683  6899  7374 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:07:00.684  6899  7501 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:07:00.684  6899  7487 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:07:00.685  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 11:07:00.685  6899  7444 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 11:07:00.687  6899  6899 V BtOppService: onDestroy
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 11:07:00.688  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 11:07:00.688  6899  7444 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 11:07:00.692  6899  6899 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 11:07:00.694  6762  6762 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:07:00.697  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:00.697  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:00.698  6899  6899 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:07:00.698  6899  6899 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:00.698  6899  6899 V BluetoothPbapReceiver: ***********state = 13
08-29 11:07:00.700  6899  6899 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 11:07:00.702  6899  6899 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:00.702  6899  6899 V BluetoothPbapService: state: 13
08-29 11:07:00.702  6899  6899 V BluetoothPbapService: Pbap Service closeService in
08-29 11:07:00.703  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:07:00.705  6899  6899 V BluetoothPbapService: successfully stopped pbap service
08-29 11:07:00.705  6899  6899 V BluetoothPbapService: Pbap Service closeService out
08-29 11:07:00.706  6899  6899 V BluetoothPbapService: Pbap Service onDestroy
08-29 11:07:00.706  6899  6899 V BluetoothPbapService: Pbap Service closeService in
08-29 11:07:00.706  6899  6899 V BluetoothPbapService: Pbap Service closeService out
08-29 11:07:00.706  6899  6899 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-29 11:07:00.708  6762  6762 D BluetoothPbap: Proxy object disconnected
08-29 11:07:00.708  6762  6762 D PbapServerProfile: Bluetooth service disconnected
08-29 11:07:00.713  6762  6762 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 11:07:00.716  6762  6762 D BluetoothPermissionRequest: onReceive
08-29 11:07:00.716  6762  6762 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 11:07:00.722  6762  6762 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:07:00.724  6899  6899 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 11:07:00.724  6899  6899 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 11:07:00.725  6899  6899 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 11:07:00.728  6899  6899 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:00.728  6899  6899 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 11:07:00.729  6899  6899 V BluetoothFtpService: Ftp Service onStartCommand
08-29 11:07:00.729  6899  6899 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:00.729  6899  6899 V BluetoothFtpService: Ftp Service closeService
08-29 11:07:00.729  6899  6899 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-29 11:07:00.730  6899  6899 V BluetoothFtpService: successfully stopped ftp service
08-29 11:07:00.730  6899  6899 V BluetoothFtpService: Ftp Service onDestroy
08-29 11:07:00.730  6899  6899 V BluetoothFtpService: Ftp Service closeService
08-29 11:07:00.732  6899  6899 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:07:00.732  6899  6899 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:07:00.732  6899  6899 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:07:00.732  6899  6899 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:00.732  6899  6899 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 11:07:00.732  6899  6899 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 11:07:00.734  6899  6899 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:00.734  6899  6899 V BluetoothSapService: state: 13
08-29 11:07:00.734  6899  6899 V BluetoothSapService: Stopping SAP server process
08-29 11:07:00.734  6899  6899 V BluetoothSapService: Sap Service closeSapService in
08-29 11:07:00.734  6899  6899 V BluetoothSapService: Close listen Socket : 
08-29 11:07:00.734  6899  6899 V BluetoothSapService: Close rfcomm Socket : 
08-29 11:07:00.735  6899  6899 V BluetoothSapService: Close sapd  Socket : 
08-29 11:07:00.737  6899  6899 V BluetoothSapService: Sap Service closeSapService out
08-29 11:07:00.737  6899  6899 V BluetoothSapService: Sap Service onDestroy
08-29 11:07:00.737  6899  6899 V BluetoothSapService: Sap Service closeSapService in
08-29 11:07:00.737  6899  6899 V BluetoothSapService: Close listen Socket : 
08-29 11:07:00.737  6899  6899 V BluetoothSapService: Close rfcomm Socket : 
08-29 11:07:00.737  6899  6899 V BluetoothSapService: Close sapd  Socket : 
08-29 11:07:00.737  6899  6899 V BluetoothSapService: Sap Service closeSapService out
08-29 11:07:00.902  7511  7511 I UEI.SmartControl: Supports setup maps: true
,08-29 11:07:00.905  7511  7511 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 11:07:00.906  7511  7511 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 11:07:00.906  7511  7511 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 11:07:00.906  7511  7511 I UEI.SmartControl: ### init IR Blaster...
08-29 11:07:00.912  7511  7511 D serial_port: Configuring serial port
08-29 11:07:00.916  7511  7511 E UEI.SmartControl: UEIBLaster setting for 616
08-29 11:07:00.916  7511  7511 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 11:07:00.916  7511  7511 I UEI.SmartControl: configuring settings for MAXQ616
08-29 11:07:00.916  7511  7511 I UEI.SmartControl: Get version...
,08-29 11:07:00.934  7511  7566 D UEI.SmartControl: serial port data available: 21
,08-29 11:07:00.964  7511  7511 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-29 11:07:00.964  7511  7511 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-29 11:07:00.965  7511  7511 I UEI.SmartControl: QS saving settings...
08-29 11:07:00.969  7511  7511 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 11:07:00.987  7511  7566 D UEI.SmartControl: serial port data available: 4
,08-29 11:07:01.030  7511  7569 I UEI.SmartControl: Device manager: loading config....
,08-29 11:07:01.031  7511  7569 D UEI.SmartControl: ----------- loading internal config...
,08-29 11:07:01.043  7511  7511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 11:07:01.045  7511  7511 E UEI.SmartControl: Services init done
08-29 11:07:01.046  7511  7511 D UEI.SmartControl: QS Service init finished
08-29 11:07:01.048  7511  7511 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 11:07:01.048  7511  7511 D UEI.SmartControl: QS Service version code: 201091
08-29 11:07:01.049  7511  7511 D UEI.SmartControl: Service requested: Control
08-29 11:07:01.057  7511  7569 E UEI.SmartControl: Loading SETTINGS...
,08-29 11:07:01.059  7511  7511 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 11:07:01.064  1043  1888 I ActivityManager: Killing 6784:com.lge.sync/1000 (adj 15): empty #17
08-29 11:07:01.067  6813  6813 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 11:07:01.068  7511  7543 I UEI.SmartControl: ------ IControl API: 11
08-29 11:07:01.070  7511  7543 I UEI.SmartControl: Registering callback...
08-29 11:07:01.072  7511  7545 I UEI.SmartControl: ------ IControl API: 19
,08-29 11:07:01.078  7511  7545 I UEI.SmartControl: Registering Services Ready callback...
,08-29 11:07:01.078  7511  7569 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 11:07:01.089  1043  1526 D WifiService: Client connection lost with reason: 4
,08-29 11:07:01.104  7511  7568 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-29 11:07:01.105  6813  6829 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-29 11:07:01.106  6813  6916 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 11:07:01.106  6813  6916 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 11:07:01.106  7511  7568 D UEI.SmartControl: -----service ready thread exits
08-29 11:07:01.106  6813  6813 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 11:07:01.107  6813  6813 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 11:07:01.107  7511  7574 I UEI.SmartControl: ------ IControl API: 8
08-29 11:07:01.108  6813  6813 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 11:07:01.109  6813  6813 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 11:07:01.109  6813  6813 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 11:07:01.109  6813  6813 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 11:07:01.110  6813  6813 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 11:07:01.110  6813  6813 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 11:07:01.117  7511  7511 D UEI.SmartControl: Internal service binding...
08-29 11:07:01.117  1043  1960 W libprocessgroup: failed to open /acct/uid_1000/pid_6784/cgroup.procs: No such file or directory
,08-29 11:07:01.121  6813  6813 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 11:07:01.125  6813  6813 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 11:07:01.126  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 11:07:01.127  6813  6813 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 11:07:01.128  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 11:07:01.129  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 11:07:01.130  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 11:07:01.130  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 11:07:01.131  6813  6813 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472461621130]
,08-29 11:07:01.144  6813  7575 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-29 11:07:01.151  6813  6813 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-29 11:07:01.152  6813  6813 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 11:07:01.153  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-29 11:07:01.153  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-29 11:07:01.154  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-29 11:07:01.154  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3,
,08-29 11:07:01.154  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-29 11:07:01.157  6813  6813 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 11:07:01.592  6899  7378 D bt_hci_bdroid: cleanup
,08-29 11:07:01.607  6899  7446 I bt_lpm  : LPM is already off!!!
08-29 11:07:01.609  6899  7470 I bt_userial_mct: exiting userial_read_thread
08-29 11:07:01.609  6899  7470 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 11:07:01.609  6899  7444 W bt-btif : ag scb idx 1 not allocated
08-29 11:07:01.609  6899  7444 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 11:07:01.609  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:07:01.609  6899  7444 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:07:01.609  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:07:01.609  6899  7444 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:07:01.609  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:07:01.609  6899  7444 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:07:01.609  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 11:07:01.610  6899  7444 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:07:01.610  6899  7444 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 11:07:01.611  6899  7378 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 11:07:01.611  6899  7446 I bt_vendor: hw_epilog_process
08-29 11:07:01.611  6899  7378 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 11:07:01.611  6899  7378 D bt_userial_mct: userial_close
08-29 11:07:01.611  6899  7378 E bt_userial_mct: pthread_join() FAILED result:3
08-29 11:07:01.611  6899  7378 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 11:07:01.617  6899  7378 D bt_hci_bdroid: set_power 0
08-29 11:07:01.617  6899  7378 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 11:07:01.617  6899  7378 I bt_vendor: bluetooth satus is on
08-29 11:07:01.617  6899  7378 I bt_vendor: bt-vendor : resetting BT status
08-29 11:07:01.617  6899  7378 I bt_vendor: Starting hciattach daemon
08-29 11:07:01.617  6899  7378 I bt_vendor: try to set false
08-29 11:07:01.618  6899  7378 I bt_vendor: Starting hciattach daemon
08-29 11:07:01.618  6899  7378 I bt_vendor: try to set false
,08-29 11:07:01.625  6899  7378 I bt_vendor: cleanup
08-29 11:07:01.626  6899  7444 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 11:07:01.627  6899  7378 I GKI_LINUX: GKI_exit_task 0 done
08-29 11:07:01.627  6899  7378 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 11:07:01.628  6899  7374 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 11:07:01.636  6899  6899 D HeadsetService: Received stop request...Stopping profile...
,08-29 11:07:01.641  6899  6899 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 11:07:01.642  6899  6899 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:07:01.642  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:07:01.643  6899  7374 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 11:07:01.644  1043  1043 D BluetoothHeadset: Proxy object disconnected
08-29 11:07:01.644  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 11:07:01.645  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-29 11:07:01.645  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-29 11:07:01.645  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-29 11:07:01.645  6899  7415 D HeadsetStateMachine: Exit Disconnected: -1
08-29 11:07:01.647  6899  6899 D A2dpService: Received stop request...Stopping profile...
08-29 11:07:01.647  6899  7436 D A2dpStateMachine: Exit Disconnected: -1
08-29 11:07:01.648  6899  6899 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-29 11:07:01.652  6899  6899 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 11:07:01.652  6899  6899 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:07:01.652  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:07:01.655  1043  1043 D BluetoothA2dp: Proxy object disconnected
08-29 11:07:01.655  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 11:07:01.655  6899  6899 D HidService: Received stop request...Stopping profile...
08-29 11:07:01.655  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:07:01.658  6899  6899 D HealthService: Received stop request...Stopping profile...
08-29 11:07:01.658  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:07:01.660  6899  6899 D PanService: Received stop request...Stopping profile...
,08-29 11:07:01.662  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:07:01.663  6899  6899 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:07:01.664  6899  6899 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 11:07:01.664  6899  6899 D BtGatt.GattService: stop()
08-29 11:07:01.664  6899  6899 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 11:07:01.667  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:07:01.668  6899  6899 D BluetoothMapService: Received stop request...Stopping profile...
08-29 11:07:01.668  6899  6899 D BluetoothMapService: stop()
08-29 11:07:01.669  6899  6899 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 11:07:01.669  6899  6899 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 11:07:01.670  6899  6899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cd5434b
08-29 11:07:01.671  6899  6899 D HeadsetStateMachine: Unbinding service...
,08-29 11:07:01.674  6899  6899 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:07:01.674  6899  6899 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:07:01.674  6899  6899 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:07:01.674  6899  6899 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:07:01.674  6899  6899 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 11:07:01.674  6899  6899 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:07:01.674  6899  6899 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 11:07:01.675  6899  6899 I BluetoothA2dpServiceJni: cleanupNative
08-29 11:07:01.675  6899  7437 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 11:07:01.676  6899  6899 I GKI_LINUX: GKI_exit_task 2 done
08-29 11:07:01.676  6899  6899 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 11:07:01.676  6899  6899 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:07:01.676  6899  6899 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 11:07:01.676  6899  6899 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:07:01.678  6899  6899 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:07:01.678  6899  6899 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:07:01.679  6899  6899 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 11:07:01.679  6899  6899 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 11:07:01.683  6899  6899 V BluetoothMapService: Handler(): got msg=4
08-29 11:07:01.683  6899  6899 D BluetoothMapService: MAP Service closeService in
08-29 11:07:01.683  6899  6899 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:07:01.683  6899  6899 V BluetoothMapService: MAP Service closeService out
,08-29 11:07:01.687  6899  7374 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 11:07:01.688  6899  7374 D BluetoothAdapterProperties: Setting state to 10
08-29 11:07:01.688  6899  7374 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 11:07:01.689  6899  6899 D BluetoothMapService: cleanup()
08-29 11:07:01.689  6899  6899 D BluetoothMapService: MAP Service closeService in
08-29 11:07:01.689  6899  6899 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 11:07:01.689  6899  6899 V BluetoothMapService: MAP Service closeService out
08-29 11:07:01.691  1043  1119 D BluetoothManagerService: Message: 60
08-29 11:07:01.692  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 11:07:01.692  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 11:07:01.693  6899  7374 I BluetoothAdapterState: Entering OffState
08-29 11:07:01.693  1835  3993 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:01.694  1835  1850 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:01.695  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:01.695  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:07:01.695  6762  6779 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 11:07:01.698  6762  6779 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:07:01.699  6762  6779 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:01.700  6762  6779 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:07:01.700  6762  6779 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:07:01.701  1835  3994 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:01.702  6762  6779 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:07:01.703  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 11:07:01.703  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 11:07:01.705  1043  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 11:07:01.705  1043  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 11:07:01.705  1043  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3566770c mBinding = false
08-29 11:07:01.706  1043  1119 D BluetoothManagerService: Sending unbind request.
08-29 11:07:01.711  6899  7378 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 11:07:01.713  6899  6899 I GKI_LINUX: GKI_exit_task 1 done
08-29 11:07:01.713  6899  6899 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 11:07:01.714  6899  6899 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 11:07:01.715  6899  6899 I art     : --- WEIRD: removing null entry 248
08-29 11:07:01.715  6899  6899 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 11:07:01.715  6899  6899 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 11:07:01.716  6899  6899 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 11:07:01.718  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 11:07:01.720  6899  6899 I art     : System.exit called, status: 0
08-29 11:07:01.720  6899  6899 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 11:07:01.739   318  2152 V AudioFlinger: 6899 died, releasing its sessions
08-29 11:07:01.739   318  2152 V AudioFlinger:  pid 1835 @ 0
08-29 11:07:01.739   318  2152 V AudioFlinger:  pid 3411 @ 1
08-29 11:07:01.739   318  2152 V AudioFlinger:  pid 3411 @ 2
,08-29 11:07:01.743  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-29 11:07:01.744  1925  2104 D LGBluetoothAPIService: Message: 101
08-29 11:07:01.744  1925  2104 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-29 11:07:01.744  1925  2104 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-29 11:07:01.744  1925  2104 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-29 11:07:01.748  6762  6762 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 11:07:01.797  1043  1997 I ActivityManager: Process com.android.bluetooth (pid 6899) has died
08-29 11:07:01.797  1043  1997 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-29 11:07:01.797  1043  1997 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-29 11:07:01.809  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:01.811  1925  2104 D LGBluetoothAPIService: Message: 2
08-29 11:07:01.811  1925  2104 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,08-29 11:07:01.812  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:07:01.817  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:01.817  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:01.819  6762  6762 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 11:07:01.819  6762  6762 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 11:07:01.821  6762  6762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 11:07:01.826  1586  1586 D BluetoothAdapter: 499244274: getState() :  mService = null. Returning STATE_OFF
08-29 11:07:01.826  1586  1586 D BluetoothAdapter: 499244274: getState() :  mService = null. Returning STATE_OFF
,08-29 11:07:01.881  1043  1558 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7602 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 11:07:01.882  6762  6762 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:07:01.954  7602  7602 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 11:07:01.955  7602  7602 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 11:07:01.955  7602  7602 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 11:07:01.956  7602  7602 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 11:07:01.977  7602  7602 D BluetoothAdapterApp: Loading JNI Library
,08-29 11:07:02.014  7602  7602 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@8030cd3 Instance Count = 1
,08-29 11:07:02.021  7602  7602 D BluetoothAdapterApp: onCreate
08-29 11:07:02.059  7602  7602 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 11:07:02.059  7602  7602 D ProfileConfigQcom: Adding HeadsetService
,08-29 11:07:02.059  7602  7602 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 11:07:02.060  7602  7602 D ProfileConfigQcom: Adding A2dpService
08-29 11:07:02.060  7602  7602 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 11:07:02.060  7602  7602 D ProfileConfigQcom: Adding HidService
08-29 11:07:02.060  7602  7602 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 11:07:02.061  7602  7602 D ProfileConfigQcom: Adding HealthService
08-29 11:07:02.061  7602  7602 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 11:07:02.062  7602  7602 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 11:07:02.062  7602  7602 D ProfileConfigQcom: Adding PanService
08-29 11:07:02.063  7602  7602 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 11:07:02.063  7602  7602 D ProfileConfigQcom: Adding GattService
08-29 11:07:02.063  7602  7602 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 11:07:02.063  7602  7602 D ProfileConfigQcom: Adding BluetoothMapService
,08-29 11:07:02.064  7602  7602 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-29 11:07:02.065  7602  7602 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-29 11:07:02.067  7602  7602 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:02.068  7602  7602 V BluetoothPbapReceiver: ***********state = 10,
08-29 11:07:02.070  7602  7602 V LGMDMManagerInternal: Create singleton instance
,08-29 11:07:02.175  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-29 11:07:02.184  7602  7602 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 11:07:02.184  7602  7602 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 11:07:02.185  6762  6762 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 11:07:02.191  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-29 11:07:02.191  1925  2104 D LGBluetoothAPIService: Message: 100
08-29 11:07:02.191  1925  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 11:07:02.197  6762  6762 D BluetoothPermissionRequest: onReceive
08-29 11:07:02.199  6762  6762 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 11:07:02.199  6762  6762 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 11:07:02.202  6762  6762 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:07:02.209  7602  7602 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-29 11:07:02.216  7602  7602 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:02.219  7602  7602 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:07:02.219  7602  7602 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:07:02.220  7602  7602 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:07:02.221  7602  7602 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:02.221  7602  7602 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 11:07:02.224  6833  6833 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 11:07:03.641  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:07:03.641  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:07:03.825  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-29 11:07:03.841  1043  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 11:07:03.920  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-29 11:07:03.930  1043  1115 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7642 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-29 11:07:03.935  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-29 11:07:03.938  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-29 11:07:03.940  1043  1043 D administrator: Handling package changes for user 0
08-29 11:07:03.968  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 11:07:03.996  7642  7642 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 11:07:04.045  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-29 11:07:04.045  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-29 11:07:04.088  7642  7642 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:07:04.089  7642  7642 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:07:04.128  1043  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:07:04.137  1043  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 11:07:04.146  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 11:07:04.148  2474  2474 V GmsNetworkLocationProvi: DISABLE
,08-29 11:07:04.177  1043  1114 D LocationProviderProxy: applying state to connected service
,08-29 11:07:04.180  2474  2474 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-29 11:07:04.219  7642  7674 I Babel   : MmsConfig: mnc/mcc: 0/0
08-29 11:07:04.219  7642  7674 I Babel   : MmsConfig.loadMmsSettings
,08-29 11:07:04.223  7642  7674 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 11:07:04.223  7642  7674 I Babel   : MmsConfig.loadFromDatabase
,08-29 11:07:04.250  7642  7674 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-29 11:07:04.250  7642  7674 I Babel   : MmsConfig.loadFromResources
08-29 11:07:04.252  7642  7674 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-29 11:07:04.253  7642  7674 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 11:07:04.253  7642  7642 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:04.275  7642  7672 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 11:07:04.277  7642  7672 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 11:07:04.280  7642  7672 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-29 11:07:04.290  1800  7677 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-29 11:07:04.290  1800  7677 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-29 11:07:04.298  7642  7672 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-29 11:07:04.299  6955  6955 I AppUp4:CustModeStarterReceiver: onReceive
08-29 11:07:04.300  7642  7672 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 11:07:04.303  1800  4643 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-29 11:07:04.303  6955  6955 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4c64ac5
08-29 11:07:04.303  6955  6955 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 11:07:04.303  6955  6955 D AppUp4:CustFacade: isPhone : true
08-29 11:07:04.304  6955  6955 D AppUp4:CustModeStarterReceiver: begin check event
08-29 11:07:04.305  6955  6955 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-29 11:07:04.306  7642  7672 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 11:07:04.328  7642  7672 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 11:07:04.333  7642  7672 W VideoCapabilities: Unsupported mime video/divx
08-29 11:07:04.336  7642  7672 W VideoCapabilities: Unsupported mime video/divx311
08-29 11:07:04.346  7642  7672 W VideoCapabilities: Unsupported mime video/divx4
,08-29 11:07:04.358  1043  1870 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7681 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-29 11:07:04.359  7642  7672 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-29 11:07:04.363  1043  1906 I ActivityManager: Killing 6986:com.lge.email/u0a23 (adj 15): empty #17
,08-29 11:07:04.387  7642  7672 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 11:07:04.391  7642  7672 W AudioCapabilities: Unsupported mime audio/eac3
,08-29 11:07:04.392  7642  7672 W AudioCapabilities: Unsupported mime audio/ac3
08-29 11:07:04.393  7642  7672 W AudioCapabilities: Unsupported mime audio/g726
08-29 11:07:04.394  7642  7672 W AudioCapabilities: Unsupported mime audio/wma-voice
08-29 11:07:04.395  7642  7672 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-29 11:07:04.396  7642  7672 W AudioCapabilities: Unsupported mime audio/adpcm
08-29 11:07:04.399  7642  7672 W VideoCapabilities: Unsupported mime video/theora
08-29 11:07:04.401  7642  7672 W VideoCapabilities: Unsupported mime video/mjpg
,08-29 11:07:04.428  1043  1997 W libprocessgroup: failed to open /acct/uid_10023/pid_6986/cgroup.procs: No such file or directory
,08-29 11:07:04.455  7681  7681 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:07:04.456  7681  7681 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 11:07:04.456  7681  7681 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-29 11:07:04.458  7681  7681 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 11:07:04.458  7681  7681 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 11:07:04.519  7681  7681 I SystemConfig: BUILD Country: EU
08-29 11:07:04.519  7681  7681 I SystemConfig: BUILD Operator: OPEN
,08-29 11:07:04.554  1043  1729 I ActivityManager: Killing 6853:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-29 11:07:04.726  1043  1997 W libprocessgroup: failed to open /acct/uid_10026/pid_6853/cgroup.procs: No such file or directory
,08-29 11:07:04.739  7681  7699 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-29 11:07:04.739  7681  7699 I SystemConfig: existFile = false
08-29 11:07:04.739  7681  7699 I SystemConfig: canReadFile = false
08-29 11:07:04.739  7681  7699 I SystemConfig: systemFeature RCS result false
08-29 11:07:04.740  7681  7699 D SystemConfig: refreshRcsSupport() :false
08-29 11:07:04.781  1043  1729 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7704 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-29 11:07:04.879  7704  7704 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:07:04.880  7704  7704 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 11:07:04.880  7704  7704 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-29 11:07:04.881  7704  7704 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 11:07:04.987  7704  7704 I AppConfig: Total System Memory = 2995761152
,08-29 11:07:04.999  7704  7704 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-29 11:07:05.055  1043  1960 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7726 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 11:07:05.058  1043  1960 I ActivityManager: Killing 6378:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-29 11:07:05.128  1043  1888 W libprocessgroup: failed to open /acct/uid_1000/pid_6378/cgroup.procs: No such file or directory
,08-29 11:07:05.317  7726  7726 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-29 11:07:05.420  7726  7726 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:07:05.420  7726  7726 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 11:07:05.482  7726  7726 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-29 11:07:05.503  7726  7726 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 11:07:05.505  7726  7726 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 11:07:05.521  7726  7726 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 11:07:05.521  7726  7726 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-29 11:07:05.543  1043  1996 I ActivityManager: Killing 7025:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-29 11:07:05.661  1043  1558 W libprocessgroup: failed to open /acct/uid_10046/pid_7025/cgroup.procs: No such file or directory
,08-29 11:07:05.676  4585  7780 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-29 11:07:05.711  1043  1059 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7781 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 11:07:05.740  3464  4455 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-29 11:07:05.744  3464  4455 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@aaa3359 on behalf of 7726
08-29 11:07:05.764  7726  7726 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-29 11:07:05.785  7781  7781 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 11:07:05.789  7726  7726 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-29 11:07:05.814  7781  7781 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-29 11:07:05.814  7781  7781 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-29 11:07:05.815  7781  7781 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-29 11:07:05.815  7781  7781 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-29 11:07:05.815  7781  7781 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-29 11:07:05.815  7781  7781 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-29 11:07:05.839  1043  1060 I ActivityManager: Killing 7045:com.android.chrome/u0a57 (adj 15): empty #17
,08-29 11:07:05.891  1043  1997 W libprocessgroup: failed to open /acct/uid_10057/pid_7045/cgroup.procs: No such file or directory
,08-29 11:07:06.031  7511  7570 D UEI.SmartControl: Internal timer expired: 1
,08-29 11:07:06.034  7511  7570 D UEI.SmartControl: unbind internal service
,08-29 11:07:06.167  1043  1729 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:07:06.192  4585  7780 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 516 ms] updated apps [took 516 ms] 
,08-29 11:07:06.258  7511  7567 D serial_port: close(fd = 25)
,08-29 11:07:06.262  7511  7567 I UEI.SmartControl: Serial port is closed.
,08-29 11:07:06.657  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:07:06.657  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e31090f added. We now have 6 listener(s)
,08-29 11:07:06.657  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:06.669  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:06.669  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c3d9d9c added. We now have 7 listener(s)
08-29 11:07:06.669  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:06.670  6564  6668 I System.out: IsBluetoothEnabled
08-29 11:07:06.671  1043  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:06.671  1043  1997 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 11:07:06.672  1043  1119 D BluetoothManagerService: Message: 2
08-29 11:07:06.675  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:06.675  1043  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:06.675  1043  1942 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-29 11:07:06.691  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:07:06.692  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 11:07:06.692  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,08-29 11:07:06.695  1043  1119 D BluetoothManagerService: Message: 1
08-29 11:07:06.695  1043  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-29 11:07:06.723  1043  1119 D BluetoothManagerService: Message: 20
08-29 11:07:06.723  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1010e2db:true
,08-29 11:07:06.727  7602  7602 D BluetoothAdapterState: make
08-29 11:07:06.732  7602  7602 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 11:07:06.732  7602  7602 I bluedroid-qcom: init
08-29 11:07:06.733  7602  7824 I BluetoothAdapterState: Entering OffState
08-29 11:07:06.733  7602  7602 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 11:07:06.734  7602  7602 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 11:07:06.734  7602  7602 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:07:06.734  7602  7602 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 11:07:06.734  7602  7602 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 11:07:06.735  7602  7602 I bluedroid-qcom: get_profile_interface socket
08-29 11:07:06.736  7602  7602 I bluedroid-qcom: get_profile_interface map_client
,08-29 11:07:06.739  7602  7828 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 11:07:06.733  7827  7827 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:06.745  7602  7828 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 11:07:06.733  7827  7827 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:06.756  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 11:07:06.756  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-29 11:07:06.759  1043  1119 D BluetoothManagerService: Message: 40
08-29 11:07:06.759  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 11:07:06.761  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 11:07:06.761  7602  7617 I bluedroid-qcom: config_hci_snoop_log
08-29 11:07:06.762  7827  7827 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 11:07:06.762  7827  7827 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 11:07:06.762  7827  7827 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 11:07:06.764  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 11:07:06.764  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 11:07:06.764  7827  7827 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 11:07:06.770  7827  7827 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 11:07:06.770  7827  7827 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-29 11:07:06.777  7602  7824 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 11:07:06.778  7602  7828 D BluetoothAdapterProperties: Name is: G3
08-29 11:07:06.778  7602  7824 D BluetoothAdapterProperties: Setting state to 11
08-29 11:07:06.778  7602  7824 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 11:07:06.779  1043  1119 D BluetoothManagerService: Message: 60
08-29 11:07:06.779  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 11:07:06.779  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 11:07:06.781  7602  7824 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 11:07:06.786  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:07:06.789  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:07:06.792  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:06.796  6762  6762 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 11:07:06.802  7602  7602 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:07:06.802  7602  7602 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:06.802  7602  7602 V BluetoothPbapReceiver: ***********state = 11
,08-29 11:07:06.825  7602  7824 D BluetoothBondStateMachine: make
08-29 11:07:06.825  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:07:06.831  7602  7824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:06.832  7602  7824 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 11:07:06.832  7602  7824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:06.832  7602  7824 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 11:07:06.833  7602  7824 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 11:07:06.835  7602  7841 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 11:07:06.840  7602  7824 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 11:07:06.843  6762  6762 D BluetoothPermissionRequest: onReceive
08-29 11:07:06.848  7602  7602 D HeadsetService: Received start request. Starting profile...
08-29 11:07:06.849  6762  6762 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:07:06.849  7602  7602 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:07:06.849  7602  7602 D LGBluetoothHfpAdapter: Version 1.6
08-29 11:07:06.849  7602  7824 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:07:06.852  7602  7602 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 11:07:06.854  7602  7602 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:07:06.854  7602  7602 D HeadsetStateMachine: make
08-29 11:07:06.869  7602  7824 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:07:06.875  7602  7824 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 11:07:06.882  7602  7824 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:07:06.888  7602  7824 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 11:07:06.896  7602  7824 E BluetoothAdapterService: File transfer profiles supported!!
08-29 11:07:06.896  7602  7602 D LgDataFeature: LgDataFeature() Constructor: none
08-29 11:07:06.897  7602  7602 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:07:06.902  7602  7602 D HeadsetStateMachine: max_hf_connections = 1
08-29 11:07:06.902  7602  7602 I bluedroid-qcom: get_profile_interface handsfree
,08-29 11:07:06.907  7602  7602 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 11:07:06.907   318   318 V AudioPolicyService: registerClient() client 0xb04104c0, uid 1002
08-29 11:07:06.907   318  2152 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 11:07:06.907   318  2152 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:07:06.907   318  2152 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:07:06.908  7602  7602 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 11:07:06.908   318  1368 V AudioFlinger: registerClient() client 0xb5581610, pid 7602
08-29 11:07:06.909   318  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:07:06.909   318  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-29 11:07:06.909  7602  7602 V ToneGenerator: Create Track: 0xb4928a80
08-29 11:07:06.909  7602  7602 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 11:07:06.909  7602  7602 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 11:07:06.909   318  2152 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 11:07:06.909   318  2152 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 11:07:06.909   318  2152 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:07:06.909   318  2152 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:07:06.909  7602  7602 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 11:07:06.909   318  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:07:06.909   318  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:07:06.909  7602  7617 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:07:06.909  7602  7617 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 11:07:06.910  7602  7617 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:07:06.910  7602  7617 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 11:07:06.910  1835  3995 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:07:06.910  1835  3995 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:07:06.910   318   318 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 11:07:06.910  3411  3426 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:07:06.910  3411  3426 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:07:06.910  1835  3995 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:07:06.910  1835  3995 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:07:06.911  1043  1059 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:07:06.911  1043  1059 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:07:06.911  1043  1059 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:07:06.911  1043  1059 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:07:06.911  1586  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 11:07:06.911  1586  1605 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 11:07:06.911   318  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 11:07:06.911   318  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 11:07:06.911  1586  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:07:06.911   318  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 11:07:06.911  1586  1605 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:07:06.911   318  1368 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 11:07:06.911  3411  3426 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 11:07:06.911  7602  7602 V AudioSystem: getLatency() output 2, latency 50
08-29 11:07:06.912  3411  3426 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 11:07:06.912  7602  7602 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 11:07:06.912  7602  7602 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 11:07:06.912   318  2152 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 11:07:06.912   318  2152 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 11:07:06.912   318  2152 V AudioFlinger: [MABL_A,udioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 11:07:06.912   318  2152 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 11:07:06.912   318  2152 V AudioFlinger: createTrack() lSessionId: 23
08-29 11:07:06.913  7602  7602 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 11:07:06.913   318  1369 V AudioFlinger: acquiring 23 from 7602, for 7602
08-29 11:07:06.913   318  1369 V AudioFlinger:  added new entry for 23
08-29 11:07:06.913  7602  7602 V ToneGenerator: ToneGenerator INIT OK, time: 137187
08-29 11:07:06.913  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:06.914  7602  7846 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 11:07:06.914  7602  7846 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 11:07:06.914  7602  7846 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 11:07:06.914  7602  7846 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 11:07:06.915   318   318 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7602
08-29 11:07:06.915   318   318 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 11:07:06.915   318   318 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 11:07:06.915   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 11:07:06.915   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 11:07:06.915   318   318 V voice   : voice_set_parameters: exit with code(0)
08-29 11:07:06.915   318   318 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 11:07:06.915   318   318 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 11:07:06.915   318   318 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 11:07:06.915   318   318 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 11:07:06.915   318   318 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 11:07:06.915   318   318 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 11:07:06.916  7602  7846 V ToneGenerator: ToneGenerator destructor
08-29 11:07:06.916  7602  7846 V ToneGenerator: stopTone
08-29 11:07:06.916  7602  7846 V ToneGenerator: Delete Track: 0xb4928a80
08-29 11:07:06.916  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:06.916  7602  7846 V AudioTrack: ~AudioTrack, releasing session id from 7602 on behalf of 7602
08-29 11:07:06.916   318  2152 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 11:07:06.916   318  2152 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 11:07:06.916   318  1368 V AudioFlinger: releasing 23 from 7602 for 7602
08-29 11:07:06.916   318  1368 V AudioFlinger:  decremented refcount to 0
08-29 11:07:06.916   318  2152 V AudioFlinger: PlaybackThread::Track destructor
08-29 11:07:06.916   318  1273 V AudioPolicyService: AudioCommandThread() waking up
08-29 11:07:06.916   318  1368 V AudioFlinger: purging stale effects
,08-29 11:07:06.916   318  2152 V AudioFlinger: removeClient_l() pid 7602, calling pid 318
08-29 11:07:06.916   318  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 11:07:06.916   318  1273 V AudioPolicyManager: releaseOutput() 2
08-29 11:07:06.916   318  1273 V AudioPolicyService: AudioCommandThread() going to sleep
,08-29 11:07:06.921  7602  7602 D A2dpService: Received start request. Starting profile...
08-29 11:07:06.922  7602  7602 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 11:07:06.923  7602  7824 V LGMDMManager: Create singleton instance
08-29 11:07:06.924  7602  7602 V Avrcp   : make
08-29 11:07:06.925  7602  7602 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 11:07:06.925  7602  7602 I bluedroid-qcom: get_profile_interface avrcp
08-29 11:07:06.925  7602  7824 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 11:07:06.934  7602  7602 V AudioManager: registerRemoteController: size of Media player list: 0
,08-29 11:07:06.935  7602  7602 E AudioManager: No RCC entry present to update
,08-29 11:07:06.935  7602  7602 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 11:07:06.939  7602  7602 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 11:07:06.941  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 11:07:06.941  7602  7602 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 11:07:06.944  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 11:07:07.098  1043  1906 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:07:07.098  1043  1906 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:07:07.234  1043  1060 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 11:07:07.253  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-29 11:07:07.261  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 11:07:07.262  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 11:07:07.262  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 11:07:07.262  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 11:07:07.262  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:07:07.262  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 11:07:07.262  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 11:07:07.262  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 11:07:07.262  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:07:07.263  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 11:07:07.263  7602  7602 I BluetoothA2dpServiceJni: classInitNative
08-29 11:07:07.263  7602  7602 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:07:07.263  7602  7602 D A2dpStateMachine: make
08-29 11:07:07.267  7602  7602 I bluedroid-qcom: get_profile_interface a2dp
08-29 11:07:07.268  7602  7858 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 11:07:07.272  7602  7602 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:07:07.272  7602  7602 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-29 11:07:07.275  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:07.276  7602  7857 D A2dpStateMachine: Enter Disconnected: -2
08-29 11:07:07.278  7602  7602 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 11:07:07.282  7602  7602 D HidService: Received start request. Starting profile...
08-29 11:07:07.282  7602  7602 I bluedroid-qcom: get_profile_interface hidhost
08-29 11:07:07.282  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:07.283  7602  7602 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 11:07:07.285  7602  7602 D HealthService: Received start request. Starting profile...
,08-29 11:07:07.289  7602  7602 I bluedroid-qcom: get_profile_interface health
,08-29 11:07:07.290  7602  7602 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 11:07:07.290  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:07.293  7602  7602 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 11:07:07.296  7602  7602 D PanService: Received start request. Starting profile...
08-29 11:07:07.296  7602  7602 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:07:07.297  7602  7602 I bluedroid-qcom: get_profile_interface pan
08-29 11:07:07.307  7602  7602 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 11:07:07.307  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:07.309  7602  7602 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-29 11:07:07.321  7602  7602 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:07:07.321  7602  7602 D BtGatt.GattService: Received start request. Starting profile...
,08-29 11:07:07.322  7602  7602 D BtGatt.GattService: start()
08-29 11:07:07.322  7602  7602 I bluedroid-qcom: get_profile_interface gatt
08-29 11:07:07.323  7602  7602 D BtGatt.AdvertiseManager: advertise manager created
,08-29 11:07:07.332  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:07.334  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:07.334  7602  7602 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 11:07:07.335  7602  7602 V BluetoothMapService: BluetoothMapBinder()
08-29 11:07:07.336  7602  7602 D BluetoothMapService: Received start request. Starting profile...
08-29 11:07:07.337  7602  7602 D BluetoothMapService: start()
,08-29 11:07:07.341  7602  7602 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-29 11:07:07.341  7602  7602 D BluetoothMapEmailAppObserver: createReceiver()
08-29 11:07:07.343  7602  7602 D BluetoothMapEmailAppObserver: initObservers()
08-29 11:07:07.343  7602  7602 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 11:07:07.352  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:07.353  7602  7602 D HeadsetStateMachine: Proxy object connected
08-29 11:07:07.354  7602  7602 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 11:07:07.355  7602  7602 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-29 11:07:07.357  7602  7846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-29 11:07:07.358  7602  7846 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 11:07:07.358  7602  7846 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 11:07:07.364  7602  7602 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:07:07.367  7602  7602 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:07:07.378  7602  7602 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 11:07:07.383  7602  7602 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 11:07:07.393  7602  7602 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 11:07:07.393  7602  7602 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 11:07:07.399  7602  7602 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 11:07:07.406  7602  7602 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-29 11:07:07.407  7602  7602 V BluetoothMapService: Handler(): got msg=1
,08-29 11:07:07.408  7602  7602 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:07:07.408  7602  7602 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:07:07.408  7602  7602 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:07:07.408  7602  7602 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:07.408  7602  7602 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 11:07:07.409  7602  7824 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 11:07:07.409  7602  7824 I bluedroid-qcom: enable
08-29 11:07:07.409  7602  7824 I bt_hci_bdroid: init
08-29 11:07:07.410  7602  7870 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 11:07:07.410  7602  7870 I bt-btu  : btu_task pending for preload complete event
08-29 11:07:07.411  7602  7824 I bt_vendor: bt-vendor : init
08-29 11:07:07.411  7602  7824 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 11:07:07.411  7602  7824 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 11:07:07.411  7602  7824 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 11:07:07.411  7602  7824 D bt_userial_mct: userial_init
08-29 11:07:07.411  7602  7824 D bt_hci_bdroid: set_power 1
08-29 11:07:07.411  7602  7824 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 11:07:07.411  7602  7824 I bt_vendor: Starting hciattach daemon
08-29 11:07:07.411  7602  7824 I bt_vendor: try to set true
08-29 11:07:07.403  7873  7873 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:07.403  7873  7873 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:07:07.441  7874  7874 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 11:07:07.543  7881  7881 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 11:07:07.560  7882  7882 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:07:07.594  7884  7884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 11:07:07.611  7885  7885 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 11:07:07.625  7886  7886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 11:07:07.648  7887  7887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 11:07:07.673  7889  7889 I libmdmdetect: ESOC framework not supported
,08-29 11:07:07.676  7889  7889 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-29 11:07:07.686  7889  7889 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 11:07:07.686  7889  7889 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 11:07:07.686  7889  7889 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 11:07:07.686  7889  7889 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 11:07:07.686  7889  7889 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 11:07:07.686  7889  7889 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 11:07:07.686  7889  7889 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-29 11:07:07.745  7889  7893 E QC-QMI  : qmi_client [7889] 15: failed to locate client data
,08-29 11:07:07.752   454   454 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-29 11:07:07.753   454   454 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-29 11:07:07.792  7897  7897 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 11:07:07.808  7898  7898 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:07:07.873  7602  7824 I bt_vendor: bluetooth satus is on
,08-29 11:07:07.873  7602  7824 D bt_hci_bdroid: preload
,08-29 11:07:07.882  7602  7872 D bt_userial_mct: userial_open(port:0)
,08-29 11:07:07.882  7602  7872 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 11:07:07.886  7602  7872 I bt_vendor: Done intiailizing UART
,08-29 11:07:07.890  7602  7872 I bt_vendor: Done intiailizing UART
08-29 11:07:07.890  7602  7872 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 11:07:07.891  7602  7872 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 11:07:07.894  7602  7870 I bt-btu  : btu_task received preload complete event
08-29 11:07:07.895  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-29 11:07:07.895  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f,
,08-29 11:07:07.912  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 11:07:07.917  7602  7900 D bt_userial_mct: Entering userial_read_thread()
,08-29 11:07:07.924  7602  7870 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 11:07:07.924  7602  7870 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:07:07.925  7602  7870 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 11:07:07.986  7602  7870 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 11:07:07.986  7602  7870 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa019a061 
08-29 11:07:07.986  7602  7870 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019a061 
,08-29 11:07:08.009  7602  7828 E bt-btif : Calling BTA_HhEnable
08-29 11:07:08.009  7602  7828 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 11:07:08.010  7602  7828 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 11:07:08.014  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-29 11:07:08.014  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-29 11:07:08.015  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 11:07:08.015  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 11:07:08.015  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 11:07:08.017  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 11:07:08.017  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 11:07:08.018  7602  7828 D BluetoothAdapterProperties: Name is: G3
08-29 11:07:08.020  7602  7828 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:07:08.020  7602  7828 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:07:08.020  7602  7828 D bt_hci_bdroid: postload
08-29 11:07:08.020  7602  7872 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:07:08.021  7602  7870 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 11:07:08.022  7602  7828 D bte_conf: Device ID record 1 : primary
08-29 11:07:08.022  7602  7828 D bte_conf:   vendorId            = 00c4
08-29 11:07:08.022  7602  7828 D bte_conf:   vendorIdSource      = 0001
08-29 11:07:08.022  7602  7828 D bte_conf:   product             = 13a1
08-29 11:07:08.022  7602  7828 D bte_conf:   version             = 1000
08-29 11:07:08.022  7602  7828 D bte_conf:   clientExecutableURL = 
08-29 11:07:08.022  7602  7828 D bte_conf:   serviceDescription  = 
08-29 11:07:08.022  7602  7828 D bte_conf:   documentationURL    = 
08-29 11:07:08.022  7602  7828 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 11:07:08.029  7602  7872 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:07:08.033  7602  7872 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:07:08.034  7602  7872 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 11:07:08.034  7602  7824 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 11:07:08.035  7602  7824 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:07:08.035  7602  7824 D BluetoothAdapterProperties: State =  11
08-29 11:07:08.035  7602  7824 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 11:07:08.035  7602  7824 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 11:07:08.035  7602  7824 D BluetoothAdapterProperties: Setting state to 12
08-29 11:07:08.035  7602  7824 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 11:07:08.036  7602  7828 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 11:07:08.037  7602  7828 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:07:08.033  7902  7902 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:07:08.033  7902  7902 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:08.050  1043  1119 D BluetoothManagerService: Message: 60
08-29 11:07:08.051  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 11:07:08.051  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-29 11:07:08.051  7602  7900 E bt_mct  : hci lib postload completed
08-29 11:07:08.057  7602  7824 I BluetoothAdapterState: Entering On State
,08-29 11:07:08.064  1835  3993 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:08.065  7602  7870 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:07:08.065  7602  7870 W bt-smp  : Plain text(LSB ~ MSB) = be 9c 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:07:08.065  7602  7870 W bt-smp  : Encrypted text(LSB ~ MSB) = d0 f5 72 b0 74 5c e2 20 2b ff fd 0a 85 5f dc fd 
08-29 11:07:08.066  7602  7870 W bt-btm  : Stopping oneshot timer
08-29 11:07:08.084  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:08.084  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:08.084  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:08.084  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:08.084  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:08.084  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:08.084  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:08.084  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:08.088  7602  7870 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:07:08.088  7602  7870 W bt-smp  : Plain text(LSB ~ MSB) = 85 e7 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:07:08.088  7602  7870 W bt-smp  : Encrypted text(LSB ~ MSB) = 2c 17 7e b0 79 69 a1 fc 21 67 cd 2b 75 65 f2 75 
08-29 11:07:08.088  7602  7870 W bt-btm  : Stopping oneshot timer
08-29 11:07:08.091  7602  7828 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:07:08.091  7602  7828 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 11:07:08.100  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:07:08.105  7602  7870 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:07:08.105  7602  7870 W bt-smp  : Plain text(LSB ~ MSB) = ff 98 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:07:08.105  7602  7870 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 60 94 9c 03 13 2c de 29 19 98 84 2b 9e 48 47 
08-29 11:07:08.106  7602  7870 W bt-btm  : Stopping oneshot timer
08-29 11:07:08.115  7602  7824 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 11:07:08.115  7602  7824 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 11:07:08.115  7602  7824 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-29 11:07:08.119  7602  7824 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 11:07:08.119  7602  7824 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 11:07:08.122  7602  7870 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:07:08.122  7602  7870 W bt-smp  : Plain text(LSB ~ MSB) = 05 76 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:07:08.122  7602  7870 W bt-smp  : Encrypted text(LSB ~ MSB) = 25 97 d1 90 0a 05 f9 58 05 f8 52 45 f3 c5 88 a3 
08-29 11:07:08.123  7602  7870 W bt-btm  : Stopping oneshot timer
08-29 11:07:08.126  1835  1835 D BluetoothHeadset: Proxy object connected
08-29 11:07:08.128  1835  2421 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 11:07:08.142  1835  1835 D BluetoothHeadset: Proxy object connected
,08-29 11:07:08.144  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:08.150  7602  7870 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 11:07:08.150  7602  7870 W bt-smp  : Plain text(LSB ~ MSB) = b7 5e 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 11:07:08.150  7602  7870 W bt-smp  : Encrypted text(LSB ~ MSB) = 93 63 4c e4 48 c6 d1 49 f8 5d aa d1 9d 98 29 80 
08-29 11:07:08.150  7602  7870 W bt-btm  : Stopping oneshot timer
08-29 11:07:08.151  1043  1043 D BluetoothHeadset: Proxy object connected
08-29 11:07:08.169  7907  7907 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-29 11:07:08.175  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:07:08.187  6762  6780 D BluetoothA2dp: onBluetoothStateChange: up=true,
,08-29 11:07:08.193  1043  1043 D BluetoothA2dp: Proxy object connected
08-29 11:07:08.195  6762  6780 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:07:08.197  6762  6762 D BluetoothA2dp: Proxy object connected
08-29 11:07:08.197  6762  6762 D A2dpProfile: Bluetooth service connected
08-29 11:07:08.199  6762  6779 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 11:07:08.203  6762  6762 D BluetoothInputDevice: Proxy object connected
08-29 11:07:08.203  6762  6762 D HidProfile: Bluetooth service connected
08-29 11:07:08.206  6762  6874 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:07:08.206  6762  6874 D BluetoothPan: onBluetoothStateChange call bindService
08-29 11:07:08.207  6762  6762 D BluetoothHeadset: Proxy object connected
08-29 11:07:08.207  6762  6762 D HeadsetProfile: Bluetooth service connected
08-29 11:07:08.210  6762  6779 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:07:08.212  6762  6762 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 11:07:08.212  6762  6762 D PanProfile: Bluetooth service connected
08-29 11:07:08.212  1835  3995 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:08.214  1835  1835 D BluetoothHeadset: Proxy object connected
08-29 11:07:08.215  6762  6874 D BluetoothMap: onBluetoothStateChange: up=true
08-29 11:07:08.218  1043  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 11:07:08.218  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 11:07:08.220  6762  6762 D BluetoothMap: Proxy object connected
08-29 11:07:08.220  6762  6762 D MapProfile: Bluetooth service connected
08-29 11:07:08.220  6762  6762 D BluetoothMap: getConnectedDevices()
08-29 11:07:08.222  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:08.222  1925  2104 D LGBluetoothAPIService: Message: 1
08-29 11:07:08.222  1925  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 11:07:08.222  1925  2104 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-29 11:07:08.222  1925  2104 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 11:07:08.223  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:08.227  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 11:07:08.229  7602  7617 V BluetoothMapService: getConnectedDevices()
08-29 11:07:08.229  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 11:07:08.231  1043  1119 D BluetoothManagerService: Message: 40
08-29 11:07:08.231  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 11:07:08.236  7602  7602 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:08.236  7602  7602 D BluetoothMapService: STATE_ON
08-29 11:07:08.243  6762  6762 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 11:07:08.247  6762  6762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 11:07:08.254  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:08.255  7602  7602 V BluetoothPbapService: Pbap Service onCreate
08-29 11:07:08.255  7602  7602 V BluetoothPbapService: Starting PBAP service
08-29 11:07:08.257  6762  6762 D DockEventReceiver: finishStartingService: stopping service
08-29 11:07:08.260  7602  7602 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 11:07:08.261  7602  7602 V BluetoothPbapService: Pbap Service onBind
08-29 11:07:08.262  7602  7602 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:08.262  7602  7602 V BluetoothPbapService: state: 12
08-29 11:07:08.262  7602  7602 V BluetoothMapService: Handler(): got msg=1
,08-29 11:07:08.263  7602  7602 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 11:07:08.264  7602  7602 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 11:07:08.264  7602  7602 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:08.264  7602  7602 V BluetoothPbapReceiver: ***********state = 12
08-29 11:07:08.265  7602  7926 D BluetoothMapMasInstance: MAS initSocket()
08-29 11:07:08.265  7602  7926 D BluetoothMapMasInstance:   masId = 00
08-29 11:07:08.265  7602  7926 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 11:07:08.265  7602  7926 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 11:07:08.265  7602  7926 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 11:07:08.266  6762  6762 D BluetoothPbap: Proxy object connected
08-29 11:07:08.266  6762  6762 D PbapServerProfile: Bluetooth service connected
08-29 11:07:08.266  7602  7602 V BluetoothPbapService: Handler(): got msg=1
08-29 11:07:08.268  7602  7602 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 11:07:08.270  1043  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:08.270  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:07:08.270  7602  7928 V BluetoothPbapService: Pbap Service initSocket
08-29 11:07:08.271  2176  2176 D c       : Getting all permits...
08-29 11:07:08.271  2176  2176 D a       : Opening database...
08-29 11:07:08.271  1043  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:08.271  7602  7926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:07:08.272  7602  7928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:07:08.274  7602  7928 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 11:07:08.275  7602  7928 V BluetoothPbapService: Succeed to create listening socket 
08-29 11:07:08.275  7602  7928 V BluetoothPbapService: Accepting socket connection...
08-29 11:07:08.275  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:08.275  2176  2176 D a       : Opening database auth.proximity.permit_store...
,08-29 11:07:08.276  7602  7828 D BluetoothAdapterProperties: Scan Mode:21
08-29 11:07:08.276  7602  7828 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 11:07:08.278  7602  7926 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 11:07:08.278  7602  7926 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 11:07:08.278  7602  7926 D BluetoothMapMasInstance: Accepting socket connection...
08-29 11:07:08.279  2176  2176 D a       : Closing database...
08-29 11:07:08.290  6762  6762 D BluetoothPermissionRequest: onReceive
,08-29 11:07:08.292  6762  6762 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 11:07:08.294  6762  6762 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 11:07:08.298  7602  7602 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 11:07:08.299  7602  7602 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 11:07:08.407  1043  1059 I art     : Explicit concurrent mark sweep GC freed 26164(1281KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.669ms total 105.073ms
,08-29 11:07:08.416  7602  7602 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-29 11:07:08.449  7602  7602 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 11:07:08.449  7602  7602 V BtOppService: onCreate
,08-29 11:07:08.453  7602  7602 V BluetoothOppNotification: send message
08-29 11:07:08.456  7602  7602 V BtOppService: Starting RfcommListener
08-29 11:07:08.459  7602  7602 D BluetoothOppPreference: Dumping Names:  
08-29 11:07:08.459  7602  7602 D BluetoothOppPreference: {}
08-29 11:07:08.459  7602  7602 D BluetoothOppPreference: Dumping Channels:  
08-29 11:07:08.459  7602  7602 D BluetoothOppPreference: {}
08-29 11:07:08.460  7602  7602 V BtOppService: onStartCommand
08-29 11:07:08.461  7602  7936 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-29 11:07:08.463  7602  7602 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:08.463  7602  7602 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 11:07:08.465  7602  7602 V BluetoothOppNotification: new notify threadi!
08-29 11:07:08.466  7602  7602 V BluetoothOppNotification: send delay message
08-29 11:07:08.466  7602  7602 V BtOppService: start RfcommListener
08-29 11:07:08.469  7602  7602 V BtOppService: RfcommListener started
08-29 11:07:08.470  7602  7938 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 11:07:08.470  1043  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:08.471  7602  7938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:07:08.474  7602  7938 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-29 11:07:08.476  7602  7938 V BtOppRfcommListener: Started RFCOMM listener....
,08-29 11:07:08.476  7602  7938 I BtOppRfcommListener: Accept thread started.
08-29 11:07:08.476  7602  7938 V BtOppRfcommListener: Accepting connection...
08-29 11:07:08.477  7602  7936 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:07:08.477  7602  7933 V BtOppService: Deleted complete outbound shares, number =  0
08-29 11:07:08.477  7602  7937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 11:07:08.479  7602  7936 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3198e64 on behalf of 
08-29 11:07:08.481  7602  7936 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 11:07:08.481  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:08.481  7602  7937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@209c48cd on behalf of 
08-29 11:07:08.481  7602  7933 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 11:07:08.481  7602  7602 V BluetoothFtpService: Ftp Service onCreate
08-29 11:07:08.481  7602  7602 I BluetoothFtpService: Ftp Service onCreate
08-29 11:07:08.481  7602  7933 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 11:07:08.481  7602  7602 V BluetoothFtpService: Ftp Service onStartCommand
08-29 11:07:08.481  7602  7602 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:08.481  7602  7937 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 11:07:08.481  7602  7602 V BluetoothFtpService: Starting Listening on sockets
08-29 11:07:08.482  7602  7602 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 11:07:08.482  7602  7602 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 11:07:08.482  7602  7602 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 11:07:08.482  7602  7602 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:08.482  7602  7602 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 11:07:08.482  7602  7602 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 11:07:08.482  7602  7933 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@237b4493 on behalf of 
08-29 11:07:08.483  7602  7937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 11:07:08.485  7602  7602 V BtOppService: ContentObserver received notification
08-29 11:07:08.485  7602  7602 V BtOppService: ContentObserver received notification
08-29 11:07:08.485  7602  7602 V BluetoothFtpService: Handler(): got msg=1
,08-29 11:07:08.487  7602  7602 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 11:07:08.487  7602  7602 V BluetoothFtpService: Ftp Service initSocket
08-29 11:07:08.488  7602  7939 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 11:07:08.488  7602  7939 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 11:07:08.490  1043  1639 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:08.491  7602  7939 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7132cd0 on behalf of 
08-29 11:07:08.491  7602  7602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:07:08.491  7602  7939 V BluetoothOppNotification: update too frequent, put in queue
08-29 11:07:08.492  7602  7937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13b1a4c9 on behalf of 
08-29 11:07:08.492  7602  7602 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-29 11:07:08.492  7602  7937 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 11:07:08.492  7602  7939 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 11:07:08.493  7602  7602 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 11:07:08.493  7602  7937 V BluetoothOppNotification: outbound notification was removed.
08-29 11:07:08.494  7602  7940 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 11:07:08.494  7602  7937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 11:07:08.495  7602  7937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f4e97ce on behalf of 
08-29 11:07:08.496  7602  7937 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 11:07:08.497  7602  7937 V BluetoothOppNotification: inbound notification was removed.
08-29 11:07:08.497  7602  7937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 11:07:08.498  7602  7937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e0b96ef on behalf of 
08-29 11:07:08.521  7602  7602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2850b128
08-29 11:07:08.521  7602  7602 V BluetoothSapService: Sap Service onCreate
,08-29 11:07:08.523  7602  7602 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:08.523  7602  7602 V BluetoothSapService: state: 12
08-29 11:07:08.523  7602  7602 V BluetoothSapService: Starting SAP server process
,08-29 11:07:08.524  7602  7602 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 11:07:08.513  7941  7941 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:08.513  7941  7941 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:08.526  7602  7942 V BluetoothSapService: Sap Service initRfcommSocket
08-29 11:07:08.528  1043  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:07:08.529  7602  7942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:07:08.530  7602  7942 V BluetoothSapService: Succeed to create listening socket 
08-29 11:07:08.530  7602  7942 V BluetoothSapService: Accepting socket connection...
08-29 11:07:08.541  7941  7941 V BT_SAP  : Event pipe created
08-29 11:07:08.541  7941  7941 V BT_SAP  : create_server_socket qcom.sap.server
08-29 11:07:08.541  7941  7941 V BT_SAP  : created socket fd 6
,08-29 11:07:08.729  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:08.729  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:08.729  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:08.729  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:08.729  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:08.729  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:08.729  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:08.729  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:08.742  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:07:08.746  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:08.746  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ee9d3a5 added. We now have 8 listener(s)
08-29 11:07:08.746  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:08.752  1043  1996 D WifiServiceImplEx: setWifiEnabled: false pid=6564, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 11:07:08.752  1043  1996 D WifiService: setWifiEnabled: false pid=6564, uid=10118
08-29 11:07:08.752  1043  1996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:07:08.759  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:08.761  1043  1059 D WifiServiceImplEx: setWifiEnabled: true pid=6564, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 11:07:08.762  1043  1059 D WifiService: setWifiEnabled: true pid=6564, uid=10118
08-29 11:07:08.762  1043  1059 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:07:08.778  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 11:07:08.778  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 11:07:08.778  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,08-29 11:07:08.779  1043  1520 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 11:07:08.779  1043  1520 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 11:07:08.783  1043  1520 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 11:07:08.783  1043  1520 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 11:07:08.783  1043  1520 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 11:07:08.783  1043  1520 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 11:07:08.784  1043  1520 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 11:07:08.784  1043  1520 E WifiHW  : unknown target_country: EU , set to default
08-29 11:07:08.784  1043  1520 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 11:07:08.784  1043  1520 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 11:07:08.784  1043  1520 I WifiUtil: gEnableBmps=1
08-29 11:07:09.468  7602  7602 V BluetoothOppNotification: new notify threadi!
08-29 11:07:09.468  7602  7602 V BluetoothOppNotification: send delay message
,08-29 11:07:09.476  7602  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 11:07:09.492  7602  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10a4b30b on behalf of 
08-29 11:07:09.494  7602  7961 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 11:07:09.495  7602  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-29 11:07:09.499  7602  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a2fc5e8 on behalf of 
,08-29 11:07:09.531   314   900 D SoftapController: Softap fwReload - Ok
,08-29 11:07:09.546  1043  1520 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (757ms)
,08-29 11:07:09.550  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:07:09.550  1043  1119 D Tethering: InitialState.processMessage what=4
08-29 11:07:09.550  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 11:07:09.572   314   900 D CommandListener: Setting iface cfg
08-29 11:07:09.573   314   900 D CommandListener: Trying to bring down wlan0
,08-29 11:07:09.575   314   900 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:07:09.586  1043  1520 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-29 11:07:09.583  7963  7963 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:09.597  1043  1520 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:07:09.597  1043  1520 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:07:09.597  1043  1520 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:07:09.603  7963  7963 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 11:07:09.616  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 11:07:09.619  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:07:09.622  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-29 11:07:09.641  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:09.644  1043  1520 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 11:07:09.644  1043  1520 D WifiMonitor: connecting to supplicant
,08-29 11:07:09.647  7602  7961 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 11:07:09.650  7602  7961 V BluetoothOppNotification: outbound notification was removed.
08-29 11:07:09.650  7602  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 11:07:09.652  7602  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e142401 on behalf of 
08-29 11:07:09.653  7602  7961 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 11:07:09.653  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:07:09.653  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:07:09.653  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:07:09.654  6762  6762 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:07:09.655  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:07:09.658  6762  6762 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:07:09.658  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:07:09.658  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:07:09.658  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:07:09.659  6762  6762 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:07:09.659  6762  6762 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-29 11:07:09.659  7963  7963 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 11:07:09.663  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:07:09.663  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:07:09.663  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:07:09.664  6762  6762 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:07:09.664  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:07:09.665  6762  6762 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:07:09.665  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 11:07:09.665  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:07:09.665  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:07:09.665  6762  6762 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:07:09.665  6762  6762 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:07:09.666  7602  7961 V BluetoothOppNotification: inbound notification was removed.
08-29 11:07:09.666  7602  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 11:07:09.677  7602  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b51d2a6 on behalf of 
,08-29 11:07:09.693  7963  7963 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 11:07:09.694  7963  7963 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 11:07:09.704  1043  1059 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7982 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-29 11:07:09.725   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 389us total 18.890ms
,08-29 11:07:09.743   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 16.584ms
,08-29 11:07:09.757   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 13.475ms
08-29 11:07:09.772  7963  7963 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 11:07:09.816  1043  1942 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8003 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 11:07:09.820  7982  8001 W FormManager: Network not available. Please check & try again.
,08-29 11:07:09.839  7982  8002 V FormManager: Network unavailable.
08-29 11:07:09.841  7982  8002 V FormManager: Network unavailable.
08-29 11:07:09.842  7963  7963 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-29 11:07:09.846  7963  7963 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-29 11:07:09.846  7963  7963 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 11:07:09.847  1043  1520 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 11:07:09.847  1043  1520 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 11:07:09.847  1043  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 11:07:09.847  1043  8021 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 11:07:09.847  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 11:07:09.847  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 11:07:09.847  1043  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 11:07:09.848  1043  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 11:07:09.848  1043  1520 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 11:07:09.848  1043  1520 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-29 11:07:09.849  1043  1520 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:07:09.849  1043  1520 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:07:09.850  1043  1520 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 11:07:09.850  1043  1520 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 11:07:09.850  1043  1520 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 11:07:09.850  1043  1520 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 11:07:09.850  1043  1520 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 11:07:09.851  1043  1520 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 11:07:09.851  1043  1520 E WifiStateMachine: useWiFiOffloading() : false
08-29 11:07:09.851  1043  1520 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 11:07:09.851  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:09.851  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:09.851  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:09.851  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:09.851  1043  1520 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 11:07:09.851  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 11:07:09.852  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:09.852  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-29 11:07:09.852  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 11:07:09.852  1043  1520 D WifiNative-wlan0: SET update_config 1: returned true
08-29 11:07:09.852  1043  1520 D WifiConfigStore: Loading config and enabling all networks 
08-29 11:07:09.852  1043  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 11:07:09.852  1043  1520 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 11:07:09.853  1043  1520 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 11:07:09.855  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:09.855  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:09.855  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:09.855  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:09.855  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:09.855  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:09.855  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:09.855  6564  6564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:07:09.856  6564  6564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:07:09.857  1043  1520 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 11:07:09.861  1043  1558 I ActivityManager: Killing 7066:com.lge.drmservice/u0a62 (adj 15): empty #17
08-29 11:07:09.862  1043  1520 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 11:07:09.863  1043  1520 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipc,onfig.txt: open failed: ENOENT (No such file or directory)
,08-29 11:07:09.878  8003  8003 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:07:09.898  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:07:09.898  1043  1520 D WifiStateMachine: enableVerboseLogging : level 2
08-29 11:07:09.899  1043  1520 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 11:07:09.899  1043  1870 W libprocessgroup: failed to open /acct/uid_10062/pid_7066/cgroup.procs: No such file or directory
08-29 11:07:09.900  1043  1520 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 11:07:09.900  1043  1520 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 11:07:09.900  1043  1520 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 11:07:09.900  1043  1520 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 11:07:09.900  1043  1520 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 11:07:09.900  1043  1520 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 11:07:09.900  1043  1520 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 11:07:09.900  1043  1520 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 11:07:09.901  1043  1520 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 11:07:09.901  1043  1520 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 11:07:09.901  1043  1520 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 11:07:09.901  1043  1520 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 11:07:09.901  1043  1520 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 11:07:09.902  1043  1520 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:07:09.902  1043  1520 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 11:07:09.902  1043  1520 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 11:07:09.902  1043  1520 D WifiNative-HAL: Setting external_sim to 1
08-29 11:07:09.902  1043  1520 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 11:07:09.903  1043  1520 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 11:07:09.903  1043  1520 I WifiNative-HAL: startHal
08-29 11:07:09.903  1043  1520 D wifi    : setting scan oui 0xaf6b51e0
08-29 11:07:09.903  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-29 11:07:09.903  1043  1520 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:07:09.903  1043  1520 I WifiNative-HAL: startHal
08-29 11:07:09.903  1043  1520 D wifi    : setting scan oui 0xaf6b51e0
08-29 11:07:09.903  1043  1520 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 11:07:09.903  1925  2285 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 11:07:09.903  1925  2285 D WfdsService: Set the WFDS Monitor: true
08-29 11:07:09.903  1925  2285 D WfdsMonitor: WfdsMonitorThread create
08-29 11:07:09.904  1925  2285 D WfdsMonitor: WFDS Monitor is created and started
08-29 11:07:09.904  1925  2285 D WfdsService: WiFi: Supplicant connection re-established
08-29 11:07:09.904  1043  1520 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 11:07:09.904  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 11:07:09.904  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 11:07:09.904  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 11:07:09.904  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 11:07:09.904  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 11:07:09.904  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 11:07:09.904  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 11:07:09.904  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 11:07:09.905  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 11:07:09.905  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 11:07:09.905  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 11:07:09.905  1925  8024 E C,trlSupplicant: Access OK "@android:wpa_wlan0"
08-29 11:07:09.905  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 11:07:09.905  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 11:07:09.905  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 11:07:09.905  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 11:07:09.905  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 11:07:09.905  1925  8024 E CtrlSupplicant: Succeed to open control connection
08-29 11:07:09.905  7963  7963 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 11:07:09.905  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 11:07:09.905  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 11:07:09.905  1925  8024 E CtrlSupplicant: Succeed to open monitor connection
08-29 11:07:09.905  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 11:07:09.906  1043  1520 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 11:07:09.906  1925  8024 D WfdsMonitor: Supplicant connection established
08-29 11:07:09.906  1925  2285 D WfdsService: Connected to the supplicant for wfds
08-29 11:07:09.906  1043  1520 E WifiNative: : [140,169,056 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 11:07:09.906  1043  1520 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 11:07:09.906  1043  1520 D WifiNative-wlan0: RECONNECT: returned true
08-29 11:07:09.906  1043  1520 D WifiNative-wlan0: doString: [STATUS]
08-29 11:07:09.907  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:07:09.907  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 11:07:09.907  1043  1520 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 11:07:09.907  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:07:09.907  1043  1520 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:07:09.907  1043  1519 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.908  1043  1520 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 11:07:09.908  1043  1520 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 11:07:09.908  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 11:07:09.908  1043  1043 D RttService: SCAN_AVAILABLE : 3
08-29 11:07:09.908  1043  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.908  1043  1539 I WifiNative-HAL: startHal
08-29 11:07:09.908  1043  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf6b51e0
08-29 11:07:09.908  1043  1539 D wifi    : failed to get capabilities : -3
08-29 11:07:09.908  1043  1539 E WifiScanningService: could not get scan capabilities
08-29 11:07:09.908  1043  1540 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.908  7642  7642 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:09.909  1043  1520 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 11:07:09.909  1043  1520 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 11:07:09.909   314   900 D CommandListener: Setting iface cfg
08-29 11:07:09.909  1043  1520 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 11:07:09.909   314   900 D CommandListener: Trying to bring up p2p0
08-29 11:07:09.909  1043  1520 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 11:07:09.909  104,3  1519 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 11:07:09.909  1043  1519 D LGWifiP2pService: P2pEnablingState
08-29 11:07:09.909  1043  1520 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 11:07:09.909  1043  1520 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 11:07:09.909  1043  1519 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.909  1043  1519 D LGWifiP2pService: P2p socket connection successful
08-29 11:07:09.909  1043  1519 D LGWifiP2pService: P2pEnabledState
08-29 11:07:09.910  7963  7963 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 11:07:09.910  1043  1520 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 11:07:09.910  1043  1520 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 11:07:09.911  1043  1520 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 11:07:09.911  1043  1520 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 11:07:09.911  7963  7963 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 11:07:09.913  1043  1520 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 11:07:09.913  1043  1520 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 11:07:09.913  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 11:07:09.913  1043  1520 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 11:07:09.913  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 11:07:09.913  1925  1925 D WfdsService: WifiP2pState is changed : true
08-29 11:07:09.914  1925  2285 D WfdsService: Receive the WFDS_ENABLE Method
08-29 11:07:09.914  1925  2285 D WfdsService: Set the WFDS Monitor: true
08-29 11:07:09.914  1925  2285 D WfdsService: Connected to the supplicant for wfds
08-29 11:07:09.914  1925  2285 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 11:07:09.914  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 11:07:09.915  7963  7963 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:07:09.915  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:07:09.915  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:07:09.915  1043  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:07:09.915  1043  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:07:09.916  7963  7963 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 11:07:09.916  1043  1520 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 11:07:09.916  7963  7963 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 11:07:09.916  1043  1520 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:07:09.916  7963  7963 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.917  1925  2285 D WfdsService: selectPreferredScanChannel [36]
08-29 11:07:09.917  1925  2285 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 11:07:09.917  1043  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:07:09.917  1043  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.917  1043  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.917  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:07:09.917  1043  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.917  1043  1520 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:07:09.917  1043  1520 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 11:07:09.917  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 11:07:09.917  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 11:07:09.918  1043  1519 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 11:07:09.918  7963  7963 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:07:09.918  1043  1519 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 11:07:09.919  7963  7963 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.919  1043  1520 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 11:07:09.919  1043  1520 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 11:07:09.919  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 11:07:09.919  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:07:09.919  1043  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:07:09.919  1043  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 11:07:09.919  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 11:07:09.920  1925  1925 D WfdsService: isConnected: false
08-29 11:07:09.920  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:07:09.920  1043  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:07:09.920  1043  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.920  1043  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.920  1043  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.921  1043  1520 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 11:07:09.921  1043  1520 D WifiNative-wlan0: doBoolean: SCAN
08-29 11:07:09.921  1043  1519 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 11:07:09.922  1043  1520 D WifiNative-wlan0: SCAN: returned false
08-29 11:07:09.922  1043  1519 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 11:07:09.922  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=140185  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:07:09.922  1043  1519 D WifiNative-p2p0: SET device_name G3: returned true
08-29 11:07:09.922  1043  1519 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 11:07:09.922  1043  1519 D LGWifiP2pService: before postfix = G3
08-29 11:07:09.922  1043  1519 D WifiServerServiceExt: postfix byte check : 2
08-29 11:07:09.922  1043  1519 D LGWifiP2pService: after postfix = G3
08-29 11:07:09.922  1043  1519 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 11:07:09.922  1043  1519 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 11:07:09.922  1043  1519 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 11:07:09.923  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=140185  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 11:07:09.923  1043  1519 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 11:07:09.923  1043  1519 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 11:07:09.923  1043  1520 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:07:09.923  1043  1519 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 11:07:09.923  1043  1520 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:07:09.923  1043  1519 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 11:07:09.923  1043  1520 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:07:09.924  1043  1520 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:07:09.924  1043  1520 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 11:07:09.924  1043  1519 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 11:07:09.924  1043  1519 D WifiNative-HAL: p2pGetDeviceAddress
08-29 11:07:09.925  1043  1519 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 11:07:09.926  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:09.926  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:09.926  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 11:07:09.926  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:07:09.926  1043  1043 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 11:07:09.926  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:09.926  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:07:09.927  1043  1519 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 11:07:09.927  1043  1519 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 11:07:09.927  1043  1519 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 11:07:09.927  1043  1519 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 11:07:09.928  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 11:07:09.928  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 11:07:09.928  1043  1519 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 11:07:09.928  1043  1519 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 11:07:09.929  1925  1925 D WfdsService: Update P2p Interface State: 3
08-29 11:07:09.929  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:09.929  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:09.929  1043  1519 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 11:07:09.929  1043  1519 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 11:07:09.929  1043  1960 I ActivityManager: Killing 7095:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 11:07:09.939  1043  1519 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 11:07:09.939  1043  1519 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-29 11:07:09.968  1043  1729 W libprocessgroup: failed to open /acct/uid_10085/pid_7095/cgroup.procs: No such file or directory
,08-29 11:07:09.971  1043  1519 D LGWifiP2pService: InactiveState
08-29 11:07:09.971  1043  1519 D LGWifiP2pService: InactiveState{ when=-54ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.971  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-54ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.971  1043  1519 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 11:07:09.972  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 11:07:09.972  7963  7963 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:07:09.973  7963  7963 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 11:07:09.973  7963  7963 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.973  1043  1519 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 11:07:09.973  1043  1519 D LGWifiP2pService: InactiveState{ when=-45ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.973  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-45ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.973  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.973  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.973  1043  1519 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.973  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.973  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.973  1043  1519 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.974  7963  7963 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.974  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.974  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.974  1043  1519 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.974  1925  2285 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 11:07:09.974  1043  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.974  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.974  1043  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:09.975  1043  1043 E WifiServerServiceExt: No p2p device connected
08-29 11:07:09.975  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:07:09.975  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:07:09.975  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:07:09.975  1043  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 11:07:09.975  1043  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:07:09.975  1043  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:07:09.976  1043  8021 E W,ifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 11:07:09.976  1043  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:07:09.976  1043  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.976  1043  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.976  1043  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.977  1043  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 11:07:09.977  1043  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.977  1043  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.977  1043  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 11:07:09.988  8003  8003 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:07:09.994  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 11:07:09.999  7982  8026 W FormManager: Network not available. Please check & try again.
08-29 11:07:10.002  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:10.007  7982  8027 V FormManager: Network unavailable.
,08-29 11:07:10.013  7982  8027 V FormManager: Network unavailable.
08-29 11:07:10.025  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 11:07:10.025  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 11:07:10.028  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:07:10.033  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 11:07:10.042  4318  8028 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 11:07:10.047  4318  8029 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 11:07:10.047  4318  8029 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 11:07:10.105  1043  1997 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8030 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 11:07:10.253  8030  8030 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 11:07:10.253  8030  8030 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 11:07:10.262  8030  8030 V [BNRBootReceiver]: Boot Receiver Return
08-29 11:07:10.264  8030  8030 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 11:07:10.327  1043  1942 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8051 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 11:07:10.328  1043  1942 I ActivityManager: Killing 7122:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-29 11:07:10.436  1043  1059 W libprocessgroup: failed to open /acct/uid_10093/pid_7122/cgroup.procs: No such file or directory
,08-29 11:07:10.471  7963  7963 E wpa_supplicant: USIM:  scard_init function
08-29 11:07:10.472  7963  7963 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 11:07:10.474  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 11:07:10.475  1043  8021 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 11:07:10.475  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 11:07:10.475  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-29 11:07:10.475  1043  8021 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 11:07:10.475  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 11:07:10.475  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-29 11:07:10.477  1043  1520 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 11:07:10.478  1043  1520 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 11:07:10.480  1043  1520 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 11:07:10.481  1043  1520 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-29 11:07:10.481  1043  1520 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 11:07:10.491  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=140753  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 11:07:10.492  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=140755  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 11:07:10.499  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.499  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:07:10.501  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.501  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.501  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.501  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 11:07:10.505  8051  8051 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 11:07:10.509  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.509  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.509  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 11:07:10.510  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:07:10.510  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 11:07:10.521  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.521  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:07:10.523  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:07:10.540  8051  8051 D PluginManager: init()
,08-29 11:07:10.587  7963  7963 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 11:07:10.590  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 11:07:10.590  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 11:07:10.591  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 11:07:10.591  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-29 11:07:10.591  1043  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 11:07:10.592  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:07:10.592  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:07:10.593  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140856  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 11:07:10.593  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140856  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 11:07:10.594  1043  1520 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140857
08-29 11:07:10.594  1043  1520 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140857
08-29 11:07:10.595  1043  1520 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140858
08-29 11:07:10.595  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140858
08-29 11:07:10.596  1043  1520 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140859
08-29 11:07:10.600  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=140863  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-29 11:07:10.607  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.607  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:07:10.608  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.609  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:07:10.609  7963  7963 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:07:10.609  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:07:10.609  7963  7963 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:07:10.610  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.610  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.610  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 11:07:10.612  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 11:07:10.612  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:07:10.612  1043  8021 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:07:10.612  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 11:07:10.612  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:07:10.612  1043  8021 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 11:07:10.613  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=140875  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 11:07:10.613  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:07:10.613  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:07:10.613  1043  1520 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:07:10.614  1043  1520 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:07:10.614  1043  1520 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:07:10.617  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:07:10.618  1043  1520 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 11:07:10.618  1043  1520 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140881  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 11:07:10.619  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.619  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.619  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-29 11:07:10.620  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:07:10.620  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 11:07:10.623  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 11:07:10.623  1043  1520 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140886
08-29 11:07:10.624  1043  1520 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140886
08-29 11:07:10.624  1043  1520 D WifiNative-wlan0: doString: [STATUS]
08-29 11:07:10.624  1043  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 11:07:10.625  1043  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 11:07:10.625  1043  1520 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 11:07:10.627  1043  1520 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 11:07:10.630  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.631  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:07:10.632  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:07:10.634  1043  1520 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 11:07:10.634  1043  1520 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 11:07:10.639  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.639  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.639  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 11:07:10.641  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.641  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.641  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 11:07:10.648  1043  1520 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 11:07:10.648  1043  1527 D ConnectivityService: Got NetworkAgent Messenger
08-29 11:07:10.648  1043  1520 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:07:10.649  1043  1520 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:07:10.649  1043  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 11:07:10.649  1043  1527 D ConnectivityService: NetworkAgent connected
,08-29 11:07:10.649  1043  1520 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:07:10.649  1043  1520 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:07:10.655  1043  1520 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 11:07:10.655  1043  1520 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:07:10.655  1043  1520 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 11:07:10.655  1043  1520 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 11:07:10.655  1043  1520 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 11:07:10.660  1043  1520 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-29 11:07:10.664   314   900 D CommandListener: Setting iface cfg
08-29 11:07:10.668  1043  8081 D DhcpStateMachine: StoppedState
08-29 11:07:10.668  1043  1520 E WifiStateMachine: Start Dhcp Watchdog 3
08-29 11:07:10.668  1043  8081 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:10.668  1043  8081 D DhcpStateMachine: WaitBeforeStartState
08-29 11:07:10.669  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:07:10.669  1043  1043 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 11:07:10.670  1043  1520 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140933  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:07:10.671  1043  1520 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140934  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:07:10.673  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=140935  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:07:10.673  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.673  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:07:10.675  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:07:10.677  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:07:10.677  1043  1043 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 11:07:10.678  1043  1520 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140941  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:07:10.678  1043  1520 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140941  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:07:10.679  1043  1520 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=140942  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 11:07:10.679  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.679  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:07:10.680  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14161] from screen [on:0 period:-712151848] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 11:07:10.680  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.681  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-712151847] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 11:07:10.681  1043  1520 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 11:07:10.685  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.686  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.686  1043  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-29 11:07:10.686  1043  1520 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.687  1043  1520 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.687  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.687  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.688  1043  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-29 11:07:10.688  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
08-29 11:07:10.689  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
08-29 11:07:10.689  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 11:07:10.689  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 11:07:10.692  1043  1520 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 11:07:10.692  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 11:07:10.693  1043  1520 D WifiNative-wlan0: SET ps 0: returned true
08-29 11:07:10.693  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 11:07:10.693  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 11:07:10.693  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 11:07:10.694  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2d1e1fe0 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:10.694  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2d1e1fe0 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:10.694  1043  8081 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:10.694  1043  8081 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 11:07:10.694  1043  1520 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 11:07:10.694  1043  1520 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 11:07:10.694  1043  1520 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 11:07:10.695   314   900 D CommandListener: Setting iface cfg
08-29 11:07:10.695   314   900 D CommandListener: Trying to bring up wlan0
08-29 11:07:10.696  1043  1520 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 11:07:10.697  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:07:10.697  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 11:07:10.699  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 11:07:10.699  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-29 11:07:10.700  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.700  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.700  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.700  1043  1520 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.701  1043  1520 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.701  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.702  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 11:07:10.702  1043  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 11:07:10.702  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 11:07:10.703  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 11:07:10.703  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 11:07:10.703  1043  1519 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:10.703  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 11:07:10.703  1043  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:10.704  1043  1520 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 11:07:10.704  1043  1520 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 11:07:10.704  7963  7963 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 11:07:10.704  1043  1520 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 11:07:10.704  1043  1520 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 11:07:10.731  1043  1520 D WifiNative-wlan0: SET ps 1: returned true
08-29 11:07:10.732  1043  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 11:07:10.732  1043  1520 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 11:07:10.732  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 11:07:10.733  1043  1520 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 11:07:10.733  1043  1527 D ConnectivityService: ignoring duplicate network state non-change
,08-29 11:07:10.738  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.738  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 11:07:10.739  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.739  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.739  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 11:07:10.741  1043  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 11:07:10.743  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.743  1043  1527 D ConnectivityService: Adding iface wlan0 to network 102
08-29 11:07:10.745  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.745  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 11:07:10.750  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.757  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.757  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.757  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 11:07:10.758  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 11:07:10.762  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.762  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.763  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 11:07:10.763  1043  1520 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 11:07:10.765  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-29 11:07:10.768  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 11:07:10.769  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.769  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:07:10.769  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 11:07:10.769  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.770  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 11:07:10.770  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.773  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:07:10.773  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 11:07:10.774  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.778  1043  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 11:07:10.778  1043  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 11:07:10.780  1043  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-29 11:07:10.781   314   900 E Netd    : netlink response contains error (File exists)
08-29 11:07:10.782  1043  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 11:07:10.783  1043  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 11:07:10.783  1043  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-29 11:07:10.783  1043  1527 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-29 11:07:10.785  1043  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 11:07:10.785  1043  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 11:07:10.785  1043  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 11:07:10.785  1043  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 11:07:10.785  1043  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:07:10.785  1043  8076 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:10.785  1043  8076 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 11:07:10.785  1043  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:07:10.785  1043  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 11:07:10.785  1043  8076 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:07:10.785  1043  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.785  1043  8076 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 11:07:10.785  1043  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 11:07:10.785  1043  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-29 11:07:10.785  1043  1527 D ConnectivityService:    accepting network in place of null
08-29 11:07:10.785  1043  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.788  1043  1520 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.788  1043  1520 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:07:10.788  1043  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 11:07:10.788  1043  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 11:07:10.789   314  8088 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 11:07:10.791  1835  1835 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.791  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 11:07:10.791  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 11:07:10.793  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:10.793  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:10.793  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:10.793  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:10.793  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:10.793  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:10.793  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:10.793  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:07:10.794  1043  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 11:07:10.794  1043  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 11:07:10.794  1043  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 11:07:10.795  1043  1043 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 11:07:10.795  1043  1527 D ConnectivityService: validation of new default Network = false
08-29 11:07:10.795  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 11:07:10.795  1043  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 11:07:10.795  1043  1527 D DSQN    : enableDataServiceNotify 
08-29 11:07:10.795  1043  1527 D DSQN    : start dsqn bin
08-29 11:07:10.795  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 11:07:10.795  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 11:07:10.797  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:07:10.799  1043  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 11:07:10.799  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.799  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:07:10.800  1043  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:07:10.793  8089  8089 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:10.802  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 11:07:10.793  8089  8089 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:10.806  6564  6668 D io.jxcore.node,.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 11:07:10.810  6564  6668 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 11:07:10.812  6564  6668 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3b0db61f Bundle[{}]
08-29 11:07:10.813  6564  6668 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 11:07:10.813  6564  6668 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 11:07:10.814  6564  6668 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 11:07:10.814  6564  6668 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 11:07:10.815  6564  6668 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 11:07:10.817  8089  8089 E DSQN    : DSQN ssw
,08-29 11:07:10.821  6564  6668 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 11:07:10.823  1043  1518 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 11:07:10.825  6564  6668 I System.out: Running OutgoingSocketThread
08-29 11:07:10.828  6564  8093 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 852)
08-29 11:07:10.829  6564  8093 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41125
08-29 11:07:10.829  6564  8093 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 11:07:10.831  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:07:10.832  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 11:07:10.833  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.839   314  8088 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 11:07:10.871   314  8088 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 11:07:10.897  1043  8081 D DhcpStateMachine: DHCPV4 request on wlan0
,08-29 11:07:10.898  1043  8081 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 11:07:10.898  1043  8081 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 11:07:10.902   314   899 D LGDataListener: argv[0]=dsqncommand
08-29 11:07:10.902   314   899 D LGDataListener: argv[1]=wlan0
,08-29 11:07:10.902   314   899 D LGDataListener: argv[2]=1
08-29 11:07:10.902   314   899 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 11:07:10.902  1043  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 11:07:10.902  1043  1117 D DSQN    : start to monitor internet connection
08-29 11:07:10.893  8096  8096 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:10.893  8096  8096 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 11:07:10.910  8096  8096 I dhcpcd  : version 5.5.6 starting
08-29 11:07:10.911  8096  8096 E dhcpcd  : get_duid: m
08-29 11:07:10.911  8096  8096 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 11:07:10.911  8096  8096 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-29 11:07:10.934  1043  8076 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 09:07:11 GMT], X-Android-Received-Millis=[1472461630934], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472461630901]}
08-29 11:07:10.934  1043  8076 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 11:07:10.934  1043  8076 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 11:07:10.934  1043  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-29 11:07:10.935  1043  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 11:07:10.935  1043  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:07:10.935  1043  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:07:10.935  1043  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 11:07:10.935  1043  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-29 11:07:10.935  1043  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 11:07:10.935  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.935  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 11:07:10.935  1043  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 11:07:10.935  1043  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.935  1043  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 11:07:10.935  1043  1520 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.936  1043  1520 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:07:10.936  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 11:07:10.936  1835  1835 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:10.936  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-29 11:07:10.949  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 11:07:10.950  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.951  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:10.991  8096  8096 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 11:07:10.991  8096  8096 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 11:07:10.991  8096  8096 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 11:07:10.991  8096  8096 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 11:07:10.992  8096  8096 D dhcpcd  : wlan0: sending REQUEST (xid 0x813dc2ef), next in 4.55 seconds
,08-29 11:07:11.028  8096  8096 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 11:07:11.056  8096  8096 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 11:07:11.056  8096  8096 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-29 11:07:11.058  8096  8096 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 11:07:11.058  8096  8096 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 11:07:11.058  8096  8096 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 11:07:11.059  8096  8096 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 11:07:11.059  8096  8096 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 11:07:11.059  8096  8096 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-29 11:07:11.069  8051  8051 W ExternalStrings: load override strings
08-29 11:07:11.069  8051  8051 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:07:11.069  8051  8051 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:07:11.072  8051  8051 D StatusProvider: onCreate
,08-29 11:07:11.108  8051  8051 V Signer  : override build config not found
08-29 11:07:11.108  8051  8051 D Signer  : value of property debug is false
,08-29 11:07:11.131  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-29 11:07:11.131  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-29 11:07:11.132  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-29 11:07:11.132  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-29 11:07:11.132  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-29 11:07:11.132  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-29 11:07:11.132  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-29 11:07:11.132  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-29 11:07:11.132  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-29 11:07:11.133  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-29 11:07:11.133  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-29 11:07:11.133  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-29 11:07:11.133  8051  8051 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-29 11:07:11.140  8051  8051 V LGMDMManager: Create singleton instance
08-29 11:07:11.176  8051  8051 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-29 11:07:11.231  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 11:07:11.233  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.245  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:07:11.252  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.258  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.258  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:07:11.259  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:07:11.261  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 11:07:11.264  6762  6762 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 11:07:11.267  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.267  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.274  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:07:11.282  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.289  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.289  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:07:11.291  6813  6813 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 11:07:11.344  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.344  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.344  8051  8116 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 11:07:11.350  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:07:11.355  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.360  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.360  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:07:11.361  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:07:11.365  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 11:07:11.365  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 11:07:11.365  6762  6762 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 11:07:11.365  6762  6762 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 11:07:11.365  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 11:07:11.366  6762  6762 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 11:07:11.366  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 11:07:11.366  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 11:07:11.366  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 11:07:11.366  6762  6762 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 11:07:11.366  6762  6762 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 11:07:11.366  6762  6762 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 11:07:11.369  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.369  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.373  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:07:11.379  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:07:11.384  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.385  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:07:11.385  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:07:11.388  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.390  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.393  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:07:11.399  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.405  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 11:07:11.406  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:07:11.406  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:07:11.410  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.410  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.417  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:07:11.424  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 11:07:11.430  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.430  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:07:11.430  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:07:11.433  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.434  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 11:07:11.441  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:07:11.447  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.452  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.452  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:07:11.452  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:07:11.459  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 11:07:11.460  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.473  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:07:11.478  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.484  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.484  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:07:11.485  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 11:07:11.489  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.489  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.497  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:07:11.502  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.504  1043  8081 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 11:07:11.506  1043  8081 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 11:07:11.506  1043  8081 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 11:07:11.506  1043  8081 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 11:07:11.506  1043  8081 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 11:07:11.506  1043  8081 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 11:07:11.506  1043  8081 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 11:07:11.506  1043  8081 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 11:07:11.507  1043  8081 D DhcpStateMachine: RunningState
08-29 11:07:11.509  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.510  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:07:11.510  6813  6813 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 11:07:11.513  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.514  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.517  8003  8003 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 11:07:11.521  8003  8003 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 11:07:11.524  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 11:07:11.530  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.537  8051  8116 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 11:07:11.537  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.537  8051  8116 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:07:11.537  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 11:07:11.538  6813  6813 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 11:07:11.539  6813  6813 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 11:07:11.540  6813  6813 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 11:07:11.544  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 11:07:11.545  8051  8117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 11:07:11.550  8003  8003 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 11:07:11.551  8003  8003 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 11:07:11.557  6762  6762 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 11:07:11.563  6762  6762 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 11:07:11.572  6813  6813 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 11:07:11.572  6813  6813 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 11:07:11.573  6813  6813 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 11:07:11.574  6813  6813 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 11:07:11.574  6813  6813 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 11:07:11.582  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 11:07:11.586  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-29 11:07:11.589  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 11:07:11.592  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 11:07:11.595  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 11:07:11.598  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 11:07:11.601  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-29 11:07:11.605  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 11:07:11.608  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 11:07:11.612  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 11:07:11.614  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-29 11:07:11.615  1043  1960 I ActivityManager: Killing 7163:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-29 11:07:11.681  8051  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-29 11:07:11.689  1043  1888 W libprocessgroup: failed to open /acct/uid_10005/pid_7163/cgroup.procs: No such file or directory
,08-29 11:07:11.729  8051  8116 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-29 11:07:11.744  8051  8116 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-29 11:07:11.744  8051  8116 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 11:07:11.745  8051  8116 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 11:07:11.746  8051  8116 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
,08-29 11:07:11.747  8051  8116 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-29 11:07:11.755  8051  8116 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-29 11:07:11.759  8051  8116 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-29 11:07:11.828  6564  6668 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 853)
08-29 11:07:11.828  6564  6668 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 853)
,08-29 11:07:11.836  6564  6668 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
,08-29 11:07:11.838  6564  6668 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 11:07:11.838  6564  6668 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 859)
08-29 11:07:11.844  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:11.844  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ea9937a added. We now have 2 listener(s)
08-29 11:07:11.845  1043  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:07:11.850  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-29 11:07:11.850  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:11.850  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:11.851  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:11.851  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f272b added. We now have 9 listener(s)
08-29 11:07:11.851  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:11.852  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:07:11.855  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:07:11.869  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:11.869  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:11.869  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:11.869  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:11.869  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:11.869  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:11.869  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:11.869  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:07:11.871  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:07:11.871  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:07:11.871  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:11.872  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc90521 added. We now have 3 listener(s)
08-29 11:07:11.872  1043  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.874  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:11.875  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:11.875  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:11.875  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:11.875  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:11.875  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ad6d46 added. We now have 10 listener(s)
08-29 11:07:11.875  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:11.875  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:07:11.875  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:07:11.875  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:11.876  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:11.876  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.876  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:11.876  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:11.876  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:11.876  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ea9937a removed from the list
08-29 11:07:11.876  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:11.876  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f272b removed from the list
08-29 11:07:11.876  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:07:11.876  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.877  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.877  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.878  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:11.878  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:11.878  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:11.878  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f272b not in the list
08-29 11:07:11.878  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.878  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.879  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:11.880  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:11.880  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:11.880  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ad6d46 removed from the list
08-29 11:07:11.880  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:11.880  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.880  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.880  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:11.880  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc90521 removed from the list
08-29 11:07:11.882  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:11.882  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b470b07 added. We now have 2 listener(s)
08-29 11:07:11.882  1043  1852 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:07:11.888  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:11.888  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:11.888  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:11.889  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:11.889  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1060434 added. We now have 9 listener(s)
08-29 11:07:11.889  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:11.889  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:07:11.892  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:07:11.895  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:11.895  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:11.895  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:11.895  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:11.895  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:11.895  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:11.895  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:11.895  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:07:11.897  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:11.897  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:07:11.899  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:11.899  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ec317d2 added. We now have 3 listener(s)
08-29 11:07:11.899  1043  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.900  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:11.902  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:11.902  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:11.902  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:11.902  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:11.902  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:11.902  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18bf50a3 added. We now have 10 listener(s)
08-29 11:07:11.902  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:11.902  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:07:11.902  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:07:11.902  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:07:11.902  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:07:11.903  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:07:11.906  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:07:11.906  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.911  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:07:11.912  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:07:11.914  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:07:11.914  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:11.916  6564  6668 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:07:11.917  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:07:11.917  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:11.919  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:07:11.919  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:07:11.919  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:11.919  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:11.919  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.919  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:11.919  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:11.919  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b470b07 removed from the list
08-29 11:07:11.919  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:11.919  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1060434 removed from the list
08-29 11:07:11.919  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:07:11.919  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.920  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.920  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.920  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:11.920  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:11.920  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:11.920  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1060434 not in the list
08-29 11:07:11.921  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.921  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.921  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:11.922  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:07:11.922  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-29 11:07:11.922  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:11.922  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:11.922  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18bf50a3 removed from the list
08-29 11:07:11.922  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:11.922  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.922  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.922  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:11.922  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ec317d2 removed from the list
08-29 11:07:11.923  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:11.923  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@516df1e added. We now have 2 listener(s)
,08-29 11:07:11.924  1043  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.927  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:11.927  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:11.928  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:11.928  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:11.928  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11ec53ff added. We now have 9 listener(s)
08-29 11:07:11.928  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:11.928  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:07:11.930  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:07:11.933  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:11.933  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:11.933  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:11.933  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:11.933  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:11.933  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:11.933  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:11.933  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:07:11.935  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:11.935  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:07:11.935  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:11.935  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daff015 added. We now have 3 listener(s)
08-29 11:07:11.935  1043  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.937  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:11.939  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:11.939  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:11.939  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:11.939  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:11.939  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:11.939  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@244dcf2a added. We now have 10 listener(s)
08-29 11:07:11.939  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:11.940  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:07:11.941  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:07:11.941  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:07:11.941  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:07:11.941  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:07:11.941  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:07:11.943  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:07:11.944  1043  1639 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.948  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:07:11.949  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 11:07:11.951  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:07:11.951  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:07:11.953  6564  6668 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:07:11.953  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:07:11.953  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:07:11.953  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:11.954  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:11.954  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.954  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:11.954  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:11.954  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@516df1e removed from the list
08-29 11:07:11.954  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:11.954  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11ec53ff removed from the list
08-29 11:07:11.954  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:07:11.954  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.955  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.955  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.956  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:11.956  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:11.956  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:11.956  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11ec53ff not in the list
08-29 11:07:11.956  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.956  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.957  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:11.958  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:07:11.958  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:07:11.958  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:11.958  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:11.958  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@244dcf2a removed from the list
08-29 11:07:11.958  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:11.958  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:11.958  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:11.958  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting d,own...
08-29 11:07:11.958  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daff015 removed from the list
08-29 11:07:11.960  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:11.960  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dac7891 added. We now have 2 listener(s)
08-29 11:07:11.960  1043  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.963  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:11.963  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:11.963  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:11.964  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:11.964  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51b3f6 added. We now have 9 listener(s)
08-29 11:07:11.964  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:11.964  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:07:11.968  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:07:11.972  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:11.972  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:11.972  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:11.972  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:11.972  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:11.972  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:11.972  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:11.972  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:07:11.974  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:11.974  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:07:11.974  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:11.974  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@294ce264 added. We now have 3 listener(s)
08-29 11:07:11.975  1043  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.977  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:11.980  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:11.980  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:11.980  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:11.980  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:07:11.981  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:11.981  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0ccd added. We now have 10 listener(s)
08-29 11:07:11.981  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:11.981  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:07:11.981  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:07:11.981  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:07:11.981  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:07:11.981  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:07:11.987  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:07:11.987  1043  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:11.994  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:07:11.995  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:07:11.998  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:07:11.998  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:12.000  6564  6668 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 11:07:12.003  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:07:12.003  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:07:12.003  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:12.003  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:07:12.003  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:12.003  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:12.003  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:12.003  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dac7891 removed from the list
08-29 11:07:12.003  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:12.003  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51b3f6 removed from the list
08-29 11:07:12.003  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:07:12.003  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:12.004  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:12.004  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:12.005  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:07:12.005  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:12.005  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:12.005  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51b3f6 not in the list
08-29 11:07:12.005  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:12.005  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:07:12.006  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:12.007  6564  6668 D BluetoothLeScanner: could not find callback wrapper
08-29 11:07:12.007  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:07:12.007  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:12.007  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:12.007  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0ccd removed from the list
08-29 11:07:12.007  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:07:12.007  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:12.007  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:12.007  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:12.007  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@294ce264 removed from the list
08-29 11:07:12.008  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:12.008  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f27c0d0 added. We now have 2 listener(s)
,08-29 11:07:12.008  1043  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 11:07:12.012  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:12.013  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:12.013  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:12.013  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:12.014  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318ca8c9 added. We now have 9 listener(s)
08-29 11:07:12.014  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:12.015  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:07:12.019  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:07:12.024  6564  6668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:12.024  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:12.024  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 11:07:12.024  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:12.024  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:12.024  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:12.024  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:12.024  6564  6668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:07:12.027  6564  6668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:12.027  6564  6668 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:07:12.027  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:12.027  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25483aef added. We now have 3 listener(s)
08-29 11:07:12.028  1043  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 11:07:12.030  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:12.031  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 11:07:12.032  6564  6564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:12.033  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:12.033  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:12.033  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:12.033  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259019fc added. We now have 10 listener(s)
08-29 11:07:12.033  6564  6668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:12.034  6564  6668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:07:12.034  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:07:12.034  6564  6668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:12.034  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:12.034  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:12.034  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:07:12.035  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:12.035  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f27c0d0 removed from the list
08-29 11:07:12.035  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:12.035  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318ca8c9 removed from the list
08-29 11:07:12.035  6564  6668 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:07:12.035  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:12.035  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:12.035  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:12.037  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:12.037  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:12.037  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:12.037  6564  6668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318ca8c9 not in the list
08-29 11:07:12.038  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:12.038  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:12.039  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:12.039  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:12.039  6564  6668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:12.039  6564  6668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259019fc removed from the list
08-29 11:07:12.040  6564  6668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:12.040  6564  6668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:12.040  6564  6668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:12.040  6564  6668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:12.040  6564  6668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25483aef removed from the list
08-29 11:07:12.042  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 11:07:12.043  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 11:07:12.043  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 11:07:12.043  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: ,false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:07:12.044  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 11:07:12.044  6564  6668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:07:12.064  6564  8150 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: My test thread name)
08-29 11:07:12.065  6564  8150 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 866, thread name: My test thread name)
08-29 11:07:12.065  6564  8150 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 866, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 11:07:12.069  6564  8151 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: My test thread name)
08-29 11:07:12.070  6564  8151 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: My test thread name)
08-29 11:07:12.070  6564  8151 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 11:07:12.073  6564  6668 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 11:07:12.073  6564  6668 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 11:07:12.073  6564  6668 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 11:07:12.073  6564  6668 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 11:07:12.073  6564  6668 D com.test.thalitest.ThaliTestRunner: Total duration: 23785 ms
08-29 11:07:12.075  6564  6668 I jxcore-log: *Native tests were executed*
08-29 11:07:12.075  6564  6668 I jxcore-log: 
08-29 11:07:12.075  6564  6668 I jxcore-log: Total number of executed tests:  80
08-29 11:07:12.075  6564  6668 I jxcore-log: 
08-29 11:07:12.075  6564  6668 I jxcore-log: Number of passed tests:  80
08-29 11:07:12.075  6564  6668 I jxcore-log: 
08-29 11:07:12.075  6564  6668 I jxcore-log: Number of failed tests:  0
08-29 11:07:12.075  6564  6668 I jxcore-log: 
08-29 11:07:12.076  6564  6668 I jxcore-log: Number of ignored tests:  0
08-29 11:07:12.076  6564  6668 I jxcore-log: 
08-29 11:07:12.076  6564  6668 I jxcore-log: Total duration:  23785
08-29 11:07:12.076  6564  6668 I jxcore-log: 
08-29 11:07:12.076  6564  6668 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 11:07:12.076  6564  6668 I jxcore-log: 
08-29 11:07:12.080  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.080  6564  6668 I jxcore-log: 
,08-29 11:07:12.083  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.083  6564  6668 I jxcore-log: 
08-29 11:07:12.085  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.085  6564  6668 I jxcore-log: 
08-29 11:07:12.086  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.086  6564  6668 I jxcore-log: 
08-29 11:07:12.088  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.088  6564  6668 I jxcore-log: 
08-29 11:07:12.089  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.089  6564  6668 I jxcore-log: 
08-29 11:07:12.093  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.093  6564  6668 I jxcore-log: 
08-29 11:07:12.095  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:07:12.095  6564  6668 I jxcore-log: 
08-29 11:07:12.096  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:07:12.096  6564  6668 I jxcore-log: 
08-29 11:07:12.098  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.098  6564  6668 I jxcore-log: 
08-29 11:07:12.099  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.099  6564  6668 I jxcore-log: 
08-29 11:07:12.100  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:07:12.100  6564  6668 I jxcore-log: 
08-29 11:07:12.102  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:07:12.102  6564  6668 I jxcore-log: 
08-29 11:07:12.102  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:07:12.102  6564  6668 I jxcore-log: 
08-29 11:07:12.103  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.103  6564  6668 I jxcore-log: 
08-29 11:07:12.104  6564  6564 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 11:07:12.104  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.104  6564  6668 I jxcore-log: 
08-29 11:07:12.105  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.105  6564  6668 I jxcore-log: 
08-29 11:07:12.106  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.106  6564  6668 I jxcore-log: 
08-29 11:07:12.107  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.107  6564  6668 I jxcore-log: 
08-29 11:07:12.108  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.108  6564  6668 I jxcore-log: 
08-29 11:07:12.109  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.109  6564  6668 I jxcore-log: 
,08-29 11:07:12.110  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:07:12.110  6564  6668 I jxcore-log: 
08-29 11:07:12.110  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:07:12.110  6564  6668 I jxcore-log: 
08-29 11:07:12.111  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:07:12.111  6564  6668 I jxcore-log: 
08-29 11:07:12.112  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.112  6564  6668 I jxcore-log: 
,08-29 11:07:12.113  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.113  6564  6668 I jxcore-log: 
08-29 11:07:12.114  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.114  6564  6668 I jxcore-log: 
,08-29 11:07:12.115  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.115  6564  6668 I jxcore-log: 
08-29 11:07:12.115  6564  6668 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:12.115  6564  6668 I jxcore-log: 
08-29 11:07:12.381  1043  1520 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:07:12.382  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:07:12.383  1043  1520 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-29 11:07:12.384  1043  1520 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:07:12.387  1043  1520 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:07:12.389  1043  1520 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 11:07:12.392  1043  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-29 11:07:12.392  1043  1527 D ConnectivityService: identical MTU - not setting
08-29 11:07:12.393  1043  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 11:07:12.393  1043  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 11:07:12.393  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:07:12.393  1043  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:07:12.394  1043  1527 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 11:07:12.397  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 11:07:12.469  8152  8152 D AndroidRuntime: 
08-29 11:07:12.469  8152  8152 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 11:07:12.473  8152  8152 D AndroidRuntime: CheckJNI is OFF
08-29 11:07:12.623  8152  8152 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 11:07:12.641  1043  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-29 11:07:12.642  1043  1115 I ActivityManager: Killing 6564:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-29 11:07:12.701  1043  1558 I WindowState: WIN DEATH: Window{13e11b25 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 11:07:12.702  1043  1526 D WifiService: Client connection lost with reason: 4
,08-29 11:07:12.708  1043  1558 D InputDispatcher: Window went away: Window{13e11b25 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 11:07:12.788  1043  1115 I ActivityManager:   Force finishing activity ActivityRecord{31034d66 u0 com.test.thalitest/.MainActivity t6}
,08-29 11:07:12.822   333   362 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 11:07:12.831  1043  1870 W ActivityManager: Spurious death for ProcessRecord{1a63b8ca 6564:com.test.thalitest/u0a118}, curProc for 6564: null
,08-29 11:07:12.834  1043  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-29 11:07:12.839  1043  1125 I ActivityManager:   Force finishing activity ActivityRecord{31034d66 u0 com.test.thalitest/.MainActivity t6 f}
,08-29 11:07:12.839  1043  1125 W ActivityManager: Duplicate finish request for ActivityRecord{31034d66 u0 com.test.thalitest/.MainActivity t6 f}
,08-29 11:07:12.869  2016  2016 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 11:07:12.870  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 11:07:12.870  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35026378 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 11:07:12.871  2016  2016 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-29 11:07:12.871  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 11:07:12.872  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33231a51 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-29 11:07:12.875  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 11:07:12.877  2016  2113 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-29 11:07:12.895  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-29 11:07:12.912  2474  2594 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 11:07:12.922  7602  7602 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 11:07:12.922  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 11:07:12.923  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 11:07:12.923  3832  3832 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 11:07:12.930  4585  4585 I art     : Explicit concurrent mark sweep GC freed 8193(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 17.183ms total 79.267ms
,08-29 11:07:12.940  1043  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 11:07:12.954  1043  1924 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:07:12.967  1043  1114 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 11:07:12.973  4466  4466 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 11:07:12.973  4466  4466 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 11:07:12.973  4466  4466 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 11:07:12.973  4466  4466 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 11:07:12.973  4466  4466 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:07:12.973  4466  4466 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:07:12.973  4466  4466 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:07:12.973  4466  4466 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:07:12.973  4466  4466 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:07:12.973  4466  4466 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:07:12.974  4466  4466 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:07:12.974  4466  4466 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:07:12.981  1043  1043 D administrator: Handling package changes for user 0
,08-29 11:07:12.983  8051  8051 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 11:07:12.986  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 11:07:12.988  1889  1889 D ActionManagerService: notifyUserLog: 1000003
08-29 11:07:12.989  3832  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-29 11:07:12.998  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-29 11:07:12.999  2016  2016 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-29 11:07:13.001  2016  2016 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 11:07:13.002  2016  2016 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 11:07:13.002  1586  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 11:07:13.002  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.005  1586  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 11:07:13.005  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.005  1889  1889 D ActionManagerService: notifyUserLog: 1000004
08-29 11:07:13.006  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 11:07:13.006  3832  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-29 11:07:13.007  3832  4098 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , display: false
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , animation: false }
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , display: false
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , animation: false }
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , display: false
08-29 11:07:13.010  2016  2016 I GBoardWebViewUtils: , animation: false }
08-29 11:07:13.018  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 11:07:13.019  1800  1800 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-29 11:07:13.025  1586  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:07:13.025  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 11:07:13.028  2016  8184 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 11:07:13.029  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 11:07:13.031  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 11:07:13.032  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:07:13.032  1586  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-29 11:07:13.033  2176  2176 I ConfigService: onCreate
,08-29 11:07:13.034  2176  2176 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 11:07:13.037  1586  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 11:07:13.037  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.037  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 11:07:13.044  1800  1800 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-29 11:07:13.053  2176  2176 I ConfigService: onBind returning update interface
08-29 11:07:13.054  2176  2176 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 11:07:13.054  2176  2176 I ConfigService: onBind returning config service
08-29 11:07:13.055  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 11:07:13.055  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 11:07:13.056  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:07:13.056  1586  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 11:07:13.060  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-29 11:07:13.061  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-29 11:07:13.062  1586  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 11:07:13.062  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.065  1043  1852 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:07:13.065  1043  1852 V SIM_STK : Menu title from STK is T-Mobile
08-29 11:07:13.067  2176  2176 I ConfigService: onDestroy
08-29 11:07:13.070  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-29 11:07:13.071  1853  1853 D SplitUIService: removed split : 
08-29 11:07:13.072  1800  8188 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 11:07:13.083  1586  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:07:13.083  1586  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 11:07:13.083  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-29 11:07:13.084  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 11:07:13.096  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:07:13.096  1586  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 11:07:13.100  1586  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 11:07:13.100  1586  1649 D KeyguardModel: createShortcutInfo...
,08-29 11:07:13.107  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-29 11:07:13.107  1853  1853 I SplitUIService: split app #11
08-29 11:07:13.107  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-29 11:07:13.107  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 11:07:13.118  1043  1906 V SIM_STK : Menu title from STK is T-Mobile
,08-29 11:07:13.120  1586  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 11:07:13.120  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.122  1586  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 11:07:13.122  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.123  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:07:13.123  1586  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 11:07:13.124  1586  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 11:07:13.124  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.124  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:07:13.124  1586  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 11:07:13.125  1586  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 11:07:13.125  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.126  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 11:07:13.126  1586  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 11:07:13.127  1586  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 11:07:13.127  1586  1649 D KeyguardModel: createShortcutInfo...
08-29 11:07:13.133  5943  8194 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-29 11:07:13.139  1043  1996 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 11:07:13.143  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 11:07:13.143  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 11:07:13.143  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 11:07:13.143  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 11:07:13.143  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 11:07:13.143  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:07:13.143  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 11:07:13.144  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 11:07:13.144  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 11:07:13.144  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 11:07:13.144  7602  7602 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 11:07:13.147  2016  2016 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-29 11:07:13.165  1800  8195 W GmsApplication: Using Auth Proxy for data requests.
,08-29 11:07:13.168  1800  8196 I PeopleContactsSync: CP2 sync disabled
08-29 11:07:13.169  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-29 11:07:13.169  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 11:07:13.173  1800  8195 W GmsApplication: Using Auth Proxy for data requests.
08-29 11:07:13.176  1800  4643 I Icing   : doRemovePackageData com.test.thalitest
08-29 11:07:13.197  6955  6955 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-29 11:07:13.211   327   438 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 11:07:13.212  3206  8199 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-29 11:07:13.223  2324  8200 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 11:07:13.244  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-29 11:07:13.253  1043  1558 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8201 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-29 11:07:13.255  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:07:13.256  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 11:07:13.257  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 11:07:13.258  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 11:07:13.260  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-29 11:07:13.270  1043  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f79239a u0 com.lge.launcher2/.Launcher t5} time:143543
08-29 11:07:13.277  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 11:07:13.277  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:07:13.277  2016  2266 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 11:07:13.278  2016  2266 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-29 11:07:13.279  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 11:07:13.279  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 11:07:13.280  1043  1043 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 11:07:13.281  1043  1560 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-29 11:07:13.292  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-29 11:07:13.292  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 11:07:13.293  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:07:13.299  2176  2310 I art     : Explicit concurrent mark sweep GC freed 6394(380KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.425ms total 17.950ms
08-29 11:07:13.300  2016  2016 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 11:07:13.302  2633  2633 D [Concierge]Service: onStartCommand(). Type : 8
08-29 11:07:13.302  2633  2633 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-29 11:07:13.302  2633  2633 D [Concierge]Service: Update widget ID : 11
08-29 11:07:13.303  2016  2016 D [Concierge]WidgetView: change position of spinner
,08-29 11:07:13.306  2633  2633 D [Concierge]Service: onStartCommand(). Type : 0
08-29 11:07:13.306  2016  2016 I [Concierge]WidgetView: initWebView(). Time : 1472461633306
08-29 11:07:13.320  2016  2016 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 158416393
08-29 11:07:13.320  2016  2016 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 11:07:13.321  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-29 11:07:13.324  2016  2016 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1233b989
08-29 11:07:13.324  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-29 11:07:13.326  8201  8201 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:07:13.327  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 11:07:13.327  8201  8201 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 11:07:13.327  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:07:13.328  8201  8201 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 11:07:13.328  8201  8201 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 11:07:13.333  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 11:07:13.334  2016  2016 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 11:07:13.334  2016  2016 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-29 11:07:13.335  2016  2016 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472461517355, New one : 1472461633306
08-29 11:07:13.335  2016  2016 D [Concierge]WidgetView: Unregister all receivers
08-29 11:07:13.335  2016  2016 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 11:07:13.336  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:07:13.338  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 11:07:13.339  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-29 11:07:13.340  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 11:07:13.342  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 11:07:13.343  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 11:07:13.343  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:07:13.344  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:07:13.349  1043  1125 I art     : Explicit concurrent mark sweep GC freed 84476(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.188ms total 300.452ms
08-29 11:07:13.379  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 11:07:13.380  8152  8152 D AndroidRuntime: Shutting down VM
,08-29 11:07:13.387  2016  2016 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-29 11:07:13.387  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-29 11:07:13.388  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 11:07:13.418  8201  8201 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 11:07:13.421  2016  2016 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@267ad8f5 time:143695
08-29 11:07:13.430  8201  8201 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-29 11:07:13.450  8201  8201 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 11:07:13.468  8201  8201 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 11:07:13.468  8201  8201 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 11:07:13.493  1043  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:07:13.498  1043  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 11:07:13.503  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-29 11:07:13.516  8201  8201 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-29 11:07:13.526  1043  1852 I ActivityManager: Killing 7642:com.google.android.talk/u0a72 (adj 15): empty #17
08-29 11:07:13.542  2016  2016 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-29 11:07:13.576  2016  2937 I GBoardtInterface: onReloaded()
,08-29 11:07:13.578  2016  2016 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-29 11:07:13.685  1043  1924 W libprocessgroup: failed to open /acct/uid_10072/pid_7642/cgroup.procs: No such file or directory
08-29 11:07:13.685  1979  1979 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 11:07:13.685  1979  1979 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-29 11:07:13.687  1043  1520 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=75.0, 0.0, 0.0  rx=147.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-712148841] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 11:07:13.688  1043  1520 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=75.0, 0.0, 0.0  rx=147.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-712148840] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 11:07:13.688  1043  1520 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 11:07:13.690  3832  4098 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 11:07:13.692  1979  1979 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-29 11:07:13.722  1043  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8227 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-29 11:07:13.726  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 11:07:13.727  3832  3848 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at com.android.inter,nal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 11:07:13.729  8051  8051 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 11:07:13.731  8051  8051 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 11:07:13.733  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-29 11:07:13.735  3832  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 11:07:13.735  3832  4490 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-29 11:07:13.737  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-29 11:07:13.738  3832  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 11:07:13.738  3832  4490 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 11:07:13.738  3832  4490 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-29 11:07:13.738  3832  4490 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-29 11:07:13.739  3832  4098 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 11:07:13.741  7398  7398 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-29 11:07:13.742  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-29 11:07:13.742  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-29 11:07:13.744  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-29 11:07:13.744  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 11:07:13.746  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-29 11:07:13.746  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 11:07:13.750  6762  6762 D PackageIntentReceiver: Not supported Hotkey customization function 

```
