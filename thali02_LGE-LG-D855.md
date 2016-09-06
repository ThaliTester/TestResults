#### Test 82914073d0f9b46_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-06 19:16:08.269  1041  1972 V SIM_STK : Menu title from STK is T-Mobile
--------- beginning of system
09-06 19:16:08.279  1041  2015 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6570 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:08.367  4607  6567 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 170 ms] updated apps [took 170 ms] 
09-06 19:16:08.554  6570  6570 D DocsApplication: Installing DEX configuration.
09-06 19:16:08.581  6570  6570 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-06 19:16:08.589  6570  6570 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1c7c3186 com.google.android.apps.docs}
09-06 19:16:08.609  6570  6570 D TAG     : onCreate()
09-06 19:16:08.646  6570  6570 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-06 19:16:08.928   326   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-06 19:16:08.931  3243  6597 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-06 19:16:09.378  1801  4784 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-06 19:16:09.465  1801  4784 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-06 19:16:09.510  1801  4784 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-06 19:16:09.537  6598  6598 D AndroidRuntime: 
09-06 19:16:09.537  6598  6598 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:16:09.541  6598  6598 D AndroidRuntime: CheckJNI is OFF
09-06 19:16:09.738  6598  6598 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 19:16:09.752  1041  1946 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 19:16:09.763  1923  1940 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-06 19:16:09.766  1041  1946 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-06 19:16:09.767  1041  1946 D ActivityManager: setTaskToReturnTo : TaskRecord{36aae742 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 19:16:09.768  1041  1946 D ActivityManager: setTaskToReturnTo : TaskRecord{36aae742 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 19:16:09.768  1041  1946 D WindowStateEx: AppWindowTokenEx init.. 
09-06 19:16:09.770   333   385 E GBMv2   : DFP En is all cleared set to be enabled
09-06 19:16:09.807  1041  1946 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6633 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:16:09.810  6598  6598 D AndroidRuntime: Shutting down VM
09-06 19:16:09.849  1923  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-06 19:16:09.850  1923  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{d5e97e2 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 19:16:09.851  1923  2543 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-06 19:16:09.851  1923  2543 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e59b773 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 19:16:09.884  6633  6633 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-06 19:16:09.968  6633  6633 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-06 19:16:09.976  6633  6633 I LibraryLoader: Loading: webviewchromium
09-06 19:16:09.978  6633  6633 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5377-5381)
09-06 19:16:09.979  6633  6633 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:16:10.004  6633  6633 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ce7d1e0}
09-06 19:16:10.005  6633  6633 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:16:10.005  6633  6633 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:16:10.023  6633  6633 I BrowserStartupController: Initializing chromium process, renderers=0
09-06 19:16:10.025  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:16:10.043  6633  6633 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-06 19:16:10.043   316  1368 V AudioPolicyService: registerClient() client 0xb57e1ec0, uid 10118
09-06 19:16:10.044  6633  6633 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-06 19:16:10.044  6633  6633 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-06 19:16:10.047  1041  1116 D BluetoothManagerService: Message: 20
09-06 19:16:10.047  1041  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25a979bc:true
09-06 19:16:10.058  6633  6633 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:16:10.058  6633  6633 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:16:10.058  6633  6633 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:16:10.058  6633  6633 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:16:10.058  6633  6633 I Adreno-EGL: Remote Branch: 
09-06 19:16:10.058  6633  6633 I Adreno-EGL: Local Patches: 
09-06 19:16:10.058  6633  6633 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:16:10.130  6633  6662 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-06 19:16:10.132  6633  6633 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-06 19:16:10.145  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:16:10.148  6633  6633 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:16:10.151  6633  6633 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-06 19:16:10.153  6633  6633 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-06 19:16:10.153  6633  6633 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-06 19:16:10.172  6633  6633 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-06 19:16:10.177  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:16:10.177  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:16:10.208  6633  6674 D OpenGLRenderer: Render dirty regions requested: true
09-06 19:16:10.208  6633  6674 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:16:10.214  6633  6674 D OpenGLRenderer: Enabling debug mode 0
,09-06 19:16:10.219  6633  6633 D Atlas   : Validating map...
09-06 19:16:10.222  1041  1936 D SplitWindow: check instance of lgWin Window{138eb716 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:16:10.256  6633  6672 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:10.256  6633  6672 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:10.289  6570  6570 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:10.290  6570  6570 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:10.337  1041  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +488ms (total +567ms)
09-06 19:16:10.337  1041  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3846c353 u0 com.test.thalitest/.MainActivity t6} time:105739
09-06 19:16:10.338  6633  6633 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36c4422f time:105741
,09-06 19:16:10.368  2772  2772 I MusicWidget: mDelayedStopHandler : unbind
09-06 19:16:10.369  2111  2111 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-06 19:16:10.369  2111  2111 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-06 19:16:10.369  2111  2111 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-06 19:16:10.371  2111  2111 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
,09-06 19:16:10.371  2111  2111 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-06 19:16:10.371  2111  2111 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-06 19:16:10.372  2111  2111 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-06 19:16:10.372  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-06 19:16:10.373  1041  1057 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2e70e09com.lge.music.MediaPlaybackService$5@69de80e
09-06 19:16:10.374  2111  2111 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-06 19:16:10.374  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.375  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.376  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.378  2111  2111 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3e282c0c
09-06 19:16:10.378  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.379  2111  2111 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-06 19:16:10.379  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.380  2111  2111 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-06 19:16:10.381  2111  2111 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-06 19:16:10.381  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.381  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.382  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.382  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 19:16:10.383  2111  2111 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-06 19:16:10.386  2111  2111 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-06 19:16:10.391  2111  2111 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-06 19:16:10.391  2111  2111 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-06 19:16:10.391  2111  2111 V MediaPlayer[Native]: reset
09-06 19:16:10.396  2111  2111 V MediaPlayer[Native]: setListener
09-06 19:16:10.396  2111  2111 V MediaPlayer[Native]: disconnect
09-06 19:16:10.396  2111  2111 V MediaPlayer[Native]: destructor
,09-06 19:16:10.396   316  2167 V AudioFlinger: releasing 18 from 2111 for -1
09-06 19:16:10.396   316  2167 V AudioFlinger:  decremented refcount to 0
09-06 19:16:10.396   316  2167 V AudioFlinger: purging stale effects
09-06 19:16:10.396  2111  2111 V MediaPlayer[Native]: disconnect
09-06 19:16:10.398  2111  2111 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,09-06 19:16:10.402  2111  2111 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-06 19:16:10.402  2111  2111 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-06 19:16:10.404  2111  2111 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-06 19:16:10.404  2111  2111 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-06 19:16:10.405  2111  2111 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-06 19:16:10.405  2111  2111 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 918831663
09-06 19:16:10.405  2111  2111 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 918831663
09-06 19:16:10.409  2111  2111 I SmartShareClient: [SmartShareManagerClient] terminate service: 2111/MediaPlaybackService/341434386
09-06 19:16:10.418  2111  2111 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-06 19:16:10.418  2111  2111 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3d14b03c
,09-06 19:16:10.420  2111  2111 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-06 19:16:10.421  2111  2111 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-06 19:16:10.421  2111  2111 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-06 19:16:10.422  2111  2111 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-06 19:16:10.424  1041  1909 I ActivityManager: Killing 5822:com.google.android.gm/u0a64 (adj 15): empty #17
09-06 19:16:10.425  2111  2111 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
09-06 19:16:10.448  6633  6633 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-06 19:16:10.448  6633  6633 I chromium: 
,09-06 19:16:10.456  6633  6633 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-06 19:16:10.489  1041  1978 W libprocessgroup: failed to open /acct/uid_10064/pid_5822/cgroup.procs: No such file or directory
,09-06 19:16:10.492  1041  1361 D PowerManagerServiceEx: acquireWakeLockInternal: lock=526456937, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1041
09-06 19:16:10.505  6117  6117 I LockScreenSettings: New app installed broadcast received ..
,09-06 19:16:10.509  6633  6672 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-06 19:16:10.509  6633  6672 I chromium: 
09-06 19:16:10.519  6117  6117 I LockScreenSettings: Number of installed packages  1
,09-06 19:16:10.525  6570  6570 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-06 19:16:10.525  2579  2579 D [Concierge]Service: onStartCommand(). Type : 9
09-06 19:16:10.581  1041  1909 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:16:10.605  6633  6702 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435040256
,09-06 19:16:10.614  6633  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:16:10.614  6633  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:16:10.614  6633  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:16:10.614  6633  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:16:10.614  6633  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 19:16:10.614  6633  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19033fc3 added. We now have 1 listener(s)
09-06 19:16:10.616  1041  1946 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6704 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:16:10.617  1041  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:10.619  6633  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,09-06 19:16:10.621  6633  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:10.622  6633  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:10.622  6633  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:16:10.627  6633  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b5a70be added. We now have 1 listener(s)
09-06 19:16:10.628  6633  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:10.630  1041  1527 D WifiService: New client listening to asynchronous messages
,09-06 19:16:10.633  6633  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:16:10.633  6633  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:16:10.634  6633  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:16:10.634  6633  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:16:10.634  6633  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-06 19:16:10.636  6633  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:10.637  1041  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:10.637  6633  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-06 19:16:10.645  6633  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:16:10.645  6633  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:10.645  6633  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:10.645  6633  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:10.645  6633  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:10.645  6633  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:10.645  6633  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:10.645  6633  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:10.645  6633  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:10.645  6633  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:16:10.645  6633  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:10.647  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:10.647  6633  6702 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:16:10.648  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:10.665  6704  6704 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-06 19:16:10.666  6704  6704 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-06 19:16:10.676  6633  6633 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-06 19:16:10.717  1041  1933 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6723 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 19:16:10.718  1041  1933 I ActivityManager: Killing 5867:com.google.android.talk/u0a72 (adj 15): empty #17
,09-06 19:16:10.810  1041  1909 W libprocessgroup: failed to open /acct/uid_10072/pid_5867/cgroup.procs: No such file or directory
,09-06 19:16:10.899  6723  6723 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-06 19:16:10.933  6723  6723 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:16:10.933  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,09-06 19:16:10.991  6442  6442 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-06 19:16:10.992  1041  2005 I ActivityManager: Killing 5664:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-06 19:16:11.009  5637  5637 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-06 19:16:11.009  5637  5637 W System.err: android.os.DeadObjectException
09-06 19:16:11.009  5637  5637 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,09-06 19:16:11.009  5637  5637 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:16:11.009  5637  5637 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 19:16:11.009  5637  5637 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 19:16:11.009  5637  5637 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:16:11.010  5637  5637 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:16:11.010  5637  5637 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:16:11.010  5637  5637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:16:11.010  5637  5637 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:16:11.010  5637  5637 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:16:11.010  5637  5637 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:11.010  5637  5637 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:11.010  5637  5637 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:16:11.010  5637  5637 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:16:11.010  5637  5637 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 19:16:11.010  5637  5637 W System.err: android.os.DeadObjectException
09-06 19:16:11.010  5637  5637 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:16:11.010  5637  5637 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:16:11.011  5637  5637 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 19:16:11.011  5637  5637 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 19:16:11.011  5637  5637 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:16:11.011  5637  5637 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:16:11.011  5637  5637 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:16:11.011  5637  5637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:16:11.011  5637  5637 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:16:11.011  5637  5637 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:16:11.011  5637  5637 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:11.011  5637  5637 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:11.011  5637  5637 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:16:11.011  5637  5637 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:16:11.011  5637  5637 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-06 19:16:11.011  5637  5637 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-06 19:16:11.029  4490  6745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-06 19:16:11.260  1041  1041 D PowerManagerServiceEx: releaseWakeLockInternal: lock=526456937 [*alarm*], flags=0x0
,09-06 19:16:11.264  1041  1562 W libprocessgroup: failed to open /acct/uid_1000/pid_5664/cgroup.procs: No such file or directory
09-06 19:16:11.265  1041  1562 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-06 19:16:11.276  5637  5637 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-06 19:16:11.276  5637  5637 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-06 19:16:11.326  1041  1889 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6753 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:16:11.326  5637  5637 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 19:16:11.406  6753  6753 D UEI.SmartControl: Quickset Services start...
,09-06 19:16:11.410  6753  6753 I UEI.SmartControl: Manufacture = LGE
09-06 19:16:11.411  6753  6753 D UEI.SmartControl: Id = LGNevo
09-06 19:16:11.412  6753  6753 D UEI.SmartControl: File observer start...
09-06 19:16:11.414  6753  6753 E UEI.SmartControl: IR Port is disabled: false
09-06 19:16:11.414  6753  6753 D UEI.SmartControl: Starting file observer...
09-06 19:16:11.415  6753  6753 D UEI.SmartControl: Extracting JNI libs...
09-06 19:16:11.415  6753  6753 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-06 19:16:11.470   333   387 E GBMv2   : DFP En is all cleared set to be enabled
09-06 19:16:11.470   333   387 E GBMv2   : Set value is all cleared set the max
09-06 19:16:11.470   333   387 I GBMv2   : DFP Enabled. Ignore VFP set
,09-06 19:16:11.472  6633  6722 W jxcore-log: Initializing JXcore engine
09-06 19:16:11.472  6633  6722 W jxcore-log: JXcore engine is ready
09-06 19:16:11.510  6753  6753 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-06 19:16:11.510  6753  6753 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-06 19:16:11.510  6753  6753 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-06 19:16:11.538  6753  6753 I UEI.SmartControl: --- Selecting new region: 6
,09-06 19:16:11.540  6753  6753 I UEI.SmartControl: Model = LG-D855
09-06 19:16:11.541  6753  6753 D UEI.SmartControl: QS Service created
09-06 19:16:11.551  6753  6753 I UEI.SmartControl: Service initServices...
,09-06 19:16:11.554  6753  6753 D UEI.SmartControl: QS start get config
09-06 19:16:11.559  6722  6722 W Thread-767: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8332]" dev="sockfs" ino=8332 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-06 19:16:11.559  6722  6722 W Thread-767: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-06 19:16:11.559  6722  6722 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8521]" dev="sockfs" ino=8521 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 19:16:11.559  6722  6722 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-06 19:16:11.559  6722  6722 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32827]" dev="sockfs" ino=32827 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-06 19:16:11.590  6753  6753 D UEI.SmartControl: Loading JNI Libs...
,09-06 19:16:11.598  6633  6722 W jxcore-log: Starting JXcore engine
09-06 19:16:11.711  6633  6722 W jxcore-log: Platform android
09-06 19:16:11.711  6633  6722 W jxcore-log: 
09-06 19:16:11.711  6633  6722 W jxcore-log: Process ARCH arm
09-06 19:16:11.711  6633  6722 W jxcore-log: 
,09-06 19:16:11.819  6753  6753 I UEI.SmartControl: Supports setup maps: true
09-06 19:16:11.823  6753  6753 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:16:11.823  6753  6753 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-06 19:16:11.823  6753  6753 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:16:11.823  6753  6753 I UEI.SmartControl: ### init IR Blaster...
,09-06 19:16:11.829  6753  6753 D serial_port: Configuring serial port
09-06 19:16:11.833  6753  6753 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:16:11.833  6753  6753 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:16:11.833  6753  6753 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:16:11.833  6753  6753 I UEI.SmartControl: Get version...
,09-06 19:16:11.848  6753  6777 D UEI.SmartControl: serial port data available: 21
,09-06 19:16:11.877  6753  6753 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:16:11.877  6753  6753 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:16:11.877  6753  6753 I UEI.SmartControl: QS saving settings...
,09-06 19:16:11.879  6753  6753 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:16:11.895  6753  6777 D UEI.SmartControl: serial port data available: 4
,09-06 19:16:11.929  6753  6783 I UEI.SmartControl: Device manager: loading config....
09-06 19:16:11.930  6753  6783 D UEI.SmartControl: ----------- loading internal config...
09-06 19:16:11.931  6753  6753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 19:16:11.937  6753  6753 E UEI.SmartControl: Services init done
09-06 19:16:11.937  6753  6753 D UEI.SmartControl: QS Service init finished
09-06 19:16:11.938  6753  6783 E UEI.SmartControl: Loading SETTINGS...
,09-06 19:16:11.944  6753  6753 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:16:11.945  6753  6753 D UEI.SmartControl: QS Service version code: 201091
09-06 19:16:11.945  6753  6753 D UEI.SmartControl: Service requested: Control
09-06 19:16:11.949  1041  1757 I ActivityManager: Killing 5637:com.lge.qremote/u0a112 (adj 15): empty #17
09-06 19:16:11.953  6753  6783 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-06 19:16:11.967  6753  6782 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:16:11.967  6753  6782 D UEI.SmartControl: -----service ready thread exits
09-06 19:16:12.005  6633  6722 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:16:12.005  6633  6722 I jxcore-log: 
,09-06 19:16:12.006  6633  6722 W jxcore-log: JXcore engine is started
,09-06 19:16:12.008  6753  6753 D UEI.SmartControl: Internal service binding...
09-06 19:16:12.009  1041  1946 W libprocessgroup: failed to open /acct/uid_10112/pid_5637/cgroup.procs: No such file or directory
09-06 19:16:12.019  6633  6702 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:16:12.025  6633  6633 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-06 19:16:14.393  6570  6570 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-06 19:16:14.404  1041  2005 I ActivityManager: Killing 6258:com.android.calendar/u0a13 (adj 15): empty #17
09-06 19:16:14.482  1041  1562 W libprocessgroup: failed to open /acct/uid_10013/pid_6258/cgroup.procs: No such file or directory
,09-06 19:16:15.384  6570  6681 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-06 19:16:16.914  6753  6781 D serial_port: close(fd = 25)
,09-06 19:16:16.921  6753  6781 I UEI.SmartControl: Serial port is closed.
09-06 19:16:16.937  6753  6784 D UEI.SmartControl: Internal timer expired: 1
09-06 19:16:16.937  6753  6784 D UEI.SmartControl: unbind internal service
,09-06 19:16:16.947  6753  6753 D UEI.SmartControl: Service.onUnbind: IControl
09-06 19:16:16.949  6753  6753 D UEI.SmartControl: Service.onDestroy
09-06 19:16:16.950  6753  6753 D UEI.SmartControl: Lock is in USE false
09-06 19:16:16.950  6753  6753 D UEI.SmartControl: unbind internal service
09-06 19:16:16.950  6753  6753 I UEI.SmartControl: Serial port is closed.
09-06 19:16:16.950  6753  6753 I UEI.SmartControl: Serial port is closed.
09-06 19:16:16.950  6753  6753 D UEI.SmartControl: Blaster closed
09-06 19:16:16.950  6753  6753 D UEI.SmartControl: Shut down QS...
09-06 19:16:16.951  6753  6753 D UEI.SmartControl: Stopping QS lib
09-06 19:16:16.951  6753  6753 D UEI.SmartControl: QS lib stop result = true
09-06 19:16:16.951  6753  6753 D UEI.SmartControl: Stopped QS lib
,09-06 19:16:16.958  6753  6753 D UEI.SmartControl: Stopped file observer...
09-06 19:16:16.958  6753  6753 D UEI.SmartControl: QS shutdown complete
09-06 19:16:17.443  1801  2355 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-06 19:16:17.449   310  6791 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-06 19:16:17.449   310  6791 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-06 19:16:17.449   310  6791 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-06 19:16:20.437  2111  2111 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
,09-06 19:16:21.761  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:16:21.761  6633  6722 I jxcore-log: 
,09-06 19:16:21.764  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:16:21.764  6633  6722 I jxcore-log: 
,09-06 19:16:21.769  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:21.769  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:21.769  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:21.769  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:21.769  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:21.769  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:21.769  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:21.769  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:21.772  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:21.775  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:16:21.775  6633  6722 I jxcore-log: 
,09-06 19:16:21.777  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:16:21.777  6633  6722 I jxcore-log: 
09-06 19:16:22.284  6633  6722 D executeNativeTests: Running unit tests
,09-06 19:16:22.366  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:22.366  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 added. We now have 2 listener(s)
09-06 19:16:22.367  1041  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:16:22.372  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:22.372  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:22.372  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:22.372  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:22.372  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 added. We now have 2 listener(s)
09-06 19:16:22.372  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:22.373  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:16:22.376  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.378  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:22.378  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:22.378  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:22.378  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:22.378  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:22.378  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.378  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:22.378  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:22.381  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.381  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:16:22.382  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.383  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.386  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:16:22.386  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:22.386  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:22.388  6633  6722 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 19:16:22.388  6633  6722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:16:22.389  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:22.389  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:22.389  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:22.389  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.390  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.390  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.390  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.391  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.391  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:22.391  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:22.391  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 removed from the list
09-06 19:16:22.391  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:16:22.391  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 removed from the list
09-06 19:16:22.391  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.391  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.393  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.393  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.394  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.394  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.394  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.394  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.396  6633  6722 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 19:16:22.396  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.396  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.396  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.396  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.396  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.396  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.396  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.396  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.396  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.396  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.396  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.396  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.396  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.396  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.397  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.397  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.397  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.397  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.401  6633  6722 D io.j,xcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19,:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:16:22.402  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:16:22.402  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.402  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.402  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.402  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.402  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.402  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.402  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
,09-06 19:16:22.403  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.403  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.403  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.403  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.403  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.403  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.403  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.404  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.404  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.404  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.404  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.405  6633  6722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:16:22.406  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.411  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:22.411  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:22.411  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:22.411  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:22.411  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:22.411  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.411  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:22.411  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:22.412  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.412  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:22.413  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:22.413  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:22.413  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.414  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.415  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:22.415  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.415  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:16:22.418  6633  6722 V org.thaliproject.p2p.btcon,nectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:22.418  1041  1756 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:22.422  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:16:22.426  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:16:22.427  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:16:22.428  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:16:22.428  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:22.429  6633  6722 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-06 19:16:22.430  6633  6722 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:16:22.432  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.432  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.432  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.432  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.432  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.432  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:22.432  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.432  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.432  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.432  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.432  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.433  6633  6722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:16:22.434  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.436  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:22.436  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:22.436  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:22.436  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:22.436  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:22.436  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.436  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:22.436  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:22.437  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.437  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:22.438  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:22.438  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:22.438  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:22.438  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.438  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:16:22.438  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConne,ctivityInfo: No relevant state changes
09-06 19:16:22.439  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.442  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:16:22.444  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:22.445  6633  6722 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:16:22.445  6633  6722 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:16:22.446  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.446  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.446  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.446  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.446  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.446  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:22.446  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.446  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.446  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.446  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.446  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.447  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.447  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.447  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.448  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.449  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.449  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.449  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.449  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.450  6633  6722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:16:22.452  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.454  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:22.454  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:22.454  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:22.454  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:22.454  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:22.454  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.454  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-,06 19:16:22.454  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:22.454  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.454  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:22.455  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.456  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.457  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:22.457  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:22.457  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:22.457  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.457  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:16:22.459  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:16:22.460  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:22.460  6633  6722 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:16:22.461  6633  6722 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:16:22.461  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.461  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.461  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.461  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.461  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.461  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.462  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.462  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.462  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:22.462  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.462  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.462  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.462  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.463  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.463  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.463  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.463  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.463  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.464  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.464  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.464  6633  6722 I org.thaliproject.p2p.btcon,nectorlib.DiscoveryManager: dispose
09-06 19:16:22.464  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.464  6633  6722 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:16:22.465  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.465  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.465  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.465  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.465  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.465  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.465  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.465  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.465  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.465  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.465  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.465  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.465  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.465  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.466  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.466  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:16:22.466  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.466  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.466  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.466  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.467  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:16:22.467  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.467  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.467  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.468  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.468  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.468  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.468  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.468  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.468  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.468  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.468  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.468  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.468  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.468  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.468  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.468  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.469  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.469  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.469  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.469  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.469  6633  6722 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 19:16:22.470  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.470  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.470  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already mat,ches the desired outcome of this operation, skipping...
09-06 19:16:22.470  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.470  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.470  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.470  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.470  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.470  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.470  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.470  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.470  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.470  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.470  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.471  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.471  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.471  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.471  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.471  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.471  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.472  6633  6722 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:16:22.472  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.472  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.472  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.472  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.472  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.472  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.472  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.472  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.472  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.472  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.472  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.472  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.472  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.472  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.473  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.473  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.475  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.475  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.475  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.475  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.475  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:16:22.475  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:22.475  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:22.475  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:22.475  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:16:22.475  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:16:22.476  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.476  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.476  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.476  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.476  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.476  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.476  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.476  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.476  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.476  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.476  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.476  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.476  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.476  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.477  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.477  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.477  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.477  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.477  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.477  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.478  6633  6722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:22.478  6633  6722 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:16:22.478  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:16:22.479  6633  6722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:22.480  6633  6722 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:16:22.480  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:16:22.480  6633  6722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:16:22.480  6633  6722 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:22.480  6633  6722 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:16:22.481  6633  6722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:22.481  6633  6722 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:22.481  6633  6722 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:16:22.481  6633  6722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:22.481  6633  6722 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:16:22.481  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:16:22.484  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:16:22.485  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:16:22.485  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:16:22.485  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:16:22.485  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:16:22.486  6633  6722 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:16:22.486  6633  6722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:16:22.486  6633  6722 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:16:22.486  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.486  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.486  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.486  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.486  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.486  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.486  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:16:22.486  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.486  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.487  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.487  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.487  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.487  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.487  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.487  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.487  6633  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
09-06 19:16:22.488  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.488  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.488  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.488  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.488  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.488  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.489  6633  6722 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:16:22.489  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.489  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.489  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.490  6633  6797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
09-06 19:16:22.490  6633  6797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 831)
09-06 19:16:22.490  6633  6797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 831)
09-06 19:16:22.490  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.490  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.490  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.490  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.490  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.490  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.490  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.490  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.490  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.490  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.490  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.491  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.491  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.491  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.491  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.491  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.491  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.492  6633  6722 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:16:22.492  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.492  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.492  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.493  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.493  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.493  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.493  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.493  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.493  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.493  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.493  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.493  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.493  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.493  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.494  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.494  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.495  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.495  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.495  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.495  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.496  6633  6722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:16:22.496  6633  6722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:16:22.496  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:22.496  6633  6722 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:16:22.496  6633  6722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:16:22.496  6633  6722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:16:22.496  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:16:22.496  6633  6722 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:16:22.496  6633  6722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:16:22.496  6633  6722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:16:22.496  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:16:22.496  6633  6722 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:16:22.496  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:16:22.496  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.496  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.497  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.497  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.497  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.497  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.497  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.497  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.497  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.497  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.497  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.497  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.497  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.498  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.498  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.498  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.498  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.498  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.498  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.499  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.499  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.499  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.499  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.499  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.499  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.499  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.499  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.499  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.499  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.499  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.499  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.499  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.499  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.499  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.499  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.499  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.499  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.500  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.500  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.500  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.500  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.500  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.500  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.500  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.500  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.500  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.500  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.500  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.501  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.501  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.501  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.501  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.501  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.501  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.502  6633  6722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:16:22.503  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.503  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:16:22.504  6633  6722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:16:22.504  6633  6722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:16:22.504  6633  6633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:16:22.504  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:16:22.504  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:16:22.509  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.509  1041  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:22.509  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:16:22.509  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:16:22.509  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:16:22.509  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.509  6633  6722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:16:22.509  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.509  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.509  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:16:22.509  6633  6722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:16:22.510  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:16:22.510  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:16:22.510  6633  6633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:16:22.510  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:22.510  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:22.510  6633  6722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:16:22.511  6633  6799 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:22.511  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.511  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.512  3852  4159 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-06 19:16:22.512  6633  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-06 19:16:22.512  6633  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:16:22.512  6633  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:16:22.513  6633  6722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:22.513  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:22.513  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:16:22.514  6633  6633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:16:22.514  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:16:22.514  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.514  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.514  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.514  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.514  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.514  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.514  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.514  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.514  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.514  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.514  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.514  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.514  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.514  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.514  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.515  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.515  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.515  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.515  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.516  6633  6722 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:16:22.516  6633  6722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:16:22.516  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:16:22.516  6633  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:16:22.517  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.517  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.517  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.517  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.517  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.517  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.517  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.517  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.517  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.517  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.517  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.517  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.517  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.517  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.518  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.518  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.518  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.518  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.519  1041  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:22.520  1041  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:22.521  1041  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:22.522  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.522  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.522  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.522  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.522  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.522  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.522  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.522  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.522  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.522  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.522  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.522  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.522  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.522  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.523  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.523  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.523  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.523  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.524  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:22.524  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:22.524  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:22.524  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:22.524  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.524  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.524  6633  6722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a1fd3 not in the list
09-06 19:16:22.524  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.524  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.524  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:22.524  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.524  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.524  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:22.524  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:22.525  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:22.525  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:22.525  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:22.525  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33340710 not in the list
09-06 19:16:22.526  6633  6722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:16:22.526  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:22.526  6633  6722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:16:22.526  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:16:22.526  6633  6722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:16:22.526  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:16:22.528  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:16:22.528  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:16:22.528  6633  6722 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:16:22.528  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:16:22.528  6633  6722 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:16:22.528  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:16:22.529  6633  6722 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:16:22.529  6633  6722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:16:22.529  6633  6722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:16:22.530  6633  6722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:16:22.530  6633  6722 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:16:22.530  6633  6722 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:16:22.531  6633  6722 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:16:22.531  6633  6722 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:16:22.534  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:22.534  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b08f941 added. We now have 2 listener(s)
09-06 19:16:22.534  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:22.536  6633  6722 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 19:16:22.537  1041  1972 D WifiServiceImplEx: setWifiEnabled: true pid=6633, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:16:22.538  1041  1972 D WifiService: setWifiEnabled: true pid=6633, uid=10118
09-06 19:16:22.538  1041  1972 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:16:22.539  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:22.539  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@180a1ee6 added. We now have 3 listener(s)
09-06 19:16:22.539  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:22.541  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:22.541  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d9d6c27 added. We now have 4 listener(s)
09-06 19:16:22.542  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:22.543  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:22.543  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20251ed4 added. We now have 5 listener(s)
09-06 19:16:22.543  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:22.545  1041  1972 D WifiServiceImplEx: setWifiEnabled: false pid=6633, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:16:22.545  1041  1972 D WifiService: setWifiEnabled: false pid=6633, uid=10118
09-06 19:16:22.545  1041  1972 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:16:22.562  6633  6796 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-06 19:16:22.562  6633  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
09-06 19:16:22.564  1041  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:22.564  1041  1889 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@521be80 mBinding = false
09-06 19:16:22.564  1041  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:22.565  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:16:22.565  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:22.565  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:16:22.565  1041  1041 D Ulp_jni : JNI:system_update. Event-4
09-06 19:16:22.565  1041  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:22.565  1041  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:22.566  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:22.566  1041  1097 I ActivityManager: Waited long enough for: ServiceRecord{1b4b998a u0 com.google.android.gms/.wearable.service.WearableService}
09-06 19:16:22.566  1041  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:16:22.566  1041  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:16:22.566  1041  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:16:22.567  1041  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:16:22.567  1041  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:16:22.577  1041  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:16:22.577  1041  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.577  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.578  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:16:22.578  2716  2716 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:16:22.579  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:16:22.579  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:16:22.579  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:16:22.579  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:16:22.579  1041  1041 D Ulp_jni : JNI:system_update. Event-4
09-06 19:16:22.580  1041  1116 D BluetoothManagerService: Message: 2
09-06 19:16:22.580  1041  1116 D BluetoothManagerService: Sending off request.
09-06 19:16:22.580  1041  1522 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:16:22.581  1041  2849 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.581  3852  3869 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 19:16:22.581  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:22.581  3852  3924 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 19:16:22.581  3852  3924 D BluetoothAdapterProperties: Setting state to 13
09-06 19:16:22.581  3852  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:16:22.581  1041  1116 D BluetoothManagerService: Message: 60
09-06 19:16:22.581  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 19:16:22.581  1041  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 19:16:22.582  3852  3924 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:16:22.582  3852  3924 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:16:22.583  3852  3852 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:22.584  3852  3852 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:16:22.584  3852  3852 V BluetoothMapService: Handler(): got msg=4
09-06 19:16:22.584  3852  3852 D BluetoothMapService: MAP Service closeService in
09-06 19:16:22.584  3852  3852 D BluetoothMapMasInstance: MAP Service shutdown
09-06 19:16:22.584  3852  4160 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 19:16:22.584  3852  4160 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:22.584  3852  4160 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 19:16:22.584  3852  4160 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 19:16:22.584  3852  4160 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 19:16:22.584  3852  4160 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 19:16:22.584  3852  4160 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 19:16:22.584  3852  4160 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 19:16:22.585  3852  3852 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:16:22.585  3852  3852 V BluetoothMapService: MAP Service closeService out
09-06 19:16:22.585  3852  3852 V BtOppService: Receiver DISABLED_ACTION 
09-06 19:16:22.585  3852  3852 I BtOppRfcommListener: stopping Accept Thread
09-06 19:16:22.585  3852  3852 V BtOppRfcommListener: close mBtServerSocket
09-06 19:16:22.585  3852  3852 V BtOppRfcommListener: waiting for thread to terminate
09-06 19:16:22.585  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:16:22.585  3852  4186 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:22.586  3852  4186 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:16:22.586  1923  1923 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:22.586  3852  3852 V BtOppRfcommListener: done waiting for thread to terminate
09-06 19:16:22.587  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:22.587  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:22.587  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:22.587  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:22.587  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:22.587  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:22.587  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.587  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:22.587  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:22.588  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:22.589  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:16:22.591  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:22.593  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.594  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.594   310   896 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:22.598  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:22.598  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:22.598  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:22.598  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:22.598  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:22.598  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:22.598  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.598  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:22.598  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:22.599  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:22.599  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:22.600  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:22.622  1041  1097 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6803 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:16:22.624  3852  3928 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:16:22.624  3852  3924 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:16:22.624  3852  3924 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:16:22.625  3852  4161 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:22.625  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 19:16:22.625  3852  3995 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 19:16:22.626  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 19:16:22.626  3852  3995 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:16:22.627  3852  4188 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:22.627  3852  4201 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:22.628  3852  3852 V BtOppService: onDestroy
09-06 19:16:22.630  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.631  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:22.634  1041  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:16:22.635  1041  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-06 19:16:22.667  1041  1097 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6822 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-06 19:16:22.668  1041  1528 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 19:16:22.668  1041  1528 D DSQN    : disableDataServiceNotify
09-06 19:16:22.668  1041  1528 D DSQN    : stop dsqn bin
09-06 19:16:22.669  1041  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.669  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.669  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.669  1041  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:16:22.670  1041  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.670  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.670  1041  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3a23e97e
09-06 19:16:22.670  1041  1521 D LGWifiP2pService: P2pDisablingState
09-06 19:16:22.670  1041  1521 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.670  1041  1521 D LGWifiP2pService: p2p socket connection lost
09-06 19:16:22.670  1041  1521 D LGWifiP2pService: P2pDisabledState
09-06 19:16:22.672  1041  1041 D WifiHS20: hidePasspointNotification off =false
,09-06 19:16:22.673  1923  1923 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 19:16:22.676   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 222us total 11.030ms
09-06 19:16:22.677  1041  1528 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 19:16:22.677  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:22.677  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:22.677  1041  1528 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:22.678  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:22.678  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:22.678  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:16:22.679  1041  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.680  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.680  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.681  1041  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.681  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.682  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:22.682  1041  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 19:16:22.687   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.840ms
,09-06 19:16:22.688  1585  2028 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:16:22.690  1041  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.690  1041  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.690  1041  2848 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:16:22.690  1041  1528 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 19:16:22.691  1041  1521 D LGWifiP2pService: P2pDisabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.691  1041  1521 D LGWifiP2pService: DefaultState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.691  1041  1528 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 19:16:22.691  1041  1528 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 19:16:22.691  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:16:22.691  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 19:16:22.691  2716  2716 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:16:22.691  1041  1041 D WifiHS20: hidePasspointNotification off =false
09-06 19:16:22.692  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:22.692  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:22.692  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:16:22.692  1041  1041 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:16:22.692  1041  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.692  1041  1041 D RttService: SCAN_AVAILABLE : 1
09-06 19:16:22.693  1041  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:22.694  1041  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:22.694  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:16:22.694  1041  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:22.694  1041  1528 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:22.694  1041  1528 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:22.695  1041  1528 D NetworkManagementService: Removing idletimer
09-06 19:16:22.695  1041  1528 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:22.695  1041  1528 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 19:16:22.696   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.955ms
09-06 19:16:22.697  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:16:22.697  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:16:22.697  1041  1522 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:16:22.698   310   896 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:22.699  1041  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:16:22.699  1041  1041 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:16:22.700  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:16:22.700  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:16:22.700  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:16:22.700  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:16:22.702  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:22.702  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:16:22.703  1041  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:16:22.703  1041  1041 D LocSvc_java: Sending msg: 4 arg1:0, arg2:1
09-06 19:16:22.703  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:16:22.703  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:16:22.703  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:16:22.703  1923  1923 D WfdsService: WifiP2pState is changed : false
09-06 19:16:22.704  1923  2324 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 19:16:22.704  1923  2324 D WfdsService: Set the WFDS Monitor: false
09-06 19:16:22.706  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:22.706  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:22.707  1923  2324 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:16:22.707  1923  2324 D WfdsService: STATE : WfdsDisabledState - enter
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: exception on config fetch: java.net.ConnectException: failed to connect to cloudconfig.googleapis.com/64.233.167.95 (port 443) after 120000ms: connect failed: ENETUNREACH (Network is unreachable)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: java.net.ConnectException: failed to connect to cloudconfig.googleapis.com/64.233.167.95 (port 443) after 120000ms: connect failed: ENETUNREACH (Network is unreachable)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at libcore.io.IoBridge.connect(IoBridge.java:124)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at java.net.Socket.connect(Socket.java:882)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.android.okhttp.Connection.connect(Connection.java:148)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:276)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	,at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:323)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponseCode(HttpURLConnectionImpl.java:491)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getResponseCode(DelegatingHttpsURLConnection.java:105)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getResponseCode(HttpsURLConnectionImpl.java:25)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.google.android.gms.config.f.a(SourceFile:120)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at com.google.android.gms.config.f.doInBackground(SourceFile:39)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at libcore.io.Posix.connect(Native Method)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-06 19:16:22.707  1801  2355 W ConfigFetchTask: 	... 20 more
,09-06 19:16:22.707  1923  2750 D CtrlSupplicant: Received on exit socket, terminate
09-06 19:16:22.707  1923  2750 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 19:16:22.707  1923  2750 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 19:16:22.707  1923  2750 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 19:16:22.707  1923  2325 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 19:16:22.708  1923  2324 W WfdsService: DefaultState - msg [9445378] is not handled
,09-06 19:16:22.708  1041  1522 D WifiNative-p2p0: doBoolean: TERMINATE
,09-06 19:16:22.711  1041  1041 D WifiHS20: hidePasspointNotification off =false
09-06 19:16:22.711  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:22.711  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:22.711  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:16:22.713  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:22.714  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:22.714  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:22.716  1041  1522 D WifiNative-p2p0: TERMINATE: returned true
09-06 19:16:22.716  1041  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:16:22.716  1041  1522 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:16:22.716  1041  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:16:22.718  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 19:16:22.718  1041  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:22.719  1041  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:22.720  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 19:16:22.720  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:16:22.724  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:22.724  1041  1041 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 19:16:22.726  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:22.726  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:22.726  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:22.726  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:22.726  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:22.726  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:22.726  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:22.726  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:22.726  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:22.726  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:22.726  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:22.728  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:22.728  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:22.728  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:22.728  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:22.728  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:22.728  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:22.728  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:22.728  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:22.728  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:22.729  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:22.729  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:22.756  1041  1909 I art     : Explicit concurrent mark sweep GC freed 38436(1890KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.603ms total 146.892ms
,09-06 19:16:22.760  3852  3852 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 19:16:22.766  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
09-06 19:16:22.767  1801  1801 I ConfigFetchService: stopping self
,09-06 19:16:22.776  2168  2168 I ConfigService: onDestroy
,09-06 19:16:22.784  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:16:22.784  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:22.784  6803  6803 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:22.785  6803  6803 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-06 19:16:22.785  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:22.785  6803  6803 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:16:22.785  6803  6803 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-06 19:16:22.786  6803  6803 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:16:22.787  6803  6803 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 19:16:22.801  1041  2849 D DhcpStateMachine: StoppedState
09-06 19:16:22.801  1041  2849 D DhcpStateMachine: StoppedState{ when=-103ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:22.801  1041  1522 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 19:16:22.802  1041  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 19:16:22.805  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:16:22.806  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:22.806  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:22.806  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:16:22.806  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:22.807  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:22.808  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:22.818  2716  2716 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:16:22.818  2716  2716 I wpa_supplicant: monitor socket send errors count : 1
09-06 19:16:22.818  2716  2716 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1923-2\x00 that cannot receive messages
,09-06 19:16:22.819  1041  2749 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 19:16:22.819  1041  2749 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:16:22.827  6822  6822 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 19:16:22.828  6822  6822 W LG Account v2.2: No ProfileInfo entries
09-06 19:16:22.828  6822  6822 I LG Account v2.2: isEnabled: false
09-06 19:16:22.828  6822  6822 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 19:16:22.828  6822  6822 I Feature : [Lifetracker]Country: EU
09-06 19:16:22.828  6822  6822 I Feature : [Lifetracker]Operator: OPEN
09-06 19:16:22.828  6822  6822 I Feature : [Lifetracker]Ranking support: false
09-06 19:16:22.828  6822  6822 I Feature : [Lifetracker]Comfort support: false
09-06 19:16:22.828  6822  6822 I Feature : [Lifetracker]Accessory: true
09-06 19:16:22.828  6822  6822 I Feature : [Lifetracker]Health device: true
09-06 19:16:22.829  6822  6822 I Feature : [Lifetracker]Extra Pedometer: false
09-06 19:16:22.829  6822  6822 I Feature : [Lifetracker]Blood glucose device: false
09-06 19:16:22.829  6822  6822 I Feature : [Lifetracker]Device Number: 3
09-06 19:16:22.835  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:22.843  2716  2716 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:16:22.843  1041  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 19:16:22.843  1041  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:16:22.843  1041  2749 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:16:22.843  1041  2749 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 19:16:22.844  2716  2716 W wpa_supplicant: USIM:  scard_deinit function
09-06 19:16:22.844  1041  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118231
09-06 19:16:22.845  1041  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118232
09-06 19:16:22.845  1041  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:22.845  1041  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:22.845  1041  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118232  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:16:22.845  1041  1116 D Tethering: InitialState.processMessage what=4
09-06 19:16:22.846  1041  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118232  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:16:22.865  1041  1936 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6850 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:16:22.866  1041  1936 I ActivityManager: Killing 6208:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-06 19:16:22.900  2716  2716 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:16:22.900  1041  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 19:16:22.901  1041  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
,09-06 19:16:22.901  1041  2749 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 19:16:22.901  1041  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-06 19:16:22.909  1041  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:16:22.916  1041  1933 W libprocessgroup: failed to open /acct/uid_10014/pid_6208/cgroup.procs: No such file or directory
,09-06 19:16:22.965  6850  6850 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-06 19:16:22.971  6850  6850 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:16:22.971  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:22.973  1041  1756 I ActivityManager: Killing 6315:com.android.defcontainer/u0a4 (adj 15): empty #17
09-06 19:16:22.997  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 19:16:23.010  1041  1909 W libprocessgroup: failed to open /acct/uid_10004/pid_6315/cgroup.procs: No such file or directory
,09-06 19:16:23.014  1041  1522 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 19:16:23.014  1041  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:16:23.014  1041  1522 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:16:23.014  1041  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:16:23.014  6633  6633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:16:23.016  1923  1923 D WfdsService: Supplicant Connection state is changed : false
09-06 19:16:23.016  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:16:23.016  1923  2324 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 19:16:23.016  1923  2324 D WfdsService: Set the WFDS Monitor: false
09-06 19:16:23.016  1923  2324 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:16:23.017  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 19:16:23.018  1041  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 19:16:23.018  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:23.018  1041  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 19:16:23.020  2484  2484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:23.020  3852  3852 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:16:23.020  3852  3852 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.021  3852  3852 V BluetoothPbapReceiver: ***********state = 13
09-06 19:16:23.022  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:23.023  3852  3852 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 19:16:23.024  3852  3852 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.024  3852  3852 V BluetoothPbapService: state: 13
09-06 19:16:23.024  3852  3852 V BluetoothPbapService: Pbap Service closeService in
09-06 19:16:23.028  3852  3852 V BluetoothPbapService: successfully stopped pbap service
09-06 19:16:23.028  3852  3852 V BluetoothPbapService: Pbap Service closeService out
09-06 19:16:23.029  3852  3852 V BluetoothPbapService: Pbap Service onDestroy
09-06 19:16:23.029  3852  3852 V BluetoothPbapService: Pbap Service closeService in
09-06 19:16:23.029  3852  3852 V BluetoothPbapService: Pbap Service closeService out
,09-06 19:16:23.029  3852  3852 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 19:16:23.029  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:23.032  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:16:23.032  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:23.066  6803  6803 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:23.067  6803  6803 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:23.074  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:23.081  1041  1116 D BluetoothManagerService: Message: 20
09-06 19:16:23.081  1041  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2daee70a:true
,09-06 19:16:23.090  1041  1116 D BluetoothManagerService: Message: 30
,09-06 19:16:23.095  1041  1116 D BluetoothManagerService: Message: 30
,09-06 19:16:23.097  6803  6803 D LocalBluetoothProfileManager: Adding local MAP profile
,09-06 19:16:23.098  6803  6803 D BluetoothMap: Create BluetoothMap proxy object
09-06 19:16:23.099  1041  1116 D BluetoothManagerService: Message: 30
09-06 19:16:23.103  1041  1116 D BluetoothManagerService: Message: 30
09-06 19:16:23.105  6803  6803 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-06 19:16:23.106  6803  6803 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-06 19:16:23.119  6803  6803 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-06 19:16:23.126  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-06 19:16:23.142  6803  6803 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:23.160  6803  6803 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 19:16:23.168  6803  6803 D BluetoothInputDevice: Proxy object connected
09-06 19:16:23.170  6803  6803 D HidProfile: Bluetooth service connected
09-06 19:16:23.172  6803  6803 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:16:23.174  6803  6803 D PanProfile: Bluetooth service connected
,09-06 19:16:23.176  6803  6803 D BluetoothMap: Proxy object connected
09-06 19:16:23.178  6803  6803 D MapProfile: Bluetooth service connected
09-06 19:16:23.178  6803  6803 D BluetoothMap: getConnectedDevices()
09-06 19:16:23.180  6803  6803 D BluetoothMap: Bluetooth is Not enabled
09-06 19:16:23.181  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:16:23.185  6803  6803 D BluetoothPermissionRequest: onReceive
,09-06 19:16:23.191  6803  6803 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 19:16:23.202  1041  2034 I ActivityManager: Killing 6495:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-06 19:16:23.206  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:16:23.217  1041  1522 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:23.218  1041  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-06 19:16:23.304  3852  3852 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-06 19:16:23.304  3852  3852 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-06 19:16:23.306  1041  1756 W libprocessgroup: failed to open /acct/uid_10008/pid_6495/cgroup.procs: No such file or directory
09-06 19:16:23.307  3852  3852 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-06 19:16:23.401  1041  2005 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6884 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-06 19:16:23.406  3852  3852 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.407  3852  3852 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:16:23.410  3852  3852 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:16:23.411  3852  3852 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.411  3852  3852 V BluetoothFtpService: Ftp Service closeService
09-06 19:16:23.411  3852  3852 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 19:16:23.412  3852  3852 V BluetoothFtpService: successfully stopped ftp service
09-06 19:16:23.413  3852  3852 V BluetoothFtpService: Ftp Service onDestroy
09-06 19:16:23.413  3852  3852 V BluetoothFtpService: Ftp Service closeService
09-06 19:16:23.415  3852  3852 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:16:23.415  3852  3852 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:16:23.415  3852  3852 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:16:23.416  3852  3852 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.416  3852  3852 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 19:16:23.416  3852  3852 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-06 19:16:23.418  3852  3852 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:23.418  3852  3852 V BluetoothSapService: state: 13
09-06 19:16:23.419  3852  3852 V BluetoothSapService: Stopping SAP server process
09-06 19:16:23.420  3852  3852 V BluetoothSapService: Sap Service closeSapService in
09-06 19:16:23.420  3852  3852 V BluetoothSapService: Close listen Socket : 
09-06 19:16:23.421  3852  3852 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:16:23.421  3852  3852 V BluetoothSapService: Close sapd  Socket : 
09-06 19:16:23.422  3852  3852 V BluetoothSapService: Sap Service closeSapService out
09-06 19:16:23.423  3852  3852 V BluetoothSapService: Sap Service onDestroy
09-06 19:16:23.423  3852  3852 V BluetoothSapService: Sap Service closeSapService in
09-06 19:16:23.423  3852  3852 V BluetoothSapService: Close listen Socket : 
09-06 19:16:23.423  3852  3852 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:16:23.423  3852  3852 V BluetoothSapService: Close sapd  Socket : 
09-06 19:16:23.423  3852  3852 V BluetoothSapService: Sap Service closeSapService out
09-06 19:16:23.463  1041  2005 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6901 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:16:23.518  6884  6884 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:16:23.530  6901  6901 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:16:23.542  6884  6884 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-06 19:16:23.549  1041  1909 I ActivityManager: Killing 6008:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-06 19:16:23.576  6884  6884 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-06 19:16:23.576  6884  6884 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 19:16:23.576  6884  6884 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 19:16:23.577  6884  6884 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 19:16:23.578  6884  6884 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 19:16:23.579  6884  6884 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 19:16:23.585  6884  6884 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-06 19:16:23.599  1041  1756 W libprocessgroup: failed to open /acct/uid_10011/pid_6008/cgroup.procs: No such file or directory
,09-06 19:16:23.610  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:23.615  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:23.629  3852  3928 D bt_hci_bdroid: cleanup
,09-06 19:16:23.629  3852  3995 W bt-btif : ag scb idx 1 not allocated
09-06 19:16:23.629  3852  3995 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:23.629  3852  3997 I bt_lpm  : LPM is already off!!!
,09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:23.629  3852  4127 I bt_userial_mct: exiting userial_read_thread
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:23.629  3852  4127 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:23.629  3852  3928 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:23.629  3852  3997 I bt_vendor: hw_epilog_process
09-06 19:16:23.629  3852  3995 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:23.630  3852  3995 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:23.630  3852  3995 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:23.630  3852  3995 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:16:23.630  3852  3928 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 19:16:23.630  3852  3928 D bt_userial_mct: userial_close
09-06 19:16:23.630  3852  3928 E bt_userial_mct: pthread_join() FAILED result:3
09-06 19:16:23.630  3852  3928 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:16:23.640  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:16:23.646  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:23.647  6884  6884 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-06 19:16:23.652  6884  6884 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-06 19:16:23.652  6850  6850 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:16:23.652  6850  6850 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:16:23.652  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:23.660  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:23.668  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:23.677  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:23.677  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:23.679  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:16:23.683  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:23.690  6850  6850 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:16:23.690  6850  6850 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:16:23.690  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:16:23.693  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:16:23.698  3852  3928 D bt_hci_bdroid: set_power 0
09-06 19:16:23.698  3852  3928 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:16:23.698  3852  3928 I bt_vendor: bluetooth satus is on
09-06 19:16:23.698  3852  3928 I bt_vendor: bt-vendor : resetting BT status
09-06 19:16:23.698  3852  3928 I bt_vendor: Starting hciattach daemon
09-06 19:16:23.698  3852  3928 I bt_vendor: try to set false
09-06 19:16:23.699  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:23.699  3852  3928 I bt_vendor: Starting hciattach daemon
09-06 19:16:23.700  3852  3928 I bt_vendor: try to set false
09-06 19:16:23.700  3852  3928 I bt_vendor: cleanup
09-06 19:16:23.701  3852  3995 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:16:23.701  3852  3928 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:16:23.701  3852  3928 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-06 19:16:23.704  3852  3924 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:16:23.710  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:23.710  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:23.712  3852  3852 D HeadsetService: Received stop request...Stopping profile...
09-06 19:16:23.714  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:16:23.714  3852  3852 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:16:23.714  3852  3852 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:16:23.714  3852  3852 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e6cc99
09-06 19:16:23.714  3852  3958 D HeadsetStateMachine: Exit Disconnected: -1
,09-06 19:16:23.718  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:16:23.718  1836  1836 D BluetoothHeadset: Proxy object disconnected
,09-06 19:16:23.718  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:16:23.719  1041  1041 D BluetoothHeadset: Proxy object disconnected
09-06 19:16:23.719  1041  1041 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:16:23.719  3852  3852 D A2dpService: Received stop request...Stopping profile...
09-06 19:16:23.720  3852  3980 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:16:23.721  3852  3852 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 19:16:23.785  1041  2034 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6934 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-06 19:16:23.790  3852  3852 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 19:16:23.790  3852  3852 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:16:23.790  3852  3852 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e6cc99
09-06 19:16:23.792  1041  1041 D BluetoothA2dp: Proxy object disconnected
,09-06 19:16:23.792  1041  1041 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:16:23.792  3852  3852 D HidService: Received stop request...Stopping profile...
09-06 19:16:23.792  3852  3852 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e6cc99
09-06 19:16:23.792  3852  3924 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:16:23.794  6803  6803 D BluetoothInputDevice: Proxy object disconnected
09-06 19:16:23.794  3852  3852 D HeadsetStateMachine: Unbinding service...
09-06 19:16:23.794  6803  6803 D HidProfile: Bluetooth service disconnected
09-06 19:16:23.795  3852  3852 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:16:23.795  3852  3852 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:16:23.795  3852  3852 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:16:23.795  3852  3852 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:16:23.795  3852  3852 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:16:23.795  3852  3852 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:16:23.795  3852  3852 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:16:23.796  3852  3852 D HealthService: Received stop request...Stopping profile...
09-06 19:16:23.796  3852  3852 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e6cc99
09-06 19:16:23.798  3852  3852 D PanService: Received stop request...Stopping profile...
09-06 19:16:23.799  3852  3852 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e6cc99
,09-06 19:16:23.801  3852  3852 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:16:23.801  3852  3852 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:16:23.802  3852  3852 D BtGatt.GattService: stop()
09-06 19:16:23.802  3852  3852 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:16:23.804  3852  3852 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e6cc99
09-06 19:16:23.805  3852  3852 I BluetoothA2dpServiceJni: cleanupNative
09-06 19:16:23.806  3852  3981 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:16:23.806  3852  3852 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:16:23.806  3852  3852 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:16:23.807  3852  3852 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:16:23.807  3852  3852 D BluetoothMapService: stop()
09-06 19:16:23.808  3852  3852 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 19:16:23.808  6803  6803 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:16:23.808  6803  6803 D PanProfile: Bluetooth service disconnected
09-06 19:16:23.808  3852  3852 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 19:16:23.809  3852  3852 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e6cc99
09-06 19:16:23.810  3852  3852 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:16:23.810  3852  3852 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:16:23.810  6803  6803 D BluetoothMap: Proxy object disconnected
09-06 19:16:23.810  6803  6803 D MapProfile: Bluetooth service disconnected
,09-06 19:16:23.810  3852  3852 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:16:23.810  3852  3852 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:16:23.810  3852  3852 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:16:23.810  3852  3852 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:16:23.810  3852  3852 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:16:23.813  3852  3852 V BluetoothMapService: Handler(): got msg=4
09-06 19:16:23.813  3852  3852 D BluetoothMapService: MAP Service closeService in
09-06 19:16:23.813  3852  3852 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:16:23.813  3852  3852 V BluetoothMapService: MAP Service closeService out
09-06 19:16:23.815  3852  3924 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:16:23.815  3852  3924 D BluetoothAdapterProperties: Setting state to 10
09-06 19:16:23.815  3852  3924 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:16:23.815  3852  3852 D BluetoothMapService: cleanup()
09-06 19:16:23.815  3852  3852 D BluetoothMapService: MAP Service closeService in
09-06 19:16:23.815  1041  1116 D BluetoothManagerService: Message: 60
09-06 19:16:23.815  3852  3852 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:16:23.816  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 19:16:23.816  3852  3852 V BluetoothMapService: MAP Service closeService out
09-06 19:16:23.816  1041  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-06 19:16:23.816  3852  3924 I BluetoothAdapterState: Entering OffState
09-06 19:16:23.817  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:23.818  6803  6828 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:16:23.819  1041  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:16:23.819  1041  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:23.819  6803  6820 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:16:23.820  6803  6828 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:16:23.821  1836  2724 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:23.822  1836  2460 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:23.823  6803  6820 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:16:23.826  1041  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 19:16:23.827  1041  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 19:16:23.829  1041  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 19:16:23.829  1041  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 19:16:23.829  1041  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@521be80 mBinding = false
09-06 19:16:23.830  1041  1116 D BluetoothManagerService: Sending unbind request.
09-06 19:16:23.832  1041  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 19:16:23.834  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:16:23.836  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:23.838  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:23.838  1923  1923 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:23.838  1923  2120 D LGBluetoothAPIService: Message: 2
09-06 19:16:23.839  1923  2120 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@180a5630 mBinding = false
09-06 19:16:23.839  1923  2120 D LGBluetoothAPIService: Sending unbind request.
09-06 19:16:23.840  3852  3928 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:16:23.842  1585  1585 D BluetoothAdapter: 861870161: getState() :  mService = null. Returning STATE_OFF
09-06 19:16:23.842  1585  1585 D BluetoothAdapter: 861870161: getState() :  mService = null. Returning STATE_OFF
09-06 19:16:23.842  6803  6803 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:16:23.843  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 19:16:23.843  6803  6803 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 19:16:23.843  3852  3852 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:16:23.844  3852  3852 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:16:23.844  3852  3852 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:16:23.845  3852  3852 I art     : --- WEIRD: removing null entry 246
09-06 19:16:23.845  3852  3852 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-06 19:16:23.845  3852  3852 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 19:16:23.847  3852  3852 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 19:16:23.849  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:16:23.850  3852  3852 I art     : System.exit called, status: 0
09-06 19:16:23.850  3852  3852 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:16:23.861  6803  6803 D DockEventReceiver: finishStartingService: stopping service
09-06 19:16:23.875   316  1367 V AudioFlinger: 3852 died, releasing its sessions
09-06 19:16:23.875   316  1367 V AudioFlinger:  pid 1836 @ 0
,09-06 19:16:23.875   316  1367 V AudioFlinger:  pid 3337 @ 1
09-06 19:16:23.875   316  1367 V AudioFlinger:  pid 3337 @ 2
09-06 19:16:23.876  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 19:16:23.938  1041  2034 I ActivityManager: Process com.android.bluetooth (pid 3852) has died
,09-06 19:16:23.939  1041  2034 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-06 19:16:23.951  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:23.988  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:16:24.000  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:24.009  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:24.009  6803  6803 D BluetoothPermissionRequest: onReceive
09-06 19:16:24.012  6803  6803 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:16:24.013  6803  6803 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 19:16:24.014  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:16:24.073  1041  1562 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6957 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 19:16:24.079  6934  6955 W FormManager: Network not available. Please check & try again.
09-06 19:16:24.099  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:24.100  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:16:24.100  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:16:24.100  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-06 19:16:24.104  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:16:24.105  6934  6956 V FormManager: Network unavailable.
09-06 19:16:24.111  6934  6956 V FormManager: Network unavailable.
09-06 19:16:24.120  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:16:24.120  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:16:24.120  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:16:24.120  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:16:24.121  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:16:24.121  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-06 19:16:24.124  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:16:24.125  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:16:24.126  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:24.132  1041  1936 I ActivityManager: Killing 6030:com.android.contacts/u0a19 (adj 15): empty #17
09-06 19:16:24.133  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:16:24.279  4326  6976 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:16:24.281  1041  1972 W libprocessgroup: failed to open /acct/uid_10019/pid_6030/cgroup.procs: No such file or directory
09-06 19:16:24.291  4326  6977 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:16:24.292  4326  6977 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:16:24.302  6957  6957 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 19:16:24.303  6957  6957 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:16:24.303  6957  6957 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-06 19:16:24.304  6957  6957 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 19:16:24.310  6850  6850 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 19:16:24.310  6850  6850 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:16:24.310  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:24.314  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:24.322  6934  6979 W FormManager: Network not available. Please check & try again.
09-06 19:16:24.325  6934  6980 V FormManager: Network unavailable.
09-06 19:16:24.330  6934  6980 V FormManager: Network unavailable.
09-06 19:16:24.332  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:24.335  6957  6957 D BluetoothAdapterApp: Loading JNI Library
,09-06 19:16:24.358  6884  6884 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 19:16:24.359  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:16:24.360  6884  6884 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 19:16:24.371  6957  6957 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1c7c3186 Instance Count = 1
,09-06 19:16:24.377  6957  6957 D BluetoothAdapterApp: onCreate
09-06 19:16:24.402  6957  6957 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-06 19:16:24.403  6957  6957 D ProfileConfigQcom: Adding HeadsetService
09-06 19:16:24.403  6957  6957 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 19:16:24.403  6957  6957 D ProfileConfigQcom: Adding A2dpService
09-06 19:16:24.403  6957  6957 D ProfileConfigQcom: [BTUI] HidService is supported
09-06 19:16:24.403  6957  6957 D ProfileConfigQcom: Adding HidService
09-06 19:16:24.404  6957  6957 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 19:16:24.404  6957  6957 D ProfileConfigQcom: Adding HealthService
09-06 19:16:24.404  6957  6957 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-06 19:16:24.405  6957  6957 D ProfileConfigQcom: [BTUI] PanService is supported
09-06 19:16:24.405  6957  6957 D ProfileConfigQcom: Adding PanService
09-06 19:16:24.406  6957  6957 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 19:16:24.406  6957  6957 D ProfileConfigQcom: Adding GattService
09-06 19:16:24.406  6957  6957 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 19:16:24.406  6957  6957 D ProfileConfigQcom: Adding BluetoothMapService
09-06 19:16:24.407  6957  6957 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 19:16:24.409  6957  6957 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-06 19:16:24.412  6884  6884 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:24.412  6884  6884 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:16:24.413  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:16:24.419  6957  6957 V LGMDMManagerInternal: Create singleton instance
09-06 19:16:24.419  6884  6884 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-06 19:16:24.422  6884  6884 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 19:16:24.422  6884  6884 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 19:16:24.422  6884  6884 V SoundPool: doLoad: loading sample sampleID=1
09-06 19:16:24.422  6884  6984 V SoundPool: Start decode
09-06 19:16:24.422  6884  6984 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-06 19:16:24.423   316  1367 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 19:16:24.423   316  1367 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 19:16:24.423   316  1367 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 19:16:24.423   316  1367 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 19:16:24.423   316  1367 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 19:16:24.423   316  1367 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 19:16:24.423   316  1367 V MediaPlayerService: player type = 3
09-06 19:16:24.423   316  1367 V AwesomePlayer: AwesomePlayer create()
09-06 19:16:24.424  6884  6884 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 19:16:24.424   316  1367 V AwesomePlayer: reset_l() 
09-06 19:16:24.424   316  1367 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:24.424   316  1367 V AwesomePlayer: setAudioSink() 
09-06 19:16:24.424   316  1367 V AwesomePlayer: reset_l() 
09-06 19:16:24.424   316  1367 V AudioCache: notify(0xb0409640, 8, 0, 0)
09-06 19:16:24.424   316  1367 V AudioCache: ignored
09-06 19:16:24.424   316  1367 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:24.424   316  1367 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 19:16:24.424   316  1367 V AwesomePlayer: setDataSource_l dataSource
09-06 19:16:24.424   316  1367 V LGParserOSAL: SniffLGParser start
09-06 19:16:24.424   316  1367 V LGParserOSAL: MainType:5, SubType=0
09-06 19:16:24.424   316  1367 V LGParserOSAL: #### check Mime : application/ogg
09-06 19:16:24.424   316  1367 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 19:16:24.424   316  1367 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 19:16:24.428  6753  6753 D UEI.SmartControl: QS Service created
09-06 19:16:24.429  6884  6884 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 19:16:24.438  6884  6884 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-06 19:16:24.439  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:16:24.450  6884  6884 V LGMDMManager: Create singleton instance
09-06 19:16:24.458  6753  6753 I UEI.SmartControl: Service initServices...
09-06 19:16:24.458  6753  6753 D UEI.SmartControl: QS start get config
,09-06 19:16:24.470   316  1367 V LGParserOSAL: supported mime: application/ogg
09-06 19:16:24.471   316  1367 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 19:16:24.471   316  1367 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 19:16:24.471   316  1367 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 19:16:24.471   316  1367 V AwesomePlayer: AudioTrack Setting
09-06 19:16:24.471   316  1367 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 19:16:24.471   316  1367 V AwesomePlayer: setAudioSource() 
09-06 19:16:24.471   316  1367 V MediaPlayerService: prepare
09-06 19:16:24.471   316  1367 V AwesomePlayer: prepareAsync_l() 
09-06 19:16:24.471   316  1367 V MediaPlayerService: wait for prepare
09-06 19:16:24.471   316  6985 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 19:16:24.471   316  6985 V AwesomePlayer: initAudioDecoder() 
09-06 19:16:24.471   316  6985 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:16:24.471   316  6985 V AudioSystem: isOffloadSupported()
09-06 19:16:24.471   316  6985 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:16:24.471   316  6985 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:16:24.471   316  6985 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:16:24.471   316  6985 V AwesomePlayer: getUseOffload() = 0 
09-06 19:16:24.471   316  6985 V OMXCodec: OMXCodec::Create
09-06 19:16:24.471   316  6985 V OMXCodec: findMatchingCodecs()
09-06 19:16:24.471   316  6985 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-06 19:16:24.471   316  6985 V OMXCodec: matchingCodecs.size()=1
09-06 19:16:24.471   316  6985 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 19:16:24.473   316  6985 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 19:16:24.473   316  6985 V LGCodecAdapter: LG Codec Adapter start
09-06 19:16:24.473   316  6985 V OMXCodec: OMXCodec Createtor
09-06 19:16:24.473   316  6985 V OMXCodec: setComponentRole
09-06 19:16:24.473   316  6985 V OMXCodec: configureCodec protected=0
09-06 19:16:24.473   316  6985 V LGCodecAdapter: called getLGCodecSpecificData
09-06 19:16:24.473   316  6985 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 19:16:24.473   316  6985 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 19:16:24.473   316  6985 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 19:16:24.473   316  6985 V LGCodecOSAL: Not support LGCodec
09-06 19:16:24.473   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:16:24.473   316  6985 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 19:16:24.473   316  6985 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 19:16:24.473   316  6985 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 19:16:24.473   316  6985 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:16:24.473   316  6985 V AudioSystem: isOffloadSupported()
09-06 19:16:24.473   316  6985 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:16:24.474   316  6985 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 19:16:24.474   316  6985 V OMXCodec: init()
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
09-06 19:16:24.474   316  6985 V OMXCodec: allocateBuffers
09-06 19:16:24.474   316  6985 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-06 19:16:24.474   316  6985 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-06 19:16:24.474   316  6985 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0240 on output port
09-06 19:16:24.474   316  6985 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:16:24.474   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:16:24.474   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:16:24.476   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 19:16:24.476   316  6985 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:16:24.476   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 19:16:24.476   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-06 19:16:24.476   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 19:16:24.476   316  6985 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 19:16:24.476   316  6985 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 19:16:24.476   316  6985 V AudioCache: notify(0xb0409640, 5, 0, 0)
09-06 19:16:24.476   316  6985 V AudioCache: ignored
09-06 19:16:24.476   316  6985 V AudioCache: notify(0xb0409640, 1, 0, 0)
09-06 19:16:24.476   316  6985 V AudioCache: prepared
09-06 19:16:24.476   316  1367 V AudioCache: wait - success
09-06 19:16:24.476   316  1367 V MediaPlayerService: start
09-06 19:16:24.476   316  1367 V AwesomePlayer: play_l() 
09-06 19:16:24.476   316  1367 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 19:16:24.476   316  1367 V AwesomePlayer: createAudioPlayer_l
09-06 19:16:24.476   316  1367 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 19:16:24.476   316  1367 V AwesomePlayer: startAudioPlayer_l() ,
09-06 19:16:24.476   316  1367 D AudioPlayer: start of Playback, useOffload 0
09-06 19:16:24.476   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:16:24.476   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:16:24.479   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 19:16:24.479   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 19:16:24.479   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 19:16:24.479   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 19:16:24.479   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1),
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803136
,09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 19:16:24.480   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 19:16:24.481   316  6987 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:16:24.481   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,09-06 19:16:24.481   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-06 19:16:24.481   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-06 19:16:24.481   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-06 19:16:24.481   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0470 on output port
09-06 19:16:24.481   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 19:16:24.481   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 19:16:24.482   316  1367 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-06 19:16:24.483   316  1367 V AudioCache: notify(0xb0409640, 6, 0, 0)
,09-06 19:16:24.483   316  1367 V AudioCache: ignored
09-06 19:16:24.483   316  1367 V MediaPlayerService: wait for playback complete
09-06 19:16:24.483   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.483   316  6988 V AudioCache: memcpy(0xaf006000, 0xb1027000, 4096)
09-06 19:16:24.485   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.485   316  6988 V AudioCache: memcpy(0xaf007000, 0xb1027000, 4096)
09-06 19:16:24.486   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.486   316  6988 V AudioCache: memcpy(0xaf008000, 0xb1027000, 4096)
,09-06 19:16:24.487   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.487   316  6988 V AudioCache: memcpy(0xaf009000, 0xb1027000, 4096)
09-06 19:16:24.488   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.488   316  6988 V AudioCache: memcpy(0xaf00a000, 0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: write(0xb1027000, 4096)
,09-06 19:16:24.489   316  6988 V AudioCache: memcpy(0xaf00b000, 0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: memcpy(0xaf00c000, 0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: memcpy(0xaf00d000, 0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: memcpy(0xaf00e000, 0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.489   316  6988 V AudioCache: memcpy(0xaf00f000, 0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: memcpy(0xaf010000, 0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: memcpy(0xaf011000, 0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: memcpy(0xaf012000, 0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: memcpy(0xaf013000, 0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.490   316  6988 V AudioCache: memcpy(0xaf014000, 0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: memcpy(0xaf015000, 0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: memcpy(0xaf016000, 0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: memcpy(0xaf017000, 0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: memcpy(0xaf018000, 0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.491   316  6988 V AudioCache: memcpy(0xaf019000, 0xb1027000, 4096)
09-06 19:16:24.492   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.492   316  6988 V AudioCache: memcpy(0xaf01a000, 0xb1027000, 4096)
09-06 19:16:24.492   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.492   316  6988 V AudioCache: memcpy(0xaf01b000, 0xb1027000, 4096)
09-06 19:16:24.492   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.492   316  6988 V AudioCache: memcpy(0xaf01c000, 0xb1027000, 4096)
09-06 19:16:24.493   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.493   316  6988 V AudioCache: memcpy(0xaf01d000, 0xb1027000, 4096)
09-06 19:16:24.494   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.494   316  6988 V AudioCache: memcpy(0xaf01e000, 0xb1027000, 4096)
09-06 19:16:24.494   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.494   316  6988 V AudioCache: memcpy(0xaf01f000, 0xb1027000, 4096)
09-06 19:16:24.494   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.494   316  6988 V AudioCache: memcpy(0xaf020000, 0xb1027000, 4096)
09-06 19:16:24.495   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.495   316  6988 V AudioCache: memcpy(0xaf021000, 0xb1027000, 4096)
09-06 19:16:24.495   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.495   316  6988 V AudioCache: memcpy(0xaf022000, 0xb1027000, 4096)
09-06 19:16:24.496   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.496   316  6988 V AudioCache: memcpy(0xaf023000, 0xb1027000, 4096)
09-06 19:16:24.496   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.496   316  6988 V AudioCache: memcpy(0xaf024000, 0xb1027000, 4096)
09-06 19:16:24.496   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.496   316  6988 V AudioCache: memcpy(0xaf025000, 0xb1027000, 4096)
,09-06 19:16:24.497   316  6988 V AudioCache: write(0xb1027000, 4096),
09-06 19:16:24.497   316  6988 V AudioCache: memcpy(0xaf026000, 0xb1027000, 4096)
,09-06 19:16:24.497   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.497   316  6988 V AudioCache: memcpy(0xaf027000, 0xb1027000, 4096),
09-06 19:16:24.497   316  6988 V AudioCache: write(0xb1027000, 4096),
09-06 19:16:24.497   316  6988 V AudioCache: memcpy(0xaf028000, 0xb1027000, 4096)
09-06 19:16:24.498   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.498   316  6988 V AudioCache: memcpy(0xaf029000, 0xb1027000, 4096)
09-06 19:16:24.498   316  6988 V AudioCache: write(0xb1027000, 4096)
,09-06 19:16:24.501   316  6988 V AudioCache: memcpy(0xaf02a000, 0xb1027000, 4096)
09-06 19:16:24.501   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.501   316  6988 V AudioCache: memcpy(0xaf02b000, 0xb1027000, 4096)
09-06 19:16:24.501   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.501   316  6988 V AudioCache: memcpy(0xaf02c000, 0xb1027000, 4096)
09-06 19:16:24.501   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.501   316  6988 V AudioCache: memcpy(0xaf02d000, 0xb1027000, 4096)
09-06 19:16:24.502   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.502   316  6988 V AudioCache: memcpy(0xaf02e000, 0xb1027000, 4096)
09-06 19:16:24.502   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.502   316  6988 V AudioCache: memcpy(0xaf02f000, 0xb1027000, 4096)
09-06 19:16:24.502   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.502   316  6988 V AudioCache: memcpy(0xaf030000, 0xb1027000, 4096)
,09-06 19:16:24.502   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.502   316  6988 V AudioCache: memcpy(0xaf031000, 0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: memcpy(0xaf032000, 0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: memcpy(0xaf033000, 0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: memcpy(0xaf034000, 0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: memcpy(0xaf035000, 0xb1027000, 4096)
09-06 19:16:24.503   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 19:16:24.503   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: memcpy(0xaf036000, 0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,09-06 19:16:24.503   316  6988 V AudioCache: write(0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V AudioCache: memcpy(0xaf037000, 0xb1027000, 4096)
09-06 19:16:24.503   316  6988 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:16:24.503   316  6988 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:16:24.503   316  6988 V AwesomePlayer: postAudioEOS() 
09-06 19:16:24.503   316  6988 V AudioCache: write(0xb1027000, 280)
09-06 19:16:24.503   316  6988 V AudioCache: memcpy(0xaf038000, 0xb1027000, 280)
09-06 19:16:24.505   316  6985 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 19:16:24.505   316  6985 V AwesomePlayer: onStreamDone
09-06 19:16:24.505   316  6985 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 19:16:24.505   316  6985 V AudioCache: notify(0xb0409640, 2, 0, 0)
09-06 19:16:24.505   316  6985 V AudioCache: playback complete
09-06 19:16:24.505   316  6985 V AwesomePlayer: pause_l() 
09-06 19:16:24.505   316  6985 V AudioCache: notify(0xb0409640, 7, 0, 0)
,09-06 19:16:24.505   316  6985 V AudioCache: ignored
09-06 19:16:24.505   316  6985 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:24.505   316  1367 V AudioCache: wait - success
09-06 19:16:24.505   316  1367 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 19:16:24.507   316  6985 D AudioPlayer: Pause Playback at 1068125
09-06 19:16:24.508   316  1367 V AwesomePlayer: reset_l() 
09-06 19:16:24.508   316  1367 V AudioCache: notify(0xb0409640, 8, 0, 0)
09-06 19:16:24.508   316  1367 V AudioCache: ignored
09-06 19:16:24.508   316  1367 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:24.508   316  1367 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 19:16:24.508   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 19:16:24.508   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 19:16:24.508   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
,09-06 19:16:24.508   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c0470 on port 1
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
09-06 19:16:24.508   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 19:16:24.509   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-06 19:16:24.509   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:16:24.509   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 19:16:24.509   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:16:24.509   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:16:24.509   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 19:16:24.509   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 19:16:24.509   316  6987 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 19:16:24.509   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:16:24.509   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 19:16:24.509   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,09-06 19:16:24.510   316  1367 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 19:16:24.510   316  1367 D AudioPlayer: AudioPlayer releasing audio source
09-06 19:16:24.510   316  1367 D AudioPlayer: AudioPlayer done releasing audio source
,09-06 19:16:24.510   316  1367 V AwesomePlayer: reset_l() 
,09-06 19:16:24.510   316  1367 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:24.510   316  1367 V AwesomePlayer: ~AwesomePlayer call
09-06 19:16:24.510   316  1367 V AwesomePlayer: reset_l() 
09-06 19:16:24.510   316  1367 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:24.510  6884  6984 V SoundPool: close(31)
09-06 19:16:24.510  6884  6984 V SoundPool: pointer = 0xa003a000, size = 205080, sampleRate = 48000, numChannels = 2
09-06 19:16:24.518  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:16:24.519  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 19:16:24.521  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:449
09-06 19:16:24.526  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:24.531  6957  6957 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-06 19:16:24.531  6957  6957 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:16:24.531  6957  6957 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:16:24.532  6957  6957 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:24.532  6957  6957 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-06 19:16:24.539  6901  6901 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-06 19:16:24.741  6753  6753 I UEI.SmartControl: Supports setup maps: true
,09-06 19:16:24.743  6753  6753 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:16:24.743  6753  6753 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:16:24.743  6753  6753 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:16:24.743  6753  6753 I UEI.SmartControl: ### init IR Blaster...
09-06 19:16:24.747  6753  6753 D serial_port: Configuring serial port
09-06 19:16:24.747  6753  6753 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:16:24.747  6753  6753 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:16:24.747  6753  6753 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:16:24.747  6753  6753 I UEI.SmartControl: Get version...
09-06 19:16:24.761  6753  6990 D UEI.SmartControl: serial port data available: 21
,09-06 19:16:24.788  6753  6753 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:16:24.788  6753  6753 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:16:24.788  6753  6753 I UEI.SmartControl: QS saving settings...
09-06 19:16:24.790  6753  6753 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:16:24.806  6753  6990 D UEI.SmartControl: serial port data available: 4
,09-06 19:16:24.836  6753  6753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 19:16:24.840  6753  6753 E UEI.SmartControl: Services init done
,09-06 19:16:24.840  6753  6753 D UEI.SmartControl: QS Service init finished
,09-06 19:16:24.842  6753  6753 D UEI.SmartControl: QS Service version name: 2.1.91
,09-06 19:16:24.843  6753  6753 D UEI.SmartControl: QS Service version code: 201091
,09-06 19:16:24.844  6753  6753 D UEI.SmartControl: Service requested: Control,
,09-06 19:16:24.850  6753  6753 D UEI.SmartControl: Internal service binding...
09-06 19:16:24.851  6884  6884 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,09-06 19:16:24.855  6753  6769 I UEI.SmartControl: ------ IControl API: 11
09-06 19:16:24.855  6753  6769 D UEI.SmartControl: File observer start...
09-06 19:16:24.856  6753  6769 E UEI.SmartControl: IR Port is disabled: false
09-06 19:16:24.856  6753  6769 D UEI.SmartControl: Starting file observer...
09-06 19:16:24.859  6753  6769 I UEI.SmartControl: Registering callback...
09-06 19:16:24.860  6753  6999 I UEI.SmartControl: Device manager: loading config....
09-06 19:16:24.860  6753  6999 D UEI.SmartControl: ----------- loading internal config...
,09-06 19:16:24.863  6753  6768 I UEI.SmartControl: ------ IControl API: 19
09-06 19:16:24.865  6753  6768 I UEI.SmartControl: Registering Services Ready callback...
09-06 19:16:24.865  6753  6999 E UEI.SmartControl: Loading SETTINGS...
09-06 19:16:24.870  6753  6999 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 19:16:24.882  6753  6998 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-06 19:16:24.883  6884  6900 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 19:16:24.883  6884  6982 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 19:16:24.884  6884  6982 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 19:16:24.884  6753  6998 D UEI.SmartControl: -----service ready thread exits
09-06 19:16:24.885  6884  6884 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 19:16:24.885  6884  6884 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 19:16:24.885  6753  6769 I UEI.SmartControl: ------ IControl API: 8
09-06 19:16:24.887  6884  6884 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 19:16:24.887  6884  6884 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 19:16:24.887  6884  6884 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 19:16:24.888  6884  6884 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 19:16:24.889  6884  6884 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 19:16:24.889  6884  6884 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-06 19:16:24.890  6884  6884 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-06 19:16:24.894  6884  6884 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 19:16:24.894  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:16:24.896  6884  6884 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:16:24.897  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:16:24.898  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:16:24.899  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-06 19:16:24.899  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 19:16:24.900  6884  6884 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473182184900]
09-06 19:16:24.903  6884  6884 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 19:16:24.905  1041  1936 I ActivityManager: Killing 6053:com.android.gallery3d/u0a27 (adj 15): empty #17
09-06 19:16:24.926  6884  7001 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 19:16:24.988  1041  1936 I ActivityManager: Killing 6530:com.lge.email/u0a23 (adj 15): empty #18
,09-06 19:16:25.047  1041  2015 W libprocessgroup: failed to open /acct/uid_10027/pid_6053/cgroup.procs: No such file or directory
,09-06 19:16:25.061  1041  1756 W libprocessgroup: failed to open /acct/uid_10023/pid_6530/cgroup.procs: No such file or directory
09-06 19:16:25.061  6884  6884 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-06 19:16:25.063  6884  6884 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:16:25.063  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 19:16:25.064  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 19:16:25.064  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-06 19:16:25.065  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 19:16:25.065  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-06 19:16:25.076  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-06 19:16:25.596  1041  1056 D WifiServiceImplEx: setWifiEnabled: true pid=6633, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-06 19:16:25.604  1041  1056 D WifiService: setWifiEnabled: true pid=6633, uid=10118
09-06 19:16:25.604  1041  1056 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:16:25.631  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:16:25.631  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:16:25.631  1041  1041 D Ulp_jni : JNI:system_update. Event-4
09-06 19:16:25.633  1041  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 19:16:25.633  1041  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 19:16:25.635  1041  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1041] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 19:16:25.635  1041  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:16:25.635  1041  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1041] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 19:16:25.635  1041  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:16:25.635  1041  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 19:16:25.635  1041  1522 E WifiHW  : unknown target_country: EU , set to default
09-06 19:16:25.635  1041  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 19:16:25.635  1041  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 19:16:25.635  1041  1522 I WifiUtil: gEnableBmps=1
09-06 19:16:25.698  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:25.706  1041  1116 D Tethering: MasterInitialState.processMessage what=3
09-06 19:16:25.715  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:25.719  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:25.720  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:25.726  1041  1096 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:25.727  1041  1116 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:16:25.738  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:25.741  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:25.744  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:16:25.747  6442  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:16:25.765  5774  5774 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:16:25.777  5774  5774 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:16:25.796  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:25.830  1041  1096 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:25.879  1041  1946 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7015 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-06 19:16:25.890  1041  1096 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:25.890  1041  1096 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:16:25.949  7015  7015 I AppUp4:AppBoxCP: onCreate
,09-06 19:16:25.950  7015  7015 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-06 19:16:25.960  7015  7015 I AppUp4:DB:  setFingerPrint start
09-06 19:16:25.961  7015  7015 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-06 19:16:25.970  7015  7015 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-06 19:16:25.970  7015  7015 I AppUp4:DB:  SDK version = 21
09-06 19:16:25.970  7015  7015 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-06 19:16:25.972  7015  7015 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-06 19:16:25.973  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:16:25.973  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:25.976  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:16:25.976  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 19:16:25.986  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:16:26.033  7015  7015 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:26.033  7015  7015 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:26.041  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ce7d1e0
09-06 19:16:26.042  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:16:26.042  7015  7015 D AppUp4:CustFacade: isPhone : true
09-06 19:16:26.042  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:16:26.043  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-06 19:16:26.043  7015  7015 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-06 19:16:26.044  7015  7042 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-06 19:16:26.044  7015  7042 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-06 19:16:26.044  7015  7042 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-06 19:16:26.047  1041  1757 I ActivityManager: Killing 6078:com.android.vending/u0a44 (adj 15): empty #17
,09-06 19:16:26.121  1041  1056 W libprocessgroup: failed to open /acct/uid_10044/pid_6078/cgroup.procs: No such file or directory
,09-06 19:16:26.122  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:26.123  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:16:26.127  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:26.133  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:16:26.143  4326  7052 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:16:26.146  4326  7053 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:26.146  4326  7053 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:16:26.221  1041  2015 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7054 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 19:16:26.289   310   896 D SoftapController: Softap fwReload - Ok
,09-06 19:16:26.290  1041  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:26.291  1041  1116 D Tethering: InitialState.processMessage what=4
09-06 19:16:26.294  1041  1522 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (654ms)
09-06 19:16:26.297   310   896 D CommandListener: Setting iface cfg
09-06 19:16:26.297   310   896 D CommandListener: Trying to bring down wlan0
09-06 19:16:26.298  1041  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:26.299   310   896 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:16:26.302  1041  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-06 19:16:26.304  1041  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:16:26.304  1041  1522 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:16:26.304  1041  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:16:26.305  1041  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 19:16:26.305  1041  1522 D WifiMonitor: connecting to supplicant
09-06 19:16:26.308  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:26.309  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-06 19:16:26.309  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 19:16:26.311  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:26.312  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:26.299  7072  7072 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:26.299  7072  7072 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:26.337  7054  7054 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:26.339  7054  7054 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:16:26.341  7054  7054 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:16:26.341  7054  7054 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:16:26.343  7072  7072 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 19:16:26.380  7072  7072 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:16:26.380  7072  7072 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-06 19:16:26.438  7054  7054 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-06 19:16:26.457  7054  7054 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-06 19:16:26.491  7072  7072 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:16:26.510  7054  7054 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:16:26.548  7054  7054 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:16:26.548  7054  7054 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:26.552  7072  7072 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-06 19:16:26.561  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-06 19:16:26.561  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 19:16:26.561  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:16:26.563  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-06 19:16:26.564  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:16:26.565  1041  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,09-06 19:16:26.566  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:26.568  1041  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:26.568  1041  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-06 19:16:26.569  1041  7081 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:16:26.569  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 19:16:26.569  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 19:16:26.569  1041  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:16:26.569  1041  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:16:26.570  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:26.572  1041  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:26.574  1041  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 19:16:26.574  1041  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 19:16:26.575  1041  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 19:16:26.575  1041  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 19:16:26.575  1041  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-06 19:16:26.643  1041  1361 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7087 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:26.644  1041  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:16:26.644  1041  1522 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:16:26.644  1041  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:16:26.648  1923  1923 D WfdService: Waiting for WifiP2p enabling
09-06 19:16:26.649  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:26.651  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:26.651  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:26.651  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:26.651  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:26.651  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:26.651  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:26.651  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:26.651  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:26.651  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:26.652  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:26.652  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:26.652  1041  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 19:16:26.653  1041  1361 V AlarmManager: RTC_WAKEUP set : Alarm{1e16da79 type 0 when 1473182183183 com.android.vending} when 1473182183183
09-06 19:16:26.653  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:26.653  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:26.653  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:26.653  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:26.653  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:26.653  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:26.653  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:26.653  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:26.653  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:26.653  1041  1522 D WifiNative-wlan0: SET update_config 1: returned true
09-06 19:16:26.653  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:26.653  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:26.653  1041  1522 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:16:26.653  1041  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 19:16:26.653  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:26.654  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:26.654  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:26.654  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:26.654  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:16:26.654  1041  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 19:16:26.655  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 19:16:26.656  1041  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 19:16:26.666  1041  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 19:16:26.677  1041  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-06 19:16:26.678  1041  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:16:26.678  1041  1522 D WifiStateMachine: enableVerboseLogging : level 2
09-06 19:16:26.678  1041  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 19:16:26.679  1041  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 19:16:26.679  1041  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 19:16:26.679  1041  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 19:16:26.679  1041  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 19:16:26.680  1041  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 19:16:26.680  1041  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 19:16:26.680  1041  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 19:16:26.681  1041  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 19:16:26.681  1041  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 19:16:26.681  1041  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 19:16:26.682  1041  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 19:16:26.682  1041  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 19:16:26.682  1041  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 19:16:26.683  1041  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:16:26.683  1041  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-06 19:16:26.683  1923  1923 D WfdsService: Supplicant Connection state is changed : true
09-06 19:16:26.683  1041  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 19:16:26.683  1041  1522 D WifiNative-HAL: Setting external_sim to 1
09-06 19:16:26.683  1041  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 19:16:26.684  1041  1522 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 19:16:26.684  1041  1522 I WifiNative-HAL: startHal
09-06 19:16:26.684  1041  1522 D wifi    : setting scan oui 0x956ccc40
09-06 19:16:26.684  1041  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:16:26.684  1041  1522 I WifiNative-HAL: startHal
09-06 19:16:26.685  1041  1522 D wifi    : setting scan oui 0x956ccc40
09-06 19:16:26.685  1041  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 19:16:26.686  1041  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 19:16:26.686  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 19:16:26.686  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 19:16:26.686  1923  2324 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 19:16:26.686  1923  2324 D WfdsService: Set the WFDS Monitor: true
09-06 19:16:26.686  1923  2324 D WfdsMonitor: WfdsMonitorThread create
09-06 19:16:26.686  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 19:16:26.686  1923  2324 D WfdsMonitor: WFDS Monitor is created and started
09-06 19:16:26.686  1923  2324 D WfdsService: WiFi: Supplicant connection re-established
09-06 19:16:26.687  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:16:26.687  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:16:26.687  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:16:26.688  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 19:16:26.688  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 19:16:26.688  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 19:16:26.688  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:16:26.688  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:16:26.688  1923  7104 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 19:16:26.689  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:16:26.689  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:16:26.689  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:16:26.689  1923  7104 E CtrlSupplicant: Succeed to open control connection
09-06 19:16:26.689  1923  7104 E CtrlSupplicant: Succeed to open monitor connection
09-06 19:16:26.689  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:16:26.689  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 19:16:26.689  1923  7104 D WfdsMonitor: Supplicant connection established
09-06 19:16:26.690  7072  7072 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 19:16:26.690  1923  2324 D WfdsService: Connected to the supplicant for wfds
09-06 19:16:26.690  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 19:16:26.690  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:16:26.690  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:16:26.691  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:16:26.692  1041  1522 E WifiNative: : [122,078,359 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 19:16:26.692  1041  1522 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 19:16:26.693  1041  1522 D WifiNative-wlan0: RECONNECT: returned true
09-06 19:16:26.693  1041  1522 D WifiNative-wlan0: doString: [STATUS]
09-06 19:16:26.694  1041  1522 D WifiNative,-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:16:26.694  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:16:26.694  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:16:26.694  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,09-06 19:16:26.699  1041  1522 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:16:26.700  1041  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.703   310   896 D CommandListener: Setting iface cfg
09-06 19:16:26.704   310   896 D CommandListener: Trying to bring up p2p0
09-06 19:16:26.704  1041  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:16:26.704  1041  1521 D LGWifiP2pService: P2pEnablingState
09-06 19:16:26.704  1041  1521 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.704  1041  1521 D LGWifiP2pService: P2p socket connection successful
09-06 19:16:26.704  1041  1521 D LGWifiP2pService: P2pEnabledState
09-06 19:16:26.705  1041  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 19:16:26.705  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 19:16:26.705  1923  1923 D WfdsService: WifiP2pState is changed : true
09-06 19:16:26.706  1923  2324 D WfdsService: Receive the WFDS_ENABLE Method
09-06 19:16:26.706  1923  2324 D WfdsService: Set the WFDS Monitor: true
09-06 19:16:26.706  1923  2324 D WfdsService: Connected to the supplicant for wfds
09-06 19:16:26.706  1923  2324 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 19:16:26.706  7072  7072 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,09-06 19:16:26.707  1041  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:16:26.709  1041  1041 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:16:26.709  1041  1041 D RttService: SCAN_AVAILABLE : 3
09-06 19:16:26.709  1923  2324 D WfdsService: selectPreferredScanChannel [36]
09-06 19:16:26.709  1923  2324 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 19:16:26.710  1041  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 19:16:26.710  1041  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 19:16:26.710  1041  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.710  1041  1540 I WifiNative-HAL: startHal
09-06 19:16:26.710  1041  1541 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.710  1041  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 19:16:26.710  1041  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 19:16:26.710  1041  1540 D wifi    : getting scan capabilities on interface[1] = 0x956ccc40
09-06 19:16:26.710  1041  1540 D wifi    : failed to get capabilities : -3
09-06 19:16:26.710  1041  1540 E WifiScanningService: could not get scan capabilities
09-06 19:16:26.710  1041  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 19:16:26.710  1041  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 19:16:26.711  1041  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 19:16:26.712  1923  1923 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 19:16:26.712  1041  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 19:16:26.713  1041  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 19:16:26.713  1041  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 19:16:26.713  1923  1923 D WfdsService: isConnected: false
09-06 19:16:26.713  7072  7072 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 19:16:26.713  1041  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 19:16:26.714  1041  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 19:16:26.714  1041  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 19:16:26.714  1041  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 19:16:26.715  7072  7072 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 19:16:26.715  1041  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-06 19:16:26.715  1041  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 19:16:26.715  1041  1521 D LGWifiP2pService: before postfix = G3
09-06 19:16:26.715  1041  1521 D WifiServerServiceExt: postfix byte check : 2
09-06 19:16:26.715  1041  1521 D LGWifiP2pService: after postfix = G3
09-06 19:16:26.715  1041  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 19:16:26.715  1041  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:16:26.716  1041  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 19:16:26.716  1041  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 19:16:26.716  1041  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:16:26.716  1041  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 19:16:26.716  1041  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 19:16:26.716  1041  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 19:16:26.716  1041  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 19:16:26.716  1041  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:16:26.716  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09,-06 19:16:26.717  1041  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 19:16:26.719  1041  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:16:26.719  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-06 19:16:26.719  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:26.720  7072  7072 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:16:26.720  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.721  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.722  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:16:26.722  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:26.722  1041  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:26.722  1041  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:26.722  1041  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:26.722  1041  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.722  1041  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.722  1041  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.722  1041  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:26.722  1041  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.722  1041  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.722  1041  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.723  1923  7104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:26.723  1923  7104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:26.723  1041  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 19:16:26.724  1041  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:16:26.724  1041  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:16:26.725  1041  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:16:26.725  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 19:16:26.725  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 19:16:26.725  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:16:26.726  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 19:16:26.726  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:16:26.726  1041  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:16:26.726  1041  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:16:26.726  1041  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 19:16:26.726  1041  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 19:16:26.726  1041  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 19:16:26.726  1041  1522 D WifiNative-wlan0: doBoolean: SCAN
09-06 19:16:26.727  1041  1522 D WifiNative-wlan0: SCAN: returned false
09-06 19:16:26.728  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122115  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:16:26.728  1041  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 19:16:26.729  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122116  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:16:26,.729  1041  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 19:16:26.729  1041  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 19:16:26.730  1041  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 19:16:26.730  1041  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 19:16:26.730  1041  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 19:16:26.730  1041  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:16:26.730  1041  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 19:16:26.731  1041  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 19:16:26.731  1041  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 19:16:26.731  1041  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-06 19:16:26.734  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:26.734  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:26.735  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:26.736  1041  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:16:26.736  1041  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:16:26.737  1041  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:16:26.739  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:26.739  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:26.739  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:16:26.741  1923  1923 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 19:16:26.742  1923  1923 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 19:16:26.743  1923  1923 D WfdsService: Update P2p Interface State: 3
09-06 19:16:26.744  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:26.744  1041  1041 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-06 19:16:26.748  1041  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
,09-06 19:16:26.748  1041  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:16:26.748  1041  1521 D LGWifiP2pService: InactiveState
09-06 19:16:26.748  1041  1521 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.748  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.748  1041  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 19:16:26.749  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:16:26.749  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:26.749  1041  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:16:26.749  1923  7104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:16:26.750  1041  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:26.750  1041  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:26.750  1041  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:26.750  7072  7072 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:16:26.750  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.750  1041  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:26.750  1041  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.750  1041  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.750  1041  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 19:16:26.750  1041  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.750  1041  1521 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.intern,al.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.751  1041  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.752  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.752  1041  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:26.752  1923  7104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:26.752  1923  7104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:26.752  1041  1041 E WifiServerServiceExt: No p2p device connected
09-06 19:16:26.752  1923  2324 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 19:16:26.777  7054  7054 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:16:26.807  3337  3337 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:16:26.807  3337  3337 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:26.807  3337  3337 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 19:16:26.811  7054  7054 I HubEmail: JNI_OnLoad()
,09-06 19:16:26.811  7054  7054 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:16:26.811  7054  7054 I HubEmail: registerNatives()
09-06 19:16:26.811  7054  7054 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:16:26.811  7054  7054 I HubEmail: registerNativeMethods()
09-06 19:16:26.811  7054  7054 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:16:26.811  7054  7054 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-06 19:16:26.846  1041  1635 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7117 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-06 19:16:26.857  7054  7116 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:26.858  6934  7115 V FormManager: Network unavailable.
09-06 19:16:26.858  6934  7113 W FormManager: Network not available. Please check & try again.
,09-06 19:16:26.862  6934  7115 V FormManager: Network unavailable.
09-06 19:16:26.872  1041  1909 I ActivityManager: Killing 2111:com.lge.music/u0a34 (adj 15): empty #17
,09-06 19:16:26.896   316   316 V AudioFlinger: 2111 died, releasing its sessions
09-06 19:16:26.896   316   316 V AudioFlinger:  pid 1836 @ 0
09-06 19:16:26.897   316   316 V AudioFlinger:  pid 3337 @ 1
09-06 19:16:26.897   316   316 V AudioFlinger:  pid 3337 @ 2
,09-06 19:16:26.952  1041  1978 W libprocessgroup: failed to open /acct/uid_10034/pid_2111/cgroup.procs: No such file or directory
,09-06 19:16:26.998  7087  7087 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-06 19:16:27.046  7117  7117 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:27.046  7117  7117 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:27.050  7117  7117 D PhoneMonitor: Register our PhoneStateListener
09-06 19:16:27.069  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-06 19:16:27.071  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:16:27.088  7117  7117 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-06 19:16:27.089  7117  7117 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-06 19:16:27.098  7117  7117 D TelephonyAutoProfiling: [parse] Load xml
,09-06 19:16:27.102  7117  7117 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-06 19:16:27.102  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-06 19:16:27.103  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-06 19:16:27.103  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-06 19:16:27.103  7117  7117 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-06 19:16:27.111  7117  7117 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-06 19:16:27.122  7087  7087 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:27.123  7087  7087 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:27.143  1041  1946 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7152 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:27.147  1041  1946 I ActivityManager: Killing 6117:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-06 19:16:27.167  7087  7087 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-06 19:16:27.185  7087  7087 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:16:27.185  7087  7087 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:16:27.199  7087  7087 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-06 19:16:27.199  7087  7087 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-06 19:16:27.230  1041  1889 W libprocessgroup: failed to open /acct/uid_10080/pid_6117/cgroup.procs: No such file or directory
,09-06 19:16:27.232  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 19:16:27.232  1041  7081 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 19:16:27.233  1041  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:16:27.233  7072  7072 E wpa_supplicant: USIM:  scard_init function
09-06 19:16:27.233  1041  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:16:27.233  1041  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:16:27.234  7072  7072 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 19:16:27.234  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 19:16:27.234  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-06 19:16:27.234  1041  7081 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 19:16:27.234  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:16:27.234  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 19:16:27.235  1041  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:16:27.235  1041  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 19:16:27.252  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122639  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-06 19:16:27.257  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.258  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.258  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.258  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:16:27.258  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:27.260  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122647  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:16:27.260  3469  4479 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-06 19:16:27.262  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.262  3469  4479 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@306e9104 on behalf of 7087
09-06 19:16:27.262  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:27.262  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:16:27.263  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.264  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:27.264  1041  1041 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 19:16:27.265  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.265  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:16:27.267  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.281  7087  7087 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-06 19:16:27.293  7087  7087 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-06 19:16:27.331  1041  1889 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:16:27.346  7072  7072 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-06 19:16:27.346  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 19:16:27.346  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 19:16:27.346  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 19:16:27.346  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 19:16:27.347  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:27.347  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 19:16:27.348  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122734  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:16:27.348  1041  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:27.348  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122735  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:16:27.349  1041  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122736
09-06 19:16:27.350  1041  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122737
09-06 19:16:27.350  1041  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122737
09-06 19:16:27.350  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122737
09-06 19:16:27.351  1041  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122738
09-06 19:16:27.351  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=122738  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:16:27.354  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.355  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.355  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:16:27.355  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.355  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:27.357  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.357  7072  7072 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:27.358  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:16:27.359  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:27.359  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:27.359  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 19:16:27.359  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:27.359  1041  7081 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:27.359  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 19:16:27.359  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:16:27.359  1041  7081 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:16:27.360  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:27.360  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:2,7.360  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.360  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:16:27.361  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.361  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.361  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.361  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 19:16:27.364  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=122750  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:16:27.365  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:27.365  1041  1041 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 19:16:27.365  1041  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:27.365  1041  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:27.366  1041  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:27.367  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:27.367  1041  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:27.368  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122755  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:16:27.369  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122756  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:16:27.370  1041  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122757
09-06 19:16:27.370  1041  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122757
09-06 19:16:27.371  1041  1522 D WifiNative-wlan0: doString: [STATUS]
09-06 19:16:27.371  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:27.371  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:27.372  1041  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-06 19:16:27.374  1041  1522 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 19:16:27.382  1041  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 19:16:27.382  1041  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-06 19:16:27.385  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.385  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.385  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:16:27.387  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.387  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.388  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:16:27.393  1041  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 19:16:27.393  1041  1528 D ConnectivityService: Got NetworkAgent Messenger
09-06 19:16:27.393  1041  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:16:27.393  1041  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:16:27.393  1041  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:16:27.393  1041  1528 D ConnectivityService: NetworkAgent connected
09-06 19:16:27.393  1041  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:16:27.393  1041  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:16:27.398  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.398  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:16:27.399  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:16:27.401  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.401  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:27.401  1041  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:16:27.401  1041  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:16:27.401  1041  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:16:27.402  1041  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:16:27.402  1041  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:16:27.403  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.408  1041  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:16:27.411   310   896 D CommandListener: Setting iface cfg
,09-06 19:16:27.441  1041  1978 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7178 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-06 19:16:27.441  1041  1978 I ActivityManager: Killing 6570:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-06 19:16:27.454   348   348 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 237us total 11.658ms
09-06 19:16:27.464   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.958ms
,09-06 19:16:27.474   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 9.266ms
09-06 19:16:27.498  1041  1522 E WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:16:27.498  1041  7177 D DhcpStateMachine: StoppedState
09-06 19:16:27.498  1041  1909 W libprocessgroup: failed to open /acct/uid_10061/pid_6570/cgroup.procs: No such file or directory
09-06 19:16:27.498  1041  7177 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.499  1041  7177 D DhcpStateMachine: WaitBeforeStartState
09-06 19:16:27.499  1041  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:27.499  1041  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:27.499  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:27.502  7087  7087 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
09-06 19:16:27.505  1041  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122892  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:27.505  1041  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122892  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:27.505  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:27.505  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122892  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:27.505  1041  1041 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 19:16:27.506  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:76897] from screen [on:0 period:8404978] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:16:27.507  1041  1757 I ActivityManager: Killing 6149:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-06 19:16:27.507  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:8404979] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:16:27.507  1041  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 19:16:27.553  1041  2034 W libprocessgroup: failed to open /acct/uid_10097/pid_6149/cgroup.procs: No such file or directory
,09-06 19:16:27.555  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.557  1041  1528 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-06 19:16:27.558  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 19:16:27.559  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.560  1041  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.561  1041  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.562  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.563  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.563  1041  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:16:27.564  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=156,0,0
09-06 19:16:27.565  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=156,0,0
,09-06 19:16:27.566  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 19:16:27.567  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 19:16:27.567  1041  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 19:16:27.567  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 19:16:27.568  1041  1522 D WifiNative-wlan0: SET ps 0: returned true
09-06 19:16:27.568  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
,09-06 19:16:27.568  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 19:16:27.568  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 19:16:27.569  1041  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e62e0da target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.569  1041  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 19:16:27.569  1041  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:16:27.569  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e62e0da target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.569  1041  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:16:27.569  1041  7177 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.570  1041  7177 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 19:16:27.570   310   896 D CommandListener: Setting iface cfg
09-06 19:16:27.571   310   896 D CommandListener: Trying to bring up wlan0
09-06 19:16:27.571  1041  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 19:16:27.606  1041  1757 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7196 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:27.607  1041  1757 I ActivityManager: Killing 6704:com.lge.eula/1000 (adj 15): empty #17
,09-06 19:16:27.649  1041  2015 W libprocessgroup: failed to open /acct/uid_1000/pid_6704/cgroup.procs: No such file or directory
09-06 19:16:27.650  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 19:16:27.651  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.651  1041  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.653  1041  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.654  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.655  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:27.656  1041  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:16:27.657  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:16:27.658  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:16:27.659  1041  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.659  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.659  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:16:27.660  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:16:27.660  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:16:27.661  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 19:16:27.661  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 19:16:27.662  1041  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 19:16:27.662  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:16:27.671  1041  1521 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.671  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.671  1041  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:27.679  1041  1522 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:16:27.680  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:16:27.681  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:16:27.681  1041  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:16:27.683  1041  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:16:27.683  1041  1528 D ConnectivityService: ignoring duplicate network state non-change
09-06 19:16:27.684  7196  7196 I art     : Almond Protected OAT
,09-06 19:16:27.688  1041  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:16:27.689  1041  1528 D ConnectivityService: Adding iface wlan0 to network 101
09-06 19:16:27.690  1041  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:16:27.702  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:27.702  1041  1041 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-06 19:16:27.705  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.705  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:27.706  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.710  1041  1528 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:16:27.710  1041  1528 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-06 19:16:27.710  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.711  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.711  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:16:27.711  1041  1528 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-06 19:16:27.711   310   896 E Netd    : netlink response contains error (File exists)
09-06 19:16:27.712  1041  1528 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-06 19:16:27.712  1041  1528 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 19:16:27.712  1041  1528 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-06 19:16:27.712  1041  1528 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-06 19:16:27.714  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.714  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.714  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:16:27.715  1041  1041 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:16:27.716  1041  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:16:27.717  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:16:27.717  1041  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:16:27.717  1041  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:16:27.717  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:16:27.718  1041  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:16:27.718  1923  1923 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 19:16:27.720  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.720  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.720  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:16:27.721  1041  1041 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:16:27.724  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.724  1041  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:16:27.724  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:27.724  1041  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 19:16:27.724  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:16:27.724  1041  1528 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-06 19:16:27.724  1041  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 19:16:27.724  1041  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:27.724  1041  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:27.724  1041  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:16:27.724  1041  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:27.724  1041  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 19:16:27.724  1041  1528 D ConnectivityService: currentScore = 0, newScore = 20
09-06 19:16:27.724  1041  1528 D ConnectivityService:    accepting network in place of null
09-06 19:16:27.724  1041  1528 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:27.725  1041  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Cap,abilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:27.725  1041  7176 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.725  1041  7176 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 19:16:27.725  1041  7176 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:27.725  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:16:27.725  1041  7176 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 19:16:27.725  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:16:27.727  1041  1528 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:16:27.727  1041  1528 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 19:16:27.727  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:16:27.727  1041  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:27.728  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.728  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:27.728   310  7216 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 19:16:27.729  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.731  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.731  1585  1585 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:16:27.731  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.732  1041  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:27.732  1041  1528 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 19:16:27.732  1041  1528 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 19:16:27.733  1041  1041 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 19:16:27.734  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:16:27.734  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roa,ming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:16:27.734  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:16:27.735  1041  1528 D ConnectivityService: validation of new default Network = false
09-06 19:16:27.735  1041  1528 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 19:16:27.735  1041  1528 D DSQN    : enableDataServiceNotify 
09-06 19:16:27.735  1041  1528 D DSQN    : start dsqn bin
09-06 19:16:27.735  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:27.735  1585  1585 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:16:27.735  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.739  1041  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-06 19:16:27.741  7196  7196 D WeatherApplication: removeAccount
,09-06 19:16:27.744  7196  7196 D WeatherApplication: Account.length = 0
09-06 19:16:27.744  7196  7196 E WeatherApplication: OPERATOR:OPEN
09-06 19:16:27.749  7196  7196 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:27
09-06 19:16:27.753  7196  7196 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-06 19:16:27.753  7196  7196 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:16:27.754  7196  7196 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:16:27.756  7196  7196 D WeatherAncestor: connectivity changed - connection : true
09-06 19:16:27.756  7196  7196 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-06 19:16:27.762  1801  7217 I CheckinService: active receiver: enabled
,09-06 19:16:27.823  1041  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 19:16:27.823  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:27.823  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:27.824  1041  7177 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 19:16:27.824  1041  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-06 19:16:27.825  7196  7196 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:16:27.825  1041  7177 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 19:16:27.825  1041  7177 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-06 19:16:27.825  7196  7196 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:16:27.825  1585  2028 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:16:27.825  7196  7196 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-06 19:16:27.809  7220  7220 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:27.809  7220  7220 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:27.819  7219  7219 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:27.819  7219  7219 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:27.831  7220  7220 I dhcpcd  : version 5.5.6 starting
09-06 19:16:27.832  7220  7220 E dhcpcd  : get_duid: m
09-06 19:16:27.832  7220  7220 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 19:16:27.832  7220  7220 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-06 19:16:27.837  7219  7219 E DSQN    : DSQN ssw
09-06 19:16:27.839  1801  7217 I CheckinService: Preparing to send checkin request
09-06 19:16:27.839  1801  7217 I EventLogService: Accumulating logs since 1473182121903
09-06 19:16:27.842  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:16:27.843  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:27.844  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:16:27.858  7196  7196 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:16:27.858  7196  7196 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:27
,09-06 19:16:27.873  7220  7220 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:16:27.874  7220  7220 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:16:27.874  7220  7220 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:16:27.874  7220  7220 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 19:16:27.874  7220  7220 D dhcpcd  : wlan0: sending REQUEST (xid 0x138f77fd), next in 3.16 seconds
,09-06 19:16:27.905  1041  1978 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7231 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:16:27.906  1041  1978 I ActivityManager: Killing 6723:com.lge.bnr/1000 (adj 15): empty #17
,09-06 19:16:27.909  7220  7220 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-06 19:16:27.937  7220  7220 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 19:16:27.937  7220  7220 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-06 19:16:27.938  7220  7220 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 19:16:27.938  7220  7220 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 19:16:27.938  7220  7220 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:16:27.938  7220  7220 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:16:27.938  7220  7220 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:16:27.938  7220  7220 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-06 19:16:27.962  1041  1889 W libprocessgroup: failed to open /acct/uid_1000/pid_6723/cgroup.procs: No such file or directory
09-06 19:16:27.962  1801  7217 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-06 19:16:28.066   279   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:16:28.066   279   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 19:16:28.066   279   430 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:16:28.067  7231  7259 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 19:16:28.069   279   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:16:28.069   279   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 19:16:28.069   279   430 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:16:28.070  7231  7259 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-06 19:16:28.093  1041  1889 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7265 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-06 19:16:28.096   279   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:16:28.096   279   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 19:16:28.097   279   430 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:16:28.098  7231  7263 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 19:16:28.108   279   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:16:28.108   279   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 19:16:28.108   279   430 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:16:28.109  7231  7263 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-06 19:16:28.152  7265  7265 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-06 19:16:28.154  7265  7265 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-06 19:16:28.177  7265  7265 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:16:28.177  7265  7265 I MultiDex: install
,09-06 19:16:28.177  7265  7265 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-06 19:16:28.185  7265  7265 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-06 19:16:28.228  1041  7177 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-06 19:16:28.229  1041  7177 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-06 19:16:28.229  1041  7177 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:16:28.229  1041  7177 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 19:16:28.229  1041  7177 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 19:16:28.229  1041  7177 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:16:28.229  1041  7177 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 19:16:28.229  1041  7177 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 19:16:28.230  1041  7177 D DhcpStateMachine: RunningState
09-06 19:16:28.278  7231  7231 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 19:16:28.351  1041  1056 I art     : Explicit concurrent mark sweep GC freed 92490(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.631ms total 136.041ms
,09-06 19:16:28.358  7231  7231 I LibraryLoader: Loading: webviewchromium
09-06 19:16:28.361  7231  7231 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3760-3763)
09-06 19:16:28.361  7231  7231 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:16:28.368  7231  7231 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {155cd24b}
,09-06 19:16:28.371  7231  7231 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:16:28.372  7231  7231 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:16:28.391  7231  7231 I BrowserStartupController: Initializing chromium process, renderers=0
,09-06 19:16:28.392  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:16:28.401  7231  7231 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-06 19:16:28.402  7231  7231 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
09-06 19:16:28.402  7231  7231 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
09-06 19:16:28.407   316  2167 V AudioPolicyService: registerClient() client 0xb57eeae0, uid 10093
,09-06 19:16:28.408  7231  7311 W AudioManagerAndroid: Requires BLUETOOTH permission
09-06 19:16:28.418  7231  7231 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:16:28.418  7231  7231 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:16:28.418  7231  7231 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:16:28.418  7231  7231 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:16:28.418  7231  7231 I Adreno-EGL: Remote Branch: 
09-06 19:16:28.418  7231  7231 I Adreno-EGL: Local Patches: 
09-06 19:16:28.418  7231  7231 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:16:28.481  7231  7231 I NSApplication: Starting up...
,09-06 19:16:28.535  1041  1909 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7324 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:28.537  1041  2015 I ActivityManager: Killing 6822:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-06 19:16:28.558  1041  1522 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:28.558  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-06 19:16:28.559  1041  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:28.559  1041  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:28.559  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:28.559  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:28.560  1041  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-06 19:16:28.560  1041  1528 D ConnectivityService: identical MTU - not setting
09-06 19:16:28.560  1041  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:16:28.560  1041  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 19:16:28.560  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:28.560  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:28.560  1041  1528 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:28.561  1585  2028 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 19:16:28.601  1041  2005 W libprocessgroup: failed to open /acct/uid_10037/pid_6822/cgroup.procs: No such file or directory
,09-06 19:16:28.622  7324  7324 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:28.635  1041  1889 D WifiServiceImplEx: setWifiEnabled: false pid=6633, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:16:28.635  1041  1889 D WifiService: setWifiEnabled: false pid=6633, uid=10118
09-06 19:16:28.635  1041  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:16:28.647  7341  7341 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 19:16:28.653  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:16:28.653  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:16:28.653  1041  1041 D Ulp_jni : JNI:system_update. Event-4
09-06 19:16:28.654  1041  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:28.654  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:28.654  1041  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:28.654  1041  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:28.655  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:16:28.655  1041  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:16:28.655  1041  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:16:28.655  1041  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:16:28.657  1041  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,09-06 19:16:28.657  1041  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:16:28.668  1041  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:16:28.668  1041  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.668  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.668  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:16:28.669  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-06 19:16:28.669  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:16:28.669  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:16:28.670  1041  1522 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:16:28.671  1041  7177 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.676   310   896 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:28.702  1041  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:16:28.702  1041  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-06 19:16:28.707  1041  1041 D WifiHS20: hidePasspointNotification off =false
09-06 19:16:28.708  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:28.708  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:28.708  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:16:28.708  1041  1041 D WifiHS20: hidePasspointNotification off =false
09-06 19:16:28.715  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:28.715  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:28.716  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:28.718  1923  1923 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-06 19:16:28.723  1041  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:28.723  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:28.723  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:28.724  1041  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:16:28.724  1041  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.724  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.724  1041  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3a23e97e
09-06 19:16:28.724  1041  1521 D LGWifiP2pService: P2pDisablingState
09-06 19:16:28.724  1041  1521 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.724  1041  1521 D LGWifiP2pService: p2p socket connection lost
09-06 19:16:28.724  1041  1521 D LGWifiP2pService: P2pDisabledState
09-06 19:16:28.726  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:16:28.726  1923  1923 D WfdsService: WifiP2pState is changed : false
09-06 19:16:28.726  1923  2324 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 19:16:28.726  1923  2324 D WfdsService: Set the WFDS Monitor: false
09-06 19:16:28.727  1923  2324 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:16:28.728  1923  7104 D CtrlSupplicant: Received on exit socket, terminate
09-06 19:16:28.728  1923  7104 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 19:16:28.728  1923  7104 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 19:16:28.728  1923  7104 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 19:16:28.730  1923  2324 D WfdsService: STATE : WfdsDisabledState - enter
,09-06 19:16:28.730  1923  2324 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 19:16:28.730  1923  2325 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 19:16:28.731  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:28.731  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:28.731  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:16:28.731  1041  1041 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:16:28.731  1041  1041 D RttService: SCAN_AVAILABLE : 1
09-06 19:16:28.731  1041  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.731  1041  1541 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.732  1041  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 19:16:28.732  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:16:28.732  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:16:28.732  1041  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.734  1041  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:28.736  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:16:28.736  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:16:28.736  1041  1522 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:16:28.739  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:28.739  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:28.739  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:28.743  7341  7341 I dex2oat : dex2oat took 96.659ms (threads: 4)
,09-06 19:16:28.759   310   896 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:28.759  1041  1528 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 19:16:28.759  1041  1528 D DSQN    : disableDataServiceNotify
09-06 19:16:28.759  1041  1528 D DSQN    : stop dsqn bin
,09-06 19:16:28.761  1041  1522 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 19:16:28.761  1041  1522 D WifiNative-p2p0: TERMINATE: returned true
09-06 19:16:28.762  1041  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:16:28.762  1041  1522 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:16:28.762  1041  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:16:28.762  1041  1041 D WifiHS20: hidePasspointNotification off =false
09-06 19:16:28.763  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:16:28.763  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:28.764  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:28.765  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:28.765  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:28.765  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:16:28.765  1041  1528 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-06 19:16:28.765  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:28.765  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:28.766  1041  1528 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:28.766  1041  1528 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 19:16:28.766  1041  1528 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 19:16:28.766  1041  1528 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 19:16:28.766  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:16:28.767  1585  2028 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:16:28.767  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 19:16:28.767  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 19:16:28.767  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:28.767  1041  1041 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 19:16:28.768  1041  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:28.768  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:16:28.768  7265  7286 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19,:16:28.768  7265  7286 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:16:28.768  7265  7286 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:16:28.768  7265  7286 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:16:28.768  7265  7286 I Adreno-EGL: Remote Branch: 
09-06 19:16:28.768  7265  7286 I Adreno-EGL: Local Patches: 
09-06 19:16:28.768  7265  7286 I Adreno-EGL: Reconstruct Branch: 
09-06 19:16:28.768  1041  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:28.768  1041  1528 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:28.768  1041  1528 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:28.768  1041  1528 D NetworkManagementService: Removing idletimer
09-06 19:16:28.768  1041  1528 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:28.768  1041  1528 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 19:16:28.768  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:28.768  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:28.768  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:28.768  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:28.768  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:28.768  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:28.768  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:28.768  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:28.768  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:28.768  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:28.769  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:28.769  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:28.769  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:28.769  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:28.769  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:28.769  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:28.769  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:28.769  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:28.769  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:28.769  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:28.769  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothM,anager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:28.769  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:28.770  1041  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:28.770  1041  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:28.770  1041  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:16:28.770  1041  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:16:28.770  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:28.770  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:16:28.771  1041  1041 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:16:28.771  1041  1041 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:16:28.771  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:16:28.771  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:16:28.771  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:16:28.771  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:16:28.771  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:16:28.771  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:16:28.775  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:16:28.799  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:16:28.800  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:28.800  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:28.819  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:16:28.820  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:16:28.820  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:28.823  1041  1528 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-06 19:16:28.849  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:16:28.849  7072  7072 I wpa_supplicant: monitor socket send errors count : 1
09-06 19:16:28.850  7072  7072 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1923-4\x00 that cannot receive messages
,09-06 19:16:28.853  1041  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 19:16:28.853  1041  7081 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:16:28.877  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:16:28.878  1041  7177 D DhcpStateMachine: StoppedState
09-06 19:16:28.878  1041  7177 D DhcpStateMachine: StoppedState{ when=-141ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:28.879  1041  1522 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 19:16:28.879  1041  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 19:16:28.879  7072  7072 W wpa_supplicant: USIM:  scard_deinit function
09-06 19:16:28.880  1041  1116 D Tethering: InitialState.processMessage what=4
09-06 19:16:28.881  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 19:16:28.881  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:16:28.881  1041  7081 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:16:28.882  1041  7081 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 19:16:28.882  1041  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:16:28.882  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:28.882  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:28.885  1041  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124272
09-06 19:16:28.886  1041  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124273
09-06 19:16:28.888  1041  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:28.888  1041  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:28.889  1041  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124275  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:16:28.889  1041  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124276  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:16:28.916  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:16:28.918  6442  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-06 19:16:28.930  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:28.937  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:16:28.937  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:28.937  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:16:28.937  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:16:28.939  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 19:16:28.942  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ce7d1e0
09-06 19:16:28.942  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:16:28.942  7015  7015 D AppUp4:CustFacade: isPhone : true
09-06 19:16:28.942  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:16:28.942  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:16:28.946  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:28.946  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:16:28.948  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:28.949  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:28.954  7054  7054 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:16:28.954  4326  7362 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:16:28.960  4326  7363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:28.961  4326  7363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:16:28.973  7054  7364 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:28.978  3337  3337 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-06 19:16:28.978  3337  3337 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:28.978  3337  3337 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:16:28.981  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:16:28.981  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:16:28.982  6934  7369 W FormManager: Network not available. Please check & try again.
09-06 19:16:28.989  7196  7196 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:28
,09-06 19:16:28.992  7196  7196 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:16:28.992  7196  7196 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:16:28.992  6934  7371 V FormManager: Network unavailable.
09-06 19:16:28.992  7196  7196 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:16:28.992  7196  7196 D WeatherAncestor: connectivity changed - connection : true
09-06 19:16:28.992  7196  7196 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2f1eb5e
09-06 19:16:28.993  7196  7196 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:16:28.993  7196  7196 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:16:28.993  7196  7196 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:16:28.993  7196  7196 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:16:28.993  7196  7196 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:28
09-06 19:16:28.997  6934  7371 V FormManager: Network unavailable.
09-06 19:16:29.018  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:16:29.019  1041  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 19:16:29.019  1041  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 19:16:29.019  1041  7081 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 19:16:29.020  1041  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,09-06 19:16:29.021  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:29.021  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:16:29.021  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:16:29.021  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:16:29.022  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:16:29.023  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:16:29.023  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:16:29.023  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:16:29.023  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:16:29.023  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:16:29.023  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:16:29.030  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:29.033  6934  7373 W FormManager: Network not available. Please check & try again.
,09-06 19:16:29.035  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:29.036  6934  7374 V FormManager: Network unavailable.
09-06 19:16:29.038  6934  7374 V FormManager: Network unavailable.
09-06 19:16:29.044  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:16:29.056  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:16:29.059  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:29.060  6934  7376 W FormManager: Network not available. Please check & try again.
09-06 19:16:29.062  6934  7377 V FormManager: Network unavailable.
09-06 19:16:29.064  6934  7377 V FormManager: Network unavailable.
09-06 19:16:29.064  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.066  7265  7286 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:29.067  7265  7286 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:29.079  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:16:29.079  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:16:29.080  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:29.084  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:16:29.089  4326  7378 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:16:29.090  4326  7379 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:16:29.090  4326  7379 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:16:29.121  1041  1936 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7380 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-06 19:16:29.123  1041  1522 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 19:16:29.123  1041  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:16:29.123  1041  1522 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:16:29.123  1041  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-06 19:16:29.125  1923  1923 D WfdsService: Supplicant Connection state is changed : false
09-06 19:16:29.125  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:29.125  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:16:29.125  2484  2484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:29.125  1923  2324 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 19:16:29.125  1923  2324 D WfdsService: Set the WFDS Monitor: false
09-06 19:16:29.125  1923  2324 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:16:29.126  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:29.126  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:29.126  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:29.126  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:29.126  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:29.126  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:29.126  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:29.126  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:29.126  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:29.128  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 19:16:29.128  1041  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 19:16:29.128  1041  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 19:16:29.128  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:29.210  7380  7380 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:16:29.210  7380  7380 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 19:16:29.219  7380  7380 V [BNRBootReceiver]: Boot Receiver Return
09-06 19:16:29.220  7380  7380 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:16:29.223  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:29.227  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:16:29.233  7265  7286 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:16:29.233  7265  7286 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:16:29.233  7265  7286 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:16:29.233  7265  7286 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:16:29.233  7265  7286 I Adreno-EGL: Remote Branch: 
09-06 19:16:29.233  7265  7286 I Adreno-EGL: Local Patches: 
09-06 19:16:29.233  7265  7286 I Adreno-EGL: Reconstruct Branch: 
09-06 19:16:29.235  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:16:29.269  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:16:29.270  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:29.273  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:16:29.283  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-06 19:16:29.292  7265  7286 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:16:29.292  7265  7286 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:16:29.292  7265  7286 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:16:29.292  7265  7286 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:16:29.292  7265  7286 I Adreno-EGL: Remote Branch: 
09-06 19:16:29.292  7265  7286 I Adreno-EGL: Local Patches: 
09-06 19:16:29.292  7265  7286 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:16:29.301  6803  6803 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 19:16:29.304  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:29.315  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.322  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.331  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:16:29.332  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:29.334  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:16:29.337  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:29.342  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.349  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.353   310  7399 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 19:16:29.353  1041  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:16:29.354  1801  7217 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-06 19:16:29.356  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.358  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:29.358  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:29.362  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:29.366  1801  7217 I CheckinService: active receiver: disabled
,09-06 19:16:29.370  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:16:29.375  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:16:29.385  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.385  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:29.386  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:29.388  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:29.397  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.403  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.409  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.409  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:29.410  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:29.414  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:29.421  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.426  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.435  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:16:29.436  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:29.436  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:29.440  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:29.447  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.455  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.464  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:16:29.464  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:29.465  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:29.475  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:29.490  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.497  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.510  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.510  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:29.514  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:16:29.522  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:29.538  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.546  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.555  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.556  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:29.558  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:29.563  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:29.567  6850  6850 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:16:29.576  1041  1527 D WifiService: New client listening to asynchronous messages
09-06 19:16:29.576  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:16:29.584  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.591  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.599  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.600  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:29.602  6884  6884 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:16:29.604  6884  6884 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:16:29.605  6884  6884 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:16:29.611  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:29.615  6850  6850 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 19:16:29.616  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:29.619  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:16:29.625  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.631  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.631  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:29.632  6884  6884 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:16:29.633  6884  6884 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:16:29.633  6884  6884 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-06 19:16:29.636  1041  1972 I ActivityManager: Killing 6901:com.lge.settings.easy/1000 (adj 15): empty #17
09-06 19:16:29.669  1041  1057 W libprocessgroup: failed to open /acct/uid_1000/pid_6901/cgroup.procs: No such file or directory
,09-06 19:16:29.676  2168  2168 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-06 19:16:29.686  2168  2168 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-06 19:16:29.688  2168  2168 D c       : Getting all permits...
09-06 19:16:29.688  2168  2168 D a       : Opening database...
09-06 19:16:29.699  2168  2168 D a       : Opening database auth.proximity.permit_store...
09-06 19:16:29.701  2168  2168 D a       : Closing database...
,09-06 19:16:29.723  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:29.736  6850  6850 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:16:29.736  6850  6850 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:16:29.736  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:29.747  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.765  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.781  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.782  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:29.786  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:16:29.793  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:29.803  6850  6850 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:16:29.803  6850  6850 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:16:29.803  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:16:29.811  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.819  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.830  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:29.830  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:29.834  6753  7000 D UEI.SmartControl: Internal timer expired: 2
09-06 19:16:29.834  6753  7000 D UEI.SmartControl: unbind internal service
09-06 19:16:29.838  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:16:29.844  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:29.854  6850  6850 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:16:29.854  6850  6850 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:16:29.854  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:29.862  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:29.864  6753  6994 D serial_port: close(fd = 24)
09-06 19:16:29.868  6753  6994 I UEI.SmartControl: Serial port is closed.
09-06 19:16:29.871  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.879  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:16:29.879  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:29.881  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:16:29.895  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:16:29.900  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:29.903  6934  7407 W FormManager: Network not available. Please check & try again.
09-06 19:16:29.907  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.923  6934  7408 V FormManager: Network unavailable.
,09-06 19:16:29.925  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:16:29.925  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:16:29.928  6934  7408 V FormManager: Network unavailable.
09-06 19:16:29.928  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:29.930  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:29.937  4326  7409 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:16:29.942  4326  7410 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:16:29.943  4326  7410 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:16:29.945  6850  6850 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 19:16:29.945  6850  6850 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:16:29.945  6850  6850 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:29.950  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:16:29.953  6934  7412 W FormManager: Network not available. Please check & try again.
,09-06 19:16:29.956  6934  7413 V FormManager: Network unavailable.
09-06 19:16:29.959  6934  7413 V FormManager: Network unavailable.
09-06 19:16:29.960  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:29.976  2168  2168 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-06 19:16:30.559  1041  1522 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:8408031] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 19:16:30.561  1041  1522 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:8408033] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 19:16:30.734  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:30.751  1041  1116 D Tethering: MasterInitialState.processMessage what=3
09-06 19:16:30.757  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:30.761  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:30.764  1041  1096 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:30.766  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:16:30.768  6442  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-06 19:16:30.781  5774  5774 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:16:30.800  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:30.819  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:16:30.820  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:30.820  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:16:30.820  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 19:16:30.824  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:16:30.828  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ce7d1e0
09-06 19:16:30.828  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:16:30.828  7015  7015 D AppUp4:CustFacade: isPhone : true
09-06 19:16:30.829  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:16:30.829  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:16:30.834  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:30.834  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:16:30.835  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:16:30.841  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:30.849  7054  7054 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:16:30.879  3337  3337 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:16:30.879  3337  3337 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:30.879  3337  3337 I LgeMiscReceiver: networkInfo.isConnected() = true
09-06 19:16:30.879  3337  3337 D PhoneState: setPdpRejectCasuse : false
,09-06 19:16:30.885  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:16:30.886  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:16:30.899  1041  1096 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:16:30.909  4326  7422 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:16:30.914  7054  7421 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:16:30.918  6934  7438 V FormManager: Network unavailable.
09-06 19:16:30.919  6934  7436 W FormManager: Network not available. Please check & try again.
09-06 19:16:30.924  7196  7196 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:30
09-06 19:16:30.925  7196  7196 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:16:30.925  7196  7196 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:16:30.927  7196  7196 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:16:30.927  7196  7196 D WeatherAncestor: connectivity changed - connection : true
09-06 19:16:30.927  7196  7196 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2f1eb5e
09-06 19:16:30.929  6934  7438 V FormManager: Network unavailable.
,09-06 19:16:30.931  7196  7196 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-06 19:16:30.931  7196  7196 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-06 19:16:30.931  7196  7196 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,09-06 19:16:30.931  7196  7196 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-06 19:16:30.931  7196  7196 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:30
09-06 19:16:30.933  4326  7440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:30.933  4326  7440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:16:31.657  1041  1972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:16:31.669  1041  1972 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 19:16:31.685  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:16:31.685  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:16:31.685  1041  1041 D Ulp_jni : JNI:system_update. Event-4
09-06 19:16:31.686  1041  1116 D BluetoothManagerService: Message: 1
09-06 19:16:31.686  1041  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-06 19:16:31.715  1041  1116 D BluetoothManagerService: Message: 20
09-06 19:16:31.715  1041  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1af388cb:true
,09-06 19:16:31.719  6957  6957 D BluetoothAdapterState: make
09-06 19:16:31.724  6957  6957 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 19:16:31.724  6957  6957 I bluedroid-qcom: init
09-06 19:16:31.725  6957  7455 I BluetoothAdapterState: Entering OffState
09-06 19:16:31.726  6957  6957 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:16:31.726  6957  6957 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:16:31.726  6957  6957 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:16:31.726  6957  6957 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:16:31.726  6957  6957 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 19:16:31.728  6957  6957 I bluedroid-qcom: get_profile_interface socket
09-06 19:16:31.728  6957  6957 I bluedroid-qcom: get_profile_interface map_client
,09-06 19:16:31.732  6957  7459 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:16:31.719  7458  7458 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:31.719  7458  7458 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:31.741  1041  1041 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 19:16:31.741  1041  1116 D BluetoothManagerService: Message: 40
09-06 19:16:31.741  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,09-06 19:16:31.744  6957  6973 I bluedroid-qcom: config_hci_snoop_log
09-06 19:16:31.748  1041  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 19:16:31.748  1041  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 19:16:31.752  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 19:16:31.752  7458  7458 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 19:16:31.752  7458  7458 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-06 19:16:31.758  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-06 19:16:31.762  6957  7455 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 19:16:31.762  6957  7455 D BluetoothAdapterProperties: Setting state to 11
09-06 19:16:31.763  6957  7455 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:16:31.764  1041  1116 D BluetoothManagerService: Message: 60
09-06 19:16:31.764  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 19:16:31.764  1041  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 19:16:31.768  7458  7458 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 19:16:31.768  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-06 19:16:31.769  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:31.773  6957  7459 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:16:31.777  1923  1923 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:31.778  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:16:31.783  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-06 19:16:31.788  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:31.792  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:31.796  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:31.804  6957  6957 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-06 19:16:31.805  6957  6957 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:31.805  6957  6957 V BluetoothPbapReceiver: ***********state = 11
09-06 19:16:31.807  6957  7459 D BluetoothAdapterProperties: Name is: G3
09-06 19:16:31.810  1041  1041 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:16:31.810  1041  1041 D BluetoothManagerService: Stored Bluetooth name: G3
,09-06 19:16:31.819  6957  7455 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 19:16:31.825  1041  1116 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:16:31.826  1041  1096 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:31.832  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:31.832  1041  1116 D Tethering: MasterInitialState.processMessage what=3
09-06 19:16:31.835  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:31.836  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:31.839  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:31.840  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:16:31.841  6442  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:16:31.843  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:31.845  5774  5774 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:16:31.850  6957  7455 D BluetoothBondStateMachine: make
09-06 19:16:31.853  6957  7455 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:31.854  6957  7476 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 19:16:31.854  6957  7455 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 19:16:31.854  6957  7455 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:31.854  6957  7455 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 19:16:31.855  6957  7455 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,09-06 19:16:31.859  6957  7455 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:31.859  5774  5774 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:16:31.905  1041  1909 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7478 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:31.919  6957  7455 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:16:31.921  1041  1096 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:31.921  6957  6957 D HeadsetService: Received start request. Starting profile...
09-06 19:16:31.922  6957  6957 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:16:31.922  6957  6957 D LGBluetoothHfpAdapter: Version 1.6
09-06 19:16:31.926  6957  6957 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:16:31.927  6957  7455 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:31.927  6957  6957 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:16:31.928  6957  6957 D HeadsetStateMachine: make
,09-06 19:16:31.928  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:31.928  1041  1096 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:31.928  1041  1096 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:31.936  6957  7455 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:16:31.940  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:16:31.940  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:31.941  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:16:31.941  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:16:31.946  6957  7455 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:31.947  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 19:16:31.951  6957  7455 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:31.951  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ce7d1e0
09-06 19:16:31.951  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:16:31.951  7015  7015 D AppUp4:CustFacade: isPhone : true
09-06 19:16:31.956  6957  7455 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:31.956  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:16:31.956  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:16:31.959  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:31.959  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:16:31.960  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:31.963  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:31.971  6957  7455 V LGMDMManager: Create singleton instance
09-06 19:16:31.971  6957  6957 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:31.971  6957  6957 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:16:31.974  6957  7455 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:16:31.975  6957  6957 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:16:31.975  6957  6957 I bluedroid-qcom: get_profile_interface handsfree
09-06 19:16:31.976  7054  7054 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:16:31.977  6957  6957 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 19:16:31.978   316   316 V AudioPolicyService: registerClient() client 0xb57f6420, uid 1002
09-06 19:16:31.978  4326  7497 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:16:31.979   316  2167 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,09-06 19:16:31.979   316  2167 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:16:31.979   316  2167 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:16:31.979  6957  6957 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:16:31.979   316  1368 V AudioFlinger: registerClient() client 0xb55814f0, pid 6957
09-06 19:16:31.980   316  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:31.980   316  1362 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:31.980  1041  2015 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:31.980  1041  2015 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:31.981  6957  6973 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:31.981  6957  6973 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 19:16:31.981  3337  3356 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:31.981  3337  3356 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:31.981   316  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:31.981   316  1363 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:31.981  1836  2685 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:31.981  3337  3355 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:31.981  3337  3355 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:31.981  1836  2685 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:31.981  4326  7498 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:31.981  1836  2685 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:31.981  6957  6974 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:31.981  1836  2685 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:31.981  6957  6974 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 19:16:31.981  6957  6957 V ToneGenerator: Create Track: 0xb4928a80
09-06 19:16:31.981  6957  6957 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 19:16:31.981  6957  6957 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 19:16:31.981  1041  2015 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:31.981  1041  2015 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:31.982   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:16:31.982   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:16:31.982   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:16:31.982   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:16:31.982   316  2167 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:16:31.982  1585  1604 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:31.982  1585  1604 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:31.982  1585  1604 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:31.982  1585  1604 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:31.982   316  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:16:31.982   316  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 19:16:31.982   316  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:16:31,.982   316  1368 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:16:31.982  6957  6957 V AudioSystem: getLatency() output 2, latency 50
09-06 19:16:31.982  6957  6957 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 19:16:31.982  6957  6957 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 19:16:31.982   316  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:16:31.982   316  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:16:31.982   316  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:16:31.982   316  1367 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:16:31.982   316  1367 V AudioFlinger: createTrack() lSessionId: 22
09-06 19:16:31.983  6957  6957 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 19:16:31.983   316   316 V AudioFlinger: acquiring 22 from 6957, for 6957
09-06 19:16:31.983   316   316 V AudioFlinger:  added new entry for 22
09-06 19:16:31.984  6957  6957 V ToneGenerator: ToneGenerator INIT OK, time: 127386
09-06 19:16:31.984  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:31.985  6957  7494 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 19:16:31.985  6957  7494 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:16:31.985  6957  7494 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:16:31.985  6957  7494 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 19:16:31.985   316  2167 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6957
09-06 19:16:31.986   316  2167 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 19:16:31.986   316  2167 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 19:16:31.986   316  2167 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 19:16:31.986   316  2167 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 19:16:31.986   316  2167 V voice   : voice_set_parameters: exit with code(0)
09-06 19:16:31.986   316  2167 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 19:16:31.986   316  2167 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 19:16:31.986  4326  7498 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:16:31.986   316  2167 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 19:16:31.986   316  2167 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 19:16:31.986   316  2167 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 19:16:31.986   316  2167 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 19:16:31.988  6957  7494 V ToneGenerator: ToneGenerator destructor
09-06 19:16:31.988  6957  7494 V ToneGenerator: stopTone
09-06 19:16:31.988  6957  7494 V ToneGenerator: Delete Track: 0xb4928a80
09-06 19:16:31.988  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:31.990  6957  6957 D A2dpService: Received start request. Starting profile...
09-06 19:16:31.991  6957  6957 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:16:31.991  1041  1978 W Process : Unable to open /proc/7499/status
09-06 19:16:31.992  6957  6957 V Avrcp   : make
09-06 19:16:31.992  6957  6957 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 19:16:31.992  6957  6957 I bluedroid-qcom: get_profile_interface avrcp
09-06 19:16:31.993  6957  7494 V AudioTrack: ~AudioTrack, releasing session id from 6957 on behalf of 6957
09-06 19:16:31.994   316  2167 V AudioFlinger: releasing 22 from 6957 for 6957
09-06 19:16:31.994   316  2167 V AudioFlinger:  decremented refcount to 0
09-06 19:16:31.994   316  2167 V AudioFlinger: purging stale effects
09-06 19:16:31.994   316  2167 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 19:16:31.994   316  2167 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 19:16:31.994   316  1267 V AudioPolicyService: AudioCommandThread() waking up
09-06 19:16:31.994   316  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 19:16:31.994   316  1267 V AudioPolicyManager: releaseOutput() 2
09-06 19:16:31.994   316  1267 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 19:16:31.994   316  2167 V AudioFlinger: PlaybackThread::Track destructor
09-06 19:16:31.994   316  2167 V AudioFlinger: removeClient_l() pid 6957, calling pid 316
09-06 19:16:32.003  6957  6957 V AudioManager: registerRemoteController: size of Media player list: 0
09-06 19:16:32.004  3337  3337 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:16:32.005  3337  3337 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:32.005  6957  6957 E AudioManager: No RCC entry present to update
09-06 19:16:32.005  6957  6957 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:16:32.007  3337  3337 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:16:32.007  6934  7503 W FormManager: Network not available. Please check & try again.
09-06 19:16:32.008  7054  7500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:32.009  6957  6957 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 19:16:32.009  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:16:32.009  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:16:32.010  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 19:16:32.010  6957  6957 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 19:16:32.013  6934  7504 V FormManager: Network unavailable.
09-06 19:16:32.015  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-06 19:16:32.058  7196  7196 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:32
,09-06 19:16:32.060  6934  7504 V FormManager: Network unavailable.
09-06 19:16:32.060  7196  7196 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:16:32.060  7196  7196 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:16:32.061  7196  7196 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:16:32.061  7196  7196 D WeatherAncestor: connectivity changed - connection : true
09-06 19:16:32.061  7196  7196 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2f1eb5e
09-06 19:16:32.062  7196  7196 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:16:32.062  7196  7196 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:16:32.062  7196  7196 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:16:32.062  7196  7196 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:16:32.062  7196  7196 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:32
09-06 19:16:32.083  6442  6442 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 19:16:32.084  6442  6471 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:16:32.101  7478  7478 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 19:16:32.101  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:32.102  7478  7478 W LG Account v2.2: No ProfileInfo entries
09-06 19:16:32.102  7478  7478 I LG Account v2.2: isEnabled: false
09-06 19:16:32.103  7478  7478 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 19:16:32.103  7478  7478 I Feature : [Lifetracker]Country: EU
09-06 19:16:32.103  7478  7478 I Feature : [Lifetracker]Operator: OPEN
,09-06 19:16:32.103  7478  7478 I Feature : [Lifetracker]Ranking support: false
09-06 19:16:32.103  7478  7478 I Feature : [Lifetracker]Comfort support: false
09-06 19:16:32.104  7478  7478 I Feature : [Lifetracker]Accessory: true
09-06 19:16:32.104  7478  7478 I Feature : [Lifetracker]Health device: true
09-06 19:16:32.104  7478  7478 I Feature : [Lifetracker]Extra Pedometer: false
09-06 19:16:32.104  7478  7478 I Feature : [Lifetracker]Blood glucose device: false
09-06 19:16:32.104  7478  7478 I Feature : [Lifetracker]Device Number: 3
09-06 19:16:32.108  1041  1978 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:16:32.108  1041  1978 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:16:32.117  6803  6803 D BluetoothPermissionRequest: onReceive
,09-06 19:16:32.119  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-06 19:16:32.119  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:32.121  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:16:32.121  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:16:32.123  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:16:32.124  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:16:32.127  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ce7d1e0
09-06 19:16:32.127  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:16:32.127  7015  7015 D AppUp4:CustFacade: isPhone : true
09-06 19:16:32.128  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:16:32.128  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:16:32.131  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:32.131  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:16:32.133  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:32.135  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:32.143  7054  7054 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:16:32.147  4326  7509 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:16:32.150  4326  7510 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:16:32.150  4326  7510 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:16:32.159  1041  1909 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 19:16:32.162  7054  7511 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:32.165  6934  7513 W FormManager: Network not available. Please check & try again.
09-06 19:16:32.165  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:16:32.168  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:16:32.169  6957  6957 I BluetoothA2dpServiceJni: classInitNative
09-06 19:16:32.169  6957  6957 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:16:32.169  6957  6957 D A2dpStateMachine: make
09-06 19:16:32.170  6957  6957 I bluedroid-qcom: get_profile_interface a2dp
09-06 19:16:32.171  6957  7517 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:16:32.173  6957  6957 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:16:32.173  6957  6957 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 19:16:32.173  3337  3337 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:16:32.174  3337  3337 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:32.174  3337  3337 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:16:32.174  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:32.174  6957  7516 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:16:32.175  6957  6957 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:16:32.178  6957  6957 D HidService: Received start request. Starting profile...
09-06 19:16:32.178  6957  6957 I bluedroid-qcom: get_profile_interface hidhost
09-06 19:16:32.178  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:32.178  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:16:32.179  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:16:32.179  6957  6957 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:16:32.181  6957  6957 D HealthService: Received start request. Starting profile...
09-06 19:16:32.182  6957  6957 I bluedroid-qcom: get_profile_interface health
09-06 19:16:32.183  6957  6957 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:16:32.183  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:32.183  6934  7514 V FormManager: Network unavailable.
09-06 19:16:32.184  6957  6957 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:16:32.187  6957  6957 D PanService: Received start request. Starting profile...
09-06 19:16:32.187  6957  6957 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:16:32.187  6957  6957 I bluedroid-qcom: get_profile_interface pan
09-06 19:16:32.190  7196  7196 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:32
09-06 19:16:32.191  6957  6957 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 19:16:32.191  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:32.191  7196  7196 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:16:32.191  7196  7196 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:16:32.192  6934  7514 V FormManager: Network unavailable.
09-06 19:16:32.192  7196  7196 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:16:32.192  7196  7196 D WeatherAncestor: connectivity changed - connection : true
09-06 19:16:32.192  7196  7196 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2f1eb5e
09-06 19:16:32.192  6957  6957 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-06 19:16:32.193  7196  7196 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:16:32.193  7196  7196 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:16:32.193  7196  7196 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:16:32.193  7196  7196 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:16:32.193  7196  7196 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:16:32
09-06 19:16:32.195  6957  6957 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:16:32.196  6957  6957 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:16:32.196  6957  6957 D BtGatt.GattService: start()
09-06 19:16:32.196  6957  6957 I bluedroid-qcom: get_profile_interface gatt
09-06 19:16:32.196  6957  6957 D BtGatt.AdvertiseManager: advertise manager created
09-06 19:16:32.202  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:32.202  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:32.203  6957  6957 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 19:16:32.203  6957  6957 V BluetoothMapService: BluetoothMapBinder()
,09-06 19:16:32.204  6957  6957 D BluetoothMapService: Received start request. Starting profile...
09-06 19:16:32.204  6957  6957 D BluetoothMapService: start()
09-06 19:16:32.207  6957  6957 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 19:16:32.207  6957  6957 D BluetoothMapEmailAppObserver: createReceiver()
09-06 19:16:32.209  6957  6957 D BluetoothMapEmailAppObserver: initObservers()
09-06 19:16:32.209  6957  6957 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 19:16:32.217  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:32.217  6957  6957 D HeadsetStateMachine: Proxy object connected
09-06 19:16:32.218  6957  6957 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 19:16:32.218  6957  6957 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-06 19:16:32.222  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:16:32.223  6957  7494 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:16:32.224  6957  7494 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:16:32.224  6957  7494 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 19:16:32.226  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:16:32.229  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:16:32.232  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:16:32.235  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:16:32.235  6957  6957 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 19:16:32.238  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 19:16:32.238  6957  6957 V BluetoothMapService: Handler(): got msg=1
09-06 19:16:32.239  6957  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:16:32.239  6957  7455 I bluedroid-qcom: enable
09-06 19:16:32.240  6957  7524 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:16:32.240  6957  7524 I bt-btu  : btu_task pending for preload complete event
09-06 19:16:32.240  6957  7455 I bt_hci_bdroid: init
09-06 19:16:32.241  6957  7455 I bt_vendor: bt-vendor : init
09-06 19:16:32.241  6957  7455 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:16:32.241  6957  7455 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:16:32.241  6957  7455 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 19:16:32.241  6957  7455 D bt_userial_mct: userial_init
,09-06 19:16:32.243  6957  7455 D bt_hci_bdroid: set_power 1
09-06 19:16:32.243  6957  7455 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:16:32.243  6957  7455 I bt_vendor: Starting hciattach daemon
09-06 19:16:32.243  6957  7455 I bt_vendor: try to set true
09-06 19:16:32.244  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:32.246  6957  6957 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-06 19:16:32.246  6957  6957 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:16:32.246  6957  6957 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:16:32.246  6957  6957 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.246  6957  6957 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 19:16:32.229  7527  7527 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:32.229  7527  7527 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:32.274  7528  7528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:16:32.316  1041  1756 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7533 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:16:32.345  7551  7551 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:16:32.356  7552  7552 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:16:32.371  7533  7533 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:16:32.382  7554  7554 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-06 19:16:32.388  1041  1972 I ActivityManager: Killing 7087:com.android.vending/u0a44 (adj 15): empty #17
,09-06 19:16:32.397  7555  7555 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-06 19:16:32.413  7556  7556 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:16:32.429  7557  7557 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:16:32.450  1041  1756 W libprocessgroup: failed to open /acct/uid_10044/pid_7087/cgroup.procs: No such file or directory
,09-06 19:16:32.451  7559  7559 I libmdmdetect: ESOC framework not supported
09-06 19:16:32.452  7559  7559 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-06 19:16:32.461  7559  7559 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 19:16:32.461  7559  7559 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 19:16:32.461  7559  7559 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 19:16:32.461  7559  7559 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 19:16:32.461  7559  7559 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 19:16:32.461  7559  7559 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 19:16:32.461  7559  7559 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-06 19:16:32.513  7559  7560 E QC-QMI  : qmi_client [7559] 14: failed to locate client data
,09-06 19:16:32.514   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 19:16:32.514   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-06 19:16:32.581  7561  7561 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 19:16:32.608  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:16:32.645  6957  7455 I bt_vendor: bluetooth satus is on
09-06 19:16:32.645  6957  7455 D bt_hci_bdroid: preload
09-06 19:16:32.645  6957  7526 D bt_userial_mct: userial_open(port:0)
09-06 19:16:32.645  6957  7526 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:16:32.649  6957  7526 I bt_vendor: Done intiailizing UART
09-06 19:16:32.650  6957  7526 I bt_vendor: Done intiailizing UART
09-06 19:16:32.650  6957  7526 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 19:16:32.650  6957  7526 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:16:32.650  6957  7524 I bt-btu  : btu_task received preload complete event
09-06 19:16:32.650  6957  7567 D bt_userial_mct: Entering userial_read_thread()
09-06 19:16:32.652  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 19:16:32.652  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 19:16:32.657  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-06 19:16:32.662  6957  7524 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:16:32.663  6957  7524 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:16:32.663  6957  7524 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:16:32.663  6957  7524 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:16:32.663  6957  7524 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:16:32.663  6957  7524 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:16:32.663  6957  7524 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:16:32.731  6957  7524 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-06 19:16:32.731  6957  7524 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0248061 
09-06 19:16:32.731  6957  7524 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0248061 
09-06 19:16:32.733   310  7216 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-06 19:16:32.734   310  7216 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
09-06 19:16:32.734   310  7216 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,09-06 19:16:32.736  1041  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-06 19:16:32.739  1041  7176 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,09-06 19:16:32.739  1041  7176 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3s973ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:32.739  1041  7176 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3s973ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:32.739  1041  7176 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:16:32.766  6957  7459 E bt-btif : Calling BTA_HhEnable
,09-06 19:16:32.766  6957  7459 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-06 19:16:32.774  6957  7459 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:16:32.776  6957  7459 D BluetoothAdapterProperties: Name is: G3
09-06 19:16:32.778  6957  7459 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:16:32.778  6957  7459 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:16:32.778  6957  7459 D bt_hci_bdroid: postload
09-06 19:16:32.779  6957  7526 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:16:32.779  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 19:16:32.779  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 19:16:32.779  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 19:16:32.785  1041  1097 W ProcessCpuTracker: Skipping unknown process pid 7466
09-06 19:16:32.786  1041  1097 W ProcessCpuTracker: Skipping unknown process pid 7467
09-06 19:16:32.786  1041  1097 W ProcessCpuTracker: Skipping unknown process pid 7473
,09-06 19:16:32.788  1041  1097 W ProcessCpuTracker: Skipping unknown process pid 7496
09-06 19:16:32.789  1041  1097 W ProcessCpuTracker: Skipping unknown process pid 7568
09-06 19:16:32.791  1041  1041 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:16:32.791  6957  7526 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:16:32.791  1041  1041 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:16:32.792  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:16:32.792  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 19:16:32.792  6957  7459 D bte_conf: Device ID record 1 : primary
09-06 19:16:32.792  6957  7459 D bte_conf:   vendorId            = 00c4
09-06 19:16:32.792  6957  7459 D bte_conf:   vendorIdSource      = 0001
09-06 19:16:32.793  6957  7459 D bte_conf:   product             = 13a1
09-06 19:16:32.793  6957  7459 D bte_conf:   version             = 1000
09-06 19:16:32.793  6957  7459 D bte_conf:   clientExecutableURL = 
09-06 19:16:32.793  6957  7459 D bte_conf:   serviceDescription  = 
09-06 19:16:32.793  6957  7459 D bte_conf:   documentationURL    = 
09-06 19:16:32.793  6957  7459 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:16:32.793  6957  7524 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 19:16:32.795  6957  7526 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:16:32.795  6957  7459 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:16:32.796  6957  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:16:32.797  6957  7455 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:16:32.797  6957  7455 D BluetoothAdapterProperties: State =  11
09-06 19:16:32.797  6957  7455 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 19:16:32.798  6957  7455 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 19:16:32.798  6957  7455 D BluetoothAdapterProperties: Setting state to 12
09-06 19:16:32.798  6957  7455 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:16:32.798  6957  7459 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:16:32.789  7572  7572 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:32.789  7572  7572 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:32.805  6957  7567 E bt_mct  : hci lib postload completed
,09-06 19:16:32.812  1041  1116 D BluetoothManagerService: Message: 60
09-06 19:16:32.812  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 19:16:32.812  1041  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-06 19:16:32.813  6957  7455 I BluetoothAdapterState: Entering On State
09-06 19:16:32.816  6957  7455 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 19:16:32.817  6957  7455 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 19:16:32.817  6957  7455 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 19:16:32.818  1836  2724 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:16:32.821  6957  7455 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 19:16:32.822  6957  7524 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:32.822  6957  7524 W bt-smp  : Plain text(LSB ~ MSB) = 0d d3 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:32.822  6957  7524 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b aa 0f bd 33 49 30 b4 0a d4 b1 b6 59 fe fa 35 
09-06 19:16:32.822  6957  7524 W bt-btm  : Stopping oneshot timer
09-06 19:16:32.833  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:32.833  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:32.833  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:32.833  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:32.833  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:32.833  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:32.833  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:32.833  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:32.836  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:32.839  6803  6828 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:16:32.839  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:16:32.843  6957  7459 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:16:32.843  1041  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:16:32.843  6957  7459 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 19:16:32.844  1041  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:16:32.845  6803  6820 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:16:32.845  6803  6820 D BluetoothPan: onBluetoothStateChange call bindService
09-06 19:16:32.846  6957  7524 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-06 19:16:32.846  6957  7524 W bt-smp  : Plain text(LSB ~ MSB) = 76 5e 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:32.846  6957  7524 W bt-smp  : Encrypted text(LSB ~ MSB) = 69 50 f7 d3 81 04 dd 2e a5 a2 37 6c 4f f6 54 c7 
09-06 19:16:32.846  6957  7524 W bt-btm  : Stopping oneshot timer
09-06 19:16:32.846  1041  1041 D BluetoothHeadset: Proxy object connected
09-06 19:16:32.853  1923  2088 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-06 19:16:32.853  1923  2088 D LEDHandler: Battery Level Remaining: 100%
09-06 19:16:32.853  1923  2088 D LEDHandler: Battery Temp: 306, mChargingStatus=5, mChargingStop=false
09-06 19:16:32.854  7380  7380 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:16:32.857  6803  6828 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:16:32.857  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:32.857  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:32.857  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:32.857  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:32.857  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:32.857  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:32.857  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:32.857  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:32.860  6957  7524 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:32.860  6957  7524 W bt-smp  : Plain text(LSB ~ MSB) = e2 21 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:32.860  6957  7524 W bt-smp  : Encrypted text(LSB ~ MSB) = 85 16 fd a3 bb 61 ee 7b 40 07 c3 d0 19 af 83 b2 
09-06 19:16:32.860  1585  1585 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-06 19:16:32.860  1585  1585 I [SystemUI]LGPowerUI: On Skip Timer : true
09-06 19:16:32.861  6957  7524 W bt-btm  : Stopping oneshot timer
,09-06 19:16:32.865  1041  1527 D WifiController: battery changed pluggedType: 2
09-06 19:16:32.866  1041  1041 D BluetoothA2dp: Proxy object connected
09-06 19:16:32.866  1836  2460 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:16:32.867  6957  7494 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:16:32.868  7590  7590 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-06 19:16:32.868  6957  7455 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-06 19:16:32.869  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:32.870  1585  1585 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
,09-06 19:16:32.870  1585  1585 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-06 19:16:32.871  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:16:32.871  1836  2685 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:16:32.871  1585  1585 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-06 19:16:32.873  6803  6803 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:16:32.873  6803  6803 D PanProfile: Bluetooth service connected
09-06 19:16:32.873  6957  7524 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:32.873  6957  7524 W bt-smp  : Plain text(LSB ~ MSB) = 20 58 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:32.873  6957  7524 W bt-smp  : Encrypted text(LSB ~ MSB) = ae 34 9e 8b 52 9c 6b 73 44 02 73 b9 19 d3 97 c5 
09-06 19:16:32.873  6957  7524 W bt-btm  : Stopping oneshot timer
09-06 19:16:32.875  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:16:32.875  6803  6820 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:16:32.877  6803  6803 D BluetoothInputDevice: Proxy object connected
09-06 19:16:32.877  6803  6803 D HidProfile: Bluetooth service connected
09-06 19:16:32.880  1041  1041 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 19:16:32.880  1041  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 19:16:32.880  1041  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 19:16:32.881  6803  6803 D BluetoothMap: Proxy object connected
09-06 19:16:32.881  6803  6803 D MapProfile: Bluetooth service connected
09-06 19:16:32.881  6803  6803 D BluetoothMap: getConnectedDevices()
09-06 19:16:32.881  1041  1116 D BluetoothManagerService: Message: 40
09-06 19:16:32.881  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 19:16:32.882  1923  1923 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.883  6957  7524 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:32.883  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:16:32.883  6957  7524 W bt-smp  : Plain text(LSB ~ MSB) = 29 83 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:32.883  6957  7524 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d 1e 67 9d 47 c9 16 66 bc 36 a8 52 4a 2b 8e 9e 
09-06 19:16:32.883  6957  7524 W bt-btm  : Stopping oneshot timer
,09-06 19:16:32.883  6957  7589 V BluetoothMapService: getConnectedDevices()
09-06 19:16:32.884  1923  2120 D LGBluetoothAPIService: Message: 1
09-06 19:16:32.884  1923  2120 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 19:16:32.888  6633  6633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:16:32.892  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:32.894  1923  2120 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-06 19:16:32.895  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:32.897  6957  6957 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.897  6957  6957 D BluetoothMapService: STATE_ON
09-06 19:16:32.899  6803  6803 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 19:16:32.899  6957  6957 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 19:16:32.899  6957  6957 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 19:16:32.900  1923  1923 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-06 19:16:32.900  1923  2120 D LGBluetoothAPIService: Message: 100
09-06 19:16:32.900  1923  2120 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 19:16:32.903  1041  1116 D BluetoothManagerService: Message: 30
09-06 19:16:32.905  6803  6803 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-06 19:16:32.909  1041  1116 D BluetoothManagerService: Message: 30
09-06 19:16:32.911  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:32.911  6957  6957 V BluetoothPbapService: Pbap Service onCreate
09-06 19:16:32.911  6957  6957 V BluetoothPbapService: Starting PBAP service
09-06 19:16:32.912  6957  6957 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 19:16:32.913  6957  6957 V BluetoothPbapService: Pbap Service onBind
09-06 19:16:32.913  6957  6957 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.913  6957  6957 V BluetoothPbapService: state: 12
09-06 19:16:32.914  6957  6957 V BluetoothMapService: Handler(): got msg=1
09-06 19:16:32.914  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-06 19:16:32.914  6957  6957 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 19:16:32.915  6957  6957 V BluetoothPbapService: Handler(): got msg=1
09-06 19:16:32.915  6957  6957 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 19:16:32.915  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:16:32.916  6957  7591 D BluetoothMapMasInstance: MAS initSocket()
09-06 19:16:32.917  6957  7591 D BluetoothMapMasInstance:   masId = 00
09-06 19:16:32.917  6957  7591 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 19:16:32.917  6957  7591 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 19:16:32.917  6957  7591 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 19:16:32.917  6957  7592 V BluetoothPbapService: Pbap Service initSocket
09-06 19:16:32.918  6803  6803 D BluetoothA2dp: Proxy object connected
09-06 19:16:32.919  6803  6803 D A2dpProfile: Bluetooth service connected
,09-06 19:16:32.920  1041  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:32.921  6957  6957 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:16:32.921  6957  6957 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.921  6957  6957 V BluetoothPbapReceiver: ***********state = 12
09-06 19:16:32.922  1041  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:32.922  6957  7592 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:32.923  6957  7591 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:32.923  6957  7592 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 19:16:32.923  6957  7592 V BluetoothPbapService: Succeed to create listening socket 
09-06 19:16:32.924  6957  7592 V BluetoothPbapService: Accepting socket connection...
09-06 19:16:32.924  6957  7591 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 19:16:32.924  6957  7591 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 19:16:32.924  6957  7591 D BluetoothMapMasInstance: Accepting socket connection...
09-06 19:16:32.925  6803  6803 D BluetoothHeadset: Proxy object connected
09-06 19:16:32.925  6957  7459 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:16:32.925  6957  7459 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 19:16:32.925  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:32.926  2168  2168 D c       : Getting all permits...
09-06 19:16:32.926  2168  2168 D a       : Opening database...
09-06 19:16:32.926  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:32.927  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:32.929  6803  6803 D HeadsetProfile: Bluetooth service connected
09-06 19:16:32.930  2168  2168 D a       : Opening database auth.proximity.permit_store...
09-06 19:16:32.930  6803  6803 D BluetoothPbap: Proxy object connected
09-06 19:16:32.930  6803  6803 D PbapServerProfile: Bluetooth service connected
09-06 19:16:32.930  2168  2168 D a       : Closing database...
,09-06 19:16:32.936  6803  6803 D DockEventReceiver: finishStartingService: stopping service
09-06 19:16:32.943  6803  6803 D BluetoothPermissionRequest: onReceive
,09-06 19:16:32.944  6803  6803 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:16:32.946  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:16:32.949  6957  6957 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 19:16:32.950  6957  6957 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 19:16:32.955  6957  6957 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 19:16:32.973  6957  6957 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:16:32.973  6957  6957 V BtOppService: onCreate
,09-06 19:16:32.977  6957  6957 V BluetoothOppNotification: send message
09-06 19:16:32.980  6957  6957 V BtOppService: Starting RfcommListener
09-06 19:16:32.984  6957  6957 D BluetoothOppPreference: Dumping Names:  
09-06 19:16:32.984  6957  6957 D BluetoothOppPreference: {}
09-06 19:16:32.984  6957  6957 D BluetoothOppPreference: Dumping Channels:  
09-06 19:16:32.984  6957  6957 D BluetoothOppPreference: {}
09-06 19:16:32.985  6957  6957 V BtOppService: onStartCommand
09-06 19:16:32.986  6957  7600 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:16:32.988  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:32.988  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-06 19:16:32.992  6957  6957 V BluetoothOppNotification: new notify threadi!
09-06 19:16:32.993  6957  6957 V BluetoothOppNotification: send delay message
09-06 19:16:32.993  6957  7597 V BtOppService: Deleted complete outbound shares, number =  0
09-06 19:16:32.993  6957  6957 V BtOppService: start RfcommListener
09-06 19:16:32.994  6957  7601 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:16:32.995  6957  7601 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ad9522b on behalf of 
09-06 19:16:32.996  6957  7601 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:16:32.996  6957  6957 V BtOppService: RfcommListener started
09-06 19:16:32.997  6957  6957 V BtOppService: ContentObserver received notification
09-06 19:16:32.997  6957  7602 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 19:16:33.000  1041  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:33.002  6957  7597 V BtOppService: Deleted complete inbound failed shares, number = 0
,09-06 19:16:33.003  6957  7597 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 19:16:33.004  6957  7602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:33.005  6957  7597 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dd34688 on behalf of 
09-06 19:16:33.008  6957  7602 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-06 19:16:33.008  6957  7602 V BtOppRfcommListener: Started RFCOMM listener....
09-06 19:16:33.017  6957  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:16:33.017  6957  7601 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:16:33.018  6957  7602 I BtOppRfcommListener: Accept thread started.
09-06 19:16:33.018  6957  7602 V BtOppRfcommListener: Accepting connection...
,09-06 19:16:33.020  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
,09-06 19:16:33.020  6957  6957 V BluetoothFtpService: Ftp Service onCreate
09-06 19:16:33.020  6957  6957 I BluetoothFtpService: Ftp Service onCreate
09-06 19:16:33.020  6957  6957 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:16:33.020  6957  6957 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:33.021  6957  6957 V BluetoothFtpService: Starting Listening on sockets
09-06 19:16:33.021  6957  6957 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:16:33.021  6957  6957 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:16:33.021  6957  6957 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:16:33.021  6957  6957 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:33.021  6957  6957 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 19:16:33.021  6957  6957 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:16:33.022  6957  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a01d446 on behalf of 
09-06 19:16:33.023  6957  7601 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2598e607 on behalf of 
09-06 19:16:33.023  6957  6957 V BtOppService: ContentObserver received notification
09-06 19:16:33.023  6957  6957 V BluetoothFtpService: Handler(): got msg=1
09-06 19:16:33.024  6957  7601 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:16:33.024  6957  6957 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 19:16:33.024  6957  6957 V BluetoothFtpService: Ftp Service initSocket
09-06 19:16:33.025  6957  7600 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:16:33.025  6957  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:16:33.026  6957  7601 V BluetoothOppNotification: outbound notification was removed.
09-06 19:16:33.026  6957  7601 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:16:33.027  1041  1972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:33.032  6957  6957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:33.035  6957  6957 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-06 19:16:33.035  6957  6957 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 19:16:33.038  6957  7603 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 19:16:33.050  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:33.050  6957  6957 V BluetoothSapService: Sap Service onCreate
,09-06 19:16:33.052  6957  6957 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:33.052  6957  6957 V BluetoothSapService: state: 12
09-06 19:16:33.052  6957  6957 V BluetoothSapService: Starting SAP server process
09-06 19:16:33.053  6957  6957 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 19:16:33.039  7604  7604 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:33.039  7604  7604 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:33.056  6957  7605 V BluetoothSapService: Sap Service initRfcommSocket
09-06 19:16:33.057  1041  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:33.058  6957  7605 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:33.060  6957  7605 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 19:16:33.061  6957  7605 V BluetoothSapService: Succeed to create listening socket 
09-06 19:16:33.061  6957  7605 V BluetoothSapService: Accepting socket connection...
09-06 19:16:33.064  7604  7604 V BT_SAP  : Event pipe created
09-06 19:16:33.065  7604  7604 V BT_SAP  : create_server_socket qcom.sap.server
09-06 19:16:33.065  7604  7604 V BT_SAP  : created socket fd 6
,09-06 19:16:33.093  7231  7264 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-06 19:16:33.136  1041  1889 I art     : Explicit concurrent mark sweep GC freed 93391(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.847ms total 110.184ms
,09-06 19:16:33.137  6957  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15d3dba3 on behalf of 
,09-06 19:16:33.137  6957  7600 V BluetoothOppNotification: update too frequent, put in queue
,09-06 19:16:33.138  6957  7601 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b325ea0 on behalf of 
,09-06 19:16:33.138  6957  7600 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-06 19:16:33.139  6957  7601 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-06 19:16:33.143  6957  7601 V BluetoothOppNotification: inbound notification was removed.
09-06 19:16:33.143  6957  7601 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:16:33.146  6957  7601 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d073a59 on behalf of 
09-06 19:16:33.730  1041  1521 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:33.730  1041  1521 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
,09-06 19:16:33.766  1041  1522 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 19:16:33.773  1041  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 19:16:33.937  1041  2005 I ActivityManager: Killing 7380:com.lge.bnr/1000 (adj 15): empty #17
,09-06 19:16:33.971  1041  2015 W libprocessgroup: failed to open /acct/uid_1000/pid_7380/cgroup.procs: No such file or directory
,09-06 19:16:33.994  6957  6957 V BluetoothOppNotification: new notify threadi!
09-06 19:16:33.994  6957  6957 V BluetoothOppNotification: send delay message
,09-06 19:16:34.000  6957  7618 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 19:16:34.003  6957  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29b1261e on behalf of 
,09-06 19:16:34.005  6957  7618 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-06 19:16:34.009  6957  7618 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-06 19:16:34.020  6957  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@133e8eff on behalf of 
,09-06 19:16:34.021  6957  7618 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-06 19:16:34.023  6957  7618 V BluetoothOppNotification: outbound notification was removed.
09-06 19:16:34.023  6957  7618 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:16:34.024  6957  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@196ec4cc on behalf of 
,09-06 19:16:34.025  6957  7618 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:16:34.027  6957  7618 V BluetoothOppNotification: inbound notification was removed.
09-06 19:16:34.027  6957  7618 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-06 19:16:34.029  6957  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15e82315 on behalf of 
09-06 19:16:34.351  1041  1056 I ActivityManager: Killing 6753:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-06 19:16:34.382  6884  6884 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-06 19:16:34.383  6884  6884 W System.err: android.os.DeadObjectException
09-06 19:16:34.383  6884  6884 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:16:34.383  6884  6884 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:16:34.383  6884  6884 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 19:16:34.383  6884  6884 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 19:16:34.383  6884  6884 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:16:34.383  6884  6884 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:16:34.383  6884  6884 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:16:34.383  6884  6884 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:16:34.383  6884  6884 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:16:34.383  6884  6884 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:16:34.383  6884  6884 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:34.383  6884  6884 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:34.383  6884  6884 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:16:34.383  6884  6884 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:16:34.384  6884  6884 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 19:16:34.384  6884  6884 W System.err: android.os.DeadObjectException
09-06 19:16:34.384  6884  6884 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:16:34.384  6884  6884 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:16:34.384  6884  6884 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 19:16:34.384  6884  6884 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 19:16:34.384  6884  6884 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:16:34.384  6884  6884 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:16:34.384  6884  6884 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:16:34.384  6884  6884 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:16:34.384  6884  6884 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:16:34.385  6884  6884 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:16:34.385  6884  6884 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:34.385  6884  6884 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:34.385  6884  6884 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:16:34.385  6884  6884 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:16:34.385  6884  6884 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-06 19:16:34.385  6884  6884 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-06 19:16:34.419  1041  2005 W libprocessgroup: failed to open /acct/uid_1000/pid_6753/cgroup.procs: No such file or directory
09-06 19:16:34.419  1041  2005 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-06 19:16:34.426  6884  6884 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-06 19:16:34.426  6884  6884 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 19:16:34.480  1041  1946 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7619 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:16:34.504  6884  6884 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 19:16:34.574  7619  7619 D UEI.SmartControl: Quickset Services start...
09-06 19:16:34.577  7619  7619 I UEI.SmartControl: Manufacture = LGE
,09-06 19:16:34.577  7619  7619 D UEI.SmartControl: Id = LGNevo
,09-06 19:16:34.579  7619  7619 D UEI.SmartControl: File observer start...
,09-06 19:16:34.581  7619  7619 E UEI.SmartControl: IR Port is disabled: false
09-06 19:16:34.581  7619  7619 D UEI.SmartControl: Starting file observer...
,09-06 19:16:34.581  7619  7619 D UEI.SmartControl: Extracting JNI libs...
09-06 19:16:34.582  7619  7619 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-06 19:16:34.676  7619  7619 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-06 19:16:34.676  7619  7619 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-06 19:16:34.677  7619  7619 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-06 19:16:34.701  1041  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:16:34.701  1041  2034 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@38148e12 mBinding = false
,09-06 19:16:34.710  7619  7619 I UEI.SmartControl: --- Selecting new region: 6
09-06 19:16:34.711  7619  7619 I UEI.SmartControl: Model = LG-D855
09-06 19:16:34.713  7619  7619 D UEI.SmartControl: QS Service created
,09-06 19:16:34.729  7619  7619 I UEI.SmartControl: Service initServices...
09-06 19:16:34.730  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:16:34.730  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:16:34.730  1041  1041 D Ulp_jni : JNI:system_update. Event-4
09-06 19:16:34.731  1041  1116 D BluetoothManagerService: Message: 2
09-06 19:16:34.731  1041  1116 D BluetoothManagerService: Sending off request.
09-06 19:16:34.732  6957  7588 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 19:16:34.733  6957  7455 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 19:16:34.733  6957  7455 D BluetoothAdapterProperties: Setting state to 13
09-06 19:16:34.733  6957  7455 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:16:34.734  6957  7455 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:16:34.734  6957  7455 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:16:34.736  6957  7459 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:16:34.737  6957  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:16:34.737  6957  7455 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:16:34.738  6957  7603 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:34.739  6957  7591 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 19:16:34.739  6957  7591 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:34.739  6957  7591 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 19:16:34.739  6957  7591 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 19:16:34.739  6957  7591 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 19:16:34.739  6957  7591 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 19:16:34.739  6957  7591 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 19:16:34.739  6957  7591 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 19:16:34.739  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 19:16:34.741  6957  7524 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 19:16:34.741  6957  7602 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:34.741  6957  7605 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:34.742  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:34.742  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:34.742  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:34.742  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:34.742  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:34.742  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:34.742  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:34.742  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:34.742  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:34.742  6957  7592 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:16:34.742  1041  1116 D BluetoothManagerService: Message: 60
09-06 19:16:34.742  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 19:16:34.742  1041  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 19:16:34.743  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:34.743  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:34,.745  6957  6957 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:34.745  6957  6957 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:16:34.747  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:16:34.747  1923  1923 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:34.748  6957  6957 V BtOppService: Receiver DISABLED_ACTION 
09-06 19:16:34.748  6957  6957 V BluetoothMapService: Handler(): got msg=4
09-06 19:16:34.748  6957  6957 D BluetoothMapService: MAP Service closeService in
,09-06 19:16:34.748  6957  6957 D BluetoothMapMasInstance: MAP Service shutdown
09-06 19:16:34.748  6957  6957 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:16:34.748  6957  6957 V BluetoothMapService: MAP Service closeService out
,09-06 19:16:34.749  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:34.749  6957  6957 I BtOppRfcommListener: stopping Accept Thread
09-06 19:16:34.749  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-06 19:16:34.749  6957  6957 V BtOppRfcommListener: close mBtServerSocket
09-06 19:16:34.749  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:34.749  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:34.749  6957  6957 V BtOppRfcommListener: waiting for thread to terminate
09-06 19:16:34.750  6957  7602 I BtOppRfcommListener: BluetoothSocket listen thread finished,
09-06 19:16:34.750  6957  6957 V BtOppRfcommListener: done waiting for thread to terminate
09-06 19:16:34.750  6957  7524 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:34.750  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:34.750  6957  7524 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:34.751  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-06 19:16:34.751  6957  7524 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:34.751  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 19:16:34.751  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 19:16:34.751  6957  7524 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:16:34.752  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:34.752  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:34.752  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:34.752  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:34.752  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-06 19:16:34.752  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:16:34.752  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:34.752  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:34.752  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:34.753  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:16:34.753  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:34.754  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:34.755  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:34.756  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-06 19:16:34.760  7619  7619 D UEI.SmartControl: QS start get config
09-06 19:16:34.764  6957  6957 V BtOppService: onDestroy
,09-06 19:16:34.766  6957  6957 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 19:16:34.768  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:16:34.771  6957  6957 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:16:34.771  6957  6957 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:34.771  6957  6957 V BluetoothPbapReceiver: ***********state = 13
09-06 19:16:34.772  6957  6957 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 19:16:34.773  6803  6803 D DockEventReceiver: finishStartingService: stopping service
09-06 19:16:34.773  6957  6957 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:34.773  6957  6957 V BluetoothPbapService: state: 13
09-06 19:16:34.774  6957  6957 V BluetoothPbapService: Pbap Service closeService in
09-06 19:16:34.776  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:34.779  6957  6957 V BluetoothPbapService: successfully stopped pbap service
09-06 19:16:34.780  6957  6957 V BluetoothPbapService: Pbap Service closeService out
09-06 19:16:34.780  6957  6957 V BluetoothPbapService: Pbap Service onDestroy
09-06 19:16:34.780  6957  6957 V BluetoothPbapService: Pbap Service closeService in
09-06 19:16:34.780  6957  6957 V BluetoothPbapService: Pbap Service closeService out
09-06 19:16:34.780  6957  6957 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 19:16:34.781  6803  6803 D BluetoothPbap: Proxy object disconnected
09-06 19:16:34.781  6803  6803 D PbapServerProfile: Bluetooth service disconnected
09-06 19:16:34.784  6803  6803 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 19:16:34.787  6803  6803 D BluetoothPermissionRequest: onReceive
09-06 19:16:34.787  6803  6803 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 19:16:34.792  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:16:34.794  6957  6957 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-06 19:16:34.795  6957  6957 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-06 19:16:34.795  6957  6957 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 19:16:34.798  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:34.798  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-06 19:16:34.798  6957  6957 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:16:34.798  6957  6957 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:34.799  6957  6957 V BluetoothFtpService: Ftp Service closeService
09-06 19:16:34.799  6957  6957 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 19:16:34.801  6957  6957 V BluetoothFtpService: successfully stopped ftp service
09-06 19:16:34.801  6957  6957 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-06 19:16:34.801  6957  6957 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:16:34.801  6957  6957 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:16:34.801  6957  6957 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:34.801  6957  6957 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 19:16:34.801  6957  6957 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:16:34.802  6957  6957 V BluetoothFtpService: Ftp Service onDestroy
09-06 19:16:34.802  6957  6957 V BluetoothFtpService: Ftp Service closeService
09-06 19:16:34.804  6957  6957 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:34.804  6957  6957 V BluetoothSapService: state: 13
09-06 19:16:34.804  6957  6957 V BluetoothSapService: Stopping SAP server process
09-06 19:16:34.806  6957  6957 V BluetoothSapService: Sap Service closeSapService in
09-06 19:16:34.806  6957  6957 V BluetoothSapService: Close listen Socket : 
09-06 19:16:34.806  6957  6957 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:16:34.806  6957  6957 V BluetoothSapService: Close sapd  Socket : 
09-06 19:16:34.808  6957  6957 V BluetoothSapService: Sap Service closeSapService out
09-06 19:16:34.808  6957  6957 V BluetoothSapService: Sap Service onDestroy
09-06 19:16:34.808  6957  6957 V BluetoothSapService: Sap Service closeSapService in
09-06 19:16:34.808  6957  6957 V BluetoothSapService: Close listen Socket : 
09-06 19:16:34.808  6957  6957 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:16:34.808  6957  6957 V BluetoothSapService: Close sapd  Socket : 
09-06 19:16:34.808  6957  6957 V BluetoothSapService: Sap Service closeSapService out
09-06 19:16:34.845  7619  7619 D UEI.SmartControl: Loading JNI Libs...
,09-06 19:16:35.242  7619  7619 I UEI.SmartControl: Supports setup maps: true
,09-06 19:16:35.251  7619  7619 D UEI.SmartControl: QS start statue = true Error code = 0
,09-06 19:16:35.252  7619  7619 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:16:35.252  7619  7619 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:16:35.252  7619  7619 I UEI.SmartControl: ### init IR Blaster...
09-06 19:16:35.258  7619  7619 D serial_port: Configuring serial port
09-06 19:16:35.262  7619  7619 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:16:35.265  7619  7619 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:16:35.266  7619  7619 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:16:35.266  7619  7619 I UEI.SmartControl: Get version...
,09-06 19:16:35.286  7619  7657 D UEI.SmartControl: serial port data available: 21
,09-06 19:16:35.318  7619  7619 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-06 19:16:35.318  7619  7619 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-06 19:16:35.319  7619  7619 I UEI.SmartControl: QS saving settings...
,09-06 19:16:35.321  7619  7619 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:16:35.354  7619  7657 D UEI.SmartControl: serial port data available: 4
,09-06 19:16:35.395  7619  7619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 19:16:35.402  7619  7660 I UEI.SmartControl: Device manager: loading config....
09-06 19:16:35.403  7619  7660 D UEI.SmartControl: ----------- loading internal config...
09-06 19:16:35.410  7619  7619 E UEI.SmartControl: Services init done
09-06 19:16:35.410  7619  7619 D UEI.SmartControl: QS Service init finished
,09-06 19:16:35.414  7619  7619 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:16:35.414  7619  7619 D UEI.SmartControl: QS Service version code: 201091
09-06 19:16:35.416  7619  7619 D UEI.SmartControl: Service requested: Control
09-06 19:16:35.419  7619  7660 E UEI.SmartControl: Loading SETTINGS...
09-06 19:16:35.421  7619  7619 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 19:16:35.424  1041  2005 I ActivityManager: Killing 6884:com.lge.qremote/u0a112 (adj 15): empty #17
,09-06 19:16:35.438  7619  7660 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-06 19:16:35.449  7619  7659 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-06 19:16:35.449  7619  7659 D UEI.SmartControl: -----service ready thread exits
,09-06 19:16:35.485  1041  1933 W libprocessgroup: failed to open /acct/uid_10112/pid_6884/cgroup.procs: No such file or directory
,09-06 19:16:35.502  7619  7619 D UEI.SmartControl: Internal service binding...
,09-06 19:16:35.667  6957  7459 D bt_hci_bdroid: cleanup
,09-06 19:16:35.676  6957  7526 I bt_lpm  : LPM is already off!!!
09-06 19:16:35.677  6957  7567 I bt_userial_mct: exiting userial_read_thread
09-06 19:16:35.677  6957  7567 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:16:35.678  6957  7524 W bt-btif : ag scb idx 1 not allocated
09-06 19:16:35.678  6957  7524 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:16:35.678  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:35.678  6957  7524 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:35.678  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:35.678  6957  7524 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:35.678  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:35.678  6957  7524 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:16:35.679  6957  7524 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:16:35.679  6957  7524 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:16:35.682  6957  7459 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:16:35.682  6957  7526 I bt_vendor: hw_epilog_process
09-06 19:16:35.687  6957  7459 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 19:16:35.687  6957  7459 D bt_userial_mct: userial_close
,09-06 19:16:35.691  6957  7459 E bt_userial_mct: pthread_join() FAILED result:3
09-06 19:16:35.691  6957  7459 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-06 19:16:35.698  6957  7459 D bt_hci_bdroid: set_power 0
09-06 19:16:35.699  6957  7459 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:16:35.699  6957  7459 I bt_vendor: bluetooth satus is on
09-06 19:16:35.699  6957  7459 I bt_vendor: bt-vendor : resetting BT status
09-06 19:16:35.700  6957  7459 I bt_vendor: Starting hciattach daemon
09-06 19:16:35.700  6957  7459 I bt_vendor: try to set false
,09-06 19:16:35.703  6957  7459 I bt_vendor: Starting hciattach daemon
09-06 19:16:35.704  6957  7459 I bt_vendor: try to set false
09-06 19:16:35.704  6957  7459 I bt_vendor: cleanup
09-06 19:16:35.705  6957  7524 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:16:35.705  6957  7459 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:16:35.706  6957  7459 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:16:35.707  6957  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:16:35.714  6957  6957 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:16:35.722  6957  6957 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:16:35.722  6957  6957 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:16:35.722  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:35.724  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:16:35.725  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:16:35.725  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-06 19:16:35.725  1041  1041 D BluetoothHeadset: Proxy object disconnected
09-06 19:16:35.725  1041  1041 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:16:35.726  6957  7455 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-06 19:16:35.728  6957  7494 D HeadsetStateMachine: Exit Disconnected: -1
09-06 19:16:35.730  6957  6957 D A2dpService: Received stop request...Stopping profile...
09-06 19:16:35.731  6957  7516 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:16:35.733  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 19:16:35.734  6957  6957 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 19:16:35.734  6957  6957 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:16:35.734  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:35.737  6957  6957 D HidService: Received stop request...Stopping profile...
09-06 19:16:35.737  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:35.739  6957  6957 D HealthService: Received stop request...Stopping profile...
09-06 19:16:35.739  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
,09-06 19:16:35.742  1041  1041 D BluetoothA2dp: Proxy object disconnected
09-06 19:16:35.742  1041  1041 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:16:35.745  6957  6957 D PanService: Received stop request...Stopping profile...
09-06 19:16:35.745  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:35.746  6957  6957 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:16:35.747  6957  6957 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:16:35.747  6957  6957 D BtGatt.GattService: stop()
09-06 19:16:35.747  6957  6957 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:16:35.749  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:35.750  6957  6957 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:16:35.750  6957  6957 D BluetoothMapService: stop()
09-06 19:16:35.751  6957  6957 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 19:16:35.751  6957  6957 D BluetoothMapEmailAppObserver: removeReceiver()
,09-06 19:16:35.755  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f1eb5e
09-06 19:16:35.757  6957  6957 D HeadsetStateMachine: Unbinding service...
09-06 19:16:35.758  6957  6957 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:16:35.758  6957  6957 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:16:35.758  6957  6957 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:16:35.758  6957  6957 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:16:35.759  6957  6957 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:16:35.759  6957  6957 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:16:35.759  6957  6957 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:16:35.759  6957  6957 I BluetoothA2dpServiceJni: cleanupNative
09-06 19:16:35.759  6957  7517 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:16:35.760  6957  6957 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:16:35.760  6957  6957 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:16:35.760  6957  6957 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:16:35.760  6957  6957 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:16:35.761  6957  6957 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:16:35.761  6957  6957 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:16:35.761  6957  6957 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:16:35.761  6957  6957 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:16:35.761  6957  6957 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:16:35.767  6957  6957 V BluetoothMapService: Handler(): got msg=4
,09-06 19:16:35.767  6957  6957 D BluetoothMapService: MAP Service closeService in
09-06 19:16:35.767  6957  6957 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:16:35.767  6957  6957 V BluetoothMapService: MAP Service closeService out
09-06 19:16:35.772  6957  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:16:35.772  6957  7455 D BluetoothAdapterProperties: Setting state to 10
09-06 19:16:35.772  6957  7455 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:16:35.773  6957  6957 D BluetoothMapService: cleanup()
09-06 19:16:35.773  6957  6957 D BluetoothMapService: MAP Service closeService in
09-06 19:16:35.773  6957  6957 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:16:35.773  6957  6957 V BluetoothMapService: MAP Service closeService out
09-06 19:16:35.774  1041  1116 D BluetoothManagerService: Message: 60
09-06 19:16:35.774  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 19:16:35.774  1041  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-06 19:16:35.775  6957  7455 I BluetoothAdapterState: Entering OffState
09-06 19:16:35.775  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:35.776  6803  6820 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:16:35.776  1041  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:16:35.777  1041  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:35.777  6803  6820 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:16:35.778  6803  6820 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:16:35.778  6803  6820 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:35.779  6803  6820 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:16:35.782  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:35.784  1836  2724 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:16:35.784  6803  6820 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:16:35.785  1041  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 19:16:35.785  1041  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 19:16:35.787  1041  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 19:16:35.787  1041  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 19:16:35.787  1041  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@38148e12 mBinding = false
09-06 19:16:35.788  1041  1116 D BluetoothManagerService: Sending unbind request.
09-06 19:16:35.792  6957  7459 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 19:16:35.795  6957  6957 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:16:35.795  6957  6957 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:16:35.796  6957  6957 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:16:35.796  6957  6957 I art     : --- WEIRD: removing null entry 248
09-06 19:16:35.796  6957  6957 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-06 19:16:35.796  6957  6957 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 19:16:35.797  6957  6957 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 19:16:35.799  1041  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 19:16:35.801  6957  6957 I art     : System.exit called, status: 0
09-06 19:16:35.801  6957  6957 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:16:35.820   316  2167 V AudioFlinger: 6957 died, releasing its sessions
09-06 19:16:35.820   316  2167 V AudioFlinger:  pid 1836 @ 0
09-06 19:16:35.820   316  2167 V AudioFlinger:  pid 3337 @ 1
09-06 19:16:35.820   316  2167 V AudioFlinger:  pid 3337 @ 2
,09-06 19:16:35.824  1923  1923 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-06 19:16:35.825  1923  2120 D LGBluetoothAPIService: Message: 101
09-06 19:16:35.825  1923  2120 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-06 19:16:35.825  1923  2120 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-06 19:16:35.825  1923  2120 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-06 19:16:35.826  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 19:16:35.829  1041  2015 I ActivityManager: Process com.android.bluetooth (pid 6957) has died
09-06 19:16:35.829  1041  2015 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-06 19:16:35.829  1041  2015 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
09-06 19:16:35.836  1923  1923 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:35.839  1923  2120 D LGBluetoothAPIService: Message: 2
09-06 19:16:35.839  1923  2120 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-06 19:16:35.840  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:35.841  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:35.841  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:16:35.846  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 19:16:35.847  6803  6803 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 19:16:35.850  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 19:16:35.879  1585  1585 D BluetoothAdapter: 861870161: getState() :  mService = null. Returning STATE_OFF
09-06 19:16:35.879  1585  1585 D BluetoothAdapter: 861870161: getState() :  mService = null. Returning STATE_OFF
,09-06 19:16:35.899  1041  1056 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7673 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 19:16:35.902  6803  6803 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:16:35.961  7673  7673 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 19:16:35.962  7673  7673 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:16:35.962  7673  7673 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-06 19:16:35.963  7673  7673 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:16:35.985  7673  7673 D BluetoothAdapterApp: Loading JNI Library
,09-06 19:16:36.022  7673  7673 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1c7c3186 Instance Count = 1
,09-06 19:16:36.029  7673  7673 D BluetoothAdapterApp: onCreate
,09-06 19:16:36.056  7673  7673 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-06 19:16:36.056  7673  7673 D ProfileConfigQcom: Adding HeadsetService
,09-06 19:16:36.056  7673  7673 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-06 19:16:36.057  7673  7673 D ProfileConfigQcom: Adding A2dpService
,09-06 19:16:36.057  7673  7673 D ProfileConfigQcom: [BTUI] HidService is supported
,09-06 19:16:36.057  7673  7673 D ProfileConfigQcom: Adding HidService
09-06 19:16:36.057  7673  7673 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-06 19:16:36.058  7673  7673 D ProfileConfigQcom: Adding HealthService
,09-06 19:16:36.058  7673  7673 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-06 19:16:36.059  7673  7673 D ProfileConfigQcom: [BTUI] PanService is supported
,09-06 19:16:36.059  7673  7673 D ProfileConfigQcom: Adding PanService
09-06 19:16:36.059  7673  7673 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 19:16:36.060  7673  7673 D ProfileConfigQcom: Adding GattService
09-06 19:16:36.060  7673  7673 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-06 19:16:36.060  7673  7673 D ProfileConfigQcom: Adding BluetoothMapService
09-06 19:16:36.061  7673  7673 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 19:16:36.062  7673  7673 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-06 19:16:36.063  7673  7673 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:36.064  7673  7673 V BluetoothPbapReceiver: ***********state = 10
,09-06 19:16:36.066  7673  7673 V LGMDMManagerInternal: Create singleton instance
,09-06 19:16:36.162  7673  7673 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-06 19:16:36.165  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:16:36.165  7673  7673 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 19:16:36.174  1923  1923 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-06 19:16:36.175  1923  2120 D LGBluetoothAPIService: Message: 100
09-06 19:16:36.175  1923  2120 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 19:16:36.187  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-06 19:16:36.194  6803  6803 D BluetoothPermissionRequest: onReceive
09-06 19:16:36.197  6803  6803 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:16:36.198  6803  6803 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 19:16:36.200  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:16:36.205  7673  7673 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-06 19:16:36.210  7673  7673 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:36.214  7673  7673 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:16:36.214  7673  7673 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:16:36.215  7673  7673 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:16:36.216  7673  7673 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:36.216  7673  7673 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 19:16:36.224  7533  7533 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-06 19:16:37.731  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:16:37.731  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:37.895  1585  1585 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-06 19:16:37.948  1041  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:16:37.998  1041  1097 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7709 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-06 19:16:38.009  1585  1585 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-06 19:16:38.010  1585  1585 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-06 19:16:38.039  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 19:16:38.056  1041  1041 D administrator: Handling package changes for user 0
09-06 19:16:38.075  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 19:16:38.107  7709  7709 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:16:38.182  1041  1041 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-06 19:16:38.182  1041  1041 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-06 19:16:38.197  7709  7709 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:38.198  7709  7709 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:38.223  1041  1096 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:38.229  1041  1096 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-06 19:16:38.235  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 19:16:38.238  2484  2484 V GmsNetworkLocationProvi: DISABLE
,09-06 19:16:38.284  1041  1096 D LocationProviderProxy: applying state to connected service
09-06 19:16:38.285  2484  2484 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-06 19:16:38.317  7709  7755 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-06 19:16:38.317  7709  7755 I Babel   : MmsConfig.loadMmsSettings
09-06 19:16:38.321  7709  7755 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 19:16:38.322  7709  7755 I Babel   : MmsConfig.loadFromDatabase
,09-06 19:16:38.338  7709  7755 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-06 19:16:38.338  7709  7755 I Babel   : MmsConfig.loadFromResources
09-06 19:16:38.343  7709  7755 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-06 19:16:38.344  7709  7755 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-06 19:16:38.365  7709  7753 W AudioCapabilities: Unsupported mime audio/evrc
09-06 19:16:38.366  7709  7709 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:38.367  7709  7753 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 19:16:38.369  7709  7753 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:16:38.384  7709  7753 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-06 19:16:38.386  7709  7753 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 19:16:38.389  7709  7753 W AudioCapabilities: Unsupported mime audio/evrc
09-06 19:16:38.395  1801  7757 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-06 19:16:38.395  1801  7757 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-06 19:16:38.396  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 19:16:38.405  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2ce7d1e0
09-06 19:16:38.405  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:16:38.405  7015  7015 D AppUp4:CustFacade: isPhone : true
09-06 19:16:38.405  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:16:38.405  7015  7015 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,09-06 19:16:38.418  1801  4784 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-06 19:16:38.424  7709  7753 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:16:38.431  7709  7753 W VideoCapabilities: Unsupported mime video/divx
09-06 19:16:38.434  7709  7753 W VideoCapabilities: Unsupported mime video/divx311
,09-06 19:16:38.444  7709  7753 W VideoCapabilities: Unsupported mime video/divx4
09-06 19:16:38.452  7709  7753 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:16:38.457  1041  1757 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7760 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-06 19:16:38.462  1041  1757 I ActivityManager: Killing 6850:com.lge.sync/1000 (adj 15): empty #17
09-06 19:16:38.480   348   348 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 23.504ms
,09-06 19:16:38.483  1041  1527 D WifiService: Client connection lost with reason: 4
09-06 19:16:38.490  7709  7753 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-06 19:16:38.495  7709  7753 W AudioCapabilities: Unsupported mime audio/eac3
,09-06 19:16:38.498  7709  7753 W AudioCapabilities: Unsupported mime audio/ac3
,09-06 19:16:38.499  7709  7753 W AudioCapabilities: Unsupported mime audio/g726
09-06 19:16:38.500  7709  7753 W AudioCapabilities: Unsupported mime audio/wma-voice
09-06 19:16:38.501  7709  7753 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-06 19:16:38.502  7709  7753 W AudioCapabilities: Unsupported mime audio/adpcm
09-06 19:16:38.503   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 20.368ms
09-06 19:16:38.504  7709  7753 W VideoCapabilities: Unsupported mime video/theora
09-06 19:16:38.506  7709  7753 W VideoCapabilities: Unsupported mime video/mjpg
,09-06 19:16:38.522   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 495us total 19.010ms
,09-06 19:16:38.548  1041  2034 W libprocessgroup: failed to open /acct/uid_1000/pid_6850/cgroup.procs: No such file or directory
,09-06 19:16:38.574  7760  7760 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:16:38.575  7760  7760 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:16:38.575  7760  7760 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 19:16:38.577  7760  7760 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-06 19:16:38.578  7760  7760 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-06 19:16:38.631  7760  7760 I SystemConfig: BUILD Country: EU
09-06 19:16:38.631  7760  7760 I SystemConfig: BUILD Operator: OPEN
,09-06 19:16:38.667  1041  1933 I ActivityManager: Killing 7054:com.lge.email/u0a23 (adj 15): empty #17
,09-06 19:16:38.750  1041  1946 W libprocessgroup: failed to open /acct/uid_10023/pid_7054/cgroup.procs: No such file or directory
,09-06 19:16:38.767  7760  7778 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-06 19:16:38.767  7760  7778 I SystemConfig: existFile = false
,09-06 19:16:38.770  7760  7778 I SystemConfig: canReadFile = false
,09-06 19:16:38.771  7760  7778 I SystemConfig: systemFeature RCS result false
09-06 19:16:38.771  7760  7778 D SystemConfig: refreshRcsSupport() :false
09-06 19:16:38.815  1041  1889 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7780 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-06 19:16:38.902  7780  7780 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:38.902  7780  7780 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 19:16:38.903  7780  7780 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 19:16:38.903  7780  7780 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-06 19:16:38.999  7780  7780 I AppConfig: Total System Memory = 2995761152
,09-06 19:16:39.010  7780  7780 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-06 19:16:39.105  1041  1936 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7802 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:39.108  1041  1936 I ActivityManager: Killing 6934:com.lge.formmanager/u0a26 (adj 15): empty #17
09-06 19:16:39.164  1041  1756 W libprocessgroup: failed to open /acct/uid_10026/pid_6934/cgroup.procs: No such file or directory
,09-06 19:16:39.387  7802  7802 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-06 19:16:39.487  7802  7802 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:39.487  7802  7802 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:39.535  7802  7802 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-06 19:16:39.556  7802  7802 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:16:39.557  7802  7802 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:16:39.573  7802  7802 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:16:39.573  7802  7802 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-06 19:16:39.590  1041  1889 I ActivityManager: Killing 6442:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-06 19:16:39.622  3469  6234 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-06 19:16:39.623  1041  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_6442/cgroup.procs: No such file or directory
,09-06 19:16:39.627  3469  6234 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3c5b26ed on behalf of 7802
09-06 19:16:39.633  4607  7842 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-06 19:16:39.680  1041  1756 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7843 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-06 19:16:39.722  7802  7802 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-06 19:16:39.752  7802  7802 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-06 19:16:39.787  1041  1361 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3fdc4dcf type 2 when 135173 com.google.android.gms} when 135173
,09-06 19:16:39.793  7843  7843 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
09-06 19:16:39.806  7843  7843 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-06 19:16:39.806  7843  7843 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-06 19:16:39.806  7843  7843 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-06 19:16:39.806  7843  7843 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-06 19:16:39.806  7843  7843 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-06 19:16:39.806  7843  7843 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-06 19:16:39.815   310  7873 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 19:16:39.817  1041  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:16:39.846  1041  1889 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7875 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-06 19:16:39.854  1041  1889 I ActivityManager: Killing 7117:com.google.android.setupwizard/u0a46 (adj 15): empty #17
09-06 19:16:39.966  1041  1936 W libprocessgroup: failed to open /acct/uid_10046/pid_7117/cgroup.procs: No such file or directory
,09-06 19:16:40.024  7875  7875 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:16:40.054  7875  7875 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-06 19:16:40.117  7875  7875 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-06 19:16:40.117  7875  7875 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 19:16:40.118  7875  7875 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 19:16:40.118  7875  7875 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 19:16:40.119  7875  7875 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 19:16:40.120  7875  7875 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 19:16:40.125  7875  7875 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-06 19:16:40.141  7875  7875 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-06 19:16:40.141  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:449
,09-06 19:16:40.146  7875  7875 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-06 19:16:40.148  7875  7875 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-06 19:16:40.148  7875  7875 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 19:16:40.149  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:16:40.149  7875  7875 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 19:16:40.166  1041  1057 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:16:40.173  7875  7875 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:40.173  7875  7875 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:16:40.181  7875  7875 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-06 19:16:40.185  7875  7875 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 19:16:40.185  7875  7875 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 19:16:40.185  7875  7875 V SoundPool: doLoad: loading sample sampleID=1
09-06 19:16:40.186  7875  7897 V SoundPool: Start decode
09-06 19:16:40.186  7875  7897 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-06 19:16:40.187  4607  7842 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 553 ms] updated apps [took 553 ms] 
09-06 19:16:40.188   316  1368 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 19:16:40.188   316  1368 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 19:16:40.188   316  1368 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 19:16:40.188   316  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 19:16:40.188   316  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 19:16:40.188   316  1368 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 19:16:40.188   316  1368 V MediaPlayerService: player type = 3
09-06 19:16:40.188   316  1368 V AwesomePlayer: AwesomePlayer create()
09-06 19:16:40.189   316  1368 V AwesomePlayer: reset_l() 
09-06 19:16:40.189   316  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:40.189   316  1368 V AwesomePlayer: setAudioSink() 
09-06 19:16:40.189   316  1368 V AwesomePlayer: reset_l() 
09-06 19:16:40.189   316  1368 V AudioCache: notify(0xb100a080, 8, 0, 0)
09-06 19:16:40.189   316  1368 V AudioCache: ignored
09-06 19:16:40.189   316  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:40.189  7875  7875 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 19:16:40.189   316  1368 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 19:16:40.189   316  1368 V AwesomePlayer: setDataSource_l dataSource
09-06 19:16:40.189   316  1368 V LGParserOSAL: SniffLGParser start
09-06 19:16:40.189   316  1368 V LGParserOSAL: MainType:5, SubType=0
09-06 19:16:40.189   316  1368 V LGParserOSAL: #### check Mime : application/ogg
09-06 19:16:40.189   316  1368 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 19:16:40.189   316  1368 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 19:16:40.192  7875  7875 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 19:16:40.200  7875  7875 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:16:40.201  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-06 19:16:40.227   316  1368 V LGParserOSAL: supported mime: application/ogg
09-06 19:16:40.227   316  1368 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 19:16:40.227   316  1368 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 19:16:40.227   316  1368 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 19:16:40.227   316  1368 V AwesomePlayer: AudioTrack Setting
09-06 19:16:40.227   316  1368 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 19:16:40.227   316  1368 V AwesomePlayer: setAudioSource() 
09-06 19:16:40.227   316  1368 V MediaPlayerService: prepare
09-06 19:16:40.227   316  1368 V AwesomePlayer: prepareAsync_l() 
09-06 19:16:40.227   316  1368 V MediaPlayerService: wait for prepare
,09-06 19:16:40.229   316  7898 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 19:16:40.230   316  7898 V AwesomePlayer: initAudioDecoder() 
09-06 19:16:40.230   316  7898 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:16:40.230   316  7898 V AudioSystem: isOffloadSupported()
09-06 19:16:40.230   316  7898 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:16:40.230   316  7898 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:16:40.230   316  7898 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:16:40.230   316  7898 V AwesomePlayer: getUseOffload() = 0 
09-06 19:16:40.230   316  7898 V OMXCodec: OMXCodec::Create
09-06 19:16:40.230   316  7898 V OMXCodec: findMatchingCodecs()
09-06 19:16:40.230   316  7898 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-06 19:16:40.231   316  7898 V OMXCodec: matchingCodecs.size()=1
09-06 19:16:40.231   316  7898 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 19:16:40.234   316  7898 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 19:16:40.234   316  7898 V LGCodecAdapter: LG Codec Adapter start
09-06 19:16:40.234   316  7898 V OMXCodec: OMXCodec Createtor
09-06 19:16:40.234   316  7898 V OMXCodec: setComponentRole
09-06 19:16:40.234   316  7898 V OMXCodec: configureCodec protected=0
09-06 19:16:40.235   316  7898 V LGCodecAdapter: called getLGCodecSpecificData
09-06 19:16:40.235   316  7898 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 19:16:40.235   316  7898 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 19:16:40.235   316  7898 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 19:16:40.235   316  7898 V LGCodecOSAL: Not support LGCodec
09-06 19:16:40.235   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:16:40.235   316  7898 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 19:16:40.235   316  7898 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 19:16:40.235   316  7898 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 19:16:40.235   316  7898 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:16:40.236   316  7898 V AudioSystem: isOffloadSupported()
09-06 19:16:40.236   316  7898 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,09-06 19:16:40.236   316  7898 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,09-06 19:16:40.236   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 19:16:40.236   316  7898 V OMXCodec: init()
09-06 19:16:40.236   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 19:16:40.236   316  7898 V OMXCodec: allocateBuffers
,09-06 19:16:40.236   316  7898 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 19:16:40.236   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 19:16:40.236  7875  7875 V LGMDMManager: Create singleton instance
09-06 19:16:40.237   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
,09-06 19:16:40.237   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-06 19:16:40.237   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-06 19:16:40.237   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-06 19:16:40.237   316  7898 V OMXCodec: allocateBuffersOnPort portIndex=1
,09-06 19:16:40.237   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:16:40.238   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
09-06 19:16:40.238   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0290 on output port
09-06 19:16:40.238   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c03d0 on output port
,09-06 19:16:40.238   316  7898 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0420 on output port
09-06 19:16:40.238   316  7898 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:16:40.238   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:16:40.238   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,09-06 19:16:40.239   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 19:16:40.239   316  7898 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:16:40.239   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 19:16:40.239   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
,09-06 19:16:40.239   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 19:16:40.239   316  7898 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 19:16:40.239   316  7898 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 19:16:40.239   316  7898 V AudioCache: notify(0xb100a080, 5, 0, 0)
,09-06 19:16:40.239   316  7898 V AudioCache: ignored
09-06 19:16:40.240   316  7898 V AudioCache: notify(0xb100a080, 1, 0, 0)
09-06 19:16:40.240   316  7898 V AudioCache: prepared
09-06 19:16:40.240   316  1368 V AudioCache: wait - success
,09-06 19:16:40.240   316  1368 V MediaPlayerService: start
09-06 19:16:40.240   316  1368 V AwesomePlayer: play_l() 
09-06 19:16:40.240   316  1368 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 19:16:40.240   316  1368 V AwesomePlayer: createAudioPlayer_l
,09-06 19:16:40.240   316  1368 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 19:16:40.240   316  1368 V AwesomePlayer: startAudioPlayer_l() 
09-06 19:16:40.240   316  1368 D AudioPlayer: start of Playback, useOffload 0
09-06 19:16:40.240   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,09-06 19:16:40.240   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803216
,09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0,
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803536
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044803616
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 19:16:40.243   316  7900 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:16:40.243   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:16:40.244   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c03d0 on output port
,09-06 19:16:40.244   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0290 on output port
09-06 19:16:40.244   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
,09-06 19:16:40.244   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c0560 on output port
09-06 19:16:40.244   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 19:16:40.244   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 19:16:40.245   316  1368 V AudioCache: open(48000, 2, 0x0, 1, 4)
,09-06 19:16:40.246   316  1368 V AudioCache: notify(0xb100a080, 6, 0, 0)
09-06 19:16:40.246   316  1368 V AudioCache: ignored
09-06 19:16:40.246   316  1368 V MediaPlayerService: wait for playback complete
09-06 19:16:40.247   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.247   316  7901 V AudioCache: memcpy(0xaf006000, 0xb57f8000, 4096)
09-06 19:16:40.249   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.249   316  7901 V AudioCache: memcpy(0xaf007000, 0xb57f8000, 4096)
,09-06 19:16:40.250   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.250   316  7901 V AudioCache: memcpy(0xaf008000, 0xb57f8000, 4096)
09-06 19:16:40.251   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.251   316  7901 V AudioCache: memcpy(0xaf009000, 0xb57f8000, 4096)
09-06 19:16:40.251   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.251   316  7901 V AudioCache: memcpy(0xaf00a000, 0xb57f8000, 4096)
09-06 19:16:40.252   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.252   316  7901 V AudioCache: memcpy(0xaf00b000, 0xb57f8000, 4096)
,09-06 19:16:40.253   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.253   316  7901 V AudioCache: memcpy(0xaf00c000, 0xb57f8000, 4096)
09-06 19:16:40.253   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.253   316  7901 V AudioCache: memcpy(0xaf00d000, 0xb57f8000, 4096)
09-06 19:16:40.254   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.254   316  7901 V AudioCache: memcpy(0xaf00e000, 0xb57f8000, 4096)
09-06 19:16:40.254   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.255   316  7901 V AudioCache: memcpy(0xaf00f000, 0xb57f8000, 4096)
,09-06 19:16:40.255   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.255   316  7901 V AudioCache: memcpy(0xaf010000, 0xb57f8000, 4096)
09-06 19:16:40.256   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.256   316  7901 V AudioCache: memcpy(0xaf011000, 0xb57f8000, 4096)
09-06 19:16:40.256   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.256   316  7901 V AudioCache: memcpy(0xaf012000, 0xb57f8000, 4096)
09-06 19:16:40.257   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.257   316  7901 V AudioCache: memcpy(0xaf013000, 0xb57f8000, 4096)
09-06 19:16:40.258   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.258   316  7901 V AudioCache: memcpy(0xaf014000, 0xb57f8000, 4096)
09-06 19:16:40.258   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.258   316  7901 V AudioCache: memcpy(0xaf015000, 0xb57f8000, 4096)
09-06 19:16:40.259   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.259   316  7901 V AudioCache: memcpy(0xaf016000, 0xb57f8000, 4096)
09-06 19:16:40.259   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.259   316  7901 V AudioCache: memcpy(0xaf017000, 0xb57f8000, 4096)
09-06 19:16:40.260   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.260   316  7901 V AudioCache: memcpy(0xaf018000, 0xb57f8000, 4096)
09-06 19:16:40.260   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.260   316  7901 V AudioCache: memcpy(0xaf019000, 0xb57f8000, 4096)
09-06 19:16:40.261   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.261   316  7901 V AudioCache: memcpy(0xaf01a000, 0xb57f8000, 4096)
09-06 19:16:40.261   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.261   316  7901 V AudioCache: memcpy(0xaf01b000, 0xb57f8000, 4096)
09-06 19:16:40.262   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.262   316  7901 V AudioCache: memcpy(0xaf01c000, 0xb57f8000, 4096)
09-06 19:16:40.263   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.263   316  7901 V AudioCache: memcpy(0xaf01d000, 0xb57f8000, 4096)
09-06 19:16:40.263   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.263   316  7901 V AudioCache: memcpy(0xaf01e000, 0xb57f8000, 4096)
09-06 19:16:40.264   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.264   316  7901 V AudioCache: memcpy(0xaf01f000, 0xb57f8000, 4096)
09-06 19:16:40.264   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.264   316  7901 V AudioCache: memcpy(0xaf020000, 0xb57f8000, 4096)
09-06 19:16:40.265   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.265   316  7901 V AudioCache: memcpy(0xaf021000, 0xb57f8000, 4096)
09-06 19:16:40.266   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.266   316  7901 V AudioCache: memcpy(0xaf022000, 0xb57f8000, 4096)
09-06 19:16:40.266   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.266   316  7901 V AudioCache: memcpy(0xaf023000, 0xb57f8000, 4096)
09-06 19:16:40.267   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.267   316  7901 V AudioCache: memcpy(0xaf024000, 0xb57f8000, 4096)
09-06 19:16:40.267   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.267   316  7901 V AudioCache: memcpy(0xaf025000, 0xb57f8000, 4096)
09-06 19:16:40.268   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.268   316  7901 V AudioCache: memcpy(0xaf026000, 0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: memcpy(0xaf027000, 0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: memcpy(0xaf028000, 0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: memcpy(0xaf029000, 0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: memcpy(0xaf02a000, 0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.269   316  7901 V AudioCache: memcpy(0xaf02b000, 0xb57f8000, 4096)
09-06 19:16:40.271   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.271   316  7901 V AudioCache: memcpy(0xaf02c000, 0xb57f8000, 4096)
09-06 19:16:40.271   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.271   316  7901 V AudioCache: memcpy(0xaf02d000, 0xb57f8000, 4096)
09-06 19:16:40.272   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.272   316  7901 V AudioCache: memcpy(0xaf02e000, 0xb57f8000, 4096)
09-06 19:16:40.272   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.272   316  7901 V AudioCache: memcpy(0xaf02f000, 0xb57f8000, 4096)
09-06 19:16:40.275   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.275   316  7901 V AudioCache: memcpy(0xaf030000, 0xb57f8000, 4096)
09-06 19:16:40.275   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.275   316  7901 V AudioCache: memcpy(0xaf031000, 0xb57f8000, 4096)
09-06 19:16:40.275   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.275   316  7901 V AudioCache: memcpy(0xaf032000, 0xb57f8000, 4096)
09-06 19:16:40.275   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.275   316  7901 V AudioCache: memcpy(0xaf033000, 0xb57f8000, 4096)
09-06 19:16:40.277   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.277   316  7901 V AudioCache: memcpy(0xaf034000, 0xb57f8000, 4096)
09-06 19:16:40.278   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.278   316  7901 V AudioCache: memcpy(0xaf035000, 0xb57f8000, 4096)
09-06 19:16:40.278   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.278   316  7901 V AudioCache: memcpy(0xaf036000, 0xb57f8000, 4096)
09-06 19:16:40.278   316  7901 V AudioCache: write(0xb57f8000, 4096)
09-06 19:16:40.278   316  7901 V AudioCache: memcpy(0xaf037000, 0xb57f8000, 4096)
09-06 19:16:40.278   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 19:16:40.278   316  7901 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:16:40.278   316  7901 V AwesomePlayer: postAudioEOS() 
09-06 19:16:40.278   316  7901 V AudioCache: write(0xb57f8000, 280)
09-06 19:16:40.278   316  7901 V AudioCache: memcpy(0xaf038000, 0xb57f8000, 280)
09-06 19:16:40.280   316  7898 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 19:16:40.280   316  7898 V AwesomePlayer: onStreamDone
09-06 19:16:40.280   316  7898 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 19:16:40.280   316  7898 V AudioCache: notify(0xb100a080, 2, 0, 0)
09-06 19:16:40.280   316  7898 V AudioCache: playback complete
09-06 19:16:40.280   316  1368 V AudioCache: wait - success
09-06 19:16:40.280   316  7898 V AwesomePlayer: pause_l() 
09-06 19:16:40.280   316  1368 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 19:16:40.280   316  7898 V AudioCache: notify(0xb100a080, 7, 0, 0)
09-06 19:16:40.280   316  7898 V AudioCache: ignored
09-06 19:16:40.280   316  7898 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:40.281   316  7898 D AudioPlayer: Pause Playback at 1068125
09-06 19:16:40.281   316  1368 V AwesomePlayer: reset_l() 
09-06 19:16:40.281   316  1368 V AudioCache: notify(0xb100a080, 8, 0, 0)
09-06 19:16:40.281   316  1368 V AudioCache: ignored
09-06 19:16:40.281   316  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:40.281   316  1368 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 19:16:40.281   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 19:16:40.281   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 19:16:40.281   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 19:16:40.282   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c0560 on port 1
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c0290 on port 1
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c03d0 on port 1
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 19:16:40.282   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:16:40.282   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 19:16:40.282   316  7900 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 19:16:40.282   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:16:40.282   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 19:16:40.283   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-06 19:16:40.283   316  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 19:16:40.283   316  1368 D AudioPlayer: AudioPlayer releasing audio source
09-06 19:16:40.284   316  1368 D AudioPlayer: AudioPlayer done releasing audio source
09-06 19:16:40.284   316  1368 V AwesomePlayer: reset_l() 
09-06 19:16:40.284   316  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:40.284   316  1368 V AwesomePlayer: ~AwesomePlayer call
09-06 19:16:40.284   316  1368 V AwesomePlayer: reset_l() 
09-06 19:16:40.284   316  1368 V AwesomePlayer: cancelPlayerEvents
09-06 19:16:40.284  7875  7897 V SoundPool: close(31)
09-06 19:16:40.284  7875  7897 V SoundPool: pointer = 0xa003a000, size = 205080, sampleRate = 48000, numChannels = 2
,09-06 19:16:40.323  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-06 19:16:40.325  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 19:16:40.328  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:929
09-06 19:16:40.330  7875  7875 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 19:16:40.332  7619  7634 I UEI.SmartControl: ------ IControl API: 11
09-06 19:16:40.333  7619  7634 I UEI.SmartControl: Registering callback...
09-06 19:16:40.334  7619  7635 I UEI.SmartControl: ------ IControl API: 19
09-06 19:16:40.336  7619  7635 I UEI.SmartControl: Registering Services Ready callback...
09-06 19:16:40.336  7619  7635 I UEI.SmartControl: Notify client services are ready...
,09-06 19:16:40.338  7875  7892 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 19:16:40.338  7875  7895 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 19:16:40.338  7875  7895 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 19:16:40.339  7875  7875 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 19:16:40.340  7875  7875 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 19:16:40.340  7619  7634 I UEI.SmartControl: ------ IControl API: 8
09-06 19:16:40.343  7875  7875 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 19:16:40.344  7875  7875 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 19:16:40.345  7875  7875 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 19:16:40.346  7875  7875 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 19:16:40.348  7875  7875 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 19:16:40.349  7875  7875 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-06 19:16:40.350  7875  7875 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-06 19:16:40.356  7875  7875 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 19:16:40.357  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:16:40.359  7875  7875 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:16:40.359  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:16:40.361  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:16:40.363  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,09-06 19:16:40.364  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 19:16:40.366  7875  7875 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473182200365]
09-06 19:16:40.371  7875  7875 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 19:16:40.378  1041  1936 I ActivityManager: Killing 7152:com.android.chrome/u0a57 (adj 15): empty #17
,09-06 19:16:40.393  7619  7661 D UEI.SmartControl: Internal timer expired: 1
,09-06 19:16:40.394  7619  7661 D UEI.SmartControl: unbind internal service
09-06 19:16:40.409  7875  7902 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 19:16:40.419  1041  1562 W libprocessgroup: failed to open /acct/uid_10057/pid_7152/cgroup.procs: No such file or directory
09-06 19:16:40.425  7875  7875 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-06 19:16:40.428  7875  7875 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:16:40.428  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 19:16:40.429  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 19:16:40.429  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-06 19:16:40.429  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 19:16:40.430  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-06 19:16:40.439  7875  7875 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-06 19:16:40.620  7619  7658 D serial_port: close(fd = 25)
,09-06 19:16:40.625  7619  7658 I UEI.SmartControl: Serial port is closed.
,09-06 19:16:40.746  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:16:40.746  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c94372 added. We now have 6 listener(s)
,09-06 19:16:40.747  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:16:40.761  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:40.762  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@316aa3c3 added. We now have 7 listener(s)
09-06 19:16:40.762  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:40.762  6633  6722 I System.out: IsBluetoothEnabled
09-06 19:16:40.764  1041  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:40.765  1041  2034 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-06 19:16:40.765  1041  1116 D BluetoothManagerService: Message: 2
09-06 19:16:40.768  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:40.768  1041  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:40.769  1041  2015 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 19:16:40.789  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:16:40.789  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-06 19:16:40.789  1041  1041 D Ulp_jni : JNI:system_update. Event-4
09-06 19:16:40.790  1041  1116 D BluetoothManagerService: Message: 1
09-06 19:16:40.790  1041  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-06 19:16:40.815  1041  1116 D BluetoothManagerService: Message: 20
09-06 19:16:40.815  1041  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@226cb1db:true
,09-06 19:16:40.820  7673  7673 D BluetoothAdapterState: make
09-06 19:16:40.824  7673  7673 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 19:16:40.824  7673  7673 I bluedroid-qcom: init
09-06 19:16:40.825  7673  7916 I BluetoothAdapterState: Entering OffState
09-06 19:16:40.826  7673  7673 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:16:40.826  7673  7673 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:16:40.826  7673  7673 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:16:40.826  7673  7673 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:16:40.826  7673  7673 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 19:16:40.828  7673  7673 I bluedroid-qcom: get_profile_interface socket
09-06 19:16:40.828  7673  7673 I bluedroid-qcom: get_profile_interface map_client
,09-06 19:16:40.832  7673  7920 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:16:40.819  7919  7919 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:40.836  7673  7920 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:16:40.819  7919  7919 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:40.846  7919  7919 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 19:16:40.846  7919  7919 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 19:16:40.846  7919  7919 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-06 19:16:40.851  1041  1041 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:16:40.851  1041  1041 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:16:40.853  1041  1041 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 19:16:40.853  1041  1116 D BluetoothManagerService: Message: 40
09-06 19:16:40.853  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 19:16:40.854  7673  7689 I bluedroid-qcom: config_hci_snoop_log
09-06 19:16:40.855  1041  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 19:16:40.855  1041  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 19:16:40.856  7919  7919 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-06 19:16:40.863  7673  7916 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-06 19:16:40.866  7673  7920 D BluetoothAdapterProperties: Name is: G3
09-06 19:16:40.868  7919  7919 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 19:16:40.868  7919  7919 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-06 19:16:40.869  7673  7916 D BluetoothAdapterProperties: Setting state to 11
09-06 19:16:40.870  7673  7916 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:16:40.870  1041  1116 D BluetoothManagerService: Message: 60
09-06 19:16:40.870  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 19:16:40.871  1041  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 19:16:40.875  1923  1923 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:40.878  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:16:40.881  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:40.884  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 19:16:40.890  7673  7673 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:16:40.890  7673  7673 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:40.890  7673  7673 V BluetoothPbapReceiver: ***********state = 11
,09-06 19:16:40.896  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:40.913  7673  7916 I LGBluetoothServiceJni: classInitNative: succeeds
,09-06 19:16:40.925  7673  7916 D BluetoothBondStateMachine: make
,09-06 19:16:40.928  6803  6803 D BluetoothPermissionRequest: onReceive
09-06 19:16:40.930  7673  7916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:40.930  7673  7916 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 19:16:40.930  7673  7916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:40.930  7673  7916 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 19:16:40.930  7673  7916 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 19:16:40.932  7673  7934 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 19:16:40.932  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:16:40.935  7673  7916 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:40.938  7673  7673 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:16:40.941  7673  7673 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:16:40.941  7673  7673 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:16:40.941  7673  7673 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:16:40.941  7673  7673 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:40.941  7673  7673 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 19:16:40.952  7673  7673 D HeadsetService: Received start request. Starting profile...
09-06 19:16:40.952  7673  7673 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:16:40.953  7673  7673 D LGBluetoothHfpAdapter: Version 1.6
,09-06 19:16:40.956  7673  7673 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:16:40.957  7673  7673 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:16:40.958  7673  7673 D HeadsetStateMachine: make
,09-06 19:16:40.960  7673  7916 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:40.967  7673  7916 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:40.972  7673  7916 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:16:40.977  7673  7916 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:40.983  7673  7916 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:16:40.988  7673  7916 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:16:41.000  7673  7673 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:16:41.001  7673  7673 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:16:41.004  7673  7916 V LGMDMManager: Create singleton instance
09-06 19:16:41.006  7673  7673 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:16:41.006  7673  7673 I bluedroid-qcom: get_profile_interface handsfree
09-06 19:16:41.006  7673  7916 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:16:41.008  7673  7673 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 19:16:41.009   316  2167 V AudioPolicyService: registerClient() client 0xb57eeb60, uid 1002
09-06 19:16:41.010   316   316 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:16:41.010   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:16:41.010   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:16:41.010  7673  7673 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:16:41.010   316  1367 V AudioFlinger: registerClient() client 0xb1433160, pid 7673
09-06 19:16:41.011   316  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:41.011   316  1362 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:41.011  7673  7673 V ToneGenerator: Create Track: 0xb4928a80
09-06 19:16:41.011  3337  3356 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:41.011  7673  7673 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 19:16:41.011  3337  3356 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:41.011  7673  7673 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 19:16:41.011  1041  1933 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:41.011  1041  1933 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:41.011  1836  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:41.011  1585  2080 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:41.011  1836  1851 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:41.011  1585  2080 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:16:41.012   316  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:41.012   316  1363 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:41.012  7673  7689 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:16:41.012  7673  7689 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 19:16:41.012   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:16:41.012   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:16:41.012   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:16:41.012   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:16:41.012  1041  2034 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:41.012  1041  2034 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-06 19:16:41.012  3337  3355 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:41.012  3337  3355 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:41.012  1585  1603 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:41.012  7673  7689 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:41.012  1585  1603 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:41.012  7673  7689 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 19:16:41.012  1836  2685 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:16:41.012  1836  2685 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:16:41.013   316   316 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:16:41.013   316  1367 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:16:41.013   316  1367 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 19:16:41.013   316  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:16:41.013   316  1367 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:16:41.013  7673  7673 V AudioSystem: getLatency() output 2, latency 50
09-06 19:16:41.013  7673  7673 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 19:16:41.013  7673  7673 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 19:16:41.013   316  1368 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:16:41.013   316  1368 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:16:41.013   316  1368 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:16:41.013   316  1368 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:16:41.013   316  1368 V AudioFlinger: createTrack() lSessionId: 23
09-06 19:16:41.014  7673  7673 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 19:16:41.015   316   316 V AudioFlinger: acquiring 23 from 7673, for 7673
09-06 19:16:41.015   316   316 V AudioFlinger:  added new entry for 23
09-06 19:16:41.015  7673  7673 V ToneGenerator: ToneGenerator INIT OK, time: 136417
09-06 19:16:41.015  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:41.016  7673  7938 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 19:16:41.016  7673  7938 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,09-06 19:16:41.016  7673  7938 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:16:41.016  7673  7938 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 19:16:41.018   316  2167 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7673
09-06 19:16:41.018   316  2167 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 19:16:41.018   316  2167 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 19:16:41.018   316  2167 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 19:16:41.018   316  2167 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 19:16:41.018   316  2167 V voice   : voice_set_parameters: exit with code(0)
09-06 19:16:41.018   316  2167 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 19:16:41.018   316  2167 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 19:16:41.018   316  2167 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 19:16:41.018   316  2167 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 19:16:41.018  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:41.018   316  2167 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 19:16:41.019   316  2167 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 19:16:41.019  7673  7938 V ToneGenerator: ToneGenerator destructor
09-06 19:16:41.019  7673  7938 V ToneGenerator: stopTone
09-06 19:16:41.019  7673  7938 V ToneGenerator: Delete Track: 0xb4928a80
09-06 19:16:41.019  7673  7938 V AudioTrack: ~AudioTrack, releasing session id from 7673 on behalf of 7673
09-06 19:16:41.019   316  1367 V AudioFlinger: releasing 23 from 7673 for 7673
09-06 19:16:41.019   316  1367 V AudioFlinger:  decremented refcount to 0
09-06 19:16:41.019   316  1367 V AudioFlinger: purging stale effects
09-06 19:16:41.019   316  1367 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 19:16:41.019   316  1367 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 19:16:41.019   316  1367 V AudioFlinger: PlaybackThread::Track destructor
09-06 19:16:41.019   316  1267 V AudioPolicyService: AudioCommandThread() waking up
09-06 19:16:41.019   316  1367 V AudioFlinger: removeClient_l() pid 7673, calling pid 316
09-06 19:16:41.019   316  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 19:16:41.020   316  1267 V AudioPolicyManager: releaseOutput() 2
09-06 19:16:41.020   316  1267 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 19:16:41.021  7673  7673 D A2dpService: Received start request. Starting profile...
09-06 19:16:41.022  1041  1936 W Process : Unable to open /proc/7940/status
09-06 19:16:41.022  7673  7673 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:16:41.023  7673  7673 V Avrcp   : make
09-06 19:16:41.024  7673  7673 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 19:16:41.024  7673  7673 I bluedroid-qcom: get_profile_interface avrcp
09-06 19:16:41.035  7673  7673 V AudioManager: registerRemoteController: size of Media player list: 0
,09-06 19:16:41.038  7673  7673 E AudioManager: No RCC entry present to update
09-06 19:16:41.038  7673  7673 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:16:41.042  7673  7673 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 19:16:41.044  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 19:16:41.044  7673  7673 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 19:16:41.050  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-06 19:16:41.200  1041  1946 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:16:41.201  1041  1946 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:16:41.350  1041  1562 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 19:16:41.362  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-06 19:16:41.368  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,09-06 19:16:41.369  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:16:41.370  7673  7673 I BluetoothA2dpServiceJni: classInitNative
09-06 19:16:41.370  7673  7673 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:16:41.370  7673  7673 D A2dpStateMachine: make
,09-06 19:16:41.372  7673  7673 I bluedroid-qcom: get_profile_interface a2dp
09-06 19:16:41.372  7673  7947 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:16:41.375  7673  7673 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,09-06 19:16:41.375  7673  7673 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 19:16:41.376  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
,09-06 19:16:41.377  7673  7673 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:16:41.379  7673  7946 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:16:41.380  7673  7673 D HidService: Received start request. Starting profile...
09-06 19:16:41.380  7673  7673 I bluedroid-qcom: get_profile_interface hidhost
09-06 19:16:41.380  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:41.380  7673  7673 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:16:41.382  7673  7673 D HealthService: Received start request. Starting profile...
09-06 19:16:41.385  7673  7673 I bluedroid-qcom: get_profile_interface health
09-06 19:16:41.386  7673  7673 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:16:41.386  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:41.387  7673  7673 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:16:41.389  7673  7673 D PanService: Received start request. Starting profile...
09-06 19:16:41.389  7673  7673 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-06 19:16:41.389  7673  7673 I bluedroid-qcom: get_profile_interface pan
09-06 19:16:41.399  7673  7673 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 19:16:41.399  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:41.402  7673  7673 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-06 19:16:41.416  7673  7673 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:16:41.417  7673  7673 D BtGatt.GattService: Received start request. Starting profile...
,09-06 19:16:41.417  7673  7673 D BtGatt.GattService: start()
09-06 19:16:41.417  7673  7673 I bluedroid-qcom: get_profile_interface gatt
09-06 19:16:41.419  7673  7673 D BtGatt.AdvertiseManager: advertise manager created
09-06 19:16:41.435  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:41.439  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
,09-06 19:16:41.441  7673  7673 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 19:16:41.443  7673  7673 V BluetoothMapService: BluetoothMapBinder()
09-06 19:16:41.445  7673  7673 D BluetoothMapService: Received start request. Starting profile...
09-06 19:16:41.445  7673  7673 D BluetoothMapService: start()
09-06 19:16:41.452  7673  7673 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-06 19:16:41.453  7673  7673 D BluetoothMapEmailAppObserver: createReceiver()
09-06 19:16:41.455  7673  7673 D BluetoothMapEmailAppObserver: initObservers()
09-06 19:16:41.456  7673  7673 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 19:16:41.472  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:41.472  7673  7673 D HeadsetStateMachine: Proxy object connected
09-06 19:16:41.473  7673  7673 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 19:16:41.473  7673  7673 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-06 19:16:41.476  7673  7938 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:16:41.476  7673  7938 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:16:41.477  7673  7938 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-06 19:16:41.484  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:16:41.488  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:16:41.492  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:16:41.496  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:16:41.497  7673  7673 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 19:16:41.501  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:16:41.505  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 19:16:41.505  7673  7673 V BluetoothMapService: Handler(): got msg=1
09-06 19:16:41.508  7673  7916 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:16:41.508  7673  7916 I bluedroid-qcom: enable
09-06 19:16:41.509  7673  7955 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:16:41.509  7673  7955 I bt-btu  : btu_task pending for preload complete event
09-06 19:16:41.509  7673  7916 I bt_hci_bdroid: init
09-06 19:16:41.512  7673  7916 I bt_vendor: bt-vendor : init
09-06 19:16:41.512  7673  7916 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:16:41.513  7673  7916 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:16:41.513  7673  7916 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 19:16:41.513  7673  7916 D bt_userial_mct: userial_init
09-06 19:16:41.513  7673  7916 D bt_hci_bdroid: set_power 1
09-06 19:16:41.514  7673  7916 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:16:41.514  7673  7916 I bt_vendor: Starting hciattach daemon
09-06 19:16:41.514  7673  7916 I bt_vendor: try to set true
,09-06 19:16:41.509  7958  7958 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:41.509  7958  7958 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:41.577  7959  7959 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:16:41.690  7968  7968 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:16:41.706  7969  7969 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:16:41.734  7971  7971 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:16:41.748  7972  7972 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-06 19:16:41.760  7973  7973 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:16:41.772  7974  7974 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:16:41.806  7976  7976 I libmdmdetect: ESOC framework not supported
09-06 19:16:41.807  7976  7976 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 19:16:41.818  7976  7976 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-06 19:16:41.818  7976  7976 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-06 19:16:41.818  7976  7976 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 19:16:41.818  7976  7976 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 19:16:41.818  7976  7976 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 19:16:41.818  7976  7976 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 19:16:41.818  7976  7976 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 19:16:41.857  7976  7977 E QC-QMI  : qmi_client [7976] 15: failed to locate client data
09-06 19:16:41.858   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 19:16:41.859   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-06 19:16:41.904  7978  7978 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 19:16:41.918  7979  7979 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:16:41.969  7673  7916 I bt_vendor: bluetooth satus is on
,09-06 19:16:41.969  7673  7916 D bt_hci_bdroid: preload
09-06 19:16:41.974  7673  7957 D bt_userial_mct: userial_open(port:0)
,09-06 19:16:41.974  7673  7957 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:16:41.978  7673  7957 I bt_vendor: Done intiailizing UART
09-06 19:16:41.982  7673  7957 I bt_vendor: Done intiailizing UART
09-06 19:16:41.982  7673  7957 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-06 19:16:41.982  7673  7957 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:16:41.982  7673  7981 D bt_userial_mct: Entering userial_read_thread()
09-06 19:16:41.983  7673  7955 I bt-btu  : btu_task received preload complete event
09-06 19:16:41.984  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 19:16:41.984  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 19:16:41.990  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-06 19:16:42.187  1041  1933 I art     : Explicit concurrent mark sweep GC freed 26775(1324KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.143ms total 177.667ms
,09-06 19:16:42.190  7673  7955 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:16:42.190  7673  7955 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:16:42.190  7673  7955 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:16:42.191  7673  7955 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:16:42.238  7673  7955 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-06 19:16:42.238  7673  7955 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0248061 
09-06 19:16:42.238  7673  7955 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0248061 
,09-06 19:16:42.267  7673  7920 E bt-btif : Calling BTA_HhEnable
09-06 19:16:42.267  7673  7920 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 19:16:42.268  7673  7920 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 19:16:42.273  1041  1041 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:16:42.273  1041  1041 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:16:42.274  7673  7920 D BluetoothAdapterProperties: Name is: G3
09-06 19:16:42.275  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 19:16:42.275  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 19:16:42.275  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 19:16:42.275  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:16:42.275  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 19:16:42.278  7673  7920 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:16:42.278  7673  7920 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:16:42.278  7673  7920 D bt_hci_bdroid: postload
09-06 19:16:42.280  7673  7957 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:16:42.281  7673  7920 D bte_conf: Device ID record 1 : primary
09-06 19:16:42.281  7673  7920 D bte_conf:   vendorId            = 00c4
09-06 19:16:42.281  7673  7920 D bte_conf:   vendorIdSource      = 0001
09-06 19:16:42.281  7673  7920 D bte_conf:   product             = 13a1
09-06 19:16:42.281  7673  7920 D bte_conf:   version             = 1000
09-06 19:16:42.281  7673  7920 D bte_conf:   clientExecutableURL = 
09-06 19:16:42.281  7673  7920 D bte_conf:   serviceDescription  = 
09-06 19:16:42.281  7673  7920 D bte_conf:   documentationURL    = 
09-06 19:16:42.281  7673  7920 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:16:42.289  7673  7955 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 19:16:42.295  7673  7916 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:16:42.295  7673  7916 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:16:42.295  7673  7916 D BluetoothAdapterProperties: State =  11
09-06 19:16:42.295  7673  7916 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 19:16:42.296  7673  7916 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 19:16:42.296  7673  7916 D BluetoothAdapterProperties: Setting state to 12
09-06 19:16:42.296  7673  7916 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:16:42.289  7986  7986 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:42.305  7673  7920 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:16:42.305  7673  7920 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:16:42.299  7986  7986 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:42.314  7673  7957 D bt_hci_bdroid: Used up Tx Cmd credits
,09-06 19:16:42.318  7673  7957 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:16:42.320  7673  7957 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:16:42.324  7673  7981 E bt_mct  : hci lib postload completed
09-06 19:16:42.329  7673  7955 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:42.329  7673  7955 W bt-smp  : Plain text(LSB ~ MSB) = 0f 3d 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:42.329  7673  7955 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 b5 ef ea a0 b1 13 3c 70 05 51 de 8f 09 92 54 
,09-06 19:16:42.332  7673  7955 W bt-btm  : Stopping oneshot timer
09-06 19:16:42.337  1041  1116 D BluetoothManagerService: Message: 60
09-06 19:16:42.337  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 19:16:42.337  1041  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-06 19:16:42.340  7673  7920 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:16:42.341  7673  7920 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-06 19:16:42.354  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:42.354  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:42.354  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:42.354  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:42.354  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:42.354  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:42.354  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:42.354  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:42.363  7673  7916 I BluetoothAdapterState: Entering On State
09-06 19:16:42.364  1836  2685 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:16:42.365  7673  7955 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:42.365  7673  7955 W bt-smp  : Plain text(LSB ~ MSB) = 15 4f 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:42.365  7673  7955 W bt-smp  : Encrypted text(LSB ~ MSB) = ff 04 7f cf 96 5f 27 24 91 30 2f f9 2e b4 94 15 
09-06 19:16:42.365  7673  7955 W bt-btm  : Stopping oneshot timer
09-06 19:16:42.372  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:42.377  7673  7955 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:42.378  7673  7955 W bt-smp  : Plain text(LSB ~ MSB) = 51 1b 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:42.378  7673  7955 W bt-smp  : Encrypted text(LSB ~ MSB) = ca 02 79 03 c8 be 80 06 9d 66 da 8e cf 39 c6 f8 
09-06 19:16:42.378  7673  7955 W bt-btm  : Stopping oneshot timer
09-06 19:16:42.393  7673  7916 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 19:16:42.393  7673  7916 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 19:16:42.393  7673  7916 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-06 19:16:42.398  7673  7916 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 19:16:42.398  7673  7955 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:42.398  7673  7955 W bt-smp  : Plain text(LSB ~ MSB) = 00 e4 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:42.398  7673  7955 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a 71 57 da 5e 03 cc ef 9f 26 13 3c 61 f6 89 fc 
09-06 19:16:42.399  7673  7955 W bt-btm  : Stopping oneshot timer
09-06 19:16:42.407  1836  1836 D BluetoothHeadset: Proxy object connected
,09-06 19:16:42.412  6803  6820 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:16:42.418  7673  7916 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-06 19:16:42.419  1041  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:42.422  7673  7955 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:16:42.422  7673  7955 W bt-smp  : Plain text(LSB ~ MSB) = 7c 62 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:16:42.422  7673  7955 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 15 53 c4 47 7e 9f aa dc ae 87 32 26 1c 39 76 
09-06 19:16:42.427  7673  7955 W bt-btm  : Stopping oneshot timer
09-06 19:16:42.436  7991  7991 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-06 19:16:42.444  1041  1041 D BluetoothA2dp: Proxy object connected
,09-06 19:16:42.445  1041  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:16:42.446  1041  1041 D BluetoothHeadset: Proxy object connected
09-06 19:16:42.451  6803  6828 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:16:42.467  6803  6803 D BluetoothA2dp: Proxy object connected
09-06 19:16:42.467  6803  6803 D A2dpProfile: Bluetooth service connected
09-06 19:16:42.470  6803  6820 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:16:42.470  6803  6820 D BluetoothPan: onBluetoothStateChange call bindService
,09-06 19:16:42.474  6803  8005 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:16:42.475  6803  6803 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:16:42.475  6803  6803 D PanProfile: Bluetooth service connected
09-06 19:16:42.477  6803  6828 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:16:42.478  6803  6803 D BluetoothHeadset: Proxy object connected
09-06 19:16:42.478  6803  6803 D HeadsetProfile: Bluetooth service connected
09-06 19:16:42.481  6803  6803 D BluetoothInputDevice: Proxy object connected
09-06 19:16:42.481  6803  6803 D HidProfile: Bluetooth service connected
09-06 19:16:42.481  1836  2460 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:16:42.483  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:16:42.485  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:16:42.487  1836  1836 D BluetoothHeadset: Proxy object connected
09-06 19:16:42.488  6803  8005 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:16:42.490  1041  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 19:16:42.490  1041  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 19:16:42.492  1923  1923 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:42.493  1923  2120 D LGBluetoothAPIService: Message: 1
09-06 19:16:42.493  1923  2120 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 19:16:42.493  1923  2120 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-06 19:16:42.493  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:16:42.493  1923  2120 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 19:16:42.496  1041  1041 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 19:16:42.499  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:42.499  6803  6803 D BluetoothMap: Proxy object connected
09-06 19:16:42.499  6803  6803 D MapProfile: Bluetooth service connected
09-06 19:16:42.499  6803  6803 D BluetoothMap: getConnectedDevices()
09-06 19:16:42.500  7673  7689 V BluetoothMapService: getConnectedDevices()
,09-06 19:16:42.502  7673  7673 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:42.502  7673  7673 D BluetoothMapService: STATE_ON
09-06 19:16:42.502  1041  1116 D BluetoothManagerService: Message: 40
09-06 19:16:42.502  1041  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 19:16:42.509  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-06 19:16:42.511  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:16:42.519  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
,09-06 19:16:42.519  7673  7673 V BluetoothPbapService: Pbap Service onCreate
09-06 19:16:42.519  7673  7673 V BluetoothPbapService: Starting PBAP service
09-06 19:16:42.521  7673  7673 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 19:16:42.521  7673  7673 V BluetoothPbapService: Pbap Service onBind
09-06 19:16:42.522  7673  7673 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:42.522  7673  7673 V BluetoothPbapService: state: 12
09-06 19:16:42.522  7673  7673 V BluetoothMapService: Handler(): got msg=1
09-06 19:16:42.523  7673  7673 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 19:16:42.524  6803  6803 D DockEventReceiver: finishStartingService: stopping service
09-06 19:16:42.524  7673  7673 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:16:42.524  7673  7673 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:42.524  7673  7673 V BluetoothPbapReceiver: ***********state = 12
09-06 19:16:42.525  6803  6803 D BluetoothPbap: Proxy object connected
09-06 19:16:42.525  6803  6803 D PbapServerProfile: Bluetooth service connected
09-06 19:16:42.526  7673  7673 V BluetoothPbapService: Handler(): got msg=1
09-06 19:16:42.527  7673  7673 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 19:16:42.528  7673  8012 D BluetoothMapMasInstance: MAS initSocket()
09-06 19:16:42.529  7673  8012 D BluetoothMapMasInstance:   masId = 00
09-06 19:16:42.529  7673  8012 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 19:16:42.529  7673  8012 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 19:16:42.529  7673  8012 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 19:16:42.529  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:16:42.530  2168  2168 D c       : Getting all permits...
09-06 19:16:42.530  2168  2168 D a       : Opening database...
09-06 19:16:42.531  1041  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:16:42.533  7673  8012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:16:42.536  7673  8012 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 19:16:42.536  7673  8012 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 19:16:42.536  7673  8012 D BluetoothMapMasInstance: Accepting socket connection...
09-06 19:16:42.537  7673  8013 V BluetoothPbapService: Pbap Service initSocket
09-06 19:16:42.537  7673  7920 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:16:42.538  7673  7920 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 19:16:42.538  1041  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:42.540  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:42.540  7673  8013 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:42.542  7673  8013 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 19:16:42.542  7673  8013 V BluetoothPbapService: Succeed to create listening socket 
09-06 19:16:42.542  7673  8013 V BluetoothPbapService: Accepting socket connection...
09-06 19:16:42.542  2168  2168 D a       : Opening database auth.proximity.permit_store...
09-06 19:16:42.543  2168  2168 D a       : Closing database...
09-06 19:16:42.554  6803  6803 D BluetoothPermissionRequest: onReceive
,09-06 19:16:42.557  6803  6803 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-06 19:16:42.559  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:16:42.562  7673  7673 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 19:16:42.563  7673  7673 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 19:16:42.570  7673  7673 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 19:16:42.592  7673  7673 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 19:16:42.592  7673  7673 V BtOppService: onCreate
,09-06 19:16:42.597  7673  7673 V BluetoothOppNotification: send message
,09-06 19:16:42.600  7673  7673 V BtOppService: Starting RfcommListener
09-06 19:16:42.607  7673  7673 D BluetoothOppPreference: Dumping Names:  
09-06 19:16:42.607  7673  7673 D BluetoothOppPreference: {}
09-06 19:16:42.607  7673  7673 D BluetoothOppPreference: Dumping Channels:  
09-06 19:16:42.607  7673  7673 D BluetoothOppPreference: {}
,09-06 19:16:42.609  7673  7673 V BtOppService: onStartCommand
,09-06 19:16:42.610  7673  8020 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:16:42.613  7673  8020 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:16:42.614  7673  7673 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:42.614  7673  7673 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:16:42.615  7673  8020 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ad9522b on behalf of 
09-06 19:16:42.618  7673  7673 V BluetoothOppNotification: new notify threadi!
09-06 19:16:42.619  7673  7673 V BluetoothOppNotification: send delay message
09-06 19:16:42.620  7673  7673 V BtOppService: start RfcommListener
09-06 19:16:42.620  7673  8017 V BtOppService: Deleted complete outbound shares, number =  0
,09-06 19:16:42.624  7673  7673 V BtOppService: RfcommListener started
09-06 19:16:42.627  7673  8017 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 19:16:42.627  7673  8017 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 19:16:42.628  7673  8017 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dd34688 on behalf of 
09-06 19:16:42.631  7673  8022 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 19:16:42.632  1041  1756 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:42.634  7673  8022 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:42.634  7673  8021 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:16:42.637  7673  8022 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
,09-06 19:16:42.637  7673  8022 V BtOppRfcommListener: Started RFCOMM listener....
09-06 19:16:42.637  7673  8022 I BtOppRfcommListener: Accept thread started.
09-06 19:16:42.637  7673  8022 V BtOppRfcommListener: Accepting connection...
09-06 19:16:42.639  7673  8020 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:16:42.639  7673  8020 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:16:42.640  7673  8020 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37a2a821 on behalf of 
09-06 19:16:42.641  7673  8020 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:16:42.641  7673  8021 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a01d446 on behalf of 
09-06 19:16:42.642  7673  8020 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 19:16:42.646  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:42.646  7673  8021 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:16:42.646  7673  7673 V BluetoothFtpService: Ftp Service onCreate
09-06 19:16:42.646  7673  7673 I BluetoothFtpService: Ftp Service onCreate
09-06 19:16:42.646  7673  7673 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:16:42.647  7673  7673 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:42.647  7673  7673 V BluetoothFtpService: Starting Listening on sockets
09-06 19:16:42.647  7673  7673 V BtOppService: ContentObserver received notification
09-06 19:16:42.647  7673  8021 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:16:42.648  7673  7673 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:16:42.648  7673  7673 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:16:42.648  7673  7673 V BluetoothSapReceiver: SapReceiver onReceive 
,09-06 19:16:42.648  7673  7673 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:42.648  7673  7673 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 19:16:42.648  7673  7673 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:16:42.649  7673  8023 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:16:42.649  7673  8023 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:16:42.649  7673  8021 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@89a4334 on behalf of 
09-06 19:16:42.651  7673  7673 V BtOppService: ContentObserver received notification
09-06 19:16:42.651  7673  7673 V BluetoothFtpService: Handler(): got msg=1
09-06 19:16:42.652  7673  7673 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 19:16:42.652  7673  7673 V BluetoothFtpService: Ftp Service initSocket
09-06 19:16:42.654  7673  8023 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1860a55d on behalf of 
09-06 19:16:42.656  7673  8023 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:16:42.656  7673  8021 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:16:42.658  7673  8023 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:16:42.658  7673  8023 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:16:42.659  7673  8021 V BluetoothOppNotification: outbound notification was removed.
09-06 19:16:42.659  7673  8021 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:16:42.660  7673  8021 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1676eed2 on behalf of 
09-06 19:16:42.661  1041  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:42.661  7673  8023 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15d3dba3 on behalf of 
,09-06 19:16:42.661  7673  8021 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-06 19:16:42.662  7673  7673 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:42.663  7673  8021 V BluetoothOppNotification: inbound notification was removed.
09-06 19:16:42.663  7673  8021 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:16:42.664  7673  7673 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=79
09-06 19:16:42.664  7673  7673 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 19:16:42.665  7673  8023 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:16:42.666  7673  8024 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 19:16:42.667  7673  8021 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b325ea0 on behalf of 
09-06 19:16:42.668  7673  8023 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-06 19:16:42.683  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f6c0b3f
09-06 19:16:42.683  7673  7673 V BluetoothSapService: Sap Service onCreate
09-06 19:16:42.685  7673  7673 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:16:42.685  7673  7673 V BluetoothSapService: state: 12
09-06 19:16:42.685  7673  7673 V BluetoothSapService: Starting SAP server process
09-06 19:16:42.686  7673  7673 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-06 19:16:42.679  8025  8025 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:42.688  7673  8026 V BluetoothSapService: Sap Service initRfcommSocket
09-06 19:16:42.679  8025  8025 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:42.689  1041  1756 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:42.690  7673  8026 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:16:42.691  7673  8026 V BluetoothSapService: Succeed to create listening socket 
09-06 19:16:42.691  7673  8026 V BluetoothSapService: Accepting socket connection...
,09-06 19:16:42.703  8025  8025 V BT_SAP  : Event pipe created
09-06 19:16:42.703  8025  8025 V BT_SAP  : create_server_socket qcom.sap.server
09-06 19:16:42.703  8025  8025 V BT_SAP  : created socket fd 6
,09-06 19:16:42.825  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:42.825  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:42.825  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:42.825  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:16:42.825  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:42.825  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:42.825  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:42.825  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:42.830  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:42.833  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:42.834  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@341f5440 added. We now have 8 listener(s)
09-06 19:16:42.834  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:42.841  1041  1756 D WifiServiceImplEx: setWifiEnabled: false pid=6633, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:16:42.842  1041  1756 D WifiService: setWifiEnabled: false pid=6633, uid=10118
09-06 19:16:42.842  1041  1756 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:16:42.854  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:42.857  1041  1946 D WifiServiceImplEx: setWifiEnabled: true pid=6633, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-06 19:16:42.858  1041  1946 D WifiService: setWifiEnabled: true pid=6633, uid=10118
09-06 19:16:42.859  1041  1946 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:16:42.876  1041  1041 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-06 19:16:42.877  1041  1041 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-06 19:16:42.877  1041  1041 D Ulp_jni : JNI:system_update. Event-4
09-06 19:16:42.879  1041  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-06 19:16:42.879  1041  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 19:16:42.883  1041  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1041] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 19:16:42.883  1041  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:16:42.883  1041  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1041] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 19:16:42.883  1041  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:16:42.883  1041  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 19:16:42.884  1041  1522 E WifiHW  : unknown target_country: EU , set to default
09-06 19:16:42.884  1041  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 19:16:42.884  1041  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 19:16:42.884  1041  1522 I WifiUtil: gEnableBmps=1
09-06 19:16:43.509   310   896 D SoftapController: Softap fwReload - Ok
,09-06 19:16:43.519  1041  1522 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (627ms)
09-06 19:16:43.529   310   896 D CommandListener: Setting iface cfg
09-06 19:16:43.529   310   896 D CommandListener: Trying to bring down wlan0
,09-06 19:16:43.533   310   896 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:16:43.535  1041  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:43.539  1041  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-06 19:16:43.539  8046  8046 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:16:43.549  8046  8046 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:16:43.580  1041  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:16:43.580  1041  1522 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:16:43.580  1041  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:16:43.580  1041  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 19:16:43.580  1041  1522 D WifiMonitor: connecting to supplicant
09-06 19:16:43.599  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:16:43.603  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 19:16:43.639  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-06 19:16:43.641  8046  8046 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 19:16:43.641  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:43.642  7673  7673 V BluetoothOppNotification: new notify threadi!
09-06 19:16:43.642  7673  7673 V BluetoothOppNotification: send delay message
09-06 19:16:43.644  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:43.644  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:16:43.644  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:16:43.644  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:16:43.644  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:16:43.645  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:16:43.645  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 19:16:43.645  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:16:43.645  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:16:43.645  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:16:43.645  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 19:16:43.646  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:16:43.646  7673  8061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:16:43.648  7673  8061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@196ec4cc on behalf of 
09-06 19:16:43.648  7673  8061 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:16:43.654  7673  8061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-06 19:16:43.658  7673  8061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15e82315 on behalf of 
09-06 19:16:43.658  7673  8061 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:16:43.660  7673  8061 V BluetoothOppNotification: outbound notification was removed.
09-06 19:16:43.660  7673  8061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:16:43.662  7673  8061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5c5862a on behalf of 
09-06 19:16:43.663  7673  8061 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:16:43.666  7673  8061 V BluetoothOppNotification: inbound notification was removed.
09-06 19:16:43.666  7673  8061 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-06 19:16:43.669  7673  8061 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12771c1b on behalf of 
09-06 19:16:43.676  8046  8046 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:16:43.676  8046  8046 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-06 19:16:43.679  1041  1116 D Tethering: InitialState.processMessage what=4
,09-06 19:16:43.687  1041  1057 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8064 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-06 19:16:43.689  1041  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:16:43.745  8046  8046 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:16:43.794  1041  1946 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8087 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:16:43.798  8064  8085 W FormManager: Network not available. Please check & try again.
09-06 19:16:43.803  8046  8046 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-06 19:16:43.809  8046  8046 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-06 19:16:43.810  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:16:43.810  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-06 19:16:43.811  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:16:43.811  8064  8086 V FormManager: Network unavailable.
09-06 19:16:43.811  1041  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:16:43.811  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 19:16:43.811  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 19:16:43.811  1041  8103 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:16:43.811  1041  8103 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:16:43.812  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:43.812  1041  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:43.813  1041  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:43.813  8064  8086 V FormManager: Network unavailable.
09-06 19:16:43.813  1041  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:43.814  1041  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 19:16:43.814  1041  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 19:16:43.814  1041  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 19:16:43.814  1041  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 19:16:43.814  1041  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-06 19:16:43.815  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:43.815  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:43.815  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:43.815  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:43.815  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:16:43.816  1041  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:16:43.816  1041  1522 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:16:43.816  1041  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:16:43.816  1041  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 19:16:43.817  1041  1522 D WifiNative-wlan0: SET update_config 1: returned true
09-06 19:16:43.817  1041  1522 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:16:43.817  1041  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 19:16:43.817  1923  1923 D WfdService: Waiting for WifiP2p enabling
09-06 19:16:43.817  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:43.818  1041  1041 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 19:16:43.818  1041  1526 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 19:16:43.820  1041  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 19:16:43.820  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:43.820  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:43.820  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:43.820  663,3  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:43.820  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:43.820  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:43.820  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:43.820  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:16:43.824  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:16:43.826  1041  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 19:16:43.833  1041  1562 I ActivityManager: Killing 7178:com.lge.drmservice/u0a62 (adj 15): empty #17
09-06 19:16:43.834  1041  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-06 19:16:43.834  1041  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:16:43.860  1041  1522 D WifiStateMachine: enableVerboseLogging : level 2
09-06 19:16:43.860  1041  2005 W libprocessgroup: failed to open /acct/uid_10062/pid_7178/cgroup.procs: No such file or directory
09-06 19:16:43.861  1041  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 19:16:43.861  1041  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 19:16:43.861  1041  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 19:16:43.861  1041  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 19:16:43.861  1041  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 19:16:43.862  1041  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 19:16:43.862  1041  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 19:16:43.862  1041  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 19:16:43.862  1041  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 19:16:43.863  1041  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 19:16:43.863  1041  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 19:16:43.863  1041  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 19:16:43.863  1041  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 19:16:43.864  1041  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 19:16:43.864  1041  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:16:43.864  1041  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 19:16:43.864  1041  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 19:16:43.864  1041  1522 D WifiNative-HAL: Setting external_sim to 1
09-06 19:16:43.864  1923  1923 D WfdsService: Supplicant Connection state is changed : true
09-06 19:16:43.865  1041  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 19:16:43.865  7709  7709 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:43.865  1923  2324 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 19:16:43.865  1923  2324 D WfdsService: Set the WFDS Monitor: true
09-06 19:16:43.865  1923  2324 D WfdsMonitor: WfdsMonitorThread create
09-06 19:16:43.865  1923  2324 D WfdsMonitor: WFDS Monitor is created and started
09-06 19:16:43.865  1923  2324 D WfdsService: WiFi: Supplicant connection re-established
09-06 19:16:43.865  1041  1522 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 19:16:43.865  1041  1522 I WifiNative-HAL: startHal
09-06 19:16:43.865  1041  1522 D wifi    : setting scan oui 0x956ccc40
09-06 19:16:43.866  1923  8106 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 19:16:43.866  1041  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:16:43.866  1041  1522 I WifiNative-HAL: startHal
09-06 19:16:43.866  1041  1522 D wifi    : setting scan oui 0x956ccc40
09-06 19:16:43.866  1923  8106 E CtrlSupplicant: Succeed to open control connection
09-06 19:16:43.866  1041  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 19:16:43.866  1923  8106 E CtrlSupplicant: Succeed to open monitor connection
09-06 19:16:43.866  1923  8106 D WfdsMonitor: Supplicant connection established
09-06 19:16:43.866  1923  2324 D WfdsService: Connected to the supplicant for wfds
09-06 19:16:43.867  1041  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 19:16:43.867  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 19:16:43.867  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 19:16:43.868  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 19:16:43.868  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:16:43.868  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILT,ER-STOP
09-06 19:16:43.868  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:16:43.868  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 19:16:43.868  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 19:16:43.869  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 19:16:43.869  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:16:43.869  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:16:43.869  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:16:43.869  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:16:43.869  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:16:43.870  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:16:43.870  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 19:16:43.870  8046  8046 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 19:16:43.870  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 19:16:43.870  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:16:43.870  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-06 19:16:43.871  1041  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:16:43.872  1041  1522 E WifiNative: : [139,258,419 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 19:16:43.872  1041  1522 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 19:16:43.872  1041  1522 D WifiNative-wlan0: RECONNECT: returned true
09-06 19:16:43.872  1041  1522 D WifiNative-wlan0: doString: [STATUS]
09-06 19:16:43.873  1041  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:16:43.873  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:16:43.873  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:16:43.873  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:16:43.873  1041  1522 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:16:43.874  1041  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.875   310   896 D CommandListener: Setting iface cfg
09-06 19:16:43.875   310   896 D CommandListener: Trying to bring up p2p0
09-06 19:16:43.875  1041  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:16:43.875  1041  1521 D LGWifiP2pService: P2pEnablingState
09-06 19:16:43.875  1041  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.875  1041  1521 D LGWifiP2pService: P2p socket connection successful
09-06 19:16:43.875  1041  1521 D LGWifiP2pService: P2pEnabledState
09-06 19:16:43.876  1041  1041 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:16:43.876  1041  1041 D RttService: SCAN_AVAILABLE : 3
09-06 19:16:43.876  1041  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 19:16:43.876  1041  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.876  1041  1540 I WifiNative-HAL: startHal
09-06 19:16:43.876  1041  1540 D wifi    : getting scan capabilities on interface[1] = 0x956ccc40
09-06 19:16:43.876  1041  1540 D wifi    : failed to get capabilities : -3
09-06 19:16:43.876  1041  1540 E WifiScanningService: could not get scan capabilities
09-06 19:16:43.877  1923  1923 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 19:16:43.877  1923  1923 D WfdsService: WifiP2pState is changed : true
09-06 19:16:43.877  1041  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.877  1041  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:16:43.877  1923  2324 D WfdsService: Receive the WFDS_ENABLE Method
09-06 19:16:43.877  1923  2324 D WfdsService: Set the WFDS Monitor: true
09-06 19:16:43.878  1923  2324 D WfdsService: Connected to the supplicant for wfds
09-06 19:16:43.878  1923  2324 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 19:16:43.878  8046  8046 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 19:16:43.878  1923  2324 D WfdsService: selectPreferredScanChannel [36]
09-06 19:16:43.878  1923  2324 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 19:16:43.878  1041  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 19:16:43.879  1041  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 19:16:43.879  1041  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 19:16:43.879  1041  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 19:16:43.880  1923  1923 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 19:16:43.880  1041  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0,
09-06 19:16:43.880  1041  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 19:16:43.880  1923  1923 D WfdsService: isConnected: false
09-06 19:16:43.880  1041  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 19:16:43.880  1041  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 19:16:43.880  1041  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 19:16:43.880  1041  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 19:16:43.880  8046  8046 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 19:16:43.881  1041  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-06 19:16:43.881  1041  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 19:16:43.881  1041  1521 D LGWifiP2pService: before postfix = G3
09-06 19:16:43.881  1041  1521 D WifiServerServiceExt: postfix byte check : 2
09-06 19:16:43.881  1041  1521 D LGWifiP2pService: after postfix = G3
09-06 19:16:43.881  1041  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 19:16:43.881  1041  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 19:16:43.881  1041  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 19:16:43.882  1041  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 19:16:43.882  1041  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,09-06 19:16:43.882  1041  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 19:16:43.882  1041  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 19:16:43.882  1041  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 19:16:43.882  1041  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:16:43.883  1041  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 19:16:43.883  1041  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 19:16:43.883  1041  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,09-06 19:16:43.884  1041  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 19:16:43.884  1041  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,09-06 19:16:43.885  1923  1923 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 19:16:43.885  1923  1923 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 19:16:43.885  1923  1923 D WfdsService: Update P2p Interface State: 3
,09-06 19:16:43.885  1041  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 19:16:43.885  1041  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 19:16:43.886  1041  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,09-06 19:16:43.886  1041  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 19:16:43.886  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:16:43.886  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:43.886  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:43.886  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:43.886  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:43.886  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:16:43.886  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:16:43.886  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:16:43.887  1041  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 19:16:43.887  1041  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 19:16:43.888  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:16:43.888  1041  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 19:16:43.888  1041  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 19:16:43.894  6633  6722 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-06 19:16:43.895  6633  6722 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:16:43.895  8046  8046 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 19:16:43.895  1041  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:16:43.896  1041  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:16:43.896  1041  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 19:16:43.896  1041  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:16:43.896  1041  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:16:43.896  1041  1521 D LGWifiP2pService: InactiveState
09-06 19:16:43.896  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 19:16:43.896  6633  6722 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@29d671c2 Bundle[{}]
09-06 19:16:43.896  1041  1521 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.896  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.896  1041  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 19:16:43.897  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:16:43.897  6633  6722 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:16:43.897  8046  8046 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:43.897  6633  6722 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:16:43.897  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:16:43.897  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:43.898  1041  8103 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:43.898  1041  8103 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:43.898  8046  8046 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:16:43.898  8046  8046 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.898  1041  8103 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:43.898  1041  8103 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.898  1041  8103 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.898  6633  6722 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 19:16:43.898  1041  8103 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.898  8046  8046 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.898  1041  8103 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:43.898  1041  8103 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.898  1041  8103 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.899  1041  8103 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.899  6633  6722 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:16:43.899  1041  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 19:16:43.899  6633  6722 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-06 19:16:43.899  1041  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:16:43.900  1041  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:16:43.900  6633  6722 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-06 19:16:43.900  1041  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:16:43.900  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 19:16:43.900  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 19:16:43.900  8046  8046 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-06 19:16:43.900  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 19:16:43.900  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:16:43.900  1041  8103 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:16:43.900  1041  8103 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:16:43.901  1923  8106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:43.901  1923  8106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:43.901  1041  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 19:16:43.901  1041  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 19:16:43.901  1041  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 19:16:43.901  1041  1522 D WifiNative-wlan0: doBoolean: SCAN
09-06 19:16:43.901  1041  1522 D WifiNative-wlan0: SCAN: returned false
09-06 19:16:43.902  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=139289  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:16:43.903  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=139289  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:16:43.903  1041  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:16:43.903  1041  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:16:43.904  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:43.904  1041  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-06 19:16:43.904  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:43.904  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:16:43.904  1041  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:16:43.904  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:16:43.904  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:43.905  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:16:43.905  8046  8046 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:43.905  1041  8103 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:16:43.905  1041  8103 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ,
09-06 19:16:43.905  1041  8103 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:43.905  1041  8103 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:16:43.905  1923  8106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:16:43.905  8046  8046 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,09-06 19:16:43.906  8046  8046 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.906  1041  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 19:16:43.906  1041  1521 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.906  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler },
09-06 19:16:43.906  8046  8046 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.906  1041  1521 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.906  1041  1521 D LGWifiP2pService: InactiveState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:43.906  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.906  1041  1521 D LGWifiP2pService: DefaultState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.906  1041  1521 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.906  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.907  1041  1521 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:43.907  1041  8103 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:43.907  1041  8103 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.907  1041  1521 D LGWifiP2pService: InactiveState{ when=-10ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.907  1923  2324 W WfdsService: DefaultState - msg [9441285] is not handled
,09-06 19:16:43.907  1041  8103 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
09-06 19:16:43.907  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.907  1041  8103 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.907  1041  1521 D LGWifiP2pService: DefaultState{ when=-10ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.907  1041  8103 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD],
09-06 19:16:43.907  1041  8103 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.907  1041  8103 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.907  1041  1041 E WifiServerServiceExt: No p2p device connected
09-06 19:16:43.907  1041  1521 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:16:43.907  1041  8103 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:16:43.907  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:43.907  1923  8106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:43.907  1923  8106 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:16:43.907  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:43.909  1041  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:16:43.909  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-06 19:16:43.909  1041  1041 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 19:16:43.910  6633  6722 I System.out: Running OutgoingSocketThread
09-06 19:16:43.911  6633  8109 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
,09-06 19:16:43.912  6633  8109 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47541,
09-06 19:16:43.912  6633  8109 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-06 19:16:43.912  8087  8087 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:43.915  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:43.920  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:43.921  1041  1756 I ActivityManager: Killing 7196:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-06 19:16:43.940  1041  1056 W libprocessgroup: failed to open /acct/uid_10085/pid_7196/cgroup.procs: No such file or directory
,09-06 19:16:43.948  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:43.948  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-06 19:16:43.948  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:16:43.948  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:16:43.949  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:16:43.949  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:16:43.949  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:16:43.949  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:16:43.949  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:16:43.949  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:16:43.949  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:16:43.956  8087  8087 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:16:43.958  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:16:43.962  8064  8111 W FormManager: Network not available. Please check & try again.
09-06 19:16:43.964  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:43.964  8064  8112 V FormManager: Network unavailable.
09-06 19:16:43.967  8064  8112 V FormManager: Network unavailable.
09-06 19:16:43.975  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:16:43.975  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:16:43.976  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:16:43.979  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:16:43.983  4326  8113 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:16:43.986  4326  8114 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:16:43.986  4326  8114 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:16:44.048  1041  1056 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8115 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 19:16:44.217  8115  8115 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:16:44.217  8115  8115 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 19:16:44.221  8115  8115 V [BNRBootReceiver]: Boot Receiver Return
,09-06 19:16:44.221  8115  8115 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:16:44.268  1041  1635 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8136 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:16:44.270  1041  1635 I ActivityManager: Killing 7231:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-06 19:16:44.382  1041  1057 W libprocessgroup: failed to open /acct/uid_10093/pid_7231/cgroup.procs: No such file or directory
,09-06 19:16:44.396  8046  8046 E wpa_supplicant: USIM:  scard_init function
09-06 19:16:44.398  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 19:16:44.398  8046  8046 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 19:16:44.399  1041  8103 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 19:16:44.399  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 19:16:44.400  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-06 19:16:44.400  1041  8103 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 19:16:44.400  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,09-06 19:16:44.402  1041  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:16:44.403  1041  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:16:44.405  1041  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:16:44.406  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 19:16:44.407  1041  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-06 19:16:44.407  1041  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 19:16:44.415  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=139802  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:16:44.418  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.418  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:16:44.421  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.423  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.423  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.423  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:16:44.426  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=139813  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:16:44.432  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.432  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.432  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-06 19:16:44.433  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-06 19:16:44.433  1041  1041 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 19:16:44.440  8136  8136 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:16:44.442  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.442  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:44.446  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:16:44.465  8136  8136 D PluginManager: init()
,09-06 19:16:44.513  8046  8046 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-06 19:16:44.513  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 19:16:44.513  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 19:16:44.514  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 19:16:44.514  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 19:16:44.514  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:44.514  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=139901  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:16:44.514  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:44.515  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=139902  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:16:44.515  1041  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139902
09-06 19:16:44.516  1041  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139903
09-06 19:16:44.516  1041  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139903
09-06 19:16:44.517  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139903
09-06 19:16:44.517  1041  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139904
09-06 19:16:44.518  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=139904  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-06 19:16:44.524  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.524  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.524  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:16:44.525  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.525  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:44.529  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.529  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.529  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 19:16:44.530  1041  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:16:44.532  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:44.532  8046  8046 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:44.532  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:44.532  8046  8046 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:16:44.532  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 19:16:44.532  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:44.533  1041  8103 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:16:44.533  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 19:16:44.533  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:16:44.533  1041  8103 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-06 19:16:44.538  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.540  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:44.540  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:44.541  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=139928  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:16:44.542  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.542  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:44.542  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:44.543  1041  1041 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 19:16:44.543  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.544  1041  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:44.545  1041  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:44.545  1041  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:44.545  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:44.546  1041  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:16:44.546  1041  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139933  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:16:44.547  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139934  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:16:44.548  1041  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139935
,09-06 19:16:44.548  1041  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139935
09-06 19:16:44.549  1041  1522 D WifiNative-wlan0: doString: [STATUS]
09-06 19:16:44.549  1041  8103 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:16:44.549  1041  8103 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:16:44.549  1041  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:16:44.551  1041  1522 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 19:16:44.559  1041  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 19:16:44.559  1041  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-06 19:16:44.563  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.563  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.563  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-06 19:16:44.566  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.566  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:44.569  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.569  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.569  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.569  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:16:44.571  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.571  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:44.572  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.576  1041  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,09-06 19:16:44.577  1041  1528 D ConnectivityService: Got NetworkAgent Messenger
09-06 19:16:44.577  1041  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:16:44.577  1041  1528 D ConnectivityService: NetworkAgent connected
09-06 19:16:44.577  1041  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:16:44.577  1041  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:16:44.577  1041  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:16:44.578  1041  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:16:44.583  1041  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:16:44.584  1041  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:16:44.584  1041  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:16:44.584  1041  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:16:44.584  1041  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:16:44.589  1041  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-06 19:16:44.591   310   896 D CommandListener: Setting iface cfg
09-06 19:16:44.597  1041  1522 E WifiStateMachine: Start Dhcp Watchdog 3
09-06 19:16:44.597  1041  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139984  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:44.598  1041  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139985  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:44.598  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=139985  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:44.599  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:44.599  1041  1041 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-06 19:16:44.607  1041  8158 D DhcpStateMachine: StoppedState
,09-06 19:16:44.608  1041  8158 D DhcpStateMachine: StoppedState{ when=-11ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:44.608  1041  8158 D DhcpStateMachine: WaitBeforeStartState
09-06 19:16:44.610  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:44.610  1041  1041 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 19:16:44.611  1041  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139998  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:44.612  1041  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139998  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:44.612  1041  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139999  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:16:44.613  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14051] from screen [on:0 period:8422085] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:16:44.614  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:8422086] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:16:44.614  1041  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 19:16:44.618  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.619  1041  1528 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-06 19:16:44.619  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.620  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.621  1041  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.622  1041  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.622  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.623  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.623  1041  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:16:44.624  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=161,0,0
,09-06 19:16:44.624  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:16:44.624  1041  1041 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:16:44.624  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=161,0,0
09-06 19:16:44.624  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 19:16:44.625  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 19:16:44.625  1041  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 19:16:44.625  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 19:16:44.625  1041  1522 D WifiNative-wlan0: SET ps 0: returned true
09-06 19:16:44.625  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 19:16:44.626  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 19:16:44.626  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 19:16:44.626  1041  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31e7e2e0 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:44.626  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31e7e2e0 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:44.627  1041  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 19:16:44.627  1041  8158 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:44.627  1041  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:16:44.627  1041  8158 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 19:16:44.627  1041  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:16:44.628   310   896 D CommandListener: Setting iface cfg
09-06 19:16:44.629   310   896 D CommandListener: Trying to bring up wlan0
09-06 19:16:44.630  1041  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 19:16:44.631  1041  1041 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-06 19:16:44.631  1041  1041 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:16:44.632  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.632  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.632  1041  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.633  1041  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.633  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.634  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:16:44.634  1041  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:16:44.634  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:16:44.635  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:16:44.635  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:16:44.635  1041  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:44.635  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:16:44.635  1041  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:44.635  1041  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:16:44.635  1041  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 19:16:44.636  8046  8046 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 19:16:44.636  1041  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 19:16:44.636  1041  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:16:44.653  1041  1522 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:16:44.653  1041  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-06 19:16:44.653  1041  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:16:44.654  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:16:44.654  1041  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:16:44.656  1041  1528 D ConnectivityService: ignoring duplicate network state non-change
09-06 19:16:44.659  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.659  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:44.660  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.660  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.660  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:16:44.661  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.661  1041  1528 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:16:44.662  1041  1528 D ConnectivityService: Adding iface wlan0 to network 102
,09-06 19:16:44.670  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.670  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.670  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:16:44.672  1041  1041 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:16:44.673  1041  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:16:44.675  1923  1923 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 19:16:44.676  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.676  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.676  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:16:44.676  1041  1041 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-06 19:16:44.680  1041  1041 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.680  1041  1041 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:16:44.680  1041  1041 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:16:44.685  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.685  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:16:44.686  1041  1528 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:16:44.686  1041  1528 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-06 19:16:44.687  1041  1528 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-06 19:16:44.688  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.688   310   896 E Netd    : netlink response contains error (File exists)
09-06 19:16:44.688  1041  1528 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-06 19:16:44.689  1041  1528 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 19:16:44.689  1041  1528 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-06 19:16:44.689  1041  1528 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-06 19:16:44.690  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.690  1585  1585 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:16:44.690  1041  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:16:44.690  1041  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 19:16:44.690  1041  1528 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-06 19:16:44.691  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.692  1041  8153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:44.692  1041  8153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 19:16:44.692  1041  8153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:16:44.692  1041  8153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-06 19:16:44.695  1041  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 19:16:44.695  1041  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:44.695  1041  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:44.695  1041  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:16:44.695  1041  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.695  1041  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 19:16:44.695  1041  1528 D ConnectivityService: currentScore = 0, newScore = 20
09-06 19:16:44.696  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:16:44.696  1041  1528 D ConnectivityService:    accepting network in place of null
09-06 19:16:44.696  1041  1528 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.696  1585  1585 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:16:44.696  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.697  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.697  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:16:44.698  1041  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.698  1041  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:44.698   310  8164 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 19:16:44.699  1041  1528 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:16:44.699  1041  1528 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-06 19:16:44.699  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:16:44.699  1041  1528 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:16:44.700  1041  1528 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 19:16:44.700  1041  1528 D ConnectivityService: Switching to new default n,etwork: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 19:16:44.700  1041  1041 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 19:16:44.700  1041  1041 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:16:44.700  1041  1041 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:16:44.700  1041  1041 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:16:44.701  1041  1528 D ConnectivityService: validation of new default Network = false
09-06 19:16:44.701  1041  1528 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 19:16:44.701  1041  1528 D DSQN    : enableDataServiceNotify 
09-06 19:16:44.701  1041  1528 D DSQN    : start dsqn bin
09-06 19:16:44.707  1041  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 19:16:44.707  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.707  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:44.707  1041  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:44.699  8165  8165 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:44.699  8165  8165 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:44.708  1041  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-06 19:16:44.708  1585  2028 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:16:44.722  8165  8165 E DSQN    : DSQN ssw
,09-06 19:16:44.731  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-06 19:16:44.732  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.733  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.751   310  8164 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-06 19:16:44.786   310  8164 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-06 19:16:44.818   310   895 D LGDataListener: argv[0]=dsqncommand
,09-06 19:16:44.818   310   895 D LGDataListener: argv[1]=wlan0
09-06 19:16:44.818   310   895 D LGDataListener: argv[2]=1
09-06 19:16:44.818   310   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-06 19:16:44.819  1041  1114 D DSQN    : DSQM DsqnNotification wlan0  1
,09-06 19:16:44.819  1041  1114 D DSQN    : start to monitor internet connection
09-06 19:16:44.829  1041  8158 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 19:16:44.831  1041  8158 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 19:16:44.831  1041  8158 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-06 19:16:44.819  8171  8171 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:16:44.829  8171  8171 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:16:44.852  1041  8153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:16:44 GMT], X-Android-Received-Millis=[1473182204851], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473182204817]}
09-06 19:16:44.852  1041  8153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 19:16:44.852  1041  8153 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-06 19:16:44.852  1041  1528 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-06 19:16:44.853  1041  1528 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 19:16:44.853  1041  1528 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:44.853  1041  1528 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:44.853  1041  1528 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:16:44.853  1041  1528 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,09-06 19:16:44.853  1041  1528 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 19:16:44.853  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.853  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:44.854  1041  1528 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:44.854  1041  1528 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.855  1585  2028 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:16:44.856  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.857  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:16:44.857  1041  1522 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:44.857  1041  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:16:44.858  1041  1528 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:16:44.859  8171  8171 I dhcpcd  : version 5.5.6 starting
09-06 19:16:44.862  8171  8171 E dhcpcd  : get_duid: m
09-06 19:16:44.862  8171  8171 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 19:16:44.862  8171  8171 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-06 19:16:44.878  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:16:44.879  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.879  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:16:44.913  6633  6722 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
09-06 19:16:44.913  6633  6722 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
,09-06 19:16:44.924  6633  6722 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
,09-06 19:16:44.927  8171  8171 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:16:44.927  6633  6722 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 19:16:44.927  6633  6722 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
09-06 19:16:44.927  8171  8171 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-06 19:16:44.927  8171  8171 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:16:44.927  8171  8171 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 19:16:44.927  8171  8171 D dhcpcd  : wlan0: sending REQUEST (xid 0x6aa6104e), next in 3.30 seconds
09-06 19:16:44.930  8136  8136 W ExternalStrings: load override strings
09-06 19:16:44.930  8136  8136 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:16:44.930  8136  8136 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:16:44.931  8136  8136 D StatusProvider: onCreate
09-06 19:16:44.934  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:44.934  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26828f79 added. We now have 2 listener(s)
09-06 19:16:44.935  1041  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:44.939  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:44.939  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:44.939  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:44.939  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:44.939  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de424be added. We now have 9 listener(s)
09-06 19:16:44.939  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:44.940  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery m,ode BLE is supported
,09-06 19:16:44.945  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:44.950  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:44.950  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:44.950  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:44.950  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:44.950  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:44.950  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:44.950  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:44.950  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:44.951  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:44.952  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:44.952  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:44.953  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10c5746c added. We now have 3 listener(s)
09-06 19:16:44.953  1041  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:44.954  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:44.956  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:16:44.960  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:44.960  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:44.960  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:44.961  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:44.961  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@513aa35 added. We now have 10 listener(s)
09-06 19:16:44.961  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:44.961  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:44.961  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:44.962  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:44.962  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:44.962  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:44.962  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:44.962  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:44.962  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26828f79 removed from the list
09-06 19:16:44.962  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:44.962  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de424be removed from the list
09-06 19:16:44.962  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:44.962  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:44.963  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:44.963  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:44.966  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:44.966  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:44.966  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:44.966  8171  8171 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-06 19:16:44.966  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de424be not in the list
09-06 19:16:44.967  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:44.967  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:44.967  8136  8136 V Signer  : override build config not found
09-06 19:16:44.967  8136  8136 D Signer  : value of property debug is false
09-06 19:16:44.968  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:44.968  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:44.968  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:44.968  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@513aa35 removed from the list
09-06 19:16:44.968  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:44.968  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:44.969  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:44.969  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:44.969  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10c5746c removed from the list
09-06 19:16:44.969  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:44.969  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139ceca added. We now have 2 listener(s)
09-06 19:16:44.970  1041  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:44.972  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:44.972  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:44.972  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:44.972  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:44.972  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cdac83b added. We now have 9 listener(s)
09-06 19:16:44.972  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:44.972  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:16:44.974  6633  6722 I org.thaliproject.p2,p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:44.978  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:44.978  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:44.978  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:44.978  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:44.978  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:44.978  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:44.978  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:44.978  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:44.979  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:44.979  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:44.981  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:44.981  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3161b4b1 added. We now have 3 listener(s)
09-06 19:16:44.981  1041  1756 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:44.981  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:44.986  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:44.987  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:44.987  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:44.987  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:44.987  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:44.987  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d8e0d96 added. We now have 10 listener(s)
09-06 19:16:44.987  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:44.987  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:44.987  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:44.987  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:44.987  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:16:44.987  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:16:44.990  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:16:44.990  1041  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:16:44.994  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:16:44.995  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:16:44.996  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:16:44.997  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:44.998  8171  8171 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 19:16:44.998  8171  8171 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 19:16:44.998  8171  8171 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 19:16:44.998  8171  8171 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 19:16:44.999  8171  8171 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:16:44.999  6633  6722 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:16:44.999  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:44.999  8171  8171 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:16:44.999  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:44.999  8171  8171 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:16:44.999  8171  8171 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-06 19:16:45.001  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:45.001  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:45.001  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:45.002  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:45.002  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.002  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:45.002  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:45.002  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139ceca removed from the list
09-06 19:16:45.002  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.002  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cdac83b removed from the list
09-06 19:16:45.002  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:45.002  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.002  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.002  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release,: 1 listener(s) left
,09-06 19:16:45.004  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:45.004  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:45.004  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.004  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cdac83b not in the list
09-06 19:16:45.004  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.004  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.005  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:45.005  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:45.005  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:45.005  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:45.006  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.006  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d8e0d96 removed from the list
09-06 19:16:45.006  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:45.006  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.006  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.006  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:45.006  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3161b4b1 removed from the list
09-06 19:16:45.006  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:45.006  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20abeaed added. We now have 2 listener(s)
09-06 19:16:45.007  1041  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:45.010  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:45.011  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:45.011  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:45.011  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:45.011  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b156d22 added. We now have 9 listener(s)
09-06 19:16:45.011  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:45.011  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:16:45.013  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blueto,othManager: bind: Binding a new listener
,09-06 19:16:45.017  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:45.017  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:45.017  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:45.017  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:45.017  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:45.017  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:45.017  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:45.017  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:45.019  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:45.019  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:45.019  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:45.019  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36d04d70 added. We now have 3 listener(s)
09-06 19:16:45.019  1041  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:45.020  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:45.022  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:45.022  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:45.022  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:45.022  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:45.022  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:45.022  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e948e9 added. We now have 10 listener(s)
09-06 19:16:45.022  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:45.022  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:45.023  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:45.023  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:45.023  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:45.023  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:45.023  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:16:45.025  6633  6722 V, org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:16:45.025  1041  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:16:45.030  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:16:45.030  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:16:45.032  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:16:45.032  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:45.033  6633  6722 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:16:45.034  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:45.034  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:45.034  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:45.034  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:45.034  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.034  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:45.034  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:45.034  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20abeaed removed from the list
09-06 19:16:45.034  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.034  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b156d22 removed from the list
09-06 19:16:45.034  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:45.034  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.035  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.035  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.036  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:45.036  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:45.036  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.036  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b156d22 not in the list
09-06 19:16:45.036  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.036  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.036  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:45.037  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:45.037  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:45.037  6633  6722 I, org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:45.037  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.037  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e948e9 removed from the list
09-06 19:16:45.037  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:45.037  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.037  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.037  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:45.038  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36d04d70 removed from the list
,09-06 19:16:45.038  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:45.038  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@144d09c added. We now have 2 listener(s)
09-06 19:16:45.039  1041  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:45.041  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:45.041  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:45.041  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:45.041  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:45.041  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36848aa5 added. We now have 9 listener(s)
09-06 19:16:45.041  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:45.041  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:16:45.044  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-06 19:16:45.044  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:45.044  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-06 19:16:45.044  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-06 19:16:45.044  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-06 19:16:45.045  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-06 19:16:45.045  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-06 19:16:45.045  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-06 19:16:45.045  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-06 19:16:45.046  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-06 19:16:45.046  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:45.046  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:45.046  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:45.046  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:45.046  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:45.046  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:45.046  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:45.046  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:16:45.046  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-06 19:16:45.046  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-06 19:16:45.047  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,09-06 19:16:45.048  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:45.048  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:45.048  8136  8136 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-06 19:16:45.048  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:45.048  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@320a362b added. We now have 3 listener(s)
09-06 19:16:45.048  1041  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:45.051  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:45.053  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:45.055  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:45.055  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:45.055  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:45.055  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:45.055  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1c5a88 added. We now have 10 listener(s)
09-06 19:16:45.055  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:45.056  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:45.056  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:16:45.056  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:16:45.056  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:45.056  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:16:45.063  8136  8136 V LGMDMManager: Create singleton instance
09-06 19:16:45.065  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:16:45.065  1041  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:45.070  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:16:45.071  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:16:45.072  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:16:45.072  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:45.074  6633  6722 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:16:45.076  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:45.076  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:16:45.076  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:45.076  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:45.076  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.076  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:45.076  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:45.076  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@144d09c removed from the list
09-06 19:16:45.076  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.076  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36848aa5 removed from the list
09-06 19:16:45.076  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:45.076  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.078  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.078  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.079  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:45.079  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:45.079  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.079  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36848aa5 not in the list
09-06 19:16:45.079  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.079  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.080  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:45.080  6633  6722 D BluetoothLeScanner: could not find callback wrapper
09-06 19:16:45.080  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:16:45.080  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:45.080  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.081  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1c5a88 removed from the list
09-06 19:16:45.081  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:45.081  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.081  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.081  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:45.081  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@320a362b removed from the list
09-06 19:16:,45.082  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:45.082  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f40a07 added. We now have 2 listener(s)
09-06 19:16:45.082  1041  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:45.084  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:45.084  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:45.084  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:45.085  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:45.085  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23609734 added. We now have 9 listener(s)
09-06 19:16:45.085  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:45.085  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:16:45.087  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:16:45.090  6633  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:16:45.090  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:16:45.090  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:16:45.090  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:16:45.090  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:16:45.090  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:45.090  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:16:45.090  6633  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:16:45.093  6633  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:16:45.094  6633  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:16:45.094  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:16:45.094  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85762d2 added. We now have 3 listener(s)
09-06 19:16:45.094  1041  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:16:45.095  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:45.096  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:16:45.096  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:16:45.096  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:16:45.097  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:16:45.097  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dbd3fa3 added. We now have 10 listener(s)
09-06 19:16:45.097  6633  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:16:45.097  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:16:45.097  6633  6722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:16:45.097  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:45.097  6633  6722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:16:45.097  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:45.097  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.097  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:16:45.097  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:45.097  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f40a07 removed from the list
09-06 19:16:45.097  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.097  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23609734 removed from the list
09-06 19:16:45.097  6633  6722 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:16:45.097  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.099  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.099  6633  6722 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.108  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:45.108  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:45.108  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.108  6633  6722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23609734 not in the list
09-06 19:16:45.108  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.108  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:16:45.108  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:16:45.108  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:16:45.108  6633  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:16:45.108  6633  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dbd3fa3 removed from the list
09-06 19:16:45.108  6633  6722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:16:45.109  6633  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:16:45.109  6633  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:16:45.109  6633  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:16:45.109  6633  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85762d2 removed from the list
09-06 19:16:45.109  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:16:45.110  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:16:45.110  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:16:45.110  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:16:45.110  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:16:45.110  6633  6722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:16:45.119  6633  8192 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
09-06 19:16:45.119  6633  8192 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
09-06 19:16:45.119  6633  8192 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:16:45.124  6633  8193 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
09-06 19:16:45.124  6633  8193 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
09-06 19:16:45.124  6633  8193 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:16:45.125  6633  6722 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:16:45.125  6633  6722 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:16:45.125  6633  6722 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:16:45.125  6633  6722 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:16:45.126  6633  6722 D com.test.thalitest.ThaliTestRunner: Total duration: 22762 ms
09-06 19:16:45.127  6633  6722 I jxcore-log: *Native tests were executed*
09-06 19:16:45.127  6633  6722 I jxcore-log: 
09-06 19:16:45.127  6633  6722 I jxcore-log: Total number of executed tests:  80
09-06 19:16:45.127  6633  6722 I jxcore-log: 
09-06 19:16:45.127  6633  6722 I jxcore-log: Number of passed tests:  80
09-06 19:16:45.127  6633  6722 I jxcore-log: 
09-06 19:16:45.127  6633  6722 I jxcore-log: Number of failed tests:  0
09-06 19:16:45.127  6633  6722 I jxcore-log: 
09-06 19:16:45.127  6633  6722 I jxcore-log: Number of ignored tests:  0
09-06 19:16:45.127  6633  6722 I jxcore-log: 
09-06 19:16:45.128  6633  6722 I jxcore-log: Total duration:  22762
09-06 19:16:45.128  6633  6722 I jxcore-log: 
09-06 19:16:45.128  6633  6722 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:16:45.128  6633  6722 I jxcore-log: 
09-06 19:16:45.130  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.130  6633  6722 I jxcore-log: 
09-06 19:16:45.133  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.133  6633  6722 I jxcore-log: 
09-06 19:16:45.134  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.134  6633  6722 I jxcore-log: 
09-06 19:16:45.135  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.135  6633  6722 I jxcore-log: 
09-06 19:16:45.136  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.136  6633  6722 I jxcore-log: 
09-06 19:16:45.137  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.137  6633  6722 I jxcore-log: 
,09-06 19:16:45.138  6633  6633 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:16:45.139  8136  8136 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
09-06 19:16:45.141  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.141  6633  6722 I jxcore-log: 
09-06 19:16:45.143  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.143  6633  6722 I jxcore-log: 
09-06 19:16:45.144  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.144  6633  6722 I jxcore-log: 
09-06 19:16:45.145  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:16:45.145  6633  6722 I jxcore-log: 
09-06 19:16:45.146  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:16:45.146  6633  6722 I jxcore-log: 
09-06 19:16:45.147  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:16:45.147  6633  6722 I jxcore-log: 
09-06 19:16:45.148  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.148  6633  6722 I jxcore-log: 
,09-06 19:16:45.149  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.149  6633  6722 I jxcore-log: 
09-06 19:16:45.150  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.150  6633  6722 I jxcore-log: 
09-06 19:16:45.150  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.150  6633  6722 I jxcore-log: 
09-06 19:16:45.151  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.151  6633  6722 I jxcore-log: 
09-06 19:16:45.152  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.152  6633  6722 I jxcore-log: 
09-06 19:16:45.152  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.152  6633  6722 I jxcore-log: 
09-06 19:16:45.153  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:16:45.153  6633  6722 I jxcore-log: 
09-06 19:16:45.153  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:45.153  6633  6722 I jxcore-log: 
09-06 19:16:45.154  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:16:45.154  6633  6722 I jxcore-log: 
09-06 19:16:45.155  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.155  6633  6722 I jxcore-log: 
09-06 19:16:45.155  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.155  6633  6722 I jxcore-log: 
09-06 19:16:45.156  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.156  6633  6722 I jxcore-log: 
09-06 19:16:45.157  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.157  6633  6722 I jxcore-log: 
09-06 19:16:45.157  6633  6722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:16:45.157  6633  6722 I jxcore-log: 
09-06 19:16:45.186  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.187  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:16:45.193  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:16:45.196  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:45.205  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:16:45.207  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:45.218  7875  7875 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:16:45.221  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-06 19:16:45.223  6803  6803 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 19:16:45.236  1041  8158 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-06 19:16:45.238  1041  8158 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 19:16:45.238  1041  8158 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:16:45.238  1041  8158 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 19:16:45.238  1041  8158 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 19:16:45.238  1041  8158 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:16:45.238  1041  8158 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 19:16:45.238  1041  8158 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 19:16:45.239  1041  8158 D DhcpStateMachine: RunningState
09-06 19:16:45.294  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:45.295  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:16:45.296  8136  8201 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-06 19:16:45.315  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:45.320  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:45.329  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:45.330  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:45.333  7875  7875 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:16:45.338  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.338  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:16:45.348  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:45.352  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:45.362  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:45.362  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:45.362  7875  7875 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:45.365  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.365  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:16:45.373  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:45.377  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:45.383  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:45.384  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:45.384  7875  7875 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:45.387  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.388  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:16:45.395  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:45.400  8206  8206 D AndroidRuntime: 
09-06 19:16:45.400  8206  8206 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:16:45.402  8206  8206 D AndroidRuntime: CheckJNI is OFF
09-06 19:16:45.402  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:45.409  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:45.410  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:45.410  7875  7875 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:45.413  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:16:45.413  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:16:45.413  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:16:45.413  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-06 19:16:45.414  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-06 19:16:45.415  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:16:45.416  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 19:16:45.417  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:16:45.417  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:16:45.417  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:16:45.417  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 19:16:45.417  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:16:45.421  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.421  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:16:45.428  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:45.437  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:16:45.445  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:45.446  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:45.447  7875  7875 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:45.450  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.450  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:16:45.457  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:45.463  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:45.468  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:45.469  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:45.469  7875  7875 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:16:45.479  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.480  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:16:45.491  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:45.496  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:45.503  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:45.503  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:45.508  7875  7875 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:45.512  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.512  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:16:45.513  8206  8206 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-06 19:16:45.520  1041  1097 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-06 19:16:45.520  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:45.520  1041  1097 I ActivityManager: Killing 6633:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-06 19:16:45.525  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:45.528  8136  8201 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:16:45.528  8136  8201 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:16:45.552  1041  1527 D WifiService: Client connection lost with reason: 4
,09-06 19:16:45.552  1041  1936 I WindowState: WIN DEATH: Window{138eb716 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:16:45.558  1041  1936 D InputDispatcher: Window went away: Window{138eb716 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:16:45.686  8136  8201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-06 19:16:45.743  1041  1097 I ActivityManager:   Force finishing activity ActivityRecord{3846c353 u0 com.test.thalitest/.MainActivity t6}
,09-06 19:16:45.800   333   385 E GBMv2   : DFP En is all cleared set to be enabled
,09-06 19:16:45.812  1041  1522 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:45.813  1041  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:45.814  1041  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:45.815  1041  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:45.816  1041  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:45.816  1041  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:16:45.818  1041  1528 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-06 19:16:45.818  1041  1528 D ConnectivityService: identical MTU - not setting
09-06 19:16:45.818  1041  1528 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:16:45.818  1041  1528 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 19:16:45.818  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:16:45.818  1041  1528 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:45.819  1041  1528 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:16:45.820  1585  2028 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:16:45.823  1041  1562 W ActivityManager: Spurious death for ProcessRecord{bfe5140 6633:com.test.thalitest/u0a118}, curProc for 6633: null
09-06 19:16:45.825  2016  2016 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-06 19:16:45.828  2016  2016 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-06 19:16:45.833  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:45.833  1041  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-06 19:16:45.833  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:45.834  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-06 19:16:45.834  7875  7875 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:16:45.835  2016  2110 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
09-06 19:16:45.836  1041  1122 I ActivityManager:   Force finishing activity ActivityRecord{3846c353 u0 com.test.thalitest/.MainActivity t6 f}
09-06 19:16:45.836  1041  1122 W ActivityManager: Duplicate finish request for ActivityRecord{3846c353 u0 com.test.thalitest/.MainActivity t6 f}
,09-06 19:16:45.851  8136  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-06 19:16:45.861  8136  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-06 19:16:45.862  1923  2543 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-06 19:16:45.863  1923  2543 D SplitWindowPolicy: topRunningActivity=ActivityInfo{130e57cf co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 19:16:45.863  1585  1585 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-06 19:16:45.864  8136  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 19:16:45.864  1923  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-06 19:16:45.864  1923  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{34f6a55c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 19:16:45.870  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-06 19:16:45.871  3781  3781 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-06 19:16:45.877  7673  7673 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-06 19:16:45.877  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 19:16:45.880  2484  2634 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-06 19:16:45.882  8136  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 19:16:45.882  4490  4490 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-06 19:16:45.882  4490  4490 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-06 19:16:45.882  4490  4490 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-06 19:16:45.882  4490  4490 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-06 19:16:45.883  4490  4490 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:16:45.883  4490  4490 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:16:45.883  4490  4490 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:16:45.883  4490  4490 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:16:45.883  4490  4490 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:16:45.883  4490  4490 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:16:45.883  4490  4490 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:16:45.883  4490  4490 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:16:45.891  1041  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:16:45.899  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-06 19:16:45.901  1887  1887 D ActionManagerService: notifyUserLog: 1000003
09-06 19:16:45.901  3781  4513 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-06 19:16:45.902  8136  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-06 19:16:45.903  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:45.903  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:16:45.907  4607  4607 I art     : Explicit concurrent mark sweep GC freed 8181(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 564us total 57.815ms
09-06 19:16:45.908  8136  8201 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-06 19:16:45.913  2016  2016 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-06 19:16:45.926  8136  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-06 19:16:45.956  1041  1946 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:16:45.963  1041  1041 D administrator: Handling package changes for user 0
09-06 19:16:45.968  8136  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-06 19:16:46.006  2016  2016 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-06 19:16:46.018  1585  1631 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 19:16:46.018  1585  1631 D KeyguardModel: createShortcutInfo...
,09-06 19:16:46.018  2016  2016 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-06 19:16:46.020  1585  1631 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 19:16:46.020  1585  1631 D KeyguardModel: createShortcutInfo...
,09-06 19:16:46.021  1585  1585 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-06 19:16:46.023  1887  1887 D ActionManagerService: notifyUserLog: 1000004
09-06 19:16:46.023  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-06 19:16:46.024  8087  8087 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:16:46.024  3781  4513 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-06 19:16:46.024  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 19:16:46.025  1585  1631 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:46.025  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 19:16:46.026  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:16:46.026  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:16:46.027  1585  1631 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 19:16:46.027  8087  8087 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:46.029  3781  3797 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:16:46.033  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:16:46.037  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:46.040  1585  1631 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 19:16:46.040  1585  1631 D KeyguardModel: createShortcutInfo...
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262123
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , expire_time: 0
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , display: false
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , animation: false }
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262287
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , expire_time: 0
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , display: false
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , animation: false }
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , create_time: 1472828323917
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , expire_time: 0
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , display: false
09-06 19:16:46.045  2016  2016 I GBoardWebViewUtils: , animation: false }
,09-06 19:16:46.052  1041  1057 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:16:46.052  1041  1057 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:16:46.056  2016  8241 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-06 19:16:46.057  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:46.057  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:16:46.058  7875  7875 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:16:46.062  7875  7875 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:16:46.064  7875  7875 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:16:46.074  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-06 19:16:46.074  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 19:16:46.074  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:16:46.075  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-06 19:16:46.076  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:16:46.076  1585  1631 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 19:16:46.077  1585  1631 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 19:16:46.079  1585  1631 D KeyguardModel: createShortcutInfo...
09-06 19:16:46.086  1585  1585 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-06 19:16:46.086  1585  1585 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-06 19:16:46.091  1585  1631 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:46.091  1585  1631 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 19:16:46.091  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 19:16:46.091  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-06 19:16:46.107  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:16:46.107  1585  1631 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 19:16:46.107  1041  1972 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:16:46.108  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:16:46.109  1585  1631 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 19:16:46.109  1585  1631 D KeyguardModel: createShortcutInfo...
09-06 19:16:46.109  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:46.109  8136  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:16:46.115  8087  8087 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 19:16:46.117  1853  1853 D SplitUIManager: split_name #11 / not available #0
09-06 19:16:46.117  1853  1853 D SplitUIService: removed split : 
09-06 19:16:46.117  8087  8087 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:16:46.121  1585  1585 D KeyguardModel: handleShortcutListChanged...
09-06 19:16:46.121  1585  1585 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-06 19:16:46.126  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:16:46.129  1585  1631 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 19:16:46.129  1585  1631 D KeyguardModel: createShortcutInfo...
,09-06 19:16:46.134  1585  1631 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 19:16:46.134  1585  1631 D KeyguardModel: createShortcutInfo...
09-06 19:16:46.139  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:16:46.139  1585  1631 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 19:16:46.144  2016  2016 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-06 19:16:46.144  1585  1631 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 19:16:46.144  1585  1631 D KeyguardModel: createShortcutInfo...
09-06 19:16:46.144  1041  1041 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-06 19:16:46.145  1041  1041 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 19:16:46.145  1041  1041 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:16:46.147  1041  1936 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:16:46.149  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:16:46.149  1585  1631 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-06 19:16:46.151  1585  1631 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 19:16:46.151  1585  1631 D KeyguardModel: createShortcutInfo...
09-06 19:16:46.152  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:16:46.152  1585  1631 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 19:16:46.153  1853  1853 D SplitUIManager: split_name #11 / not available #0
09-06 19:16:46.153  1853  1853 I SplitUIService: split app #11
09-06 19:16:46.155  1585  1631 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 19:16:46.155  1585  1631 D KeyguardModel: createShortcutInfo...
09-06 19:16:46.165  1041  1560 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-06 19:16:46.167  1041  1096 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-06 19:16:46.168  1585  1585 D KeyguardModel: handleShortcutListChanged...
09-06 19:16:46.168  1585  1585 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-06 19:16:46.181  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:16:46.203  7875  7875 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:16:46.203  7875  7875 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:16:46.204  7875  7875 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-06 19:16:46.204  7875  7875 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:16:46.204  7875  7875 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-06 19:16:46.217  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:46.218  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-06 19:16:46.221  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:16:46.222  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-06 19:16:46.223  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-06 19:16:46.224  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-06 19:16:46.225  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-06 19:16:46.251  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-06 19:16:46.251  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:16:46.251  2016  2188 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-06 19:16:46.251  2016  2188 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,09-06 19:16:46.256  1041  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cdf338d u0 com.lge.launcher2/.Launcher t5} time:141659
09-06 19:16:46.268  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-06 19:16:46.269  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,09-06 19:16:46.269  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:16:46.278  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:46.280  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:46.281  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:46.283  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:46.284  2016  2016 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-06 19:16:46.285  2579  2579 D [Concierge]Service: onStartCommand(). Type : 8
09-06 19:16:46.285  2579  2579 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-06 19:16:46.286  2579  2579 D [Concierge]Service: Update widget ID : 11
09-06 19:16:46.287  2016  2016 D [Concierge]WidgetView: change position of spinner
09-06 19:16:46.288  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:46.288  2016  2016 I [Concierge]WidgetView: initWebView(). Time : 1473182206288
09-06 19:16:46.288  2579  2579 D [Concierge]Service: onStartCommand(). Type : 0
09-06 19:16:46.291  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:46.293  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:16:46.295  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:16:46.297  8136  8136 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-06 19:16:46.299  1041  1635 I ActivityManager: Killing 7265:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-06 19:16:46.319  1041  1122 I art     : Explicit concurrent mark sweep GC freed 85198(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.750ms total 292.969ms
,09-06 19:16:46.344  8206  8206 D AndroidRuntime: Shutting down VM
,09-06 19:16:46.365  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-06 19:16:46.367  1041  1889 W libprocessgroup: failed to open /acct/uid_10005/pid_7265/cgroup.procs: No such file or directory
09-06 19:16:46.376  2168  2168 I ConfigService: onCreate
09-06 19:16:46.378  2168  2168 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-06 19:16:46.385  2168  2168 I ConfigService: onBind returning update interface
,09-06 19:16:46.393  1041  1096 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:46.397  1041  1096 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-06 19:16:46.419  1041  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8251 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-06 19:16:46.420  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-06 19:16:46.420  2016  2016 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 804899143
,09-06 19:16:46.420  2016  2016 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-06 19:16:46.420  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-06 19:16:46.423  2016  2016 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@17e00e48
09-06 19:16:46.423  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-06 19:16:46.424  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 19:16:46.424  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:16:46.426  2168  2168 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-06 19:16:46.426  2168  2168 I ConfigService: onBind returning config service
09-06 19:16:46.430  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-06 19:16:46.430  2016  2016 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-06 19:16:46.430  2016  2016 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 19:16:46.431  2016  2016 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473182091873, New one : 1473182206288
09-06 19:16:46.431  2016  2016 D [Concierge]WidgetView: Unregister all receivers
09-06 19:16:46.431  2016  2016 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 19:16:46.432  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-06 19:16:46.433  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:16:46.434  1801  1801 I ConfigFetchService: service connected
09-06 19:16:46.435  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-06 19:16:46.436  2168  2168 I ConfigService: onDestroy
09-06 19:16:46.437  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-06 19:16:46.438  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-06 19:16:46.439  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-06 19:16:46.440  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-06 19:16:46.441  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:16:46.443  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:16:46.450  1801  8266 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-06 19:16:46.493  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-06 19:16:46.498  5941  8273 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-06 19:16:46.505  2016  2016 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-06 19:16:46.505  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-06 19:16:46.507  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 19:16:46.509  1801  8276 I PeopleContactsSync: CP2 sync disabled
09-06 19:16:46.514  1801  4784 I Icing   : doRemovePackageData com.test.thalitest
09-06 19:16:46.520  7015  7015 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-06 19:16:46.529  1041  1889 I ActivityManager: Killing 7709:com.google.android.talk/u0a72 (adj 15): empty #17
09-06 19:16:46.529  2016  2016 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@216aafd0 time:141932
09-06 19:16:46.610  1041  1978 W libprocessgroup: failed to open /acct/uid_10072/pid_7709/cgroup.procs: No such file or directory
,09-06 19:16:46.619  2330  8280 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 19:16:46.641  2330  8280 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
09-06 19:16:46.643  2330  8280 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-06 19:16:46.643  2330  8280 E AndroidRuntime: Process: android.process.acore, PID: 2330
09-06 19:16:46.643  2330  8280 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:16:46.643  2330  8280 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:16:46.647  1041  1056 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8281 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-06 19:16:46.652  2016  2016 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:16:46.655  1041  8292 E DropBoxManagerService: 	... 5 more
,09-06 19:16:46.660  1801  8274 W GmsApplication: Using Auth Proxy for data requests.
09-06 19:16:46.661  2330  8280 I Process : Sending signal. PID: 2330 SIG: 9
,09-06 19:16:46.692  2168  2194 I art     : Explicit concurrent mark sweep GC freed 7537(442KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 724us total 28.895ms
09-06 19:16:46.695  2016  2872 I GBoardtInterface: onReloaded()
,09-06 19:16:46.697  2016  2016 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-06 19:16:46.707  8281  8281 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:16:46.708  8281  8281 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:16:46.710  8281  8281 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:16:46.711  8281  8281 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:16:46.717  1041  1909 I ActivityManager: Process android.process.acore (pid 2330) has died
09-06 19:16:46.717  1041  1909 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
09-06 19:16:46.718  1041  1909 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
09-06 19:16:46.720  3781  3797 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)

```
