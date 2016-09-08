#### Test 8362733784eab4b_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-08 13:33:59.634  1989  1989 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
09-08 13:33:59.634  1989  1989 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
--------- beginning of system
09-08 13:33:59.635  1031  2040 W libprocessgroup: failed to open /acct/uid_10046/pid_5419/cgroup.procs: No such file or directory
09-08 13:33:59.650  1989  1989 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-08 13:33:59.682  6400  6400 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-08 13:33:59.687  6400  6400 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-08 13:33:59.711  4581  6548 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-08 13:33:59.752  1031  1971 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6549 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 13:33:59.779  1031  2007 V SIM_STK : Menu title from STK is T-Mobile
09-08 13:33:59.873  4581  6548 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 162 ms] updated apps [took 162 ms] 
09-08 13:34:00.005  6549  6549 D DocsApplication: Installing DEX configuration.
09-08 13:34:00.029  6549  6549 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-08 13:34:00.036  6549  6549 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{21a14b09 com.google.android.apps.docs}
09-08 13:34:00.037  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-08 13:34:00.037  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
09-08 13:34:00.037  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-08 13:34:00.038  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
09-08 13:34:00.041  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
09-08 13:34:00.041  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
09-08 13:34:00.043  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
09-08 13:34:00.045  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
09-08 13:34:00.055  6549  6549 D TAG     : onCreate()
09-08 13:34:00.077  6549  6549 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-08 13:34:00.183  2788  2788 I MusicWidget: mDelayedStopHandler : unbind
09-08 13:34:00.189  2160  2160 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-08 13:34:00.189  2160  2160 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-08 13:34:00.191  2160  2160 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-08 13:34:00.193  2160  2160 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-08 13:34:00.195  2160  2160 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-08 13:34:00.195  2160  2160 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-08 13:34:00.201  2160  2160 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-08 13:34:00.201  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-08 13:34:00.202  1031  2045 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2e87c858com.lge.music.MediaPlaybackService$5@3aeb4db1
09-08 13:34:00.203  2160  2160 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-08 13:34:00.204  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.205  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.205  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.206  2160  2160 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@35b4ed27
09-08 13:34:00.206  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.207  2160  2160 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-08 13:34:00.207  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.208  2160  2160 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-08 13:34:00.208  2160  2160 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-08 13:34:00.208  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.209  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.209  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.210  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.211  2160  2160 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-08 13:34:00.212  2160  2160 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-08 13:34:00.214  2160  2160 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-08 13:34:00.215  2160  2160 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-08 13:34:00.215  2160  2160 V MediaPlayer[Native]: reset
09-08 13:34:00.222  2160  2160 V MediaPlayer[Native]: setListener
09-08 13:34:00.222  2160  2160 V MediaPlayer[Native]: disconnect
09-08 13:34:00.222  2160  2160 V MediaPlayer[Native]: destructor
09-08 13:34:00.223   319  2185 V AudioFlinger: releasing 18 from 2160 for -1
09-08 13:34:00.223   319  2185 V AudioFlinger:  decremented refcount to 0
09-08 13:34:00.223   319  2185 V AudioFlinger: purging stale effects
09-08 13:34:00.223  2160  2160 V MediaPlayer[Native]: disconnect
09-08 13:34:00.224  2160  2160 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-08 13:34:00.226  2160  2160 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-08 13:34:00.226  2160  2160 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-08 13:34:00.227  2160  2160 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-08 13:34:00.227  2160  2160 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-08 13:34:00.228  2160  2160 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-08 13:34:00.228  2160  2160 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 264385174
09-08 13:34:00.228  2160  2160 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 264385174
09-08 13:34:00.232  2160  2160 I SmartShareClient: [SmartShareManagerClient] terminate service: 2160/MediaPlaybackService/915050181
09-08 13:34:00.237  2160  2160 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-08 13:34:00.237  2160  2160 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@171d6e17
09-08 13:34:00.240  2160  2160 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-08 13:34:00.241  2160  2160 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-08 13:34:00.242  2160  2160 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-08 13:34:00.243  2160  2160 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-08 13:34:00.245  1031  1570 I ActivityManager: Killing 5837:com.google.android.gm/u0a64 (adj 15): empty #17
09-08 13:34:00.249  2160  2160 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
09-08 13:34:00.290  1031  2007 W libprocessgroup: failed to open /acct/uid_10064/pid_5837/cgroup.procs: No such file or directory
09-08 13:34:00.437   331   411 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-08 13:34:00.443  3262  6567 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-08 13:34:00.560  2604  2604 D [Concierge]Service: onStartCommand(). Type : 9
09-08 13:34:00.718  6568  6568 D AndroidRuntime: 
09-08 13:34:00.718  6568  6568 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 13:34:00.722  6568  6568 D AndroidRuntime: CheckJNI is OFF
09-08 13:34:00.873  1811  4647 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-08 13:34:00.887  6568  6568 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 13:34:00.895  1031  1970 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 13:34:00.920  1935  2863 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-08 13:34:00.925  1031  1970 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-08 13:34:00.926  1031  1970 D ActivityManager: setTaskToReturnTo : TaskRecord{1b39a94a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-08 13:34:00.926  1031  1970 D ActivityManager: setTaskToReturnTo : TaskRecord{1b39a94a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-08 13:34:00.927  1031  1970 D WindowStateEx: AppWindowTokenEx init.. 
09-08 13:34:00.928   340   352 E GBMv2   : DFP En is all cleared set to be enabled
09-08 13:34:00.974  1031  1970 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6595 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-08 13:34:00.976  6568  6568 D AndroidRuntime: Shutting down VM
09-08 13:34:00.992  1811  4647 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-08 13:34:01.031  1935  1951 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-08 13:34:01.031  1935  1951 D SplitWindowPolicy: topRunningActivity=ActivityInfo{343f39d5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-08 13:34:01.032  1935  1950 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-08 13:34:01.032  1935  1950 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1248b5ea co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-08 13:34:01.058  6595  6595 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-08 13:34:01.108  1811  4647 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-08 13:34:01.115  6595  6595 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-08 13:34:01.121  6595  6595 I LibraryLoader: Loading: webviewchromium
09-08 13:34:01.123  6595  6595 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6160-6163)
09-08 13:34:01.123  6595  6595 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 13:34:01.138  6595  6595 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f3d274b}
09-08 13:34:01.139  6595  6595 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 13:34:01.139  6595  6595 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 13:34:01.145  6595  6595 I BrowserStartupController: Initializing chromium process, renderers=0
09-08 13:34:01.146  6595  6595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 13:34:01.161  6595  6595 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-08 13:34:01.162  6595  6595 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-08 13:34:01.162  6595  6595 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-08 13:34:01.164   319  1380 V AudioPolicyService: registerClient() client 0xb558a260, uid 10118
09-08 13:34:01.167  1031  1113 D BluetoothManagerService: Message: 20
09-08 13:34:01.167  1031  1113 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f54eb84:true
09-08 13:34:01.175  6595  6595 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 13:34:01.175  6595  6595 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 13:34:01.175  6595  6595 I Adreno-EGL: Build Date: 12/12/14 금
09-08 13:34:01.175  6595  6595 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 13:34:01.175  6595  6595 I Adreno-EGL: Remote Branch: 
09-08 13:34:01.175  6595  6595 I Adreno-EGL: Local Patches: 
09-08 13:34:01.175  6595  6595 I Adreno-EGL: Reconstruct Branch: 
,09-08 13:34:01.272  6595  6624 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-08 13:34:01.278  6595  6595 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-08 13:34:01.294  6595  6595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 13:34:01.299  6595  6595 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-08 13:34:01.303  6595  6595 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-08 13:34:01.306  6595  6595 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-08 13:34:01.306  6595  6595 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-08 13:34:01.320  6595  6595 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
09-08 13:34:01.325  6595  6595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 13:34:01.325  6595  6595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 13:34:01.355  6595  6639 D OpenGLRenderer: Render dirty regions requested: true
09-08 13:34:01.355  6595  6639 I OpenGLRenderer: Initialized EGL, version 1.4
09-08 13:34:01.358  6595  6639 D OpenGLRenderer: Enabling debug mode 0
09-08 13:34:01.373  6595  6595 D Atlas   : Validating map...
,09-08 13:34:01.375  1031  1897 D SplitWindow: check instance of lgWin Window{eaf4c9e u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 13:34:01.431  6595  6634 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:01.432  6595  6634 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:01.469  1031  1114 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +443ms (total +540ms)
09-08 13:34:01.469  1031  1114 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{225dd0bb u0 com.test.thalitest/.MainActivity t6} time:106509
,09-08 13:34:01.469  6595  6595 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fc23296 time:106509
09-08 13:34:01.502  6549  6549 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:01.502  6549  6549 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:01.644  6595  6595 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 13:34:01.660  6213  6213 I LockScreenSettings: New app installed broadcast received ..
,09-08 13:34:01.663  6213  6213 I LockScreenSettings: Number of installed packages  1
09-08 13:34:01.680  6549  6549 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-08 13:34:01.725  1031  1934 V SIM_STK : Menu title from STK is T-Mobile
,09-08 13:34:01.782  1031  1933 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6666 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 13:34:01.790  6595  6665 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
09-08 13:34:01.800  6595  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 13:34:01.800  6595  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 13:34:01.800  6595  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 13:34:01.800  6595  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 13:34:01.800  6595  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-08 13:34:01.800  6595  6665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b36937a added. We now have 1 listener(s)
,09-08 13:34:01.808  1031  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:01.810  6595  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-08 13:34:01.812  6595  6665 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-08 13:34:01.813  6595  6665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:01.813  6595  6665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 13:34:01.820  6595  6665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b7a0521 added. We now have 1 listener(s)
09-08 13:34:01.820  6595  6665 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:01.824  1031  1538 D WifiService: New client listening to asynchronous messages
,09-08 13:34:01.828  6595  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:34:01.828  6595  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 13:34:01.828  6595  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 13:34:01.828  6595  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 13:34:01.828  6595  6665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 13:34:01.833  6595  6665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:01.833  1031  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:01.834  6666  6666 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-08 13:34:01.834  6666  6666 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
09-08 13:34:01.834  6595  6665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-08 13:34:01.893  1031  1570 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6685 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-08 13:34:01.894  1031  1570 I ActivityManager: Killing 5878:com.google.android.talk/u0a72 (adj 15): empty #17
,09-08 13:34:01.951  1031  1607 W libprocessgroup: failed to open /acct/uid_10072/pid_5878/cgroup.procs: No such file or directory
,09-08 13:34:01.966  6595  6665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-08 13:34:01.969  6595  6665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:01.969  6595  6665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:01.969  6595  6665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:01.969  6595  6665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:01.969  6595  6665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:01.969  6595  6665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:01.969  6595  6665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:01.969  6595  6665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:01.969  6595  6665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 13:34:01.969  6595  6665 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:01.973  6595  6665 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 13:34:01.974  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:01.977  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:02.013  6685  6685 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-08 13:34:02.034  6595  6595 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-08 13:34:02.035  6685  6685 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-08 13:34:02.039  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-08 13:34:02.046  6595  6634 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-08 13:34:02.046  6595  6634 I chromium: 
09-08 13:34:02.068  1031  1779 I ActivityManager: Killing 5694:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-08 13:34:02.081  5667  5667 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-08 13:34:02.081  5667  5667 W System.err: android.os.DeadObjectException
09-08 13:34:02.081  5667  5667 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 13:34:02.081  5667  5667 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 13:34:02.081  5667  5667 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-08 13:34:02.081  5667  5667 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-08 13:34:02.082  5667  5667 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 13:34:02.082  5667  5667 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 13:34:02.082  5667  5667 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 13:34:02.082  5667  5667 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 13:34:02.082  5667  5667 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 13:34:02.082  5667  5667 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 13:34:02.082  5667  5667 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:02.082  5667  5667 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 13:34:02.082  5667  5667 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 13:34:02.082  5667  5667 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 13:34:02.082  5667  5667 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-08 13:34:02.082  5667  5667 W System.err: android.os.DeadObjectException
09-08 13:34:02.083  5667  5667 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 13:34:02.083  5667  5667 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 13:34:02.083  5667  5667 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-08 13:34:02.083  5667  5667 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-08 13:34:02.083  5667  5667 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 13:34:02.083  5667  5667 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 13:34:02.083  5667  5667 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 13:34:02.083  5667  5667 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 13:34:02.083  5667  5667 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 13:34:02.083  5667  5667 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 13:34:02.083  5667  5667 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:02.083  5667  5667 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 13:34:02.083  5667  5667 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 13:34:02.083  5667  5667 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 13:34:02.083  5667  5667 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-08 13:34:02.084  5667  5667 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-08 13:34:02.191  6595  6595 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-08 13:34:02.191  6595  6595 I chromium: 
,09-08 13:34:02.206  1031  1897 W libprocessgroup: failed to open /acct/uid_1000/pid_5694/cgroup.procs: No such file or directory
09-08 13:34:02.207  1031  1897 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-08 13:34:02.215  5667  5667 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-08 13:34:02.216  5667  5667 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 13:34:02.265  4473  6706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-08 13:34:02.285  1031  1898 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6710 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 13:34:02.288  5667  5667 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-08 13:34:02.290  1811  1811 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-08 13:34:02.292  1811  6719 I ConfigFetchService: running network task: configservice_periodic
,09-08 13:34:02.362  6710  6710 D UEI.SmartControl: Quickset Services start...
09-08 13:34:02.364  6710  6710 I UEI.SmartControl: Manufacture = LGE
09-08 13:34:02.364  6710  6710 D UEI.SmartControl: Id = LGNevo
09-08 13:34:02.366  6710  6710 D UEI.SmartControl: File observer start...
,09-08 13:34:02.370  6710  6710 E UEI.SmartControl: IR Port is disabled: false
,09-08 13:34:02.370  6710  6710 D UEI.SmartControl: Starting file observer...
09-08 13:34:02.371  6710  6710 D UEI.SmartControl: Extracting JNI libs...
09-08 13:34:02.371  6710  6710 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 13:34:02.472  6710  6710 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-08 13:34:02.472  6710  6710 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 13:34:02.472  6710  6710 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-08 13:34:02.498  6710  6710 I UEI.SmartControl: --- Selecting new region: 6
,09-08 13:34:02.500  6710  6710 I UEI.SmartControl: Model = LG-D855
09-08 13:34:02.501  6710  6710 D UEI.SmartControl: QS Service created
09-08 13:34:02.512  6710  6710 I UEI.SmartControl: Service initServices...
,09-08 13:34:02.515  6710  6710 D UEI.SmartControl: QS start get config
,09-08 13:34:02.548  6710  6710 D UEI.SmartControl: Loading JNI Libs...
,09-08 13:34:02.641  6595  6704 W jxcore-log: Initializing JXcore engine
09-08 13:34:02.641  6595  6704 W jxcore-log: JXcore engine is ready
,09-08 13:34:02.661  6704  6704 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9830]" dev="sockfs" ino=9830 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-08 13:34:02.661  6704  6704 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-08 13:34:02.661  6704  6704 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9994]" dev="sockfs" ino=9994 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-08 13:34:02.661  6704  6704 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-08 13:34:02.661  6704  6704 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32135]" dev="sockfs" ino=32135 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-08 13:34:02.688  6595  6704 W jxcore-log: Starting JXcore engine
09-08 13:34:02.760   340   354 E GBMv2   : DFP En is all cleared set to be enabled
09-08 13:34:02.760   340   354 E GBMv2   : Set value is all cleared set the max
09-08 13:34:02.760   340   354 I GBMv2   : DFP Enabled. Ignore VFP set
,09-08 13:34:02.766  6595  6704 W jxcore-log: Platform android
09-08 13:34:02.766  6595  6704 W jxcore-log: 
,09-08 13:34:02.766  6595  6704 W jxcore-log: Process ARCH arm
09-08 13:34:02.766  6595  6704 W jxcore-log: 
,09-08 13:34:02.950  6710  6710 I UEI.SmartControl: Supports setup maps: true
09-08 13:34:02.956  6710  6710 D UEI.SmartControl: QS start statue = true Error code = 0
,09-08 13:34:02.956  6710  6710 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 13:34:02.957  6710  6710 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 13:34:02.957  6710  6710 I UEI.SmartControl: ### init IR Blaster...
09-08 13:34:02.963  6710  6710 D serial_port: Configuring serial port
09-08 13:34:02.969  6710  6710 E UEI.SmartControl: UEIBLaster setting for 616
,09-08 13:34:02.969  6710  6710 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 13:34:02.970  6710  6710 I UEI.SmartControl: configuring settings for MAXQ616
09-08 13:34:02.970  6710  6710 I UEI.SmartControl: Get version...
,09-08 13:34:02.986  6710  6732 D UEI.SmartControl: serial port data available: 21
,09-08 13:34:03.013  6710  6710 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-08 13:34:03.013  6710  6710 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 13:34:03.013  6710  6710 I UEI.SmartControl: QS saving settings...
09-08 13:34:03.015  6710  6710 D UEI.SmartControl: IR Blaster version: 25672567
,09-08 13:34:03.022  6595  6704 I jxcore-log: JXcore Cordova bridge is ready!
09-08 13:34:03.022  6595  6704 I jxcore-log: 
09-08 13:34:03.022  6595  6704 W jxcore-log: JXcore engine is started
,09-08 13:34:03.032  6710  6732 D UEI.SmartControl: serial port data available: 4
,09-08 13:34:03.034  6595  6665 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-08 13:34:03.041  6595  6595 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-08 13:34:03.066  6710  6735 I UEI.SmartControl: Device manager: loading config....
09-08 13:34:03.067  6710  6710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-08 13:34:03.067  6710  6735 D UEI.SmartControl: ----------- loading internal config...
09-08 13:34:03.068  6710  6710 E UEI.SmartControl: Services init done
09-08 13:34:03.068  6710  6710 D UEI.SmartControl: QS Service init finished
,09-08 13:34:03.069  6710  6710 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 13:34:03.069  6710  6710 D UEI.SmartControl: QS Service version code: 201091
,09-08 13:34:03.069  6710  6710 D UEI.SmartControl: Service requested: Control
09-08 13:34:03.077  6710  6735 E UEI.SmartControl: Loading SETTINGS...
09-08 13:34:03.080  6710  6710 D UEI.SmartControl: Request IControl service: devices are loaded...
09-08 13:34:03.082  1031  1970 I ActivityManager: Killing 5667:com.lge.qremote/u0a112 (adj 15): empty #17
,09-08 13:34:03.091  6710  6735 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-08 13:34:03.104  6710  6734 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 13:34:03.104  6710  6734 D UEI.SmartControl: -----service ready thread exits
,09-08 13:34:03.262  1031  2045 W libprocessgroup: failed to open /acct/uid_10112/pid_5667/cgroup.procs: No such file or directory
,09-08 13:34:03.264  6710  6710 D UEI.SmartControl: Internal service binding...
,09-08 13:34:05.586  6549  6549 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-08 13:34:05.587  1031  1897 I ActivityManager: Killing 5219:com.android.calendar/u0a13 (adj 15): empty #17
,09-08 13:34:05.662  1031  1971 W libprocessgroup: failed to open /acct/uid_10013/pid_5219/cgroup.procs: No such file or directory
,09-08 13:34:06.579  6549  6647 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-08 13:34:08.066  6710  6736 D UEI.SmartControl: Internal timer expired: 1
,09-08 13:34:08.067  6710  6736 D UEI.SmartControl: unbind internal service
,09-08 13:34:08.075  6710  6710 D UEI.SmartControl: Service.onUnbind: IControl
09-08 13:34:08.076  6710  6710 D UEI.SmartControl: Service.onDestroy
09-08 13:34:08.076  6710  6710 D UEI.SmartControl: Lock is in USE false
09-08 13:34:08.076  6710  6710 D UEI.SmartControl: unbind internal service
09-08 13:34:08.079  6710  6710 D serial_port: close(fd = 25)
09-08 13:34:08.083  6710  6710 I UEI.SmartControl: Serial port is closed.
,09-08 13:34:08.089  6710  6710 I UEI.SmartControl: Serial port is closed.
09-08 13:34:08.090  6710  6710 D UEI.SmartControl: Blaster closed
09-08 13:34:08.091  6710  6710 D UEI.SmartControl: Shut down QS...
09-08 13:34:08.091  6710  6710 D UEI.SmartControl: Stopping QS lib
09-08 13:34:08.091  6710  6710 D UEI.SmartControl: QS lib stop result = true
09-08 13:34:08.091  6710  6710 D UEI.SmartControl: Stopped QS lib
09-08 13:34:08.091  6710  6710 D UEI.SmartControl: Stopped file observer...
09-08 13:34:08.091  6710  6710 D UEI.SmartControl: QS shutdown complete
09-08 13:34:08.744  1811  6454 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-08 13:34:08.761   315  6785 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-08 13:34:08.763   315  6785 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
,09-08 13:34:08.763   315  6785 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-08 13:34:09.039  1811  1811 I ConfigFetchService: launchTask
,09-08 13:34:09.093  1031  1779 V SIM_STK : Menu title from STK is T-Mobile
,09-08 13:34:09.099  1811  6454 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-08 13:34:09.364  1811  6454 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-08 13:34:09.369  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
09-08 13:34:09.371  1811  1811 I ConfigFetchService: stopping self
,09-08 13:34:09.513  1031  1933 I art     : Explicit concurrent mark sweep GC freed 25142(1168KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.388ms total 134.143ms
,09-08 13:34:09.551  2177  2177 I ConfigService: onDestroy
,09-08 13:34:10.260  2160  2160 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19983
,09-08 13:34:13.691  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 13:34:13.691  6595  6704 I jxcore-log: 
,09-08 13:34:13.694  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 13:34:13.694  6595  6704 I jxcore-log: 
09-08 13:34:13.699  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:13.699  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:13.699  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:13.699  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:13.699  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:13.699  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:13.699  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:13.699  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:13.702  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:13.704  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 13:34:13.704  6595  6704 I jxcore-log: 
,09-08 13:34:13.706  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 13:34:13.706  6595  6704 I jxcore-log: 
09-08 13:34:13.904  1031  1109 I ActivityManager: Waited long enough for: ServiceRecord{201efd19 u0 com.google.android.gms/.wearable.service.WearableService}
,09-08 13:34:14.209  6595  6704 I jxcore-log: Unit Test app is loaded
09-08 13:34:14.209  6595  6704 I jxcore-log: 
,09-08 13:34:14.216  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:14.216  6595  6704 I jxcore-log: 
09-08 13:34:14.221  6595  6704 D executeNativeTests: Running unit tests
09-08 13:34:14.222  6595  6704 D BluetoothAdapter: enable(): BT is already enabled..!
09-08 13:34:14.223  1031  2045 D WifiServiceImplEx: setWifiEnabled: true pid=6595, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 13:34:14.224  1031  2045 D WifiService: setWifiEnabled: true pid=6595, uid=10118
09-08 13:34:14.224  1031  2045 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 13:34:14.233  6595  6595 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 13:34:14.714  1031  1374 V AlarmManager: RTC_WAKEUP set : Alarm{56c4e98 type 0 when 1473334454697 com.android.vending} when 1473334454697
,09-08 13:34:14.821  1031  2006 V SIM_STK : Menu title from STK is T-Mobile
,09-08 13:34:15.000  6173  6173 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-08 13:34:17.388  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 13:34:17.388  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca added. We now have 2 listener(s)
,09-08 13:34:17.391  1031  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.394  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 13:34:17.394  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:17.395  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:17.395  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:17.395  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b added. We now have 2 listener(s)
09-08 13:34:17.395  6595  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:17.395  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:34:17.399  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.402  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:17.402  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.402  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.402  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:17.402  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.402  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.402  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:17.402  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:17.407  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.407  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:17.409  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.411  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.418  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 13:34:17.422  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 13:34:17.422  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 13:34:17.424  6595  6704 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 13:34:17.425  6595  6704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 13:34:17.425  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 13:34:17.425  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 13:34:17.425  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 13:34:17.426  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.426  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.426  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.426  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:17.426  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca removed from the list
09-08 13:34:17.426  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.426  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b removed from the list
09-08 13:34:17.426  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.426  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.430  6595  6704 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 13:34:17.431  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.431  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.431  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.431  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.431  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.431  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.431  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.431  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.431  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 13:34:17.443  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 13:34:17.444  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.444  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.444  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.444  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.444  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.444  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
,09-08 13:34:17.444  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.444  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.444  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.445  6595  6704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 13:34:17.449  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:17.461  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:17.461  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.461  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.461  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:17.461  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.461  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.461  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:17.461  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:17.465  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.465  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:17.467  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.469  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.470  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 13:34:17.470  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 13:34:17.470  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 13:34:17.470  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.470  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:17.475  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 13:34:17.477  1031  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.484  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 13:34:17.491  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 13:34:17.495  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 13:34:17.497  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 13:34:17.498  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.500  6595  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 13:34:17.501  6595  6704 I io.jxcore.node.ConnectionHelper: start: OK
09-08 13:34:17.502  6595  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-08 13:34:17.502  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 13:34:17.502  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 13:34:17.505  6595  6704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 13:34:17.505  6595  6704 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-08 13:34:17.505  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 13:34:17.505  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 13:34:17.505  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 13:34:17.505  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.505  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 13:34:17.514  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 13:34:17.515  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.516  6595  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 13:34:17.516  6595  6704 I io.jxcore.node.ConnectionHelper: start: OK
09-08 13:34:17.517  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.517  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.517  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.517  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.517  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.517  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.517  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.517  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.519  6595  6704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 13:34:17.524  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.527  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:17.527  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.527  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.527  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:17.527  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.527  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.527  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:17.527  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:17.528  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.528  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:17.532  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 13:34:17.532  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 13:34:17.532  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 13:34:17.532  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.532  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 13:34:17.541  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.542  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.548  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 13:34:17.550  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.552  6595  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 13:34:17.552  6595  6704 I io.jxcore.node.ConnectionHelper: start: OK
09-08 13:34:17.552  6595  6704 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-08 13:34:17.552  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 13:34:17.552  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 13:34:17.556  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.556  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.556  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.556  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.556  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.556  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.556  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.556  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.558  6595  6704 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 13:34:17.558  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.558  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.558  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.558  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.558  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.558  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.558  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.558  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.558  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.559  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 13:34:17.560  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.560  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.560  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.560  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.560  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.560  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.560  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.560  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.560  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.561  6595  6704 I io.jxcore.node.ConnectionHelper: o,nConnectionManagerStateChanged: null
09-08 13:34:17.561  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.561  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.562  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.562  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.562  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.562  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.562  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.562  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.562  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.563  6595  6704 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 13:34:17.563  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.563  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.563  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.563  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.563  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.563  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.563  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:17.563  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.563  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.564  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 13:34:17.565  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 13:34:17.565  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 13:34:17.565  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 13:34:17.565  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 13:34:17.565  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 13:34:17.566  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:17.566  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.566  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.566  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.566  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.566  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.566  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.566  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.566  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.567  6595  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:17.567  6595  6704 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 13:34:17.567  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 13:34:17.570  6595  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:17.571  6595  6704 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 13:34:17.571  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010],
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 13:34:17.572  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-08 13:34:17.572  6595  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 13:34:17.572  6595  6704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 13:34:17.572  6595  6704 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 13:34:17.572  6595  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:17.573  6595  6704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 13:34:17.573  6595  6704 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 13:34:17.573  6595  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:17.573  6595  6704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 13:34:17.573  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 13:34:17.577  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 13:34:17.584  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 13:34:17.584  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 13:34:17.586  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 13:34:17.586  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 13:34:17.586  6595  6704 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-08 13:34:17.588  6595  6704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:17.588  6595  6704 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 13:34:17.589  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.589  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.589  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.590  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 13:34:17.590  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.590  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.590  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.590  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.590  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.590  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.592  6595  6704 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 13:34:17.592  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.592  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.592  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.593  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.593  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.593  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.593  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.593  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.593  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.595  6595  6812 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 855
09-08 13:34:17.598  6595  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 855)
09-08 13:34:17.598  6595  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 855)
,09-08 13:34:17.601  6595  6704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 13:34:17.601  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.601  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.601  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.601  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.601  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.601  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.601  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.601  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.602  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.602  6595  6704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 13:34:17.603  6595  6704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 13:34:17.603  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 13:34:17.603  6595  6704 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 13:34:17.603  6595  6704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 13:34:17.603  6595  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 13:34:17.603  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 13:34:17.603  6595  6704 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 13:34:17.603  6595  6704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 13:34:17.604  6595  6704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 13:34:17.604  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 13:34:17.604  6595  6704 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 13:34:17.604  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.604  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.604  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.604  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.604  6595  6704 I org.thaliproject.p2p,.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.604  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.604  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.604  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.604  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.605  6595  6704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 13:34:17.607  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.610  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:17.610  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.610  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.610  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:17.610  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.610  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.610  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:17.610  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:17.614  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.614  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:17.616  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.617  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 13:34:17.617  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 13:34:17.617  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 13:34:17.617  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.617  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:17.619  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.622  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 13:34:17.622  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.624  6595  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 13:34:17.624  6595  6704 I io.jxcore.node.ConnectionHelper: start: OK
09-08 13:34:17.625  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.625  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.625  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.625  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.625  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.625  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.625  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.625  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.628  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.628  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.628  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.628  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.628  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.628  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.628  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.628  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.628  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.630  6595  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 13:34:17.631  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.631  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 13:34:17.632  6595  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 13:34:17.632  6595  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 13:34:17.633  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 13:34:17.633  6595  6595 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 13:34:17.633  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 13:34:17.634  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.634  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:17.634  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 13:34:17.634  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 13:34:17.634  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.634  6595  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 13:34:17.634  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
,09-08 13:34:17.634  6595  6595 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 13:34:17.634  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.635  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 13:34:17.635  6595  6704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 13:34:17.635  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:17.636  1031  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.637  6595  6815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:17.638  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 13:34:17.639  3818  3834 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-08 13:34:17.640  6595  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:17.640  6595  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 13:34:17.641  6595  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 13:34:17.642  6595  6704 D BluetoothLeScanner: could not find callback wrapper
09-08 13:34:17.642  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 13:34:17.642  6595  6704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 13:34:17.642  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.642  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.643  6595  6704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 13:34:17.644  6595  6595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 13:34:17.644  6595  6595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 13:34:17.644  6595  6595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 13:34:17.644  6595  6595 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 13:34:17.644  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.644  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.644  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.644  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.646  6595  6704 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 13:34:17.646  6595  6704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 13:34:17.646  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 13:34:17.647  6595  6704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 13:34:17.647  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.647  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.647  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.647  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.647  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.647  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.647  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.647  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.647  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.649  1031  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.650  1031  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.651  1031  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.652  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.652  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.652  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.652  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.652  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.652  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.652  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.652  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.652  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.654  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.654  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.654  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.654  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e697ca not in the list
09-08 13:34:17.654  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.654  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12aa5d3b not in the list
09-08 13:34:17.654  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.654  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.654  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.656  6595  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 13:34:17.656  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 13:34:17.656  6595  6704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 13:34:17.656  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 13:34:17.656  6595  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 13:34:17.656  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 13:34:17.659  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 13:34:17.659  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 13:34:17.660  6595  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 13:34:17.660  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 13:34:17.660  6595  6704 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 13:34:17.660  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 13:34:17.660  6595  6704 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 13:34:17.661  6595  6704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 13:34:17.661  6595  6704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 13:34:17.662  6595  6704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 13:34:17.662  6595  6704 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 13:34:17.663  6595  6704 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 13:34:17.663  6595  6704 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 13:34:17.663  6595  6704 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 13:34:17.666  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:17.666  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33b605e9 added. We now have 2 listener(s)
09-08 13:34:17.667  1031  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.669  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 13:34:17.669  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:17.670  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:17.670  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:17.670  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3583b26e added. We now have 2 listener(s)
09-08 13:34:17.670  6595  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:17.671  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:34:17.674  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.678  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:17.678  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.678  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.678  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:17.678  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.678  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.678  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:17.678  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:17.680  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.680  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:17.683  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.685  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.685  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.685  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.685  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:17.685  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.685  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33b605e9 removed from the list
09-08 13:34:17.685  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.686  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3583b26e removed from the list
09-08 13:34:17.686  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.686  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.687  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:17.687  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d2719c added. We now have 2 listener(s)
09-08 13:34:17.687  1031  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.690  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 13:34:17.690  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:17.690  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:17.690  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:17.690  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13e017a5 added. We now have 2 listener(s)
09-08 13:34:17.690  6595  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:17.691  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:34:17.698  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:17.702  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:17.702  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.702  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.702  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:17.702  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.702  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.702  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:17.702  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:17.704  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.704  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:17.705  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:17.705  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:17.705  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:17.705  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:17.705  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d2719c removed from the list
09-08 13:34:17.705  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:17.706  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13e017a5 removed from the list
09-08 13:34:17.706  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.709  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.709  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:17.709  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:17.710  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:17.710  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9690b2b added. We now have 2 listener(s)
09-08 13:34:17.711  1031  1570 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:17.714  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 13:34:17.714  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:17.714  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:17.714  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:17.714  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11630b88 added. We now have 2 listener(s)
09-08 13:34:17.714  6595  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:17.714  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:17.717  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:17.722  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:17.722  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.722  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.722  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:17.722  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.722  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.722  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:17.722  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:17.724  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:17.724  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:17.726  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:17.728  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:17.733  1031  1971 D WifiServiceImplEx: setWifiEnabled: false pid=6595, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-08 13:34:17.733  1031  1971 D WifiService: setWifiEnabled: false pid=6595, uid=10118
09-08 13:34:17.733  1031  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 13:34:17.755  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 13:34:17.755  1031  1533 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-08 13:34:17.756  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 13:34:17.756  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:17.756  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,09-08 13:34:17.756  1031  1533 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:17.757  1031  1533 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:17.757  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:17.757  1031  1533 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 13:34:17.757  1031  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 13:34:17.757  1031  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 13:34:17.759  1031  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 13:34:17.759  1031  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 13:34:17.776  1031  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-08 13:34:17.776  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 13:34:17.777  1031  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.777  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 13:34:17.777  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.777  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 13:34:17.778  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 13:34:17.778  1031  1533 D WifiNative-wlan0: SET ps 1: returned true
09-08 13:34:17.778  1031  2862 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.779   315   904 D CommandListener: Clearing all IP addresses on wlan0
09-08 13:34:17.814  1031  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 13:34:17.814  1031  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-08 13:34:17.819  1935  1935 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-08 13:34:17.823  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:17.823  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:17.824  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-08 13:34:17.824  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:17.824  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:17.825  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 13:34:17.830  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:17.840  1031  1046 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-08 13:34:17.840  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.840  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 13:34:17.840  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 13:34:17.840  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.841  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-08 13:34:17.854  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-08 13:34:17.854  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:17.854  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:17.854  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 13:34:17.855  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 13:34:17.855  1031  1031 D RttService: SCAN_AVAILABLE : 1
09-08 13:34:17.855  1031  1551 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.856  1031  1552 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.858  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.858  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.858  1031  1532 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@18fb10e1
09-08 13:34:17.858  1031  1532 D LGWifiP2pService: P2pDisablingState
09-08 13:34:17.859  1031  1532 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.859  1031  1532 D LGWifiP2pService: p2p socket connection lost
09-08 13:34:17.859  1031  1532 D LGWifiP2pService: P2pDisabledState
09-08 13:34:17.860  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 13:34:17.862  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 13:34:17.864  1031  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 1 0 cz
09-08 13:34:17.865  1935  1935 D WfdsService: WifiP2pState is changed : false
09-08 13:34:17.865  1935  2281 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-08 13:34:17.865  1935  2281 D WfdsService: Set the WFDS Monitor: false
09-08 13:34:17.866  1935  2281 D WfdsMonitor: WFDS Monitor is stopped
09-08 13:34:17.866  1935  2281 D WfdsService: STATE : WfdsDisabledState - enter
09-08 13:34:17.866  1935  2858 D CtrlSupplicant: Received on exit socket, terminate
09-08 13:34:17.866  1935  2858 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-08 13:34:17.867  1935  2858 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-08 13:34:17.867  1935  2858 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-08 13:34:17.867  1935  2281 W WfdsService: DefaultState - msg [9445378] is not handled
09-08 13:34:17.867  1935  2290 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-08 13:34:17.869  1031  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:17.872  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:17.872  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:17.873  1031  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:17.873  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:17.873  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 13:34:17.873  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:17.874  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:17.874  1031  1533 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 13:34:17.875  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:17.875  1031  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-08 13:34:17.876  1031  1532 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.876  1031  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.876  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 13:34:17.876  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 13:34:17.877  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 13:34:17.877  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 13:34:17.877  1031  1533 D WifiNative-wlan0: SET ps 1: returned true
09-08 13:34:17.891   315   904 D CommandListener: Clearing all IP addresses on wlan0
,09-08 13:34:17.891  1031  1539 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-08 13:34:17.891  1031  1539 D DSQN    : disableDataServiceNotify
09-08 13:34:17.891  1031  1539 D DSQN    : stop dsqn bin
09-08 13:34:17.891   315  6830 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-08 13:34:17.892  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-08 13:34:17.892  1031  1111 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 13:34:17.902  1031  1539 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 13:34:17.902  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:17.902  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:17.902  1031  1539 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:17.903  1031  1539 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-08 13:34:17.903  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 13:34:17.903  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.903  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:17.903  1031  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 13:34:17.903  1031  1539 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-08 13:34:17.903  1031  1539 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 13:34:17.904  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 13:34:17.917  1031  2006 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6831 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 13:34:17.920  1031  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:17.920  1031  1533 D WifiNative-p2p0: doBoolean: TERMINATE
09-08 13:34:17.921  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 13:34:17.921  1031  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:17.922  1031  1533 D WifiNative-p2p0: TERMINATE: returned true
09-08 13:34:17.922  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-08 13:34:17.922  1031  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 13:34:17.922  1031  1533 E WifiStateMachine: useWiFiOffloading() : false
09-08 13:34:17.922  1031  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 13:34:17.922  1031  1539 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:17.922  1031  1539 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:17.922  1031  1539 D NetworkManagementService: Removing idletimer
09-08 13:34:17.923  1031  1539 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:17.923  1846  1846 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:17.923  1031  1539 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 13:34:17.923  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:17.924  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:17.924  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 13:34:17.924  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 13:34:17.925  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 13:34:17.925  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:17.925  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,09-08 13:34:17.925  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 13:34:17.925  1031  1531 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 13:34:17.926  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 13:34:17.926  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 13:34:17.927  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 13:34:17.927  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 13:34:17.927  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 13:34:17.927  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 13:34:17.927  1031  1531 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 13:34:17.928  1031  1533 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 1 0 cz
09-08 13:34:17.928  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 13:34:17.928  1031  1533 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:17.928  1031  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:17.930  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-08 13:34:17.931  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-08 13:34:17.932  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:17.932  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-08 13:34:17.938  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:17.938  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.938  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.938  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 13:34:17.938  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.938  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:17.938  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:17.938  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:17.940  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 13:34:17.946  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:17.946  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:17.946  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:17.946  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 13:34:17.946  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:17.946  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:17.946  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:17.946  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:17.947  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:17.986  1031  2862 D DhcpStateMachine: StoppedState
,09-08 13:34:17.986  1031  2862 D DhcpStateMachine: StoppedState{ when=-108ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 13:34:17.987  1031  1533 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-08 13:34:17.987  1031  1533 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-08 13:34:17.989  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 13:34:17.989  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:17.990  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:17.994  2744  2744 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-08 13:34:17.995  2744  2744 I wpa_supplicant: monitor socket send errors count : 1
09-08 13:34:17.995  2744  2744 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1935-2\x00 that cannot receive messages
09-08 13:34:17.996  1031  2857 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-08 13:34:17.996  1031  2857 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-08 13:34:18.003  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-08 13:34:18.004  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:18.004  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:18.006  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:18.016  6831  6831 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 13:34:18.020  6831  6831 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-08 13:34:18.022  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:18.028  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 13:34:18.029  1031  2857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-08 13:34:18.029  1031  2857 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 13:34:18.029  1031  2857 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 13:34:18.029  1031  2857 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-08 13:34:18.029  2744  2744 W wpa_supplicant: USIM:  scard_deinit function
09-08 13:34:18.030  1031  2857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:18.030  1031  2857 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:18.031  1031  1533 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123058
09-08 13:34:18.031  1031  1533 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123059
09-08 13:34:18.032  1031  1113 D Tethering: InitialState.processMessage what=4
09-08 13:34:18.032  1031  1533 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=123060  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,09-08 13:34:18.033  1031  1533 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=123060  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 13:34:18.069  1031  2007 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6851 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 13:34:18.070  1031  2007 I ActivityManager: Killing 6230:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-08 13:34:18.122  1031  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-08 13:34:18.123  1031  1047 W libprocessgroup: failed to open /acct/uid_10014/pid_6230/cgroup.procs: No such file or directory
09-08 13:34:18.127  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-08 13:34:18.127  1031  2857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-08 13:34:18.127  1031  2857 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-TERMINATING 
09-08 13:34:18.127  1031  2857 D WifiMonitor: Disconnecting from the supplicant, no more events
09-08 13:34:18.129  1031  1533 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 19 0
09-08 13:34:18.145  6595  6595 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 13:34:18.178  6851  6851 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 13:34:18.178  6851  6851 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-08 13:34:18.179  6851  6851 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 13:34:18.179  6851  6851 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-08 13:34:18.181  6851  6851 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 13:34:18.182  6851  6851 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-08 13:34:18.232  1031  1533 D WifiOffDelayIfNotUsed: stopMonitoring
09-08 13:34:18.232  1031  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 13:34:18.232  1031  1533 E WifiStateMachine: useWiFiOffloading() : false
09-08 13:34:18.232  1031  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 13:34:18.238  1935  1935 D WfdsService: Supplicant Connection state is changed : false
09-08 13:34:18.239  1935  2281 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-08 13:34:18.239  1935  2281 D WfdsService: Set the WFDS Monitor: false
09-08 13:34:18.239  1935  2281 D WfdsMonitor: WFDS Monitor is stopped
09-08 13:34:18.243  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:18.246  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,09-08 13:34:18.248  2449  2449 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:18.253  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-08 13:34:18.254  1031  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-08 13:34:18.254  1031  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-08 13:34:18.256  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:18.258  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:18.353  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:18.401  6851  6851 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 13:34:18.401  6851  6851 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:18.414  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:18.444  1031  1533 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 1 0 cz
,09-08 13:34:18.445  1031  1533 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 1 0 cz
,09-08 13:34:18.446  1031  1533 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:18.447  1031  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:18.494  1031  1897 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6869 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-08 13:34:18.496  1031  1897 I ActivityManager: Killing 6312:com.android.defcontainer/u0a4 (adj 15): empty #17
,09-08 13:34:18.551  1031  1970 W libprocessgroup: failed to open /acct/uid_10004/pid_6312/cgroup.procs: No such file or directory
,09-08 13:34:18.582  6869  6869 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 13:34:18.608  6869  6869 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-08 13:34:18.639  6869  6869 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-08 13:34:18.640  6869  6869 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-08 13:34:18.640  6869  6869 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-08 13:34:18.641  6869  6869 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-08 13:34:18.641  6869  6869 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-08 13:34:18.643  6869  6869 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-08 13:34:18.648  6869  6869 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-08 13:34:18.653  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 13:34:18.658  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:18.675  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 13:34:18.677  6869  6869 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-08 13:34:18.680  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:18.681  6869  6869 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-08 13:34:18.686  6831  6831 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 13:34:18.687  6831  6831 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 13:34:18.687  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:18.696  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:18.703  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:18.709  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:18.710  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 13:34:18.711  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 13:34:18.716  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:18.720  6831  6831 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 13:34:18.720  6831  6831 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 13:34:18.721  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:18.725  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:18.742  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:18.750  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:18.750  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:18.752  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 13:34:18.809  1031  1934 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6892 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-08 13:34:18.831   395   395 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 21.873ms
,09-08 13:34:18.852   395   395 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 20.643ms
,09-08 13:34:18.874   395   395 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 472us total 20.741ms
09-08 13:34:18.920  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 13:34:18.927  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 13:34:18.935  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:18.952  6892  6911 W FormManager: Network not available. Please check & try again.
,09-08 13:34:18.956  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 13:34:18.956  6851  6851 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 13:34:18.956  6851  6851 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 13:34:18.956  6851  6851 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 13:34:18.958  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 13:34:18.961  6892  6912 V FormManager: Network unavailable.
09-08 13:34:18.963  6892  6912 V FormManager: Network unavailable.
09-08 13:34:18.969  6851  6851 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-08 13:34:18.969  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 13:34:18.969  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 13:34:18.969  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 13:34:18.969  6851  6851 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 13:34:18.971  6851  6851 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 13:34:18.975  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 13:34:18.975  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:18.977  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:18.980  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:18.988  6831  6831 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-08 13:34:18.988  6831  6831 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 13:34:18.988  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 13:34:18.993  4291  6915 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 13:34:18.995  4291  6918 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 13:34:18.995  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 13:34:18.996  4291  6918 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-08 13:34:19.002  6892  6916 W FormManager: Network not available. Please check & try again.
09-08 13:34:19.006  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:19.006  6892  6917 V FormManager: Network unavailable.
09-08 13:34:19.012  6892  6917 V FormManager: Network unavailable.
09-08 13:34:19.017  1031  1952 I ActivityManager: Killing 6472:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-08 13:34:19.046  1031  2006 W libprocessgroup: failed to open /acct/uid_10008/pid_6472/cgroup.procs: No such file or directory
,09-08 13:34:19.057  6869  6869 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-08 13:34:19.058  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 13:34:19.059  6869  6869 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-08 13:34:19.107  6869  6869 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:19.107  6869  6869 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:19.119  6869  6869 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-08 13:34:19.122  6869  6869 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-08 13:34:19.122  6869  6869 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-08 13:34:19.123  6869  6869 V SoundPool: doLoad: loading sample sampleID=1
,09-08 13:34:19.126  6869  6921 V SoundPool: Start decode
09-08 13:34:19.126  6869  6921 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-08 13:34:19.127  6869  6869 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 13:34:19.128   319  1380 V MediaPlayerService: decode(22, 10857164, 17813)
09-08 13:34:19.128   319  1380 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-08 13:34:19.128   319  1380 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-08 13:34:19.128   319  1380 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-08 13:34:19.128   319  1380 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-08 13:34:19.128   319  1380 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-08 13:34:19.128   319  1380 V MediaPlayerService: player type = 3
09-08 13:34:19.128   319  1380 V AwesomePlayer: AwesomePlayer create()
09-08 13:34:19.129   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:19.129   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:19.129   319  1380 V AwesomePlayer: setAudioSink() 
09-08 13:34:19.129   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:19.129   319  1380 V AudioCache: notify(0xb1432400, 8, 0, 0)
09-08 13:34:19.129   319  1380 V AudioCache: ignored
09-08 13:34:19.129   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:19.129   319  1380 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-08 13:34:19.129   319  1380 V AwesomePlayer: setDataSource_l dataSource
09-08 13:34:19.129   319  1380 V LGParserOSAL: SniffLGParser start
09-08 13:34:19.129   319  1380 V LGParserOSAL: MainType:5, SubType=0
09-08 13:34:19.129   319  1380 V LGParserOSAL: #### check Mime : application/ogg
09-08 13:34:19.129   319  1380 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-08 13:34:19.129   319  1380 E MediaExtractor: Use LGExtractor :application/ogg 
09-08 13:34:19.140  6710  6710 D UEI.SmartControl: QS Service created
09-08 13:34:19.140  6869  6869 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-08 13:34:19.151  6869  6869 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 13:34:19.152  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 13:34:19.165  6869  6869 V LGMDMManager: Create singleton instance
,09-08 13:34:19.172  6710  6710 I UEI.SmartControl: Service initServices...
09-08 13:34:19.172  6710  6710 D UEI.SmartControl: QS start get config
,09-08 13:34:19.183   319  1380 V LGParserOSAL: supported mime: application/ogg
09-08 13:34:19.183   319  1380 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,09-08 13:34:19.183   319  1380 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,09-08 13:34:19.183   319  1380 V AwesomePlayer: mBitrate = -1 bits/sec
09-08 13:34:19.183   319  1380 V AwesomePlayer: AudioTrack Setting
09-08 13:34:19.183   319  1380 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-08 13:34:19.183   319  1380 V AwesomePlayer: setAudioSource() 
09-08 13:34:19.183   319  1380 V MediaPlayerService: prepare
09-08 13:34:19.183   319  1380 V AwesomePlayer: prepareAsync_l() 
09-08 13:34:19.183   319  1380 V MediaPlayerService: wait for prepare
09-08 13:34:19.183   319  6922 V AwesomePlayer: onPrepareAsyncEvent() 
09-08 13:34:19.183   319  6922 V AwesomePlayer: initAudioDecoder() 
09-08 13:34:19.183   319  6922 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-08 13:34:19.183   319  6922 V AudioSystem: isOffloadSupported()
09-08 13:34:19.184   319  6922 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-08 13:34:19.184   319  6922 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-08 13:34:19.184   319  6922 I AudioFlinger: isAudioPlaybackHookOn() false
09-08 13:34:19.184   319  6922 V AwesomePlayer: getUseOffload() = 0 
09-08 13:34:19.184   319  6922 V OMXCodec: OMXCodec::Create
09-08 13:34:19.184   319  6922 V OMXCodec: findMatchingCodecs()
09-08 13:34:19.184   319  6922 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-08 13:34:19.184   319  6922 V OMXCodec: matchingCodecs.size()=1
09-08 13:34:19.184   319  6922 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-08 13:34:19.186   319  6922 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-08 13:34:19.186   319  6922 V LGCodecAdapter: LG Codec Adapter start
09-08 13:34:19.186   319  6922 V OMXCodec: OMXCodec Createtor
09-08 13:34:19.186   319  6922 V OMXCodec: setComponentRole
09-08 13:34:19.186   319  6922 V OMXCodec: configureCodec protected=0
09-08 13:34:19.186   319  6922 V LGCodecAdapter: called getLGCodecSpecificData
09-08 13:34:19.186   319  6922 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-08 13:34:19.187   319  6922 V LGCodecOSAL: Called LGconfigureCodecMETA
09-08 13:34:19.187   319  6922 V LGCodecOSAL: Called LGconfigureCodecMSG
09-08 13:34:19.187   319  6922 V LGCodecOSAL: Not support LGCodec
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-08 13:34:19.187   319  6922 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-08 13:34:19.187   319  6922 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-08 13:34:19.187   319  6922 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-08 13:34:19.187   319  6922 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-08 13:34:19.187   319  6922 V AudioSystem: isOffloadSupported()
09-08 13:34:19.187   319  6922 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-08 13:34:19.187   319  6922 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-08 13:34:19.187   319  6922 V OMXCodec: init()
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-08 13:34:19.187   319  6922 V OMXCodec: allocateBuffers
09-08 13:34:19.187   319  6922 V OMXCodec: allocateBuffersOnPort portIndex=0
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on, input port
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-08 13:34:19.187   319  6922 V OMXCodec: allocateBuffersOnPort portIndex=1
09-08 13:34:19.187   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-08 13:34:19.188   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-08 13:34:19.188   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-08 13:34:19.188   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
09-08 13:34:19.188   319  6922 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
09-08 13:34:19.188   319  6922 V OMXCodec: init() mAsyncCompletion wait!!! 
09-08 13:34:19.188   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-08 13:34:19.188   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-08 13:34:19.188   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-08 13:34:19.188   319  6922 V OMXCodec: init() mAsyncCompletion wait!!! 
09-08 13:34:19.188   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-08 13:34:19.188   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-08 13:34:19.188   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-08 13:34:19.188   319  6922 V OMXCodec: init() mAsyncCompletion wait free! 
09-08 13:34:19.188   319  6922 V AwesomePlayer: finishAsyncPrepare_l() 
09-08 13:34:19.188   319  6922 V AudioCache: notify(0xb1432400, 5, 0, 0)
09-08 13:34:19.188   319  6922 V AudioCache: ignored
09-08 13:34:19.188   319  6922 V AudioCache: notify(0xb1432400, 1, 0, 0)
09-08 13:34:19.188   319  6922 V AudioCache: prepared
09-08 13:34:19.188   319  1380 V AudioCache: wait - success
09-08 13:34:19.188   319  1380 V MediaPlayerService: start
09-08 13:34:19.188   319  1380 V AwesomePlayer: play_l() 
09-08 13:34:19.188   319  1380 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-08 13:34:19.188   319  1380 V AwesomePlayer: createAudioPlayer_l
09-08 13:34:19.189   319  1380 V AwesomePlayer: seekAudioIfNecessary_l() 
09-08 13:34:19.189   319  1380 V AwesomePlayer: startAudioPlayer_l() 
,09-08 13:34:19.189   319  1380 D AudioPlayer: start of Playback, useOffload 0
09-08 13:34:19.189   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-08 13:34:19.189   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-08 13:34:19.191   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-08 13:34:19.192   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-08 13:34:19.193   319  6924 V OMXCodec: allocateBuffersOnPort portIndex=1
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-08 13:34:19.193   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-08 13:34:19.194   319  1380 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-08 13:34:19.194   319  1380 V AudioCache: notify(0xb1432400, 6, 0, 0)
,09-08 13:34:19.194   319  1380 V AudioCache: ignored
09-08 13:34:19.194   319  1380 V MediaPlayerService: wait for playback complete
09-08 13:34:19.195   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.195   319  6925 V AudioCache: memcpy(0xaf104000, 0xb57cc000, 4096)
,09-08 13:34:19.200   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.200   319  6925 V AudioCache: memcpy(0xaf105000, 0xb57cc000, 4096)
09-08 13:34:19.201   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.201   319  6925 V AudioCache: memcpy(0xaf106000, 0xb57cc000, 4096)
09-08 13:34:19.201   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.201   319  6925 V AudioCache: memcpy(0xaf107000, 0xb57cc000, 4096)
09-08 13:34:19.202   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.202   319  6925 V AudioCache: memcpy(0xaf108000, 0xb57cc000, 4096)
09-08 13:34:19.203   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.203   319  6925 V AudioCache: memcpy(0xaf109000, 0xb57cc000, 4096)
09-08 13:34:19.204   319  6925 V AudioCache: write(0xb57cc000, 4096)
,09-08 13:34:19.204   319  6925 V AudioCache: memcpy(0xaf10a000, 0xb57cc000, 4096)
09-08 13:34:19.205   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.206   319  6925 V AudioCache: memcpy(0xaf10b000, 0xb57cc000, 4096)
09-08 13:34:19.207   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.207   319  6925 V AudioCache: memcpy(0xaf10c000, 0xb57cc000, 4096)
09-08 13:34:19.207   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.207   319  6925 V AudioCache: memcpy(0xaf10d000, 0xb57cc000, 4096)
09-08 13:34:19.208   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.208   319  6925 V AudioCache: memcpy(0xaf10e000, 0xb57cc000, 4096)
09-08 13:34:19.209   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.209   319  6925 V AudioCache: memcpy(0xaf10f000, 0xb57cc000, 4096)
09-08 13:34:19.209   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.209   319  6925 V AudioCache: memcpy(0xaf110000, 0xb57cc000, 4096)
09-08 13:34:19.210   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.210   319  6925 V AudioCache: memcpy(0xaf111000, 0xb57cc000, 4096)
09-08 13:34:19.211   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.211   319  6925 V AudioCache: memcpy(0xaf112000, 0xb57cc000, 4096)
09-08 13:34:19.211   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.211   319  6925 V AudioCache: memcpy(0xaf113000, 0xb57cc000, 4096)
09-08 13:34:19.212   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.212   319  6925 V AudioCache: memcpy(0xaf114000, 0xb57cc000, 4096)
09-08 13:34:19.214   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.214   319  6925 V AudioCache: memcpy(0xaf115000, 0xb57cc000, 4096)
09-08 13:34:19.215   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.215   319  6925 V AudioCache: memcpy(0xaf116000, 0xb57cc000, 4096)
09-08 13:34:19.216   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.216   319  6925 V AudioCache: memcpy(0xaf117000, 0xb57cc000, 4096)
09-08 13:34:19.216   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.216   319  6925 V AudioCache: memcpy(0xaf118000, 0xb57cc000, 4096)
09-08 13:34:19.217   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.217   319  6925 V AudioCache: memcpy(0xaf119000, 0xb57cc000, 4096)
09-08 13:34:19.218   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.218   319  6925 V AudioCache: memcpy(0xaf11a000, 0xb57cc000, 4096)
09-08 13:34:19.218   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.218   319  6925 V AudioCache: memcpy(0xaf11b000, 0xb57cc000, 4096)
09-08 13:34:19.219   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.219   319  6925 V AudioCache: memcpy(0xaf11c000, 0xb57cc000, 4096)
09-08 13:34:19.220   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.220   319  6925 V AudioCache: memcpy(0xaf11d000, 0xb57cc000, 4096)
09-08 13:34:19.220   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.220   319  6925 V AudioCache: memcpy(0xaf11e000, 0xb57cc000, 4096)
09-08 13:34:19.221   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.221   319  6925 V AudioCache: memcpy(0xaf11f000, 0xb57cc000, 4096)
09-08 13:34:19.222   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.222   319  6925 V AudioCache: memcpy(0xaf120000, 0xb57cc000, 4096)
09-08 13:34:19.222   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.222   319  6925 V AudioCache: memcpy(0xaf121000, 0xb57cc000, 4096)
09-08 13:34:19.223   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.223   319  6925 V AudioCache: memcpy(0xaf122000, 0xb57cc000, 4096)
09-08 13:34:19.224   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.224   319  6925 V AudioCache: memcpy(0xaf123000, 0xb57cc000, 4096)
09-08 13:34:19.224   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.224   319  6925 V AudioCache: memcpy(0xaf124000, 0xb57cc000, 4096)
09-08 13:34:19.225   319  6925 V Au,dioCache: write(0xb57cc000, 4096)
09-08 13:34:19.225   319  6925 V AudioCache: memcpy(0xaf125000, 0xb57cc000, 4096)
09-08 13:34:19.226   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.226   319  6925 V AudioCache: memcpy(0xaf126000, 0xb57cc000, 4096)
09-08 13:34:19.226   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.226   319  6925 V AudioCache: memcpy(0xaf127000, 0xb57cc000, 4096)
09-08 13:34:19.227   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.227   319  6925 V AudioCache: memcpy(0xaf128000, 0xb57cc000, 4096)
09-08 13:34:19.227   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.228   319  6925 V AudioCache: memcpy(0xaf129000, 0xb57cc000, 4096)
09-08 13:34:19.228   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.228   319  6925 V AudioCache: memcpy(0xaf12a000, 0xb57cc000, 4096)
09-08 13:34:19.229   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.229   319  6925 V AudioCache: memcpy(0xaf12b000, 0xb57cc000, 4096)
09-08 13:34:19.231   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.231   319  6925 V AudioCache: memcpy(0xaf12c000, 0xb57cc000, 4096)
09-08 13:34:19.232   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.232   319  6925 V AudioCache: memcpy(0xaf12d000, 0xb57cc000, 4096)
09-08 13:34:19.232   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.233   319  6925 V AudioCache: memcpy(0xaf12e000, 0xb57cc000, 4096)
09-08 13:34:19.233   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.233   319  6925 V AudioCache: memcpy(0xaf12f000, 0xb57cc000, 4096)
09-08 13:34:19.234   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.234   319  6925 V AudioCache: memcpy(0xaf130000, 0xb57cc000, 4096)
09-08 13:34:19.234   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.234   319  6925 V AudioCache: memcpy(0xaf131000, 0xb57cc000, 4096)
09-08 13:34:19.235   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.235   319  6925 V AudioCache: memcpy(0xaf132000, 0xb57cc000, 4096)
09-08 13:34:19.236   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.236   319  6925 V AudioCache: memcpy(0xaf133000, 0xb57cc000, 4096)
09-08 13:34:19.236   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.236   319  6925 V AudioCache: memcpy(0xaf134000, 0xb57cc000, 4096)
09-08 13:34:19.237   319  6925 V AudioCache: write(0xb57cc000, 4096)
09-08 13:34:19.237   319  6925 V AudioCache: memcpy(0xaf135000, 0xb57cc000, 4096)
09-08 13:34:19.237   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-08 13:34:19.237   319  6925 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-08 13:34:19.237   319  6925 V AwesomePlayer: postAudioEOS() 
09-08 13:34:19.237   319  6925 V AudioCache: write(0xb57cc000, 280)
09-08 13:34:19.237   319  6925 V AudioCache: memcpy(0xaf136000, 0xb57cc000, 280)
,09-08 13:34:19.250   319  6922 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-08 13:34:19.250   319  6922 V AwesomePlayer: onStreamDone
09-08 13:34:19.250   319  6922 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-08 13:34:19.250   319  6922 V AudioCache: notify(0xb1432400, 2, 0, 0)
09-08 13:34:19.250   319  6922 V AudioCache: playback complete
09-08 13:34:19.250   319  6922 V AwesomePlayer: pause_l() 
09-08 13:34:19.250   319  6922 V AudioCache: notify(0xb1432400, 7, 0, 0)
09-08 13:34:19.250   319  6922 V AudioCache: ignored
09-08 13:34:19.250   319  6922 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:19.250   319  6922 D AudioPlayer: Pause Playback at 1068125
09-08 13:34:19.255   319  1380 V AudioCache: wait - success
09-08 13:34:19.255   319  1380 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-08 13:34:19.258   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:19.258   319  1380 V AudioCache: notify(0xb1432400, 8, 0, 0)
09-08 13:34:19.258   319  1380 V AudioCache: ignored
09-08 13:34:19.258   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:19.258   319  1380 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-08 13:34:19.258   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-08 13:34:19.258   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-08 13:34:19.258   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-08 13:34:19.259   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-08 13:34:19.259   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-08 13:34:19.259   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-08 13:34:19.259   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-08 13:34:19.259   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-08 13:34:19.259   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-08 13:34:19.259   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-08 13:34:19.260   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
09-08 13:34:19.261   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-08 13:34:19.261   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-08 13:34:19.261   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-08 13:34:19.261   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
09-08 13:34:19.261   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:19.261   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-08 13:34:19.261   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-08 13:34:19.261   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-08 13:34:19.262   319  6924 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-08 13:34:19.264  , 319  1380 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-08 13:34:19.264   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-08 13:34:19.264   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,09-08 13:34:19.267   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-08 13:34:19.267   319  1380 D AudioPlayer: AudioPlayer releasing audio source
09-08 13:34:19.267   319  1380 D AudioPlayer: AudioPlayer done releasing audio source
09-08 13:34:19.268   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:19.268   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:19.268   319  1380 V AwesomePlayer: ~AwesomePlayer call
09-08 13:34:19.269   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:19.269   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:19.270  6869  6921 V SoundPool: close(31)
09-08 13:34:19.270  6869  6921 V SoundPool: pointer = 0x9fe5c000, size = 205080, sampleRate = 48000, numChannels = 2
09-08 13:34:19.276  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 13:34:19.278  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-08 13:34:19.281  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6455
09-08 13:34:19.582  6710  6710 I UEI.SmartControl: Supports setup maps: true
,09-08 13:34:19.585  6710  6710 D UEI.SmartControl: QS start statue = true Error code = 0
,09-08 13:34:19.585  6710  6710 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 13:34:19.585  6710  6710 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 13:34:19.585  6710  6710 I UEI.SmartControl: ### init IR Blaster...
09-08 13:34:19.589  6710  6710 D serial_port: Configuring serial port
09-08 13:34:19.590  6710  6710 E UEI.SmartControl: UEIBLaster setting for 616
09-08 13:34:19.590  6710  6710 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 13:34:19.590  6710  6710 I UEI.SmartControl: configuring settings for MAXQ616
09-08 13:34:19.590  6710  6710 I UEI.SmartControl: Get version...
09-08 13:34:19.608  6710  6934 D UEI.SmartControl: serial port data available: 21
,09-08 13:34:19.635  6710  6710 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-08 13:34:19.635  6710  6710 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 13:34:19.635  6710  6710 I UEI.SmartControl: QS saving settings...
09-08 13:34:19.637  6710  6710 D UEI.SmartControl: IR Blaster version: 25672567
,09-08 13:34:19.657  6710  6934 D UEI.SmartControl: serial port data available: 4
,09-08 13:34:19.695  6710  6710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-08 13:34:19.704  6710  6943 I UEI.SmartControl: Device manager: loading config....
09-08 13:34:19.704  6710  6943 D UEI.SmartControl: ----------- loading internal config...
09-08 13:34:19.708  6710  6710 E UEI.SmartControl: Services init done
09-08 13:34:19.708  6710  6710 D UEI.SmartControl: QS Service init finished
09-08 13:34:19.709  6710  6710 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 13:34:19.709  6710  6710 D UEI.SmartControl: QS Service version code: 201091
09-08 13:34:19.711  6710  6710 D UEI.SmartControl: Service requested: Control
09-08 13:34:19.713  6710  6943 E UEI.SmartControl: Loading SETTINGS...
,09-08 13:34:19.730  6710  6710 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-08 13:34:19.756  6710  6710 D UEI.SmartControl: Internal service binding...
,09-08 13:34:19.759  6869  6869 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-08 13:34:19.761  6710  6727 I UEI.SmartControl: ------ IControl API: 11
09-08 13:34:19.761  6710  6727 D UEI.SmartControl: File observer start...
09-08 13:34:19.761  6710  6727 E UEI.SmartControl: IR Port is disabled: false
09-08 13:34:19.761  6710  6727 D UEI.SmartControl: Starting file observer...
09-08 13:34:19.762  6710  6727 I UEI.SmartControl: Registering callback...
09-08 13:34:19.766  6710  6943 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-08 13:34:19.771  6710  6728 I UEI.SmartControl: ------ IControl API: 19
09-08 13:34:19.772  6710  6728 I UEI.SmartControl: Registering Services Ready callback...
,09-08 13:34:19.791  6710  6942 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-08 13:34:19.793  6869  6885 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-08 13:34:19.794  6869  6919 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-08 13:34:19.794  6869  6919 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-08 13:34:19.794  6869  6869 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-08 13:34:19.795  6869  6869 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-08 13:34:19.795  6710  6727 I UEI.SmartControl: ------ IControl API: 8
09-08 13:34:19.796  6710  6942 D UEI.SmartControl: -----service ready thread exits
09-08 13:34:19.797  6869  6869 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-08 13:34:19.798  6869  6869 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-08 13:34:19.798  6869  6869 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-08 13:34:19.798  6869  6869 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-08 13:34:19.799  6869  6869 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-08 13:34:19.800  6869  6869 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-08 13:34:19.803  6869  6869 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-08 13:34:19.808  6869  6869 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-08 13:34:19.809  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 13:34:19.809  6869  6869 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 13:34:19.810  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 13:34:19.811  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 13:34:19.812  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-08 13:34:19.812  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-08 13:34:19.813  6869  6869 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473334459813]
09-08 13:34:19.816  6869  6869 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-08 13:34:19.821  1031  1897 I ActivityManager: Killing 6102:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-08 13:34:19.857  6869  6945 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-08 13:34:19.863  1031  1952 W libprocessgroup: failed to open /acct/uid_10011/pid_6102/cgroup.procs: No such file or directory
09-08 13:34:19.869  6869  6869 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-08 13:34:19.872  6869  6869 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 13:34:19.872  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0,
09-08 13:34:19.872  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-08 13:34:19.873  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-08 13:34:19.873  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-08 13:34:19.873  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-08 13:34:19.902  6869  6869 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-08 13:34:20.672  1031  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{29d29028 type 2 when 125685 com.google.android.gms} when 125685
,09-08 13:34:20.679   315  6954 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-08 13:34:20.685  1031  1111 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-08 13:34:20.767  1031  1971 D WifiServiceImplEx: setWifiEnabled: true pid=6595, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-08 13:34:20.769  1031  1971 D WifiService: setWifiEnabled: true pid=6595, uid=10118
,09-08 13:34:20.769  1031  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 13:34:20.807  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-08 13:34:20.807  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-08 13:34:20.807  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,09-08 13:34:20.809  1031  1533 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-08 13:34:20.809  1031  1533 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-08 13:34:20.811  1031  1533 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-08 13:34:20.811  1031  1533 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 13:34:20.811  1031  1533 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-08 13:34:20.812  1031  1533 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 13:34:20.812  1031  1533 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-08 13:34:20.812  1031  1533 E WifiHW  : unknown target_country: EU , set to default
09-08 13:34:20.812  1031  1533 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-08 13:34:20.812  1031  1533 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-08 13:34:20.812  1031  1533 I WifiUtil: gEnableBmps=1
09-08 13:34:20.924  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:20.949  1031  1113 D Tethering: MasterInitialState.processMessage what=3
09-08 13:34:20.955  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:20.964  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:20.968  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:20.978  1031  1113 D Tethering: MasterInitialState.processMessage what=3
09-08 13:34:20.988  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:20.992  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:20.993  1031  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:20.995  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 13:34:20.998  6400  6439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 13:34:21.000  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-08 13:34:21.021  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-08 13:34:21.046  2177  2177 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:21.094  1031  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:21.122  1031  1898 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6971 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-08 13:34:21.125  1031  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 13:34:21.184  1031  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 13:34:21.224  6971  6971 I AppUp4:AppBoxCP: onCreate
,09-08 13:34:21.225  6971  6971 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-08 13:34:21.236  6971  6971 I AppUp4:DB:  setFingerPrint start
09-08 13:34:21.237  6971  6971 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-08 13:34:21.245  6971  6971 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-08 13:34:21.245  6971  6971 I AppUp4:DB:  SDK version = 21
09-08 13:34:21.246  6971  6971 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-08 13:34:21.248  6971  6971 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-08 13:34:21.250  6971  6971 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 13:34:21.250  6971  6971 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:21.252  6971  6971 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 13:34:21.253  6971  6971 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 13:34:21.261  6971  6971 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 13:34:21.324  6971  6971 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 13:34:21.324  6971  6971 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:21.334  6971  6971 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f3d274b
,09-08 13:34:21.335  6971  6971 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 13:34:21.335  6971  6971 D AppUp4:CustFacade: isPhone : true
,09-08 13:34:21.336  6971  6971 D AppUp4:CustModeStarterReceiver: begin check event
09-08 13:34:21.336  6971  6971 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-08 13:34:21.337  6971  6971 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-08 13:34:21.338  6971  6991 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-08 13:34:21.338  6971  6991 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-08 13:34:21.338  6971  6991 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-08 13:34:21.343  1031  1046 I ActivityManager: Killing 6123:com.android.contacts/u0a19 (adj 15): empty #17
,09-08 13:34:21.449  1031  2040 W libprocessgroup: failed to open /acct/uid_10019/pid_6123/cgroup.procs: No such file or directory
,09-08 13:34:21.454  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:21.454  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:21.456  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:21.463  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:21.468  4291  7006 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 13:34:21.473  4291  7007 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:21.473  4291  7007 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 13:34:21.496  6509  6509 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 13:34:21.512  1031  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 13:34:21.512  1031  1113 D Tethering: InitialState.processMessage what=4
09-08 13:34:21.512  1031  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-08 13:34:21.517   315   904 D SoftapController: Softap fwReload - Ok
09-08 13:34:21.552  1031  1533 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (729ms)
,09-08 13:34:21.557   315   904 D CommandListener: Setting iface cfg
09-08 13:34:21.557   315   904 D CommandListener: Trying to bring down wlan0
09-08 13:34:21.558   315   904 D CommandListener: Clearing all IP addresses on wlan0
09-08 13:34:21.561  1031  1533 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-08 13:34:21.566  1031  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 13:34:21.566  1031  1533 E WifiStateMachine: useWiFiOffloading() : false
09-08 13:34:21.566  1031  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 13:34:21.551  7010  7010 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:21.561  7010  7010 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:21.572  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:21.573  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-08 13:34:21.579  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-08 13:34:21.581  1031  1533 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 13:34:21.581  1031  1533 D WifiMonitor: connecting to supplicant
09-08 13:34:21.594  7010  7010 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 13:34:21.606  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:21.606  3323  3323 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 13:34:21.606  3323  3323 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:21.607  3323  3323 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 13:34:21.610  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:21.637  7010  7010 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 13:34:21.637  7010  7010 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-08 13:34:21.663  1031  1779 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7026 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-08 13:34:21.672  6892  7021 W FormManager: Network not available. Please check & try again.
09-08 13:34:21.675  6892  7022 V FormManager: Network unavailable.
,09-08 13:34:21.678  6892  7022 V FormManager: Network unavailable.
09-08 13:34:21.679  6509  6509 I HubEmail: JNI_OnLoad()
09-08 13:34:21.679  6509  6509 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:21.679  6509  6509 I HubEmail: registerNatives()
09-08 13:34:21.679  6509  6509 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:21.679  6509  6509 I HubEmail: registerNativeMethods()
09-08 13:34:21.679  6509  6509 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:21.680  6509  6509 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-08 13:34:21.687  6509  7043 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:21.691  7010  7010 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 13:34:21.749  7010  7010 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-08 13:34:21.762  7010  7010 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-08 13:34:21.764  7010  7010 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 13:34:21.764  7026  7026 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:21.765  7026  7026 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 13:34:21.765  1031  1533 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-08 13:34:21.766  1031  1533 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-08 13:34:21.767  1031  7044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-08 13:34:21.767  1031  7044 D WifiMonitor: Dropping event because (p2p0) is stopped
09-08 13:34:21.767  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-08 13:34:21.767  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-08 13:34:21.767  1031  7044 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-08 13:34:21.767  1031  7044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-08 13:34:21.768  7026  7026 D PhoneMonitor: Register our PhoneStateListener
09-08 13:34:21.768  1031  1533 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-08 13:34:21.771  1031  1533 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-08 13:34:21.772  1031  1533 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:21.774  1031  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:21.776  1031  1533 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-08 13:34:21.776  1031  1533 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-08 13:34:21.778  1031  1533 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,09-08 13:34:21.779  1031  1533 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-08 13:34:21.779  1031  1533 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-08 13:34:21.781  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:21.781  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:21.782  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:21.782  1031  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 13:34:21.782  1031  1533 E WifiStateMachine: useWiFiOffloading() : false
09-08 13:34:21.782  1031  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 13:34:21.782  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:21.782  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 13:34:21.783  7026  7026 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 13:34:21.783  1031  1533 D WifiNative-wlan0: doBoolean: SET update_config 1
09-08 13:34:21.785  7026  7026 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 13:34:21.786  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:21.787  1935  1935 D WfdService: Waiting for WifiP2p enabling
09-08 13:34:21.787  1031  1533 D WifiNative-wlan0: SET update_config 1: returned true
09-08 13:34:21.788  1031  1533 D WifiConfigStore: Loading config and enabling all networks 
09-08 13:34:21.788  1031  1533 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-08 13:34:21.791  1031  1533 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-08 13:34:21.792  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:21.792  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:21.792  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:21.792  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:21.792  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:21.792  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:21.792  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:21.792  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:21.794  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 13:34:21.798  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:21.798  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:21.798  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:21.798  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:21.798  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:21.798  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:21.798  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:21.798  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:21.799  1031  1533 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-08 13:34:21.801  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:21.811  7026  7026 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-08 13:34:21.811  1031  1533 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-08 13:34:21.811  1031  1533 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-08 13:34:21.812  7026  7026 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-08 13:34:21.813  7026  7026 D TelephonyAutoProfiling: [parse] Load xml
09-08 13:34:21.819  7026  7026 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-08 13:34:21.819  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,09-08 13:34:21.819  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-08 13:34:21.819  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-08 13:34:21.819  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-08 13:34:21.820  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-08 13:34:21.820  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-08 13:34:21.820  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-08 13:34:21.820  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-08 13:34:21.820  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-08 13:34:21.820  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-08 13:34:21.820  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-08 13:34:21.820  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-08 13:34:21.821  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-08 13:34:21.821  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-08 13:34:21.821  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-08 13:34:21.821  7026  7026 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-08 13:34:21.826  7026  7026 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-08 13:34:21.836  1031  2006 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7047 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:21.837  1031  2006 I ActivityManager: Killing 6149:com.android.gallery3d/u0a27 (adj 15): empty #17
09-08 13:34:21.881  1031  1533 D WifiStateMachine: enableVerboseLogging : level 2
09-08 13:34:21.881  1031  1533 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-08 13:34:21.882  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 13:34:21.882  1031  1047 W libprocessgroup: failed to open /acct/uid_10027/pid_6149/cgroup.procs: No such file or directory
,09-08 13:34:21.883  1031  1533 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-08 13:34:21.883  1031  1533 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-08 13:34:21.884  1031  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 13:34:21.884  1031  1533 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-08 13:34:21.884  1031  1533 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-08 13:34:21.885  1031  1533 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-08 13:34:21.885  1031  1533 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-08 13:34:21.886  1031  1533 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-08 13:34:21.886  1031  1533 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-08 13:34:21.887  1031  1533 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-08 13:34:21.887  1031  1533 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-08 13:34:21.887  1031  1533 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-08 13:34:21.887  1031  1533 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-08 13:34:21.888  1031  1533 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-08 13:34:21.898  1031  1533 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 13:34:21.898  1031  1533 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-08 13:34:21.901  1935  1935 D WfdsService: Supplicant Connection state is changed : true
09-08 13:34:21.901  1935  2281 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 13:34:21.901  1935  2281 D WfdsService: Set the WFDS Monitor: true
09-08 13:34:21.901  1935  2281 D WfdsMonitor: WfdsMonitorThread create
09-08 13:34:21.902  1935  2281 D WfdsMonitor: WFDS Monitor is created and started
09-08 13:34:21.902  1935  2281 D WfdsService: WiFi: Supplicant connection re-established
09-08 13:34:21.903  1031  1533 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-08 13:34:21.903  1031  1533 D WifiNative-HAL: Setting external_sim to 1
09-08 13:34:21.903  1935  7065 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 13:34:21.903  1031  1533 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-08 13:34:21.903  1935  7065 E CtrlSupplicant: Succeed to open control connection
09-08 13:34:21.903  1935  7065 E CtrlSupplicant: Succeed to open monitor connection
09-08 13:34:21.903  1031  1533 D WifiNative-wlan0: SET external_sim 1: returned true
09-08 13:34:21.904  1031  1533 I WifiNative-HAL: startHal
09-08 13:34:21.904  1935  7065 D WfdsMonitor: Supplicant connection established
09-08 13:34:21.904  1031  1533 D wifi    : setting scan oui 0xaf6b5e20
09-08 13:34:21.904  1935  2281 D WfdsService: Connected to the supplicant for wfds
09-08 13:34:21.905  1031  1533 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 13:34:21.905  1031  1533 I WifiNative-HAL: startHal
09-08 13:34:21.905  1031  1533 D wifi    : setting scan oui 0xaf6b5e20
09-08 13:34:21.906  1031  1533 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-08 13:34:21.906  1031  1533 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-08 13:34:21.906  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-08 13:34:21.906  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-08 13:34:21.907  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-08 13:34:21.907  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 13:34:21.907  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 13:34:21.907  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 13:34:21.907  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-08 13:34:21.908  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-08 13:34:21.908  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-08 13:34:21.908  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 13:34:21.908  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 13:34:21.908  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,09-08 13:34:21.908  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 13:34:21.908  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-08 13:34:21.909  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 13:34:21.909  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-08 13:34:21.909  7010  7010 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-08 13:34:21.909  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-08 13:34:21.909  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,09-08 13:34:21.909  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 13:34:21.910  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 13:34:21.911  1031  1533 E WifiNative: : [126,937,888 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-08 13:34:21.911  1031  1533 D WifiNative-wlan0: doBoolean: RECONNECT
09-08 13:34:21.911  1031  1533 D WifiNative-wlan0: RECONNECT: returned true
,09-08 13:34:21.911  1031  1533 D WifiNative-wlan0: doString: [STATUS]
09-08 13:34:21.912  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 13:34:21.912  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 13:34:21.912  1031  1533 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-08 13:34:21.912  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 13:34:21.913  1031  1533 D WifiNative-wlan0: SET ps 1: returned true
09-08 13:34:21.913  1031  1532 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 13:34:21.917  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 13:34:21.917  1031  1031 D RttService: SCAN_AVAILABLE : 3
09-08 13:34:21.918  1031  1551 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.918  1031  1551 I WifiNative-HAL: startHal
09-08 13:34:21.918  1031  1551 D wifi    : getting scan capabilities on interface[1] = 0xaf6b5e20
09-08 13:34:21.918  1031  1551 D wifi    : failed to get capabilities : -3
09-08 13:34:21.918  1031  1551 E WifiScanningService: could not get scan capabilities
09-08 13:34:21.918  1031  1552 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.919  1031  1533 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-08 13:34:21.920  1031  1533 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-08 13:34:21.920  1031  1533 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-08 13:34:21.921  1031  1533 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-08 13:34:21.921   315   904 D CommandListener: Setting iface cfg
09-08 13:34:21.921   315   904 D CommandListener: Trying to bring up p2p0
09-08 13:34:21.921  1031  1533 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-08 13:34:21.921  1031  1532 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 13:34:21.922  1031  1532 D LGWifiP2pService: P2pEnablingState
09-08 13:34:21.922  1031  1532 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.922  1031  1532 D LGWifiP2pService: P2p socket connection successful
09-08 13:34:21.922  1031  1532 D LGWifiP2pService: P2pEnabledState
09-08 13:34:21.922  1031  1533 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-08 13:34:21.922  1031  1532 D LGWifiP2pService: sending p2p connection changed broadcast
09-08 13:34:21.922  1031  1533 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-08 13:34:21.922  1031  1533 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 13:34:21.922  1031  1532 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-08 13:34:21.922  7010  7010 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 13:34:21.924  1031  1533 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-08 13:34:21.924  1031  1533 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-08 13:34:21.925  1031  1533 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-08 13:34:21.925  1031  1533 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 13:34:21.925  7010  7010 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 13:34:21.926  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-08 13:34:21.926  1031  1533 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 13:34:21.926  1935  1935 D WfdsService: WifiP2pState is changed : true
09-08 13:34:21.926  1935  2281 D WfdsService: Receive the WFDS_ENABLE Method
09-08 13:34:21.926  1935  2281 D WfdsService: Set the WFDS Monitor: true
09-08 13:34:21.926  1935  1935 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 13:34:21.926  1935  2281 D WfdsService: Connected to the supplicant for wfds
09-08 13:34:21.926  1935  2281 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 13:34:21.926  7010  7010 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 13:34:21.926  1935  2281 D WfdsService: selectPreferredScanChannel [36]
09-08 13:34:21.926  1935  2281 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-08 13:34:21.926  1935  1935 D WfdsService: isConnected: false
,09-08 13:34:21.927  1031  1533 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 13:34:21.928  1031  1533 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-08 13:34:21.928  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,09-08 13:34:21.930  1031  1532 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-08 13:34:21.931  1031  1532 D WifiNative-p2p0: doBoolean: SET device_name G3
09-08 13:34:21.931  1031  1532 D WifiNative-p2p0: SET device_name G3: returned true
09-08 13:34:21.931  1031  1532 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-08 13:34:21.931  1031  1532 D LGWifiP2pService: before postfix = G3
09-08 13:34:21.931  1031  1532 D WifiServerServiceExt: postfix byte check : 2
09-08 13:34:21.931  1031  1532 D LGWifiP2pService: after postfix = G3
09-08 13:34:21.931  1031  1532 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-08 13:34:21.932  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 13:34:21.933  7010  7010 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:21.933  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 13:34:21.933  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:21.933  1031  7044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:21.933  1031  7044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:21.933  7010  7010 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 13:34:21.933  7010  7010 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.934  1031  7044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:21.934  1031  1533 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-08 13:34:21.934  1031  7044 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.934  1031  7044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.934  1031  7044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.934  1935  7065 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:21.934  1031  1533 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-08 13:34:21.934  7010  7010 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.935  1031  1533 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-08 13:34:21.935  1031  1533 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-08 13:34:21.935  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-08 13:34:21.935  1031  1532 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-08 13:34:21.935  1031  1532 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-08 13:34:21.936  1935  7065 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:21.936  1031  1532 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-08 13:34:21.936  1031  7044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:21.936  1031  1532 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-08 13:34:21.936  1031  7044 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.936  1031  7044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.936  1031  7044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.936  1031  1532 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-08 13:34:21.936  1031  1532 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-08 13:34:21.937  1031  1532 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,09-08 13:34:21.937  1031  1532 D WifiNative-HAL: p2pGetDeviceAddress
09-08 13:34:21.937  1031  1532 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-08 13:34:21.938  1031  1532 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-08 13:34:21.938  1031  1532 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-08 13:34:21.938  1031  1532 D WifiNative-p2p0: P2P_FLUSH: returned true
09-08 13:34:21.938  1031  1532 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-08 13:34:21.939  1031  1532 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-08 13:34:21.939  1031  1532 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,09-08 13:34:21.939  1031  1532 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-08 13:34:21.939  1031  1532 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-08 13:34:21.940  1935  1935 I WfdStateTracker: handleP2pThisDeviceChanged
09-08 13:34:21.940  1935  1935 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 13:34:21.940  1935  1935 D WfdsService: Update P2p Interface State: 3
,09-08 13:34:21.964  1031  1532 D WifiNative-p2p0: SAVE_CONFIG: returned true,
09-08 13:34:21.964  1031  1532 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-08 13:34:21.964  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-08 13:34:21.964  7010  7010 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 13:34:21.964  1031  1532 D LGWifiP2pService: InactiveState
,09-08 13:34:21.964  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-08 13:34:21.964  1031  1532 D LGWifiP2pService: InactiveState{ when=-30ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.965  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 13:34:21.965  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-31ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.965  1031  1532 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-08 13:34:21.965  1031  7044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 13:34:21.965  1031  7044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 13:34:21.965  1031  1533 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-08 13:34:21.965  1031  1533 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-08 13:34:21.965  1031  1533 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-08 13:34:21.965  1031  1533 D WifiNative-wlan0: doBoolean: SCAN
09-08 13:34:21.966  1031  1533 D WifiNative-wlan0: SCAN: returned false
09-08 13:34:21.966  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=126994  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 13:34:21.967  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 13:34:21.967  7010  7010 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:21.968  1935  7065 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 13:34:21.968  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:21.968  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:21.968  1031  7044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 13:34:21.968  1031  7044 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:21.968  7010  7010 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 13:34:21.968  1031  7044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:21.968  1031  7044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:21.968  7010  7010 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.968  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=126996  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 13:34:21.968  1031  1533 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:21.968  1935  7065 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:21.969  1031  7044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:21.969  1031  7044 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.969  7010  7010 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.969  1031  7044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.969  1031  1532 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-08 13:34:21.969  1031  7044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.969  1031  1533 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:21.969  1031  1532 D LGWifiP2pService: InactiveState{ when=-30ms what=143376 ,obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.969  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-30ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.969  1031  1532 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.969  1031  1533 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:21.969  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.969  1031  1532 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.969  1031  1532 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.969  1031  7044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:21.969  1031  1533 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:21.969  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.969  1031  7044 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.969  1031  1532 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.969  1031  7044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.970  1935  7065 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:21.970  1031  1533 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:21.970  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.970  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.970  1031  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.970  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.970  1031  7044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:21.970  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 13:34:21.970  1031  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:21.970  1031  1031 E WifiServerServiceExt: No p2p device connected
09-08 13:34:21.970  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:21.971  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:21.971  1935  2281 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 13:34:21.971  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 13:34:21.972  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:21.973  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:21.973  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 13:34:22.099  1031  1046 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7067 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-08 13:34:22.099  1031  1046 I ActivityManager: Killing 2160:com.lge.music/u0a34 (adj 15): empty #17
,09-08 13:34:22.118   319   319 V AudioFlinger: 2160 died, releasing its sessions
09-08 13:34:22.118   319   319 V AudioFlinger:  pid 1846 @ 0
09-08 13:34:22.118   319   319 V AudioFlinger:  pid 3323 @ 1
09-08 13:34:22.118   319   319 V AudioFlinger:  pid 3323 @ 2
09-08 13:34:22.150  1031  1934 W libprocessgroup: failed to open /acct/uid_10034/pid_2160/cgroup.procs: No such file or directory
,09-08 13:34:22.264  1031  1933 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7085 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 13:34:22.266  1031  1933 I ActivityManager: Killing 6549:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-08 13:34:22.341  1031  1934 W libprocessgroup: failed to open /acct/uid_10061/pid_6549/cgroup.procs: No such file or directory
,09-08 13:34:22.387  7085  7085 I art     : Almond Protected OAT
,09-08 13:34:22.404  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-08 13:34:22.404  1031  7044 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-08 13:34:22.404  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-08 13:34:22.404  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: WPS-AP-AVAILABLE 
09-08 13:34:22.404  1031  7044 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-08 13:34:22.405  7010  7010 E wpa_supplicant: USIM:  scard_init function
,09-08 13:34:22.405  1031  1533 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-08 13:34:22.405  1031  1533 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-08 13:34:22.406  7010  7010 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-08 13:34:22.406  1031  1533 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-08 13:34:22.406  1031  1533 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-08 13:34:22.406  1031  1533 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-08 13:34:22.407  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-08 13:34:22.407  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-08 13:34:22.421  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=127449  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 13:34:22.423  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=127450  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 13:34:22.425  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.425  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 13:34:22.426  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 13:34:22.426  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.426  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 13:34:22.429  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.429  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.430  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 13:34:22.430  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:22.430  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 13:34:22.430  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.433  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.433  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:22.434  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.475  7085  7085 D WeatherApplication: removeAccount
09-08 13:34:22.477  7085  7085 D WeatherApplication: Account.length = 0
,09-08 13:34:22.477  7085  7085 E WeatherApplication: OPERATOR:OPEN
,09-08 13:34:22.482  7085  7085 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:22
09-08 13:34:22.485  7085  7085 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 13:34:22.485  7085  7085 D Weather.Utils: 2 : All the weather widget is gone.
09-08 13:34:22.487  7085  7085 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-08 13:34:22.490  7085  7085 D WeatherAncestor: connectivity changed - connection : true
09-08 13:34:22.491  7085  7085 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-08 13:34:22.499  7085  7085 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-08 13:34:22.499  7085  7085 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 13:34:22.499  7085  7085 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-08 13:34:22.521  7085  7085 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 13:34:22.521  7085  7085 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:22
,09-08 13:34:22.522  7010  7010 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-08 13:34:22.523  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-08 13:34:22.523  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-08 13:34:22.523  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-08 13:34:22.524  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-08 13:34:22.524  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:22.524  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:22.524  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=127551  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 13:34:22.524  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=127552  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-08 13:34:22.525  1031  1533 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=127553
09-08 13:34:22.525  1031  1533 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=127553
09-08 13:34:22.526  1031  1533 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=127554
09-08 13:34:22.528  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=127555
09-08 13:34:22.529  1031  1533 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 32 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=127556
09-08 13:34:22.530  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=127557  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 13:34:22.530  7010  7010 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 13:34:22.530  7010  7010 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 13:34:22.530  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:22.530  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:22.532  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-08 13:34:22.532  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 13:34:22.532  1031  7044 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 13:34:22.532  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-08 13:34:22.532  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 13:34:22.532  1031  7044 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 13:34:22.533  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:22.533  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-08 13:34:22.579  1031  1047 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7106 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:22.582  1031  1047 I ActivityManager: Killing 6213:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-08 13:34:22.613  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=127641  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-08 13:34:22.614  1031  1897 W libprocessgroup: failed to open /acct/uid_10080/pid_6213/cgroup.procs: No such file or directory
09-08 13:34:22.614  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=127642  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 13:34:22.616  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=127644  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 13:34:22.617  1031  1533 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=127644
09-08 13:34:22.617  1031  1533 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=127645
09-08 13:34:22.618  1031  1533 D WifiNative-wlan0: doString: [STATUS]
09-08 13:34:22.618  1031  1533 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-08 13:34:22.620  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:22.620  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:22.621  1031  1533 I WifiServiceExtension: setVHTCapabilityType  : false
09-08 13:34:22.621  1031  1113 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 13:34:22.624  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.624  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.624  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 13:34:22.625  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.625  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:22.626  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.628  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.628  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.628  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 13:34:22.628  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:22.628  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-08 13:34:22.631  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.632  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:22.633  1031  1533 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 13:34:22.633  1031  1533 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-08 13:34:22.634  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.642  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.642  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.642  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-08 13:34:22.646  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.646  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.646  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 13:34:22.650  1031  1533 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 13:34:22.650  1031  1539 D ConnectivityService: Got NetworkAgent Messenger
09-08 13:34:22.650  1031  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 13:34:22.650  1031  1539 D ConnectivityService: NetworkAgent connected
09-08 13:34:22.651  1031  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 13:34:22.651  1031  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 13:34:22.651  1031  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 13:34:22.651  1031  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 13:34:22.652  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.652  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:22.653  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.656  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.656  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 13:34:22.659  1031  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 13:34:22.659  1031  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 13:34:22.659  1031  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 13:34:22.659  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.659  1031  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 13:34:22.659  1031  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 13:34:22.662  1031  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 13:34:22.665   315   904 D CommandListener: Setting iface cfg
09-08 13:34:22.667  1031  7124 D DhcpStateMachine: StoppedState
09-08 13:34:22.667  1031  1533 E WifiStateMachine: Start Dhcp Watchdog 2
09-08 13:34:22.668  1031  7124 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.668  1031  7124 D DhcpStateMachine: WaitBeforeStartState
09-08 13:34:22.668  1031  1533 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=127696  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:22.669  1031  1533 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=127696  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:22.669  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=127697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:22.670  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:22.670  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-08 13:34:22.671  1031  1533 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=127699  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:22.672  1031  1533 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=127699  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:22.672  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:22.672  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=127700  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:22.672  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 13:34:22.673  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:22.674  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:22.674  1031  1533 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:22.674  1031  1533 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:22.675  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:22.675  1031  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:22.676  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:81629] from screen [on:0 period:160680148] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-08 13:34:22.677  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:160680149] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-08 13:34:22.677  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 13:34:22.682  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 13:34:22.685  1031  1539 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-08 13:34:22.685  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.686  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.686  1031  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.687  1031  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.687  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.688  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.688  1031  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 13:34:22.689  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=165,0,0
09-08 13:34:22.690  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=165,0,0
09-08 13:34:22.690  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-08 13:34:22.690  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-08 13:34:22.691  1031  1533 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-08 13:34:22.691  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 0
09-08 13:34:22.691  1031  1533 D WifiNative-wlan0: SET ps 0: returned true
09-08 13:34:22.691  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-08 13:34:22.692  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-08 13:34:22.692  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-08 13:34:22.692  1031  1533 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 13:34:22.692  1031  1533 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 13:34:22.692  1031  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26c2abcd target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.692  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26c2abcd target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.692  1031  7124 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.692  1031  7124 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 13:34:22.693  1031  1533 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-08 13:34:22.694   315   904 D CommandListener: Setting iface cfg
09-08 13:34:22.694   315   904 D CommandListener: Trying to bring up wlan0
09-08 13:34:22.696  1031  1533 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 13:34:22.697  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:22.697  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 13:34:22.697  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.698  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.698  1031  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.699  1031  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.699  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.699  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:22.699  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 13:34:22.700  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:22.700  1031  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 13:34:22.701  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 13:34:22.701  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 13:34:22.701  1031  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.701  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.701  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 13:34:22.702  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 13:34:22.702  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 13:34:22.702  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-08 13:34:22.702  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-08 13:34:22.703  1031  1533 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-08 13:34:22.703  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 13:34:22.718  1031  1533 D WifiNative-wlan0: SET ps 1: returned true
09-08 13:34:22.719  1031  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 13:34:22.719  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 13:34:22.719  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 13:34:22.720  1031  1533 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 13:34:22.720  1031  1539 D ConnectivityService: ignoring duplicate network state non-change
,09-08 13:34:22.723  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.723  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:22.727  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.730  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.731  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.731  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 13:34:22.731  1031  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 13:34:22.732  1031  1539 D ConnectivityService: Adding iface wlan0 to network 101
09-08 13:34:22.733  1031  1533 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 13:34:22.743  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.744  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 13:34:22.744  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 13:34:22.746  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 13:34:22.749  1935  1935 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-08 13:34:22.754  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.755  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.755  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 13:34:22.756  1031  1539 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 13:34:22.756  1031  1539 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 13:34:22.757  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 13:34:22.759  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.759  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:22.760  1031  1539 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-08 13:34:22.761   315   904 E Netd    : netlink response contains error (File exists)
09-08 13:34:22.761  1031  1539 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-08 13:34:22.761  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.762  1031  1539 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-08 13:34:22.762  1031  1539 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-08 13:34:22.762  1031  1539 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-08 13:34:22.764  1031  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 13:34:22.764  1031  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 13:34:22.764  1031  1539 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-08 13:34:22.764  1031  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 13:34:22.764  1031  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:22.764  1031  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:22.764  1031  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 13:34:22.764  1031  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.764  1031  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-08 13:34:22.764  1031  1539 D ConnectivityService: currentScore = 0, newScore = 20
09-08 13:34:22.764  1031  1539 D ConnectivityService:    accepting network in place of null
09-08 13:34:22.764  1031  1539 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.765  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.765  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:22.765  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 13:34:22.765  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.765  1031  1533 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.765  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 13:34:22.765  1031  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:22.765  1031  7123 D NetworkMonitor Networ,kAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.765  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 13:34:22.766  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.767  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 13:34:22.767  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.767  1846  1846 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.768  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 13:34:22.768   315  7134 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,09-08 13:34:22.770  1031  1539 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 13:34:22.770  1031  1539 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 13:34:22.771  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 13:34:22.771  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:22.772  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 13:34:22.772  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.777  1031  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:22.777  1031  1539 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 13:34:22.778  1031  1539 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 13:34:22.781  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-08 13:34:22.781  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 13:34:22.781  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 13:34:22.781  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-08 13:34:22.783  1031  1539 D ConnectivityService: validation of new default Network = false
09-08 13:34:22.783  1031  1539 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 13:34:22.783  1031  1539 D DSQN    : enableDataServiceNotify 
09-08 13:34:22.783  1031  1539 D DSQN    : start dsqn bin
09-08 13:34:22.788   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:22.788   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 13:34:22.788   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 13:34:22.790  7106  7136 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 13:34:22.791  1031  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 13:34:22.791  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.791  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:22.791  1031  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:22.781  7138  7138 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:22.781  7138  7138 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:22.793  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 13:34:22.795   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:22.795   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 13:34:22.795   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 13:34:22.799  1031  1531 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-08 13:34:22.803  7138  7138 E DSQN    : DSQN ssw
09-08 13:34:22.803  7106  7136 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 13:34:22.816   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:22.816   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 13:34:22.816   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 13:34:22.817   315  7134 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 13:34:22.818  7106  7144 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 13:34:22.821   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:22.821   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 13:34:22.821   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 13:34:22.822  7106  7144 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 13:34:22.822  1811  7145 I CheckinService: active receiver: enabled
,09-08 13:34:22.831  1811  7145 I CheckinService: Preparing to send checkin request
09-08 13:34:22.831  1811  7145 I EventLogService: Accumulating logs since 1473334392156
09-08 13:34:22.835  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 13:34:22.836  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.837  1811  7145 W EventLogAggregator: Unknown tag: snet_gcore
09-08 13:34:22.837  1811  7145 W EventLogAggregator: Unknown tag: snet_launch_service
09-08 13:34:22.837  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.849   315  7134 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-08 13:34:22.860  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.860  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.860  1031  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:22.879   315   903 D LGDataListener: argv[0]=dsqncommand
09-08 13:34:22.879   315   903 D LGDataListener: argv[1]=wlan0
09-08 13:34:22.879   315   903 D LGDataListener: argv[2]=1
09-08 13:34:22.879   315   903 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 13:34:22.879  1031  1111 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 13:34:22.879  1031  1111 D DSQN    : start to monitor internet connection
09-08 13:34:22.883  1811  7145 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-08 13:34:22.894  1031  7124 D DhcpStateMachine: DHCPV4 request on wlan0
09-08 13:34:22.895  1031  7124 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-08 13:34:22.895  1031  7124 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-08 13:34:22.881  7151  7151 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:22.881  7151  7151 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-08 13:34:22.908  7151  7151 I dhcpcd  : version 5.5.6 starting
09-08 13:34:22.908  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 11:34:22 GMT], X-Android-Received-Millis=[1473334462908], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473334462879]}
09-08 13:34:22.908  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 13:34:22.908  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 13:34:22.909  1031  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-08 13:34:22.909  1031  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 13:34:22.909  1031  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:22.909  1031  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:22.909  1031  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 13:34:22.909  1031  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-08 13:34:22.909  1031  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 13:34:22.909  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.909  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:22.910  7151  7151 E dhcpcd  : get_duid: m
09-08 13:34:22.910  7151  7151 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-08 13:34:22.910  7151  7151 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-08 13:34:22.910  1031  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:22.910  1031  1539 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.911  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 13:34:22.911  1031  1533 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.911  1031  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:22.912  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 13:34:22.912  1846  1846 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:22.913  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 13:34:22.923  1031  1533 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 13:34:22.924  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 13:34:22.924  1031  1533 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 13:34:22.924  1031  1533 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 13:34:22.925  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-08 13:34:22.925  1031  1533 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-08 13:34:22.935  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 13:34:22.936  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:22.937  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 13:34:22.971  7151  7151 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 13:34:22.971  7151  7151 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 13:34:22.971  7151  7151 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 13:34:22.971  7151  7151 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-08 13:34:22.972  7151  7151 D dhcpcd  : wlan0: sending REQUEST (xid 0x376bf64d), next in 3.54 seconds
,09-08 13:34:23.001  1031  1046 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7170 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-08 13:34:23.009  7106  7106 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-08 13:34:23.010  7151  7151 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-08 13:34:23.016  7106  7106 I LibraryLoader: Loading: webviewchromium
,09-08 13:34:23.018  7106  7106 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8055-8058)
09-08 13:34:23.018  7106  7106 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 13:34:23.022  7106  7106 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ce6e222}
09-08 13:34:23.023  7106  7106 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 13:34:23.024  7106  7106 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 13:34:23.030  7151  7151 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-08 13:34:23.030  7151  7151 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-08 13:34:23.030  7151  7151 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-08 13:34:23.030  7151  7151 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,09-08 13:34:23.030  7151  7151 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 13:34:23.030  7151  7151 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 13:34:23.030  7151  7151 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 13:34:23.030  7151  7151 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-08 13:34:23.036  7106  7106 I BrowserStartupController: Initializing chromium process, renderers=0
09-08 13:34:23.036  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 13:34:23.037  7170  7170 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 13:34:23.037  7170  7170 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-08 13:34:23.046   319  1381 V AudioPolicyService: registerClient() client 0xb558ab00, uid 10093
,09-08 13:34:23.047  7106  7193 W AudioManagerAndroid: Requires BLUETOOTH permission
09-08 13:34:23.049  7106  7106 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-08 13:34:23.050  7106  7106 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-08 13:34:23.050  7106  7106 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-08 13:34:23.055  7170  7170 I MultiDex: VM with version 2.1.0 has multidex support
09-08 13:34:23.055  7170  7170 I MultiDex: install
09-08 13:34:23.055  7170  7170 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-08 13:34:23.062  7170  7170 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-08 13:34:23.071  7106  7106 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 13:34:23.071  7106  7106 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 13:34:23.071  7106  7106 I Adreno-EGL: Build Date: 12/12/14 금
09-08 13:34:23.071  7106  7106 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 13:34:23.071  7106  7106 I Adreno-EGL: Remote Branch: 
09-08 13:34:23.071  7106  7106 I Adreno-EGL: Local Patches: 
09-08 13:34:23.071  7106  7106 I Adreno-EGL: Reconstruct Branch: 
,09-08 13:34:23.117  7106  7106 I NSApplication: Starting up...
,09-08 13:34:23.141  1031  1934 I ActivityManager: Killing 6666:com.lge.eula/1000 (adj 15): empty #17
,09-08 13:34:23.225  1031  1971 W libprocessgroup: failed to open /acct/uid_1000/pid_6666/cgroup.procs: No such file or directory
,09-08 13:34:23.231  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-08 13:34:23.232  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
09-08 13:34:23.233  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
09-08 13:34:23.233  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-08 13:34:23.233  1935  2093 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-08 13:34:23.233  1935  2093 D LEDHandler: Battery Level Remaining: 100%
09-08 13:34:23.233  1935  2093 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
09-08 13:34:23.234  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-08 13:34:23.234  1031  1538 D WifiController: battery changed pluggedType: 2
09-08 13:34:23.235  3818  3932 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-08 13:34:23.236  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:23.236  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:23.236  6685  6685 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-08 13:34:23.244  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-08 13:34:23.249  6400  6439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 13:34:23.260  2177  2177 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:23.264  1031  1934 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-08 13:34:23.265  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:23.265  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:23.265  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-08 13:34:23.265  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:23.265  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 13:34:23.266   315  7230 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 13:34:23.267   315  7230 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-08 13:34:23.270  6971  6971 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 13:34:23.270  6971  6971 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:23.270  6971  6971 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 13:34:23.270  6971  6971 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 13:34:23.272  6971  6971 I AppUp4:CustModeStarterReceiver: onReceive
09-08 13:34:23.274  6971  6971 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f3d274b
09-08 13:34:23.274  6971  6971 D AppUp4:CustFacade: isCustomizationCompleted : false
,09-08 13:34:23.274  6971  6971 D AppUp4:CustFacade: isPhone : true
09-08 13:34:23.275  6971  6971 D AppUp4:CustModeStarterReceiver: begin check event
09-08 13:34:23.275  6971  6971 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-08 13:34:23.280  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:23.281  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:23.282  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:23.284  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:23.287  3431  3431 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:23.288  4291  7231 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 13:34:23.289  3431  3431 V DownloadManager: DownloadService onCreate
09-08 13:34:23.291  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 11:34:23 GMT], X-Android-Received-Millis=[1473334463290], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473334463266]}
09-08 13:34:23.291  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 13:34:23.291  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 13:34:23.291  4291  7231 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 13:34:23.291  1031  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-08 13:34:23.291  1031  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 13:34:23.291  1031  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:23.291  1031  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:23.291  1031  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 13:34:23.291  1031  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-08 13:34:23.292  6509  6509 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-08 13:34:23.292  1031  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 13:34:23.292  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:23.292  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:23.292  1031  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:23.293  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 13:34:23.297  3431  3431 V DownloadManager: DownloadService onStartCommand
09-08 13:34:23.297  3431  7234 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 13:34:23.298  1031  7124 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-08 13:34:23.299  4291  7231 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 13:34:23.299  1031  7124 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-08 13:34:23.299  1031  7124 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 13:34:23.300  1031  7124 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-08 13:34:23.300  1031  7124 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-08 13:34:23.300  1031  7124 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 13:34:23.300  1031  7124 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-08 13:34:23.300  1031  7124 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 13:34:23.300  1031  7124 D DhcpStateMachine: RunningState
09-08 13:34:23.300  3431  7233 I DownloadManager: i,n removeSpuriousFiles
09-08 13:34:23.301  3431  7233 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-08 13:34:23.301   315  7230 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-08 13:34:23.305  3431  7233 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2936a5cc on behalf of 3431
09-08 13:34:23.305  4291  7232 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:23.306  4291  7232 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 13:34:23.307  3431  7234 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a90f015 on behalf of 3431
09-08 13:34:23.309  4291  4291 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 13:34:23.310  4291  4291 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 13:34:23.311  4291  4291 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 13:34:23.312  4291  4291 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-08 13:34:23.316  6509  7236 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:23.316  4291  4291 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 13:34:23.319  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-08 13:34:23.319  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-08 13:34:23.319  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-08 13:34:23.319  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-08 13:34:23.319  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-08 13:34:23.319  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-08 13:34:23.319  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-08 13:34:23.320  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-08 13:34:23.320  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-08 13:34:23.320  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-08 13:34:23.320  3431  7233 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-08 13:34:23.320  3431  7233 I DownloadManager: in trimDatabase
09-08 13:34:23.321  3431  7233 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 13:34:23.322  3431  7233 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1e1acf2a on behalf of 3431
09-08 13:34:23.324  3431  7234 V DownloadManager: processing inserted download 1
09-08 13:34:23.325  3323  3323 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 13:34:23.325  3323  3323 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:23.325  3323  3323 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 13:34:23.327  7026  7026 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 13:34:23.327  7026  7026 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-08 13:34:23.331  3431  7234 V DownloadManager: processing inserted download 4
09-08 13:34:23.332  3431  7234 V DownloadManager: processing inserted download 7
09-08 13:34:23.334  7085  7085 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:23
09-08 13:34:23.335  7085  7085 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 13:34:23.335  7085  7085 D Weather.Utils: 2 : All the weather widget is gone.
09-08 13:34:23.335  3431  7234 V DownloadManager: processing inserted download 8
09-08 13:34:23.336  7085  7085 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 13:34:23.336  3431  7234 V DownloadManager: processing inserted download 9
09-08 13:34:23.336  7085  7085 D WeatherAncestor: connectivity changed - connection : true
09-08 13:34:23.336  7085  7085 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@310a5241
09-08 13:34:23.337  3431  7234 V DownloadManager: processing inserted download 10
09-08 13:34:23.337  7085  7085 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 13:34:23.337  7085  7085 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 13:34:23.337  7085  7085 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 13:34:23.337  7085  7085 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-08 13:34:23.337  7085  7085 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:23
09-08 13:34:23.337  3431  7234 V DownloadManager: processing inserted download 11
09-08 13:34:23.338  3431  7234 V DownloadManager: processing inserted download 12
09-08 13:34:23.339  3431  7234 V DownloadManager: processing inserted download 13
09-08 13:34:23.340  3431  7234 V DownloadManager: processing inserted download 14
09-08 13:34:23.341  3431  7234 V DownloadManager: processing inserted download 16
09-08 13:34:23.346  3431  3431 V DownloadManager: DownloadService onDestroy
09-08 13:34:23.357  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 13:34:23.357  6851  6851 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 13:34:23.357  6851  6851 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 13:34:23.357  6851  6851 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-08 13:34:23.359  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 13:34:23.360  6851  6851 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 13:34:23.360  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 13:34:23.360  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 13:34:23.360  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 13:34:23.360  6851  6851 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 13:34:23.360  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 13:34:23.361  6851  6851 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 13:34:23.364  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:23.366  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 13:34:23.366   315  7242 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 13:34:23.366   315  7242 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-08 13:34:23.374  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 13:34:23.385  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:23.386  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 13:34:23.389  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.397  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 13:34:23.398  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:23.399  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 13:34:23.403  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:23.407  4291  7243 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 13:34:23.408   315  7242 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-08 13:34:23.408  4291  7243 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 13:34:23.408  6685  6685 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 13:34:23.409  6685  6685 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 13:34:23.412  4291  7243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-08 13:34:23.414  4291  4291 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 13:34:23.415  4291  4291 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 13:34:23.416  4291  4291 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 13:34:23.417  4291  7244 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 13:34:23.417  4291  7244 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 13:34:23.418  4291  4291 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 13:34:23.421  6685  6685 V [BNRBootReceiver]: Boot Receiver Return
09-08 13:34:23.422  4291  4291 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 13:34:23.424  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 13:34:23.432  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.438  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.446  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 13:34:23.447  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.448  6892  7240 V FormManager: There are no updated forms. The schedule will be deleted.
09-08 13:34:23.448  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 13:34:23.450  6892  7240 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 13:34:23.451  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-08 13:34:23.454  6851  6851 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 13:34:23.455  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:23.458  7248  7248 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-08 13:34:23.464  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.471  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.477  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.478  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 13:34:23.480  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 13:34:23.484  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:23.489  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.499  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.505  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.505  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.505  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 13:34:23.506  7248  7248 I dex2oat : dex2oat took 47.850ms (threads: 4)
09-08 13:34:23.508  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:23.513  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.517  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.521  7170  7185 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 13:34:23.521  7170  7185 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 13:34:23.521  7170  7185 I Adreno-EGL: Build Date: 12/12/14 금
09-08 13:34:23.521  7170  7185 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 13:34:23.521  7170  7185 I Adreno-EGL: Remote Branch: 
09-08 13:34:23.521  7170  7185 I Adreno-EGL: Local Patches: 
09-08 13:34:23.521  7170  7185 I Adreno-EGL: Reconstruct Branch: 
09-08 13:34:23.522  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.522  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.522  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 13:34:23.523  6892  7251 V FormManager: There are no updated forms. The schedule will be deleted.
,09-08 13:34:23.524  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:23.528  6892  7251 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 13:34:23.529  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 13:34:23.532  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.537  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.537  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.537  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 13:34:23.541  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:23.546  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.554  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.560  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.560  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.560  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 13:34:23.564  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 13:34:23.571  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.574  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.583  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.583  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.583  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 13:34:23.587  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:23.597  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.597  6892  7256 V FormManager: There are no updated forms. The schedule will be deleted.
,09-08 13:34:23.599  6892  7256 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 13:34:23.603  7170  7185 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 13:34:23.603  7170  7185 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 13:34:23.603  7170  7185 I Adreno-EGL: Build Date: 12/12/14 금
09-08 13:34:23.603  7170  7185 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 13:34:23.603  7170  7185 I Adreno-EGL: Remote Branch: 
09-08 13:34:23.603  7170  7185 I Adreno-EGL: Local Patches: 
09-08 13:34:23.603  7170  7185 I Adreno-EGL: Reconstruct Branch: 
09-08 13:34:23.605  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.611  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.612  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.614  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 13:34:23.617  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:23.623  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.628  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 13:34:23.633  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.633  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.634  6869  6869 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 13:34:23.636  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 13:34:23.640  6831  6831 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 13:34:23.641  7170  7185 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 13:34:23.641  7170  7185 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 13:34:23.641  7170  7185 I Adreno-EGL: Build Date: 12/12/14 금
09-08 13:34:23.641  7170  7185 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 13:34:23.641  7170  7185 I Adreno-EGL: Remote Branch: 
09-08 13:34:23.641  7170  7185 I Adreno-EGL: Local Patches: 
09-08 13:34:23.641  7170  7185 I Adreno-EGL: Reconstruct Branch: 
09-08 13:34:23.643  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:23.646  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:23.650  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.656  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.656  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:23.657  6869  6869 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 13:34:23.658  6869  6869 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 13:34:23.658  6869  6869 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 13:34:23.661  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 13:34:23.664  6831  6831 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 13:34:23.665  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:23.667  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 13:34:23.672  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:23.679  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:23.679  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 13:34:23.680  6869  6869 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 13:34:23.681  6869  6869 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 13:34:23.682  6869  6869 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 13:34:23.686  2177  2177 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-08 13:34:23.697  2177  2177 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-08 13:34:23.697  2177  2177 D c       : Getting all permits...
09-08 13:34:23.697  2177  2177 D a       : Opening database...
09-08 13:34:23.700  2177  2177 D a       : Opening database auth.proximity.permit_store...
,09-08 13:34:23.701  2177  2177 D a       : Closing database...
09-08 13:34:23.756  7170  7185 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:23.756  7170  7185 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:23.793  1031  1539 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 13:34:23.822  6595  6704 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 13:34:23.924  1031  1533 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:23.927  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:23.928  1031  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:23.929  1031  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:23.930  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:23.931  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:23.933  1031  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-08 13:34:23.933  1031  1539 D ConnectivityService: identical MTU - not setting
,09-08 13:34:23.933  1031  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,09-08 13:34:23.933  1031  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 13:34:23.933  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:23.934  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:23.934  1031  1539 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:23.935  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-08 13:34:24.069   315  7265 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-08 13:34:24.072   315  7265 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-08 13:34:24.120   315  7265 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-08 13:34:24.279  1811  7145 I CheckinTask: Sending checkin request (7963 bytes)
,09-08 13:34:24.494  1811  7145 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-08 13:34:24.510  1811  7145 I CheckinService: active receiver: disabled
,09-08 13:34:24.533  2177  2177 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-08 13:34:24.551  2177  2177 I GCM     : GCM config loaded
,09-08 13:34:24.690  6710  6944 D UEI.SmartControl: Internal timer expired: 2
09-08 13:34:24.690  6710  6944 D UEI.SmartControl: unbind internal service
,09-08 13:34:24.767  1031  1898 I art     : Explicit concurrent mark sweep GC freed 122446(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.740ms total 196.296ms
,09-08 13:34:24.773  7026  7026 V SetupWizard: Connected to Gservices successfully
09-08 13:34:24.842  1031  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-08 13:34:24.843  1031  1952 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3e02831d mBinding = false
09-08 13:34:24.860  1031  1113 D BluetoothManagerService: Message: 2
,09-08 13:34:24.862  1031  1113 D BluetoothManagerService: Sending off request.
,09-08 13:34:24.863  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 13:34:24.864  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 13:34:24.864  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-08 13:34:24.864  3818  3835 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-08 13:34:24.866  6710  6938 D serial_port: close(fd = 24)
09-08 13:34:24.866  3818  3902 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-08 13:34:24.866  3818  3902 D BluetoothAdapterProperties: Setting state to 13
,09-08 13:34:24.866  3818  3902 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 13:34:24.867  1031  1113 D BluetoothManagerService: Message: 60
09-08 13:34:24.867  1031  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-08 13:34:24.867  1031  1113 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-08 13:34:24.867  3818  3902 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 13:34:24.868  3818  3902 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-08 13:34:24.871  2177  7291 D GCM     : Connected
09-08 13:34:24.874  3818  3910 D BluetoothAdapterProperties: Scan Mode:20
09-08 13:34:24.875  3818  3902 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-08 13:34:24.876  6710  6938 I UEI.SmartControl: Serial port is closed.
09-08 13:34:24.877  3818  3902 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 13:34:24.877  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-08 13:34:24.877  3818  3984 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,09-08 13:34:24.879  3818  4172 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 13:34:24.881  3818  4141 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 13:34:24.881  3818  4157 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 13:34:24.882  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:24.882  3818  4137 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-08 13:34:24.882  3818  4137 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 13:34:24.882  3818  4137 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-08 13:34:24.882  3818  4137 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-08 13:34:24.882  3818  4137 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-08 13:34:24.882  3818  4137 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-08 13:34:24.882  3818  4137 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-08 13:34:24.882  3818  4137 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-08 13:34:24.882  3818  4159 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-08 13:34:24.885  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-08 13:34:24.885  3818  3984 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 13:34:24.886  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 13:34:24.887  3818  3818 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:24.888  3818  3818 D BluetoothMapService: STATE_TURNING_OFF
09-08 13:34:24.888  3818  3818 V BluetoothMapService: Handler(): got msg=4
09-08 13:34:24.888  3818  3818 D BluetoothMapService: MAP Service closeService in
09-08 13:34:24.888  3818  3818 D BluetoothMapMasInstance: MAP Service shutdown
09-08 13:34:24.889  3818  3818 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 13:34:24.889  3818  3818 V BluetoothMapService: MAP Service closeService out
,09-08 13:34:24.894  3818  3818 V BtOppService: Receiver DISABLED_ACTION 
09-08 13:34:24.894  3818  3818 I BtOppRfcommListener: stopping Accept Thread
09-08 13:34:24.894  3818  3818 V BtOppRfcommListener: close mBtServerSocket
09-08 13:34:24.895  3818  3818 V BtOppRfcommListener: waiting for thread to terminate
09-08 13:34:24.895  3818  4157 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 13:34:24.895  3818  3818 V BtOppRfcommListener: done waiting for thread to terminate
09-08 13:34:24.897  6595  6595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:24.897  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:24.897  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:24.897  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:24.897  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:24.897  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:24.897  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:24.897  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:24.897  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
09-08 13:34:24.898  3818  3818 V BtOppService: onDestroy
09-08 13:34:24.900  3818  3818 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-08 13:34:24.901  6595  6595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:24.901  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:24.903  6595  6595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:24.903  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:24.903  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:24.903  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:24.903  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:24.903  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:24.903  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:24.903  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:24.903  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:24.909  6595  6595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:24.909  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:24.914  2177  7291 D GCM     : Message class com.google.e.a.a.q
09-08 13:34:24.916  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:24.916  6851  6851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 13:34:24.921  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:24.943  1031  1109 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7298 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-08 13:34:24.947  3818  3818 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 13:34:24.947  3818  3818 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:24.947  3818  3818 V BluetoothPbapReceiver: ***********state = 13
09-08 13:34:24.948  3818  3818 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-08 13:34:24.949  3818  3818 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:24.949  3818  3818 V BluetoothPbapService: state: 13
09-08 13:34:24.949  3818  3818 V BluetoothPbapService: Pbap Service closeService in
09-08 13:34:24.951  3818  3818 V BluetoothPbapService: successfully stopped pbap service
09-08 13:34:24.951  3818  3818 V BluetoothPbapService: Pbap Service closeService out
09-08 13:34:24.951  3818  3818 V BluetoothPbapService: Pbap Service onDestroy
09-08 13:34:24.951  3818  3818 V BluetoothPbapService: Pbap Service closeService in
09-08 13:34:24.952  3818  3818 V BluetoothPbapService: Pbap Service closeService out
09-08 13:34:24.952  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 13:34:24.952  3818  3818 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-08 13:34:24.952  1031  1113 D BluetoothManagerService: Message: 20
09-08 13:34:24.952  1031  1113 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c3d2760:true
09-08 13:34:24.963  1031  1113 D BluetoothManagerService: Message: 30
,09-08 13:34:24.971  1031  1113 D BluetoothManagerService: Message: 30
09-08 13:34:24.972  6851  6851 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 13:34:24.974  6851  6851 D BluetoothMap: Create BluetoothMap proxy object
09-08 13:34:24.974  1031  1113 D BluetoothManagerService: Message: 30
,09-08 13:34:24.977  1031  1113 D BluetoothManagerService: Message: 30
09-08 13:34:24.978  6851  6851 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-08 13:34:24.979  6851  6851 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-08 13:34:24.991  6851  6851 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-08 13:34:24.994  6851  6851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-08 13:34:25.000  6851  6851 D DockEventReceiver: finishStartingService: stopping service
,09-08 13:34:25.001  6851  6851 D BluetoothInputDevice: Proxy object connected
09-08 13:34:25.002  6851  6851 D HidProfile: Bluetooth service connected
09-08 13:34:25.003  6851  6851 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 13:34:25.004  6851  6851 D PanProfile: Bluetooth service connected
09-08 13:34:25.004  6851  6851 D BluetoothMap: Proxy object connected
09-08 13:34:25.005  6851  6851 D MapProfile: Bluetooth service connected
09-08 13:34:25.005  6851  6851 D BluetoothMap: getConnectedDevices()
09-08 13:34:25.006  6851  6851 D BluetoothMap: Bluetooth is Not enabled
09-08 13:34:25.006  6851  6851 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-08 13:34:25.047  7298  7298 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-08 13:34:25.048  7298  7298 W LG Account v2.2: No ProfileInfo entries
09-08 13:34:25.048  7298  7298 I LG Account v2.2: isEnabled: false
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Country: EU
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Operator: OPEN
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Ranking support: false
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Comfort support: false
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Accessory: true
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Health device: true
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Extra Pedometer: false
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Blood glucose device: false
09-08 13:34:25.048  7298  7298 I Feature : [Lifetracker]Device Number: 3
,09-08 13:34:25.055  6851  6851 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-08 13:34:25.059  6851  6851 D BluetoothPermissionRequest: onReceive
09-08 13:34:25.062  6851  6851 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-08 13:34:25.078  6851  6851 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-08 13:34:25.084  1031  1934 I ActivityManager: Killing 6173:com.android.vending/u0a44 (adj 15): empty #17
09-08 13:34:25.152  1031  1970 W libprocessgroup: failed to open /acct/uid_10044/pid_6173/cgroup.procs: No such file or directory
09-08 13:34:25.153  3818  3818 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-08 13:34:25.153  3818  3818 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-08 13:34:25.154  3818  3818 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-08 13:34:25.167  3818  3818 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-08 13:34:25.167  3818  3818 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-08 13:34:25.170  3818  3818 V BluetoothFtpService: Ftp Service onStartCommand
,09-08 13:34:25.171  3818  3818 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:25.171  3818  3818 V BluetoothFtpService: Ftp Service closeService
09-08 13:34:25.172  3818  3818 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-08 13:34:25.173  3818  3818 V BluetoothFtpService: successfully stopped ftp service
09-08 13:34:25.174  3818  3818 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 13:34:25.174  3818  3818 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 13:34:25.174  3818  3818 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 13:34:25.175  3818  3818 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:25.175  3818  3818 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-08 13:34:25.175  3818  3818 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-08 13:34:25.177  3818  3818 V BluetoothFtpService: Ftp Service onDestroy
09-08 13:34:25.177  3818  3818 V BluetoothFtpService: Ftp Service closeService
09-08 13:34:25.236  1031  1971 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7325 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-08 13:34:25.238  3818  3818 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:25.238  3818  3818 V BluetoothSapService: state: 13
09-08 13:34:25.238  3818  3818 V BluetoothSapService: Stopping SAP server process
09-08 13:34:25.240  3818  3818 V BluetoothSapService: Sap Service closeSapService in
09-08 13:34:25.240  3818  3818 V BluetoothSapService: Close listen Socket : 
09-08 13:34:25.241  3818  3818 V BluetoothSapService: Close rfcomm Socket : 
09-08 13:34:25.241  3818  3818 V BluetoothSapService: Close sapd  Socket : 
,09-08 13:34:25.245  3818  3818 V BluetoothSapService: Sap Service closeSapService out
09-08 13:34:25.245  3818  3818 V BluetoothSapService: Sap Service onDestroy
09-08 13:34:25.245  3818  3818 V BluetoothSapService: Sap Service closeSapService in
09-08 13:34:25.245  3818  3818 V BluetoothSapService: Close listen Socket : 
09-08 13:34:25.245  3818  3818 V BluetoothSapService: Close rfcomm Socket : 
09-08 13:34:25.245  3818  3818 V BluetoothSapService: Close sapd  Socket : 
09-08 13:34:25.246  3818  3818 V BluetoothSapService: Sap Service closeSapService out
,09-08 13:34:25.316  7325  7325 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 13:34:25.335  1031  2040 I ActivityManager: Killing 6971:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-08 13:34:25.365  1031  1779 W libprocessgroup: failed to open /acct/uid_10011/pid_6971/cgroup.procs: No such file or directory
,09-08 13:34:25.692  1031  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2437 sc=60 link=72 tx=82.5, 0.0, 0.0  rx=98.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:160683163] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:25.695  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2437 sc=60 link=72 tx=82.5, 0.0, 0.0  rx=98.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:160683167] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:25.695  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 13:34:25.741  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 13:34:25.747  1031  1534 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-08 13:34:25.779  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:25.797  1031  1113 D Tethering: MasterInitialState.processMessage what=3
09-08 13:34:25.822  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:25.829  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:25.834  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-08 13:34:25.837  6400  6439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 13:34:25.849  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 13:34:25.871  2177  2177 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:25.878  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:25.878  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:25.879  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:25.879  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:25.879  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:25.879  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:25.879  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9690b2b removed from the list
09-08 13:34:25.879  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:25.879  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11630b88 removed from the list
09-08 13:34:25.879  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:25.879  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:25.879  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:25.886  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:25.886  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@267ba146 added. We now have 2 listener(s)
,09-08 13:34:25.890  3818  3910 D bt_hci_bdroid: cleanup
09-08 13:34:25.891  3818  3986 I bt_lpm  : LPM is already off!!!
09-08 13:34:25.891  3818  4123 I bt_userial_mct: exiting userial_read_thread
09-08 13:34:25.891  3818  4123 D bt_userial_mct: Leaving userial_evt_read_thread()
09-08 13:34:25.891  3818  3984 W bt-btif : ag scb idx 1 not allocated
09-08 13:34:25.891  3818  3984 E bt-btif : BTA AG is already disabled, ignoring ...
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 13:34:25.891  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-08 13:34:25.892  3818  3984 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 13:34:25.892  3818  3984 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 13:34:25.892  3818  3910 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-08 13:34:25.893  3818  3986 I bt_vendor: hw_epilog_process
09-08 13:34:25.893  3818  3910 D bt_hci_bdroid: cleanup Finalizing cleanup
09-08 13:34:25.893  3818  3910 D bt_userial_mct: userial_close
09-08 13:34:25.893  3818  3910 E bt_userial_mct: pthread_join() FAILED result:3
09-08 13:34:25.893  3818  3910 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-08 13:34:25.896  1031  1607 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:25.912  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 13:34:25.912  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:25.912  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:25.912  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:25.912  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@feb2f07 added. We now have 2 listener(s)
09-08 13:34:25.912  6595  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 13:34:25.918  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:34:25.945  1031  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:25.947  1031  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:25.964  1031  1897 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7365 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-08 13:34:25.967  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:25.970  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:25.970  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:25.970  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:25.970  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:25.970  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:25.970  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:25.970  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:25.970  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:25.970  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:25.971  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:25.971  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:25.971  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:25.971  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:25.971  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:25.971  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:25.971  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:25.972  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@267ba146 removed from the list
09-08 13:34:25.972  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:25.972  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@feb2f07 removed from the list
09-08 13:34:25.975  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:25.979  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:25.979  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:25.979  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:25.981  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:25.981  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@260a965d added. We now have 2 listener(s)
09-08 13:34:25.982  1031  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:25.984  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 13:34:25.984  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:25.984  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:25.985  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:25.985  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15408bd2 added. We now have 2 listener(s)
09-08 13:34:25.985  6595  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:25.985  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:25.988  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:25.990  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:25.991  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:25.991  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:25.991  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:25.991  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:25.991  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:25.991  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:25.991  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:25.991  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:25.991  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:25.991  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:25.991  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:25.993  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:25.995  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:25.996  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:25.996  1031  1046 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3e02831d mBinding = false
09-08 13:34:25.996  1031  1113 D BluetoothManagerService: Message: 2
09-08 13:34:25.996  1031  1113 D BluetoothManagerService: Sending off request.
09-08 13:34:25.997  3818  7297 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-08 13:34:25.997  3818  7297 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
09-08 13:34:25.998  1031  1113 E BluetoothManagerService: IBluetooth.disable() returned false
,09-08 13:34:26.020  3818  3910 D bt_hci_bdroid: set_power 0
09-08 13:34:26.020  3818  3910 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 13:34:26.020  3818  3910 I bt_vendor: bluetooth satus is on
09-08 13:34:26.020  3818  3910 I bt_vendor: bt-vendor : resetting BT status
09-08 13:34:26.020  3818  3910 I bt_vendor: Starting hciattach daemon
09-08 13:34:26.020  3818  3910 I bt_vendor: try to set false
,09-08 13:34:26.022  3818  3910 I bt_vendor: Starting hciattach daemon
09-08 13:34:26.022  3818  3910 I bt_vendor: try to set false
09-08 13:34:26.023  3818  3910 I bt_vendor: cleanup
09-08 13:34:26.023  3818  3984 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-08 13:34:26.024  3818  3910 I GKI_LINUX: GKI_exit_task 0 done
09-08 13:34:26.024  3818  3910 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-08 13:34:26.025  3818  3902 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-08 13:34:26.027  3818  3818 D HeadsetService: Received stop request...Stopping profile...
09-08 13:34:26.027  3818  3818 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-08 13:34:26.027  3818  3818 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 13:34:26.027  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e04c528
09-08 13:34:26.028  3818  3932 D HeadsetStateMachine: Exit Disconnected: -1
09-08 13:34:26.029  1031  1031 D BluetoothHeadset: Proxy object disconnected
09-08 13:34:26.029  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-08 13:34:26.029  1846  1846 D BluetoothHeadset: Proxy object disconnected
09-08 13:34:26.029  1846  1846 D BluetoothHeadset: Proxy object disconnected
09-08 13:34:26.029  1846  1846 D BluetoothHeadset: Proxy object disconnected
09-08 13:34:26.029  3818  3818 D A2dpService: Received stop request...Stopping profile...
09-08 13:34:26.030  3818  3967 D A2dpStateMachine: Exit Disconnected: -1
09-08 13:34:26.031  3818  3818 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-08 13:34:26.032  3818  3902 D BluetoothAdapterState: Stopping profile services that were post enabled
09-08 13:34:26.032  3818  3818 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-08 13:34:26.032  3818  3818 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 13:34:26.032  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e04c528
09-08 13:34:26.033  1031  1031 D BluetoothA2dp: Proxy object disconnected
09-08 13:34:26.033  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-08 13:34:26.036  3818  3818 D HidService: Received stop request...Stopping profile...
09-08 13:34:26.036  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e04c528
09-08 13:34:26.037  6851  6851 D BluetoothInputDevice: Proxy object disconnected
09-08 13:34:26.037  6851  6851 D HidProfile: Bluetooth service disconnected
09-08 13:34:26.037  3818  3818 D HeadsetStateMachine: Unbinding service...
09-08 13:34:26.038  3818  3818 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 13:34:26.038  3818  3818 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 13:34:26.038  3818  3818 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 13:34:26.038  3818  3818 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 13:34:26.038  3818  3818 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 13:34:26.038  3818  3818 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 13:34:26.038  3818  3818 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 13:34:26.039  3818  3818 D HealthService: Received stop request...Stopping profile...
09-08 13:34:26.039  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e04c528
09-08 13:34:26.041  3818  3818 D PanService: Received stop request...Stopping profile...
09-08 13:34:26.042  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e04c528
09-08 13:34:26.042  6851  6851 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 13:34:26.042  6851  6851 D PanProfile: Bluetooth service disconnected
09-08 13:34:26.042  3818  3818 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 13:34:26.043  3818  3818 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 13:34:26.043  3818  3818 D BtGatt.GattService: stop()
09-08 13:34:26.043  3818  3818 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 13:34:26.044  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e04c528
09-08 13:34:26.045  3818  3818 D BluetoothMapService: Received stop request...Stopping profile...
09-08 13:34:26.045  3818  3818 D BluetoothMapService: stop()
09-08 13:34:26.045  3818  3818 D BluetoothMapEmailAppObserver: deinitObservers()
09-08 13:34:26.045  3818  3818 D BluetoothMapEmailAppObserver: removeReceiver()
,09-08 13:34:26.046  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e04c528
09-08 13:34:26.047  3818  3818 I BluetoothA2dpServiceJni: cleanupNative
09-08 13:34:26.048  3818  3968 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 13:34:26.048  3818  3818 I GKI_LINUX: GKI_exit_task 2 done
09-08 13:34:26.048  3818  3818 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-08 13:34:26.048  3818  3818 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 13:34:26.048  3818  3818 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 13:34:26.049  3818  3818 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 13:34:26.049  3818  3818 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 13:34:26.049  3818  3818 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 13:34:26.049  3818  3818 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 13:34:26.049  3818  3818 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 13:34:26.050  3818  3818 V BluetoothMapService: Handler(): got msg=4
09-08 13:34:26.050  3818  3818 D BluetoothMapService: MAP Service closeService in
09-08 13:34:26.050  3818  3818 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 13:34:26.050  3818  3818 V BluetoothMapService: MAP Service closeService out
09-08 13:34:26.051  3818  3818 D BluetoothMapService: cleanup()
09-08 13:34:26.051  3818  3818 D BluetoothMapService: MAP Service closeService in
09-08 13:34:26.051  3818  3818 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 13:34:26.051  3818  3818 V BluetoothMapService: MAP Service closeService out
09-08 13:34:26.052  3818  3902 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-08 13:34:26.052  3818  3902 D BluetoothAdapterProperties: Setting state to 10
09-08 13:34:26.052  3818  3902 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-08 13:34:26.053  1031  1113 D BluetoothManagerService: Message: 60
09-08 13:34:26.053  1031  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-08 13:34:26.053  1031  1113 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-08 13:34:26.054  3818  3902 I BluetoothAdapterState: Entering OffState
09-08 13:34:26.054  6851  6867 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 13:34:26.054  6851  6851 D BluetoothMap: Proxy object disconnected
09-08 13:34:26.054  6851  6851 D MapProfile: Bluetooth service disconnected
09-08 13:34:26.054  6851  6866 D BluetoothMap: onBluetoothStateChange: up=false
09-08 13:34:26.055  6851  6867 D BluetoothPan: onBluetoothStateChange on: false
09-08 13:34:26.055  1031  1113 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:26.056  1846  3935 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:26.056  1031  1113 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 13:34:26.056  6851  6866 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 13:34:26.057  1846  3933 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:26.057  1846  1861 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:26.059  1031  1113 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-08 13:34:26.059  1031  1113 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-08 13:34:26.060  7365  7365 I AppUp4:AppBoxCP: onCreate
09-08 13:34:26.061  7365  7365 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-08 13:34:26.062  1031  1113 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-08 13:34:26.062  1031  1113 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-08 13:34:26.062  1031  1113 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3e02831d mBinding = false
09-08 13:34:26.062  1031  1113 D BluetoothManagerService: Sending unbind request.
09-08 13:34:26.064  1031  1113 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-08 13:34:26.065  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:26.065  1935  2121 D LGBluetoothAPIService: Message: 2
09-08 13:34:26.066  1935  2121 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@d5ef0db mBinding = false
09-08 13:34:26.066  1935  2121 D LGBluetoothAPIService: Sending unbind request.
09-08 13:34:26.067  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 13:34:26.067  6851  6851 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 13:34:26.068  6851  6851 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-08 13:34:26.068  6851  6851 D LGBluetoothEventManager: [BTUI] clear device connection state
09-08 13:34:26.069  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:26.070  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:26.072  1597  1597 D BluetoothAdapter: 119628611: getState() :  mService = null. Returning STATE_OFF
09-08 13:34:26.072  1597  1597 D BluetoothAdapter: 119628611: getState() :  mService = null. Returning STATE_OFF
09-08 13:34:26.074  3818  3910 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-08 13:34:26.074  3818  3818 I GKI_LINUX: GKI_exit_task 1 done
09-08 13:34:26.074  3818  3818 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-08 13:34:26.075  3818  3818 I BluetoothServiceJni: cleanupNative: return from cleanup
09-08 13:34:26.075  3818  3818 I art     : --- WEIRD: removing null entry 246
09-08 13:34:26.075  3818  3818 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-08 13:34:26.075  3818  3818 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-08 13:34:26.076  3818  3818 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-08 13:34:26.076  6851  6851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 13:34:26.078  3818  3818 I art     : System.exit called, status: 0
09-08 13:34:26.078  3818  3818 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-08 13:34:26.082  6851  6851 D DockEventReceiver: finishStartingService: stopping service
,09-08 13:34:26.087  7365  7365 I AppUp4:DB:  setFingerPrint start
09-08 13:34:26.087  7365  7365 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-08 13:34:26.097  7365  7365 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-08 13:34:26.097  7365  7365 I AppUp4:DB:  SDK version = 21
09-08 13:34:26.097  7365  7365 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-08 13:34:26.099  7365  7365 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-08 13:34:26.100   319   319 V AudioFlinger: 3818 died, releasing its sessions
,09-08 13:34:26.100   319   319 V AudioFlinger:  pid 1846 @ 0
09-08 13:34:26.100   319   319 V AudioFlinger:  pid 3323 @ 1
09-08 13:34:26.100   319   319 V AudioFlinger:  pid 3323 @ 2
09-08 13:34:26.101  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 13:34:26.101  6851  6851 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-08 13:34:26.101  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:26.102  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 13:34:26.103  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 13:34:26.120  1031  1779 I ActivityManager: Process com.android.bluetooth (pid 3818) has died
09-08 13:34:26.120  1031  1779 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-08 13:34:26.125  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 13:34:26.127  7365  7365 I AppUp4:CustModeStarterReceiver: onReceive
09-08 13:34:26.136  6851  6851 D BluetoothPermissionRequest: onReceive
,09-08 13:34:26.138  6851  6851 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-08 13:34:26.138  6851  6851 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-08 13:34:26.141  6851  6851 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 13:34:26.176  7365  7365 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 13:34:26.176  7365  7365 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 13:34:26.183  7365  7365 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f3d274b
09-08 13:34:26.183  7365  7365 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 13:34:26.183  7365  7365 D AppUp4:CustFacade: isPhone : true
09-08 13:34:26.184  7365  7365 D AppUp4:CustModeStarterReceiver: begin check event
09-08 13:34:26.184  7365  7365 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-08 13:34:26.185  7365  7365 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-08 13:34:26.185  7365  7390 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,09-08 13:34:26.185  7365  7390 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-08 13:34:26.185  7365  7390 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-08 13:34:26.218  1031  2006 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7392 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-08 13:34:26.222  1031  2006 I ActivityManager: Killing 6509:com.lge.email/u0a23 (adj 15): empty #17
,09-08 13:34:26.259   395   395 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 477us total 38.162ms
,09-08 13:34:26.281   395   395 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 422us total 20.792ms
,09-08 13:34:26.302   395   395 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 375us total 18.904ms
,09-08 13:34:26.334  1031  2045 W libprocessgroup: failed to open /acct/uid_10023/pid_6509/cgroup.procs: No such file or directory
09-08 13:34:26.338  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:26.338  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 13:34:26.349  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:26.361  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 13:34:26.368  4291  7412 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 13:34:26.371  4291  7412 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 13:34:26.372  3431  3431 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:26.374  4291  7413 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:26.375  4291  7413 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-08 13:34:26.380  3431  3431 V DownloadManager: DownloadService onCreate
09-08 13:34:26.385  4291  7412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 13:34:26.389  3431  7414 I DownloadManager: in removeSpuriousFiles
,09-08 13:34:26.389  3431  7414 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-08 13:34:26.390  7392  7392 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-08 13:34:26.392  3431  7414 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@79d7891 on behalf of 3431
09-08 13:34:26.392  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-08 13:34:26.392  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-08 13:34:26.392  7392  7392 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 13:34:26.392  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-08 13:34:26.392  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-08 13:34:26.393  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-08 13:34:26.393  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-08 13:34:26.393  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-08 13:34:26.393  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-08 13:34:26.393  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-08 13:34:26.393  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-08 13:34:26.393  7392  7392 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-08 13:34:26.393  3431  7414 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-08 13:34:26.394  7392  7392 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-08 13:34:26.398  3431  7414 I DownloadManager: in trimDatabase
09-08 13:34:26.398  3431  7414 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 13:34:26.399  3431  7414 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9eeb3f6 on behalf of 3431
09-08 13:34:26.420  7392  7392 D BluetoothAdapterApp: Loading JNI Library
,09-08 13:34:26.427  1031  2040 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7417 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-08 13:34:26.432  3431  3431 V DownloadManager: DownloadService onStartCommand
09-08 13:34:26.433  4291  4291 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 13:34:26.434  3431  7415 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-08 13:34:26.438  4291  4291 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 13:34:26.438  4291  4291 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 13:34:26.440  4291  4291 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 13:34:26.442  3431  7415 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@cb1e264 on behalf of 3431
09-08 13:34:26.448  3431  7415 V DownloadManager: processing inserted download 1
,09-08 13:34:26.452  4291  4291 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 13:34:26.464  7392  7392 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@21a14b09 Instance Count = 1
,09-08 13:34:26.470  7392  7392 D BluetoothAdapterApp: onCreate
09-08 13:34:26.471  3431  7415 V DownloadManager: processing inserted download 4
09-08 13:34:26.472  3431  7415 V DownloadManager: processing inserted download 7
09-08 13:34:26.473  3431  7415 V DownloadManager: processing inserted download 8
09-08 13:34:26.474  3431  7415 V DownloadManager: processing inserted download 9
09-08 13:34:26.475  3431  7415 V DownloadManager: processing inserted download 10
09-08 13:34:26.477  3431  7415 V DownloadManager: processing inserted download 11
09-08 13:34:26.478  3431  7415 V DownloadManager: processing inserted download 12
09-08 13:34:26.479  3431  7415 V DownloadManager: processing inserted download 13
,09-08 13:34:26.482  3431  7415 V DownloadManager: processing inserted download 14
09-08 13:34:26.483  3431  7415 V DownloadManager: processing inserted download 16
09-08 13:34:26.490  3431  3431 V DownloadManager: DownloadService onDestroy
09-08 13:34:26.495  7392  7392 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-08 13:34:26.495  7392  7392 D ProfileConfigQcom: Adding HeadsetService
09-08 13:34:26.495  7392  7392 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-08 13:34:26.496  7392  7392 D ProfileConfigQcom: Adding A2dpService
09-08 13:34:26.497  7392  7392 D ProfileConfigQcom: [BTUI] HidService is supported
09-08 13:34:26.497  7392  7392 D ProfileConfigQcom: Adding HidService
09-08 13:34:26.497  7392  7392 D ProfileConfigQcom: [BTUI] HealthService is supported
09-08 13:34:26.497  7392  7392 D ProfileConfigQcom: Adding HealthService
09-08 13:34:26.498  7392  7392 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-08 13:34:26.498  7392  7392 D ProfileConfigQcom: [BTUI] PanService is supported
09-08 13:34:26.499  7392  7392 D ProfileConfigQcom: Adding PanService
09-08 13:34:26.499  7392  7392 D ProfileConfigQcom: [BTUI] GattService is supported
09-08 13:34:26.499  7392  7392 D ProfileConfigQcom: Adding GattService
09-08 13:34:26.499  7392  7392 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-08 13:34:26.500  7392  7392 D ProfileConfigQcom: Adding BluetoothMapService
,09-08 13:34:26.501  7392  7392 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-08 13:34:26.504  7392  7392 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-08 13:34:26.508  6851  6851 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-08 13:34:26.509  7392  7392 V LGMDMManagerInternal: Create singleton instance
09-08 13:34:26.513  7417  7417 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 13:34:26.514  7417  7417 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 13:34:26.515  7417  7417 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 13:34:26.516  7417  7417 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 13:34:26.594  7392  7392 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-08 13:34:26.597  7392  7392 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-08 13:34:26.598  7392  7392 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-08 13:34:26.598  7392  7392 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 13:34:26.600  7392  7392 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:26.600  7392  7392 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-08 13:34:26.607  7417  7417 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-08 13:34:26.611  7325  7325 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-08 13:34:26.615  1031  1970 I ActivityManager: Killing 7047:com.android.chrome/u0a57 (adj 15): empty #17
09-08 13:34:26.621  7417  7417 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-08 13:34:26.658  7417  7417 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-08 13:34:26.752  1031  1971 W libprocessgroup: failed to open /acct/uid_10057/pid_7047/cgroup.procs: No such file or directory
,09-08 13:34:26.805  7417  7417 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 13:34:26.805  7417  7417 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:26.928  7417  7417 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 13:34:26.963   315  7452 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 13:34:26.964   315  7452 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,09-08 13:34:26.977  3323  3323 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 13:34:26.977  3323  3323 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:26.977  3323  3323 I LgeMiscReceiver: networkInfo.isConnected() = true
09-08 13:34:26.977  3323  3323 D PhoneState: setPdpRejectCasuse : false
,09-08 13:34:26.981  7026  7026 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 13:34:26.982  7026  7026 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 13:34:26.988  7417  7417 I HubEmail: JNI_OnLoad()
09-08 13:34:26.988  7417  7417 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:26.988  7417  7417 I HubEmail: registerNatives()
09-08 13:34:26.988  7417  7417 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:26.988  7417  7417 I HubEmail: registerNativeMethods()
09-08 13:34:26.988  7417  7417 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:26.989  7417  7417 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-08 13:34:27.004   315  7452 D libc-netbsd: res_queryN name = www.google.com succeed
,09-08 13:34:27.010   315  7459 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 13:34:27.010   315  7459 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 13:34:27.010   315  7459 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-08 13:34:27.031  1031  1897 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7460 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:27.038  7417  7455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 13:34:27.080  1031  1535 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-08 13:34:27.082  6892  7457 V FormManager: There are no updated forms. The schedule will be deleted.
09-08 13:34:27.090  6892  7457 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-08 13:34:27.111  1031  1898 I ActivityManager: Killing 7067:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-08 13:34:27.182  1031  1897 W libprocessgroup: failed to open /acct/uid_10062/pid_7067/cgroup.procs: No such file or directory
,09-08 13:34:27.291  1031  1779 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7483 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-08 13:34:27.292  1031  1779 I ActivityManager: Killing 7085:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-08 13:34:27.333  1031  1047 W libprocessgroup: failed to open /acct/uid_10085/pid_7085/cgroup.procs: No such file or directory
,09-08 13:34:27.434  1031  1933 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7504 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:27.436  1031  1933 I ActivityManager: Killing 7106:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-08 13:34:27.651  1031  1570 W libprocessgroup: failed to open /acct/uid_10093/pid_7106/cgroup.procs: No such file or directory
,09-08 13:34:27.707  7504  7504 I art     : Almond Protected OAT
,09-08 13:34:27.761  7504  7504 D WeatherApplication: removeAccount
,09-08 13:34:27.766  7504  7504 D WeatherApplication: Account.length = 0
09-08 13:34:27.766  7504  7504 E WeatherApplication: OPERATOR:OPEN
09-08 13:34:27.773  7504  7504 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:27
09-08 13:34:27.776  7504  7504 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 13:34:27.776  7504  7504 D Weather.Utils: 2 : All the weather widget is gone.
,09-08 13:34:27.781  7504  7504 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 13:34:27.784  7504  7504 D WeatherAncestor: connectivity changed - connection : true
09-08 13:34:27.785  7504  7504 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-08 13:34:27.793  7504  7504 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 13:34:27.794  7504  7504 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 13:34:27.794  7504  7504 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-08 13:34:27.816  7504  7504 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 13:34:27.817  7504  7504 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:27
,09-08 13:34:27.856  1031  1898 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7525 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:27.860  1031  1898 I ActivityManager: Killing 5572:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-08 13:34:28.058  1031  2006 W libprocessgroup: failed to open /acct/uid_10097/pid_5572/cgroup.procs: No such file or directory
,09-08 13:34:28.170   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-08 13:34:28.170   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 13:34:28.170   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 13:34:28.174  7525  7559 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-08 13:34:28.180   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:28.180   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 13:34:28.180   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 13:34:28.181  7525  7559 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 13:34:28.190   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:28.190   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 13:34:28.190   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 13:34:28.191  7525  7562 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 13:34:28.197   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:28.197   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 13:34:28.197   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 13:34:28.198  7525  7562 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 13:34:28.491  7525  7525 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-08 13:34:28.504  7525  7525 I LibraryLoader: Loading: webviewchromium
09-08 13:34:28.507  7525  7525 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3543-3547)
09-08 13:34:28.507  7525  7525 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 13:34:28.516  7525  7525 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ce6e222}
09-08 13:34:28.517  7525  7525 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 13:34:28.517  7525  7525 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 13:34:28.529  7525  7525 I BrowserStartupController: Initializing chromium process, renderers=0
,09-08 13:34:28.541  7525  7525 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 13:34:28.555  7525  7525 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-08 13:34:28.556  7525  7525 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
09-08 13:34:28.556  7525  7525 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
,09-08 13:34:28.567   319  1381 V AudioPolicyService: registerClient() client 0xb558ade0, uid 10093
09-08 13:34:28.569  7525  7592 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 13:34:28.592  7525  7525 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 13:34:28.592  7525  7525 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 13:34:28.592  7525  7525 I Adreno-EGL: Build Date: 12/12/14 금
09-08 13:34:28.592  7525  7525 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 13:34:28.592  7525  7525 I Adreno-EGL: Remote Branch: 
09-08 13:34:28.592  7525  7525 I Adreno-EGL: Local Patches: 
09-08 13:34:28.592  7525  7525 I Adreno-EGL: Reconstruct Branch: 
,09-08 13:34:28.688  7525  7525 I NSApplication: Starting up...
,09-08 13:34:28.725  1031  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2437 sc=60 link=72 tx=66.8, 0.0, 0.0  rx=69.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:160686197] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:28.726  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2437 sc=60 link=72 tx=66.8, 0.0, 0.0  rx=69.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:160686198] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:28.727  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 13:34:28.792  1031  2040 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7621 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:28.795  1031  1607 I ActivityManager: Killing 6685:com.lge.bnr/1000 (adj 15): empty #17
09-08 13:34:28.855  1031  1898 W libprocessgroup: failed to open /acct/uid_1000/pid_6685/cgroup.procs: No such file or directory
,09-08 13:34:28.911  7621  7621 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 13:34:29.002  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:29.003  1031  1570 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:29.004  1031  1570 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-08 13:34:29.026  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 13:34:29.027  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 13:34:29.028  1031  1113 D BluetoothManagerService: Message: 1
09-08 13:34:29.028  1031  1113 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-08 13:34:29.030  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-08 13:34:29.054  1031  1113 D BluetoothManagerService: Message: 20
09-08 13:34:29.055  1031  1113 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a4fcd8b:true
,09-08 13:34:29.057  7392  7392 D BluetoothAdapterState: make
09-08 13:34:29.062  7392  7392 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-08 13:34:29.062  7392  7392 I bluedroid-qcom: init
09-08 13:34:29.063  7392  7647 I BluetoothAdapterState: Entering OffState
09-08 13:34:29.063  7392  7392 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 13:34:29.064  7392  7392 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-08 13:34:29.064  7392  7392 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 13:34:29.064  7392  7392 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 13:34:29.064  7392  7392 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-08 13:34:29.064  7392  7392 I bluedroid-qcom: get_profile_interface socket
09-08 13:34:29.065  7392  7650 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-08 13:34:29.066  7392  7392 I bluedroid-qcom: get_profile_interface map_client
09-08 13:34:29.051  7651  7651 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:29.051  7651  7651 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:29.067  7392  7650 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-08 13:34:29.070  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-08 13:34:29.071  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-08 13:34:29.071  7392  7650 D BluetoothAdapterProperties: Name is: G3
,09-08 13:34:29.074  7651  7651 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-08 13:34:29.074  7651  7651 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-08 13:34:29.074  7651  7651 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-08 13:34:29.075  7651  7651 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-08 13:34:29.076  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-08 13:34:29.076  1031  1113 D BluetoothManagerService: Message: 40
09-08 13:34:29.076  1031  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-08 13:34:29.077  7392  7407 I bluedroid-qcom: config_hci_snoop_log
09-08 13:34:29.079  1031  1113 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-08 13:34:29.079  1031  1113 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-08 13:34:29.080  7651  7651 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-08 13:34:29.080  7651  7651 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-08 13:34:29.086  7392  7647 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-08 13:34:29.087  7392  7647 D BluetoothAdapterProperties: Setting state to 11
09-08 13:34:29.087  7392  7647 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-08 13:34:29.089  7392  7647 I LGBluetoothServiceJni: classInitNative: succeeds
09-08 13:34:29.089  1031  1113 D BluetoothManagerService: Message: 60
09-08 13:34:29.089  1031  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-08 13:34:29.089  1031  1113 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-08 13:34:29.091  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:29.092  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 13:34:29.095  6851  6851 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-08 13:34:29.097  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:29.098  7392  7647 D BluetoothBondStateMachine: make
,09-08 13:34:29.099  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:29.102  7392  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.102  7392  7647 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-08 13:34:29.102  7392  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.102  7392  7647 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-08 13:34:29.103  7392  7647 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-08 13:34:29.103  7392  7392 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 13:34:29.104  7392  7392 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:29.104  7392  7392 V BluetoothPbapReceiver: ***********state = 11
09-08 13:34:29.107  7392  7647 E BluetoothAdapterService: File transfer profiles supported!!
09-08 13:34:29.107  7392  7652 I BluetoothBondStateMachine: StableState(): Entering Off State
09-08 13:34:29.109  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 13:34:29.117  7392  7392 D HeadsetService: Received start request. Starting profile...
09-08 13:34:29.118  7392  7392 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 13:34:29.118  7392  7392 D LGBluetoothHfpAdapter: Version 1.6
,09-08 13:34:29.121  7392  7647 E BluetoothAdapterService: File transfer profiles supported!!
09-08 13:34:29.122  7392  7392 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 13:34:29.123  7392  7392 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 13:34:29.124  7392  7392 D HeadsetStateMachine: make
09-08 13:34:29.132  6851  6851 D BluetoothPermissionRequest: onReceive
,09-08 13:34:29.137  7392  7647 E BluetoothAdapterService: File transfer profiles supported!!
09-08 13:34:29.137  6851  6851 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 13:34:29.148  7392  7647 E BluetoothAdapterService: File transfer profiles supported!!
09-08 13:34:29.153  7392  7647 E BluetoothAdapterService: File transfer profiles supported!!
09-08 13:34:29.159  7392  7647 E BluetoothAdapterService: File transfer profiles supported!!
09-08 13:34:29.164  7392  7647 E BluetoothAdapterService: File transfer profiles supported!!
,09-08 13:34:29.167  7392  7392 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:29.167  7392  7392 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 13:34:29.173  7392  7392 D HeadsetStateMachine: max_hf_connections = 1
09-08 13:34:29.173  7392  7392 I bluedroid-qcom: get_profile_interface handsfree
09-08 13:34:29.175  7392  7392 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-08 13:34:29.176   319   319 V AudioPolicyService: registerClient() client 0xb558ac40, uid 1002
09-08 13:34:29.176   319  1381 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-08 13:34:29.176   319  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 13:34:29.176   319  1381 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 13:34:29.176  7392  7392 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-08 13:34:29.177   319  2185 V AudioFlinger: registerClient() client 0xb55815f8, pid 7392
09-08 13:34:29.177   319  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 13:34:29.177   319  1376 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 13:34:29.177  1846  1862 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 13:34:29.177  1846  1862 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 13:34:29.178   319  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 13:34:29.178   319  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 13:34:29.178  7392  7654 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 13:34:29.178  1031  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 13:34:29.178  1031  1607 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-08 13:34:29.178  1031  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 13:34:29.178  1031  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 13:34:29.178  1597  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 13:34:29.178  1597  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 13:34:29.178  1597  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 13:34:29.178  1597  1619 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 13:34:29.178  7392  7654 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-08 13:34:29.178  7392  7654 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 13:34:29.178  7392  7654 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-08 13:34:29.178  1846  2461 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 13:34:29.178  1846  2461 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 13:34:29.180  3323  3343 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-08 13:34:29.180  3323  3343 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-08 13:34:29.180  3323  3343 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-08 13:34:29.180  3323  3343 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-08 13:34:29.181  7392  7392 V ToneGenerator: Create Track: 0xb4928080
09-08 13:34:29.181  7392  7392 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-08 13:34:29.181  7392  7392 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-08 13:34:29.181   319   319 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-08 13:34:29.181   319   319 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-08 13:34:29.181   319   319 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 13:34:29.181   319   319 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 13:34:29.182   319  1381 I AudioFlinger: isAudioPlaybackHookOn() false
09-08 13:34:29.182   319  2185 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-08 13:34:29.182   319  2185 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-08 13:34:29.182   319  2185 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-08 13:34:29.182   319  2185 V AudioPolicyManagerEx: getOutput() returns output 2
09-08 13:34:29.182  7392  7392 V AudioSystem: getLatency() output 2, latency 50
09-08 13:34:29.182  7392  7392 V AudioSystem: getFrameCount() output 2, frameCount 960
09-08 13:34:29.182  7392  7392 V AudioTrack: createTrack_l() output 2 afLatency 50
09-08 13:34:29.183   319  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-08 13:34:29.183   319  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-08 13:34:29.183   319  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-08 13:34:29.183   319  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-08 13:34:29.183   319  1380 V AudioFlinger: createTrack() lSessionId: 22
09-08 13:34:29.184  7392  7392 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-08 13:34:29.184   319   319 V AudioFlinger: acquiring 22 from 7392, for 7392
09-08 13:34:29.184   319   319 V AudioFlinger:  added new entry for 22
09-08 13:34:29.185  7392  7392 V ToneGenerator: ToneGenerator INIT OK, time: 134225
09-08 13:34:29.185  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.185  7392 , 7647 V LGMDMManager: Create singleton instance
09-08 13:34:29.186  7392  7655 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-08 13:34:29.186  7392  7655 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 13:34:29.186  7392  7655 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 13:34:29.187  7392  7655 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-08 13:34:29.187  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.188   319  1380 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7392
09-08 13:34:29.189  7392  7392 D A2dpService: Received start request. Starting profile...
09-08 13:34:29.190   319  1380 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-08 13:34:29.190   319  1380 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-08 13:34:29.190   319  1380 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-08 13:34:29.190   319  1380 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-08 13:34:29.190   319  1380 V voice   : voice_set_parameters: exit with code(0)
09-08 13:34:29.190   319  1380 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-08 13:34:29.190   319  1380 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-08 13:34:29.190   319  1380 V msm8974_platform: platform_set_parameters: exit with code(0)
09-08 13:34:29.190   319  1380 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-08 13:34:29.190   319  1380 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-08 13:34:29.190   319  1380 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,09-08 13:34:29.190  7392  7647 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-08 13:34:29.191  7392  7392 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 13:34:29.192  7392  7392 V Avrcp   : make
09-08 13:34:29.193  7392  7392 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-08 13:34:29.193  7392  7392 I bluedroid-qcom: get_profile_interface avrcp
09-08 13:34:29.195  7392  7655 V ToneGenerator: ToneGenerator destructor
09-08 13:34:29.195  7392  7655 V ToneGenerator: stopTone
,09-08 13:34:29.195  7392  7655 V ToneGenerator: Delete Track: 0xb4928080
09-08 13:34:29.196  7392  7655 V AudioTrack: ~AudioTrack, releasing session id from 7392 on behalf of 7392
09-08 13:34:29.196   319   319 V AudioFlinger: releasing 22 from 7392 for 7392
09-08 13:34:29.197   319   319 V AudioFlinger:  decremented refcount to 0
09-08 13:34:29.197   319   319 V AudioFlinger: purging stale effects
09-08 13:34:29.197   319   319 V AudioPolicyService: AudioCommandThread() adding release output 2
09-08 13:34:29.197   319   319 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-08 13:34:29.197   319  1268 V AudioPolicyService: AudioCommandThread() waking up
09-08 13:34:29.197   319  1268 V AudioPolicyService: AudioCommandThread() processing release output 2
09-08 13:34:29.197   319  1268 V AudioPolicyManager: releaseOutput() 2
09-08 13:34:29.197   319  1268 V AudioPolicyService: AudioCommandThread() going to sleep
09-08 13:34:29.199   319   319 V AudioFlinger: PlaybackThread::Track destructor
09-08 13:34:29.199   319   319 V AudioFlinger: removeClient_l() pid 7392, calling pid 319
09-08 13:34:29.206  7392  7392 V AudioManager: registerRemoteController: size of Media player list: 0
,09-08 13:34:29.209  7392  7392 E AudioManager: No RCC entry present to update
09-08 13:34:29.209  7392  7392 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-08 13:34:29.213  7392  7392 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-08 13:34:29.214  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-08 13:34:29.214  7392  7392 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-08 13:34:29.219  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-08 13:34:29.350  1031  2040 V SIM_STK : Menu title from STK is T-Mobile
09-08 13:34:29.350  1031  2040 V SIM_STK : Menu title from STK is T-Mobile
,09-08 13:34:29.432  1031  1898 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-08 13:34:29.438  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-08 13:34:29.442  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 13:34:29.443  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-08 13:34:29.443  7392  7392 I BluetoothA2dpServiceJni: classInitNative
09-08 13:34:29.443  7392  7392 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 13:34:29.444  7392  7392 D A2dpStateMachine: make
,09-08 13:34:29.447  7392  7392 I bluedroid-qcom: get_profile_interface a2dp
09-08 13:34:29.447  7392  7675 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-08 13:34:29.449  7392  7392 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-08 13:34:29.449  7392  7392 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-08 13:34:29.450  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.450  7392  7674 D A2dpStateMachine: Enter Disconnected: -2
09-08 13:34:29.450  7392  7392 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 13:34:29.452  7392  7392 D HidService: Received start request. Starting profile...
09-08 13:34:29.452  7392  7392 I bluedroid-qcom: get_profile_interface hidhost
09-08 13:34:29.452  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.452  7392  7392 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 13:34:29.453  7392  7392 D HealthService: Received start request. Starting profile...
09-08 13:34:29.455  7392  7392 I bluedroid-qcom: get_profile_interface health
09-08 13:34:29.455  7392  7392 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-08 13:34:29.455  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.455  7392  7392 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 13:34:29.456  7392  7392 D PanService: Received start request. Starting profile...
09-08 13:34:29.456  7392  7392 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 13:34:29.456  7392  7392 I bluedroid-qcom: get_profile_interface pan
,09-08 13:34:29.461  7392  7392 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-08 13:34:29.461  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.462  7392  7392 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-08 13:34:29.466  7392  7392 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 13:34:29.466  7392  7392 D BtGatt.GattService: Received start request. Starting profile...
09-08 13:34:29.466  7392  7392 D BtGatt.GattService: start()
09-08 13:34:29.466  7392  7392 I bluedroid-qcom: get_profile_interface gatt
09-08 13:34:29.466  7392  7392 D BtGatt.AdvertiseManager: advertise manager created
09-08 13:34:29.470  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.472  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.472  7392  7392 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-08 13:34:29.473  7392  7392 V BluetoothMapService: BluetoothMapBinder()
,09-08 13:34:29.474  7392  7392 D BluetoothMapService: Received start request. Starting profile...
09-08 13:34:29.474  7392  7392 D BluetoothMapService: start()
09-08 13:34:29.479  7392  7392 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-08 13:34:29.479  7392  7392 D BluetoothMapEmailAppObserver: createReceiver()
09-08 13:34:29.480  7392  7392 D BluetoothMapEmailAppObserver: initObservers()
09-08 13:34:29.480  7392  7392 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-08 13:34:29.485  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:29.485  7392  7392 D HeadsetStateMachine: Proxy object connected
09-08 13:34:29.485  7392  7392 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,09-08 13:34:29.485  7392  7392 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-08 13:34:29.488  7392  7392 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 13:34:29.489  7392  7655 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-08 13:34:29.489  7392  7655 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 13:34:29.489  7392  7655 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-08 13:34:29.492  7392  7392 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 13:34:29.493  7392  7392 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:29.495  7392  7392 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 13:34:29.497  7392  7392 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 13:34:29.497  7392  7392 V PanService: [BTUI] SIM Extra State :ABSENT
,09-08 13:34:29.502  7392  7392 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-08 13:34:29.504  7392  7392 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-08 13:34:29.504  7392  7392 V BluetoothMapService: Handler(): got msg=1
09-08 13:34:29.507  7392  7392 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 13:34:29.507  7392  7647 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-08 13:34:29.507  7392  7392 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 13:34:29.507  7392  7392 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 13:34:29.507  7392  7647 I bluedroid-qcom: enable
09-08 13:34:29.507  7392  7392 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:29.507  7392  7392 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-08 13:34:29.507  7392  7683 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-08 13:34:29.507  7392  7683 I bt-btu  : btu_task pending for preload complete event
09-08 13:34:29.507  7392  7647 I bt_hci_bdroid: init
09-08 13:34:29.508  7392  7647 I bt_vendor: bt-vendor : init
09-08 13:34:29.508  7392  7647 I bt_vendor: bt-vendor : get_bt_soc_type
09-08 13:34:29.508  7392  7647 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-08 13:34:29.508  7392  7647 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-08 13:34:29.508  7392  7647 D bt_userial_mct: userial_init
09-08 13:34:29.509  7392  7647 D bt_hci_bdroid: set_power 1
09-08 13:34:29.509  7392  7647 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-08 13:34:29.509  7392  7647 I bt_vendor: Starting hciattach daemon
09-08 13:34:29.509  7392  7647 I bt_vendor: try to set true
09-08 13:34:29.501  7686  7686 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:29.501  7686  7686 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:29.524  1031  2006 I art     : Explicit concurrent mark sweep GC freed 24414(1272KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.169ms total 138.522ms
,09-08 13:34:29.542  7687  7687 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-08 13:34:29.627  7693  7693 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-08 13:34:29.652  7694  7694 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-08 13:34:29.703  7696  7696 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-08 13:34:29.719  7697  7697 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-08 13:34:29.737  7698  7698 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-08 13:34:29.762  7699  7699 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-08 13:34:29.792  7701  7701 I libmdmdetect: ESOC framework not supported
09-08 13:34:29.793  7701  7701 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-08 13:34:29.803  7701  7701 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-08 13:34:29.803  7701  7701 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-08 13:34:29.803  7701  7701 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-08 13:34:29.803  7701  7701 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-08 13:34:29.803  7701  7701 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-08 13:34:29.803  7701  7701 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-08 13:34:29.803  7701  7701 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-08 13:34:29.843  7701  7705 E QC-QMI  : qmi_client [7701] 14: failed to locate client data
09-08 13:34:29.844   460   460 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-08 13:34:29.844   460   460 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-08 13:34:29.897  7709  7709 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-08 13:34:29.921  7710  7710 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-08 13:34:29.961  7392  7647 I bt_vendor: bluetooth satus is on
,09-08 13:34:29.961  7392  7647 D bt_hci_bdroid: preload
09-08 13:34:29.962  7392  7685 D bt_userial_mct: userial_open(port:0)
09-08 13:34:29.962  7392  7685 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-08 13:34:29.966  7392  7685 I bt_vendor: Done intiailizing UART
,09-08 13:34:29.967  7392  7685 I bt_vendor: Done intiailizing UART
09-08 13:34:29.967  7392  7685 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-08 13:34:29.967  7392  7685 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-08 13:34:29.967  7392  7712 D bt_userial_mct: Entering userial_read_thread()
09-08 13:34:29.967  7392  7683 I bt-btu  : btu_task received preload complete event
,09-08 13:34:29.968  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-08 13:34:29.968  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-08 13:34:29.970  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-08 13:34:29.973  7392  7683 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 13:34:29.974  7392  7683 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 13:34:30.047  7392  7683 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-08 13:34:30.047  7392  7683 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0172061 
09-08 13:34:30.047  7392  7683 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0172061 
,09-08 13:34:30.076  7392  7650 E bt-btif : Calling BTA_HhEnable
09-08 13:34:30.076  7392  7650 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-08 13:34:30.076  7392  7650 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-08 13:34:30.079  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-08 13:34:30.079  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,09-08 13:34:30.079  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-08 13:34:30.081  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-08 13:34:30.081  7392  7650 D BluetoothAdapterProperties: Name is: G3
09-08 13:34:30.082  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-08 13:34:30.083  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-08 13:34:30.083  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-08 13:34:30.083  7392  7650 D BluetoothAdapterProperties: Scan Mode:20
09-08 13:34:30.084  7392  7650 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 13:34:30.084  7392  7650 D bt_hci_bdroid: postload
09-08 13:34:30.084  7392  7685 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 13:34:30.085  7392  7683 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-08 13:34:30.085  7392  7650 D bte_conf: Device ID record 1 : primary
09-08 13:34:30.085  7392  7650 D bte_conf:   vendorId            = 00c4
09-08 13:34:30.085  7392  7650 D bte_conf:   vendorIdSource      = 0001
09-08 13:34:30.086  7392  7650 D bte_conf:   product             = 13a1
09-08 13:34:30.086  7392  7650 D bte_conf:   version             = 1000
09-08 13:34:30.086  7392  7650 D bte_conf:   clientExecutableURL = 
09-08 13:34:30.088  7392  7650 D bte_conf:   serviceDescription  = 
09-08 13:34:30.088  7392  7650 D bte_conf:   documentationURL    = 
09-08 13:34:30.088  7392  7650 D bte_conf: bte_load_did_conf no section named DID2.
09-08 13:34:30.089  7392  7685 D bt_hci_bdroid: Used up Tx Cmd credits
,09-08 13:34:30.094  7392  7685 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 13:34:30.099  7392  7685 D bt_hci_bdroid: Used up Tx Cmd credits
09-08 13:34:30.101  7392  7712 E bt_mct  : hci lib postload completed
09-08 13:34:30.091  7714  7714 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:30.091  7714  7714 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:30.104  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:30.104  7392  7650 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 13:34:30.104  7392  7647 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-08 13:34:30.105  7392  7647 D BluetoothAdapterProperties: ScanMode =  20
09-08 13:34:30.105  7392  7647 D BluetoothAdapterProperties: State =  11
,09-08 13:34:30.105  7392  7647 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-08 13:34:30.106  7392  7647 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-08 13:34:30.106  7392  7647 D BluetoothAdapterProperties: Setting state to 12
09-08 13:34:30.106  7392  7647 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 13:34:30.108  7392  7683 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 13:34:30.108  7392  7683 W bt-smp  : Plain text(LSB ~ MSB) = 5f 38 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 13:34:30.108  7392  7683 W bt-smp  : Encrypted text(LSB ~ MSB) = bc d6 cd f5 de 6b 8e 8a 28 dd 6c 2f d5 2b b1 f4 
09-08 13:34:30.109  7392  7683 W bt-btm  : Stopping oneshot timer
09-08 13:34:30.109  1031  1113 D BluetoothManagerService: Message: 60
09-08 13:34:30.109  7392  7650 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 13:34:30.109  1031  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-08 13:34:30.109  1031  1113 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-08 13:34:30.111  6851  6866 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 13:34:30.112  7392  7647 I BluetoothAdapterState: Entering On State
09-08 13:34:30.115  7392  7647 D LGBluetoothServiceAdapter: [BTUI] OnState
09-08 13:34:30.115  7392  7647 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-08 13:34:30.115  7392  7647 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-08 13:34:30.116  7392  7647 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-08 13:34:30.125  7392  7683 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 13:34:30.125  7392  7683 W bt-smp  : Plain text(LSB ~ MSB) = bc 8d 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 13:34:30.125  7392  7683 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 75 2c ad 00 41 39 3b 53 03 bc e0 2f e6 19 cb 
09-08 13:34:30.125  7392  7683 W bt-btm  : Stopping oneshot timer
09-08 13:34:30.129  6851  6867 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 13:34:30.131  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:30.131  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:30.131  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:30.131  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:30.131  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:30.131  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:30.131  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:30.131  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:30.135  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:30.139  7392  7683 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 13:34:30.139  7392  7683 W bt-smp  : Plain text(LSB ~ MSB) = ce 26 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 13:34:30.139  7392  7683 W bt-smp  : Encrypted text(LSB ~ MSB) = 6e 0e 93 41 74 80 81 b9 0e 4e 70 37 fa 42 56 46 
09-08 13:34:30.139  7392  7683 W bt-btm  : Stopping oneshot timer
09-08 13:34:30.141  6851  6866 D BluetoothPan: onBluetoothStateChange on: true
09-08 13:34:30.141  6851  6866 D BluetoothPan: onBluetoothStateChange call bindService
,09-08 13:34:30.141  7392  7650 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 13:34:30.141  7392  7650 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-08 13:34:30.145  6851  6851 D BluetoothMap: Proxy object connected
09-08 13:34:30.145  6851  6851 D MapProfile: Bluetooth service connected
09-08 13:34:30.145  6851  6851 D BluetoothMap: getConnectedDevices()
09-08 13:34:30.146  7392  7654 V BluetoothMapService: getConnectedDevices()
09-08 13:34:30.152  7392  7683 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 13:34:30.152  7392  7683 W bt-smp  : Plain text(LSB ~ MSB) = d7 98 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-08 13:34:30.152  7392  7683 W bt-smp  : Encrypted text(LSB ~ MSB) = 6f 2f 31 e7 90 b7 3c 76 fe 9b 58 32 32 1b a5 bc 
09-08 13:34:30.152  7392  7683 W bt-btm  : Stopping oneshot timer
09-08 13:34:30.159  1031  1113 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 13:34:30.162  6851  6851 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 13:34:30.162  6851  6851 D PanProfile: Bluetooth service connected
09-08 13:34:30.163  7392  7647 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-08 13:34:30.165  1846  1861 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 13:34:30.166  1031  1031 D BluetoothHeadset: Proxy object connected
09-08 13:34:30.169  1846  1846 D BluetoothHeadset: Proxy object connected
09-08 13:34:30.169  1031  1113 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 13:34:30.171  6851  7716 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 13:34:30.173  1846  2461 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 13:34:30.174  1031  1031 D BluetoothA2dp: Proxy object connected
09-08 13:34:30.177  6851  6851 D BluetoothInputDevice: Proxy object connected
09-08 13:34:30.177  6851  6851 D HidProfile: Bluetooth service connected
09-08 13:34:30.178  7392  7683 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-08 13:34:30.178  7392  7683 W bt-smp  : Plain text(LSB ~ MSB) = 33 5a 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-08 13:34:30.178  7392  7683 W bt-smp  : Encrypted text(LSB ~ MSB) = 3c bb 69 a6 42 25 de 14 9c 60 9e 28 9d 57 c3 11 
09-08 13:34:30.178  7392  7683 W bt-btm  : Stopping oneshot timer
09-08 13:34:30.179  1846  1846 D BluetoothHeadset: Proxy object connected
09-08 13:34:30.180  1846  3509 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 13:34:30.182  1846  1846 D BluetoothHeadset: Proxy object connected
09-08 13:34:30.182  1031  1113 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-08 13:34:30.183  1031  1113 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-08 13:34:30.183  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,09-08 13:34:30.186  1031  1113 D BluetoothManagerService: Message: 40
09-08 13:34:30.186  1031  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-08 13:34:30.186  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:30.187  1935  2121 D LGBluetoothAPIService: Message: 1
09-08 13:34:30.187  1935  2121 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-08 13:34:30.190  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-08 13:34:30.195  7731  7731 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-08 13:34:30.202  1935  2121 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-08 13:34:30.203  6851  6851 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 13:34:30.204  7392  7392 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:30.204  7392  7392 D BluetoothMapService: STATE_ON
09-08 13:34:30.206  7392  7392 D LGBluetoothAPIServer: [BTUI] onCreate()
09-08 13:34:30.206  6595  6595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 13:34:30.206  7392  7392 D LGBluetoothAPIServer: [BTUI] onBind()
09-08 13:34:30.206  1031  1113 D BluetoothManagerService: Message: 30
09-08 13:34:30.208  1935  1935 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-08 13:34:30.208  1935  2121 D LGBluetoothAPIService: Message: 100
09-08 13:34:30.208  1935  2121 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-08 13:34:30.213  6851  6851 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-08 13:34:30.213  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:30.213  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:30.213  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:30.213  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:30.213  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:30.213  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:30.213  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:30.213  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:30.216  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:30.217  1031  1113 D BluetoothManagerService: Message: 30
09-08 13:34:30.222  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:30.224  6851  6851 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-08 13:34:30.226  6851  6851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 13:34:30.227  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:30.227  7392  7392 V BluetoothPbapService: Pbap Service onCreate
09-08 13:34:30.227  7392  7392 V BluetoothPbapService: Starting PBAP service
09-08 13:34:30.228  6851  6851 D BluetoothA2dp: Proxy object connected
09-08 13:34:30.229  7392  7392 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-08 13:34:30.229  6851  6851 D A2dpProfile: Bluetooth service connected
09-08 13:34:30.229  7392  7392 V BluetoothPbapService: Pbap Service onBind
09-08 13:34:30.230  7392  7392 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:30.230  7392  7392 V BluetoothPbapService: state: 12
09-08 13:34:30.231  7392  7392 V BluetoothMapService: Handler(): got msg=1
09-08 13:34:30.231  7392  7392 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-08 13:34:30.231  6851  6851 D BluetoothHeadset: Proxy object connected
09-08 13:34:30.231  7392  7392 V BluetoothPbapService: Handler(): got msg=1
09-08 13:34:30.232  7392  7392 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-08 13:34:30.232  6851  6851 D HeadsetProfile: Bluetooth service connected
09-08 13:34:30.233  7392  7733 D BluetoothMapMasInstance: MAS initSocket()
09-08 13:34:30.233  7392  7392 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 13:34:30.233  7392  7392 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:30.233  7392  7392 V BluetoothPbapReceiver: ***********state = 12
09-08 13:34:30.233  7392  7733 D BluetoothMapMasInstance:   masId = 00
09-08 13:34:30.233  7392  7733 D BluetoothMapMasInstance:   msgTypes = 0e
09-08 13:34:30.233  7392  7733 D BluetoothMapMasInstance:   masName = SMS/MMS
09-08 13:34:30.233  7392  7733 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-08 13:34:30.233  7392  7734 V BluetoothPbapService: Pbap Service initSocket
,09-08 13:34:30.237  1031  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:30.237  1031  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:30.238  7392  7734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:30.237  2177  2177 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 13:34:30.240  2177  2177 D c       : Getting all permits...
09-08 13:34:30.240  2177  2177 D a       : Opening database...
09-08 13:34:30.240  6851  6851 D DockEventReceiver: finishStartingService: stopping service
09-08 13:34:30.240  7392  7733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:30.241  7392  7734 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-08 13:34:30.241  7392  7733 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-08 13:34:30.241  7392  7734 V BluetoothPbapService: Succeed to create listening socket 
09-08 13:34:30.241  7392  7733 V BluetoothMapMasInstance: Succeed to create listening socket 
09-08 13:34:30.241  7392  7734 V BluetoothPbapService: Accepting socket connection...
09-08 13:34:30.241  7392  7733 D BluetoothMapMasInstance: Accepting socket connection...
09-08 13:34:30.242  7392  7650 D BluetoothAdapterProperties: Scan Mode:21
09-08 13:34:30.242  7392  7650 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-08 13:34:30.243  6851  6851 D BluetoothPbap: Proxy object connected
09-08 13:34:30.244  6851  6851 D PbapServerProfile: Bluetooth service connected
09-08 13:34:30.245  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:30.246  2177  2177 D a       : Opening database auth.proximity.permit_store...
09-08 13:34:30.247  2177  2177 D a       : Closing database...
09-08 13:34:30.249  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:30.257  6851  6851 D BluetoothPermissionRequest: onReceive
,09-08 13:34:30.260  6851  6851 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-08 13:34:30.261  6851  6851 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-08 13:34:30.264  7392  7392 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-08 13:34:30.265  7392  7392 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-08 13:34:30.271  7392  7392 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-08 13:34:30.307  7392  7392 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 13:34:30.307  7392  7392 V BtOppService: onCreate
,09-08 13:34:30.313  7392  7392 V BluetoothOppNotification: send message
09-08 13:34:30.317  7392  7392 V BtOppService: Starting RfcommListener
09-08 13:34:30.331  7392  7739 V BtOppService: Deleted complete outbound shares, number =  0
,09-08 13:34:30.332  7392  7392 D BluetoothOppPreference: Dumping Names:  
09-08 13:34:30.332  7392  7392 D BluetoothOppPreference: {}
09-08 13:34:30.332  7392  7392 D BluetoothOppPreference: Dumping Channels:  
09-08 13:34:30.332  7392  7392 D BluetoothOppPreference: {}
09-08 13:34:30.333  7392  7392 V BtOppService: onStartCommand
09-08 13:34:30.335  7392  7739 V BtOppService: Deleted complete inbound failed shares, number = 0
,09-08 13:34:30.337  7392  7392 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:30.338  7392  7742 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 13:34:30.338  7392  7392 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-08 13:34:30.340  7392  7742 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 13:34:30.340  7392  7739 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-08 13:34:30.342  7392  7392 V BluetoothOppNotification: new notify threadi!
09-08 13:34:30.343  7392  7392 V BluetoothOppNotification: send delay message
09-08 13:34:30.343  7392  7739 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@164a1982 on behalf of 
09-08 13:34:30.345  7392  7392 V BtOppService: start RfcommListener
,09-08 13:34:30.348  7392  7742 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ddea893 on behalf of 
09-08 13:34:30.349  7392  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-08 13:34:30.349  7392  7392 V BtOppService: RfcommListener started
09-08 13:34:30.350  7392  7392 V BtOppService: ContentObserver received notification
09-08 13:34:30.350  7392  7392 V BtOppService: ContentObserver received notification
09-08 13:34:30.357  7392  7744 V BtOppRfcommListener: Starting RFCOMM listener....
,09-08 13:34:30.358  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:30.360  7392  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33dcc0d0 on behalf of 
,09-08 13:34:30.361  7392  7742 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-08 13:34:30.361  7392  7742 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-08 13:34:30.361  7392  7744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:30.363  7392  7744 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-08 13:34:30.363  7392  7744 V BtOppRfcommListener: Started RFCOMM listener....
09-08 13:34:30.363  7392  7744 I BtOppRfcommListener: Accept thread started.
09-08 13:34:30.363  7392  7744 V BtOppRfcommListener: Accepting connection...
09-08 13:34:30.364  7392  7743 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-08 13:34:30.365  7392  7742 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@89da8c9 on behalf of 
09-08 13:34:30.365  7392  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-08 13:34:30.366  7392  7742 V BluetoothOppNotification: update too frequent, put in queue
09-08 13:34:30.367  7392  7742 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-08 13:34:30.367  7392  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9044bce on behalf of 
09-08 13:34:30.369  7392  7743 V BluetoothOppNotification: outbound: succ-0  fail-0
09-08 13:34:30.370  7392  7743 V BluetoothOppNotification: outbound notification was removed.
09-08 13:34:30.370  7392  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-08 13:34:30.372  7392  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15413aef on behalf of 
09-08 13:34:30.373  7392  7743 V BluetoothOppNotification: inbound: succ-0  fail-0
09-08 13:34:30.375  7392  7743 V BluetoothOppNotification: inbound notification was removed.
09-08 13:34:30.375  7392  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-08 13:34:30.377  7392  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@309519fc on behalf of 
09-08 13:34:30.383  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:30.383  7392  7392 V BluetoothFtpService: Ftp Service onCreate
09-08 13:34:30.383  7392  7392 I BluetoothFtpService: Ftp Service onCreate
09-08 13:34:30.383  7392  7392 V BluetoothFtpService: Ftp Service onStartCommand
09-08 13:34:30.383  7392  7392 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:30.383  7392  7392 V BluetoothFtpService: Starting Listening on sockets
09-08 13:34:30.384  7392  7392 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 13:34:30.384  7392  7392 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-08 13:34:30.384  7392  7392 V BluetoothSapReceiver: SapReceiver onReceive 
09-08 13:34:30.384  7392  7392 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:30.384  7392  7392 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-08 13:34:30.384  7392  7392 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-08 13:34:30.386  7392  7392 V BluetoothFtpService: Handler(): got msg=1
,09-08 13:34:30.389  7392  7392 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-08 13:34:30.389  7392  7392 V BluetoothFtpService: Ftp Service initSocket
09-08 13:34:30.391  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:30.392  7392  7392 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:30.395  7392  7392 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-08 13:34:30.396  7392  7392 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-08 13:34:30.397  7392  7745 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-08 13:34:30.411  7392  7392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@310a5241
09-08 13:34:30.412  7392  7392 V BluetoothSapService: Sap Service onCreate
,09-08 13:34:30.414  7392  7392 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 13:34:30.414  7392  7392 V BluetoothSapService: state: 12
09-08 13:34:30.414  7392  7392 V BluetoothSapService: Starting SAP server process
09-08 13:34:30.401  7747  7747 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:30.416  7392  7392 V BluetoothSapService: SAP Service startRfcommListenerThread
09-08 13:34:30.401  7747  7747 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:30.418  7392  7748 V BluetoothSapService: Sap Service initRfcommSocket
09-08 13:34:30.419  1031  1570 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:30.420  7392  7748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:30.421  7392  7748 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-08 13:34:30.421  7392  7748 V BluetoothSapService: Succeed to create listening socket 
09-08 13:34:30.421  7392  7748 V BluetoothSapService: Accepting socket connection...
09-08 13:34:30.433  7747  7747 V BT_SAP  : Event pipe created
09-08 13:34:30.433  7747  7747 V BT_SAP  : create_server_socket qcom.sap.server
09-08 13:34:30.433  7747  7747 V BT_SAP  : created socket fd 6
,09-08 13:34:31.346  7392  7392 V BluetoothOppNotification: new notify threadi!
,09-08 13:34:31.347  7392  7392 V BluetoothOppNotification: send delay message
,09-08 13:34:31.360  7392  7758 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-08 13:34:31.366  7392  7758 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bfca801 on behalf of 
09-08 13:34:31.371  7392  7758 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-08 13:34:31.374  7392  7758 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-08 13:34:31.375  7392  7758 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@378a06a6 on behalf of 
09-08 13:34:31.376  7392  7758 V BluetoothOppNotification: outbound: succ-0  fail-0
09-08 13:34:31.377  7392  7758 V BluetoothOppNotification: outbound notification was removed.
09-08 13:34:31.377  7392  7758 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-08 13:34:31.378  7392  7758 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e2f98e7 on behalf of 
09-08 13:34:31.379  7392  7758 V BluetoothOppNotification: inbound: succ-0  fail-0
09-08 13:34:31.382  7392  7758 V BluetoothOppNotification: inbound notification was removed.
09-08 13:34:31.382  7392  7758 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-08 13:34:31.383  7392  7758 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2484ac94 on behalf of 
,09-08 13:34:31.752  1031  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=38.4, 0.0, 0.0  rx=37.5 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:160689224] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:31.765  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=38.4, 0.0, 0.0  rx=37.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:160689237] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:31.765  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 13:34:32.040  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:32.040  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:32.041  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:32.041  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:32.041  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:32.041  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@260a965d removed from the list
09-08 13:34:32.041  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:32.041  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15408bd2 removed from the list
09-08 13:34:32.041  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:32.042  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:32.056  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:32.056  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e55c3a0 added. We now have 2 listener(s)
09-08 13:34:32.056  1031  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:32.060  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-08 13:34:32.060  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:32.060  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:32.060  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:32.060  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df3b59 added. We now have 2 listener(s)
09-08 13:34:32.060  6595  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:32.061  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:34:32.067  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:32.073  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:32.073  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:32.073  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:32.073  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:32.073  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:32.073  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:32.073  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:32.073  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:32.077  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:32.077  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:32.079  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:32.083  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:32.085  1031  1898 D WifiServiceImplEx: setWifiEnabled: false pid=6595, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-08 13:34:32.085  1031  1898 D WifiService: setWifiEnabled: false pid=6595, uid=10118
09-08 13:34:32.085  1031  1898 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 13:34:32.101  1031  1533 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:32.101  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:32.102  1031  1533 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:32.102  1031  1533 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:32.102  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-08 13:34:32.103  1031  1533 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 13:34:32.103  1031  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 13:34:32.103  1031  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-08 13:34:32.108  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 13:34:32.108  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 13:34:32.108  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-08 13:34:32.109  1031  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 13:34:32.109  1031  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 13:34:32.117  1031  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 13:34:32.117  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 13:34:32.117  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-08 13:34:32.120  1031  1532 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.120  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.121  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 13:34:32.121  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 13:34:32.122  1031  1533 D WifiNative-wlan0: SET ps 1: returned true
09-08 13:34:32.122   315   904 D CommandListener: Clearing all IP addresses on wlan0
09-08 13:34:32.130  1031  7124 D DhcpStateMachine: RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 13:34:32.196  1031  1897 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-08 13:34:32.196  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.196  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.196  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 13:34:32.197  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.197  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-08 13:34:32.211  1031  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 13:34:32.211  1031  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-08 13:34:32.219  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-08 13:34:32.222  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:32.222  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:32.223  1935  1935 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-08 13:34:32.228  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:32.228  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:32.228  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 13:34:32.231  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.231  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:32.235  1031  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.236  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.236  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.237  1031  1532 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.237  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.237  1031  1532 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@18fb10e1
09-08 13:34:32.239  1031  1031 D WifiHS20: hidePasspointNotification off =false
,09-08 13:34:32.241  1031  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.241  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.242  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.242  1031  1533 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 13:34:32.242  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:32.242  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:32.242  1031  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.242  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 13:34:32.242  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 13:34:32.242  1031  1031 D RttService: SCAN_AVAILABLE : 1
09-08 13:34:32.242  1031  1551 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.243  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.243  1031  1552 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.243  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:32.249  1031  1532 D LGWifiP2pService: P2pDisablingState
09-08 13:34:32.249  1031  1532 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.249  1031  1532 D LGWifiP2pService: p2p socket connection lost
09-08 13:34:32.249  1031  1532 D LGWifiP2pService: P2pDisabledState
09-08 13:34:32.249  6831  6831 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 13:34:32.249  6831  6831 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 13:34:32.250  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:32.254  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-08 13:34:32.254  1935  1935 D WfdsService: WifiP2pState is changed : false
09-08 13:34:32.254  1935  2281 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-08 13:34:32.254  1935  2281 D WfdsService: Set the WFDS Monitor: false
,09-08 13:34:32.255  1935  2281 D WfdsMonitor: WFDS Monitor is stopped
09-08 13:34:32.255  1935  2281 D WfdsService: STATE : WfdsDisabledState - enter
09-08 13:34:32.255  1935  2290 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-08 13:34:32.256  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:32.256  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:32.257  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.258  1935  7065 D CtrlSupplicant: Received on exit socket, terminate
09-08 13:34:32.258  1935  7065 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed,
09-08 13:34:32.258  1935  7065 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-08 13:34:32.259  1935  7065 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-08 13:34:32.259  1935  2281 W WfdsService: DefaultState - msg [9445378] is not handled
09-08 13:34:32.260  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 13:34:32.264  1031  1533 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-08 13:34:32.264  1031  1532 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.264  1031  1532 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.264  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 13:34:32.264  7010  7010 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 13:34:32.265  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 13:34:32.265  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 13:34:32.265  1031  1533 D WifiNative-wlan0: SET ps 1: returned true
,09-08 13:34:32.267  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:32.272   315   904 D CommandListener: Clearing all IP addresses on wlan0
09-08 13:34:32.273   315  7782 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-08 13:34:32.273  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-08 13:34:32.274  1031  1539 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-08 13:34:32.274  1031  1539 D DSQN    : disableDataServiceNotify
09-08 13:34:32.274  1031  1539 D DSQN    : stop dsqn bin
09-08 13:34:32.275  1031  1111 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 13:34:32.277  1031  1533 D WifiNative-p2p0: doBoolean: TERMINATE
09-08 13:34:32.277  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:32.277  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:32.278  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-08 13:34:32.279  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 13:34:32.280  1031  1539 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-08 13:34:32.280  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 13:34:32.280  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:32.281  1031  1539 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:32.281  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:32.281  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 13:34:32.281  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:32.281  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:32.281  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 13:34:32.281  1031  1539 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-08 13:34:32.281  1031  1533 D WifiNative-p2p0: TERMINATE: returned true
09-08 13:34:32.281  1031  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 13:34:32.281  1031  1533 E WifiStateMachine: useWiFiOffloading() : false
09-08 13:34:32.281  1031  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 13:34:32.281  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.281  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:32.281  1031  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 13:34:32.282  1031  1539 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-08 13:34:32.282  1031  1539 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 13:34:32.282  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 13:34:32.282  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 13:34:32.283  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.284  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:32.285  1031  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:32.285  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 13:34:32.286  1031  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:32.286  1031  1539 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: I,NTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:32.286  1031  1531 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 13:34:32.286  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 13:34:32.286  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 13:34:32.286  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 13:34:32.286  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 13:34:32.286  1031  1539 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:32.287  1031  1531 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 13:34:32.287  1846  1846 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:32.287  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 13:34:32.287  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 13:34:32.288  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 13:34:32.288  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 13:34:32.288  1031  1539 D NetworkManagementService: Removing idletimer
09-08 13:34:32.288  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 13:34:32.288  1031  1539 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:32.288  1031  1539 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 13:34:32.290  6831  6831 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 13:34:32.290  6831  6831 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 13:34:32.290  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:32.291  1031  1533 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:32.291  1031  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:32.293  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-08 13:34:32.293  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,09-08 13:34:32.298  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 13:34:32.301  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-08 13:34:32.301  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-08 13:34:32.304  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:32.304  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:32.304  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:32.304  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 13:34:32.304  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:32.304  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:32.304  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:32.304  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:32.306  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:32.309  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:32.310  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:32.310  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:32.310  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:32.310  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 13:34:32.310  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:32.310  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:32.310  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:32.310  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:32.311  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 13:34:32.315  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:32.316  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:32.318  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 13:34:32.321  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:32.325  6831  6831 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 13:34:32.325  6831  6831 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 13:34:32.325  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:32.329  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:32.333  7010  7010 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-08 13:34:32.333  7010  7010 I wpa_supplicant: monitor socket send errors count : 1
09-08 13:34:32.333  7010  7010 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1935-4\x00 that cannot receive messages
09-08 13:34:32.334  1031  7044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-08 13:34:32.334  1031  7044 D WifiMonitor: Dropping event because (p2p0) is stopped
09-08 13:34:32.334  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:32.345  6869  6869 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:32.345  6869  6869 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:32.346  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 13:34:32.346  6869  6869 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 13:34:32.347  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.349  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.354  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:32.357  7010  7010 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 13:34:32.358  7010  7010 W wpa_supplicant: USIM:  scard_deinit function
09-08 13:34:32.358  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-08 13:34:32.358  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 13:34:32.358  1031  7044 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 13:34:32.358  1031  7044 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-08 13:34:32.358  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:32.358  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:32.359  1031  1533 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=137386
09-08 13:34:32.359  1031  1533 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=137387
,09-08 13:34:32.360  1031  1533 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=137387  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 13:34:32.360  1031  1533 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=137388  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-08 13:34:32.361  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 13:34:32.361  1031  1113 D Tethering: InitialState.processMessage what=4
09-08 13:34:32.362  1031  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 13:34:32.363  1031  1533 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:32.364  1031  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:32.366  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:32.372  6892  7786 W FormManager: Network not available. Please check & try again.
,09-08 13:34:32.376  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 13:34:32.377  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.377  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.377  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.381  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 13:34:32.381  6851  6851 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 13:34:32.381  6851  6851 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 13:34:32.381  6851  6851 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 13:34:32.383  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-08 13:34:32.383  6892  7787 V FormManager: Network unavailable.
09-08 13:34:32.383  6851  6851 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 13:34:32.383  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 13:34:32.383  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 13:34:32.383  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 13:34:32.383  6851  6851 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 13:34:32.383  6851  6851 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 13:34:32.387  6892  7787 V FormManager: Network unavailable.
09-08 13:34:32.411  7010  7010 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-08 13:34:32.411  1031  7044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-08 13:34:32.411  1031  7044 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-TERMINATING 
09-08 13:34:32.411  1031  7044 D WifiMonitor: Disconnecting from the supplicant, no more events
09-08 13:34:32.412  1031  1533 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 41 0
,09-08 13:34:32.433  1031  7124 D DhcpStateMachine: StoppedState
09-08 13:34:32.433  1031  7124 D DhcpStateMachine: StoppedState{ when=-168ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 13:34:32.515  1031  1533 D WifiOffDelayIfNotUsed: stopMonitoring
,09-08 13:34:32.515  1031  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 13:34:32.515  1031  1533 E WifiStateMachine: useWiFiOffloading() : false
09-08 13:34:32.515  1031  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 13:34:32.519  1935  1935 D WfdsService: Supplicant Connection state is changed : false
09-08 13:34:32.519  1935  2281 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-08 13:34:32.519  1935  2281 D WfdsService: Set the WFDS Monitor: false
09-08 13:34:32.519  1935  2281 D WfdsMonitor: WFDS Monitor is stopped
09-08 13:34:32.521  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,09-08 13:34:32.523  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:32.528  2449  2449 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:32.532  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:32.534  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-08 13:34:32.534  1031  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-08 13:34:32.534  1031  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-08 13:34:32.535  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:32.536  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 13:34:32.537  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:32.542  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:32.545  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:32.552  4291  7788 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 13:34:32.555  4291  7789 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 13:34:32.555  4291  7789 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 13:34:32.563  6831  6831 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-08 13:34:32.563  6831  6831 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 13:34:32.563  6831  6831 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:32.569  6892  7791 W FormManager: Network not available. Please check & try again.
,09-08 13:34:32.573  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 13:34:32.576  6892  7792 V FormManager: Network unavailable.
09-08 13:34:32.580  6892  7792 V FormManager: Network unavailable.
09-08 13:34:32.580  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:32.719  1031  1533 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
,09-08 13:34:32.720  1031  1533 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-08 13:34:32.877  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-08 13:34:32.906  1031  1424 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 13:34:32.912  1597  1597 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-08 13:34:32.929  1031  1031 D administrator: Handling package changes for user 0
,09-08 13:34:32.978  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 13:34:32.991  1031  1109 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7809 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-08 13:34:32.994  1597  1597 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-08 13:34:32.996  1597  1597 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-08 13:34:33.051  7809  7809 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 13:34:33.064  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-08 13:34:33.064  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-08 13:34:33.112  1031  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 13:34:33.116  1031  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-08 13:34:33.122  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-08 13:34:33.123  2449  2449 V GmsNetworkLocationProvi: DISABLE
09-08 13:34:33.156  1031  1108 D LocationProviderProxy: applying state to connected service
,09-08 13:34:33.158  7809  7809 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:33.158  7809  7809 D LgDataFeature: LgDataFeature() Constructor Done, null
09-08 13:34:33.166  2449  2449 E GCoreFlp: Bound FusedProviderService with LocationManager
09-08 13:34:33.190  7525  7561 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-08 13:34:33.250  7809  7840 I Babel   : MmsConfig: mnc/mcc: 0/0
09-08 13:34:33.250  7809  7840 I Babel   : MmsConfig.loadMmsSettings
,09-08 13:34:33.263  7809  7840 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-08 13:34:33.263  7809  7840 I Babel   : MmsConfig.loadFromDatabase
,09-08 13:34:33.289  7809  7840 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-08 13:34:33.289  7809  7840 I Babel   : MmsConfig.loadFromResources
09-08 13:34:33.291  7809  7840 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-08 13:34:33.292  7809  7840 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-08 13:34:33.301  7809  7809 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 13:34:33.312  7809  7838 W AudioCapabilities: Unsupported mime audio/evrc
,09-08 13:34:33.314  7809  7838 W AudioCapabilities: Unsupported mime audio/qcelp
,09-08 13:34:33.315  7809  7838 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 13:34:33.329  1811  7841 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-08 13:34:33.329  1811  7841 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-08 13:34:33.340  7365  7365 I AppUp4:CustModeStarterReceiver: onReceive
09-08 13:34:33.340  7809  7838 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-08 13:34:33.344  7365  7365 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f3d274b
09-08 13:34:33.344  7365  7365 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 13:34:33.344  7365  7365 D AppUp4:CustFacade: isPhone : true
09-08 13:34:33.344  7809  7838 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 13:34:33.346  7365  7365 D AppUp4:CustModeStarterReceiver: begin check event
09-08 13:34:33.346  7365  7365 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-08 13:34:33.348  7809  7838 W AudioCapabilities: Unsupported mime audio/evrc
09-08 13:34:33.350  1811  4647 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-08 13:34:33.378  7809  7838 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-08 13:34:33.380  7809  7838 W VideoCapabilities: Unsupported mime video/divx
09-08 13:34:33.382  7809  7838 W VideoCapabilities: Unsupported mime video/divx311
09-08 13:34:33.384  7809  7838 W VideoCapabilities: Unsupported mime video/divx4
09-08 13:34:33.388  1031  1607 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7845 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-08 13:34:33.392  1031  1570 I ActivityManager: Killing 7417:com.lge.email/u0a23 (adj 15): empty #17
,09-08 13:34:33.394  7809  7838 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-08 13:34:33.407  7809  7838 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 13:34:33.411  7809  7838 W AudioCapabilities: Unsupported mime audio/eac3
,09-08 13:34:33.412  7809  7838 W AudioCapabilities: Unsupported mime audio/ac3
09-08 13:34:33.413  7809  7838 W AudioCapabilities: Unsupported mime audio/g726
09-08 13:34:33.414  7809  7838 W AudioCapabilities: Unsupported mime audio/wma-voice
09-08 13:34:33.415  7809  7838 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 13:34:33.415  7809  7838 W AudioCapabilities: Unsupported mime audio/adpcm
09-08 13:34:33.417  7809  7838 W VideoCapabilities: Unsupported mime video/theora
09-08 13:34:33.418  7809  7838 W VideoCapabilities: Unsupported mime video/mjpg
09-08 13:34:33.481  1031  1933 W libprocessgroup: failed to open /acct/uid_10023/pid_7417/cgroup.procs: No such file or directory
,09-08 13:34:33.518  7845  7845 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 13:34:33.519  7845  7845 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 13:34:33.520  7845  7845 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-08 13:34:33.522  7845  7845 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-08 13:34:33.522  7845  7845 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 13:34:33.604  7845  7845 I SystemConfig: BUILD Country: EU
09-08 13:34:33.604  7845  7845 I SystemConfig: BUILD Operator: OPEN
,09-08 13:34:33.651  1031  1970 I ActivityManager: Killing 7026:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-08 13:34:33.807  1031  2040 W libprocessgroup: failed to open /acct/uid_10046/pid_7026/cgroup.procs: No such file or directory
,09-08 13:34:33.827  7845  7864 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,09-08 13:34:33.827  7845  7864 I SystemConfig: existFile = false
,09-08 13:34:33.827  7845  7864 I SystemConfig: canReadFile = false
09-08 13:34:33.827  7845  7864 I SystemConfig: systemFeature RCS result false
09-08 13:34:33.828  7845  7864 D SystemConfig: refreshRcsSupport() :false
,09-08 13:34:33.864  1031  1970 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7869 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-08 13:34:33.933  7869  7869 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 13:34:33.933  7869  7869 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 13:34:33.933  7869  7869 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-08 13:34:33.934  7869  7869 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-08 13:34:34.031  7869  7869 I AppConfig: Total System Memory = 2995761152
,09-08 13:34:34.043  7869  7869 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-08 13:34:34.131  1031  1934 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7889 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 13:34:34.133  1031  1934 I ActivityManager: Killing 7460:com.android.chrome/u0a57 (adj 15): empty #17
,09-08 13:34:34.231  1031  1971 W libprocessgroup: failed to open /acct/uid_10057/pid_7460/cgroup.procs: No such file or directory
,09-08 13:34:34.319  1031  1607 I ActivityManager: Killing 7483:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-08 13:34:34.352  1031  2045 W libprocessgroup: failed to open /acct/uid_10062/pid_7483/cgroup.procs: No such file or directory
,09-08 13:34:34.465  7889  7889 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-08 13:34:34.569  7889  7889 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:34.569  7889  7889 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:34.633  7889  7889 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-08 13:34:34.654  7889  7889 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-08 13:34:34.656  7889  7889 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-08 13:34:34.681  7889  7889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-08 13:34:34.682  7889  7889 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-08 13:34:34.711  1031  1970 I ActivityManager: Killing 7504:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-08 13:34:34.783  1031  2045 W libprocessgroup: failed to open /acct/uid_10085/pid_7504/cgroup.procs: No such file or directory
,09-08 13:34:34.785  1031  1533 E WifiStateMachine:  InitialState CMD_RSSI_POLL 5 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:160692257] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:34.787  1031  1533 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 5 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:160692259] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:34.804  4581  7930 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-08 13:34:34.822  3431  3447 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-08 13:34:34.831  3431  3447 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@164a1982 on behalf of 7889
09-08 13:34:34.847  1031  1897 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7931 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:34.872   395   395 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 498us total 26.279ms
,09-08 13:34:34.908   395   395 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 34.231ms
,09-08 13:34:34.929   395   395 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.186ms
,09-08 13:34:34.943  7889  7889 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-08 13:34:34.966  7931  7931 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-08 13:34:34.973  7889  7889 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-08 13:34:34.990  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-08 13:34:34.990  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-08 13:34:34.990  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-08 13:34:34.990  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-08 13:34:34.990  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,09-08 13:34:34.990  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-08 13:34:35.015  1031  1047 I ActivityManager: Killing 7525:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-08 13:34:35.072  1031  1607 W libprocessgroup: failed to open /acct/uid_10093/pid_7525/cgroup.procs: No such file or directory
,09-08 13:34:35.119  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:35.122  1031  1933 D WifiServiceImplEx: setWifiEnabled: true pid=6595, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-08 13:34:35.124  1031  1933 D WifiService: setWifiEnabled: true pid=6595, uid=10118
09-08 13:34:35.124  1031  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 13:34:35.146  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-08 13:34:35.147  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 13:34:35.147  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-08 13:34:35.149  1031  1533 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-08 13:34:35.149  1031  1533 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-08 13:34:35.151  1031  1533 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-08 13:34:35.151  1031  1533 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 13:34:35.151  1031  1533 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-08 13:34:35.151  1031  1533 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-08 13:34:35.152  1031  1533 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-08 13:34:35.152  1031  1533 E WifiHW  : unknown target_country: EU , set to default
09-08 13:34:35.152  1031  1533 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-08 13:34:35.152  1031  1533 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-08 13:34:35.152  1031  1533 I WifiUtil: gEnableBmps=1
09-08 13:34:35.289  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:35.291  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:35.294  1031  1113 D Tethering: MasterInitialState.processMessage what=3
09-08 13:34:35.295  1031  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:35.306  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:35.308  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:35.311  1031  1113 D Tethering: MasterInitialState.processMessage what=3
,09-08 13:34:35.321  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:35.323  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:35.324  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-08 13:34:35.328  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-08 13:34:35.329  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-08 13:34:35.331  6400  6439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-08 13:34:35.350  1031  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:35.352  2177  2177 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:35.364  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 13:34:35.364  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:35.364  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 13:34:35.364  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 13:34:35.372  1031  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:35.372  1031  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:35.374  7365  7365 I AppUp4:CustModeStarterReceiver: onReceive
,09-08 13:34:35.379  1031  1779 V SIM_STK : Menu title from STK is T-Mobile
09-08 13:34:35.380  7365  7365 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f3d274b
09-08 13:34:35.380  7365  7365 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 13:34:35.380  7365  7365 D AppUp4:CustFacade: isPhone : true
09-08 13:34:35.380  7365  7365 D AppUp4:CustModeStarterReceiver: begin check event
09-08 13:34:35.381  7365  7365 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 13:34:35.384  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:35.385  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:35.386  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:35.388  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 13:34:35.411  4581  7930 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 607 ms] updated apps [took 607 ms] 
,09-08 13:34:35.551  1031  2006 I art     : Explicit concurrent mark sweep GC freed 62199(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.584ms total 160.406ms
,09-08 13:34:35.561  4291  7984 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 13:34:35.571  4291  7985 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:35.571  4291  7985 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-08 13:34:35.630  1031  1971 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7986 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-08 13:34:35.714  7986  7986 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 13:34:35.714  7986  7986 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 13:34:35.716  7986  7986 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-08 13:34:35.716  7986  7986 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-08 13:34:35.793  7986  7986 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-08 13:34:35.804  7986  7986 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-08 13:34:35.831  7986  7986 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-08 13:34:35.852  7986  7986 D LgDataFeature: LgDataFeature() Constructor: none
,09-08 13:34:35.852  7986  7986 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:35.946  7986  7986 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 13:34:35.987  1031  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 13:34:35.988  1031  1113 D Tethering: InitialState.processMessage what=4
,09-08 13:34:35.992   315   904 D SoftapController: Softap fwReload - Ok
09-08 13:34:35.995  1031  1533 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (838ms)
09-08 13:34:35.998   315   904 D CommandListener: Setting iface cfg
09-08 13:34:35.998   315   904 D CommandListener: Trying to bring down wlan0
09-08 13:34:35.998   315   904 D CommandListener: Clearing all IP addresses on wlan0
,09-08 13:34:36.005  1031  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 13:34:36.007  1031  1533 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-08 13:34:36.001  8020  8020 W wpa_supplicant: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:36.001  8020  8020 W wpa_supplicant: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:36.020  1031  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 13:34:36.020  1031  1533 E WifiStateMachine: useWiFiOffloading() : false
09-08 13:34:36.020  1031  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-08 13:34:36.025  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-08 13:34:36.026  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-08 13:34:36.026  1031  1533 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 13:34:36.026  1031  1533 D WifiMonitor: connecting to supplicant
09-08 13:34:36.042  8020  8020 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 13:34:36.052  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming,
09-08 13:34:36.076  8020  8020 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 13:34:36.082  8020  8020 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-08 13:34:36.082  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:36.084  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:36.095  3323  3323 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 13:34:36.095  3323  3323 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:36.095  3323  3323 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-08 13:34:36.100  7986  7986 I HubEmail: JNI_OnLoad()
09-08 13:34:36.100  7986  7986 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:36.100  7986  7986 I HubEmail: registerNatives()
09-08 13:34:36.100  7986  7986 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:36.100  7986  7986 I HubEmail: registerNativeMethods()
09-08 13:34:36.100  7986  7986 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 13:34:36.100  7986  7986 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-08 13:34:36.142  1031  1897 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8036 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-08 13:34:36.145  6892  8031 W FormManager: Network not available. Please check & try again.
09-08 13:34:36.148  6892  8032 V FormManager: Network unavailable.
09-08 13:34:36.149  7986  8035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.150  6892  8032 V FormManager: Network unavailable.
09-08 13:34:36.158  8020  8020 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 13:34:36.165  1031  2007 I ActivityManager: Killing 7170:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-08 13:34:36.186  8020  8020 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-08 13:34:36.191  8020  8020 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-08 13:34:36.192  1031  1533 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-08 13:34:36.192  1031  1533 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-08 13:34:36.192  1031  1533 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-08 13:34:36.193  1031  1533 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-08 13:34:36.193  1031  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-08 13:34:36.193  1031  8055 D WifiMonitor: Dropping event because (p2p0) is stopped
09-08 13:34:36.193  1031  1533 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:36.193  1031  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:36.193  1031  1533 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-08 13:34:36.193  1031  1533 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-08 13:34:36.194  1031  1533 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-08 13:34:36.194  1031  1533 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-08 13:34:36.194  1031  1533 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-08 13:34:36.211  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 13:34:36.211  8020  8020 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 13:34:36.211  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 13:34:36.211  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-08 13:34:36.211  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-08 13:34:36.212  1031  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-08 13:34:36.212  1031  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-08 13:34:36.218  1031  1898 W libprocessgroup: failed to open /acct/uid_10005/pid_7170/cgroup.procs: No such file or directory
09-08 13:34:36.224  1031  1533 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-08 13:34:36.224  1031  1533 E WifiStateMachine: useWiFiOffloading() : false
09-08 13:34:36.224  1031  1533 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-08 13:34:36.225  1031  1533 D WifiNative-wlan0: doBoolean: SET update_config 1
09-08 13:34:36.225  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.226  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.226  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.226  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.226  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 13:34:36.226  1031  1533 D WifiNative-wlan0: SET update_config 1: returned true
09-08 13:34:36.226  1031  1533 D WifiConfigStore: Loading config and enabling all networks 
09-08 13:34:36.226  1031  1533 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-08 13:34:36.227  1935  1935 D WfdService: Waiting for WifiP2p enabling
09-08 13:34:36.227  1031  1533 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-08 13:34:36.227  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 13:34:36.229  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 13:34:36.231  1031  1537 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 13:34:36.234  1031  1533 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-08 13:34:36.239  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:36.239  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:36.239  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:36.239  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:36.239  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:36.239  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:36.239  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:36.239  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:36.243  1031  1533 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-08 13:34:36.243  1031  1533 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-08 13:34:36.244  1031  1533 D WifiStateMachine: enableVerboseLogging : level 2
09-08 13:34:36.244  1031  1533 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-08 13:34:36.244  1031  1533 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-08 13:34:36.244  1031  1533 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-08 13:34:36.244  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:36.245  1031  1533 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-08 13:34:36.245  1031  1533 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-08 13:34:36.245  1031  1533 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-08 13:34:36.246  1031  1533 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,09-08 13:34:36.246  1031  1533 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-08 13:34:36.246  1031  1533 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-08 13:34:36.246  1031  1533 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-08 13:34:36.246  1031  1533 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-08 13:34:36.247  1031  1533 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-08 13:34:36.247  1031  1533 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-08 13:34:36.248  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:36.248  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:36.248  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:36.248  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:36.248  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:36.248  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:36.248  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:36.248  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:36.248  1031  1533 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-08 13:34:36.250  1935  1935 D WfdsService: Supplicant Connection state is changed : true
09-08 13:34:36.250  7809  7809 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.250  1935  2281 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 13:34:36.250  1935  2281 D WfdsService: Set the WFDS Monitor: true
09-08 13:34:36.250  1935  2281 D WfdsMonitor: WfdsMonitorThread create
09-08 13:34:36.250  1031  1533 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 13:34:36.250  1031  1533 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-08 13:34:36.250  1935  2281 D WfdsMonitor: WFDS Monitor is created and started
09-08 13:34:36.250  1935  2281 D WfdsService: WiFi: Supplicant connection re-established
09-08 13:34:36.251  1031  1533 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-08 13:34:36.251  1031  1533 D WifiNative-HAL: Setting external_sim to 1
09-08 13:34:36.251  1031  1533 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-08 13:34:36.251  1031  1533 D WifiNative-wlan0: SET external_sim 1: returned true
09-08 13:34:36.251  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 13:34:36.251  1031  1533 I WifiNative-HAL: startHal
09-08 13:34:36.251  1031  1533 D wifi    : setting scan oui 0xaf6b5e20
09-08 13:34:36.251  1935  8056 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 13:34:36.252  1031  1533 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 13:34:36.252  1031  1533 I WifiNative-HAL: startHal
09-08 13:34:36.252  1935  8056 E CtrlSupplicant: Succeed to open control connection
09-08 13:34:36.252  1031  1533 D wifi    : setting scan oui 0xaf6b5e20
09-08 13:34:36.252  1031  1533 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-08 13:34:36.252  1935  8056 E CtrlSupplicant: Succeed to open monitor connection
09-08 13:34:36.252  1031  1533 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-08 13:34:36.252  1935  8056 D WfdsMonitor: Supplicant connection established
09-08 13:34:36.252  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-08 13:34:36.253  1935  2281 D WfdsService: Connected to the supplicant for wfds
09-08 13:34:36.253  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-08 13:34:36.253  1031  1533 D WifiNative-w,lan0: DRIVER BTCOEXSCAN-STOP: returned true
09-08 13:34:36.253  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 13:34:36.253  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 13:34:36.254  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 13:34:36.254  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-08 13:34:36.254  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,09-08 13:34:36.257  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-08 13:34:36.257  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 13:34:36.257  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 13:34:36.257  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 13:34:36.257  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-08 13:34:36.257  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-08 13:34:36.258  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-08 13:34:36.258  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-08 13:34:36.258  8020  8020 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-08 13:34:36.258  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-08 13:34:36.258  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-08 13:34:36.258  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-08 13:34:36.259  1031  1533 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-08 13:34:36.260  1031  1533 E WifiNative: : [141,286,772 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-08 13:34:36.260  1031  1533 D WifiNative-wlan0: doBoolean: RECONNECT
09-08 13:34:36.260  1031  1533 D WifiNative-wlan0: RECONNECT: returned true
09-08 13:34:36.261  1031  1533 D WifiNative-wlan0: doString: [STATUS]
09-08 13:34:36.261  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-08 13:34:36.261  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-08 13:34:36.261  1031  1533 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 13:34:36.261  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 13:34:36.262  1031  1533 D WifiNative-wlan0: SET ps 1: returned true
09-08 13:34:36.262  1031  1532 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.263  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 13:34:36.263  1031  1031 D RttService: SCAN_AVAILABLE : 3
09-08 13:34:36.263  1031  1551 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.263  1031  1551 I WifiNative-HAL: startHal
,09-08 13:34:36.263  1031  1533 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-08 13:34:36.263  1031  1551 D wifi    : getting scan capabilities on interface[1] = 0xaf6b5e20
09-08 13:34:36.263  1031  1551 D wifi    : failed to get capabilities : -3
09-08 13:34:36.263  1031  1551 E WifiScanningService: could not get scan capabilities
09-08 13:34:36.264  1031  1533 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-08 13:34:36.264   315   904 D CommandListener: Setting iface cfg
09-08 13:34:36.264   315   904 D CommandListener: Trying to bring up p2p0
09-08 13:34:36.264  1031  1552 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.264  1031  1532 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 13:34:36.264  1031  1532 D LGWifiP2pService: P2pEnablingState
09-08 13:34:36.265  1031  1533 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-08 13:34:36.265  1031  1532 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.265  1031  1532 D LGWifiP2pService: P2p socket connection successful
09-08 13:34:36.265  1031  1532 D LGWifiP2pService: P2pEnabledState
09-08 13:34:36.265  1031  1533 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-08 13:34:36.265  1031  1532 D LGWifiP2pService: sending p2p connection changed broadcast
09-08 13:34:36.266  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-08 13:34:36.266  1935  1935 D WfdsService: WifiP2pState is changed : true
09-08 13:34:36.266  1031  1532 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-08 13:34:36.266  1935  2281 D WfdsService: Receive the WFDS_ENABLE Method
09-08 13:34:36.266  1935  2281 D WfdsService: Set the WFDS Monitor: true
09-08 13:34:36.266  1935  2281 D WfdsService: Connected to the supplicant for wfds
09-08 13:34:36.266  1935  2281 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 13:34:36.266  8020  8020 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 13:34:36.266  1031  1532 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-08 13:34:36.267  1031  1532 D WifiNative-p2p0: doBoolean: SET device_name G3
09-08 13:34:36.267  1935  2281 D WfdsService: selectPreferredScanChannel [36]
09-08 13:34:36.267  1935  2281 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-08 13:34:36.267  1031  1532 D WifiNative-p2p0: SET device_name G3: returned true
09-08 13:34:36.267  1031  1532 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-08 13:34:36.267  1031  1532 D LGWifiP2pService: before postfix = G3
09-08 13:34:36.267  1031  1532 D WifiServerServiceExt: postfix byte check : 2
09-08 13:34:36.267  1031  1532 D LGWifiP2pService: after postfix = G3
09-08 13:34:36.267  1031  1532 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-08 13:34:36.268  1935  1935 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 13:34:36.268  1031  1532 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-08 13:34:36.268  1031  1532 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-08 13:34:36.268  1031  1532 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-08 13:34:36.268  1031  1532 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-08 13:34:36.268  1935  1935 D WfdsService: isConnected: false
09-08 13:34:36.268  1031  1532 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-08 13:34:36.268  1031  1532 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-08 13:34:36.269  1031  1532 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-08 13:34:36.269  1031  1532 D WifiNative-HAL: p2pGetDeviceAddress
09-08 13:34:36.269  1031  1532 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-08 13:34:36.269  1031  1532 D LGWifiP2pService: DeviceAddr,ess: 02:9a:02:7f:fb:5d
09-08 13:34:36.269  1031  1532 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,09-08 13:34:36.271  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=141298  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 13:34:36.272  1935  1935 I WfdStateTracker: handleP2pThisDeviceChanged
09-08 13:34:36.272  1935  1935 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 13:34:36.272  1935  1935 D WfdsService: Update P2p Interface State: 3
09-08 13:34:36.272  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=141300  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 13:34:36.272  1031  1532 D WifiNative-p2p0: P2P_FLUSH: returned true
09-08 13:34:36.272  1031  1532 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-08 13:34:36.273  1031  1532 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-08 13:34:36.273  1031  1532 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-08 13:34:36.274  1031  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{202301e4 type 2 when 141300 com.google.android.gms} when 141300
09-08 13:34:36.274  1031  1532 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-08 13:34:36.274  1031  1532 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-08 13:34:36.274  1031  1533 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-08 13:34:36.275  1031  1533 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-08 13:34:36.275  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.275  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.275  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 13:34:36.276  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:36.276  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:36.276  1031  1533 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-08 13:34:36.276  1031  1533 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 13:34:36.277  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:36.285  8020  8020 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 13:34:36.285  1031  1533 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-08 13:34:36.286  1031  1533 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-08 13:34:36.286  1031  1533 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-08 13:34:36.286  1031  1533 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,09-08 13:34:36.286  8020  8020 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 13:34:36.286  1031  1532 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-08 13:34:36.286  1031  1532 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-08 13:34:36.287  1031  1532 D LGWifiP2pService: InactiveState
09-08 13:34:36.287  1031  1532 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.287  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.287  1031  1532 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-08 13:34:36.287  1031  1532 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-08 13:34:36.287  1031  1532 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.287  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.287  1031  1532 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.288  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.288  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.288  1031  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.288  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 13:34:36.288  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.288  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.288  1031  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.288  8020  8020 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:36.288  1935  8056 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 13:34:36.289  1031  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 13:34:36.289  1031  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:36.289  1031  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:36.289  1031  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:36.289  8020  8020 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 13:34:36.289  8020  8020 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.289  1935  8056 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:36.289  1935  2281 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 13:34:36.289  1031  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:36.289  1031  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.289  1031  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.289  1031  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.290  8020  8020 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.290  1935  8056 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:36.290  1031  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:36.290  1031  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:,36.290  1031  1532 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.290  1031  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.290  1031  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.290  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.290  1031  1532 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.290  1031  1031 E WifiServerServiceExt: No p2p device connected
09-08 13:34:36.291  1031  1533 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 13:34:36.292  1031  1533 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 13:34:36.292  1031  1533 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-08 13:34:36.292  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-08 13:34:36.293  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-08 13:34:36.294  8020  8020 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:36.294  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-08 13:34:36.294  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:36.294  1031  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:36.294  1031  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-08 13:34:36.294  8020  8020 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-08 13:34:36.295  8020  8020 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.295  1935  8056 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:36.295  1031  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:36.295  1031  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.295  1031  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.295  1031  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.295  8020  8020 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-08 13:34:36.296  1935  8056 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:36.296  1031  8055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-08 13:34:36.296  1031  8055 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.296  1031  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.296  1031  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-08 13:34:36.296  1031  1533 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-08 13:34:36.297  1031  1533 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-08 13:34:36.297  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.297  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:36.297  1031  1533 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,09-08 13:34:36.297  1031  1533 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-08 13:34:36.297  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-08 13:34:36.298  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-08 13:34:36.298  8020  8020 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 13:34:36.298  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-08 13:34:36.298  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 13:34:36.298  1031  8055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 13:34:36.298  1031  8055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 13:34:36.299  1031  1533 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,09-08 13:34:36.299  1031  1533 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-08 13:34:36.301  1031  1533 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,09-08 13:34:36.301  1031  1533 D WifiNative-wlan0: doBoolean: SCAN
,09-08 13:34:36.302  1031  1533 D WifiNative-wlan0: SCAN: returned false
09-08 13:34:36.302  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=141330  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 13:34:36.303  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=141331  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-08 13:34:36.304  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:36.304  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 13:34:36.304  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.304  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:36.304  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 13:34:36.305  1031  1533 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:36.306  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:36.306  1031  1533 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-08 13:34:36.306  1031  1533 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:36.307  1031  1533 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:36.308  1031  1533 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-08 13:34:36.308  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:36.308  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 13:34:36.309  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-08 13:34:36.309  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 13:34:36.321  8036  8036 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:36.321  8036  8036 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:36.324  8036  8036 D PhoneMonitor: Register our PhoneStateListener,
09-08 13:34:36.336  8036  8036 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-08 13:34:36.338  8036  8036 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1,
,09-08 13:34:36.351  8036  8036 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-08 13:34:36.352  8036  8036 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-08 13:34:36.353  8036  8036 D TelephonyAutoProfiling: [parse] Load xml
09-08 13:34:36.355  8036  8036 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-08 13:34:36.355  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-08 13:34:36.356  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-08 13:34:36.356  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-08 13:34:36.356  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-08 13:34:36.356  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-08 13:34:36.356  8036  8036 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-08 13:34:36.356  8036  8036 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-08 13:34:36.362  8036  8036 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-08 13:34:36.384  1031  1971 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8059 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 13:34:36.385  1031  1971 I ActivityManager: Killing 7298:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-08 13:34:36.492  1031  1898 W libprocessgroup: failed to open /acct/uid_10037/pid_7298/cgroup.procs: No such file or directory
,09-08 13:34:36.737  1031  1971 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8083 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-08 13:34:36.739  1031  1971 I ActivityManager: Killing 7325:com.lge.settings.easy/1000 (adj 15): empty #17
,09-08 13:34:36.791  1031  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_7325/cgroup.procs: No such file or directory
,09-08 13:34:36.889  8020  8020 E wpa_supplicant: USIM:  scard_init function
,09-08 13:34:36.894  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-08 13:34:36.894  1031  8055 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-08 13:34:36.894  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-08 13:34:36.894  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: WPS-AP-AVAILABLE 
09-08 13:34:36.894  1031  8055 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-08 13:34:36.897  1031  1533 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,09-08 13:34:36.898  1031  1533 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 13:34:36.899  1031  1533 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 13:34:36.901  8020  8020 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-08 13:34:36.905  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-08 13:34:36.905  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-08 13:34:36.906  1031  1533 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-08 13:34:36.906  1031  1533 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-08 13:34:36.917  1031  2006 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8100 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:36.921  1031  2006 I ActivityManager: Killing 6710:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-08 13:34:36.958  6869  6869 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-08 13:34:36.958  6869  6869 W System.err: android.os.DeadObjectException
09-08 13:34:36.958  6869  6869 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 13:34:36.958  6869  6869 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 13:34:36.958  6869  6869 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-08 13:34:36.958  6869  6869 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-08 13:34:36.958  6869  6869 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 13:34:36.958  6869  6869 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 13:34:36.958  6869  6869 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 13:34:36.958  6869  6869 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 13:34:36.958  6869  6869 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 13:34:36.958  6869  6869 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 13:34:36.958  6869  6869 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:36.958  6869  6869 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 13:34:36.958  6869  6869 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 13:34:36.958  6869  6869 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 13:34:36.959  6869  6869 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-08 13:34:36.959  6869  6869 W System.err: android.os.DeadObjectException
09-08 13:34:36.959  6869  6869 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 13:34:36.959  6869  6869 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 13:34:36.959  6869  6869 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-08 13:34:36.959  6869  6869 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-08 13:34:36.959  6869  6869 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-08 13:34:36.959  6869  6869 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-08 13:34:36.959  6869  6869 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 13:34:36.959  6869  6869 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 13:34:36.959  6869  6869 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 13:34:36.959  6869  6869 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 13:34:36.959  6869  6869 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:36.959  6869  6869 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 13:34:36.959  6869  6869 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 13:34:36.959  6869  6869 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 13:34:36.959  6869  6869 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-08 13:34:36.961  6869  6869 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-08 13:34:37.052  8020  8020 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 13:34:37.053  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-08 13:34:37.053  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-08 13:34:37.059  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-08 13:34:37.059  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-08 13:34:37.060  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:37.061  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:37.070  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:37.070  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:37.071  8020  8020 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 13:34:37.072  8020  8020 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-08 13:34:37.073  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,09-08 13:34:37.073  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 13:34:37.073  1031  8055 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 13:34:37.073  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,09-08 13:34:37.073  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 13:34:37.073  1031  8055 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 13:34:37.076  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:37.076  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:37.138  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=142165  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-08 13:34:37.140  1031  1898 W libprocessgroup: failed to open /acct/uid_1000/pid_6710/cgroup.procs: No such file or directory
09-08 13:34:37.141  1031  1898 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-08 13:34:37.143  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=142170  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-08 13:34:37.146  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=142172  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-08 13:34:37.149  6869  6869 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-08 13:34:37.150  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=142177  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-08 13:34:37.151  6869  6869 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-08 13:34:37.152  1031  1533 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142179
09-08 13:34:37.153  1031  1533 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142180
09-08 13:34:37.154  1031  1533 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142181,
09-08 13:34:37.155  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142183
09-08 13:34:37.156  1031  1533 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142184
,09-08 13:34:37.160  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=142187  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-08 13:34:37.163  1031  1113 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 13:34:37.168  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.168  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:37.171  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.174  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.174  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.174  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-08 13:34:37.196  8100  8100 I art     : Almond Protected OAT
,09-08 13:34:37.230  1031  1970 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8130 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 13:34:37.232  6869  6869 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-08 13:34:37.234  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=142261  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-08 13:34:37.236  1031  1533 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=142263  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 13:34:37.236  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=142264  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-08 13:34:37.237  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.237  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.237  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 13:34:37.239  1031  1533 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142266
09-08 13:34:37.239  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.239  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.239  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 13:34:37.239  1031  1533 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142267
09-08 13:34:37.240  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.240  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:37.240  1031  1533 D WifiNative-wlan0: doString: [STATUS]
09-08 13:34:37.241  1031  8055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-08 13:34:37.241  1031  8055 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-08 13:34:37.241  1031  1533 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-08 13:34:37.241  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.244  1031  1533 I WifiServiceExtension: setVHTCapabilityType  : false
,09-08 13:34:37.245  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.245  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:37.247  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.250  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.250  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.250  1031  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.251  1031  1533 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 13:34:37.252  1031  1533 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-08 13:34:37.264  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.264  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.264  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 13:34:37.265  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.265  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.265  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 13:34:37.267  1031  1533 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 13:34:37.267  1031  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 13:34:37.267  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.267  1031  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 13:34:37.267  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:37.267  1031  1539 D ConnectivityService: Got NetworkAgent Messenger
09-08 13:34:37.267  1031  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 13:34:37.267  1031  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 13:34:37.267  1031  1539 D ConnectivityService: NetworkAgent connected
09-08 13:34:37.267  1031  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-08 13:34:37.269  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.271  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.271  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:37.272  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.273  1031  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 13:34:37.273  1031  1533 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 13:34:37.273  1031  1533 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-08 13:34:37.273  1031  1533 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-08 13:34:37.273  1031  1533 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-08 13:34:37.277  1031  1533 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-08 13:34:37.279   315   904 D CommandListener: Setting iface cfg
09-08 13:34:37.280  8100  8100 D WeatherApplication: removeAccount
09-08 13:34:37.281  8100  8100 D WeatherApplication: Account.length = 0
09-08 13:34:37.281  8100  8100 E WeatherApplication: OPERATOR:OPEN
09-08 13:34:37.282  1031  1533 E WifiStateMachine: Start Dhcp Watchdog 3
09-08 13:34:37.282  1031  1533 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=142310  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:37.283  1031  1533 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=142311  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:37.284  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=142311  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-08 13:34:37.285  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:37.285  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 13:34:37.286  8100  8100 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:37
,09-08 13:34:37.289  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:37.291  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:37.291  1031  1533 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:37.291  1031  1533 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:37.292  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-08 13:34:37.292  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-08 13:34:37.292  1031  8148 D DhcpStateMachine: StoppedState
09-08 13:34:37.292  1031  8148 D DhcpStateMachine: StoppedState{ when=-10ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.292  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:37.292  1031  8148 D DhcpStateMachine: WaitBeforeStartState
09-08 13:34:37.293  1031  1533 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-08 13:34:37.294  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:37.294  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-08 13:34:37.294  8100  8100 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 13:34:37.294  8100  8100 D Weather.Utils: 2 : All the weather widget is gone.
09-08 13:34:37.295  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:37.295  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 13:34:37.295  1031  1533 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=142323  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:37.296  1031  1533 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=142323  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:37.296  8100  8100 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 13:34:37.296  1031  1533 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=142324  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-08 13:34:37.297  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2509] from screen [on:0 period:160694769] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:37.298  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:160694770] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:37.298  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 13:34:37.298  8100  8100 D WeatherAncestor: connectivity changed - connection : true
09-08 13:34:37.299  8100  8100 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-08 13:34:37.303  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.303  1031  1539 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-08 13:34:37.304  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.304  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.304  1031  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.305  1031  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.305  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.306  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.306  1031  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 13:34:37.306  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 13:34:37.307  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 13:34:37.307  1031  1533 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 13:34:37.308  8100  8100 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 13:34:37.308  1031  1533 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 13:34:37.308  8100  8100 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 13:34:37.308  8100  8100 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-08 13:34:37.308  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 13:34:37.308  1031  1533 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-08 13:34:37.309  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:37.309  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 13:34:37.309  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=228,0,0
09-08 13:34:37.310  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=228,0,0
09-08 13:34:37.310  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-08 13:34:37.311  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-08 13:34:37.311  1031  1533 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-08 13:34:37.311  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 0
09-08 13:34:37.312  1031  1533 D WifiNative-wlan0: SET ps 0: returned true
09-08 13:34:37.312  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-08 13:34:37.312  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-08 13:34:37.312  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,09-08 13:34:37.313  1031  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1cd9acae target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.313  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1cd9acae target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.313  1031  8148 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.313  1031  8148 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 13:34:37.314  1031  1533 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 13:34:37.314  1031  1533 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 13:34:37.314  1031  1533 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 13:34:37.315   315   904 D CommandListener: Setting iface cfg
09-08 13:34:37.315   315   904 D CommandListener: Trying to bring up wlan0
09-08 13:34:37.317  1031  1533 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 13:34:37.318  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 13:34:37.318  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 13:34:37.318  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.318  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.319  1031  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.319  1031  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.320  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.320  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-08 13:34:37.321  1031  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 13:34:37.321  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 13:34:37.322  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-08 13:34:37.322  1031  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.322  1031  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.322  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-08 13:34:37.322  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-08 13:34:37.323  1031  1533 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-08 13:34:37.323  1031  1533 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-08 13:34:37.323  8020  8020 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-08 13:34:37.324  1031  1533 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-08 13:34:37.324  1031  1533 D WifiNative-wlan0: doBoolean: SET ps 1
09-08 13:34:37.326  8130  8130 D UEI.SmartControl: Quickset Services start...
,09-08 13:34:37.328  8130  8130 I UEI.SmartControl: Manufacture = LGE
09-08 13:34:37.328  8130  8130 D UEI.SmartControl: Id = LGNevo
09-08 13:34:37.329  8130  8130 D UEI.SmartControl: File observer start...
09-08 13:34:37.330  8130  8130 E UEI.SmartControl: IR Port is disabled: false
09-08 13:34:37.330  8130  8130 D UEI.SmartControl: Starting file observer...
09-08 13:34:37.330  8130  8130 D UEI.SmartControl: Extracting JNI libs...
09-08 13:34:37.331  8130  8130 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 13:34:37.333  8100  8100 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 13:34:37.333  8100  8100 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:37
09-08 13:34:37.340  1031  1533 D WifiNative-wlan0: SET ps 1: returned true
,09-08 13:34:37.340  1031  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 13:34:37.341  1031  1533 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 13:34:37.341  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-08 13:34:37.341  1031  1533 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 13:34:37.342  1031  1539 D ConnectivityService: ignoring duplicate network state non-change
,09-08 13:34:37.371  1031  1047 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8151 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 13:34:37.372  1031  1047 I ActivityManager: Killing 6869:com.lge.qremote/u0a112 (adj 15): empty #17
09-08 13:34:37.402  8130  8130 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-08 13:34:37.402  8130  8130 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 13:34:37.402  8130  8130 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-08 13:34:37.424  8130  8130 I UEI.SmartControl: --- Selecting new region: 6
,09-08 13:34:37.425  8130  8130 I UEI.SmartControl: Model = LG-D855
09-08 13:34:37.426  8130  8130 D UEI.SmartControl: QS Service created
09-08 13:34:37.432  1031  1971 W libprocessgroup: failed to open /acct/uid_10112/pid_6869/cgroup.procs: No such file or directory
09-08 13:34:37.432  1031  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 13:34:37.433  1031  1539 D ConnectivityService: Adding iface wlan0 to network 102
09-08 13:34:37.442  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.442  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:37.442  1031  1533 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 13:34:37.443  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.444  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.444  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.444  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 13:34:37.451  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.451  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.451  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 13:34:37.451  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 13:34:37.452  1935  1935 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-08 13:34:37.453  1031  1539 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 13:34:37.453  1031  1539 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-08 13:34:37.454  1031  1539 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-08 13:34:37.456   315   904 E Netd    : netlink response contains error (File exists)
,09-08 13:34:37.457  1031  1539 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-08 13:34:37.457  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.457  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.457  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 13:34:37.458  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 13:34:37.458  8130  8130 I UEI.SmartControl: Service initServices...
09-08 13:34:37.459  1031  1539 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-08 13:34:37.459  1031  1539 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-08 13:34:37.459  1031  1539 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-08 13:34:37.462  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.462  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 13:34:37.463  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.463  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.463  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:37.463  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 13:34:37.463  1031  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 13:34:37.463  1031  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 13:34:37.463  1031  1539 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 13:34:37.463  1031  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 13:34:37.463  1031  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:37.463  1031  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:37.463  1031  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 13:34:37.464  1031  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37.464  1031  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-08 13:34:37.464  1031  1539 D ConnectivityService: currentScore = 0, newScore = 20
09-08 13:34:37.464  1031  1539 D ConnectivityService:    accepting network in place of null
09-08 13:34:37.464  1031  1539 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37.465  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.465  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 13:34:37,.465  8130  8130 D UEI.SmartControl: QS start get config
09-08 13:34:37.465  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.465  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.465  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 13:34:37.465  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:37.465  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 13:34:37.466  1031  1533 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37.466  1031  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:37.466  1846  1846 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37.466  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-08 13:34:37.469  1031  1539 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,09-08 13:34:37.469  1031  1539 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 13:34:37.469  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 13:34:37.470   315  8171 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-08 13:34:37.472  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 13:34:37.472  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 13:34:37.472  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.473  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1,
09-08 13:34:37.473  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 13:34:37.473  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 13:34:37.473  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 13:34:37.474  1031  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:37.474  1031  1539 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 13:34:37.475  1031  1539 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 13:34:37.477  1031  1539 D ConnectivityService: validation of new default Network = false
09-08 13:34:37.477  1031  1539 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 13:34:37.477  1031  1539 D DSQN    : enableDataServiceNotify 
09-08 13:34:37.477  1031  1539 D DSQN    : start dsqn bin
09-08 13:34:37.483  1031  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 13:34:37.483  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37.483  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:37.471  8172  8172 W dsqn    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:37.471  8172  8172 W dsqn    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:37.483  1031  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:37.485  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 13:34:37.494  8172  8172 E DSQN    : DSQN ssw
09-08 13:34:37.501  1031  1531 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-08 13:34:37.503  8130  8130 D UEI.SmartControl: Loading JNI Libs...
09-08 13:34:37.512   315  8171 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 13:34:37.514  1031  8148 D DhcpStateMachine: DHCPV4 request on wlan0
,09-08 13:34:37.515  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 13:34:37.516  1031  8148 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-08 13:34:37.516  1031  8148 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-08 13:34:37.516  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.516  1811  8176 I CheckinService: active receiver: disabled
09-08 13:34:37.516  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.501  8177  8177 W dhcpcd  : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-08 13:34:37.501  8177  8177 W dhcpcd  : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-08 13:34:37.535  8177  8177 I dhcpcd  : version 5.5.6 starting
09-08 13:34:37.537  8177  8177 E dhcpcd  : get_duid: m
09-08 13:34:37.537  8177  8177 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-08 13:34:37.537  8177  8177 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-08 13:34:37.549   315  8171 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-08 13:34:37.574   315   903 D LGDataListener: argv[0]=dsqncommand
09-08 13:34:37.574   315   903 D LGDataListener: argv[1]=wlan0
09-08 13:34:37.574   315   903 D LGDataListener: argv[2]=1
09-08 13:34:37.574   315   903 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 13:34:37.574  1031  1111 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 13:34:37.574  1031  1111 D DSQN    : start to monitor internet connection
,09-08 13:34:37.581   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:37.581   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-08 13:34:37.581   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 13:34:37.581  8151  8183 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 13:34:37.583   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:37.583   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 13:34:37.583   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 13:34:37.583  8151  8183 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 13:34:37.586  8177  8177 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 13:34:37.586  8177  8177 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-08 13:34:37.586  8177  8177 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 13:34:37.586   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:37.586   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 13:34:37.586   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 13:34:37.586  8177  8177 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-08 13:34:37.586  8151  8191 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 13:34:37.586  8177  8177 D dhcpcd  : wlan0: sending REQUEST (xid 0x774115e6), next in 3.07 seconds
09-08 13:34:37.588   281   448 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 13:34:37.588   281   448 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 13:34:37.588   281   448 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 13:34:37.588  8151  8191 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 13:34:37.600  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 11:34:37 GMT], X-Android-Received-Millis=[1473334477600], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473334477574]}
09-08 13:34:37.600  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 13:34:37.601  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 13:34:37.601  1031  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-08 13:34:37.601  1031  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 13:34:37.601  1031  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:37.601  1031  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:37.601  1031  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 13:34:37.601  1031  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-08 13:34:37.601  1031  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 13:34:37.601  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37,.601  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:37.601  1031  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:37.601  1031  1539 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37.602  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 13:34:37.602  1031  1533 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37.602  1031  1533 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:37.602  1846  1846 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:37.602  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 13:34:37.603  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-08 13:34:37.616  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 13:34:37.617  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.617  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-08 13:34:37.621  8177  8177 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-08 13:34:37.650  8177  8177 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-08 13:34:37.650  8177  8177 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-08 13:34:37.650  8177  8177 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-08 13:34:37.650  8177  8177 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-08 13:34:37.650  8177  8177 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-08 13:34:37.650  8177  8177 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-08 13:34:37.650  8177  8177 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-08 13:34:37.650  8177  8177 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-08 13:34:37.748  8130  8130 I UEI.SmartControl: Supports setup maps: true
,09-08 13:34:37.751  8130  8130 D UEI.SmartControl: QS start statue = true Error code = 0
09-08 13:34:37.751  8130  8130 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 13:34:37.751  8130  8130 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 13:34:37.751  8130  8130 I UEI.SmartControl: ### init IR Blaster...
09-08 13:34:37.755  8130  8130 D serial_port: Configuring serial port
09-08 13:34:37.759  8130  8130 E UEI.SmartControl: UEIBLaster setting for 616
09-08 13:34:37.759  8151  8151 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-08 13:34:37.759  8130  8130 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 13:34:37.760  8130  8130 I UEI.SmartControl: configuring settings for MAXQ616
09-08 13:34:37.760  8130  8130 I UEI.SmartControl: Get version...
,09-08 13:34:37.769  8151  8151 I LibraryLoader: Loading: webviewchromium
09-08 13:34:37.773  8151  8151 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2808-2813)
09-08 13:34:37.773  8151  8151 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 13:34:37.777  8151  8151 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ce6e222}
09-08 13:34:37.778  8130  8217 D UEI.SmartControl: serial port data available: 21
09-08 13:34:37.779  8151  8151 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 13:34:37.779  8151  8151 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 13:34:37.787  8151  8151 I BrowserStartupController: Initializing chromium process, renderers=0
,09-08 13:34:37.788  8151  8151 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 13:34:37.798   319  1380 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 10093
09-08 13:34:37.799  8151  8226 W AudioManagerAndroid: Requires BLUETOOTH permission
09-08 13:34:37.800  8151  8151 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-08 13:34:37.801  8151  8151 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,09-08 13:34:37.802  8151  8151 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-08 13:34:37.805  8130  8130 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-08 13:34:37.805  8130  8130 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 13:34:37.806  8130  8130 I UEI.SmartControl: QS saving settings...
09-08 13:34:37.807  8130  8130 D UEI.SmartControl: IR Blaster version: 25672567
09-08 13:34:37.813  8151  8151 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 13:34:37.813  8151  8151 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 13:34:37.813  8151  8151 I Adreno-EGL: Build Date: 12/12/14 금
09-08 13:34:37.813  8151  8151 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-08 13:34:37.813  8151  8151 I Adreno-EGL: Remote Branch: 
09-08 13:34:37.813  8151  8151 I Adreno-EGL: Local Patches: 
09-08 13:34:37.813  8151  8151 I Adreno-EGL: Reconstruct Branch: 
,09-08 13:34:37.822  8130  8217 D UEI.SmartControl: serial port data available: 4
09-08 13:34:37.852  8130  8241 I UEI.SmartControl: Device manager: loading config....
09-08 13:34:37.853  8130  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-08 13:34:37.855  8130  8241 D UEI.SmartControl: ----------- loading internal config...
,09-08 13:34:37.858  8130  8130 E UEI.SmartControl: Services init done
09-08 13:34:37.858  8130  8130 D UEI.SmartControl: QS Service init finished
09-08 13:34:37.859  8130  8130 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 13:34:37.859  8130  8130 D UEI.SmartControl: QS Service version code: 201091
09-08 13:34:37.860  8130  8130 D UEI.SmartControl: Service requested: Control
09-08 13:34:37.862  8130  8241 E UEI.SmartControl: Loading SETTINGS...
09-08 13:34:37.865  8130  8130 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-08 13:34:37.868  8130  8130 D UEI.SmartControl: Service.onUnbind: IControl
09-08 13:34:37.868  8130  8241 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-08 13:34:37.870  8130  8130 D UEI.SmartControl: Service.onDestroy
09-08 13:34:37.870  8130  8130 D UEI.SmartControl: Lock is in USE false
09-08 13:34:37.870  8130  8130 D UEI.SmartControl: unbind internal service
09-08 13:34:37.871  8130  8240 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 13:34:37.871  8130  8240 D UEI.SmartControl: -----service ready thread exits
09-08 13:34:37.872  8130  8130 D serial_port: close(fd = 25)
09-08 13:34:37.875  8130  8130 I UEI.SmartControl: Serial port is closed.
09-08 13:34:37.875  8130  8130 I UEI.SmartControl: Serial port is closed.
09-08 13:34:37.875  8130  8130 D UEI.SmartControl: Blaster closed
09-08 13:34:37.875  8130  8130 D UEI.SmartControl: Shut down QS...
09-08 13:34:37.875  8130  8130 D UEI.SmartControl: Stopping QS lib
09-08 13:34:37.875  8130  8130 D UEI.SmartControl: QS lib stop result = true
09-08 13:34:37.875  8130  8130 D UEI.SmartControl: Stopped QS lib
09-08 13:34:37.876  8130  8130 D UEI.SmartControl: Stopped file observer...
09-08 13:34:37.876  8130  8130 D UEI.SmartControl: QS shutdown complete
09-08 13:34:37.876  8130  8130 D UEI.SmartControl: QS Service created
09-08 13:34:37.876  8151  8151 I NSApplication: Starting up...
,09-08 13:34:37.892  1031  1898 I ActivityManager: Killing 6831:com.lge.sync/1000 (adj 15): empty #17
,09-08 13:34:37.894  8130  8130 I UEI.SmartControl: Service initServices...
09-08 13:34:37.894  8130  8130 D UEI.SmartControl: QS start get config
,09-08 13:34:37.918  1031  8148 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-08 13:34:37.919  1031  8148 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-08 13:34:37.919  1031  8148 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 13:34:37.919  1031  8148 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-08 13:34:37.919  1031  8148 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-08 13:34:37.919  1031  8148 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 13:34:37.919  1031  8148 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-08 13:34:37.919  1031  8148 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 13:34:37.920  1031  8148 D DhcpStateMachine: RunningState
09-08 13:34:37.956  1031  1971 W libprocessgroup: failed to open /acct/uid_1000/pid_6831/cgroup.procs: No such file or directory
,09-08 13:34:37.986  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-08 13:34:37.991  6400  6439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 13:34:38.009  2177  2177 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:38.018  1031  1779 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-08 13:34:38.018  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:38.018   315  8252 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 13:34:38.018  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:38.019  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 13:34:38.019   315  8252 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-08 13:34:38.019  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 13:34:38.019  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-08 13:34:38.021  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 13:34:38.021  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:38.021  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 13:34:38.021  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 13:34:38.022  7365  7365 I AppUp4:CustModeStarterReceiver: onReceive
09-08 13:34:38.025  7365  7365 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f3d274b
09-08 13:34:38.025  7365  7365 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 13:34:38.025  7365  7365 D AppUp4:CustFacade: isPhone : true
09-08 13:34:38.025  7365  7365 D AppUp4:CustModeStarterReceiver: begin check event
09-08 13:34:38.025  7365  7365 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 13:34:38.028  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:38.028  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:38.030  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 13:34:38.032  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:38.035  3431  3431 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:38.037  3431  3431 V DownloadManager: DownloadService onCreate
09-08 13:34:38.038  4291  8253 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 13:34:38.039  7986  7986 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-08 13:34:38.040  4291  8253 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 13:34:38.043  4291  8254 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:38.043  3431  8255 I DownloadManager: in removeSpuriousFiles
09-08 13:34:38.043  4291  8254 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 13:34:38.044  3431  8255 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-08 13:34:38.050  3431  8255 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@ddea893 on behalf of 3431
09-08 13:34:38.051  3323  3323 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 13:34:38.051  3323  3323 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:38.051  4291  8253 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 13:34:38.051  3323  3323 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 13:34:38.054  3431  3431 V DownloadManager: DownloadService onStartCommand
09-08 13:34:38.054  4291  4291 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 13:34:38.054  4291  4291 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 13:34:38.054  3431  8256 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 13:34:38.055  4291  4291 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 13:34:38.055  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-08 13:34:38.055  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-08 13:34:38.055  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-08 13:34:38.055  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-08 13:34:38.055  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-08 13:34:38.055  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-08 13:34:38.055  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-08 13:34:38.056  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-08 13:34:38.056  4291  4291 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 13:34:38.056  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-08 13:34:38.056  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-08 13:34:38.056  3431  8255 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,09-08 13:34:38.060  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 11:34:38 GMT], X-Android-Received-Millis=[1473334478060], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473334478026]}
09-08 13:34:38.060  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 13:34:38.060  1031  8147 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 13:34:38.060  1031  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-08 13:34:38.060  1031  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 13:34:38.060  1031  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 13:34:38.060  8036  8036 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 13:34:38.060  1031  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:38.061  1031  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 13:34:38.061  1031  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-08 13:34:38.061  1031  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 13:34:38.061  8036  8036 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 13:34:38.061  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:38.061  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:38.061  1031  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:38.061  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 13:34:38.063  3431  8255 I DownloadManager: in trimDatabase
09-08 13:34:38.063  3431  8255 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 13:34:38.063  4291  4291 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 13:34:38.064  3431  8255 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9044bce on behalf of 3431
09-08 13:34:38.065  3431  8256 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@15413aef on behalf of 3431
09-08 13:34:38.068  7986  8259 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:38.069   315  8252 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-08 13:34:38.069  3431  8256 V DownloadManager: processing inserted download 1
09-08 13:34:38.071  3431  8256 V DownloadManager: processing inserted download 4
09-08 13:34:38.072  3431  8256 V DownloadManager: processing inserted download 7
09-08 13:34:38.073  3431  8256 V DownloadManager: processing inserted download 8
09-08 13:34:38.074  3431  8256 V DownloadManager: processing inserted download 9
09-08 13:34:38.075  3431  8256 V DownloadManager: processing inserted download 10
09-08 13:34:38.075   315  8264 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 13:34:38.075   315  8264 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-08 13:34:38.075  8100  8100 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:,min:sec) 13:34:38
09-08 13:34:38.076  3431  8256 V DownloadManager: processing inserted download 11
09-08 13:34:38.076  8100  8100 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 13:34:38.076  8100  8100 D Weather.Utils: 2 : All the weather widget is gone.
09-08 13:34:38.076  8100  8100 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 13:34:38.077  3431  8256 V DownloadManager: processing inserted download 12
09-08 13:34:38.077  8100  8100 D WeatherAncestor: connectivity changed - connection : true
09-08 13:34:38.077  8100  8100 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@310a5241
09-08 13:34:38.077  8100  8100 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 13:34:38.077  8100  8100 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 13:34:38.077  8100  8100 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 13:34:38.077  8100  8100 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 13:34:38.077  8100  8100 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:38
09-08 13:34:38.078  3431  8256 V DownloadManager: processing inserted download 13
,09-08 13:34:38.079  3431  8256 V DownloadManager: processing inserted download 14
09-08 13:34:38.080  3431  8256 V DownloadManager: processing inserted download 16
09-08 13:34:38.085  3431  3431 V DownloadManager: DownloadService onDestroy
09-08 13:34:38.094  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 13:34:38.094  6851  6851 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 13:34:38.094  6851  6851 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 13:34:38.094  6851  6851 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 13:34:38.094  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-08 13:34:38.094  6851  6851 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 13:34:38.094  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 13:34:38.095  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 13:34:38.095  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 13:34:38.095  6851  6851 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 13:34:38.095  6851  6851 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 13:34:38.095  6851  6851 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 13:34:38.116   315  8264 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-08 13:34:38.128  1031  1570 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8265 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-08 13:34:38.154  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:38.154  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:38.154  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:38.154  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:38.154  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:38.154  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:38.154  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:38.154  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:38.156  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:38.156  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:38.156  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:38.156  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:38.156  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:38.156  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e55c3a0 removed from the list
09-08 13:34:38.156  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:38.156  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df3b59 removed from the list
09-08 13:34:38.156  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:38.156  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:38.162  6595  8282 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-08 13:34:38.162  6595  8282 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-08 13:34:38.166  6595  8282 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-08 13:34:38.166  6595  8282 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 13:34:38.166  6595  8282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:38.166  6595  8282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:38.166  6595  8282 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 13:34:38.167  6595  8284 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-08 13:34:38.167  6595  8284 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 13:34:38.167  6595  8284 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 13:34:38.168  6892  8262 V FormManager: There are no updated forms. The schedule will be deleted.
09-08 13:34:38.168  6595  8288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 917, name: OutgoingSocketThread/Receiver)
09-08 13:34:38.169  6595  8288 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 917, thread name: OutgoingSocketThread/Receiver)
09-08 13:34:38.169  6595  8288 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 13:34:38.169  6595  8288 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 917, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 13:34:38.170  6892  8262 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 13:34:38.170  6595  8287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 916, name: OutgoingSocketThread/Sender)
09-08 13:34:38.170  6595  8284 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:38.170  6595  8284 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 13:34:38.172  6595  8289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 918, name: IncomingSocketThread/Sender)
09-08 13:34:38.173  6595  8290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 919, name: IncomingSocketThread/Receiver)
09-08 13:34:38.173  6595  8290 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 919, thread name: IncomingSocketThread/Receiver)
09-08 13:34:38.173  6595  8290 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 13:34:38.173  6595  8290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 919, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 13:34:38.211  8265  8265 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 13:34:38.212  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 13:34:38.216  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:38.226  8265  8265 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:38.227  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 13:34:38.231  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:38.235  6892  8294 V FormManager: There are no updated forms. The schedule will be deleted.
09-08 13:34:38.237  6892  8294 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 13:34:38.239  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 13:34:38.239  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:38.241  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:38.242  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:38.246  4291  8297 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 13:34:38.249  4291  8297 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 13:34:38.254  4291  8298 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 13:34:38.254  4291  8298 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-08 13:34:38.255  8130  8130 I UEI.SmartControl: Supports setup maps: true
,09-08 13:34:38.258  8130  8130 D UEI.SmartControl: QS start statue = true Error code = 0
09-08 13:34:38.258  8130  8130 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-08 13:34:38.258  8130  8130 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-08 13:34:38.258  8130  8130 I UEI.SmartControl: ### init IR Blaster...
09-08 13:34:38.261  8130  8130 D serial_port: Configuring serial port
09-08 13:34:38.262  8130  8130 E UEI.SmartControl: UEIBLaster setting for 616
09-08 13:34:38.262  8130  8130 I UEI.SmartControl: Setting serial record hearder size = 2
09-08 13:34:38.262  8130  8130 I UEI.SmartControl: configuring settings for MAXQ616
09-08 13:34:38.262  8130  8130 I UEI.SmartControl: Get version...
09-08 13:34:38.278  8130  8299 D UEI.SmartControl: serial port data available: 21
,09-08 13:34:38.292  1031  1047 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8300 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-08 13:34:38.296  4291  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 13:34:38.298  4291  4291 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 13:34:38.299  4291  4291 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-08 13:34:38.299  4291  4291 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 13:34:38.301  4291  4291 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 13:34:38.303  8130  8130 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-08 13:34:38.303  8130  8130 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-08 13:34:38.303  8130  8130 I UEI.SmartControl: QS saving settings...
09-08 13:34:38.304  8130  8130 D UEI.SmartControl: IR Blaster version: 25672567
09-08 13:34:38.306  4291  4291 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-08 13:34:38.321  8130  8299 D UEI.SmartControl: serial port data available: 4
,09-08 13:34:38.338  6892  8316 V FormManager: There are no updated forms. The schedule will be deleted.
,09-08 13:34:38.340  6892  8316 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-08 13:34:38.350  8130  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-08 13:34:38.350  8130  8321 I UEI.SmartControl: Device manager: loading config....
09-08 13:34:38.351  8130  8321 D UEI.SmartControl: ----------- loading internal config...
09-08 13:34:38.352  8130  8130 E UEI.SmartControl: Services init done
09-08 13:34:38.352  8130  8130 D UEI.SmartControl: QS Service init finished
09-08 13:34:38.353  8130  8130 D UEI.SmartControl: QS Service version name: 2.1.91
09-08 13:34:38.353  8130  8130 D UEI.SmartControl: QS Service version code: 201091
09-08 13:34:38.353  8130  8130 D UEI.SmartControl: Service requested: Control
,09-08 13:34:38.357  1031  1607 I ActivityManager: Killing 7809:com.google.android.talk/u0a72 (adj 15): empty #17
,09-08 13:34:38.359  8130  8321 E UEI.SmartControl: Loading SETTINGS...
09-08 13:34:38.364  8130  8130 D UEI.SmartControl: Request IControl service: devices are loaded...
09-08 13:34:38.371  8130  8321 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-08 13:34:38.389  8130  8320 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-08 13:34:38.389  8130  8320 D UEI.SmartControl: -----service ready thread exits
,09-08 13:34:38.403  1031  1952 I ActivityManager: Killing 7845:com.android.contacts/u0a19 (adj 15): empty #17
,09-08 13:34:38.443  1031  1533 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:38.444  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-08 13:34:38.446  1031  1533 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:38.447  1031  1533 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:38.448  1031  1533 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:38.449  1031  1533 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-08 13:34:38.451  1031  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-08 13:34:38.452  1031  1539 D ConnectivityService: identical MTU - not setting
09-08 13:34:38.452  1031  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 13:34:38.452  1031  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 13:34:38.452  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 13:34:38.453  1031  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:38.454  1031  1539 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 13:34:38.454  1031  1970 W libprocessgroup: failed to open /acct/uid_10072/pid_7809/cgroup.procs: No such file or directory
09-08 13:34:38.456  8130  8130 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@35b4ed27 that was originally bound here
09-08 13:34:38.456  8130  8130 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@35b4ed27 that was originally bound here
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 13:34:38.456  8130  8130 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-08 13:34:38.457  1597  2064 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 13:34:38.461  1031  1934 W libprocessgroup: failed to open /acct/uid_10019/pid_7845/cgroup.procs: No, such file or directory
,09-08 13:34:38.472  8130  8130 D UEI.SmartControl: Internal service binding...
09-08 13:34:38.472  8300  8300 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 13:34:38.473  8300  8300 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 13:34:38.480  8300  8300 V [BNRBootReceiver]: Boot Receiver Return
,09-08 13:34:38.483  8300  8300 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-08 13:34:38.484  1031  1539 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-08 13:34:38.485  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:38.499  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:38.511  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:38.575  1031  1933 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8327 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-08 13:34:38.578  1031  1933 I ActivityManager: Killing 7869:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-08 13:34:38.635  1031  1607 W libprocessgroup: failed to open /acct/uid_10027/pid_7869/cgroup.procs: No such file or directory
,09-08 13:34:38.678  6595  6704 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-08 13:34:38.680  6595  6704 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-08 13:34:38.681  8327  8327 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 13:34:38.685  6595  6704 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2705b335 Bundle[{}]
09-08 13:34:38.688  6595  6704 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 13:34:38.688  6595  6704 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 13:34:38.690  6595  6704 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 13:34:38.692  6595  6704 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 13:34:38.694  6595  6704 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 13:34:38.696  6595  6704 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 13:34:38.710  6595  8344 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 13:34:38.710  6595  8344 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-08 13:34:38.711  8327  8327 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-08 13:34:38.760  8327  8327 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-08 13:34:38.761  8327  8327 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-08 13:34:38.761  8327  8327 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-08 13:34:38.761  8327  8327 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-08 13:34:38.762  8327  8327 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-08 13:34:38.764  8327  8327 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-08 13:34:38.772  8327  8327 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-08 13:34:38.786  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 13:34:38.790  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 13:34:38.815  8327  8327 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-08 13:34:38.818  8327  8327 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-08 13:34:38.832  8327  8327 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-08 13:34:38.838  8327  8327 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-08 13:34:38.839  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6455
09-08 13:34:38.843  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 13:34:38.850  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:38.859  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:38.865  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:38.866  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:38.868  8327  8327 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-08 13:34:38.870  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-08 13:34:38.871  8130  8248 D UEI.SmartControl: Internal timer expired: 2
09-08 13:34:38.875  6851  6851 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 13:34:38.878  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:38.890  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 13:34:38.895  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 13:34:38.904  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:38.904  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:38.905  8327  8327 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 13:34:38.907  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:38.912  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:38.918  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:38.923  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:38.924  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:38.924  8327  8327 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 13:34:38.927  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:38.936  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:38.944  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:38.953  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:38.953  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:38.954  8327  8327 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 13:34:38.960  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:38.965  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:38.973  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:38.980  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:38.980  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:38.981  8327  8327 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 13:34:38.984  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:38.988  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:38.994  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 13:34:39.000  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:39.000  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:39.000  8327  8327 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 13:34:39.004  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:39.016  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:39.023  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:39.034  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-08 13:34:39.034  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 13:34:39.044  8327  8327 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-08 13:34:39.050  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:39.060  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:39.066  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:39.072  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:39.072  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:39.073  8327  8327 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-08 13:34:39.076  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-08 13:34:39.082  8265  8265 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 13:34:39.089  8265  8265 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 13:34:39.091  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 13:34:39.095  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:39.100  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:39.101  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-08 13:34:39.102  8327  8327 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 13:34:39.103  8327  8327 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 13:34:39.103  8327  8327 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-08 13:34:39.108  2177  8356 D GCM     : Connected
09-08 13:34:39.109  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-08 13:34:39.113  8265  8265 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 13:34:39.115  8265  8265 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 13:34:39.118  6851  6851 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 13:34:39.126  6851  6851 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 13:34:39.127  2177  8356 D GCM     : Message class com.google.e.a.a.q
09-08 13:34:39.133  8327  8327 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-08 13:34:39.133  8327  8327 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-08 13:34:39.134  8327  8327 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-08 13:34:39.135  8327  8327 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-08 13:34:39.135  8327  8327 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-08 13:34:39.145  2177  2177 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-08 13:34:39.157  8327  8327 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-08 13:34:39.158  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 13:34:39.158  8327  8327 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-08 13:34:39.200  8327  8327 D LgDataFeature: LgDataFeature() Constructor: none
09-08 13:34:39.200  8327  8327 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-08 13:34:39.209  8327  8327 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-08 13:34:39.220  8327  8327 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-08 13:34:39.220  8327  8327 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-08 13:34:39.220  8327  8327 V SoundPool: doLoad: loading sample sampleID=1
09-08 13:34:39.220  8327  8359 V SoundPool: Start decode
09-08 13:34:39.220  8327  8359 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-08 13:34:39.221   319  1380 V MediaPlayerService: decode(22, 10857164, 17813)
09-08 13:34:39.221   319  1380 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-08 13:34:39.221   319  1380 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-08 13:34:39.221   319  1380 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-08 13:34:39.221   319  1380 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-08 13:34:39.221   319  1380 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-08 13:34:39.221   319  1380 V MediaPlayerService: player type = 3
09-08 13:34:39.221   319  1380 V AwesomePlayer: AwesomePlayer create()
09-08 13:34:39.222   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:39.222   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:39.222   319  1380 V AwesomePlayer: setAudioSink() 
09-08 13:34:39.222   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:39.222   319  1380 V AudioCache: notify(0xb1432280, 8, 0, 0)
09-08 13:34:39.222   319  1380 V AudioCache: ignored
09-08 13:34:39.222   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:39.222   319  1380 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-08 13:34:39.222   319  1380 V AwesomePlayer: setDataSource_l dataSource
09-08 13:34:39.222   319  1380 V LGParserOSAL: SniffLGParser start
09-08 13:34:39.222   319  1380 V LGParserOSAL: MainType:5, SubType=0
09-08 13:34:39.222   319  1380 V LGParserOSAL: #### check Mime : application/ogg
09-08 13:34:39.222   319  1380 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-08 13:34:39.222   319  1380 E MediaExtractor: Use LGExtractor :application/ogg 
09-08 13:34:39.227  8327  8327 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-08 13:34:39.231  8327  8327 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-08 13:34:39.233  8327  8327 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 13:34:39.233  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 13:34:39.248  8327  8327 V LGMDMManager: Create singleton instance
09-08 13:34:39.253   319  1380 V LGParserOSAL: supported mime: application/ogg
09-08 13:34:39.253   319  1380 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-08 13:34:39.253   319  1380 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-08 13:34:39.253   319  1380 V AwesomePlayer: mBitrate = -1 bits/sec
09-08 13:34:39.253   319  1380 V AwesomePlayer: AudioTrack Setting
09-08 13:34:39.253   319  1380 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-08 13:34:39.253   319  1380 V AwesomePlayer: setAudioSource() 
09-08 13:34:39.253   319  1380 V MediaPlayerService: prepare
09-08 13:34:39.253   319  1380 V AwesomePlayer: prepareAsync_l() 
09-08 13:34:39.254   319  1380 V MediaPlayerService: wait for prepare
09-08 13:34:39.254   319  8360 V AwesomePlayer: onPrepareAsyncEvent() 
09-08 13:34:39.254   319  8360 V AwesomePlayer: initAudioDecoder() 
09-08 13:34:39.254   319  8360 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-08 13:34:39.254   319  8360 V AudioSystem: isOffloadSupported()
09-08 13:34:39.254   319  8360 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,09-08 13:34:39.254   319  8360 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,09-08 13:34:39.254   319  8360 I AudioFlinger: isAudioPlaybackHookOn() false
09-08 13:34:39.254   319  8360 V AwesomePlayer: getUseOffload() = 0 
09-08 13:34:39.254   319  8360 V OMXCodec: OMXCodec::Create
,09-08 13:34:39.254   319  8360 V OMXCodec: findMatchingCodecs()
09-08 13:34:39.254   319  8360 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-08 13:34:39.255   319  8360 V OMXCodec: matchingCodecs.size()=1
09-08 13:34:39.255   319  8360 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-08 13:34:39.259   319  8360 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-08 13:34:39.259   319  8360 V LGCodecAdapter: LG Codec Adapter start
09-08 13:34:39.259   319  8360 V OMXCodec: OMXCodec Createtor
09-08 13:34:39.259   319  8360 V OMXCodec: setComponentRole
09-08 13:34:39.261   319  8360 V OMXCodec: configureCodec protected=0
09-08 13:34:39.261   319  8360 V LGCodecAdapter: called getLGCodecSpecificData
09-08 13:34:39.261   319  8360 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-08 13:34:39.262   319  8360 V LGCodecOSAL: Called LGconfigureCodecMETA
,09-08 13:34:39.262   319  8360 V LGCodecOSAL: Called LGconfigureCodecMSG
09-08 13:34:39.262   319  8360 V LGCodecOSAL: Not support LGCodec
09-08 13:34:39.262   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-08 13:34:39.262   319  8360 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-08 13:34:39.262   319  8360 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-08 13:34:39.262   319  8360 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-08 13:34:39.262   319  8360 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-08 13:34:39.262   319  8360 V AudioSystem: isOffloadSupported()
09-08 13:34:39.262   319  8360 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-08 13:34:39.262   319  8360 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-08 13:34:39.262   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-08 13:34:39.262   319  8360 V OMXCodec: init()
09-08 13:34:39.262   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-08 13:34:39.262   319  8360 V OMXCodec: allocateBuffers
09-08 13:34:39.262   319  8360 V OMXCodec: allocateBuffersOnPort portIndex=0
09-08 13:34:39.262   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
09-08 13:34:39.263   319  8360 V OMXCodec: allocateBuffersOnPort portIndex=1
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-08 13:34:39.263   319  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-08 13:34:39.263   319  8360 V OMXCodec: init() mAsyncCompletion wait!!! 
09-08 13:34:39.263   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-08 13:34:39.263   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-08 13:34:39.264   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-08 13:34:39.264   319  8360 V OMXCodec: init() mAsyncCompletion wait!!! 
09-08 13:34:39.264   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-08 13:34:39.264   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-08 13:34:39.264   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-08 13:34:39.264   319  8360 V OMXCodec: init() mAsyncCompletion wait free! 
09-08 13:34:39.264   319  8360 V AwesomePlayer: finishAsyncPrepare_l() 
09-08 13:34:39.264   319  8360 V AudioCache: notify(0xb1432280, 5, 0, 0)
09-08 13:34:39.264   319  8360 V AudioCache: ignored
09-08 13:34:39.264   319  8360 V AudioCache: notify(0xb1432280, 1, 0, 0)
09-08 13:34:39.264   319  8360 V AudioCache: prepared
09-08 13:34:39.264   319  1380 V AudioCache: wait - success
09-08 13:34:39.264   319  1380 V MediaPlayerService: star,t
09-08 13:34:39.264   319  1380 V AwesomePlayer: play_l() 
09-08 13:34:39.264   319  1380 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-08 13:34:39.264   319  1380 V AwesomePlayer: createAudioPlayer_l
09-08 13:34:39.264   319  1380 V AwesomePlayer: seekAudioIfNecessary_l() 
09-08 13:34:39.264   319  1380 V AwesomePlayer: startAudioPlayer_l() 
09-08 13:34:39.264   319  1380 D AudioPlayer: start of Playback, useOffload 0
09-08 13:34:39.264   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-08 13:34:39.264   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-08 13:34:39.266   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-08 13:34:39.266   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-08 13:34:39.266   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-08 13:34:39.266   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-08 13:34:39.266   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884448
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-08 13:34:39.267   319  8362 V OMXCodec: allocateBuffersOnPort portIndex=1
09-08 13:34:39.267   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,09-08 13:34:39.268   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-08 13:34:39.268   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-08 13:34:39.268   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
09-08 13:34:39.268   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c7150 on output port
09-08 13:34:39.268   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-08 13:34:39.269   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-08 13:34:39.270   319  1380 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-08 13:34:39.271   319  1380 V AudioCache: notify(0xb1432280, 6, 0, 0)
,09-08 13:34:39.271   319  1380 V AudioCache: ignored
09-08 13:34:39.272   319  1380 V MediaPlayerService: wait for playback complete
09-08 13:34:39.273   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.273   319  8363 V AudioCache: memcpy(0xaf104000, 0xb57c6000, 4096)
,09-08 13:34:39.275   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.275   319  8363 V AudioCache: memcpy(0xaf105000, 0xb57c6000, 4096)
09-08 13:34:39.276   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.276   319  8363 V AudioCache: memcpy(0xaf106000, 0xb57c6000, 4096)
09-08 13:34:39.277   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.277   319  8363 V AudioCache: memcpy(0xaf107000, 0xb57c6000, 4096)
09-08 13:34:39.277   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.277   319  8363 V AudioCache: memcpy(0xaf108000, 0xb57c6000, 4096)
09-08 13:34:39.279   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.279   319  8363 V AudioCache: memcpy(0xaf109000, 0xb57c6000, 4096)
09-08 13:34:39.279   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.279   319  8363 V AudioCache: memcpy(0xaf10a000, 0xb57c6000, 4096)
09-08 13:34:39.280   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.280   319  8363 V AudioCache: memcpy(0xaf10b000, 0xb57c6000, 4096)
09-08 13:34:39.281   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.281   319  8363 V AudioCache: memcpy(0xaf10c000, 0xb57c6000, 4096)
09-08 13:34:39.282   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.282   319  8363 V AudioCache: memcpy(0xaf10d000, 0xb57c6000, 4096)
09-08 13:34:39.282   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.282   319  8363 V AudioCache: memcpy(0xaf10e000, 0xb57c6000, 4096)
09-08 13:34:39.283   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.283   319  8363 V AudioCache: memcpy(0xaf10f000, 0xb57c6000, 4096)
09-08 13:34:39.284   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.284   319  8363 V AudioCache: memcpy(0xaf110000, 0xb57c6000, 4096)
09-08 13:34:39.284   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.284   319  8363 V AudioCache: memcpy(0xaf111000, 0xb57c6000, 4096)
09-08 13:34:39.285   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.285   319  8363 V AudioCache: memcpy(0xaf112000, 0xb57c6000, 4096)
09-08 13:34:39.285   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.285   319  8363 V AudioCache: memcpy(0xaf113000, 0xb57c6000, 4096)
09-08 13:34:39.286   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.286   319  8363 V AudioCache: memcpy(0xaf114000, 0xb57c6000, 4096)
09-08 13:34:39.287   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.287   319  8363 V AudioCache: memcpy(0xaf115000, 0xb57c6000, 4096)
09-08 13:34:39.287   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.287   319  8363 V AudioCache: memcpy(0xaf116000, 0xb57c6000, 4096)
09-08 13:34:39.288   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.288   319  8363 V AudioCache: memcpy(0xaf117000, 0xb57c6000, 4096)
09-08 13:34:39.289   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.289   319  8363 V AudioCache: memcpy(0xaf118000, 0xb57c6000, 4096)
09-08 13:34:39.289   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.289   319  8363 V AudioCache: memcpy(0xaf119000, 0xb57c6000, 4096)
09-08 13:34:39.290   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.290   319  8363 V AudioCache: memcpy(0xaf11a000, 0xb57c6000, 4096)
09-08 13:34:39.291   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.291   319  8363 V AudioCache: memcpy(0xaf11b000, 0xb57c6000, 4096)
09-08 13:34:39.291   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.291   319  8363 V AudioCache: memcpy(0xaf11c000, 0xb57c6000, 4096)
09-08 13:34:39.292   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.292   319  8363 V AudioCache: memcpy(0xaf11d000, 0xb57c6000, 4096)
09-08 13:34:39.292   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.292   319  8363 V AudioCache: memcpy(0xaf11e000, 0xb57c6000, 4096)
09-08 13:34:39.292   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.292   319  8363 V AudioCache: mem,cpy(0xaf11f000, 0xb57c6000, 4096)
09-08 13:34:39.292   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.292   319  8363 V AudioCache: memcpy(0xaf120000, 0xb57c6000, 4096)
09-08 13:34:39.294   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.294   319  8363 V AudioCache: memcpy(0xaf121000, 0xb57c6000, 4096)
09-08 13:34:39.295   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.295   319  8363 V AudioCache: memcpy(0xaf122000, 0xb57c6000, 4096)
09-08 13:34:39.295   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.295   319  8363 V AudioCache: memcpy(0xaf123000, 0xb57c6000, 4096)
09-08 13:34:39.295   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.295   319  8363 V AudioCache: memcpy(0xaf124000, 0xb57c6000, 4096)
09-08 13:34:39.297   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.297   319  8363 V AudioCache: memcpy(0xaf125000, 0xb57c6000, 4096)
09-08 13:34:39.297   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.297   319  8363 V AudioCache: memcpy(0xaf126000, 0xb57c6000, 4096)
09-08 13:34:39.297   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.297   319  8363 V AudioCache: memcpy(0xaf127000, 0xb57c6000, 4096)
09-08 13:34:39.297   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.297   319  8363 V AudioCache: memcpy(0xaf128000, 0xb57c6000, 4096)
09-08 13:34:39.298   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.298   319  8363 V AudioCache: memcpy(0xaf129000, 0xb57c6000, 4096)
09-08 13:34:39.299   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.299   319  8363 V AudioCache: memcpy(0xaf12a000, 0xb57c6000, 4096)
09-08 13:34:39.299   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.299   319  8363 V AudioCache: memcpy(0xaf12b000, 0xb57c6000, 4096)
09-08 13:34:39.300   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.300   319  8363 V AudioCache: memcpy(0xaf12c000, 0xb57c6000, 4096)
09-08 13:34:39.300   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.300   319  8363 V AudioCache: memcpy(0xaf12d000, 0xb57c6000, 4096)
,09-08 13:34:39.301   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.301   319  8363 V AudioCache: memcpy(0xaf12e000, 0xb57c6000, 4096)
09-08 13:34:39.301   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.301   319  8363 V AudioCache: memcpy(0xaf12f000, 0xb57c6000, 4096)
09-08 13:34:39.302   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.302   319  8363 V AudioCache: memcpy(0xaf130000, 0xb57c6000, 4096)
09-08 13:34:39.302   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.302   319  8363 V AudioCache: memcpy(0xaf131000, 0xb57c6000, 4096)
09-08 13:34:39.303   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.303   319  8363 V AudioCache: memcpy(0xaf132000, 0xb57c6000, 4096)
09-08 13:34:39.303   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.303   319  8363 V AudioCache: memcpy(0xaf133000, 0xb57c6000, 4096)
09-08 13:34:39.304   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.304   319  8363 V AudioCache: memcpy(0xaf134000, 0xb57c6000, 4096)
09-08 13:34:39.304  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 13:34:39.304   319  8363 V AudioCache: write(0xb57c6000, 4096)
09-08 13:34:39.304   319  8363 V AudioCache: memcpy(0xaf135000, 0xb57c6000, 4096)
09-08 13:34:39.304   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,09-08 13:34:39.305   319  8363 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-08 13:34:39.305   319  8363 V AwesomePlayer: postAudioEOS() 
09-08 13:34:39.305   319  8363 V AudioCache: write(0xb57c6000, 280)
09-08 13:34:39.305   319  8363 V AudioCache: memcpy(0xaf136000, 0xb57c6000, 280)
09-08 13:34:39.305  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-08 13:34:39.306  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8918
09-08 13:34:39.306   319  8360 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-08 13:34:39.306   319  8360 V AwesomePlayer: onStreamDone
09-08 13:34:39.306   319  8360 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-08 13:34:39.306   319  8360 V AudioCache: notify(0xb1432280, 2, 0, 0)
09-08 13:34:39.306   319  8360 V AudioCache: playback complete
09-08 13:34:39.306   319  8360 V AwesomePlayer: pause_l() 
09-08 13:34:39.306   319  8360 V AudioCache: notify(0xb1432280, 7, 0, 0)
09-08 13:34:39.306   319  8360 V AudioCache: ignored
09-08 13:34:39.306   319  8360 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:39.306   319  1380 V AudioCache: wait - success
09-08 13:34:39.306   319  1380 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-08 13:34:39.306   319  8360 D AudioPlayer: Pause Playback at 1068125
09-08 13:34:39.307   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:39.307   319  1380 V AudioCache: notify(0xb1432280, 8, 0, 0)
09-08 13:34:39.307   319  1380 V AudioCache: ignored
09-08 13:34:39.307   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:39.307   319  1380 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-08 13:34:39.307   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-08 13:34:39.307   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-08 13:34:39.307   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-08 13:34:39.307   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c7150 on port 1
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuff,er portIndex=1,bufIndex=1
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-08 13:34:39.307   319  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-08 13:34:39.307   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-08 13:34:39.307   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-08 13:34:39.307   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-08 13:34:39.308  8327  8327 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-08 13:34:39.308   319  1380 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-08 13:34:39.308   319  1380 D AudioPlayer: AudioPlayer releasing audio source
09-08 13:34:39.308   319  1380 D AudioPlayer: AudioPlayer done releasing audio source
09-08 13:34:39.308   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:39.308   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:39.308   319  1380 V AwesomePlayer: ~AwesomePlayer call
09-08 13:34:39.308  8130  8145 I UEI.SmartControl: ------ IControl API: 11
09-08 13:34:39.308  8130  8145 D UEI.SmartControl: File observer start...
09-08 13:34:39.309   319  1380 V AwesomePlayer: reset_l() 
09-08 13:34:39.309   319  1380 V AwesomePlayer: cancelPlayerEvents
09-08 13:34:39.309  8130  8145 E UEI.SmartControl: IR Port is disabled: false
09-08 13:34:39.309  8130  8145 D UEI.SmartControl: Starting file observer...
09-08 13:34:39.309  8327  8359 V SoundPool: close(31)
09-08 13:34:39.309  8327  8359 V SoundPool: pointer = 0x9fe66000, size = 205080, sampleRate = 48000, numChannels = 2
09-08 13:34:39.309  8130  8145 I UEI.SmartControl: Registering callback...
09-08 13:34:39.310  8130  8146 I UEI.SmartControl: ------ IControl API: 19
09-08 13:34:39.310  8130  8146 I UEI.SmartControl: Registering Services Ready callback...
09-08 13:34:39.310  8130  8146 I UEI.SmartControl: Notify client services are ready...
09-08 13:34:39.311  8327  8342 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-08 13:34:39.311  8327  8357 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-08 13:34:39.311  8327  8357 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-08 13:34:39.311  8327  8327 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-08 13:34:39.312  8327  8327 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-08 13:34:39.312  8130  8145 I UEI.SmartControl: ------ IControl API: 8
,09-08 13:34:39.313  8327  8327 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-08 13:34:39.313  8327  8327 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-08 13:34:39.313  8327  8327 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-08 13:34:39.313  8327  8327 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-08 13:34:39.314  8327  8327 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-08 13:34:39.314  8327  8327 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-08 13:34:39.316  8327  8327 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-08 13:34:39.317  8327  8327 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-08 13:34:39.317  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-08 13:34:39.318  8327  8327 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 13:34:39.318  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-08 13:34:39.318  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-08 13:34:39.319  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-08 13:34:39.319  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-08 13:34:39.319  8327  8327 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473334479319]
09-08 13:34:39.320  8327  8327 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-08 13:34:39.323  1031  1047 I ActivityManager: Killing 7931:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-08 13:34:39.333  8327  8364 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
09-08 13:34:39.360  1031  2045 W libprocessgroup: failed to open /acct/uid_10080/pid_7931/cgroup.procs: No such file or directory
,09-08 13:34:39.367  8327  8327 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-08 13:34:39.367  8327  8327 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-08 13:34:39.368  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-08 13:34:39.368  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-08 13:34:39.368  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-08 13:34:39.368  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-08 13:34:39.369  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-08 13:34:39.392  8327  8327 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-08 13:34:40.308  1031  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2437 sc=60 link=72 tx=114.0, 0.0, 0.0  rx=121.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:160697779] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:40.318  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2437 sc=60 link=72 tx=114.0, 0.0, 0.0  rx=121.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:160697790] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:40.318  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-08 13:34:40.333  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-08 13:34:40.455  1031  1534 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-08 13:34:40.477  1031  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:40.492  1031  1113 D Tethering: MasterInitialState.processMessage what=3
,09-08 13:34:40.521  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:40.521  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:40.521  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:40.521  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:40.521  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:40.521  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:40.521  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:40.521  6595  6595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:40.527  6595  6595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:40.537  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-08 13:34:40.542  6400  6439 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-08 13:34:40.555  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 13:34:40.576  2177  2177 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:40.591  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 13:34:40.591  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:40.592  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 13:34:40.592  7365  7365 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-08 13:34:40.596  7365  7365 I AppUp4:CustModeStarterReceiver: onReceive
09-08 13:34:40.600  7365  7365 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f3d274b
09-08 13:34:40.600  7365  7365 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 13:34:40.600  7365  7365 D AppUp4:CustFacade: isPhone : true
09-08 13:34:40.600  7365  7365 D AppUp4:CustModeStarterReceiver: begin check event
09-08 13:34:40.600  7365  7365 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 13:34:40.605  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:40.605  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 13:34:40.607  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-08 13:34:40.613  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-08 13:34:40.613  1031  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:40.619  3431  3431 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:40.631  3431  3431 V DownloadManager: DownloadService onCreate
,09-08 13:34:40.653  3431  8374 I DownloadManager: in removeSpuriousFiles
,09-08 13:34:40.653  3431  8374 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-08 13:34:40.659  3431  3431 V DownloadManager: DownloadService onStartCommand
09-08 13:34:40.662  3431  8375 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-08 13:34:40.672  3431  8375 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f90970b on behalf of 3431
09-08 13:34:40.672  3431  8374 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c17d9e8 on behalf of 3431
09-08 13:34:40.675  1031  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 13:34:40.678  3431  8375 V DownloadManager: processing inserted download 1
09-08 13:34:40.681  3431  8375 V DownloadManager: processing inserted download 4
09-08 13:34:40.681  3323  3323 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-08 13:34:40.681  3323  3323 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:40.681  3323  3323 I LgeMiscReceiver: networkInfo.isConnected() = true
09-08 13:34:40.681  3323  3323 D PhoneState: setPdpRejectCasuse : false
09-08 13:34:40.682  3431  8375 V DownloadManager: processing inserted download 7
09-08 13:34:40.685  8036  8036 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 13:34:40.685  8036  8036 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 13:34:40.685  3431  8375 V DownloadManager: processing inserted download 8
09-08 13:34:40.687  3431  8375 V DownloadManager: processing inserted download 9
09-08 13:34:40.688  3431  8375 V DownloadManager: processing inserted download 10
09-08 13:34:40.693  3431  8375 V DownloadManager: processing inserted download 11
09-08 13:34:40.695  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-08 13:34:40.696  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
,09-08 13:34:40.697  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-08 13:34:40.697  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-08 13:34:40.697  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-08 13:34:40.698  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-08 13:34:40.698  4291  8377 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 13:34:40.698  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-08 13:34:40.698  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
,09-08 13:34:40.698  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-08 13:34:40.698  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-08 13:34:40.698  3431  8374 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-08 13:34:40.701  3431  8374 I DownloadManager: in trimDatabase
09-08 13:34:40.702  3431  8374 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 13:34:40.704  8100  8100 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:40
09-08 13:34:40.704  3431  8374 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3bfca801 on behalf of 3431
09-08 13:34:40.707  8100  8100 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-08 13:34:40.707  8100  8100 D Weather.Utils: 2 : All the weather widget is gone.
09-08 13:34:40.707  8100  8100 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 13:34:40.707  8100  8100 D WeatherAncestor: connectivity changed - connection : true
09-08 13:34:40.707  8100  8100 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@310a5241
09-08 13:34:40.708  8100  8100 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-08 13:34:40.708  8100  8100 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-08 13:34:40.708  8100  8100 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-08 13:34:40.708  8100  8100 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 13:34:40.708  8100  8100 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:34:40
09-08 13:34:40.708  4291  8380 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:40.708  4291  8380 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-08 13:34:40.711  3431  8375 V DownloadManager: processing inserted download 12
09-08 13:34:40.713  3431  8375 V DownloadManager: processing inserted download 13
09-08 13:34:40.716  4291  8377 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 13:34:40.717  3431  8375 V DownloadManager: processing inserted download 14
09-08 13:34:40.720  3431  8375 V DownloadManager: processing inserted download 16
09-08 13:34:40.724  4291  8377 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-08 13:34:40.730  3431  3431 V DownloadManager: DownloadService onDestroy
09-08 13:34:40.732  4291  4291 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-08 13:34:40.733  4291  4291 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,09-08 13:34:40.733  4291  4291 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 13:34:40.735  4291  4291 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 13:34:40.739  4291  4291 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-08 13:34:40.759  6892  8399 V FormManager: There are no updated forms. The schedule will be deleted.
,09-08 13:34:40.762  6892  8399 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-08 13:34:40.783  7986  8378 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 13:34:41.676   315  8410 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-08 13:34:41.685   315  8410 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,09-08 13:34:41.731   315  8410 D libc-netbsd: res_queryN name = www.google.com succeed
,09-08 13:34:41.740  6595  8344 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-08 13:34:41.740  6595  8344 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 13:34:41.740  6595  8344 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:41.741  6595  8344 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:41.741  6595  8344 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 13:34:41.742   315  8415 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-08 13:34:41.743   315  8415 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-08 13:34:41.743   315  8415 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-08 13:34:41.745  6595  8411 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-08 13:34:41.745  6595  8411 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 13:34:41.746  6595  8411 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:41.746  6595  8411 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:41.746  6595  8411 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 13:34:41.752  6595  8417 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 931, name: OutgoingSocketThread/Receiver)
09-08 13:34:41.753  6595  8417 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 931, thread name: OutgoingSocketThread/Receiver)
09-08 13:34:41.753  6595  8417 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 13:34:41.753  6595  8417 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 931, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 13:34:41.756  6595  8416 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 930, name: OutgoingSocketThread/Sender)
09-08 13:34:41.758  6595  8419 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 933, name: IncomingSocketThread/Receiver)
09-08 13:34:41.758  6595  8419 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 933, thread name: IncomingSocketThread/Receiver)
09-08 13:34:41.758  6595  8419 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 13:34:41.758  6595  8419 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 933, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 13:34:41.761  6595  8418 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 932, name: IncomingSocketThread/Sender)
,09-08 13:34:41.803  1031  1535 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-08 13:34:42.332  8130  8141 E UEI.SmartControl: file observer is disposed!
,09-08 13:34:42.587  8151  8186 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-08 13:34:43.342  1031  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2437 sc=60 link=72 tx=74.0, 0.0, 0.0  rx=73.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:160700814] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:43.347  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2437 sc=60 link=72 tx=74.0, 0.0, 0.0  rx=73.5 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:160700819] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:43.347  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 13:34:43.352  8130  8322 D UEI.SmartControl: Internal timer expired: 3
,09-08 13:34:43.352  8130  8322 D UEI.SmartControl: unbind internal service
,09-08 13:34:43.449  8130  8319 D serial_port: close(fd = 24)
,09-08 13:34:43.465  8130  8319 I UEI.SmartControl: Serial port is closed.
,09-08 13:34:44.732  6595  6704 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 942)
09-08 13:34:44.733  6595  6704 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-08 13:34:44.733  6595  6704 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 943)
09-08 13:34:44.736  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:44.736  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a70f7ff added. We now have 2 listener(s)
,09-08 13:34:44.750  1031  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-08 13:34:44.756  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-08 13:34:44.756  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:44.756  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:44.756  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:44.756  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be379cc added. We now have 2 listener(s)
09-08 13:34:44.756  6595  6704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:44.757  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:34:44.761  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:44.764  6595  6704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:44.764  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:44.764  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 13:34:44.764  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:44.764  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:44.764  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:44.764  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:44.764  6595  6704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:44.770  6595  6704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:44.771  6595  6704 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:44.773  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:44.774  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:44.778  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:44.778  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:44.778  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:44.778  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:44.778  6595  6704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a70f7ff removed from the list
09-08 13:34:44.778  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:44.778  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be379cc removed from the list
09-08 13:34:44.778  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:44.778  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:44.788  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 13:34:44.788  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 13:34:44.788  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 13:34:44.788  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:44.789  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:44.793  6595  6704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 13:34:44.796  1031  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:44.804  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 13:34:44.805  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 13:34:44.808  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 13:34:44.810  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:44.811  6595  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-08 13:34:46.357  1031  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2437 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=39.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:160703829] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:46.371  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2437 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=39.8 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:160703843] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:46.372  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 13:34:47.324  1811  1811 I art     : Explicit concurrent mark sweep GC freed 37166(2MB) AllocSpace objects, 18(284KB) LOS objects, 51% free, 29MB/61MB, paused 2.326ms total 68.088ms
,09-08 13:34:47.812  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-08 13:34:47.812  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 13:34:47.831  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:47.831  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:47.831  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:47.831  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a70f7ff not in the list
09-08 13:34:47.831  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:47.831  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be379cc not in the list
09-08 13:34:47.831  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:47.831  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:47.831  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:47.832  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 13:34:47.833  6595  6704 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-08 13:34:47.833  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 13:34:47.841  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 13:34:47.841  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 13:34:47.841  6595  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 13:34:47.841  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:47.842  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 13:34:47.843  6595  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 13:34:47.843  6595  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 13:34:47.843  6595  6595 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 13:34:47.844  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 13:34:47.845  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 13:34:47.845  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:47.845  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:47.851  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 13:34:47.857  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:47.858  6595  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 13:34:47.860  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:47.860  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:47.860  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 13:34:47.860  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 13:34:47.860  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:47.860  6595  6704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 13:34:47.860  6595  6595 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 13:34:47.861  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a70f7ff not in the list
09-08 13:34:47.861  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:47.861  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be379cc not in the list
09-08 13:34:47.861  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:47.861  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:47.861  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:47.862  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 13:34:47.862  6595  6704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 13:34:47.862  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 13:34:47.862  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:47.862  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:47.863  1031  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 13:34:47.864  6595  8423 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 13:34:47.873  7392  7654 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,09-08 13:34:47.874  6595  8423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:47.874  6595  8423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 13:34:47.874  6595  8423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 13:34:47.874  6595  6595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 13:34:47.878  6595  6704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 13:34:47.882  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:47.884  6595  6704 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-08 13:34:49.391  1031  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2437 sc=60 link=72 tx=21.0, 0.0, 0.0  rx=19.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:160706863] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:49.394  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2437 sc=60 link=72 tx=21.0, 0.0, 0.0  rx=19.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:160706866] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:49.394  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 13:34:50.886  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:50.886  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:50.886  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:50.886  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a70f7ff not in the list
,09-08 13:34:50.886  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-08 13:34:50.886  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be379cc not in the list
,09-08 13:34:50.887  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop,
09-08 13:34:50.887  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:50.887  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-08 13:34:50.911  6595  6704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:50.911  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:50.911  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:50.911  6595  6704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a70f7ff not in the list
09-08 13:34:50.911  6595  6704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:50.911  6595  6704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be379cc not in the list
09-08 13:34:50.911  6595  6704 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:50.911  6595  6704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:50.911  6595  6704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:50.912  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 13:34:50.912  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 13:34:50.913  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 13:34:50.913  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 13:34:50.913  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 13:34:50.913  6595  6704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 13:34:50.928  6595  8424 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 962, name: My test thread name)
,09-08 13:34:52.421  1031  1533 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2437 sc=60 link=72 tx=11.0, 0.0, 0.0  rx=9.9 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:160709892] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-08 13:34:52.424  1031  1533 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2437 sc=60 link=72 tx=11.0, 0.0, 0.0  rx=9.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:160709895] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-08 13:34:52.424  1031  1533 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-08 13:34:52.927  6595  6704 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 962
,09-08 13:34:52.927  6595  6704 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 962, name: My test thread name)
,09-08 13:34:52.942  6595  8425 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 963, name: My test thread name)
09-08 13:34:52.942  6595  8425 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 963, thread name: My test thread name)
09-08 13:34:52.942  6595  8425 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 963, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-08 13:34:52.944  6595  6704 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:52.947  6595  8426 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 967, name: My test thread name)
09-08 13:34:52.948  6595  8426 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 967, thread name: My test thread name): Test exception.
09-08 13:34:52.948  6595  8426 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 967, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 13:34:52.954  6595  6704 I jxcore-log: Total number of executed tests:  82
09-08 13:34:52.954  6595  6704 I jxcore-log: 
09-08 13:34:52.955  6595  6704 I jxcore-log: Number of passed tests:  82
09-08 13:34:52.955  6595  6704 I jxcore-log: 
09-08 13:34:52.955  6595  6704 I jxcore-log: Number of failed tests:  0
09-08 13:34:52.955  6595  6704 I jxcore-log: 
09-08 13:34:52.955  6595  6704 I jxcore-log: Number of ignored tests:  0
09-08 13:34:52.955  6595  6704 I jxcore-log: 
09-08 13:34:52.956  6595  6704 I jxcore-log: Total duration:  35569
09-08 13:34:52.956  6595  6704 I jxcore-log: 
09-08 13:34:52.957  6595  6704 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-08 13:34:52.957  6595  6704 I jxcore-log: 
09-08 13:34:52.958  6595  6704 I jxcore-log: My device name is: LGE-LG-D855
09-08 13:34:52.958  6595  6704 I jxcore-log: 
09-08 13:34:52.965  6595  6704 I jxcore-log: WARN testUtils: myNameCallback not set!
09-08 13:34:52.965  6595  6704 I jxcore-log: 
,09-08 13:34:52.981  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:52.981  6595  6704 I jxcore-log: 
09-08 13:34:52.982  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:52.982  6595  6704 I jxcore-log: 
09-08 13:34:52.983  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:52.983  6595  6704 I jxcore-log: 
09-08 13:34:52.984  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:52.984  6595  6704 I jxcore-log: 
09-08 13:34:52.987  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:52.987  6595  6704 I jxcore-log: 
09-08 13:34:52.989  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:52.989  6595  6704 I jxcore-log: 
,09-08 13:34:52.999  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:52.999  6595  6704 I jxcore-log: 
09-08 13:34:53.001  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 13:34:53.001  6595  6704 I jxcore-log: 
09-08 13:34:53.002  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 13:34:53.002  6595  6704 I jxcore-log: 
09-08 13:34:53.003  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 13:34:53.003  6595  6704 I jxcore-log: 
09-08 13:34:53.004  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:53.004  6595  6704 I jxcore-log: 
09-08 13:34:53.005  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:53.005  6595  6704 I jxcore-log: 
09-08 13:34:53.006  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.006  6595  6704 I jxcore-log: 
09-08 13:34:53.007  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.007  6595  6704 I jxcore-log: 
09-08 13:34:53.008  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.008  6595  6704 I jxcore-log: 
09-08 13:34:53.008  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.008  6595  6704 I jxcore-log: 
09-08 13:34:53.009  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.009  6595  6704 I jxcore-log: 
09-08 13:34:53.011  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.011  6595  6704 I jxcore-log: 
09-08 13:34:53.011  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.011  6595  6704 I jxcore-log: 
09-08 13:34:53.012  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 13:34:53.012  6595  6704 I jxcore-log: 
09-08 13:34:53.013  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 13:34:53.013  6595  6704 I jxcore-log: 
,09-08 13:34:53.017  6595  8424 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 962, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
09-08 13:34:53.019  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:53.019  6595  6704 I jxcore-log: 
09-08 13:34:53.020  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:53.020  6595  6704 I jxcore-log: 
09-08 13:34:53.022  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.022  6595  6704 I jxcore-log: 
09-08 13:34:53.024  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.024  6595  6704 I jxcore-log: 
09-08 13:34:53.024  6595  6704 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:53.024  6595  6704 I jxcore-log: 
09-08 13:34:53.302  8427  8427 D AndroidRuntime: 
09-08 13:34:53.302  8427  8427 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 13:34:53.305  8427  8427 D AndroidRuntime: CheckJNI is OFF
,09-08 13:34:53.468  8427  8427 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-08 13:34:53.481  1031  1109 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-08 13:34:53.482  1031  1109 I ActivityManager: Killing 6595:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-08 13:34:53.513  1031  2045 I WindowState: WIN DEATH: Window{eaf4c9e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 13:34:53.517  1031  1538 D WifiService: Client connection lost with reason: 4
,09-08 13:34:53.522  1031  2045 D InputDispatcher: Window went away: Window{eaf4c9e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 13:34:53.607  1031  1109 I ActivityManager:   Force finishing activity ActivityRecord{225dd0bb u0 com.test.thalitest/.MainActivity t6}
,09-08 13:34:53.674   340   352 E GBMv2   : DFP En is all cleared set to be enabled
,09-08 13:34:53.678  1031  1933 W ActivityManager: Spurious death for ProcessRecord{33c483b8 6595:com.test.thalitest/u0a118}, curProc for 6595: null
,09-08 13:34:53.683  1031  1119 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-08 13:34:53.690  1031  1119 I ActivityManager:   Force finishing activity ActivityRecord{225dd0bb u0 com.test.thalitest/.MainActivity t6 f}
09-08 13:34:53.691  1031  1119 W ActivityManager: Duplicate finish request for ActivityRecord{225dd0bb u0 com.test.thalitest/.MainActivity t6 f}
,09-08 13:34:53.714  2027  2027 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-08 13:34:53.716  1935  1951 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-08 13:34:53.717  1935  1951 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ef446b6 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-08 13:34:53.718  1935  1950 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-08 13:34:53.719  1935  1950 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1251bfb7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-08 13:34:53.722  1597  1597 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-08 13:34:53.728  2027  2027 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-08 13:34:53.733  1031  1424 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 13:34:53.745  2449  2614 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 13:34:53.747  1989  1989 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-08 13:34:53.747  2747  2747 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-08 13:34:53.758  7392  7392 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-08 13:34:53.758  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-08 13:34:53.845  4473  4473 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-08 13:34:53.845  4473  4473 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-08 13:34:53.845  4473  4473 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-08 13:34:53.845  4473  4473 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-08 13:34:53.845  4473  4473 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 13:34:53.845  4473  4473 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 13:34:53.845  4473  4473 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 13:34:53.845  4473  4473 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-08 13:34:53.845  4473  4473 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:53.845  4473  4473 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 13:34:53.845  4473  4473 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-08 13:34:53.845  4473  4473 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-08 13:34:53.863  1031  1952 V SIM_STK : Menu title from STK is T-Mobile
,09-08 13:34:53.890  1031  2040 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8458 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-08 13:34:53.891  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-08 13:34:53.892  2027  2120 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-08 13:34:53.895  1597  1597 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-08 13:34:53.896  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-08 13:34:53.898  1899  1899 D ActionManagerService: notifyUserLog: 1000003
09-08 13:34:53.898  2747  4462 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-08 13:34:53.898  2027  2027 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-08 13:34:53.899  2027  2027 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-08 13:34:53.902  2027  2027 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-08 13:34:53.907  6400  6400 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-08 13:34:53.910   395   395 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 22.110ms
09-08 13:34:53.925  4581  4581 I art     : Explicit concurrent mark sweep GC freed 8380(477KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 392us total 217.671ms
,09-08 13:34:53.932   395   395 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 21.201ms
09-08 13:34:53.943  1863  1863 D SplitUIManager: split_name #11 / not available #0
09-08 13:34:53.943  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-08 13:34:53.944  1863  1863 D SplitUIService: removed split : 
,09-08 13:34:53.945  2747  2786 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-08 13:34:53.945  1811  1811 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-08 13:34:53.945  1597  1597 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-08 13:34:53.945  1597  1597 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-08 13:34:53.947  1899  1899 D ActionManagerService: notifyUserLog: 1000004
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , create_time: 1430832262123
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , expire_time: 0
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , display: false
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , animation: false }
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , create_time: 1430832262287
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , expire_time: 0
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , display: false
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , animation: false }
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , create_time: 1472828323917
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , expire_time: 0
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , display: false
09-08 13:34:53.947  2027  2027 I GBoardWebViewUtils: , animation: false }
09-08 13:34:53.947  2747  4462 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-08 13:34:53.952   395   395 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 19.641ms
09-08 13:34:53.954  2177  2177 I ConfigService: onCreate
09-08 13:34:53.954  2177  2177 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-08 13:34:53.956  1031  1779 V SIM_STK : Menu title from STK is T-Mobile
09-08 13:34:53.956  1031  1779 V SIM_STK : Menu title from STK is T-Mobile
09-08 13:34:53.963  2177  2177 I ConfigService: onBind returning update interface
09-08 13:34:53.967  2027  8476 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-08 13:34:53.980  1863  1863 D SplitUIManager: split_name #11 / not available #0
09-08 13:34:53.980  1863  1863 I SplitUIService: split app #11
09-08 13:34:53.987  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 13:34:53.988  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,09-08 13:34:53.996  2177  2177 I art     : Explicit concurrent mark sweep GC freed 10433(689KB) AllocSpace objects, 8(128KB) LOS objects, 52% free, 29MB/61MB, paused 1.244ms total 23.831ms
09-08 13:34:54.020  1031  1031 I art     : Explicit concurrent mark sweep GC freed 102516(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.545ms total 306.412ms
,09-08 13:34:54.029  1031  1119 I art     : WaitForGcToComplete blocked for 309.650ms for cause Explicit
09-08 13:34:54.057  1031  2045 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-08 13:34:54.058  1031  1031 D administrator: Handling package changes for user 0
,09-08 13:34:54.059  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-08 13:34:54.059  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-08 13:34:54.060  7392  7392 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-08 13:34:54.060  2027  2027 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-08 13:34:54.092  1031  1108 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-08 13:34:54.099  1031  1897 V SIM_STK : Menu title from STK is T-Mobile
09-08 13:34:54.141  1031  1119 I art     : Explicit concurrent mark sweep GC freed 6911(430KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.319ms total 110.759ms
,09-08 13:34:54.141  1031  1047 I art     : WaitForGcToComplete blocked for 182.094ms for cause Explicit
,09-08 13:34:54.173  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-08 13:34:54.173  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 13:34:54.173  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-08 13:34:54.176  1031  1572 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-08 13:34:54.242  8427  8427 D AndroidRuntime: Shutting down VM
,09-08 13:34:54.276  1031  1047 I art     : Explicit concurrent mark sweep GC freed 4537(269KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.820ms total 129.849ms
,09-08 13:34:54.278  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-08 13:34:54.286  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 13:34:54.287  1811  1811 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-08 13:34:54.287  2177  2177 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-08 13:34:54.287  2177  2177 I ConfigService: onBind returning config service
,09-08 13:34:54.293  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-08 13:34:54.297  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-08 13:34:54.301  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-08 13:34:54.302  8458  8458 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
09-08 13:34:54.302  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-08 13:34:54.309  1031  1114 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{13de4cec u0 com.lge.launcher2/.Launcher t5} time:159349
09-08 13:34:54.313  1597  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-08 13:34:54.313  1597  1651 D KeyguardModel: createShortcutInfo...
09-08 13:34:54.314  1811  1811 I ConfigFetchService: service connected
09-08 13:34:54.317  1597  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-08 13:34:54.317  1597  1651 D KeyguardModel: createShortcutInfo...
,09-08 13:34:54.321  1597  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-08 13:34:54.322  1597  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 13:34:54.322  1597  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-08 13:34:54.323  2177  2177 I ConfigService: onDestroy
09-08 13:34:54.324  1597  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 13:34:54.324  1597  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 13:34:54.324  1597  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-08 13:34:54.325  1811  8482 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-08 13:34:54.326  1597  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-08 13:34:54.326  1597  1651 D KeyguardModel: createShortcutInfo...
09-08 13:34:54.327  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-08 13:34:54.327  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 13:34:54.330  2027  2157 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-08 13:34:54.330  2027  2157 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,09-08 13:34:54.339  1597  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-08 13:34:54.339  1597  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 13:34:54.341  1597  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 13:34:54.341  1597  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-08 13:34:54.342  1597  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-08 13:34:54.342  1597  1651 D KeyguardModel: createShortcutInfo...
,09-08 13:34:54.345  1597  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 13:34:54.346  1597  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 13:34:54.346  1597  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-08 13:34:54.346  1597  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-08 13:34:54.348  1597  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 13:34:54.348  1597  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-08 13:34:54.349  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-08 13:34:54.350  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-08 13:34:54.350  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-08 13:34:54.351  1597  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-08 13:34:54.351  1597  1651 D KeyguardModel: createShortcutInfo...
09-08 13:34:54.359  2027  2027 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-08 13:34:54.360  5954  8488 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-08 13:34:54.360  2604  2604 D [Concierge]Service: onStartCommand(). Type : 8
09-08 13:34:54.361  2604  2604 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-08 13:34:54.361  2604  2604 D [Concierge]Service: Update widget ID : 11
09-08 13:34:54.362  1597  1597 D KeyguardModel: handleShortcutListChanged...
09-08 13:34:54.362  1597  1597 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-08 13:34:54.363  2027  2027 D [Concierge]WidgetView: change position of spinner
09-08 13:34:54.365  2027  2027 I [Concierge]WidgetView: initWebView(). Time : 1473334494365
09-08 13:34:54.365  2604  2604 D [Concierge]Service: onStartCommand(). Type : 0
09-08 13:34:54.369  1597  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-08 13:34:54.369  1597  1651 D KeyguardModel: createShortcutInfo...
09-08 13:34:54.371  1597  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-08 13:34:54.371  1597  1651 D KeyguardModel: createShortcutInfo...
09-08 13:34:54.372  1597  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 13:34:54.372  1597  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-08 13:34:54.373  1597  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-08 13:34:54.373  1597  1651 D KeyguardModel: createShortcutInfo...
,09-08 13:34:54.374  1597  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 13:34:54.374  1597  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-08 13:34:54.375  1597  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-08 13:34:54.375  1597  1651 D KeyguardModel: createShortcutInfo...
09-08 13:34:54.377  1597  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 13:34:54.377  1597  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-08 13:34:54.379  1811  8490 I PeopleContactsSync: CP2 sync disabled
09-08 13:34:54.381  1597  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-08 13:34:54.381  1597  1651 D KeyguardModel: createShortcutInfo...
09-08 13:34:54.383  1811  4647 I Icing   : doRemovePackageData com.test.thalitest
09-08 13:34:54.394  1597  1597 D KeyguardModel: handleShortcutListChanged...
,09-08 13:34:54.394  1597  1597 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-08 13:34:54.396  1811  8489 W GmsApplication: Using Auth Proxy for data requests.
09-08 13:34:54.403  1811  8489 W GmsApplication: Using Auth Proxy for data requests.
09-08 13:34:54.457  7365  7365 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-08 13:34:54.480  1031  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 13:34:54.487  1031  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-08 13:34:54.489  1031  1119 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8494 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-08 13:34:54.490  2027  2027 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 71699470
09-08 13:34:54.491  2027  2027 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-08 13:34:54.491  2027  2027 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-08 13:34:54.493  2027  2027 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3353bd89
09-08 13:34:54.494  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-08 13:34:54.496  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-08 13:34:54.496  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 13:34:54.502  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-08 13:34:54.502  2027  2027 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-08 13:34:54.502  2027  2027 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-08 13:34:54.520  1031  1971 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8512 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-08 13:34:54.521  1031  1971 I ActivityManager: Killing 7889:com.android.vending/u0a44 (adj 15): empty #17
,09-08 13:34:54.560  2027  2027 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473334362665, New one : 1473334494365
09-08 13:34:54.560  2027  2027 D [Concierge]WidgetView: Unregister all receivers
09-08 13:34:54.561  2027  2027 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-08 13:34:54.562  1031  1897 W libprocessgroup: failed to open /acct/uid_10044/pid_7889/cgroup.procs: No such file or directory
09-08 13:34:54.568  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 13:34:54.570  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-08 13:34:54.571  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-08 13:34:54.573  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,09-08 13:34:54.574  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-08 13:34:54.576  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-08 13:34:54.577  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-08 13:34:54.578  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 13:34:54.579  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-08 13:34:54.588  1811  8484 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-08 13:34:54.589  1811  8484 E DriveAsyncService: disk I/O error (code 3850)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
09-08 13:34:54.589  1811  8484 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 13:34:54.595  8512  8512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 13:34:54.600  8512  8512 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 13:34:54.600  8512  8512 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-08 13:34:54.601  8512  8512 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-08 13:34:54.601  8512  8512 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 13:34:54.601  1031  1933 I ActivityManager: Killing 8300:com.lge.bnr/1000 (adj 15): empty #17
,09-08 13:34:54.617  2027  2027 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created

```
