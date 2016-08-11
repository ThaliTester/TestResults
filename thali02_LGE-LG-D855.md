#### Test 807613742dabe25_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-11 12:27:11.045  6438  6438 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
--------- beginning of system
08-11 12:27:11.051  6438  6438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-11 12:27:11.077  4623  6566 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-11 12:27:11.135  1035  1870 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6570 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-11 12:27:11.161  1035  1716 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:27:11.252  4623  6566 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 175 ms] updated apps [took 175 ms] 
08-11 12:27:11.381  6570  6570 D DocsApplication: Installing DEX configuration.
08-11 12:27:11.401  6570  6570 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-11 12:27:11.406  6570  6570 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{28be5a74 com.google.android.apps.docs}
08-11 12:27:11.426  6570  6570 D TAG     : onCreate()
08-11 12:27:11.458  6570  6570 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-11 12:27:12.211  6605  6605 D AndroidRuntime: 
08-11 12:27:12.211  6605  6605 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 12:27:12.215  6605  6605 D AndroidRuntime: CheckJNI is OFF
08-11 12:27:12.257  1817  4777 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-11 12:27:12.377  6605  6605 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 12:27:12.383  1817  4777 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-11 12:27:12.389  1035  1577 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 12:27:12.404  1942  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-11 12:27:12.408  1035  1577 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-11 12:27:12.417  1035  1577 D ActivityManager: setTaskToReturnTo : TaskRecord{13c212a9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 12:27:12.417  1035  1577 D ActivityManager: setTaskToReturnTo : TaskRecord{13c212a9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 12:27:12.419  1035  1577 D WindowStateEx: AppWindowTokenEx init.. 
08-11 12:27:12.420   341   349 E GBMv2   : DFP En is all cleared set to be enabled
08-11 12:27:12.452  1035  1577 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6630 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 12:27:12.455  6605  6605 D AndroidRuntime: Shutting down VM
08-11 12:27:12.469  1817  4777 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-11 12:27:12.529  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-11 12:27:12.530  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{228d2e30 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 12:27:12.532  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-11 12:27:12.532  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{234f7aa9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 12:27:12.583  6630  6630 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 12:27:12.642  6570  6570 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:27:12.642  6570  6570 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 12:27:12.644  6630  6630 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-11 12:27:12.651  6630  6630 I LibraryLoader: Loading: webviewchromium
08-11 12:27:12.653  6630  6630 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6583-6586)
08-11 12:27:12.653  6630  6630 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:27:12.664  6630  6630 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2bb2835e}
08-11 12:27:12.665  6630  6630 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 12:27:12.665  6630  6630 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 12:27:12.673  6630  6630 I BrowserStartupController: Initializing chromium process, renderers=0
,08-11 12:27:12.674  6630  6630 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:27:12.688   326   326 V AudioPolicyService: registerClient() client 0xb558aae0, uid 10118
08-11 12:27:12.689  6630  6630 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-11 12:27:12.689  6630  6630 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-11 12:27:12.689  6630  6630 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-11 12:27:12.694  1035  1109 D BluetoothManagerService: Message: 20
08-11 12:27:12.695  1035  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@276b1eb:true
08-11 12:27:12.698  6630  6630 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:27:12.698  6630  6630 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:27:12.698  6630  6630 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:27:12.698  6630  6630 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:27:12.698  6630  6630 I Adreno-EGL: Remote Branch: 
08-11 12:27:12.698  6630  6630 I Adreno-EGL: Local Patches: 
08-11 12:27:12.698  6630  6630 I Adreno-EGL: Reconstruct Branch: 
08-11 12:27:12.784  6113  6113 I LockScreenSettings: New app installed broadcast received ..
,08-11 12:27:12.786  6630  6663 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-11 12:27:12.788  6113  6113 I LockScreenSettings: Number of installed packages  1
08-11 12:27:12.788  6630  6630 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-11 12:27:12.802  6630  6630 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 12:27:12.807  6630  6630 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 12:27:12.809  6570  6570 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-11 12:27:12.810  6630  6630 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 12:27:12.812  6630  6630 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 12:27:12.812  6630  6630 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 12:27:12.821  6630  6630 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 12:27:12.838  6630  6630 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:27:12.838  6630  6630 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 12:27:12.849  1035  1978 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:27:12.885  1035  1050 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6689 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a,
,08-11 12:27:12.894  6630  6701 D OpenGLRenderer: Render dirty regions requested: true
08-11 12:27:12.894  6630  6701 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 12:27:12.907  6630  6701 D OpenGLRenderer: Enabling debug mode 0
,08-11 12:27:12.920  6630  6630 D Atlas   : Validating map...
08-11 12:27:12.925  1035  2033 D SplitWindow: check instance of lgWin Window{25cacd8e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 12:27:12.948  6689  6689 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-11 12:27:12.949  6689  6689 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-11 12:27:12.964  6630  6683 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 12:27:12.964  6630  6683 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 12:27:12.996  1035  1870 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6707 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-11 12:27:12.997  1035  1870 I ActivityManager: Killing 5804:com.google.android.gm/u0a64 (adj 15): empty #17
08-11 12:27:13.057  1035  1051 W libprocessgroup: failed to open /acct/uid_10064/pid_5804/cgroup.procs: No such file or directory
,08-11 12:27:13.077  2787  2787 I MusicWidget: mDelayedStopHandler : unbind
,08-11 12:27:13.078  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-11 12:27:13.078  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-11 12:27:13.079  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-11 12:27:13.079  1035  1110 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +552ms (total +659ms)
08-11 12:27:13.080  1035  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2307a02e u0 com.test.thalitest/.MainActivity t6} time:107013
08-11 12:27:13.080  6630  6630 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3782f9c5 time:107013
08-11 12:27:13.083  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-11 12:27:13.084  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-11 12:27:13.084  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-11 12:27:13.085  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-11 12:27:13.085  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-11 12:27:13.086  1035  1050 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@b2fa2fcom.lge.music.MediaPlaybackService$5@3c9083c
08-11 12:27:13.086  2161  2161 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-11 12:27:13.087  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.087  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.088  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.089  2161  2161 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@49f776a
08-11 12:27:13.089  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-11 12:27:13.091  2161  2161 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-11 12:27:13.091  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.095  2161  2161 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-11 12:27:13.096  2161  2161 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-11 12:27:13.096  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.097  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.097  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.098  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.098  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-11 12:27:13.100  2161  2161 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,08-11 12:27:13.102  2161  2161 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
,08-11 12:27:13.102  2161  2161 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-11 12:27:13.102  2161  2161 V MediaPlayer[Native]: reset
08-11 12:27:13.108  2161  2161 V MediaPlayer[Native]: setListener
08-11 12:27:13.109  2161  2161 V MediaPlayer[Native]: disconnect
08-11 12:27:13.109  2161  2161 V MediaPlayer[Native]: destructor
08-11 12:27:13.109   326  2174 V AudioFlinger: releasing 16 from 2161 for -1
08-11 12:27:13.109   326  2174 V AudioFlinger:  decremented refcount to 0
08-11 12:27:13.109   326  2174 V AudioFlinger: purging stale effects
08-11 12:27:13.115  2161  2161 V MediaPlayer[Native]: disconnect
08-11 12:27:13.116  2161  2161 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-11 12:27:13.117  2161  2161 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-11 12:27:13.117  2161  2161 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-11 12:27:13.118  2161  2161 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-11 12:27:13.119  2161  2161 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-11 12:27:13.119  2161  2161 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-11 12:27:13.119  2161  2161 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 931330501
08-11 12:27:13.119  2161  2161 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 931330501
08-11 12:27:13.123  2161  2161 I SmartShareClient: [SmartShareManagerClient] terminate service: 2161/MediaPlaybackService/815835616
08-11 12:27:13.126  2161  2161 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-11 12:27:13.126  2161  2161 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3e3c8f1a
08-11 12:27:13.133  6707  6707 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-11 12:27:13.138  2161  2161 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-11 12:27:13.139  2161  2161 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-11 12:27:13.140  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-11 12:27:13.141  2161  2161 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-11 12:27:13.143  1035  1924 I ActivityManager: Killing 5842:com.google.android.talk/u0a72 (adj 15): empty #17
08-11 12:27:13.145  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 30000
,08-11 12:27:13.166  6707  6707 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 12:27:13.204  6630  6630 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-11 12:27:13.204  6630  6630 I chromium: 
,08-11 12:27:13.215  6630  6630 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 12:27:13.228  1035  1978 W libprocessgroup: failed to open /acct/uid_10072/pid_5842/cgroup.procs: No such file or directory
,08-11 12:27:13.234  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-11 12:27:13.269  6630  6683 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-11 12:27:13.269  6630  6683 I chromium: 
,08-11 12:27:13.293  1035  1906 I ActivityManager: Killing 5667:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-11 12:27:13.316  5645  5645 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-11 12:27:13.316  5645  5645 W System.err: android.os.DeadObjectException
08-11 12:27:13.316  5645  5645 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 12:27:13.316  5645  5645 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 12:27:13.316  5645  5645 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-11 12:27:13.317  5645  5645 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-11 12:27:13.317  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 12:27:13.317  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 12:27:13.317  5645  5645 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:27:13.317  5645  5645 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:27:13.317  5645  5645 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:27:13.317  5645  5645 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:27:13.317  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:27:13.317  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:27:13.317  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:27:13.317  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 12:27:13.317  5645  5645 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-11 12:27:13.317  5645  5645 W System.err: android.os.DeadObjectException
08-11 12:27:13.317  5645  5645 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 12:27:13.317  5645  5645 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 12:27:13.318  5645  5645 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-11 12:27:13.318  5645  5645 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-11 12:27:13.318  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 12:27:13.318  5645  5645 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 12:27:13.318  5645  5645 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:27:13.318  5645  5645 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:27:13.318  5645  5645 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:27:13.318  5645  5645 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:27:13.318  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:27:13.318  5645  5645 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:27:13.318  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:27:13.318  5645  5645 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 12:27:13.318  5645  5645 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-11 12:27:13.318  5645  5645 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-11 12:27:13.384  6630  6731 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-11 12:27:13.402  6630  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 12:27:13.402  6630  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 12:27:13.402  6630  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 12:27:13.402  6630  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 12:27:13.402  6630  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 12:27:13.403  6630  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d28379 added. We now have 1 listener(s)
,08-11 12:27:13.434  1035  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=78540993, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-11 12:27:13.434  1035  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_5667/cgroup.procs: No such file or directory
,08-11 12:27:13.435  1035  2032 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-11 12:27:13.440  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:27:13.445  6630  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-11 12:27:13.446  5645  5645 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-11 12:27:13.449  6630  6731 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:27:13.450  5645  5645 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-11 12:27:13.451  6630  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:27:13.453  6630  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 12:27:13.479  6630  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307cf86c added. We now have 1 listener(s)
08-11 12:27:13.480  6630  6731 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:27:13.485  1035  1445 D WifiService: New client listening to asynchronous messages
,08-11 12:27:13.491  6630  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:27:13.491  6630  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 12:27:13.493  6630  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 12:27:13.493  6630  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 12:27:13.493  6630  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 12:27:13.519  1035  1978 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6737 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 12:27:13.519  5645  5645 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-11 12:27:13.521  6630  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:13.524  1035  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:27:13.527  6630  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-11 12:27:13.538  6630  6731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 12:27:13.538  6630  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:27:13.538  6630  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:13.538  6630  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:13.538  6630  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:13.538  6630  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:27:13.538  6630  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:13.538  6630  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:13.538  6630  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:27:13.538  6630  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 12:27:13.538  6630  6731 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:27:13.541  6630  6731 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 12:27:13.544  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:13.546  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:27:13.570  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,08-11 12:27:13.578  4513  6749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-11 12:27:13.584  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=78540993 [*alarm*], flags=0x0
08-11 12:27:13.594  6630  6630 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 12:27:13.628  6737  6737 D UEI.SmartControl: Quickset Services start...
08-11 12:27:13.630  6737  6737 I UEI.SmartControl: Manufacture = LGE
08-11 12:27:13.630  6737  6737 D UEI.SmartControl: Id = LGNevo
,08-11 12:27:13.632  6737  6737 D UEI.SmartControl: File observer start...
08-11 12:27:13.632  6737  6737 E UEI.SmartControl: IR Port is disabled: false
08-11 12:27:13.633  6737  6737 D UEI.SmartControl: Starting file observer...
08-11 12:27:13.633  6737  6737 D UEI.SmartControl: Extracting JNI libs...
08-11 12:27:13.633  6737  6737 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-11 12:27:13.695  6737  6737 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-11 12:27:13.695  6737  6737 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-11 12:27:13.695  6737  6737 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-11 12:27:13.723  6737  6737 I UEI.SmartControl: --- Selecting new region: 6
08-11 12:27:13.724  6737  6737 I UEI.SmartControl: Model = LG-D855
08-11 12:27:13.725  6737  6737 D UEI.SmartControl: QS Service created
,08-11 12:27:13.734  6737  6737 I UEI.SmartControl: Service initServices...
08-11 12:27:13.737  6737  6737 D UEI.SmartControl: QS start get config
,08-11 12:27:13.763  6737  6737 D UEI.SmartControl: Loading JNI Libs...
,08-11 12:27:13.839   341   351 E GBMv2   : DFP En is all cleared set to be enabled
08-11 12:27:13.840   341   351 E GBMv2   : Set value is all cleared set the max
08-11 12:27:13.840   341   351 I GBMv2   : DFP Enabled. Ignore VFP set
,08-11 12:27:13.991  6737  6737 I UEI.SmartControl: Supports setup maps: true
,08-11 12:27:13.993  6737  6737 D UEI.SmartControl: QS start statue = true Error code = 0
08-11 12:27:13.994  6737  6737 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-11 12:27:13.994  6737  6737 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-11 12:27:13.994  6737  6737 I UEI.SmartControl: ### init IR Blaster...
08-11 12:27:13.999  6737  6737 D serial_port: Configuring serial port
08-11 12:27:14.002  6737  6737 E UEI.SmartControl: UEIBLaster setting for 616
08-11 12:27:14.002  6737  6737 I UEI.SmartControl: Setting serial record hearder size = 2
08-11 12:27:14.002  6737  6737 I UEI.SmartControl: configuring settings for MAXQ616
08-11 12:27:14.002  6737  6737 I UEI.SmartControl: Get version...
08-11 12:27:14.020  6737  6771 D UEI.SmartControl: serial port data available: 21
,08-11 12:27:14.054  6737  6737 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-11 12:27:14.054  6737  6737 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-11 12:27:14.055  6737  6737 I UEI.SmartControl: QS saving settings...
,08-11 12:27:14.058  6737  6737 D UEI.SmartControl: IR Blaster version: 25672567
08-11 12:27:14.075  6737  6771 D UEI.SmartControl: serial port data available: 4
,08-11 12:27:14.112  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-11 12:27:14.114  6737  6737 E UEI.SmartControl: Services init done
08-11 12:27:14.114  6737  6737 D UEI.SmartControl: QS Service init finished
,08-11 12:27:14.117  6737  6737 D UEI.SmartControl: QS Service version name: 2.1.91
08-11 12:27:14.117  6737  6737 D UEI.SmartControl: QS Service version code: 201091
08-11 12:27:14.118  6737  6737 D UEI.SmartControl: Service requested: Control
08-11 12:27:14.127  6737  6777 I UEI.SmartControl: Device manager: loading config....
08-11 12:27:14.128  6737  6777 D UEI.SmartControl: ----------- loading internal config...
,08-11 12:27:14.138  6737  6777 E UEI.SmartControl: Loading SETTINGS...
,08-11 12:27:14.138  6737  6737 D UEI.SmartControl: Request IControl service: devices are loaded...
08-11 12:27:14.141  5645  5645 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-11 12:27:14.141  6737  6758 I UEI.SmartControl: ------ IControl API: 11
08-11 12:27:14.141  1035  1906 I ActivityManager: Killing 5645:com.lge.qremote/u0a112 (adj 15): empty #17
08-11 12:27:14.141  6737  6758 I UEI.SmartControl: Registering callback...
08-11 12:27:14.152  6737  6777 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-11 12:27:14.166  6737  6776 I UEI.SmartControl: Notify AllClients services are ready: 0
08-11 12:27:14.166  6737  6776 D UEI.SmartControl: -----service ready thread exits
08-11 12:27:14.225  1035  2032 W libprocessgroup: failed to open /acct/uid_10112/pid_5645/cgroup.procs: No such file or directory
,08-11 12:27:14.226  6737  6737 D UEI.SmartControl: Internal service binding...
08-11 12:27:14.476  6630  6760 W jxcore-log: Initializing JXcore engine
08-11 12:27:14.476  6630  6760 W jxcore-log: JXcore engine is ready
,08-11 12:27:14.503  6760  6760 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8655]" dev="sockfs" ino=8655 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 12:27:14.503  6760  6760 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-11 12:27:14.503  6760  6760 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10512]" dev="sockfs" ino=10512 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 12:27:14.503  6760  6760 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-11 12:27:14.503  6760  6760 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[29691]" dev="sockfs" ino=29691 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-11 12:27:14.529  6630  6760 W jxcore-log: Starting JXcore engine
,08-11 12:27:14.695  6630  6760 W jxcore-log: Platform android
08-11 12:27:14.695  6630  6760 W jxcore-log: 
08-11 12:27:14.695  6630  6760 W jxcore-log: Process ARCH arm
08-11 12:27:14.695  6630  6760 W jxcore-log: 
,08-11 12:27:15.161  6630  6760 I jxcore-log: JXcore Cordova bridge is ready!
08-11 12:27:15.161  6630  6760 I jxcore-log: 
,08-11 12:27:15.161  6630  6760 W jxcore-log: JXcore engine is started
,08-11 12:27:15.168  6630  6731 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 12:27:15.171  6630  6630 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-11 12:27:15.467   335   420 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-11 12:27:15.469  3201  6790 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-11 12:27:16.741  6570  6570 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-11 12:27:16.746  1035  1577 I ActivityManager: Killing 6256:com.android.calendar/u0a13 (adj 15): empty #17
08-11 12:27:16.819  1035  1906 W libprocessgroup: failed to open /acct/uid_10013/pid_6256/cgroup.procs: No such file or directory
,08-11 12:27:17.732  6570  6653 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-11 12:27:19.111  6737  6778 D UEI.SmartControl: Internal timer expired: 1
,08-11 12:27:19.112  6737  6778 D UEI.SmartControl: unbind internal service
08-11 12:27:19.116  6737  6737 D UEI.SmartControl: Service.onUnbind: IControl
,08-11 12:27:19.119  6737  6737 D UEI.SmartControl: Service.onDestroy
08-11 12:27:19.119  6737  6737 D UEI.SmartControl: Lock is in USE false
08-11 12:27:19.119  6737  6737 D UEI.SmartControl: unbind internal service
08-11 12:27:19.120  6737  6737 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@49f776a
08-11 12:27:19.120  6737  6737 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-11 12:27:19.120  6737  6737 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-11 12:27:19.120  6737  6737 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-11 12:27:19.120  6737  6737 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-11 12:27:19.120  6737  6737 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-11 12:27:19.120  6737  6737 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-11 12:27:19.120  6737  6737 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-11 12:27:19.120  6737  6737 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-11 12:27:19.121  6737  6737 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:27:19.121  6737  6737 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:27:19.121  6737  6737 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:27:19.121  6737  6737 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:27:19.121  6737  6737 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:27:19.121  6737  6737 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:27:19.121  6737  6737 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 12:27:19.121  6737  6737 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@49f776a
08-11 12:27:19.122  6737  6737 D serial_port: close(fd = 25)
08-11 12:27:19.126  6737  6737 I UEI.SmartControl: Serial port is closed.
08-11 12:27:19.127  6737  6737 I UEI.SmartControl: Serial port is closed.
08-11 12:27:19.127  6737  6737 D UEI.SmartControl: Blaster closed
08-11 12:27:19.127  6737  6737 D UEI.SmartControl: Shut down QS...
08-11 12:27:19.127  6737  6737 D UEI.SmartControl: Stopping QS lib
08-11 12:27:19.127  6737  6737 D UEI.SmartControl: QS lib stop result = true
08-11 12:27:19.127  6737  6737 D UEI.SmartControl: Stopped QS lib
08-11 12:27:19.128  6737  6737 D UEI.SmartControl: Stopped file observer...
08-11 12:27:19.128  6737  6737 D UEI.SmartControl: QS shutdown complete
,08-11 12:27:20.158  1817  6472 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-11 12:27:20.168   322  6803 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 12:27:20.169   322  6803 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-11 12:27:20.169   322  6803 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-11 12:27:20.368  1817  1817 I ConfigFetchService: fetch service done; releasing wakelock
,08-11 12:27:20.374  1817  1817 I ConfigFetchService: stopping self
08-11 12:27:20.385  2214  2214 I ConfigService: onDestroy
,08-11 12:27:23.151  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19990
,08-11 12:27:25.273  1035  1092 I ActivityManager: Waited long enough for: ServiceRecord{3be36b91 u0 com.google.android.gms/.wearable.service.WearableService}
,08-11 12:27:27.689  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 12:27:27.689  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-11 12:27:27.724  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
08-11 12:27:27.724  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-11 12:27:27.726  1942  2071 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 12:27:27.726  1942  2071 D LEDHandler: Battery Level Remaining: 100%
08-11 12:27:27.726  1942  2071 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
08-11 12:27:27.727  3882  3994 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 12:27:27.727  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 12:27:27.727  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:27.727  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:27.727  1035  1445 D WifiController: battery changed pluggedType: 2
08-11 12:27:27.730  6707  6707 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-11 12:27:31.496  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 12:27:31.496  6630  6760 I jxcore-log: 
08-11 12:27:31.499  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 12:27:31.499  6630  6760 I jxcore-log: 
,08-11 12:27:31.503  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:27:31.503  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:31.503  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:31.503  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:31.503  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:27:31.503  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:31.503  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:31.503  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:27:31.505  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:31.508  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 12:27:31.508  6630  6760 I jxcore-log: 
,08-11 12:27:31.510  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 12:27:31.510  6630  6760 I jxcore-log: 
08-11 12:27:31.663  1035  1379 V AlarmManager: RTC_WAKEUP set : Alarm{1bdf9f33 type 0 when 1470911246062 com.android.vending} when 1470911246062
,08-11 12:27:31.779  1035  1996 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:27:31.866  6075  6075 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-11 12:27:31.955  6630  6760 I jxcore-log: Running unit tests
08-11 12:27:31.955  6630  6760 I jxcore-log: 
08-11 12:27:31.956  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:27:31.956  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1a75ce added. We now have 2 listener(s)
08-11 12:27:31.957  1035  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:27:31.960  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:27:31.960  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:27:31.960  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:27:31.960  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:27:31.960  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@387d1cef added. We now have 2 listener(s)
08-11 12:27:31.960  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:27:31.960  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:27:31.963  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:31.968  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:27:31.968  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:31.968  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:31.968  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:31.968  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:27:31.968  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:31.968  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:31.968  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:27:31.971  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:27:31.972  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:27:31.973  6630  6760 D ExecuteNativeTests: Running unit tests
08-11 12:27:31.975  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:31.977  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:32.063  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:27:32.063  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 added. We now have 3 listener(s)
,08-11 12:27:32.064  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:27:32.066  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:27:32.066  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 12:27:32.066  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:27:32.066  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 12:27:32.066  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a added. We now have 3 listener(s)
08-11 12:27:32.066  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:27:32.066  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 12:27:32.069  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:32.072  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:27:32.072  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:32.072  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:32.072  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:32.072  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:27:32.072  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:32.072  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:32.072  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:27:32.073  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:32.073  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:27:32.075  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:32.077  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:32.082  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 12:27:32.083  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 12:27:32.083  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 12:27:32.083  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:27:32.093  6630  6760 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-11 12:27:32.094  6630  6760 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 12:27:32.094  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 12:27:32.094  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:27:32.094  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:27:32.095  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:27:32.096  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:32.098  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:27:32.098  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:32.099  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:32.099  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:32.100  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:27:32.100  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 12:27:32.100  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 removed from the list
08-11 12:27:32.100  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:27:32.100  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a removed from the list
08-11 12:27:32.100  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:32.100  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:32.101  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:32.101  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:32.101  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:32.101  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:32.101  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:32.101  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:32.103  6630  6760 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-11 12:27:32.103  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:32.103  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:32.103  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:32.104  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:32.104  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:32.104  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:32.104  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:32.104  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:32.104  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
,08-11 12:27:32.104  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:32.104  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:32.104  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-11 12:27:32.104  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:32.104  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:32.105  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:32.105  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 12:27:32.105  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:32.105  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 12:27:32.109  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 12:27:32.110  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:27:32.110  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:32.110  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:32.110  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:32.110  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:32.110  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:32.110  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:32.110  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:32.110  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:32.110  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:32.110  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:27:32.110  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:32.110  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:32.110  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:32.111  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:32.111  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:32.111  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:32.111  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:32.112  6630  6760 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-11 12:27:32.113  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:32.115  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:27:32.115  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:32.115  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:32.115  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:32.115  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:27:32.115  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:32.115  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:32.115  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:27:32.116  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:32.116  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:27:32.117  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:27:32.118  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:27:32.118  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:27:32.119  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-11 12:27:32.119  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 12:27:32.119  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:32.119  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 12:27:32.122  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 12:27:32.122  1035  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:27:32.125  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 12:27:32.129  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 12:27:32.131  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
,08-11 12:27:32.132  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 12:27:32.132  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 12:27:32.133  6630  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
08-11 12:27:32.133  6630  6760 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 12:27:34.275  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 12:27:34.276  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-11 12:27:34.297  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:34.297  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:27:34.304  1035  1445 D WifiController: battery changed pluggedType: 2
08-11 12:27:34.305  3882  3994 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 12:27:34.307  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
08-11 12:27:34.307  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 12:27:34.308  1942  2071 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 12:27:34.309  1942  2071 D LEDHandler: Battery Level Remaining: 100%
08-11 12:27:34.309  1942  2071 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
08-11 12:27:34.310  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-11 12:27:34.318  6707  6707 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 12:27:37.145  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:37.146  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:37.146  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:27:37.151  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:37.152  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:37.152  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:27:37.152  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:37.152  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:37.152  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:37.152  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:37.152  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:42.153  6630  6760 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 12:27:42.168  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:42.173  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:27:42.173  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:42.173  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:42.173  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:42.173  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:27:42.173  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:42.173  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:42.173  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:27:42.176  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:42.176  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:27:42.178  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:42.180  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:42.180  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:27:42.181  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 12:27:42.181  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 12:27:42.181  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:42.181  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 12:27:42.186  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 12:27:42.189  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:27:42.191  6630  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-11 12:27:42.191  6630  6760 I io.jxcore.node.ConnectionHelper: start: OK
08-11 12:27:42.193  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:42.193  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:42.193  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:42.194  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:42.194  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:42.194  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:27:42.194  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:42.194  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:42.194  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:42.194  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:42.194  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:42.195  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:42.195  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:42.196  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:42.196  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:42.198  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:42.198  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:42.198  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:42.198  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:42.199  6630  6760 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 12:27:42.206  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:42.210  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:27:42.210  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:42.210  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:42.210  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:42.210  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:27:42.210  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:42.210  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:42.210  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:27:42.211  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:42.212  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:27:42.215  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:27:42.219  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:42.219  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:27:42.219  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 12:27:42.219  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 12:27:42.219  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:42.219  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 12:27:42.224  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 12:27:42.226  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:27:42.228  6630  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-11 12:27:42.230  6630  6760 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 12:27:43.153  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-11 12:27:43.161  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-11 12:27:47.230  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:27:47.230  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:27:47.231  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:27:52.243  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:27:52.244  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:27:52.244  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:27:52.253  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.253  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.254  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:27:52.254  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.254  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.254  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.254  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.254  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.258  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.258  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.260  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.260  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:52.262  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.262  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.262  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.262  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.263  6630  6760 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-11 12:27:52.263  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.263  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.263  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:52.264  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.264  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.264  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.264  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.264  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.264  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.264  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.264  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.264  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blueto,othManager: release: 2 listener(s) left
08-11 12:27:52.265  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.265  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:27:52.269  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.269  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:52.270  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.270  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.270  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.270  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.272  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-11 12:27:52.272  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.272  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.272  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:52.273  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.273  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.273  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.273  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.273  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.273  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.273  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.274  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.274  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.274  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.274  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.277  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.277  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 12:27:52.280  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.280  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.280  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.280  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.281  6630  6760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-11 12:27:52.281  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.281  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.281  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:52.282  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.282  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.282  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.282  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.282  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.282  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.282  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.282  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.282  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.282  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.283  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.284  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.284  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:52.285  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.285  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.285  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.285  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.286  6630  6760 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-11 12:27:52.286  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.286  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.286  6630  6760 V io.jxcore.node.StartStopOperationHand,ler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:52.287  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.287  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.287  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.287  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.287  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.287  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.287  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.287  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.287  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.287  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.287  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.290  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.290  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 12:27:52.295  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.295  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.295  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.295  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.296  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 12:27:52.299  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:27:52.299  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:27:52.299  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-11 12:27:52.301  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:27:52.301  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 12:27:52.305  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 12:27:52.305  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:27:52.305  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:27:52.305  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.305  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.305  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:52.306  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.306  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.306  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.306  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.306  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.306  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.306  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.306  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.306  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.306  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.306  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.308  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.308  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:52.309  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.309  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.309  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.309  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.313  6630  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 12:27:52.318  6630  6760 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-11 12:27:52.321  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 12:27:52.325  6630  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 12:27:52.326  6630  6760 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 12:27:52.326  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2,310:2310:2310]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 12:27:52.328  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 12:27:52.329  6630  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-11 12:27:52.329  6630  6760 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 12:27:52.329  6630  6760 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-11 12:27:52.329  6630  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-11 12:27:52.329  6630  6760 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 12:27:52.329  6630  6760 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-11 12:27:52.329  6630  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 12:27:52.329  6630  6760 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 12:27:52.329  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-11 12:27:52.333  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-11 12:27:52.334  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-11 12:27:52.334  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-11 12:27:52.335  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-11 12:27:52.335  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-11 12:27:52.335  6630  6760 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55),
08-11 12:27:52.336  6630  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 12:27:52.336  6630  6760 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-11 12:27:52.336  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.336  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.336  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:27:52.344  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.344  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.344  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.346  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-11 12:27:52.348  6630  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-11 12:27:52.357  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.357  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.357  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.357  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.357  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.357  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.357  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.357  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:27:52.361  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.361  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:52.361  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.361  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.361  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.361  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.362  6630  6760 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-11 12:27:52.363  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.363  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.363  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:52.365  6630  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-11 12:27:52.365  6630  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
08-11 12:27:52.365  6630  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
08-11 12:27:52.365  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.365  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.365  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.365  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.365  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.365  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.366  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.366  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.366  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.366  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.366  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.367  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.367  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:52.368  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.368  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.368  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.368  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettin,gs: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.369  6630  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-11 12:27:52.369  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.369  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.369  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:52.370  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.370  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.370  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.371  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.371  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.371  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.371  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.371  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.371  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.371  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.371  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.378  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.378  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:52.379  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.379  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.379  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.380  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.380  6630  6760 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-11 12:27:52.381  6630  6760 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-11 12:27:52.381  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 12:27:52.381  6630  6760 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-11 12:27:52.381  6630  6760 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 12:27:52.381  6630  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-11 12:27:52.381  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 12:27:52.381  6630  6760 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-11 12:27:52.381  6630  6760 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 12:27:52.381  6630  6760 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 12:27:52.381  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 12:27:52.381  6630  6760 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-11 12:27:52.382  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:52.382  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:52.382  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:52.383  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:52.383  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.383  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.383  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.383  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.383  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.383  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.383  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.383  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.383  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.383  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:27:52.387  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:52.388  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:52.390  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:52.390  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:52.390  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.390  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.391  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:27:52.391  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.391  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.391  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:52.391  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:52.391  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:52.391  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:52.391  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:52.391  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:52.469  6630  6820 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-11 12:27:52.474  6630  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
,08-11 12:27:57.127  1035  1996 I art     : Explicit concurrent mark sweep GC freed 22488(1190KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.744ms total 157.274ms
,08-11 12:27:57.392  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.392  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.392  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:57.392  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.393  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.393  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:57.393  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:57.393  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:57.393  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:27:57.400  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:57.400  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.400  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.401  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:57.401  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.401  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.401  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:57.401  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.401  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.401  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.401  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.405  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:57.405  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:57.406  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:57.407  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 12:27:57.412  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.412  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.418  6630  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 12:27:57.419  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:57.420  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 12:27:57.421  6630  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 12:27:57.421  6630  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-11 12:27:57.423  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:27:57.424  6630  6630 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 12:27:57.424  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 12:27:57.424  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 12:27:57.425  6630  6843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:27:57.426  3882  3901 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-11 12:27:57.427  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:57.427  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 12:27:57.427  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-11 12:27:57.427  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-11 12:27:57.427  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.427  6630  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 12:27:57.428  6630  6630 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 12:27:57.428  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:57.428  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.428  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 12:27:57.428  6630  6760 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 12:27:57.428  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 12:27:57.428  6630  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-11 12:27:57.428  6630  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 12:27:57.428  6630  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 12:27:57.429  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 12:27:57.430  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:27:57.430  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:27:57.431  6630  6760 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 12:27:57.431  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.431  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.432  6630  6760 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:27:57.432  6630  6630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 12:27:57.432  6630  6630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 12:27:57.432  6630  6630 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
0,8-11 12:27:57.432  6630  6630 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:27:57.433  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.433  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:57.433  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:57.433  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:27:57.438  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:57.438  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.438  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.438  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:57.438  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.438  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.438  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:57.438  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.438  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.438  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.438  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.440  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:57.440  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:57.440  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.440  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.441  6630  6760 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-11 12:27:57.442  6630  6760 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 12:27:57.442  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 12:27:57.443  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:27:57.443  6630  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:27:57.444  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:57.444  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:57.444  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:57.444  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:57.444  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.444  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.444  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the ,list
08-11 12:27:57.444  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.444  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.444  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:57.444  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.445  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.445  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.445  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.450  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:27:57.450  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:57.450  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.450  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.452  1035  1716 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:27:57.452  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:27:57.454  1035  1892 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,08-11 12:27:57.454  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:57.455  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:57.455  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:57.455  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:57.455  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.455  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.455  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
,08-11 12:27:57.455  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.455  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.455  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:57.455  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.455  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.455  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.455  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.457  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:57.457  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:57.457  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.457  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.459  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:27:57.459  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:27:57.459  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:27:57.459  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:27:57.459  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.459  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.459  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b904ef5 not in the list
08-11 12:27:57.459  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.460  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.460  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:57.460  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.460  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.460  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.460  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.462  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:27:57.462  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:27:57.462  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.462  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afe748a not in the list
08-11 12:27:57.463  6630  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-11 12:27:57.463  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 12:27:57.464  6630  6760 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-11 12:27:57.464  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 12:27:57.464  6630  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-11 12:27:57.464  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 12:27:57.477  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-11 12:27:57.477  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-11 12:27:57.478  6630  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-11 12:27:57.478  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 12:27:57.478  6630  6760 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-11 12:27:57.478  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 12:27:57.478  6630  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-11 12:27:57.478  6630  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-11 12:27:57.479  6630  6760 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-11 12:27:57.479  6630  6760 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-11 12:27:57.480  6630  6760 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-11 12:27:57.480  6630  6760 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-11 12:27:57.480  6630  6760 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-11 12:27:57.481  6630  6760 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-11 12:27:57.482  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:27:57.482  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bdeae73 added. We now have 3 listener(s)
08-11 12:27:57.482  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:27:57.487  6630  6760 D BluetoothAdapter: enable(): BT is already enabled..!
08-11 12:27:57.488  1035  1959 D WifiServiceImplEx: setWifiEnabled: true pid=6630, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-11 12:27:57.489  1035  1959 D WifiService: setWifiEnabled: true pid=6630, uid=10118
08-11 12:27:57.489  1035  1959 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 12:27:57.492  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:27:57.492  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e98130 added. We now have 4 listener(s)
08-11 12:27:57.493  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:27:57.496  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.497  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e98130 removed from the list
08-11 12:27:57.497  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:57.497  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.497  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:27:57.497  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:27:57.497  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31e8d1a9 added. We now have 4 listener(s)
08-11 12:27:57.498  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:27:57.500  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:27:57.500  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31e8d1a9 removed from the list
08-11 12:27:57.500  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:27:57.500  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:27:57.501  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:27:57.501  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:27:57.501  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b8f32e added. We now have 4 listener(s)
08-11 12:27:57.501  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:27:57.504  1035  1577 D WifiServiceImplEx: setWifiEnabled: false pid=6630, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 12:27:57.505  1035  1577 D WifiService: setWifiEnabled: false pid=6630, uid=10118
08-11 12:27:57.505  1035  1577 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 12:27:57.517  1035  1399 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-11 12:27:57.518  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:27:57.519  1035  1050 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@eff3b38 mBinding = false
08-11 12:27:57.519  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-11 12:27:57.519  1035  1399 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-11 12:27:57.519  1035  1399 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-11 12:27:57.520  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-11 12:27:57.520  1035  1399 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-11 12:27:57.520  1035  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 12:27:57.520  1035  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 12:27:57.521  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 12:27:57.521  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 12:27:57.521  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-11 12:27:57.522  1035  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 12:27:57.522  1035  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-11 12:27:57.529  1035  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-11 12:27:57.529  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-11 12:27:57.529  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.529  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.529  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-11 12:27:57.530  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-11 12:27:57.530  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 12:27:57.530  1035  1399 D WifiNative-wlan0: SET ps 1: returned true
,08-11 12:27:57.531   322   894 D CommandListener: Clearing all IP addresses on wlan0
08-11 12:27:57.533  1035  2861 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.537  1035  1109 D BluetoothManagerService: Message: 2
08-11 12:27:57.538  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 12:27:57.539  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 12:27:57.539  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-11 12:27:57.540  1035  1109 D BluetoothManagerService: Sending off request.
08-11 12:27:57.540  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:27:57.541  3882  6812 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-11 12:27:57.542  3882  3961 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-11 12:27:57.542  3882  3961 D BluetoothAdapterProperties: Setting state to 13
08-11 12:27:57.542  3882  3961 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-11 12:27:57.543  3882  3961 D BluetoothAdapterProperties: onBluetoothDisable()
08-11 12:27:57.543  3882  3961 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-11 12:27:57.545  1035  1109 D BluetoothManagerService: Message: 60
08-11 12:27:57.545  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-11 12:27:57.545  1035  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-11 12:27:57.547  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:57.550  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 12:27:57.552  3882  3882 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:57.552  3882  3882 D BluetoothMapService: STATE_TURNING_OFF
08-11 12:27:57.552  3882  3882 V BluetoothMapService: Handler(): got msg=4
08-11 12:27:57.552  3882  3882 D BluetoothMapService: MAP Service closeService in
08-11 12:27:57.552  3882  3882 D BluetoothMapMasInstance: MAP Service shutdown
08-11 12:27:57.553  3882  4210 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-11 12:27:57.553  3882  4210 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:27:57.553  3882  4210 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-11 12:27:57.553  3882  4210 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-11 12:27:57.553  3882  4210 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-11 12:27:57.553  3882  4210 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-11 12:27:57.553  3882  4210 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-11 12:27:57.553  3882  4210 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-11 12:27:57.556  3882  3882 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 12:27:57.556  3882  3882 V BluetoothMapService: MAP Service closeService out
08-11 12:27:57.556  3882  3882 V BtOppService: Receiver DISABLED_ACTION 
08-11 12:27:57.557  3882  3882 I BtOppRfcommListener: stopping Accept Thread
08-11 12:27:57.557  3882  3882 V BtOppRfcommListener: close mBtServerSocket
08-11 12:27:57.557  3882  3882 V BtOppRfcommListener: waiting for thread to terminate
08-11 12:27:57.557  3882  4228 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:27:57.557  3882  4228 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 12:27:57.558  3882  3882 V BtOppRfcommListener: done waiting for thread to terminate
08-11 12:27:57.559  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.560  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:27:57.560  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.560  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.560  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:57.560  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.560  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:57.560  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:57.560  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:27:57.560  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.560  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:57.560  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:27:57.562  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:57.563  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:57.565  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.565  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:27:57.565  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.565  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.565  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:57.565  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.565  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:57.565  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:57.565  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:27:57.566  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.566  6630  6,630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:27:57.577  1035  1458 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-11 12:27:57.577  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.577  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:27:57.577  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.577  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.577  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:57.577  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.577  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:57.577  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:27:57.577  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:27:57.577  1035  1458 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-11 12:27:57.579  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.579  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:27:57.585  1035  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-11 12:27:57.585  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.585  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.585  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-11 12:27:57.585  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.585  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-11 12:27:57.587  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.587  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:27:57.587  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.587  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.587  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:57.587  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.587  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:27:57.587  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:27:57.587  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:27:57.589  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.589  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:27:57.597  1035  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6861 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 12:27:57.598  3882  3965 D BluetoothAdapterProperties: Scan Mode:20
08-11 12:27:57.598  3882  3961 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-11 12:27:57.599  3882  4242 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:27:57.599  3882  3961 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-11 12:27:57.600  3882  4211 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:27:57.600  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-11 12:27:57.600  3882  4076 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-11 12:27:57.600  3882  4230 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:27:57.601  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.601  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:27:57.601  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.601  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.601  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:57.601  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.601  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:27:57.601  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:27:57.601  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:27:57.602  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.602  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:27:57.602  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:27:57.602  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:27:57.602  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:27:57.603  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:27:57.603  3882  4076 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:27:57.603  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:27:57.603  3882  4076 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:27:57.603  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:27:57.603  3882  4076 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 12:27:57.603  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-11 12:27:57.603  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-11 12:27:57.603  3882  4076 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-11 12:27:57.604  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.604  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:27:57.604  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.604  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.604  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:27:57.604  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.604  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:27:57.604  6630  6630 V io.jxcore.node.Conne,ctivityMonitor:     - is connected/connecting to active network: false
08-11 12:27:57.604  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:27:57.604  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.604  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:27:57.605  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:57.621  1035  1458 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
,08-11 12:27:57.621  1035  1458 D DSQN    : disableDataServiceNotify
08-11 12:27:57.621  1035  1458 D DSQN    : stop dsqn bin
08-11 12:27:57.622   322  6879 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-11 12:27:57.623  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-11 12:27:57.623  1035  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-11 12:27:57.627  1035  1458 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-11 12:27:57.627  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:27:57.627  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:27:57.627  1035  1458 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:27:57.627  1035  1458 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-11 12:27:57.627  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.627  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.628  1035  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-11 12:27:57.628  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-11 12:27:57.628  1035  1458 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-11 12:27:57.628  1035  1458 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-11 12:27:57.628  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-11 12:27:57.633  1035  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6881 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-11 12:27:57.634  3882  3882 V BtOppService: onDestroy
08-11 12:27:57.634  1035  1458 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-11 12:27:57.634  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-11 12:27:57.635  1035  1458 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-11 12:27:57.635  1035  1458 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:27:57.635  1035  1458 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:27:57.635  1035  1458 D NetworkManagementService: Removing idletimer
08-11 12:27:57.635  3882  3882 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-11 12:27:57.635  1035  1458 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:57.636  1035  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:27:57.636  1035  1458 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-11 12:27:57.636  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:27:57.636  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:27:57.636  1035  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.636  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.637  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@351aff2c
08-11 12:27:57.637  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-11 12:27:57.637  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:27:57.637  1035  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:27:57.637  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-11 12:27:57.637  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:27:57.637  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-11 12:27:57.638  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-11 12:27:57.638  1035  1399 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-11 12:27:57.638  1035  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:27:57.639  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:27:57.639  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:27:57.639  1035  1399 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:27:57.639  1035  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:27:57.641  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-11 12:27:57.641  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-11 12:27:57.641  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:57.641  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:57.641  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 12:27:57.641  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-11 12:27:57.642  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-11 12:27:57.642  1035  1390 D LGWifiP2pService: P2pDisablingState
08-11 12:27:57.642  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-11 12:27:57.642  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=-5ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.642  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:57.642  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:57.642  1035  1390 D LGWifiP2pService: p2p socket connection lost
08-11 12:27:57.642  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 12:27:57.642  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-11 12:27:57.642  1035  1390 D LGWifiP2pService: P2pDisabledState
08-11 12:27:57.642  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-11 12:27:57.642  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 12:27:57.642  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 12:27:57.642  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-11 12:27:57.642  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 12:27:57.642  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 12:27:57.642  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-11 12:27:57.643  1035  1559 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.643  1035  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.643  1035  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0,
08-11 12:27:57.643  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-11 12:27:57.643  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-11 12:27:57.644  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-11 12:27:57.644  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 12:27:57.644  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.644  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:27:57.644  1035  1399 D WifiNative-wlan0: SET ps 1: returned true
08-11 12:27:57.644   322   894 D CommandListener: Clearing all IP addresses on wlan0
08-11 12:27:57.648  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-11 12:27:57.648  1035  1399 D WifiNative-p2p0: doBoolean: TERMINATE
08-11 12:27:57.648  1035  1399 D WifiNative-p2p0: TERMINATE: returned true
08-11 12:27:57.649  1035  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 12:27:57.649  1035  1399 E WifiStateMachine: useWiFiOffloading() : false
08-11 12:27:57.649  1035  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 12:27:57.649  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:27:57.649  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-11 12:27:57.649  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-11 12:27:57.649  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:57.650  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:57.650  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 12:27:57.650  1942  1942 D WfdsService: WifiP2pState is changed : false
08-11 12:27:57.650  1942  2268 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-11 12:27:57.650  1942  2268 D WfdsService: Set the WFDS Monitor: false
08-11 12:27:57.651  1942  2268 D WfdsMonitor: WFDS Monitor is stopped
08-11 12:27:57.651  1942  2268 D WfdsService: STATE : WfdsDisabledState - enter
08-11 12:27:57.652  1942  2780 D CtrlSupplicant: Received on exit socket, terminate
08-11 12:27:57.652  1942  2780 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-11 12:27:57.652  1942  2780 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-11 12:27:57.652  1942  2780 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-11 12:27:57.652  1942  2269 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-11 12:27:57.652  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:27:57.652  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-11 12:27:57.652  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-11 12:27:57.652  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:27:57.652  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-11 12:27:57.653  1942  2268 W WfdsService: DefaultState - msg [9445378] is not handled
08-11 12:27:57.655  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.655  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:27:57.655  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.655  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.655  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:27:57.655  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.655  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:27:57.655  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:27:57.655  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:27:57.656  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.656  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:27:57.659  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.659  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:27:57.659  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.659  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bl,uetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.659  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:27:57.659  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.659  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:27:57.659  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:27:57.659  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:27:57.659  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.659  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:27:57.660  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.660  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:27:57.660  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:27:57.660  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:27:57.660  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:27:57.660  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:27:57.660  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:27:57.660  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:27:57.660  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:27:57.661  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:27:57.661  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:27:57.667  6861  6861 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:27:57.667  6861  6861 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-11 12:27:57.667  6861  6861 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:27:57.668  6861  6861 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-11 12:27:57.669  6861  6861 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 12:27:57.669  6861  6861 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-11 12:27:57.679  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 12:27:57.680  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 12:27:57.680  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:27:57.697  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 12:27:57.698  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:27:57.698  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:27:57.698  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:27:57.698  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:27:57.699  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:27:57.700  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-11 12:27:57.700  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:27:57.700  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 12:27:57.703  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:27:57.737  6881  6881 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-11 12:27:57.738  6881  6881 W LG Account v2.2: No ProfileInfo entries
08-11 12:27:57.738  6881  6881 I LG Account v2.2: isEnabled: false
08-11 12:27:57.738  6881  6881 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 12:27:57.738  6881  6881 I Feature : [Lifetracker]Country: EU
08-11 12:27:57.738  6881  6881 I Feature : [Lifetracker]Operator: OPEN
08-11 12:27:57.738  6881  6881 I Feature : [Lifetracker]Ranking support: false
08-11 12:27:57.738  6881  6881 I Feature : [Lifetracker]Comfort support: false
08-11 12:27:57.738  6881  6881 I Feature : [Lifetracker]Accessory: true
08-11 12:27:57.738  6881  6881 I Feature : [Lifetracker]Health device: true
08-11 12:27:57.739  6881  6881 I Feature : [Lifetracker]Extra Pedometer: false
08-11 12:27:57.739  6881  6881 I Feature : [Lifetracker]Blood glucose device: false
08-11 12:27:57.739  6881  6881 I Feature : [Lifetracker]Device Number: 3
08-11 12:27:57.745  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 12:27:57.753  2744  2744 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-11 12:27:57.753  2744  2744 I wpa_supplicant: monitor socket send errors count : 1
08-11 12:27:57.753  2744  2744 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
,08-11 12:27:57.754  1035  2776 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-11 12:27:57.754  1035  2776 D WifiMonitor: Dropping event because (p2p0) is stopped
08-11 12:27:57.755  6861  6861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 12:27:57.773  1035  2861 D DhcpStateMachine: StoppedState
08-11 12:27:57.773  1035  2861 D DhcpStateMachine: StoppedState{ when=-129ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-11 12:27:57.785  1035  2033 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6900 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-11 12:27:57.786  1035  2033 I ActivityManager: Killing 6219:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-11 12:27:57.792  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 12:27:57.792  1035  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-11 12:27:57.792  1035  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 12:27:57.792  1035  2776 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 12:27:57.793  1035  2776 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-11 12:27:57.793  2744  2744 W wpa_supplicant: USIM:  scard_deinit function
08-11 12:27:57.793  1035  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:27:57.793  1035  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:27:57.794  1035  1109 D Tethering: InitialState.processMessage what=4
08-11 12:27:57.794  1035  1399 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=151715
08-11 12:27:57.795  1035  1399 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=151715
08-11 12:27:57.795  1035  1399 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=151715  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-11 12:27:57.795  1035  1399 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=151716  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-11 12:27:57.814   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 27.228ms
,08-11 12:27:57.841   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 731us total 24.758ms
,08-11 12:27:57.863   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 21.224ms
,08-11 12:27:57.871  1035  1399 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-11 12:27:57.872  1035  1399 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-11 12:27:57.873  1035  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-11 12:27:57.873  1035  1959 W libprocessgroup: failed to open /acct/uid_10014/pid_6219/cgroup.procs: No such file or directory
08-11 12:27:57.879  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-11 12:27:57.879  1035  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-11 12:27:57.879  1035  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-11 12:27:57.880  1035  2776 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-11 12:27:57.882  1035  1109 D BluetoothManagerService: Message: 20
08-11 12:27:57.882  1035  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3474b313:true
08-11 12:27:57.886  1035  1399 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-11 12:27:57.907  3882  3882 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 12:27:57.908  3882  3882 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:57.908  3882  3882 V BluetoothPbapReceiver: ***********state = 13
08-11 12:27:57.909  3882  3882 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-11 12:27:57.911  3882  3882 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:57.912  3882  3882 V BluetoothPbapService: state: 13
08-11 12:27:57.912  3882  3882 V BluetoothPbapService: Pbap Service closeService in
,08-11 12:27:57.913  3882  3882 V BluetoothPbapService: successfully stopped pbap service
08-11 12:27:57.914  3882  3882 V BluetoothPbapService: Pbap Service closeService out
08-11 12:27:57.914  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:27:57.914  3882  3882 V BluetoothPbapService: Pbap Service onDestroy
08-11 12:27:57.914  3882  3882 V BluetoothPbapService: Pbap Service closeService in
08-11 12:27:57.914  3882  3882 V BluetoothPbapService: Pbap Service closeService out
08-11 12:27:57.914  3882  3882 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-11 12:27:57.919  1035  1109 D BluetoothManagerService: Message: 30
08-11 12:27:57.925  1035  1109 D BluetoothManagerService: Message: 30
,08-11 12:27:57.929  6861  6861 D LocalBluetoothProfileManager: Adding local MAP profile
08-11 12:27:57.931  6861  6861 D BluetoothMap: Create BluetoothMap proxy object
08-11 12:27:57.931  1035  1109 D BluetoothManagerService: Message: 30
08-11 12:27:57.933  6630  6630 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-11 12:27:57.936  1035  1109 D BluetoothManagerService: Message: 30
08-11 12:27:57.938  6861  6861 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-11 12:27:57.939  6861  6861 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-11 12:27:57.955  6861  6861 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-11 12:27:57.958  6861  6861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-11 12:27:57.965  6861  6861 D DockEventReceiver: finishStartingService: stopping service
08-11 12:27:57.971  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-11 12:27:57.974  6861  6861 D BluetoothInputDevice: Proxy object connected
08-11 12:27:57.974  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 12:27:57.974  6861  6861 D HidProfile: Bluetooth service connected
08-11 12:27:57.974  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:27:57.975  6861  6861 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 12:27:57.975  6861  6861 D PanProfile: Bluetooth service connected
08-11 12:27:57.976  1035  1892 I ActivityManager: Killing 6320:com.android.defcontainer/u0a4 (adj 15): empty #17
08-11 12:27:57.977  6861  6861 D BluetoothMap: Proxy object connected
08-11 12:27:57.978  6861  6861 D MapProfile: Bluetooth service connected
08-11 12:27:57.978  6861  6861 D BluetoothMap: getConnectedDevices()
08-11 12:27:57.979  6861  6861 D BluetoothMap: Bluetooth is Not enabled
08-11 12:27:57.979  6861  6861 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-11 12:27:57.984  6861  6861 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-11 12:27:58.018  1035  2032 W libprocessgroup: failed to open /acct/uid_10004/pid_6320/cgroup.procs: No such file or directory
,08-11 12:27:58.020  1035  1399 D WifiOffDelayIfNotUsed: stopMonitoring
08-11 12:27:58.020  1035  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 12:27:58.020  1035  1399 E WifiStateMachine: useWiFiOffloading() : false
08-11 12:27:58.020  1035  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 12:27:58.023  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-11 12:27:58.024  1942  2268 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-11 12:27:58.024  1942  2268 D WfdsService: Set the WFDS Monitor: false
08-11 12:27:58.024  1942  2268 D WfdsMonitor: WFDS Monitor is stopped
,08-11 12:27:58.024  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-11 12:27:58.024  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:27:58.025  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-11 12:27:58.026  1035  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-11 12:27:58.026  1035  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-11 12:27:58.027  2476  2476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:27:58.028  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:58.032  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:27:58.036  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:27:58.037  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:58.068  6861  6861 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 12:27:58.068  6861  6861 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:27:58.081  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:27:58.083  6861  6861 D BluetoothPermissionRequest: onReceive
08-11 12:27:58.084  6861  6861 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-11 12:27:58.090  1035  2032 I ActivityManager: Killing 6479:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-11 12:27:58.096  6861  6861 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-11 12:27:58.162  3882  3882 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-11 12:27:58.162  3882  3882 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-11 12:27:58.162  1035  1906 W libprocessgroup: failed to open /acct/uid_10008/pid_6479/cgroup.procs: No such file or directory
,08-11 12:27:58.165  3882  3882 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-11 12:27:58.226  1035  1399 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:27:58.227  1035  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-11 12:27:58.228  1035  1959 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6929 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-11 12:27:58.228  3882  3882 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:58.229  3882  3882 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-11 12:27:58.231  3882  3882 V BluetoothFtpService: Ftp Service onStartCommand
08-11 12:27:58.231  3882  3882 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:58.232  3882  3882 V BluetoothFtpService: Ftp Service closeService
08-11 12:27:58.232  3882  3882 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-11 12:27:58.234  3882  3882 V BluetoothFtpService: successfully stopped ftp service
08-11 12:27:58.235  3882  3882 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 12:27:58.235  3882  3882 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 12:27:58.235  3882  3882 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 12:27:58.235  3882  3882 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:58.235  3882  3882 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-11 12:27:58.235  3882  3882 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-11 12:27:58.236  3882  3882 V BluetoothFtpService: Ftp Service onDestroy
08-11 12:27:58.236  3882  3882 V BluetoothFtpService: Ftp Service closeService
08-11 12:27:58.236  3882  3882 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:58.236  3882  3882 V BluetoothSapService: state: 13
08-11 12:27:58.237  3882  3882 V BluetoothSapService: Stopping SAP server process
08-11 12:27:58.238  3882  3882 V BluetoothSapService: Sap Service closeSapService in
08-11 12:27:58.238  3882  3882 V BluetoothSapService: Close listen Socket : 
08-11 12:27:58.238  3882  3882 V BluetoothSapService: Close rfcomm Socket : 
08-11 12:27:58.238  3882  3882 V BluetoothSapService: Close sapd  Socket : 
,08-11 12:27:58.283  1035  1050 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6946 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 12:27:58.285  3882  3882 V BluetoothSapService: Sap Service closeSapService out
08-11 12:27:58.285  3882  3882 V BluetoothSapService: Sap Service onDestroy
08-11 12:27:58.285  3882  3882 V BluetoothSapService: Sap Service closeSapService in
08-11 12:27:58.285  3882  3882 V BluetoothSapService: Close listen Socket : 
08-11 12:27:58.285  3882  3882 V BluetoothSapService: Close rfcomm Socket : 
08-11 12:27:58.285  3882  3882 V BluetoothSapService: Close sapd  Socket : 
08-11 12:27:58.288  3882  3882 V BluetoothSapService: Sap Service closeSapService out
08-11 12:27:58.309  6929  6929 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 12:27:58.332  6946  6946 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 12:27:58.345  1035  1577 I ActivityManager: Killing 6004:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-11 12:27:58.378  1035  2032 W libprocessgroup: failed to open /acct/uid_10011/pid_6004/cgroup.procs: No such file or directory
,08-11 12:27:58.379  6929  6929 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-11 12:27:58.414  6929  6929 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-11 12:27:58.414  6929  6929 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-11 12:27:58.415  6929  6929 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-11 12:27:58.415  6929  6929 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-11 12:27:58.415  6929  6929 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-11 12:27:58.417  6929  6929 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-11 12:27:58.422  6929  6929 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-11 12:27:58.428  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:27:58.432  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 12:27:58.449  6929  6929 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-11 12:27:58.452  6929  6929 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-11 12:27:58.453  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:27:58.456  6929  6929 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-11 12:27:58.460  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 12:27:58.460  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 12:27:58.460  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:27:58.465  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:27:58.477  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:27:58.493  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 12:27:58.494  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 12:27:58.497  6929  6929 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 12:27:58.504  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:27:58.515  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 12:27:58.515  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 12:27:58.515  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 12:27:58.523  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:27:58.532  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:27:58.541  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 12:27:58.543  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:27:58.546  6929  6929 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 12:27:58.607  3882  4076 W bt-btif : ag scb idx 1 not allocated
08-11 12:27:58.607  3882  3965 D bt_hci_bdroid: cleanup
08-11 12:27:58.607  3882  4076 E bt-btif : BTA AG is already disabled, ignoring ...
08-11 12:27:58.607  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:27:58.607  3882  4076 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:27:58.607  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:27:58.607  3882  4076 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:27:58.607  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:27:58.607  3882  4076 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:27:58.608  3882  4078 I bt_lpm  : LPM is already off!!!
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:27:58.608  3882  4199 I bt_userial_mct: exiting userial_read_thread
08-11 12:27:58.608  3882  4199 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:27:58.608  3882  4076 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 12:27:58.608  3882  4076 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-11 12:27:58.608  3882  3965 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-11 12:27:58.609  3882  4078 I bt_vendor: hw_epilog_process
08-11 12:27:58.609  3882  3965 D bt_hci_bdroid: cleanup Finalizing cleanup
08-11 12:27:58.609  3882  3965 D bt_userial_mct: userial_close
08-11 12:27:58.609  3882  3965 E bt_userial_mct: pthread_join() FAILED result:3
08-11 12:27:58.609  3882  3965 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-11 12:27:58.623  1035  2033 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6970 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-11 12:27:58.687  3882  3965 D bt_hci_bdroid: set_power 0
,08-11 12:27:58.687  3882  3965 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-11 12:27:58.687  3882  3965 I bt_vendor: bluetooth satus is on
08-11 12:27:58.687  3882  3965 I bt_vendor: bt-vendor : resetting BT status
08-11 12:27:58.687  3882  3965 I bt_vendor: Starting hciattach daemon
08-11 12:27:58.687  3882  3965 I bt_vendor: try to set false
08-11 12:27:58.690  3882  3965 I bt_vendor: Starting hciattach daemon
08-11 12:27:58.690  3882  3965 I bt_vendor: try to set false
08-11 12:27:58.692  3882  3965 I bt_vendor: cleanup
08-11 12:27:58.693  3882  4076 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-11 12:27:58.694  3882  3965 I GKI_LINUX: GKI_exit_task 0 done
08-11 12:27:58.694  3882  3965 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-11 12:27:58.698  3882  3961 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-11 12:27:58.706  3882  3882 D HeadsetService: Received stop request...Stopping profile...
08-11 12:27:58.707  3882  3882 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-11 12:27:58.708  3882  3882 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 12:27:58.708  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37bcc33f
08-11 12:27:58.708  3882  3994 D HeadsetStateMachine: Exit Disconnected: -1
08-11 12:27:58.710  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-11 12:27:58.710  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-11 12:27:58.710  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-11 12:27:58.711  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-11 12:27:58.712  3882  3882 D A2dpService: Received stop request...Stopping profile...
08-11 12:27:58.713  3882  4040 D A2dpStateMachine: Exit Disconnected: -1
,08-11 12:27:58.716  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-11 12:27:58.718  3882  3882 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-11 12:27:58.720  3882  3961 D BluetoothAdapterState: Stopping profile services that were post enabled
08-11 12:27:58.721  3882  3882 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-11 12:27:58.721  3882  3882 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 12:27:58.721  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37bcc33f
08-11 12:27:58.722  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-11 12:27:58.722  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-11 12:27:58.723  3882  3882 D HidService: Received stop request...Stopping profile...
08-11 12:27:58.723  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37bcc33f
08-11 12:27:58.724  6861  6861 D BluetoothInputDevice: Proxy object disconnected
08-11 12:27:58.724  3882  3882 D HeadsetStateMachine: Unbinding service...
08-11 12:27:58.725  6861  6861 D HidProfile: Bluetooth service disconnected
,08-11 12:27:58.727  3882  3882 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 12:27:58.727  3882  3882 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 12:27:58.727  3882  3882 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 12:27:58.727  3882  3882 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 12:27:58.727  3882  3882 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 12:27:58.727  3882  3882 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 12:27:58.727  3882  3882 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-11 12:27:58.727  3882  3882 D HealthService: Received stop request...Stopping profile...
08-11 12:27:58.728  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37bcc33f
08-11 12:27:58.729  3882  3882 D PanService: Received stop request...Stopping profile...
08-11 12:27:58.729  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37bcc33f
08-11 12:27:58.730  3882  3882 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 12:27:58.731  6861  6861 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 12:27:58.731  6861  6861 D PanProfile: Bluetooth service disconnected
08-11 12:27:58.731  3882  3882 D BtGatt.GattService: Received stop request...Stopping profile...
08-11 12:27:58.731  3882  3882 D BtGatt.GattService: stop()
08-11 12:27:58.731  3882  3882 D BtGatt.AdvertiseManager: advertise clients cleared
08-11 12:27:58.732  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37bcc33f
08-11 12:27:58.733  3882  3882 D BluetoothMapService: Received stop request...Stopping profile...
08-11 12:27:58.733  3882  3882 D BluetoothMapService: stop()
08-11 12:27:58.734  3882  3882 D BluetoothMapEmailAppObserver: deinitObservers()
08-11 12:27:58.734  3882  3882 D BluetoothMapEmailAppObserver: removeReceiver()
08-11 12:27:58.734  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37bcc33f
08-11 12:27:58.736  3882  3882 I BluetoothA2dpServiceJni: cleanupNative
08-11 12:27:58.736  3882  4042 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-11 12:27:58.736  3882  3882 I GKI_LINUX: GKI_exit_task 2 done
08-11 12:27:58.736  3882  3882 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-11 12:27:58.737  6861  6861 D BluetoothMap: Proxy object disconnected
08-11 12:27:58.737  6861  6861 D MapProfile: Bluetooth service disconnected
08-11 12:27:58.737  3882  3882 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 12:27:58.737  3882  3882 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 12:27:58.737  3882  3882 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-11 12:27:58.738  3882  3882 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 12:27:58.738  3882  3882 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 12:27:58.738  3882  3882 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 12:27:58.738  3882  3882 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 12:27:58.739  3882  3882 V BluetoothMapService: Handler(): got msg=4
08-11 12:27:58.739  3882  3882 D BluetoothMapService: MAP Service closeService in
08-11 12:27:58.739  3882  3882 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 12:27:58.739  3882  3882 V BluetoothMapService: MAP Service closeService out
08-11 12:27:58.740  3882  3961 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-11 12:27:58.741  3882  3961 D BluetoothAdapterProperties: Setting state to 10
08-11 12:27:58.741  3882  3961 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-11 12:27:58.741  1035  1109 D BluetoothManagerService: Message: 60
08-11 12:27:58.741  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-11 12:27:58.741  1035  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-11 12:27:58.742  3882  3961 I BluetoothAdapterState: Entering OffState
08-11 12:27:58.742  6861  6878 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 12:27:58.742  3882  3882 D BluetoothMapService: cleanup()
08-11 12:27:58.742  3882  3882 D BluetoothMapService: MAP Service closeService in
08-11 12:27:58.742  3882  3882 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 12:27:58.742  3882  3882 V BluetoothMapService: MAP Service closeService out
08-11 12:27:58.743  1853  3990 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:27:58.743  6861  6880 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 12:27:58.744  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:27:58.744  1035  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:27:58.745  1853  2768 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:27:58.745  6861  6878 D BluetoothPan: onBluetoothStateChange on: false
08-11 12:27:58.746  1035  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 12:27:58.746  6861  6880 D BluetoothMap: onBluetoothStateChange: up=false
08-11 12:27:58.747  1035  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-11 12:27:58.747  1035  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-11 12:27:58.749  1035  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-11 12:27:58.749  1035  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-11 12:27:58.750  1035  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@eff3b38 mBinding = false
08-11 12:27:58.750  1035  1109 D BluetoothManagerService: Sending unbind request.
08-11 12:27:58.752  1035  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-11 12:27:58.757  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:58.757  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 12:27:58.758  1942  2095 D LGBluetoothAPIService: Message: 2
08-11 12:27:58.758  1942  2095 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@7ece82e mBinding = false
08-11 12:27:58.758  1942  2095 D LGBluetoothAPIService: Sending unbind request.
08-11 12:27:58.758  6861  6861 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-11 12:27:58.759  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:58.760  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:58.760  6861  6861 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-11 12:27:58.761  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:27:58.761  6861  6861 D LGBluetoothEventManager: [BTUI] clear device connection state
08-11 12:27:58.763  3882  3965 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-11 12:27:58.764  3882  3882 I GKI_LINUX: GKI_exit_task 1 done
08-11 12:27:58.764  3882  3882 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-11 12:27:58.764  3882  3882 I BluetoothServiceJni: cleanupNative: return from cleanup
08-11 12:27:58.764  3882  3882 I art     : --- WEIRD: removing null entry 246
08-11 12:27:58.764  3882  3882 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-11 12:27:58.764  3882  3882 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-11 12:27:58.765  6861  6861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 12:27:58.766  3882  3882 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-11 12:27:58.768  1604  1604 D BluetoothAdapter: 557810103: getState() :  mService = null. Returning STATE_OFF
08-11 12:27:58.768  1604  1604 D BluetoothAdapter: 557810103: getState() :  mService = null. Returning STATE_OFF
08-11 12:27:58.770  3882  3882 I art     : System.exit called, status: 0
08-11 12:27:58.771  3882  3882 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-11 12:27:58.781  6861  6861 D DockEventReceiver: finishStartingService: stopping service
08-11 12:27:58.782  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 12:27:58.790  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 12:27:58.796   326   326 V AudioFlinger: 3882 died, releasing its sessions
08-11 12:27:58.796   326   326 V AudioFlinger:  pid 1853 @ 0
08-11 12:27:58.796   326   326 V AudioFlinger:  pid 3477 @ 1
08-11 12:27:58.796   326   326 V AudioFlinger:  pid 3477 @ 2
08-11 12:27:58.798  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:27:58.798  6861  6861 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-11 12:27:58.817  1035  1978 I ActivityManager: Process com.android.bluetooth (pid 3882) has died
08-11 12:27:58.817  1035  1978 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-11 12:27:58.827  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:27:58.838  6970  6991 W FormManager: Network not available. Please check & try again.
,08-11 12:27:58.851  6970  6992 V FormManager: Network unavailable.
,08-11 12:27:58.851  6861  6861 D BluetoothPermissionRequest: onReceive
08-11 12:27:58.858  6861  6861 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-11 12:27:58.861  6970  6992 V FormManager: Network unavailable.
,08-11 12:27:58.867  6861  6861 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-11 12:27:58.874  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 12:27:58.874  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 12:27:58.874  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 12:27:58.874  6861  6861 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-11 12:27:58.875  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 12:27:58.886  6861  6861 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-11 12:27:58.887  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 12:27:58.887  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 12:27:58.887  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 12:27:58.887  6861  6861 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 12:27:58.888  6861  6861 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 12:27:58.888  6861  6861 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 12:27:58.953  1035  2032 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7000 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-11 12:27:58.956  1035  2032 I ActivityManager: Killing 6028:com.android.contacts/u0a19 (adj 15): empty #17
,08-11 12:27:59.001  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 12:27:59.001  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:27:59.003  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:27:59.004  1035  1051 W libprocessgroup: failed to open /acct/uid_10019/pid_6028/cgroup.procs: No such file or directory
08-11 12:27:59.011  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:27:59.018  4321  7017 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 12:27:59.021  4321  7018 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 12:27:59.022  4321  7018 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 12:27:59.027  6900  6900 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-11 12:27:59.027  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 12:27:59.027  7000  7000 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-11 12:27:59.027  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:27:59.028  7000  7000 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:27:59.029  7000  7000 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-11 12:27:59.030  7000  7000 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-11 12:27:59.031  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-11 12:27:59.035  6970  7020 W FormManager: Network not available. Please check & try again.
08-11 12:27:59.040  6970  7021 V FormManager: Network unavailable.
,08-11 12:27:59.046  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:27:59.048  6970  7021 V FormManager: Network unavailable.
08-11 12:27:59.054  7000  7000 D BluetoothAdapterApp: Loading JNI Library
08-11 12:27:59.067  6929  6929 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-11 12:27:59.068  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-11 12:27:59.068  6929  6929 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-11 12:27:59.089  7000  7000 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@28be5a74 Instance Count = 1
,08-11 12:27:59.094  7000  7000 D BluetoothAdapterApp: onCreate
08-11 12:27:59.109  6929  6929 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:27:59.109  6929  6929 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:27:59.117  7000  7000 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-11 12:27:59.118  7000  7000 D ProfileConfigQcom: Adding HeadsetService
08-11 12:27:59.118  7000  7000 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-11 12:27:59.118  7000  7000 D ProfileConfigQcom: Adding A2dpService
08-11 12:27:59.118  7000  7000 D ProfileConfigQcom: [BTUI] HidService is supported
08-11 12:27:59.118  6929  6929 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-11 12:27:59.118  7000  7000 D ProfileConfigQcom: Adding HidService
08-11 12:27:59.119  7000  7000 D ProfileConfigQcom: [BTUI] HealthService is supported
08-11 12:27:59.119  7000  7000 D ProfileConfigQcom: Adding HealthService
08-11 12:27:59.119  7000  7000 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-11 12:27:59.119  6929  6929 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-11 12:27:59.119  6929  6929 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-11 12:27:59.119  6929  6929 V SoundPool: doLoad: loading sample sampleID=1
08-11 12:27:59.120  6929  6929 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-11 12:27:59.120  7000  7000 D ProfileConfigQcom: [BTUI] PanService is supported
08-11 12:27:59.120  7000  7000 D ProfileConfigQcom: Adding PanService
08-11 12:27:59.120  7000  7000 D ProfileConfigQcom: [BTUI] GattService is supported
08-11 12:27:59.121  7000  7000 D ProfileConfigQcom: Adding GattService
08-11 12:27:59.121  7000  7000 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-11 12:27:59.121  7000  7000 D ProfileConfigQcom: Adding BluetoothMapService
,08-11 12:27:59.121  7000  7000 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-11 12:27:59.123  7000  7000 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-11 12:27:59.124  6929  7026 V SoundPool: Start decode
08-11 12:27:59.124  6929  7026 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-11 12:27:59.125   326  1397 V MediaPlayerService: decode(23, 10857164, 17813)
08-11 12:27:59.125   326  1397 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-11 12:27:59.125   326  1397 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-11 12:27:59.125   326  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-11 12:27:59.125   326  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-11 12:27:59.125   326  1397 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
,08-11 12:27:59.125   326  1397 V MediaPlayerService: player type = 3
08-11 12:27:59.125   326  1397 V AwesomePlayer: AwesomePlayer create()
08-11 12:27:59.126  6737  6737 D UEI.SmartControl: QS Service created
08-11 12:27:59.127  6929  6929 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-11 12:27:59.128   326  1397 V AwesomePlayer: reset_l() 
08-11 12:27:59.128   326  1397 V AwesomePlayer: cancelPlayerEvents
08-11 12:27:59.128   326  1397 V AwesomePlayer: setAudioSink() 
08-11 12:27:59.128   326  1397 V AwesomePlayer: reset_l() 
08-11 12:27:59.128   326  1397 V AudioCache: notify(0xb16a6b80, 8, 0, 0)
08-11 12:27:59.128   326  1397 V AudioCache: ignored
08-11 12:27:59.128   326  1397 V AwesomePlayer: cancelPlayerEvents
,08-11 12:27:59.128   326  1397 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-11 12:27:59.128   326  1397 V AwesomePlayer: setDataSource_l dataSource
08-11 12:27:59.128   326  1397 V LGParserOSAL: SniffLGParser start
08-11 12:27:59.128   326  1397 V LGParserOSAL: MainType:5, SubType=0
08-11 12:27:59.128   326  1397 V LGParserOSAL: #### check Mime : application/ogg
08-11 12:27:59.129   326  1397 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-11 12:27:59.129   326  1397 E MediaExtractor: Use LGExtractor :application/ogg 
08-11 12:27:59.130  6861  6861 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-11 12:27:59.142  7000  7000 V LGMDMManagerInternal: Create singleton instance
,08-11 12:27:59.148  6929  6929 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-11 12:27:59.149  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-11 12:27:59.150  6737  6737 I UEI.SmartControl: Service initServices...
08-11 12:27:59.151  6737  6737 D UEI.SmartControl: QS start get config
08-11 12:27:59.162  6929  6929 V LGMDMManager: Create singleton instance
08-11 12:27:59.179   326  1397 V LGParserOSAL: supported mime: application/ogg
08-11 12:27:59.179   326  1397 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-11 12:27:59.179   326  1397 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-11 12:27:59.179   326  1397 V AwesomePlayer: mBitrate = -1 bits/sec
08-11 12:27:59.179   326  1397 V AwesomePlayer: AudioTrack Setting
08-11 12:27:59.179   326  1397 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-11 12:27:59.179   326  1397 V AwesomePlayer: setAudioSource() 
08-11 12:27:59.179   326  1397 V MediaPlayerService: prepare
08-11 12:27:59.179   326  1397 V AwesomePlayer: prepareAsync_l() 
08-11 12:27:59.179   326  1397 V MediaPlayerService: wait for prepare
,08-11 12:27:59.180   326  7027 V AwesomePlayer: onPrepareAsyncEvent() 
08-11 12:27:59.180   326  7027 V AwesomePlayer: initAudioDecoder() 
08-11 12:27:59.180   326  7027 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-11 12:27:59.181   326  7027 V AudioSystem: isOffloadSupported()
08-11 12:27:59.181   326  7027 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-11 12:27:59.181   326  7027 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-11 12:27:59.181   326  7027 I AudioFlinger: isAudioPlaybackHookOn() false
08-11 12:27:59.181   326  7027 V AwesomePlayer: getUseOffload() = 0 
08-11 12:27:59.181   326  7027 V OMXCodec: OMXCodec::Create
08-11 12:27:59.181   326  7027 V OMXCodec: findMatchingCodecs()
08-11 12:27:59.181   326  7027 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-11 12:27:59.181   326  7027 V OMXCodec: matchingCodecs.size()=1
08-11 12:27:59.181   326  7027 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-11 12:27:59.182   326  7027 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-11 12:27:59.182   326  7027 V LGCodecAdapter: LG Codec Adapter start
08-11 12:27:59.182   326  7027 V OMXCodec: OMXCodec Createtor
08-11 12:27:59.182   326  7027 V OMXCodec: setComponentRole
08-11 12:27:59.182   326  7027 V OMXCodec: configureCodec protected=0
08-11 12:27:59.182   326  7027 V LGCodecAdapter: called getLGCodecSpecificData
08-11 12:27:59.182   326  7027 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-11 12:27:59.183   326  7027 V LGCodecOSAL: Called LGconfigureCodecMETA
08-11 12:27:59.183   326  7027 V LGCodecOSAL: Called LGconfigureCodecMSG
08-11 12:27:59.183   326  7027 V LGCodecOSAL: Not support LGCodec
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-11 12:27:59.183   326  7027 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-11 12:27:59.183   326  7027 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-11 12:27:59.183   326  7027 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-11 12:27:59.183   326  7027 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-11 12:27:59.183   326  7027 V AudioSystem: isOffloadSupported()
08-11 12:27:59.183   326  7027 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-11 12:27:59.183   326  7027 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-11 12:27:59.183   326  7027 V OMXCodec: init()
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-11 12:27:59.183   326  7027 V OMXCodec: allocateBuffers
08-11 12:27:59.183   326  7027 V OMXCodec: allocateBuffersOnPort portIndex=0
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-11 12:27:59.183   32,6  7027 V OMXCodec: allocateBuffersOnPort portIndex=1
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-11 12:27:59.183   326  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-11 12:27:59.183   326  7027 V OMXCodec: init() mAsyncCompletion wait!!! 
08-11 12:27:59.183   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-11 12:27:59.183   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-11 12:27:59.184   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-11 12:27:59.184   326  7027 V OMXCodec: init() mAsyncCompletion wait!!! 
08-11 12:27:59.186   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-11 12:27:59.186   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-11 12:27:59.186   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-11 12:27:59.187   326  7027 V OMXCodec: init() mAsyncCompletion wait free! 
08-11 12:27:59.187   326  7027 V AwesomePlayer: finishAsyncPrepare_l() 
08-11 12:27:59.187   326  7027 V AudioCache: notify(0xb16a6b80, 5, 0, 0)
08-11 12:27:59.187   326  7027 V AudioCache: ignored
08-11 12:27:59.187   326  7027 V AudioCache: notify(0xb16a6b80, 1, 0, 0)
08-11 12:27:59.187   326  7027 V AudioCache: prepared
08-11 12:27:59.187   326  1397 V AudioCache: wait - success
08-11 12:27:59.187   326  1397 V MediaPlayerService: start
08-11 12:27:59.187   326  1397 V AwesomePlayer: play_l() 
08-11 12:27:59.187   326  1397 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-11 12:27:59.187   326  1397 V AwesomePlayer: createAudioPlayer_l
08-11 12:27:59.187   326  1397 V AwesomePlayer: seekAudioIfNecessary_l() 
08-11 12:27:59.187   326  1397 V AwesomePlayer: startAudioPlayer_l() 
08-11 12:27:59.187   326  1397 D AudioPlayer: start of Playback, useOffload 0
08-11 12:27:59.187   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-11 12:27:59.187   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
,08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-11 12:27:59.190   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-11 12:27:59.191   326  7029 V OMXCodec: allocateBuffersOnPort portIndex=1
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c5510 on output port
,08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-11 12:27:59.191   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-11 12:27:59.192   326  1397 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-11 12:27:59.193   326  1397 V AudioCache: notify(0xb16a6b80, 6, 0, 0)
08-11 12:27:59.193   326  1397 V AudioCache: ignored
08-11 12:27:59.193   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.193   326  7030 V AudioCache: memcpy(0xaf004000, 0xb16e3000, 4096),
08-11 12:27:59.193   326  1397 V MediaPlayerService: wait for playback complete
08-11 12:27:59.194   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.194   326  7030 V AudioCache: memcpy(0xaf005000, 0xb16e3000, 4096)
08-11 12:27:59.195   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.195   326  7030 V AudioCache: memcpy(0xaf006000, 0xb16e3000, 4096)
08-11 12:27:59.195   326  7030 V AudioCache: write(0xb16e3000, 4096)
,08-11 12:27:59.195   326  7030 V AudioCache: memcpy(0xaf007000, 0xb16e3000, 4096)
08-11 12:27:59.196   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.196   326  7030 V AudioCache: memcpy(0xaf008000, 0xb16e3000, 4096)
08-11 12:27:59.197   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.197   326  7030 V AudioCache: memcpy(0xaf009000, 0xb16e3000, 4096)
08-11 12:27:59.197   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.197   326  7030 V AudioCache: memcpy(0xaf00a000, 0xb16e3000, 4096)
08-11 12:27:59.198   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.198   326  7030 V AudioCache: memcpy(0xaf00b000, 0xb16e3000, 4096)
,08-11 12:27:59.198   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.198   326  7030 V AudioCache: memcpy(0xaf00c000, 0xb16e3000, 4096)
08-11 12:27:59.199   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.199   326  7030 V AudioCache: memcpy(0xaf00d000, 0xb16e3000, 4096)
08-11 12:27:59.200   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.200   326  7030 V AudioCache: memcpy(0xaf00e000, 0xb16e3000, 4096)
08-11 12:27:59.200   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.200   326  7030 V AudioCache: memcpy(0xaf00f000, 0xb16e3000, 4096)
08-11 12:27:59.201   326  7030 V AudioCache: write(0xb16e3000, 4096)
,08-11 12:27:59.201   326  7030 V AudioCache: memcpy(0xaf010000, 0xb16e3000, 4096)
08-11 12:27:59.202   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.202   326  7030 V AudioCache: memcpy(0xaf011000, 0xb16e3000, 4096)
08-11 12:27:59.202   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.203   326  7030 V AudioCache: memcpy(0xaf012000, 0xb16e3000, 4096)
08-11 12:27:59.203   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.203   326  7030 V AudioCache: memcpy(0xaf013000, 0xb16e3000, 4096)
08-11 12:27:59.204   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.204   326  7030 V AudioCache: memcpy(0xaf014000, 0xb16e3000, 4096)
,08-11 12:27:59.204   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.204   326  7030 V AudioCache: memcpy(0xaf015000, 0xb16e3000, 4096)
08-11 12:27:59.205   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.205   326  7030 V AudioCache: memcpy(0xaf016000, 0xb16e3000, 4096)
08-11 12:27:59.205   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.205   326  7030 V AudioCache: memcpy(0xaf017000, 0xb16e3000, 4096)
,08-11 12:27:59.206   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.206   326  7030 V AudioCache: memcpy(0xaf018000, 0xb16e3000, 4096)
08-11 12:27:59.215   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.215   326  7030 V AudioCache: memcpy(0xaf019000, 0xb16e3000, 4096)
08-11 12:27:59.216   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.216   326  7030 V AudioCache: memcpy(0xaf01a000, 0xb16e3000, 4096)
08-11 12:27:59.219   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.219   326  7030 V AudioCache: memcpy(0xaf01b000, 0xb16e3000, 4096)
08-11 12:27:59.220   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.220   326  7030 V AudioCache: memcpy(0xaf01c000, 0xb16e3000, 4096)
,08-11 12:27:59.221   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.221   326  7030 V AudioCache: memcpy(0xaf01d000, 0xb16e3000, 4096)
08-11 12:27:59.221   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.221   326  7030 V AudioCache: memcpy(0xaf01e000, 0xb16e3000, 4096)
08-11 12:27:59.222   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.222   326  7030 V AudioCache: memcpy(0xaf01f000, 0xb16e3000, 4096)
08-11 12:27:59.222   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.222   326  7030 V AudioCache: memcpy(0xaf020000, 0xb16e3000, 4096)
,08-11 12:27:59.223   326  7030 V AudioCache: write(0xb16e3000, 4096)
,08-11 12:27:59.223   326  7030 V AudioCache: memcpy(0xaf021000, 0xb16e3000, 4096)
,08-11 12:27:59.223   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.223   326  7030 V AudioCache: memcpy(0xaf022000, 0xb16e3000, 4096)
08-11 12:27:59.224   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.224   326  7030 V AudioCache: memcpy(0xaf023000, 0xb16e3000, 4096)
08-11 12:27:59.225   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.225   326  7030 V AudioCache: memcpy(0xaf024000, 0xb16e3000, 4096)
08-11 12:27:59.225   326  7030 V AudioCache: write(0xb16e3000, 4096)
,08-11 12:27:59.225   326  7030 V AudioCache: memcpy(0xaf025000, 0xb16e3000, 4096)
08-11 12:27:59.226   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.226   326  7030 V AudioCache: memcpy(0xaf026000, 0xb16e3000, 4096)
08-11 12:27:59.226   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.226   326  7030 V AudioCache: memcpy(0xaf027000, 0xb16e3000, 4096)
08-11 12:27:59.227   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.227   326  7030 V AudioCache: memcpy(0xaf028000, 0xb16e3000, 4096)
08-11 12:27:59.227   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.227   326  7030 V AudioCache: memcpy(0xaf029000, 0xb16e3000, 4096)
08-11 12:27:59.228   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.228   326  7030 V AudioCache: memcpy(0xaf02a000, 0xb16e3000, 4096)
08-11 12:27:59.229   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.229   326  7030 V AudioCache: memcpy(0xaf02b000, 0xb16e3000, 4096)
08-11 12:27:59.229   326  7030 V AudioCache: write(0xb16e3000, 4096)
,08-11 12:27:59.229   326  7030 V AudioCache: memcpy(0xaf02c000, 0xb16e3000, 4096)
08-11 12:27:59.230   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.230   326  7030 V AudioCache: memcpy(0xaf02d000, 0xb16e3000, 4096)
08-11 12:27:59.230   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.230   326  7030 V AudioCache: memcpy(0xaf02e000, 0xb16e3000, 4096)
08-11 12:27:59.231   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.231   326  7030 V AudioCache: memcpy(0xaf02f000, 0xb16e3000, 4096)
08-11 12:27:59.232   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.232   326  7030 V AudioCache: memcpy(0xaf030000, 0xb16e3000, 4096)
08-11 12:27:59.232   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.232   326  7030 V AudioCache: memcpy(0xaf031000, 0xb16e3000, 4096)
,08-11 12:27:59.233   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.233   326  7030 V AudioCache: memcpy(0xaf032000, 0xb16e3000, 4096)
08-11 12:27:59.233   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.233   326  7030 V AudioCache: memcpy(0xaf033000, 0xb16e3000, 4096)
08-11 12:27:59.234   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.234   326  7030 V AudioCache: memcpy(0xaf034000, 0xb16e3000, 4096)
08-11 12:27:59.234   326  7030 V AudioCache: write(0xb16e3000, 4096)
08-11 12:27:59.234   326  7030 V AudioCache: memcpy(0xaf035000, 0xb16e3000, 4096)
08-11 12:27:59.234   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-11 12:27:59.234   326  7030 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-11 12:27:59.234   326  7030 V AwesomePlayer: postAudioEOS() 
,08-11 12:27:59.235   326  7030 V AudioCache: write(0xb16e3000, 280)
08-11 12:27:59.235   326  7030 V AudioCache: memcpy(0xaf036000, 0xb16e3000, 280)
08-11 12:27:59.236  7000  7000 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:59.237   326  7027 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-11 12:27:59.237   326  7027 V AwesomePlayer: onStreamDone
08-11 12:27:59.237   326  7027 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-11 12:27:59.237   326  7027 V AudioCache: notify(0xb16a6b80, 2, 0, 0)
08-11 12:27:59.237   326  7027 V AudioCache: playback complete
08-11 12:27:59.237   326  7027 V AwesomePlayer: pause_l() 
08-11 12:27:59.237   326  7027 V AudioCache: notify(0xb16a6b80, 7, 0, 0)
08-11 12:27:59.237   326  7027 V AudioCache: ignored
,08-11 12:27:59.237   326  7027 V AwesomePlayer: cancelPlayerEvents
08-11 12:27:59.237   326  1397 V AudioCache: wait - success
08-11 12:27:59.237   326  1397 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-11 12:27:59.237   326  7027 D AudioPlayer: Pause Playback at 1068125
08-11 12:27:59.237   326  1397 V AwesomePlayer: reset_l() 
08-11 12:27:59.237   326  1397 V AudioCache: notify(0xb16a6b80, 8, 0, 0)
08-11 12:27:59.237   326  1397 V AudioCache: ignored
08-11 12:27:59.237   326  1397 V AwesomePlayer: cancelPlayerEvents
08-11 12:27:59.237   326  1397 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-11 12:27:59.237   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-11 12:27:59.237   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
,08-11 12:27:59.237   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-11 12:27:59.237   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
,08-11 12:27:59.238  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c5510 on port 1
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
,08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:27:59.238   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-11 12:27:59.238   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-11 12:27:59.238   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-11 12:27:59.239   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-11 12:27:59.239   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-11 12:27:59.239   326  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-11 12:27:59.239   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,08-11 12:27:59.239   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-11 12:27:59.239   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-11 12:27:59.239  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-11 12:27:59.239  7000  7000 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 12:27:59.239  7000  7000 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 12:27:59.239  7000  7000 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 12:27:59.239   326  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-11 12:27:59.239   326  1397 D AudioPlayer: AudioPlayer releasing audio source
08-11 12:27:59.239   326  1397 D AudioPlayer: AudioPlayer done releasing audio source
08-11 12:27:59.239   326  1397 V AwesomePlayer: reset_l() 
08-11 12:27:59.240   326  1397 V AwesomePlayer: cancelPlayerEvents
,08-11 12:27:59.240   326  1397 V AwesomePlayer: ~AwesomePlayer call
08-11 12:27:59.240   326  1397 V AwesomePlayer: reset_l() 
08-11 12:27:59.240   326  1397 V AwesomePlayer: cancelPlayerEvents
08-11 12:27:59.240  6929  7026 V SoundPool: close(31)
08-11 12:27:59.240  6929  7026 V SoundPool: pointer = 0x9ffe0000, size = 205080, sampleRate = 48000, numChannels = 2
08-11 12:27:59.240  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9423
08-11 12:27:59.240  7000  7000 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:27:59.240  7000  7000 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-11 12:27:59.247  6946  6946 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-11 12:27:59.426  6737  6737 I UEI.SmartControl: Supports setup maps: true
08-11 12:27:59.429  6737  6737 D UEI.SmartControl: QS start statue = true Error code = 0
,08-11 12:27:59.429  6737  6737 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-11 12:27:59.429  6737  6737 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-11 12:27:59.429  6737  6737 I UEI.SmartControl: ### init IR Blaster...
08-11 12:27:59.434  6737  6737 D serial_port: Configuring serial port
,08-11 12:27:59.434  6737  6737 E UEI.SmartControl: UEIBLaster setting for 616
08-11 12:27:59.434  6737  6737 I UEI.SmartControl: Setting serial record hearder size = 2
,08-11 12:27:59.434  6737  6737 I UEI.SmartControl: configuring settings for MAXQ616
08-11 12:27:59.434  6737  6737 I UEI.SmartControl: Get version...
08-11 12:27:59.450  6737  7032 D UEI.SmartControl: serial port data available: 21
,08-11 12:27:59.476  6737  6737 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-11 12:27:59.476  6737  6737 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-11 12:27:59.476  6737  6737 I UEI.SmartControl: QS saving settings...
08-11 12:27:59.477  6737  6737 D UEI.SmartControl: IR Blaster version: 25672567
,08-11 12:27:59.493  6737  7032 D UEI.SmartControl: serial port data available: 4
,08-11 12:27:59.525  6737  6737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-11 12:27:59.529  6737  7038 I UEI.SmartControl: Device manager: loading config....
08-11 12:27:59.531  6737  6737 E UEI.SmartControl: Services init done
08-11 12:27:59.531  6737  6737 D UEI.SmartControl: QS Service init finished
08-11 12:27:59.533  6737  6737 D UEI.SmartControl: QS Service version name: 2.1.91
08-11 12:27:59.533  6737  6737 D UEI.SmartControl: QS Service version code: 201091
08-11 12:27:59.533  6737  7038 D UEI.SmartControl: ----------- loading internal config...
08-11 12:27:59.534  6737  6737 D UEI.SmartControl: Service requested: Control
08-11 12:27:59.540  6737  7038 E UEI.SmartControl: Loading SETTINGS...
,08-11 12:27:59.545  6737  6737 D UEI.SmartControl: Request IControl service: devices are loaded...
08-11 12:27:59.546  6737  7038 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-11 12:27:59.546  6737  6737 D UEI.SmartControl: Internal service binding...
08-11 12:27:59.547  6929  6929 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-11 12:27:59.548  6737  6758 I UEI.SmartControl: ------ IControl API: 11
08-11 12:27:59.548  6737  6758 D UEI.SmartControl: File observer start...
08-11 12:27:59.549  6737  6758 E UEI.SmartControl: IR Port is disabled: false
08-11 12:27:59.549  6737  6758 D UEI.SmartControl: Starting file observer...
08-11 12:27:59.549  6737  6758 I UEI.SmartControl: Registering callback...
08-11 12:27:59.550  6737  6759 I UEI.SmartControl: ------ IControl API: 19
08-11 12:27:59.551  6737  6759 I UEI.SmartControl: Registering Services Ready callback...
,08-11 12:27:59.574  6737  7037 I UEI.SmartControl: Notify AllClients services are ready: 0
08-11 12:27:59.574  6737  7037 D UEI.SmartControl: -----service ready thread exits
08-11 12:27:59.576  6929  6945 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-11 12:27:59.576  6929  7023 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-11 12:27:59.576  6929  7023 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-11 12:27:59.578  6929  6929 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-11 12:27:59.578  6929  6929 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-11 12:27:59.579  6737  6758 I UEI.SmartControl: ------ IControl API: 8
08-11 12:27:59.581  6929  6929 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-11 12:27:59.581  6929  6929 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-11 12:27:59.581  6929  6929 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-11 12:27:59.582  6929  6929 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-11 12:27:59.583  6929  6929 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-11 12:27:59.583  6929  6929 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-11 12:27:59.586  6929  6929 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-11 12:27:59.590  6929  6929 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-11 12:27:59.591  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-11 12:27:59.592  6929  6929 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-11 12:27:59.592  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-11 12:27:59.593  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-11 12:27:59.595  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-11 12:27:59.595  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-11 12:27:59.597  6929  6929 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470911279596]
08-11 12:27:59.600  6929  6929 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-11 12:27:59.608  1035  1716 I ActivityManager: Killing 6051:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-11 12:27:59.627  6929  7040 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-11 12:27:59.640  1035  1716 I ActivityManager: Killing 6530:com.lge.email/u0a23 (adj 15): empty #18
,08-11 12:27:59.674  1035  1978 W libprocessgroup: failed to open /acct/uid_10027/pid_6051/cgroup.procs: No such file or directory
,08-11 12:27:59.675  6929  6929 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-11 12:27:59.676  1035  1870 W libprocessgroup: failed to open /acct/uid_10023/pid_6530/cgroup.procs: No such file or directory
08-11 12:27:59.678  6929  6929 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-11 12:27:59.679  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-11 12:27:59.680  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-11 12:27:59.681  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-11 12:27:59.681  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-11 12:27:59.682  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-11 12:27:59.700  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-11 12:28:00.038  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-11 12:28:00.039  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 12:28:00.039  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-11 12:28:00.039  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-11 12:28:00.053  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 12:28:00.054  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-11 12:28:00.056  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-11 12:28:00.060  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 12:28:00.638  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:00.653  1035  1109 D Tethering: MasterInitialState.processMessage what=3
08-11 12:28:00.668  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:00.673  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:00.674  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:00.677  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:00.679  1035  1109 D Tethering: MasterInitialState.processMessage what=3
08-11 12:28:00.689  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:00.693  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:00.694  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:00.694  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:00.697  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-11 12:28:00.700  6438  6467 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 12:28:00.711  5755  5755 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-11 12:28:00.719  5755  5755 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-11 12:28:00.739  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:00.770  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:00.813  1035  1716 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7061 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-11 12:28:00.816  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:00.816  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-11 12:28:00.899  7061  7061 I AppUp4:AppBoxCP: onCreate
,08-11 12:28:00.900  7061  7061 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-11 12:28:00.911  7061  7061 I AppUp4:DB:  setFingerPrint start
,08-11 12:28:00.911  7061  7061 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-11 12:28:00.920  7061  7061 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-11 12:28:00.920  7061  7061 I AppUp4:DB:  SDK version = 21
,08-11 12:28:00.920  7061  7061 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-11 12:28:00.924  7061  7061 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-11 12:28:00.926  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 12:28:00.926  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:00.928  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-11 12:28:00.929  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-11 12:28:00.936  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
,08-11 12:28:00.975  7061  7061 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:28:00.976  7061  7061 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:00.986  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2bb2835e
,08-11 12:28:00.987  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-11 12:28:00.987  7061  7061 D AppUp4:CustFacade: isPhone : true
08-11 12:28:00.988  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-11 12:28:00.989  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-11 12:28:00.990  7061  7061 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-11 12:28:00.991  7061  7080 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-11 12:28:00.992  7061  7080 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-11 12:28:00.992  7061  7080 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-11 12:28:00.996  1035  1978 I ActivityManager: Killing 6113:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-11 12:28:01.030  1035  1651 W libprocessgroup: failed to open /acct/uid_10080/pid_6113/cgroup.procs: No such file or directory
,08-11 12:28:01.032  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:01.033  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:01.037  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:01.042  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:01.049  4321  7083 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 12:28:01.056  4321  7084 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:01.056  4321  7084 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 12:28:01.133  1035  1050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7088 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-11 12:28:01.203  7088  7088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:01.204  7088  7088 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:28:01.205  7088  7088 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-11 12:28:01.206  7088  7088 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 12:28:01.306  7088  7088 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 12:28:01.323  7088  7088 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-11 12:28:01.376  7088  7088 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 12:28:01.431  7088  7088 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 12:28:01.432  7088  7088 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:01.564  7088  7088 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-11 12:28:01.629  3477  3477 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 12:28:01.629  3477  3477 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:01.629  3477  3477 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-11 12:28:01.636  6970  7113 W FormManager: Network not available. Please check & try again.
,08-11 12:28:01.639  6970  7114 V FormManager: Network unavailable.
08-11 12:28:01.647  7088  7088 I HubEmail: JNI_OnLoad()
,08-11 12:28:01.647  7088  7088 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 12:28:01.647  7088  7088 I HubEmail: registerNatives()
08-11 12:28:01.647  7088  7088 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 12:28:01.647  7088  7088 I HubEmail: registerNativeMethods()
08-11 12:28:01.647  7088  7088 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 12:28:01.648  7088  7088 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-11 12:28:01.682  1035  1924 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7117 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-11 12:28:01.686  6970  7114 V FormManager: Network unavailable.
08-11 12:28:01.696  7088  7116 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:01.705  1035  1051 I ActivityManager: Killing 6570:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-11 12:28:01.795  1035  2032 W libprocessgroup: failed to open /acct/uid_10061/pid_6570/cgroup.procs: No such file or directory
08-11 12:28:01.886  7117  7117 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:28:01.887  7117  7117 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:01.890  7117  7117 D PhoneMonitor: Register our PhoneStateListener
,08-11 12:28:01.910  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-11 12:28:01.913  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-11 12:28:01.943  7117  7117 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-11 12:28:01.944  7117  7117 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-11 12:28:01.945  7117  7117 D TelephonyAutoProfiling: [parse] Load xml
08-11 12:28:01.953  7117  7117 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-11 12:28:01.953  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-11 12:28:01.953  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-11 12:28:01.953  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-11 12:28:01.953  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-11 12:28:01.953  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-11 12:28:01.954  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-11 12:28:01.954  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-11 12:28:01.954  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-11 12:28:01.954  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-11 12:28:01.954  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-11 12:28:01.954  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-11 12:28:01.955  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-11 12:28:01.955  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-11 12:28:01.955  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-11 12:28:01.955  7117  7117 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-11 12:28:01.955  7117  7117 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-11 12:28:01.969  7117  7117 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-11 12:28:01.974  1035  1959 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7146 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-11 12:28:01.975  1035  1959 I ActivityManager: Killing 6137:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-11 12:28:02.039  1035  1978 W libprocessgroup: failed to open /acct/uid_10097/pid_6137/cgroup.procs: No such file or directory
08-11 12:28:02.251  1035  1716 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7166 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-11 12:28:02.253  1035  1716 I ActivityManager: Killing 6689:com.lge.eula/1000 (adj 15): empty #17
08-11 12:28:02.308  1035  1577 W libprocessgroup: failed to open /acct/uid_1000/pid_6689/cgroup.procs: No such file or directory
,08-11 12:28:02.435  1035  1906 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7186 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-11 12:28:02.440  1035  1906 I ActivityManager: Killing 6707:com.lge.bnr/1000 (adj 15): empty #17
08-11 12:28:02.511  1035  1716 W libprocessgroup: failed to open /acct/uid_1000/pid_6707/cgroup.procs: No such file or directory
,08-11 12:28:02.559  7186  7186 I art     : Almond Protected OAT
,08-11 12:28:02.566  1035  1924 D WifiServiceImplEx: setWifiEnabled: true pid=6630, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 12:28:02.567  1035  1924 D WifiService: setWifiEnabled: true pid=6630, uid=10118
08-11 12:28:02.567  1035  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 12:28:02.585  1035  1399 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-11 12:28:02.585  1035  1399 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-11 12:28:02.586  1035  1399 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-11 12:28:02.586  1035  1399 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-11 12:28:02.586  1035  1399 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-11 12:28:02.586  1035  1399 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-11 12:28:02.586  1035  1399 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-11 12:28:02.586  1035  1399 E WifiHW  : unknown target_country: EU , set to default
08-11 12:28:02.586  1035  1399 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-11 12:28:02.586  1035  1399 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-11 12:28:02.587  1035  1399 I WifiUtil: gEnableBmps=1
08-11 12:28:02.591  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 12:28:02.592  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 12:28:02.592  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-11 12:28:02.623  7186  7186 D WeatherApplication: removeAccount
08-11 12:28:02.624  7186  7186 D WeatherApplication: Account.length = 0
08-11 12:28:02.625  7186  7186 E WeatherApplication: OPERATOR:OPEN
,08-11 12:28:02.631  7186  7186 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:2
08-11 12:28:02.634  7186  7186 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 12:28:02.634  7186  7186 D Weather.Utils: 2 : All the weather widget is gone.
08-11 12:28:02.637  7186  7186 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-11 12:28:02.640  7186  7186 D WeatherAncestor: connectivity changed - connection : true
,08-11 12:28:02.641  7186  7186 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-11 12:28:02.647  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:02.647  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:02.654  7186  7186 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-11 12:28:02.655  7186  7186 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 12:28:02.655  7186  7186 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-11 12:28:02.697  7186  7186 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-11 12:28:02.698  7186  7186 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:2
,08-11 12:28:02.744  1035  1924 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7205 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-11 12:28:02.746  1035  1924 I ActivityManager: Killing 2161:com.lge.music/u0a34 (adj 15): empty #17
,08-11 12:28:02.767   354   354 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 434us total 19.706ms
,08-11 12:28:02.784   326  1398 V AudioFlinger: 2161 died, releasing its sessions
08-11 12:28:02.784   326  1398 V AudioFlinger:  pid 1853 @ 0
08-11 12:28:02.784   326  1398 V AudioFlinger:  pid 3477 @ 1
08-11 12:28:02.784   326  1398 V AudioFlinger:  pid 3477 @ 2
08-11 12:28:02.785   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 17.053ms
,08-11 12:28:02.809   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 23.147ms
,08-11 12:28:02.817  1035  1050 W libprocessgroup: failed to open /acct/uid_10034/pid_2161/cgroup.procs: No such file or directory
08-11 12:28:02.928   278   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-11 12:28:02.928   278   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-11 12:28:02.928   278   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 12:28:02.929  7205  7228 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-11 12:28:02.932   278   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-11 12:28:02.932   278   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-11 12:28:02.932   278   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 12:28:02.932  7205  7228 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-11 12:28:02.952   278   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-11 12:28:02.952   278   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-11 12:28:02.952   278   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 12:28:02.952  7205  7231 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-11 12:28:02.955   278   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-11 12:28:02.955   278   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-11 12:28:02.955   278   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 12:28:02.955  7205  7231 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-11 12:28:03.243  7205  7205 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-11 12:28:03.256  7205  7205 I LibraryLoader: Loading: webviewchromium
08-11 12:28:03.260  7205  7205 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7188-7193)
08-11 12:28:03.260  7205  7205 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 12:28:03.270  7205  7205 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b7f0a4b}
,08-11 12:28:03.273  7205  7205 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 12:28:03.274  7205  7205 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 12:28:03.297  7205  7205 I BrowserStartupController: Initializing chromium process, renderers=0
08-11 12:28:03.298  7205  7205 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 12:28:03.327  1035  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-11 12:28:03.327  1035  1109 D Tethering: InitialState.processMessage what=4
08-11 12:28:03.328  1035  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-11 12:28:03.333   322   894 D SoftapController: Softap fwReload - Ok
08-11 12:28:03.334  1035  1399 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (744ms)
08-11 12:28:03.336   322   894 D CommandListener: Setting iface cfg
08-11 12:28:03.336   322   894 D CommandListener: Trying to bring down wlan0
08-11 12:28:03.336   322   894 D CommandListener: Clearing all IP addresses on wlan0
08-11 12:28:03.340  1035  1399 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-11 12:28:03.333  7263  7263 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:03.333  7263  7263 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 12:28:03.357  1035  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 12:28:03.357  1035  1399 E WifiStateMachine: useWiFiOffloading() : false
08-11 12:28:03.357  1035  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 12:28:03.361  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 12:28:03.373  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-11 12:28:03.375  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:03.377  1035  1399 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-11 12:28:03.377  1035  1399 D WifiMonitor: connecting to supplicant
08-11 12:28:03.383  7263  7263 I wpa_supplicant: Successfully initialized wpa_supplicant
08-11 12:28:03.387  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:03.389  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:03.389  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-11 12:28:03.411  7263  7263 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-11 12:28:03.411  7263  7263 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-11 12:28:03.411  7205  7205 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-11 12:28:03.411   326  2173 V AudioPolicyService: registerClient() client 0xb0410620, uid 10093
08-11 12:28:03.412  7205  7277 W AudioManagerAndroid: Requires BLUETOOTH permission
08-11 12:28:03.414  7205  7205 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-11 12:28:03.414  7205  7205 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-11 12:28:03.429  7205  7205 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:28:03.429  7205  7205 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:28:03.429  7205  7205 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:28:03.429  7205  7205 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:28:03.429  7205  7205 I Adreno-EGL: Remote Branch: 
08-11 12:28:03.429  7205  7205 I Adreno-EGL: Local Patches: 
08-11 12:28:03.429  7205  7205 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:28:03.502  7205  7205 I NSApplication: Starting up...
08-11 12:28:03.502  7263  7263 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-11 12:28:03.540  7263  7263 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-11 12:28:03.546  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-11 12:28:03.546  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-11 12:28:03.547  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-11 12:28:03.548  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-11 12:28:03.548  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-11 12:28:03.549  1035  1399 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-11 12:28:03.549  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-11 12:28:03.550  1035  1399 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-11 12:28:03.550  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:03.551  1035  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:03.551  1035  1399 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-11 12:28:03.551  1035  1399 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-11 12:28:03.552  1035  7292 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-11 12:28:03.552  1035  7292 D WifiMonitor: Dropping event because (p2p0) is stopped
08-11 12:28:03.552  1035  1399 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-11 12:28:03.552  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-11 12:28:03.552  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-11 12:28:03.552  1035  7292 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-11 12:28:03.552  1035  7292 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-11 12:28:03.552  1035  1399 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-11 12:28:03.552  1035  1399 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-11 12:28:03.586  1035  1651 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7293 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-11 12:28:03.588  1035  1651 I ActivityManager: Killing 6075:com.android.vending/u0a44 (adj 15): empty #17
08-11 12:28:03.638  1035  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 12:28:03.638  1035  1399 E WifiStateMachine: useWiFiOffloading() : false
08-11 12:28:03.638  1035  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-11 12:28:03.639  1035  1399 D WifiNative-wlan0: doBoolean: SET update_config 1
08-11 12:28:03.640  1035  1399 D WifiNative-wlan0: SET update_config 1: returned true
08-11 12:28:03.640  1035  1399 D WifiConfigStore: Loading config and enabling all networks 
08-11 12:28:03.641  1035  1399 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-11 12:28:03.641  1035  1399 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-11 12:28:03.642  1035  1716 W libprocessgroup: failed to open /acct/uid_10044/pid_6075/cgroup.procs: No such file or directory
08-11 12:28:03.652  1035  1399 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-11 12:28:03.657  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:03.657  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:03.657  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:03.657  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:03.657  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 12:28:03.661  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-11 12:28:03.662  1035  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-11 12:28:03.662  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:03.662  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:03.662  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:03.662  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:03.662  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:03.662  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:03.662  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:03.662  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:03.662  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:03.662  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:03.662  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:28:03.664  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:03.664  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:03.664  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:03.664  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:03.664  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:03.664  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:03.664  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:03.664  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:03.664  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:03.664  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:03.664  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:03.664  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:03.665  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:03.665  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:03.665  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:03.665  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:03.665  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:03.665  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:03.665  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:03.665  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:03.665  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:03.665  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:03.665  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:03.665  1035  1399 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-11 12:28:03.665  1035  1399 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-11 12:28:03.666  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-11 12:28:03.667  1035  1399 D WifiStateMachine: enableVerboseLogging : level 2
08-11 12:28:03.667  1035  1399 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-11 12:28:03.668  1035  1399 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-11 12:28:03.668  1035  1399 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-11 12:28:03.668  1035  1399 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-11 12:28:03.668  1035  1399 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-11 12:28:03.668  1035  1399 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-11 12:28:03.668  1035  1399 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-11 12:28:03.669  1035  1399 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-11 12:28:03.669  1035  1399 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-11 12:28:03.669  1035  1399 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-11 12:28:03.669  1035  1399 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-11 12:28:03.670  1035  1399 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-11 12:28:03.670  1035  1399 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-11 12:28:03.670  1035  1399 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-11 12:28:03.671  1035  1399 D WifiStateMachine: Setting OUI to DA-A1-19
08-11 12:28:03.671  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-11 12:28:03.671  1035  1399 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-11 12:28:03.671  1942  2268 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-11 12:28:03.671  1942  2268 D WfdsService: Set the WFDS Monitor: true
08-11 12:28:03.671  1942  2268 D WfdsMonitor: WfdsMonitorThread create
08-11 12:28:03.671  1035  1399 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-11 12:28:03.671  1035  1399 D WifiNative-HAL: Setting external_sim to 1
08-11 12:28:03.671  1035  1399 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-11 12:28:03.671  1942  2268 D WfdsMonitor: WFDS Monitor is created and started
08-11 12:28:03.671  1942  2268 D WfdsService: WiFi: Supplicant connection re-established
08-11 12:28:03.672  1035  1399 D WifiNative-wlan0: SET external_sim 1: returned true
08-11 12:28:03.672  1035  1399 I WifiNative-HAL: startHal
08-11 12:28:03.672  1035  1399 D wifi    : setting scan oui 0xaf5fdee0
08-11 12:28:03.672  1035  1399 D WifiStateMachine: Setting OUI to DA-A1-19
08-11 12:28:03.672  1035  1399 I WifiNative-HAL: startHal
08-11 12:28:03.672  1035  1399 D wifi    : setting scan oui 0xaf5fdee0
08-11 12:28:03.673  1035  1399 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-11 12:28:03.673  1035  1399 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-11 12:28:03.674  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-11 12:28:03.674  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,08-11 12:28:03.674  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-11 12:28:03.675  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-11 12:28:03.675  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-11 12:28:03.675  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-11 12:28:03.675  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-11 12:28:03.676  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-11 12:28:03.676  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-11 12:28:03.676  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-11 12:28:03.676  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-11 12:28:03.677  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-11 12:28:03.677  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-11 12:28:03.677  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-11 12:28:03.677  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-11 12:28:03.678  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-11 12:28:03.678  1942  7310 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-11 12:28:03.678  7263  7263 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-11 12:28:03.678  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-11 12:28:03.678  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-11 12:28:03.678  1942  7310 E CtrlSupplicant: Succeed to open control connection
08-11 12:28:03.678  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-11 12:28:03.678  1942  7310 E CtrlSupplicant: Succeed to open monitor connection
08-11 12:28:03.679  1942  7310 D WfdsMonitor: Supplicant connection established
08-11 12:28:03.679  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-11 12:28:03.679  1942  2268 D WfdsService: Connected to the supplicant for wfds
08-11 12:28:03.680  1035  1399 E WifiNative: : [157,599,484 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-11 12:28:03.680  1035  1399 D WifiNative-wlan0: doBoolean: RECONNECT
08-11 12:28:03.680  1035  1399 D WifiNative-wlan0: RECONNECT: returned true
08-11 12:28:03.680  1035  1399 D WifiNative-wlan0: doString: [STATUS]
08-11 12:28:03.681  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-11 12:28:03.681  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-11 12:28:03.681  1035  1399 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-11 12:28:03.681  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 12:28:03.682  1035  1399 D WifiNative-wlan0: SET ps 1: returned true
08-11 12:28:03.682  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.683  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-11 12:28:03.683  1035  1399 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-11 12:28:03.683  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-11 12:28:03.683  1035  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.683  1035  1557 I WifiNative-HAL: startHal
08-11 12:28:03.683  1035  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf5fdee0
08-11 12:28:03.683  1035  1557 D wifi    : failed to get capabilities : -3
08-11 12:28:03.683  1035  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.683  1035,  1557 E WifiScanningService: could not get scan capabilities
08-11 12:28:03.683  1035  1399 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-11 12:28:03.684   322   894 D CommandListener: Setting iface cfg
08-11 12:28:03.684   322   894 D CommandListener: Trying to bring up p2p0
08-11 12:28:03.684  1035  1399 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-11 12:28:03.684  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-11 12:28:03.684  1035  1390 D LGWifiP2pService: P2pEnablingState
08-11 12:28:03.684  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-11 12:28:03.684  1035  1390 D LGWifiP2pService: P2p socket connection successful
08-11 12:28:03.684  1035  1390 D LGWifiP2pService: P2pEnabledState
08-11 12:28:03.684  1035  1399 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-11 12:28:03.685  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-11 12:28:03.685  1035  1399 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-11 12:28:03.685  1035  1399 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-11 12:28:03.685  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-11 12:28:03.685  1942  1942 D WfdsService: WifiP2pState is changed : true
08-11 12:28:03.686  1035  1399 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-11 12:28:03.686  1035  1399 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-11 12:28:03.686  1942  2268 D WfdsService: Receive the WFDS_ENABLE Method
08-11 12:28:03.686  1942  2268 D WfdsService: Set the WFDS Monitor: true
08-11 12:28:03.686  1942  2268 D WfdsService: Connected to the supplicant for wfds
08-11 12:28:03.686  7263  7263 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-11 12:28:03.686  1942  2268 D WfdsJNI : doCommand: WFDS_SET TRUE
08-11 12:28:03.686  7263  7263 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-11 12:28:03.686  1942  2268 D WfdsService: selectPreferredScanChannel [36]
08-11 12:28:03.686  1942  2268 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-11 12:28:03.690  1035  1399 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-11 12:28:03.690  1035  1399 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-11 12:28:03.690  1035  1399 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-11 12:28:03.691  1035  1399 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-11 12:28:03.691  7263  7263 E wpa_supplicant: disconnect_rssi_lvl: -100
08-11 12:28:03.692  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-11 12:28:03.693  1942  1942 D WfdsService: isConnected: false
08-11 12:28:03.693  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-11 12:28:03.693  1035  1399 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-11 12:28:03.693  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-11 12:28:03.694  1035  1399 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-11 12:28:03.694  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-11 12:28:03.694  1035  1399 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-11 12:28:03.694  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-11 12:28:03.694  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-11 12:28:03.694  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-11 12:28:03.694  1035  1390 D LGWifiP2pService: before postfix = G3
08-11 12:28:03.694  1035  1390 D WifiServerServiceExt: postfix byte check : 2
08-11 12:28:03.694  1035  1390 D LGWifiP2pService: after postfix = G3
08-11 12:28:03.694  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-11 12:28:03.695  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-11 12:28:03.696  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:03.696  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 12:28:03.696  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:03.696  1035  7292 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:03.696  1035  7292 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:03.697  7263  7263 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-11 12:28:,03.697  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.697  1942  7310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:03.697  1035  7292 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:03.697  1035  7292 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.697  1035  7292 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.697  1035  7292 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.698  1035  1399 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-11 12:28:03.698  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.698  1942  7310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:03.698  1035  7292 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:03.698  1035  7292 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.698  1035  7292 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.698  1035  7292 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.699  1035  1399 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-11 12:28:03.699  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-11 12:28:03.699  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-11 12:28:03.699  1035  1399 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-11 12:28:03.699  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-11 12:28:03.699  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-11 12:28:03.700  1035  1399 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-11 12:28:03.700  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-11 12:28:03.700  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-11 12:28:03.700  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-11 12:28:03.700  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-11 12:28:03.700  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-11 12:28:03.700  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-11 12:28:03.701  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-11 12:28:03.701  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 12:28:03.702  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,08-11 12:28:03.702  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 12:28:03.702  1035  7292 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 12:28:03.702  1035  7292 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 12:28:03.703  1035  1399 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-11 12:28:03.703  1035  1399 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-11 12:28:03.704  1035  1399 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-11 12:28:03.704  1035  1399 D WifiNative-wlan0: doBoolean: SCAN
08-11 12:28:03.705  1035  1399 D WifiNative-wlan0: SCAN: returned false
08-11 12:28:03.705  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-11 12:28:03.705  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-11 12:28:03.705  1942  1942 D WfdsService: Update P2p Interface State: 3
08-11 12:28:03.705  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=157625  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-11 12:28:03.705  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-11 12:28:03.705  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-11 12:28:03.705  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-11 12:28:03.706  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-11 12:28:03.706  7293  7293 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:03.706  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-11 12:28:03.706  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-11 12:28:03.706  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-11 12:28:03.706  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-11 12:28:03.710  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:03.710  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:03.711  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:03.711  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:03.711  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-11 12:28:03.711  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:03.713  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=157633  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-11 12:28:03.713  1035  1399 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:03.714  1035  1399 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:03.714  1035  1399 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:03.714  1035  1399 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:03.715  1035  1399 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:03.717  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:03.717  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-11 12:28:03.719  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-11 12:28:03.719  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-11 12:28:03.720  1035  1390 D LGWifiP2pService: InactiveState
08-11 12:28:03.720  1035  1390 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.720  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.720  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-11 12:28:03.720  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-11 12:28:03.721  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:03.721  7263  7263 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-11 12:28:03.721  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.722  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.723  1942  7310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 12:28:03.723  1942  7310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:03.723  1942  7310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:03.723  1035  7292 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 12:28:03.723  1035  7292 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:03.723  1035  7292 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:03.723  1035  7292 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:03.723  1035  7292 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:03.723  1035  7292 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.723  1035  7292 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.723  1035  7292 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.723  1035  7292 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:03.723  1035  7292 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.723  1035  7292 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.723  1035  7292 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:03.724  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$Sm,Handler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.724  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.725  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.725  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.725  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:03.725  1035  1035 E WifiServerServiceExt: No p2p device connected
08-11 12:28:03.725  1942  2268 W WfdsService: DefaultState - msg [9441285] is not handled
,08-11 12:28:04.057  1035  1996 I art     : Explicit concurrent mark sweep GC freed 71866(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.140ms total 116.468ms
,08-11 12:28:04.063  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-11 12:28:04.066  6438  6467 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 12:28:04.082  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:04.099  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 12:28:04.099  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:04.100  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-11 12:28:04.100  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-11 12:28:04.103  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-11 12:28:04.106  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2bb2835e
08-11 12:28:04.106  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-11 12:28:04.107  7061  7061 D AppUp4:CustFacade: isPhone : true
08-11 12:28:04.107  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-11 12:28:04.107  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-11 12:28:04.111  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:04.111  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:04.113  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 12:28:04.115  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:04.122  7088  7088 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-11 12:28:04.123  4321  7323 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-11 12:28:04.131  4321  7324 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:04.132  4321  7324 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-11 12:28:04.150  3477  3477 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 12:28:04.151  3477  3477 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:04.151  3477  3477 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-11 12:28:04.153  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-11 12:28:04.153  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-11 12:28:04.162  6970  7334 W FormManager: Network not available. Please check & try again.
08-11 12:28:04.162  7088  7327 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:04.169  7186  7186 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:4
08-11 12:28:04.171  7186  7186 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 12:28:04.171  7186  7186 D Weather.Utils: 2 : All the weather widget is gone.
08-11 12:28:04.171  7186  7186 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 12:28:04.171  7186  7186 D WeatherAncestor: connectivity changed - connection : true
08-11 12:28:04.171  7186  7186 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@96840c
08-11 12:28:04.172  7186  7186 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-11 12:28:04.172  7186  7186 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 12:28:04.172  7186  7186 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-11 12:28:04.172  7186  7186 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-11 12:28:04.173  7186  7186 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:4
08-11 12:28:04.184  6970  7335 V FormManager: Network unavailable.
,08-11 12:28:04.189  7263  7263 E wpa_supplicant: USIM:  scard_init function
,08-11 12:28:04.190  7263  7263 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-11 12:28:04.191  6970  7335 V FormManager: Network unavailable.
08-11 12:28:04.191  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-11 12:28:04.191  1035  7292 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-11 12:28:04.192  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-11 12:28:04.192  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-11 12:28:04.192  1035  7292 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-11 12:28:04.192  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-11 12:28:04.192  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-11 12:28:04.193  1035  1399 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-11 12:28:04.193  1035  1399 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-11 12:28:04.194  1035  1399 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-11 12:28:04.195  1035  1399 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-11 12:28:04.195  1035  1399 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-11 12:28:04.202  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=158122  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-11 12:28:04.206  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.206  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:04.207  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.208  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.208  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-11 12:28:04.208  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.210  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 12:28:04.210  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 12:28:04.211  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 12:28:04.211  6861  6861 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 12:28:04.212  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=158132  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-11 12:28:04.213  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.213  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.214  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-11 12:28:04.215  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:04.215  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-11 12:28:04.216  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-11 12:28:04.217  6861  6861 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 12:28:04.217  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 12:28:04.217  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 12:28:04.217  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 12:28:04.217  6861  6861 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 12:28:04.218  6861  6861 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 12:28:04.227  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:28:04.229  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.229  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-11 12:28:04.230  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-11 12:28:04.232  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.236  6970  7339 W FormManager: Network not available. Please check & try again.
08-11 12:28:04.237  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.242  1035  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=78540993, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-11 12:28:04.242  6970  7340 V FormManager: Network unavailable.
,08-11 12:28:04.247  6970  7340 V FormManager: Network unavailable.
08-11 12:28:04.257  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 12:28:04.259  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 12:28:04.263  6970  7341 W FormManager: Network not available. Please check & try again.
08-11 12:28:04.266  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.280  6970  7342 V FormManager: Network unavailable.
08-11 12:28:04.281  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,08-11 12:28:04.290  6970  7342 V FormManager: Network unavailable.
,08-11 12:28:04.299  7263  7263 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-11 12:28:04.299  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-11 12:28:04.299  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-11 12:28:04.300  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-11 12:28:04.300  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-11 12:28:04.300  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:04.300  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:04.300  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=158220  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-11 12:28:04.301  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=158221  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-11 12:28:04.301  1035  1399 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158222
08-11 12:28:04.302  1035  1399 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158222
08-11 12:28:04.302  1035  1399 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158222
08-11 12:28:04.303  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158223
08-11 12:28:04.303  1035  1399 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158223
08-11 12:28:04.303  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=158224  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-11 12:28:04.305  1035  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-11 12:28:04.308  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.308  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:04.310  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.310  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.310  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-11 12:28:04.311  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.312  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=158232  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-11 12:28:04.313  1035  1399 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:04.313  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:04.313  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:04.313  7263  7263 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 12:28:04.313  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 12:28:04.313  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-11 12:28:04.313  1035  1399 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-11 12:28:04.313  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 12:28:04.313  1035  7292 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 12:28:04.313  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-11 12:28:04.313  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 12:28:04.313  1035  1399 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:04.314  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:04.315  1035  7292 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 12:28:04.315  1035  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:04.315  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:04.315  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:04.316  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 12:28:04.316  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:04.317  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.317  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.317  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-11 12:28:04.317  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:04.317  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-11 12:28:04.318  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 12:28:04.321  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=158241  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-11 12:28:04.321  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=158242  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-11 12:28:04.322  1035  1399 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=158242
08-11 12:28:04.322  1035  1399 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=158243
08-11 12:28:04.323  1035  1399 D WifiNative-wlan0: doString: [STATUS]
08-11 12:28:04.323  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:04.323  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:04.324  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-11 12:28:04.324  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:04.324  1035  1399 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-11 12:28:04.324  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:04.327  1035  1399 I WifiServiceExtension: setVHTCapabilityType  : false
08-11 12:28:04.330  4321  7343 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 12:28:04.334  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.334  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:04.335  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.337  4321  7344 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 12:28:04.337  4321  7344 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 12:28:04.368  1035  1050 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7346 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-11 12:28:04.370  1035  1399 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-11 12:28:04.370  1035  1399 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-11 12:28:04.373  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.373  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:04.374  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.374  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.374  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.374  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-11 12:28:04.377  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.377  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.377  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-11 12:28:04.381  1035  1399 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-11 12:28:04.383  1035  1458 D ConnectivityService: Got NetworkAgent Messenger
08-11 12:28:04.383  1035  1458 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-11 12:28:04.383  1035  1458 D ConnectivityService: NetworkAgent connected
08-11 12:28:04.383  1035  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 12:28:04.383  1035  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 12:28:04.384  1035  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 12:28:04.384  1035  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-11 12:28:04.388  1035  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-11 12:28:04.388  1035  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 12:28:04.388  1035  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 12:28:04.389  1035  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 12:28:04.389  1035  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-11 12:28:04.392  1035  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-11 12:28:04.393   322   894 D CommandListener: Setting iface cfg
08-11 12:28:04.393  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.393  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:04.394  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.396  1035  1399 E WifiStateMachine: Start Dhcp Watchdog 2
08-11 12:28:04.396  1035  7364 D DhcpStateMachine: StoppedState
08-11 12:28:04.396  1035  7364 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:04.397  1035  7364 D DhcpStateMachine: WaitBeforeStartState
08-11 12:28:04.397  1035  1399 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=158317  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:04.397  1035  1399 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=158317  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:04.398  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=158318  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:04.398  1035  1399 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=158319  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-11 12:28:04.399  1035  1399 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=158319  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:04.399  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=158319  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:04.400  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:112341] from screen [on:0 period:2032469168] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:04.401  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:2032469169] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:04.401  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-11 12:28:04.402  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:04.402  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-11 12:28:04.405  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-11 12:28:04.405  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.406  1035  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.406  1035  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.406  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.407  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.407  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
08-11 12:28:04.408  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
08-11 12:28:04.408  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-11 12:28:04.408  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-11 12:28:04.409  1035  1458 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-11 12:28:04.409  1035  1458 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-11 12:28:04.409  1035  1399 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-11 12:28:04.409  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 0
08-11 12:28:04.409  1035  1399 D WifiNative-wlan0: SET ps 0: returned true
08-11 12:28:04.409  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-11 12:28:04.410  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-11 12:28:04.410  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-11 12:28:04.410  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@106d3e94 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:04.410  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@106d3e94 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:04.410  1035  7364 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:04.410  1035  7364 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-11 12:28:04.411  1035  1399 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-11 12:28:04.411  1035  1399 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-11 12:28:04.411  1035  1399 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-11 12:28:04.411   322   894 D CommandListener: Setting iface cfg
08-11 12:28:04.412   322   894 D CommandListener: Trying to bring up wlan0
08-11 12:28:04.412  1035  1399 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-11 12:28:04.413  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:04.413  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-11 12:28:04.413  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:04.414  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-11 12:28:04.414  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.414  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.415  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.415  1035  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.415  1035  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.416  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.416  1035  1399 E WifiStateMachine:  DefaultStat,e CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:04.417  1035  1458 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-11 12:28:04.417  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-11 12:28:04.417  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-11 12:28:04.418  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-11 12:28:04.418  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:04.418  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:04.418  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-11 12:28:04.418  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-11 12:28:04.418  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-11 12:28:04.418  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-11 12:28:04.419  1035  1399 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-11 12:28:04.419  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 12:28:04.434  1035  1399 D WifiNative-wlan0: SET ps 1: returned true
,08-11 12:28:04.435  1035  1458 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-11 12:28:04.436  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-11 12:28:04.436  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-11 12:28:04.436  1035  1399 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-11 12:28:04.437  1035  1458 D ConnectivityService: ignoring duplicate network state non-change
08-11 12:28:04.440  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.440  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:04.440  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.440  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.440  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-11 12:28:04.440  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.444  1035  1458 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-11 12:28:04.444  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.444  1035  1458 D ConnectivityService: Adding iface wlan0 to network 101
08-11 12:28:04.444  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.444  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-11 12:28:04.446  1035  1399 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-11 12:28:04.448  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-11 12:28:04.450  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-11 12:28:04.452  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.452  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.452  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-11 12:28:04.453  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-11 12:28:04.458  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.458  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:04.458  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-11 12:28:04.461  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-11 12:28:04.461  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:04.462  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.465  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.465  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-11 12:28:04.465  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.469  7346  7346 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-11 12:28:04.469  7346  7346 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-11 12:28:04.469  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:04.469  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-11 12:28:04.470  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.470  1035  1458 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-11 12:28:04.470  1035  1458 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-11 12:28:04.471  1035  1458 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-11 12:28:04.472   322   894 E Netd    : netlink response contains error (File exists)
08-11 12:28:04.472  1035  1458 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-11 12:28:04.473  1035  1458 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-11 12:28:04.473  1035  1458 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-11 12:28:04.473  1035  1458 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-11 12:28:04.475  1035  1458 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-11 12:28:04.475  1035  1458 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-11 12:28:04.475  1035  1458 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-11 12:28:04.475  1035  1458 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-11 12:28:04.475  1035  1458 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:04.475  1035  1458 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:04.475  1035  1458 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 12:28:04.475  7346  7346 V [BNRBootReceiver]: Boot Receiver Return
08-11 12:28:04.475  1035  1458 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.475  1035  1458 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-11 12:28:04.475  1035  1458 D ConnectivityService: currentScore = 0, newScore = 20
08-11 12:28:04.475  1035  1458 D ConnectivityService:    accepting network in place of null
08-11 12:28:04.475  1035  1458 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.476  1035  1399 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.476  1035  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:04.477  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:04.477  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected,
08-11 12:28:04.477  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:04.477  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-11 12:28:04.478  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.478  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-11 12:28:04.479  1035  1458 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-11 12:28:04.479  1035  1458 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-11 12:28:04.479  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-11 12:28:04.479  1035  1458 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE,
08-11 12:28:04.479  1035  1458 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-11 12:28:04.480   322  7369 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-11 12:28:04.480  1035  1458 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-11 12:28:04.480  7346  7346 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-11 12:28:04.481  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-11 12:28:04.481  1035  1458 D ConnectivityService: validation of new default Network = false
08-11 12:28:04.481  1035  1458 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-11 12:28:04.481  1035  1458 D DSQN    : enableDataServiceNotify 
08-11 12:28:04.481  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 12:28:04.481  1035  1458 D DSQN    : start dsqn bin
08-11 12:28:04.481  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 12:28:04.481  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-11 12:28:04.489  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.490  1035  1458 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-11 12:28:04.490  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.490  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:04.491  1035  1458 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:04.491  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-11 12:28:04.483  7370  7370 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:04.483  7370  7370 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:04.498  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:04.504  7370  7370 E DSQN    : DSQN ssw
08-11 12:28:04.506  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-11 12:28:04.507  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:28:04.519  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.520  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.520  6929  6929 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 12:28:04.521  1817  7374 I CheckinService: active receiver: enabled
08-11 12:28:04.521  6737  7039 D UEI.SmartControl: Internal timer expired: 2
08-11 12:28:04.521  6737  7039 D UEI.SmartControl: unbind internal service
,08-11 12:28:04.531  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-11 12:28:04.531  1817  7374 I CheckinService: Preparing to send checkin request
08-11 12:28:04.531  1817  7374 I EventLogService: Accumulating logs since 1470911184940
08-11 12:28:04.535   322  7369 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-11 12:28:04.535  6861  6861 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-11 12:28:04.538  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 12:28:04.539  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.539  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.543  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.546  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:04.551  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.556  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.557  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.558  6929  6929 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-11 12:28:04.561  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.567  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:04.569  1817  7374 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-11 12:28:04.574  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.576   322  7369 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-11 12:28:04.579  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.579  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.580  6929  6929 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:04.582  6929  6929 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-11 12:28:04.582  6929  6929 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9423
08-11 12:28:04.583  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=78540993 [*alarm*], flags=0x0
,08-11 12:28:04.586  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-11 12:28:04.586  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 12:28:04.586  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-11 12:28:04.586  6861  6861 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 12:28:04.587  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 12:28:04.587  6861  6861 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 12:28:04.587  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-11 12:28:04.587  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 12:28:04.587  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 12:28:04.587  6861  6861 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 12:28:04.588  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-11 12:28:04.588  6861  6861 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 12:28:04.591  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 12:28:04.600  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 12:28:04.606  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.611   322   893 D LGDataListener: argv[0]=dsqncommand
08-11 12:28:04.611   322   893 D LGDataListener: argv[1]=wlan0
08-11 12:28:04.611   322   893 D LGDataListener: argv[2]=1
08-11 12:28:04.611   322   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-11 12:28:04.611  1035  1106 D DSQN    : DSQM DsqnNotification wlan0  1
08-11 12:28:04.611  1035  1106 D DSQN    : start to monitor internet connection
,08-11 12:28:04.614  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.615  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.615  6929  6929 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:04.617  1035  7364 D DhcpStateMachine: DHCPV4 request on wlan0
08-11 12:28:04.618  1035  7364 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-11 12:28:04.618  1035  7364 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-11 12:28:04.622  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.613  7378  7378 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:04.613  7378  7378 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 12:28:04.628  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 12:28:04.633  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.634  7378  7378 I dhcpcd  : version 5.5.6 starting
08-11 12:28:04.637  7378  7378 E dhcpcd  : get_duid: m
08-11 12:28:04.637  7378  7378 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-11 12:28:04.637  7378  7378 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-11 12:28:04.638  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 10:28:04 GMT], X-Android-Received-Millis=[1470911284638], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470911284610]}
08-11 12:28:04.638  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-11 12:28:04.638  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-11 12:28:04.639  1035  1458 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-11 12:28:04.639  1035  1458 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-11 12:28:04.639  1035  1458 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:04.639  1035  1458 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:04.639  1035  1458 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 12:28:04.639  1035  1458 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-11 12:28:04.639  1035  1458 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-11 12:28:04.639  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.639  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:04.640  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.640  1035  1458 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:04.640  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.640  1035  1458 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.640  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-11 12:28:04.640  6929  6929 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:04.641  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-11 12:28:04.641  1035  1399 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.641  1035  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:04.642  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:04.642  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-11 12:28:04.643  6737  7033 D serial_port: close(fd = 24)
08-11 12:28:04.650  6737  7033 I UEI.SmartControl: Serial port is closed.
08-11 12:28:04.651  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 12:28:04.663  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:04.674  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.678  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 12:28:04.679  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:04.680  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 12:28:04.693  7378  7378 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-11 12:28:04.693  7378  7378 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-11 12:28:04.693  7378  7378 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-11 12:28:04.693  7378  7378 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-11 12:28:04.693  7378  7378 D dhcpcd  : wlan0: sending REQUEST (xid 0xfb44972f), next in 4.51 seconds
08-11 12:28:04.724  1035  1050 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7385 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-11 12:28:04.735  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 12:28:04.736  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.737  7378  7378 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-11 12:28:04.737  6929  6929 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:04.740  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.749  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:04.755  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.756  7378  7378 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-11 12:28:04.757  7378  7378 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-11 12:28:04.757  7378  7378 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-11 12:28:04.757  7378  7378 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-11 12:28:04.757  7378  7378 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-11 12:28:04.757  7378  7378 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-11 12:28:04.758  7378  7378 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-11 12:28:04.758  7378  7378 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-11 12:28:04.765  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 12:28:04.765  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.766  6929  6929 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-11 12:28:04.781  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.795  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:04.802  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.803  7385  7385 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-11 12:28:04.803  7385  7385 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-11 12:28:04.811  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.812  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 12:28:04.818  6929  6929 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:04.821  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.830  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:04.836  7385  7385 I MultiDex: VM with version 2.1.0 has multidex support
08-11 12:28:04.836  7385  7385 I MultiDex: install
08-11 12:28:04.836  7385  7385 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-11 12:28:04.837  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.844  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.844  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.845  6929  6929 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-11 12:28:04.849  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.853  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-11 12:28:04.853  7385  7385 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-11 12:28:04.857  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 12:28:04.860  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 12:28:04.865  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.870  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.870  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:04.871  6929  6929 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-11 12:28:04.871  6929  6929 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-11 12:28:04.872  6929  6929 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-11 12:28:04.877  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:04.883  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-11 12:28:04.884  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:28:04.889  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:04.899  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:04.907  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:04.908  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 12:28:04.908  6929  6929 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-11 12:28:04.909  6929  6929 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-11 12:28:04.917  6929  6929 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-11 12:28:04.919  1035  1959 I ActivityManager: Killing 6881:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-11 12:28:05.005  1035  1906 W libprocessgroup: failed to open /acct/uid_10037/pid_6881/cgroup.procs: No such file or directory
,08-11 12:28:05.012  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e8dd2fb type 2 when 158886 com.google.android.gms} when 158886
08-11 12:28:05.013  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-11 12:28:05.022  1035  7364 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-11 12:28:05.023  1035  7364 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-11 12:28:05.023  1035  7364 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-11 12:28:05.023  1035  7364 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-11 12:28:05.023  1035  7364 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-11 12:28:05.023  1035  7364 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-11 12:28:05.023  1035  7364 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-11 12:28:05.023  1035  7364 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-11 12:28:05.024  1035  7364 D DhcpStateMachine: RunningState
08-11 12:28:05.031  2214  2214 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-11 12:28:05.032  2214  2214 D c       : Getting all permits...
08-11 12:28:05.032  2214  2214 D a       : Opening database...
08-11 12:28:05.034  2214  2214 D a       : Opening database auth.proximity.permit_store...
08-11 12:28:05.034  2214  2214 D a       : Closing database...
08-11 12:28:05.056   322  7428 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 12:28:05.056   322  7428 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-11 12:28:05.091   322  7428 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-11 12:28:05.266  7433  7433 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-11 12:28:05.342  7433  7433 I dex2oat : dex2oat took 76.236ms (threads: 4)
,08-11 12:28:05.354  2214  7434 D GCM     : Connected
,08-11 12:28:05.372  2214  7434 D GCM     : Message class com.google.e.a.a.q
,08-11 12:28:05.375  7385  7401 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:28:05.375  7385  7401 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:28:05.375  7385  7401 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:28:05.375  7385  7401 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:28:05.375  7385  7401 I Adreno-EGL: Remote Branch: 
08-11 12:28:05.375  7385  7401 I Adreno-EGL: Local Patches: 
08-11 12:28:05.375  7385  7401 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:28:05.491  1035  1458 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-11 12:28:05.508  7385  7401 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:28:05.508  7385  7401 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:28:05.508  7385  7401 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:28:05.508  7385  7401 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:28:05.508  7385  7401 I Adreno-EGL: Remote Branch: 
08-11 12:28:05.508  7385  7401 I Adreno-EGL: Local Patches: 
08-11 12:28:05.508  7385  7401 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:28:05.595  7385  7401 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:28:05.595  7385  7401 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:28:05.595  7385  7401 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:28:05.595  7385  7401 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:28:05.595  7385  7401 I Adreno-EGL: Remote Branch: 
08-11 12:28:05.595  7385  7401 I Adreno-EGL: Local Patches: 
08-11 12:28:05.595  7385  7401 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:28:05.748  7385  7401 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 12:28:05.748  7385  7401 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:06.090   322  7445 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 12:28:06.090   322  7445 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-11 12:28:06.151   322  7445 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-11 12:28:06.151  1035  1399 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:06.152  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:06.154  1035  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:06.155  1035  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:06.157  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-11 12:28:06.163  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-11 12:28:06.164  1035  1458 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-11 12:28:06.164  1035  1458 D ConnectivityService: identical MTU - not setting
08-11 12:28:06.165  1035  1458 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-11 12:28:06.165  1035  1458 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-11 12:28:06.165  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:06.166  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:06.168  1035  1458 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:06.169  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-11 12:28:06.367  1817  7374 I CheckinTask: Sending checkin request (8038 bytes)
,08-11 12:28:06.578  1817  7374 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-11 12:28:06.595  1817  7374 I CheckinService: active receiver: disabled
,08-11 12:28:06.622  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-11 12:28:06.641  2214  2214 I GCM     : GCM config loaded
,08-11 12:28:06.660  7117  7117 V SetupWizard: Connected to Gservices successfully
,08-11 12:28:07.410  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=49.5, 0.0, 0.0  rx=57.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2032472177] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:07.413  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=49.5, 0.0, 0.0  rx=57.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2032472180] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:07.413  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 12:28:07.435  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 12:28:07.448  1035  1438 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-11 12:28:07.482  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:07.494  1035  1109 D Tethering: MasterInitialState.processMessage what=3
,08-11 12:28:07.509  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:28:07.509  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:07.509  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:07.509  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:07.509  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:07.509  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:07.509  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:07.509  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:07.509  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:07.509  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.510  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:28:07.518  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:28:07.518  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:07.518  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:07.518  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:07.518  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:07.518  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:07.518  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:07.518  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:07.518  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:07.518  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.518  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:07.520  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:07.522  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.522  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:07.522  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:07.522  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:07.522  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:07.522  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:07.522  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:07.522  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:07.522  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:07.522  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.522  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:07.538  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-11 12:28:07.544  6438  6467 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 12:28:07.555  5755  5755 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-11 12:28:07.573  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:07.587  1035  1716 D WifiServiceImplEx: setWifiEnabled: false pid=6630, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 12:28:07.587  1035  1716 D WifiService: setWifiEnabled: false pid=6630, uid=10118
08-11 12:28:07.587  1035  1716 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 12:28:07.595  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 12:28:07.595  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:07.600  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 12:28:07.600  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 12:28:07.600  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-11 12:28:07.603  1035  1399 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-11 12:28:07.604  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-11 12:28:07.604  1035  1399 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-11 12:28:07.604  1035  1399 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-11 12:28:07.605  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-11 12:28:07.605  1035  1399 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-11 12:28:07.605  1035  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 12:28:07.605  1035  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 12:28:07.606  1035  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 12:28:07.606  1035  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-11 12:28:07.612  1035  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-11 12:28:07.613  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-11 12:28:07.613  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-11 12:28:07.616  1035  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.616  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.616  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-11 12:28:07.616  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 12:28:07.619  1035  1399 D WifiNative-wlan0: SET ps 1: returned true
08-11 12:28:07.620   322   894 D CommandListener: Clearing all IP addresses on wlan0
08-11 12:28:07.627  1035  7364 D DhcpStateMachine: RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-11 12:28:07.658  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-11 12:28:07.659  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-11 12:28:07.663  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-11 12:28:07.673  1035  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:07.673  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:07.674  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:07.674  1035  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:07.674  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-11 12:28:07.674  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:07.675  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2bb2835e
08-11 12:28:07.675  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-11 12:28:07.675  7061  7061 D AppUp4:CustFacade: isPhone : true
08-11 12:28:07.677  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.677  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.677  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@351aff2c
08-11 12:28:07.677  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-11 12:28:07.679  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:07.679  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:07.679  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-11 12:28:07.679  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-11 12:28:07.681  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-11 12:28:07.681  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:07.681  1035  1458 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-11 12:28:07.681  1035  1458 D ConnectivityService: ignoring duplicate network state non-change
08-11 12:28:07.681  1035  1458 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-11 12:28:07.682  1035  1399 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-11 12:28:07.685  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:07.685  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:07.686  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 12:28:07.691  1035  1651 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-11 12:28:07.691  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.691  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.691  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-11 12:28:07.691  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.692  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-11 12:28:07.698  1035  1390 D LGWifiP2pService: P2pDisablingState
08-11 12:28:07.698  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=-21ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.698  1035  1390 D LGWifiP2pService: p2p socket connection lost
08-11 12:28:07.698  1035  1390 D LGWifiP2pService: P2pDisabledState
08-11 12:28:07.699  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-11 12:28:07.699  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:07.699  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:07.699  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 12:28:07.699  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-11 12:28:07.699  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-11 12:28:07.700  1035  1399 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-11 12:28:07.700  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.701  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.701  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-11 12:28:07.701  7263  7263 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-11 12:28:07.701  1035  1559 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.701  1035  1557 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.701  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-11 12:28:07.701  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 12:28:07.702  1035  1399 D WifiNative-wlan0: SET ps 1: returned true
08-11 12:28:07.707  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-11 12:28:07.707  1942  1942 D WfdsService: WifiP2pState is changed : false
,08-11 12:28:07.708  1942  2268 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-11 12:28:07.708  1942  2268 D WfdsService: Set the WFDS Monitor: false
08-11 12:28:07.710  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:07.710  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:07.711  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:07.712  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:07.712  1942  2268 D WfdsMonitor: WFDS Monitor is stopped
08-11 12:28:07.712  1942  2268 D WfdsService: STATE : WfdsDisabledState - enter
08-11 12:28:07.712  1942  7310 D CtrlSupplicant: Received on exit socket, terminate
08-11 12:28:07.712  1942  7310 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-11 12:28:07.712  1942  7310 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-11 12:28:07.712  1942  7310 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-11 12:28:07.712  1942  2269 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-11 12:28:07.712  1942  2268 W WfdsService: DefaultState - msg [9445378] is not handled
08-11 12:28:07.713  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:07.715  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:07.717  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:07.725  7088  7088 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-11 12:28:07.729  4321  7473 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-11 12:28:07.731  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:07.734   322   894 D CommandListener: Clearing all IP addresses on wlan0
08-11 12:28:07.734  1035  1458 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-11 12:28:07.734  1035  1458 D DSQN    : disableDataServiceNotify
08-11 12:28:07.734  1035  1458 D DSQN    : stop dsqn bin
,08-11 12:28:07.735  4321  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:07.735  4321  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 12:28:07.736   322  7476 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-11 12:28:07.736  1035  1399 D WifiNative-p2p0: doBoolean: TERMINATE
08-11 12:28:07.737  1035  1399 D WifiNative-p2p0: TERMINATE: returned true
08-11 12:28:07.737  1035  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 12:28:07.737  1035  1399 E WifiStateMachine: useWiFiOffloading() : false
08-11 12:28:07.737  1035  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 12:28:07.737  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-11 12:28:07.737  1035  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-11 12:28:07.739  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-11 12:28:07.741  1035  1458 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-11 12:28:07.741  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:07.742  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-11 12:28:07.742  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:07.742  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:07.742  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:07.742  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 12:28:07.742  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:07.742  1035  1458 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:07.743  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-11 12:28:07.743  1035  1458 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-11 12:28:07.743  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.743  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.743  1035  7361 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-11 12:28:07.743  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-11 12:28:07.743  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:07.744  1035  1458 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-11 12:28:07.744  1035  1458 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-11 12:28:07.744  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-11 12:28:07.745  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-11 12:28:07.745  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:07.745  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-11 12:28:07.746  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:07.750  1035  1458 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, a,ction=android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:07.750  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-11 12:28:07.750  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.750  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:07.750  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:07.750  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:07.750  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:07.750  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:07.750  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:07.750  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:07.750  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:07.750  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.750  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:07.751  1035  1458 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:07.751  1035  1458 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:07.751  1035  1458 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:07.751  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-11 12:28:07.752  1035  1458 D NetworkManagementService: Removing idletimer
08-11 12:28:07.752  1035  1399 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:07.752  1035  1458 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:07.752  1035  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:07.752  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:07.752  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-11 12:28:07.753  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-11 12:28:07.753  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-11 12:28:07.755  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-11 12:28:07.755  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 12:28:07.755  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 12:28:07.755  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-11 12:28:07.755  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 12:28:07.755  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 12:28:07.755  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-11 12:28:07.758  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.758  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:07.758  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:07.758  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:07.758  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:07.758  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:07.758  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:07.758  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:07.758  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:07.758  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.758  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:07.759  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.759  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:07.759  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:07.759  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:07.759  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:07.759  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:07.759  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:07.759  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:07.759  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:07.759  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:07.759  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:07.760  7088  7477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:07.765  6970  7479 W FormManager: Network not available. Please check & try again.
08-11 12:28:07.771  3477  3477 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 12:28:07.771  3477  3477 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:07.771  3477  3477 I LgeMiscReceiver: networkInfo.isConnected() = true
08-11 12:28:07.771  3477  3477 D PhoneState: setPdpRejectCasuse : false
08-11 12:28:07.774  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-11 12:28:07.774  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-11 12:28:07.775  6970  7480 V FormManager: Network unavailable.
08-11 12:28:07.784  7186  7186 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:7
,08-11 12:28:07.787  6970  7480 V FormManager: Network unavailable.
08-11 12:28:07.788  7263  7263 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-11 12:28:07.788  7263  7263 I wpa_supplicant: monitor socket send errors count : 1
08-11 12:28:07.788  7263  7263 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
08-11 12:28:07.789  1035  7292 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-11 12:28:07.789  1035  7292 D WifiMonitor: Dropping event because (p2p0) is stopped
08-11 12:28:07.789  7186  7186 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 12:28:07.789  7186  7186 D Weather.Utils: 2 : All the weather widget is gone.
08-11 12:28:07.790  7186  7186 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 12:28:07.790  7186  7186 D WeatherAncestor: connectivity changed - connection : true
08-11 12:28:07.790  7186  7186 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@96840c
08-11 12:28:07.790  7186  7186 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-11 12:28:07.790  7186  7186 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 12:28:07.791  7186  7186 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-11 12:28:07.791  7186  7186 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-11 12:28:07.791  7186  7186 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:7
08-11 12:28:07.808  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 12:28:07.809  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:07.810  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:07.812  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 12:28:07.812  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-11 12:28:07.812  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 12:28:07.812  1035  7292 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 12:28:07.812  1035  7292 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-11 12:28:07.813  7263  7263 W wpa_supplicant: USIM:  scard_deinit function
08-11 12:28:07.813  1035  1399 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=161733
08-11 12:28:07.813  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:07.813  1035  1109 D Tethering: InitialState.processMessage what=4
08-11 12:28:07.813  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:07.814  1035  1399 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=161734
08-11 12:28:07.814  1035  1399 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=161735  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-11 12:28:07.815  1035  1399 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=161735  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-11 12:28:07.815  1035  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-11 12:28:07.815  1035  1399 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:07.815  1035  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:07.820  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 12:28:07.824  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 12:28:07.824  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 12:28:07.824  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:28:07.828  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 12:28:07.833  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:28:07.840  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 12:28:07.841  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:07.841  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:07.842  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:07.842  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:07.843  6929  6929 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 12:28:07.846  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 12:28:07.847  1035  7364 D DhcpStateMachine: StoppedState
08-11 12:28:07.847  1035  7364 D DhcpStateMachine: StoppedState{ when=-145ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:07.848  1035  1399 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-11 12:28:07.848  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 12:28:07.848  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 12:28:07.848  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:28:07.848  1035  1399 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-11 12:28:07.850  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 12:28:07.854  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:07.859  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:07.859  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 12:28:07.860  6929  6929 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 12:28:07.864  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:07.867  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-11 12:28:07.867  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 12:28:07.867  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:28:07.870  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:07.877  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:07.882  6929  6929 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:07.882  6929  6929 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 12:28:07.883  6929  6929 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-11 12:28:07.889  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:28:07.891  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 12:28:07.895  6970  7484 W FormManager: Network not available. Please check & try again.
,08-11 12:28:07.895  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:07.898  7263  7263 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-11 12:28:07.898  1035  7292 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-11 12:28:07.898  1035  7292 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-11 12:28:07.899  1035  7292 D WifiMonitor: Disconnecting from the supplicant, no more events
08-11 12:28:07.899  1035  1399 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-11 12:28:07.906  6970  7485 V FormManager: Network unavailable.
08-11 12:28:07.908  6970  7485 V FormManager: Network unavailable.
,08-11 12:28:07.914  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 12:28:07.914  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 12:28:07.914  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 12:28:07.914  6861  6861 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 12:28:07.916  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 12:28:07.919  6861  6861 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 12:28:07.919  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 12:28:07.919  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 12:28:07.919  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 12:28:07.919  6861  6861 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 12:28:07.919  6861  6861 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-11 12:28:07.969  7205  7232 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-11 12:28:08.001  1035  1399 D WifiOffDelayIfNotUsed: stopMonitoring
,08-11 12:28:08.002  1035  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 12:28:08.002  1035  1399 E WifiStateMachine: useWiFiOffloading() : false
08-11 12:28:08.002  1035  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 12:28:08.004  1942  1942 D WfdsService: Supplicant Connection state is changed : false
,08-11 12:28:08.005  1942  2268 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-11 12:28:08.005  1942  2268 D WfdsService: Set the WFDS Monitor: false
08-11 12:28:08.006  1942  2268 D WfdsMonitor: WFDS Monitor is stopped
08-11 12:28:08.008  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-11 12:28:08.008  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:08.015  2476  2476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:08.017  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:08.017  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:08.017  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:08.017  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:08.017  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:08.017  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:08.017  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:08.017  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:08.017  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:08.018  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-11 12:28:08.019  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:08.020  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:08.020  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:08.020  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:08.020  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:08.020  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:08.020  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:08.020  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:08.020  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:08.020  1035  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-11 12:28:08.020  1035  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-11 12:28:08.022  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:08.023  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 12:28:08.023  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:08.025  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:08.030  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:08.037  4321  7489 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 12:28:08.044  6900  6900 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-11 12:28:08.044  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-11 12:28:08.044  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:28:08.048  4321  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 12:28:08.049  4321  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 12:28:08.051  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-11 12:28:08.054  6970  7491 W FormManager: Network not available. Please check & try again.
08-11 12:28:08.055  6970  7492 V FormManager: Network unavailable.
08-11 12:28:08.057  6970  7492 V FormManager: Network unavailable.
08-11 12:28:08.062  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:28:08.394  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7457
,08-11 12:28:08.396  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7460
,08-11 12:28:08.396  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7462
,08-11 12:28:08.397  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7463
,08-11 12:28:08.398  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7468
08-11 12:28:08.399  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7469
08-11 12:28:08.400  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7494
08-11 12:28:08.949  1035  1959 I ActivityManager: Killing 6946:com.lge.settings.easy/1000 (adj 15): empty #17
,08-11 12:28:08.983  1035  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_6946/cgroup.procs: No such file or directory
,08-11 12:28:10.444  1035  1399 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:2032475212] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:10.446  1035  1399 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:2032475214] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:10.753  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:10.770  1035  1109 D Tethering: MasterInitialState.processMessage what=3
08-11 12:28:10.780  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:10.785  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:10.787  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:10.789  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:10.791  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:10.795  1035  1109 D Tethering: MasterInitialState.processMessage what=3
,08-11 12:28:10.805  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:10.806  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:10.809  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:10.813  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-11 12:28:10.814  6438  6467 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 12:28:10.825  5755  5755 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-11 12:28:10.833  5755  5755 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-11 12:28:10.851  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:10.870  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 12:28:10.870  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:10.871  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-11 12:28:10.871  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-11 12:28:10.875  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-11 12:28:10.879  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2bb2835e
08-11 12:28:10.879  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-11 12:28:10.879  7061  7061 D AppUp4:CustFacade: isPhone : true
08-11 12:28:10.879  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-11 12:28:10.879  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-11 12:28:10.884  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:10.884  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:10.886  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 12:28:10.891  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:10.898  7088  7088 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-11 12:28:10.914  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:10.916  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:10.916  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:10.928  4321  7515 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 12:28:10.935  4321  7523 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:10.935  4321  7523 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 12:28:10.938  3477  3477 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 12:28:10.938  3477  3477 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:10.940  3477  3477 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-11 12:28:10.942  7088  7517 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:10.945  6970  7521 W FormManager: Network not available. Please check & try again.
08-11 12:28:10.945  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-11 12:28:10.946  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-11 12:28:10.956  7186  7186 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:10
,08-11 12:28:10.958  6970  7522 V FormManager: Network unavailable.
08-11 12:28:10.960  7186  7186 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-11 12:28:10.960  7186  7186 D Weather.Utils: 2 : All the weather widget is gone.
08-11 12:28:10.961  7186  7186 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 12:28:10.961  7186  7186 D WeatherAncestor: connectivity changed - connection : true
08-11 12:28:10.961  7186  7186 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@96840c
08-11 12:28:10.962  6970  7522 V FormManager: Network unavailable.
08-11 12:28:10.962  7186  7186 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-11 12:28:10.962  7186  7186 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 12:28:10.962  7186  7186 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-11 12:28:10.962  7186  7186 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-11 12:28:10.962  7186  7186 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:10
08-11 12:28:10.986  6438  6438 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-11 12:28:10.994  6438  6467 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 12:28:11.004  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:11.017  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 12:28:11.018  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:11.018  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-11 12:28:11.018  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-11 12:28:11.021  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-11 12:28:11.026  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2bb2835e
08-11 12:28:11.026  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-11 12:28:11.026  7061  7061 D AppUp4:CustFacade: isPhone : true
08-11 12:28:11.026  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-11 12:28:11.027  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-11 12:28:11.031  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:11.031  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:11.034  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 12:28:11.037  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:11.041  4321  7527 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 12:28:11.044  4321  7528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:11.044  4321  7528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-11 12:28:11.048  7088  7088 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-11 12:28:11.073  7088  7530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:11.080  3477  3477 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 12:28:11.080  3477  3477 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:11.080  3477  3477 I LgeMiscReceiver: networkInfo.isConnected() = false
08-11 12:28:11.082  6970  7531 W FormManager: Network not available. Please check & try again.
08-11 12:28:11.093  7117  7117 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-11 12:28:11.093  7117  7117 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-11 12:28:11.107  6970  7533 V FormManager: Network unavailable.
,08-11 12:28:11.111  7186  7186 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:11
08-11 12:28:11.114  7186  7186 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 12:28:11.114  6970  7533 V FormManager: Network unavailable.
08-11 12:28:11.114  7186  7186 D Weather.Utils: 2 : All the weather widget is gone.
08-11 12:28:11.115  7186  7186 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 12:28:11.115  7186  7186 D WeatherAncestor: connectivity changed - connection : true
08-11 12:28:11.115  7186  7186 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@96840c
08-11 12:28:11.116  7186  7186 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-11 12:28:11.116  7186  7186 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 12:28:11.116  7186  7186 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-11 12:28:11.116  7186  7186 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-11 12:28:11.117  7186  7186 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:11
08-11 12:28:11.135  1035  1870 I ActivityManager: Killing 7346:com.lge.bnr/1000 (adj 15): empty #17
,08-11 12:28:11.177  1035  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_7346/cgroup.procs: No such file or directory
,08-11 12:28:12.605  1035  1716 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:28:12.606  1035  1716 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-11 12:28:12.637  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 12:28:12.638  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 12:28:12.638  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-11 12:28:12.641  1035  1109 D BluetoothManagerService: Message: 1
08-11 12:28:12.641  1035  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-11 12:28:12.671  1035  1109 D BluetoothManagerService: Message: 20
08-11 12:28:12.671  1035  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@248d9b7:true
,08-11 12:28:12.675  7000  7000 D BluetoothAdapterState: make
08-11 12:28:12.680  7000  7000 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-11 12:28:12.680  7000  7000 I bluedroid-qcom: init
08-11 12:28:12.681  7000  7545 I BluetoothAdapterState: Entering OffState
08-11 12:28:12.681  7000  7000 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-11 12:28:12.682  7000  7000 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-11 12:28:12.682  7000  7000 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 12:28:12.682  7000  7000 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 12:28:12.682  7000  7000 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-11 12:28:12.684  7000  7000 I bluedroid-qcom: get_profile_interface socket
08-11 12:28:12.684  7000  7000 I bluedroid-qcom: get_profile_interface map_client
,08-11 12:28:12.688  7000  7549 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-11 12:28:12.683  7548  7548 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:12.683  7548  7548 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:12.698  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-11 12:28:12.700  1035  1109 D BluetoothManagerService: Message: 40
08-11 12:28:12.700  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-11 12:28:12.701  7000  7015 I bluedroid-qcom: config_hci_snoop_log
08-11 12:28:12.703  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:12.703  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:12.703  1035  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-11 12:28:12.703  1035  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-11 12:28:12.709  7548  7548 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-11 12:28:12.709  7548  7548 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-11 12:28:12.709  7548  7548 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-11 12:28:12.712  7548  7548 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-11 12:28:12.718  7000  7545 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-11 12:28:12.718  7000  7545 D BluetoothAdapterProperties: Setting state to 11
08-11 12:28:12.718  7000  7545 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-11 12:28:12.720  7548  7548 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-11 12:28:12.720  7548  7548 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-11 12:28:12.721  1035  1109 D BluetoothManagerService: Message: 60
08-11 12:28:12.721  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-11 12:28:12.722  1035  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-11 12:28:12.729  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 12:28:12.732  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:12.734  6861  6861 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-11 12:28:12.739  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:12.739  1035  1399 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-11 12:28:12.740  1035  1399 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-11 12:28:12.745  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:12.752  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:12.755  7000  7549 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-11 12:28:12.758  7000  7000 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-11 12:28:12.763  7000  7549 D BluetoothAdapterProperties: Name is: G3
08-11 12:28:12.765  7000  7000 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:12.765  7000  7000 V BluetoothPbapReceiver: ***********state = 11
08-11 12:28:12.767  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-11 12:28:12.767  7000  7545 I LGBluetoothServiceJni: classInitNative: succeeds
08-11 12:28:12.767  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-11 12:28:12.774  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 12:28:12.778  7000  7545 D BluetoothBondStateMachine: make
08-11 12:28:12.781  7000  7545 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:12.781  7000  7545 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-11 12:28:12.782  7000  7545 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:12.782  7000  7545 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-11 12:28:12.782  7000  7545 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-11 12:28:12.783  7000  7567 I BluetoothBondStateMachine: StableState(): Entering Off State
08-11 12:28:12.786  7000  7545 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:12.815  1035  1892 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7568 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-11 12:28:12.819  7000  7545 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 12:28:12.822  7000  7000 D HeadsetService: Received start request. Starting profile...
08-11 12:28:12.823  7000  7000 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 12:28:12.823  7000  7000 D LGBluetoothHfpAdapter: Version 1.6
08-11 12:28:12.824  7000  7545 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:12.826  7000  7000 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-11 12:28:12.827  7000  7000 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 12:28:12.827  7000  7000 D HeadsetStateMachine: make
,08-11 12:28:12.829  7000  7545 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:12.834  7000  7545 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:12.839  7000  7545 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 12:28:12.844  7000  7545 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:12.861  7000  7000 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 12:28:12.861  7000  7000 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 12:28:12.863  7000  7545 V LGMDMManager: Create singleton instance
08-11 12:28:12.866  7000  7000 D HeadsetStateMachine: max_hf_connections = 1
08-11 12:28:12.866  7000  7000 I bluedroid-qcom: get_profile_interface handsfree
08-11 12:28:12.867  7000  7545 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-11 12:28:12.868  7000  7000 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-11 12:28:12.869   326  1397 V AudioPolicyService: registerClient() client 0xb04106e0, uid 1002
08-11 12:28:12.869   326  1398 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-11 12:28:12.869   326  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 12:28:12.869   326  1398 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 12:28:12.869  7000  7000 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-11 12:28:12.870   326  2173 V AudioFlinger: registerClient() client 0xb55814f0, pid 7000
08-11 12:28:12.870   326  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:12.870   326  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:12.870   326  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:12.870  3477  3492 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:12.870   326  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:12.870  3477  3492 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:12.870  7000  7000 V ToneGenerator: Create Track: 0xb4928a80
08-11 12:28:12.870  7000  7000 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-11 12:28:12.871  7000  7000 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-11 12:28:12.871  7000  7016 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:12.871  7000  7016 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-11 12:28:12.871  7000  7016 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:12.871   326  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-11 12:28:12.871  7000  7016 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-11 12:28:12.871   326  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-11 12:28:12.871   326  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 12:28:12.871   326  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 12:28:12.871  1035  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:12.871  1035  1051 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:12.871  1035  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:12.871  1035  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:12.871   326  2173 I AudioFlinger: isAudioPlaybackHookOn() false
08-11 12:28:12.871   326  2174 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-11 12:28:12.871  1604  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:12.871   326  2174 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-11 12:28:12.871  1604  1624 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:12.871   326  2174 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 12:28:12.871   326  2174 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 12:28:12.871 , 1604  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:12.871  1604  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:12.871  1853  3990 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:12.871  7000  7000 V AudioSystem: getLatency() output 2, latency 50
08-11 12:28:12.871  1853  3990 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:12.871  7000  7000 V AudioSystem: getFrameCount() output 2, frameCount 960
08-11 12:28:12.871  7000  7000 V AudioTrack: createTrack_l() output 2 afLatency 50
08-11 12:28:12.871  1853  3990 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:12.871  1853  3990 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:12.871  3477  3493 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:12.871  3477  3493 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:12.872   326  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-11 12:28:12.872   326  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-11 12:28:12.872   326  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-11 12:28:12.872   326  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-11 12:28:12.872   326  1397 V AudioFlinger: createTrack() lSessionId: 20
08-11 12:28:12.873  7000  7000 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-11 12:28:12.873   326  1397 V AudioFlinger: acquiring 20 from 7000, for 7000
08-11 12:28:12.873   326  1397 V AudioFlinger:  added new entry for 20
08-11 12:28:12.873  7000  7000 V ToneGenerator: ToneGenerator INIT OK, time: 166806
08-11 12:28:12.873  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
,08-11 12:28:12.874  7000  7583 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-11 12:28:12.874  7000  7583 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 12:28:12.874  7000  7583 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 12:28:12.874  7000  7583 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-11 12:28:12.875   326  2173 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7000
08-11 12:28:12.876  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:12.876   326  2173 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-11 12:28:12.876   326  2173 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-11 12:28:12.876   326  2173 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-11 12:28:12.876   326  2173 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-11 12:28:12.876   326  2173 V voice   : voice_set_parameters: exit with code(0)
08-11 12:28:12.876   326  2173 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-11 12:28:12.876   326  2173 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-11 12:28:12.876   326  2173 V msm8974_platform: platform_set_parameters: exit with code(0)
08-11 12:28:12.876   326  2173 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-11 12:28:12.876   326  2173 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-11 12:28:12.876   326  2173 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-11 12:28:12.876  7000  7583 V ToneGenerator: ToneGenerator destructor
08-11 12:28:12.876  7000  7583 V ToneGenerator: stopTone
08-11 12:28:12.876  7000  7583 V ToneGenerator: Delete Track: 0xb4928a80
08-11 12:28:12.877  7000  7583 V AudioTrack: ~AudioTrack, releasing session id from 7000 on behalf of 7000
08-11 12:28:12.877   326   326 V AudioFlinger: releasing 20 from 7000 for 7000
08-11 12:28:12.877   326  1398 V AudioPolicyService: AudioCommandThread() adding release output 2
08-11 12:28:12.877   326   326 V AudioFlinger:  decremented refcount to 0
08-11 12:28:12.877   326  1398 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-11 12:28:12.877   326   326 V AudioFlinger: purging stale effects
08-11 12:28:12.877   326  1398 V AudioFlinger: PlaybackThread::Track destructor
08-11 12:28:12.877   326  1256 V AudioPolicyService: AudioCommandThread() waking up
08-11 12:28:12.877   326  1398 V AudioFlinger: removeClient_l() pid 7000, calling pid 326
08-11 12:28:12.877   326  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-11 12:28:12.877   326  1256 V AudioPolicyManager: releaseOutput() 2
08-11 12:28:12.877   326  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-11 12:28:12.877  7000  7000 D A2dpService: Received start request. Starting profile...
08-11 12:28:12.878  7000  7000 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 12:28:12.879  7000  7000 V Avrcp   : make
08-11 12:28:12.880  7000  7000 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-11 12:28:12.880  7000  7000 I bluedroid-qcom: get_profile_interface avrcp
08-11 12:28:12.881  1035  1959 W Process : Unable to open /proc/7587/status
08-11 12:28:12.888  7000  7000 V AudioManager: registerRemoteController: size of Media player list: 0
,08-11 12:28:12.891  7000  7000 E AudioManager: No RCC entry present to update
08-11 12:28:12.891  7000  7000 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-11 12:28:12.895  7000  7000 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-11 12:28:12.896  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-11 12:28:12.896  7000  7000 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-11 12:28:12.901  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-11 12:28:12.955  7568  7568 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-11 12:28:12.956  7568  7568 W LG Account v2.2: No ProfileInfo entries
08-11 12:28:12.956  7568  7568 I LG Account v2.2: isEnabled: false
08-11 12:28:12.957  7568  7568 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 12:28:12.958  7568  7568 I Feature : [Lifetracker]Country: EU
08-11 12:28:12.958  7568  7568 I Feature : [Lifetracker]Operator: OPEN
08-11 12:28:12.958  7568  7568 I Feature : [Lifetracker]Ranking support: false
08-11 12:28:12.958  7568  7568 I Feature : [Lifetracker]Comfort support: false
08-11 12:28:12.958  7568  7568 I Feature : [Lifetracker]Accessory: true
08-11 12:28:12.958  7568  7568 I Feature : [Lifetracker]Health device: true
08-11 12:28:12.959  7568  7568 I Feature : [Lifetracker]Extra Pedometer: false
08-11 12:28:12.959  7568  7568 I Feature : [Lifetracker]Blood glucose device: false
08-11 12:28:12.959  7568  7568 I Feature : [Lifetracker]Device Number: 3
08-11 12:28:12.981  6861  6861 D BluetoothPermissionRequest: onReceive
,08-11 12:28:12.988  6861  6861 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-11 12:28:13.030  1035  1906 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:28:13.030  1035  1906 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:28:13.102  1035  2033 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-11 12:28:13.111  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-11 12:28:13.115  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-11 12:28:13.116  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 12:28:13.116  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 12:28:13.116  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 12:28:13.116  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 12:28:13.116  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,08-11 12:28:13.116  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 12:28:13.116  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 12:28:13.116  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 12:28:13.117  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 12:28:13.117  7000  7000 I BluetoothA2dpServiceJni: classInitNative
08-11 12:28:13.117  7000  7000 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 12:28:13.117  7000  7000 D A2dpStateMachine: make
08-11 12:28:13.121  7000  7000 I bluedroid-qcom: get_profile_interface a2dp
08-11 12:28:13.121  7000  7593 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-11 12:28:13.124  7000  7000 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-11 12:28:13.124  7000  7000 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-11 12:28:13.125  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:13.125  7000  7592 D A2dpStateMachine: Enter Disconnected: -2
08-11 12:28:13.125  7000  7000 I BluetoothHidServiceJni: classInitNative: succeeds
08-11 12:28:13.127  7000  7000 D HidService: Received start request. Starting profile...
08-11 12:28:13.127  7000  7000 I bluedroid-qcom: get_profile_interface hidhost
08-11 12:28:13.127  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:13.128  7000  7000 I BluetoothHealthServiceJni: classInitNative: succeeds
08-11 12:28:13.129  7000  7000 D HealthService: Received start request. Starting profile...
08-11 12:28:13.132  7000  7000 I bluedroid-qcom: get_profile_interface health
08-11 12:28:13.132  7000  7000 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-11 12:28:13.132  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:13.133  7000  7000 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 12:28:13.134  7000  7000 D PanService: Received start request. Starting profile...
08-11 12:28:13.134  7000  7000 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 12:28:13.134  7000  7000 I bluedroid-qcom: get_profile_interface pan
08-11 12:28:13.143  7000  7000 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-11 12:28:13.143  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:13.146  7000  7000 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-11 12:28:13.162  7000  7000 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 12:28:13.163  7000  7000 D BtGatt.GattService: Received start request. Starting profile...
,08-11 12:28:13.163  7000  7000 D BtGatt.GattService: start()
08-11 12:28:13.163  7000  7000 I bluedroid-qcom: get_profile_interface gatt
08-11 12:28:13.164  7000  7000 D BtGatt.AdvertiseManager: advertise manager created
08-11 12:28:13.177  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
,08-11 12:28:13.180  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:13.181  7000  7000 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-11 12:28:13.184  7000  7000 V BluetoothMapService: BluetoothMapBinder()
08-11 12:28:13.185  7000  7000 D BluetoothMapService: Received start request. Starting profile...
08-11 12:28:13.185  7000  7000 D BluetoothMapService: start()
08-11 12:28:13.189  7000  7000 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-11 12:28:13.189  7000  7000 D BluetoothMapEmailAppObserver: createReceiver()
,08-11 12:28:13.191  7000  7000 D BluetoothMapEmailAppObserver: initObservers()
,08-11 12:28:13.191  7000  7000 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-11 12:28:13.201  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:13.202  7000  7000 D HeadsetStateMachine: Proxy object connected
08-11 12:28:13.203  7000  7000 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-11 12:28:13.203  7000  7000 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-11 12:28:13.206  7000  7583 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 12:28:13.208  7000  7583 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-11 12:28:13.208  7000  7583 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-11 12:28:13.216  7000  7000 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 12:28:13.225  7000  7000 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 12:28:13.230  7000  7000 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 12:28:13.237  7000  7000 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 12:28:13.238  7000  7000 V PanService: [BTUI] SIM Extra State :ABSENT
08-11 12:28:13.245  7000  7000 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 12:28:13.252  7000  7000 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-11 12:28:13.252  7000  7000 V BluetoothMapService: Handler(): got msg=1
08-11 12:28:13.254  7000  7545 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-11 12:28:13.254  7000  7545 I bluedroid-qcom: enable
08-11 12:28:13.255  7000  7545 I bt_hci_bdroid: init
08-11 12:28:13.255  7000  7603 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-11 12:28:13.255  7000  7603 I bt-btu  : btu_task pending for preload complete event
08-11 12:28:13.258  7000  7545 I bt_vendor: bt-vendor : init
08-11 12:28:13.259  7000  7000 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:13.258  7000  7545 I bt_vendor: bt-vendor : get_bt_soc_type
08-11 12:28:13.260  7000  7545 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-11 12:28:13.260  7000  7545 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-11 12:28:13.260  7000  7545 D bt_userial_mct: userial_init
,08-11 12:28:13.264  7000  7000 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 12:28:13.264  7000  7000 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 12:28:13.265  7000  7000 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 12:28:13.265  7000  7545 D bt_hci_bdroid: set_power 1
08-11 12:28:13.265  7000  7545 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-11 12:28:13.265  7000  7545 I bt_vendor: Starting hciattach daemon
08-11 12:28:13.265  7000  7545 I bt_vendor: try to set true
08-11 12:28:13.265  7000  7000 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:13.265  7000  7000 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-11 12:28:13.263  7606  7606 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:13.263  7606  7606 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 12:28:13.298  7607  7607 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-11 12:28:13.327  1035  1924 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7610 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 12:28:13.369  7630  7630 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-11 12:28:13.380  7631  7631 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-11 12:28:13.387  7610  7610 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 12:28:13.402  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-11 12:28:13.404  1035  1051 I ActivityManager: Killing 6737:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-11 12:28:13.415  7634  7634 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-11 12:28:13.424  6929  6929 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-11 12:28:13.425  6929  6929 W System.err: android.os.DeadObjectException
08-11 12:28:13.426  6929  6929 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 12:28:13.426  6929  6929 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-11 12:28:13.426  6929  6929 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-11 12:28:13.426  6929  6929 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-11 12:28:13.426  6929  6929 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 12:28:13.426  6929  6929 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 12:28:13.426  6929  6929 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:28:13.427  6929  6929 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:28:13.427  6929  6929 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:28:13.427  6929  6929 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:28:13.427  6929  6929 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:28:13.427  6929  6929 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:28:13.427  6929  6929 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:28:13.427  6929  6929 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 12:28:13.427  6929  6929 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-11 12:28:13.427  6929  6929 W System.err: android.os.DeadObjectException
08-11 12:28:13.428  6929  6929 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 12:28:13.428  6929  6929 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-11 12:28:13.428  6929  6929 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-11 12:28:13.428  6929  6929 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-11 12:28:13.428  6929  6929 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-11 12:28:13.428  6929  6929 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-11 12:28:13.428  6929  6929 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:28:13.428  6929  6929 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:28:13.428  6929  6929 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:28:13.428  6929  6929 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:28:13.428  6929  6929 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:28:13.428  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-11 12:28:13.428  6929  6929 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:28:13.429  6929  6929 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:28:13.429  6929  6929 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 12:28:13.429  6929  6929 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-11 12:28:13.432  6929  6929 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-11 12:28:13.441  7637  7637 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-11 12:28:13.462  7639  7639 I libmdmdetect: ESOC framework not supported
08-11 12:28:13.463  7639  7639 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-11 12:28:13.471  7639  7639 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-11 12:28:13.471  7639  7639 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-11 12:28:13.471  7639  7639 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-11 12:28:13.471  7639  7639 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-11 12:28:13.471  7639  7639 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-11 12:28:13.471  7639  7639 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-11 12:28:13.471  7639  7639 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-11 12:28:13.509  7639  7640 E QC-QMI  : qmi_client [7639] 14: failed to locate client data
,08-11 12:28:13.509   491   491 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-11 12:28:13.509   491   491 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-11 12:28:13.519  1035  1924 W libprocessgroup: failed to open /acct/uid_1000/pid_6737/cgroup.procs: No such file or directory
08-11 12:28:13.520  1035  1924 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-11 12:28:13.528  6929  6929 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-11 12:28:13.529  6929  6929 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-11 12:28:13.554  7641  7641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-11 12:28:13.570  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-11 12:28:13.591  1035  1996 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7644 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 12:28:13.592  6929  6929 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-11 12:28:13.618  7000  7545 I bt_vendor: bluetooth satus is on
08-11 12:28:13.618  7000  7545 D bt_hci_bdroid: preload
08-11 12:28:13.618  7000  7605 D bt_userial_mct: userial_open(port:0)
08-11 12:28:13.618  7000  7605 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-11 12:28:13.622  7000  7605 I bt_vendor: Done intiailizing UART
08-11 12:28:13.623  7000  7605 I bt_vendor: Done intiailizing UART
08-11 12:28:13.623  7000  7605 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-11 12:28:13.623  7000  7605 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-11 12:28:13.623  7000  7661 D bt_userial_mct: Entering userial_read_thread()
08-11 12:28:13.623  7000  7603 I bt-btu  : btu_task received preload complete event
08-11 12:28:13.623  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-11 12:28:13.624  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-11 12:28:13.628  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_HCI
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_BNEP
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_BTM
,08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_GAP
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_SMP
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 12:28:13.634  7000  7603 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 12:28:13.678  7644  7644 D UEI.SmartControl: Quickset Services start...
,08-11 12:28:13.681  7644  7644 I UEI.SmartControl: Manufacture = LGE
08-11 12:28:13.681  7644  7644 D UEI.SmartControl: Id = LGNevo
,08-11 12:28:13.683  7644  7644 D UEI.SmartControl: File observer start...
08-11 12:28:13.684  7644  7644 E UEI.SmartControl: IR Port is disabled: false
08-11 12:28:13.684  7644  7644 D UEI.SmartControl: Starting file observer...
08-11 12:28:13.685  7644  7644 D UEI.SmartControl: Extracting JNI libs...
08-11 12:28:13.685  7644  7644 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-11 12:28:13.726  7000  7603 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-11 12:28:13.726  7000  7603 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ee061 
08-11 12:28:13.726  7000  7603 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ee061 
,08-11 12:28:13.771  7000  7549 E bt-btif : Calling BTA_HhEnable
,08-11 12:28:13.771  7000  7549 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-11 12:28:13.772  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-11 12:28:13.772  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-11 12:28:13.772  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-11 12:28:13.772  7000  7549 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-11 12:28:13.772  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-11 12:28:13.772  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-11 12:28:13.775  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-11 12:28:13.776  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-11 12:28:13.777  7000  7549 D BluetoothAdapterProperties: Name is: G3
,08-11 12:28:13.780  7000  7549 D BluetoothAdapterProperties: Scan Mode:20
08-11 12:28:13.781  7000  7549 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 12:28:13.781  7000  7549 D bt_hci_bdroid: postload
08-11 12:28:13.781  7000  7605 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 12:28:13.782  7000  7605 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 12:28:13.782  7000  7603 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-11 12:28:13.783  7000  7549 D bte_conf: Device ID record 1 : primary
08-11 12:28:13.783  7000  7549 D bte_conf:   vendorId            = 00c4
08-11 12:28:13.783  7000  7549 D bte_conf:   vendorIdSource      = 0001
08-11 12:28:13.783  7000  7549 D bte_conf:   product             = 13a1
08-11 12:28:13.783  7000  7549 D bte_conf:   version             = 1000
08-11 12:28:13.783  7000  7549 D bte_conf:   clientExecutableURL = 
08-11 12:28:13.783  7000  7549 D bte_conf:   serviceDescription  = 
08-11 12:28:13.783  7000  7549 D bte_conf:   documentationURL    = 
08-11 12:28:13.783  7000  7549 D bte_conf: bte_load_did_conf no section named DID2.
08-11 12:28:13.787  7000  7545 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-11 12:28:13.787  7000  7545 D BluetoothAdapterProperties: ScanMode =  20
08-11 12:28:13.787  7000  7545 D BluetoothAdapterProperties: State =  11
08-11 12:28:13.787  7000  7545 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-11 12:28:13.787  7000  7545 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-11 12:28:13.788  7000  7545 D BluetoothAdapterProperties: Setting state to 12
08-11 12:28:13.788  7000  7545 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 12:28:13.788  1035  1109 D BluetoothManagerService: Message: 60
08-11 12:28:13.788  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-11 12:28:13.788  1035  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-11 12:28:13.789  7000  7545 I BluetoothAdapterState: Entering On State
08-11 12:28:13.789  7000  7549 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-11 12:28:13.790  7000  7549 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-11 12:28:13.793  6861  6878 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 12:28:13.783  7664  7664 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:13.783  7664  7664 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:13.805  7000  7549 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 12:28:13.805  7000  7605 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 12:28:13.806  7000  7605 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 12:28:13.806  7000  7549 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-11 12:28:13.807  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:28:13.808  7644  7644 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-11 12:28:13.808  7644  7644 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-11 12:28:13.808  7644  7644 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-11 12:28:13.810  7000  7545 D LGBluetoothServiceAdapter: [BTUI] OnState
08-11 12:28:13.810  7000  7545 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-11 12:28:13.810  7000  7545 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-11 12:28:13.813  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:13.813  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:13.813  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:13.813  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:13.813  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:13.813  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:13.813  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:13.813  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:13.814  7000  7603 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:13.814  7000  7603 W bt-smp  : Plain text(LSB ~ MSB) = 5c 89 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:13.814  7000  7603 W bt-smp  : Encrypted text(LSB ~ MSB) = 2e 29 86 9c 70 80 47 ef 1a a5 c6 37 6e ab 8c b8 
08-11 12:28:13.814  7000  7603 W bt-btm  : Stopping oneshot timer
08-11 12:28:13.814  7000  7605 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 12:28:13.815  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:13.815  7000  7661 E bt_mct  : hci lib postload completed
08-11 12:28:13.817  7000  7545 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-11 12:28:13.820  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:13.820  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:13.820  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:13.820  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:13.820  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:13.820  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:13.820  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:13.820  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:28:13.825  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:13.829  6861  6880 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 12:28:13.830  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:13.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:13.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:13.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:13.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:13.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:13.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:13.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:13.830  1853  1853 D BluetoothHeadset: Proxy object connected
08-11 12:28:13.832  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:28:13.835  1853  3992 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:28:13.838  7000  7603 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:13.838  7000  7603 W bt-smp  : Plain text(LSB ~ MSB) = 6a 19 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:13.838  7000  7603 W bt-smp  : Encrypted text(LSB ~ MSB) = 40 13 bb 5d bf 60 5c 4e 0e 84 d5 76 c3 56 16 da 
08-11 12:28:13.838  7000  7603 W bt-btm  : Stopping oneshot timer
08-11 12:28:13.838  6861  6861 D BluetoothInputDevice: Proxy object connected
08-11 12:28:13.838  6861  6861 D HidProfile: Bluetooth service connected
08-11 12:28:13.840  7000  7545 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-11 12:28:13.840  1853  1853 D BluetoothHeadset: Proxy object connected
08-11 12:28:13.841  1035  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:28:13.841  1853  3990 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:28:13.842  1035  1035 D BluetoothHeadset: Proxy object connected
08-11 12:28:13.846  1853  1853 D BluetoothHeadset: Proxy object connected
08-11 12:28:13.846  6861  6880 D BluetoothPan: onBluetoothStateChange on: true
08-11 12:28:13.846  6861  6880 D BluetoothPan: onBluetoothStateChange call bindService
08-11 12:28:13.849  1035  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-11 12:28:13.852  6861  6878 D BluetoothMap: onBluetoothStateChange: up=true
08-11 12:28:13.853  7000  7603 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:13.853  7000  7603 W bt-smp  : Plain text(LSB ~ MSB) = c4 7f 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:13.853  7000  7603 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d 8b 9b 0a 86 93 b7 39 61 1c 3d 65 5c 24 2d 86 
08-11 12:28:13.853  7000  7603 W bt-btm  : Stopping oneshot timer
08-11 12:28:13.854  1035  1035 D BluetoothA2dp: Proxy object connected
08-11 12:28:13.857  6861  6861 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 12:28:13.857  6861  6861 D PanProfile: Bluetooth service connected
08-11 12:28:13.859  7670  7670 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-11 12:28:13.861  1035  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-11 12:28:13.861  1035  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-11 12:28:13.864  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-11 12:28:13.865  7000  7603 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:13.865  7000  7603 W bt-smp  : Plain text(LSB ~ MSB) = c5 8e 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:13.865  7000  7603 W bt-smp  : Encrypted text(LSB ~ MSB) = ee 98 7d 99 a9 30 b6 36 28 ff 0a 52 9f 0f 82 ea 
08-11 12:28:13.865  7000  7603 W bt-btm  : Stopping oneshot timer
08-11 12:28:13.866  1942  2095 D LGBluetoothAPIService: Message: 1
08-11 12:28:13.866  1942  2095 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-11 12:28:13.867  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-11 12:28:13.867  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 12:28:13.870  1035  1109 D BluetoothManagerService: Message: 40
08-11 12:28:13.870  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-11 12:28:13.874  6630  6630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 12:28:13.875  7000  7000 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:13.875  7000  7000 D BluetoothMapService: STATE_ON
08-11 12:28:13.876  1942  2095 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-11 12:28:13.876  7000  7000 D LGBluetoothAPIServer: [BTUI] onCreate()
08-11 12:28:13.876  7000  7000 D LGBluetoothAPIServer: [BTUI] onBind()
,08-11 12:28:13.879  6861  6861 D BluetoothMap: Proxy object connected
08-11 12:28:13.879  6861  6861 D MapProfile: Bluetooth service connected
08-11 12:28:13.879  6861  6861 D BluetoothMap: getConnectedDevices()
08-11 12:28:13.879  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-11 12:28:13.879  7000  7000 V BluetoothMapService: Handler(): got msg=1
08-11 12:28:13.880  7000  7000 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-11 12:28:13.880  1942  2095 D LGBluetoothAPIService: Message: 100
08-11 12:28:13.880  1942  2095 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-11 12:28:13.880  7000  7016 V BluetoothMapService: getConnectedDevices()
08-11 12:28:13.881  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:13.882  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:13.883  6861  6861 D LocalBluetoothProfileManager: Adding local A2DP profile
08-11 12:28:13.884  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:13.885  1035  1109 D BluetoothManagerService: Message: 30
08-11 12:28:13.886  7000  7677 D BluetoothMapMasInstance: MAS initSocket()
08-11 12:28:13.886  7000  7677 D BluetoothMapMasInstance:   masId = 00
08-11 12:28:13.886  7000  7677 D BluetoothMapMasInstance:   msgTypes = 0e
08-11 12:28:13.886  7000  7677 D BluetoothMapMasInstance:   masName = SMS/MMS
08-11 12:28:13.886  7000  7677 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-11 12:28:13.887  1035  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:13.887  6861  6861 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-11 12:28:13.889  7000  7603 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:13.889  7000  7603 W bt-smp  : Plain text(LSB ~ MSB) = c8 a2 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:13.889  7000  7603 W bt-smp  : Encrypted text(LSB ~ MSB) = 99 e9 19 bb 3f d9 79 e0 f0 52 1f e1 65 4e 11 ac 
08-11 12:28:13.890  7000  7603 W bt-btm  : Stopping oneshot timer
08-11 12:28:13.894  7644  7644 I UEI.SmartControl: --- Selecting new region: 6
08-11 12:28:13.894  1035  1109 D BluetoothManagerService: Message: 30
08-11 12:28:13.895  7644  7644 I UEI.SmartControl: Model = LG-D855
08-11 12:28:13.896  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:13.896  7000  7000 V BluetoothPbapService: Pbap Service onCreate
08-11 12:28:13.896  7644  7644 D UEI.SmartControl: QS Service created
08-11 12:28:13.896  7000  7000 V BluetoothPbapService: Starting PBAP service
08-11 12:28:13.897  7000  7677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:13.897  7000  7000 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-11 12:28:13.898  7000  7000 V BluetoothPbapService: Pbap Service onBind
08-11 12:28:13.900  7000  7000 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:13.900  7000  7000 V BluetoothPbapService: state: 12
08-11 12:28:13.900  7000  7000 V BluetoothPbapService: Handler(): got msg=1
08-11 12:28:13.901  7000  7677 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-11 12:28:13.901  7000  7677 V BluetoothMapMasInstance: Succeed to create listening socket 
08-11 12:28:13.901  7000  7677 D BluetoothMapMasInstance: Accepting socket connection...
08-11 12:28:13.901  7000  7549 D BluetoothAdapterProperties: Scan Mode:21
08-11 12:28:13.902  7000  7000 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-11 12:28:13.902  7000  7549 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-11 12:28:13.903  7000  7678 V BluetoothPbapService: Pbap Service initSocket
08-11 12:28:13.903  1035  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:13.903  6861  6861 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-11 12:28:13.904  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:13.904  7000  7678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:13.906  6861  6861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 12:28:13.909  7000  7678 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-11 12:28:13.909  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:13.909  7000  7678 V BluetoothPbapService: Succeed to create listening socket 
08-11 12:28:13.909  7000  7678 V BluetoothPbapService: Accepting socket connection...
,08-11 12:28:13.910  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:13.912  6861  6861 D BluetoothA2dp: Proxy object connected
08-11 12:28:13.913  6861  6861 D A2dpProfile: Bluetooth service connected
08-11 12:28:13.913  7000  7000 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 12:28:13.913  7000  7000 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:13.913  7000  7000 V BluetoothPbapReceiver: ***********state = 12
08-11 12:28:13.916  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:28:13.916  2214  2214 D c       : Getting all permits...
08-11 12:28:13.916  2214  2214 D a       : Opening database...
08-11 12:28:13.916  6861  6861 D BluetoothHeadset: Proxy object connected
08-11 12:28:13.917  6861  6861 D HeadsetProfile: Bluetooth service connected
08-11 12:28:13.918  2214  2214 D a       : Opening database auth.proximity.permit_store...
08-11 12:28:13.918  2214  2214 D a       : Closing database...
08-11 12:28:13.923  6861  6861 D BluetoothPbap: Proxy object connected
,08-11 12:28:13.923  7644  7644 I UEI.SmartControl: Service initServices...
,08-11 12:28:13.924  6861  6861 D PbapServerProfile: Bluetooth service connected
08-11 12:28:13.928  6861  6861 D DockEventReceiver: finishStartingService: stopping service
08-11 12:28:13.930  7644  7644 D UEI.SmartControl: QS start get config
08-11 12:28:13.934  6861  6861 D BluetoothPermissionRequest: onReceive
,08-11 12:28:13.935  6861  6861 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-11 12:28:13.938  6861  6861 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 12:28:13.941  7000  7000 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-11 12:28:13.942  7000  7000 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-11 12:28:13.948  7000  7000 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-11 12:28:13.968  7000  7000 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-11 12:28:13.968  7000  7000 V BtOppService: onCreate
,08-11 12:28:13.983  7644  7644 D UEI.SmartControl: Loading JNI Libs...
,08-11 12:28:14.089  1035  1959 I art     : Explicit concurrent mark sweep GC freed 125460(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.592ms total 118.183ms
,08-11 12:28:14.090  7000  7000 V BluetoothOppNotification: send message
,08-11 12:28:14.094  7000  7000 V BtOppService: Starting RfcommListener
08-11 12:28:14.097  7000  7684 V BtOppService: Deleted complete outbound shares, number =  0
08-11 12:28:14.098  7000  7684 V BtOppService: Deleted complete inbound failed shares, number = 0
08-11 12:28:14.099  7000  7684 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-11 12:28:14.099  7000  7684 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d411e88 on behalf of 
08-11 12:28:14.100  7000  7000 D BluetoothOppPreference: Dumping Names:  
08-11 12:28:14.100  7000  7000 D BluetoothOppPreference: {}
08-11 12:28:14.100  7000  7000 D BluetoothOppPreference: Dumping Channels:  
08-11 12:28:14.100  7000  7000 D BluetoothOppPreference: {}
08-11 12:28:14.101  7000  7000 V BtOppService: onStartCommand
08-11 12:28:14.102  7000  7687 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 12:28:14.102  7000  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 12:28:14.103  7000  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31ff6c46 on behalf of 
08-11 12:28:14.103  7000  7687 V BluetoothOppNotification: update too frequent, put in queue
08-11 12:28:14.104  7000  7687 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 12:28:14.104  7000  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 12:28:14.105  7000  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20e29e07 on behalf of 
08-11 12:28:14.105  7000  7687 V BluetoothOppNotification: update too frequent, put in queue
08-11 12:28:14.105  7000  7687 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-11 12:28:14.106  7000  7000 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:14.106  7000  7000 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-11 12:28:14.109  7000  7000 V BluetoothOppNotification: new notify threadi!
08-11 12:28:14.110  7000  7000 V BluetoothOppNotification: send delay message
08-11 12:28:14.112  7000  7000 V BtOppService: start RfcommListener
08-11 12:28:14.113  7000  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-11 12:28:14.114  7000  7000 V BtOppService: RfcommListener started
08-11 12:28:14.115  7000  7000 V BtOppService: ContentObserver received notification
08-11 12:28:14.115  7000  7689 V BtOppRfcommListener: Starting RFCOMM listener....
08-11 12:28:14.115  1035  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:14.115  7000  7000 V BtOppService: ContentObserver received notification
08-11 12:28:14.116  7000  7689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:14.116  7000  7690 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 12:28:14.116  7000  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 12:28:14.116  7000  7689 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-11 12:28:14.117  7000  7689 V BtOppRfcommListener: Started RFCOMM listener....
08-11 12:28:14.117  7000  7689 I BtOppRfcommListener: Accept thread started.
08-11 12:28:14.117  7000  7689 V BtOppRfcommListener: Accepting connection...
08-11 12:28:14.117  7000  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d0d9b34 on behalf of 
08-11 12:28:14.118  7000  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@324d1d5d on behalf of 
08-11 12:28:14.118  7000  7690 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-11 12:28:14.119  7000  7688 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-11 12:28:14.120  7000  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-11 12:28:14.120  7000  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cb606d2 on behalf of 
08-11 12:28:14.121  7000  7688 V BluetoothOppNotification: outbound: succ-0  fail-0
08-11 12:28:14.127  7000  7688 V BluetoothOppNotification: outbound notification was removed.
08-11 12:28:14.127  7000  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-11 12:28:14.128  7000  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@280113a3 on behalf of 
08-11 12:28:14.128  7000  7688 V BluetoothOppNotification: inbound: succ-0  fail-0
08-11 12:28:14.129  7000  7688 V BluetoothOppNotification: inbound notification was removed.
08-11 12:28:14.129  7000  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-11 12:28:14.130  7000  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f8336a0 on behalf of 
08-11 12:28:14.133  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:14.133  7000  7000 V BluetoothFtpService: Ftp Service onCreate
08-11 12:28:14.133  7000  7000 I BluetoothFtpService: Ftp Service onCreate
08-11 12:28:14.134  7000  7000 V BluetoothFtpService: Ftp Service onStartCommand
08-11 12:28:14.134  7000  7000 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:14.134  7000  7000 V BluetoothFtpService: Starting Listening on sockets
08-11 12:28:14.134  7000  7000 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 12:28:14.134  7000  7000 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 12:28:14.134  7000  7000 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 12:28:14.134  7000  7000 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:14.134  7000  7000 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-11 12:28:14.134  7000  7000 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-11 12:28:14.136  7000  7000 V BluetoothFtpService: Handler(): got msg=1
,08-11 12:28:14.136  7000  7000 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-11 12:28:14.136  7000  7000 V BluetoothFtpService: Ftp Service initSocket
08-11 12:28:14.140  1035  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:14.141  7000  7000 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:14.141  7000  7000 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-11 12:28:14.142  7000  7000 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-11 12:28:14.143  7000  7691 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-11 12:28:14.157  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
,08-11 12:28:14.157  7000  7000 V BluetoothSapService: Sap Service onCreate
08-11 12:28:14.159  7000  7000 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-11 12:28:14.159  7000  7000 V BluetoothSapService: state: 12
08-11 12:28:14.160  7000  7000 V BluetoothSapService: Starting SAP server process
08-11 12:28:14.161  7000  7000 V BluetoothSapService: SAP Service startRfcommListenerThread
08-11 12:28:14.162  7000  7693 V BluetoothSapService: Sap Service initRfcommSocket
08-11 12:28:14.153  7692  7692 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:14.153  7692  7692 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:14.163  1035  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:14.164  7000  7693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:14.164  7000  7693 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-11 12:28:14.164  7000  7693 V BluetoothSapService: Succeed to create listening socket 
08-11 12:28:14.164  7000  7693 V BluetoothSapService: Accepting socket connection...
08-11 12:28:14.171  7692  7692 V BT_SAP  : Event pipe created
08-11 12:28:14.171  7692  7692 V BT_SAP  : create_server_socket qcom.sap.server
08-11 12:28:14.171  7692  7692 V BT_SAP  : created socket fd 6
,08-11 12:28:14.262  7644  7644 I UEI.SmartControl: Supports setup maps: true
,08-11 12:28:14.266  7644  7644 D UEI.SmartControl: QS start statue = true Error code = 0
08-11 12:28:14.266  7644  7644 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-11 12:28:14.266  7644  7644 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-11 12:28:14.266  7644  7644 I UEI.SmartControl: ### init IR Blaster...
08-11 12:28:14.272  7644  7644 D serial_port: Configuring serial port
08-11 12:28:14.275  7644  7644 E UEI.SmartControl: UEIBLaster setting for 616
08-11 12:28:14.275  7644  7644 I UEI.SmartControl: Setting serial record hearder size = 2
08-11 12:28:14.276  7644  7644 I UEI.SmartControl: configuring settings for MAXQ616
,08-11 12:28:14.276  7644  7644 I UEI.SmartControl: Get version...
08-11 12:28:14.293  7644  7694 D UEI.SmartControl: serial port data available: 21
,08-11 12:28:14.321  7644  7644 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-11 12:28:14.321  7644  7644 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-11 12:28:14.322  7644  7644 I UEI.SmartControl: QS saving settings...
,08-11 12:28:14.323  7644  7644 D UEI.SmartControl: IR Blaster version: 25672567
,08-11 12:28:14.340  7644  7694 D UEI.SmartControl: serial port data available: 4
,08-11 12:28:14.380  7644  7697 I UEI.SmartControl: Device manager: loading config....
,08-11 12:28:14.381  7644  7697 D UEI.SmartControl: ----------- loading internal config...
,08-11 12:28:14.386  7644  7644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-11 12:28:14.390  7644  7644 E UEI.SmartControl: Services init done
08-11 12:28:14.390  7644  7644 D UEI.SmartControl: QS Service init finished
08-11 12:28:14.392  7644  7644 D UEI.SmartControl: QS Service version name: 2.1.91
08-11 12:28:14.392  7644  7644 D UEI.SmartControl: QS Service version code: 201091
08-11 12:28:14.393  7644  7644 D UEI.SmartControl: Service requested: Control
08-11 12:28:14.402  7644  7697 E UEI.SmartControl: Loading SETTINGS...
,08-11 12:28:14.405  7644  7644 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-11 12:28:14.410  6929  6929 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-11 12:28:14.410  1035  1051 I ActivityManager: Killing 6929:com.lge.qremote/u0a112 (adj 15): empty #17
08-11 12:28:14.411  7644  7659 I UEI.SmartControl: ------ IControl API: 11
08-11 12:28:14.412  7644  7659 I UEI.SmartControl: Registering callback...
08-11 12:28:14.416  7644  7697 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-11 12:28:14.436  7644  7696 I UEI.SmartControl: Notify AllClients services are ready: 0
08-11 12:28:14.436  7644  7696 D UEI.SmartControl: -----service ready thread exits
,08-11 12:28:14.466  1035  1906 W libprocessgroup: failed to open /acct/uid_10112/pid_6929/cgroup.procs: No such file or directory
08-11 12:28:14.466  7644  7644 D UEI.SmartControl: Internal service binding...
,08-11 12:28:14.612  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-11 12:28:14.641  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-11 12:28:14.661  1035  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7705 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-11 12:28:14.672  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-11 12:28:14.673  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-11 12:28:14.692  1035  1035 D administrator: Handling package changes for user 0
,08-11 12:28:14.722  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:28:14.728  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 12:28:14.754  7705  7705 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-11 12:28:14.800  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-11 12:28:14.800  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-11 12:28:14.850  7705  7705 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:28:14.850  7705  7705 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:14.872  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 12:28:14.879  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 12:28:14.886  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 12:28:14.891  2476  2476 V GmsNetworkLocationProvi: DISABLE
,08-11 12:28:14.923  1035  1091 D LocationProviderProxy: applying state to connected service
,08-11 12:28:14.926  2476  2476 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-11 12:28:14.972  7705  7744 I Babel   : MmsConfig: mnc/mcc: 0/0
08-11 12:28:14.973  7705  7744 I Babel   : MmsConfig.loadMmsSettings
08-11 12:28:14.975  7705  7744 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-11 12:28:14.975  7705  7744 I Babel   : MmsConfig.loadFromDatabase
,08-11 12:28:15.004  7705  7744 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-11 12:28:15.004  7705  7744 I Babel   : MmsConfig.loadFromResources
08-11 12:28:15.006  7705  7744 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-11 12:28:15.007  7705  7744 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-11 12:28:15.033  7705  7705 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:15.047  7705  7743 W AudioCapabilities: Unsupported mime audio/evrc
,08-11 12:28:15.051  7705  7743 W AudioCapabilities: Unsupported mime audio/qcelp
08-11 12:28:15.055  7705  7743 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-11 12:28:15.077  1817  7747 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-11 12:28:15.077  1817  7747 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-11 12:28:15.082  7705  7743 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-11 12:28:15.083  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
,08-11 12:28:15.090  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2bb2835e
08-11 12:28:15.090  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-11 12:28:15.090  7061  7061 D AppUp4:CustFacade: isPhone : true
08-11 12:28:15.090  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-11 12:28:15.090  7061  7061 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-11 12:28:15.095  1817  4777 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-11 12:28:15.096  7705  7743 W AudioCapabilities: Unsupported mime audio/qcelp
,08-11 12:28:15.112  7000  7000 V BluetoothOppNotification: new notify threadi!
08-11 12:28:15.112  7000  7000 V BluetoothOppNotification: send delay message
08-11 12:28:15.118  7705  7743 W AudioCapabilities: Unsupported mime audio/evrc
,08-11 12:28:15.127  7000  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-11 12:28:15.128  7000  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1eb9b15 on behalf of 
08-11 12:28:15.129  7000  7750 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-11 12:28:15.132  7000  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-11 12:28:15.135  7000  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21cf9e2a on behalf of 
08-11 12:28:15.138  1035  1577 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7751 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-11 12:28:15.141  7000  7750 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-11 12:28:15.142  1035  1924 I ActivityManager: Killing 6900:com.lge.sync/1000 (adj 15): empty #17
08-11 12:28:15.144  7705  7743 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-11 12:28:15.145  7000  7750 V BluetoothOppNotification: outbound notification was removed.
08-11 12:28:15.145  7000  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-11 12:28:15.146  7000  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2613541b on behalf of 
08-11 12:28:15.147  7000  7750 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-11 12:28:15.151  7000  7750 V BluetoothOppNotification: inbound notification was removed.
08-11 12:28:15.158  7705  7743 W VideoCapabilities: Unsupported mime video/divx
08-11 12:28:15.159  7000  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-11 12:28:15.160  7000  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bd39b8 on behalf of 
08-11 12:28:15.167  7705  7743 W VideoCapabilities: Unsupported mime video/divx311
08-11 12:28:15.169  7705  7743 W VideoCapabilities: Unsupported mime video/divx4
08-11 12:28:15.173  7705  7743 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-11 12:28:15.186  7705  7743 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-11 12:28:15.190  7705  7743 W AudioCapabilities: Unsupported mime audio/eac3
08-11 12:28:15.190  7705  7743 W AudioCapabilities: Unsupported mime audio/ac3
08-11 12:28:15.191  7705  7743 W AudioCapabilities: Unsupported mime audio/g726
,08-11 12:28:15.192  7705  7743 W AudioCapabilities: Unsupported mime audio/wma-voice
08-11 12:28:15.192  7705  7743 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-11 12:28:15.193  7705  7743 W AudioCapabilities: Unsupported mime audio/adpcm
08-11 12:28:15.195  7705  7743 W VideoCapabilities: Unsupported mime video/theora
08-11 12:28:15.196  7705  7743 W VideoCapabilities: Unsupported mime video/mjpg
08-11 12:28:15.207  1035  1978 W libprocessgroup: failed to open /acct/uid_1000/pid_6900/cgroup.procs: No such file or directory
,08-11 12:28:15.229  7751  7751 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:15.230  7751  7751 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:28:15.230  7751  7751 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 12:28:15.231  7751  7751 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-11 12:28:15.231  7751  7751 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-11 12:28:15.282  7751  7751 I SystemConfig: BUILD Country: EU
08-11 12:28:15.282  7751  7751 I SystemConfig: BUILD Operator: OPEN
,08-11 12:28:15.318  1035  1906 I ActivityManager: Killing 7088:com.lge.email/u0a23 (adj 15): empty #17
,08-11 12:28:15.459  1035  1996 W libprocessgroup: failed to open /acct/uid_10023/pid_7088/cgroup.procs: No such file or directory
,08-11 12:28:15.472  7751  7769 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-11 12:28:15.473  7751  7769 I SystemConfig: existFile = false
08-11 12:28:15.473  7751  7769 I SystemConfig: canReadFile = false
08-11 12:28:15.473  7751  7769 I SystemConfig: systemFeature RCS result false
08-11 12:28:15.473  7751  7769 D SystemConfig: refreshRcsSupport() :false
,08-11 12:28:15.501  1035  1906 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7774 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-11 12:28:15.567  7774  7774 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:15.567  7774  7774 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-11 12:28:15.567  7774  7774 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 12:28:15.568  7774  7774 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-11 12:28:15.654  7774  7774 I AppConfig: Total System Memory = 2995761152
,08-11 12:28:15.662  7774  7774 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-11 12:28:15.762  1035  2033 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7793 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-11 12:28:15.763  1035  2033 I ActivityManager: Killing 6970:com.lge.formmanager/u0a26 (adj 15): empty #17
08-11 12:28:15.818  1035  1651 W libprocessgroup: failed to open /acct/uid_10026/pid_6970/cgroup.procs: No such file or directory
,08-11 12:28:16.022  7793  7793 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-11 12:28:16.139  7793  7793 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:28:16.139  7793  7793 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:16.184  7793  7793 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-11 12:28:16.206  7793  7793 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-11 12:28:16.207  7793  7793 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-11 12:28:16.223  7793  7793 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-11 12:28:16.223  7793  7793 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-11 12:28:16.238  1035  1978 I ActivityManager: Killing 6438:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-11 12:28:16.281  1035  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6438/cgroup.procs: No such file or directory
,08-11 12:28:16.282  3526  4512 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-11 12:28:16.287  3526  4512 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@25b99eed on behalf of 7793
08-11 12:28:16.292  4623  7833 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-11 12:28:16.345  1035  1651 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7839 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-11 12:28:16.370   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 24.820ms
,08-11 12:28:16.378  7793  7793 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-11 12:28:16.391   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 20.173ms
,08-11 12:28:16.412   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 19.917ms
,08-11 12:28:16.416  7793  7793 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-11 12:28:16.451  7839  7839 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-11 12:28:16.477  7839  7839 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-11 12:28:16.477  7839  7839 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-11 12:28:16.477  7839  7839 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-11 12:28:16.477  7839  7839 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-11 12:28:16.477  7839  7839 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-11 12:28:16.477  7839  7839 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-11 12:28:16.507  1035  1906 I ActivityManager: Killing 7385:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-11 12:28:16.539  1035  1924 W libprocessgroup: failed to open /acct/uid_10005/pid_7385/cgroup.procs: No such file or directory
,08-11 12:28:16.731  1035  1906 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:28:16.772  4623  7833 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 480 ms] updated apps [took 480 ms] 
,08-11 12:28:17.660  1035  1892 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:28:17.660  1035  1892 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ef353a6 mBinding = false
,08-11 12:28:17.690  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 12:28:17.690  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 12:28:17.690  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-11 12:28:17.694  1035  1109 D BluetoothManagerService: Message: 2
08-11 12:28:17.695  1035  1109 D BluetoothManagerService: Sending off request.
08-11 12:28:17.695  7000  7667 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-11 12:28:17.696  7000  7545 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-11 12:28:17.696  7000  7545 D BluetoothAdapterProperties: Setting state to 13
08-11 12:28:17.696  7000  7545 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-11 12:28:17.697  7000  7545 D BluetoothAdapterProperties: onBluetoothDisable()
08-11 12:28:17.697  7000  7545 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-11 12:28:17.699  7000  7549 D BluetoothAdapterProperties: Scan Mode:20
08-11 12:28:17.701  7000  7545 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-11 12:28:17.702  7000  7677 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-11 12:28:17.702  7000  7677 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:28:17.702  7000  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-11 12:28:17.702  7000  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-11 12:28:17.702  7000  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-11 12:28:17.702  7000  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-11 12:28:17.702  7000  7677 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-11 12:28:17.702  7000  7677 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-11 12:28:17.706  7000  7678 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:28:17.708  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-11 12:28:17.708  7000  7693 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:28:17.708  7000  7691 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:28:17.709  7000  7689 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:28:17.709  7000  7603 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-11 12:28:17.711  7000  7545 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-11 12:28:17.714  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-11 12:28:17.714  7000  7603 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-11 12:28:17.719  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:17.719  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:17.719  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:17.719  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:17.719  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:17.719  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:17.719  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:17.719  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:17.719  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:28:17.733  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:17.733  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:28:17.740  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:17.740  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:17.740  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:17.740  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:17.740  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:17.740  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:17.740  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:17.740  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:17.740  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:17.742  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:17.742  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:17.745  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:17.745  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:17.745  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:17.745  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:17.745  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:17.745  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:28:17.745  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:17.745  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:17.745  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:28:17.748  6630  6630 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:28:17.749  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:17.749  1035  1109 D BluetoothManagerService: Message: 60
08-11 12:28:17.749  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-11 12:28:17.749  1035  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-11 12:28:17.755  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:17.756  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 12:28:17.757  1035  1458 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-11 12:28:17.770  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:17.774  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:17.775  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:17.776  7000  7000 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:17.777  7000  7000 D BluetoothMapService: STATE_TURNING_OFF
08-11 12:28:17.777  7000  7000 V BluetoothMapService: Handler(): got msg=4
08-11 12:28:17.777  7000  7000 D BluetoothMapService: MAP Service closeService in
08-11 12:28:17.777  7000  7000 D BluetoothMapMasInstance: MAP Service shutdown
08-11 12:28:17.777  7000  7000 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 12:28:17.777  7000  7000 V BluetoothMapService: MAP Service closeService out
08-11 12:28:17.778  7000  7000 V BtOppService: Receiver DISABLED_ACTION 
08-11 12:28:17.778  7000  7000 I BtOppRfcommListener: stopping Accept Thread
08-11 12:28:17.778  7000  7000 V BtOppRfcommListener: close mBtServerSocket
08-11 12:28:17.779  7000  7689 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 12:28:17.779  7000  7000 V BtOppRfcommListener: waiting for thread to terminate
08-11 12:28:17.779  7000  7000 V BtOppRfcommListener: done waiting for thread to terminate
,08-11 12:28:17.791  6861  6861 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-11 12:28:17.794  6861  6861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 12:28:17.797  7000  7000 V BtOppService: onDestroy
08-11 12:28:17.799  7000  7000 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-11 12:28:17.803  7000  7000 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 12:28:17.803  7000  7000 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:17.803  7000  7000 V BluetoothPbapReceiver: ***********state = 13
08-11 12:28:17.806  7000  7000 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-11 12:28:17.808  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:28:17.811  7000  7000 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:17.811  7000  7000 V BluetoothPbapService: state: 13
08-11 12:28:17.811  7000  7000 V BluetoothPbapService: Pbap Service closeService in
,08-11 12:28:17.816  7000  7000 V BluetoothPbapService: successfully stopped pbap service
08-11 12:28:17.816  7000  7000 V BluetoothPbapService: Pbap Service closeService out
,08-11 12:28:17.821  7000  7000 V BluetoothPbapService: Pbap Service onDestroy
08-11 12:28:17.821  7000  7000 V BluetoothPbapService: Pbap Service closeService in
08-11 12:28:17.821  7000  7000 V BluetoothPbapService: Pbap Service closeService out
08-11 12:28:17.822  7000  7000 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-11 12:28:17.834  6861  6861 D DockEventReceiver: finishStartingService: stopping service
,08-11 12:28:17.836  6861  6861 D BluetoothPbap: Proxy object disconnected
08-11 12:28:17.836  6861  6861 D PbapServerProfile: Bluetooth service disconnected
08-11 12:28:17.842  6861  6861 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-11 12:28:17.847  6861  6861 D BluetoothPermissionRequest: onReceive
08-11 12:28:17.847  6861  6861 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-11 12:28:17.858  6861  6861 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 12:28:17.861  7000  7000 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-11 12:28:17.861  7000  7000 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-11 12:28:17.862  7000  7000 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-11 12:28:17.868  7000  7000 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:17.868  7000  7000 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-11 12:28:17.869  7000  7000 V BluetoothFtpService: Ftp Service onStartCommand
08-11 12:28:17.869  7000  7000 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:17.869  7000  7000 V BluetoothFtpService: Ftp Service closeService
,08-11 12:28:17.869  7000  7000 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-11 12:28:17.872  7000  7000 V BluetoothFtpService: successfully stopped ftp service
08-11 12:28:17.872  7000  7000 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 12:28:17.872  7000  7000 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 12:28:17.872  7000  7000 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 12:28:17.872  7000  7000 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:17.873  7000  7000 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-11 12:28:17.873  7000  7000 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-11 12:28:17.875  7000  7000 V BluetoothFtpService: Ftp Service onDestroy
,08-11 12:28:17.875  7000  7000 V BluetoothFtpService: Ftp Service closeService
,08-11 12:28:17.879  7000  7000 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-11 12:28:17.879  7000  7000 V BluetoothSapService: state: 13
,08-11 12:28:17.879  7000  7000 V BluetoothSapService: Stopping SAP server process
,08-11 12:28:17.880  7000  7000 V BluetoothSapService: Sap Service closeSapService in
08-11 12:28:17.880  7000  7000 V BluetoothSapService: Close listen Socket : 
08-11 12:28:17.880  7000  7000 V BluetoothSapService: Close rfcomm Socket : 
,08-11 12:28:17.880  7000  7000 V BluetoothSapService: Close sapd  Socket : 
08-11 12:28:17.881  7000  7000 V BluetoothSapService: Sap Service closeSapService out
08-11 12:28:17.881  7000  7000 V BluetoothSapService: Sap Service onDestroy
,08-11 12:28:17.881  7000  7000 V BluetoothSapService: Sap Service closeSapService in
08-11 12:28:17.881  7000  7000 V BluetoothSapService: Close listen Socket : 
08-11 12:28:17.881  7000  7000 V BluetoothSapService: Close rfcomm Socket : 
08-11 12:28:17.882  7000  7000 V BluetoothSapService: Close sapd  Socket : 
,08-11 12:28:17.882  7000  7000 V BluetoothSapService: Sap Service closeSapService out
08-11 12:28:18.643  7000  7549 D bt_hci_bdroid: cleanup
,08-11 12:28:18.660  7000  7605 I bt_lpm  : LPM is already off!!!
08-11 12:28:18.661  7000  7661 I bt_userial_mct: exiting userial_read_thread
08-11 12:28:18.661  7000  7661 D bt_userial_mct: Leaving userial_evt_read_thread()
08-11 12:28:18.661  7000  7603 W bt-btif : ag scb idx 1 not allocated
08-11 12:28:18.661  7000  7603 E bt-btif : BTA AG is already disabled, ignoring ...
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:28:18.661  7000  7603 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-11 12:28:18.662  7000  7603 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-11 12:28:18.662  7000  7603 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-11 12:28:18.664  7000  7549 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-11 12:28:18.664  7000  7605 I bt_vendor: hw_epilog_process
08-11 12:28:18.666  7000  7549 D bt_hci_bdroid: cleanup Finalizing cleanup
08-11 12:28:18.666  7000  7549 D bt_userial_mct: userial_close
08-11 12:28:18.666  7000  7549 E bt_userial_mct: pthread_join() FAILED result:3
,08-11 12:28:18.666  7000  7549 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-11 12:28:18.697  7000  7549 D bt_hci_bdroid: set_power 0
08-11 12:28:18.697  7000  7549 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-11 12:28:18.697  7000  7549 I bt_vendor: bluetooth satus is on
08-11 12:28:18.698  7000  7549 I bt_vendor: bt-vendor : resetting BT status,
08-11 12:28:18.698  7000  7549 I bt_vendor: Starting hciattach daemon
08-11 12:28:18.698  7000  7549 I bt_vendor: try to set false
,08-11 12:28:18.708  7000  7549 I bt_vendor: Starting hciattach daemon
08-11 12:28:18.708  7000  7549 I bt_vendor: try to set false
08-11 12:28:18.709  7000  7549 I bt_vendor: cleanup
08-11 12:28:18.710  7000  7603 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-11 12:28:18.710  7000  7549 I GKI_LINUX: GKI_exit_task 0 done
08-11 12:28:18.710  7000  7549 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-11 12:28:18.712  7000  7545 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-11 12:28:18.715  7000  7000 D HeadsetService: Received stop request...Stopping profile...
,08-11 12:28:18.719  7000  7000 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-11 12:28:18.719  7000  7000 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 12:28:18.719  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:18.720  7000  7583 D HeadsetStateMachine: Exit Disconnected: -1
08-11 12:28:18.723  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-11 12:28:18.723  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-11 12:28:18.723  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-11 12:28:18.724  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-11 12:28:18.724  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-11 12:28:18.725  7000  7000 D A2dpService: Received stop request...Stopping profile...
08-11 12:28:18.726  7000  7592 D A2dpStateMachine: Exit Disconnected: -1
08-11 12:28:18.729  7000  7000 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-11 12:28:18.736  7000  7545 D BluetoothAdapterState: Stopping profile services that were post enabled
08-11 12:28:18.737  7000  7000 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-11 12:28:18.737  7000  7000 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 12:28:18.737  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:18.738  7000  7000 D HeadsetStateMachine: Unbinding service...
08-11 12:28:18.739  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-11 12:28:18.740  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-11 12:28:18.742  7000  7000 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 12:28:18.742  7000  7000 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 12:28:18.742  7000  7000 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 12:28:18.742  7000  7000 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 12:28:18.742  7000  7000 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 12:28:18.742  7000  7000 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 12:28:18.742  7000  7000 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-11 12:28:18.746  7000  7000 D HidService: Received stop request...Stopping profile...
08-11 12:28:18.746  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:18.749  7000  7000 D HealthService: Received stop request...Stopping profile...
08-11 12:28:18.749  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:18.751  7000  7000 D PanService: Received stop request...Stopping profile...
08-11 12:28:18.751  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:18.752  7000  7000 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 12:28:18.753  7000  7000 D BtGatt.GattService: Received stop request...Stopping profile...
08-11 12:28:18.753  7000  7000 D BtGatt.GattService: stop()
08-11 12:28:18.753  7000  7000 D BtGatt.AdvertiseManager: advertise clients cleared
08-11 12:28:18.754  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
,08-11 12:28:18.759  7000  7000 D BluetoothMapService: Received stop request...Stopping profile...
08-11 12:28:18.759  7000  7000 D BluetoothMapService: stop()
08-11 12:28:18.761  7000  7000 D BluetoothMapEmailAppObserver: deinitObservers()
08-11 12:28:18.761  7000  7000 D BluetoothMapEmailAppObserver: removeReceiver()
08-11 12:28:18.762  7000  7000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:18.763  7000  7000 I BluetoothA2dpServiceJni: cleanupNative
08-11 12:28:18.763  7000  7593 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-11 12:28:18.763  7000  7000 I GKI_LINUX: GKI_exit_task 2 done
08-11 12:28:18.763  7000  7000 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-11 12:28:18.764  7000  7000 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 12:28:18.764  7000  7000 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 12:28:18.764  7000  7000 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-11 12:28:18.764  7000  7000 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 12:28:18.764  7000  7000 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 12:28:18.765  7000  7000 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 12:28:18.765  7000  7000 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 12:28:18.767  7000  7000 V BluetoothMapService: Handler(): got msg=4
08-11 12:28:18.767  7000  7000 D BluetoothMapService: MAP Service closeService in
08-11 12:28:18.767  7000  7000 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 12:28:18.767  7000  7000 V BluetoothMapService: MAP Service closeService out
,08-11 12:28:18.770  7000  7545 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-11 12:28:18.770  7000  7545 D BluetoothAdapterProperties: Setting state to 10
08-11 12:28:18.771  7000  7545 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-11 12:28:18.772  7000  7000 D BluetoothMapService: cleanup()
08-11 12:28:18.772  7000  7000 D BluetoothMapService: MAP Service closeService in
08-11 12:28:18.772  7000  7000 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-11 12:28:18.772  7000  7000 V BluetoothMapService: MAP Service closeService out
08-11 12:28:18.773  1035  1109 D BluetoothManagerService: Message: 60
08-11 12:28:18.773  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-11 12:28:18.773  1035  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-11 12:28:18.774  7000  7545 I BluetoothAdapterState: Entering OffState
08-11 12:28:18.774  6861  6880 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 12:28:18.775  1853  2459 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:28:18.775  6861  6880 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 12:28:18.776  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:28:18.777  1035  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:28:18.777  6861  6880 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:28:18.778  1853  3990 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:28:18.778  6861  6880 D BluetoothPan: onBluetoothStateChange on: false
08-11 12:28:18.779  1035  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 12:28:18.779  6861  6880 D BluetoothMap: onBluetoothStateChange: up=false
08-11 12:28:18.779  6861  6880 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-11 12:28:18.783  1035  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-11 12:28:18.783  1035  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-11 12:28:18.787  1035  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-11 12:28:18.787  1035  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-11 12:28:18.787  1035  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ef353a6 mBinding = false
08-11 12:28:18.787  1035  1109 D BluetoothManagerService: Sending unbind request.
08-11 12:28:18.792  7000  7549 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-11 12:28:18.794  7000  7000 I GKI_LINUX: GKI_exit_task 1 done
,08-11 12:28:18.794  7000  7000 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-11 12:28:18.795  7000  7000 I BluetoothServiceJni: cleanupNative: return from cleanup,
08-11 12:28:18.795  7000  7000 I art     : --- WEIRD: removing null entry 248
08-11 12:28:18.795  7000  7000 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-11 12:28:18.795  7000  7000 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object,
08-11 12:28:18.798  1035  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-11 12:28:18.805  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-11 12:28:18.811  1942  2095 D LGBluetoothAPIService: Message: 2
08-11 12:28:18.811  1942  2095 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1a7c1865 mBinding = false
08-11 12:28:18.811  7000  7000 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-11 12:28:18.811  1942  2095 D LGBluetoothAPIService: Sending unbind request.
,08-11 12:28:18.815  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 12:28:18.818  7000  7000 I art     : System.exit called, status: 0
08-11 12:28:18.818  7000  7000 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-11 12:28:18.818  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:18.819  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:18.820  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:18.822  6861  6861 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-11 12:28:18.822  6861  6861 D LGBluetoothEventManager: [BTUI] clear device connection state
08-11 12:28:18.823  6861  6861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 12:28:18.829  1604  1604 D BluetoothAdapter: 557810103: getState() :  mService = null. Returning STATE_OFF
08-11 12:28:18.829  1604  1604 D BluetoothAdapter: 557810103: getState() :  mService = null. Returning STATE_OFF
08-11 12:28:18.832  6861  6861 D DockEventReceiver: finishStartingService: stopping service
08-11 12:28:18.837   326   326 V AudioFlinger: 7000 died, releasing its sessions
08-11 12:28:18.837   326   326 V AudioFlinger:  pid 1853 @ 0
08-11 12:28:18.837   326   326 V AudioFlinger:  pid 3477 @ 1
08-11 12:28:18.837   326   326 V AudioFlinger:  pid 3477 @ 2
08-11 12:28:18.837  6861  6861 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-11 12:28:18.897  1035  1577 I ActivityManager: Process com.android.bluetooth (pid 7000) has died
,08-11 12:28:18.897  1035  1577 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-11 12:28:18.906  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:28:18.929  6861  6861 D BluetoothPermissionRequest: onReceive
,08-11 12:28:18.934  6861  6861 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-11 12:28:18.934  6861  6861 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-11 12:28:18.939  6861  6861 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 12:28:19.023  1035  1996 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7924 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-11 12:28:19.117  7924  7924 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-11 12:28:19.118  7924  7924 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 12:28:19.118  7924  7924 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-11 12:28:19.119  7924  7924 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-11 12:28:19.139  7924  7924 D BluetoothAdapterApp: Loading JNI Library
,08-11 12:28:19.199  7924  7924 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@28be5a74 Instance Count = 1
,08-11 12:28:19.208  7924  7924 D BluetoothAdapterApp: onCreate
08-11 12:28:19.243  7924  7924 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-11 12:28:19.243  7924  7924 D ProfileConfigQcom: Adding HeadsetService
08-11 12:28:19.243  7924  7924 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-11 12:28:19.243  7924  7924 D ProfileConfigQcom: Adding A2dpService
08-11 12:28:19.244  7924  7924 D ProfileConfigQcom: [BTUI] HidService is supported
08-11 12:28:19.244  7924  7924 D ProfileConfigQcom: Adding HidService
08-11 12:28:19.244  7924  7924 D ProfileConfigQcom: [BTUI] HealthService is supported
08-11 12:28:19.244  7924  7924 D ProfileConfigQcom: Adding HealthService
08-11 12:28:19.246  7924  7924 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-11 12:28:19.248  7924  7924 D ProfileConfigQcom: [BTUI] PanService is supported
08-11 12:28:19.248  7924  7924 D ProfileConfigQcom: Adding PanService
08-11 12:28:19.249  7924  7924 D ProfileConfigQcom: [BTUI] GattService is supported
08-11 12:28:19.249  7924  7924 D ProfileConfigQcom: Adding GattService
,08-11 12:28:19.249  7924  7924 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-11 12:28:19.249  7924  7924 D ProfileConfigQcom: Adding BluetoothMapService
08-11 12:28:19.250  7924  7924 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-11 12:28:19.252  7924  7924 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-11 12:28:19.260  6861  6861 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-11 12:28:19.261  7924  7924 V LGMDMManagerInternal: Create singleton instance
08-11 12:28:19.353  7924  7924 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-11 12:28:19.359  7924  7924 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 12:28:19.360  7924  7924 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 12:28:19.360  7924  7924 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 12:28:19.361  7924  7924 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:19.362  7924  7924 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-11 12:28:19.374  7610  7610 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-11 12:28:19.381  1035  1892 I ActivityManager: Killing 7117:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-11 12:28:19.382  7644  7698 D UEI.SmartControl: Internal timer expired: 1
08-11 12:28:19.382  7644  7698 D UEI.SmartControl: unbind internal service
08-11 12:28:19.410  1035  1906 W libprocessgroup: failed to open /acct/uid_10046/pid_7117/cgroup.procs: No such file or directory
,08-11 12:28:19.414  7644  7644 D UEI.SmartControl: Service.onUnbind: IControl
08-11 12:28:19.414  7644  7644 D UEI.SmartControl: Service.onDestroy
08-11 12:28:19.415  7644  7644 D UEI.SmartControl: Lock is in USE false
08-11 12:28:19.415  7644  7644 D UEI.SmartControl: unbind internal service
08-11 12:28:19.415  7644  7644 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@49f776a
08-11 12:28:19.416  7644  7644 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-11 12:28:19.416  7644  7644 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-11 12:28:19.416  7644  7644 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-11 12:28:19.416  7644  7644 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-11 12:28:19.416  7644  7644 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-11 12:28:19.416  7644  7644 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-11 12:28:19.416  7644  7644 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-11 12:28:19.416  7644  7644 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-11 12:28:19.416  7644  7644 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:28:19.416  7644  7644 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:28:19.416  7644  7644 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:28:19.417  7644  7644 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:28:19.417  7644  7644 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:28:19.417  7644  7644 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:28:19.417  7644  7644 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 12:28:19.417  7644  7644 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@49f776a
08-11 12:28:19.417  7644  7644 D serial_port: close(fd = 25)
08-11 12:28:19.421  7644  7644 I UEI.SmartControl: Serial port is closed.
08-11 12:28:19.422  7644  7644 I UEI.SmartControl: Serial port is closed.
08-11 12:28:19.422  7644  7644 D UEI.SmartControl: Blaster closed
08-11 12:28:19.422  7644  7644 D UEI.SmartControl: Shut down QS...
08-11 12:28:19.422  7644  7644 D UEI.SmartControl: Stopping QS lib
08-11 12:28:19.423  7644  7644 D UEI.SmartControl: QS lib stop result = true
08-11 12:28:19.423  7644  7644 D UEI.SmartControl: Stopped QS lib
08-11 12:28:19.423  7644  7644 D UEI.SmartControl: Stopped file observer...
08-11 12:28:19.424  7644  7644 D UEI.SmartControl: QS shutdown complete
,08-11 12:28:19.486  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2a923583 type 2 when 173402 com.google.android.gms} when 173402
,08-11 12:28:19.500   322  7951 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-11 12:28:19.501  1035  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-11 12:28:22.776  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:28:22.776  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:28:27.789  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:28:27.789  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b8f32e removed from the list
08-11 12:28:27.789  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:28:27.789  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:27.789  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:28:27.792  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:28:27.792  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1d805c added. We now have 4 listener(s)
08-11 12:28:27.792  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:28:27.802  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:27.802  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1d805c removed from the list
08-11 12:28:27.803  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:28:27.803  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:27.803  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:27.803  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:28:27.803  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ed3df65 added. We now have 4 listener(s)
08-11 12:28:27.804  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:28:27.804  6630  6760 I System.out: IsBluetoothEnabled
08-11 12:28:27.805  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:27.805  1035  1051 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-11 12:28:27.806  1035  1109 D BluetoothManagerService: Message: 2
08-11 12:28:27.809  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:27.809  1035  1892 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:27.809  1035  1892 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-11 12:28:27.825  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-11 12:28:27.825  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 12:28:27.825  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-11 12:28:27.829  1035  1109 D BluetoothManagerService: Message: 1
08-11 12:28:27.829  1035  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-11 12:28:27.859  1035  1109 D BluetoothManagerService: Message: 20
08-11 12:28:27.859  1035  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39f12f2c:true
,08-11 12:28:27.863  7924  7924 D BluetoothAdapterState: make
08-11 12:28:27.867  7924  7924 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-11 12:28:27.868  7924  7924 I bluedroid-qcom: init
08-11 12:28:27.869  7924  7958 I BluetoothAdapterState: Entering OffState
08-11 12:28:27.869  7924  7924 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-11 12:28:27.870  7924  7924 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-11 12:28:27.870  7924  7924 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 12:28:27.870  7924  7924 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 12:28:27.870  7924  7924 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-11 12:28:27.872  7924  7924 I bluedroid-qcom: get_profile_interface socket
08-11 12:28:27.872  7924  7924 I bluedroid-qcom: get_profile_interface map_client
,08-11 12:28:27.877  7924  7962 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-11 12:28:27.879  7924  7962 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-11 12:28:27.873  7961  7961 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:27.873  7961  7961 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:27.890  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-11 12:28:27.890  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-11 12:28:27.895  7961  7961 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-11 12:28:27.895  7961  7961 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-11 12:28:27.895  7961  7961 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-11 12:28:27.897  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-11 12:28:27.897  1035  1109 D BluetoothManagerService: Message: 40
08-11 12:28:27.897  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-11 12:28:27.898  7924  7940 I bluedroid-qcom: config_hci_snoop_log
08-11 12:28:27.899  7961  7961 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-11 12:28:27.901  1035  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-11 12:28:27.901  1035  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-11 12:28:27.902  7924  7962 D BluetoothAdapterProperties: Name is: G3
,08-11 12:28:27.906  7961  7961 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-11 12:28:27.906  7961  7961 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-11 12:28:27.912  7924  7958 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-11 12:28:27.912  7924  7958 D BluetoothAdapterProperties: Setting state to 11
08-11 12:28:27.913  7924  7958 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-11 12:28:27.913  1035  1109 D BluetoothManagerService: Message: 60
08-11 12:28:27.913  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-11 12:28:27.913  1035  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-11 12:28:27.917  7924  7958 I LGBluetoothServiceJni: classInitNative: succeeds
08-11 12:28:27.925  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:27.925  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 12:28:27.929  6861  6861 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-11 12:28:27.932  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:27.934  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:27.944  7924  7958 D BluetoothBondStateMachine: make
,08-11 12:28:27.946  7924  7924 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 12:28:27.947  7924  7958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:27.947  7924  7958 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-11 12:28:27.947  7924  7958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:27.947  7924  7958 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-11 12:28:27.947  7924  7924 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:27.947  7924  7924 V BluetoothPbapReceiver: ***********state = 11
08-11 12:28:27.948  7924  7958 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-11 12:28:27.949  7924  7975 I BluetoothBondStateMachine: StableState(): Entering Off State
08-11 12:28:27.951  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:28:27.952  7924  7958 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:27.961  7924  7958 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 12:28:27.962  7924  7924 D HeadsetService: Received start request. Starting profile...
08-11 12:28:27.963  7924  7924 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 12:28:27.963  7924  7924 D LGBluetoothHfpAdapter: Version 1.6
08-11 12:28:27.966  7924  7924 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-11 12:28:27.967  7924  7958 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:27.967  7924  7924 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 12:28:27.968  7924  7924 D HeadsetStateMachine: make
08-11 12:28:27.975  6861  6861 D BluetoothPermissionRequest: onReceive
,08-11 12:28:27.979  6861  6861 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 12:28:27.982  7924  7958 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:27.989  7924  7958 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 12:28:27.994  7924  7958 E BluetoothAdapterService: File transfer profiles supported!!
08-11 12:28:28.001  7924  7958 E BluetoothAdapterService: File transfer profiles supported!!
,08-11 12:28:28.009  7924  7924 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:28:28.009  7924  7924 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 12:28:28.015  7924  7924 D HeadsetStateMachine: max_hf_connections = 1
08-11 12:28:28.015  7924  7924 I bluedroid-qcom: get_profile_interface handsfree
08-11 12:28:28.017  7924  7924 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-11 12:28:28.018   326  1398 V AudioPolicyService: registerClient() client 0xb558a3c0, uid 1002
08-11 12:28:28.018   326  2174 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-11 12:28:28.018   326  2174 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 12:28:28.018   326  2174 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 12:28:28.018  7924  7924 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-11 12:28:28.019   326  1397 V AudioFlinger: registerClient() client 0xb14337f0, pid 7924
08-11 12:28:28.020   326  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:28.020   326  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:28.020  7924  7924 V ToneGenerator: Create Track: 0xb4928a80
08-11 12:28:28.020  7924  7924 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-11 12:28:28.020  7924  7924 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-11 12:28:28.020  1035  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:28.020  1035  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:28.020   326  1398 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-11 12:28:28.020   326  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-11 12:28:28.020   326  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 12:28:28.020   326  1398 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 12:28:28.020  3477  3492 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:28.020  3477  3492 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:28.020  7924  7924 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-11 12:28:28.020  7924  7940 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:28.020  7924  7940 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-11 12:28:28.020   326  2173 I AudioFlinger: isAudioPlaybackHookOn() false
08-11 12:28:28.021   326  1398 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-11 12:28:28.021   326  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-11 12:28:28.021   326  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-11 12:28:28.021   326  1398 V AudioPolicyManagerEx: getOutput() returns output 2
08-11 12:28:28.021  1604  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:28.021  1604  2099 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:28.021  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-11 12:28:28.021  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-11 12:28:28.021   326  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:28.021   326  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:28.022  1035  1978 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:28.022  1035  1978 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:28.022  7924  7941 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:28.022  7924  7941 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-11 12:28:28.022  7924  7924 V AudioSystem: getLatency() output 2, latency 50
08-11 12:28:28.022  7924  7924 V AudioSystem: getFrameCount() output 2, frameCount 960
08-11 12:28:28.022  7924  7924 V AudioTrack: createTrack_l() output 2 afLatency 50
08-11 12:28:28.022  1604  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:28.022  1604  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:28.022   326  2173 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-11 12:28:28.022   326  2173 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-11 12:28:28.022  1853  3990 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:28.022  1853  3990 V AudioSystem: ioConfigChanged,() opening already existing output! 2
08-11 12:28:28.023  3477  3493 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-11 12:28:28.023  3477  3493 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-11 12:28:28.023   326  2173 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-11 12:28:28.023   326  2173 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-11 12:28:28.023   326  2173 V AudioFlinger: createTrack() lSessionId: 21
08-11 12:28:28.025  7924  7924 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-11 12:28:28.025   326  2173 V AudioFlinger: acquiring 21 from 7924, for 7924
08-11 12:28:28.025   326  2173 V AudioFlinger:  added new entry for 21
08-11 12:28:28.026  7924  7924 V ToneGenerator: ToneGenerator INIT OK, time: 181959
08-11 12:28:28.026  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:28.027  7924  7978 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-11 12:28:28.027  7924  7978 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-11 12:28:28.027  7924  7978 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-11 12:28:28.027  7924  7978 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-11 12:28:28.028   326  1398 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7924
08-11 12:28:28.028  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:28.032   326  1398 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-11 12:28:28.032   326  1398 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-11 12:28:28.032   326  1398 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-11 12:28:28.032   326  1398 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-11 12:28:28.032   326  1398 V voice   : voice_set_parameters: exit with code(0)
08-11 12:28:28.032   326  1398 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-11 12:28:28.032   326  1398 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-11 12:28:28.032   326  1398 V msm8974_platform: platform_set_parameters: exit with code(0)
08-11 12:28:28.032   326  1398 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-11 12:28:28.032   326  1398 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-11 12:28:28.032   326  1398 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-11 12:28:28.033  7924  7924 D A2dpService: Received start request. Starting profile...
,08-11 12:28:28.033  7924  7978 V ToneGenerator: ToneGenerator destructor
,08-11 12:28:28.033  7924  7978 V ToneGenerator: stopTone
08-11 12:28:28.033  7924  7978 V ToneGenerator: Delete Track: 0xb4928a80
08-11 12:28:28.034  7924  7924 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 12:28:28.035  7924  7924 V Avrcp   : make
08-11 12:28:28.035  7924  7924 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-11 12:28:28.035  7924  7924 I bluedroid-qcom: get_profile_interface avrcp
08-11 12:28:28.036  7924  7958 V LGMDMManager: Create singleton instance
08-11 12:28:28.036  7924  7978 V AudioTrack: ~AudioTrack, releasing session id from 7924 on behalf of 7924
08-11 12:28:28.036   326  1397 V AudioPolicyService: AudioCommandThread() adding release output 2
08-11 12:28:28.036   326  1397 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-11 12:28:28.036   326  1256 V AudioPolicyService: AudioCommandThread() waking up
08-11 12:28:28.036   326  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
,08-11 12:28:28.036   326  1256 V AudioPolicyManager: releaseOutput() 2
08-11 12:28:28.036   326  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-11 12:28:28.037   326  1397 V AudioFlinger: PlaybackThread::Track destructor
08-11 12:28:28.037   326  1397 V AudioFlinger: removeClient_l() pid 7924, calling pid 326
08-11 12:28:28.037   326  2174 V AudioFlinger: releasing 21 from 7924 for 7924
08-11 12:28:28.037   326  2174 V AudioFlinger:  decremented refcount to 0
08-11 12:28:28.037   326  2174 V AudioFlinger: purging stale effects
,08-11 12:28:28.040  7924  7958 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-11 12:28:28.045  7924  7924 V AudioManager: registerRemoteController: size of Media player list: 0
08-11 12:28:28.046  7924  7924 E AudioManager: No RCC entry present to update
08-11 12:28:28.046  7924  7924 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-11 12:28:28.050  7924  7924 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-11 12:28:28.051  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-11 12:28:28.051  7924  7924 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-11 12:28:28.055  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-11 12:28:28.185  1035  1906 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:28:28.185  1035  1906 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:28:28.313  1035  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-11 12:28:28.323  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 12:28:28.328  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 12:28:28.329  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 12:28:28.330  7924  7924 I BluetoothA2dpServiceJni: classInitNative
08-11 12:28:28.330  7924  7924 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 12:28:28.330  7924  7924 D A2dpStateMachine: make
08-11 12:28:28.333  7924  7924 I bluedroid-qcom: get_profile_interface a2dp
08-11 12:28:28.333  7924  7990 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-11 12:28:28.338  7924  7924 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-11 12:28:28.338  7924  7924 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-11 12:28:28.341  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:28.343  7924  7924 I BluetoothHidServiceJni: classInitNative: succeeds
08-11 12:28:28.347  7924  7989 D A2dpStateMachine: Enter Disconnected: -2
08-11 12:28:28.350  7924  7924 D HidService: Received start request. Starting profile...
08-11 12:28:28.350  7924  7924 I bluedroid-qcom: get_profile_interface hidhost
08-11 12:28:28.350  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:28.352  7924  7924 I BluetoothHealthServiceJni: classInitNative: succeeds
08-11 12:28:28.358  7924  7924 D HealthService: Received start request. Starting profile...
,08-11 12:28:28.363  7924  7924 I bluedroid-qcom: get_profile_interface health
,08-11 12:28:28.363  7924  7924 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-11 12:28:28.364  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:28.366  7924  7924 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 12:28:28.370  7924  7924 D PanService: Received start request. Starting profile...
,08-11 12:28:28.371  7924  7924 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 12:28:28.371  7924  7924 I bluedroid-qcom: get_profile_interface pan
08-11 12:28:28.385  7924  7924 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-11 12:28:28.385  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
,08-11 12:28:28.388  7924  7924 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-11 12:28:28.401  7924  7924 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 12:28:28.402  7924  7924 D BtGatt.GattService: Received start request. Starting profile...
08-11 12:28:28.402  7924  7924 D BtGatt.GattService: start()
,08-11 12:28:28.403  7924  7924 I bluedroid-qcom: get_profile_interface gatt
08-11 12:28:28.405  7924  7924 D BtGatt.AdvertiseManager: advertise manager created
,08-11 12:28:28.419  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:28.421  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
,08-11 12:28:28.422  7924  7924 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-11 12:28:28.424  7924  7924 V BluetoothMapService: BluetoothMapBinder()
08-11 12:28:28.425  7924  7924 D BluetoothMapService: Received start request. Starting profile...
08-11 12:28:28.425  7924  7924 D BluetoothMapService: start()
08-11 12:28:28.431  7924  7924 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-11 12:28:28.431  7924  7924 D BluetoothMapEmailAppObserver: createReceiver()
08-11 12:28:28.433  7924  7924 D BluetoothMapEmailAppObserver: initObservers()
08-11 12:28:28.434  7924  7924 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-11 12:28:28.448  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
,08-11 12:28:28.448  7924  7924 D HeadsetStateMachine: Proxy object connected
08-11 12:28:28.449  7924  7924 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-11 12:28:28.449  7924  7924 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-11 12:28:28.452  7924  7978 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 12:28:28.453  7924  7978 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-11 12:28:28.453  7924  7978 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-11 12:28:28.458  7924  7924 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 12:28:28.462  7924  7924 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-11 12:28:28.467  7924  7924 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 12:28:28.469  7924  7924 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:28.474  7924  7924 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 12:28:28.474  7924  7924 V PanService: [BTUI] SIM Extra State :ABSENT
,08-11 12:28:28.478  7924  7924 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-11 12:28:28.482  7924  7924 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-11 12:28:28.482  7924  7924 V BluetoothMapService: Handler(): got msg=1
08-11 12:28:28.483  7924  7924 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 12:28:28.483  7924  7924 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 12:28:28.483  7924  7924 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 12:28:28.484  7924  7924 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:28.484  7924  7958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-11 12:28:28.484  7924  7924 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-11 12:28:28.484  7924  7958 I bluedroid-qcom: enable
08-11 12:28:28.484  7924  7997 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-11 12:28:28.485  7924  7958 I bt_hci_bdroid: init
08-11 12:28:28.485  7924  7997 I bt-btu  : btu_task pending for preload complete event
08-11 12:28:28.489  7924  7958 I bt_vendor: bt-vendor : init
08-11 12:28:28.489  7924  7958 I bt_vendor: bt-vendor : get_bt_soc_type
08-11 12:28:28.489  7924  7958 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-11 12:28:28.489  7924  7958 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-11 12:28:28.489  7924  7958 D bt_userial_mct: userial_init
08-11 12:28:28.490  7924  7958 D bt_hci_bdroid: set_power 1
08-11 12:28:28.490  7924  7958 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-11 12:28:28.490  7924  7958 I bt_vendor: Starting hciattach daemon
08-11 12:28:28.491  7924  7958 I bt_vendor: try to set true
08-11 12:28:28.483  8000  8000 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 12:28:28.493  8000  8000 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:28.535  8001  8001 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-11 12:28:28.640  8007  8007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-11 12:28:28.662  8008  8008 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-11 12:28:28.690  8010  8010 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-11 12:28:28.702  8011  8011 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-11 12:28:28.715  8012  8012 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-11 12:28:28.730  8013  8013 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-11 12:28:28.768  8015  8015 I libmdmdetect: ESOC framework not supported
,08-11 12:28:28.769  8015  8015 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-11 12:28:28.778  8015  8015 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-11 12:28:28.779  8015  8015 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-11 12:28:28.779  8015  8015 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-11 12:28:28.779  8015  8015 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-11 12:28:28.779  8015  8015 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-11 12:28:28.779  8015  8015 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-11 12:28:28.779  8015  8015 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-11 12:28:28.822  8015  8019 E QC-QMI  : qmi_client [8015] 15: failed to locate client data
,08-11 12:28:28.825   491   491 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-11 12:28:28.825   491   491 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-11 12:28:28.843  8023  8023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-11 12:28:28.858  8024  8024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-11 12:28:28.897  7924  7958 I bt_vendor: bluetooth satus is on
08-11 12:28:28.897  7924  7958 D bt_hci_bdroid: preload
,08-11 12:28:28.899  7924  7999 D bt_userial_mct: userial_open(port:0)
08-11 12:28:28.899  7924  7999 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-11 12:28:28.903  7924  7999 I bt_vendor: Done intiailizing UART
08-11 12:28:28.904  7924  7999 I bt_vendor: Done intiailizing UART
08-11 12:28:28.904  7924  7999 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-11 12:28:28.904  7924  7999 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-11 12:28:28.905  7924  7997 I bt-btu  : btu_task received preload complete event
08-11 12:28:28.905  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-11 12:28:28.905  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-11 12:28:28.908  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-11 12:28:28.909  7924  8026 D bt_userial_mct: Entering userial_read_thread()
,08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_HCI
,08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_BNEP
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_GAP
,08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_PAN,
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_SDP
,08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_SMP,
08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-11 12:28:28.914  7924  7997 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 12:28:28.974  7924  7997 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-11 12:28:28.974  7924  7997 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ee061 ,
08-11 12:28:28.974  7924  7997 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ee061 
,08-11 12:28:29.018  7924  7962 E bt-btif : Calling BTA_HhEnable
,08-11 12:28:29.018  7924  7962 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-11 12:28:29.018  7924  7962 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-11 12:28:29.025  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-11 12:28:29.025  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-11 12:28:29.025  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-11 12:28:29.025  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-11 12:28:29.025  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-11 12:28:29.028  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-11 12:28:29.029  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-11 12:28:29.030  7924  7962 D BluetoothAdapterProperties: Name is: G3
08-11 12:28:29.032  7924  7962 D BluetoothAdapterProperties: Scan Mode:20
,08-11 12:28:29.033  7924  7962 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 12:28:29.033  7924  7962 D bt_hci_bdroid: postload
08-11 12:28:29.033  7924  7999 D bt_hci_bdroid: Used up Tx Cmd credits
,08-11 12:28:29.043  7924  7999 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 12:28:29.044  7924  7997 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-11 12:28:29.045  7924  7962 D bte_conf: Device ID record 1 : primary
08-11 12:28:29.045  7924  7962 D bte_conf:   vendorId            = 00c4
08-11 12:28:29.045  7924  7962 D bte_conf:   vendorIdSource      = 0001
08-11 12:28:29.045  7924  7962 D bte_conf:   product             = 13a1
08-11 12:28:29.045  7924  7962 D bte_conf:   version             = 1000
08-11 12:28:29.045  7924  7962 D bte_conf:   clientExecutableURL = 
08-11 12:28:29.045  7924  7962 D bte_conf:   serviceDescription  = 
08-11 12:28:29.045  7924  7962 D bte_conf:   documentationURL    = 
08-11 12:28:29.045  7924  7962 D bte_conf: bte_load_did_conf no section named DID2.
08-11 12:28:29.048  7924  7999 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 12:28:29.051  7924  7999 D bt_hci_bdroid: Used up Tx Cmd credits
08-11 12:28:29.053  7924  8026 E bt_mct  : hci lib postload completed
,08-11 12:28:29.055  7924  7958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-11 12:28:29.055  7924  7958 D BluetoothAdapterProperties: ScanMode =  20
08-11 12:28:29.056  7924  7958 D BluetoothAdapterProperties: State =  11
08-11 12:28:29.056  7924  7958 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-11 12:28:29.056  7924  7958 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-11 12:28:29.056  7924  7958 D BluetoothAdapterProperties: Setting state to 12
08-11 12:28:29.056  7924  7958 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 12:28:29.053  8028  8028 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:29.059  7924  7962 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-11 12:28:29.059  7924  7962 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-11 12:28:29.053  8028  8028 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:29.064  7924  7997 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:29.064  7924  7997 W bt-smp  : Plain text(LSB ~ MSB) = 53 f2 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:29.064  7924  7997 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d 08 cd 27 6f 44 02 3b 50 aa bc 27 59 15 88 ab 
08-11 12:28:29.065  7924  7997 W bt-btm  : Stopping oneshot timer
,08-11 12:28:29.084  1035  1109 D BluetoothManagerService: Message: 60
08-11 12:28:29.084  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-11 12:28:29.084  1035  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-11 12:28:29.090  7924  7997 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:29.090  7924  7997 W bt-smp  : Plain text(LSB ~ MSB) = 86 50 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:29.090  7924  7997 W bt-smp  : Encrypted text(LSB ~ MSB) = 85 af a6 98 13 46 f1 6e ea fe af f3 ae cc f2 29 
08-11 12:28:29.090  7924  7997 W bt-btm  : Stopping oneshot timer
08-11 12:28:29.089  7924  7962 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 12:28:29.090  7924  7962 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-11 12:28:29.102  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:29.102  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:29.102  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:29.102  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:29.102  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:29.102  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:29.102  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:29.102  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:28:29.106  7924  7958 I BluetoothAdapterState: Entering On State
08-11 12:28:29.110  7924  7997 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:29.110  7924  7997 W bt-smp  : Plain text(LSB ~ MSB) = 81 d9 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:29.110  7924  7997 W bt-smp  : Encrypted text(LSB ~ MSB) = 75 94 b0 7f e5 aa c4 56 4f 7d 0a 86 f1 aa 92 2a 
08-11 12:28:29.111  7924  7997 W bt-btm  : Stopping oneshot timer
08-11 12:28:29.112  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:29.121  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:29.121  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:29.121  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:29.121  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:29.121  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:29.121  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:29.121  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:29.121  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:28:29.126  7924  7997 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:29.126  7924  7997 W bt-smp  : Plain text(LSB ~ MSB) = 80 d1 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:29.126  7924  7997 W bt-smp  : Encrypted text(LSB ~ MSB) = 5f 61 7d 39 92 3f c7 73 7f b5 2f b4 6a b1 60 91 
08-11 12:28:29.126  7924  7997 W bt-btm  : Stopping oneshot timer
08-11 12:28:29.132  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:29.139  7924  7958 D LGBluetoothServiceAdapter: [BTUI] OnState
08-11 12:28:29.139  7924  7958 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-11 12:28:29.139  7924  7958 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-11 12:28:29.143  7924  7958 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-11 12:28:29.144  7924  7997 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-11 12:28:29.144  7924  7997 W bt-smp  : Plain text(LSB ~ MSB) = a4 69 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-11 12:28:29.144  7924  7997 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 d0 78 03 e0 db 19 aa ea 49 a0 46 65 14 6f ba 
08-11 12:28:29.144  7924  7997 W bt-btm  : Stopping oneshot timer
08-11 12:28:29.144  6861  7671 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 12:28:29.150  1853  3992 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:28:29.157  7924  7958 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-11 12:28:29.162  1853  1853 D BluetoothHeadset: Proxy object connected
08-11 12:28:29.168  6861  6880 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-11 12:28:29.192  1853  2459 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:28:29.193  6861  6861 D BluetoothInputDevice: Proxy object connected
08-11 12:28:29.193  6861  6861 D HidProfile: Bluetooth service connected
08-11 12:28:29.199  1853  1853 D BluetoothHeadset: Proxy object connected
08-11 12:28:29.199  1035  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:28:29.200  1035  1035 D BluetoothHeadset: Proxy object connected
08-11 12:28:29.201  6861  6878 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:28:29.203  8045  8045 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-11 12:28:29.204  1853  3990 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:28:29.206  6861  6861 D BluetoothHeadset: Proxy object connected
08-11 12:28:29.206  6861  6861 D HeadsetProfile: Bluetooth service connected
08-11 12:28:29.206  1853  1853 D BluetoothHeadset: Proxy object connected
08-11 12:28:29.207  6861  7671 D BluetoothPan: onBluetoothStateChange on: true
08-11 12:28:29.207  6861  7671 D BluetoothPan: onBluetoothStateChange call bindService
08-11 12:28:29.210  1035  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 12:28:29.211  6861  6861 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 12:28:29.211  6861  6861 D PanProfile: Bluetooth service connected
08-11 12:28:29.212  6861  6880 D BluetoothMap: onBluetoothStateChange: up=true
08-11 12:28:29.213  1035  1035 D BluetoothA2dp: Proxy object connected
08-11 12:28:29.325  1035  1109 I art     : Explicit concurrent mark sweep GC freed 27918(1378KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.724ms total 110.350ms
,08-11 12:28:29.335  6861  6880 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 12:28:29.336  6861  6861 D BluetoothMap: Proxy object connected
08-11 12:28:29.336  6861  6861 D MapProfile: Bluetooth service connected
08-11 12:28:29.336  6861  6861 D BluetoothMap: getConnectedDevices()
08-11 12:28:29.338  7924  7940 V BluetoothMapService: getConnectedDevices()
08-11 12:28:29.340  1035  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-11 12:28:29.341  1035  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-11 12:28:29.341  6861  6861 D BluetoothA2dp: Proxy object connected
,08-11 12:28:29.341  6861  6861 D A2dpProfile: Bluetooth service connected
08-11 12:28:29.342  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-11 12:28:29.342  1035  1109 D BluetoothManagerService: Message: 40
08-11 12:28:29.342  1035  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-11 12:28:29.346  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:29.346  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-11 12:28:29.347  1942  2095 D LGBluetoothAPIService: Message: 1
08-11 12:28:29.347  1942  2095 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-11 12:28:29.347  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:29.350  1942  2095 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-11 12:28:29.351  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:29.353  7924  7924 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:29.353  7924  7924 D BluetoothMapService: STATE_ON
08-11 12:28:29.354  7924  7924 D LGBluetoothAPIServer: [BTUI] onCreate()
08-11 12:28:29.355  7924  7924 D LGBluetoothAPIServer: [BTUI] onBind()
,08-11 12:28:29.357  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-11 12:28:29.357  1942  2095 D LGBluetoothAPIService: Message: 100
08-11 12:28:29.357  1942  2095 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-11 12:28:29.358  6861  6861 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-11 12:28:29.360  6861  6861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-11 12:28:29.365  6861  6861 D DockEventReceiver: finishStartingService: stopping service
08-11 12:28:29.385  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:29.385  7924  7924 V BluetoothPbapService: Pbap Service onCreate
08-11 12:28:29.386  7924  7924 V BluetoothPbapService: Starting PBAP service
,08-11 12:28:29.387  7924  7924 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-11 12:28:29.387  7924  7924 V BluetoothMapService: Handler(): got msg=1
08-11 12:28:29.387  7924  7924 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-11 12:28:29.388  7924  7924 V BluetoothPbapService: Pbap Service onBind
08-11 12:28:29.389  6861  6861 D BluetoothPbap: Proxy object connected
08-11 12:28:29.389  6861  6861 D PbapServerProfile: Bluetooth service connected
08-11 12:28:29.389  7924  7924 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:29.389  7924  7924 V BluetoothPbapService: state: 12
08-11 12:28:29.389  7924  7924 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-11 12:28:29.389  7924  8054 D BluetoothMapMasInstance: MAS initSocket()
08-11 12:28:29.389  7924  7924 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:29.389  7924  7924 V BluetoothPbapReceiver: ***********state = 12
08-11 12:28:29.390  7924  8054 D BluetoothMapMasInstance:   masId = 00
08-11 12:28:29.390  7924  8054 D BluetoothMapMasInstance:   msgTypes = 0e
08-11 12:28:29.390  7924  8054 D BluetoothMapMasInstance:   masName = SMS/MMS
08-11 12:28:29.390  7924  8054 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-11 12:28:29.390  7924  7924 V BluetoothPbapService: Handler(): got msg=1
08-11 12:28:29.391  7924  7924 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-11 12:28:29.391  1035  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:29.392  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:28:29.392  7924  8054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:29.393  7924  8055 V BluetoothPbapService: Pbap Service initSocket
08-11 12:28:29.393  2214  2214 D c       : Getting all permits...
08-11 12:28:29.393  2214  2214 D a       : Opening database...
08-11 12:28:29.393  1035  1651 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:29.394  7924  7962 D BluetoothAdapterProperties: Scan Mode:21
08-11 12:28:29.394  7924  7962 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-11 12:28:29.394  7924  8054 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-11 12:28:29.395  7924  8054 V BluetoothMapMasInstance: Succeed to create listening socket 
08-11 12:28:29.395  7924  8054 D BluetoothMapMasInstance: Accepting socket connection...
08-11 12:28:29.395  7924  8055 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:29.396  7924  8055 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-11 12:28:29.396  7924  8055 V BluetoothPbapService: Succeed to create listening socket 
08-11 12:28:29.396  7924  8055 V BluetoothPbapService: Accepting socket connection...
08-11 12:28:29.396  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:29.397  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:29.398  2214  2214 D a       : Opening database auth.proximity.permit_store...
,08-11 12:28:29.399  2214  2214 D a       : Closing database...
08-11 12:28:29.409  6861  6861 D BluetoothPermissionRequest: onReceive
08-11 12:28:29.411  6861  6861 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-11 12:28:29.413  6861  6861 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-11 12:28:29.416  7924  7924 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-11 12:28:29.417  7924  7924 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-11 12:28:29.424  7924  7924 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-11 12:28:29.449  7924  7924 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-11 12:28:29.450  7924  7924 V BtOppService: onCreate
,08-11 12:28:29.454  7924  7924 V BluetoothOppNotification: send message
08-11 12:28:29.458  7924  7924 V BtOppService: Starting RfcommListener
08-11 12:28:29.475  7924  7924 D BluetoothOppPreference: Dumping Names:  
08-11 12:28:29.476  7924  7924 D BluetoothOppPreference: {}
08-11 12:28:29.476  7924  7924 D BluetoothOppPreference: Dumping Channels:  
08-11 12:28:29.476  7924  7924 D BluetoothOppPreference: {}
08-11 12:28:29.476  7924  7924 V BtOppService: onStartCommand
,08-11 12:28:29.481  7924  8062 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-11 12:28:29.481  7924  7924 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:29.481  7924  7924 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-11 12:28:29.484  7924  8059 V BtOppService: Deleted complete outbound shares, number =  0
08-11 12:28:29.486  7924  8062 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 12:28:29.486  7924  8059 V BtOppService: Deleted complete inbound failed shares, number = 0
08-11 12:28:29.487  7924  8059 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-11 12:28:29.488  7924  8059 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@137a021 on behalf of 
08-11 12:28:29.488  7924  8062 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31ff6c46 on behalf of 
08-11 12:28:29.489  7924  7924 V BluetoothOppNotification: new notify threadi!
08-11 12:28:29.490  7924  7924 V BluetoothOppNotification: send delay message
08-11 12:28:29.491  7924  7924 V BtOppService: start RfcommListener
08-11 12:28:29.493  7924  8062 V BluetoothOppNotification: update too frequent, put in queue
08-11 12:28:29.494  7924  8062 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-11 12:28:29.495  7924  8063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-11 12:28:29.496  7924  7924 V BtOppService: RfcommListener started
08-11 12:28:29.497  7924  7924 V BtOppService: ContentObserver received notification
08-11 12:28:29.498  7924  8063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20e29e07 on behalf of 
08-11 12:28:29.499  7924  8063 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-11 12:28:29.500  7924  8064 V BtOppRfcommListener: Starting RFCOMM listener....
08-11 12:28:29.501  7924  8065 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 12:28:29.502  7924  8065 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 12:28:29.502  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:29.503  7924  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d0d9b34 on behalf of 
08-11 12:28:29.505  7924  8063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-11 12:28:29.507  7924  8065 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-11 12:28:29.507  7924  8063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@324d1d5d on behalf of 
08-11 12:28:29.509  7924  8063 V BluetoothOppNotification: outbound: succ-0  fail-0
08-11 12:28:29.511  7924  8064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:29.513  7924  8064 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-11 12:28:29.514  7924  8064 V BtOppRfcommListener: Started RFCOMM listener....
08-11 12:28:29.514  7924  8064 I BtOppRfcommListener: Accept thread started.
08-11 12:28:29.514  7924  8064 V BtOppRfcommListener: Accepting connection...
08-11 12:28:29.515  7924  8063 V BluetoothOppNotification: outbound notification was removed.
08-11 12:28:29.515  7924  8063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-11 12:28:29.517  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
08-11 12:28:29.518  7924  7924 V BluetoothFtpService: Ftp Service onCreate
08-11 12:28:29.518  7924  7924 I BluetoothFtpService: Ftp Service onCreate
08-11 12:28:29.518  7924  7924 V BluetoothFtpService: Ftp Service onStartCommand
08-11 12:28:29.518  7924  7924 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:29.518  7924  7924 V BluetoothFtpService: Starting Listening on sockets
08-11 12:28:29.518  7924  8063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@280113a3 on behalf of 
08-11 12:28:29.518  7924  7924 V BtOppService: ContentObserver received notification
08-11 12:28:29.519  7924  7924 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-11 12:28:29.519  7924  7924 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-11 12:28:29.519  7924  7924 V BluetoothSapReceiver: SapReceiver onReceive 
08-11 12:28:29.520  7924  7924 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:29.520  7924  7924 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,08-11 12:28:29.522  7924  8066 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-11 12:28:29.522  7924  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-11 12:28:29.522  7924  8063 V BluetoothOppNotification: inbound: succ-0  fail-0
08-11 12:28:29.524  7924  8063 V BluetoothOppNotification: inbound notification was removed.
08-11 12:28:29.524  7924  8063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-11 12:28:29.524  7924  7924 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-11 12:28:29.524  7924  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f8336a0 on behalf of 
08-11 12:28:29.525  7924  8063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15433259 on behalf of 
08-11 12:28:29.527  7924  8066 V BluetoothOppNotification: update too frequent, put in queue
08-11 12:28:29.528  7924  8066 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-11 12:28:29.528  7924  7924 V BluetoothFtpService: Handler(): got msg=1
08-11 12:28:29.530  7924  7924 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-11 12:28:29.530  7924  7924 V BluetoothFtpService: Ftp Service initSocket
,08-11 12:28:29.535  1035  1651 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:29.537  7924  7924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:29.538  7924  7924 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-11 12:28:29.539  7924  7924 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-11 12:28:29.547  7924  8067 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-11 12:28:29.565  7924  7924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96840c
,08-11 12:28:29.565  7924  7924 V BluetoothSapService: Sap Service onCreate
08-11 12:28:29.567  7924  7924 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:28:29.567  7924  7924 V BluetoothSapService: state: 12
08-11 12:28:29.567  7924  7924 V BluetoothSapService: Starting SAP server process
08-11 12:28:29.569  7924  7924 V BluetoothSapService: SAP Service startRfcommListenerThread
08-11 12:28:29.570  7924  8069 V BluetoothSapService: Sap Service initRfcommSocket
08-11 12:28:29.563  8068  8068 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:29.571  1035  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:29.563  8068  8068 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:29.572  7924  8069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:28:29.573  7924  8069 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-11 12:28:29.573  7924  8069 V BluetoothSapService: Succeed to create listening socket 
08-11 12:28:29.573  7924  8069 V BluetoothSapService: Accepting socket connection...
08-11 12:28:29.582  8068  8068 V BT_SAP  : Event pipe created
08-11 12:28:29.582  8068  8068 V BT_SAP  : create_server_socket qcom.sap.server
08-11 12:28:29.582  8068  8068 V BT_SAP  : created socket fd 6
,08-11 12:28:29.861  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:29.861  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:29.861  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:29.861  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:28:29.861  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:29.861  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:29.861  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:29.861  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:28:29.867  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:28:29.867  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:29.867  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ed3df65 removed from the list
08-11 12:28:29.867  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:28:29.867  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:29.867  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:29.868  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:28:29.868  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b65143a added. We now have 4 listener(s)
08-11 12:28:29.868  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:28:29.872  1035  1906 D WifiServiceImplEx: setWifiEnabled: false pid=6630, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 12:28:29.872  1035  1906 D WifiService: setWifiEnabled: false pid=6630, uid=10118
08-11 12:28:29.872  1035  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 12:28:29.878  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:29.881  1035  1924 D WifiServiceImplEx: setWifiEnabled: true pid=6630, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-11 12:28:29.882  1035  1924 D WifiService: setWifiEnabled: true pid=6630, uid=10118
08-11 12:28:29.882  1035  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 12:28:29.894  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-11 12:28:29.894  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-11 12:28:29.894  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-11 12:28:29.896  1035  1399 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-11 12:28:29.896  1035  1399 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-11 12:28:29.898  1035  1399 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-11 12:28:29.898  1035  1399 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-11 12:28:29.898  1035  1399 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-11 12:28:29.899  1035  1399 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-11 12:28:29.899  1035  1399 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-11 12:28:29.899  1035  1399 E WifiHW  : unknown target_country: EU , set to default
,08-11 12:28:29.899  1035  1399 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-11 12:28:29.899  1035  1399 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-11 12:28:29.900  1035  1399 I WifiUtil: gEnableBmps=1
08-11 12:28:30.492  7924  7924 V BluetoothOppNotification: new notify threadi!
08-11 12:28:30.492  7924  7924 V BluetoothOppNotification: send delay message
,08-11 12:28:30.511   322   894 D SoftapController: Softap fwReload - Ok
,08-11 12:28:30.516  1035  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-11 12:28:30.516  1035  1109 D Tethering: InitialState.processMessage what=4
08-11 12:28:30.516  1035  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-11 12:28:30.536  1035  1399 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (609ms)
08-11 12:28:30.540   322   894 D CommandListener: Setting iface cfg
08-11 12:28:30.541   322   894 D CommandListener: Trying to bring down wlan0
,08-11 12:28:30.545   322   894 D CommandListener: Clearing all IP addresses on wlan0
08-11 12:28:30.557  1035  1399 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-11 12:28:30.553  8090  8090 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:30.563  8090  8090 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-11 12:28:30.597  1035  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 12:28:30.597  1035  1399 E WifiStateMachine: useWiFiOffloading() : false
08-11 12:28:30.597  1035  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-11 12:28:30.619  7924  8088 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-11 12:28:30.625  1035  1399 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-11 12:28:30.625  1035  1399 D WifiMonitor: connecting to supplicant
08-11 12:28:30.628  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:30.629  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 12:28:30.630  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 12:28:30.630  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 12:28:30.630  6861  6861 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 12:28:30.631  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-11 12:28:30.633  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-11 12:28:30.634  8090  8090 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-11 12:28:30.639  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:30.641  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:30.642  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 12:28:30.642  7924  8088 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1eb9b15 on behalf of 
08-11 12:28:30.643  7924  8088 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-11 12:28:30.643  6861  6861 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 12:28:30.643  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 12:28:30.643  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 12:28:30.643  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 12:28:30.643  6861  6861 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 12:28:30.643  6861  6861 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 12:28:30.646  7924  8088 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-11 12:28:30.647  7924  8088 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21cf9e2a on behalf of 
08-11 12:28:30.647  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 12:28:30.647  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-11 12:28:30.647  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 12:28:30.647  6861  6861 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 12:28:30.648  7924  8088 V BluetoothOppNotification: outbound: succ-0  fail-0
08-11 12:28:30.648  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 12:28:30.649  6861  6861 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-11 12:28:30.649  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-11 12:28:30.649  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 12:28:30.649  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 12:28:30.649  6861  6861 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 12:28:30.650  6861  6861 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 12:28:30.654  7924  8088 V BluetoothOppNotification: outbound notification was removed.
08-11 12:28:30.654  7924  8088 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-11 12:28:30.655  7924  8088 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2613541b on behalf of 
08-11 12:28:30.656  7924  8088 V BluetoothOppNotification: inbound: succ-0  fail-0
08-11 12:28:30.661  7924  8088 V BluetoothOppNotification: inbound notification was removed.
08-11 12:28:30.661  7924  8088 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-11 12:28:30.662  7924  8088 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bd39b8 on behalf of 
08-11 12:28:30.670  8090  8090 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-11 12:28:30.670  8090  8090 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-11 12:28:30.698  1035  2032 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8107 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-11 12:28:30.750  8090  8090 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-11 12:28:30.782  8090  8090 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-11 12:28:30.787  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-11 12:28:30.788  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-11 12:28:30.788  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-11 12:28:30.789  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-11 12:28:30.789  1035  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-11 12:28:30.789  1035  1399 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-11 12:28:30.789  1035  8130 D WifiMonitor: Dropping event because (p2p0) is stopped
08-11 12:28:30.789  1035  1399 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:30.789  1035  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:30.789  1035  1399 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-11 12:28:30.789  1035  1399 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-11 12:28:30.790  1035  1399 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-11 12:28:30.790  1035  1399 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-11 12:28:30.790  1035  1399 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-11 12:28:30.808  8090  8090 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-11 12:28:30.808  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-11 12:28:30.808  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-11 12:28:30.808  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-11 12:28:30.808  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-11 12:28:30.808  1035  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-11 12:28:30.808  1035  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-11 12:28:30.831  1035  1870 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8131 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 12:28:30.833  1035  1399 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-11 12:28:30.833  1035  1399 E WifiStateMachine: useWiFiOffloading() : false
08-11 12:28:30.833  1035  1399 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-11 12:28:30.835  1035  1399 D WifiNative-wlan0: doBoolean: SET update_config 1
08-11 12:28:30.836  1035  1399 D WifiNative-wlan0: SET update_config 1: returned true
08-11 12:28:30.836  1035  1399 D WifiConfigStore: Loading config and enabling all networks 
08-11 12:28:30.836  1035  1399 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-11 12:28:30.836  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.837  1035  1399 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-11 12:28:30.838  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:30.838  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-11 12:28:30.839  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.839  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.839  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.840  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-11 12:28:30.841  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-11 12:28:30.841  1035  1442 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-11 12:28:30.844  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:30.844  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:30.844  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:30.844  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:30.844  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:30.844  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:30.844  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:30.844  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:28:30.847  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:30.850  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:30.850  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:30.850  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:30.850  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:30.850  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:30.850  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:28:30.850  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:28:30.850  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:28:30.852  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:28:30.853  8107  8128 W FormManager: Network not available. Please check & try again.
08-11 12:28:30.860  1035  1399 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-11 12:28:30.866  8107  8129 V FormManager: Network unavailable.
08-11 12:28:30.869  8107  8129 V FormManager: Network unavailable.
08-11 12:28:30.869  1035  1399 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-11 12:28:30.870  1035  1399 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-11 12:28:30.871  1035  1399 D WifiStateMachine: enableVerboseLogging : level 2
08-11 12:28:30.871  1035  1399 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-11 12:28:30.871  1035  1399 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-11 12:28:30.871  1035  1399 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-11 12:28:30.872  1035  1399 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-11 12:28:30.872  1035  1399 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-11 12:28:30.872  1035  1399 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-11 12:28:30.872  1035  1399 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-11 12:28:30.873  1035  1399 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-11 12:28:30.873  1035  1399 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-11 12:28:30.873  1035  1399 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-11 12:28:30.873  1035  1399 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-11 12:28:30.874  1035  1399 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-11 12:28:30.874  1035  1399 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-11 12:28:30.874  1035  1399 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-11 12:28:30.875  1035  1399 D WifiStateMachine: Setting OUI to DA-A1-19
08-11 12:28:30.875  1035  1399 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-11 12:28:30.875  1035  1399 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-11 12:28:30.875  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-11 12:28:30.876  1035  1399 D WifiNative-HAL: Setting external_sim to 1
08-11 12:28:30.876  1035  1399 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-11 12:28:30.876  1942  2268 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-11 12:28:30.876  1942  2268 D WfdsService: Set the WFDS Monitor: true
08-11 12:28:30.876  1942  2268 D WfdsMonitor: WfdsMonitorThread create
08-11 12:28:30.876  1942  2268 D WfdsMonitor: WFDS Monitor is created and started
08-11 12:28:30.876  1942  2268 D WfdsService: WiFi: Supplicant connection re-established
08-11 12:28:30.876  7705  7705 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.877  1035  1399 D WifiNative-wlan0: SET external_sim 1: returned true
08-11 12:28:30.877  1035  1399 I WifiNative-HAL: startHal
,08-11 12:28:30.877  1035  1399 D wifi    : setting scan oui 0xaf5fdee0
08-11 12:28:30.877  1035  1399 D WifiStateMachine: Setting OUI to DA-A1-19
08-11 12:28:30.877  1942  8149 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-11 12:28:30.877  1035  1399 I WifiNative-HAL: startHal
08-11 12:28:30.877  1035  1399 D wifi    : setting scan oui 0xaf5fdee0
08-11 12:28:30.877  1035  1399 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-11 12:28:30.878  1942  8149 E CtrlSupplicant: Succeed to open control connection
08-11 12:28:30.878  1942  8149 E CtrlSupplicant: Succeed to open monitor connection
08-11 12:28:30.878  1035  1399 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-11 12:28:30.878  1942  8149 D WfdsMonitor: Supplicant connection established
08-11 12:28:30.878  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-11 12:28:30.878  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-11 12:28:30.878  1942  2268 D WfdsService: Connected to the supplicant for wfds
08-11 12:28:30.879  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-11 12:28:30.879  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-11 12:28:30.879  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-11 12:28:30.879  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-11 12:28:30.879  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-11 12:28:30.879  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-11 12:28:30.880  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-11 12:28:30.880  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-11 12:28:30.880  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-11 12:28:30.880  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-11 12:28:30.880  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-11 12:28:30.880  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-11 12:28:30.882  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-11 12:28:30.882  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-11 12:28:30.882  8090  8090 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-11 12:28:30.882  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-11 12:28:30.882  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-11 12:28:30.883  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-11 12:28:30.883  1035  1399 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-11 12:28:30.884  1035  1399 E WifiNative: : [184,803,904 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-11 12:28:30.884  1035  1399 D WifiNative-wlan0: doBoolean: RECONNECT
08-11 12:28:30.885  1035  1399 D WifiNative-wlan0: RECONNECT: returned true
08-11 12:28:30.885  1035  1399 D WifiNative-wlan0: doString: [STATUS]
08-11 12:28:30.885  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-11 12:28:30.885  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-11 12:28:30.885  1035  1399 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-11 12:28:30.886  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 12:28:30.886  1035  1399 D WifiNative-wlan0: SET ps 1: returned true
08-11 12:28:30.887  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.889   322   894 D CommandListener: Setting iface cfg
08-11 12:28:30.889   322   894 D CommandListener: Trying to bring up p2p0
08-11 12:2,8:30.889  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-11 12:28:30.889  1035  1390 D LGWifiP2pService: P2pEnablingState
08-11 12:28:30.889  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.889  1035  1390 D LGWifiP2pService: P2p socket connection successful
08-11 12:28:30.889  1035  1390 D LGWifiP2pService: P2pEnabledState
08-11 12:28:30.891  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-11 12:28:30.891  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-11 12:28:30.891  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-11 12:28:30.891  1035  1035 D RttService: SCAN_AVAILABLE : 3
,08-11 12:28:30.891  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-11 12:28:30.891  1035  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.891  1035  1557 I WifiNative-HAL: startHal
08-11 12:28:30.892  1035  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf5fdee0
08-11 12:28:30.892  1035  1557 D wifi    : failed to get capabilities : -3
08-11 12:28:30.892  1035  1557 E WifiScanningService: could not get scan capabilities
08-11 12:28:30.892  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-11 12:28:30.892  1035  1559 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.892  1035  1399 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-11 12:28:30.892  1035  1399 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-11 12:28:30.893  1035  1399 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-11 12:28:30.893  1035  1399 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-11 12:28:30.894  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=184814  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-11 12:28:30.894  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-11 12:28:30.894  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-11 12:28:30.894  1035  1390 D LGWifiP2pService: before postfix = G3
08-11 12:28:30.894  1035  1390 D WifiServerServiceExt: postfix byte check : 2
08-11 12:28:30.894  1035  1390 D LGWifiP2pService: after postfix = G3
08-11 12:28:30.894  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-11 12:28:30.895  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-11 12:28:30.896  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-11 12:28:30.896  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-11 12:28:30.896  1942  1942 D WfdsService: WifiP2pState is changed : true
08-11 12:28:30.896  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-11 12:28:30.897  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-11 12:28:30.897  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-11 12:28:30.897  1942  1942 D WfdsService: isConnected: false
08-11 12:28:30.897  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-11 12:28:30.897  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-11 12:28:30.898  1942  2268 D WfdsService: Receive the WFDS_ENABLE Method
08-11 12:28:30.898  1942  2268 D WfdsService: Set the WFDS Monitor: true
08-11 12:28:30.898  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-11 12:28:30.898  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-11 12:28:30.898  1942  2268 D WfdsService: Connected to the supplicant for wfds
08-11 12:28:30.898  1942  2268 D WfdsJNI : doCommand: WFDS_SET TRUE
08-11 12:28:30.898  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:30.898  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:30.898  8090  8090 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-11 12:28:30.898  1942  2268 D WfdsService: selectPreferredScanChannel [36]
08-11 12:28:30.898  1942  2268 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-11 12:28:30.898  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-11 12:28:30.899  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no d,ata type icon / Roaming
08-11 12:28:30.900  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.901  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.901  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-11 12:28:30.901  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-11 12:28:30.901  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-11 12:28:30.901  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=184822  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-11 12:28:30.902  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-11 12:28:30.902  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-11 12:28:30.902  1035  1399 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-11 12:28:30.902  1035  1399 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-11 12:28:30.902  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-11 12:28:30.902  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-11 12:28:30.902  1035  1399 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-11 12:28:30.902  1035  1399 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-11 12:28:30.903  8090  8090 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-11 12:28:30.903  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-11 12:28:30.903  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-11 12:28:30.903  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-11 12:28:30.903  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-11 12:28:30.904  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-11 12:28:30.904  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-11 12:28:30.904  1942  1942 D WfdsService: Update P2p Interface State: 3
08-11 12:28:30.905  1035  1390 D LGWifiP2pService: InactiveState
08-11 12:28:30.905  1035  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.905  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.905  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-11 12:28:30.924  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-11 12:28:30.925  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:30.925  1942  8149 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 12:28:30.925  1035  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 12:28:30.925  1035  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:30.925  1035  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:30.925  1035  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:30.925  8090  8090 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-11 12:28:30.926  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.926  1942  8149 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:30.926  1035  1399 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-11 12:28:30.926  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.926  1035  1399 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-11 12:28:30.927  1035  1399 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-11 12:28:30.927  1035  1399 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-11 12:28:30.927  1035  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:30.927  8090  8090 E wpa_supplicant: disconnect_rssi_lvl: -100
08-11 12:28:30.927  1035  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.927  1035  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.927  1035  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.927  1035  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:30.927  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-11 12:28:30.927  1035  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.927  1035  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.927  1035  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.927  1035  1390 D LGWifiP2pService: InactiveState{ when=-22ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.927  1035  1399 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-11 12:28:30.927  1942  8149 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:30.927  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.927  1035  1390 D LGWifiP2pService: DefaultState{ when=-22ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.927  1035  1390 D LGWifiP2pService: InactiveState{ when=-22ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.927  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.927  1035  1390 D LGWifiP2pService: DefaultState{ when=-23ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.927  1035  1399 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-11 12:28:30.928  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.928  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=13,9287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.928  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.928  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.928  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.928  1035  1399 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-11 12:28:30.928  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.928  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-11 12:28:30.928  1035  1035 E WifiServerServiceExt: No p2p device connected
08-11 12:28:30.928  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-11 12:28:30.929  8090  8090 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:30.929  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-11 12:28:30.929  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:30.929  1035  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:30.929  1035  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-11 12:28:30.929  1942  2268 W WfdsService: DefaultState - msg [9441285] is not handled
08-11 12:28:30.929  8090  8090 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-11 12:28:30.929  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.930  1942  8149 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:30.930  1035  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:30.930  1035  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.930  1035  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.930  1035  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.930  8090  8090 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.930  1942  8149 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:30.930  1035  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-11 12:28:30.930  1035  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.930  1035  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.930  1035  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-11 12:28:30.932  1035  1399 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-11 12:28:30.932  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.932  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:30.932  1035  1399 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-11 12:28:30.933  1035  1399 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-11 12:28:30.933  1035  1399 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0,
08-11 12:28:30.933  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-11 12:28:30.933  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-11 12:28:30.933  8090  8090 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 12:28:30.933  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-11 12:28:30.933  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 12:28:30.933  1035  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 12:28:30.933  1035  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-11 12:28:30.934  1035  1399 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-11 12:28:30.934  1035  1399 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-11 12:28:30.934  1035  1399 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-11 12:28:30.934  1035  1399 D WifiNative-wlan0: doBoolean: SCAN
08-11 12:28:30.935  1035  1399 D WifiNative-wlan0: SCAN: returned false
08-11 12:28:30.935  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 12:28:30.935  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=184855  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-11 12:28:30.938  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 12:28:30.939  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=184859  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-11 12:28:30.940  1035  1399 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-11 12:28:30.941  1035  1399 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:30.942  1035  1399 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:30.942  1035  1399 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:30.942  1035  1399 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-11 12:28:30.945  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:30.945  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:30.947  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.947  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:30.947  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-11 12:28:30.947  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:30.947  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:30.947  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-11 12:28:30.952  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:28:30.953  1035  1924 I ActivityManager: Killing 7146:com.android.chrome/u0a57 (adj 15): empty #17
,08-11 12:28:31.027  1035  1978 W libprocessgroup: failed to open /acct/uid_10057/pid_7146/cgroup.procs: No such file or directory
,08-11 12:28:31.059  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 12:28:31.064  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-11 12:28:31.073  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:31.074  8107  8153 W FormManager: Network not available. Please check & try again.
,08-11 12:28:31.089  8107  8154 V FormManager: Network unavailable.
,08-11 12:28:31.094  8107  8154 V FormManager: Network unavailable.
08-11 12:28:31.115  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-11 12:28:31.115  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:31.118  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 12:28:31.122  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:31.130  4321  8155 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-11 12:28:31.142  4321  8156 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-11 12:28:31.142  4321  8156 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 12:28:31.201  1035  1577 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8157 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-11 12:28:31.348  8157  8157 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-11 12:28:31.348  8157  8157 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-11 12:28:31.360  8157  8157 V [BNRBootReceiver]: Boot Receiver Return
,08-11 12:28:31.363  8157  8157 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 12:28:31.444  1035  1577 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8181 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 12:28:31.448  1035  1577 I ActivityManager: Killing 7166:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-11 12:28:31.462  8090  8090 E wpa_supplicant: USIM:  scard_init function
08-11 12:28:31.462  8090  8090 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-11 12:28:31.465  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-11 12:28:31.465  1035  8130 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-11 12:28:31.465  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-11 12:28:31.466  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-11 12:28:31.466  1035  8130 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-11 12:28:31.466  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-11 12:28:31.466  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-11 12:28:31.467  1035  1399 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-11 12:28:31.468  1035  1399 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-11 12:28:31.468  1035  1399 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-11 12:28:31.469  1035  1399 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-11 12:28:31.469  1035  1399 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-11 12:28:31.518  1035  1978 W libprocessgroup: failed to open /acct/uid_10062/pid_7166/cgroup.procs: No such file or directory
,08-11 12:28:31.519  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=185439  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-11 12:28:31.530  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=185450  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-11 12:28:31.534  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:31.535  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.535  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-11 12:28:31.535  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:31.535  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-11 12:28:31.539  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.539  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:31.544  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.562  8181  8181 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 12:28:31.582  8090  8090 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 12:28:31.587  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-11 12:28:31.587  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-11 12:28:31.587  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-11 12:28:31.587  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-11 12:28:31.588  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:31.588  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:31.589  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=185509  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-11 12:28:31.589  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=185510  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-11 12:28:31.590  1035  1399 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=185510
08-11 12:28:31.590  1035  1399 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=185511
08-11 12:28:31.591  1035  1399 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=185511
08-11 12:28:31.591  8181  8181 D PluginManager: init()
08-11 12:28:31.591  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=185512
08-11 12:28:31.592  1035  1399 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=185512
08-11 12:28:31.592  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=185512  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-11 12:28:31.595  8090  8090 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 12:28:31.595  8090  8090 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-11 12:28:31.600  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:31.600  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:31.600  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-11 12:28:31.600  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 12:28:31.600  1035  8130 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 12:28:31.600  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-11 12:28:31.600  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 12:28:31.600  1035  8130 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-11 12:28:31.600  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:31.600  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:31.604  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.604  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:31.605  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.605  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.605  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-11 12:28:31.606  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.606  1035  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-11 12:28:31.611  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.612  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:31.612  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-11 12:28:31.613  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=185533  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-11 12:28:31.615  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:31.615  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-11 12:28:31.616  1035  1399 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=185536  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-11 12:28:31.616  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=185537  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-11 12:28:31.617  1035  1399 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=185538
08-11 12:28:31.618  1035  1399 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=185538
08-11 12:28:31.618  1035  1399 D WifiNative-wlan0: doString: [STATUS]
08-11 12:28:31.619  1035  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-11 12:28:31.619  1035  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-11 12:28:31.620  1035  1399 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-11 12:28:31.621  1035  1399 I WifiServiceExtension: setVHTCapabilityType  : false
08-11 12:28:31.627  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.627  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-11 12:28:31.633  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.637  1035  1399 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-11 12:28:31.637  1035  1399 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-11 12:28:31.643  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.643  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.643  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-11 12:28:31.651  1035  1399 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-11 12:28:31.651  1035  1458 D ConnectivityService: Got NetworkAgent Messenger
08-11 12:28:31.652  1035  1458 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-11 12:28:31.652  1035  1458 D ConnectivityService: NetworkAgent connected
08-11 12:28:31.652  1035  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 12:28:31.652  1035  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 12:28:31.652  1035  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 12:28:31.653  1035  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-11 12:28:31.654  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.654  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:31.655  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.655  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.655  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.655  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-11 12:28:31.657  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.657  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:31.659  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.661  1035  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-11 12:28:31.661  1035  1399 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 12:28:31.661  1035  1399 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-11 12:28:31.662  1035  1399 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-11 12:28:31.662  1035  1399 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-11 12:28:31.671  1035  1399 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-11 12:28:31.677   322   894 D CommandListener: Setting iface cfg
08-11 12:28:31.680  1035  1399 E WifiStateMachine: Start Dhcp Watchdog 3
08-11 12:28:31.681  1035  1399 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=185601  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:31.681  1035  1399 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=185601  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:31.682  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=185602  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:31.682  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:31.682  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:31.683  1035  1399 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-11 12:28:31.683  1035  1399 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:31.684  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-11 12:28:31.684  1035  1399 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-11 12:28:31.685  1035  8209 D DhcpStateMachine: StoppedState
08-11 12:28:31.685  1035  8209 D DhcpStateMachine: StoppedState{ when=-5ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:31.685  1035  8209 D DhcpStateMachine: WaitBeforeStartState
08-11 12:28:31.686  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:31.686  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-11 12:28:31.687  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:31.687  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-11 12:28:31.688  1035  1399 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=185608  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:31.688  1035  1399 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=185609  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:31.689  1035  1399 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=185609  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-11 12:28:31.690  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:21235] from screen [on:0 period:2032496458] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:31.691  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:2032496459] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:31.691  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-11 12:28:31.695  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 12:28:31.696  1035  1458 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-11 12:28:31.697  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.697  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.698  1035  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.698  1035  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.698  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.699  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.700  1035  1458 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-11 12:28:31.700  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:31.700  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-11 12:28:31.701  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=140,0,0
08-11 12:28:31.701  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=140,0,0
08-11 12:28:31.701  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-11 12:28:31.702  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-11 12:28:31.702  1035  1399 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-11 12:28:31.702  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 0
08-11 12:28:31.702  1035  1399 D WifiNative-wlan0: SET ps 0: returned true
08-11 12:28:31.702  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-11 12:28:31.703  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-11 12:28:31.703  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-11 12:28:31.703  1035  1399 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-11 12:28:31.703  1035  1399 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-11 12:28:31.703  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@165cfc80 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:31.703  1035  1399 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-11 12:28:31.703  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@165cfc80 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:31.703  1035  8209 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:31.703  1035  8209 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-11 12:28:31.704   322   894 D CommandListener: Setting iface cfg
08-11 12:28:31.704   322   894 D CommandListener: Trying to bring up wlan0
08-11 12:28:31.705  1035  1399 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-11 12:28:31.706  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.706  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-11 12:28:31.706  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-11 12:28:31.706  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.706  1035  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.707  1035  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.707  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-11 12:28:31.707  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES ,0 0
08-11 12:28:31.707  1035  1458 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-11 12:28:31.708  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-11 12:28:31.708  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-11 12:28:31.708  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:31.708  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:31.708  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-11 12:28:31.708  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-11 12:28:31.708  1035  1399 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-11 12:28:31.709  1035  1399 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-11 12:28:31.709  8090  8090 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-11 12:28:31.709  1035  1399 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-11 12:28:31.709  1035  1399 D WifiNative-wlan0: doBoolean: SET ps 1
08-11 12:28:31.731  1035  1399 D WifiNative-wlan0: SET ps 1: returned true
08-11 12:28:31.731  1035  1458 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-11 12:28:31.731  1035  1399 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-11 12:28:31.732  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-11 12:28:31.732  1035  1399 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-11 12:28:31.732  1035  1458 D ConnectivityService: ignoring duplicate network state non-change
08-11 12:28:31.735  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.735  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:31.735  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.735  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.735  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-11 12:28:31.736  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.736  1035  1458 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-11 12:28:31.737  1035  1458 D ConnectivityService: Adding iface wlan0 to network 102
08-11 12:28:31.743  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.743  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.743  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-11 12:28:31.745  1035  1399 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-11 12:28:31.746  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-11 12:28:31.749  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-11 12:28:31.751  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.751  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.751  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-11 12:28:31.752  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-11 12:28:31.756  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:31.756  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:31.756  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-11 12:28:31.759  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.759  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-11 12:28:31.760  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.760  1035  1458 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-11 12:28:31.760  1035  1458 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-11 12:28:31.761  1035  1458 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-11 12:28:31.761   322   894 E Netd    : netlink response contains error (File exists)
08-11 12:28:31.762  1035  1458 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-11 12:28:31.762  1035  1458 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-11 12:28:31.762  1035  1458 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-11 12:28:31.762  1035  1458 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-11 12:28:31.763  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.765  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-11 12:28:31.766  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.766  1035  1458 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-11 12:28:31.766  1035  1458 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-11 12:28:31.766  1035  1458 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-11 12:28:31.766  1035  1458 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-11 12:28:31.766  1035  1458 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:31.766  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:31.766  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-11 12:28:31.766  1035  1458 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:31.766  1035  1458 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 12:28:31.767  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:31.767  1035  1458 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.767  1035  1458 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-11 12:28:31.767  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-11 12:28:31.767  1035  1458 D ConnectivityService: currentScore = 0, newScore = 20
08-11 12:28:31.767  1035  1458 D ConnectivityService:    accepting network in place of null
08-11 12:28:31.767  1035  1458 D ConnectivityService: sending new Min Network Score(20):, NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.767  1035  1399 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.767  1035  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:31.768  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.768  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-11 12:28:31.768  1035  1458 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-11 12:28:31.768  1035  1458 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-11 12:28:31.768  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-11 12:28:31.769  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-11 12:28:31.769  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-11 12:28:31.770  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-11 12:28:31.770  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-11 12:28:31.771   322  8215 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-11 12:28:31.772  1035  1458 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:31.772  1035  1458 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,08-11 12:28:31.772  1035  1458 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-11 12:28:31.773  1035  1458 D ConnectivityService: validation of new default Network = false
08-11 12:28:31.773  1035  1458 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-11 12:28:31.773  1035  1458 D DSQN    : enableDataServiceNotify 
08-11 12:28:31.773  1035  1458 D DSQN    : start dsqn bin
08-11 12:28:31.775  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-11 12:28:31.775  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-11 12:28:31.775  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.778  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-11 12:28:31.787  1035  1458 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-11 12:28:31.787  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.787  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:31.787  1035  1458 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:31.787  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-11 12:28:31.783  8216  8216 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:31.783  8216  8216 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:31.794  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-11 12:28:31.794  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.795  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 12:28:31.802  8216  8216 E DSQN    : DSQN ssw
,08-11 12:28:31.830   322  8215 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-11 12:28:31.870   322  8215 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-11 12:28:31.901   322   893 D LGDataListener: argv[0]=dsqncommand
,08-11 12:28:31.901   322   893 D LGDataListener: argv[1]=wlan0
,08-11 12:28:31.901   322   893 D LGDataListener: argv[2]=1
08-11 12:28:31.902   322   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-11 12:28:31.904  1035  1106 D DSQN    : DSQM DsqnNotification wlan0  1
08-11 12:28:31.904  1035  1106 D DSQN    : start to monitor internet connection
08-11 12:28:31.905  1035  8209 D DhcpStateMachine: DHCPV4 request on wlan0
,08-11 12:28:31.903  8222  8222 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:31.903  8222  8222 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-11 12:28:31.905  1035  8209 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-11 12:28:31.905  1035  8209 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-11 12:28:31.913  8222  8222 I dhcpcd  : version 5.5.6 starting
08-11 12:28:31.914  8222  8222 E dhcpcd  : get_duid: m
08-11 12:28:31.914  8222  8222 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-11 12:28:31.914  8222  8222 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-11 12:28:31.918  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:31.918  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:31.918  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:31.918  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:31.918  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:31.918  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:31.918  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:31.918  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:31.919  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:31.919  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:31.919  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b65143a removed from the list
08-11 12:28:31.919  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:28:31.919  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:31.919  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:28:31.928  6630  8224 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-11 12:28:31.928  6630  8224 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-11 12:28:31.937  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 10:28:31 GMT], X-Android-Received-Millis=[1470911311937], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470911311900]}
08-11 12:28:31.937  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-11 12:28:31.937  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-11 12:28:31.937  1035  1458 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-11 12:28:31.938  1035  1458 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-11 12:28:31.938  1035  1458 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-11 12:28:31.938  1035  1458 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:31.938  1035  1458 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 12:28:31.938  1035  1458 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-11 12:28:31.938  1035  1458 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-11 12:28:31.938  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.938  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:31.938  1035  1458 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:31.939  1035  1458 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.939  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-11 12:28:31.939  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-11 12:28:31.940  1035  1399 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.940  1035  1399 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:31.940  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:31.940  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-11 12:28:31.953  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-11 12:28:31.954  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.955  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-11 12:28:31.995  8222  8222 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-11 12:28:31.996  8222  8222 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-11 12:28:31.996  8222  8222 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-11 12:28:31.996  8222  8222 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,08-11 12:28:31.997  8222  8222 D dhcpcd  : wlan0: sending REQUEST (xid 0x9cef7a8c), next in 4.01 seconds
,08-11 12:28:32.037  8181  8181 W ExternalStrings: load override strings
08-11 12:28:32.037  8181  8181 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:28:32.037  8181  8181 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 12:28:32.039  8181  8181 D StatusProvider: onCreate
,08-11 12:28:32.058  8222  8222 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-11 12:28:32.075  8181  8181 V Signer  : override build config not found
,08-11 12:28:32.076  8181  8181 D Signer  : value of property debug is false
,08-11 12:28:32.077  8222  8222 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-11 12:28:32.077  8222  8222 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-11 12:28:32.078  8222  8222 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-11 12:28:32.078  8222  8222 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-11 12:28:32.078  8222  8222 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-11 12:28:32.079  8222  8222 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-11 12:28:32.080  8222  8222 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-11 12:28:32.080  8222  8222 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-11 12:28:32.099  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-11 12:28:32.099  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-11 12:28:32.100  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-11 12:28:32.100  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-11 12:28:32.100  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-11 12:28:32.100  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-11 12:28:32.100  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-11 12:28:32.100  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-11 12:28:32.100  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-11 12:28:32.101  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-11 12:28:32.101  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-11 12:28:32.101  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,08-11 12:28:32.101  8181  8181 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-11 12:28:32.108  8181  8181 V LGMDMManager: Create singleton instance
08-11 12:28:32.146  8181  8181 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-11 12:28:32.255  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.258  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-11 12:28:32.274  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.289  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:32.339  1035  1978 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8258 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-11 12:28:32.340  1035  1978 I ActivityManager: Killing 7186:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-11 12:28:32.428  1035  1906 W libprocessgroup: failed to open /acct/uid_10085/pid_7186/cgroup.procs: No such file or directory
,08-11 12:28:32.460  8258  8258 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 12:28:32.466  8181  8246 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-11 12:28:32.486  8258  8258 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-11 12:28:32.507  1035  8209 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-11 12:28:32.510  1035  8209 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-11 12:28:32.511  1035  8209 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-11 12:28:32.511  1035  8209 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-11 12:28:32.511  1035  8209 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-11 12:28:32.511  1035  8209 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-11 12:28:32.511  1035  8209 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-11 12:28:32.511  1035  8209 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-11 12:28:32.512  1035  8209 D DhcpStateMachine: RunningState
08-11 12:28:32.523  8258  8258 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-11 12:28:32.523  8258  8258 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-11 12:28:32.524  8258  8258 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-11 12:28:32.525  8258  8258 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-11 12:28:32.525  8258  8258 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-11 12:28:32.527  8258  8258 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-11 12:28:32.532  8258  8258 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-11 12:28:32.549  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 12:28:32.558  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.574  8258  8258 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-11 12:28:32.578  8258  8258 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-11 12:28:32.580  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.580  8258  8258 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-11 12:28:32.581  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-11 12:28:32.597  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.603  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:32.613  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.613  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-11 12:28:32.615  8258  8258 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-11 12:28:32.617  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-11 12:28:32.620  6861  6861 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-11 12:28:32.624  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.624  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-11 12:28:32.631  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.639  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:28:32.647  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.648  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.648  8258  8258 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:32.651  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.651  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-11 12:28:32.657  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.663  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:32.671  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-11 12:28:32.671  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.672  8258  8258 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:32.676  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-11 12:28:32.676  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-11 12:28:32.676  6861  6861 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-11 12:28:32.676  6861  6861 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-11 12:28:32.677  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-11 12:28:32.678  6861  6861 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-11 12:28:32.678  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-11 12:28:32.678  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-11 12:28:32.678  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-11 12:28:32.678  6861  6861 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-11 12:28:32.678  6861  6861 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-11 12:28:32.678  6861  6861 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-11 12:28:32.682  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.683  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-11 12:28:32.692  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.699  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:32.705  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.705  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.706  8258  8258 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:32.709  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 12:28:32.709  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-11 12:28:32.716  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.724  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:32.731  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.732  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.732  8258  8258 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:32.735  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-11 12:28:32.738  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-11 12:28:32.740  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.749  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:28:32.756  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.757  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.757  8258  8258 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:32.766  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.766  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-11 12:28:32.781  8181  8246 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:28:32.781  8181  8246 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 12:28:32.783  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.792  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:28:32.800  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.800  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.808  8258  8258 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-11 12:28:32.809  1035  1399 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:32.809  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:32.810  1035  1399 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:32.810  1035  1399 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:32.811  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:32.812  1035  1399 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-11 12:28:32.812  1035  1458 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-11 12:28:32.812  1035  1458 D ConnectivityService: identical MTU - not setting
08-11 12:28:32.812  1035  1458 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-11 12:28:32.812  1035  1458 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-11 12:28:32.812  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:32.813  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:32.813  1035  1458 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-11 12:28:32.814  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.814  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-11 12:28:32.818  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-11 12:28:32.822  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-11 12:28:32.829  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:32.836  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.836  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.837  8258  8258 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-11 12:28:32.842  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.843  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-11 12:28:32.846  8131  8131 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-11 12:28:32.851  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-11 12:28:32.856  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 12:28:32.861  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-11 12:28:32.867  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.868  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.869  8258  8258 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-11 12:28:32.870  8258  8258 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-11 12:28:32.870  8258  8258 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-11 12:28:32.874  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-11 12:28:32.875  8181  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-11 12:28:32.878  8131  8131 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-11 12:28:32.879  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-11 12:28:32.883  6861  6861 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-11 12:28:32.890  6861  6861 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-11 12:28:32.898  8258  8258 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-11 12:28:32.898  8258  8258 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-11 12:28:32.899  8258  8258 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-11 12:28:32.899  8258  8258 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-11 12:28:32.900  8258  8258 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-11 12:28:32.903  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:32.909  8258  8258 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-11 12:28:32.911  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-11 12:28:32.912  8258  8258 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-11 12:28:32.940  8181  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-11 12:28:32.959  8181  8246 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-11 12:28:32.964  8258  8258 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 12:28:32.964  8258  8258 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 12:28:32.969  8181  8246 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-11 12:28:32.969  8181  8246 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-11 12:28:32.970  8181  8246 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-11 12:28:32.971  8181  8246 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-11 12:28:32.971  8181  8246 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-11 12:28:32.972  8258  8258 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-11 12:28:32.973  8258  8258 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-11 12:28:32.973  8258  8258 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-11 12:28:32.973  8258  8258 V SoundPool: doLoad: loading sample sampleID=1
08-11 12:28:32.974  8258  8306 V SoundPool: Start decode
08-11 12:28:32.974  8258  8306 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-11 12:28:32.974  8258  8258 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-11 12:28:32.974  8181  8246 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-11 12:28:32.975   326   326 V MediaPlayerService: decode(23, 10857164, 17813)
08-11 12:28:32.976   326   326 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-11 12:28:32.976   326   326 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-11 12:28:32.976   326   326 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,08-11 12:28:32.976   326   326 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-11 12:28:32.976   326   326 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-11 12:28:32.976   326   326 V MediaPlayerService: player type = 3
08-11 12:28:32.976   326   326 V AwesomePlayer: AwesomePlayer create()
08-11 12:28:32.977   326   326 V AwesomePlayer: reset_l() 
08-11 12:28:32.977   326   326 V AwesomePlayer: cancelPlayerEvents
08-11 12:28:32.977   326   326 V AwesomePlayer: setAudioSink() 
,08-11 12:28:32.977   326   326 V AwesomePlayer: reset_l() 
08-11 12:28:32.977   326   326 V AudioCache: notify(0xb1432300, 8, 0, 0)
08-11 12:28:32.977   326   326 V AudioCache: ignored
08-11 12:28:32.977   326   326 V AwesomePlayer: cancelPlayerEvents
08-11 12:28:32.977   326   326 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
,08-11 12:28:32.977   326   326 V AwesomePlayer: setDataSource_l dataSource
08-11 12:28:32.977   326   326 V LGParserOSAL: SniffLGParser start
,08-11 12:28:32.977   326   326 V LGParserOSAL: MainType:5, SubType=0
08-11 12:28:32.977   326   326 V LGParserOSAL: #### check Mime : application/ogg
08-11 12:28:32.977   326   326 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-11 12:28:32.977   326   326 E MediaExtractor: Use LGExtractor :application/ogg 
08-11 12:28:32.978  7644  7644 D UEI.SmartControl: QS Service created
08-11 12:28:32.979  8258  8258 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-11 12:28:32.981  8258  8258 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-11 12:28:32.981  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-11 12:28:32.987  8181  8246 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-11 12:28:32.994  8258  8258 V LGMDMManager: Create singleton instance
08-11 12:28:33.001  7644  7644 I UEI.SmartControl: Service initServices...
08-11 12:28:33.002  7644  7644 D UEI.SmartControl: QS start get config
,08-11 12:28:33.019   326   326 V LGParserOSAL: supported mime: application/ogg
08-11 12:28:33.019   326   326 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-11 12:28:33.019   326   326 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-11 12:28:33.019   326   326 V AwesomePlayer: mBitrate = -1 bits/sec
08-11 12:28:33.019   326   326 V AwesomePlayer: AudioTrack Setting
08-11 12:28:33.019   326   326 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-11 12:28:33.019   326   326 V AwesomePlayer: setAudioSource() 
08-11 12:28:33.019   326   326 V MediaPlayerService: prepare
08-11 12:28:33.019   326   326 V AwesomePlayer: prepareAsync_l() 
,08-11 12:28:33.020   326   326 V MediaPlayerService: wait for prepare
08-11 12:28:33.020   326  8308 V AwesomePlayer: onPrepareAsyncEvent() 
08-11 12:28:33.020   326  8308 V AwesomePlayer: initAudioDecoder() 
08-11 12:28:33.020   326  8308 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-11 12:28:33.020   326  8308 V AudioSystem: isOffloadSupported()
08-11 12:28:33.020   326  8308 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-11 12:28:33.020   326  8308 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-11 12:28:33.020   326  8308 I AudioFlinger: isAudioPlaybackHookOn() false
08-11 12:28:33.020   326  8308 V AwesomePlayer: getUseOffload() = 0 
08-11 12:28:33.020   326  8308 V OMXCodec: OMXCodec::Create
08-11 12:28:33.020   326  8308 V OMXCodec: findMatchingCodecs()
08-11 12:28:33.020   326  8308 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-11 12:28:33.020   326  8308 V OMXCodec: matchingCodecs.size()=1
08-11 12:28:33.020   326  8308 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-11 12:28:33.022   326  8308 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-11 12:28:33.022   326  8308 V LGCodecAdapter: LG Codec Adapter start
08-11 12:28:33.022   326  8308 V OMXCodec: OMXCodec Createtor
08-11 12:28:33.022   326  8308 V OMXCodec: setComponentRole
08-11 12:28:33.022   326  8308 V OMXCodec: configureCodec protected=0
08-11 12:28:33.022   326  8308 V LGCodecAdapter: called getLGCodecSpecificData
08-11 12:28:33.022   326  8308 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-11 12:28:33.022   326  8308 V LGCodecOSAL: Called LGconfigureCodecMETA
08-11 12:28:33.022   326  8308 V LGCodecOSAL: Called LGconfigureCodecMSG
08-11 12:28:33.022   326  8308 V LGCodecOSAL: Not support LGCodec
08-11 12:28:33.022   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-11 12:28:33.022   326  8308 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-11 12:28:33.022   326  8308 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-11 12:28:33.022   326  8308 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-11 12:28:33.022   326  8308 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-11 12:28:33.022   326  8308 V AudioSystem: isOffloadSupported()
08-11 12:28:33.022   326  8308 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-11 12:28:33.022   326  8308 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-11 12:28:33.022   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-11 12:28:33.022   326  8308 V OMXCodec: init()
08-11 12:28:33.022   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-11 12:28:33.022   326  8308 V OMXCodec: allocateBuffers
08-11 12:28:33.022   326  8308 V OMXCodec: allocateBuffersOnPort portIndex=0
08-11 12:28:33.022   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.deco,der] allocated buffer 0xb54f7ab0 on input port
08-11 12:28:33.023   326  8308 V OMXCodec: allocateBuffersOnPort portIndex=1
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-11 12:28:33.023   326  8308 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c5150 on output port
08-11 12:28:33.023   326  8308 V OMXCodec: init() mAsyncCompletion wait!!! 
08-11 12:28:33.023   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-11 12:28:33.023   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-11 12:28:33.023   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-11 12:28:33.023   326  8308 V OMXCodec: init() mAsyncCompletion wait!!! 
08-11 12:28:33.023   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-11 12:28:33.023   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-11 12:28:33.023   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-11 12:28:33.023   326  8308 V OMXCodec: init() mAsyncCompletion wait free! 
08-11 12:28:33.023   326  8308 V AwesomePlayer: finishAsyncPrepare_l() 
08-11 12:28:33.023   326  8308 V AudioCache: notify(0xb1432300, 5, 0, 0)
08-11 12:28:33.023   326  8308 V AudioCache: ignored
08-11 12:28:33.023   326  8308 V AudioCache: notify(0xb1432300, 1, 0, 0)
08-11 12:28:33.023   326  8308 V AudioCache: prepared
08-11 12:28:33.024   326   326 V AudioCache: wait - success
08-11 12:28:33.024   326   326 V MediaPlayerService: start
08-11 12:28:33.024   326   326 V AwesomePlayer: play_l() 
08-11 12:28:33.024   326   326 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-11 12:28:33.024   326   326 V AwesomePlayer: createAudioPlayer_l
08-11 12:28:33.024   326   326 V AwesomePlayer: seekAudioIfNecessary_l() 
08-11 12:28:33.024   326   326 V AwesomePlayer: startAudioPlayer_l() 
08-11 12:28:33.024   326   326 D AudioPlayer: start of Playback, useOffload 0
08-11 12:28:33.024   326   326 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-11 12:28:33.024   326   326 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-11 12:28:33.025   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044823376
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbi,s.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-11 12:28:33.026   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-11 12:28:33.027   326  8310 V OMXCodec: allocateBuffersOnPort portIndex=1
08-11 12:28:33.027   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-11 12:28:33.027   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-11 12:28:33.027   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-11 12:28:33.027   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-11 12:28:33.027   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
08-11 12:28:33.027   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-11 12:28:33.027   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-11 12:28:33.028   326   326 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-11 12:28:33.029   326   326 V AudioCache: notify(0xb1432300, 6, 0, 0)
08-11 12:28:33.029   326   326 V AudioCache: ignored
08-11 12:28:33.029   326   326 V MediaPlayerService: wait for playback complete
08-11 12:28:33.029   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.030   326  8311 V AudioCache: memcpy(0xac200000, 0xb17fb000, 4096)
08-11 12:28:33.031   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.031   326  8311 V AudioCache: memcpy(0xac201000, 0xb17fb000, 4096)
08-11 12:28:33.036   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.036   326  8311 V AudioCache: memcpy(0xac202000, 0xb17fb000, 4096)
08-11 12:28:33.037   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.037   326  8311 V AudioCache: memcpy(0xac203000, 0xb17fb000, 4096)
08-11 12:28:33.037   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.037   326  8311 V AudioCache: memcpy(0xac204000, 0xb17fb000, 4096)
08-11 12:28:33.038   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.038   326  8311 V AudioCache: memcpy(0xac205000, 0xb17fb000, 4096)
08-11 12:28:33.038   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.038   326  8311 V AudioCache: memcpy(0xac206000, 0xb17fb000, 4096)
08-11 12:28:33.039   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.039   326  8311 V AudioCache: memcpy(0xac207000, 0xb17fb000, 4096)
08-11 12:28:33.039   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.039   326  8311 V AudioCache: memcpy(0xac208000, 0xb17fb000, 4096)
08-11 12:28:33.040   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.040   326  8311 V AudioCache: memcpy(0xac209000, 0xb17fb000, 4096)
08-11 12:28:33.040   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.040   326  8311 V AudioCache: memcpy(0xac20a000, 0xb17fb000, 4096)
08-11 12:28:33.040   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.041   326  8311 V AudioCache: memcpy(0xac20b000, 0xb17fb000, 4096)
08-11 12:28:33.041   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.041   326  8311 V AudioCache: memcpy(0xac20c000, 0xb17fb000, 4096)
08-11 12:28:33.041   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.041   326  8311 V AudioCache: memcpy(0xac20d000, 0xb17fb000, 4096)
08-11 12:28:33.042   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.042   326  8311 V AudioCache: memcpy(0xac20e000, 0xb17fb000, 4096)
08-11 12:28:33.042   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.042   326  8311 V AudioCache: memcpy(0xac20f000, 0xb17fb000, 4096)
08-11 12:28:33.043   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.043   326  8311 V AudioCache: memcpy(0xac210000, 0xb17fb000, 4096)
08-11 12:28:33.045   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.045   326  8311 V AudioCache: memcpy(0xac211000, 0xb17fb000, 4096)
08-11 12:28:33.046   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.046   326  8311 V AudioCache: memcpy(0xac212000, 0xb17fb000, 4096)
08-11 12:28:33.046   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.046   326  8311 V AudioCache: memcpy(0xac213000, 0xb17fb000, 4096)
08-11 12:28:33.047   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.047   326  8311 V AudioCache: memcpy(0xac214000, 0xb17fb000, 4096)
08-11 12:28:33.047   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.047   326  8311 V AudioCache: memcpy(0xac215000, 0xb17fb000, 4096)
08-11 12:28:33.048   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.048   326  8311 V AudioCache: memcpy(0xac216000, 0xb17fb000, 4096)
08-11 12:28:33.048   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.048   326  8311 V AudioCache: memcpy(0xac217000, 0xb17fb000, 4096)
08-11 12:28:33.048   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.048   326  8311 V AudioCache: memcpy(0xac218000, 0xb17fb000, 4096)
08-11 12:28:33.049   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.049   326  8311 V AudioCache: memcpy(0xac219000, 0xb17fb000, 4096)
08-11 12:28:33.049   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.049   326  8311 V AudioCache: memcpy(0xac21a000, 0xb17fb000, 4096)
08-11 12:28:33.049   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.049   326  8311 V AudioCache: memcpy(0xac21b000, 0xb17fb000, 4096)
08-11 12:28:33.050   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.050   326  8311 V AudioCache: memcpy(0xac21c000, 0xb17fb000, 4096)
08-11 12:28:33.050   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.050   326  8311 V AudioCache: memcpy(0xac21d000, 0xb17fb000, 4096)
08-11 12:28:33.050   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.050   326  8311 V AudioCache: memcpy(0xac21e000, 0xb17fb000, 4096)
08-11 12:28:33.050   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.050   326  8311 V AudioCache: memcpy(0xac21f000, 0xb17fb000, 4096)
08-11 12:28:33.051   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.051   326  8311 V AudioCache: memcpy(0xac220000, 0xb17fb000, 4096)
08-11 12:28:33.052   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.052   326  8311 V AudioCache: memcpy(0xac221000, 0xb17fb000, 4096)
08-11 12:28:33.052   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.052   326  8311 V AudioCache: memcpy(0xac222000, 0xb17fb000, 4096)
08-11 12:28:33.052   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.052   326  8311 V AudioCache: memcpy(0xac223000, 0xb17fb000, 4096)
08-11 12:28:33.053   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.053   326  8311 V AudioCache: memcpy(0xac224000, 0xb17fb000, 4096)
08-11 12:28:33.053   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.053   326  8311 V AudioCache: memcpy(0xac225000, 0xb17fb000, 4096)
08-11 12:28:33.053   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.053   326  8311 V AudioCache: memcpy(0xac226000, 0xb17fb000, 4096)
08-11 12:28:33.053   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.053   326  8311 V AudioCache: memcpy(0xac227000, 0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: memcpy(0xac228000, 0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: memcpy(0xac229000, 0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.054,   326  8311 V AudioCache: memcpy(0xac22a000, 0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: memcpy(0xac22b000, 0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.054   326  8311 V AudioCache: memcpy(0xac22c000, 0xb17fb000, 4096)
08-11 12:28:33.055   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.055   326  8311 V AudioCache: memcpy(0xac22d000, 0xb17fb000, 4096)
08-11 12:28:33.055   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.055   326  8311 V AudioCache: memcpy(0xac22e000, 0xb17fb000, 4096)
08-11 12:28:33.055   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.055   326  8311 V AudioCache: memcpy(0xac22f000, 0xb17fb000, 4096)
08-11 12:28:33.056   326  8311 V Au,dioCache: write(0xb17fb000, 4096)
08-11 12:28:33.056   326  8311 V AudioCache: memcpy(0xac230000, 0xb17fb000, 4096)
08-11 12:28:33.056   326  8311 V AudioCache: write(0xb17fb000, 4096)
08-11 12:28:33.056   326  8311 V AudioCache: memcpy(0xac231000, 0xb17fb000, 4096)
08-11 12:28:33.056   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-11 12:28:33.056   326  8311 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-11 12:28:33.056   326  8311 V AwesomePlayer: postAudioEOS() 
08-11 12:28:33.056   326  8311 V AudioCache: write(0xb17fb000, 280)
08-11 12:28:33.056   326  8311 V AudioCache: memcpy(0xac232000, 0xb17fb000, 280)
08-11 12:28:33.059   326  8308 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-11 12:28:33.059   326  8308 V AwesomePlayer: onStreamDone
08-11 12:28:33.059   326  8308 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-11 12:28:33.059   326  8308 V AudioCache: notify(0xb1432300, 2, 0, 0)
08-11 12:28:33.059   326  8308 V AudioCache: playback complete
08-11 12:28:33.059   326  8308 V AwesomePlayer: pause_l() 
08-11 12:28:33.059   326  8308 V AudioCache: notify(0xb1432300, 7, 0, 0)
08-11 12:28:33.059   326  8308 V AudioCache: ignored
08-11 12:28:33.059   326  8308 V AwesomePlayer: cancelPlayerEvents
08-11 12:28:33.059   326   326 V AudioCache: wait - success
08-11 12:28:33.059   326   326 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-11 12:28:33.059   326  8308 D AudioPlayer: Pause Playback at 1068125
08-11 12:28:33.059   326   326 V AwesomePlayer: reset_l() 
08-11 12:28:33.059   326   326 V AudioCache: notify(0xb1432300, 8, 0, 0)
08-11 12:28:33.059   326   326 V AudioCache: ignored
08-11 12:28:33.059   326   326 V AwesomePlayer: cancelPlayerEvents
08-11 12:28:33.059   326   326 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-11 12:28:33.059   326   326 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-11 12:28:33.059   326   326 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-11 12:28:33.059   326   326 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-11 12:28:33.059   326   326 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-11 12:28:33.059   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-11 12:28:33.060   326   326 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-11 12:28:33.060   326   326 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-11 12:28:33.060   326  8310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-11 12:28:33.060   326   326 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-11 12:28:33.060   326   326 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-11 12:28:33.060   326   326 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-11 12:28:33.060   326   326 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-11 12:28:33.061   326   326 D AudioPlayer: AudioPlayer releasing audio source
08-11 12:28:33.061   326   326 D AudioPlayer: AudioPlayer done releasing audio source
08-11 12:28:33.061   326   326 V AwesomePlayer: reset_l() 
08-11 12:28:33.061   326   326 V AwesomePlayer: cancelPlayerEvents
08-11 12:28:33.061   326   326 V AwesomePlayer: ~AwesomePlayer call
08-11 12:28:33.061   326   326 V AwesomePlayer: reset_l() 
08-11 12:28:33.061   326   326 V AwesomePlayer: cancelPlayerEvents
08-11 12:28:33.061  8258  8306 V SoundPool: close(31)
08-11 12:28:33.061  8258  8306 V SoundPool: pointer = 0x9ffe0000, size = 205080, sampleRate = 48000, numChannels = 2
08-11 12:28:33.065  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-11 12:28:33.067  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-11 12:28:33.069  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1241
08-11 12:28:33.072  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.073  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.075  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.076  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.077  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.079  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.080  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.081  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.083  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-11 12:28:33.084  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-11 12:28:33.293  7644  7644 I UEI.SmartControl: Supports setup maps: true
,08-11 12:28:33.296  7644  7644 D UEI.SmartControl: QS start statue = true Error code = 0
08-11 12:28:33.296  7644  7644 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-11 12:28:33.296  7644  7644 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-11 12:28:33.296  7644  7644 I UEI.SmartControl: ### init IR Blaster...
,08-11 12:28:33.300  7644  7644 D serial_port: Configuring serial port
08-11 12:28:33.300  7644  7644 E UEI.SmartControl: UEIBLaster setting for 616
08-11 12:28:33.300  7644  7644 I UEI.SmartControl: Setting serial record hearder size = 2
08-11 12:28:33.300  7644  7644 I UEI.SmartControl: configuring settings for MAXQ616
08-11 12:28:33.300  7644  7644 I UEI.SmartControl: Get version...
08-11 12:28:33.323  7644  8315 D UEI.SmartControl: serial port data available: 21
,08-11 12:28:33.349  7644  7644 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-11 12:28:33.349  7644  7644 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-11 12:28:33.349  7644  7644 I UEI.SmartControl: QS saving settings...
08-11 12:28:33.351  7644  7644 D UEI.SmartControl: IR Blaster version: 25672567
,08-11 12:28:33.367  7644  8315 D UEI.SmartControl: serial port data available: 4
,08-11 12:28:33.400  7644  8324 I UEI.SmartControl: Device manager: loading config....
,08-11 12:28:33.401  7644  8324 D UEI.SmartControl: ----------- loading internal config...
,08-11 12:28:33.402  7644  7644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-11 12:28:33.405  7644  7644 E UEI.SmartControl: Services init done
,08-11 12:28:33.405  7644  7644 D UEI.SmartControl: QS Service init finished
,08-11 12:28:33.411  7644  7644 D UEI.SmartControl: QS Service version name: 2.1.91
,08-11 12:28:33.411  7644  7644 D UEI.SmartControl: QS Service version code: 201091,
,08-11 12:28:33.413  7644  7644 D UEI.SmartControl: Service requested: Control
,08-11 12:28:33.421  7644  8324 E UEI.SmartControl: Loading SETTINGS...
,08-11 12:28:33.424  7644  7644 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-11 12:28:33.429  7644  7644 D UEI.SmartControl: Internal service binding...
08-11 12:28:33.429  8258  8258 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-11 12:28:33.430  7644  7659 I UEI.SmartControl: ------ IControl API: 11
08-11 12:28:33.430  7644  7659 D UEI.SmartControl: File observer start...
08-11 12:28:33.431  7644  7659 E UEI.SmartControl: IR Port is disabled: false
08-11 12:28:33.432  7644  7659 D UEI.SmartControl: Starting file observer...
08-11 12:28:33.432  7644  7659 I UEI.SmartControl: Registering callback...
08-11 12:28:33.432  7644  7660 I UEI.SmartControl: ------ IControl API: 19
08-11 12:28:33.433  7644  7660 I UEI.SmartControl: Registering Services Ready callback...
08-11 12:28:33.435  7644  8324 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-11 12:28:33.448  7644  8323 I UEI.SmartControl: Notify AllClients services are ready: 0
08-11 12:28:33.449  8258  8274 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-11 12:28:33.450  8258  8303 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-11 12:28:33.450  8258  8303 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-11 12:28:33.451  8258  8258 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,08-11 12:28:33.451  8258  8258 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-11 12:28:33.452  7644  8323 D UEI.SmartControl: -----service ready thread exits
08-11 12:28:33.453  7644  7659 I UEI.SmartControl: ------ IControl API: 8
08-11 12:28:33.454  8258  8258 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-11 12:28:33.455  8258  8258 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-11 12:28:33.455  8258  8258 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-11 12:28:33.455  8258  8258 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-11 12:28:33.456  8258  8258 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-11 12:28:33.456  8258  8258 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-11 12:28:33.458  8258  8258 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-11 12:28:33.460  8258  8258 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-11 12:28:33.461  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-11 12:28:33.462  8258  8258 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-11 12:28:33.462  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-11 12:28:33.465  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-11 12:28:33.466  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-11 12:28:33.467  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-11 12:28:33.468  8258  8258 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470911313467]
08-11 12:28:33.469  8258  8258 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-11 12:28:33.471  1035  1050 I ActivityManager: Killing 7205:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-11 12:28:33.494  8258  8326 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-11 12:28:33.580  1035  1716 W libprocessgroup: failed to open /acct/uid_10093/pid_7205/cgroup.procs: No such file or directory
,08-11 12:28:33.591  8258  8258 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-11 12:28:33.592  8258  8258 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-11 12:28:33.593  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-11 12:28:33.593  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-11 12:28:33.593  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-11 12:28:33.594  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-11 12:28:33.594  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-11 12:28:33.612  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-11 12:28:34.426  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 12:28:34.426  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-11 12:28:34.446  1035  1445 D WifiController: battery changed pluggedType: 2
,08-11 12:28:34.451  1942  2071 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 12:28:34.451  1942  2071 D LEDHandler: Battery Level Remaining: 100%
08-11 12:28:34.452  1942  2071 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
08-11 12:28:34.453  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
08-11 12:28:34.453  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 12:28:34.455  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 12:28:34.457  7924  7978 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 12:28:34.458  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:28:34.458  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:34.463  8157  8157 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-11 12:28:34.700  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=70.0, 0.0, 0.0  rx=72.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:2032499468] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:34.703  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=70.0, 0.0, 0.0  rx=72.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2032499471] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:34.703  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 12:28:34.721  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-11 12:28:34.750  1035  1438 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-11 12:28:34.774  1035  1458 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:34.788  1035  1109 D Tethering: MasterInitialState.processMessage what=3
,08-11 12:28:34.819  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:34.819  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:34.819  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:34.819  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:34.819  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:34.819  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:34.819  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:34.819  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:28:34.825  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:34.830  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:28:34.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:34.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:34.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:34.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:34.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:34.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:34.830  6630  6630 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:34.831  6630  6630 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:34.835  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:34.842  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-11 12:28:34.846  5755  5755 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-11 12:28:34.877  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-11 12:28:34.887  8181  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-11 12:28:34.901  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:28:34.921  1035  1978 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-11 12:28:34.923  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:34.923  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:34.924  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-11 12:28:34.924  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:34.924  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-11 12:28:34.925   322  8333 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 12:28:34.925   322  8333 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-11 12:28:34.933  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-11 12:28:34.933  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:34.933  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-11 12:28:34.938  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-11 12:28:34.945  6630  8224 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-11 12:28:34.945  6630  8224 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-11 12:28:34.945  6630  8224 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:34.945  6630  8224 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:34.946  6630  8224 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 12:28:34.950  6630  8334 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-11 12:28:34.950  6630  8334 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 12:28:34.950  6630  8334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:34.950  6630  8334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:34.950  6630  8334 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 12:28:34.954  6630  8337 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 857, name: OutgoingSocketThread/Receiver)
08-11 12:28:34.955  6630  8337 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 857, thread name: OutgoingSocketThread/Receiver)
08-11 12:28:34.955  6630  8337 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 12:28:34.955  6630  8337 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 857, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-11 12:28:34.963  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 10:28:34 GMT], X-Android-Received-Millis=[1470911314962], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470911314932]}
08-11 12:28:34.963  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-11 12:28:34.963  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-11 12:28:34.967   322  8333 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-11 12:28:34.974  1035  1458 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-11 12:28:34.975  1035  1458 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-11 12:28:34.975  1035  1458 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:34.975  1035  1458 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:34.975  1035  1458 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 12:28:34.975  1035  1458 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-11 12:28:34.975  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-11 12:28:34.975  1035  1458 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-11 12:28:34.976  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:34.976  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:34.977  6630  8339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 859, name: IncomingSocketThread/Receiver)
08-11 12:28:34.978  6630  8339 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 859, thread name: IncomingSocketThread/Receiver)
08-11 12:28:34.978  6630  8339 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-11 12:28:34.978  6630  8339 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 859, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-11 12:28:34.980  6630  8338 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 858, name: IncomingSocketThread/Sender)
08-11 12:28:34.981  6630  8336 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 856, name: OutgoingSocketThread/Sender)
08-11 12:28:34.981  1035  1458 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:34.982  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-11 12:28:34.985  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2bb2835e
08-11 12:28:34.985  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-11 12:28:34.985  7061  7061 D AppUp4:CustFacade: isPhone : true
08-11 12:28:34.986  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-11 12:28:34.987  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-11 12:28:34.990  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:34.991  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-11 12:28:34.992  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-11 12:28:34.995  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-11 12:28:34.999  3526  3526 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:35.002  3526  3526 V DownloadManager: DownloadService onCreate
08-11 12:28:35.003  4321  8356 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-11 12:28:35.004  3526  8357 I DownloadManager: in removeSpuriousFiles
08-11 12:28:35.004  3526  8357 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-11 12:28:35.005  4321  8359 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:35.005  4321  8359 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-11 12:28:35.006  4321  8356 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,08-11 12:28:35.013  3526  8357 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@36c31122 on behalf of 3526
08-11 12:28:35.013  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-11 12:28:35.014  3526  8357 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-11 12:28:35.016  3526  8357 I DownloadManager: in trimDatabase
08-11 12:28:35.016  3526  8357 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-11 12:28:35.017  3526  8357 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3db09170 on behalf of 3526
,08-11 12:28:35.042  1035  1892 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8362 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-11 12:28:35.045  3526  3526 V DownloadManager: DownloadService onStartCommand
,08-11 12:28:35.045  3526  8358 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-11 12:28:35.048  4321  8356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-11 12:28:35.051  4321  4321 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-11 12:28:35.052  4321  4321 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-11 12:28:35.053  4321  4321 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-11 12:28:35.054  3526  8358 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a51d6e on behalf of 3526
08-11 12:28:35.055  4321  4321 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-11 12:28:35.056  3526  8358 V DownloadManager: processing inserted download 1
08-11 12:28:35.060  4321  4321 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-11 12:28:35.064  3526  8358 V DownloadManager: processing inserted download 4
08-11 12:28:35.066  3526  8358 V DownloadManager: processing inserted download 7
08-11 12:28:35.067  3526  8358 V DownloadManager: processing inserted download 8
,08-11 12:28:35.068  3526  8358 V DownloadManager: processing inserted download 9
08-11 12:28:35.069  3526  8358 V DownloadManager: processing inserted download 10
08-11 12:28:35.070  3526  8358 V DownloadManager: processing inserted download 11
08-11 12:28:35.071  3526  8358 V DownloadManager: processing inserted download 12
08-11 12:28:35.072  3526  8358 V DownloadManager: processing inserted download 13
08-11 12:28:35.073  3526  8358 V DownloadManager: processing inserted download 14
08-11 12:28:35.074  3526  8358 V DownloadManager: processing inserted download 16
08-11 12:28:35.082  3526  3526 V DownloadManager: DownloadService onDestroy
,08-11 12:28:35.099  8362  8362 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:35.100  8362  8362 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 12:28:35.101  8362  8362 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-11 12:28:35.102  8362  8362 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 12:28:35.198  8362  8362 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 12:28:35.210  8362  8362 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-11 12:28:35.245  8362  8362 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 12:28:35.270  8362  8362 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 12:28:35.271  8362  8362 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:35.417  8362  8362 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-11 12:28:35.471  8362  8362 I HubEmail: JNI_OnLoad()
,08-11 12:28:35.471  8362  8362 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 12:28:35.471  8362  8362 I HubEmail: registerNatives()
08-11 12:28:35.471  8362  8362 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 12:28:35.471  8362  8362 I HubEmail: registerNativeMethods()
08-11 12:28:35.471  8362  8362 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-11 12:28:35.471  8362  8362 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-11 12:28:35.490  8362  8395 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:28:35.510  3477  3477 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-11 12:28:35.510  3477  3477 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-11 12:28:35.510  3477  3477 I LgeMiscReceiver: networkInfo.isConnected() = true
08-11 12:28:35.510  3477  3477 D PhoneState: setPdpRejectCasuse : false
,08-11 12:28:35.537   322  8398 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-11 12:28:35.539   322  8398 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-11 12:28:35.551  1035  1892 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8399 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-11 12:28:35.600   322  8398 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
08-11 12:28:35.644  8107  8394 V FormManager: There are no updated forms. The schedule will be deleted.
,08-11 12:28:35.649  8107  8394 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-11 12:28:35.664  8399  8399 D LgDataFeature: LgDataFeature() Constructor: none
08-11 12:28:35.664  8399  8399 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:35.668  8399  8399 D PhoneMonitor: Register our PhoneStateListener
08-11 12:28:35.674  1035  1051 I ActivityManager: Killing 7705:com.google.android.talk/u0a72 (adj 15): empty #17
08-11 12:28:35.702  1035  2032 W libprocessgroup: failed to open /acct/uid_10072/pid_7705/cgroup.procs: No such file or directory
,08-11 12:28:35.709  8399  8399 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-11 12:28:35.712  8399  8399 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-11 12:28:35.724  8399  8399 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-11 12:28:35.724  8399  8399 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-11 12:28:35.725  8399  8399 D TelephonyAutoProfiling: [parse] Load xml
08-11 12:28:35.729  8399  8399 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-11 12:28:35.729  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-11 12:28:35.729  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-11 12:28:35.729  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,08-11 12:28:35.729  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-11 12:28:35.729  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-11 12:28:35.729  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-11 12:28:35.729  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
,08-11 12:28:35.734  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-11 12:28:35.735  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-11 12:28:35.735  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-11 12:28:35.735  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-11 12:28:35.735  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-11 12:28:35.735  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-11 12:28:35.735  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-11 12:28:35.735  8399  8399 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-11 12:28:35.735  8399  8399 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-11 12:28:35.749  8399  8399 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-11 12:28:35.768  1035  1960 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8424 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-11 12:28:35.771  1035  1960 I ActivityManager: Killing 7751:com.android.contacts/u0a19 (adj 15): empty #17
08-11 12:28:35.819  1035  1892 W libprocessgroup: failed to open /acct/uid_10019/pid_7751/cgroup.procs: No such file or directory
,08-11 12:28:35.859  1817  8441 I CheckinService: active receiver: disabled
,08-11 12:28:35.961   322  8443 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-11 12:28:35.966   322  8443 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-11 12:28:35.999   322  8443 D libc-netbsd: res_queryN name = www.google.com succeed
,08-11 12:28:36.007   322  8445 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-11 12:28:36.008   322  8445 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-11 12:28:36.009   322  8445 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-11 12:28:36.044  1035  1050 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8446 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-11 12:28:36.044  1035  1050 I ActivityManager: Killing 7774:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-11 12:28:36.063  1035  1439 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-11 12:28:36.098  1035  2033 W libprocessgroup: failed to open /acct/uid_10027/pid_7774/cgroup.procs: No such file or directory
,08-11 12:28:36.245  1035  1716 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8463 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-11 12:28:36.249  1035  1716 I ActivityManager: Killing 7793:com.android.vending/u0a44 (adj 15): empty #17
08-11 12:28:36.271   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 472us total 25.912ms
,08-11 12:28:36.293   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 21.931ms
,08-11 12:28:36.315   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 21.172ms
,08-11 12:28:36.327  1035  2033 W libprocessgroup: failed to open /acct/uid_10044/pid_7793/cgroup.procs: No such file or directory
,08-11 12:28:36.360  8463  8463 I art     : Almond Protected OAT
,08-11 12:28:36.417  8463  8463 D WeatherApplication: removeAccount
,08-11 12:28:36.419  8463  8463 D WeatherApplication: Account.length = 0
08-11 12:28:36.419  8463  8463 E WeatherApplication: OPERATOR:OPEN
08-11 12:28:36.424  8463  8463 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:36
08-11 12:28:36.428  8463  8463 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-11 12:28:36.428  8463  8463 D Weather.Utils: 2 : All the weather widget is gone.
08-11 12:28:36.430  8463  8463 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-11 12:28:36.433  8463  8463 D WeatherAncestor: connectivity changed - connection : true
,08-11 12:28:36.434  8463  8463 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-11 12:28:36.447  8463  8463 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-11 12:28:36.447  8463  8463 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-11 12:28:36.447  8463  8463 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-11 12:28:36.469  8463  8463 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-11 12:28:36.469  8463  8463 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:36
,08-11 12:28:36.545  1035  1050 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8481 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-11 12:28:36.547  1035  1050 I ActivityManager: Killing 7839:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-11 12:28:36.628  1035  1051 W libprocessgroup: failed to open /acct/uid_10080/pid_7839/cgroup.procs: No such file or directory
,08-11 12:28:36.723   278   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-11 12:28:36.723   278   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-11 12:28:36.723   278   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 12:28:36.724  8481  8502 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-11 12:28:36.728   278   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-11 12:28:36.728   278   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-11 12:28:36.729   278   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 12:28:36.729  8481  8502 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-11 12:28:36.766   278   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-11 12:28:36.767   278   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-11 12:28:36.767   278   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 12:28:36.767  8481  8506 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-11 12:28:36.769   278   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-11 12:28:36.769   278   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-11 12:28:36.769   278   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-11 12:28:36.770  8481  8506 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-11 12:28:36.969  8481  8481 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-11 12:28:36.980  8481  8481 I LibraryLoader: Loading: webviewchromium
,08-11 12:28:36.984  8481  8481 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 913-917)
08-11 12:28:36.984  8481  8481 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 12:28:36.991  8481  8481 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9e6d41}
08-11 12:28:36.992  8481  8481 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:28:36.993  8481  8481 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 12:28:37.019  8481  8481 I BrowserStartupController: Initializing chromium process, renderers=0
,08-11 12:28:37.022  8481  8481 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:28:37.035  8481  8481 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-11 12:28:37.036  8481  8481 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-11 12:28:37.039  8481  8481 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-11 12:28:37.042   326  1398 V AudioPolicyService: registerClient() client 0xb558a960, uid 10093
08-11 12:28:37.043  8481  8526 W AudioManagerAndroid: Requires BLUETOOTH permission
08-11 12:28:37.061  8481  8481 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:28:37.061  8481  8481 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:28:37.061  8481  8481 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:28:37.061  8481  8481 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:28:37.061  8481  8481 I Adreno-EGL: Remote Branch: 
08-11 12:28:37.061  8481  8481 I Adreno-EGL: Local Patches: 
08-11 12:28:37.061  8481  8481 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:28:37.217  1035  1960 I art     : Explicit concurrent mark sweep GC freed 77384(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.203ms total 162.774ms
,08-11 12:28:37.245  8481  8481 I NSApplication: Starting up...
,08-11 12:28:37.271  1035  1960 I ActivityManager: Killing 7568:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-11 12:28:37.303  1035  1577 W libprocessgroup: failed to open /acct/uid_10037/pid_7568/cgroup.procs: No such file or directory
,08-11 12:28:37.325  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-11 12:28:37.678  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{fc88ba5 type 2 when 191590 com.google.android.gms} when 191590
,08-11 12:28:37.731  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=39.5, 0.0, 0.0  rx=39.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2032502499] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:37.732  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=39.5, 0.0, 0.0  rx=39.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:2032502500] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:37.732  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 12:28:37.743  1817  1817 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-11 12:28:37.748  2214  2214 I ConfigService: onCreate
,08-11 12:28:37.754  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-11 12:28:37.756  1817  8551 I ConfigFetchService: running network task: configservice_periodic
08-11 12:28:37.765  1817  8551 I ConfigFetchService: launchTask
,08-11 12:28:37.768  2214  2214 I ConfigService: onBind returning update interface
08-11 12:28:37.771  1817  1817 I ConfigFetchService: service connected
08-11 12:28:37.771  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 12:28:37.771  2214  2214 I ConfigService: onBind returning config service
08-11 12:28:37.773  1817  1817 I ConfigClient: service connected
08-11 12:28:37.819  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:28:37.832  1817  2372 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-11 12:28:37.838   322  8554 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-11 12:28:37.838   322  8554 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-11 12:28:37.880   322  8554 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-11 12:28:37.930  6630  6760 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-11 12:28:37.931  6630  6760 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-11 12:28:37.933  6630  6760 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2da24b10 Bundle[{}]
08-11 12:28:37.934  6630  6760 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 12:28:37.934  6630  6760 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-11 12:28:37.935  6630  6760 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-11 12:28:37.935  6630  6760 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-11 12:28:37.936  6630  6760 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-11 12:28:37.942  6630  6760 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-11 12:28:37.949  6630  6760 I System.out: Running OutgoingSocketThread
08-11 12:28:37.954  6630  8555 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-11 12:28:37.954  6630  8555 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 12:28:38.152  1817  2372 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-11 12:28:38.162  1817  1817 I ConfigFetchService: fetch service done; releasing wakelock
,08-11 12:28:38.165  1817  1817 I ConfigFetchService: stopping self
08-11 12:28:38.217  2214  2214 I ConfigService: onDestroy
,08-11 12:28:38.400  7644  8325 D UEI.SmartControl: Internal timer expired: 2
,08-11 12:28:38.400  7644  8325 D UEI.SmartControl: unbind internal service
,08-11 12:28:38.476  7644  8319 D serial_port: close(fd = 24)
,08-11 12:28:38.485  7644  8319 I UEI.SmartControl: Serial port is closed.
,08-11 12:28:40.760  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=29.8, 0.0, 0.0  rx=27.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:2032505527] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:40.763  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=29.8, 0.0, 0.0  rx=27.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2032505530] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:40.763  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 12:28:40.967  6630  8555 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-11 12:28:40.968  6630  8555 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-11 12:28:40.968  6630  8555 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:40.968  6630  8555 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:40.968  6630  8555 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 12:28:40.974  6630  8556 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-11 12:28:40.974  6630  8556 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 12:28:40.974  6630  8556 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:40.975  6630  8556 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:40.975  6630  8556 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 12:28:40.978  6630  8559 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: OutgoingSocketThread/Receiver)
08-11 12:28:40.978  6630  8559 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 869, thread name: OutgoingSocketThread/Receiver)
08-11 12:28:40.978  6630  8559 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 12:28:40.978  6630  8559 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 869, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-11 12:28:40.980  6630  8558 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: OutgoingSocketThread/Sender)
08-11 12:28:40.981  6630  8561 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: IncomingSocketThread/Receiver)
08-11 12:28:40.982  6630  8561 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 871, thread name: IncomingSocketThread/Receiver)
08-11 12:28:40.982  6630  8561 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-11 12:28:40.982  6630  8561 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-11 12:28:40.984  6630  8560 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: IncomingSocketThread/Sender)
,08-11 12:28:41.763  8481  8504 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-11 12:28:43.788  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=21.9, 0.0, 0.0  rx=19.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2032508556] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:43.791  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=21.9, 0.0, 0.0  rx=19.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2032508559] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:43.791  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 12:28:43.969  6630  6760 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 880)
,08-11 12:28:43.970  6630  6760 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-11 12:28:43.970  6630  6760 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 881)
08-11 12:28:43.973  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:28:43.973  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@250f78eb added. We now have 3 listener(s)
,08-11 12:28:43.979  1035  1651 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:28:43.982  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:28:43.982  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:28:43.982  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:28:43.982  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:28:43.982  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f304648 added. We now have 4 listener(s)
08-11 12:28:43.982  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:28:43.983  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:28:43.987  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:28:43.991  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:28:43.991  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:43.991  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:43.991  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:43.991  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:43.991  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:43.991  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:43.991  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:28:43.997  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:43.997  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:28:43.999  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:44.001  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:44.001  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:28:44.001  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:28:44.001  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:28:44.002  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:44.002  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:44.002  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:44.002  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 12:28:44.002  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@250f78eb removed from the list
08-11 12:28:44.002  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:44.002  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f304648 removed from the list
08-11 12:28:44.002  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:28:44.002  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:44.003  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:44.003  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:44.007  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:44.007  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:44.007  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:44.007  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f304648 not in the list
08-11 12:28:44.007  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:44.007  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:28:44.011  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:44.011  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:44.011  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:44.011  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f304648 not in the list
08-11 12:28:44.011  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:44.011  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:44.011  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:44.012  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@250f78eb not in the list
08-11 12:28:44.012  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:28:44.012  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2803a06 added. We now have 3 listener(s)
08-11 12:28:44.013  1035  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:44.016  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:28:44.016  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:28:44.016  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:28:44.016  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:28:44.016  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eab8c7 added. We now have 4 listener(s)
08-11 12:28:44.016  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:28:44.018  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:28:44.022  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:28:44.028  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:28:44.028  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:44.028  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:44.028  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:44.028  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:44.028  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:44.028  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:44.028  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:44.031  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:44.031  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:28:44.033  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:44.035  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:44.037  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:28:44.037  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 12:28:44.037  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 12:28:44.037  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:28:44.037  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 12:28:44.041  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 12:28:44.042  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:44.047  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 12:28:44.050  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 12:28:44.051  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 12:28:44.052  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:44.053  6630  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-11 12:28:44.054  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:28:44.054  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:28:44.397  1035  1399 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-11 12:28:44.398  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-11 12:28:44.398  1035  1399 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-11 12:28:44.398  1035  1399 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-11 12:28:44.399  1035  1399 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-11 12:28:44.399  1035  1399 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-11 12:28:46.820  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=11.9, 0.0, 0.0  rx=9.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:2032511588] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:46.823  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=11.9, 0.0, 0.0  rx=9.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2032511591] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:46.823  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 12:28:47.056  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:28:47.056  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:28:47.056  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:28:47.068  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:47.068  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:47.068  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:47.068  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 12:28:47.068  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2803a06 removed from the list
08-11 12:28:47.068  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:47.068  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eab8c7 removed from the list
08-11 12:28:47.068  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:28:47.068  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:47.069  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:47.069  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:47.071  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:47.071  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:47.071  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:28:47.071  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:28:47.071  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:47.071  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eab8c7 not in the list
08-11 12:28:47.071  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:47.072  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:47.073  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:47.075  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:28:47.075  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:28:47.075  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:47.075  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:47.075  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eab8c7 not in the list
08-11 12:28:47.075  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:47.075  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:47.075  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:47.075  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2803a06 not in the list
08-11 12:28:47.076  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:28:47.076  6630  67,60 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36501a63 added. We now have 3 listener(s)
08-11 12:28:47.077  1035  1651 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:28:47.084  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:28:47.084  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:28:47.084  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:28:47.084  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:28:47.084  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b79660 added. We now have 4 listener(s)
08-11 12:28:47.084  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:28:47.085  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:28:47.090  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:28:47.096  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:28:47.096  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:47.096  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:47.096  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:47.096  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:47.096  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:47.096  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:47.096  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:47.097  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:47.098  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:28:47.101  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:47.103  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:28:47.105  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 12:28:47.107  6630  6760 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-11 12:28:47.108  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-11 12:28:47.110  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 12:28:47.110  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-11 12:28:47.110  6630  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 12:28:47.110  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:28:47.113  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 12:28:47.113  6630  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 12:28:47.114  6630  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 12:28:47.114  6630  6630 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-11 12:28:47.117  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 12:28:47.118  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-11 12:28:47.118  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:28:47.118  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 12:28:47.122  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 12:28:47.123  1035  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:47.130  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 12:28:47.132  1035  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 12:28:47.133  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 12:28:47.136  6630  8564 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 12:28:47.137  7924  7941 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,08-11 12:28:47.137  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 12:28:47.138  6630  8564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-11 12:28:47.138  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 12:28:47.140  6630  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
08-11 12:28:49.853  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:2032514621] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:49.870  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:17] from screen [on:0 period:2032514638] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:49.870  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-11 12:28:50.141  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:28:50.141  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:28:50.142  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 12:28:50.142  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections,
,08-11 12:28:50.142  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-11 12:28:50.142  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,08-11 12:28:50.159  6630  8564 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-11 12:28:50.159  6630  8564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 12:28:50.159  6630  8564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 12:28:50.161  6630  6630 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 12:28:50.162  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:50.162  6630  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 12:28:50.162  6630  6630 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 12:28:50.162  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 12:28:50.162  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:50.162  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:50.165  6630  6630 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:28:50.165  6630  6630 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-11 12:28:50.165  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:50.165  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:50.165  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:50.165  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 12:28:50.165  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36501a63 removed from the list
08-11 12:28:50.166  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:50.166  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b79660 removed from the list
08-11 12:28:50.166  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:28:50.166  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:50.167  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:50.167  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:50.168  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:28:50.168  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:50.168  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:28:50.168  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:28:50.168  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:28:50.168  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b79660 not in the list
08-11 12:28:50.169  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:50.169  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:28:50.175  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:50.178  6630  6760 D BluetoothLeScanner: could not find callback wrapper
08-11 12:28:50.178  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:28:50.178  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:50.178  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:50.178  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b79660 not in the list
08-11 12:28:50.178  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:50.178  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:50.178  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:50.178  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36501a63 not in the list
08-11 12:28:50.179  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:28:50.179  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f6fb88c added. We now have 3 listener(s)
08-11 12:28:50.180  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:50.183  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:28:50.183  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:28:50.183  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:28:50.183  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:28:50.184  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15146bd5 added. We now have 4 listener(s)
08-11 12:28:50.184  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:28:50.188  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:28:50.193  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:28:50.197  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:28:50.197  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:50.197  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:50.197  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:50.197  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:50.197  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:50.197  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:50.197  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:28:50.201  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:50.201  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:28:50.205  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:50.207  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:50.208  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:28:50.208  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 12:28:50.208  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 12:28:50.208  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:28:50.208  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 12:28:50.211  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 12:28:50.214  1035  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:50.219  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-11 12:28:50.220  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 12:28:50.222  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 12:28:50.222  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:50.224  6630  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-11 12:28:51.705  1035  1379 V AlarmManager: RTC_WAKEUP set : Alarm{391b90e7 type 0 when 1470911316578 com.google.android.gms} when 1470911316578
,08-11 12:28:51.733  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{15837b3d type 2 when 205173 com.google.android.gms} when 205173
,08-11 12:28:51.747   322  8567 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-11 12:28:51.750   322  8567 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-11 12:28:51.750   322  8567 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-11 12:28:51.753  8258  8258 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-11 12:28:51.753  8258  8258 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1241
,08-11 12:28:51.777  1817  8566 I CheckinService: active receiver: enabled
,08-11 12:28:51.836  1817  8566 I CheckinService: Preparing to send checkin request
08-11 12:28:51.836  1817  8566 I EventLogService: Accumulating logs since 1470911284532
,08-11 12:28:51.912  1817  8566 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-11 12:28:51.967  2214  4161 I art     : Explicit concurrent mark sweep GC freed 10629(708KB) AllocSpace objects, 8(128KB) LOS objects, 52% free, 29MB/61MB, paused 1.308ms total 26.447ms
,08-11 12:28:52.009  2214  8581 D GCM     : Connected
,08-11 12:28:52.057  1035  1051 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8582 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-11 12:28:52.079  2214  8581 D GCM     : Message class com.google.e.a.a.q
,08-11 12:28:52.141  8582  8582 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-11 12:28:52.141  8582  8582 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-11 12:28:52.174  8582  8582 I MultiDex: VM with version 2.1.0 has multidex support
,08-11 12:28:52.175  8582  8582 I MultiDex: install
,08-11 12:28:52.175  8582  8582 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 12:28:52.191  8582  8582 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-11 12:28:52.198  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-11 12:28:52.210  2214  2214 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-11 12:28:52.211  2214  2214 D c       : Getting all permits...
08-11 12:28:52.211  2214  2214 D a       : Opening database...
,08-11 12:28:52.220  2214  2214 D a       : Opening database auth.proximity.permit_store...
08-11 12:28:52.221  2214  2214 D a       : Closing database...
08-11 12:28:52.643  8606  8606 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-11 12:28:52.738  8606  8606 I dex2oat : dex2oat took 94.988ms (threads: 4)
,08-11 12:28:52.757  8582  8598 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:28:52.757  8582  8598 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:28:52.757  8582  8598 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:28:52.757  8582  8598 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:28:52.757  8582  8598 I Adreno-EGL: Remote Branch: 
08-11 12:28:52.757  8582  8598 I Adreno-EGL: Local Patches: 
08-11 12:28:52.757  8582  8598 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:28:52.886  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:2032517654] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 12:28:52.887  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:2032517655] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-11 12:28:52.887  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 12:28:52.900  8582  8598 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:28:52.900  8582  8598 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:28:52.900  8582  8598 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:28:52.900  8582  8598 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:28:52.900  8582  8598 I Adreno-EGL: Remote Branch: 
08-11 12:28:52.900  8582  8598 I Adreno-EGL: Local Patches: 
08-11 12:28:52.900  8582  8598 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:28:52.968  8582  8598 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:28:52.968  8582  8598 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:28:52.968  8582  8598 I Adreno-EGL: Build Date: 12/12/14 금
08-11 12:28:52.968  8582  8598 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 12:28:52.968  8582  8598 I Adreno-EGL: Remote Branch: 
08-11 12:28:52.968  8582  8598 I Adreno-EGL: Local Patches: 
08-11 12:28:52.968  8582  8598 I Adreno-EGL: Reconstruct Branch: 
,08-11 12:28:53.062  8582  8598 D LgDataFeature: LgDataFeature() Constructor: none
,08-11 12:28:53.062  8582  8598 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-11 12:28:53.228  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:28:53.228  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:28:53.228  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:28:53.228  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:53.228  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:28:53.228  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:53.228  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 12:28:53.229  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f6fb88c removed from the list
,08-11 12:28:53.229  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:53.229  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15146bd5 removed from the list
,08-11 12:28:53.229  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:28:53.229  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-11 12:28:53.229  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:53.229  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:28:53.231  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:53.231  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:53.231  6630  6760 D BluetoothLeScanner: could not find callback wrapper
,08-11 12:28:53.231  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:28:53.231  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:28:53.231  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15146bd5 not in the list
08-11 12:28:53.231  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:53.231  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:28:53.232  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:53.232  6630  6760 D BluetoothLeScanner: could not find callback wrapper
,08-11 12:28:53.232  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:28:53.232  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:53.232  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:28:53.232  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15146bd5 not in the list
08-11 12:28:53.232  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:28:53.232  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:53.232  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:53.232  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f6fb88c not in the list
,08-11 12:28:53.233  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:28:53.233  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3cf051 added. We now have 3 listener(s)
,08-11 12:28:53.234  1035  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:28:53.236  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 12:28:53.236  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 12:28:53.236  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:28:53.237  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:28:53.237  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29d130b6 added. We now have 4 listener(s)
08-11 12:28:53.237  6630  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:28:53.238  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:28:53.242  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:28:53.249  6630  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:28:53.249  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:28:53.249  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:28:53.249  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:28:53.249  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:28:53.249  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:53.249  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:28:53.249  6630  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:28:53.250  6630  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:28:53.250  6630  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:28:53.251  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:53.252  6630  6630 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:28:53.253  6630  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:28:53.253  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:28:53.253  6630  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:28:53.253  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:53.253  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:53.253  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:28:53.254  6630  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 12:28:53.254  6630  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3cf051 removed from the list
08-11 12:28:53.254  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:53.254  6630  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29d130b6 removed from the list
08-11 12:28:53.254  6630  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:28:53.254  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:53.254  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:53.254  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:53.255  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:53.255  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:53.255  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:53.255  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29d130b6 not in the list
08-11 12:28:53.255  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:53.255  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:28:53.255  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:28:53.255  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:28:53.255  6630  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:28:53.255  6630  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29d130b6 not in the list
08-11 12:28:53.255  6630  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:28:53.255  6630  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:28:53.255  6630  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:28:53.255  6630  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b3cf051 not in the list
08-11 12:28:53.256  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-11 12:28:53.256  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-11 12:28:53.256  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-11 12:28:53.257  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:28:53.257  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 12:28:53.257  6630  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 12:28:53.361   322  8622 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-11 12:28:53.362   322  8622 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-11 12:28:53.362   322  8622 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-11 12:28:53.505  1817  8566 I CheckinTask: Sending checkin request (8038 bytes)
,08-11 12:28:53.689  1817  8566 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-11 12:28:53.700  1817  8566 I CheckinService: active receiver: disabled
,08-11 12:28:53.733  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-11 12:28:53.752  2214  2214 I GCM     : GCM config loaded
,08-11 12:28:53.772  8399  8399 V SetupWizard: Connected to Gservices successfully
,08-11 12:28:55.120  1035  1906 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-11 12:28:55.124  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-11 12:28:55.124  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:55.124  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-11 12:28:55.124  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-11 12:28:55.124  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-11 12:28:55.158  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 10:28:55 GMT], X-Android-Received-Millis=[1470911335157], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470911335126]}
08-11 12:28:55.158  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-11 12:28:55.158  1035  8206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-11 12:28:55.163  1035  1458 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-11 12:28:55.164  1035  1458 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-11 12:28:55.164  1035  1458 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-11 12:28:55.164  1035  1458 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:55.164  1035  1458 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-11 12:28:55.164  1035  1458 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,08-11 12:28:55.164  1035  1458 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-11 12:28:55.164  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 12:28:55.164  1035  1458 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-11 12:28:55.165  1035  1458 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-11 12:28:55.166  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-11 12:28:55.275  6630  8628 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 890, name: My test thread name)
,08-11 12:28:55.903  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:2032520671] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:55.913  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:2032520674] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:55.914  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-11 12:28:57.273  6630  6760 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 890
08-11 12:28:57.273  6630  6760 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 890, name: My test thread name)
,08-11 12:28:57.290  6630  8629 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: My test thread name)
08-11 12:28:57.290  6630  8629 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 891, thread name: My test thread name)
08-11 12:28:57.290  6630  8629 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-11 12:28:57.292  6630  6760 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:28:57.295  6630  8630 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 895, name: My test thread name)
08-11 12:28:57.295  6630  8630 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 895, thread name: My test thread name): Test exception.
08-11 12:28:57.296  6630  8630 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 895, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-11 12:28:57.302  6630  6760 I jxcore-log: Total number of executed tests:  82
08-11 12:28:57.302  6630  6760 I jxcore-log: 
08-11 12:28:57.302  6630  6760 I jxcore-log: Number of passed tests:  82
08-11 12:28:57.302  6630  6760 I jxcore-log: 
08-11 12:28:57.302  6630  6760 I jxcore-log: Number of failed tests:  0
08-11 12:28:57.302  6630  6760 I jxcore-log: 
08-11 12:28:57.302  6630  6760 I jxcore-log: Number of ignored tests:  0
08-11 12:28:57.302  6630  6760 I jxcore-log: 
08-11 12:28:57.303  6630  6760 I jxcore-log: Total duration:  85239
08-11 12:28:57.303  6630  6760 I jxcore-log: 
08-11 12:28:57.303  6630  6760 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 12:28:57.303  6630  6760 I jxcore-log: 
,08-11 12:28:57.323  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.323  6630  6760 I jxcore-log: 
08-11 12:28:57.326  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.326  6630  6760 I jxcore-log: 
,08-11 12:28:57.332  6630  8628 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 890, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
08-11 12:28:57.343  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.343  6630  6760 I jxcore-log: 
08-11 12:28:57.345  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.345  6630  6760 I jxcore-log: 
08-11 12:28:57.346  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.346  6630  6760 I jxcore-log: 
,08-11 12:28:57.350  6630  6630 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-11 12:28:57.351  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.351  6630  6760 I jxcore-log: 
08-11 12:28:57.355  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.355  6630  6760 I jxcore-log: 
08-11 12:28:57.357  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.357  6630  6760 I jxcore-log: 
08-11 12:28:57.358  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 12:28:57.358  6630  6760 I jxcore-log: 
08-11 12:28:57.359  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.359  6630  6760 I jxcore-log: 
08-11 12:28:57.360  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 12:28:57.360  6630  6760 I jxcore-log: 
08-11 12:28:57.361  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 12:28:57.361  6630  6760 I jxcore-log: 
08-11 12:28:57.361  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.361  6630  6760 I jxcore-log: 
08-11 12:28:57.362  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.362  6630  6760 I jxcore-log: 
08-11 12:28:57.363  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.363  6630  6760 I jxcore-log: 
08-11 12:28:57.364  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 12:28:57.364  6630  6760 I jxcore-log: 
08-11 12:28:57.365  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 12:28:57.365  6630  6760 I jxcore-log: 
08-11 12:28:57.366  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 12:28:57.366  6630  6760 I jxcore-log: 
08-11 12:28:57.368  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 12:28:57.368  6630  6760 I jxcore-log: 
08-11 12:28:57.368  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.368  6630  6760 I jxcore-log: 
08-11 12:28:57.369  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.369  6630  6760 I jxcore-log: 
08-11 12:28:57.370  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluet,ooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.370  6630  6760 I jxcore-log: 
08-11 12:28:57.371  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.371  6630  6760 I jxcore-log: 
08-11 12:28:57.371  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.371  6630  6760 I jxcore-log: 
08-11 12:28:57.372  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.372  6630  6760 I jxcore-log: 
08-11 12:28:57.373  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.373  6630  6760 I jxcore-log: 
08-11 12:28:57.374  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.374  6630  6760 I jxcore-log: 
08-11 12:28:57.374  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.374  6630  6760 I jxcore-log: 
08-11 12:28:57.375  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.375  6630  6760 I jxcore-log: 
08-11 12:28:57.376  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.376  6630  6760 I jxcore-log: 
,08-11 12:28:57.383  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.383  6630  6760 I jxcore-log: 
,08-11 12:28:57.384  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.384  6630  6760 I jxcore-log: 
,08-11 12:28:57.385  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.385  6630  6760 I jxcore-log: 
,08-11 12:28:57.386  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 12:28:57.386  6630  6760 I jxcore-log: 
,08-11 12:28:57.389  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-11 12:28:57.389  6630  6760 I jxcore-log: 
,08-11 12:28:57.390  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-11 12:28:57.390  6630  6760 I jxcore-log: 
08-11 12:28:57.391  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.391  6630  6760 I jxcore-log: 
,08-11 12:28:57.392  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.392  6630  6760 I jxcore-log: 
08-11 12:28:57.392  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.392  6630  6760 I jxcore-log: 
08-11 12:28:57.393  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.393  6630  6760 I jxcore-log: ,
08-11 12:28:57.394  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.394  6630  6760 I jxcore-log: 
08-11 12:28:57.395  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-11 12:28:57.395  6630  6760 I jxcore-log: 
,08-11 12:28:57.396  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:28:57.396  6630  6760 I jxcore-log: 
,08-11 12:28:57.396  6630  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-11 12:28:57.396  6630  6760 I jxcore-log: 
,08-11 12:28:57.635  8631  8631 D AndroidRuntime: 
,08-11 12:28:57.635  8631  8631 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 12:28:57.640  8631  8631 D AndroidRuntime: CheckJNI is OFF,
,08-11 12:28:57.796  8631  8631 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 12:28:57.812  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-11 12:28:57.816  1035  1092 I ActivityManager: Killing 6630:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-11 12:28:57.888  1035  1445 D WifiService: Client connection lost with reason: 4
08-11 12:28:57.889  1035  1996 I WindowState: WIN DEATH: Window{25cacd8e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 12:28:57.896  1035  1996 D InputDispatcher: Window went away: Window{25cacd8e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 12:28:58.036  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{2307a02e u0 com.test.thalitest/.MainActivity t6}
,08-11 12:28:58.057   341   349 E GBMv2   : DFP En is all cleared set to be enabled
,08-11 12:28:58.057  1035  1978 W ActivityManager: Spurious death for ProcessRecord{1923d0fb 6630:com.test.thalitest/u0a118}, curProc for 6630: null
08-11 12:28:58.058  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-11 12:28:58.063  1035  1124 I ActivityManager:   Force finishing activity ActivityRecord{2307a02e u0 com.test.thalitest/.MainActivity t6 f}
08-11 12:28:58.063  1035  1124 W ActivityManager: Duplicate finish request for ActivityRecord{2307a02e u0 com.test.thalitest/.MainActivity t6 f}
,08-11 12:28:58.088  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-11 12:28:58.092  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-11 12:28:58.095  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-11 12:28:58.101  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-11 12:28:58.101  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1963593a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 12:28:58.101  2034  2077 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-11 12:28:58.105  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-11 12:28:58.105  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1158d9eb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-11 12:28:58.111  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-11 12:28:58.112  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 12:28:58.113  1907  1907 D ActionManagerService: notifyUserLog: 1000003
08-11 12:28:58.113  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-11 12:28:58.114  3826  4501 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-11 12:28:58.114  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-11 12:28:58.119  1907  1907 D ActionManagerService: notifyUserLog: 1000004
08-11 12:28:58.120  3826  4501 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-11 12:28:58.120  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-11 12:28:58.122  3826  3842 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-11 12:28:58.126  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-11 12:28:58.136  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 12:28:58.159  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 12:28:58.159  3826  3826 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-11 12:28:58.162  7924  7924 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-11 12:28:58.162  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-11 12:28:58.164  2476  2629 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 12:28:58.187  4623  4623 I art     : Explicit concurrent mark sweep GC freed 8184(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 2.129ms total 107.345ms
,08-11 12:28:58.191  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-11 12:28:58.210  1035  1906 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:28:58.212  8181  8181 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-11 12:28:58.217  4513  4513 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 12:28:58.217  4513  4513 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 12:28:58.227  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-11 12:28:58.229  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-11 12:28:58.251  4513  4513 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 12:28:58.251  4513  4513 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-11 12:28:58.251  4513  4513 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:28:58.251  4513  4513 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:28:58.251  4513  4513 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:28:58.251  4513  4513 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 12:28:58.251  4513  4513 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:28:58.251  4513  4513 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:28:58.251  4513  4513 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 12:28:58.252  4513  4513 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-11 12:28:58.258  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-11 12:28:58.259  1871  1871 D SplitUIService: removed split : 
08-11 12:28:58.264  1035  1870 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8664 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , display: false
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , animation: false }
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , display: false
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , animation: false }
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , create_time: 1470393743569
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , display: false
08-11 12:28:58.265  2034  2034 I GBoardWebViewUtils: , animation: false }
,08-11 12:28:58.270  2214  2214 I ConfigService: onCreate
08-11 12:28:58.270  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 12:28:58.280  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-11 12:28:58.289  2214  2214 I ConfigService: onBind returning update interface
08-11 12:28:58.290  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 12:28:58.290  2214  2214 I ConfigService: onBind returning config service
08-11 12:28:58.310  2034  8674 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-11 12:28:58.313  1035  1035 I art     : Explicit concurrent mark sweep GC freed 30201(1988KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 10.956ms total 227.174ms
08-11 12:28:58.313  1035  1124 I art     : WaitForGcToComplete blocked for 223.983ms for cause Explicit
08-11 12:28:58.319  2214  2214 I ConfigService: onDestroy
08-11 12:28:58.320  1871  1871 D SplitUIManager: split_name #11 / not available #0
,08-11 12:28:58.320  1871  1871 I SplitUIService: split app #11
08-11 12:28:58.325  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 12:28:58.325  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-11 12:28:58.342  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-11 12:28:58.342  1035  1959 I ActivityManager: Killing 7610:com.lge.settings.easy/1000 (adj 15): empty #17
08-11 12:28:58.345  1817  8684 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-11 12:28:58.348  8664  8664 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-11 12:28:58.360  1035  2032 V SIM_STK : Menu title from STK is T-Mobile
08-11 12:28:58.360  1035  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:28:58.376  1035  1035 D administrator: Handling package changes for user 0
08-11 12:28:58.420  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-11 12:28:58.433  1035  1892 V SIM_STK : Menu title from STK is T-Mobile
,08-11 12:28:58.451  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_7610/cgroup.procs: No such file or directory
,08-11 12:28:58.454  1035  1924 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-11 12:28:58.454  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 12:28:58.454  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-11 12:28:58.454  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 12:28:58.454  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 12:28:58.454  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 12:28:58.455  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 12:28:58.455  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 12:28:58.455  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 12:28:58.455  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 12:28:58.455  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 12:28:58.455  7924  7924 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 12:28:58.457  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-11 12:28:58.459  1604  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 12:28:58.459  1604  1664 D KeyguardModel: createShortcutInfo...
08-11 12:28:58.460  1604  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 12:28:58.460  1604  1664 D KeyguardModel: createShortcutInfo...
08-11 12:28:58.468  1604  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 12:28:58.469  1604  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:58.469  1604  1664 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 12:28:58.470  1604  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-11 12:28:58.471  1604  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:28:58.471  1604  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 12:28:58.473  1604  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 12:28:58.473  1604  1664 D KeyguardModel: createShortcutInfo...
08-11 12:28:58.476  5928  8691 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-11 12:28:58.480  1604  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-11 12:28:58.480  1604  1664 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:28:58.481  1817  8692 I PeopleContactsSync: CP2 sync disabled
08-11 12:28:58.481  1604  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:28:58.481  1604  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-11 12:28:58.484  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 12:28:58.484  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 12:28:58.484  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 12:28:58.486  1604  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 12:28:58.486  1604  1664 D KeyguardModel: createShortcutInfo...
08-11 12:28:58.490  1035  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-11 12:28:58.493  1604  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:58.493  1604  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-11 12:28:58.493  1604  1664 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 12:28:58.493  1604  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 12:28:58.495  1604  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:28:58.495  1604  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-11 12:28:58.498  1604  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 12:28:58.498  1604  1664 D KeyguardModel: createShortcutInfo...
08-11 12:28:58.503  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-11 12:28:58.503  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 12:28:58.504  1035  1124 I art     : Explicit concurrent mark sweep GC freed 5205(250KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.296ms total 184.928ms
08-11 12:28:58.504  1817  8690 W GmsApplication: Using Auth Proxy for data requests.
08-11 12:28:58.507  1604  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 12:28:58.507  1604  1664 D KeyguardModel: createShortcutInfo...
,08-11 12:28:58.510  1604  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 12:28:58.510  1604  1664 D KeyguardModel: createShortcutInfo...
08-11 12:28:58.510  1817  4777 I Icing   : doRemovePackageData com.test.thalitest
08-11 12:28:58.511  1817  8690 W GmsApplication: Using Auth Proxy for data requests.
08-11 12:28:58.511  1604  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:28:58.511  1604  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 12:28:58.512  1604  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 12:28:58.512  1604  1664 D KeyguardModel: createShortcutInfo...
08-11 12:28:58.513  1604  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:28:58.513  1604  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 12:28:58.514  1604  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 12:28:58.514  1604  1664 D KeyguardModel: createShortcutInfo...
08-11 12:28:58.516  1604  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:28:58.516  1604  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 12:28:58.518  1604  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 12:28:58.518  1604  1664 D KeyguardModel: createShortcutInfo...
,08-11 12:28:58.526  7061  7061 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-11 12:28:58.562  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-11 12:28:58.564  1035  1996 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8694 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-11 12:28:58.567  1035  1651 I ActivityManager: Killing 8157:com.lge.bnr/1000 (adj 15): empty #17
08-11 12:28:58.567  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:28:58.569  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-11 12:28:58.570  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-11 12:28:58.571  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-11 12:28:58.572  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-11 12:28:58.589  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-11 12:28:58.589  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:28:58.593  2034  2135 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-11 12:28:58.593  2034  2135 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-11 12:28:58.597   335   420 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-11 12:28:58.598  3201  8712 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-11 12:28:58.612  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-11 12:28:58.613  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 12:28:58.613  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 12:28:58.620  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-11 12:28:58.625  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:58.628  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-11 12:28:58.630  8631  8631 D AndroidRuntime: Shutting down VM
,08-11 12:28:58.647  1604  1604 D KeyguardModel: handleShortcutListChanged...
,08-11 12:28:58.647  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-11 12:28:58.652  1035  1716 W libprocessgroup: failed to open /acct/uid_1000/pid_8157/cgroup.procs: No such file or directory
08-11 12:28:58.657  2600  2600 D [Concierge]Service: onStartCommand(). Type : 8
08-11 12:28:58.657  2600  2600 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-11 12:28:58.658  2600  2600 D [Concierge]Service: Update widget ID : 11
08-11 12:28:58.659  2034  2034 D [Concierge]WidgetView: change position of spinner
,08-11 12:28:58.662  1035  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19b9411d u0 com.lge.launcher2/.Launcher t5} time:212596
08-11 12:28:58.663  2600  2600 D [Concierge]Service: onStartCommand(). Type : 0
08-11 12:28:58.663  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1470911338663
08-11 12:28:58.669  8694  8694 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:58.670  8694  8694 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:28:58.670  8694  8694 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 12:28:58.670  8694  8694 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-11 12:28:58.671  8694  8694 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-11 12:28:58.694  1035  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8715 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-11 12:28:58.702  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 719770269
08-11 12:28:58.702  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-11 12:28:58.702  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-11 12:28:58.705  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@115eb61d
08-11 12:28:58.705  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-11 12:28:58.707  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 12:28:58.707  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:28:58.712  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-11 12:28:58.712  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-11 12:28:58.712  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 12:28:58.714  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 12:28:58.715  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470911153973, New one : 1470911338663
08-11 12:28:58.715  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-11 12:28:58.715  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 12:28:58.716  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-11 12:28:58.718  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-11 12:28:58.719  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-11 12:28:58.720  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-11 12:28:58.721  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-11 12:28:58.722  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-11 12:28:58.727  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:28:58.727  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:28:58.748  1035  2033 I ActivityManager: Killing 8131:com.lge.sync/1000 (adj 15): empty #17
,08-11 12:28:58.753  1817  8688 I art     : Explicit concurrent mark sweep GC freed 47188(3MB) AllocSpace objects, 25(393KB) LOS objects, 51% free, 30MB/62MB, paused 925us total 28.972ms
08-11 12:28:58.754  8694  8694 I SystemConfig: BUILD Country: EU
08-11 12:28:58.755  8694  8694 I SystemConfig: BUILD Operator: OPEN
08-11 12:28:58.756  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-11 12:28:58.757  1817  1829 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-11 12:28:58.757  1817  1829 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-11 12:28:58.758  1817  1829 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-11 12:28:58.763  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-11 12:28:58.764  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-11 12:28:58.764  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 12:28:58.794  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@226feace time:212728
,08-11 12:28:58.818  1035  1651 W libprocessgroup: failed to open /acct/uid_1000/pid_8131/cgroup.procs: No such file or directory
,08-11 12:28:58.823  1035  1959 I ActivityManager: Killing 6861:com.android.settings/1000 (adj 15): empty #17
08-11 12:28:58.899  1035  1716 W libprocessgroup: failed to open /acct/uid_1000/pid_6861/cgroup.procs: No such file or directory
,08-11 12:28:58.904  8694  8733 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-11 12:28:58.904  8694  8733 I SystemConfig: existFile = false
08-11 12:28:58.904  8694  8733 I SystemConfig: canReadFile = false
08-11 12:28:58.904  8694  8733 I SystemConfig: systemFeature RCS result false
08-11 12:28:58.905  8694  8733 D SystemConfig: refreshRcsSupport() :false
08-11 12:28:58.909  8362  8362 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-11 12:28:58.912  2346  8737 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 12:28:58.916  1817  8736 E DocListDatabase: Failed to delete from FileContent40
08-11 12:28:58.916  1817  8736 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:393)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at com.google.android.gms.drive.database.d.a(SourceFile:1017)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at com.google.android.gms.drive.b.c.run(SourceFile:58)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at com.google.android.gms.drive.g.an.run(SourceFile:51)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-11 12:28:58.916  1817  8736 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
08-11 12:28:58.917  1817  8736 E AndroidRuntime: FATAL EXCEPTION: pool-29-thread-1
08-11 12:28:58.917  1817  8736 E AndroidRuntime: Process: com.google.android.gms, PID: 1817
08-11 12:28:58.917  1817  8736 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:393)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.a(SourceFile:1017)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at com.google.android.gms.drive.b.c.run(SourceFile:58)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at com.google.android.gms.drive.g.an.run(SourceFile:51)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-11 12:28:58.917  1817  8736 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:28:58.918  2346  8737 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-11 12:28:58.919  2346  8737 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-11 12:28:58.919  2346  8737 E AndroidRuntime: Process: android.process.acore, PID: 2346
08-11 12:28:58.919  2346  8737 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	a,t android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:28:58.919  2346  8737 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:28:58.932  1035  1399 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=11.2, 0.0, 0.0  rx=8.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:2032523700] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-11 12:28:58.933  1035  1399 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=11.2, 0.0, 0.0  rx=8.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:2032523701] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-11 12:28:58.933  1035  1399 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-11 12:28:58.940  1035  1870 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8739 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-11 12:28:58.943  1817  8736 I Process : Sending signal. PID: 1817 SIG: 9
,08-11 12:28:58.944  2346  8737 I Process : Sending signal. PID: 2346 SIG: 9
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: Can't write: system_app_crash
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-11 12:28:58.945  1035  8748 E DropBoxManagerService: 	... 5 more
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: Can't write: system_app_crash
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-11 12:28:58.947  1035  8750 E DropBoxManagerService: 	... 5 more
08-11 12:28:58.948  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-11 12:28:58.962   276   276 E lowmemorykiller: Error writing /proc/2346/oom_score_adj; errno=22
08-11 12:28:58.974  8739  8739 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:28:58.974  8739  8739 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-11 12:28:58.974  8739  8739 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 12:28:58.974  8739  8739 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-11 12:28:58.988  2034  2878 I GBoardtInterface: onReloaded()

```
