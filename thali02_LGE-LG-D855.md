#### Test 83627337381d561_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-07 11:37:04.304  4582  6538 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 207 ms] updated apps [took 206 ms] 
09-07 11:37:04.436  6542  6542 D DocsApplication: Installing DEX configuration.
09-07 11:37:04.455  6542  6542 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-07 11:37:04.459  6542  6542 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{28b0e15b com.google.android.apps.docs}
09-07 11:37:04.474  6542  6542 D TAG     : onCreate()
09-07 11:37:04.496  6542  6542 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-07 11:37:04.919   328   442 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-07 11:37:04.925  3247  6574 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-07 11:37:05.311  1821  4735 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-07 11:37:05.365  6575  6575 D AndroidRuntime: 
09-07 11:37:05.365  6575  6575 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 11:37:05.367  6575  6575 D AndroidRuntime: CheckJNI is OFF
09-07 11:37:05.437  1821  4735 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-07 11:37:05.482  1821  4735 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-07 11:37:05.484  6575  6575 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 11:37:05.487  1037  1976 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 11:37:05.499  1944  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-07 11:37:05.503  1037  1976 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-07 11:37:05.505  1037  1976 D ActivityManager: setTaskToReturnTo : TaskRecord{2a8df12e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 11:37:05.505  1037  1976 D ActivityManager: setTaskToReturnTo : TaskRecord{2a8df12e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 11:37:05.506  1037  1976 D WindowStateEx: AppWindowTokenEx init.. 
09-07 11:37:05.507   334   339 E GBMv2   : DFP En is all cleared set to be enabled
09-07 11:37:05.560  1037  1976 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6601 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 11:37:05.562  6575  6575 D AndroidRuntime: Shutting down VM
09-07 11:37:05.612  1944  2758 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-07 11:37:05.613  1944  2758 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25a46c7 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 11:37:05.615  1944  2760 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-07 11:37:05.615  1944  2760 D SplitWindowPolicy: topRunningActivity=ActivityInfo{6eaf4f4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 11:37:05.672  6601  6601 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 11:37:05.737  6601  6601 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-07 11:37:05.745  6601  6601 I LibraryLoader: Loading: webviewchromium
09-07 11:37:05.747  6601  6601 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4293-4296)
09-07 11:37:05.747  6601  6601 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 11:37:05.776  6601  6601 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1df43b0d}
09-07 11:37:05.777  6601  6601 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 11:37:05.778  6601  6601 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 11:37:05.784  6601  6601 I BrowserStartupController: Initializing chromium process, renderers=0
09-07 11:37:05.785  6601  6601 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 11:37:05.798  6601  6601 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-07 11:37:05.798  6601  6601 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-07 11:37:05.799  6601  6601 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-07 11:37:05.804   316  2147 V AudioPolicyService: registerClient() client 0xb558a700, uid 10118
09-07 11:37:05.810  1037  1119 D BluetoothManagerService: Message: 20
,09-07 11:37:05.810  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10ad5448:true
09-07 11:37:05.812  6601  6601 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 11:37:05.812  6601  6601 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 11:37:05.812  6601  6601 I Adreno-EGL: Build Date: 12/12/14 금
09-07 11:37:05.812  6601  6601 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 11:37:05.812  6601  6601 I Adreno-EGL: Remote Branch: 
09-07 11:37:05.812  6601  6601 I Adreno-EGL: Local Patches: 
09-07 11:37:05.812  6601  6601 I Adreno-EGL: Reconstruct Branch: 
09-07 11:37:05.840  6542  6542 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 11:37:05.840  6542  6542 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 11:37:05.860  6601  6631 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-07 11:37:05.862  6601  6601 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-07 11:37:05.873  6601  6601 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 11:37:05.876  6601  6601 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 11:37:05.879  6601  6601 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 11:37:05.881  6601  6601 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 11:37:05.881  6601  6601 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 11:37:05.891  6601  6601 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-07 11:37:05.895  6601  6601 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 11:37:05.895  6601  6601 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 11:37:05.922  6601  6644 D OpenGLRenderer: Render dirty regions requested: true
09-07 11:37:05.922  6601  6644 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 11:37:05.926  6601  6644 D OpenGLRenderer: Enabling debug mode 0
,09-07 11:37:05.934  6601  6601 D Atlas   : Validating map...
09-07 11:37:05.937  1037  1748 D SplitWindow: check instance of lgWin Window{207fc042 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 11:37:05.994  6601  6642 D LgDataFeature: LgDataFeature() Constructor: none
09-07 11:37:05.994  6601  6642 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 11:37:06.023  6098  6098 I LockScreenSettings: New app installed broadcast received ..
,09-07 11:37:06.027  6098  6098 I LockScreenSettings: Number of installed packages  1
09-07 11:37:06.044  6542  6542 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 11:37:06.089  1037  1052 V SIM_STK : Menu title from STK is T-Mobile
,09-07 11:37:06.091  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +479ms (total +580ms)
09-07 11:37:06.091  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{157fe4cf u0 com.test.thalitest/.MainActivity t6} time:104640
09-07 11:37:06.094  6601  6601 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16c90140 time:104644
09-07 11:37:06.139  1037  2030 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6663 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 11:37:06.199  6601  6601 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-07 11:37:06.199  6601  6601 I chromium: 
,09-07 11:37:06.206  6601  6601 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-07 11:37:06.218  6663  6663 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-07 11:37:06.218  6663  6663 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-07 11:37:06.261  2800  2800 I MusicWidget: mDelayedStopHandler : unbind
,09-07 11:37:06.278  6601  6642 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-07 11:37:06.278  6601  6642 I chromium: 
,09-07 11:37:06.284  1037  1749 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6682 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-07 11:37:06.286  1037  1749 I ActivityManager: Killing 5759:com.google.android.gm/u0a64 (adj 15): empty #17
09-07 11:37:06.369  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,09-07 11:37:06.369  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-07 11:37:06.369  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-07 11:37:06.370  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
09-07 11:37:06.370  1037  1917 W libprocessgroup: failed to open /acct/uid_10064/pid_5759/cgroup.procs: No such file or directory
09-07 11:37:06.370  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-07 11:37:06.370  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-07 11:37:06.371  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-07 11:37:06.383  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-07 11:37:06.383  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-07 11:37:06.384  1037  1976 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@214de872com.lge.music.MediaPlaybackService$5@252ae4c3
,09-07 11:37:06.388  2131  2131 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-07 11:37:06.388  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.390  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.391  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.392  2131  2131 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@35367b09
09-07 11:37:06.392  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-07 11:37:06.393  2131  2131 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-07 11:37:06.393  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.394  2131  2131 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-07 11:37:06.394  2131  2131 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-07 11:37:06.394  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.395  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.395  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.396  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.397  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-07 11:37:06.398  2131  2131 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-07 11:37:06.400  2131  2131 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
,09-07 11:37:06.401  2131  2131 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-07 11:37:06.401  2131  2131 V MediaPlayer[Native]: reset
09-07 11:37:06.404  6601  6699 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435044352
09-07 11:37:06.407  2131  2131 V MediaPlayer[Native]: setListener
09-07 11:37:06.407  2131  2131 V MediaPlayer[Native]: disconnect
09-07 11:37:06.407  2131  2131 V MediaPlayer[Native]: destructor
09-07 11:37:06.407   316  2149 V AudioFlinger: releasing 18 from 2131 for -1
09-07 11:37:06.407   316  2149 V AudioFlinger:  decremented refcount to 0
09-07 11:37:06.408   316  2149 V AudioFlinger: purging stale effects
09-07 11:37:06.408  2131  2131 V MediaPlayer[Native]: disconnect
09-07 11:37:06.413  2131  2131 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,09-07 11:37:06.415  2131  2131 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-07 11:37:06.416  2131  2131 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-07 11:37:06.417  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
09-07 11:37:06.418  6601  6699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 11:37:06.418  6601  6699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 11:37:06.418  6601  6699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 11:37:06.418  6601  6699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 11:37:06.418  6601  6699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 11:37:06.418  6601  6699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36220204 added. We now have 1 listener(s)
09-07 11:37:06.420  2131  2131 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-07 11:37:06.421  2131  2131 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-07 11:37:06.421  2131  2131 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
,09-07 11:37:06.421  2131  2131 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 382271808
09-07 11:37:06.421  2131  2131 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 382271808
09-07 11:37:06.424  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 11:37:06.429  2131  2131 I SmartShareClient: [SmartShareManagerClient] terminate service: 2131/MediaPlaybackService/739391543
,09-07 11:37:06.431  6601  6699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-07 11:37:06.433  6601  6699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 11:37:06.436  6601  6699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 11:37:06.436  6601  6699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 11:37:06.445  6601  6699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@227e84b3 added. We now have 1 listener(s)
09-07 11:37:06.445  6601  6699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 11:37:06.447  2131  2131 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-07 11:37:06.447  2131  2131 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@29773879
,09-07 11:37:06.450  1037  1547 D WifiService: New client listening to asynchronous messages
09-07 11:37:06.452  2131  2131 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-07 11:37:06.452  2131  2131 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-07 11:37:06.453  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-07 11:37:06.453  2131  2131 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-07 11:37:06.454  6601  6699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 11:37:06.454  6601  6699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 11:37:06.455  6601  6699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 11:37:06.455  6601  6699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 11:37:06.455  6601  6699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 11:37:06.456  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
09-07 11:37:06.457  1037  1749 I ActivityManager: Killing 5803:com.google.android.talk/u0a72 (adj 15): empty #17
09-07 11:37:06.486  1037  1052 W libprocessgroup: failed to open /acct/uid_10072/pid_5803/cgroup.procs: No such file or directory
09-07 11:37:06.486  6601  6699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 11:37:06.488  1037  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 11:37:06.488  6601  6699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-07 11:37:06.489  6682  6682 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
09-07 11:37:06.495  6601  6699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 11:37:06.496  6601  6699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:06.496  6601  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:06.496  6601  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:06.496  6601  6699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:06.496  6601  6699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:06.496  6601  6699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:06.496  6601  6699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:06.496  6601  6699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:06.496  6601  6699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-07 11:37:06.496  6601  6699 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:06.497  6601  6699 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 11:37:06.515  6414  6414 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-07 11:37:06.516  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:06.517  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 11:37:06.521  6682  6682 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 11:37:06.527  6601  6601 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-07 11:37:06.538  1037  1976 I ActivityManager: Killing 5607:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-07 11:37:06.553  5577  5577 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-07 11:37:06.553  5577  5577 W System.err: android.os.DeadObjectException
09-07 11:37:06.554  5577  5577 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 11:37:06.554  5577  5577 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,09-07 11:37:06.554  5577  5577 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-07 11:37:06.554  5577  5577 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-07 11:37:06.554  5577  5577 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 11:37:06.554  5577  5577 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 11:37:06.554  5577  5577 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 11:37:06.554  5577  5577 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 11:37:06.554  5577  5577 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 11:37:06.554  5577  5577 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 11:37:06.554  5577  5577 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:06.554  5577  5577 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 11:37:06.554  5577  5577 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 11:37:06.554  5577  5577 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 11:37:06.555  5577  5577 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-07 11:37:06.555  5577  5577 W System.err: android.os.DeadObjectException
09-07 11:37:06.555  5577  5577 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 11:37:06.555  5577  5577 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 11:37:06.555  5577  5577 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-07 11:37:06.555  5577  5577 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-07 11:37:06.555  5577  5577 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 11:37:06.555  5577  5577 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 11:37:06.555  5577  5577 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 11:37:06.555  5577  5577 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 11:37:06.555  5577  5577 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 11:37:06.555  5577  5577 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 11:37:06.555  5577  5577 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:06.555  5577  5577 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 11:37:06.556  5577  5577 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 11:37:06.556  5577  5577 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-07 11:37:06.556  5577  5577 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-07 11:37:06.556  5577  5577 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-07 11:37:06.558  4469  6704 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-07 11:37:06.755  1037  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_5607/cgroup.procs: No such file or directory
09-07 11:37:06.755  1037  1906 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-07 11:37:06.766  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
09-07 11:37:06.767  5577  5577 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-07 11:37:06.768  5577  5577 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-07 11:37:06.834  1037  2030 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6713 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 11:37:06.835  5577  5577 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-07 11:37:06.915  6713  6713 D UEI.SmartControl: Quickset Services start...
09-07 11:37:06.917  6713  6713 I UEI.SmartControl: Manufacture = LGE
09-07 11:37:06.917  6713  6713 D UEI.SmartControl: Id = LGNevo
,09-07 11:37:06.920  6713  6713 D UEI.SmartControl: File observer start...
09-07 11:37:06.921  6713  6713 E UEI.SmartControl: IR Port is disabled: false
09-07 11:37:06.921  6713  6713 D UEI.SmartControl: Starting file observer...
09-07 11:37:06.921  6713  6713 D UEI.SmartControl: Extracting JNI libs...
09-07 11:37:06.921  6713  6713 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-07 11:37:07.006  6713  6713 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-07 11:37:07.006  6713  6713 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-07 11:37:07.006  6713  6713 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-07 11:37:07.037  6713  6713 I UEI.SmartControl: --- Selecting new region: 6
09-07 11:37:07.039  6713  6713 I UEI.SmartControl: Model = LG-D855
,09-07 11:37:07.040  6713  6713 D UEI.SmartControl: QS Service created
09-07 11:37:07.053  6713  6713 I UEI.SmartControl: Service initServices...
,09-07 11:37:07.057  6713  6713 D UEI.SmartControl: QS start get config
09-07 11:37:07.102  6713  6713 D UEI.SmartControl: Loading JNI Libs...
,09-07 11:37:07.235  6601  6702 W jxcore-log: Initializing JXcore engine
09-07 11:37:07.236  6601  6702 W jxcore-log: JXcore engine is ready
,09-07 11:37:07.272   334   341 E GBMv2   : DFP En is all cleared set to be enabled
09-07 11:37:07.272   334   341 E GBMv2   : Set value is all cleared set the max
09-07 11:37:07.272   334   341 I GBMv2   : DFP Enabled. Ignore VFP set
,09-07 11:37:07.268  6702  6702 W Thread-752: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7458]" dev="sockfs" ino=7458 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 11:37:07.268  6702  6702 W Thread-752: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-07 11:37:07.268  6702  6702 W Thread-752: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7646]" dev="sockfs" ino=7646 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 11:37:07.268  6702  6702 W Thread-752: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-07 11:37:07.268  6702  6702 W Thread-752: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[24512]" dev="sockfs" ino=24512 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-07 11:37:07.283  6601  6702 W jxcore-log: Starting JXcore engine
,09-07 11:37:07.359  6601  6702 W jxcore-log: Platform android
09-07 11:37:07.359  6601  6702 W jxcore-log: 
09-07 11:37:07.359  6601  6702 W jxcore-log: Process ARCH arm
09-07 11:37:07.359  6601  6702 W jxcore-log: 
,09-07 11:37:07.422  6713  6713 I UEI.SmartControl: Supports setup maps: true
,09-07 11:37:07.439  6713  6713 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 11:37:07.439  6713  6713 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-07 11:37:07.440  6713  6713 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 11:37:07.440  6713  6713 I UEI.SmartControl: ### init IR Blaster...
09-07 11:37:07.448  6713  6713 D serial_port: Configuring serial port
09-07 11:37:07.454  6713  6713 E UEI.SmartControl: UEIBLaster setting for 616
09-07 11:37:07.454  6713  6713 I UEI.SmartControl: Setting serial record hearder size = 2
,09-07 11:37:07.455  6713  6713 I UEI.SmartControl: configuring settings for MAXQ616
09-07 11:37:07.456  6713  6713 I UEI.SmartControl: Get version...
09-07 11:37:07.472  6713  6741 D UEI.SmartControl: serial port data available: 21
,09-07 11:37:07.499  6713  6713 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-07 11:37:07.499  6713  6713 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-07 11:37:07.499  6713  6713 I UEI.SmartControl: QS saving settings...
09-07 11:37:07.500  6713  6713 D UEI.SmartControl: IR Blaster version: 25672567
,09-07 11:37:07.519  6713  6741 D UEI.SmartControl: serial port data available: 4
,09-07 11:37:07.550  6601  6702 I jxcore-log: JXcore Cordova bridge is ready!
09-07 11:37:07.550  6601  6702 I jxcore-log: 
09-07 11:37:07.550  6601  6702 W jxcore-log: JXcore engine is started
,09-07 11:37:07.563  6713  6745 I UEI.SmartControl: Device manager: loading config....
09-07 11:37:07.564  6713  6745 D UEI.SmartControl: ----------- loading internal config...
09-07 11:37:07.564  6601  6699 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 11:37:07.567  6713  6713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-07 11:37:07.570  6713  6713 E UEI.SmartControl: Services init done
09-07 11:37:07.571  6713  6713 D UEI.SmartControl: QS Service init finished
09-07 11:37:07.571  6713  6745 E UEI.SmartControl: Loading SETTINGS...
09-07 11:37:07.572  6713  6713 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 11:37:07.572  6713  6713 D UEI.SmartControl: QS Service version code: 201091
09-07 11:37:07.573  6713  6713 D UEI.SmartControl: Service requested: Control
09-07 11:37:07.574  5577  5577 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-07 11:37:07.575  6713  6729 I UEI.SmartControl: ------ IControl API: 11
09-07 11:37:07.575  1037  1748 I ActivityManager: Killing 5577:com.lge.qremote/u0a112 (adj 15): empty #17
,09-07 11:37:07.575  6713  6729 I UEI.SmartControl: Registering callback...
09-07 11:37:07.576  6713  6745 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 11:37:07.576  6601  6601 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-07 11:37:07.596  6713  6744 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 11:37:07.596  6713  6744 D UEI.SmartControl: -----service ready thread exits
,09-07 11:37:07.672  1037  1578 W libprocessgroup: failed to open /acct/uid_10112/pid_5577/cgroup.procs: No such file or directory
09-07 11:37:07.672  6713  6713 D UEI.SmartControl: Internal service binding...
,09-07 11:37:10.047  6542  6542 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-07 11:37:10.052  1037  1947 I ActivityManager: Killing 6229:com.android.calendar/u0a13 (adj 15): empty #17
09-07 11:37:10.152  1037  1941 W libprocessgroup: failed to open /acct/uid_10013/pid_6229/cgroup.procs: No such file or directory
,09-07 11:37:10.932  6542  6639 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 11:37:12.571  6713  6746 D UEI.SmartControl: Internal timer expired: 1
09-07 11:37:12.571  6713  6746 D UEI.SmartControl: unbind internal service
,09-07 11:37:12.592  6713  6713 D UEI.SmartControl: Service.onUnbind: IControl
,09-07 11:37:12.601  6713  6713 D UEI.SmartControl: Service.onDestroy
09-07 11:37:12.601  6713  6713 D UEI.SmartControl: Lock is in USE false
09-07 11:37:12.601  6713  6713 D UEI.SmartControl: unbind internal service
09-07 11:37:12.602  6713  6713 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@35367b09
09-07 11:37:12.602  6713  6713 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-07 11:37:12.602  6713  6713 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-07 11:37:12.602  6713  6713 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-07 11:37:12.602  6713  6713 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-07 11:37:12.602  6713  6713 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-07 11:37:12.602  6713  6713 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-07 11:37:12.602  6713  6713 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-07 11:37:12.602  6713  6713 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-07 11:37:12.602  6713  6713 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 11:37:12.602  6713  6713 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 11:37:12.602  6713  6713 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 11:37:12.602  6713  6713 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 11:37:12.602  6713  6713 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 11:37:12.602  6713  6713 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 11:37:12.603  6713  6713 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 11:37:12.603  6713  6713 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@35367b09
09-07 11:37:12.644  6713  6713 D serial_port: close(fd = 25)
,09-07 11:37:12.681  6713  6713 I UEI.SmartControl: Serial port is closed.
,09-07 11:37:12.683  6713  6713 I UEI.SmartControl: Serial port is closed.
09-07 11:37:12.683  6713  6713 D UEI.SmartControl: Blaster closed
09-07 11:37:12.683  6713  6713 D UEI.SmartControl: Shut down QS...
09-07 11:37:12.683  6713  6713 D UEI.SmartControl: Stopping QS lib
09-07 11:37:12.683  6713  6713 D UEI.SmartControl: QS lib stop result = true
09-07 11:37:12.684  6713  6713 D UEI.SmartControl: Stopped QS lib
09-07 11:37:12.684  6713  6713 D UEI.SmartControl: Stopped file observer...
09-07 11:37:12.684  6713  6713 D UEI.SmartControl: QS shutdown complete
09-07 11:37:13.442  1821  6450 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 11:37:13.511   312  6849 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 11:37:13.511   312  6849 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 11:37:13.512   312  6849 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 11:37:13.746  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
09-07 11:37:13.748  1821  1821 I ConfigFetchService: stopping self
,09-07 11:37:13.761  2184  2184 I ConfigService: onDestroy
,09-07 11:37:16.460  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19994
,09-07 11:37:18.496  1037  1093 I ActivityManager: Waited long enough for: ServiceRecord{2de33093 u0 com.google.android.gms/.wearable.service.WearableService}
,09-07 11:37:19.536  6601  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 11:37:19.536  6601  6702 I jxcore-log: 
,09-07 11:37:19.539  6601  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 11:37:19.539  6601  6702 I jxcore-log: 
09-07 11:37:19.545  6601  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:19.545  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:19.545  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:19.545  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:19.545  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:19.545  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:19.545  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:19.545  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:19.548  6601  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:19.551  6601  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 11:37:19.551  6601  6702 I jxcore-log: 
09-07 11:37:19.552  6601  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 11:37:19.552  6601  6702 I jxcore-log: 
,09-07 11:37:20.057  6601  6702 I jxcore-log: Unit Test app is loaded
09-07 11:37:20.057  6601  6702 I jxcore-log: 
,09-07 11:37:20.062  6601  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 11:37:20.062  6601  6702 I jxcore-log: 
09-07 11:37:20.068  6601  6702 D executeNativeTests: Running unit tests
09-07 11:37:20.084  6601  6601 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-07 11:37:20.143  6601  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 11:37:20.143  6601  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 added. We now have 2 listener(s)
09-07 11:37:20.143  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 11:37:20.145  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 11:37:20.145  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 11:37:20.145  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 11:37:20.145  6601  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 11:37:20.145  6601  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d added. We now have 2 listener(s)
09-07 11:37:20.145  6601  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 11:37:20.148  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 11:37:20.152  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:20.157  6601  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:20.157  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:20.157  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:20.157  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:20.157  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:20.157  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:20.157  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:20.157  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:20.158  6601  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:20.158  6601  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:20.162  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:20.165  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:20.173  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 11:37:20.175  6601  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:20.175  6601  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:20.181  6601  6702 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 11:37:20.182  6601  6702 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 11:37:20.182  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 11:37:20.182  6601  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:37:20.182  6601  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:37:20.183  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:20.183  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:20.183  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:20.183  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 11:37:20.183  6601  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 removed from the list
09-07 11:37:20.183  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:20.183  6601  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d removed from the list
09-07 11:37:20.184  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:20.184  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:20.186  6601  6702 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 11:37:20.187  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:20.187  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:20.188  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:20.188  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:20.188  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:20.188  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:20.188  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:20.188  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:20.188  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 11:37:20.200  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 11:37:20.201  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 11:37:20.201  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 11:37:20.201  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 11:37:20.201  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 11:37:20.201  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 11:37:20.202  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:20.202  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:20.202  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:20.202  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:20.202  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:20.202  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thal,iproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:20.202  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:20.204  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:20.204  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:20.205  6601  6702 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 11:37:20.207  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:20.210  6601  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:20.210  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:20.210  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:20.210  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:20.210  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:20.210  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:20.210  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:20.210  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 11:37:20.212  6601  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:20.212  6601  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 11:37:20.214  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:20.217  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:20.218  6601  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:37:20.219  6601  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:37:20.219  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:37:20.219  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:20.219  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:20.224  6601  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 11:37:20.225  1037  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 11:37:20.234  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 11:37:20.243  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 11:37:20.246  6601  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 11:37:20.247  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 11:37:20.248  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:20.250  6601  6702 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 11:37:20.250  6601  6702 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:22.289  1037  1386 V AlarmManager: RTC_WAKEUP set : Alarm{148ef8a1 type 0 when 1473241039072 com.android.vending} when 1473241039072
,09-07 11:37:22.402  1037  2036 V SIM_STK : Menu title from STK is T-Mobile
,09-07 11:37:22.552  6058  6058 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-07 11:37:23.255  6601  6702 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-07 11:37:23.256  6601  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 11:37:23.256  6601  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 11:37:26.273  6601  6702 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 11:37:26.273  6601  6702 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-07 11:37:26.274  6601  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:37:26.274  6601  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:37:26.274  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:37:26.274  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:26.274  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 11:37:26.295  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 11:37:26.297  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:26.299  6601  6702 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 11:37:26.299  6601  6702 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:29.301  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:29.301  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:29.301  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:29.301  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:29.301  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:29.302  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:29.302  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:29.302  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:29.314  6601  6702 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 11:37:29.317  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:29.322  6601  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:29.322  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:29.322  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:29.322  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:29.322  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:29.322  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:29.322  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:29.322  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:29.325  6601  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:29.325  6601  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:29.327  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:29.329  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:29.330  6601  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:37:29.330  6601  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:37:29.330  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:37:29.330  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:29.330  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:29.335  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 11:37:29.338  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:29.339  6601  6702 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 11:37:29.340  6601  6702 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:32.340  6601  6702 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 11:37:32.341  6601  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 11:37:32.341  6601  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 11:37:35.356  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 11:37:35.356  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:35.356  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:35.356  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.356  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:35.357  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.357  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 11:37:35.357  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-07 11:37:35.373  6601  6702 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 11:37:35.374  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.374  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.374  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.374  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.374  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:35.374  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.374  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.374  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.374  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.375  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 11:37:35.376  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.376  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.376  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.376  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.376  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:35.376  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.376  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.376  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.376  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.377  6601  6702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 11:37:35.380  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.380  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.380  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.380  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.380  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:35.380  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.380  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.380  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMan,ager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.380  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.381  6601  6702 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 11:37:35.381  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.381  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.381  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.381  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.381  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:35.381  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
,09-07 11:37:35.382  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.382  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.382  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.382  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 11:37:35.391  6601  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:35.391  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 11:37:35.391  6601  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 11:37:35.393  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 11:37:35.393  6601  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 11:37:35.394  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.394  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.394  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.395  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.395  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:35.395  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.395  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.395  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.395  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.396  6601  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:35.396  6601  6702 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 11:37:35.396  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 11:37:35.400  6601  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:35.400  6601  6702 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 11:37:35.400  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 11:37:35.400  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 11:37:35.400  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 11:37:35.400  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 11:37:35.405  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 11:37:35.407  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 11:37:35.408  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 11:37:35.408  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 11:37:35.408  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 11:37:35.408  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 11:37:35.408  6601  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to ,peer with ID abcd
09-07 11:37:35.408  6601  6702 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:35.408  6601  6702 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 11:37:35.408  6601  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:35.408  6601  6702 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:35.409  6601  6702 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 11:37:35.409  6601  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:35.409  6601  6702 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 11:37:35.409  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55],
09-07 11:37:35.416  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-07 11:37:35.425  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 11:37:35.426  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 11:37:35.428  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 11:37:35.429  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 11:37:35.429  6601  6702 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 11:37:35.429  6601  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 11:37:35.429  6601  6702 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 11:37:35.430  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.430  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.430  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.430  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 11:37:35.434  6601  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 849)
,09-07 11:37:35.443  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.443  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:35.443  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.443  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.443  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.443  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.445  6601  6702 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 11:37:35.445  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.445  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.445  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.445  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.445  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:35.445  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.445  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.445  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.445  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.446  6601  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 11:37:35.447  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.447  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.447  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.447  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.447  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 11:37:35.447  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.447  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.447  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.447  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.448  6601  6702 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 11:37:35.448  6601  6702 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Fai,led to find an outgoing connection to peer with ID randomString
09-07 11:37:35.448  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 11:37:35.448  6601  6702 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 11:37:35.448  6601  6702 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 11:37:35.449  6601  6702 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 11:37:35.449  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 11:37:35.449  6601  6702 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 11:37:35.449  6601  6702 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 11:37:35.449  6601  6702 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-07 11:37:35.449  6601  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 11:37:35.449  6601  6702 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 11:37:35.449  6601  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 11:37:35.449  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 11:37:35.449  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 11:37:35.449  6601  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@309a4fd4 not in the list
09-07 11:37:35.449  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 11:37:35.449  6601  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fec57d not in the list
09-07 11:37:35.449  6601  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-07 11:37:35.449  6601  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 11:37:35.449  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 11:37:35.450  6601  6702 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 11:37:35.456  6601  6876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 849
09-07 11:37:35.456  6601  6876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 849)
,09-07 11:37:35.456  6601  6876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 849)
,09-07 11:37:35.467  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:35.473  6601  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 11:37:35.473  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 11:37:35.473  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 11:37:35.473  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 11:37:35.473  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 11:37:35.473  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:35.473  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 11:37:35.473  6601  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 11:37:35.475  6601  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 11:37:35.476  6601  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 11:37:35.479  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:35.482  6601  6601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 11:37:35.482  6601  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 11:37:35.482  6601  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 11:37:35.482  6601  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 11:37:35.482  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 11:37:35.482  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 11:37:35.487  6601  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 11:37:35.489  6601  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 11:37:35.502  6601  6702 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 11:37:35.504  6601  6702 I io.jxcore.node.ConnectionHelper: start: OK
09-07 11:37:35.582  6601  6875 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,09-07 11:37:35.585  6601  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 849)
,09-07 11:37:36.464  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,09-07 11:37:36.474  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,09-07 11:38:00.090  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:38:00.095  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:38:00.096  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:38:00.097  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
09-07 11:38:00.103  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:38:00.103  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:38:00.103  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:38:00.104  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate,
09-07 11:39:00.102  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:39:00.102  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:39:00.103  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:39:00.103  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:39:00.120  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:39:00.120  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:39:00.124  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:39:00.125  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:39:29.974  1606  1606 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:39:29.975  1606  1606 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:39:29.990  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:39:29.990  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 11:39:29.993  1037  1547 D WifiController: battery changed pluggedType: 2
09-07 11:39:29.995  1606  1606 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
09-07 11:39:29.995  1606  1606 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:39:29.997  1944  2076 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:39:29.997  1944  2076 D LEDHandler: Battery Level Remaining: 100%
09-07 11:39:29.997  1944  2076 D LEDHandler: Battery Temp: 276, mChargingStatus=5, mChargingStop=false
09-07 11:39:29.999  3848  3975 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:39:30.000  1606  1606 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:39:30.006  6682  6682 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 11:40:00.087  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:40:00.087  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:40:00.087  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 11:40:00.088  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:40:00.102  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:40:00.102  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:40:00.103  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:40:00.105  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:40:19.222  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:40:19.234  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1f964c11 type 2 when 223816 android} when 223816
09-07 11:40:19.237  1037  1386 V AlarmManager: RTC_WAKEUP set : Alarm{2451c176 type 0 when 1473241080465 com.google.android.gms} when 1473241080465
,09-07 11:40:19.280  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:40:19.467  1037  2010 I art     : Explicit concurrent mark sweep GC freed 26131(1288KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.953ms total 219.029ms
,09-07 11:40:19.476  1821  6907 I EventLogService: Aggregate from 1473240977661 (log), 1473239280397 (data)
,09-07 11:40:19.480  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:40:56.143  1037  3551 I LocationManagerService: remove 1159b34b
09-07 11:40:56.144  1037  3551 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
09-07 11:40:56.145  1037  3551 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 11:40:56.146  1037  3551 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-07 11:40:56.147  1037  3551 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,09-07 11:40:56.148  1037  3551 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1],
,09-07 11:41:00.092  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:41:00.092  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:41:00.093  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:41:00.093  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:41:00.106  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:41:00.106  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:41:00.109  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:41:00.112  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:41:06.300  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:41:06.348  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:41:06.377  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:42:00.107  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:42:00.107  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:42:00.107  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 11:42:00.108  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:42:00.122  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:42:00.122  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:42:00.123  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:42:00.124  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:42:34.175  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:42:34.200  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{716be4 type 2 when 432707 com.google.android.gms} when 432707
,09-07 11:42:34.235  1821  1821 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 11:42:34.248  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:42:34.262  2184  2184 I ConfigService: onCreate
09-07 11:42:34.263  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-07 11:42:34.269  1821  6927 I ConfigFetchService: running network task: configservice_periodic
09-07 11:42:34.282  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:42:34.286  1821  6927 I ConfigFetchService: launchTask
09-07 11:42:34.292  2184  2184 I ConfigService: onBind returning update interface
09-07 11:42:34.293  1821  1821 I ConfigFetchService: service connected
,09-07 11:42:34.295  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 11:42:34.295  2184  2184 I ConfigService: onBind returning config service
09-07 11:42:34.297  1821  1821 I ConfigClient: service connected
09-07 11:42:34.393  1037  2036 V SIM_STK : Menu title from STK is T-Mobile
,09-07 11:42:34.415  1821  2351 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 11:42:34.425   312  6946 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 11:42:34.426   312  6946 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 11:42:34.467   312  6946 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 11:42:34.681  1821  2351 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 11:42:34.692  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
09-07 11:42:34.695  1821  1821 I ConfigFetchService: stopping self
,09-07 11:42:34.759  2184  2184 I ConfigService: onDestroy
,09-07 11:43:00.058  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:43:00.058  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:43:00.058  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:43:00.059  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:43:00.072  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:43:00.073  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:43:00.073  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:43:00.074  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:43:04.767  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:43:04.783  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{25283867 type 2 when 463299 com.google.android.gms} when 463299
09-07 11:43:04.822  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:43:04.854  2184  2184 I ConfigService: onCreate
09-07 11:43:04.855  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-07 11:43:04.860  1821  1821 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-07 11:43:04.878  1821  6958 I ConfigFetchService: running network task: configservice_periodic
,09-07 11:43:04.881  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
09-07 11:43:04.883  1821  6958 I ConfigFetchService: launchTask
09-07 11:43:04.885  2184  2184 I ConfigService: onBind returning update interface
09-07 11:43:04.886  1821  1821 I ConfigFetchService: service connected
09-07 11:43:04.886  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 11:43:04.886  2184  2184 I ConfigService: onBind returning config service
09-07 11:43:04.887  1821  1821 I ConfigClient: service connected
09-07 11:43:04.955  1037  1983 V SIM_STK : Menu title from STK is T-Mobile
,09-07 11:43:04.981  1821  2352 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 11:43:04.986   312  6969 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-07 11:43:04.987   312  6969 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
,09-07 11:43:04.987   312  6969 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-07 11:43:05.194  1821  2352 W ConfigFetchTask: bad response from server: 401 Unauthorized
09-07 11:43:05.196  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
,09-07 11:43:05.203  1821  1821 I ConfigFetchService: stopping self
09-07 11:43:05.246  2184  2184 I ConfigService: onDestroy
,09-07 11:44:00.105  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:44:00.105  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:44:00.105  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:44:00.106  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:44:00.117  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:44:00.117  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:44:00.120  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:44:00.125  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:44:05.217  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:44:05.230  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{29af32d6 type 2 when 523749 com.google.android.gms} when 523749
,09-07 11:44:05.268  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:44:05.305  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:44:05.318  1821  1821 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 11:44:05.324  2184  2184 I ConfigService: onCreate
09-07 11:44:05.324  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 11:44:05.331  1821  6977 I ConfigFetchService: running network task: configservice_periodic
,09-07 11:44:05.335  1821  6977 I ConfigFetchService: launchTask
09-07 11:44:05.336  2184  2184 I ConfigService: onBind returning update interface
09-07 11:44:05.337  1821  1821 I ConfigFetchService: service connected
09-07 11:44:05.337  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 11:44:05.337  2184  2184 I ConfigService: onBind returning config service
09-07 11:44:05.338  1821  1821 I ConfigClient: service connected
09-07 11:44:05.407  1037  1906 V SIM_STK : Menu title from STK is T-Mobile
,09-07 11:44:05.433  1821  3970 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 11:44:05.438   312  6991 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-07 11:44:05.439   312  6991 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
,09-07 11:44:05.439   312  6991 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-07 11:44:05.924  1821  3970 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 11:44:05.936  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
09-07 11:44:05.939  1821  1821 I ConfigFetchService: stopping self
09-07 11:44:05.973  2184  2184 I ConfigService: onDestroy
,09-07 11:45:00.108  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:45:00.108  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:45:00.108  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 11:45:00.109  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:45:00.123  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:45:00.123  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:45:00.124  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:45:00.124  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:45:01.875  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:45:01.951  1037  1093 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6999 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-07 11:45:01.983  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:45:02.102  6999  6999 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,09-07 11:45:02.109  6999  6999 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1b015136
09-07 11:45:02.109  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
09-07 11:45:02.111  1037  2030 I ActivityManager: Killing 6177:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-07 11:45:02.154  1037  1748 W libprocessgroup: failed to open /acct/uid_10014/pid_6177/cgroup.procs: No such file or directory
,09-07 11:45:57.398  1606  1606 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,09-07 11:45:57.398  1606  1606 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:45:57.414  1606  1606 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
09-07 11:45:57.414  1606  1606 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:45:57.416  1037  1547 D WifiController: battery changed pluggedType: 2
,09-07 11:45:57.419  1944  2076 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:45:57.419  1944  2076 D LEDHandler: Battery Level Remaining: 100%
09-07 11:45:57.419  1944  2076 D LEDHandler: Battery Temp: 271, mChargingStatus=5, mChargingStop=false
09-07 11:45:57.422  1606  1606 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:45:57.425  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:45:57.425  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:45:57.426  3848  3975 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:45:57.432  6682  6682 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 11:46:00.052  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:46:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:46:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 11:46:00.053  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:46:00.068  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:46:00.069  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:46:00.073  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:46:00.074  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:46:05.952  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:46:05.966  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{7beae61 type 2 when 644484 com.google.android.gms} when 644484
,09-07 11:46:06.002  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:46:06.028  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:46:06.052  1821  1821 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 11:46:06.057  2184  2184 I ConfigService: onCreate
09-07 11:46:06.057  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 11:46:06.065  1821  7040 I ConfigFetchService: running network task: configservice_periodic
,09-07 11:46:06.068  1821  7040 I ConfigFetchService: launchTask
09-07 11:46:06.069  2184  2184 I ConfigService: onBind returning update interface
09-07 11:46:06.070  1821  1821 I ConfigFetchService: service connected
09-07 11:46:06.071  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 11:46:06.071  2184  2184 I ConfigService: onBind returning config service
09-07 11:46:06.073  1821  1821 I ConfigClient: service connected
09-07 11:46:06.162  1037  2030 V SIM_STK : Menu title from STK is T-Mobile
,09-07 11:46:06.178  1821  6450 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 11:46:06.182   312  7053 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 11:46:06.183   312  7053 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 11:46:06.183   312  7053 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-07 11:46:06.388  1821  6450 W ConfigFetchTask: bad response from server: 401 Unauthorized
09-07 11:46:06.391  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
,09-07 11:46:06.394  1821  1821 I ConfigFetchService: stopping self
09-07 11:46:06.435  2184  2184 I ConfigService: onDestroy
,09-07 11:47:00.003  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:47:00.050  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:47:00.063  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:47:00.063  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:47:00.063  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:47:00.064  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:47:00.069  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:47:00.069  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:47:00.070  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:47:00.073  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:47:00.115  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:47:10.935  1037  1749 I ActivityManager: Killing 6297:com.android.defcontainer/u0a4 (adj 15): empty #17
,09-07 11:47:10.966  1037  1947 W libprocessgroup: failed to open /acct/uid_10004/pid_6297/cgroup.procs: No such file or directory
,09-07 11:48:00.102  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:48:00.103  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:48:00.103  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:48:00.103  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:48:00.117  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:48:00.117  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:48:00.119  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:48:00.122  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:49:00.112  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:49:00.112  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:49:00.113  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:49:00.113  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:49:00.125  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:49:00.126  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:49:00.128  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:49:00.130  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:50:00.111  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:50:00.111  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:50:00.111  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:50:00.112  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:50:00.125  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:50:00.125  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:50:00.127  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:50:00.129  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:50:06.417  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:50:06.434  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1610e8f8 type 2 when 884950 com.google.android.gms} when 884950
,09-07 11:50:06.469  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:50:06.495  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:50:06.523  2184  2184 I ConfigService: onCreate
,09-07 11:50:06.527  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 11:50:06.529  1821  1821 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-07 11:50:06.547  1821  7063 I ConfigFetchService: running network task: configservice_periodic
,09-07 11:50:06.551  1821  7063 I ConfigFetchService: launchTask
09-07 11:50:06.552  2184  2184 I ConfigService: onBind returning update interface
09-07 11:50:06.553  1821  1821 I ConfigFetchService: service connected
09-07 11:50:06.554  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 11:50:06.554  2184  2184 I ConfigService: onBind returning config service
09-07 11:50:06.555  1821  1821 I ConfigClient: service connected
09-07 11:50:06.616  1037  1052 V SIM_STK : Menu title from STK is T-Mobile
,09-07 11:50:06.641  1821  6907 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 11:50:06.648   312  7080 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 11:50:06.649   312  7080 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 11:50:06.694   312  7080 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 11:50:06.972  1821  6907 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 11:50:06.979  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
09-07 11:50:06.982  1821  1821 I ConfigFetchService: stopping self
09-07 11:50:07.038  2184  2184 I ConfigService: onDestroy
,09-07 11:51:00.105  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:51:00.105  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:51:00.106  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:51:00.106  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:51:00.119  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:51:00.120  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:51:00.123  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:51:00.123  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:51:03.280  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:51:03.299  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2df2ee4b type 2 when 941813 com.android.bluetooth} when 941813
,09-07 11:51:03.306  3848  4066 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 11:51:03.306  3848  4066 W bt-smp  : Plain text(LSB ~ MSB) = 0f 3d 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 11:51:03.306  3848  4066 W bt-smp  : Encrypted text(LSB ~ MSB) = 2e e5 b2 1b 0f ba 34 2f c9 65 4e d8 58 b2 86 96 
09-07 11:51:03.306  3848  4066 W bt-btm  : Stopping oneshot timer
09-07 11:51:03.340  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:51:03.365  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:52:00.108  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:52:00.108  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:52:00.108  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 11:52:00.109  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:52:00.123  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:52:00.123  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:52:00.124  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:52:00.124  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:52:32.057  1606  1606 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 11:52:32.058  1606  1606 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 11:52:32.081  1606  1606 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
,09-07 11:52:32.084  1037  1547 D WifiController: battery changed pluggedType: 2
09-07 11:52:32.089  1944  2076 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 11:52:32.089  1944  2076 D LEDHandler: Battery Level Remaining: 100%
09-07 11:52:32.089  1944  2076 D LEDHandler: Battery Temp: 269, mChargingStatus=5, mChargingStop=false
09-07 11:52:32.090  1606  1606 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:52:32.091  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:52:32.091  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 11:52:32.092  3848  3975 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 11:52:32.093  1606  1606 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 11:52:32.098  6682  6682 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 11:52:33.210  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:52:33.223  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2e0c8028 type 2 when 980054 com.google.android.gms} when 980054
,09-07 11:52:33.261  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:52:33.287  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:52:33.309  2184  6176 D GCM     : Message class com.google.e.a.a.h
,09-07 11:53:00.076  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:53:00.077  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:53:00.077  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:53:00.077  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:53:00.092  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:53:00.092  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:53:00.093  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:53:00.093  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:54:00.109  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:54:00.109  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:54:00.109  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 11:54:00.110  1606  1606 I [SystemUI]Clock: called onTimeUpdated(),
,09-07 11:54:00.125  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:54:00.125  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:54:00.126  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:54:00.126  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:55:00.059  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 11:55:00.060  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:55:00.060  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 11:55:00.060  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
09-07 11:55:00.074  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:55:00.074  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:55:00.075  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:55:00.075  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:55:41.605  1037  1092 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 11:56:00.094  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:56:00.094  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:56:00.094  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:56:00.095  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:56:00.108  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:56:00.108  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:56:00.110  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:56:00.113  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:57:00.112  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:57:00.112  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:57:00.113  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:57:00.113  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:57:00.126  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 11:57:00.127  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:57:00.130  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:57:00.135  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 11:58:00.116  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:58:00.116  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 11:58:00.116  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:58:00.117  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:58:00.130  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:58:00.130  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:58:00.133  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:58:00.134  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 11:58:07.009  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 11:58:07.025  1037  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{314ef141 type 2 when 1365543 com.google.android.gms} when 1365543
09-07 11:58:07.059  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 11:58:07.085  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,09-07 11:58:07.113  1821  1821 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 11:58:07.117  2184  2184 I ConfigService: onCreate
09-07 11:58:07.118  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 11:58:07.125  1821  7105 I ConfigFetchService: running network task: configservice_periodic
,09-07 11:58:07.129  1821  7105 I ConfigFetchService: launchTask
09-07 11:58:07.129  2184  2184 I ConfigService: onBind returning update interface
09-07 11:58:07.131  1821  1821 I ConfigFetchService: service connected
09-07 11:58:07.131  2184  2184 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 11:58:07.131  2184  2184 I ConfigService: onBind returning config service
09-07 11:58:07.133  1821  1821 I ConfigClient: service connected
09-07 11:58:07.212  1037  1947 V SIM_STK : Menu title from STK is T-Mobile
,09-07 11:58:07.227  1821  2351 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 11:58:07.233   312  7125 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 11:58:07.233   312  7125 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 11:58:07.283   312  7125 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 11:58:07.563  1821  2351 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 11:58:07.566  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
09-07 11:58:07.567  1821  1821 I ConfigFetchService: stopping self
09-07 11:58:07.616  2184  2184 I ConfigService: onDestroy
,09-07 11:59:00.104  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 11:59:00.104  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 11:59:00.104  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 11:59:00.105  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 11:59:00.118  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,09-07 11:59:00.119  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 11:59:00.122  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 11:59:00.123  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:00:00.112  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:00:00.112  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 12:00:00.112  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
,09-07 12:00:00.113  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:00:00.130  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:00:00.130  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:00:00.134  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,09-07 12:00:00.136  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 12:00:01.107  1037  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=814698187, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,09-07 12:00:01.127  6999  6999 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,09-07 12:00:01.132  6999  6999 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1b015136
09-07 12:00:01.161  2581  2581 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:00:01.186  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=814698187 [*alarm*], flags=0x0
,TIME-OUT KILL (timeout was 1400000ms)
```
