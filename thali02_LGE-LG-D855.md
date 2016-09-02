#### Test 83444050ceb1988_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-02 19:06:39.413  6361  6361 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
--------- beginning of system
09-02 19:06:39.419  6361  6361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-02 19:06:39.448  4559  6495 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-02 19:06:39.491  1044  1904 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6498 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:06:39.531  1044  1059 V SIM_STK : Menu title from STK is T-Mobile
09-02 19:06:39.664  4559  6495 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 215 ms] updated apps [took 215 ms] 
09-02 19:06:39.738  6498  6498 D DocsApplication: Installing DEX configuration.
09-02 19:06:39.756  6498  6498 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-02 19:06:39.760  6498  6498 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1d5513a1 com.google.android.apps.docs}
09-02 19:06:39.777  6498  6498 D TAG     : onCreate()
09-02 19:06:39.798  6498  6498 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,09-02 19:06:40.431   333   429 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-02 19:06:40.433  3204  6522 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-02 19:06:40.534  6520  6520 D AndroidRuntime: 
09-02 19:06:40.534  6520  6520 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 19:06:40.537  6520  6520 D AndroidRuntime: CheckJNI is OFF
09-02 19:06:40.643  6520  6520 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-02 19:06:40.648  1044  1998 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 19:06:40.663  1801  4711 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-02 19:06:40.666  1927  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-02 19:06:40.670  1044  1998 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-02 19:06:40.671  1044  1998 D ActivityManager: setTaskToReturnTo : TaskRecord{1a665d7a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 19:06:40.671  1044  1998 D ActivityManager: setTaskToReturnTo : TaskRecord{1a665d7a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 19:06:40.673  1044  1998 D WindowStateEx: AppWindowTokenEx init.. 
09-02 19:06:40.673   343   367 E GBMv2   : DFP En is all cleared set to be enabled
09-02 19:06:40.714  1044  1998 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6536 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 19:06:40.717  6520  6520 D AndroidRuntime: Shutting down VM
09-02 19:06:40.765  1927  2822 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-02 19:06:40.765  1927  2822 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37a16ded co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 19:06:40.767  1927  2822 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-02 19:06:40.767  1927  2822 D SplitWindowPolicy: topRunningActivity=ActivityInfo{11883422 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 19:06:40.792  1801  4711 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-02 19:06:40.851  6536  6536 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-02 19:06:40.872  1801  4711 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-02 19:06:40.946  6536  6536 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 19:06:40.955  6536  6536 I LibraryLoader: Loading: webviewchromium
09-02 19:06:40.958  6536  6536 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5254-5257)
09-02 19:06:40.958  6536  6536 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:06:40.970  6536  6536 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4e6eb23}
,09-02 19:06:40.971  6536  6536 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:06:40.972  6536  6536 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 19:06:40.979  6536  6536 I BrowserStartupController: Initializing chromium process, renderers=0
09-02 19:06:40.980  6536  6536 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 19:06:40.989  6536  6536 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-02 19:06:40.989  6536  6536 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-02 19:06:40.990  6536  6536 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-02 19:06:40.991   320  2174 V AudioPolicyService: registerClient() client 0xb558a4a0, uid 10118
09-02 19:06:40.996  1044  1119 D BluetoothManagerService: Message: 20
09-02 19:06:40.996  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c4c7e34:true
09-02 19:06:40.999  6536  6536 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 19:06:40.999  6536  6536 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 19:06:40.999  6536  6536 I Adreno-EGL: Build Date: 12/12/14 금
09-02 19:06:40.999  6536  6536 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 19:06:40.999  6536  6536 I Adreno-EGL: Remote Branch: 
09-02 19:06:40.999  6536  6536 I Adreno-EGL: Local Patches: 
09-02 19:06:40.999  6536  6536 I Adreno-EGL: Reconstruct Branch: 
09-02 19:06:41.053  6498  6498 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:06:41.053  6498  6498 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:06:41.085  6536  6577 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
09-02 19:06:41.087  6536  6536 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,09-02 19:06:41.110  6536  6536 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:06:41.113  6536  6536 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-02 19:06:41.116  6536  6536 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-02 19:06:41.118  6536  6536 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-02 19:06:41.118  6536  6536 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-02 19:06:41.127  6536  6536 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-02 19:06:41.135  6536  6536 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 19:06:41.135  6536  6536 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:06:41.171  6536  6592 D OpenGLRenderer: Render dirty regions requested: true
,09-02 19:06:41.172  6536  6592 I OpenGLRenderer: Initialized EGL, version 1.4
09-02 19:06:41.180  6536  6592 D OpenGLRenderer: Enabling debug mode 0
09-02 19:06:41.181  6058  6058 I LockScreenSettings: New app installed broadcast received ..
09-02 19:06:41.183  6058  6058 I LockScreenSettings: Number of installed packages  1
09-02 19:06:41.186  6536  6536 D Atlas   : Validating map...
,09-02 19:06:41.189  1044  1963 D SplitWindow: check instance of lgWin Window{151e990b u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-02 19:06:41.193  6498  6498 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-02 19:06:41.220  1044  1904 V SIM_STK : Menu title from STK is T-Mobile
,09-02 19:06:41.224  6536  6589 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:06:41.224  6536  6589 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 19:06:41.264  1044  1998 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6606 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 19:06:41.291  2768  2768 I MusicWidget: mDelayedStopHandler : unbind
,09-02 19:06:41.292  2156  2156 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-02 19:06:41.294  2156  2156 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-02 19:06:41.295  2156  2156 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-02 19:06:41.297  2156  2156 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-02 19:06:41.297  2156  2156 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-02 19:06:41.297  2156  2156 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-02 19:06:41.298  2156  2156 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-02 19:06:41.298  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-02 19:06:41.299  1044  1963 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1190a749com.lge.music.MediaPlaybackService$5@3905a84e
09-02 19:06:41.299  2156  2156 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-02 19:06:41.299  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.300  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.300  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.301  2156  2156 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@533167f
09-02 19:06:41.301  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.302  2156  2156 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-02 19:06:41.302  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.302  2156  2156 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-02 19:06:41.302  2156  2156 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-02 19:06:41.302  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.303  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-02 19:06:41.303  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.304  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.304  2156  2156 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-02 19:06:41.305  2156  2156 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-02 19:06:41.306  2156  2156 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-02 19:06:41.306  2156  2156 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-02 19:06:41.306  2156  2156 V MediaPlayer[Native]: reset
09-02 19:06:41.311  2156  2156 V MediaPlayer[Native]: setListener
09-02 19:06:41.311  2156  2156 V MediaPlayer[Native]: disconnect
09-02 19:06:41.311  2156  2156 V MediaPlayer[Native]: destructor
09-02 19:06:41.311   320  2175 V AudioFlinger: releasing 18 from 2156 for -1
09-02 19:06:41.311   320  2175 V AudioFlinger:  decremented refcount to 0
09-02 19:06:41.311   320  2175 V AudioFlinger: purging stale effects
09-02 19:06:41.311  2156  2156 V MediaPlayer[Native]: disconnect
09-02 19:06:41.312  2156  2156 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-02 19:06:41.313  2156  2156 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-02 19:06:41.313  2156  2156 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-02 19:06:41.314  2156  2156 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-02 19:06:41.314  2156  2156 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-02 19:06:41.314  2156  2156 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-02 19:06:41.314  2156  2156 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 990158191
09-02 19:06:41.314  2156  2156 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 990158191
,09-02 19:06:41.316  1044  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +553ms (total +642ms)
09-02 19:06:41.317  6536  6536 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3905a84e time:105616
09-02 19:06:41.317  1044  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{346d292b u0 com.test.thalitest/.MainActivity t6} time:105616
09-02 19:06:41.318  2156  2156 I SmartShareClient: [SmartShareManagerClient] terminate service: 2156/MediaPlaybackService/562972893
09-02 19:06:41.321  2156  2156 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-02 19:06:41.321  2156  2156 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3bc90a7c
09-02 19:06:41.323  2156  2156 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-02 19:06:41.324  2156  2156 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-02 19:06:41.324  2156  2156 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-02 19:06:41.324  2156  2156 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-02 19:06:41.326  1044  1766 I ActivityManager: Killing 5400:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-02 19:06:41.326  2156  2156 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
,09-02 19:06:41.437  6536  6536 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 19:06:41.463  1044  1060 W libprocessgroup: failed to open /acct/uid_10005/pid_5400/cgroup.procs: No such file or directory
,09-02 19:06:41.473  6606  6606 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-02 19:06:41.473  6606  6606 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
09-02 19:06:41.498  6536  6536 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-02 19:06:41.498  6536  6536 I chromium: 
,09-02 19:06:41.531  1044  1962 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6629 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 19:06:41.532  1044  1962 I ActivityManager: Killing 5796:com.google.android.talk/u0a72 (adj 15): empty #17
09-02 19:06:41.533  6536  6589 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-02 19:06:41.533  6536  6589 I chromium: 
09-02 19:06:41.646  6536  6646 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,09-02 19:06:41.653  1044  1998 W libprocessgroup: failed to open /acct/uid_10072/pid_5796/cgroup.procs: No such file or directory
,09-02 19:06:41.663  6536  6646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 19:06:41.663  6536  6646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 19:06:41.663  6536  6646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 19:06:41.663  6536  6646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 19:06:41.663  6536  6646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-02 19:06:41.663  6536  6646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ada9bb2 added. We now have 1 listener(s)
09-02 19:06:41.669  1044  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:06:41.672  6536  6646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,09-02 19:06:41.674  6536  6646 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-02 19:06:41.676  6536  6646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:06:41.676  6536  6646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-02 19:06:41.686  6536  6646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33d4f4b9 added. We now have 1 listener(s)
09-02 19:06:41.687  6536  6646 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:06:41.691  1044  1528 D WifiService: New client listening to asynchronous messages
09-02 19:06:41.692   343   369 E GBMv2   : DFP En is all cleared set to be enabled
09-02 19:06:41.692   343   369 E GBMv2   : Set value is all cleared set the max
09-02 19:06:41.692   343   369 I GBMv2   : DFP Enabled. Ignore VFP set
09-02 19:06:41.696  6536  6646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:06:41.696  6536  6646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 19:06:41.696  6536  6646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 19:06:41.697  6536  6646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 19:06:41.697  6536  6646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-02 19:06:41.703  6536  6646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:41.703  1044  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:06:41.704  6536  6646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-02 19:06:41.714  6536  6646 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-02 19:06:41.714  6536  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:41.714  6536  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:41.714  6536  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:41.714  6536  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:41.714  6536  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:41.714  6536  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:41.714  6536  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:41.714  6536  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:41.715  6536  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 19:06:41.715  6536  6646 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:06:41.718  6536  6646 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 19:06:41.718  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:41.721  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:41.741  6629  6629 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-02 19:06:41.765  6629  6629 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-02 19:06:41.767  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,09-02 19:06:41.789  1044  1872 I ActivityManager: Killing 5594:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-02 19:06:41.793  6536  6536 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-02 19:06:41.803  5572  5572 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-02 19:06:41.803  5572  5572 W System.err: android.os.DeadObjectException
,09-02 19:06:41.803  5572  5572 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 19:06:41.803  5572  5572 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 19:06:41.803  5572  5572 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-02 19:06:41.803  5572  5572 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-02 19:06:41.803  5572  5572 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 19:06:41.803  5572  5572 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 19:06:41.803  5572  5572 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 19:06:41.803  5572  5572 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 19:06:41.803  5572  5572 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:06:41.803  5572  5572 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:06:41.803  5572  5572 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:41.803  5572  5572 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:06:41.803  5572  5572 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:06:41.803  5572  5572 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:06:41.804  5572  5572 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-02 19:06:41.804  5572  5572 W System.err: android.os.DeadObjectException
09-02 19:06:41.804  5572  5572 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 19:06:41.804  5572  5572 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 19:06:41.804  5572  5572 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-02 19:06:41.804  5572  5572 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-02 19:06:41.804  5572  5572 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 19:06:41.804  5572  5572 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 19:06:41.804  5572  5572 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 19:06:41.804  5572  5572 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 19:06:41.804  5572  5572 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:06:41.804  5572  5572 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:06:41.804  5572  5572 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:41.804  5572  5572 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:06:41.804  5572  5572 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:06:41.804  5572  5572 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:06:41.804  5572  5572 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-02 19:06:41.805  5572  5572 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-02 19:06:41.964  1044  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_5594/cgroup.procs: No such file or directory
09-02 19:06:41.965  1044  1942 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-02 19:06:41.977  5572  5572 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-02 19:06:41.981  5572  5572 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 19:06:42.026  1044  1904 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6652 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 19:06:42.026  5572  5572 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-02 19:06:42.113  6652  6652 D UEI.SmartControl: Quickset Services start...
,09-02 19:06:42.119  6652  6652 I UEI.SmartControl: Manufacture = LGE
09-02 19:06:42.120  6652  6652 D UEI.SmartControl: Id = LGNevo
09-02 19:06:42.122  6652  6652 D UEI.SmartControl: File observer start...
09-02 19:06:42.123  6652  6652 E UEI.SmartControl: IR Port is disabled: false
09-02 19:06:42.123  6652  6652 D UEI.SmartControl: Starting file observer...
09-02 19:06:42.124  6652  6652 D UEI.SmartControl: Extracting JNI libs...
09-02 19:06:42.124  6652  6652 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-02 19:06:42.212  6652  6652 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-02 19:06:42.212  6652  6652 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-02 19:06:42.212  6652  6652 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-02 19:06:42.265  6652  6652 I UEI.SmartControl: --- Selecting new region: 6
09-02 19:06:42.268  6652  6652 I UEI.SmartControl: Model = LG-D855
09-02 19:06:42.270  6652  6652 D UEI.SmartControl: QS Service created
,09-02 19:06:42.288  6652  6652 I UEI.SmartControl: Service initServices...
,09-02 19:06:42.294  6652  6652 D UEI.SmartControl: QS start get config
09-02 19:06:42.341  6652  6652 D UEI.SmartControl: Loading JNI Libs...
,09-02 19:06:42.750  6652  6652 I UEI.SmartControl: Supports setup maps: true
,09-02 19:06:42.757  6652  6652 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 19:06:42.757  6652  6652 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 19:06:42.757  6652  6652 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 19:06:42.757  6652  6652 I UEI.SmartControl: ### init IR Blaster...
09-02 19:06:42.765  6652  6652 D serial_port: Configuring serial port
,09-02 19:06:42.773  6652  6652 E UEI.SmartControl: UEIBLaster setting for 616
09-02 19:06:42.773  6652  6652 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 19:06:42.773  6652  6652 I UEI.SmartControl: configuring settings for MAXQ616
09-02 19:06:42.773  6652  6652 I UEI.SmartControl: Get version...
09-02 19:06:42.790  6652  6673 D UEI.SmartControl: serial port data available: 21
,09-02 19:06:42.816  6652  6652 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 19:06:42.816  6652  6652 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 19:06:42.816  6652  6652 I UEI.SmartControl: QS saving settings...
,09-02 19:06:42.818  6652  6652 D UEI.SmartControl: IR Blaster version: 25672567
09-02 19:06:42.840  6652  6673 D UEI.SmartControl: serial port data available: 4
,09-02 19:06:42.859  6536  6649 W jxcore-log: Initializing JXcore engine
09-02 19:06:42.859  6536  6649 W jxcore-log: JXcore engine is ready
,09-02 19:06:42.875  6652  6652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-02 19:06:42.877  6652  6676 I UEI.SmartControl: Device manager: loading config....
09-02 19:06:42.877  6652  6676 D UEI.SmartControl: ----------- loading internal config...
09-02 19:06:42.881  6652  6652 E UEI.SmartControl: Services init done
09-02 19:06:42.882  6652  6652 D UEI.SmartControl: QS Service init finished
09-02 19:06:42.882  6652  6652 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 19:06:42.882  6652  6652 D UEI.SmartControl: QS Service version code: 201091
09-02 19:06:42.883  6652  6652 D UEI.SmartControl: Service requested: Control
09-02 19:06:42.889  6652  6676 E UEI.SmartControl: Loading SETTINGS...
,09-02 19:06:42.893  6652  6652 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 19:06:42.896  6652  6676 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-02 19:06:42.902  1044  1942 I ActivityManager: Killing 5572:com.lge.qremote/u0a112 (adj 15): empty #17
,09-02 19:06:42.907  6649  6649 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8571]" dev="sockfs" ino=8571 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-02 19:06:42.907  6649  6649 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-02 19:06:42.907  6649  6649 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9739]" dev="sockfs" ino=9739 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-02 19:06:42.907  6649  6649 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-02 19:06:42.907  6649  6649 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30673]" dev="sockfs" ino=30673 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-02 19:06:42.917  6652  6675 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-02 19:06:42.917  6652  6675 D UEI.SmartControl: -----service ready thread exits
09-02 19:06:42.921  6536  6649 W jxcore-log: Starting JXcore engine
09-02 19:06:42.981  1044  1766 W libprocessgroup: failed to open /acct/uid_10112/pid_5572/cgroup.procs: No such file or directory
09-02 19:06:42.981  6652  6652 D UEI.SmartControl: Internal service binding...
,09-02 19:06:43.005  6536  6649 W jxcore-log: Platform android
09-02 19:06:43.005  6536  6649 W jxcore-log: 
09-02 19:06:43.005  6536  6649 W jxcore-log: Process ARCH arm
09-02 19:06:43.005  6536  6649 W jxcore-log: 
,09-02 19:06:43.332  6536  6649 I jxcore-log: JXcore Cordova bridge is ready!
09-02 19:06:43.332  6536  6649 I jxcore-log: 
09-02 19:06:43.332  6536  6649 W jxcore-log: JXcore engine is started
,09-02 19:06:43.344  6536  6646 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 19:06:43.349  6536  6536 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-02 19:06:45.117  6498  6498 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-02 19:06:45.124  1044  1872 I ActivityManager: Killing 6192:com.android.calendar/u0a13 (adj 15): empty #17
09-02 19:06:45.193  1044  1060 W libprocessgroup: failed to open /acct/uid_10013/pid_6192/cgroup.procs: No such file or directory
,09-02 19:06:46.116  6498  6583 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-02 19:06:47.875  6652  6677 D UEI.SmartControl: Internal timer expired: 1
09-02 19:06:47.875  6652  6677 D UEI.SmartControl: unbind internal service
,09-02 19:06:47.886  6652  6652 D UEI.SmartControl: Service.onUnbind: IControl
09-02 19:06:47.891  6652  6652 D UEI.SmartControl: Service.onDestroy
,09-02 19:06:47.892  6652  6652 D UEI.SmartControl: Lock is in USE false
09-02 19:06:47.892  6652  6652 D UEI.SmartControl: unbind internal service
09-02 19:06:47.892  6652  6652 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@533167f
09-02 19:06:47.893  6652  6652 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-02 19:06:47.893  6652  6652 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-02 19:06:47.894  6652  6652 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-02 19:06:47.894  6652  6652 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-02 19:06:47.894  6652  6652 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-02 19:06:47.894  6652  6652 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
,09-02 19:06:47.898  6652  6652 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-02 19:06:47.898  6652  6652 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-02 19:06:47.898  6652  6652 W System.err: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:47.898  6652  6652 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:06:47.898  6652  6652 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:06:47.899  6652  6652 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:47.899  6652  6652 W System.err: 	,at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:06:47.899  6652  6652 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:06:47.899  6652  6652 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:06:47.899  6652  6652 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@533167f
09-02 19:06:47.904  6652  6652 D serial_port: close(fd = 25)
09-02 19:06:47.908  6652  6652 I UEI.SmartControl: Serial port is closed.
09-02 19:06:47.908  6652  6652 I UEI.SmartControl: Serial port is closed.
09-02 19:06:47.908  6652  6652 D UEI.SmartControl: Blaster closed
09-02 19:06:47.908  6652  6652 D UEI.SmartControl: Shut down QS...
,09-02 19:06:47.920  6652  6652 D UEI.SmartControl: Stopping QS lib
09-02 19:06:47.920  6652  6652 D UEI.SmartControl: QS lib stop result = true
09-02 19:06:47.921  6652  6652 D UEI.SmartControl: Stopped QS lib
09-02 19:06:47.921  6652  6652 D UEI.SmartControl: Stopped file observer...
09-02 19:06:47.921  6652  6652 D UEI.SmartControl: QS shutdown complete
09-02 19:06:48.802  1801  6415 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-02 19:06:48.807   316  6709 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-02 19:06:48.807   316  6709 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-02 19:06:48.807   316  6709 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-02 19:06:49.056  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
,09-02 19:06:49.062  1801  1801 I ConfigFetchService: stopping self
09-02 19:06:49.067  2176  2176 I ConfigService: onDestroy
,09-02 19:06:51.338  2156  2156 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19988
,09-02 19:06:53.446  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 19:06:53.446  6536  6649 I jxcore-log: 
,09-02 19:06:53.449  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 19:06:53.449  6536  6649 I jxcore-log: 
09-02 19:06:53.453  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:53.453  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:53.453  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:53.453  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:53.453  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:53.453  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:53.453  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:53.453  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:53.456  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:53.458  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 19:06:53.458  6536  6649 I jxcore-log: 
09-02 19:06:53.460  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 19:06:53.460  6536  6649 I jxcore-log: 
,09-02 19:06:53.900  1044  1115 I ActivityManager: Waited long enough for: ServiceRecord{38b1dd09 u0 com.google.android.gms/.wearable.service.WearableService}
,09-02 19:06:53.964  6536  6649 D executeNativeTests: Running unit tests
,09-02 19:06:54.045  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:06:54.045  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 added. We now have 2 listener(s)
,09-02 19:06:54.046  1044  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 19:06:54.048  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:06:54.048  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:06:54.048  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:06:54.048  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:06:54.048  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 added. We now have 2 listener(s)
09-02 19:06:54.048  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:06:54.048  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:06:54.051  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:06:54.053  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:54.053  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.053  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.053  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.053  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:54.053  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:54.053  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:54.053  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:54.054  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:54.055  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:06:54.056  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.056  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.064  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 19:06:54.072  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:06:54.072  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:06:54.078  6536  6649 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-02 19:06:54.080  6536  6649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 19:06:54.080  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 19:06:54.080  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:06:54.081  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:06:54.082  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.082  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.082  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.083  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.083  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.083  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:54.083  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:06:54.083  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 removed from the list
09-02 19:06:54.083  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.083  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 removed from the list
09-02 19:06:54.083  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.083  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.084  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.084  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.085  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.085  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.085  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.085  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.086  6536  6649 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-02 19:06:54.086  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.086  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.086  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.086  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.087  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.087  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.087  6536  6649 E org.thaliproject.p2p.btconnectorlib.Co,nnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.087  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.087  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.087  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.087  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.087  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.087  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.087  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.088  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.088  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.088  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:54.088  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-02 19:06:54.092  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 19:06:54.093  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.093  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.093  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.093  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:06:54.093  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.093  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.093  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.093  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.093  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list,
09-02 19:06:54.093  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.093  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.093  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-02 19:06:54.093  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.093  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:54.094  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.095  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.095  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.095  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.095  6536  6649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 19:06:54.097  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:54.098  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:54.098  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.098  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.098  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.098  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:54.098  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:54.098  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:54.098  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:54.099  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:54.099  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:06:54.100  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.101  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.101  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:06:54.102  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:06:54.102  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:06:54.102  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:54.102  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:06:54.104  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 19:06:54.104  1044  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:06:54.108  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:06:54.111  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 19:06:54.113  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 19:06:54.113  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:06:54.113  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:54.114  6536  6649 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 19:06:54.114  6536  6649 I io.jxcore.node.ConnectionHelper: start: OK
09-02 19:06:54.116  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.117  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.117  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.117  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.117  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.117  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:54.117  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.117  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.117  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.117  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.117  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.117  6536  6649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 19:06:54.119  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:54.121  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:54.121  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.121  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.121  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.121  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:54.121  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:54.121  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:54.121  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:54.121  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:54.121  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:06:54.123  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.124  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.124  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:06:54.124  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:06:54.124  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:06:54.124  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:54.124  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:06:54.127  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:06:54.127  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:54.128  6536  6649 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 19:06:54.128  6536  6649 I io.jxcore.node.ConnectionHelper: start: OK
09-02 19:06:54.129  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.129  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.129  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.129  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.129  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.129  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:54.129  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.129  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.129  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.129  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.129  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.130  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.130  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.130  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.130  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.131  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.132  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.132  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06,:54.132  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.132  6536  6649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 19:06:54.136  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:54.138  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:54.138  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.138  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.138  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.138  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:54.138  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:54.138  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:54.138  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:54.139  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:54.139  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:06:54.139  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:06:54.139  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:06:54.139  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:06:54.139  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:54.139  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:06:54.141  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.142  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.147  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:06:54.149  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:54.151  6536  6649 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 19:06:54.151  6536  6649 I io.jxcore.node.ConnectionHelper: start: OK
09-02 19:06:54.151  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.151  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.151  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.152  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.152  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.152  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.153  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.153  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.153  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:54.153  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.153  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.153  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.153  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.153  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.153  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.154  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.154  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.154  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.155  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.155  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.155  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.155  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.156  6536  6649 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 19:06:54.156  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.156  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.156  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.157  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.157  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.157  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.157  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.157  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.157  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.157  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.157  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.157  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.157  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.157  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.158  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.158  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:06:54.161  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.161  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.161  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.161  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.162  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 19:06:54.162  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.162  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.162  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.162  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.162  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.162  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.162  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.162  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.162  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.163  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.163  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.163  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.163  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.163  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.163  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.163  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.164  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.164  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.164  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.164  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.164  6536  6649 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 19:06:54.164  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.164  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.164  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.164  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.164  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.165  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.165  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.165  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.165  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.165  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.165  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.165  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.165  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.165  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.165  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.165  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.166  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.166  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.166  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.166  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.166  6536  6649 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 19:06:54.166  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.166  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.166  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.166  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.166  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.166  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.166  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.166  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.166  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.166  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.166  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.167  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.167  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.167  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.167  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.167  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.167  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.167  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.167  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.167  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.168  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 19:06:54.168  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:06:54.168  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:06:54.168  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:06:54.168  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 19:06:54.168  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:06:54.168  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.168  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.168  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.168  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.168  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.168  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.168  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.168  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.168  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.168  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.168  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.169  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.169  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.169  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.169  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.169  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.169  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.169  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.169  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.169  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.172  6536  6649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:54.172  6536  6649 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 19:06:54.172  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 19:06:54.175  6536  6649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:54.176  6536  6649 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 19:06:54.176  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 19:06:54.176  6536  6649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 19:06:54.177  6536  6649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:06:54.177  6536  6649 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 19:06:54.177  6536  6649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:54.177  6536  6649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:06:54.177  6536  6649 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 19:06:54.177  6536  6649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:54.177  6536  6649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:06:54.177  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 19:06:54.178  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 19:06:54.179  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 19:06:54.179  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 19:06:54.180  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 19:06:54.180  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 19:06:54.180  6536  6649 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 19:06:54.180  6536  6649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:54.180  6536  6649 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 19:06:54.180  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.180  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.180  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.181  6536  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
09-02 19:06:54.183  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.183  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.183  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.185  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 19:06:54.185  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.185  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.186  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.186  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.186  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.186  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.186  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.186  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.188  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.188  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.188  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.188  6536  6715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
09-02 19:06:54.188  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.188  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.188  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.188  6536  6715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
09-02 19:06:54.189  6536  6715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
09-02 19:06:54.189  6536  6649 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 19:06:54.189  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.189  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.189  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.189  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.189  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.189  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.189  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.190  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.190  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.190  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.190  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.190  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.190  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.190  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.192  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.192  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.192  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.192  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.192  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.192  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.193  6536  6649 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 19:06:54.193  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.193  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.193  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.193  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.193  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.193  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.194  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.194  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.194  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.194  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.194  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.194  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.194  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.194  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.195  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.195  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.195  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.195  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.195  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.195  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.196  6536  6649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 19:06:54.196  6536  6649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 19:06:54.196  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:06:54.196  6536  6649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 19:06:54.196  6536  6649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 19:06:54.196  6536  6649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 19:06:54.196  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 19:06:54.196  6536  6649 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 19:06:54.196  6536  6649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 19:06:54.196  6536  6649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 19:06:54.196  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 19:06:54.196  6536  6649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 19:06:54.196  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.197  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.197  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.197  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.197  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.197  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.197  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.197  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.197  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.197  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.197  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.197  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.197  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.197  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.198  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.198  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.200  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.200  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.200  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.200  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.201  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.201  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.201  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.201  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.201  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.201  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.201  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.201  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.201  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.201  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.201  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list,
09-02 19:06:54.201  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.201  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.201  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.201  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.201  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.201  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.201  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.202  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.202  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.202  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.202  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.202  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.202  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.202  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.202  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.202  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.202  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.202  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.203  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.203  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.203  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.204  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.204  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.204  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.205  6536  6649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 19:06:54.205  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:54.205  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 19:06:54.206  6536  6649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 19:06:54.206  6536  6649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 19:06:54.207  6536  6536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 19:06:54.207  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 19:06:54.207  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:06:54.211  1044  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:06:54.212  6536  6717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:06:54.212  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.213  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 19:06:54.213  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 19:06:54.213  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 19:06:54.213  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.213  6536  6649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 19:06:54.213  6536  6536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 19:06:54.213  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.214  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.214  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:06:54.214  6536  6649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:06:54.214  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:06:54.215  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:06:54.222  3828  3937 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-02 19:06:54.222  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:06:54.222  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:54.222  6536  6649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:06:54.223  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.223  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.223  6536  6717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 19:06:54.223  6536  6717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 19:06:54.224  6536  6717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 19:06:54.225  6536  6649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:06:54.225  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.225  6536  6536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:06:54.226  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.226  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.226  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.226  6536  6536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:06:54.226  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.226  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.226  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.226  6536  6536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 19:06:54.226  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.226  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.226  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.226  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.226  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.226  6536  6536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:06:54.226  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.226  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.226  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.230  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.230  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.230  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.230  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.231  6536  6649 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 19:06:54.231  6536  6649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 19:06:54.231  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:06:54.232  6536  6649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:06:54.232  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.232  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.232  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.232  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.232  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.232  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.232  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.232  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.232  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.232  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.232  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.232  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.232  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.232  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.233  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.233  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.233  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.233  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.234  1044  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:06:54.235  1044  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:06:54.237  1044  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:06:54.238  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.238  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:54.238  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.238  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.238  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.238  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.238  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.238  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:54.238  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.238  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.238  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:54.238  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.238  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:54.238  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.239  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.239  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.239  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 19:06:54.239  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.240  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:54.240  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:06:54.240  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:54.240  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:54.240  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:54.240  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.240  6536  6649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e42202 not in the list
09-02 19:06:54.240  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:54.240  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.240  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:54.240  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:54.240  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:54.241  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:54.241  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:54.242  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:54.242  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:54.242  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:54.242  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0b4713 not in the list
09-02 19:06:54.243  6536  6649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 19:06:54.243  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-02 19:06:54.243  6536  6649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 19:06:54.243  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:06:54.243  6536  6649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-02 19:06:54.243  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-02 19:06:54.248  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-02 19:06:54.248  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 19:06:54.249  6536  6649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 19:06:54.250  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 19:06:54.250  6536  6649 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-02 19:06:54.250  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 19:06:54.261  6536  6649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 19:06:54.261  6536  6649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-02 19:06:54.263  6536  6649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-02 19:06:54.263  6536  6649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 19:06:54.264  6536  6649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 19:06:54.264  6536  6649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 19:06:54.264  6536  6649 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 19:06:54.264  6536  6649 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 19:06:54.266  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:06:54.266  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17a56668 added. We now have 2 listener(s)
09-02 19:06:54.266  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:06:54.267  6536  6649 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 19:06:54.268  1044  1942 D WifiServiceImplEx: setWifiEnabled: true pid=6536, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 19:06:54.268  1044  1942 D WifiService: setWifiEnabled: true pid=6536, uid=10118
09-02 19:06:54.269  1044  1942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:06:54.270  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:06:54.270  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13107a81 added. We now have 3 listener(s)
09-02 19:06:54.270  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:06:54.273  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:06:54.273  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@241da726 added. We now have 4 listener(s)
,09-02 19:06:54.273  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:06:54.275  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:06:54.275  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16f1ef67 added. We now have 5 listener(s)
09-02 19:06:54.275  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:06:54.276  1044  1963 D WifiServiceImplEx: setWifiEnabled: false pid=6536, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 19:06:54.276  1044  1963 D WifiService: setWifiEnabled: false pid=6536, uid=10118
09-02 19:06:54.276  1044  1963 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:06:54.299  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 19:06:54.299  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 19:06:54.299  1044  1044 D Ulp_jni : JNI:system_update. Event-4
09-02 19:06:54.301  1044  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 19:06:54.301  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 19:06:54.301  1044  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 19:06:54.301  6536  6714 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-02 19:06:54.302  1044  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-02 19:06:54.302  6536  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
09-02 19:06:54.302  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 19:06:54.302  1044  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 19:06:54.302  1044  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:06:54.302  1044  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 19:06:54.302  1044  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:06:54.303  1044  1871 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@32da72db mBinding = false
09-02 19:06:54.303  1044  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 19:06:54.303  1044  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 19:06:54.320  1044  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 19:06:54.321  1044  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.321  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.321  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 19:06:54.321  2650  2650 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 19:06:54.322  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 19:06:54.322  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 1
,09-02 19:06:54.322  1044  1523 D WifiNative-wlan0: SET ps 1: returned true
09-02 19:06:54.322  1044  2828 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.322   316   916 D CommandListener: Clearing all IP addresses on wlan0
09-02 19:06:54.334  1044  1119 D BluetoothManagerService: Message: 2
09-02 19:06:54.334  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 19:06:54.334  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 19:06:54.335  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,09-02 19:06:54.336  1044  1119 D BluetoothManagerService: Sending off request.
09-02 19:06:54.337  3828  3847 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-02 19:06:54.337  3828  3906 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 19:06:54.337  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:54.337  3828  3906 D BluetoothAdapterProperties: Setting state to 13
09-02 19:06:54.337  3828  3906 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 19:06:54.339  3828  3906 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 19:06:54.339  3828  3906 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 19:06:54.340  1044  1119 D BluetoothManagerService: Message: 60
09-02 19:06:54.340  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 19:06:54.340  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-02 19:06:54.341  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:54.344  3828  3828 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:54.344  3828  3828 D BluetoothMapService: STATE_TURNING_OFF
09-02 19:06:54.344  3828  3828 V BluetoothMapService: Handler(): got msg=4
09-02 19:06:54.344  3828  3828 D BluetoothMapService: MAP Service closeService in
09-02 19:06:54.344  3828  3828 D BluetoothMapMasInstance: MAP Service shutdown
09-02 19:06:54.345  3828  4141 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 19:06:54.345  3828  4141 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:06:54.345  3828  4141 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 19:06:54.345  3828  4141 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 19:06:54.345  3828  4141 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 19:06:54.345  3828  4141 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 19:06:54.345  3828  4141 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 19:06:54.345  3828  4141 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-02 19:06:54.345  3828  3828 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 19:06:54.345  3828  3828 V BluetoothMapService: MAP Service closeService out
09-02 19:06:54.345  3828  3828 V BtOppService: Receiver DISABLED_ACTION 
09-02 19:06:54.345  3828  3828 I BtOppRfcommListener: stopping Accept Thread
09-02 19:06:54.345  3828  3828 V BtOppRfcommListener: close mBtServerSocket
09-02 19:06:54.346  3828  3828 V BtOppRfcommListener: waiting for thread to terminate
09-02 19:06:54.346  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 19:06:54.347  3828  4165 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:06:54.347  3828  4165 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 19:06:54.348  3828  3828 V BtOppRfcommListener: done waiting for thread to terminate
09-02 19:06:54.349  1044  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 19:06:54.351  1044  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-02 19:06:54.360  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:54.360  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:54.360  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.360  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.360  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.360  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.360  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.360  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:54.360  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:54.361  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:54.361  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:06:54.361  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:06:54.374  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.374  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:54.374  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.374  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.374  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.374  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.374  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.374  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:54.374  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:54.375  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.377  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.377  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:54.377  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.377  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.377  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.377  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.377  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.377  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:54.377  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:54.378  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.378  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:06:54.379  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:54.385  1044  2017 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-02 19:06:54.386  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.386  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.386  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-02 19:06:54.386  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.386  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-02 19:06:54.395  1044  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 19:06:54.395  1044  1529 D DSQN    : disableDataServiceNotify
09-02 19:06:54.395  1044  1529 D DSQN    : stop dsqn bin
09-02 19:06:54.395   316  6734 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-02 19:06:54.396  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 19:06:54.397  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-02 19:06:54.400  1044  1115 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6731 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 19:06:54.401  3828  3828 V BtOppService: onDestroy
09-02 19:06:54.403  1044  1044 D WifiHS20: hidePasspointNotification off =false
09-02 19:06:54.403  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:54.403  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:54.403  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 19:06:54.403  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 19:06:54.411  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:06:54.413  3828  3828 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-02 19:06:54.413  1044  1044 D WifiHS20: hidePasspointNotification off =false
09-02 19:06:54.415  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:54.415  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:54.416  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:54.417  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:54.417  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:54.417  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 19:06:54.418  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 19:06:54.418  1044  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 1 0 cz
09-02 19:06:54.418  1044  1044 D RttService: SCAN_AVAILABLE : 1
09-02 19:06:54.418  1044  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.418  1044  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.418  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.418  1044  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.419  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.419  1044  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 19:06:54.419  1044  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.419  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.419  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.420  1044  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.420  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.421  1044  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.421  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.421  1044  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1da71879
09-02 19:06:54.421  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:54.429  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:54.429  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 19:06:54.430  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:54.445  1044  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-02 19:06:54.445  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:54.445  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:06:54.446  1044  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:06:54.446  1044  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 19:06:54.446  1044  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 19:06:54.446  1044  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 19:06:54.446  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-02 19:06:54.447  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.447  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.447  1044  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 19:06:54.448  1588  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 19:06:54.455  1044  1904 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6749 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 19:06:54.457  1044  1521 D LGWifiP2pService: P2pDisablingState
09-02 19:06:54.457  1044  1521 D LGWifiP2pService: P2pDisablingState{ when=-36ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.457  1044  1521 D LGWifiP2pService: p2p socket connection lost
09-02 19:06:54.457  1044  1521 D LGWifiP2pService: P2pDisabledState
09-02 19:06:54.458  1044  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 19:06:54.458  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 19:06:54.458  2650  2650 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 19:06:54.458  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 19:06:54.458  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 19:06:54.458  1044  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.459  1044  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.459  1044  1523 D WifiNative-wlan0: SET ps 1: returned true
09-02 19:06:54.459   316   916 D CommandListener: Clearing all IP addresses on wlan0
09-02 19:06:54.459  1044  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:06:54.459  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 19:06:54.460  1044  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:06:54.460  1044  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:54.460  1044  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:54.460  1044  1529 D NetworkManagementService: Removing idletimer
09-02 19:06:54.460  1044  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 19:06:54.461  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:54.461  1044  1523 D WifiNative-p2p0: TERMINATE: returned true
09-02 19:06:54.461  1044  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 19:06:54.461  1044  1523 E WifiStateMachine: useWiFiOffloading() : false
09-02 19:06:54.461  1044  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-02 19:06:54.462  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 19:06:54.462  1044  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:54.469  1044  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 19:06:54.469  1044  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 19:06:54.470  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 19:06:54.470  1927  1927 D WfdsService: WifiP2pState is changed : false
09-02 19:06:54.471  1927  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 19:06:54.471  1927  2296 D WfdsService: Set the WFDS Monitor: false
09-02 19:06:54.472  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
09-02 19:06:54.472  1927  2296 D WfdsService: STATE : WfdsDisabledState - enter
09-02 19:06:54.472  1927  2824 D CtrlSupplicant: Received on exit socket, terminate
09-02 19:06:54.472  1927  2824 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 19:06:54.472  1927  2299 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,09-02 19:06:54.472  1927  2824 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-02 19:06:54.472  1927  2824 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 19:06:54.473  1927  2296 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 19:06:54.474  1044  1523 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 1 0 cz
09-02 19:06:54.474  1044  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:54.474  1044  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:06:54.475  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-02 19:06:54.480  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.480  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:54.480  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.480  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.480  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:06:54.480  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.480  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.480  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:54.480  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:54.481  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.481  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:06:54.483  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.483  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:54.483  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.483  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.483  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:06:54.483  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.483  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.483  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:54.483  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:06:54.485  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.485  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:06:54.488  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 19:06:54.489  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:54.489  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:54.504  1044  1962 I art     : Explicit concurrent mark sweep GC freed 35317(1697KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.337ms total 162.860ms
,09-02 19:06:54.505  1044  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 19:06:54.506  3828  3909 D BluetoothAdapterProperties: Scan Mode:20
09-02 19:06:54.506  6731  6731 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:06:54.506  3828  3906 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 19:06:54.506  1044  1364 V AlarmManager: RTC_WAKEUP set : Alarm{20c08d24 type 0 when 1472836014430 com.android.vending} when 1472836014430
09-02 19:06:54.506  6731  6731 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-02 19:06:54.506  3828  4168 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:06:54.506  3828  4143 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:06:54.506  3828  3906 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 19:06:54.506  3828  4187 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:06:54.506  6731  6731 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 19:06:54.507  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 19:06:54.507  6731  6731 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-02 19:06:54.507  3828  4020 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 19:06:54.507  6731  6731 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 19:06:54.508  6731  6731 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 19:06:54.508  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 19:06:54.508  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-02 19:06:54.509  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:54.509  3828  4020 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 19:06:54.509  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:54.509  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 19:06:54.509  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:54.512  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 19:06:54.513  1044  1044, D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 19:06:54.513  1044  1044 D WifiHS20: hidePasspointNotification off =false
09-02 19:06:54.513  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:54.513  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:54.513  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 19:06:54.513  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 19:06:54.513  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:06:54.513  1044  1044 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 19:06:54.513  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 19:06:54.513  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 19:06:54.513  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:54.513  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 19:06:54.513  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 19:06:54.513  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 19:06:54.513  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-02 19:06:54.518  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.518  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:54.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:06:54.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:54.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:54.519  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.519  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:54.519  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.519  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:54.519  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:06:54.519  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.519  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.519  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:54.519  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:54.526  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-02 19:06:54.536  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 19:06:54.536  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:06:54.538  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:54.540  1044  2828 D DhcpStateMachine: StoppedState
09-02 19:06:54.540  1044  2828 D DhcpStateMachine: StoppedState{ when=-81ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:54.544  1044  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-02 19:06:54.544  1044  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-02 19:06:54.563  1044  1942 V SIM_STK : Menu title from STK is T-Mobile
,09-02 19:06:54.581  2650  2650 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 19:06:54.581  2650  2650 I wpa_supplicant: monitor socket send errors count : 1
09-02 19:06:54.581  2650  2650 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
,09-02 19:06:54.582  1044  2813 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 19:06:54.582  1044  2813 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 19:06:54.607  6731  6731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 19:06:54.610  3828  3828 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 19:06:54.610  3828  3828 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:54.610  3828  3828 V BluetoothPbapReceiver: ***********state = 13
09-02 19:06:54.611  3828  3828 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-02 19:06:54.613  3828  3828 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:54.613  3828  3828 V BluetoothPbapService: state: 13
09-02 19:06:54.613  3828  3828 V BluetoothPbapService: Pbap Service closeService in
09-02 19:06:54.613  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:06:54.613  3828  3828 V BluetoothPbapService: successfully stopped pbap service
09-02 19:06:54.613  3828  3828 V BluetoothPbapService: Pbap Service closeService out
09-02 19:06:54.614  3828  3828 V BluetoothPbapService: Pbap Service onDestroy
09-02 19:06:54.614  3828  3828 V BluetoothPbapService: Pbap Service closeService in
09-02 19:06:54.614  3828  3828 V BluetoothPbapService: Pbap Service closeService out
09-02 19:06:54.614  3828  3828 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-02 19:06:54.625  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:06:54.645  2650  2650 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 19:06:54.646  2650  2650 W wpa_supplicant: USIM:  scard_deinit function
09-02 19:06:54.646  1044  2813 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-02 19:06:54.647  1044  2813 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 19:06:54.647  1044  2813 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 19:06:54.647  1044  2813 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-02 19:06:54.647  1044  2813 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:06:54.647  1044  2813 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 19:06:54.649  1044  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118935
09-02 19:06:54.649  1044  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118935
09-02 19:06:54.650  1044  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=118936  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 19:06:54.652  1044  1119 D Tethering: InitialState.processMessage what=4
09-02 19:06:54.654  1044  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=118939  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 19:06:54.659  1044  1963 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6771 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-02 19:06:54.661  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:06:54.662  1044  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:54.662  1044  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:54.667  6731  6731 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:06:54.668  6731  6731 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:06:54.678  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:06:54.685  1044  1119 D BluetoothManagerService: Message: 20
,09-02 19:06:54.685  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21626253:true
09-02 19:06:54.686  6019  6019 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
09-02 19:06:54.693  1044  1998 I ActivityManager: Killing 6155:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-02 19:06:54.725  2650  2650 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 19:06:54.725  1044  2813 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 19:06:54.725  1044  2813 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 19:06:54.725  1044  2813 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 19:06:54.726  1044  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 19 0
,09-02 19:06:54.728  6536  6536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-02 19:06:54.742  1044  1942 W libprocessgroup: failed to open /acct/uid_10014/pid_6155/cgroup.procs: No such file or directory
,09-02 19:06:54.747  1044  1119 D BluetoothManagerService: Message: 30
09-02 19:06:54.751  1044  1119 D BluetoothManagerService: Message: 30
09-02 19:06:54.754  6731  6731 D LocalBluetoothProfileManager: Adding local MAP profile
,09-02 19:06:54.755  6731  6731 D BluetoothMap: Create BluetoothMap proxy object
09-02 19:06:54.755  1044  1119 D BluetoothManagerService: Message: 30
09-02 19:06:54.759  1044  1119 D BluetoothManagerService: Message: 30
09-02 19:06:54.760  6771  6771 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-02 19:06:54.761  6771  6771 W LG Account v2.2: No ProfileInfo entries
09-02 19:06:54.761  6771  6771 I LG Account v2.2: isEnabled: false
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Country: EU
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Operator: OPEN
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Ranking support: false
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Comfort support: false
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Accessory: true
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Health device: true
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Extra Pedometer: false
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Blood glucose device: false
09-02 19:06:54.761  6771  6771 I Feature : [Lifetracker]Device Number: 3
09-02 19:06:54.762  6731  6731 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-02 19:06:54.763  6731  6731 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-02 19:06:54.765  1044  1962 I ActivityManager: Killing 6262:com.android.defcontainer/u0a4 (adj 15): empty #17
,09-02 19:06:54.796  1044  1872 W libprocessgroup: failed to open /acct/uid_10004/pid_6262/cgroup.procs: No such file or directory
09-02 19:06:54.797  6731  6731 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-02 19:06:54.803  6731  6731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-02 19:06:54.817  6731  6731 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:06:54.827  1044  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 19:06:54.827  1044  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 19:06:54.827  1044  1523 E WifiStateMachine: useWiFiOffloading() : false
09-02 19:06:54.827  1044  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 19:06:54.828  1927  1927 D WfdsService: Supplicant Connection state is changed : false
09-02 19:06:54.828  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 19:06:54.828  1927  2296 D WfdsService: Set the WFDS Monitor: false
09-02 19:06:54.828  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
09-02 19:06:54.831  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 19:06:54.831  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 19:06:54.836  2493  2493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:54.836  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 19:06:54.837  1044  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 19:06:54.838  1044  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 19:06:54.839  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.842  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:54.849  6731  6731 D BluetoothInputDevice: Proxy object connected
,09-02 19:06:54.855  6731  6731 D HidProfile: Bluetooth service connected
09-02 19:06:54.856  6731  6731 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:06:54.857  6731  6731 D PanProfile: Bluetooth service connected
09-02 19:06:54.858  6731  6731 D BluetoothMap: Proxy object connected
09-02 19:06:54.859  6731  6731 D MapProfile: Bluetooth service connected
09-02 19:06:54.859  6731  6731 D BluetoothMap: getConnectedDevices()
09-02 19:06:54.859  6731  6731 D BluetoothMap: Bluetooth is Not enabled
09-02 19:06:54.863  6731  6731 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-02 19:06:54.866  6731  6731 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-02 19:06:54.870  6731  6731 D BluetoothPermissionRequest: onReceive
09-02 19:06:54.872  6731  6731 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-02 19:06:54.879  1044  1962 I ActivityManager: Killing 6422:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-02 19:06:54.879  6731  6731 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-02 19:06:54.914  1044  1766 W libprocessgroup: failed to open /acct/uid_10008/pid_6422/cgroup.procs: No such file or directory
,09-02 19:06:54.914  3828  3828 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 19:06:54.915  3828  3828 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 19:06:54.915  3828  3828 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-02 19:06:54.999  1044  1962 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6801 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-02 19:06:55.014  3828  3828 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:55.014  3828  3828 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-02 19:06:55.017  3828  3828 V BluetoothFtpService: Ftp Service onStartCommand
09-02 19:06:55.018  3828  3828 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:55.018  3828  3828 V BluetoothFtpService: Ftp Service closeService
09-02 19:06:55.018  3828  3828 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 19:06:55.023   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 24.328ms
09-02 19:06:55.023  3828  3828 V BluetoothFtpService: successfully stopped ftp service
09-02 19:06:55.023  3828  3828 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 19:06:55.024  3828  3828 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 19:06:55.024  3828  3828 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 19:06:55.024  3828  3828 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:55.024  3828  3828 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 19:06:55.024  3828  3828 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 19:06:55.028  3828  3828 V BluetoothFtpService: Ftp Service onDestroy
09-02 19:06:55.028  3828  3828 V BluetoothFtpService: Ftp Service closeService
09-02 19:06:55.030  1044  1523 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 1 0 cz
,09-02 19:06:55.032  1044  1523 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 1 0 cz
09-02 19:06:55.045   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 21.436ms
,09-02 19:06:55.067   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 21.574ms
,09-02 19:06:55.112  1044  1904 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6818 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 19:06:55.118  3828  3828 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:55.118  3828  3828 V BluetoothSapService: state: 13
09-02 19:06:55.118  3828  3828 V BluetoothSapService: Stopping SAP server process
09-02 19:06:55.121  3828  3828 V BluetoothSapService: Sap Service closeSapService in
09-02 19:06:55.122  3828  3828 V BluetoothSapService: Close listen Socket : 
09-02 19:06:55.122  3828  3828 V BluetoothSapService: Close rfcomm Socket : 
09-02 19:06:55.122  3828  3828 V BluetoothSapService: Close sapd  Socket : 
09-02 19:06:55.125  3828  3828 V BluetoothSapService: Sap Service closeSapService out
09-02 19:06:55.125  3828  3828 V BluetoothSapService: Sap Service onDestroy
09-02 19:06:55.126  3828  3828 V BluetoothSapService: Sap Service closeSapService in
09-02 19:06:55.126  3828  3828 V BluetoothSapService: Close listen Socket : 
09-02 19:06:55.126  3828  3828 V BluetoothSapService: Close rfcomm Socket : 
,09-02 19:06:55.126  3828  3828 V BluetoothSapService: Close sapd  Socket : 
09-02 19:06:55.127  3828  3828 V BluetoothSapService: Sap Service closeSapService out
,09-02 19:06:55.151  6801  6801 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 19:06:55.176  6818  6818 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 19:06:55.185  6801  6801 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-02 19:06:55.195  1044  2017 I ActivityManager: Killing 5949:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-02 19:06:55.226  6801  6801 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-02 19:06:55.227  6801  6801 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-02 19:06:55.227  6801  6801 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-02 19:06:55.228  6801  6801 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,09-02 19:06:55.228  6801  6801 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-02 19:06:55.230  6801  6801 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-02 19:06:55.236  6801  6801 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-02 19:06:55.256  1044  1766 W libprocessgroup: failed to open /acct/uid_10011/pid_5949/cgroup.procs: No such file or directory
,09-02 19:06:55.275  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 19:06:55.283  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:06:55.321  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 19:06:55.326  6801  6801 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-02 19:06:55.328  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:06:55.329  6801  6801 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-02 19:06:55.333  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 19:06:55.333  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 19:06:55.333  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 19:06:55.340  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:06:55.346  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:06:55.353  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:06:55.354  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:06:55.355  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 19:06:55.359  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:06:55.365  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 19:06:55.365  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 19:06:55.365  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:06:55.372  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:06:55.383  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 19:06:55.396  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 19:06:55.397  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:06:55.400  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 19:06:55.486  1044  1581 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6838 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-02 19:06:55.512  3828  4020 W bt-btif : ag scb idx 1 not allocated
09-02 19:06:55.512  3828  4020 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 19:06:55.512  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:06:55.512  3828  3909 D bt_hci_bdroid: cleanup
09-02 19:06:55.512  3828  4020 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 19:06:55.512  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 19:06:55.512  3828  4020 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:06:55.512  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:06:55.512  3828  4020 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:06:55.512  3828  4022 I bt_lpm  : LPM is already off!!!
09-02 19:06:55.512  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:06:55.512  3828  4020 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-02 19:06:55.513  3828  4020 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:06:55.513  3828  4020 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 19:06:55.513  3828  4121 I bt_userial_mct: exiting userial_read_thread
,09-02 19:06:55.513  3828  4121 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 19:06:55.514  3828  3909 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-02 19:06:55.514  3828  4022 I bt_vendor: hw_epilog_process
09-02 19:06:55.515  3828  3909 D bt_hci_bdroid: cleanup Finalizing cleanup
,09-02 19:06:55.515  3828  3909 D bt_userial_mct: userial_close
09-02 19:06:55.515  3828  3909 E bt_userial_mct: pthread_join() FAILED result:3
09-02 19:06:55.515  3828  3909 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-02 19:06:55.601  3828  3909 D bt_hci_bdroid: set_power 0
09-02 19:06:55.601  3828  3909 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 19:06:55.601  3828  3909 I bt_vendor: bluetooth satus is on
09-02 19:06:55.601  3828  3909 I bt_vendor: bt-vendor : resetting BT status
09-02 19:06:55.601  3828  3909 I bt_vendor: Starting hciattach daemon
09-02 19:06:55.601  3828  3909 I bt_vendor: try to set false
,09-02 19:06:55.603  3828  3909 I bt_vendor: Starting hciattach daemon
09-02 19:06:55.603  3828  3909 I bt_vendor: try to set false
09-02 19:06:55.605  3828  3909 I bt_vendor: cleanup
09-02 19:06:55.606  3828  4020 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 19:06:55.606  3828  3909 I GKI_LINUX: GKI_exit_task 0 done
09-02 19:06:55.606  3828  3909 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 19:06:55.608  3828  3906 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 19:06:55.609  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:06:55.613  3828  3828 D HeadsetService: Received stop request...Stopping profile...
09-02 19:06:55.619  3828  3828 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 19:06:55.619  3828  3828 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:06:55.619  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3208f820
09-02 19:06:55.619  3828  3938 D HeadsetStateMachine: Exit Disconnected: -1
,09-02 19:06:55.622  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 19:06:55.623  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-02 19:06:55.623  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-02 19:06:55.623  1044  1044 D BluetoothHeadset: Proxy object disconnected
09-02 19:06:55.623  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 19:06:55.624  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-02 19:06:55.626  3828  3828 D A2dpService: Received stop request...Stopping profile...
09-02 19:06:55.626  3828  3994 D A2dpStateMachine: Exit Disconnected: -1
09-02 19:06:55.627  3828  3828 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 19:06:55.628  3828  3906 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 19:06:55.630  3828  3828 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 19:06:55.630  3828  3828 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:06:55.630  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3208f820
09-02 19:06:55.631  1044  1044 D BluetoothA2dp: Proxy object disconnected
09-02 19:06:55.631  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-02 19:06:55.633  3828  3828 D HidService: Received stop request...Stopping profile...
09-02 19:06:55.633  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3208f820
09-02 19:06:55.635  3828  3828 D HealthService: Received stop request...Stopping profile...
09-02 19:06:55.635  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3208f820
09-02 19:06:55.636  3828  3828 D PanService: Received stop request...Stopping profile...
09-02 19:06:55.637  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3208f820
09-02 19:06:55.638  3828  3828 D HeadsetStateMachine: Unbinding service...
09-02 19:06:55.639  3828  3828 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 19:06:55.639  3828  3828 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 19:06:55.639  3828  3828 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 19:06:55.639  3828  3828 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 19:06:55.639  3828  3828 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 19:06:55.639  3828  3828 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:06:55.639  3828  3828 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 19:06:55.639  3828  3828 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 19:06:55.640  3828  3828 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 19:06:55.640  3828  3828 D BtGatt.GattService: stop()
09-02 19:06:55.640  3828  3828 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 19:06:55.640  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:06:55.643  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3208f820
,09-02 19:06:55.645  3828  3828 D BluetoothMapService: Received stop request...Stopping profile...
09-02 19:06:55.645  3828  3828 D BluetoothMapService: stop()
09-02 19:06:55.646  3828  3828 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 19:06:55.646  3828  3828 D BluetoothMapEmailAppObserver: removeReceiver()
09-02 19:06:55.647  6731  6731 D BluetoothInputDevice: Proxy object disconnected
09-02 19:06:55.647  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3208f820
09-02 19:06:55.647  6731  6731 D HidProfile: Bluetooth service disconnected
09-02 19:06:55.647  6731  6731 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 19:06:55.647  6731  6731 D PanProfile: Bluetooth service disconnected
09-02 19:06:55.649  3828  3828 I BluetoothA2dpServiceJni: cleanupNative
09-02 19:06:55.649  3828  3995 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 19:06:55.650  6731  6731 D BluetoothMap: Proxy object disconnected
09-02 19:06:55.650  6731  6731 D MapProfile: Bluetooth service disconnected
09-02 19:06:55.650  3828  3828 I GKI_LINUX: GKI_exit_task 2 done
09-02 19:06:55.650  3828  3828 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 19:06:55.650  3828  3828 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 19:06:55.650  3828  3828 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 19:06:55.651  3828  3828 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 19:06:55.651  3828  3828 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 19:06:55.651  3828  3828 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 19:06:55.652  3828  3828 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 19:06:55.652  3828  3828 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 19:06:55.653  3828  3828 V BluetoothMapService: Handler(): got msg=4
09-02 19:06:55.653  3828  3828 D BluetoothMapService: MAP Service closeService in
09-02 19:06:55.653  3828  3828 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 19:06:55.653  3828  3828 V BluetoothMapService: MAP Service closeService out
09-02 19:06:55.653  3828  3828 D BluetoothMapService: cleanup()
09-02 19:06:55.653  3828  3828 D BluetoothMapService: MAP Service closeService in
09-02 19:06:55.653  3828  3828 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 19:06:55.653  3828  3906 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 19:06:55.653  3828  3828 V BluetoothMapService: MAP Service closeService out
09-02 19:06:55.654  3828  3906 D BluetoothAdapterProperties: Setting state to 10
09-02 19:06:55.654  3828  3906 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 19:06:55.654  1044  1119 D BluetoothManagerService: Message: 60
09-02 19:06:55.654  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 19:06:55.654  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-02 19:06:55.654  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:06:55.654  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 19:06:55.655  3828  3906 I BluetoothAdapterState: Entering OffState
09-02 19:06:55.655  6731  6748 D BluetoothPan: onBluetoothStateChange on: false
09-02 19:06:55.655  6731  6747 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 19:06:55.656  6731  6748 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 19:06:55.657  6731  6747 D BluetoothMap: onBluetoothStateChange: up=false
09-02 19:06:55.658  1837  2557 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:06:55.658  1837  3942 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 19:06:55.661  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:06:55.663  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 19:06:55.663  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 19:06:55.666  1044  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 19:06:55.666  1044  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
,09-02 19:06:55.666  1044  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@32da72db mBinding = false
09-02 19:06:55.667  1044  1119 D BluetoothManagerService: Sending unbind request.
09-02 19:06:55.669  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 19:06:55.670  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 19:06:55.671  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 19:06:55.671  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 19:06:55.671  6731  6731 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-02 19:06:55.678  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:55.679  1927  2104 D LGBluetoothAPIService: Message: 2
09-02 19:06:55.679  1927  2104 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2b2cbeb3 mBinding = false
09-02 19:06:55.679  3828  3909 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-02 19:06:55.679  1927  2104 D LGBluetoothAPIService: Sending unbind request.
09-02 19:06:55.679  3828  3828 I GKI_LINUX: GKI_exit_task 1 done
09-02 19:06:55.679  3828  3828 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 19:06:55.680  3828  3828 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 19:06:55.681  3828  3828 I art     : --- WEIRD: removing null entry 246
09-02 19:06:55.681  3828  3828 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-02 19:06:55.681  3828  3828 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 19:06:55.683  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:55.683  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 19:06:55.685  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:55.687  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 19:06:55.689  3828  3828 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 19:06:55.692  3828  3828 I art     : System.exit called, status: 0
09-02 19:06:55.692  3828  3828 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-02 19:06:55.693  6838  6858 W FormManager: Network not available. Please check & try again.
09-02 19:06:55.694  1588  1588 D BluetoothAdapter: 339789752: getState() :  mService = null. Returning STATE_OFF
09-02 19:06:55.694  1588  1588 D BluetoothAdapter: 339789752: getState() :  mService = null. Returning STATE_OFF
09-02 19:06:55.700  6731  6731 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 19:06:55.700  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 19:06:55.700  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 19:06:55.700  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 19:06:55.700  6731  6731 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 19:06:55.700  6731  6731 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-02 19:06:55.701  6731  6731 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 19:06:55.702  6731  6731 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 19:06:55.702  6731  6731 D LGBluetoothEventManager: [BTUI] clear device connection state
09-02 19:06:55.707  6731  6731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 19:06:55.711   320  2174 V AudioFlinger: 3828 died, releasing its sessions
09-02 19:06:55.711   320  2174 V AudioFlinger:  pid 1837 @ 0
,09-02 19:06:55.711   320  2174 V AudioFlinger:  pid 3432 @ 1
09-02 19:06:55.711   320  2174 V AudioFlinger:  pid 3432 @ 2
09-02 19:06:55.712  6838  6859 V FormManager: Network unavailable.
09-02 19:06:55.725  4447  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-02 19:06:55.770  1044  1998 I ActivityManager: Process com.android.bluetooth (pid 3828) has died
,09-02 19:06:55.771  1044  1998 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-02 19:06:55.779  6731  6731 D DockEventReceiver: finishStartingService: stopping service
09-02 19:06:55.780  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 19:06:55.780  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 19:06:55.781  6731  6731 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 19:06:55.782  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:06:55.784  6838  6859 V FormManager: Network unavailable.
,09-02 19:06:55.792  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:06:55.808  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 19:06:55.809  6731  6731 D BluetoothPermissionRequest: onReceive
09-02 19:06:55.816  6731  6731 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 19:06:55.816  6731  6731 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-02 19:06:55.820  6731  6731 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 19:06:55.822  4268  6875 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 19:06:55.823  4268  6877 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 19:06:55.823  4268  6877 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 19:06:55.878  1044  1766 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6881 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-02 19:06:55.886  6749  6749 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 19:06:55.886  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 19:06:55.886  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:06:55.888  6838  6879 W FormManager: Network not available. Please check & try again.
09-02 19:06:55.892  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:06:55.899  6838  6880 V FormManager: Network unavailable.
09-02 19:06:55.901  6838  6880 V FormManager: Network unavailable.
09-02 19:06:55.901  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 19:06:55.909  1044  1926 I ActivityManager: Killing 5972:com.android.contacts/u0a19 (adj 15): empty #17
09-02 19:06:55.994  1044  1059 W libprocessgroup: failed to open /acct/uid_10019/pid_5972/cgroup.procs: No such file or directory
,09-02 19:06:56.026  6881  6881 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 19:06:56.026  6881  6881 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 19:06:56.027  6881  6881 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 19:06:56.028  6881  6881 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 19:06:56.033  6801  6801 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-02 19:06:56.036  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-02 19:06:56.037  6801  6801 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-02 19:06:56.046  6881  6881 D BluetoothAdapterApp: Loading JNI Library
,09-02 19:06:56.075  6881  6881 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d5513a1 Instance Count = 1
,09-02 19:06:56.079  6881  6881 D BluetoothAdapterApp: onCreate
09-02 19:06:56.081  6801  6801 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 19:06:56.082  6801  6801 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 19:06:56.090  6801  6801 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-02 19:06:56.095  6801  6801 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-02 19:06:56.095  6801  6801 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
09-02 19:06:56.095  6801  6801 V SoundPool: doLoad: loading sample sampleID=1
09-02 19:06:56.096  6801  6901 V SoundPool: Start decode
09-02 19:06:56.096  6801  6901 V MediaPlayer[Native]: decode(32, 10857164, 17813)
09-02 19:06:56.096  6881  6881 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 19:06:56.096  6881  6881 D ProfileConfigQcom: Adding HeadsetService
09-02 19:06:56.096  6881  6881 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-02 19:06:56.097  6881  6881 D ProfileConfigQcom: Adding A2dpService
09-02 19:06:56.097  6881  6881 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 19:06:56.097  6881  6881 D ProfileConfigQcom: Adding HidService
09-02 19:06:56.097  6881  6881 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 19:06:56.097   320  1371 V MediaPlayerService: decode(23, 10857164, 17813)
09-02 19:06:56.097   320  1371 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-02 19:06:56.097  6881  6881 D ProfileConfigQcom: Adding HealthService
09-02 19:06:56.097   320  1371 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-02 19:06:56.097   320  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-02 19:06:56.097  6881  6881 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-02 19:06:56.097   320  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-02 19:06:56.097   320  1371 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-02 19:06:56.098   320  1371 V MediaPlayerService: player type = 3
09-02 19:06:56.098   320  1371 V AwesomePlayer: AwesomePlayer create()
09-02 19:06:56.098   320  1371 V AwesomePlayer: reset_l() 
09-02 19:06:56.098   320  1371 V AwesomePlayer: cancelPlayerEvents
09-02 19:06:56.098   320  1371 V AwesomePlayer: setAudioSink() 
09-02 19:06:56.098   320  1371 V AwesomePlayer: reset_l() 
09-02 19:06:56.098  6881  6881 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 19:06:56.098   320  1371 V AudioCache: notify(0xb1432480, 8, 0, 0)
09-02 19:06:56.098   320  1371 V AudioCache: ignored
09-02 19:06:56.098   320  1371 V AwesomePlayer: cancelPlayerEvents
09-02 19:06:56.098  6881  6881 D ProfileConfigQcom: Adding PanService
09-02 19:06:56.099  6881  6881 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 19:06:56.099  6881  6881 D ProfileConfigQcom: Adding GattService
09-02 19:06:56.099   320  1371 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-02 19:06:56.099  6881  6881 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 19:06:56.099   320  1371 V AwesomePlayer: setDataSource_l dataSource
09-02 19:06:56.099   320  1371 V LGParserOSAL: SniffLGParser start
09-02 19:06:56.099  6881  6881 D ProfileConfigQcom: Adding BluetoothMapService
09-02 19:06:56.099   320  1371 V LGParserOSAL: MainType:5, SubType=0
09-02 19:06:56.099   320  1371 V LGParserOSAL: #### check Mime : application/ogg
09-02 19:06:56.099   320  1371 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-02 19:06:56.099  6881  6881 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 19:06:56.099   320  1371 E MediaExtractor: Use LGExtractor :application/ogg 
09-02 19:06:56.100  6881  6881 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-02 19:06:56.101  6801  6801 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 19:06:56.105  6652  6652 D UEI.SmartControl: QS Service created
,09-02 19:06:56.107  6731  6731 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 19:06:56.109  6881  6881 V LGMDMManagerInternal: Create singleton instance
09-02 19:06:56.114  6652  6652 I UEI.SmartControl: Service initServices...
09-02 19:06:56.114  6652  6652 D UEI.SmartControl: QS start get config
09-02 19:06:56.105  6801  6801 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-02 19:06:56.115  6801  6801 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 19:06:56.115  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 19:06:56.124  6801  6801 V LGMDMManager: Create singleton instance
09-02 19:06:56.144   320  1371 V LGParserOSAL: supported mime: application/ogg
09-02 19:06:56.144   320  1371 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-02 19:06:56.144   320  1371 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-02 19:06:56.144   320  1371 V AwesomePlayer: mBitrate = -1 bits/sec
09-02 19:06:56.144   320  1371 V AwesomePlayer: AudioTrack Setting
09-02 19:06:56.144   320  1371 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-02 19:06:56.144   320  1371 V AwesomePlayer: setAudioSource() 
09-02 19:06:56.144   320  1371 V MediaPlayerService: prepare
09-02 19:06:56.144   320  1371 V AwesomePlayer: prepareAsync_l() 
09-02 19:06:56.144   320  1371 V MediaPlayerService: wait for prepare
09-02 19:06:56.145   320  6903 V AwesomePlayer: onPrepareAsyncEvent() 
09-02 19:06:56.145   320  6903 V AwesomePlayer: initAudioDecoder() 
09-02 19:06:56.145   320  6903 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 19:06:56.145   320  6903 V AudioSystem: isOffloadSupported()
09-02 19:06:56.145   320  6903 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 19:06:56.145   320  6903 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 19:06:56.145   320  6903 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 19:06:56.145   320  6903 V AwesomePlayer: getUseOffload() = 0 
09-02 19:06:56.145   320  6903 V OMXCodec: OMXCodec::Create
09-02 19:06:56.145   320  6903 V OMXCodec: findMatchingCodecs()
09-02 19:06:56.145   320  6903 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-02 19:06:56.145   320  6903 V OMXCodec: matchingCodecs.size()=1
09-02 19:06:56.145   320  6903 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-02 19:06:56.148   320  6903 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-02 19:06:56.148   320  6903 V LGCodecAdapter: LG Codec Adapter start
09-02 19:06:56.148   320  6903 V OMXCodec: OMXCodec Createtor
09-02 19:06:56.148   320  6903 V OMXCodec: setComponentRole
09-02 19:06:56.148   320  6903 V OMXCodec: configureCodec protected=0
09-02 19:06:56.148   320  6903 V LGCodecAdapter: called getLGCodecSpecificData
09-02 19:06:56.148   320  6903 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-02 19:06:56.148   320  6903 V LGCodecOSAL: Called LGconfigureCodecMETA
09-02 19:06:56.148   320  6903 V LGCodecOSAL: Called LGconfigureCodecMSG
09-02 19:06:56.148   320  6903 V LGCodecOSAL: Not support LGCodec
09-02 19:06:56.148   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 19:06:56.148   320  6903 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-02 19:06:56.148   320  6903 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-02 19:06:56.148   320  6903 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-02 19:06:56.148   320  6903 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 19:06:56.148   320  6903 V AudioSystem: isOffloadSupported()
09-02 19:06:56.148   320  6903 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,09-02 19:06:56.148   320  6903 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 19:06:56.148   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-02 19:06:56.148   320  6903 V OMXCodec: init()
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-02 19:06:56.149   320  6903 V OMXCodec: allocateBuffers
09-02 19:06:56.149   320  6903 V OMXCodec: allocateBuffersOnPort portIndex=0
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-02 19:06:56.149   320  6903 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-02 19:06:56.149   320  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
09-02 19:06:56.149   320  6903 V OMXCodec: init() mAsyncCompletion wait!!! 
09-02 19:06:56.150   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 19:06:56.150   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 19:06:56.150   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-02 19:06:56.150   320  6903 V OMXCodec: init() mAsyncCompletion wait!!! 
09-02 19:06:56.150   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-02 19:06:56.150   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-02 19:06:56.150   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-02 19:06:56.150   320  6903 V OMXCodec: init() mAsyncCompletion wait free! 
09-02 19:06:56.150   320  6903 V AwesomePlayer: finishAsyncPrepare_l() 
09-02 19:06:56.150   320  6903 V AudioCache: notify(0xb1432480, 5, 0, 0)
09-02 19:06:56.150   320  6903 V AudioCache: ignored
09-02 19:06:56.150   320  6903 V AudioCache: notify(0xb1432480, 1, 0, 0)
09-02 19:06:56.151   320  6903 V AudioCache: prepared
09-02 19:06:56.151   320  1371 V AudioCache: wait - success
09-02 19:06:56.151   320  1371 V MediaPlayerService: start
09-02 19:06:56.151   320  1371 V AwesomePlayer: play_l() 
09-02 19:06:56.151   320  1371 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-02 19:06:56.151   320  1371 V AwesomePlayer: createAudioPlayer_l
09-02 19:06:56.151   320  1371 V AwesomePlayer: seekAudioIfNecessary_l() 
09-02 19:06:56.151   320  1371 V AwesomePlayer: startAudioPlayer_l() 
09-02 19:06:56.151   320  1371 D AudioPlayer: start of Playback, useOffload 0
09-02 19:06:56.151   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-02 19:06:56.151   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-02 19:06:56.154   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-02 19:06:56.154   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-02 19:06:56.154   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-02 19:06:56.154   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-02 19:06:56.154   320  6905 ,V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-02 19:06:56.155   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-02 19:06:56.156   320  6905 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 19:06:56.156   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 19:06:56.156   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-02 19:06:56.156   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-02 19:06:56.156   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-02 19:06:56.156   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd920 on output port
09-02 19:06:56.156   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-02 19:06:56.156   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-02 19:06:56.158   320  1371 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-02 19:06:56.158   320  1371 V AudioCache: notify(0xb1432480, 6, 0, 0)
09-02 19:06:56.158   320  1371 V AudioCache: ignored
09-02 19:06:56.159   320  1371 V MediaPlayerService: wait for playback complete
,09-02 19:06:56.159   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.159   320  6906 V AudioCache: memcpy(0xac300000, 0xb16a7000, 4096)
09-02 19:06:56.164   320  6906 V AudioCache: write(0xb16a7000, 4096)
,09-02 19:06:56.164   320  6906 V AudioCache: memcpy(0xac301000, 0xb16a7000, 4096)
09-02 19:06:56.165   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.165   320  6906 V AudioCache: memcpy(0xac302000, 0xb16a7000, 4096)
09-02 19:06:56.166   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.166   320  6906 V AudioCache: memcpy(0xac303000, 0xb16a7000, 4096)
09-02 19:06:56.166   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.166   320  6906 V AudioCache: memcpy(0xac304000, 0xb16a7000, 4096)
09-02 19:06:56.167   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.167   320  6906 V AudioCache: memcpy(0xac305000, 0xb16a7000, 4096)
09-02 19:06:56.167  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 19:06:56.168   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.168   320  6906 V AudioCache: memcpy(0xac306000, 0xb16a7000, 4096)
09-02 19:06:56.168  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-02 19:06:56.168   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.169   320  6906 V AudioCache: memcpy(0xac307000, 0xb16a7000, 4096)
09-02 19:06:56.169   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.169   320  6906 V AudioCache: memcpy(0xac308000, 0xb16a7000, 4096)
09-02 19:06:56.170   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.170   320  6906 V AudioCache: memcpy(0xac309000, 0xb16a7000, 4096)
09-02 19:06:56.171   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.171   320  6906 V AudioCache: memcpy(0xac30a000, 0xb16a7000, 4096)
09-02 19:06:56.171  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7426
09-02 19:06:56.172   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.172   320  6906 V AudioCache: memcpy(0xac30b000, 0xb16a7000, 4096)
09-02 19:06:56.172   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.172   320  6906 V AudioCache: memcpy(0xac30c000, 0xb16a7000, 4096)
09-02 19:06:56.173   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.173   320  6906 V AudioCache: memcpy(0xac30d000, 0xb16a7000, 4096)
09-02 19:06:56.174   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.174   320  6906 V AudioCache: memcpy(0xac30e000, 0xb16a7000, 4096)
09-02 19:06:56.174   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.174   320  6906 V AudioCache: memcpy(0xac30f000, 0xb16a7000, 4096)
09-02 19:06:56.175   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.175   320  6906 V AudioCache: memcpy(0xac310000, 0xb16a7000, 4096)
09-02 19:06:56.176   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.176   320  6906 V AudioCache: memcpy(0xac311000, 0xb16a7000, 4096)
09-02 19:06:56.177   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.177   320  6906 V AudioCache: memcpy(0xac312000, 0xb16a7000, 4096)
09-02 19:06:56.177   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.177   320  6906 V AudioCache: memcpy(0xac313000, 0xb16a7000, 4096)
09-02 19:06:56.178   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.178   320  6906 V AudioCache: memcpy(0xac314000, 0xb16a7000, 4096)
09-02 19:06:56.179   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.179   320  6906 V AudioCache: memcpy(0xac315000, 0xb16a7000, 4096)
,09-02 19:06:56.180   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.180   320  6906 V AudioCache: memcpy(0xac316000, 0xb16a7000, 4096)
09-02 19:06:56.181  6881  6881 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:56.181   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.181   320  6906 V AudioCache: memcpy(0xac317000, 0xb16a7000, 4096)
09-02 19:06:56.181   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.181   320  6906 V AudioCache: memcpy(0xac318000, 0xb16a7000, 4096)
09-02 19:06:56.182   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.182   320  6906 V AudioCache: memcpy(0xac319000, 0xb16a7000, 4096)
09-02 19:06:56.182   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.182   320  6906 V AudioCache: memcpy(0xac31a000, 0xb16a7000, 4096)
09-02 19:06:56.182   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.182   320  6906 V AudioCache: memcpy(0xac31b000, 0xb16a7000, 4096)
09-02 19:06:56.182   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.183   320  6906 V AudioCache: memcpy(0xac31c000, 0xb16a7000, 4096)
09-02 19:06:56.183   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.183  6881  6881 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-02 19:06:56.183   320  6906 V AudioCache: memcpy(0xac31d000, 0xb16a7000, 4096)
09-02 19:06:56.184   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.184   320  6906 V AudioCache: memcpy(0xac31e000, 0xb16a7000, 4096)
09-02 19:06:56.184  6881  6881 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 19:06:56.184   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.184   320  6906 V AudioCache: memcpy(0xac31f000, 0xb16a7000, 4096)
09-02 19:06:56.184  6881  6881 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 19:06:56.184   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.184   320  6906 V AudioCache: memcpy(0xac320000, 0xb16a7000, 4096)
09-02 19:06:56.185  6881  6881 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:06:56.185  6881  6881 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 19:06:56.185   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.185   320  6906 V AudioCache: memcpy(0xac321000, 0xb16a7000, 4096)
09-02 19:06:56.185   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.185   320  6906 V AudioCache: memcpy(0xac322000, 0xb16a7000, 4096)
09-02 19:06:56.185   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.185   320  6906 V AudioCache: memcpy(0xac323000, 0xb16a7000, 4096)
09-02 19:06:56.185   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.185   320  6906 V AudioCache: memcpy(0xac324000, 0xb16a7000, 4096)
09-02 19:06:56.186   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.186   320  6906 V AudioCache: memcpy(0xac325000, 0xb16a7000, 4096)
09-02 19:06:56.187   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.187   320  6906 V AudioCache: memcpy(0xac326000, 0xb16a7000, 4096)
09-02 19:06:56.187   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.187   320  6906 V AudioCache: memcpy(0xac327000, 0xb16a7000, 4096)
09-02 19:06:56.187   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.187   320  6906 V AudioCache: memcpy(0xac328000, 0xb16a7000, 4096)
09-02 19:06:56.188   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.188   320  6906 V AudioCache: memcpy(0xac329000, 0xb16a7000, 4096)
09-02 19:06:56.188   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.188   320  6906 V AudioCache: memcpy(0xac32a000, 0xb16a7000, 4096)
09-02 19:06:56.188   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.188   320  6906 V AudioCache: memcpy(0xac32b000, 0xb16a7000, 4096)
09-02 19:06:56.188   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.188   320  6906 V AudioCache: memcpy(0xac32c000, 0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: memcpy(0xac32d000, 0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: memcpy(0xac32e000, 0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: memcpy(0xac32f000, 0xb16a7000, 4096)
,09-02 19:06:56.189   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: memcpy(0xac330000, 0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: write(0xb16a7000, 4096)
09-02 19:06:56.189   320  6906 V AudioCache: memcpy(0xac331000, 0xb16a7000, 4096)
09-02 19:06:56.190   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-02 19:06:56.190   320  6906 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-02 19:06:56.190   320  6906 V AwesomePlayer: postAudioEOS() 
09-02 19:06:56.190   320  6906 V AudioCache: write(0xb16a7000, 280)
09-02 19:06:56.190   320  6906 V AudioCache: memcpy(0xac332000, 0xb16a7000, 280)
09-02 19:06:56.191   320  6903 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-02 19:06:56.191   320  6903 V AwesomePlayer: onStreamDone
09-02 19:06:56.191   320  6903 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-02 19:06:56.191   320  6903 V AudioCache: notify(0xb1432480, 2, 0, 0)
09-02 19:06:56.191   320  6903 V AudioCache: playback complete
09-02 19:06:56.191   320  6903 V AwesomePlayer: pause_l() 
09-02 19:06:56.191   320  6903 V AudioCache: notify(0xb1432480, 7, 0, 0)
09-02 19:06:56.191   320  6903 V AudioCache: ignored
09-02 19:06:56.191   320  1371 V AudioCache: wait - success
09-02 19:06:56.191   320  6903 V AwesomePlayer: cancelPlayerEvents
09-02 19:06:56.191   320  1371 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-02 19:06:56.191   320  6903 D AudioPlayer: Pause Playback at 1068125
09-02 19:06:56.192   320  1371 V AwesomePlayer: reset_l() 
09-02 19:06:56.192   320  1371 V AudioCache: notify(0xb1432480, 8, 0, 0)
,09-02 19:06:56.192   320  1371 V AudioCache: ignored
09-02 19:06:56.192   320  1371 V AwesomePlayer: cancelPlayerEvents
09-02 19:06:56.192   320  1371 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-02 19:06:56.192   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-02 19:06:56.192   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-02 19:06:56.192   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-02 19:06:56.192   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-02 19:06:56.192  6818  6818 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd920 on port 1
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-02 19:06:56.192   320  6905 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-02 19:06:56.192   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 19:06:56.192   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-02 19:06:56.192   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-02 19:06:56.193   320  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-02 19:06:56.193   320  1371 D AudioPlayer: AudioPlayer releasing audio source
09-02 19:06:56.193   320  1371 D AudioPlayer: AudioPlayer done releasing audio source
09-02 19:06:56.193   320  1371 V AwesomePlayer: reset_l() 
09-02 19:06:56.193   320  1371 V AwesomePlayer: cancelPlayerEvents
09-02 19:06:56.193   320  1371 V AwesomePlayer: ~AwesomePlayer call
09-02 19:06:56.193   320  1371 V AwesomePlayer: reset_l() 
09-02 19:06:56.193   320  1371 V AwesomePlayer: cancelPlayerEven,ts
09-02 19:06:56.193  6801  6901 V SoundPool: close(32)
09-02 19:06:56.194  6801  6901 V SoundPool: pointer = 0x9fe7d000, size = 205080, sampleRate = 48000, numChannels = 2
09-02 19:06:56.589  6652  6652 I UEI.SmartControl: Supports setup maps: true
09-02 19:06:56.595  6652  6652 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 19:06:56.595  6652  6652 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 19:06:56.595  6652  6652 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 19:06:56.595  6652  6652 I UEI.SmartControl: ### init IR Blaster...
,09-02 19:06:56.601  6652  6652 D serial_port: Configuring serial port
,09-02 19:06:56.601  6652  6652 E UEI.SmartControl: UEIBLaster setting for 616
09-02 19:06:56.602  6652  6652 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 19:06:56.602  6652  6652 I UEI.SmartControl: configuring settings for MAXQ616
09-02 19:06:56.602  6652  6652 I UEI.SmartControl: Get version...
09-02 19:06:56.619  6652  6914 D UEI.SmartControl: serial port data available: 21
,09-02 19:06:56.645  6652  6652 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 19:06:56.645  6652  6652 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 19:06:56.645  6652  6652 I UEI.SmartControl: QS saving settings...
09-02 19:06:56.646  6652  6652 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 19:06:56.664  6652  6914 D UEI.SmartControl: serial port data available: 4
,09-02 19:06:56.696  6652  6652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-02 19:06:56.707  6652  6920 I UEI.SmartControl: Device manager: loading config....
09-02 19:06:56.708  6652  6920 D UEI.SmartControl: ----------- loading internal config...
09-02 19:06:56.714  6652  6652 E UEI.SmartControl: Services init done
09-02 19:06:56.714  6652  6652 D UEI.SmartControl: QS Service init finished
,09-02 19:06:56.717  6652  6652 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 19:06:56.717  6652  6652 D UEI.SmartControl: QS Service version code: 201091
09-02 19:06:56.718  6652  6652 D UEI.SmartControl: Service requested: Control
09-02 19:06:56.722  6652  6920 E UEI.SmartControl: Loading SETTINGS...
09-02 19:06:56.723  6652  6652 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 19:06:56.725  6652  6652 D UEI.SmartControl: Internal service binding...
09-02 19:06:56.727  6801  6801 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,09-02 19:06:56.731  6652  6667 I UEI.SmartControl: ------ IControl API: 11
09-02 19:06:56.731  6652  6667 D UEI.SmartControl: File observer start...
09-02 19:06:56.731  6652  6667 E UEI.SmartControl: IR Port is disabled: false
09-02 19:06:56.732  6652  6667 D UEI.SmartControl: Starting file observer...
09-02 19:06:56.733  6652  6667 I UEI.SmartControl: Registering callback...
09-02 19:06:56.736  6652  6920 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-02 19:06:56.740  6652  6668 I UEI.SmartControl: ------ IControl API: 19
,09-02 19:06:56.744  6652  6668 I UEI.SmartControl: Registering Services Ready callback...
09-02 19:06:56.754  6652  6919 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-02 19:06:56.756  6801  6816 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-02 19:06:56.757  6801  6899 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-02 19:06:56.757  6801  6899 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-02 19:06:56.757  6801  6801 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-02 19:06:56.758  6801  6801 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-02 19:06:56.758  6652  6667 I UEI.SmartControl: ------ IControl API: 8
09-02 19:06:56.759  6652  6919 D UEI.SmartControl: -----service ready thread exits
09-02 19:06:56.760  6801  6801 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-02 19:06:56.760  6801  6801 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-02 19:06:56.761  6801  6801 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-02 19:06:56.761  6801  6801 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-02 19:06:56.762  6801  6801 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-02 19:06:56.762  6801  6801 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-02 19:06:56.766  6801  6801 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-02 19:06:56.770  1044  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f5388ab type 2 when 121052 com.google.android.gms} when 121052
09-02 19:06:56.772  6801  6801 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-02 19:06:56.773  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-02 19:06:56.773  6801  6801 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 19:06:56.774  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 19:06:56.775  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 19:06:56.776  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-02 19:06:56.776  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-02 19:06:56.777  6801  6801 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472836016777]
09-02 19:06:56.784  6801  6801 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-02 19:06:56.791   316  6924 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 19:06:56.792  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 19:06:56.795  1044  1926 I ActivityManager: Killing 5994:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-02 19:06:56.836  6801  6922 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-02 19:06:56.841  1044  1926 I ActivityManager: Killing 6461:com.lge.email/u0a23 (adj 15): empty #18
09-02 19:06:56.872  1044  1060 W libprocessgroup: failed to open /acct/uid_10027/pid_5994/cgroup.procs: No such file or directory
,09-02 19:06:56.878  1044  1904 W libprocessgroup: failed to open /acct/uid_10023/pid_6461/cgroup.procs: No such file or directory
09-02 19:06:56.884  6801  6801 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-02 19:06:56.887  6801  6801 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 19:06:56.887  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-02 19:06:56.888  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-02 19:06:56.888  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-02 19:06:56.888  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-02 19:06:56.889  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-02 19:06:56.898  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-02 19:06:57.365  1044  1998 D WifiServiceImplEx: setWifiEnabled: true pid=6536, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-02 19:06:57.367  1044  1998 D WifiService: setWifiEnabled: true pid=6536, uid=10118
,09-02 19:06:57.367  1044  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:06:57.397  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 19:06:57.397  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 19:06:57.397  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,09-02 19:06:57.401  1044  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-02 19:06:57.401  1044  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-02 19:06:57.404  1044  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 19:06:57.404  1044  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 19:06:57.404  1044  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 19:06:57.404  1044  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 19:06:57.404  1044  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 19:06:57.404  1044  1523 E WifiHW  : unknown target_country: EU , set to default
09-02 19:06:57.404  1044  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 19:06:57.404  1044  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-02 19:06:57.404  1044  1523 I WifiUtil: gEnableBmps=1
09-02 19:06:57.461  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:57.476  1044  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 19:06:57.485  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:57.489  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:57.493  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:06:57.494  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 19:06:57.496  1044  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 19:06:57.504  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:57.508  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:57.509  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 19:06:57.512  6361  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 19:06:57.529  5698  5698 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 19:06:57.539  5698  5698 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 19:06:57.565  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:57.594  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:57.643  1044  1559 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6926 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-02 19:06:57.649  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:57.650  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 19:06:57.717  6926  6926 I AppUp4:AppBoxCP: onCreate
,09-02 19:06:57.717  6926  6926 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-02 19:06:57.728  6926  6926 I AppUp4:DB:  setFingerPrint start
,09-02 19:06:57.728  6926  6926 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-02 19:06:57.736  6926  6926 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-02 19:06:57.736  6926  6926 I AppUp4:DB:  SDK version = 21
09-02 19:06:57.736  6926  6926 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-02 19:06:57.739  6926  6926 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-02 19:06:57.740  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-02 19:06:57.740  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:57.742  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-02 19:06:57.743  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 19:06:57.750  6926  6926 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 19:06:57.794  6926  6926 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:06:57.795  6926  6926 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:06:57.804  6926  6926 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e6eb23
09-02 19:06:57.804  6926  6926 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 19:06:57.804  6926  6926 D AppUp4:CustFacade: isPhone : true
09-02 19:06:57.805  6926  6926 D AppUp4:CustModeStarterReceiver: begin check event
09-02 19:06:57.806  6926  6926 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-02 19:06:57.806  6926  6926 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-02 19:06:57.807  6926  6960 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-02 19:06:57.807  6926  6960 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-02 19:06:57.807  6926  6960 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-02 19:06:57.812  1044  1060 I ActivityManager: Killing 6058:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-02 19:06:57.855  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 19:06:57.856  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 19:06:57.858  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 19:06:57.860  1044  1942 W libprocessgroup: failed to open /acct/uid_10080/pid_6058/cgroup.procs: No such file or directory
09-02 19:06:57.866  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:06:57.874  4268  6962 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 19:06:57.879  4268  6963 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 19:06:57.879  4268  6963 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 19:06:57.943  1044  1963 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6973 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-02 19:06:58.043  6973  6973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 19:06:58.043  6973  6973 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 19:06:58.045  6973  6973 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 19:06:58.045  6973  6973 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 19:06:58.108  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-02 19:06:58.114  1044  1119 D Tethering: InitialState.processMessage what=4
09-02 19:06:58.115  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:06:58.126   316   916 D SoftapController: Softap fwReload - Ok
09-02 19:06:58.128  1044  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (718ms)
,09-02 19:06:58.132   316   916 D CommandListener: Setting iface cfg
09-02 19:06:58.132   316   916 D CommandListener: Trying to bring down wlan0
09-02 19:06:58.134   316   916 D CommandListener: Clearing all IP addresses on wlan0
09-02 19:06:58.142  1044  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 19:06:58.137  6992  6992 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:06:58.137  6992  6992 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 19:06:58.156  6973  6973 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-02 19:06:58.170  6992  6992 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 19:06:58.170  6973  6973 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-02 19:06:58.199  6992  6992 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 19:06:58.199  6992  6992 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-02 19:06:58.211  6973  6973 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 19:06:58.242  6973  6973 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 19:06:58.243  1044  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 19:06:58.243  1044  1523 E WifiStateMachine: useWiFiOffloading() : false
09-02 19:06:58.243  1044  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 19:06:58.244  1044  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 19:06:58.246  1044  1523 D WifiMonitor: connecting to supplicant
09-02 19:06:58.246  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-02 19:06:58.247  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-02 19:06:58.248  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:58.250  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:58.251  6973  6973 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:06:58.252  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:58.309  6992  6992 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 19:06:58.333  6992  6992 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-02 19:06:58.339  6992  6992 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-02 19:06:58.340  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 19:06:58.341  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-02 19:06:58.341  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 19:06:58.342  1044  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 19:06:58.342  1044  7002 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-02 19:06:58.342  1044  7002 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 19:06:58.342  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:58.342  1044  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:58.343  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:58.343  1044  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:58.344  1044  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 19:06:58.344  1044  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 19:06:58.344  1044  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 19:06:58.345  1044  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 19:06:58.345  1044  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 19:06:58.346  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.346  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.346  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.346  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.346  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 19:06:58.346  1044  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 19:06:58.346  1044  1523 E WifiStateMachine: useWiFiOffloading() : false
09-02 19:06:58.346  1044  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 19:06:58.348  6973  6973 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 19:06:58.349  1044  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 19:06:58.350  1044  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-02 19:06:58.350  1044  1523 D WifiConfigStore: Loading config and enabling all networks 
09-02 19:06:58.350  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:58.350  1044  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 19:06:58.350  1044  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-02 19:06:58.350  1927  1927 D WfdService: Waiting for WifiP2p enabling
09-02 19:06:58.351  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 19:06:58.352  1044  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 19:06:58.354  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:58.354  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:58.354  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:58.354  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:58.354  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:58.354  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 1,9:06:58.354  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:58.354  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:58.354  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:58.354  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:58.354  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:06:58.355  6992  6992 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-02 19:06:58.355  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 19:06:58.355  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 19:06:58.355  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 19:06:58.355  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,09-02 19:06:58.355  1044  7002 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 19:06:58.355  1044  7002 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 19:06:58.356  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:58.356  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:58.356  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:58.356  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:06:58.356  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:58.356  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:58.356  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:58.356  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:58.356  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:58.356  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:58.356  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:06:58.359  1044  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 19:06:58.368  1044  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-02 19:06:58.368  1044  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 19:06:58.369  1044  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-02 19:06:58.370  1044  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-02 19:06:58.370  1044  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-02 19:06:58.370  1044  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 19:06:58.371  1044  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 19:06:58.371  1044  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 19:06:58.371  1044  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 19:06:58.371  1044  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 19:06:58.372  1044  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 19:06:58.372  1044  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,09-02 19:06:58.372  1044  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 19:06:58.372  1044  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-02 19:06:58.373  1044  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 19:06:58.373  1044  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 19:06:58.373  1044  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 19:06:58.374  6973  6973 I HubEmail: JNI_OnLoad()
09-02 19:06:58.374  6973  6973 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 19:06:58.374  6973  6973 I HubEmail: registerNatives()
09-02 19:06:58.375  6973  6973 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 19:06:58.375  6973  6973 I HubEmail: registerNativeMethods()
09-02 19:06:58.375  6973  6973 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 19:06:58.375  6973  6973 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-02 19:06:58.375  1927  1927 D WfdsService: Supplicant Connection state is changed : true
09-02 19:06:58.375  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 19:06:58.375  1927  2296 D WfdsService: Set the WFDS Monitor: true
09-02 19:06:58.375  1927  2296 D WfdsMonitor: WfdsMonitorThread create
09-02 19:06:58.375  1927  2296 D WfdsMonitor: WFDS Monitor is created and started
09-02 19:06:58.375  1927  2296 D WfdsService: WiFi: Supplicant connection re-established
09-02 19:06:58.376  1044  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 19:06:58.376  1044  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 19:06:58.377  1927  7004 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 19:06:58.377  1927  7004 E CtrlSupplicant: Succeed to open control connection
09-02 19:06:58.377  1927  7004 E CtrlSupplicant: Succeed to open monitor connection
09-02 19:06:58.378  1044  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 19:06:58.378  1044  1523 D WifiNative-HAL: Setting external_sim to 1
,09-02 19:06:58.378  1927  7004 D WfdsMonitor: Supplicant connection established
09-02 19:06:58.378  1044  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 19:06:58.378  1927  2296 D WfdsService: Connected to the supplicant for wfds
09-02 19:06:58.381  1044  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 19:06:58.381  1044  1523 I WifiNative-HAL: startHal
09-02 19:06:58.381  1044  1523 D wifi    : setting scan oui 0x95275f80
09-02 19:06:58.381  1044  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 19:06:58.381  1044  1523 I WifiNative-HAL: startHal
09-02 19:06:58.381  1044  1523 D wifi    : setting scan oui 0x95275f80
09-02 19:06:58.381  1044  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 19:06:58.382  1044  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 19:06:58.382  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 19:06:58.382  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 19:06:58.383  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-02 19:06:58.383  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 19:06:58.383  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 19:06:58.383  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 19:06:58.383  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 19:06:58.383  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 19:06:58.384  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 19:06:58.384  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 19:06:58.384  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 19:06:58.384  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,09-02 19:06:58.384  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 19:06:58.384  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 19:06:58.385  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 19:06:58.385  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 19:06:58.385  6992  6992 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 19:06:58.386  3432  3432 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 19:06:58.386  3432  3432 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 19:06:58.386  3432  3432 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-02 19:06:58.386  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 19:06:58.386  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 19:06:58.387  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 19:06:58.387  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 19:06:58.387  1044  1523 E WifiNative: : [122,673,029 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 19:06:58.387  6973  7005 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.387  1044  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 19:06:58.388  1044  1523 D WifiNative-wlan0: RECONNECT: returned true
09-02 19:06:58.388  1044  1523 D WifiNative-wlan0: doString: [STATUS]
09-02 19:06:58.388  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 19:06:58.388  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 19:06:58.388  6838  7006 W FormManager: Network not available. Please check & try again.
09-02 19:06:58.389  1044  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 19:06:58.389  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 19:06:58.389  1044  1523 D WifiNative-wlan0: SET ps 1: returned true
09-02 19:06:58.390  1044  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.391   316   916 D CommandListener: Setting iface cfg
09-02 19:06:58.391   316   916 D CommandListener: Trying to bring up p2p0
09-02 19:06:58.391  1044  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 19:06:58.391  1044  1521 D LGWifiP2pService: P2pEnablingState
09-02 19:06:58.392  1044  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.392  1044  1521 D LGWifiP2pService: P2p socket connection successful
09-02 19:06:58.392  1044  1521 D LGWifiP2pService: P2pEnabledState
09-02 19:06:58.422  1044  1963 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7009 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-02 19:06:58.427  1044  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 19:06:58.427  1044  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 19:06:58.427  1044  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 19:06:58.428  1044  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 19:06:58.428  1044  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 19:06:58.429  1044  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
,09-02 19:06:58.429  1044  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 19:06:58.429  1044  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 19:06:58.429  6992  6992 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 19:06:58.429  1044  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 19:06:58.430  1044  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 19:06:58.431  1044  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 19:06:58.432  1044  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-02 19:06:58.432  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 19:06:58.432  1044  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-02 19:06:58.432  1044  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 19:06:58.432  1044  1044 D RttService: SCAN_AVAILABLE : 3
09-02 19:06:58.432  1044  1521 D LGWifiP2pService: before postfix = G3
09-02 19:06:58.432  1044  1521 D WifiServerServiceExt: postfix byte check : 2
09-02 19:06:58.432  1044  1521 D LGWifiP2pService: after postfix = G3
09-02 19:06:58.432  1044  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 19:06:58.432  1044  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 19:06:58.432  1044  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 19:06:58.433  1044  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 19:06:58.433  1044  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 19:06:58.433  1044  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 19:06:58.433  1044  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 19:06:58.434  1044  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 19:06:58.434  1044  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 19:06:58.435  1044  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 19:06:58.435  1044  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-02 19:06:58.435  6992  6992 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 19:06:58.435  1044  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 19:06:58.435  1044  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-02 19:06:58.436  1044  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-02 19:06:58.436  1044  1540 D WifiScanningService: DefaultState got{ when=-4ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.436  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=122722  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 19:06:58.436  1044  1540 I WifiNative-HAL: startHal
09-02 19:06:58.436  1044  1540 D wifi    : getting scan capabilities on interface[1] = 0x95275f80
09-02 19:06:58.436  1044  1540 D wifi    : failed to get capabilities : -3
09-02 19:06:58.436  1044  1540 E WifiScanningService: could not get scan capabilities
09-02 19:06:58.437  1044  1541 D RttService: DefaultState got{ when=-5ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.437  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=122723  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 19:06:58.437  1044  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 19:06:58.438  1044  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 19:06:58.438  1044  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 19:06:58.438  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 19:06:58.438  1044  1521 D LGWifiP2pService: DeviceAddress: 
09-02 19:06:58.438  1044  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 19:06:58.439  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_d,river_cmd COUNTRY CZ
09-02 19:06:58.439  6992  6992 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:06:58.440  6992  6992 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 19:06:58.440  6992  6992 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.440  6992  6992 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.440  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 19:06:58.441  1927  1927 D WfdsService: WifiP2pState is changed : true
,09-02 19:06:58.441  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 19:06:58.441  1927  7004 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:06:58.441  1927  7004 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:06:58.442  1927  2296 D WfdsService: Receive the WFDS_ENABLE Method
09-02 19:06:58.442  1927  2296 D WfdsService: Set the WFDS Monitor: true
09-02 19:06:58.442  1044  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 19:06:58.442  1927  2296 D WfdsService: Connected to the supplicant for wfds
09-02 19:06:58.442  1927  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 19:06:58.442  6992  6992 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 19:06:58.442  1927  2296 D WfdsService: selectPreferredScanChannel [36]
09-02 19:06:58.442  1927  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-02 19:06:58.442  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 19:06:58.442  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:06:58.442  1044  7002 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:06:58.443  1044  7002 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:06:58.443  1044  7002 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:06:58.443  1044  7002 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.443  1044  7002 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.443  1044  7002 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.443  1044  7002 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:06:58.443  1044  7002 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.443  1044  7002 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.443  1044  7002 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.443  1044  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 19:06:58.443  1927  1927 D WfdsService: isConnected: false
09-02 19:06:58.443  1044  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 19:06:58.444  1044  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 19:06:58.444  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 19:06:58.444  1044  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 19:06:58.444  1044  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 19:06:58.444  1044  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 19:06:58.444  1044  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 19:06:58.445  1044  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-02 19:06:58.445  1044  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 19:06:58.448  6838  7007 V FormManager: Network unavailable.
09-02 19:06:58.450  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:58.450  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:58.451  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:58.452  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Globa,l, returning read-only value.
09-02 19:06:58.452  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.452  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-02 19:06:58.455  1044  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-02 19:06:58.455  1044  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-02 19:06:58.455  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 19:06:58.455  6992  6992 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 19:06:58.455  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 19:06:58.455  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 19:06:58.455  1044  7002 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 19:06:58.455  1044  7002 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 19:06:58.456  1044  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 19:06:58.456  1044  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-02 19:06:58.457  1044  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 19:06:58.457  1044  1523 D WifiNative-wlan0: doBoolean: SCAN
09-02 19:06:58.458  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 19:06:58.458  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 19:06:58.458  1927  1927 D WfdsService: Update P2p Interface State: 3
09-02 19:06:58.459  1044  1523 D WifiNative-wlan0: SCAN: returned false
09-02 19:06:58.459  1044  1521 D LGWifiP2pService: InactiveState
09-02 19:06:58.459  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=122745  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 19:06:58.459  1044  1521 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.459  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.459  1044  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 19:06:58.460  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 19:06:58.461  6992  6992 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:06:58.461  1044  7002 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 19:06:58.461  1044  7002 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:06:58.461  1044  7002 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:06:58.461  1044  7002 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:06:58.461  6992  6992 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 19:06:58.461  6992  6992 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.462  1044  7002 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:06:58.462  1044  7002 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.462  1044  7002 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.462  1044  7002 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.462  6992  6992 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.462  1044  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 19:06:58.462  1044  1521 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.462  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: InactiveState{ w,hen=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.463  1044  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:58.464  1927  7004 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 19:06:58.464  1927  7004 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:06:58.464  1927  7004 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:06:58.464  1044  7002 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:06:58.464  1044  7002 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.464  1927  2296 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 19:06:58.465  1044  7002 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.465  1044  7002 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:06:58.465  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=122750  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 19:06:58.465  1044  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 19:06:58.466  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.466  1044  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 19:06:58.466  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.466  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 19:06:58.466  1044  1044 E WifiServerServiceExt: No p2p device connected
09-02 19:06:58.466  6838  7007 V FormManager: Network unavailable.
09-02 19:06:58.466  1044  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-02 19:06:58.467  1044  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 19:06:58.467  1044  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 19:06:58.468  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:06:58.468  1044  1044 D WifiServerServiceExt: setSupplicantStateSCANNING
09-02 19:06:58.474  1044  1559 I ActivityManager: Killing 6498:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-02 19:06:58.475  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:58.475  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:58.476  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:58.525  7009  7009 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:06:58.526  7009  7009 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:06:58.528  7009  7009 D PhoneMonitor: Register our PhoneStateListener
09-02 19:06:58.542  1044  1962 W libprocessgroup: failed to open /acct/uid_10061/pid_6498/cgroup.procs: No such file or directory
,09-02 19:06:58.559  7009  7009 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-02 19:06:58.560  7009  7009 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-02 19:06:58.580  7009  7009 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-02 19:06:58.581  7009  7009 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-02 19:06:58.582  7009  7009 D TelephonyAutoProfiling: [parse] Load xml
09-02 19:06:58.589  7009  7009 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,09-02 19:06:58.589  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-02 19:06:58.589  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
,09-02 19:06:58.589  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-02 19:06:58.589  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-02 19:06:58.589  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-02 19:06:58.589  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-02 19:06:58.589  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-02 19:06:58.590  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-02 19:06:58.590  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-02 19:06:58.590  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-02 19:06:58.590  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-02 19:06:58.590  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-02 19:06:58.590  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-02 19:06:58.591  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-02 19:06:58.591  7009  7009 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-02 19:06:58.591  7009  7009 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-02 19:06:58.602  7009  7009 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-02 19:06:58.609  1044  1963 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7030 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:06:58.610  1044  1963 I ActivityManager: Killing 6087:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-02 19:06:58.662  1044  1766 W libprocessgroup: failed to open /acct/uid_10097/pid_6087/cgroup.procs: No such file or directory
,09-02 19:06:58.902  6992  6992 E wpa_supplicant: USIM:  scard_init function
09-02 19:06:58.903  6992  6992 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-02 19:06:58.904  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 19:06:58.904  1044  7002 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 19:06:58.905  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 19:06:58.905  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPS-AP-AVAILABLE 
09-02 19:06:58.905  1044  7002 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 19:06:58.905  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 19:06:58.905  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 19:06:58.906  1044  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-02 19:06:58.906  1044  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-02 19:06:58.911  1044  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-02 19:06:58.911  1044  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-02 19:06:58.911  1044  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-02 19:06:58.927  1044  1962 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7054 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-02 19:06:58.928  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=123214  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 19:06:58.933  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=123219  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 19:06:58.938  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:58.938  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:58.938  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.939  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:58.939  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 19:06:58.940  1044  1962 I ActivityManager: Killing 2156:com.lge.music/u0a34 (adj 15): empty #17
,09-02 19:06:58.941  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:58.976   320  2174 V AudioFlinger: 2156 died, releasing its sessions
09-02 19:06:58.976   320  2174 V AudioFlinger:  pid 1837 @ 0
09-02 19:06:58.976   320  2174 V AudioFlinger:  pid 3432 @ 1
09-02 19:06:58.976   320  2174 V AudioFlinger:  pid 3432 @ 2
,09-02 19:06:59.002  1044  1963 W libprocessgroup: failed to open /acct/uid_10034/pid_2156/cgroup.procs: No such file or directory
,09-02 19:06:59.018  6992  6992 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-02 19:06:59.018  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:06:59.018  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-02 19:06:59.021  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 19:06:59.021  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-02 19:06:59.022  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 19:06:59.022  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 19:06:59.022  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:06:59.022  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 19:06:59.026  6992  6992 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:06:59.026  6992  6992 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 19:06:59.026  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=123312  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-02 19:06:59.028  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=123313  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 19:06:59.029  1044  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123315
09-02 19:06:59.030  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:06:59.034  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:06:59.034  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 19:06:59.034  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 19:06:59.034  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:06:59.034  1044  7002 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:06:59.034  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 19:06:59.034  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 19:06:59.034  1044  7002 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 19:06:59.035  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:06:59.035  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 19:06:59.036  1044  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123316
09-02 19:06:59.036  1044  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123322
09-02 19:06:59.036  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123322
09-02 19:06:59.037  1044  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123322
09-02 19:06:59.037  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123323  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 19:06:59.039  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:59.040  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:59.041  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.041  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.041  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 19:06:59.041  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 19:06:59.046  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=123332  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 19:06:59.048  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.048  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.048  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 19:06:59.049  1044  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:59.050  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:06:59.050  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 19:06:59.050  1044  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:59.051  1044  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:59.051  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:59.051  1044  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:06:59.052  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=123338  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 19:06:59.053  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=123338  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 19:06:59.053  1044  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123339
09-02 19:06:59.054  1044  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123339
09-02 19:06:59.054  1044  1523 D WifiNative-wlan0: doString: [STATUS]
09-02 19:06:59.055  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:06:59.055  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 19:06:59.057  1044  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 19:06:59.059  1044  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-02 19:06:59.063  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:59.063  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:59.064  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.066  1044  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 19:06:59.066  1044  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-02 19:06:59.070  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.071  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.071  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 19:06:59.073  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.073  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.073  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 19:06:59.080  1044  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 19:06:59.080  1044  1529 D ConnectivityService: Got NetworkAgent Messenger
,09-02 19:06:59.080  1044  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:06:59.081  1044  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 19:06:59.081  1044  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 19:06:59.081  1044  1529 D ConnectivityService: NetworkAgent connected
09-02 19:06:59.081  1044  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 19:06:59.081  1044  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 19:06:59.084  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:59.084  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:59.085  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.086  1044  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 19:06:59.086  1044  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:06:59.086  1044  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 19:06:59.086  1044  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 19:06:59.086  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:59.086  1044  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 19:06:59.086  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:59.087  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.090  1044  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 19:06:59.094   316   916 D CommandListener: Setting iface cfg
09-02 19:06:59.142  1044  1060 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7084 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:06:59.144  1044  1060 I ActivityManager: Killing 6606:com.lge.eula/1000 (adj 15): empty #17
,09-02 19:06:59.193  1044  2017 W libprocessgroup: failed to open /acct/uid_1000/pid_6606/cgroup.procs: No such file or directory
,09-02 19:06:59.202  1044  1523 E WifiStateMachine: Start Dhcp Watchdog 2
09-02 19:06:59.202  1044  7078 D DhcpStateMachine: StoppedState
09-02 19:06:59.203  1044  7078 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.203  1044  7078 D DhcpStateMachine: WaitBeforeStartState
09-02 19:06:59.204  1044  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=123489  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:06:59.205  1044  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=123491  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:06:59.207  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=123492  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-02 19:06:59.210  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:06:59.210  1044  1044 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-02 19:06:59.211  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:06:59.211  1044  1044 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-02 19:06:59.213  1044  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=123498  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:06:59.215  1044  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=123500  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:06:59.216  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=123502  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:06:59.219  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77630] from screen [on:0 period:-337763309] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 19:06:59.222  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-337763306] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 19:06:59.222  1044  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-02 19:06:59.228  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 19:06:59.231  1044  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-02 19:06:59.231  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.232  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.232  1044  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.233  1044  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.233  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.234  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.234  1044  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 19:06:59.235  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=163,0,0
09-02 19:06:59.235  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=163,0,0
09-02 19:06:59.235  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 19:06:59.236  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 19:06:59.237  1044  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 19:06:59.237  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 19:06:59.237  1044  1523 D WifiNative-wlan0: SET ps 0: returned true
09-02 19:06:59.237  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 19:06:59.238  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 19:06:59.238  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 19:06:59.238  1044  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 19:06:59.238  1044  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 19:06:59.238  1044  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bd5b861 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.238  1044  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 19:06:59.239  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bd5b861 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.239  1044  7078 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.239  1044  7078 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 19:06:59.240   316   916 D CommandListener: Setting iface cfg
09-02 19:06:59.240   316   916 D CommandListener: Trying to bring up wlan0
09-02 19:06:59.241  1044  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,09-02 19:06:59.243  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:06:59.243  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 19:06:59.244  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 19:06:59.244  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.245  1044  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.245  7084  7084 I art     : Almond Protected OAT
09-02 19:06:59.245  1044  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.246  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.246  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:06:59.247  1044  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 19:06:59.247  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 19:06:59.248  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 19:06:59.248  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 19:06:59.248  1044  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.248  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.249  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 19:06:59.249  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 19:06:59.249  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 19:06:59.250  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 19:06:59.251  1044  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 19:06:59.251  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 19:06:59.266  1044  1523 D WifiNative-wlan0: SET ps 1: returned true
09-02 19:06:59.267  1044  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 19:06:59.268  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 19:06:59.268  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 19:06:59.268  1044  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 19:06:59.269  1044  1529 D ConnectivityService: ignoring duplicate network state non-change
,09-02 19:06:59.273  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:59.273  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:59.274  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.276  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.276  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.276  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 19:06:59.280  1044  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 19:06:59.281  1044  1529 D ConnectivityService: Adding iface wlan0 to network 101
,09-02 19:06:59.286  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.286  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.286  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 19:06:59.289  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 19:06:59.292  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-02 19:06:59.294  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.294  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.294  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 19:06:59.295  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-02 19:06:59.299  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:59.299  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:06:59.302  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.303  1044  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 19:06:59.303  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.303  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:59.303  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 19:06:59.305  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:59.305  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 19:06:59.305  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.310  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:06:59.311  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 19:06:59.311  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 19:06:59.322  1044  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 19:06:59.322  1044  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-02 19:06:59.324  1044  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-02 19:06:59.325   316   916 E Netd    : netlink response contains error (File exists)
09-02 19:06:59.325  7084  7084 D WeatherApplication: removeAccount
09-02 19:06:59.325  1044  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-02 19:06:59.326  1044  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 19:06:59.326  1044  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-02 19:06:59.326  1044  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-02 19:06:59.327  1044  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 19:06:59.327  1044  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 19:06:59.327  1044  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-02 19:06:59.328  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.328  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 19:06:59.328  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.328  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 19:06:59.329  1044  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-02 19:06:59.329  1044  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:06:59.329  1044  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:06:59.330  1044  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 19:06:59.330  1044  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.331  1044  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 19:06:59.331  1044  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-02 19:06:59.331  1044  1529 D ConnectivityService:    accepting network in place of null
09-02 19:06:59.331  1044  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.331  1044  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.331  1044  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:06:59.332   316  7105 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 19:06:59.332  1044  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{tru,e} explicitlySelected{false} } for legacy network type 1
09-02 19:06:59.332  1044  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 19:06:59.333  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 19:06:59.333  1044  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:06:59.333  1044  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 19:06:59.333  1044  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-02 19:06:59.334  1044  1529 D ConnectivityService: validation of new default Network = false
09-02 19:06:59.334  1044  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 19:06:59.334  1044  1529 D DSQN    : enableDataServiceNotify 
09-02 19:06:59.334  1044  1529 D DSQN    : start dsqn bin
,09-02 19:06:59.339  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.340  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 19:06:59.341  1044  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-02 19:06:59.341  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.341  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:06:59.341  1044  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:06:59.342  1588  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 19:06:59.342  7084  7084 D WeatherApplication: Account.length = 0
09-02 19:06:59.342  7084  7084 E WeatherApplication: OPERATOR:OPEN
09-02 19:06:59.337  7106  7106 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:06:59.337  7106  7106 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:06:59.347  7084  7084 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:6:59
,09-02 19:06:59.351  7084  7084 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 19:06:59.351  7084  7084 D Weather.Utils: 2 : All the weather widget is gone.
09-02 19:06:59.352  7084  7084 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 19:06:59.355  7084  7084 D WeatherAncestor: connectivity changed - connection : true
09-02 19:06:59.356  7084  7084 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-02 19:06:59.357  7106  7106 E DSQN    : DSQN ssw
09-02 19:06:59.363  7084  7084 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-02 19:06:59.363  7084  7084 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 19:06:59.363  7084  7084 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-02 19:06:59.377  1044  1044 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 19:06:59.378  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 19:06:59.378  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,09-02 19:06:59.378  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 19:06:59.382  7084  7084 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 19:06:59.382  7084  7084 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:6:59
09-02 19:06:59.429  1044  1926 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7111 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:06:59.430  1044  1926 I ActivityManager: Killing 6629:com.lge.bnr/1000 (adj 15): empty #17
09-02 19:06:59.441  1044  7078 D DhcpStateMachine: DHCPV4 request on wlan0
09-02 19:06:59.442  1044  7078 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 19:06:59.442  1044  7078 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-02 19:06:59.437  7123  7123 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:06:59.437  7123  7123 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:06:59.457  1044  1521 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.457  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:06:59.457  1044  1521 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:06:59.461  1044  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 19:06:59.462  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 19:06:59.462  1044  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 19:06:59.463  1044  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 19:06:59.463  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 19:06:59.464  1044  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 19:06:59.469  7123  7123 I dhcpcd  : version 5.5.6 starting
,09-02 19:06:59.472  7123  7123 E dhcpcd  : get_duid: m
,09-02 19:06:59.472  7123  7123 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 19:06:59.472  7123  7123 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-02 19:06:59.505   316  7105 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-02 19:06:59.512  1044  1963 W libprocessgroup: failed to open /acct/uid_1000/pid_6629/cgroup.procs: No such file or directory
09-02 19:06:59.526  1044  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-02 19:06:59.531  7123  7123 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 19:06:59.532  7123  7123 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 19:06:59.532  7123  7123 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 19:06:59.532  7123  7123 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 19:06:59.532  7123  7123 D dhcpcd  : wlan0: sending REQUEST (xid 0x39e9f5d5), next in 3.11 seconds
09-02 19:06:59.539   316  7105 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-02 19:06:59.547  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 19:06:59.548  1801  7135 I CheckinService: active receiver: enabled
09-02 19:06:59.548  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.549  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.566  7123  7123 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-02 19:06:59.576   316   915 D LGDataListener: argv[0]=dsqncommand
09-02 19:06:59.576   316   915 D LGDataListener: argv[1]=wlan0
09-02 19:06:59.576   316   915 D LGDataListener: argv[2]=1
09-02 19:06:59.576   316   915 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-02 19:06:59.577  1044  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-02 19:06:59.577  1044  1117 D DSQN    : start to monitor internet connection
09-02 19:06:59.580  7123  7123 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 19:06:59.580  7123  7123 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 19:06:59.580  7123  7123 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 19:06:59.581  7123  7123 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 19:06:59.581  7123  7123 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-02 19:06:59.609  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 17:06:59 GMT], X-Android-Received-Millis=[1472836019608], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472836019576]}
09-02 19:06:59.609  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-02 19:06:59.609  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-02 19:06:59.609  1044  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-02 19:06:59.609  1044  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-02 19:06:59.609  1044  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:06:59.609  1044  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:06:59.610  1044  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 19:06:59.610  1044  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-02 19:06:59.610  1044  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-02 19:06:59.610  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.610  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:06:59.611  1044  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:06:59.612  1044  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.612  1588  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 19:06:59.613  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.613  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 19:06:59.613  1044  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:06:59.613  1044  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:06:59.614  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 19:06:59.673  7123  7123 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 19:06:59.673  7123  7123 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-02 19:06:59.673  7123  7123 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-02 19:06:59.700  1801  7135 I CheckinService: Preparing to send checkin request
09-02 19:06:59.701  1801  7135 I EventLogService: Accumulating logs since 1472835953671
,09-02 19:06:59.728  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 19:06:59.729  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.729  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:06:59.750   280   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 19:06:59.750   280   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 19:06:59.750   280   441 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:06:59.750  7111  7146 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-02 19:06:59.752   280   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 19:06:59.752   280   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 19:06:59.752   280   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 19:06:59.755  7111  7146 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-02 19:06:59.756  1801  7135 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-02 19:06:59.760   280   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 19:06:59.760   280   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 19:06:59.760   280   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 19:06:59.762  7111  7152 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-02 19:06:59.766   280   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-02 19:06:59.766   280   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 19:06:59.766   280   441 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 19:06:59.767  7111  7152 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-02 19:06:59.854  1044  1581 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7176 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-02 19:06:59.864   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 10.276ms
09-02 19:06:59.874   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.507ms
,09-02 19:06:59.883   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 8.890ms
,09-02 19:06:59.909  7176  7176 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-02 19:06:59.909  7176  7176 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-02 19:06:59.914  7111  7111 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 19:06:59.922  7111  7111 I LibraryLoader: Loading: webviewchromium
09-02 19:06:59.925  7111  7111 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4221-4224)
,09-02 19:06:59.925  7111  7111 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:06:59.929  7111  7111 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2417fb5a}
09-02 19:06:59.931  7111  7111 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:06:59.931  7111  7111 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 19:06:59.932  7176  7176 I MultiDex: VM with version 2.1.0 has multidex support
09-02 19:06:59.932  7176  7176 I MultiDex: install
09-02 19:06:59.932  7176  7176 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-02 19:06:59.940  7176  7176 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-02 19:06:59.940  7111  7111 I BrowserStartupController: Initializing chromium process, renderers=0
09-02 19:06:59.941  7111  7111 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:06:59.950   320   320 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
,09-02 19:06:59.952  7111  7111 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-02 19:06:59.952  7111  7202 W AudioManagerAndroid: Requires BLUETOOTH permission
09-02 19:06:59.952  7111  7111 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-02 19:06:59.953  7111  7111 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-02 19:06:59.968  7111  7111 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 19:06:59.968  7111  7111 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 19:06:59.968  7111  7111 I Adreno-EGL: Build Date: 12/12/14 금
09-02 19:06:59.968  7111  7111 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 19:06:59.968  7111  7111 I Adreno-EGL: Remote Branch: 
09-02 19:06:59.968  7111  7111 I Adreno-EGL: Local Patches: 
09-02 19:06:59.968  7111  7111 I Adreno-EGL: Reconstruct Branch: 
,09-02 19:07:00.043  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-02 19:07:00.043  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
09-02 19:07:00.043  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-02 19:07:00.043  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
09-02 19:07:00.044  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
09-02 19:07:00.045  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-02 19:07:00.045  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-02 19:07:00.046  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
09-02 19:07:00.049  1044  7078 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-02 19:07:00.052  1044  7078 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 19:07:00.052  1044  7078 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 19:07:00.053  1044  7078 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-02 19:07:00.053  1044  7078 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 19:07:00.053  1044  7078 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 19:07:00.053  1044  7078 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 19:07:00.053  1044  7078 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 19:07:00.053  1044  7078 D DhcpStateMachine: RunningState
09-02 19:07:00.053  7111  7111 I NSApplication: Starting up...
,09-02 19:07:00.116  1044  1766 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7215 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-02 19:07:00.119  1044  1766 I ActivityManager: Killing 6019:com.android.vending/u0a44 (adj 15): empty #17
09-02 19:07:00.212  1044  1871 W libprocessgroup: failed to open /acct/uid_10044/pid_6019/cgroup.procs: No such file or directory
,09-02 19:07:00.261  7215  7215 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 19:07:00.343  1044  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-02 19:07:00.360  7176  7195 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:07:00.360  7176  7195 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:07:00.405  1044  1998 D WifiServiceImplEx: setWifiEnabled: false pid=6536, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 19:07:00.405  1044  1998 D WifiService: setWifiEnabled: false pid=6536, uid=10118
09-02 19:07:00.405  1044  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:07:00.428  1044  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 19:07:00.428  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 19:07:00.428  1044  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 19:07:00.429  1044  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,09-02 19:07:00.429  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 19:07:00.429  1044  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 19:07:00.429  1044  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:07:00.429  1044  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 19:07:00.429  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 19:07:00.430  1044  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 19:07:00.430  1044  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 19:07:00.431  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 19:07:00.431  1044  1044 D Ulp_jni : JNI:system_update. Event-4
09-02 19:07:00.435  1044  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 19:07:00.435  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 19:07:00.435  1044  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.435  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.435  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 19:07:00.435  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 19:07:00.435  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 19:07:00.436  1044  1523 D WifiNative-wlan0: SET ps 1: returned true
09-02 19:07:00.436   316   916 D CommandListener: Clearing all IP addresses on wlan0
09-02 19:07:00.436  1044  7078 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:07:00.458  1044  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:00.458  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:00.458  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:00.459  1044  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:00.459  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:00.459  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:00.459  1044  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 19:07:00.459  1044  1529 D ConnectivityService: ignoring duplicate network state non-change
09-02 19:07:00.459  1044  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-02 19:07:00.460  1044  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.460  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.460  1044  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1da71879
09-02 19:07:00.461  1044  1521 D LGWifiP2pService: P2pDisablingState
09-02 19:07:00.461  1044  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.461  1044  1521 D LGWifiP2pService: p2p socket connection lost
09-02 19:07:00.461  1044  1521 D LGWifiP2pService: P2pDisabledState
09-02 19:07:00.461  1044  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 19:07:00.461  1044  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 19:07:00.462  1044  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.462  1044  1521 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.462  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 19:07:00.462  6992  6992 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 19:07:00.462  1044  1044 D WifiHS20: hidePasspointNotification off =false
09-02 19:07:00.463  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 19:07:00.463  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:00.463  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:00.471  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 19:07:00.474  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 19:07:00.474  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 19:07:00.475  1044  1523 D WifiNative-wlan0: SET ps 1: returned true
09-02 19:07:00.479  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 19:07:00.479  1927  1927 D WfdsService: WifiP2pState is changed : false
09-02 19:07:00.479  1927  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 19:07:00.479  1927  2296 D WfdsService: Set the WFDS Monitor: false
09-02 19:07:00.480  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:00.480  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:00.480  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 19:07:00.480  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
09-02 19:07:00.480  1927  2296 D WfdsService: STATE : WfdsDisabledState - enter
09-02 19:07:00.480  1927  7004 D CtrlSupplicant: Received on exit socket, terminate
09-02 19:07:00.480  1927  7004 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 19:07:00.480  1044  1044 D WifiHS20: hidePasspointNotification off =false
09-02 19:07:00.480  1927  7004 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-02 19:07:00.480  1927  7004 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 19:07:00.480  1927  2299 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 19:07:00.480  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:00.480  1927  2296 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 19:07:00.480  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:00.480  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 19:07:00.481  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 19:07:00.481  1044  1044 D RttService: SCAN_AVAILABLE : 1
09-02 19:07:00.481  1044  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.481  1044  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.486  7234  7234 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-02 19:07:00.495  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:00.496  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:00.496  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:00.509   316   916 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:07:00.509  1044  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 19:07:00.509  1044  1529 D DSQN    : disableDataServiceNotify
09-02 19:07:00.509  1044  1529 D DSQN    : stop dsqn bin
09-02 19:07:00.511  1044  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 19:07:00.513  1044  1044 D WifiHS20: hidePasspointNotification off =false
09-02 19:07:00.513  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:00.513  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:00.513  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 19:07:00.513  1044  1523 D WifiNative-p2p0: TERMINATE: returned true
09-02 19:07:00.514  1044  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 19:07:00.514  1044  1523 E WifiStateMachine: useWiFiOffloading() : false
09-02 19:07:00.514  1044  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 19:07:00.514  1044  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-02 19:07:00.514  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:00.514  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:00.514  1044  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:00.515  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-02 19:07:00.515  1044  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 19:07:00.516  1044  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 19:07:00.516  1044  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 19:07:00.516  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 19:07:00.516  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 19:07:00.516  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:07:00.516  1044  1044 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 19:07:00.516  1044  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:00.516  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 19:07:00.516  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.516  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 19:07:00.516  1588  1588 I StatusBar.NetworkController: mWifiConn,ected = false, mWifiLevel = 0
09-02 19:07:00.516  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:00.516  1044  7077 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 19:07:00.517  1588  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 19:07:00.518  1044  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:00.518  1044  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:00.518  1044  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:00.518  1044  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 19:07:00.518  1044  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 19:07:00.518  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 19:07:00.518  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 19:07:00.518  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 19:07:00.518  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 19:07:00.518  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:00.518  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:00.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:00.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:00.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:00.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:00.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:00.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:00.518  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:00.518  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:00.518  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:00.520  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:00.520  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 19:07:00.520  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 19:07:00.521  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 19:07:00.521  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:00.521  1044  1529 D NetworkManagementServ,ice: Removing idletimer
09-02 19:07:00.521  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:00.521  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:00.521  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:00.521  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:00.521  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:00.521  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:00.521  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:00.521  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:00.521  1044  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:00.521  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:00.521  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:00.521  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 19:07:00.521  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 19:07:00.521  1044  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:00.521  1044  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:00.522  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:00.532  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:00.542  7234  7234 I dex2oat : dex2oat took 55.721ms (threads: 4)
09-02 19:07:00.551  7176  7195 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 19:07:00.551  7176  7195 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 19:07:00.551  7176  7195 I Adreno-EGL: Build Date: 12/12/14 금
09-02 19:07:00.551  7176  7195 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 19:07:00.551  7176  7195 I Adreno-EGL: Remote Branch: 
09-02 19:07:00.551  7176  7195 I Adreno-EGL: Local Patches: 
09-02 19:07:00.551  7176  7195 I Adreno-EGL: Reconstruct Branch: 
,09-02 19:07:00.557  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 19:07:00.558  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:00.558  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:00.561  1044  1963 I art     : Explicit concurrent mark sweep GC freed 105257(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 3.899ms total 202.694ms
,09-02 19:07:00.576  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 19:07:00.577  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:00.578  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:00.623  6992  6992 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-02 19:07:00.623  6992  6992 I wpa_supplicant: monitor socket send errors count : 1
09-02 19:07:00.623  6992  6992 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
09-02 19:07:00.625  1044  7002 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 19:07:00.625  1044  7002 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 19:07:00.652  1044  7078 D DhcpStateMachine: StoppedState
09-02 19:07:00.652  1044  7078 D DhcpStateMachine: StoppedState{ when=-178ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:07:00.654  1044  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-02 19:07:00.655  1044  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-02 19:07:00.663  6992  6992 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 19:07:00.663  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 19:07:00.663  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 19:07:00.664  1044  7002 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 19:07:00.664  1044  1119 D Tethering: InitialState.processMessage what=4
09-02 19:07:00.664  1044  7002 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-02 19:07:00.664  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:07:00.664  1044  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124950
09-02 19:07:00.665  1044  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124951
09-02 19:07:00.666  6992  6992 W wpa_supplicant: USIM:  scard_deinit function
09-02 19:07:00.666  1044  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:00.667  1044  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:00.667  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:07:00.668  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 19:07:00.669  1044  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=124955  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 19:07:00.671  1044  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=124956  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 19:07:00.715  7176  7195 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 19:07:00.715  7176  7195 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 19:07:00.715  7176  7195 I Adreno-EGL: Build Date: 12/12/14 금
09-02 19:07:00.715  7176  7195 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 19:07:00.715  7176  7195 I Adreno-EGL: Remote Branch: 
09-02 19:07:00.715  7176  7195 I Adreno-EGL: Local Patches: 
09-02 19:07:00.715  7176  7195 I Adreno-EGL: Reconstruct Branch: 
,09-02 19:07:00.756  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 19:07:00.758  7176  7195 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 19:07:00.758  7176  7195 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 19:07:00.758  7176  7195 I Adreno-EGL: Build Date: 12/12/14 금
09-02 19:07:00.758  7176  7195 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 19:07:00.758  7176  7195 I Adreno-EGL: Remote Branch: 
09-02 19:07:00.758  7176  7195 I Adreno-EGL: Local Patches: 
09-02 19:07:00.758  7176  7195 I Adreno-EGL: Reconstruct Branch: 
09-02 19:07:00.759  6361  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 19:07:00.775  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:00.784  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 19:07:00.784  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:00.785  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 19:07:00.785  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 19:07:00.786  6926  6926 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 19:07:00.792  6926  6926 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e6eb23
09-02 19:07:00.792  6926  6926 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 19:07:00.792  6926  6926 D AppUp4:CustFacade: isPhone : true
09-02 19:07:00.794  6926  6926 D AppUp4:CustModeStarterReceiver: begin check event
09-02 19:07:00.794  6926  6926 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 19:07:00.797  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:00.798  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 19:07:00.799  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:00.801  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 19:07:00.809  4268  7253 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 19:07:00.810  4268  7254 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:00.810  6973  6973 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 19:07:00.810  4268  7254 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 19:07:00.815  6992  6992 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 19:07:00.820  1044  7002 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 19:07:00.820  1044  7002 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 19:07:00.820  1044  7002 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 19:07:00.821  1044  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 42 0
,09-02 19:07:00.824  1044  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 19:07:00.824  1044  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 19:07:00.824  1044  1523 E WifiStateMachine: useWiFiOffloading() : false
09-02 19:07:00.824  1044  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 19:07:00.824  1927  1927 D WfdsService: Supplicant Connection state is changed : false
09-02 19:07:00.825  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 19:07:00.825  1927  2296 D WfdsService: Set the WFDS Monitor: false
09-02 19:07:00.825  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
09-02 19:07:00.826  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 19:07:00.827  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 19:07:00.828  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:00.828  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:00.828  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:00.828  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:00.828  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:00.828  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:00.828  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:00.828  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:00.828  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:00.828  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:00.828  1044  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 19:07:00.829  1044  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 19:07:00.829  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:00.829  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:00.829  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:00.829  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:00.829  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:00.829  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:00.829  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:00.829  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:00.829  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:00.829  2493  2493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:00.836  6973  7257 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:00.842   316  7263 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-02 19:07:00.842  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 19:07:00.842  1801  7135 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-02 19:07:00.843  3432  3432 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 19:07:00.843  3432  3432 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:00.843  3432  3432 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 19:07:00.845  6838  7259 W FormManager: Network not available. Please check & try again.
09-02 19:07:00.846  7009  7009 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 19:07:00.847  7009  7009 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 19:07:00.856  6838  7260 V FormManager: Network unavailable.
,09-02 19:07:00.857  7084  7084 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:7:0
,09-02 19:07:00.858  6838  7260 V FormManager: Network unavailable.
09-02 19:07:00.859  7084  7084 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 19:07:00.859  7084  7084 D Weather.Utils: 2 : All the weather widget is gone.
09-02 19:07:00.859  7084  7084 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 19:07:00.859  7084  7084 D WeatherAncestor: connectivity changed - connection : true
09-02 19:07:00.859  7084  7084 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@122b95d9
09-02 19:07:00.861  7084  7084 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 19:07:00.861  7084  7084 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 19:07:00.861  7084  7084 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 19:07:00.861  7084  7084 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 19:07:00.861  7084  7084 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:7:0
09-02 19:07:00.867  1801  7135 I CheckinService: active receiver: disabled
,09-02 19:07:00.900  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 19:07:00.900  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 19:07:00.900  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 19:07:00.901  6731  6731 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 19:07:00.901  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-02 19:07:00.902  6731  6731 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 19:07:00.902  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 19:07:00.902  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 19:07:00.902  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 19:07:00.902  6731  6731 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 19:07:00.902  6731  6731 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 19:07:00.908  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:07:00.910  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:00.913  6838  7266 W FormManager: Network not available. Please check & try again.
09-02 19:07:00.915  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:00.915  6838  7267 V FormManager: Network unavailable.
09-02 19:07:00.919  6838  7267 V FormManager: Network unavailable.
09-02 19:07:00.931  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 19:07:00.934  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 19:07:00.934  6838  7269 W FormManager: Network not available. Please check & try again.
09-02 19:07:00.937  6838  7270 V FormManager: Network unavailable.
09-02 19:07:00.939  6838  7270 V FormManager: Network unavailable.
09-02 19:07:00.941  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 19:07:00.951  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 19:07:00.951  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 19:07:00.953  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 19:07:00.955  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:00.958  4268  7271 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 19:07:00.960  4268  7272 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 19:07:00.960  4268  7272 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 19:07:01.021  1044  1581 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7273 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 19:07:01.153  7273  7273 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 19:07:01.154  7273  7273 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-02 19:07:01.163  7273  7273 V [BNRBootReceiver]: Boot Receiver Return
09-02 19:07:01.167  7273  7273 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-02 19:07:01.168  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:01.174  1044  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=828790802, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
09-02 19:07:01.178  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.186  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.203  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.204  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 19:07:01.215  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 19:07:01.216  2583  2583 D [Concierge]Service: onStartCommand(). Type : 9
09-02 19:07:01.220  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:01.246  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.256  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.267  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.268  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:01.269  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 19:07:01.273  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-02 19:07:01.277  6731  6731 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-02 19:07:01.280  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:01.287  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.294  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.302  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 19:07:01.302  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:01.303  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 19:07:01.307  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:01.317  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.324  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.337  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.338  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:01.339  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:01.346  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:01.366  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.375  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.385  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.386  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:01.387  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:01.392  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:01.401  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.409  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.421  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.422  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:01.423  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:01.429  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:01.445  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.462  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.484  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.485  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:01.486  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:01.504  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:01.525  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.532  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 19:07:01.539  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.540  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 19:07:01.544  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 19:07:01.550  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:01.562  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.569  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 19:07:01.579  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.579  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:01.581  6801  6801 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:01.591  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:01.598  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 19:07:01.612  1044  1528 D WifiService: New client listening to asynchronous messages
,09-02 19:07:01.613  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 19:07:01.621  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.632  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.647  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.648  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:01.650  6801  6801 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 19:07:01.652  6801  6801 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-02 19:07:01.654  6801  6801 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-02 19:07:01.663  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:01.679  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 19:07:01.684  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 19:07:01.693  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 19:07:01.695  6652  6921 D UEI.SmartControl: Internal timer expired: 2
09-02 19:07:01.695  6652  6921 D UEI.SmartControl: unbind internal service
,09-02 19:07:01.708  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.725  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.726  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 19:07:01.728  6801  6801 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 19:07:01.730  6801  6801 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 19:07:01.731  6801  6801 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 19:07:01.738  1044  1962 I ActivityManager: Killing 6771:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-02 19:07:01.744  6652  6915 D serial_port: close(fd = 24)
,09-02 19:07:01.749  6652  6915 I UEI.SmartControl: Serial port is closed.
09-02 19:07:01.815  1044  1871 W libprocessgroup: failed to open /acct/uid_10037/pid_6771/cgroup.procs: No such file or directory
,09-02 19:07:01.831  2176  2176 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-02 19:07:01.854  2176  2176 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-02 19:07:01.857  2176  2176 D c       : Getting all permits...
09-02 19:07:01.857  2176  2176 D a       : Opening database...
09-02 19:07:01.865  2176  2176 D a       : Opening database auth.proximity.permit_store...
09-02 19:07:01.866  2176  2176 D a       : Closing database...
09-02 19:07:01.878  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:01.888  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 19:07:01.888  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 19:07:01.888  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:07:01.893  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.902  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.911  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.911  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 19:07:01.915  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 19:07:01.920  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:01.925  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 19:07:01.925  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 19:07:01.925  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 19:07:01.933  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.941  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.949  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.950  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 19:07:01.953  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 19:07:01.958  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:01.963  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 19:07:01.964  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 19:07:01.964  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 19:07:01.970  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:01.978  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:01.986  6801  6801 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:01.986  6801  6801 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 19:07:01.990  6801  6801 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 19:07:01.999  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 19:07:02.006  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:02.015  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 19:07:02.054  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-02 19:07:02.057  6838  7309 W FormManager: Network not available. Please check & try again.
09-02 19:07:02.057  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 19:07:02.059  6838  7310 V FormManager: Network unavailable.
09-02 19:07:02.061  6838  7310 V FormManager: Network unavailable.
09-02 19:07:02.061  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:02.065  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:02.075  4268  7311 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 19:07:02.078  6749  6749 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 19:07:02.078  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 19:07:02.078  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:07:02.080  4268  7317 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 19:07:02.080  4268  7317 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 19:07:02.083  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 19:07:02.090  6838  7322 W FormManager: Network not available. Please check & try again.
09-02 19:07:02.091  6838  7324 V FormManager: Network unavailable.
,09-02 19:07:02.092  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 19:07:02.100  6838  7324 V FormManager: Network unavailable.
09-02 19:07:02.109  2176  2176 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-02 19:07:02.122  6801  6801 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-02 19:07:02.122  6801  6801 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7426
,09-02 19:07:02.123  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=828790802 [*alarm*], flags=0x0
,09-02 19:07:02.232  1044  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 5 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-337760297] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 19:07:02.234  1044  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 5 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-337760294] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-02 19:07:02.335  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:02.342  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:02.345  1044  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 19:07:02.348  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:02.349  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:02.353  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 19:07:02.354  6361  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-02 19:07:02.371  5698  5698 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 19:07:02.374  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 19:07:02.388  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:02.407  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 19:07:02.407  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:02.407  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 19:07:02.407  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-02 19:07:02.409  6926  6926 I AppUp4:CustModeStarterReceiver: onReceive
09-02 19:07:02.413  6926  6926 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e6eb23
09-02 19:07:02.413  6926  6926 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 19:07:02.413  6926  6926 D AppUp4:CustFacade: isPhone : true
09-02 19:07:02.414  6926  6926 D AppUp4:CustModeStarterReceiver: begin check event
09-02 19:07:02.414  6926  6926 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 19:07:02.418  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:02.419  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 19:07:02.421  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 19:07:02.423  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:02.431  6973  6973 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 19:07:02.432  4268  7334 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 19:07:02.435  4268  7335 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:02.436  4268  7335 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 19:07:02.458  3432  3432 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-02 19:07:02.458  3432  3432 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:02.463  6973  7340 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:02.466  3432  3432 I LgeMiscReceiver: networkInfo.isConnected() = true
09-02 19:07:02.467  3432  3432 D PhoneState: setPdpRejectCasuse : false
09-02 19:07:02.471  7009  7009 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 19:07:02.471  7009  7009 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 19:07:02.473  6838  7337 W FormManager: Network not available. Please check & try again.
,09-02 19:07:02.485  7084  7084 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:7:2
09-02 19:07:02.486  7084  7084 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 19:07:02.487  7084  7084 D Weather.Utils: 2 : All the weather widget is gone.
,09-02 19:07:02.488  7084  7084 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 19:07:02.488  6838  7338 V FormManager: Network unavailable.
09-02 19:07:02.488  7084  7084 D WeatherAncestor: connectivity changed - connection : true
09-02 19:07:02.488  7084  7084 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@122b95d9
09-02 19:07:02.489  7084  7084 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 19:07:02.489  7084  7084 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 19:07:02.489  7084  7084 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 19:07:02.489  7084  7084 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 19:07:02.490  7084  7084 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:7:2
09-02 19:07:02.503  6838  7338 V FormManager: Network unavailable.
,09-02 19:07:03.430  1044  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 19:07:03.437  1044  1559 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-02 19:07:03.457  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 19:07:03.458  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 19:07:03.458  1044  1044 D Ulp_jni : JNI:system_update. Event-4
09-02 19:07:03.459  1044  1119 D BluetoothManagerService: Message: 1
09-02 19:07:03.459  1044  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-02 19:07:03.493  1044  1119 D BluetoothManagerService: Message: 20
09-02 19:07:03.493  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2676e246:true
,09-02 19:07:03.497  6881  6881 D BluetoothAdapterState: make
09-02 19:07:03.502  6881  6881 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 19:07:03.502  6881  6881 I bluedroid-qcom: init
09-02 19:07:03.503  6881  7354 I BluetoothAdapterState: Entering OffState
09-02 19:07:03.504  6881  6881 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 19:07:03.504  6881  6881 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 19:07:03.504  6881  6881 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 19:07:03.504  6881  6881 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 19:07:03.504  6881  6881 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 19:07:03.506  6881  6881 I bluedroid-qcom: get_profile_interface socket
09-02 19:07:03.506  6881  6881 I bluedroid-qcom: get_profile_interface map_client
,09-02 19:07:03.510  6881  7358 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 19:07:03.507  7357  7357 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:03.507  7357  7357 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:03.517  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.520  1044  1119 D Tethering: MasterInitialState.processMessage what=3
,09-02 19:07:03.533  7357  7357 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 19:07:03.533  7357  7357 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 19:07:03.533  7357  7357 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-02 19:07:03.536  7357  7357 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-02 19:07:03.538  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.540  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.540  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.542  7357  7357 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 19:07:03.542  7357  7357 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-02 19:07:03.549  1044  1119 D Tethering: MasterInitialState.processMessage what=3
,09-02 19:07:03.558  6881  7358 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 19:07:03.563  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:03.566  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.568  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-02 19:07:03.568  1044  1119 D BluetoothManagerService: Message: 40
09-02 19:07:03.568  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 19:07:03.569  6881  6897 I bluedroid-qcom: config_hci_snoop_log
09-02 19:07:03.571  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 19:07:03.571  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 19:07:03.575  6881  7358 D BluetoothAdapterProperties: Name is: G3
,09-02 19:07:03.579  6881  7354 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 19:07:03.579  6881  7354 D BluetoothAdapterProperties: Setting state to 11
09-02 19:07:03.580  6881  7354 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 19:07:03.586  1044  1119 D BluetoothManagerService: Message: 60
09-02 19:07:03.586  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 19:07:03.586  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,09-02 19:07:03.588  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 19:07:03.591  6881  7354 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 19:07:03.591  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 19:07:03.592  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 19:07:03.593  6361  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 19:07:03.593  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.599  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:03.604  6731  6731 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-02 19:07:03.604  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 19:07:03.605  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.606  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.615  5698  5698 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 19:07:03.619  6881  7354 D BluetoothBondStateMachine: make
,09-02 19:07:03.621  6881  6881 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 19:07:03.622  6881  6881 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:03.622  6881  6881 V BluetoothPbapReceiver: ***********state = 11
09-02 19:07:03.624  6881  7354 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:03.624  6881  7354 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 19:07:03.624  6881  7354 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:03.624  6881  7354 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 19:07:03.625  6881  7354 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 19:07:03.627  6881  7374 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 19:07:03.628  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:07:03.629  6881  7354 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:03.680  1044  1872 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7377 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-02 19:07:03.687  5698  5698 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 19:07:03.687  6881  7354 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:03.689  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.692  6881  6881 D HeadsetService: Received start request. Starting profile...
09-02 19:07:03.694  6881  6881 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 19:07:03.694  6881  6881 D LGBluetoothHfpAdapter: Version 1.6
09-02 19:07:03.695  6881  7354 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 19:07:03.700  6881  7354 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:03.701  6881  6881 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 19:07:03.702  6881  6881 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 19:07:03.703  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.703  6881  6881 D HeadsetStateMachine: make
09-02 19:07:03.705  6881  7354 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:03.712  6881  7354 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 19:07:03.717  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 19:07:03.717  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.717  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:03.718  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 19:07:03.718  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 19:07:03.718  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:03.721  6881  7354 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:03.724  6926  6926 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 19:07:03.729  6926  6926 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e6eb23
09-02 19:07:03.729  6926  6926 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 19:07:03.729  6926  6926 D AppUp4:CustFacade: isPhone : true
09-02 19:07:03.729  6926  6926 D AppUp4:CustModeStarterReceiver: begin check event
09-02 19:07:03.729  6926  6926 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 19:07:03.732  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.732  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 19:07:03.733  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:03.736  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 19:07:03.738  6881  6881 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:07:03.738  6881  6881 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 19:07:03.740  6881  7354 V LGMDMManager: Create singleton instance
09-02 19:07:03.742  6881  7354 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 19:07:03.743  6881  6881 D HeadsetStateMachine: max_hf_connections = 1
09-02 19:07:03.743  6881  6881 I bluedroid-qcom: get_profile_interface handsfree
09-02 19:07:03.745  6973  6973 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 19:07:03.745  4268  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.745  6881  6881 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 19:07:03.746  4268  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 19:07:03.746   320  1371 V AudioPolicyService: registerClient() client 0xb0410620, uid 1002
09-02 19:07:03.746   320  2174 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 19:07:03.746   320  2174 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 19:07:03.746   320  2174 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 19:07:03.746  6881  6881 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 19:07:03.747   320   320 V AudioFlinger: registerClient() client 0xb5581568, pid 6881
,09-02 19:07:03.747   320  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:03.747   320  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:03.747  6881  6881 V ToneGenerator: Create Track: 0xb4928a80
09-02 19:07:03.747  6881  6881 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 19:07:03.747  6881  6881 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 19:07:03.748  3432  3448 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:03.748  3432  3448 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:03.748   320  2175 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 19:07:03.748   320  2175 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 19:07:03.748   320  2175 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 19:07:03.748   320  2175 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 19:07:03.748  6881  6881 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 19:07:03.748  1044  1871 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:03.748  1044  1871 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:03.748  6881  6897 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:03.748  6881  6897 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 19:07:03.748   320  2174 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 19:07:03.748  1588  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:03.748  1588  2084 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:03.749   320  1370 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 19:07:03.749   320  1370 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 19:07:03.749  1837  3939 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:03.749   320  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 19:07:03.749  1837  3939 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:03.749   320  1370 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 19:07:03.749  4268  7395 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 19:07:03.749  6881  6881 V AudioSystem: getLatency() output 2, latency 50
09-02 19:07:03.749  6881  6881 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 19:07:03.749  6881  6881 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 19:07:03.749   320  2175 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 19:07:03.750   320  2175 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 19:07:03.750   320  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:03.750   320  1366 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:03.750  1588  3113 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:03.750  1588  3113 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:03.750  6881  6897 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:03.750  1044  1059 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:03.750  6881  6897 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 19:07:03.750  1044  1059 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:03.751   320  2175 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enabl,e = 0 
09-02 19:07:03.751   320  2175 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 19:07:03.751   320  2175 V AudioFlinger: createTrack() lSessionId: 22
09-02 19:07:03.751  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:03.751  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:03.751  3432  3447 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:03.751  3432  3447 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:03.752  6881  6881 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 19:07:03.752   320  2175 V AudioFlinger: acquiring 22 from 6881, for 6881
09-02 19:07:03.752   320  2175 V AudioFlinger:  added new entry for 22
09-02 19:07:03.752  6881  6881 V ToneGenerator: ToneGenerator INIT OK, time: 128051
09-02 19:07:03.752  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:03.753  6881  7394 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 19:07:03.753  6881  7394 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 19:07:03.753  6881  7394 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 19:07:03.753  6881  7394 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-02 19:07:03.753   320  1371 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6881
09-02 19:07:03.753   320  1371 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 19:07:03.753   320  1371 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 19:07:03.753   320  1371 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 19:07:03.753   320  1371 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 19:07:03.753   320  1371 V voice   : voice_set_parameters: exit with code(0)
09-02 19:07:03.753   320  1371 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 19:07:03.753   320  1371 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 19:07:03.754   320  1371 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 19:07:03.754   320  1371 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 19:07:03.754   320  1371 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 19:07:03.754   320  1371 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 19:07:03.754  6881  7394 V ToneGenerator: ToneGenerator destructor
09-02 19:07:03.754  6881  7394 V ToneGenerator: stopTone
09-02 19:07:03.754  6881  7394 V ToneGenerator: Delete Track: 0xb4928a80
09-02 19:07:03.754  6881  7394 V AudioTrack: ~AudioTrack, releasing session id from 6881 on behalf of 6881
09-02 19:07:03.754   320  2174 V AudioFlinger: releasing 22 from 6881 for 6881
09-02 19:07:03.754   320  2174 V AudioFlinger:  decremented refcount to 0
09-02 19:07:03.754   320  2174 V AudioFlinger: purging stale effects
09-02 19:07:03.754   320  2174 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 19:07:03.754   320  2174 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 19:07:03.755  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:03.756   320  1274 V AudioPolicyService: AudioCommandThread() waking up
09-02 19:07:03.756   320  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 19:07:03.756   320  1274 V AudioPolicyManager: releaseOutput() 2
09-02 19:07:03.756   320  1274 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 19:07:03.756   320  2174 V AudioFlinger: PlaybackThread::Track destructor
09-02 19:07:03.756   320  2174 V AudioFlinger: removeClient_l() pid 6881, calling pid 320
09-02 19:07:03.757  6881  6881 D A2dpService: Received start request. Starting profile...
09-02 19:07:03.757  6881  6881 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 19:07:03.758  6881  6881 V Avrcp   : make
09-02 19:07:03.758  1044  1766 W Process : Unable to open /proc/7397/status
09-02 19:07:03.758  6881  6881 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 19:07:03.758  6881  6881 I bluedroid-qcom: get_profile_interface avrcp
09-02 19:07:03.765  6881  6881 V AudioManager: registerRemoteController: size of Media player list: 0
09-02 19:07:03.767  6881  6881 E AudioManager: No RCC entry present to update
09-02 19:07:03.767  6881  6881 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 19:07:03.769  6881  6881 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 19:07:03.769  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 19:07:03.769  6881  6881 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-02 19:07:03.771  6973  7398 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:03.773  3432  3432 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 19:07:03.774  3432  3432 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.774  3432  3432 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 19:07:03.775  6838  7401 W FormManager: Network not available. Please check & try again.
09-02 19:07:03.775  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 19:07:03.777  7009  7009 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 19:07:03.777  7009  7009 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 19:07:03.821  6838  7402 V FormManager: Network unavailable.
,09-02 19:07:03.830  7377  7377 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-02 19:07:03.830  7377  7377 W LG Account v2.2: No ProfileInfo entries
09-02 19:07:03.830  7377  7377 I LG Account v2.2: isEnabled: false
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Country: EU
,09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Operator: OPEN
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Ranking support: false
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Comfort support: false
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Accessory: true
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Health device: true
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Extra Pedometer: false
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Blood glucose device: false
09-02 19:07:03.831  7377  7377 I Feature : [Lifetracker]Device Number: 3
09-02 19:07:03.845  7084  7084 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:7:3
,09-02 19:07:03.848  6838  7402 V FormManager: Network unavailable.
,09-02 19:07:03.849  7084  7084 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 19:07:03.849  7084  7084 D Weather.Utils: 2 : All the weather widget is gone.
09-02 19:07:03.850  7084  7084 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 19:07:03.850  7084  7084 D WeatherAncestor: connectivity changed - connection : true
09-02 19:07:03.850  7084  7084 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@122b95d9
09-02 19:07:03.852  7084  7084 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 19:07:03.852  7084  7084 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 19:07:03.852  7084  7084 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 19:07:03.852  7084  7084 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 19:07:03.852  7084  7084 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:7:3
09-02 19:07:03.854  6731  6731 D BluetoothPermissionRequest: onReceive
09-02 19:07:03.868  6731  6731 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-02 19:07:03.873  1044  1872 V SIM_STK : Menu title from STK is T-Mobile
09-02 19:07:03.873  1044  1872 V SIM_STK : Menu title from STK is T-Mobile
09-02 19:07:03.889  6361  6361 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 19:07:03.896  6361  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 19:07:03.912  2176  2176 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:03.922  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 19:07:03.922  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.923  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 19:07:03.923  6926  6926 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 19:07:03.925  6926  6926 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 19:07:03.929  6926  6926 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e6eb23
09-02 19:07:03.929  6926  6926 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 19:07:03.929  6926  6926 D AppUp4:CustFacade: isPhone : true
09-02 19:07:03.930  6926  6926 D AppUp4:CustModeStarterReceiver: begin check event
09-02 19:07:03.930  6926  6926 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 19:07:03.936  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.936  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 19:07:03.941  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 19:07:03.943  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:03.951  6973  6973 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 19:07:03.952  4268  7408 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 19:07:03.961  4268  7409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:03.964  4268  7409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 19:07:03.971  1044  1963 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-02 19:07:03.976  6973  7410 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:03.979  3432  3432 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 19:07:03.979  3432  3432 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:03.979  3432  3432 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 19:07:03.980  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 19:07:03.984  7009  7009 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 19:07:03.984  7009  7009 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-02 19:07:03.986  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 19:07:03.987  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 19:07:03.988  6881  6881 I BluetoothA2dpServiceJni: classInitNative
09-02 19:07:03.988  6881  6881 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 19:07:03.988  6881  6881 D A2dpStateMachine: make
09-02 19:07:03.990  6881  6881 I bluedroid-qcom: get_profile_interface a2dp
09-02 19:07:03.990  6881  7416 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 19:07:03.992  6881  6881 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 19:07:03.992  6881  6881 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 19:07:03.993  6838  7413 W FormManager: Network not available. Please check & try again.
09-02 19:07:03.993  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:03.994  6881  6881 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 19:07:03.997  6881  7415 D A2dpStateMachine: Enter Disconnected: -2
09-02 19:07:03.997  6881  6881 D HidService: Received start request. Starting profile...
,09-02 19:07:03.997  6881  6881 I bluedroid-qcom: get_profile_interface hidhost
09-02 19:07:03.997  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:03.998  6881  6881 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 19:07:04.000  6881  6881 D HealthService: Received start request. Starting profile...
09-02 19:07:04.000  6838  7414 V FormManager: Network unavailable.
09-02 19:07:04.002  6881  6881 I bluedroid-qcom: get_profile_interface health
09-02 19:07:04.002  6881  6881 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 19:07:04.002  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:04.003  6881  6881 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 19:07:04.005  6881  6881 D PanService: Received start request. Starting profile...
09-02 19:07:04.005  6838  7414 V FormManager: Network unavailable.
,09-02 19:07:04.005  6881  6881 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 19:07:04.005  6881  6881 I bluedroid-qcom: get_profile_interface pan
09-02 19:07:04.005  7084  7084 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:7:4
09-02 19:07:04.007  7084  7084 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 19:07:04.007  7084  7084 D Weather.Utils: 2 : All the weather widget is gone.
09-02 19:07:04.007  7084  7084 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 19:07:04.007  7084  7084 D WeatherAncestor: connectivity changed - connection : true
09-02 19:07:04.007  7084  7084 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@122b95d9
09-02 19:07:04.008  7084  7084 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 19:07:04.008  7084  7084 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 19:07:04.008  7084  7084 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,09-02 19:07:04.010  7084  7084 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 19:07:04.011  7084  7084 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:7:4
09-02 19:07:04.017  6881  6881 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 19:07:04.017  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:04.018  6881  6881 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-02 19:07:04.023  6881  6881 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:07:04.023  6881  6881 D BtGatt.GattService: Received start request. Starting profile...
09-02 19:07:04.024  6881  6881 D BtGatt.GattService: start()
09-02 19:07:04.024  6881  6881 I bluedroid-qcom: get_profile_interface gatt
09-02 19:07:04.024  6881  6881 D BtGatt.AdvertiseManager: advertise manager created
09-02 19:07:04.030  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:04.031  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:04.032  6881  6881 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 19:07:04.033  6881  6881 V BluetoothMapService: BluetoothMapBinder()
09-02 19:07:04.033  6881  6881 D BluetoothMapService: Received start request. Starting profile...
09-02 19:07:04.033  6881  6881 D BluetoothMapService: start()
09-02 19:07:04.036  6881  6881 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-02 19:07:04.036  6881  6881 D BluetoothMapEmailAppObserver: createReceiver()
,09-02 19:07:04.037  6881  6881 D BluetoothMapEmailAppObserver: initObservers()
09-02 19:07:04.037  6881  6881 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-02 19:07:04.047  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:04.047  6881  6881 D HeadsetStateMachine: Proxy object connected
,09-02 19:07:04.048  6881  6881 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 19:07:04.048  6881  6881 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 19:07:04.052  6881  6881 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 19:07:04.053  6881  7394 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 19:07:04.054  6881  7394 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 19:07:04.054  6881  7394 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 19:07:04.056  6881  6881 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 19:07:04.059  6881  6881 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 19:07:04.063  6881  6881 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 19:07:04.063  6881  6881 V PanService: [BTUI] SIM Extra State :ABSENT
09-02 19:07:04.067  6881  6881 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 19:07:04.070  6881  6881 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 19:07:04.070  6881  6881 V BluetoothMapService: Handler(): got msg=1
09-02 19:07:04.071  6881  7354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-02 19:07:04.071  6881  7354 I bluedroid-qcom: enable
09-02 19:07:04.071  6881  7423 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 19:07:04.071  6881  7423 I bt-btu  : btu_task pending for preload complete event
,09-02 19:07:04.073  6881  7354 I bt_hci_bdroid: init
,09-02 19:07:04.073  6881  6881 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:04.074  6881  7354 I bt_vendor: bt-vendor : init
09-02 19:07:04.074  6881  7354 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 19:07:04.074  6881  7354 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 19:07:04.074  6881  7354 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 19:07:04.074  6881  7354 D bt_userial_mct: userial_init
09-02 19:07:04.075  6881  7354 D bt_hci_bdroid: set_power 1
09-02 19:07:04.075  6881  7354 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 19:07:04.075  6881  7354 I bt_vendor: Starting hciattach daemon
09-02 19:07:04.075  6881  7354 I bt_vendor: try to set true
09-02 19:07:04.076  6881  6881 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 19:07:04.076  6881  6881 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 19:07:04.076  6881  6881 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 19:07:04.076  6881  6881 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:04.076  6881  6881 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-02 19:07:04.067  7426  7426 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:04.067  7426  7426 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:04.118  7427  7427 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-02 19:07:04.216  7433  7433 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 19:07:04.230  7434  7434 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-02 19:07:04.258  7436  7436 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 19:07:04.270  7437  7437 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-02 19:07:04.284  7438  7438 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 19:07:04.299  7442  7442 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-02 19:07:04.331  7444  7444 I libmdmdetect: ESOC framework not supported
09-02 19:07:04.332  7444  7444 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 19:07:04.344  7444  7444 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-02 19:07:04.345  7444  7444 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 19:07:04.345  7444  7444 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 19:07:04.345  7444  7444 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 19:07:04.345  7444  7444 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-02 19:07:04.345  7444  7444 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 19:07:04.345  7444  7444 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-02 19:07:04.388  7444  7445 E QC-QMI  : qmi_client [7444] 14: failed to locate client data
09-02 19:07:04.389   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-02 19:07:04.389   479   479 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-02 19:07:04.433  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7359
,09-02 19:07:04.437  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7362
09-02 19:07:04.437  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7364
09-02 19:07:04.438  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7365
09-02 19:07:04.438  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7371
09-02 19:07:04.439  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7376
09-02 19:07:04.453  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7443
09-02 19:07:04.454  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7444
09-02 19:07:04.454  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7446
,09-02 19:07:04.464  7452  7452 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 19:07:04.475  7453  7453 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 19:07:04.530  6881  7354 I bt_vendor: bluetooth satus is on
,09-02 19:07:04.530  6881  7354 D bt_hci_bdroid: preload
,09-02 19:07:04.533  6881  7425 D bt_userial_mct: userial_open(port:0)
09-02 19:07:04.533  6881  7425 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-02 19:07:04.537  6881  7425 I bt_vendor: Done intiailizing UART
09-02 19:07:04.538  6881  7425 I bt_vendor: Done intiailizing UART
09-02 19:07:04.538  6881  7425 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 19:07:04.539  6881  7425 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 19:07:04.539  6881  7423 I bt-btu  : btu_task received preload complete event
09-02 19:07:04.539  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 19:07:04.539  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 19:07:04.541  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-02 19:07:04.544  6881  7455 D bt_userial_mct: Entering userial_read_thread()
,09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 19:07:04.548  6881  7423 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 19:07:04.595  6881  7423 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-02 19:07:04.595  6881  7423 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0189061 
09-02 19:07:04.595  6881  7423 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0189061 
,09-02 19:07:04.624  6881  7358 E bt-btif : Calling BTA_HhEnable
09-02 19:07:04.624  6881  7358 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-02 19:07:04.624  6881  7358 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 19:07:04.628  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-02 19:07:04.628  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 19:07:04.628  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-02 19:07:04.629  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 19:07:04.629  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 19:07:04.631  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 19:07:04.632  6881  7358 D BluetoothAdapterProperties: Name is: G3
09-02 19:07:04.635  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 19:07:04.635  6881  7358 D BluetoothAdapterProperties: Scan Mode:20
09-02 19:07:04.636  6881  7358 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:07:04.636  6881  7358 D bt_hci_bdroid: postload
09-02 19:07:04.638  6881  7425 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 19:07:04.643  6881  7425 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 19:07:04.644  6881  7423 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 19:07:04.644  6881  7358 D bte_conf: Device ID record 1 : primary
09-02 19:07:04.644  6881  7358 D bte_conf:   vendorId            = 00c4
09-02 19:07:04.644  6881  7358 D bte_conf:   vendorIdSource      = 0001
09-02 19:07:04.644  6881  7358 D bte_conf:   product             = 13a1
09-02 19:07:04.644  6881  7358 D bte_conf:   version             = 1000
09-02 19:07:04.644  6881  7358 D bte_conf:   clientExecutableURL = 
09-02 19:07:04.644  6881  7358 D bte_conf:   serviceDescription  = 
09-02 19:07:04.644  6881  7358 D bte_conf:   documentationURL    = 
09-02 19:07:04.644  6881  7358 D bte_conf: bte_load_did_conf no section named DID2.
09-02 19:07:04.647  6881  7425 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 19:07:04.652  6881  7354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-02 19:07:04.658  6881  7354 D BluetoothAdapterProperties: ScanMode =  20
09-02 19:07:04.658  6881  7354 D BluetoothAdapterProperties: State =  11
09-02 19:07:04.659  6881  7354 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 19:07:04.661  6881  7354 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 19:07:04.657  7457  7457 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:04.663  6881  7354 D BluetoothAdapterProperties: Setting state to 12
09-02 19:07:04.663  6881  7354 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 19:07:04.664  6881  7358 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 19:07:04.664  6881  7358 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 19:07:04.657  7457  7457 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 19:07:04.671  6881  7354 I BluetoothAdapterState: Entering On State
09-02 19:07:04.679  1044  1119 D BluetoothManagerService: Message: 60
09-02 19:07:04.679  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 19:07:04.679  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-02 19:07:04.679  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 19:07:04.686  6881  7423 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 19:07:04.686  6881  7423 W bt-smp  : Plain text(LSB ~ MSB) = 2d ee 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 19:07:04.686  6881  7423 W bt-smp  : Encrypted text(LSB ~ MSB) = 1c 4d b1 bd 18 4b aa 8f f6 c9 56 22 98 d1 67 13 
09-02 19:07:04.686  6881  7425 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 19:07:04.686  6881  7423 W bt-btm  : Stopping oneshot timer
09-02 19:07:04.686  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:04.689  6881  7455 E bt_mct  : hci lib postload completed
09-02 19:07:04.695  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:04.695  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:04.695  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:04.695  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:04.695  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:04.695  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:04.695  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:04.695  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:04.714  6881  7358 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:07:04.715  6881  7358 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-02 19:07:04.717  6881  7423 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 19:07:04.717  6881  7423 W bt-smp  : Plain text(LSB ~ MSB) = bf d6 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 19:07:04.717  6881  7423 W bt-smp  : Encrypted text(LSB ~ MSB) = d6 e1 90 c3 d3 a4 63 cd 72 a2 93 3f 03 be 91 d7 
09-02 19:07:04.721  6881  7423 W bt-btm  : Stopping oneshot timer
09-02 19:07:04.723  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:04.732  6881  7354 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 19:07:04.732  6881  7354 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-02 19:07:04.732  6881  7354 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-02 19:07:04.741  6881  7354 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 19:07:04.741  6881  7354 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-02 19:07:04.742  6881  7423 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 19:07:04.742  6881  7423 W bt-smp  : Plain text(LSB ~ MSB) = a2 63 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 19:07:04.742  6881  7423 W bt-smp  : Encrypted text(LSB ~ MSB) = 6f cf 78 ca c6 54 65 d1 08 64 f2 a0 0a 52 43 8f 
09-02 19:07:04.742  6881  7423 W bt-btm  : Stopping oneshot timer
09-02 19:07:04.742  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:07:04.749  1044  1044 D BluetoothHeadset: Proxy object connected
,09-02 19:07:04.754  1044  1044 D BluetoothA2dp: Proxy object connected
09-02 19:07:04.759  6731  6747 D BluetoothPan: onBluetoothStateChange on: true
09-02 19:07:04.759  6731  6747 D BluetoothPan: onBluetoothStateChange call bindService
09-02 19:07:04.769  6881  7423 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 19:07:04.769  6881  7423 W bt-smp  : Plain text(LSB ~ MSB) = 20 9c 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 19:07:04.769  6881  7423 W bt-smp  : Encrypted text(LSB ~ MSB) = f6 0e ab 4a 58 e5 ab f5 78 c3 80 b8 95 60 fc e1 
09-02 19:07:04.769  6881  7423 W bt-btm  : Stopping oneshot timer
,09-02 19:07:04.783  6731  6748 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 19:07:04.795  6731  6747 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 19:07:04.800  6731  6731 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:07:04.800  6731  6731 D PanProfile: Bluetooth service connected
,09-02 19:07:04.801  6881  7423 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 19:07:04.801  6881  7423 W bt-smp  : Plain text(LSB ~ MSB) = ca 7f 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 19:07:04.801  6881  7423 W bt-smp  : Encrypted text(LSB ~ MSB) = 37 2e 80 55 41 0e 85 75 17 a8 64 bf 31 45 d5 7a 
09-02 19:07:04.801  6881  7423 W bt-btm  : Stopping oneshot timer
09-02 19:07:04.804  6731  6731 D BluetoothInputDevice: Proxy object connected
09-02 19:07:04.804  6731  6731 D HidProfile: Bluetooth service connected
09-02 19:07:04.804  6731  6748 D BluetoothMap: onBluetoothStateChange: up=true
09-02 19:07:04.807  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:04.810  1837  1837 D BluetoothHeadset: Proxy object connected
09-02 19:07:04.810  1837  2557 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:04.811  6731  6731 D BluetoothMap: Proxy object connected
09-02 19:07:04.811  6731  6731 D MapProfile: Bluetooth service connected
09-02 19:07:04.811  6731  6731 D BluetoothMap: getConnectedDevices()
09-02 19:07:04.812  7478  7478 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-02 19:07:04.813  1837  1837 D BluetoothHeadset: Proxy object connected
,09-02 19:07:04.814  1837  2556 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:04.816  6881  6896 V BluetoothMapService: getConnectedDevices()
09-02 19:07:04.816  1837  1837 D BluetoothHeadset: Proxy object connected
09-02 19:07:04.817  1044  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 19:07:04.817  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-02 19:07:04.819  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 19:07:04.820  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:04.820  1927  2104 D LGBluetoothAPIService: Message: 1
09-02 19:07:04.820  1927  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 19:07:04.821  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 19:07:04.824  1044  1119 D BluetoothManagerService: Message: 40
09-02 19:07:04.824  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,09-02 19:07:04.828  6536  6536 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 19:07:04.835  1927  2104 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-02 19:07:04.837  6881  6881 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:04.837  6881  6881 D BluetoothMapService: STATE_ON
09-02 19:07:04.837  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:04.837  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:04.837  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:04.837  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:04.837  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:04.837  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:04.837  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:04.837  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:04.837  6731  6731 D LocalBluetoothProfileManager: Adding local A2DP profile
09-02 19:07:04.838  6881  6881 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 19:07:04.839  6881  6881 D LGBluetoothAPIServer: [BTUI] onBind()
,09-02 19:07:04.841  1044  1119 D BluetoothManagerService: Message: 30
09-02 19:07:04.842  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:04.844  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:04.845  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 19:07:04.845  1927  2104 D LGBluetoothAPIService: Message: 100
09-02 19:07:04.845  1927  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 19:07:04.847  6731  6731 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-02 19:07:04.851  1044  1119 D BluetoothManagerService: Message: 30
09-02 19:07:04.853  7111  7149 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-02 19:07:04.857  6731  6731 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 19:07:04.858  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:04.858  6881  6881 V BluetoothPbapService: Pbap Service onCreate
09-02 19:07:04.858  6881  6881 V BluetoothPbapService: Starting PBAP service
09-02 19:07:04.859  6881  6881 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 19:07:04.860  6881  6881 V BluetoothMapService: Handler(): got msg=1
09-02 19:07:04.860  6881  6881 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 19:07:04.860  6731  6731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 19:07:04.861  6881  6881 V BluetoothPbapService: Pbap Service onBind
09-02 19:07:04.862  6881  7486 D BluetoothMapMasInstance: MAS initSocket()
09-02 19:07:04.862  6881  7486 D BluetoothMapMasInstance:   masId = 00
09-02 19:07:04.862  6881  7486 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 19:07:04.862  6881  7486 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 19:07:04.862  6881  7486 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 19:07:04.863  6881  6881 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:04.864  6881  6881 V BluetoothPbapService: state: 12
09-02 19:07:04.864  1044  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 19:07:04.866  6881  6881 V BluetoothPbapService: Handler(): got msg=1
09-02 19:07:04.867  6731  6731 D BluetoothA2dp: Proxy object connected
09-02 19:07:04.868  6731  6731 D A2dpProfile: Bluetooth service connected
09-02 19:07:04.868  6881  6881 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 19:07:04.869  6881  6881 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 19:07:04.869  6881  6881 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:04.869  6881  6881 V BluetoothPbapReceiver: ***********state = 12
09-02 19:07:04.869  6881  7487 V BluetoothPbapService: Pbap Service initSocket
09-02 19:07:04.870  6731  6731 D BluetoothHeadset: Proxy object connected
09-02 19:07:04.870  6881  7486 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:07:04.870  1044  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:04.872  6881  7487 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:07:04.872  6731  6731 D HeadsetProfile: Bluetooth service connected
09-02 19:07:04.872  6881  7358 D BluetoothAdapterProperties: Scan Mode:21
09-02 19:07:04.873  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:07:04.874  2176  2176 D c       : Getting all permits...
09-02 19:07:04.874  2176  2176 D a       : Opening database...
09-02 19:07:04.875  6881  7358 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 19:07:04.875  6881  7487 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
09-02 19:07:04.875  6881  7486 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 19:07:04.875  6881  7486 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 19:07:04.875  6881  7487 V BluetoothPbapService: Succeed to create listening socket 
09-02 19:07:04.875  6881  7486 D BluetoothMapMasInstance: Accepting socket connection...
09-02 19:07:04.876  6881  7487 V BluetoothPbapService: Accepting socket connection...
09-02 19:07:04.877  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:04.877  2176  2176 D a       : Opening database auth.proximity.permit_store...
,09-02 19:07:04.878  2176  2176 D a       : Closing database...
09-02 19:07:04.880  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:04.885  6731  6731 D BluetoothPbap: Proxy object connected
09-02 19:07:04.885  6731  6731 D PbapServerProfile: Bluetooth service connected
09-02 19:07:04.888  6731  6731 D DockEventReceiver: finishStartingService: stopping service
09-02 19:07:04.892  6731  6731 D BluetoothPermissionRequest: onReceive
,09-02 19:07:04.894  6731  6731 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 19:07:04.895  6731  6731 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 19:07:04.898  6881  6881 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 19:07:04.899  6881  6881 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 19:07:04.905  6881  6881 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-02 19:07:04.922  6881  6881 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-02 19:07:04.923  6881  6881 V BtOppService: onCreate
,09-02 19:07:04.928  6881  6881 V BluetoothOppNotification: send message
09-02 19:07:04.931  6881  6881 V BtOppService: Starting RfcommListener
09-02 19:07:04.937  6881  6881 D BluetoothOppPreference: Dumping Names:  
09-02 19:07:04.937  6881  6881 D BluetoothOppPreference: {}
09-02 19:07:04.937  6881  6881 D BluetoothOppPreference: Dumping Channels:  
09-02 19:07:04.937  6881  6881 D BluetoothOppPreference: {}
,09-02 19:07:04.941  6881  6881 V BtOppService: onStartCommand
09-02 19:07:04.942  6881  7494 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 19:07:04.947  6881  6881 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:04.948  6881  6881 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 19:07:04.951  6881  7491 V BtOppService: Deleted complete outbound shares, number =  0
,09-02 19:07:04.951  6881  7494 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 19:07:04.954  6881  6881 V BluetoothOppNotification: new notify threadi!
09-02 19:07:04.954  6881  7491 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 19:07:04.955  6881  7491 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-02 19:07:04.955  6881  7494 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c102eba on behalf of 
09-02 19:07:04.956  6881  6881 V BluetoothOppNotification: send delay message
09-02 19:07:04.956  6881  7494 V BluetoothOppNotification: update too frequent, put in queue
09-02 19:07:04.957  6881  7491 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1efcc16b on behalf of 
09-02 19:07:04.957  6881  6881 V BtOppService: start RfcommListener
09-02 19:07:04.959  6881  7495 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 19:07:04.961  6881  7494 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 19:07:04.961  6881  7494 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 19:07:04.963  6881  7495 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@384f24c8 on behalf of 
09-02 19:07:04.963  6881  7494 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1197c961 on behalf of 
,09-02 19:07:04.965  6881  7495 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 19:07:04.965  6881  6881 V BtOppService: RfcommListener started
09-02 19:07:04.966  6881  6881 V BtOppService: ContentObserver received notification
09-02 19:07:04.967  6881  7496 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 19:07:04.967  1044  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:04.968  6881  7494 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,09-02 19:07:04.968  6881  7494 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 19:07:04.968  6881  7496 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:07:04.969  6881  7495 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 19:07:04.969  6881  7496 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=73
09-02 19:07:04.969  6881  7496 V BtOppRfcommListener: Started RFCOMM listener....
09-02 19:07:04.970  6881  7496 I BtOppRfcommListener: Accept thread started.
09-02 19:07:04.970  6881  7496 V BtOppRfcommListener: Accepting connection...
09-02 19:07:04.971  6881  7494 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f027c86 on behalf of 
09-02 19:07:04.972  6881  7495 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ba40947 on behalf of 
09-02 19:07:04.973  6881  7495 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 19:07:04.973  6881  7494 V BluetoothOppNotification: update too frequent, put in queue
09-02 19:07:04.974  6881  7494 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 19:07:04.975  6881  7495 V BluetoothOppNotification: outbound notification was removed.
09-02 19:07:04.975  6881  7495 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-02 19:07:04.976  6881  7495 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2395c574 on behalf of 
09-02 19:07:04.977  6881  7495 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 19:07:04.980  6881  7495 V BluetoothOppNotification: inbound notification was removed.
09-02 19:07:04.980  6881  7495 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 19:07:04.981  6881  7495 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34a69a9d on behalf of 
09-02 19:07:04.990  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
,09-02 19:07:04.990  6881  6881 V BluetoothFtpService: Ftp Service onCreate
09-02 19:07:04.991  6881  6881 I BluetoothFtpService: Ftp Service onCreate
09-02 19:07:04.991  6881  6881 V BluetoothFtpService: Ftp Service onStartCommand
,09-02 19:07:04.991  6881  6881 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:04.991  6881  6881 V BluetoothFtpService: Starting Listening on sockets
09-02 19:07:04.991  6881  6881 V BtOppService: ContentObserver received notification
09-02 19:07:04.992  6881  6881 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 19:07:04.992  6881  6881 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 19:07:04.992  6881  6881 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 19:07:04.992  6881  6881 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:04.992  6881  6881 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 19:07:04.992  6881  6881 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 19:07:04.994  6881  6881 V BluetoothFtpService: Handler(): got msg=1
09-02 19:07:04.995  6881  6881 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 19:07:04.995  6881  6881 V BluetoothFtpService: Ftp Service initSocket
09-02 19:07:04.997  6881  7497 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 19:07:04.997  6881  7497 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 19:07:04.998  6881  7497 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@368df2e3 on behalf of 
09-02 19:07:04.999  6881  7497 V BluetoothOppNotification: update too frequent, put in queue
09-02 19:07:05.000  6881  7497 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 19:07:05.002  1044  1581 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:05.003  6881  6881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:05.005  6881  6881 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-02 19:07:05.005  6881  6881 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 19:07:05.007  6881  7499 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-02 19:07:05.021  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:05.022  6881  6881 V BluetoothSapService: Sap Service onCreate
,09-02 19:07:05.024  6881  6881 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:05.024  6881  6881 V BluetoothSapService: state: 12
09-02 19:07:05.024  6881  6881 V BluetoothSapService: Starting SAP server process
09-02 19:07:05.017  7500  7500 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:05.027  6881  6881 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 19:07:05.017  7500  7500 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:05.029  6881  7501 V BluetoothSapService: Sap Service initRfcommSocket
09-02 19:07:05.029  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:05.030  6881  7501 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:07:05.032  6881  7501 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-02 19:07:05.033  6881  7501 V BluetoothSapService: Succeed to create listening socket 
09-02 19:07:05.033  6881  7501 V BluetoothSapService: Accepting socket connection...
09-02 19:07:05.042  7500  7500 V BT_SAP  : Event pipe created
09-02 19:07:05.042  7500  7500 V BT_SAP  : create_server_socket qcom.sap.server
09-02 19:07:05.042  7500  7500 V BT_SAP  : created socket fd 6
,09-02 19:07:05.463  1044  1521 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:07:05.463  1044  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:07:05.518  1044  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-02 19:07:05.519  1044  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-02 19:07:05.770  1044  1904 I ActivityManager: Killing 7273:com.lge.bnr/1000 (adj 15): empty #17
,09-02 19:07:05.811  1044  1059 W libprocessgroup: failed to open /acct/uid_1000/pid_7273/cgroup.procs: No such file or directory
,09-02 19:07:05.829  1044  1926 I ActivityManager: Killing 6749:com.lge.sync/1000 (adj 15): empty #17
,09-02 19:07:05.848  1044  1528 D WifiService: Client connection lost with reason: 4
,09-02 19:07:05.862  1044  1872 W libprocessgroup: failed to open /acct/uid_1000/pid_6749/cgroup.procs: No such file or directory
,09-02 19:07:05.958  6881  6881 V BluetoothOppNotification: new notify threadi!
,09-02 19:07:05.958  6881  6881 V BluetoothOppNotification: send delay message
,09-02 19:07:05.971  6881  7511 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 19:07:05.975  6881  7511 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ca2da3f on behalf of 
09-02 19:07:05.977  6881  7511 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 19:07:05.984  6881  7511 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-02 19:07:05.989  6881  7511 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b904f0c on behalf of 
09-02 19:07:05.991  6881  7511 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 19:07:05.994  6881  7511 V BluetoothOppNotification: outbound notification was removed.
09-02 19:07:05.994  6881  7511 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 19:07:05.996  6881  7511 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23cf8055 on behalf of 
09-02 19:07:05.996  6881  7511 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-02 19:07:05.999  6881  7511 V BluetoothOppNotification: inbound notification was removed.
,09-02 19:07:06.000  6881  7511 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-02 19:07:06.001  6881  7511 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f31ba6a on behalf of 
,09-02 19:07:06.474  1044  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 19:07:06.474  1044  1926 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1d1b5af2 mBinding = false
,09-02 19:07:06.506  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 19:07:06.507  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 19:07:06.507  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,09-02 19:07:06.510  1044  1119 D BluetoothManagerService: Message: 2
09-02 19:07:06.511  1044  1119 D BluetoothManagerService: Sending off request.
09-02 19:07:06.511  6881  6896 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-02 19:07:06.512  6881  7354 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 19:07:06.512  6881  7354 D BluetoothAdapterProperties: Setting state to 13
09-02 19:07:06.512  6881  7354 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 19:07:06.513  6881  7354 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 19:07:06.513  6881  7354 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 19:07:06.515  6881  7358 D BluetoothAdapterProperties: Scan Mode:20
09-02 19:07:06.517  6881  7354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 19:07:06.519  6881  7486 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 19:07:06.519  6881  7486 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:07:06.519  6881  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 19:07:06.519  6881  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 19:07:06.519  6881  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 19:07:06.519  6881  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 19:07:06.519  6881  7486 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 19:07:06.519  6881  7486 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-02 19:07:06.523  6881  7487 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:07:06.524  6881  7496 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:07:06.524  6881  7499 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:07:06.524  6881  7501 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:07:06.525  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 19:07:06.525  6881  7423 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 19:07:06.527  6881  7354 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 19:07:06.531  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 19:07:06.535  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
,09-02 19:07:06.540  6881  7423 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 19:07:06.543  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:06.543  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:06.543  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:06.543  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:06.543  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:06.543  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:06.543  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:06.543  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:06.543  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:06.545  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:06.545  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:06.550  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:06.550  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:06.550  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:06.550  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:06.550  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:06.550  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:06.550  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:06.550  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:06.550  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:06.554  6536  6536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:06.554  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:06.555  1044  1119 D BluetoothManagerService: Message: 60
09-02 19:07:06.555  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 19:07:06.555  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-02 19:07:06.557  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:06.558  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 19:07:06.563  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:06.567  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:06.569  6881  6881 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:06.569  6881  6881 D BluetoothMapService: STATE_TURNING_OFF
09-02 19:07:06.569  6881  6881 V BluetoothMapService: Handler(): got msg=4
09-02 19:07:06.569  6881  6881 D BluetoothMapService: MAP Service closeService in
09-02 19:07:06.569  6881  6881 D BluetoothMapMasInstance: MAP Service shutdown
09-02 19:07:06.570  6881  6881 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 19:07:06.570  6881  6881 V BluetoothMapService: MAP Service closeService out
09-02 19:07:06.571  6881  6881 V BtOppService: Receiver DISABLED_ACTION 
09-02 19:07:06.571  6881  6881 I BtOppRfcommListener: stopping Accept Thread
09-02 19:07:06.571  6881  6881 V BtOppRfcommListener: close mBtServerSocket
09-02 19:07:06.572  6881  7496 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 19:07:06.572  6881  6881 V BtOppRfcommListener: waiting for thread to terminate
09-02 19:07:06.572  6881  6881 V BtOppRfcommListener: done waiting for thread to terminate
09-02 19:07:06.576  6731  6731 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-02 19:07:06.590  6731  6731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 19:07:06.593  6881  6881 V BtOppService: onDestroy
09-02 19:07:06.595  6881  6881 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-02 19:07:06.600  6881  6881 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 19:07:06.600  6881  6881 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:06.600  6881  6881 V BluetoothPbapReceiver: ***********state = 13
09-02 19:07:06.601  6881  6881 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-02 19:07:06.605  6881  6881 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:06.605  6881  6881 V BluetoothPbapService: state: 13
,09-02 19:07:06.605  6881  6881 V BluetoothPbapService: Pbap Service closeService in
09-02 19:07:06.608  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:07:06.610  6881  6881 V BluetoothPbapService: successfully stopped pbap service
09-02 19:07:06.610  6881  6881 V BluetoothPbapService: Pbap Service closeService out
09-02 19:07:06.611  6881  6881 V BluetoothPbapService: Pbap Service onDestroy
09-02 19:07:06.611  6881  6881 V BluetoothPbapService: Pbap Service closeService in
09-02 19:07:06.611  6881  6881 V BluetoothPbapService: Pbap Service closeService out
09-02 19:07:06.611  6881  6881 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-02 19:07:06.632  6731  6731 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:07:06.643  6731  6731 D BluetoothPbap: Proxy object disconnected
09-02 19:07:06.643  6731  6731 D PbapServerProfile: Bluetooth service disconnected
,09-02 19:07:06.647  6731  6731 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 19:07:06.653  6731  6731 D BluetoothPermissionRequest: onReceive
09-02 19:07:06.653  6731  6731 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-02 19:07:06.660  6731  6731 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-02 19:07:06.664  6881  6881 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 19:07:06.664  6881  6881 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 19:07:06.665  6881  6881 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-02 19:07:06.670  6881  6881 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:06.671  6881  6881 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 19:07:06.672  6881  6881 V BluetoothFtpService: Ftp Service onStartCommand
09-02 19:07:06.672  6881  6881 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:06.672  6881  6881 V BluetoothFtpService: Ftp Service closeService
09-02 19:07:06.672  6881  6881 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 19:07:06.675  6881  6881 V BluetoothFtpService: successfully stopped ftp service
09-02 19:07:06.675  6881  6881 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 19:07:06.675  6881  6881 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 19:07:06.675  6881  6881 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 19:07:06.675  6881  6881 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:06.676  6881  6881 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 19:07:06.676  6881  6881 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-02 19:07:06.679  6881  6881 V BluetoothFtpService: Ftp Service onDestroy
09-02 19:07:06.679  6881  6881 V BluetoothFtpService: Ftp Service closeService
09-02 19:07:06.686  6881  6881 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:06.686  6881  6881 V BluetoothSapService: state: 13
09-02 19:07:06.686  6881  6881 V BluetoothSapService: Stopping SAP server process
09-02 19:07:06.688  6881  6881 V BluetoothSapService: Sap Service closeSapService in
09-02 19:07:06.688  6881  6881 V BluetoothSapService: Close listen Socket : 
09-02 19:07:06.688  6881  6881 V BluetoothSapService: Close rfcomm Socket : 
09-02 19:07:06.688  6881  6881 V BluetoothSapService: Close sapd  Socket : 
,09-02 19:07:06.692  6881  6881 V BluetoothSapService: Sap Service closeSapService out
,09-02 19:07:06.692  6881  6881 V BluetoothSapService: Sap Service onDestroy
,09-02 19:07:06.693  6881  6881 V BluetoothSapService: Sap Service closeSapService in,
09-02 19:07:06.693  6881  6881 V BluetoothSapService: Close listen Socket : 
09-02 19:07:06.693  6881  6881 V BluetoothSapService: Close rfcomm Socket : 
,09-02 19:07:06.693  6881  6881 V BluetoothSapService: Close sapd  Socket : 
09-02 19:07:06.693  6881  6881 V BluetoothSapService: Sap Service closeSapService out
09-02 19:07:07.432  6881  7358 D bt_hci_bdroid: cleanup
,09-02 19:07:07.443  6881  7425 I bt_lpm  : LPM is already off!!!
,09-02 19:07:07.444  6881  7455 I bt_userial_mct: exiting userial_read_thread
09-02 19:07:07.444  6881  7455 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-02 19:07:07.444  6881  7423 W bt-btif : ag scb idx 1 not allocated
09-02 19:07:07.444  6881  7423 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:07.444  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 19:07:07.445  6881  7423 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:07:07.445  6881  7423 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 19:07:07.446  6881  7358 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 19:07:07.446  6881  7425 I bt_vendor: hw_epilog_process
09-02 19:07:07.446  6881  7358 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 19:07:07.446  6881  7358 D bt_userial_mct: userial_close
09-02 19:07:07.446  6881  7358 E bt_userial_mct: pthread_join() FAILED result:3
09-02 19:07:07.446  6881  7358 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 19:07:07.451  6881  7358 D bt_hci_bdroid: set_power 0
09-02 19:07:07.451  6881  7358 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 19:07:07.451  6881  7358 I bt_vendor: bluetooth satus is on
09-02 19:07:07.451  6881  7358 I bt_vendor: bt-vendor : resetting BT status
09-02 19:07:07.451  6881  7358 I bt_vendor: Starting hciattach daemon
09-02 19:07:07.451  6881  7358 I bt_vendor: try to set false
09-02 19:07:07.455  6881  7358 I bt_vendor: Starting hciattach daemon
09-02 19:07:07.455  6881  7358 I bt_vendor: try to set false
,09-02 19:07:07.460  6881  7358 I bt_vendor: cleanup
09-02 19:07:07.461  6881  7423 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 19:07:07.462  6881  7358 I GKI_LINUX: GKI_exit_task 0 done
09-02 19:07:07.462  6881  7358 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 19:07:07.464  6881  7354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 19:07:07.468  6881  6881 D HeadsetService: Received stop request...Stopping profile...
,09-02 19:07:07.471  6881  6881 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 19:07:07.471  6881  6881 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:07:07.471  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:07.471  6881  7394 D HeadsetStateMachine: Exit Disconnected: -1
09-02 19:07:07.474  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:07.474  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:07.474  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:07.475  1044  1044 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:07.475  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 19:07:07.476  6881  6881 D HeadsetStateMachine: Unbinding service...
,09-02 19:07:07.478  6881  6881 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 19:07:07.478  6881  6881 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 19:07:07.478  6881  6881 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 19:07:07.478  6881  6881 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 19:07:07.478  6881  6881 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 19:07:07.478  6881  6881 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:07:07.478  6881  6881 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 19:07:07.484  6881  6881 D A2dpService: Received stop request...Stopping profile...
,09-02 19:07:07.487  6881  7415 D A2dpStateMachine: Exit Disconnected: -1
09-02 19:07:07.492  6881  6881 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 19:07:07.493  6881  7354 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 19:07:07.494  6881  6881 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 19:07:07.494  6881  6881 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:07:07.494  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:07.496  1044  1044 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:07.496  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 19:07:07.497  6881  6881 D HidService: Received stop request...Stopping profile...
09-02 19:07:07.497  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
,09-02 19:07:07.502  6881  6881 D HealthService: Received stop request...Stopping profile...
09-02 19:07:07.502  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:07.505  6881  6881 D PanService: Received stop request...Stopping profile...
09-02 19:07:07.506  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:07.507  6881  6881 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 19:07:07.508  6881  6881 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 19:07:07.508  6881  6881 D BtGatt.GattService: stop()
09-02 19:07:07.508  6881  6881 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 19:07:07.509  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
,09-02 19:07:07.513  6881  6881 D BluetoothMapService: Received stop request...Stopping profile...
09-02 19:07:07.513  6881  6881 D BluetoothMapService: stop()
09-02 19:07:07.513  6881  6881 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 19:07:07.514  6881  6881 D BluetoothMapEmailAppObserver: removeReceiver()
09-02 19:07:07.515  6881  6881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@122b95d9
09-02 19:07:07.516  6881  6881 I BluetoothA2dpServiceJni: cleanupNative
09-02 19:07:07.517  6881  7416 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 19:07:07.517  6881  6881 I GKI_LINUX: GKI_exit_task 2 done
09-02 19:07:07.517  6881  6881 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 19:07:07.517  6881  6881 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 19:07:07.517  6881  6881 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 19:07:07.518  6881  6881 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 19:07:07.518  6881  6881 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 19:07:07.518  6881  6881 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 19:07:07.518  6881  6881 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 19:07:07.518  6881  6881 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 19:07:07.522  6881  6881 V BluetoothMapService: Handler(): got msg=4
09-02 19:07:07.522  6881  6881 D BluetoothMapService: MAP Service closeService in
09-02 19:07:07.522  6881  6881 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 19:07:07.522  6881  6881 V BluetoothMapService: MAP Service closeService out
,09-02 19:07:07.525  6881  7354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 19:07:07.526  6881  7354 D BluetoothAdapterProperties: Setting state to 10
09-02 19:07:07.526  6881  7354 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 19:07:07.527  6881  6881 D BluetoothMapService: cleanup()
09-02 19:07:07.527  6881  6881 D BluetoothMapService: MAP Service closeService in
09-02 19:07:07.527  6881  6881 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 19:07:07.527  6881  6881 V BluetoothMapService: MAP Service closeService out
09-02 19:07:07.528  1044  1119 D BluetoothManagerService: Message: 60
09-02 19:07:07.528  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 19:07:07.528  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-02 19:07:07.528  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:07:07.529  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 19:07:07.531  6881  7354 I BluetoothAdapterState: Entering OffState
09-02 19:07:07.532  6731  7475 D BluetoothPan: onBluetoothStateChange on: false
09-02 19:07:07.532  6731  7475 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 19:07:07.533  6731  7475 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:07:07.533  6731  7475 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 19:07:07.537  6731  7475 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 19:07:07.538  6731  7475 D BluetoothMap: onBluetoothStateChange: up=false
09-02 19:07:07.539  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:07:07.539  1837  2556 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:07:07.540  1837  3942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:07:07.541  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 19:07:07.541  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 19:07:07.543  1044  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 19:07:07.543  1044  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 19:07:07.543  1044  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1d1b5af2 mBinding = false
09-02 19:07:07.544  1044  1119 D BluetoothManagerService: Sending unbind request.
09-02 19:07:07.549  6881  7358 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 19:07:07.551  6881  6881 I GKI_LINUX: GKI_exit_task 1 done
09-02 19:07:07.552  6881  6881 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 19:07:07.552  6881  6881 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 19:07:07.552  6881  6881 I art     : --- WEIRD: removing null entry 248
09-02 19:07:07.552  6881  6881 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-02 19:07:07.553  6881  6881 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 19:07:07.554  6881  6881 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 19:07:07.555  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 19:07:07.557  6881  6881 I art     : System.exit called, status: 0
09-02 19:07:07.557  6881  6881 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-02 19:07:07.576   320  1371 V AudioFlinger: 6881 died, releasing its sessions
09-02 19:07:07.577   320  1371 V AudioFlinger:  pid 1837 @ 0
09-02 19:07:07.577   320  1371 V AudioFlinger:  pid 3432 @ 1
09-02 19:07:07.577   320  1371 V AudioFlinger:  pid 3432 @ 2
,09-02 19:07:07.583  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-02 19:07:07.584  1927  2104 D LGBluetoothAPIService: Message: 101
09-02 19:07:07.584  1927  2104 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
,09-02 19:07:07.584  1927  2104 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-02 19:07:07.585  1927  2104 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,09-02 19:07:07.587  6731  6731 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 19:07:07.661  1044  1060 I ActivityManager: Process com.android.bluetooth (pid 6881) has died
,09-02 19:07:07.662  1044  1060 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-02 19:07:07.662  1044  1060 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-02 19:07:07.680  6731  6731 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,09-02 19:07:07.680  6731  6731 D LGBluetoothEventManager: [BTUI] clear device connection state
09-02 19:07:07.681  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:07.681  1927  2104 D LGBluetoothAPIService: Message: 2
09-02 19:07:07.682  1927  2104 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,09-02 19:07:07.686  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 19:07:07.686  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:07.687  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:07.687  6731  6731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 19:07:07.693  1588  1588 D BluetoothAdapter: 339789752: getState() :  mService = null. Returning STATE_OFF
09-02 19:07:07.693  1588  1588 D BluetoothAdapter: 339789752: getState() :  mService = null. Returning STATE_OFF
09-02 19:07:07.852  1044  1998 I art     : Explicit concurrent mark sweep GC freed 85144(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.196ms total 159.069ms
,09-02 19:07:07.913  1044  1871 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7560 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-02 19:07:07.917  6731  6731 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:07:07.997  7560  7560 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-02 19:07:07.998  7560  7560 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 19:07:07.999  7560  7560 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 19:07:08.000  7560  7560 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 19:07:08.022  7560  7560 D BluetoothAdapterApp: Loading JNI Library
,09-02 19:07:08.073  7560  7560 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d5513a1 Instance Count = 1
,09-02 19:07:08.078  7560  7560 D BluetoothAdapterApp: onCreate
,09-02 19:07:08.105  7560  7560 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-02 19:07:08.106  7560  7560 D ProfileConfigQcom: Adding HeadsetService
,09-02 19:07:08.106  7560  7560 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-02 19:07:08.106  7560  7560 D ProfileConfigQcom: Adding A2dpService
,09-02 19:07:08.106  7560  7560 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 19:07:08.106  7560  7560 D ProfileConfigQcom: Adding HidService
09-02 19:07:08.107  7560  7560 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 19:07:08.107  7560  7560 D ProfileConfigQcom: Adding HealthService
09-02 19:07:08.107  7560  7560 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-02 19:07:08.109  7560  7560 D ProfileConfigQcom: [BTUI] PanService is supported
,09-02 19:07:08.109  7560  7560 D ProfileConfigQcom: Adding PanService
09-02 19:07:08.109  7560  7560 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 19:07:08.109  7560  7560 D ProfileConfigQcom: Adding GattService
09-02 19:07:08.110  7560  7560 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-02 19:07:08.110  7560  7560 D ProfileConfigQcom: Adding BluetoothMapService
09-02 19:07:08.111  7560  7560 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 19:07:08.112  7560  7560 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 19:07:08.113  7560  7560 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:08.113  7560  7560 V BluetoothPbapReceiver: ***********state = 10
,09-02 19:07:08.115  7560  7560 V LGMDMManagerInternal: Create singleton instance,
,09-02 19:07:08.214  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:07:08.217  7560  7560 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 19:07:08.217  7560  7560 D LGBluetoothAPIServer: [BTUI] onBind()
09-02 19:07:08.218  6731  6731 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 19:07:08.222  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 19:07:08.223  1927  2104 D LGBluetoothAPIService: Message: 100
09-02 19:07:08.223  1927  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 19:07:08.236  6731  6731 D BluetoothPermissionRequest: onReceive
,09-02 19:07:08.239  6731  6731 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 19:07:08.239  6731  6731 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-02 19:07:08.241  6731  6731 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 19:07:08.245  7560  7560 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-02 19:07:08.250  7560  7560 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:08.255  7560  7560 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-02 19:07:08.256  7560  7560 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 19:07:08.256  7560  7560 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 19:07:08.257  7560  7560 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:08.257  7560  7560 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 19:07:08.260  6818  6818 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-02 19:07:09.575  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:09.575  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:09.770  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-02 19:07:09.796  1044  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 19:07:09.880  1044  1115 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7588 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-02 19:07:09.886  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-02 19:07:09.886  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-02 19:07:09.906  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-02 19:07:09.920  1044  1044 D administrator: Handling package changes for user 0
,09-02 19:07:09.952  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 19:07:09.971  7588  7588 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 19:07:10.037  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-02 19:07:10.037  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-02 19:07:10.064  7588  7588 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:07:10.064  7588  7588 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:07:10.085  1044  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 19:07:10.092  1044  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-02 19:07:10.102  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-02 19:07:10.102  2493  2493 V GmsNetworkLocationProvi: DISABLE
,09-02 19:07:10.140  1044  1114 D LocationProviderProxy: applying state to connected service
,09-02 19:07:10.143  2493  2493 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-02 19:07:10.173  7588  7634 I Babel   : MmsConfig: mnc/mcc: 0/0
09-02 19:07:10.173  7588  7634 I Babel   : MmsConfig.loadMmsSettings
09-02 19:07:10.175  7588  7634 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-02 19:07:10.175  7588  7634 I Babel   : MmsConfig.loadFromDatabase
,09-02 19:07:10.197  7588  7634 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-02 19:07:10.197  7588  7634 I Babel   : MmsConfig.loadFromResources
09-02 19:07:10.201  7588  7634 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-02 19:07:10.202  7588  7634 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-02 19:07:10.207  7588  7588 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:10.224  7588  7632 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 19:07:10.225  7588  7632 W AudioCapabilities: Unsupported mime audio/qcelp
09-02 19:07:10.227  1801  7635 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-02 19:07:10.227  1801  7635 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-02 19:07:10.229  7588  7632 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-02 19:07:10.231  6926  6926 I AppUp4:CustModeStarterReceiver: onReceive
09-02 19:07:10.234  1801  4711 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-02 19:07:10.234  6926  6926 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e6eb23
09-02 19:07:10.234  6926  6926 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 19:07:10.234  6926  6926 D AppUp4:CustFacade: isPhone : true
09-02 19:07:10.234  6926  6926 D AppUp4:CustModeStarterReceiver: begin check event
09-02 19:07:10.235  6926  6926 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,09-02 19:07:10.246  7588  7632 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-02 19:07:10.253  7588  7632 W AudioCapabilities: Unsupported mime audio/qcelp
09-02 19:07:10.254  7588  7632 W AudioCapabilities: Unsupported mime audio/evrc
09-02 19:07:10.261  7588  7632 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 19:07:10.263  7588  7632 W VideoCapabilities: Unsupported mime video/divx
09-02 19:07:10.264  7588  7632 W VideoCapabilities: Unsupported mime video/divx311
09-02 19:07:10.266  7588  7632 W VideoCapabilities: Unsupported mime video/divx4
09-02 19:07:10.270  7588  7632 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-02 19:07:10.281  7588  7632 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 19:07:10.285  7588  7632 W AudioCapabilities: Unsupported mime audio/eac3
09-02 19:07:10.286  1044  1766 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7639 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-02 19:07:10.286  7588  7632 W AudioCapabilities: Unsupported mime audio/ac3
09-02 19:07:10.287  7588  7632 W AudioCapabilities: Unsupported mime audio/g726
09-02 19:07:10.288  7588  7632 W AudioCapabilities: Unsupported mime audio/wma-voice
09-02 19:07:10.289  7588  7632 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-02 19:07:10.290  1044  1871 I ActivityManager: Killing 6652:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-02 19:07:10.291  7588  7632 W AudioCapabilities: Unsupported mime audio/adpcm
09-02 19:07:10.292  7588  7632 W VideoCapabilities: Unsupported mime video/theora
,09-02 19:07:10.296  7588  7632 W VideoCapabilities: Unsupported mime video/mjpg
09-02 19:07:10.309  6801  6801 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-02 19:07:10.309  6801  6801 W System.err: android.os.DeadObjectException
09-02 19:07:10.309  6801  6801 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 19:07:10.309  6801  6801 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,09-02 19:07:10.309  6801  6801 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,09-02 19:07:10.309  6801  6801 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-02 19:07:10.310  6801  6801 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 19:07:10.310  6801  6801 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 19:07:10.310  6801  6801 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 19:07:10.310  6801  6801 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 19:07:10.310  6801  6801 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:10.310  6801  6801 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:10.310  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:10.310  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:10.310  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:10.310  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:07:10.310  6801  6801 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-02 19:07:10.310  6801  6801 W System.err: android.os.DeadObjectException
09-02 19:07:10.311  6801  6801 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 19:07:10.311  6801  6801 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 19:07:10.311  6801  6801 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-02 19:07:10.311  6801  6801 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-02 19:07:10.311  6801  6801 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 19:07:10.311  6801  6801 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 19:07:10.311  6801  6801 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 19:07:10.311  6801  6801 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 19:07:10.311  6801  6801 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:10.311  6801  6801 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:10.311  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:10.311  6801  6801 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:10.311  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:10.311  6801  6801 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:07:10.311  6801  6801 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-02 19:07:10.312  6801  6801 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-02 19:07:10.528  1044  1529 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-02 19:07:10.591  1044  1926 W libprocessgroup: failed to open /acct/uid_1000/pid_6652/cgroup.procs: No such file or directory
09-02 19:07:10.591  1044  1926 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-02 19:07:10.601  6801  6801 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-02 19:07:10.602  6801  6801 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 19:07:10.606  7639  7639 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:07:10.606  7639  7639 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 19:07:10.607  7639  7639 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 19:07:10.607  7639  7639 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-02 19:07:10.608  7639  7639 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-02 19:07:10.646  1044  1871 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7660 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 19:07:10.647  6801  6801 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-02 19:07:10.681  7660  7660 D UEI.SmartControl: Quickset Services start...
,09-02 19:07:10.682  7660  7660 I UEI.SmartControl: Manufacture = LGE
09-02 19:07:10.683  7660  7660 D UEI.SmartControl: Id = LGNevo
09-02 19:07:10.683  7660  7660 D UEI.SmartControl: File observer start...
09-02 19:07:10.684  7660  7660 E UEI.SmartControl: IR Port is disabled: false
09-02 19:07:10.684  7660  7660 D UEI.SmartControl: Starting file observer...
09-02 19:07:10.684  7660  7660 D UEI.SmartControl: Extracting JNI libs...
09-02 19:07:10.684  7660  7660 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-02 19:07:10.684  7639  7639 I SystemConfig: BUILD Country: EU
09-02 19:07:10.685  7639  7639 I SystemConfig: BUILD Operator: OPEN
09-02 19:07:10.731  7660  7660 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-02 19:07:10.731  7660  7660 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-02 19:07:10.731  7660  7660 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-02 19:07:10.749  1044  1926 I ActivityManager: Killing 6801:com.lge.qremote/u0a112 (adj 15): empty #17
,09-02 19:07:10.752  7660  7660 I UEI.SmartControl: --- Selecting new region: 6
,09-02 19:07:10.754  7660  7660 I UEI.SmartControl: Model = LG-D855
09-02 19:07:10.755  7660  7660 D UEI.SmartControl: QS Service created
09-02 19:07:10.792  1044  1872 W libprocessgroup: failed to open /acct/uid_10112/pid_6801/cgroup.procs: No such file or directory
,09-02 19:07:10.821  7660  7660 I UEI.SmartControl: Service initServices...
,09-02 19:07:10.827  7660  7660 D UEI.SmartControl: QS start get config
09-02 19:07:10.853  1044  1926 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7681 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-02 19:07:10.859  7639  7679 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,09-02 19:07:10.859  7639  7679 I SystemConfig: existFile = false
09-02 19:07:10.859  7639  7679 I SystemConfig: canReadFile = false
09-02 19:07:10.859  7639  7679 I SystemConfig: systemFeature RCS result false
09-02 19:07:10.859  7639  7679 D SystemConfig: refreshRcsSupport() :false
,09-02 19:07:10.924  7681  7681 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:07:10.925  7681  7681 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 19:07:10.925  7681  7681 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-02 19:07:10.925  7681  7681 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-02 19:07:10.934  7660  7660 D UEI.SmartControl: Loading JNI Libs...
09-02 19:07:10.995  7681  7681 I AppConfig: Total System Memory = 2995761152
,09-02 19:07:11.001  7681  7681 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-02 19:07:11.055  1044  2017 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7705 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:07:11.055  1044  2017 I ActivityManager: Killing 6973:com.lge.email/u0a23 (adj 15): empty #17
09-02 19:07:11.172  1044  1904 W libprocessgroup: failed to open /acct/uid_10023/pid_6973/cgroup.procs: No such file or directory
,09-02 19:07:11.216  7660  7660 I UEI.SmartControl: Supports setup maps: true
,09-02 19:07:11.225  7660  7660 D UEI.SmartControl: QS start statue = true Error code = 0
09-02 19:07:11.226  7660  7660 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 19:07:11.226  7660  7660 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 19:07:11.226  7660  7660 I UEI.SmartControl: ### init IR Blaster...
09-02 19:07:11.231  7660  7660 D serial_port: Configuring serial port
,09-02 19:07:11.237  7660  7660 E UEI.SmartControl: UEIBLaster setting for 616
09-02 19:07:11.237  7660  7660 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 19:07:11.237  7660  7660 I UEI.SmartControl: configuring settings for MAXQ616
09-02 19:07:11.237  7660  7660 I UEI.SmartControl: Get version...
09-02 19:07:11.253  7660  7725 D UEI.SmartControl: serial port data available: 21
,09-02 19:07:11.282  7660  7660 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-02 19:07:11.282  7660  7660 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 19:07:11.282  7660  7660 I UEI.SmartControl: QS saving settings...
09-02 19:07:11.284  7660  7660 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 19:07:11.301  7660  7725 D UEI.SmartControl: serial port data available: 4
,09-02 19:07:11.334  7660  7734 I UEI.SmartControl: Device manager: loading config....
09-02 19:07:11.335  7660  7734 D UEI.SmartControl: ----------- loading internal config...
,09-02 19:07:11.337  7660  7660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-02 19:07:11.340  7660  7660 E UEI.SmartControl: Services init done
09-02 19:07:11.340  7660  7660 D UEI.SmartControl: QS Service init finished
,09-02 19:07:11.341  7660  7660 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 19:07:11.341  7660  7660 D UEI.SmartControl: QS Service version code: 201091
09-02 19:07:11.345  7660  7660 D UEI.SmartControl: Service requested: Control
09-02 19:07:11.350  7660  7660 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 19:07:11.350  7660  7734 E UEI.SmartControl: Loading SETTINGS...
09-02 19:07:11.352  7660  7660 D UEI.SmartControl: Service.onUnbind: IControl
09-02 19:07:11.352  7660  7660 D UEI.SmartControl: Service.onDestroy
09-02 19:07:11.352  7660  7660 D UEI.SmartControl: Lock is in USE false
09-02 19:07:11.352  7660  7660 D UEI.SmartControl: unbind internal service
,09-02 19:07:11.356  7660  7660 D serial_port: close(fd = 25)
09-02 19:07:11.356  7660  7733 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 19:07:11.356  7660  7733 D UEI.SmartControl: -----service ready thread exits
09-02 19:07:11.360  7660  7660 I UEI.SmartControl: Serial port is closed.
09-02 19:07:11.360  7660  7660 I UEI.SmartControl: Serial port is closed.
09-02 19:07:11.360  7660  7660 D UEI.SmartControl: Blaster closed
09-02 19:07:11.360  7660  7660 D UEI.SmartControl: Shut down QS...
09-02 19:07:11.360  7660  7660 D UEI.SmartControl: Stopping QS lib
09-02 19:07:11.361  7660  7660 D UEI.SmartControl: QS lib stop result = true
09-02 19:07:11.361  7660  7660 D UEI.SmartControl: Stopped QS lib
09-02 19:07:11.361  7660  7660 D UEI.SmartControl: Stopped file observer...
09-02 19:07:11.361  7660  7660 D UEI.SmartControl: QS shutdown complete
09-02 19:07:11.362  7660  7660 D UEI.SmartControl: QS Service created
09-02 19:07:11.364  7705  7705 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-02 19:07:11.369  7660  7734 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-02 19:07:11.396  7660  7660 I UEI.SmartControl: Service initServices...
09-02 19:07:11.397  7660  7660 D UEI.SmartControl: QS start get config
,09-02 19:07:11.443  7705  7705 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 19:07:11.443  7705  7705 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:07:11.505  7705  7705 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-02 19:07:11.534  7705  7705 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-02 19:07:11.535  7705  7705 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-02 19:07:11.555  7705  7705 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-02 19:07:11.556  7705  7705 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-02 19:07:11.578  1044  1872 I ActivityManager: Killing 6838:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-02 19:07:11.677  1044  1942 W libprocessgroup: failed to open /acct/uid_10026/pid_6838/cgroup.procs: No such file or directory
,09-02 19:07:11.684  3503  3519 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-02 19:07:11.687  3503  3519 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@ae95c57 on behalf of 7705
09-02 19:07:11.688  4559  7757 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-02 19:07:11.724  1044  1871 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7762 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-02 19:07:11.745  7705  7705 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-02 19:07:11.762  7660  7660 I UEI.SmartControl: Supports setup maps: true
09-02 19:07:11.762  7705  7705 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-02 19:07:11.765  7660  7660 D UEI.SmartControl: QS start statue = true Error code = 0
,09-02 19:07:11.765  7660  7660 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-02 19:07:11.765  7660  7660 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 19:07:11.765  7660  7660 I UEI.SmartControl: ### init IR Blaster...
09-02 19:07:11.769  7660  7660 D serial_port: Configuring serial port
09-02 19:07:11.769  7660  7660 E UEI.SmartControl: UEIBLaster setting for 616
09-02 19:07:11.769  7660  7660 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 19:07:11.769  7660  7660 I UEI.SmartControl: configuring settings for MAXQ616
09-02 19:07:11.769  7660  7660 I UEI.SmartControl: Get version...
09-02 19:07:11.785  7660  7782 D UEI.SmartControl: serial port data available: 21
,09-02 19:07:11.796  7762  7762 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-02 19:07:11.811  7660  7660 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 19:07:11.811  7660  7660 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 19:07:11.811  7660  7660 I UEI.SmartControl: QS saving settings...
09-02 19:07:11.811  7660  7660 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 19:07:11.823  7762  7762 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-02 19:07:11.823  7762  7762 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-02 19:07:11.823  7762  7762 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,09-02 19:07:11.823  7762  7762 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-02 19:07:11.823  7762  7762 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,09-02 19:07:11.823  7762  7762 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-02 19:07:11.829  7660  7782 D UEI.SmartControl: serial port data available: 4
09-02 19:07:11.834  1044  1559 I ActivityManager: Killing 6361:com.wsandroid.suite.lge/1000 (adj 15): empty #17
09-02 19:07:11.856  7660  7786 I UEI.SmartControl: Device manager: loading config....
09-02 19:07:11.856  7660  7786 D UEI.SmartControl: ----------- loading internal config...
09-02 19:07:11.856  7660  7660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-02 19:07:11.860  7660  7786 E UEI.SmartControl: Loading SETTINGS...
09-02 19:07:11.864  7660  7786 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-02 19:07:11.872  1044  1963 W libprocessgroup: failed to open /acct/uid_1000/pid_6361/cgroup.procs: No such file or directory
,09-02 19:07:11.874  7660  7660 E UEI.SmartControl: Services init done
,09-02 19:07:11.874  7660  7660 D UEI.SmartControl: QS Service init finished
,09-02 19:07:11.875  7660  7660 D UEI.SmartControl: QS Service version name: 2.1.91
,09-02 19:07:11.875  7660  7660 D UEI.SmartControl: QS Service version code: 201091
09-02 19:07:11.875  7660  7660 D UEI.SmartControl: Service requested: Control
09-02 19:07:11.875  7660  7785 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 19:07:11.875  7660  7785 D UEI.SmartControl: -----service ready thread exits
09-02 19:07:11.877  1044  1871 I ActivityManager: Killing 7009:com.google.android.setupwizard/u0a46 (adj 15): empty #17
09-02 19:07:11.930  1044  1998 W libprocessgroup: failed to open /acct/uid_10046/pid_7009/cgroup.procs: No such file or directory
09-02 19:07:11.934  7660  7660 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@533167f that was originally bound here
09-02 19:07:11.934  7660  7660 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@533167f that was originally bound here
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:11.934  7660  7660 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-02 19:07:11.944  7660  7660 D UEI.SmartControl: Internal service binding...
09-02 19:07:12.022  1044  1060 V SIM_STK : Menu title from STK is T-Mobile
,09-02 19:07:12.045  4559  7757 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 357 ms] updated apps [took 357 ms] 
,09-02 19:07:12.353  7660  7737 D UEI.SmartControl: Internal timer expired: 2
,09-02 19:07:12.585  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:12.586  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14493dbd added. We now have 6 listener(s)
,09-02 19:07:12.586  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:12.600  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:12.600  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@312d0fb2 added. We now have 7 listener(s)
09-02 19:07:12.600  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:12.602  6536  6649 I System.out: IsBluetoothEnabled
09-02 19:07:12.604  1044  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:12.604  1044  1871 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-02 19:07:12.605  1044  1119 D BluetoothManagerService: Message: 2
09-02 19:07:12.608  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:12.611  1044  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:12.611  1044  1962 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-02 19:07:12.628  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 19:07:12.628  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 19:07:12.628  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,09-02 19:07:12.633  1044  1119 D BluetoothManagerService: Message: 1
09-02 19:07:12.633  1044  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-02 19:07:12.662  1044  1119 D BluetoothManagerService: Message: 20
,09-02 19:07:12.662  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@381a3335:true
,09-02 19:07:12.666  7560  7560 D BluetoothAdapterState: make
09-02 19:07:12.671  7560  7560 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 19:07:12.671  7560  7560 I bluedroid-qcom: init
09-02 19:07:12.672  7560  7798 I BluetoothAdapterState: Entering OffState
09-02 19:07:12.673  7560  7560 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 19:07:12.673  7560  7560 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 19:07:12.673  7560  7560 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 19:07:12.673  7560  7560 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 19:07:12.673  7560  7560 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 19:07:12.676  7560  7560 I bluedroid-qcom: get_profile_interface socket
09-02 19:07:12.676  7560  7560 I bluedroid-qcom: get_profile_interface map_client
,09-02 19:07:12.681  7560  7802 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 19:07:12.683  7560  7802 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 19:07:12.677  7801  7801 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:12.677  7801  7801 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:12.693  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 19:07:12.693  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
,09-02 19:07:12.699  7801  7801 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 19:07:12.699  7801  7801 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 19:07:12.699  7801  7801 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-02 19:07:12.700  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-02 19:07:12.701  1044  1119 D BluetoothManagerService: Message: 40
09-02 19:07:12.701  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 19:07:12.702  7560  7577 I bluedroid-qcom: config_hci_snoop_log
09-02 19:07:12.703  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 19:07:12.703  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 19:07:12.703  7801  7801 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-02 19:07:12.707  7560  7802 D BluetoothAdapterProperties: Name is: G3
,09-02 19:07:12.711  7801  7801 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 19:07:12.711  7801  7801 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-02 19:07:12.717  7560  7798 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 19:07:12.717  7560  7798 D BluetoothAdapterProperties: Setting state to 11
09-02 19:07:12.717  7560  7798 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 19:07:12.718  7560  7798 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 19:07:12.721  1044  1119 D BluetoothManagerService: Message: 60
09-02 19:07:12.721  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 19:07:12.721  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,09-02 19:07:12.727  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:12.728  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 19:07:12.745  6731  6731 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-02 19:07:12.750  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:12.754  7560  7560 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 19:07:12.754  7560  7560 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:12.754  7560  7560 V BluetoothPbapReceiver: ***********state = 11
09-02 19:07:12.758  7560  7798 D BluetoothBondStateMachine: make
,09-02 19:07:12.760  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:07:12.763  7560  7817 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 19:07:12.763  7560  7798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:12.763  7560  7798 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 19:07:12.763  7560  7798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:12.763  7560  7798 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 19:07:12.764  7560  7798 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 19:07:12.767  7560  7798 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:12.778  7560  7560 D HeadsetService: Received start request. Starting profile...
09-02 19:07:12.779  7560  7560 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 19:07:12.779  7560  7560 D LGBluetoothHfpAdapter: Version 1.6
09-02 19:07:12.781  6731  6731 D BluetoothPermissionRequest: onReceive
,09-02 19:07:12.782  7560  7560 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 19:07:12.784  7560  7560 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 19:07:12.784  7560  7560 D HeadsetStateMachine: make
09-02 19:07:12.785  7560  7798 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:12.788  6731  6731 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 19:07:12.794  7560  7798 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:12.801  7560  7798 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 19:07:12.806  7560  7798 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:12.811  7560  7798 E BluetoothAdapterService: File transfer profiles supported!!
09-02 19:07:12.816  7560  7798 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 19:07:12.824  7560  7560 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:07:12.824  7560  7560 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 19:07:12.829  7560  7560 D HeadsetStateMachine: max_hf_connections = 1
09-02 19:07:12.829  7560  7560 I bluedroid-qcom: get_profile_interface handsfree
,09-02 19:07:12.831  7560  7560 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 19:07:12.832   320  2174 V AudioPolicyService: registerClient() client 0xb558a7e0, uid 1002
09-02 19:07:12.832   320   320 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,09-02 19:07:12.832   320   320 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 19:07:12.832   320   320 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 19:07:12.832  7560  7560 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 19:07:12.832  7560  7798 V LGMDMManager: Create singleton instance
09-02 19:07:12.833   320  1371 V AudioFlinger: registerClient() client 0xb55815e0, pid 7560
09-02 19:07:12.833   320  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:12.833   320  1366 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-02 19:07:12.833  1044  2017 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:12.833  1044  2017 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:12.834  1837  2557 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:12.834   320  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:12.834   320  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
,09-02 19:07:12.834  7560  7577 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:12.834  1044  1060 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:12.834  1044  1060 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:12.834  3432  3448 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:12.834  3432  3448 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:12.834  3432  3448 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:12.834  3432  3448 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:12.834  1837  2557 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:12.834  1837  2557 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:12.834  1837  2557 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:12.834  7560  7577 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 19:07:12.834  7560  7577 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:12.834  7560  7560 V ToneGenerator: Create Track: 0xb4928a80
09-02 19:07:12.834  7560  7560 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 19:07:12.834  7560  7577 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 19:07:12.834  7560  7560 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 19:07:12.834  1588  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 19:07:12.834  1588  2084 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 19:07:12.835  1588  2084 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 19:07:12.835   320  1370 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 19:07:12.835  1588  2084 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 19:07:12.835   320  1370 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 19:07:12.835   320  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 19:07:12.835   320  1370 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 19:07:12.835   320  2174 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 19:07:12.835   320   320 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 19:07:12.835   320   320 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 19:07:12.835   320   320 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 19:07:12.835   320   320 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 19:07:12.835  7560  7560 V AudioSystem: getLatency() output 2, latency 50
09-02 19:07:12.835  7560  7560 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 19:07:12.835  7560  7560 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 19:07:12.836   320  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 19:07:12.836   320  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 19:07:12.836   320  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 19:07:12.836   320  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 19:07:12.836   320  1371 V AudioFlinger: createTrack() lSessionId: 23
09-02 19:07:12.836  7560  7798 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 19:07:12.837  7560  7560 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 19:07:12.837   320  1371 V AudioFlinger: acquiring 23 from 7560, for 7560
09-02 19:0,7:12.837   320  1371 V AudioFlinger:  added new entry for 23
09-02 19:07:12.837  7560  7560 V ToneGenerator: ToneGenerator INIT OK, time: 137137
09-02 19:07:12.837  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:12.838  7560  7821 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 19:07:12.838  7560  7821 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 19:07:12.839  7560  7821 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 19:07:12.839  7560  7821 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-02 19:07:12.839  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:12.840   320  2175 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7560
09-02 19:07:12.841   320  2175 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 19:07:12.841   320  2175 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 19:07:12.841   320  2175 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 19:07:12.841   320  2175 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 19:07:12.841   320  2175 V voice   : voice_set_parameters: exit with code(0)
09-02 19:07:12.841   320  2175 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 19:07:12.841   320  2175 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 19:07:12.841   320  2175 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 19:07:12.841   320  2175 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 19:07:12.841   320  2175 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 19:07:12.841   320  2175 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 19:07:12.841  7560  7821 V ToneGenerator: ToneGenerator destructor
09-02 19:07:12.841  7560  7821 V ToneGenerator: stopTone
09-02 19:07:12.841  7560  7821 V ToneGenerator: Delete Track: 0xb4928a80
09-02 19:07:12.841  7560  7821 V AudioTrack: ~AudioTrack, releasing session id from 7560 on behalf of 7560
09-02 19:07:12.841  7560  7560 D A2dpService: Received start request. Starting profile...
09-02 19:07:12.841   320  2174 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 19:07:12.842   320  2174 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 19:07:12.842   320  1370 V AudioFlinger: releasing 23 from 7560 for 7560
09-02 19:07:12.842   320  1370 V AudioFlinger:  decremented refcount to 0
09-02 19:07:12.842   320  2174 V AudioFlinger: PlaybackThread::Track destructor
09-02 19:07:12.842   320  1370 V AudioFlinger: purging stale effects
,09-02 19:07:12.842   320  1274 V AudioPolicyService: AudioCommandThread() waking up
09-02 19:07:12.842   320  2174 V AudioFlinger: removeClient_l() pid 7560, calling pid 320
09-02 19:07:12.842   320  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 19:07:12.842   320  1274 V AudioPolicyManager: releaseOutput() 2
09-02 19:07:12.842   320  1274 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 19:07:12.843  7560  7560 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 19:07:12.844  7560  7560 V Avrcp   : make
09-02 19:07:12.844  1044  1872 W Process : Unable to open /proc/7823/status
09-02 19:07:12.844  7560  7560 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 19:07:12.844  7560  7560 I bluedroid-qcom: get_profile_interface avrcp
,09-02 19:07:12.853  7560  7560 V AudioManager: registerRemoteController: size of Media player list: 0
09-02 19:07:12.855  7560  7560 E AudioManager: No RCC entry present to update
09-02 19:07:12.855  7560  7560 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 19:07:12.858  7560  7560 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 19:07:12.859  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 19:07:12.859  7560  7560 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-02 19:07:12.865  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 19:07:12.964  1044  1871 V SIM_STK : Menu title from STK is T-Mobile
09-02 19:07:12.964  1044  1871 V SIM_STK : Menu title from STK is T-Mobile
,09-02 19:07:13.090  1044  1581 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 19:07:13.098  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 19:07:13.102  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 19:07:13.103  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 19:07:13.104  7560  7560 I BluetoothA2dpServiceJni: classInitNative
09-02 19:07:13.104  7560  7560 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 19:07:13.104  7560  7560 D A2dpStateMachine: make
09-02 19:07:13.107  7560  7560 I bluedroid-qcom: get_profile_interface a2dp
,09-02 19:07:13.108  7560  7830 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 19:07:13.113  7560  7560 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 19:07:13.113  7560  7560 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 19:07:13.114  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:13.114  7560  7829 D A2dpStateMachine: Enter Disconnected: -2
09-02 19:07:13.116  7560  7560 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 19:07:13.117  7560  7560 D HidService: Received start request. Starting profile...
09-02 19:07:13.117  7560  7560 I bluedroid-qcom: get_profile_interface hidhost
,09-02 19:07:13.117  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:13.118  7560  7560 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 19:07:13.121  7560  7560 D HealthService: Received start request. Starting profile...
09-02 19:07:13.123  7560  7560 I bluedroid-qcom: get_profile_interface health
09-02 19:07:13.123  7560  7560 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 19:07:13.124  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:13.126  7560  7560 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 19:07:13.130  7560  7560 D PanService: Received start request. Starting profile...
,09-02 19:07:13.130  7560  7560 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 19:07:13.131  7560  7560 I bluedroid-qcom: get_profile_interface pan
09-02 19:07:13.148  7560  7560 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 19:07:13.149  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:13.152  7560  7560 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-02 19:07:13.165  7560  7560 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:07:13.166  7560  7560 D BtGatt.GattService: Received start request. Starting profile...
09-02 19:07:13.166  7560  7560 D BtGatt.GattService: start()
09-02 19:07:13.166  7560  7560 I bluedroid-qcom: get_profile_interface gatt
09-02 19:07:13.166  7560  7560 D BtGatt.AdvertiseManager: advertise manager created
09-02 19:07:13.179  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
,09-02 19:07:13.185  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:13.186  7560  7560 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 19:07:13.188  7560  7560 V BluetoothMapService: BluetoothMapBinder()
09-02 19:07:13.190  7560  7560 D BluetoothMapService: Received start request. Starting profile...
09-02 19:07:13.190  7560  7560 D BluetoothMapService: start()
09-02 19:07:13.197  7560  7560 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-02 19:07:13.197  7560  7560 D BluetoothMapEmailAppObserver: createReceiver()
09-02 19:07:13.199  7560  7560 D BluetoothMapEmailAppObserver: initObservers()
09-02 19:07:13.200  7560  7560 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-02 19:07:13.209  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:13.209  7560  7560 D HeadsetStateMachine: Proxy object connected
,09-02 19:07:13.210  7560  7560 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 19:07:13.211  7560  7560 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 19:07:13.216  7560  7560 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 19:07:13.217  7560  7821 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 19:07:13.217  7560  7821 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 19:07:13.218  7560  7821 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 19:07:13.223  7560  7560 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 19:07:13.225  7560  7560 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:13.231  7560  7560 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 19:07:13.236  7560  7560 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 19:07:13.236  7560  7560 V PanService: [BTUI] SIM Extra State :ABSENT
,09-02 19:07:13.242  7560  7560 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 19:07:13.247  7560  7560 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 19:07:13.247  7560  7560 V BluetoothMapService: Handler(): got msg=1
09-02 19:07:13.248  7560  7560 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 19:07:13.249  7560  7560 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 19:07:13.249  7560  7560 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 19:07:13.249  7560  7798 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-02 19:07:13.249  7560  7560 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:13.249  7560  7560 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-02 19:07:13.249  7560  7798 I bluedroid-qcom: enable
09-02 19:07:13.250  7560  7798 I bt_hci_bdroid: init
09-02 19:07:13.256  7560  7798 I bt_vendor: bt-vendor : init
09-02 19:07:13.256  7560  7798 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 19:07:13.256  7560  7798 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 19:07:13.256  7560  7798 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 19:07:13.256  7560  7798 D bt_userial_mct: userial_init
09-02 19:07:13.256  7560  7837 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 19:07:13.256  7560  7837 I bt-btu  : btu_task pending for preload complete event
09-02 19:07:13.257  7560  7798 D bt_hci_bdroid: set_power 1
09-02 19:07:13.257  7560  7798 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 19:07:13.257  7560  7798 I bt_vendor: Starting hciattach daemon
09-02 19:07:13.257  7560  7798 I bt_vendor: try to set true
09-02 19:07:13.257  7840  7840 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:13.257  7840  7840 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 19:07:13.313  7841  7841 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-02 19:07:13.418  7847  7847 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 19:07:13.434  7848  7848 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 19:07:13.479  7850  7850 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 19:07:13.493  7851  7851 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-02 19:07:13.506  7852  7852 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 19:07:13.519  7853  7853 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-02 19:07:13.556  7855  7855 I libmdmdetect: ESOC framework not supported
09-02 19:07:13.558  7855  7855 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 19:07:13.570  7855  7855 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-02 19:07:13.570  7855  7855 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 19:07:13.570  7855  7855 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 19:07:13.570  7855  7855 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 19:07:13.570  7855  7855 D bthci_qcomm_common: [BTUI]     LE: Class 2
,09-02 19:07:13.570  7855  7855 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 19:07:13.570  7855  7855 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-02 19:07:13.615  7855  7856 E QC-QMI  : qmi_client [7855] 15: failed to locate client data
09-02 19:07:13.616   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-02 19:07:13.616   479   479 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-02 19:07:13.664  7857  7857 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 19:07:13.680  7858  7858 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 19:07:13.712  7560  7798 I bt_vendor: bluetooth satus is on
09-02 19:07:13.712  7560  7798 D bt_hci_bdroid: preload
,09-02 19:07:13.712  7560  7839 D bt_userial_mct: userial_open(port:0)
09-02 19:07:13.712  7560  7839 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 19:07:13.716  7560  7839 I bt_vendor: Done intiailizing UART
09-02 19:07:13.717  7560  7839 I bt_vendor: Done intiailizing UART
09-02 19:07:13.717  7560  7839 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 19:07:13.717  7560  7839 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 19:07:13.717  7560  7837 I bt-btu  : btu_task received preload complete event
09-02 19:07:13.718  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 19:07:13.718  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 19:07:13.720  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-02 19:07:13.721  7560  7860 D bt_userial_mct: Entering userial_read_thread()
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 19:07:13.724  7560  7837 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 19:07:13.811  7560  7837 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-02 19:07:13.812  7560  7837 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0189061 
,09-02 19:07:13.812  7560  7837 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0189061 
,09-02 19:07:13.871  7560  7802 E bt-btif : Calling BTA_HhEnable
,09-02 19:07:13.871  7560  7802 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-02 19:07:13.872  7560  7802 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 19:07:13.880  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-02 19:07:13.880  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 19:07:13.880  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-02 19:07:13.881  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 19:07:13.881  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 19:07:13.884  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 19:07:13.884  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 19:07:13.885  7560  7802 D BluetoothAdapterProperties: Name is: G3
09-02 19:07:13.888  7560  7802 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:07:13.895  7560  7802 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:07:13.895  7560  7802 D bt_hci_bdroid: postload
09-02 19:07:13.896  7560  7839 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 19:07:13.897  7560  7837 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 19:07:13.897  7560  7837 W bt-smp  : Plain text(LSB ~ MSB) = d5 d6 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 19:07:13.897  7560  7837 W bt-smp  : Encrypted text(LSB ~ MSB) = 01 4f 94 55 93 a8 aa 1d 8d 44 fc bd bc e2 bd 90 
09-02 19:07:13.898  7560  7839 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 19:07:13.898  7560  7837 W bt-btm  : Stopping oneshot timer
09-02 19:07:13.898  7560  7839 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 19:07:13.900  7560  7837 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 19:07:13.901  7560  7802 D bte_conf: Device ID record 1 : primary
09-02 19:07:13.901  7560  7802 D bte_conf:   vendorId            = 00c4
09-02 19:07:13.901  7560  7802 D bte_conf:   vendorIdSource      = 0001
09-02 19:07:13.901  7560  7802 D bte_conf:   product             = 13a1
09-02 19:07:13.901  7560  7802 D bte_conf:   version             = 1000
09-02 19:07:13.901  7560  7802 D bte_conf:   clientExecutableURL = 
09-02 19:07:13.901  7560  7802 D bte_conf:   serviceDescription  = 
09-02 19:07:13.901  7560  7802 D bte_conf:   documentationURL    = 
09-02 19:07:13.901  7560  7802 D bte_conf: bte_load_did_conf no section named DID2.
09-02 19:07:13.903  7560  7839 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 19:07:13.907  7560  7860 E bt_mct  : hci lib postload completed
09-02 19:07:13.910  7560  7798 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 19:07:13.910  7560  7798 D BluetoothAdapterProperties: ScanMode =  20
09-02 19:07:13.910  7560  7798 D BluetoothAdapterProperties: State =  11
09-02 19:07:13.910  7560  7798 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 19:07:13.910  7560  7798 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 19:07:13.911  7560  7798 D BluetoothAdapterProperties: Setting state to 12
09-02 19:07:13.911  7560  7798 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 19:07:13.911  7560  7802 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 19:07:13.912  7560  7802 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 19:07:13.917  7868  7868 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 19:07:13.917  7868  7868 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 19:07:13.931  1044  1119 D BluetoothManagerService: Message: 60
09-02 19:07:13.931  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 19:07:13.931  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-02 19:07:13.931  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:13.939  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:07:13.965  7560  7798 I BluetoothAdapterState: Entering On State
,09-02 19:07:13.972  7560  7802 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:07:13.973  7560  7802 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 19:07:13.979  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:13.979  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:13.979  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:13.979  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:13.979  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:13.979  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:13.979  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:13.979  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:13.988  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:14.002  7560  7798 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 19:07:14.002  7560  7798 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-02 19:07:14.002  7560  7798 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-02 19:07:14.006  7560  7798 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 19:07:14.006  7560  7798 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-02 19:07:14.007  1044  1044 D BluetoothHeadset: Proxy object connected
09-02 19:07:14.020  1044  1044 D BluetoothA2dp: Proxy object connected
,09-02 19:07:14.026  6731  7475 D BluetoothPan: onBluetoothStateChange on: true
,09-02 19:07:14.027  6731  7475 D BluetoothPan: onBluetoothStateChange call bindService
09-02 19:07:14.039  6731  7475 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:07:14.048  6731  6731 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:07:14.048  6731  6731 D PanProfile: Bluetooth service connected
09-02 19:07:14.052  6731  6731 D BluetoothA2dp: Proxy object connected
09-02 19:07:14.052  6731  6731 D A2dpProfile: Bluetooth service connected
09-02 19:07:14.054  6731  6748 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 19:07:14.058  6731  7475 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 19:07:14.059  7882  7882 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-02 19:07:14.064  6731  6748 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 19:07:14.065  6731  6731 D BluetoothHeadset: Proxy object connected
09-02 19:07:14.065  6731  6731 D HeadsetProfile: Bluetooth service connected
09-02 19:07:14.065  6731  6747 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 19:07:14.070  1837  3939 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:14.072  6731  6731 D BluetoothInputDevice: Proxy object connected
09-02 19:07:14.072  6731  6731 D HidProfile: Bluetooth service connected
09-02 19:07:14.073  6731  6731 D BluetoothMap: Proxy object connected
09-02 19:07:14.073  1837  1837 D BluetoothHeadset: Proxy object connected
09-02 19:07:14.073  6731  6731 D MapProfile: Bluetooth service connected
09-02 19:07:14.073  6731  6731 D BluetoothMap: getConnectedDevices()
09-02 19:07:14.074  7560  7576 V BluetoothMapService: getConnectedDevices()
09-02 19:07:14.075  1837  3942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:14.077  1837  1837 D BluetoothHeadset: Proxy object connected
09-02 19:07:14.078  1837  2557 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 19:07:14.080  1837  1837 D BluetoothHeadset: Proxy object connected
09-02 19:07:14.083  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 19:07:14.083  1044  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 19:07:14.083  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-02 19:07:14.084  1044  1119 D BluetoothManagerService: Message: 40
09-02 19:07:14.084  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 19:07:14.087  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:14.087  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 19:07:14.090  1927  2104 D LGBluetoothAPIService: Message: 1
09-02 19:07:14.090  1927  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 19:07:14.090  1927  2104 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
,09-02 19:07:14.090  1927  2104 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-02 19:07:14.094  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:14.100  7560  7560 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:14.100  7560  7560 D BluetoothMapService: STATE_ON
09-02 19:07:14.106  6731  6731 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-02 19:07:14.109  6731  6731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 19:07:14.118  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
,09-02 19:07:14.118  7560  7560 V BluetoothPbapService: Pbap Service onCreate
09-02 19:07:14.118  7560  7560 V BluetoothPbapService: Starting PBAP service
09-02 19:07:14.120  7560  7560 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 19:07:14.121  7560  7560 V BluetoothMapService: Handler(): got msg=1
09-02 19:07:14.121  6731  6731 D DockEventReceiver: finishStartingService: stopping service
09-02 19:07:14.121  7560  7560 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 19:07:14.122  7560  7560 V BluetoothPbapService: Pbap Service onBind
09-02 19:07:14.123  7560  7560 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:14.123  7560  7560 V BluetoothPbapService: state: 12
09-02 19:07:14.123  7560  7560 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 19:07:14.123  7560  7560 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:14.123  7560  7892 D BluetoothMapMasInstance: MAS initSocket()
09-02 19:07:14.123  6731  6731 D BluetoothPbap: Proxy object connected
09-02 19:07:14.123  7560  7560 V BluetoothPbapReceiver: ***********state = 12
09-02 19:07:14.123  6731  6731 D PbapServerProfile: Bluetooth service connected
09-02 19:07:14.124  7560  7892 D BluetoothMapMasInstance:   masId = 00
09-02 19:07:14.124  7560  7892 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 19:07:14.124  7560  7892 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 19:07:14.124  7560  7892 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 19:07:14.126  7560  7560 V BluetoothPbapService: Handler(): got msg=1
09-02 19:07:14.127  7560  7560 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 19:07:14.128  7560  7893 V BluetoothPbapService: Pbap Service initSocket
09-02 19:07:14.129  1044  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:14.130  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:14.132  7560  7893 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:07:14.133  7560  7892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:14.137  2176  2176 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:07:14.138  2176  2176 D c       : Getting all permits...
09-02 19:07:14.138  2176  2176 D a       : Opening database...
09-02 19:07:14.139  7560  7893 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 19:07:14.139  7560  7893 V BluetoothPbapService: Succeed to create listening socket 
09-02 19:07:14.140  7560  7893 V BluetoothPbapService: Accepting socket connection...
09-02 19:07:14.141  7560  7892 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 19:07:14.141  7560  7802 D BluetoothAdapterProperties: Scan Mode:21
09-02 19:07:14.141  7560  7892 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 19:07:14.141  7560  7892 D BluetoothMapMasInstance: Accepting socket connection...
09-02 19:07:14.141  7560  7802 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 19:07:14.144  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:14.145  2176  2176 D a       : Opening database auth.proximity.permit_store...
,09-02 19:07:14.146  2176  2176 D a       : Closing database...
,09-02 19:07:14.160  6731  6731 D BluetoothPermissionRequest: onReceive
,09-02 19:07:14.162  6731  6731 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 19:07:14.164  6731  6731 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 19:07:14.167  7560  7560 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 19:07:14.169  7560  7560 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 19:07:14.181  7560  7560 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-02 19:07:14.216  7560  7560 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-02 19:07:14.216  7560  7560 V BtOppService: onCreate
,09-02 19:07:14.222  7560  7560 V BluetoothOppNotification: send message
09-02 19:07:14.226  7560  7560 V BtOppService: Starting RfcommListener
09-02 19:07:14.236  7560  7560 D BluetoothOppPreference: Dumping Names:  
09-02 19:07:14.236  7560  7560 D BluetoothOppPreference: {}
09-02 19:07:14.236  7560  7560 D BluetoothOppPreference: Dumping Channels:  
,09-02 19:07:14.236  7560  7560 D BluetoothOppPreference: {}
09-02 19:07:14.237  7560  7560 V BtOppService: onStartCommand
09-02 19:07:14.242  7560  7560 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:14.242  7560  7900 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 19:07:14.242  7560  7560 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 19:07:14.246  7560  7560 V BluetoothOppNotification: new notify threadi!
09-02 19:07:14.247  7560  7560 V BluetoothOppNotification: send delay message
09-02 19:07:14.248  7560  7560 V BtOppService: start RfcommListener
09-02 19:07:14.251  7560  7560 V BtOppService: RfcommListener started
09-02 19:07:14.252  7560  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-02 19:07:14.255  7560  7897 V BtOppService: Deleted complete outbound shares, number =  0
09-02 19:07:14.262  7560  7901 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 19:07:14.263  7560  7902 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 19:07:14.263  1044  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:14.264  7560  7902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:14.266  7560  7902 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-02 19:07:14.266  7560  7902 V BtOppRfcommListener: Started RFCOMM listener....
09-02 19:07:14.266  7560  7902 I BtOppRfcommListener: Accept thread started.
09-02 19:07:14.266  7560  7902 V BtOppRfcommListener: Accepting connection...
09-02 19:07:14.267  7560  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c102eba on behalf of 
09-02 19:07:14.273  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
09-02 19:07:14.273  7560  7560 V BluetoothFtpService: Ftp Service onCreate
09-02 19:07:14.273  7560  7560 I BluetoothFtpService: Ftp Service onCreate
09-02 19:07:14.274  7560  7560 V BluetoothFtpService: Ftp Service onStartCommand
09-02 19:07:14.274  7560  7560 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:14.274  7560  7560 V BluetoothFtpService: Starting Listening on sockets
09-02 19:07:14.274  7560  7560 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 19:07:14.274  7560  7560 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 19:07:14.274  7560  7560 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 19:07:14.274  7560  7560 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:14.274  7560  7560 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 19:07:14.275  7560  7560 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 19:07:14.276  7560  7897 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 19:07:14.277  7560  7897 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,09-02 19:07:14.403  1044  1998 I art     : Explicit concurrent mark sweep GC freed 24607(1218KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.421ms total 132.559ms
09-02 19:07:14.404  7560  7901 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@384f24c8 on behalf of 
,09-02 19:07:14.404  7560  7901 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 19:07:14.405  7560  7901 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-02 19:07:14.406  7560  7901 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1197c961 on behalf of 
09-02 19:07:14.406  7560  7901 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 19:07:14.407  7560  7560 V BtOppService: ContentObserver received notification
09-02 19:07:14.408  7560  7560 V BtOppService: ContentObserver received notification
09-02 19:07:14.408  7560  7560 V BluetoothFtpService: Handler(): got msg=1
09-02 19:07:14.408  7560  7901 V BluetoothOppNotification: outbound notification was removed.
09-02 19:07:14.408  7560  7901 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 19:07:14.408  7560  7897 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f027c86 on behalf of 
09-02 19:07:14.412  7560  7901 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ba40947 on behalf of 
09-02 19:07:14.412  7560  7560 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 19:07:14.412  7560  7901 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 19:07:14.413  7560  7560 V BluetoothFtpService: Ftp Service initSocket
09-02 19:07:14.414  7560  7901 V BluetoothOppNotification: inbound notification was removed.
09-02 19:07:14.415  7560  7901 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 19:07:14.414  7560  7900 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 19:07:14.415  7560  7900 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 19:07:14.417  1044  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:14.418  7560  7900 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2395c574 on behalf of 
09-02 19:07:14.419  7560  7901 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34a69a9d on behalf of 
09-02 19:07:14.419  7560  7560 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:07:14.420  7560  7900 V BluetoothOppNotification: update too frequent, put in queue
09-02 19:07:14.422  7560  7560 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
09-02 19:07:14.422  7560  7900 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-02 19:07:14.423  7560  7560 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 19:07:14.427  7560  7903 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-02 19:07:14.442  7560  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30d1b9e
,09-02 19:07:14.443  7560  7560 V BluetoothSapService: Sap Service onCreate
09-02 19:07:14.446  7560  7560 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:14.446  7560  7560 V BluetoothSapService: state: 12
09-02 19:07:14.446  7560  7560 V BluetoothSapService: Starting SAP server process
09-02 19:07:14.447  7560  7560 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 19:07:14.448  7560  7905 V BluetoothSapService: Sap Service initRfcommSocket
09-02 19:07:14.449  1044  1581 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:14.449  7560  7905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:07:14.450  7560  7905 V BluetoothSapService: Succeed to create listening socket 
09-02 19:07:14.437  7906  7906 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:14.450  7560  7905 V BluetoothSapService: Accepting socket connection...
09-02 19:07:14.437  7906  7906 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:14.461  7906  7906 V BT_SAP  : Event pipe created
09-02 19:07:14.461  7906  7906 V BT_SAP  : create_server_socket qcom.sap.server
09-02 19:07:14.461  7906  7906 V BT_SAP  : created socket fd 6
,09-02 19:07:14.667  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:14.667  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:14.667  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:14.667  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:14.667  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:14.667  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:14.667  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:14.667  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:14.672  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:14.677  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:14.677  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a41b03 added. We now have 8 listener(s)
09-02 19:07:14.677  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:14.684  1044  1871 D WifiServiceImplEx: setWifiEnabled: false pid=6536, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 19:07:14.684  1044  1871 D WifiService: setWifiEnabled: false pid=6536, uid=10118
09-02 19:07:14.684  1044  1871 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:07:14.702  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:14.704  1044  1998 D WifiServiceImplEx: setWifiEnabled: true pid=6536, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 19:07:14.706  1044  1998 D WifiService: setWifiEnabled: true pid=6536, uid=10118
09-02 19:07:14.706  1044  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:07:14.733  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 19:07:14.733  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 19:07:14.734  1044  1044 D Ulp_jni : JNI:system_update. Event-4
09-02 19:07:14.736  1044  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-02 19:07:14.736  1044  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-02 19:07:14.741  1044  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 19:07:14.741  1044  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 19:07:14.741  1044  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 19:07:14.741  1044  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 19:07:14.742  1044  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 19:07:14.742  1044  1523 E WifiHW  : unknown target_country: EU , set to default
09-02 19:07:14.742  1044  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 19:07:14.742  1044  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-02 19:07:14.742  1044  1523 I WifiUtil: gEnableBmps=1
09-02 19:07:15.249  7560  7560 V BluetoothOppNotification: new notify threadi!
09-02 19:07:15.249  7560  7560 V BluetoothOppNotification: send delay message
,09-02 19:07:15.256  7560  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 19:07:15.257  7560  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11d74399 on behalf of 
09-02 19:07:15.258  7560  7925 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 19:07:15.281  7560  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-02 19:07:15.306  7560  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1096965e on behalf of 
,09-02 19:07:15.309  7560  7925 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-02 19:07:15.311  7560  7925 V BluetoothOppNotification: outbound notification was removed.
09-02 19:07:15.311  7560  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 19:07:15.312  7560  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ca2da3f on behalf of 
,09-02 19:07:15.312  7560  7925 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 19:07:15.314  7560  7925 V BluetoothOppNotification: inbound notification was removed.
09-02 19:07:15.314  7560  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 19:07:15.315  7560  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b904f0c on behalf of 
09-02 19:07:15.385   316   916 D SoftapController: Softap fwReload - Ok
,09-02 19:07:15.390  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:07:15.394  1044  1523 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (641ms)
09-02 19:07:15.404   316   916 D CommandListener: Setting iface cfg
09-02 19:07:15.404   316   916 D CommandListener: Trying to bring down wlan0
,09-02 19:07:15.421   316   916 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:07:15.424  1044  1119 D Tethering: InitialState.processMessage what=4
09-02 19:07:15.426  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:07:15.432  1044  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 19:07:15.437  7927  7927 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 19:07:15.447  7927  7927 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:15.470  1044  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 19:07:15.470  1044  1523 E WifiStateMachine: useWiFiOffloading() : false
09-02 19:07:15.470  1044  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-02 19:07:15.475  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:15.476  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-02 19:07:15.507  1044  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 19:07:15.507  1044  1523 D WifiMonitor: connecting to supplicant
,09-02 19:07:15.509  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-02 19:07:15.512  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:15.514  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 19:07:15.515  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 19:07:15.515  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 19:07:15.515  6731  6731 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 19:07:15.516  7927  7927 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 19:07:15.517  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 19:07:15.518  6731  6731 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 19:07:15.519  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 19:07:15.519  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 19:07:15.519  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 19:07:15.519  6731  6731 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 19:07:15.519  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 19:07:15.520  6731  6731 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 19:07:15.525  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 19:07:15.525  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 19:07:15.525  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 19:07:15.525  6731  6731 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 19:07:15.526  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 19:07:15.526  6731  6731 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 19:07:15.526  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 19:07:15.526  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 19:07:15.527  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 19:07:15.527  6731  6731 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 19:07:15.527  6731  6731 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-02 19:07:15.554  7927  7927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 19:07:15.555  7927  7927 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-02 19:07:15.571  1044  1559 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7945 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-02 19:07:15.587   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 389us total 19.258ms
,09-02 19:07:15.605   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 282us total 16.888ms
,09-02 19:07:15.619   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.302ms
,09-02 19:07:15.636  7927  7927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 19:07:15.677  1044  1581 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 19:07:15.682  7945  7965 W FormManager: Network not available. Please check & try again.
09-02 19:07:15.687  7660  7671 E UEI.SmartControl: file observer is disposed!
09-02 19:07:15.687  7945  7966 V FormManager: Network unavailable.
09-02 19:07:15.689  7945  7966 V FormManager: Network unavailable.
,09-02 19:07:15.699  1044  1871 I ActivityManager: Killing 7030:com.android.chrome/u0a57 (adj 15): empty #17
09-02 19:07:15.704  7927  7927 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-02 19:07:15.712  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-02 19:07:15.713  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-02 19:07:15.713  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 19:07:15.713  1044  7985 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,09-02 19:07:15.713  1044  7985 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 19:07:15.713  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 19:07:15.713  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 19:07:15.713  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 19:07:15.713  1044  7985 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 19:07:15.713  1044  7985 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 19:07:15.714  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 19:07:15.714  1044  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 19:07:15.715  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:15.715  1044  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:15.715  1044  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:15.716  1044  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:15.716  1044  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 19:07:15.716  1044  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 19:07:15.717  1044  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 19:07:15.717  1044  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 19:07:15.717  1044  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 19:07:15.748  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:15.748  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:15.748  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:15.748  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:15.748  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:15.748  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:15.748  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:15.748  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:15.751  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:15.758  6536  6649 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-02 19:07:15.758  6536  6649 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-02 19:07:15.761  6536  6649 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3258234d Bundle[{}]
09-02 19:07:15.762  6536  6649 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 19:07:15.762  6536  6649 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-02 19:07:15.763  6536  6649 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-02 19:07:15.764  6536  6649 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-02 19:07:15.765  6536  6649 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-02 19:07:15.766  6536  6649 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 19:07:15.774  6536  6649 I System.out: Running OutgoingSocketThread
,09-02 19:07:15.781  6536  7986 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 852)
,09-02 19:07:15.785  6536  7986 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54868
09-02 19:07:15.785  6536  7986 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 19:07:15.799  1044  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 19:07:15.799  1044  1523 E WifiStateMachine: useWiFiOffloading() : false
09-02 19:07:15.799  1044  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 19:07:15.800  1044  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 19:07:15.801  1044  1060 W libprocessgroup: failed to open /acct/uid_10057/pid_7030/cgroup.procs: No such file or directory
09-02 19:07:15.801  1044  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-02 19:07:15.801  1044  1523 D WifiConfigStore: Loading config and enabling all networks 
,09-02 19:07:15.801  1044  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 19:07:15.803  1044  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-02 19:07:15.806  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:15.806  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:15.807  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:15.807  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:15.807  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 19:07:15.807  1927  1927 D WfdService: Waiting for WifiP2p enabling
09-02 19:07:15.808  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 19:07:15.809  1044  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 19:07:15.811  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:15.813  1044  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 19:07:15.816  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:15.816  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:15.816  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:15.816  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:15.816  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:15.816  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:15.816  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:15.816  6536  6536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:15.818  6536  6536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:15.826  1044  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-02 19:07:15.826  1044  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 19:07:15.827  1044  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-02 19:07:15.827  1044  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-02 19:07:15.828  1044  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,09-02 19:07:15.828  1044  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 19:07:15.828  1044  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 19:07:15.828  1044  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 19:07:15.829  1044  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 19:07:15.829  1044  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 19:07:15.829  1044  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 19:07:15.829  1044  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 19:07:15.830  1044  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 19:07:15.830  1044  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-02 19:07:15.831  1044  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 19:07:15.831  1044  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,09-02 19:07:15.831  1044  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 19:07:15.832  1044  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 19:07:15.832  1044  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 19:07:15.833  1044  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 19:07:15.833  1044  1523 D WifiNative-HAL: Setting external_sim to 1
09-02 19:07:15.833  1044  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 19:07:15.833  1927  1927 D WfdsService: Supplicant Connection state is changed : true
09-02 19:07:15.833  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 19:07:15.833  1044  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 19:07:15.833  1044  1523 I WifiNative-HAL: startHal
09-02 19:07:15.833  1927  2296 D WfdsService: Set the WFDS Monitor: true
09-02 19:07:15.833  1044  1523 D wifi    : setting scan oui 0x95275f80
09-02 19:07:15.833  1927  2296 D WfdsMonitor: WfdsMonitorThread create
09-02 19:07:15.834  1927  2296 D WfdsMonitor: WFDS Monitor is created and started
09-02 19:07:15.834  1044  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 19:07:15.834  1927  2296 D WfdsService: WiFi: Supplicant connection re-established
09-02 19:07:15.834  7588  7588 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:15.834  1044  1523 I WifiNative-HAL: startHal
09-02 19:07:15.834  1044  1523 D wifi    : setting scan oui 0x95275f80
09-02 19:07:15.834  1044  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 19:07:15.835  1927  7987 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 19:07:15.835  1044  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 19:07:15.835  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 19:07:15.835  1927  7987 E CtrlSupplicant: Succeed to open control connection
09-02 19:07:15.836  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 19:07:15.836  1927  7987 E CtrlSupplicant: Succeed to open monitor connection
09-02 19:07:15.836  1927  7987 D WfdsMonitor: Supplicant connection established
09-02 19:07:15.836  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-02 19:07:15.836  1927  2296 D WfdsService: Connected to the supplicant for wfds
09-02 19:07:15.836  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 19:07:15.837  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 19:07:15.837  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 19:07:15.837  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 19:07:15.837  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 19:07:15.838  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 19:07:15.838  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 19:07:15.838  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 19:07:15.838  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 19:07:15.838  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 19:07:15.838  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 19:07:15.839  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 19:07:15.839  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 19:07:15.839  7927  7927 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 19:07:15.839  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 19:07:15.839  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 19:07:15.839  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 19:07:15.840  1044  1523 D WifiNative-wlan0: DRIVER RXFILTER-ST,ART: returned true
09-02 19:07:15.841  1044  1523 E WifiNative: : [140,125,951 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 19:07:15.841  1044  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 19:07:15.842  1044  1523 D WifiNative-wlan0: RECONNECT: returned true
09-02 19:07:15.842  1044  1523 D WifiNative-wlan0: doString: [STATUS]
09-02 19:07:15.842  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 19:07:15.842  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 19:07:15.842  1044  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 19:07:15.842  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 19:07:15.843  1044  1523 D WifiNative-wlan0: SET ps 1: returned true
09-02 19:07:15.843  1044  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:07:15.845   316   916 D CommandListener: Setting iface cfg
09-02 19:07:15.845   316   916 D CommandListener: Trying to bring up p2p0
09-02 19:07:15.845  1044  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 19:07:15.845  1044  1521 D LGWifiP2pService: P2pEnablingState
09-02 19:07:15.845  1044  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.846  1044  1521 D LGWifiP2pService: P2p socket connection successful
09-02 19:07:15.846  1044  1521 D LGWifiP2pService: P2pEnabledState
09-02 19:07:15.847  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 19:07:15.848  1927  1927 D WfdsService: WifiP2pState is changed : true
09-02 19:07:15.848  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 19:07:15.848  1927  2296 D WfdsService: Receive the WFDS_ENABLE Method
09-02 19:07:15.848  1927  2296 D WfdsService: Set the WFDS Monitor: true
09-02 19:07:15.848  1044  1044 D RttService: SCAN_AVAILABLE : 3
09-02 19:07:15.848  1927  2296 D WfdsService: Connected to the supplicant for wfds
09-02 19:07:15.848  1927  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 19:07:15.848  1044  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.848  1044  1540 I WifiNative-HAL: startHal
09-02 19:07:15.848  7927  7927 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 19:07:15.848  1044  1540 D wifi    : getting scan capabilities on interface[1] = 0x95275f80
09-02 19:07:15.848  1044  1540 D wifi    : failed to get capabilities : -3
09-02 19:07:15.848  1044  1540 E WifiScanningService: could not get scan capabilities
09-02 19:07:15.848  1927  2296 D WfdsService: selectPreferredScanChannel [36]
09-02 19:07:15.848  1927  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-02 19:07:15.848  1044  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.849  1044  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 19:07:15.849  1044  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 19:07:15.850  1044  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 19:07:15.850  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 19:07:15.850  1927  1927 D WfdsService: isConnected: false
09-02 19:07:15.851  1044  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-02 19:07:15.851  1044  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-02 19:07:15.851  1044  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 19:07:15.851  1044  1521 D LGWifiP2pService: before postfix = G3
09-02 19:07:15.851  1044  1521 D WifiServerServiceExt: postfix byte check : 2
09-02 19:07:15.851  1044  1521 D LGWifiP2pService: after postfix = G3
,09-02 19:07:15.851  1044  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 19:07:15.852  1044  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 19:07:15.852  1044  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 19:07:15.853  1044  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 19:07:15.853  1044  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 19:07:15.853  1044  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 19:07:15.853  1044  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 19:07:15.853  1044  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 19:07:15.853  1044  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 19:07:15.854  1044  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 19:07:15.854  1044  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-02 19:07:15.854  1044  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 19:07:15.854  1044  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-02 19:07:15.854  1044  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 19:07:15.855  1044  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 19:07:15.856  1044  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-02 19:07:15.856  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 19:07:15.856  1044  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 19:07:15.856  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 19:07:15.856  1927  1927 D WfdsService: Update P2p Interface State: 3
09-02 19:07:15.856  1044  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 19:07:15.856  1044  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 19:07:15.857  1044  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-02 19:07:15.857  1044  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 19:07:15.857  1044  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 19:07:15.857  1044  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 19:07:15.857  1044  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 19:07:15.858  7927  7927 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 19:07:15.858  1044  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 19:07:15.858  1044  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 19:07:15.858  1044  1521 D WifiNative-p2p0:    returned OK
09-02 19:07:15.858  1044  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 19:07:15.858  1044  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 19:07:15.858  1044  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,09-02 19:07:15.865  7967  7967 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:07:15.869  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 19:07:15.870  7927  7927 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 19:07:15.870  1044  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-02 19:07:15.870  1044  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 19:07:15.870  1044  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-02 19:07:15.870  1044  1521 D LGWifiP2pService: InactiveState
09-02 19:07:15.870  1044  1521 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.870  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.870  1044  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 19:07:15.871  1044  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 19:07:15.871  1044  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 19:07:15.871  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 19:07:15.871  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 19:07:15.872  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:07:15.872  1044  7985 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 19:07:15.872  1044  7985 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:07:15.872  1927  7987 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 19:07:15.872  1044  7985 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:07:15.872  1044  7985 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:07:15.872  7927  7927 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 19:07:15.873  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.873  1927  7987 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:07:15.873  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.873  1044  7985 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:07:15.873  1044  7985 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.873  1927  7987 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:07:15.873  1044  7985 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.873  1044  7985 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.874  1044  7985 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:07:15.874  1044  7985 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.874  1044  7985 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.874  1044  7985 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.874  1044  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 19:07:15.874  1044  1521 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.874  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.874  1044  1521 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.875  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 19:07:15.875  1044  1521 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.875  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.875  1044  1521 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.,android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.875  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:07:15.876  7927  7927 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 19:07:15.876  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.877  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.877  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:15.878  1927  7987 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:07:15.878  1927  7987 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:07:15.878  1927  2296 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 19:07:15.878  1044  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 19:07:15.878  1044  1871 I ActivityManager: Killing 7054:com.lge.drmservice/u0a62 (adj 15): empty #17
09-02 19:07:15.879  1044  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 19:07:15.879  1044  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 19:07:15.879  1044  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 19:07:15.879  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 19:07:15.880  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 19:07:15.880  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 19:07:15.881  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 19:07:15.881  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:07:15.881  1044  7985 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:07:15.881  1044  7985 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 19:07:15.881  1044  7985 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:07:15.881  1044  7985 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.881  1044  7985 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.881  1044  7985 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.881  1044  7985 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 19:07:15.881  1044  7985 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.881  1044  7985 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-02 19:07:15.881  1044  7985 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 19:07:15.881  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 19:07:15.881  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 19:07:15.881  1044  7985 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 19:07:15.881  1044  7985 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 19:07:15.882  1044  1521 D LGWifiP2pService: InactiveState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.882  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.882  1044  1521 D LGWifiP2pService: DefaultState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.882  1044  1521 D LGWifiP2pService: InactiveState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.882  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:07:15.882  1044  1521 D LGWifiP2pService: DefaultState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.882  1044  1044 E WifiServerServiceExt: No p2p device connected
09-02 19:07:15.882  1044  1521 D LGWifiP2pService: InactiveState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.882  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:15.882  1044  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 19:07:15.882  1044  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-02 19:07:15.883  1044  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 19:07:15.883  1044  1523 D WifiNative-wlan0: doBoolean: SCAN
09-02 19:07:15.883  1044  1523 D WifiNative-wlan0: SCAN: returned false
09-02 19:07:15.884  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=140169  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 19:07:15.944  1044  1872 W libprocessgroup: failed to open /acct/uid_10062/pid_7054/cgroup.procs: No such file or directory
09-02 19:07:15.945  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=140230  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 19:07:15.946  1044  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-02 19:07:15.947  1044  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 19:07:15.948  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:15.948  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:15.948  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 19:07:15.949  1044  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 19:07:15.950  1044  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 19:07:15.950  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:15.950  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:15.951  1044  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 19:07:15.953  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:15.953  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:07:15.953  1044  1044 D WifiServerServiceExt: setSupplicantStateSCANNING
09-02 19:07:15.974  7967  7967 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 19:07:15.980  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 19:07:15.985  7945  7991 W FormManager: Network not available. Please check & try again.
,09-02 19:07:15.992  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:16.000  7945  7992 V FormManager: Network unavailable.
,09-02 19:07:16.008  7945  7992 V FormManager: Network unavailable.
09-02 19:07:16.024  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 19:07:16.024  4268  4268 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-02 19:07:16.027  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:16.029  4268  4268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 19:07:16.039  4268  7993 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 19:07:16.051  4268  7994 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-02 19:07:16.051  4268  7994 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 19:07:16.100  1044  2017 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7995 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 19:07:16.246  7995  7995 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 19:07:16.246  7995  7995 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-02 19:07:16.258  7995  7995 V [BNRBootReceiver]: Boot Receiver Return
,09-02 19:07:16.259  7995  7995 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-02 19:07:16.316  1044  1962 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8016 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 19:07:16.321  1044  1962 I ActivityManager: Killing 7084:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-02 19:07:16.354  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 19:07:16.354  1044  7985 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 19:07:16.354  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 19:07:16.354  7927  7927 E wpa_supplicant: USIM:  scard_init function
09-02 19:07:16.354  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: WPS-AP-AVAILABLE 
09-02 19:07:16.354  1044  7985 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 19:07:16.354  7927  7927 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-02 19:07:16.355  1044  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-02 19:07:16.355  1044  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-02 19:07:16.356  1044  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-02 19:07:16.356  1044  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-02 19:07:16.356  1044  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-02 19:07:16.358  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 19:07:16.358  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 19:07:16.372  1044  1581 W libprocessgroup: failed to open /acct/uid_10085/pid_7084/cgroup.procs: No such file or directory
,09-02 19:07:16.380  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=140665  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 19:07:16.382  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.382  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:16.383  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.383  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.384  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.384  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 19:07:16.385  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=140670  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 19:07:16.389  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.389  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.389  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 19:07:16.389  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:07:16.389  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-02 19:07:16.407  8016  8016 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 19:07:16.408  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.408  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 19:07:16.412  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.430  8016  8016 D PluginManager: init()
,09-02 19:07:16.467  7927  7927 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 19:07:16.469  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 19:07:16.469  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-02 19:07:16.470  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 19:07:16.470  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 19:07:16.472  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=140758  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 19:07:16.474  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:07:16.475  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 19:07:16.476  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=140761  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 19:07:16.477  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:07:16.477  1044  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140763
09-02 19:07:16.481  1044  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140766
09-02 19:07:16.481  1044  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140767
09-02 19:07:16.481  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140767
,09-02 19:07:16.482  1044  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140768
09-02 19:07:16.483  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 19:07:16.485  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.485  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 19:07:16.485  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.485  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.486  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 19:07:16.486  7927  7927 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:07:16.486  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 19:07:16.488  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:07:16.488  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 19:07:16.490  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 19:07:16.490  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:07:16.490  1044  7985 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:07:16.491  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 19:07:16.491  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 19:07:16.491  1044  7985 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 19:07:16.491  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:07:16.491  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 19:07:16.493  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.493  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.493  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 19:07:16.497  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140782  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 19:07:16.497  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.498  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:07:16.498  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 19:07:16.499  1044  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:16.499  1044  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:16.499  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.500  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:16.500  1044  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:16.500  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:16.501  1044  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 19:07:16.501  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.501  1044  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140787  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 19:07:16.502  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140788  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 19:07:16.503  1044  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140788
09-02 19:07:16.503  1044  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140789
,09-02 19:07:16.504  1044  1523 D WifiNative-wlan0: doString: [STATUS]
09-02 19:07:16.504  1044  7985 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 19:07:16.504  1044  7985 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 19:07:16.504  1044  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 19:07:16.506  1044  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-02 19:07:16.513  1044  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 19:07:16.513  1044  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-02 19:07:16.517  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:16.517  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.517  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 19:07:16.519  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.519  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:16.522  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.522  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.522  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.522  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 19:07:16.523  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.523  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:16.524  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.529  1044  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 19:07:16.529  1044  1529 D ConnectivityService: Got NetworkAgent Messenger
09-02 19:07:16.529  1044  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 19:07:16.529  1044  1529 D ConnectivityService: NetworkAgent connected
09-02 19:07:16.529  1044  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:07:16.529  1044  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 19:07:16.530  1044  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 19:07:16.530  1044  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-02 19:07:16.536  1044  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 19:07:16.536  1044  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:07:16.536  1044  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 19:07:16.537  1044  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 19:07:16.537  1044  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 19:07:16.540  1044  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 19:07:16.542   316   916 D CommandListener: Setting iface cfg
,09-02 19:07:16.546  1044  1523 E WifiStateMachine: Start Dhcp Watchdog 3
09-02 19:07:16.546  1044  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:07:16.547  1044  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:07:16.547  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:07:16.548  1044  8034 D DhcpStateMachine: StoppedState
09-02 19:07:16.548  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:07:16.548  1044  8034 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:16.548  1044  1044 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-02 19:07:16.548  1044  8034 D DhcpStateMachine: WaitBeforeStartState
09-02 19:07:16.549  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:07:16.549  1044  1044 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-02 19:07:16.549  1044  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=140835  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:07:16.550  1044  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=140835  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:07:16.550  1044  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=140836  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 19:07:16.552  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14317] from screen [on:0 period:-337745976] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 19:07:16.553  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-337745976] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 19:07:16.553  1044  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-02 19:07:16.556  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.557  1044  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-02 19:07:16.558  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.558  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.558  1044  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.559  1044  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.559  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.560  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 19:07:16.560  1044  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 19:07:16.564  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 19:07:16.564  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 19:07:16.566  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=171,0,0
09-02 19:07:16.567  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=171,0,0
09-02 19:07:16.567  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 19:07:16.568  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 19:07:16.568  1044  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 19:07:16.568  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 19:07:16.569  1044  1523 D WifiNative-wlan0: SET ps 0: returned true
09-02 19:07:16.569  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 19:07:16.569  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 19:07:16.570  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 19:07:16.570  1044  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 19:07:16.570  1044  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 19:07:16.570  1044  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35b395f2 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:16.570  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35b395f2 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:16.570  1044  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 19:07:16.571  1044  8034 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:16.571  1044  8034 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 19:07:16.571   316   916 D CommandListener: Setting iface cfg
09-02 19:07:16.571   316   916 D CommandListener: Trying to bring up wlan0
,09-02 19:07:16.572  1044  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-02 19:07:16.575  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-02 19:07:16.575  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 19:07:16.577  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.578  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.579  1044  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.580  1044  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.581  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.582  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 19:07:16.582  1044  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 19:07:16.583  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 19:07:16.584  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 19:07:16.584  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 19:07:16.584  1044  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:16.584  1044  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:16.585  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-02 19:07:16.585  1044  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 19:07:16.586  1044  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 19:07:16.586  7927  7927 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 19:07:16.587  1044  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 19:07:16.587  1044  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 19:07:16.603  1044  1523 D WifiNative-wlan0: SET ps 1: returned true
,09-02 19:07:16.604  1044  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 19:07:16.604  1044  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 19:07:16.605  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 19:07:16.605  1044  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 19:07:16.606  1044  1529 D ConnectivityService: ignoring duplicate network state non-change
09-02 19:07:16.610  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.610  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:16.611  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.613  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.613  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.613  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 19:07:16.615  1044  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 19:07:16.615  1044  1529 D ConnectivityService: Adding iface wlan0 to network 102
,09-02 19:07:16.621  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.621  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.621  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-02 19:07:16.625  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 19:07:16.629  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-02 19:07:16.632  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.632  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.632  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 19:07:16.633  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.633  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 19:07:16.634  1044  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 19:07:16.634  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 19:07:16.638  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 19:07:16.641  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.642  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 19:07:16.642  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.643  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.643  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:07:16.643  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 19:07:16.649  1044  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 19:07:16.649  1044  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-02 19:07:16.650  1044  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-02 19:07:16.651   316   916 E Netd    : netlink response contains error (File exists)
09-02 19:07:16.652  1044  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-02 19:07:16.652  1044  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 19:07:16.652  1044  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-02 19:07:16.652  1044  1529 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-02 19:07:16.653  1044  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 19:07:16.653  1044  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 19:07:16.654  1044  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-02 19:07:16.654  1044  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-02 19:07:16.654  1044  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:16.654  1044  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:16.654  1044  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 19:07:16.654  1044  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.654  1044  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:16.654  1044  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 19:07:16.655  1044  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:16.655  1044  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 19:07:16.656  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:16.656  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 19:07:16.656  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.657  1044  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 19:07:16.657  1044  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-02 19:07:16.657  1044  1529 D ConnectivityService:    accepting network in place of null
09-02 19:07:16.657  1044  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.658  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.658  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 19:07:16.659  1044  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe8,0::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 19:07:16.659  1044  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-02 19:07:16.659  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 19:07:16.659  1044  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 19:07:16.659  1044  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 19:07:16.660  1044  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-02 19:07:16.660  1044  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.661  1044  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:16.661  1044  1044 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 19:07:16.661   316  8044 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 19:07:16.661  1044  1529 D ConnectivityService: validation of new default Network = false
09-02 19:07:16.661  1044  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 19:07:16.661  1044  1529 D DSQN    : enableDataServiceNotify 
09-02 19:07:16.661  1044  1529 D DSQN    : start dsqn bin
09-02 19:07:16.661  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 19:07:16.661  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 19:07:16.661  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-02 19:07:16.668  1044  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-02 19:07:16.668  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.668  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:16.669  1044  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:16.669  1588  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 19:07:16.657  8045  8045 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:16.657  8045  8045 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:16.673  1044  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-02 19:07:16.683  8045  8045 E DSQN    : DSQN ssw
,09-02 19:07:16.691  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 19:07:16.692  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.692  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.712   316  8044 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-02 19:07:16.749   316  8044 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-02 19:07:16.773  1044  8034 D DhcpStateMachine: DHCPV4 request on wlan0
,09-02 19:07:16.775  1044  8034 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 19:07:16.775  1044  8034 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-02 19:07:16.776  6536  6649 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 853)
09-02 19:07:16.776  6536  6649 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 853)
09-02 19:07:16.779  6536  6649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
09-02 19:07:16.783  6536  6649 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-02 19:07:16.783  6536  6649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 859)
09-02 19:07:16.785  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.785  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d6c9a80 added. We now have 2 listener(s)
09-02 19:07:16.785  1044  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.777  8049  8049 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:16.777  8049  8049 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 19:07:16.788  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.788  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.788  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.788  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.788  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d50f8b9 added. We now have 9 listener(s)
09-02 19:07:16.788  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.791  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:07:16.795   316   915 D LGDataListener: argv[0]=dsqncommand
09-02 19:07:16.795   316   915 D LGDataListener: argv[1]=wlan0
09-02 19:07:16.795   316   915 D LGDataListener: argv[2]=1
09-02 19:07:16.795   316   915 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-02 19:07:16.795  1044  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-02 19:07:16.795  1044  1117 D DSQN    : start to monitor internet connection
09-02 19:07:16.796  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:16.799  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:16.799  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:16.799  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:16.799  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:16.799  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:16.799  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.799  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:16.799  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:16.800  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.800  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:16.800  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.800  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c3645f added. We now have 3 listener(s)
09-02 19:07:16.801  1044  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 19:07:16.804  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:16.806  8049  8049 I dhcpcd  : version 5.5.6 starting
09-02 19:07:16.809  8049  8049 E dhcpcd  : get_duid: m
09-02 19:07:16.809  8049  8049 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 19:07:16.809  8049  8049 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-02 19:07:16.809  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.809  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.809  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.809  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.809  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a40deac added. We now have 10 listener(s)
09-02 19:07:16.809  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.809  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:16.809  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:16.809  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:16.809  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.809  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.810  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:16.810  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.810  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d6c9a80 removed from the list
09-02 19:07:16.810  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.810  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d50f8b9 removed from the list
09-02 19:07:16.817  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:16.817  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:16.818  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.818  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.818  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:16.819  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.819  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.819  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:16.820  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d50f8b9 not in the list
09-02 19:07:16.820  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.820  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.821  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.821  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.821  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.821  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a40deac removed from the list
09-02 19:07:16.821  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.821  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.821  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.821  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.821  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c3645f removed from the list
09-02 19:07:16.822  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.822  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@167f6775 added. We now have 2 listener(s)
09-02 19:07:16.822  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.824  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.824  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.824  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.824  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.824  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f42e30a added. We now have 9 listener(s)
09-02 19:07:16.825  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.825  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:07:16.828  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:16.830  1044  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 17:07:16 GMT], X-Android-Received-Millis=[1472836036829], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472836036792]}
09-02 19:07:16.830  1044  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user conse,nt.
09-02 19:07:16.830  1044  8033 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-02 19:07:16.830  1044  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-02 19:07:16.830  1044  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-02 19:07:16.830  1044  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:16.830  1044  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:16.830  1044  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 19:07:16.830  1044  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-02 19:07:16.830  1044  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-02 19:07:16.830  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.830  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:16.831  1044  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:16.831  1044  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.831  1044  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 19:07:16.832  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.832  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 19:07:16.832  1588  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 19:07:16.833  1044  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:16.833  1044  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:16.835  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:16.835  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:16.835  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:16.835  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:16.835  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:16.835  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.835  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:16.835  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:16.836  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.836  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:16.836  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.836  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23333998 added. We now have 3 listener(s)
09-02 19:07:16.836  1044  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.838  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.838  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.838  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.838  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.838  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bec05f1 added. We now have 10 listener(s)
09-02 19:07:16.838  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.838  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:16.839  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:16.839  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:16.839  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:16.839  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:07:16.839  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:16.841  6,536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:16.843  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 19:07:16.843  1044  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.850  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:07:16.852  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 19:07:16.853  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 19:07:16.854  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.855  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 19:07:16.856  7660  7787 D UEI.SmartControl: Internal timer expired: 3
09-02 19:07:16.856  7660  7787 D UEI.SmartControl: unbind internal service
09-02 19:07:16.856  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:07:16.859  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:16.859  7660  7660 D UEI.SmartControl: Service.onUnbind: IControl
09-02 19:07:16.860  7660  7660 D UEI.SmartControl: Service.onDestroy
09-02 19:07:16.860  7660  7660 D UEI.SmartControl: Lock is in USE false
09-02 19:07:16.860  7660  7660 D UEI.SmartControl: unbind internal service
09-02 19:07:16.860  7660  7660 D serial_port: close(fd = 24)
09-02 19:07:16.860  6536  6649 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 19:07:16.861  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:16.861  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:16.861  8049  8049 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 19:07:16.861  8049  8049 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 19:07:16.861  8049  8049 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 19:07:16.861  8049  8049 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 19:07:16.862  8049  8049 D dhcpcd  : wlan0: sending REQUEST (xid 0xc5a101b7), next in 3.00 seconds
09-02 19:07:16.863  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:16.863  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:16.863  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:16.863  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.863  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.863  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:16.863  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.863  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@167f6775 removed from the list
,09-02 19:07:16.863  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.863  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f42e30a removed from the list
,09-02 19:07:16.863  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:16.864  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.864  7660  7660 I UEI.SmartControl: Serial port is closed.
09-02 19:07:16.864  7660  7660 I UEI.SmartControl: Serial port is closed.
09-02 19:07:16.864  7660  7660 D UEI.SmartControl: Blaster closed
09-02 19:07:16.864  7660  7660 D UEI.SmartControl: Shut down QS...
09-02 19:07:16.864  7660  7660 D UEI.SmartControl: Stopping QS lib
09-02 19:07:16.864  7660  7660 D UEI.SmartControl: QS lib stop result = true
09-02 19:07:16.864  7660  7660 D UEI.SmartControl: Stopped QS lib
09-02 19:07:16.864  7660  7660 D UEI.SmartControl: QS shutdown complete
09-02 19:07:16.865  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.865  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.866  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.866  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.866  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.866  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f42e30a not in the list
09-02 19:07:16.866  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.866  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.866  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.867  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:07:16.867  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:07:16.867  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.867  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.867  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bec05f1 removed from the list
09-02 19:07:16.867  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.867  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.867  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.867  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.867  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23333998 removed from the list
09-02 19:07:16.868  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.868  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fee5744 added. We now have 2 listener(s)
09-02 19:07:16.868  1044  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.869  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MA,C address: "58:3F:54:73:BA:17"
09-02 19:07:16.869  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.869  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.869  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.869  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa102d added. We now have 9 listener(s)
09-02 19:07:16.869  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.870  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:07:16.872  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:16.874  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:16.874  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:16.874  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:16.874  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:16.874  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:16.874  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.874  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:16.874  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:16.876  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.876  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:16.876  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.876  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ed1caf3 added. We now have 3 listener(s)
09-02 19:07:16.876  1044  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 19:07:16.877  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:16.880  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.880  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.880  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.880  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.880  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161ba3b0 added. We now have 10 listener(s)
09-02 19:07:16.880  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.880  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:16.880  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:16.881  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:16.881  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:16.881  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:16.881  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:16.881  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:07:16.884  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 19:07:16.884  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.887  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 19:07:16.888  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:07:16.889  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:07:16.890  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:16.891  6536  6649 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 19:07:16.891  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:16.891  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:07:16.891  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:16.891  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.891  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.891  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:16.891  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 19:07:16.891  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fee5744 removed from the list
09-02 19:07:16.891  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.892  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa102d removed from the list
09-02 19:07:16.892  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:16.892  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.894  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.894  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.895  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.895  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.895  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.895  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa102d not in the list
09-02 19:07:16.895  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.895  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.896  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.896  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:07:16.897  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:07:16.897  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.897  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.897  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@161ba3b0 removed from the list
09-02 19:07:16.897  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.897  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.897  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.897  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.897  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ed1caf3 removed from the list
09-02 19:07:16.897  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.898  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b4234f added. We now have 2 listener(s)
09-02 19:07:16.898  1044  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.900  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.900  6536  6649 D, org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.900  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.900  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.900  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a8f4adc added. We now have 9 listener(s)
09-02 19:07:16.900  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.901  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:07:16.903  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:16.906  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-02 19:07:16.906  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:16.906  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:16.906  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:16.906  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:16.906  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.906  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:16.906  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:16.907  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.907  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:16.907  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.907  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22e222ba added. We now have 3 listener(s)
09-02 19:07:16.908  1044  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.908  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:16.910  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:16.911  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.911  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.911  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.911  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.911  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b9a56b added. We now have 10 listener(s)
09-02 19:07:16.911  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.911  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:16.912  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:16.912  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:16.912  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:16.912  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:07:16.914  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 19:07:16.914  1044  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.916  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 19:07:16.917  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 19:07:16.918  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:07:16.918  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:16.919  6536  6649 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-02 19:07:16.920  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:16.921  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:16.921  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:16.921  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.921  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.921  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:16.921  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.921  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b4234f removed from the list
09-02 19:07:16.921  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.921  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a8f4adc removed from the list
09-02 19:07:16.921  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:16.921  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.921  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.921  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.922  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.922  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.922  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.922  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a8f4adc not in the list
09-02 19:07:16.922  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.922  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.922  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.923  6536  6649 D BluetoothLeScanner: could not find callback wrapper
09-02 19:07:16.923  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:07:16.923  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.923  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.923  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b9a56b removed from the list
09-02 19:07:16.923  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.923  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.923  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 1,9:07:16.923  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.923  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22e222ba removed from the list
09-02 19:07:16.923  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.924  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ffb086 added. We now have 2 listener(s)
09-02 19:07:16.924  1044  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.925  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.925  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:16.925  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.925  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.925  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b2d47 added. We now have 9 listener(s)
09-02 19:07:16.925  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.926  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:07:16.929  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:16.931  6536  6649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:16.931  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:16.931  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 19:07:16.931  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:16.931  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:16.931  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.931  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:16.931  6536  6649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:16.933  6536  6649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:16.933  6536  6649 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:16.933  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:16.933  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdc5e9d added. We now have 3 listener(s)
09-02 19:07:16.933  1044  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 19:07:16.934  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:16.935  8049  8049 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-02 19:07:16.936  6536  6536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:16.936  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 19:07:16.936  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:07:16.936  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:16.936  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:16.936  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29164f12 added. We now have 10 listener(s)
,09-02 19:07:16.936  6536  6649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:16.937  6536  6649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:16.937  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:07:16.937  6536  6649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:16.940  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.940  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:16.940  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:16.940  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.940  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ffb086 removed from the list
,09-02 19:07:16.940  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-02 19:07:16.940  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b2d47 removed from the list
09-02 19:07:16.940  6536  6649 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:16.940  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.941  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.941  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:16.941  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.941  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.941  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.941  6536  6649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4b2d47 not in the list
09-02 19:07:16.941  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.941  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:16.942  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:16.942  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:16.942  6536  6649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:16.942  6536  6649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29164f12 removed from the list
,09-02 19:07:16.942  6536  6649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:16.942  6536  6649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:16.942  6536  6649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:16.942  6536  6649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:16.942  6536  6649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdc5e9d removed from the list
09-02 19:07:16.942  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 19:07:16.943  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-02 19:07:16.943  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 19:07:16.943  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:16.943  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-02 19:07:16.943  6536  6649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:16.950  6536  8058 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: My test thread name)
09-02 19:07:16.951  6536  8058 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 866, thread name: My test thread name)
09-02 19:07:16.951  6536  8058 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 866, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 19:07:16.954  6536  8059 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: My test thread name)
09-02 19:07:16.955  6536  8059 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: My test thread name)
09-02 19:07:16.955  6536  8059 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 19:07:16.956  6536  6649 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 19:07:16.956  6536  6649 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 19:07:16.956  6536  6649 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 19:07:16.956  6536  6649 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 19:07:16.957  6536  6649 D com.test.thalitest.ThaliTestRunner: Total duration: 22914 ms
09-02 19:07:16.957  6536  6649 I jxcore-log: *Native tests were executed*
09-02 19:07:16.957  6536  6649 I jxcore-log: 
09-02 19:07:16.957  6536  6649 I jxcore-log: Total number of executed tests:  80
09-02 19:07:16.957  6536  6649 I jxcore-log: 
09-02 19:07:16.958  6536  6649 I jxcore-log: Number of passed tests:  80
09-02 19:07:16.958  6536  6649 I jxcore-log: 
09-02 19:07:16.958  6536  6649 I jxcore-log: Number of failed tests:  0
09-02 19:07:16.958  6536  6649 I jxcore-log: 
09-02 19:07:16.958  6536  6649 I jxcore-log: Number of ignored tests:  0
09-02 19:07:16.958  6536  6649 I jxcore-log: 
09-02 19:07:16.958  6536  6649 I jxcore-log: Total duration:  22914
09-02 19:07:16.958  6536  6649 I jxcore-log: 
09-02 19:07:16.958  6536  6649 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 19:07:16.958  6536  6649 I jxcore-log: 
,09-02 19:07:16.961  8049  8049 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 19:07:16.961  8049  8049 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 19:07:16.961  8049  8049 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 19:07:16.962  8049  8049 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 19:07:16.962  8049  8049 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 19:07:16.963  8049  8049 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 19:07:16.963  8049  8049 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 19:07:16.963  8049  8049 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-02 19:07:16.966  6536  6536 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 19:07:16.967  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.967  6536  6649 I jxcore-log: 
09-02 19:07:16.968  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.968  6536  6649 I jxcore-log: 
09-02 19:07:16.969  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.969  6536  6649 I jxcore-log: 
09-02 19:07:16.970  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.970  6536  6649 I jxcore-log: 
09-02 19:07:16.971  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.971  6536  6649 I jxcore-log: 
09-02 19:07:16.973  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:07:16.973  6536  6649 I jxcore-log: 
09-02 19:07:16.974  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:07:16.974  6536  6649 I jxcore-log: 
09-02 19:07:16.975  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.975  6536  6649 I jxcore-log: 
09-02 19:07:16.976  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.976  6536  6649 I jxcore-log: 
09-02 19:07:16.976  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:07:16.976  6536  6649 I jxcore-log: 
09-02 19:07:16.977  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:07:16.977  6536  6649 I jxcore-log: 
09-02 19:07:16.978  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:07:16.978  6536  6649 I jxcore-log: 
09-02 19:07:16.978  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.978  6536  6649 I jxcore-log: 
09-02 19:07:16.978  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.978  6536  6649 I jxcore-log: 
09-02 19:07:16.979  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.979  6536  6649 I jxcore-log: 
09-02 19:07:16.979  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.979  6536  6649 I jxcore-log: 
09-02 19:07:16.980  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.980  6536  6649 I jxcore-log: 
09-02 19:07:16.980  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.980  6536  6649 I jxcore-log: 
09-02 19:07:16.981  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.981  6536  6649 I jxcore-log: 
09-02 19:07:16.981  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:07:16.981  6536  6649 I jxcore-log: 
09-02 19:07:16.981  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:16.981  6536  6649 I jxcore-log: 
09-02 19:07:16.982  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:16.982  6536  6649 I jxcore-log: 
09-02 19:07:16.982  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.982  6536  6649 I jxcore-log: 
09-02 19:07:16.983  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.983  6536  6649 I jxcore-log: 
09-02 19:07:16.983  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.983  6536  6649 I jxcore-log: 
09-02 19:07:16.984  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.984  6536  6649 I jxcore-log: 
09-02 19:07:16.984  6536  6649 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:16.984  6536  6649 I jxcore-log: 
,09-02 19:07:17.038  8016  8016 W ExternalStrings: load override strings
09-02 19:07:17.038  8016  8016 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:17.038  8016  8016 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-02 19:07:17.040  8016  8016 D StatusProvider: onCreate
,09-02 19:07:17.121  8016  8016 V Signer  : override build config not found
09-02 19:07:17.121  8016  8016 D Signer  : value of property debug is false
,09-02 19:07:17.164  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,09-02 19:07:17.164  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-02 19:07:17.164  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-02 19:07:17.165  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-02 19:07:17.165  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-02 19:07:17.165  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-02 19:07:17.165  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-02 19:07:17.165  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-02 19:07:17.166  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-02 19:07:17.166  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-02 19:07:17.166  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-02 19:07:17.166  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-02 19:07:17.166  8016  8016 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,09-02 19:07:17.181  8016  8016 V LGMDMManager: Create singleton instance
09-02 19:07:17.218  8068  8068 D AndroidRuntime: 
09-02 19:07:17.218  8068  8068 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-02 19:07:17.220  8068  8068 D AndroidRuntime: CheckJNI is OFF
09-02 19:07:17.258  8016  8016 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-02 19:07:17.299  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:17.304  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:17.312  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:17.323  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:17.378  8068  8068 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 19:07:17.381  1044  8034 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-02 19:07:17.383  1044  8034 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 19:07:17.384  1044  8034 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 19:07:17.384  1044  8034 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-02 19:07:17.384  1044  8034 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 19:07:17.385  1044  8034 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 19:07:17.385  1044  8034 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 19:07:17.385  1044  8034 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 19:07:17.386  1044  8034 D DhcpStateMachine: RunningState
09-02 19:07:17.401  1044  1766 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8099 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-02 19:07:17.402  1044  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-02 19:07:17.402  1044  1115 I ActivityManager: Killing 6536:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-02 19:07:17.445  8016  8093 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-02 19:07:17.458  1044  1942 I WindowState: WIN DEATH: Window{151e990b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 19:07:17.459  1044  1528 D WifiService: Client connection lost with reason: 4
,09-02 19:07:17.463  1044  1942 D InputDispatcher: Window went away: Window{151e990b u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-02 19:07:17.583  1044  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 19:07:17.584  1044  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-02 19:07:17.584  1044  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 19:07:17.585  1044  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 19:07:17.585  1044  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 19:07:17.585  1044  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 19:07:17.586  1044  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-02 19:07:17.586  1044  1529 D ConnectivityService: identical MTU - not setting
09-02 19:07:17.586  1044  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 19:07:17.586  1044  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 19:07:17.586  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:17.586  1044  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:17.587  1044  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 19:07:17.588  1588  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-02 19:07:17.615  1044  1115 I ActivityManager: Killing 7111:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-02 19:07:17.753  1044  1115 I ActivityManager:   Force finishing activity ActivityRecord{346d292b u0 com.test.thalitest/.MainActivity t6}
,09-02 19:07:17.825   343   367 E GBMv2   : DFP En is all cleared set to be enabled
,09-02 19:07:17.842  1044  1559 W ActivityManager: Spurious death for ProcessRecord{27a42108 6536:com.test.thalitest/u0a118}, curProc for 6536: null
,09-02 19:07:17.843  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-02 19:07:17.845  1044  1871 W libprocessgroup: failed to open /acct/uid_10093/pid_7111/cgroup.procs: No such file or directory
09-02 19:07:17.845  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-02 19:07:17.853  1044  1136 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-02 19:07:17.853  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,09-02 19:07:17.857  2018  2114 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-02 19:07:17.861  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-02 19:07:17.861  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2719706e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-02 19:07:17.862  1927  2822 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-02 19:07:17.863  1927  2822 D SplitWindowPolicy: topRunningActivity=ActivityInfo{92a930f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-02 19:07:17.866  1044  1136 I ActivityManager:   Force finishing activity ActivityRecord{346d292b u0 com.test.thalitest/.MainActivity t6 f}
09-02 19:07:17.866  1044  1136 W ActivityManager: Duplicate finish request for ActivityRecord{346d292b u0 com.test.thalitest/.MainActivity t6 f}
,09-02 19:07:17.894  8099  8099 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 19:07:17.921  1891  1891 D ActionManagerService: notifyUserLog: 1000003
09-02 19:07:17.923  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-02 19:07:17.927  2715  4428 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-02 19:07:17.931  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-02 19:07:17.931  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-02 19:07:17.937  1044  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 19:07:17.941  2493  2673 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-02 19:07:17.942  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-02 19:07:17.942  2715  2715 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-02 19:07:17.944  7560  7560 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-02 19:07:17.944  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 19:07:17.963  8099  8099 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-02 19:07:17.966  4559  4559 I art     : Explicit concurrent mark sweep GC freed 8230(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 656us total 89.743ms
09-02 19:07:17.983  1044  1060 V SIM_STK : Menu title from STK is T-Mobile
,09-02 19:07:18.007  4447  4447 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-02 19:07:18.007  4447  4447 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-02 19:07:18.007  4447  4447 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-02 19:07:18.007  4447  4447 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-02 19:07:18.007  4447  4447 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 19:07:18.007  4447  4447 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 19:07:18.007  4447  4447 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:18.007  4447  4447 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:18.007  4447  4447 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:18.007  4447  4447 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:18.007  4447  4447 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:18.007  4447  4447 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:07:18.008  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,09-02 19:07:18.018  1044  1044 D administrator: Handling package changes for user 0
,09-02 19:07:18.031  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-02 19:07:18.040  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-02 19:07:18.048  1588  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 19:07:18.048  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.049  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-02 19:07:18.050  1588  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 19:07:18.050  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.050  1891  1891 D ActionManagerService: notifyUserLog: 1000004
09-02 19:07:18.051  2715  4428 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-02 19:07:18.051  2715  2765 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 19:07:18.054  1588  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 19:07:18.055  1588  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:07:18.055  1588  1643 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 19:07:18.056  1588  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 19:07:18.057  1588  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 19:07:18.057  1588  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-02 19:07:18.060  1588  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 19:07:18.060  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , display: false
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , animation: false }
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , display: false
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , animation: false }
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , create_time: 1472828323917
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , display: false
09-02 19:07:18.063  2018  2018 I GBoardWebViewUtils: , animation: false }
,09-02 19:07:18.064  1588  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 19:07:18.064  1588  1643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 19:07:18.069  2018  8143 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,09-02 19:07:18.071  1588  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 19:07:18.071  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-02 19:07:18.071  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-02 19:07:18.074  1588  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-02 19:07:18.076  1588  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 19:07:18.076  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.079  1044  1998 V SIM_STK : Menu title from STK is T-Mobile
09-02 19:07:18.079  1044  1998 V SIM_STK : Menu title from STK is T-Mobile
09-02 19:07:18.081  1588  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:07:18.081  1588  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 19:07:18.082  1588  1643 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-02 19:07:18.082  1588  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-02 19:07:18.083  1588  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 19:07:18.083  1588  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 19:07:18.086  1588  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 19:07:18.086  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.087  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-02 19:07:18.091  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-02 19:07:18.091  1854  1854 D SplitUIService: removed split : 
09-02 19:07:18.092  1588  1588 D KeyguardModel: handleShortcutListChanged...
09-02 19:07:18.092  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 19:07:18.098  8099  8099 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-02 19:07:18.098  8099  8099 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-02 19:07:18.099  8099  8099 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,09-02 19:07:18.099  8099  8099 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-02 19:07:18.099  8099  8099 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-02 19:07:18.100  1588  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 19:07:18.100  8099  8099 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-02 19:07:18.100  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.103  1588  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 19:07:18.103  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.105  8099  8099 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-02 19:07:18.106  1588  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 19:07:18.106  1588  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-02 19:07:18.107  1588  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 19:07:18.107  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.108  1588  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 19:07:18.108  1588  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-02 19:07:18.110  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.125  1588  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,09-02 19:07:18.126  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.144  1044  1059 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 19:07:18.146  7560  7560 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 19:07:18.146  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-02 19:07:18.147  1588  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 19:07:18.147  1588  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 19:07:18.147  2018  2032 I art     : Background sticky concurrent mark sweep GC freed 2605(143KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 80MB/80MB, paused 10.254ms total 15.432ms
09-02 19:07:18.148  1588  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 19:07:18.148  1588  1643 D KeyguardModel: createShortcutInfo...
09-02 19:07:18.149  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-02 19:07:18.151  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.171  8016  8093 D LgDataFeature: LgDataFeature() Constructor: none
09-02 19:07:18.171  8016  8093 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 19:07:18.178  1044  1114 W InputMethodInfo: Duplicated subtype definition found: , voice
09-02 19:07:18.192  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-02 19:07:18.192  1854  1854 I SplitUIService: split app #11
,09-02 19:07:18.195  8099  8099 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 19:07:18.198  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-02 19:07:18.199  1044  1060 V SIM_STK : Menu title from STK is T-Mobile
09-02 19:07:18.200  6731  6731 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-02 19:07:18.203  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:18.204  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:18.209  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:18.211  8099  8099 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-02 19:07:18.213  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-02 19:07:18.215  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 19:07:18.217  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-02 19:07:18.218  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-02 19:07:18.219  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-02 19:07:18.220  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-02 19:07:18.221  8099  8099 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-02 19:07:18.224  1588  1588 D KeyguardModel: handleShortcutListChanged...
09-02 19:07:18.224  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 19:07:18.230  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.233  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-02 19:07:18.234  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-02 19:07:18.234  1044  1044 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-02 19:07:18.236  1044  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-02 19:07:18.241  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-02 19:07:18.241  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 19:07:18.243  2018  2143 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-02 19:07:18.243  2018  2143 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-02 19:07:18.245  1044  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ee2b493 u0 com.lge.launcher2/.Launcher t5} time:142545
09-02 19:07:18.253  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.253  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.254  8099  8099 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 19:07:18.256  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:18.256  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:18.260  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 19:07:18.263  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-02 19:07:18.264  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,09-02 19:07:18.265  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 19:07:18.274  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-02 19:07:18.275  2583  2583 D [Concierge]Service: onStartCommand(). Type : 8
09-02 19:07:18.275  2583  2583 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-02 19:07:18.277  2583  2583 D [Concierge]Service: Update widget ID : 11
09-02 19:07:18.278  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.278  2018  2018 D [Concierge]WidgetView: change position of spinner
09-02 19:07:18.279  2583  2583 D [Concierge]Service: onStartCommand(). Type : 0
09-02 19:07:18.280  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1472836038280
09-02 19:07:18.285  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.285  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.285  8099  8099 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 19:07:18.287  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 19:07:18.287  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 19:07:18.287  6731  6731 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 19:07:18.287  6731  6731 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 19:07:18.287  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 19:07:18.287  6731  6731 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 19:07:18.287  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 19:07:18.288  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 19:07:18.288  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 19:07:18.288  6731  6731 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 19:07:18.288  6731  6731 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 19:07:18.288  6731  6731 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-02 19:07:18.290  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:18.290  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:18.296  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:18.302  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.303  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 270838919
09-02 19:07:18.304  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-02 19:07:18.304  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-02 19:07:18.307  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@c84829c
09-02 19:07:18.307  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-02 19:07:18.307  8016  8093 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-02 19:07:18.308  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 19:07:18.308  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 19:07:18.312  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.312  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.312  8099  8099 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 19:07:18.313  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,09-02 19:07:18.313  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-02 19:07:18.314  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 19:07:18.316  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472835923260, New one : 1472836038280
09-02 19:07:18.316  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:18.316  2018  2018 D [Concierge]WidgetView: Unregister all receivers
09-02 19:07:18.316  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 19:07:18.316  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:18.317  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 19:07:18.319  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-02 19:07:18.320  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-02 19:07:18.322  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-02 19:07:18.323  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-02 19:07:18.324  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-02 19:07:18.325  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 19:07:18.325  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 19:07:18.325  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 19:07:18.336  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.349  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.349  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.349  8099  8099 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:18.352  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:18.356  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 19:07:18.359  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.363  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:18.364  8016  8093 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-02 19:07:18.368  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-02 19:07:18.376  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.376  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.376  8016  8093 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-02 19:07:18.376  8099  8099 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:18.378  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-02 19:07:18.378  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-02 19:07:18.379  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:18.379  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 19:07:18.380  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:18.380  8016  8093 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-02 19:07:18.380  8016  8093 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-02 19:07:18.381  8016  8093 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-02 19:07:18.381  8016  8093 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-02 19:07:18.387  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 19:07:18.388  8016  8093 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-02 19:07:18.391  8016  8093 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-02 19:07:18.394  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.399  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20515ad3 time:142699
09-02 19:07:18.402  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.402  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.402  8099  8099 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:18.408  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:18.409  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:18.416  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 19:07:18.420  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.424  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.424  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.429  1044  1136 I art     : Explicit concurrent mark sweep GC freed 83199(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.870ms total 358.667ms
09-02 19:07:18.430  8099  8099 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 19:07:18.432  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:18.433  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 19:07:18.439  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:18.443  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.448  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.448  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.449  8099  8099 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 19:07:18.453  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 19:07:18.453  8016  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-02 19:07:18.464  7967  7967 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 19:07:18.470  8068  8068 D AndroidRuntime: Shutting down VM
,09-02 19:07:18.472  7967  7967 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:07:18.488  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:18.503  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.532  1044  1136 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8158 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-02 19:07:18.536  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.537  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.537  8099  8099 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 19:07:18.538  8099  8099 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 19:07:18.538  8099  8099 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 19:07:18.545  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:18.570  7967  7967 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 19:07:18.571  7967  7967 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 19:07:18.576  1044  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:07:18.581  6731  6731 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 19:07:18.587  6731  6731 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 19:07:18.590  1044  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-02 19:07:18.591  8099  8099 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 19:07:18.591  8099  8099 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 19:07:18.591  2018  2018 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-02 19:07:18.591  8099  8099 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 19:07:18.592  8099  8099 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 19:07:18.592  8099  8099 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 19:07:18.594  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 19:07:18.596  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-02 19:07:18.598  8016  8016 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-02 19:07:18.602  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-02 19:07:18.604  1044  1926 I ActivityManager: Killing 7176:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-02 19:07:18.642  2018  2878 I GBoardtInterface: onReloaded()
,09-02 19:07:18.644  2018  2018 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-02 19:07:18.663  1044  1871 W libprocessgroup: failed to open /acct/uid_10005/pid_7176/cgroup.procs: No such file or directory
09-02 19:07:18.663  2176  2176 I ConfigService: onCreate
,09-02 19:07:18.664  2176  2176 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-02 19:07:18.667  2715  2743 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-02 19:07:18.668  2176  2176 I ConfigService: onBind returning update interface
09-02 19:07:18.672  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-02 19:07:18.683  2176  2176 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-02 19:07:18.683  2176  2176 I ConfigService: onBind returning config service
,09-02 19:07:18.686  2715  2764 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 19:07:18.695  1801  1801 I ConfigFetchService: service connected
09-02 19:07:18.699  2176  2176 I ConfigService: onDestroy
,09-02 19:07:18.703  1891  1891 D ActionManagerService: notifyUserLog: 1000001
09-02 19:07:18.706  2715  4428 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 19:07:18.707  2715  4428 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 19:07:18.709  1801  8178 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-02 19:07:18.716  1891  1891 D ActionManagerService: notifyUserLog: 1000001
,09-02 19:07:18.718  2715  4428 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 19:07:18.718  2715  4428 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 19:07:18.718  2715  4428 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-02 19:07:18.719  2715  4428 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-02 19:07:18.721  2715  2764 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 19:07:18.725  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-02 19:07:18.725  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-02 19:07:18.728  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,09-02 19:07:18.728  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,09-02 19:07:18.731  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-02 19:07:18.731  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-02 19:07:18.741  5877  8184 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-02 19:07:18.748  1801  8186 I PeopleContactsSync: CP2 sync disabled
09-02 19:07:18.752  1801  4711 I Icing   : doRemovePackageData com.test.thalitest
09-02 19:07:18.804  1801  8185 W GmsApplication: Using Auth Proxy for data requests.
,09-02 19:07:18.807  6926  6926 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-02 19:07:18.812  1801  8185 W GmsApplication: Using Auth Proxy for data requests.
09-02 19:07:18.826  2335  8188 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-02 19:07:18.855  1044  1059 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8189 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-02 19:07:18.905  2176  2304 I art     : Explicit concurrent mark sweep GC freed 7101(411KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 799us total 18.932ms
,09-02 19:07:18.917  8189  8189 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:07:18.918  8189  8189 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 19:07:18.918  8189  8189 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 19:07:18.919  8189  8189 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-02 19:07:18.925  2335  8188 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
09-02 19:07:18.926  2335  8188 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-02 19:07:18.926  2335  8188 E AndroidRuntime: Process: android.process.acore, PID: 2335
09-02 19:07:18.926  2335  8188 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:18.926  2335  8188 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 19:07:18.926  1801  8180 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-02 19:07:18.927  1801  8180 E DriveAsyncService: disk I/O error (code 3850)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at com.goog,le.android.gms.common.service.c.onHandleIntent(SourceFile:60)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:18.927  1801  8180 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 19:07:18.929  2335  8188 I Process : Sending signal. PID: 2335 SIG: 9
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: Can't write: system_app_crash
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 19:07:18.944  1044  8208 E DropBoxManagerService: 	... 5 more
,09-02 19:07:18.974  8189  8189 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:18.974  8189  8189 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:07:18.974  8189  8189 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,09-02 19:07:18.974  8189  8189 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:07:18.974  8189  8189 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-02 19:07:18.974  8189  8189 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-02 19:07:18.974  8189  8189 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 19:07:18.974  8189  8189 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 19:07:18.974  8189  8189 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 19:07:18.974  8189  8189 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:07:18.975  8189  8189 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:18.975  8189  8189 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:18.975  8189  8189 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:18.975  8189  8189 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:18.975  8189  8189 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:18.975  8189  8189 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.databas,e.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:18.979  8189  8189 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:07:18.979  8189  8189 D AndroidRuntime: Shutting down VM
09-02 19:07:18.980  8189  8189 E AndroidRuntime: FATAL EXCEPTION: main
09-02 19:07:18.980  8189  8189 E AndroidRuntime: Process: com.lge.email, PID: 8189
09-02 19:07:18.980  8189  8189 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.app.ActivityThread$H.han,dleMessage(ActivityThread.java:1344)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-02 19:07:18.980  8189  8189 E AndroidRuntime: 	... 11 more
09-02 19:07:18.990  1044  1559 I ActivityManager: Process android.process.acore (pid 2335) has died
,09-02 19:07:18.991  1044  1559 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
09-02 19:07:18.991  1044  1559 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
09-02 19:07:18.997  8189  8189 I Process : Sending signal. PID: 8189 SIG: 9
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: Can't write: system_app_crash
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 19:07:18.998  1044  8211 E DropBoxManagerService: 	... 5 more
09-02 19:07:19.064  2018  2878 I GBoardtInterface: exportHTML()
,09-02 19:07:19.080  1044  1998 I ActivityManager: Process com.lge.email (pid 8189) has died
,09-02 19:07:19.093  2018  2878 I GBoardtInterface: exportHTML()
,09-02 19:07:19.117  2018  2878 I GBoardtInterface: exportHTML()

```
