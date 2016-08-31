#### Test 83084099807e426_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-31 16:50:48.844  1029  2018 I ActivityManager: Killing 5148:com.google.android.setupwizard/u0a46 (adj 15): empty #17
--------- beginning of main
08-31 16:50:48.874  1987  1987 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-31 16:50:48.874  1987  1987 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-31 16:50:48.876  1029  1924 W libprocessgroup: failed to open /acct/uid_10046/pid_5148/cgroup.procs: No such file or directory
08-31 16:50:48.880  1987  1987 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-31 16:50:48.901  5115  5115 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 16:50:48.906  5115  5115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-31 16:50:48.975  1029  2024 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5823 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:50:49.194  5823  5823 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-31 16:50:49.278  5823  5823 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:50:49.278  5823  5823 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 16:50:49.332  5823  5823 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-31 16:50:49.353  5823  5823 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-31 16:50:49.354  5823  5823 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-31 16:50:49.371  5823  5823 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-31 16:50:49.371  5823  5823 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-31 16:50:49.378   340   432 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-31 16:50:49.378  3158  5865 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-31 16:50:49.391  1029  2024 I ActivityManager: Killing 5199:com.lge.clock/u0a10 (adj 15): empty #17
08-31 16:50:49.426  1029  1566 W libprocessgroup: failed to open /acct/uid_10010/pid_5199/cgroup.procs: No such file or directory
08-31 16:50:49.435  4367  5867 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-31 16:50:49.443  3421  5287 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-31 16:50:49.444  3421  5287 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@e62e2fe on behalf of 5823
08-31 16:50:49.486  1029  2024 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5868 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:50:49.518  5823  5823 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-31 16:50:49.543  5823  5823 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-31 16:50:49.662  5868  5868 D DocsApplication: Installing DEX configuration.
08-31 16:50:49.678  5868  5868 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-31 16:50:49.682  5868  5868 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{c3212dd com.google.android.apps.docs}
08-31 16:50:49.701  5868  5868 D TAG     : onCreate()
08-31 16:50:49.718  5868  5868 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-31 16:50:49.834  1029  2024 V SIM_STK : Menu title from STK is T-Mobile
08-31 16:50:49.928  5898  5898 D AndroidRuntime: 
08-31 16:50:49.928  5898  5898 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 16:50:49.930  5898  5898 D AndroidRuntime: CheckJNI is OFF
08-31 16:50:49.933  4367  5867 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 493 ms] updated apps [took 492 ms] 
08-31 16:50:50.142  5898  5898 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 16:50:50.148  1029  2018 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 16:50:50.164  1932  1950 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 16:50:50.167  1029  2018 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 16:50:50.170  1029  2018 D ActivityManager: setTaskToReturnTo : TaskRecord{2ccb0f20 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 16:50:50.170  1029  2018 D ActivityManager: setTaskToReturnTo : TaskRecord{2ccb0f20 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 16:50:50.172  1029  2018 D WindowStateEx: AppWindowTokenEx init.. 
08-31 16:50:50.172   347   361 E GBMv2   : DFP En is all cleared set to be enabled
08-31 16:50:50.207  1029  2018 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5918 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 16:50:50.208  5898  5898 D AndroidRuntime: Shutting down VM
08-31 16:50:50.239  1932  1950 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 16:50:50.240  1932  1950 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1076c696 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 16:50:50.240  1932  3788 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 16:50:50.241  1932  3788 D SplitWindowPolicy: topRunningActivity=ActivityInfo{21187217 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 16:50:50.272  5918  5918 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 16:50:50.374  5918  5918 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-31 16:50:50.384  5918  5918 I LibraryLoader: Loading: webviewchromium
08-31 16:50:50.387  5918  5918 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3737-3741)
08-31 16:50:50.387  5918  5918 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:50:50.406  5918  5918 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28907f}
08-31 16:50:50.407  5918  5918 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:50:50.407  5918  5918 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 16:50:50.417  5918  5918 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 16:50:50.418  5918  5918 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:50.424  5918  5937 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,08-31 16:50:50.429  5918  5918 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 16:50:50.430  5918  5918 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 16:50:50.430  5918  5918 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-31 16:50:50.436   324   324 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 10118
08-31 16:50:50.442  1029  1111 D BluetoothManagerService: Message: 20
08-31 16:50:50.442  1029  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3544b2aa:true
,08-31 16:50:50.445  5918  5941 D BluetoothAdapter: 780560460: getState() :  mService = null. Returning STATE_OFF
08-31 16:50:50.449  5918  5918 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 16:50:50.449  5918  5918 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 16:50:50.449  5918  5918 I Adreno-EGL: Build Date: 12/12/14 금
08-31 16:50:50.449  5918  5918 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 16:50:50.449  5918  5918 I Adreno-EGL: Remote Branch: 
08-31 16:50:50.449  5918  5918 I Adreno-EGL: Local Patches: 
08-31 16:50:50.449  5918  5918 I Adreno-EGL: Reconstruct Branch: 
08-31 16:50:50.536  5918  5947 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 16:50:50.545  5918  5918 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 16:50:50.559  5918  5918 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:50:50.569  5918  5918 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 16:50:50.572  5918  5918 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-31 16:50:50.576  5918  5918 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 16:50:50.576  5918  5918 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-31 16:50:50.595  5918  5918 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 16:50:50.602  5918  5918 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:50.602  5918  5918 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:50:50.640  5918  5959 D OpenGLRenderer: Render dirty regions requested: true
08-31 16:50:50.640  5918  5959 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 16:50:50.646  5918  5959 D OpenGLRenderer: Enabling debug mode 0
,08-31 16:50:50.654  5918  5918 D Atlas   : Validating map...
08-31 16:50:50.658  1029  1566 D SplitWindow: check instance of lgWin Window{15945414 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:50:50.690  2770  2770 I MusicWidget: mDelayedStopHandler : unbind
,08-31 16:50:50.691  5918  5957 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:50:50.691  5918  5957 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 16:50:50.692  2116  2116 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-31 16:50:50.692  2116  2116 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-31 16:50:50.693  2116  2116 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-31 16:50:50.694  2116  2116 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-31 16:50:50.695  2116  2116 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-31 16:50:50.695  2116  2116 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-31 16:50:50.697  2116  2116 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-31 16:50:50.701  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-31 16:50:50.703  1029  1942 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@139cf905com.lge.music.MediaPlaybackService$5@c93bd5a
08-31 16:50:50.704  2116  2116 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-31 16:50:50.704  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.705  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.706  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.706  2116  2116 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2dbfb59b
08-31 16:50:50.706  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.707  2116  2116 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-31 16:50:50.707  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.707  2116  2116 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-31 16:50:50.707  2116  2116 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-31 16:50:50.708  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.708  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.709  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.709  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.710  2116  2116 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 16:50:50.710  2116  2116 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-31 16:50:50.712  2116  2116 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-31 16:50:50.712  2116  2116 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-31 16:50:50.712  2116  2116 V MediaPlayer[Native]: reset
,08-31 16:50:50.717  2116  2116 V MediaPlayer[Native]: setListener
08-31 16:50:50.717  2116  2116 V MediaPlayer[Native]: disconnect
08-31 16:50:50.717  2116  2116 V MediaPlayer[Native]: destructor
08-31 16:50:50.717   324  2144 V AudioFlinger: releasing 18 from 2116 for -1
08-31 16:50:50.717   324  2144 V AudioFlinger:  decremented refcount to 0
08-31 16:50:50.717   324  2144 V AudioFlinger: purging stale effects
08-31 16:50:50.718  2116  2116 V MediaPlayer[Native]: disconnect
08-31 16:50:50.720  2116  2116 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-31 16:50:50.721  2116  2116 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-31 16:50:50.721  2116  2116 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-31 16:50:50.722  2116  2116 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-31 16:50:50.723  2116  2116 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-31 16:50:50.723  2116  2116 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-31 16:50:50.723  2116  2116 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 741686155
08-31 16:50:50.723  2116  2116 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 741686155
08-31 16:50:50.727  2116  2116 I SmartShareClient: [SmartShareManagerClient] terminate service: 2116/MediaPlaybackService/608305113
08-31 16:50:50.730  2116  2116 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-31 16:50:50.730  2116  2116 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@2350e468
,08-31 16:50:50.733  2116  2116 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-31 16:50:50.733  2116  2116 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-31 16:50:50.734  2116  2116 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-31 16:50:50.734  2116  2116 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-31 16:50:50.736  1029  1566 I ActivityManager: Killing 4772:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-31 16:50:50.737  2116  2116 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
08-31 16:50:50.776  5918  5918 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c353b8b time:104131
,08-31 16:50:50.821  1029  1760 W libprocessgroup: failed to open /acct/uid_10085/pid_4772/cgroup.procs: No such file or directory
,08-31 16:50:50.824  1029  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +585ms (total +651ms)
08-31 16:50:50.825  1029  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d160d9 u0 com.test.thalitest/.MainActivity t6} time:104179
08-31 16:50:50.888  5918  5918 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 16:50:50.888  5918  5918 I chromium: 
,08-31 16:50:50.917  5918  5918 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 16:50:50.941  1808  4527 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-31 16:50:50.981  5918  5957 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 16:50:50.981  5918  5957 I chromium: 
,08-31 16:50:50.987  1808  4527 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-31 16:50:51.080  1808  4527 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-31 16:50:51.088  5918  5970 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435159040
08-31 16:50:51.098  5918  5970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:50:51.098  5918  5970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:50:51.098  5918  5970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:50:51.098  5918  5970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:50:51.098  5918  5970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 16:50:51.098  5918  5970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb83a5f added. We now have 1 listener(s)
08-31 16:50:51.103  1029  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:50:51.104  5918  5970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 16:50:51.105  5918  5970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 16:50:51.106  5918  5970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 16:50:51.106  5918  5970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 16:50:51.112  5918  5970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f86310a added. We now have 1 listener(s)
08-31 16:50:51.112  5918  5970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 16:50:51.118  1029  1524 D WifiService: New client listening to asynchronous messages
08-31 16:50:51.120  5918  5970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 16:50:51.120  5918  5970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 16:50:51.121  5918  5970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 16:50:51.121  5918  5970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 16:50:51.121  5918  5970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 16:50:51.123  5918  5970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 16:50:51.123  1029  1877 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:50:51.123  5918  5970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 16:50:51.126  5918  5970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:51.126  5918  5970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:51.126  5918  5970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:51.126  5918  5970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:51.126  5918  5970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:51.126  5918  5970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:51.126  5918  5970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:51.126  5918  5970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:51.126  5918  5970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:50:51.126  5918  5970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:50:51.126  5918  5970 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 16:50:51.127  5918  5970 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 16:50:51.162  5918  5918 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 16:50:51.362  5868  5868 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:50:51.362  5868  5868 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 16:50:51.449   347   363 E GBMv2   : DFP En is all cleared set to be enabled
08-31 16:50:51.450   347   363 E GBMv2   : Set value is all cleared set the max
08-31 16:50:51.450   347   363 I GBMv2   : DFP Enabled. Ignore VFP set
,08-31 16:50:51.576  1029  2018 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5978 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-31 16:50:51.576  1029  2018 I ActivityManager: Killing 4922:com.lge.bnr/1000 (adj 15): empty #17
,08-31 16:50:51.652  1029  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4922/cgroup.procs: No such file or directory
,08-31 16:50:51.662  5868  5868 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-31 16:50:51.724  5978  5978 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-31 16:50:51.738  5978  5978 I LockScreenSettings: New app installed broadcast received ..
08-31 16:50:51.741  5978  5978 I LockScreenSettings: Number of installed packages  1
,08-31 16:50:51.794  1029  2018 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6003 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 16:50:51.847  6003  6003 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:50:51.889  5918  5973 W jxcore-log: Initializing JXcore engine
08-31 16:50:51.889  5918  5973 W jxcore-log: JXcore engine is ready
,08-31 16:50:51.933  5973  5973 W Thread-647: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[6125]" dev="sockfs" ino=6125 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 16:50:51.933  5973  5973 W Thread-647: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 16:50:51.933  5973  5973 W Thread-647: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7933]" dev="sockfs" ino=7933 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-31 16:50:51.933  5973  5973 W Thread-647: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 16:50:51.933  5973  5973 W Thread-647: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[26516]" dev="sockfs" ino=26516 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 16:50:51.949  5918  5973 W jxcore-log: Starting JXcore engine
08-31 16:50:52.032  5918  5973 W jxcore-log: Platform android
08-31 16:50:52.032  5918  5973 W jxcore-log: 
08-31 16:50:52.032  5918  5973 W jxcore-log: Process ARCH arm
08-31 16:50:52.032  5918  5973 W jxcore-log: 
,08-31 16:50:52.419  1029  1760 V SIM_STK : Menu title from STK is T-Mobile
,08-31 16:50:52.446  5918  5973 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:50:52.446  5918  5973 I jxcore-log: 
08-31 16:50:52.446  5918  5973 W jxcore-log: JXcore engine is started
,08-31 16:50:52.452  5918  5970 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 16:50:52.454  5918  5918 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-31 16:50:52.489  1029  1877 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6043 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 16:50:52.542  6043  6043 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-31 16:50:52.542  6043  6043 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-31 16:50:52.597  1029  1044 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6061 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-31 16:50:52.598  1029  1044 I ActivityManager: Killing 5269:com.google.android.gm/u0a64 (adj 15): empty #17
,08-31 16:50:52.634  1029  1045 I art     : Explicit concurrent mark sweep GC freed 37557(1717KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 42MB/64MB, paused 1.392ms total 98.797ms
,08-31 16:50:52.777  1029  2024 W libprocessgroup: failed to open /acct/uid_10064/pid_5269/cgroup.procs: No such file or directory
,08-31 16:50:52.853  6061  6061 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-31 16:50:52.887  1029  1983 I ActivityManager: Killing 5317:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 16:50:52.887  6061  6061 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 16:50:53.057  1029  1937 W libprocessgroup: failed to open /acct/uid_10072/pid_5317/cgroup.procs: No such file or directory
,08-31 16:50:55.478  5868  5868 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-31 16:50:55.487  1029  1877 I ActivityManager: Killing 5046:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-31 16:50:55.502  5025  5025 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 16:50:55.502  5025  5025 W System.err: android.os.DeadObjectException
08-31 16:50:55.502  5025  5025 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 16:50:55.502  5025  5025 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 16:50:55.502  5025  5025 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 16:50:55.502  5025  5025 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 16:50:55.502  5025  5025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 16:50:55.502  5025  5025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 16:50:55.502  5025  5025 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 16:50:55.503  5025  5025 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 16:50:55.503  5025  5025 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:50:55.503  5025  5025 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 16:50:55.503  5025  5025 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:50:55.503  5025  5025 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:50:55.503  5025  5025 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 16:50:55.503  5025  5025 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 16:50:55.503  5025  5025 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 16:50:55.503  5025  5025 W System.err: android.os.DeadObjectException
08-31 16:50:55.503  5025  5025 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 16:50:55.503  5025  5025 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 16:50:55.503  5025  5025 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 16:50:55.503  5025  5025 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 16:50:55.504  5025  5025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 16:50:55.504  5025  5025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 16:50:55.504  5025  5025 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 16:50:55.504  5025  5025 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 16:50:55.504  5025  5025 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:50:55.504  5025  5025 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 16:50:55.504  5025  5025 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:50:55.504  5025  5025 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:50:55.504  5025  5025 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 16:50:55.504  5025  5025 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 16:50:55.504  5025  5025 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 16:50:55.504  5025  5025 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-31 16:50:55.778  1029  2018 W libprocessgroup: failed to open /acct/uid_1000/pid_5046/cgroup.procs: No such file or directory
,08-31 16:50:55.778  1029  2018 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-31 16:50:55.781  5025  5025 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 16:50:55.781  5025  5025 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 16:50:55.839  1029  1878 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6110 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 16:50:55.843  5025  5025 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 16:50:55.913  6110  6110 D UEI.SmartControl: Quickset Services start...
,08-31 16:50:55.918  6110  6110 I UEI.SmartControl: Manufacture = LGE
,08-31 16:50:55.918  6110  6110 D UEI.SmartControl: Id = LGNevo
,08-31 16:50:55.922  6110  6110 D UEI.SmartControl: File observer start...
,08-31 16:50:55.923  6110  6110 E UEI.SmartControl: IR Port is disabled: false
08-31 16:50:55.923  6110  6110 D UEI.SmartControl: Starting file observer...
08-31 16:50:55.924  6110  6110 D UEI.SmartControl: Extracting JNI libs...
08-31 16:50:55.924  6110  6110 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 16:50:56.010  6110  6110 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 16:50:56.010  6110  6110 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 16:50:56.010  6110  6110 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 16:50:56.044  6110  6110 I UEI.SmartControl: --- Selecting new region: 6
,08-31 16:50:56.047  6110  6110 I UEI.SmartControl: Model = LG-D855
08-31 16:50:56.048  6110  6110 D UEI.SmartControl: QS Service created
08-31 16:50:56.064  6110  6110 I UEI.SmartControl: Service initServices...
,08-31 16:50:56.068  6110  6110 D UEI.SmartControl: QS start get config
08-31 16:50:56.107  6110  6110 D UEI.SmartControl: Loading JNI Libs...
,08-31 16:50:56.346  6110  6110 I UEI.SmartControl: Supports setup maps: true
,08-31 16:50:56.348  6110  6110 D UEI.SmartControl: QS start statue = true Error code = 0
,08-31 16:50:56.349  6110  6110 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 16:50:56.349  6110  6110 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 16:50:56.349  6110  6110 I UEI.SmartControl: ### init IR Blaster...
08-31 16:50:56.354  6110  6110 D serial_port: Configuring serial port
,08-31 16:50:56.371  6110  6110 E UEI.SmartControl: UEIBLaster setting for 616
,08-31 16:50:56.371  6110  6110 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 16:50:56.373  6110  6110 I UEI.SmartControl: configuring settings for MAXQ616
08-31 16:50:56.374  6110  6110 I UEI.SmartControl: Get version...
08-31 16:50:56.390  6110  6134 D UEI.SmartControl: serial port data available: 21
,08-31 16:50:56.418  6110  6110 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 16:50:56.418  6110  6110 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 16:50:56.419  6110  6110 I UEI.SmartControl: QS saving settings...
,08-31 16:50:56.421  6110  6110 D UEI.SmartControl: IR Blaster version: 25672567
08-31 16:50:56.443  6110  6134 D UEI.SmartControl: serial port data available: 4
,08-31 16:50:56.459  5868  5974 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 16:50:56.482  6110  6110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 16:50:56.483  6110  6139 I UEI.SmartControl: Device manager: loading config....
08-31 16:50:56.485  6110  6110 E UEI.SmartControl: Services init done
08-31 16:50:56.485  6110  6110 D UEI.SmartControl: QS Service init finished
08-31 16:50:56.487  6110  6139 D UEI.SmartControl: ----------- loading internal config...
08-31 16:50:56.494  6110  6110 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 16:50:56.494  6110  6110 D UEI.SmartControl: QS Service version code: 201091
,08-31 16:50:56.498  6110  6110 D UEI.SmartControl: Service requested: Control
08-31 16:50:56.502  6110  6139 E UEI.SmartControl: Loading SETTINGS...
08-31 16:50:56.503  6110  6110 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 16:50:56.506  1029  1044 I ActivityManager: Killing 5025:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 16:50:56.515  6110  6139 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 16:50:56.538  6110  6138 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 16:50:56.538  6110  6138 D UEI.SmartControl: -----service ready thread exits
,08-31 16:50:56.627  6110  6110 D UEI.SmartControl: Internal service binding...
08-31 16:50:56.627  1029  1566 W libprocessgroup: failed to open /acct/uid_10112/pid_5025/cgroup.procs: No such file or directory
,08-31 16:50:57.417  1029  1878 I ActivityManager: Killing 4968:com.android.calendar/u0a13 (adj 15): empty #17
,08-31 16:50:57.507  1029  1044 W libprocessgroup: failed to open /acct/uid_10013/pid_4968/cgroup.procs: No such file or directory
,08-31 16:51:00.002  1029  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=276706401, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,08-31 16:51:00.036  2583  2583 D [Concierge]Service: onStartCommand(). Type : 9
,08-31 16:51:00.046  1594  1594 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-31 16:51:00.046  1594  1594 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 16:51:00.047  1594  1594 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 16:51:00.047  1594  1594 I [SystemUI]Clock: called onTimeUpdated()
08-31 16:51:00.048  1594  1594 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 16:51:00.048  1594  1594 I [SystemUI]DateView: called onTimeUpdated()
,08-31 16:51:00.048  1594  1594 I [SystemUI]DateView: called onTimeUpdated()
08-31 16:51:00.048  1594  1594 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 16:51:00.069  4264  6144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-31 16:51:00.102  1029  1029 D PowerManagerServiceEx: releaseWakeLockInternal: lock=276706401 [*alarm*], flags=0x0
,08-31 16:51:00.750  2116  2116 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19984
,08-31 16:51:01.486  6110  6140 D UEI.SmartControl: Internal timer expired: 1
08-31 16:51:01.486  6110  6140 D UEI.SmartControl: unbind internal service
,08-31 16:51:01.529  6110  6110 D UEI.SmartControl: Service.onUnbind: IControl
,08-31 16:51:01.532  6110  6110 D UEI.SmartControl: Service.onDestroy
08-31 16:51:01.532  6110  6110 D UEI.SmartControl: Lock is in USE false
08-31 16:51:01.532  6110  6110 D UEI.SmartControl: unbind internal service
08-31 16:51:01.532  6110  6110 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2dbfb59b
08-31 16:51:01.532  6110  6110 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 16:51:01.533  6110  6110 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 16:51:01.533  6110  6110 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 16:51:01.533  6110  6110 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 16:51:01.533  6110  6110 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 16:51:01.533  6110  6110 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 16:51:01.533  6110  6110 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 16:51:01.533  6110  6110 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 16:51:01.533  6110  6110 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.533  6110  6110 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:51:01.533  6110  6110 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 16:51:01.533  6110  6110 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.533  6110  6110 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.533  6110  6110 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 16:51:01.533  6110  6110 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 16:51:01.533  6110  6110 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2dbfb59b
08-31 16:51:01.535  6110  6110 D serial_port: close(fd = 25)
08-31 16:51:01.556  6110  6110 I UEI.SmartControl: Serial port is closed.
08-31 16:51:01.556  6110  6110 I UEI.SmartControl: Serial port is closed.
08-31 16:51:01.556  6110  6110 D UEI.SmartControl: Blaster closed
08-31 16:51:01.556  6110  6110 D UEI.SmartControl: Shut down QS...
08-31 16:51:01.556  6110  6110 D UEI.SmartControl: Stopping QS lib
08-31 16:51:01.557  6110  6110 D UEI.SmartControl: QS lib stop result = true
08-31 16:51:01.557  6110  6110 D UEI.SmartControl: Stopped QS lib
,08-31 16:51:01.581  6110  6110 D UEI.SmartControl: Stopped file observer...
08-31 16:51:01.581  6110  6110 D UEI.SmartControl: QS shutdown complete
,08-31 16:51:02.350  1029  1097 I ActivityManager: Waited long enough for: ServiceRecord{47a9b65 u0 com.google.android.gms/.wearable.service.WearableService}
,08-31 16:51:08.249  5918  5973 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 16:51:08.249  5918  5973 I jxcore-log: 
,08-31 16:51:08.252  5918  5973 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 16:51:08.252  5918  5973 I jxcore-log: 
,08-31 16:51:08.254  5918  5973 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:08.254  5918  5973 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:51:08.254  5918  5973 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:08.254  5918  5973 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:51:08.254  5918  5973 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:51:08.254  5918  5973 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:51:08.254  5918  5973 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:08.254  5918  5973 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:08.254  5918  5973 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:51:08.255  5918  5973 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:08.255  5918  5973 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:51:08.258  5918  5973 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 16:51:08.258  5918  5973 I jxcore-log: 
08-31 16:51:08.259  5918  5973 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 16:51:08.259  5918  5973 I jxcore-log: 
08-31 16:51:08.608  5918  5973 I jxcore-log: Running unit tests
08-31 16:51:08.608  5918  5973 I jxcore-log: 
08-31 16:51:08.609  5918  5973 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 16:51:08.609  5918  5973 I jxcore-log: Failed to execute UT.
08-31 16:51:08.609  5918  5973 I jxcore-log: 
08-31 16:51:08.610  5918  5973 I jxcore-log: Unit Test app is loaded
08-31 16:51:08.610  5918  5973 I jxcore-log: 
,08-31 16:51:08.618  5918  5918 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 16:51:08.629  5918  5973 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 16:51:08.629  5918  5973 I jxcore-log: 
,08-31 16:51:08.640  1029  1877 D WifiServiceImplEx: setWifiEnabled: true pid=5918, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 16:51:08.642  1029  1877 D WifiService: setWifiEnabled: true pid=5918, uid=10118
08-31 16:51:08.642  1029  1877 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 16:51:08.667  1029  1878 D WifiServiceImplEx: disconnect pid=5918, uid=10118, packageName=com.test.thalitest
08-31 16:51:08.667  1029  1044 D WifiServiceImplEx: reconnect pid=5918, uid=10118, packageName=com.test.thalitest
08-31 16:51:08.667  1029  1423 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 16:51:08.667  1029  1423 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 16:51:08.669  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 16:51:08.669  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 16:51:08.669  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-31 16:51:08.669  1029  1423 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 16:51:08.669  1029  1423 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 16:51:08.669  1029  1423 E WifiUtil: wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 16:51:08.669  1029  1423 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 16:51:08.669  1029  1423 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 16:51:08.669  1029  1423 E WifiHW  : unknown target_country: EU , set to default
08-31 16:51:08.669  1029  1423 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 16:51:08.669  1029  1423 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 16:51:08.670  1029  1423 I WifiUtil: gEnableBmps=1
08-31 16:51:08.670  1029  1566 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:51:08.671  1029  1566 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-31 16:51:08.683  1029  1111 D BluetoothManagerService: Message: 1
08-31 16:51:08.684  1029  1029 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 16:51:08.684  1029  1029 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 16:51:08.685  1029  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 16:51:08.686  1029  1029 D Ulp_jni : JNI:system_update. Event-4
08-31 16:51:08.695  5918  5973 I jxcore-log: My device name is: LGE-LG-D855
08-31 16:51:08.695  5918  5973 I jxcore-log: 
,08-31 16:51:08.738  1029  1111 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6208 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 16:51:08.775  6208  6208 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 16:51:08.776  6208  6208 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 16:51:08.776  6208  6208 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 16:51:08.776  6208  6208 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 16:51:08.834  6208  6208 D BluetoothAdapterApp: Loading JNI Library,
,08-31 16:51:08.864  1029  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 16:51:08.865   317   887 D SoftapController: Softap fwReload - Ok
08-31 16:51:08.869   317   887 D CommandListener: Setting iface cfg
08-31 16:51:08.869   317   887 D CommandListener: Trying to bring down wlan0
08-31 16:51:08.870   317   887 D CommandListener: Clearing all IP addresses on wlan0
08-31 16:51:08.871  1029  1111 D Tethering: InitialState.processMessage what=4
08-31 16:51:08.872   317  6238 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-31 16:51:08.872  1029  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 16:51:08.914  1029  1097 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6239 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 16:51:08.914  1029  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 16:51:08.947  6208  6208 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@c3212dd Instance Count = 1
08-31 16:51:08.949   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 833us total 31.575ms
08-31 16:51:08.953  6208  6208 D BluetoothAdapterApp: onCreate
08-31 16:51:08.958  6239  6239 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:08.958  6239  6239 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 16:51:08.958  6239  6239 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 16:51:08.958  6239  6239 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-31 16:51:08.959  6239  6239 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 16:51:08.959  6239  6239 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 16:51:08.969  6208  6208 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 16:51:08.969  6208  6208 D ProfileConfigQcom: Adding HeadsetService
08-31 16:51:08.970  6208  6208 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 16:51:08.970  6208  6208 D ProfileConfigQcom: Adding A2dpService
08-31 16:51:08.970  6208  6208 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 16:51:08.970  6208  6208 D ProfileConfigQcom: Adding HidService
08-31 16:51:08.970   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 20.012ms
08-31 16:51:08.970  6208  6208 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 16:51:08.970  6208  6208 D ProfileConfigQcom: Adding HealthService
08-31 16:51:08.970  6208  6208 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 16:51:08.971  6208  6208 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 16:51:08.971  6208  6208 D ProfileConfigQcom: Adding PanService
08-31 16:51:08.971  6208  6208 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 16:51:08.971  6208  6208 D ProfileConfigQcom: Adding GattService
08-31 16:51:08.971  6208  6208 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 16:51:08.971  6208  6208 D ProfileConfigQcom: Adding BluetoothMapService
08-31 16:51:08.972  6208  6208 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 16:51:08.975  1029  1423 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 16:51:08.973  6257  6257 W wpa_supplicant: type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:08.973  6257  6257 W wpa_supplicant: type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:08.994  1029  1111 D BluetoothManagerService: Message: 20
08-31 16:51:08.994  1029  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32f9fb55:true
,08-31 16:51:08.995   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 765us total 24.277ms
08-31 16:51:08.995  6208  6208 D BluetoothAdapterState: make
08-31 16:51:08.997  6257  6257 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 16:51:08.999  6208  6208 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 16:51:08.999  6208  6208 I bluedroid-qcom: init
08-31 16:51:09.000  6208  6258 I BluetoothAdapterState: Entering OffState
08-31 16:51:09.003  6208  6208 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 16:51:09.004  6208  6208 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 16:51:09.004  6208  6208 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 16:51:09.004  6208  6208 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 16:51:09.004  6208  6208 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 16:51:09.006  6208  6208 I bluedroid-qcom: get_profile_interface socket
08-31 16:51:09.006  6208  6262 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 16:51:09.006  6208  6208 I bluedroid-qcom: get_profile_interface map_client
08-31 16:51:09.003  6261  6261 W bdaddr_loader: type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:09.003  6261  6261 W bdaddr_loader: type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:09.008  6208  6262 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 16:51:09.009  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 16:51:09.009  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 16:51:09.009  6208  6262 D BluetoothAdapterProperties: Name is: G3
08-31 16:51:09.010  6261  6261 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 16:51:09.010  6261  6261 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 16:51:09.010  6261  6261 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 16:51:09.010  6261  6261 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 16:51:09.012  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 16:51:09.012  1029  1111 D BluetoothManagerService: Message: 40
08-31 16:51:09.012  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 16:51:09.014  6208  6232 I bluedroid-qcom: config_hci_snoop_log
08-31 16:51:09.015  1029  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 16:51:09.015  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
08-31 16:51:09.019  6261  6261 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 16:51:09.019  6261  6261 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 16:51:09.020  6208  6231 V LGMDMManagerInternal: Create singleton instance
,08-31 16:51:09.022  6257  6257 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 16:51:09.022  6257  6257 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-31 16:51:09.061  6208  6258 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 16:51:09.061  6208  6258 D BluetoothAdapterProperties: Setting state to 11
08-31 16:51:09.062  6208  6258 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 16:51:09.062  1029  1111 D BluetoothManagerService: Message: 60
08-31 16:51:09.063  6208  6258 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 16:51:09.063  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,08-31 16:51:09.063  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 16:51:09.065  1932  1932 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:09.067  1594  1594 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 16:51:09.068  6208  6258 D BluetoothBondStateMachine: make
08-31 16:51:09.071  6208  6258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.071  6208  6258 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 16:51:09.071  6208  6258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.071  6208  6258 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 16:51:09.072  6208  6258 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 16:51:09.073  6208  6263 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 16:51:09.074  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:09.074  6239  6239 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 16:51:09.074  6239  6239 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 16:51:09.074  6239  6239 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 16:51:09.076  5918  5918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:09.077  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-31 16:51:09.078  1029  1423 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 16:51:09.078  1029  1423 E WifiStateMachine: useWiFiOffloading() : false
08-31 16:51:09.078  1029  1423 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 16:51:09.080  1029  1423 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 16:51:09.080  1029  1423 D WifiMonitor: connecting to supplicant
08-31 16:51:09.080  1932  1932 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 16:51:09.080  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 16:51:09.083  5918  5918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:09.093  6208  6258 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 16:51:09.096  6239  6239 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 16:51:09.096  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 16:51:09.096  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 16:51:09.096  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 16:51:09.096  6239  6239 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 16:51:09.096  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 16:51:09.097  6239  6239 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 16:51:09.099  1029  1959 I ActivityManager: Killing 4674:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-31 16:51:09.106  6208  6258 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 16:51:09.134  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 16:51:09.140  6257  6257 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 16:51:09.215  1029  1983 W libprocessgroup: failed to open /acct/uid_10014/pid_4674/cgroup.procs: No such file or directory
,08-31 16:51:09.220  1029  1029 D BluetoothHeadset: Proxy object connected
,08-31 16:51:09.222  6208  6208 D HeadsetService: Received start request. Starting profile...
08-31 16:51:09.222  6208  6258 E BluetoothAdapterService: File transfer profiles supported!!
08-31 16:51:09.223  1843  1843 D BluetoothHeadset: Proxy object connected
08-31 16:51:09.225  6208  6208 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 16:51:09.225  6208  6208 D LGBluetoothHfpAdapter: Version 1.6
08-31 16:51:09.227  1843  1843 D BluetoothHeadset: Proxy object connected
08-31 16:51:09.228  1843  1843 D BluetoothHeadset: Proxy object connected
08-31 16:51:09.229  6208  6208 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 16:51:09.230  6208  6208 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 16:51:09.230  6208  6208 D HeadsetStateMachine: make
,08-31 16:51:09.231  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:09.231  6239  6239 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 16:51:09.231  6239  6239 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 16:51:09.231  6239  6239 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 16:51:09.233  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 16:51:09.235  6239  6239 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 16:51:09.235  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 16:51:09.235  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 16:51:09.235  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 16:51:09.235  6239  6239 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 16:51:09.235  6239  6239 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 16:51:09.238  6208  6258 E BluetoothAdapterService: File transfer profiles supported!!
08-31 16:51:09.244  6257  6257 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-31 16:51:09.253  6208  6208 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:51:09.253  6208  6208 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 16:51:09.258  6257  6257 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 16:51:09.258  6257  6257 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 16:51:09.264  1029  1423 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 16:51:09.265  1029  6266 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 16:51:09.265  1029  6266 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 16:51:09.265  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 16:51:09.266  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 16:51:09.266  1029  6266 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 16:51:09.266  1029  1423 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 16:51:09.266  1029  6266 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 16:51:09.267  1029  1423 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-31 16:51:09.268  1029  1423 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 16:51:09.269  1029  1423 E WifiStateMachine:  SupplicantStartingState CMD_DISCONNECT 0 0
08-31 16:51:09.273  1029  1423 E WifiStateMachine:  DefaultState CMD_DISCONNECT 0 0
08-31 16:51:09.274  1029  1913 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6267 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-31 16:51:09.275  1029  1423 E WifiStateMachine:  SupplicantStartingState CMD_RECONNECT 0 0
08-31 16:51:09.276  6208  6208 D HeadsetStateMachine: max_hf_connections = 1
08-31 16:51:09.276  6208  6208 I bluedroid-qcom: get_profile_interface handsfree
08-31 16:51:09.276  1029  1423 E WifiStateMachine:  DefaultState CMD_RECONNECT 0 0
08-31 16:51:09.277  6208  6208 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 16:51:09.278   324   324 V AudioPolicyService: registerClient() client 0xb558ac80, uid 1002
08-31 16:51:09.278   324   324 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 16:51:09.278   324   324 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 16:51:09.278   324   324 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 16:51:09.278  6208  6208 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 16:51:09.279   324  1388 V AudioFlinger: registerClient() client 0xb1433670, pid 6208
08-31 16:51:09.279   324  1383 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:09.279   324  1383 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-31 16:51:09.279  6208  6208 V ToneGenerator: Create Track: 0xb4928080
08-31 16:51:09.279  6208  6208 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 16:51:09.279  6208  6208 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 16:51:09.280   324  1388 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 16:51:09.280   324  1388 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 16:51:09.280   324  1388 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 16:51:09.280   324  1388 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 16:51:09.280  6208  6208 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 16:51:09.280  1029  1924 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:09.280  1029  1924 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:09.280   324  2143 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 16:51:09.281  1029  1423 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:09.281   324  2144 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 16:51:09.281   324  2144 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 16:51:09.281   324  2144 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 16:51:09.281   324  2144 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 16:51:09.281  1029  1423 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:09.282  1029  1423 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:09.282  1594  1611 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:09.282  1594  1611 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:09.282  1029  1423 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:09.282  1843  1858 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:09.282  1843  1858 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:09.282   324  1384 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:09.282   324  1384 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:09.283  6208  6208 V AudioSystem: getLatency() output 2, latency 50
08-31 16:51:09.283  1029  1423 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 16:51:09.283  2116  2131 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:09.283  2116  2131 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-31 16:51:09.283  3351  3367 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:09.283  3351  3367 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:09.283  1029  1423 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 16:51:09.283  6208  6232 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:09.283  6208  6232 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 16:51:09.284  1843  1859 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:09.284  1843  1859 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:09.284  1594  3063 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:09.284  1594  3063 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:09.284  1029  1423 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 16:51:09.285  1029  1423 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 16:51:09.285  1029  1423 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 16:51:09.285  1029  1760 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:09.285  1029  1760 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:09.286  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.286  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.286  1029  1423 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 16:51:09.286  1029  1423 E WifiStateMachine: useWiFiOffloading() : false
08-31 16:51:09.286  1029  1423 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 16:51:09.286  6208  6231 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:09.286  6208  6231 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
,08-31 16:51:09.287  2116  4202 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:09.287  2116  4202 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:09.287  3351  3366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:09.287  3351  3366 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:09.287  6208  6208 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 16:51:09.287  6208  6208 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 16:51:09.287  6208  6258 E BluetoothAdapterService: File transfer profiles supported!!
08-31 16:51:09.287   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 16:51:09.287   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 16:51:09.288   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 16:51:09.288   324  1389 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 16:51:09.288   324  1389 V AudioFlinger: createTrack() lSessionId: 21
08-31 16:51:09.289  6208  6208 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 16:51:09.290   324  1389 V AudioFlinger: acquiring 21 from 6208, for 6208
08-31 16:51:09.290   324  1389 V AudioFlinger:  added new entry for 21
08-31 16:51:09.290  6208  6208 V ToneGenerator: ToneGenerator INIT OK, time: 122644
08-31 16:51:09.290  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.290  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:09.291  6208  6265 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 16:51:09.291  1932  1932 D WfdService: Waiting for WifiP2p enabling
08-31 16:51:09.291  6208  6265 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 16:51:09.291  6208  6265 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 16:51:09.291  6208  6265 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 16:51:09.291   324   324 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6208
08-31 16:51:09.291   324   324 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 16:51:09.291   324   324 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 16:51:09.291   324   324 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 16:51:09.291   324   324 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 16:51:09.291   324   324 V voice   : voice_set_parameters: exit with code(0)
08-31 16:51:09.291   324   324 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 16:51:09.291   324   324 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 16:51:09.292   324   324 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 16:51:09.292   324   324 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 16:51:09.292   324   324 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 16:51:09.292   324   324 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 16:51:09.292  6208  6265 V ToneGenerator: ToneGenerator destructor
08-31 16:51:09.292  6208  6265 V ToneGenerator: stopTone
08-31 16:51:09.292  6208  6265 V ToneGenerator: Delete Track: 0xb4928080
08-31 16:51:09.292  6208  6265 V AudioTrack: ~AudioTrack, releasing session id from 6208 on behalf of 6208
08-31 16:51:09.293  1029  1878 W Process : Unable to open /proc/6276/status
08-31 16:51:09.294  1029  1029 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 16:51:09.294   324  2143 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 16:51:09.294   324  214,3 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 16:51:09.294   324  1260 V AudioPolicyService: AudioCommandThread() waking up
08-31 16:51:09.294   324  2143 V AudioFlinger: PlaybackThread::Track destructor
08-31 16:51:09.294   324  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 16:51:09.294   324  1260 V AudioPolicyManager: releaseOutput() 2
08-31 16:51:09.294   324  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 16:51:09.294   324  2143 V AudioFlinger: removeClient_l() pid 6208, calling pid 324
08-31 16:51:09.295  5918  5918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:09.295  5918  5918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:09.295  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:09.295  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:51:09.295  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:09.295  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:51:09.295  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:09.295  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:09.295  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:51:09.296  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.297  6208  6208 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 16:51:09.297   324   324 V AudioFlinger: releasing 21 from 6208 for 6208
08-31 16:51:09.297   324   324 V AudioFlinger:  decremented refcount to 0
08-31 16:51:09.297   324   324 V AudioFlinger: purging stale effects
08-31 16:51:09.297  1029  1458 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 16:51:09.297  6208  6208 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:09.297  6208  6208 V BluetoothPbapReceiver: ***********state = 11
08-31 16:51:09.297  5918  5918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:09.297  5918  5918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:51:09.298  1029  1423 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 16:51:09.298  6208  6258 E BluetoothAdapterService: File transfer profiles supported!!
08-31 16:51:09.299  1029  1423 D WifiNative-wlan0: SET update_config 1: returned true
08-31 16:51:09.299  1029  1423 D WifiConfigStore: Loading config and enabling all networks 
08-31 16:51:09.299  1029  1423 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 16:51:09.299  1029  1423 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 16:51:09.301  2134  2134 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 16:51:09.311  1029  1423 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 16:51:09.322  1029  1423 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 16:51:09.323  1029  1423 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 16:51:09.342  1029  1983 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6286 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:09.343  1029  1029 D BluetoothA2dp: Proxy object connected
08-31 16:51:09.344  6208  6208 D A2dpService: Received start request. Starting profile...
08-31 16:51:09.345  6208  6208 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 16:51:09.345  1029  1423 D WifiStateMachine: enableVerboseLogging : level 2
08-31 16:51:09.345  1029  1423 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 16:51:09.345  6208  6208 V Avrcp   : make
08-31 16:51:09.346  6208  6208 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 16:51:09.346  6208  6208 I bluedroid-qcom: get_profile_interface avrcp
08-31 16:51:09.349  6208  6258 E BluetoothAdapterService: File transfer profiles supported!!
08-31 16:51:09.350  1029  1423 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 16:51:09.350  1029  1423 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 16:51:09.350  1029  1423 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 16:51:09.350  1029  1423 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 16:51:09.351  1029  1423 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 16:51:09.351  1029  1423 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 16:51:09.351  1029  1423 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 16:51:09.351  1029  1423 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 16:51:09.352  1029  1423 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 16:51:09.352  1029  1423 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 16:51:09.353  1029  1423 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 16:51:09.353  1029  1423 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 16:51:09.353  1029  1423 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 16:51:09.354  6208  6208 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 16:51:09.356  1932  1932 D WfdsService: Supplicant Connection state is changed : true
08-31 16:51:09.357  1932  2380 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 16:51:09.357  1932  2380 D WfdsService: Set the WFDS Monitor: true
08-31 16:51:09.357  1029  1423 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 16:51:09.357  1029  1423 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 16:51:09.357  1029  1423 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 16:51:09.358  1029  1423 D WifiNative-HAL: Setting external_sim to 1
08-31 16:51:09.358  1029  1423 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 16:51:09.358  1932  2380 D WfdsMonitor: WfdsMonitorThread create
08-31 16:51:09.358  1932  2380 D WfdsMonitor: WFDS Monitor is created and started
08-31 16:51:09.358  1932  2380 D WfdsService: WiFi: Supplicant connection re-established
08-31 16:51:09.358  1029  1423 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 16:51:09.358  1029  1423 I WifiNative-HAL: startHal
08-31 16:51:09.358  1029  1423 E wifi    : getStaticLongField sWifiHalHandle 0x9886e8dc
08-31 16:51:09.358  1029  1423 E WifiHAL : Could not connect handle
08-31 16:51:09.358  1029  1423 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x901dd6
08-31 16:51:09.358  1029  1423 I WifiNative-HAL: Could not start hal
08-31 16:51:09.359  1029  1423 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 16:51:09.359  1029  1423 I WifiNative-HAL: startHal
08-31 16:51:09.359  1029  1423 E wifi    : getStaticLongField sWifiHalHandle 0x9886e85c
08-31 16:51:09.359  1029  1423 E WifiHAL : Could not connect handle
08-31 16:51:09.359  1029  1423 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301d5e
08-31 16:51:09.359  1029  1423 I WifiNative-HAL: Could not start hal
08-31 16:51:09.359  6208  6208 E AudioManager: No RCC entry present to update
08-31 16:51:09.359  1029  1423 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 16:51:09.359  6208  6208 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 16:51:09.359  1932  6296 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 16:51:09.360  1932  6296 E CtrlSupplicant: Succeed to open control connection
08-31 16:51:09.360  1932  6296 E CtrlSupplicant: Succeed to open monitor connection
08-31 16:51:09.360  1932  6296 D WfdsMonitor: Supplicant connection established
08-31 16:51:09.361  1932  2380 D WfdsService: Connected to the supplicant for wfds
08-31 16:51:09.361  6208  6208 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 16:51:09.361  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 16:51:09.361  6208  6208 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 16:51:09.363  1029  1370 V AlarmManager: RTC_WAKEUP set : Alarm{3b94cd79 type 0 when 1472655064381 com.android.vending} when 1472655064381
08-31 16:51:09.363  6208  6258 V LGMDMManager: Create singleton instance
08-31 16:51:09.365  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-31 16:51:09.369  1029  1423 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 16:51:09.369  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 16:51:09.369  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 16:51:09.370  1029  1423 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 16:51:09.372  6208  6258 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 16:51:09.400  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 16:51:09.400  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 16:51:09.402  1029  1423 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 16:51:09.402  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 16:51:09.402  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 16:51:09.403  1029  1029 D WifiHS20: hidePasspointNotification off =false
08-31 16:51:09.404  1029  1423 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 16:51:09.404  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 16:51:09.404  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 16:51:09.404  1029  1423 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 16:51:09.404  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 16:51:09.404  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 16:51:09.405  1029  1423 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 16:51:09.405  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 16:51:09.405  6257  6257 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 16:51:09.405  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.405  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.406  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 16:51:09.407  1029  1423 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 16:51:09.407  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 16:51:09.407  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 16:51:09.407  1029  1423 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 16:51:09.409  1029  1423 E WifiNative: : [122,750,198 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 16:51:09.409  1029  1423 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 16:51:09.409  1029  1423 D WifiNative-wlan0: RECONNECT: returned true
08-31 16:51:09.409  1029  1423 D WifiNative-wlan0: doString: [STATUS]
08-31 16:51:09.410  1029  1423 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 16:51:09.410  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 16:51:09.410  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 16:51:09.410  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 16:51:09.410  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 16:51:09.411  1029  1423 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-31 16:51:09.415  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:09.420  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:09.421  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:09.422  1029  1423 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 16:51:09.422  1029  1423 D WifiNative-wlan0: SET ps 1: returned true
08-31 16:51:09.423  1029  1382 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.424   317   887 D CommandListener: Setting iface cfg
08-31 16:51:09.424   317   887 D CommandListener: Trying to bring up p2p0
08-31 16:51:09.424  1029  1423 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 16:51:09.424  1029  1029 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 16:51:09.424  1029  1029 D RttService: SCAN_AVAILABLE : 3
08-31 16:51:09.424  1029  1423 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 16:51:09.424  1029  1547 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.424  1029  1547 I WifiNative-HAL: startHal
08-31 16:51:09.424  1029  1547 E wifi    : getStaticLongField sWifiHalHandle 0x94e1599c
08-31 16:51:09.424  1029  1423 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 16:51:09.425  1029  1547 E WifiHAL : Could not connect handle
08-31 16:51:09.425  1029  1547 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401ba2
08-31 16:51:09.425  1029  1547 I WifiNative-HAL: Could not start hal
08-31 16:51:09.425  1029  1423 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 16:51:09.425  1029  1548 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.425  1029  1423 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 16:51:09.425  1029  1547 E WifiScanningService: could not start HAL
08-31 16:51:09.425  1029  1423 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 16:51:09.425  1029  1382 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 16:51:09.425  1029  1423 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 16:51:09.425  1029  1382 D LGWifiP2pService: P2pEnablingState
08-31 16:51:09.425  1029  1423 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 16:51:09.426  1029  1382 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.426  1029  1382 D LGWifiP2pService: P2p socket connection successful
08-31 16:51:09.426  6257  6257 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 16:51:09.426  1029  1382 D LGWifiP2pService: P2pEnabledState
08-31 16:51:09.426  1029  1423 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 16:51:09.426  1029  1382 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 16:51:09.427  1932  1932 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 16:51:09.427  1932  1932 D WfdsService: WifiP2pState is changed : true
,08-31 16:51:09.427  1932  2380 D WfdsService: Receive the WFDS_ENABLE Method
08-31 16:51:09.427  1932  2380 D WfdsService: Set the WFDS Monitor: true
08-31 16:51:09.427  1029  1382 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 16:51:09.427  1932  2380 D WfdsService: Connected to the supplicant for wfds
08-31 16:51:09.428  1932  2380 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 16:51:09.428  6257  6257 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 16:51:09.428  1932  2380 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-31 16:51:09.428  6257  6257 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-31 16:51:09.428  1029  1382 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 16:51:09.428  1029  1382 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 16:51:09.428  1932  2380 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-31 16:51:09.428  1932  2380 D WfdsService: selectPreferredScanChannel [36]
08-31 16:51:09.429  1932  2380 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 16:51:09.429  1029  1382 D WifiNative-p2p0: SET device_name G3: returned true
08-31 16:51:09.429  1029  1382 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 16:51:09.429  1029  1382 D LGWifiP2pService: before postfix = G3
08-31 16:51:09.429  1029  1382 D WifiServerServiceExt: postfix byte check : 2
08-31 16:51:09.429  1029  1382 D LGWifiP2pService: after postfix = G3
08-31 16:51:09.429  1029  1382 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 16:51:09.429  1029  1382 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 16:51:09.429  1029  1382 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 16:51:09.430  1029  1382 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 16:51:09.430  1029  1382 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 16:51:09.430  1029  1382 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 16:51:09.430  1029  1382 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 16:51:09.430  1029  1382 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 16:51:09.430  1029  1382 D WifiNative-HAL: p2pGetDeviceAddress
08-31 16:51:09.430  1029  1382 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 16:51:09.431  1029  1382 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 16:51:09.431  1029  1382 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 16:51:09.432  1029  1382 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 16:51:09.432  1029  1382 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 16:51:09.435  1932  1932 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 16:51:09.436  1932  1932 D WfdsService: isConnected: false
08-31 16:51:09.438  1029  1423 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 16:51:09.438  1029  1423 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 16:51:09.439  1029  1423 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 16:51:09.439  6257  6257 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 16:51:09.439  1029  1382 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 16:51:09.439  1029  1382 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 16:51:09.439  1029  1382 D WifiNative-p2p0:    returned OK
08-31 16:51:09.439  1029  1382 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 16:51:09.439  1932  1932 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 16:51:09.440  1932  1932 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 16:51:09.440  1932  1932 D WfdsService: Update P2p Interface State: 3
08-31 16:51:09.440  1029  1423 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
08-31 16:51:09.440  1029  1423 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
08-31 16:51:09.440  1029  1423 E WifiStateMachine:  Dr,iverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
08-31 16:51:09.441  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-31 16:51:09.445  1029  2043 V SIM_STK : Menu title from STK is T-Mobile
08-31 16:51:09.445  1029  2043 V SIM_STK : Menu title from STK is T-Mobile
08-31 16:51:09.448  1029  1524 D WifiService: New client listening to asynchronous messages
,08-31 16:51:09.450  1029  1382 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 16:51:09.451  1029  1382 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 16:51:09.451  1029  1382 D LGWifiP2pService: InactiveState
08-31 16:51:09.451  1029  1382 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.451  1029  1382 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.451  1029  1382 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 16:51:09.451  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 16:51:09.452  6257  6257 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 16:51:09.452  6257  6257 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 16:51:09.452  6257  6257 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.452  6257  6257 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.453  1932  6296 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 16:51:09.453  1932  6296 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 16:51:09.453  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 16:51:09.453  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 16:51:09.453  1029  6266 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 16:51:09.453  1029  6266 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-31 16:51:09.453  1029  6266 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 16:51:09.453  1029  6266 E WifiMonitor: WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.453  1029  6266 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.453  1029  6266 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.453  1029  6266 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 16:51:09.453  1029  6266 E WifiMonitor: WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.453  1029  6266 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.453  1029  6266 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.453  1029  1423 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 16:51:09.454  1029  1423 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 16:51:09.454  1029  1423 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 16:51:09.454  1029  1423 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 16:51:09.454  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 16:51:09.454  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 16:51:09.454  6257  6257 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 16:51:09.455  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 16:51:09.455  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 16:51:09.455  1029  6266 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 16:51:09.455  1029  6266 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 16:51:09.455  1029  1423 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 16:51:09.455  1029  1423 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 16:51:09.455  1029  1423 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 16:51:09.455  1029  1423 D WifiNative-wlan0: doBoolean: SCAN
08-31 16:51:09.455  1029  1423 D WifiNative-wlan0: SCAN: returned false
08-31 16:51:09.456  1029  1423 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=122798  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 16:51:09.457  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 16:51:09.457  6257  6257 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 16:51:09.457  6257  6257 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 16:51:09.457  6257  6257 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.458  6257  6257 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.458  1932  6296 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 16:51:09.458  1932  6296 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 16:51:09.458  1932  6296 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 16:51:09.458  1029  1382 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 16:51:09.458  1029  1382 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: Inact,iveState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1382 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.459  1029  1029 E WifiServerServiceExt: No p2p device connected
08-31 16:51:09.459  1029  6266 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 16:51:09.459  1029  6266 E WifiMonitor: WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 16:51:09.459  1029  6266 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 16:51:09.459  1029  6266 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 16:51:09.459  1029  6266 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 16:51:09.460  1029  6266 E WifiMonitor: WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.460  1029  6266 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.460  1029  6266 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.460  1029  6266 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 16:51:09.460  1029  6266 E WifiMonitor: WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.460  1029  6266 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.460  1029  6266 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 16:51:09.461  1029  1423 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=122803  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 16:51:09.461  1029  1423 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 16:51:09.461  1029  1423 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 16:51:09.461  1029  1382 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.461  1029  1382 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:09.462  1029  1423 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 16:51:09.462  1932  2380 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 16:51:09.462  1029  1423 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 16:51:09.462  1029  1423 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 16:51:09.465 , 1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:09.465  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:09.466  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.467  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.467  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 16:51:09.468  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:09.468  1029  1029 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 16:51:09.474  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:09.494  1029  1942 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 16:51:09.499  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 16:51:09.502  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 16:51:09.503  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 16:51:09.503  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 16:51:09.503  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 16:51:09.503  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 16:51:09.503  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 16:51:09.504  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 16:51:09.504  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 16:51:09.504  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 16:51:09.504  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 16:51:09.504  6208  6208 I BluetoothA2dpServiceJni: classInitNative
08-31 16:51:09.504  6208  6208 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:51:09.504  6208  6208 D A2dpStateMachine: make
08-31 16:51:09.506  6208  6208 I bluedroid-qcom: get_profile_interface a2dp
08-31 16:51:09.506  6208  6310 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 16:51:09.507  6286  6286 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 16:51:09.507  6286  6286 W LG Account v2.2: No ProfileInfo entries
08-31 16:51:09.507  6286  6286 I LG Account v2.2: isEnabled: false
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Country: EU
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Operator: OPEN
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Ranking support: false
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Comfort support: false
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Accessory: true
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Health device: true
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Extra Pedometer: false
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Blood glucose device: false
08-31 16:51:09.508  6286  6286 I Feature : [Lifetracker]Device Number: 3
08-31 16:51:09.509  6208  6208 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:51:09.509  6208  6208 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 16:51:09.510  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.511  6208  6208 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 16:51:09.512  6208  6309 D A2dpStateMachine: Enter Disconnected: -2
08-31 16:51:09.513  6208  6208 D HidService: Received start request. Starting profile...
,08-31 16:51:09.513  6208  6208 I bluedroid-qcom: get_profile_interface hidhost
08-31 16:51:09.513  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.513  6208  6208 D HeadsetStateMachine: Proxy object connected
08-31 16:51:09.514  6208  6208 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 16:51:09.514  6208  6208 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 16:51:09.516  1843  1843 D BluetoothPhoneService.BluetoothLTECall:  call mBluetoothHeadset.phoneStateChanged()
08-31 16:51:09.516  6208  6208 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 16:51:09.519  6208  6208 D HealthService: Received start request. Starting profile...
08-31 16:51:09.519  1843  1843 W BluetoothHeadset: Proxy not attached to service
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: java.lang.Throwable
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 16:51:09.520  1843  1843 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 16:51:09.520  6208  6208 I bluedroid-qcom: get_profile_interface health
08-31 16:51:09.521  6208  6208 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 16:51:09.521  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.522  6239  6239 D BluetoothPermissionRequest: onReceive
08-31 16:51:09.523  6239  6239 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 16:51:09.525  1029  1959 V SIM_STK : Menu title from STK is T-Mobile
08-31 16:51:09.525  6208  6208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 16:51:09.526  6208  6208 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 16:51:09.527  6208  6208 D PanService: Received start request. Starting profile...
08-31 16:51:09.528  6208  6208 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 16:51:09.528  6208  6208 I bluedroid-qcom: get_profile_interface pan
08-31 16:51:09.531  6208  6208 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 16:51:09.531  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.532  6208  6208 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 16:51:09.536  6208  6265 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 16:51:09.537  1029  1111 D BluetoothManagerService: Message: 20
08-31 16:51:09.537  1029  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36ca7b04:true
08-31 16:51:09.537  6208  6265 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:51:09.537  6208  6208 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 16:51:09.537  6208  6265 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:51:09.537  6208  6208 D BtGatt.GattService: Received start request. Starting profile...
08-31 16:51:09.537  6208  6208 D BtGatt.GattService: start()
08-31 16:51:09.538  6208  6208 I bluedroid-qcom: get_profile_interface gatt
08-31 16:51:09.538  6208  6208 D BtGatt.AdvertiseManager: advertise manager created
08-31 16:51:09.543  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.544  6239  6239 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 16:51:09.544  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.544  6208  6208 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 16:51:09.545  6208  6208 V BluetoothMapService: BluetoothMapBinder()
08-31 16:51:09.545  6208  6208 D BluetoothMapService: Received start request. Starting profile...
08-31 16:51:09.545  6208  6208 D BluetoothMapService: start()
08-31 16:51:09.547  6208  6208 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 16:51:09.547  6208  6208 D BluetoothMapEmailAppObserver: createReceiver()
08-31 16:51:09.548  6208  6208 D BluetoothMapEmailAppObserver: initObservers()
08-31 16:51:09.548  6208  6208 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 16:51:09.553  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:09.555  6208  6208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 16:51:09.556  6208  6208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 16:51:09.558  6208  6208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 16:51:09.559  6208  6208 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 16:51:09.560  6208  6208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 16:51:09.562  6208  6208 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 16:51:09.563  6208  6208 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 16:51:09.563  6208  6208 V BluetoothMapService: Handler(): got msg=1
,08-31 16:51:09.565  6208  6258 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 16:51:09.565  6208  6258 I bluedroid-qcom: enable
08-31 16:51:09.565  6208  6258 I bt_hci_bdroid: init
08-31 16:51:09.566  6208  6323 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 16:51:09.566  6208  6323 I bt-btu  : btu_task pending for preload complete event
08-31 16:51:09.569  6208  6258 I bt_vendor: bt-vendor : init
08-31 16:51:09.569  6208  6258 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 16:51:09.569  6208  6258 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 16:51:09.569  6208  6258 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 16:51:09.569  6208  6258 D bt_userial_mct: userial_init
08-31 16:51:09.569  6208  6258 D bt_hci_bdroid: set_power 1
08-31 16:51:09.569  6208  6258 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 16:51:09.569  6208  6258 I bt_vendor: Starting hciattach daemon
08-31 16:51:09.569  6208  6258 I bt_vendor: try to set true
08-31 16:51:09.563  6326  6326 W sh      : type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:09.563  6326  6326 W sh      : type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:09.579  1029  1877 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6327 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 16:51:09.581  6329  6329 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-31 16:51:09.587  6267  6321 W FormManager: Network not available. Please check & try again.
08-31 16:51:09.589  6267  6322 V FormManager: Network unavailable.
08-31 16:51:09.594  6208  6208 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:09.596  6208  6208 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 16:51:09.597  6208  6208 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 16:51:09.597  6208  6208 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 16:51:09.597  6208  6208 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:09.597  6208  6208 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-31 16:51:09.617  6351  6351 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 16:51:09.622  6352  6352 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-31 16:51:09.633  1029  1924 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6355 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 16:51:09.634  6354  6354 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 16:51:09.638  6267  6322 V FormManager: Network unavailable.
08-31 16:51:09.642  6364  6364 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-31 16:51:09.649  6371  6371 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 16:51:09.656  6373  6373 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-31 16:51:09.662  1029  1877 I ActivityManager: Killing 5536:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-31 16:51:09.668  6355  6355 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 16:51:09.669  6376  6376 I libmdmdetect: ESOC framework not supported
08-31 16:51:09.670  6376  6376 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-31 16:51:09.674  6376  6376 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 16:51:09.674  6376  6376 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 16:51:09.674  6376  6376 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 16:51:09.674  6376  6376 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 16:51:09.674  6376  6376 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 16:51:09.674  6376  6376 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 16:51:09.674  6376  6376 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 16:51:09.683  6327  6327 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 16:51:09.725  5823  5823 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-31 16:51:09.747  1029  1045 W libprocessgroup: failed to open /acct/uid_10004/pid_5536/cgroup.procs: No such file or directory
,08-31 16:51:09.750  1029  1045 I ActivityManager: Killing 5661:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-31 16:51:09.864  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 16:51:09.865  1029  6266 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 16:51:09.865  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 16:51:09.865  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
,08-31 16:51:09.866  6257  6257 E wpa_supplicant: USIM:  scard_init function
08-31 16:51:09.869  6257  6257 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 16:51:09.872  1029  6266 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 16:51:09.872  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 16:51:09.873  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 16:51:09.874  1029  1924 W libprocessgroup: failed to open /acct/uid_10008/pid_5661/cgroup.procs: No such file or directory
08-31 16:51:09.874  1029  1423 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-31 16:51:09.876  1029  1423 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-31 16:51:09.876  1029  1423 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-31 16:51:09.876  1029  1423 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-31 16:51:09.876  1029  1423 I WifiNative-HAL: startHal
08-31 16:51:09.876  1029  1423 E wifi    : getStaticLongField sWifiHalHandle 0x9886e8cc
08-31 16:51:09.876  1029  1423 E WifiHAL : Could not connect handle
08-31 16:51:09.877  1029  1423 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x2020ba
08-31 16:51:09.877  1029  1423 I WifiNative-HAL: Could not start hal
08-31 16:51:09.877  1029  1423 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 16:51:09.884  1029  1423 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=123226  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 16:51:09.885  1029  1423 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=123227  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 16:51:09.886  1029  1877 I ActivityManager: Killing 5696:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-31 16:51:09.892  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:09.898  1029  1524 D WifiService: New client listening to asynchronous messages
,08-31 16:51:09.915  6239  6239 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:51:09.916  6239  6239 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 16:51:09.920  6239  6239 D WiFiOffLoadUpdatePriority: remove : truetruetrue
08-31 16:51:09.969  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:09.969  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:09.970  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:09.972  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.972  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.972  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-31 16:51:09.983  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 16:51:09.983  6257  6257 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 16:51:09.983  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 16:51:09.983  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 16:51:09.983  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 16:51:09.984  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 16:51:09.984  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-31 16:51:09.990  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:09.990  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:09.992  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.992  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:09.993  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:09.993  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 16:51:09.996  1029  1983 W libprocessgroup: failed to open /acct/uid_10011/pid_5696/cgroup.procs: No such file or directory
08-31 16:51:09.996  1029  1423 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-31 16:51:09.997  1029  1423 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-31 16:51:09.997  1029  1423 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=123339  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 16:51:09.998  1029  1423 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=123340  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 16:51:09.999  1029  1423 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123341
08-31 16:51:09.999  1029  1423 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123341
08-31 16:51:09.999  1029  1423 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123341
08-31 16:51:10.000  1029  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 16:51:10.000  1029  1423 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123342
08-31 16:51:10.000  6257  6257 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:51:10.000  6257  6257 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 16:51:10.000  1029  1423 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123342
08-31 16:51:10.001  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 16:51:10.001  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 16:51:10.001  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 16:51:10.001  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:51:10.001  1029  6266 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:51:10.001  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 16:51:10.001  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 16:51:10.001  1029  6266 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 16:51:10.002  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=,NG700]
08-31 16:51:10.002  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 16:51:10.002  1029  1423 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=123344  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 16:51:10.003  1029  1423 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=123346  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 16:51:10.004  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:10.004  1029  1029 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 16:51:10.004  1029  1423 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=123346  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 16:51:10.005  1029  1423 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=123347  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 16:51:10.006  1029  1423 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123348
08-31 16:51:10.006  1029  1423 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123348
08-31 16:51:10.007  1029  1423 D WifiNative-wlan0: doString: [STATUS]
08-31 16:51:10.007  1029  6266 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 16:51:10.007  1029  6266 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-31 16:51:10.008  1029  1423 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 16:51:10.010  1029  1423 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 16:51:10.016  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:10.016  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:10.016  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 16:51:10.019  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:10.019  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:10.019  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 16:51:10.019  1029  1423 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 16:51:10.019  1029  1423 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-31 16:51:10.020  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:10.020  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 16:51:10.023  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:10.023  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:10.023  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 16:51:10.024  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:10.026  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:10.026  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:10.027  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:10.029  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:10.029  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:10.029  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:10.029  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 16:51:10.029  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:10.030  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:10.039  1029  1423 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-31 16:51:10.039  1029  1532 D ConnectivityService: Got NetworkAgent Messenger
08-31 16:51:10.039  1029  1423 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 16:51:10.040  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 16:51:10.040  1029  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 16:51:10.040  1029  1532 D ConnectivityService: NetworkAgent connected
08-31 16:51:10.042  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 16:51:10.042  1029  1423 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 16:51:10.043  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:10.043  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:10.045  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:10.052  1029  1423 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 16:51:10.052  1029  1423 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 16:51:10.052  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 16:51:10.052  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 16:51:10.052  1029  1423 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 16:51:10.058  1029  1423 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 16:51:10.060   317   887 D CommandListener: Setting iface cfg
08-31 16:51:10.064  1029  1423 E WifiStateMachine: Start Dhcp Watchdog 1
,08-31 16:51:10.065  1029  1423 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=123407  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 16:51:10.065  1029  1423 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=123407  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 16:51:10.066  1029  1423 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=123408  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 16:51:10.067  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:10.067  1029  1029 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 16:51:10.068  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:10.068  1029  1029 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 16:51:10.068  1029  1423 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=123410  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-31 16:51:10.069  1029  1423 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=123411  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 16:51:10.069  1029  1423 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=123411  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 16:51:10.070  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:10.070  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:10.070  1029  1423 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:10.071  1029  1423 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:10.071  1029  1423 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:10.071  1029  1423 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 16:51:10.072  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
08-31 16:51:10.072  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
08-31 16:51:10.072  1029  1423 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
08-31 16:51:10.072  1029  1423 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 16:51:10.073  1029  6386 D DhcpStateMachine: StoppedState
08-31 16:51:10.073  1029  6386 D DhcpStateMachine: StoppedState{ when=-9ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:10.073  1029  6386 D DhcpStateMachine: WaitBeforeStartState
08-31 16:51:10.080  1029  1423 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 16:51:10.080  6239  6239 D WiFiOffLoadUpdatePriority: remove1
08-31 16:51:10.081  6239  6239 V WiFiOffLoadSharedPrefsUtils: save remove
08-31 16:51:10.083  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-518712446] from screen [on:0 period:-518712446]
08-31 16:51:10.084  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-518712445]
08-31 16:51:10.084  1029  1423 I WifiNative-HAL: startHal
08-31 16:51:10.084  1029  1423 E wifi    : getStaticLongField sWifiHalHandle 0x9886e8bc
08-31 16:51:10.084  1029  1423 E WifiHAL : Could not connect handle
08-31 16:51:10.084  1029  1423 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701e2a
08-31 16:51:10.084  1029  1423 I WifiNative-HAL: Could not start hal
08-31 16:51:10.084  1029  1423 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 16:51:10.087  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:10.088  1029  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-31 16:51:10.088  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.089  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.089  1029  1423 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.089  1029  1423 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.089  1029  1423 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 16:51:10.091  6239  6239 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
,08-31 16:51:10.091  6239  6239 D WiFiOffLoadBroadcast: S: false, R: false
08-31 16:51:10.091  1029  1423 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.092  1029  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-31 16:51:10.092  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:10.092  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 16:51:10.094  1029  1029 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:10.094  1029  1029 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 16:51:10.094  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-31 16:51:10.094  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-31 16:51:10.095  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 16:51:10.195  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 16:51:10.196  1029  1423 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 16:51:10.196  1029  1423 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 16:51:10.197  1029  1423 D WifiNative-wlan0: SET ps 0: returned true
08-31 16:51:10.198  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
,08-31 16:51:10.198  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 16:51:10.199  1029  1423 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 16:51:10.200  1029  1382 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@321f22fc target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:10.200  1029  1382 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@321f22fc target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:10.200  1029  6386 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:10.202  1029  6386 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 16:51:10.203  1029  1423 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 16:51:10.203  1029  1423 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 16:51:10.203  1029  1423 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 16:51:10.204  1029  1423 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-31 16:51:10.205  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-31 16:51:10.207  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-31 16:51:10.208  1029  1423 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-31 16:51:10.211  6239  6239 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
08-31 16:51:10.211  6239  6239 D WiFiOffLoadUpdatePriority: connected SSID: null
08-31 16:51:10.212  6239  6239 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
,08-31 16:51:10.218  1029  2024 D WifiServiceImplEx: addOrUpdateNetwork pid=6239, uid=1000, packageName=android.uid.system:1000
08-31 16:51:10.221  1029  2024 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
08-31 16:51:10.223  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
08-31 16:51:10.224  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
08-31 16:51:10.225  1029  1423 E WifiStateMachine:  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
,08-31 16:51:10.226  1029  1423 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
08-31 16:51:10.227  1029  1423 D WifiServerServiceExt: addOrUpdateNetwork: mThisIsFirstEnableing = false
,08-31 16:51:10.228  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 ssid 4e47373030
08-31 16:51:10.279  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 ssid 4e47373030: returned true
08-31 16:51:10.279  1029  1423 E WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
08-31 16:51:10.279  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 16:51:10.280  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 16:51:10.280  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
08-31 16:51:10.280  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 key_mgmt WPA-PSK: returned true
08-31 16:51:10.280  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 proto WPA RSN
08-31 16:51:10.281  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 proto WPA RSN: returned true
08-31 16:51:10.281  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
08-31 16:51:10.281  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 pairwise TKIP CCMP: returned true
08-31 16:51:10.281  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
08-31 16:51:10.282  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
08-31 16:51:10.282  1029  1423 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 priority 300
,08-31 16:51:10.283  1029  1423 D WifiNative-wlan0: SET_NETWORK 0 priority 300: returned true
08-31 16:51:10.283  1029  1423 E WifiConfigStore: will read network variables netId=0
08-31 16:51:10.289  1029  1423 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
08-31 16:51:10.289  1029  1423 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
08-31 16:51:10.291  6239  6239 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
08-31 16:51:10.291  6239  6239 D WiFiOffLoadUpdatePriority: configuration updated: 0
08-31 16:51:10.292  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
08-31 16:51:10.293  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
08-31 16:51:10.293  1029  1423 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
08-31 16:51:10.293  1029  1423 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-31 16:51:10.309  1029  1423 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 16:51:10.311  6239  6239 D WiFiOffLoadUpdatePriority: configuration saved: true
08-31 16:51:10.312  1029  1044 I ActivityManager: Killing 5715:com.android.contacts/u0a19 (adj 15): empty #17
08-31 16:51:10.406  1029  6386 D DhcpStateMachine: DHCPV4 request on wlan0
,08-31 16:51:10.408  1029  6386 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 16:51:10.408  1029  6386 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 16:51:10.420  1029  1877 W libprocessgroup: failed to open /acct/uid_10019/pid_5715/cgroup.procs: No such file or directory
08-31 16:51:10.423  6390  6390 W dhcpcd  : type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 16:51:10.423  6390  6390 W dhcpcd  : type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:10.449  6390  6390 I dhcpcd  : version 5.5.6 starting
,08-31 16:51:10.450  6390  6390 E dhcpcd  : get_duid: m
08-31 16:51:10.450  6390  6390 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 16:51:10.451  6390  6390 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 16:51:10.459  6327  6327 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 16:51:10.461  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:51:10.470  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:10.488  3217  3217 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 16:51:10.488  3217  3217 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 16:51:10.490  6267  6395 V FormManager: Network unavailable.
08-31 16:51:10.490  3217  3217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 16:51:10.493  3217  3217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 16:51:10.495  6267  6394 W FormManager: Network not available. Please check & try again.
08-31 16:51:10.503  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 16:51:10.506  6267  6395 V FormManager: Network unavailable.
08-31 16:51:10.508  6327  6327 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 16:51:10.509  3217  6398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 16:51:10.516  3217  6399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 16:51:10.516  3217  6399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 16:51:10.532  6390  6390 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 16:51:10.532  6390  6390 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 16:51:10.532  6390  6390 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-31 16:51:10.534  6327  6327 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 16:51:10.534  6327  6327 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 16:51:10.537  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 16:51:10.539  6390  6390 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 16:51:10.540  6390  6390 D dhcpcd  : wlan0: sending REQUEST (xid 0xb267e2d8), next in 4.71 seconds
,08-31 16:51:10.543  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:10.587  1029  2024 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6407 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 16:51:10.589  6390  6390 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-31 16:51:10.639  6407  6407 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 16:51:10.642  6390  6390 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 16:51:10.642  6390  6390 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 16:51:10.642  6390  6390 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 16:51:10.643  6390  6390 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 16:51:10.643  6390  6390 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 16:51:10.643  6390  6390 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 16:51:10.643  6390  6390 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 16:51:10.643  6390  6390 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 16:51:10.646  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.647  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.648  1029  1423 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.650  1029  1423 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.651  1029  1423 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 16:51:10.652  1029  1423 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 16:51:10.653  1029  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-31 16:51:10.665  6407  6407 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-31 16:51:10.685  6407  6407 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-31 16:51:10.685  6407  6407 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 16:51:10.686  6407  6407 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 16:51:10.686  6407  6407 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 16:51:10.686  6407  6407 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 16:51:10.687  6407  6407 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 16:51:10.691  6407  6407 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 16:51:10.691  6376  6377 E QC-QMI  : qmi_client [6376] 13: failed to locate client data
08-31 16:51:10.691   459   459 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 16:51:10.691   459   459 E QC-QMI  : QMUX qmux_client_id=13 not found in qmux client list, unable to remove
08-31 16:51:10.696  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:10.698  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 16:51:10.718  6407  6407 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 16:51:10.719  6407  6407 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-31 16:51:10.722  6061  6061 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 16:51:10.722  6061  6061 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-31 16:51:10.723  6407  6407 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 16:51:10.727  6061  6061 V [BNRBootReceiver]: Boot Receiver Return
08-31 16:51:10.730  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:10.737  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:10.741  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 16:51:10.747  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:10.747  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:10.748  6407  6407 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 16:51:10.751  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 16:51:10.756  6239  6239 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 16:51:10.759  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:10.765  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:10.773  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:10.778  6444  6444 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 16:51:10.779  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:10.779  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:10.785  6407  6407 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 16:51:10.787  6447  6447 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-31 16:51:10.787  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:10.793  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:10.798  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:10.803  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:10.803  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:10.804  6407  6407 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 16:51:10.806  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:10.806  6239  6239 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 16:51:10.806  6239  6239 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 16:51:10.806  6239  6239 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 16:51:10.806  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-31 16:51:10.807  6239  6239 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 16:51:10.807  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 16:51:10.807  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 16:51:10.807  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 16:51:10.807  6239  6239 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 16:51:10.807  6239  6239 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 16:51:10.807  6239  6239 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 16:51:10.810  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:10.814  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:10.817  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:10.822  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:10.822  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:10.822  6407  6407 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 16:51:10.824  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:10.827  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:10.831  6208  6258 I bt_vendor: bluetooth satus is on
08-31 16:51:10.831  6208  6258 D bt_hci_bdroid: preload
08-31 16:51:10.831  6208  6325 D bt_userial_mct: userial_open(port:0)
08-31 16:51:10.831  6208  6325 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 16:51:10.831  6208  6325 I bt_vendor: Done intiailizing UART
,08-31 16:51:10.831  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:10.831  6208  6325 I bt_vendor: Done intiailizing UART
08-31 16:51:10.831  6208  6325 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 16:51:10.831  6208  6325 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 16:51:10.831  6208  6453 D bt_userial_mct: Entering userial_read_thread()
08-31 16:51:10.832  6208  6323 I bt-btu  : btu_task received preload complete event
08-31 16:51:10.832  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 16:51:10.832  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 16:51:10.834  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 16:51:10.834  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:10.834  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:10.835  6407  6407 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 16:51:10.835  6208  6323 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 16:51:10.835  6208  6323 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 16:51:10.835  6208  6323 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 16:51:10.835  6208  6323 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 16:51:10.836  6208  6323 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 16:51:10.837  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:10.841  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:10.844  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:10.847  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 16:51:10.847  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:10.848  6407  6407 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 16:51:10.849  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:10.854  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:10.856  6208  6323 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 16:51:10.856  6208  6323 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0236061 
08-31 16:51:10.856  6208  6323 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0236061 
08-31 16:51:10.857  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:10.861  6208  6262 E bt-btif : Calling BTA_HhEnable
08-31 16:51:10.861  6208  6262 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 16:51:10.861  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 16:51:10.861  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 16:51:10.861  6208  6262 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 16:51:10.861  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 16:51:10.862  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 16:51:10.862  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 16:51:10.862  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:10.862  6208  6262 D BluetoothAdapterProperties: Name is: G3
08-31 16:51:10.862  1029  1029 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 16:51:10.863  1029  1029 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 16:51:10.863  6208  6262 D BluetoothAdapterProperties: Scan Mode:20
08-31 16:51:10.863  6208  6262 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:51:10.863  6208  6262 D bt_hci_bdroid: postload
08-31 16:51:10.863  6208  6325 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 16:51:10.863  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:10.864  6208  6323 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 16:51:10.865  5918  5918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:10.865  6407  6407 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 16:51:10.868  6208  6323 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 16:51:10.868  6208  6323 W bt-smp  : Plain text(LSB ~ MSB) = 9d 1e 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 16:51:10.868  6208  6323 W bt-smp  : Encrypted text(LSB ~ MSB) = 3e 7b 4e d9 5f a0 cc ef de 55 22 95 93 72 72 5a 
08-31 16:51:10.868  6208  6323 W bt-btm  : Stopping oneshot timer
08-31 16:51:10.868  6208  6325 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 16:51:10.868  6208  6325 D bt_hci_bdroid: Used up Tx Cmd credits
,08-31 16:51:10.868  6208  6325 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 16:51:10.869  6208  6325 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 16:51:10.869  6208  6453 E bt_mct  : hci lib postload completed
08-31 16:51:10.870  6208  6262 D bte_conf: Device ID record 1 : primary
08-31 16:51:10.870  6208  6262 D bte_conf:   vendorId            = 00c4
08-31 16:51:10.870  6208  6262 D bte_conf:   vendorIdSource      = 0001
08-31 16:51:10.870  6208  6262 D bte_conf:   product             = 13a1
08-31 16:51:10.870  6208  6262 D bte_conf:   version             = 1000
08-31 16:51:10.870  6208  6262 D bte_conf:   clientExecutableURL = 
08-31 16:51:10.870  6208  6262 D bte_conf:   serviceDescription  = 
08-31 16:51:10.870  6208  6262 D bte_conf:   documentationURL    = 
08-31 16:51:10.870  6208  6262 D bte_conf: bte_load_did_conf no section named DID2.
08-31 16:51:10.871  6407  6407 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 16:51:10.872  6208  6262 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 16:51:10.872  6208  6258 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 16:51:10.872  6208  6258 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:51:10.872  6208  6258 D BluetoothAdapterProperties: State =  11
08-31 16:51:10.872  6208  6258 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 16:51:10.872  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 16:51:10.872  6208  6258 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 16:51:10.873  6208  6258 D BluetoothAdapterProperties: Setting state to 12
08-31 16:51:10.873  6208  6258 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 16:51:10.873  1029  1111 D BluetoothManagerService: Message: 60
08-31 16:51:10.873  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 16:51:10.873  6208  6262 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 16:51:10.873  1029  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 5 receivers.
08-31 16:51:10.873  1029  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:51:10.873  1029  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:51:10.873  1843  1859 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:51:10.873  6208  6258 I BluetoothAdapterState: Entering On State
08-31 16:51:10.874  1843  2470 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:51:10.874  6407  6407 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 16:51:10.863  6455  6455 W sh      : type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:10.875  6208  6258 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 16:51:10.875  6208  6258 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 16:51:10.875  6208  6258 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 16:51:10.873  6455  6455 W sh      : type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:10.876  6208  6258 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 16:51:10.876  1843  4150 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:51:10.877  6208  6323 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 16:51:10.877  6208  6323 W bt-smp  : Plain text(LSB ~ MSB) = fc c5 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 16:51:10.877  6208  6323 W bt-smp  : Encryp,ted text(LSB ~ MSB) = 51 18 e6 6e ea fd b2 b8 3e 6b 2f a1 22 40 cc 7c 
08-31 16:51:10.877  6208  6323 W bt-btm  : Stopping oneshot timer
08-31 16:51:10.878  1029  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 16:51:10.878  1029  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-31 16:51:10.883  1594  1594 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 16:51:10.885  1932  1932 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:10.887  1029  1029 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 16:51:10.888  5918  5918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 16:51:10.888  1029  1111 D BluetoothManagerService: Message: 40
08-31 16:51:10.888  1029  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 16:51:10.891  5918  5918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 16:51:10.895  5918  5918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 16:51:10.895  1932  2202 D LGBluetoothAPIService: Message: 1
08-31 16:51:10.895  1932  2202 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 16:51:10.896  6208  6323 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 16:51:10.897  6208  6323 W bt-smp  : Plain text(LSB ~ MSB) = e6 88 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 16:51:10.897  6208  6323 W bt-smp  : Encrypted text(LSB ~ MSB) = 6d 00 05 af 45 ad e9 98 7e f0 af 9d 19 a5 56 db 
08-31 16:51:10.897  6208  6323 W bt-btm  : Stopping oneshot timer
08-31 16:51:10.897  6208  6208 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:10.898  6208  6208 D BluetoothMapService: STATE_ON
08-31 16:51:10.900  1932  2202 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 16:51:10.907  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
,08-31 16:51:10.907  6208  6208 V BluetoothPbapService: Pbap Service onCreate
08-31 16:51:10.907  6208  6208 V BluetoothPbapService: Starting PBAP service
08-31 16:51:10.910  5918  5918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:10.910  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:10.910  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 16:51:10.910  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:10.910  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:10.910  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:10.910  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:10.910  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:51:10.912  6208  6208 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 16:51:10.912  6208  6208 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:10.912  6208  6208 V BluetoothPbapService: state: 12
08-31 16:51:10.912  6239  6239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 16:51:10.913  6208  6208 V BluetoothMapService: Handler(): got msg=1
08-31 16:51:10.914  6208  6208 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 16:51:10.915  6208  6462 D BluetoothMapMasInstance: MAS initSocket()
08-31 16:51:10.915  6208  6462 D BluetoothMapMasInstance:   masId = 00
08-31 16:51:10.915  6208  6462 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 16:51:10.915  6208  6462 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 16:51:10.915  6208  6462 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 16:51:10.916  6208  6208 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 16:51:10.917  6208  6208 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 16:51:10.917  5918  5918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:51:10.918  1029  2024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:51:10.919  6208  6462 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:51:10.920  6208  6208 V BluetoothPbapService: Handler(): got msg=1
08-31 16:51:10.920  6208  6462 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 16:51:10.920  1932  1932 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 16:51:10.920  1932  2202 D LGBluetoothAPIService: Message: 100
08-31 16:51:10.920  1932  2202 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 16:51:10.920  6208  6462 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 16:51:10.920  6208  6462 D BluetoothMapMasInstance: Accepting socket connection...
08-31 16:51:10.921  6208  6208 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 16:51:10.922  6208  6464 V BluetoothPbapService: Pbap Service initSocket
08-31 16:51:10.923  6208  6208 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 16:51:10.923  1029  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:51:10.923  6208  6208 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:10.923  6208  6208 V BluetoothPbapReceiver: ***********state = 12
08-31 16:51:10.923  6208  6464, W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:51:10.924  6208  6464 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 16:51:10.924  6208  6464 V BluetoothPbapService: Succeed to create listening socket 
08-31 16:51:10.924  6208  6464 V BluetoothPbapService: Accepting socket connection...
,08-31 16:51:10.925  6463  6463 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 16:51:10.925  6208  6323 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 16:51:10.925  6208  6323 W bt-smp  : Plain text(LSB ~ MSB) = a3 17 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 16:51:10.925  6208  6323 W bt-smp  : Encrypted text(LSB ~ MSB) = f6 e0 30 f6 9f c0 d9 fb b0 5f 18 78 71 6c 81 3c 
08-31 16:51:10.925  6208  6323 W bt-btm  : Stopping oneshot timer
08-31 16:51:10.925  6208  6258 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 16:51:10.930  2134  2134 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 16:51:10.931  6208  6262 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:51:10.931  6208  6262 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-31 16:51:10.931  2134  2134 D c       : Getting all permits...
08-31 16:51:10.931  2134  2134 D a       : Opening database...
08-31 16:51:10.932  6208  6262 D BluetoothAdapterProperties: Scan Mode:21
08-31 16:51:10.932  6208  6262 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 16:51:10.934  5918  5918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:10.935  6239  6239 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 16:51:10.935  6208  6323 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 16:51:10.935  6208  6323 W bt-smp  : Plain text(LSB ~ MSB) = e8 fe 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 16:51:10.935  6208  6323 W bt-smp  : Encrypted text(LSB ~ MSB) = 91 7c 05 71 a5 8b 41 30 82 3c 32 ea 99 2a cb 97 
08-31 16:51:10.936  6208  6323 W bt-btm  : Stopping oneshot timer
08-31 16:51:10.936  2134  2134 D a       : Opening database auth.proximity.permit_store...
08-31 16:51:10.937  2134  2134 D a       : Closing database...
08-31 16:51:10.937  1029  1111 D BluetoothManagerService: Message: 30
08-31 16:51:10.939  6239  6239 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 16:51:10.941  1029  1111 D BluetoothManagerService: Message: 30
,08-31 16:51:10.944  1029  1111 D BluetoothManagerService: Message: 30
08-31 16:51:10.947  1029  1111 D BluetoothManagerService: Message: 30
08-31 16:51:10.949  6239  6239 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 16:51:10.950  6239  6239 D BluetoothMap: Create BluetoothMap proxy object
08-31 16:51:10.951  1029  1111 D BluetoothManagerService: Message: 30
08-31 16:51:10.954  6407  6407 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 16:51:10.954  6407  6407 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 16:51:10.955  1029  1111 D BluetoothManagerService: Message: 30
08-31 16:51:10.957  6208  6208 V BluetoothPbapService: Pbap Service onBind
08-31 16:51:10.957  6239  6239 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 16:51:10.959  6407  6407 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 16:51:10.959  6407  6407 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 16:51:10.959  6407  6407 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 16:51:10.959  6407  6407 V SoundPool: doLoad: loading sample sampleID=1
08-31 16:51:10.960  6407  6468 V SoundPool: Start decode
08-31 16:51:10.960  6407  6468 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 16:51:10.960  6407  6407 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 16:51:10.960  6239  6239 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-31 16:51:10.961   324  2143 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 16:51:10.961   324  2143 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 16:51:10.961   324  2143 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 16:51:10.961   324  2143 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 16:51:10.961   324  2143 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 16:51:10.961   324  2143 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 16:51:10.961   324  2143 V MediaPlayerService: player type = 3
08-31 16:51:10.961   324  2143 V AwesomePlayer: AwesomePlayer create()
08-31 16:51:10.961   324  2143 V AwesomePlayer: reset_l() 
08-31 16:51:10.961   324  2143 V AwesomePlayer: cancelPlayerEvents
08-31 16:51:10.961   324  2143 V AwesomePlayer: setAudioSink() 
08-31 16:51:10.961   324  2143 V AwesomePlayer: reset_l() 
08-31 16:51:10.961   324  2143 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-31 16:51:10.961   324  2143 V AudioCache: ignored
08-31 16:51:10.961   324  2143 V AwesomePlayer: cancelPlayerEvents
08-31 16:51:10.961   324  2143 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 16:51:10.961   324  2143 V AwesomePlayer: setDataSource_l dataSource
08-31 16:51:10.961   324  2143 V LGParserOSAL: SniffLGParser start
08-31 16:51:10.961   324  2143 V LGParserOSAL: MainType:5, SubType=0
08-31 16:51:10.961   324  2143 V LGParserOSAL: #### check Mime : application/ogg
08-31 16:51:10.961   324  2143 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 16:51:10.961   324  2143 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 16:51:10.962  6239  6239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-31 16:51:10.964  6110  6110 D UEI.SmartControl: QS Service created
08-31 16:51:10.966  6407  6407 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 16:51:10.967  6407  6407 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 16:51:10.967  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 16:51:10.969  6239  6239 D DockEventReceiver: finishStartingService: stopping service
08-31 16:51:10.970  6239  6239 D BluetoothA2dp: Proxy object connected
08-31 16:51:10.970  6239  6239 D A2dpProfile: Bluetooth service connected
08-31 16:51:10.973  6407  6407 V LGMDMManager: Create singleton instance
08-31 16:51:10.977  6110  6110 I UEI.SmartControl: Service initServices...
08-31 16:51:10.977  6110  6110 D UEI.SmartControl: QS start get config
08-31 16:51:10.986   324  2143 V LGParserOSAL: supported mime: application/ogg
08-31 16:51:10.986   324  2143 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 16:51:10.987   324  2143 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 16:51:10.987   324  2143 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 16:51:10.987   324  2143 V AwesomePlayer: AudioTrack Setting
08-31 16:51:10.987   324  2143 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 16:51:10.987   324  2143 V AwesomePlayer: setAudioSource() 
08-31 16:51:10.987   324  2143 V MediaPlayerService: prepare
,08-31 16:51:10.987   324  2143 V AwesomePlayer: prepareAsync_l() 
08-31 16:51:10.987   324  6472 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 16:51:10.987   324  2143 V MediaPlayerService: wait for prepare
08-31 16:51:10.987   324  6472 V AwesomePlayer: initAudioDecoder() 
08-31 16:51:10.987   324  6472 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 16:51:10.987   324  6472 V AudioSystem: isOffloadSupported()
08-31 16:51:10.987   324  6472 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 16:51:10.987   324  6472 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,08-31 16:51:10.987   324  6472 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 16:51:10.987   324  6472 V AwesomePlayer: getUseOffload() = 0 
08-31 16:51:10.987   324  6472 V OMXCodec: OMXCodec::Create
08-31 16:51:10.987   324  6472 V OMXCodec: findMatchingCodecs()
08-31 16:51:10.988   324  6472 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 16:51:10.988   324  6472 V OMXCodec: matchingCodecs.size()=1
08-31 16:51:10.988   324  6472 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 16:51:10.988   324  6472 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 16:51:10.988   324  6472 V LGCodecAdapter: LG Codec Adapter start
08-31 16:51:10.988   324  6472 V OMXCodec: OMXCodec Createtor
08-31 16:51:10.988   324  6472 V OMXCodec: setComponentRole
08-31 16:51:10.989   324  6472 V OMXCodec: configureCodec protected=0
08-31 16:51:10.989   324  6472 V LGCodecAdapter: called getLGCodecSpecificData
08-31 16:51:10.989   324  6472 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 16:51:10.989   324  6472 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 16:51:10.989   324  6472 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 16:51:10.989   324  6472 V LGCodecOSAL: Not support LGCodec
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 16:51:10.989   324  6472 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 16:51:10.989   324  6472 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 16:51:10.989   324  6472 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 16:51:10.989   324  6472 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 16:51:10.989   324  6472 V AudioSystem: isOffloadSupported()
08-31 16:51:10.989   324  6472 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 16:51:10.989   324  6472 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 16:51:10.989   324  6472 V OMXCodec: init()
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 16:51:10.989   324  6472 V OMXCodec: allocateBuffers
08-31 16:51:10.989   324  6472 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on input port
08-31 16:51:10.989   324  6472 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb2e0 on output port
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb420 on output port
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb510 on output port
08-31 16:51:10.989   324  6472 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb5b0 on output port
08-31 16:51:10.989   324  6472 V OMXCodec: init() mAsyncCompletion wait!!! 
08-,31 16:51:10.995   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 16:51:10.995   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 16:51:10.995   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 16:51:10.995   324  6472 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 16:51:10.995   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 16:51:10.995   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 16:51:10.995   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 16:51:10.995   324  6472 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 16:51:10.995   324  6472 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 16:51:10.996   324  6472 V AudioCache: notify(0xb1432480, 5, 0, 0)
08-31 16:51:10.996   324  6472 V AudioCache: ignored
08-31 16:51:10.996   324  6472 V AudioCache: notify(0xb1432480, 1, 0, 0)
08-31 16:51:10.996   324  6472 V AudioCache: prepared
08-31 16:51:10.996   324  2143 V AudioCache: wait - success
08-31 16:51:10.996   324  2143 V MediaPlayerService: start
08-31 16:51:10.996   324  2143 V AwesomePlayer: play_l() 
08-31 16:51:10.996   324  2143 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 16:51:10.996   324  2143 V AwesomePlayer: createAudioPlayer_l
08-31 16:51:10.996   324  2143 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 16:51:10.996   324  2143 V AwesomePlayer: startAudioPlayer_l() 
08-31 16:51:10.996   324  2143 D AudioPlayer: start of Playback, useOffload 0
08-31 16:51:10.996   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 16:51:10.996   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7,
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782816
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044783136
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044783376
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044783536
,08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 16:51:10.997   324  6474 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-31 16:51:10.997   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb510 on output port
08-31 16:51:10.998   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb420 on output port
08-31 16:51:10.998   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb2e0 on output port
08-31 16:51:10.998   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb6f0 on output port
08-31 16:51:10.998   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 16:51:10.998   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 16:51:10.998   324  2143 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 16:51:10.998   324  2143 V AudioCache: notify(0xb1432480, 6, 0, 0)
,08-31 16:51:10.998   324  2143 V AudioCache: ignored
08-31 16:51:10.999   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:10.999   324  6475 V AudioCache: memcpy(0xaf104000, 0xb040a000, 4096)
08-31 16:51:10.999   324  2143 V MediaPlayerService: wait for playback complete
08-31 16:51:10.999   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:10.999   324  6475 V AudioCache: memcpy(0xaf105000, 0xb040a000, 4096)
08-31 16:51:10.999   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:10.999   324  6475 V AudioCache: memcpy(0xaf106000, 0xb040a000, 4096)
08-31 16:51:11.000   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.000   324  6475 V AudioCache: memcpy(0xaf107000, 0xb040a000, 4096)
08-31 16:51:11.000   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.000   324  6475 V AudioCache: memcpy(0xaf108000, 0xb040a000, 4096)
08-31 16:51:11.000   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.000   324  6475 V AudioCache: memcpy(0xaf109000, 0xb040a000, 4096)
08-31 16:51:11.000   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.000   324  6475 V AudioCache: memcpy(0xaf10a000, 0xb040a000, 4096)
08-31 16:51:11.001   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.001   324  6475 V AudioCache: memcpy(0xaf10b000, 0xb040a000, 4096)
08-31 16:51:11.001   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.001   324  6475 V AudioCache: memcpy(0xaf10c000, 0xb040a000, 4096)
08-31 16:51:11.001   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.001   324  6475 V AudioCache: memcpy(0xaf10d000, 0xb040a000, 4096)
08-31 16:51:11.001   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.001   324  6475 V AudioCache: memcpy(0xaf10e000, 0xb040a000, 4096)
08-31 16:51:11.002   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.002   324  6475 V AudioCache: memcpy(0xaf10f000, 0xb040a000, 4096)
08-31 16:51:11.002   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.002   324  6475 V AudioCache: memcpy(0xaf110000, 0xb040a000, 4096)
08-31 16:51:11.002   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.002   324  6475 V AudioCache: memcpy(0xaf111000, 0xb040a000, 4096)
08-31 16:51:11.002   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.002   324  6475 V AudioCache: memcpy(0xaf112000, 0xb040a000, 4096)
08-31 16:51:11.003   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.003   324  6475 V AudioCache: memcpy(0xaf113000, 0xb040a000, 4096)
08-31 16:51:11.003   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.003   324  6475 V AudioCache: memcpy(0xaf114000, 0xb040a000, 4096)
08-31 16:51:11.003   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.003   324  6475 V AudioCache: memcpy(0xaf115000, 0xb040a000, 4096)
08-31 16:51:11.003   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.003   324  6475 V AudioCache: memcpy(0xaf116000, 0xb040a000, 4096)
08-31 16:51:11.004   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.004   324  6475 V AudioCache: memcpy(0xaf117000, 0xb040a000, 4096)
08-31 16:51:11.004   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.004   324  6475 V AudioCache: memcpy(0xaf118000, 0xb040a000, 4096)
08-31 16:51:11.004   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.004   324  6475 V AudioCache: memcpy(0xaf119000, 0xb040a000, 4096)
08-31 16:51:11.005   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.005   324  6475 V AudioCache: memcpy(0xaf11a000, 0xb040a000, 4096)
08-31 16:51:11.005   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.005   324  6475 V AudioCache: memcpy(0xaf11b000, 0xb040a000, 4096)
08-31 16:51:11.005   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.005   324  6475 V AudioCache: memcpy(0xaf11c000, 0xb040a000, 4096)
08-31 16:51:11.006   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.006   324  6475 V AudioCache: memcpy(0xaf11d000, 0x,b040a000, 4096)
08-31 16:51:11.006   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.006   324  6475 V AudioCache: memcpy(0xaf11e000, 0xb040a000, 4096)
08-31 16:51:11.007   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.007   324  6475 V AudioCache: memcpy(0xaf11f000, 0xb040a000, 4096)
08-31 16:51:11.007   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.007   324  6475 V AudioCache: memcpy(0xaf120000, 0xb040a000, 4096)
08-31 16:51:11.007   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.007   324  6475 V AudioCache: memcpy(0xaf121000, 0xb040a000, 4096)
08-31 16:51:11.008   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.008   324  6475 V AudioCache: memcpy(0xaf122000, 0xb040a000, 4096)
08-31 16:51:11.008   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.008   324  6475 V AudioCache: memcpy(0xaf123000, 0xb040a000, 4096)
08-31 16:51:11.009   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.009   324  6475 V AudioCache: memcpy(0xaf124000, 0xb040a000, 4096)
08-31 16:51:11.009   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.009   324  6475 V AudioCache: memcpy(0xaf125000, 0xb040a000, 4096)
08-31 16:51:11.009   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.009   324  6475 V AudioCache: memcpy(0xaf126000, 0xb040a000, 4096)
08-31 16:51:11.010   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.010   324  6475 V AudioCache: memcpy(0xaf127000, 0xb040a000, 4096)
08-31 16:51:11.010  1029  6386 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-31 16:51:11.010   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.010   324  6475 V AudioCache: memcpy(0xaf128000, 0xb040a000, 4096)
08-31 16:51:11.010   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.011   324  6475 V AudioCache: memcpy(0xaf129000, 0xb040a000, 4096)
08-31 16:51:11.011  1029  6386 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 16:51:11.011  1029  6386 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 16:51:11.011  1029  6386 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 16:51:11.011   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.011   324  6475 V AudioCache: memcpy(0xaf12a000, 0xb040a000, 4096)
08-31 16:51:11.011  1029  6386 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 16:51:11.011  1029  6386 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 16:51:11.011  1029  6386 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-31 16:51:11.011  1029  6386 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 16:51:11.011   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.011   324  6475 V AudioCache: memcpy(0xaf12b000, 0xb040a000, 4096)
08-31 16:51:11.012  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 16:51:11.012  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 16:51:11.012  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 16:51:11.012  1029  1382 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:11.012   324  6475 V AudioCache: write(0xb040a000, 4096)
,08-31 16:51:11.012   324  6475 V AudioCache: memcpy(0xaf12c000, 0xb040a000, 4096)
08-31 16:51:11.012  1029  1382 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:11.012  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 16:51:11.012  1029  1423 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 16:51:11.012  1029  1423 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 16:51:11.012  6257  6257 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 16:51:11.012   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.012   324  6475 V AudioCache: memcpy(0xaf12d000, 0xb040a000, 4096)
08-31 16:51:11.012  1029  1423 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 16:51:11.013  1029  1423 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 16:51:11.013  1029  6386 D DhcpStateMachine: RunningState
08-31 16:51:11.013   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.013   324  6475 V AudioCache: memcpy(0xaf12e000, 0xb040a000, 4096)
,08-31 16:51:11.013   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.013   324  6475 V AudioCache: memcpy(0xaf12f000, 0xb040a000, 4096)
08-31 16:51:11.014   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.014   324  6475 V AudioCache: memcpy(0xaf130000, 0xb040a000, 4096)
08-31 16:51:11.014   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.014   324  6475 V AudioCache: memcpy(0xaf131000, 0xb040a000, 4096)
08-31 16:51:11.014   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.014   324  6475 V AudioCache: memcpy(0xaf132000, 0xb040a000, 4096)
08-31 16:51:11.015   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.015   324  6475 V AudioCache: memcpy(0xaf133000, 0xb040a000, 4096)
08-31 16:51:11.015   324  6475 V AudioCache: write(0xb040a000, 4096)
,08-31 16:51:11.015   324  6475 V AudioCache: memcpy(0xaf134000, 0xb040a000, 4096)
08-31 16:51:11.016   324  6475 V AudioCache: write(0xb040a000, 4096)
08-31 16:51:11.016   324  6475 V AudioCache: memcpy(0xaf135000, 0xb040a000, 4096)
08-31 16:51:11.016   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 16:51:11.016   324  6475 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 16:51:11.016   324  6475 V AwesomePlayer: postAudioEOS() 
,08-31 16:51:11.016   324  6475 V AudioCache: write(0xb040a000, 280)
08-31 16:51:11.016   324  6475 V AudioCache: memcpy(0xaf136000, 0xb040a000, 280)
08-31 16:51:11.017   324  6472 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
,08-31 16:51:11.017   324  6472 V AwesomePlayer: onStreamDone
08-31 16:51:11.017   324  6472 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 16:51:11.018   324  6472 V AudioCache: notify(0xb1432480, 2, 0, 0)
08-31 16:51:11.018   324  6472 V AudioCache: playback complete
08-31 16:51:11.018   324  6472 V AwesomePlayer: pause_l() 
08-31 16:51:11.018   324  6472 V AudioCache: notify(0xb1432480, 7, 0, 0)
08-31 16:51:11.018   324  6472 V AudioCache: ignored
08-31 16:51:11.018   324  6472 V AwesomePlayer: cancelPlayerEvents
08-31 16:51:11.018   324  2143 V AudioCache: wait - success
08-31 16:51:11.018   324  2143 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 16:51:11.018   324  6472 D AudioPlayer: Pause Playback at 1068125
08-31 16:51:11.018   324  2143 V AwesomePlayer: reset_l() 
08-31 16:51:11.018   324  2143 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-31 16:51:11.018   324  2143 V AudioCache: ignored
08-31 16:51:11.018   324  2143 V AwesomePlayer: cancelPlayerEvents
08-31 16:51:11.018   324  2143 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 16:51:11.018   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 16:51:11.018   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 16:51:11.018   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 16:51:11.018   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 0
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb6f0 on port 1
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb2e0 on port 1
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb420 on port 1
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb510 on port 1
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 16:51:11.019   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 16:51:11.019   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 16:51:11.020   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 16:51:11.020   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 16:51:11.020   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 16:51,:11.020   324  6474 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 16:51:11.020   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 16:51:11.020   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 16:51:11.020   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 16:51:11.020   324  2143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 16:51:11.020   324  2143 D AudioPlayer: AudioPlayer releasing audio source
08-31 16:51:11.020   324  2143 D AudioPlayer: AudioPlayer done releasing audio source
08-31 16:51:11.020   324  2143 V AwesomePlayer: reset_l() 
08-31 16:51:11.020   324  2143 V AwesomePlayer: cancelPlayerEvents
08-31 16:51:11.020   324  2143 V AwesomePlayer: ~AwesomePlayer call
08-31 16:51:11.021   324  2143 V AwesomePlayer: reset_l() 
08-31 16:51:11.021   324  2143 V AwesomePlayer: cancelPlayerEvents
08-31 16:51:11.021  6407  6468 V SoundPool: close(31)
08-31 16:51:11.021  6407  6468 V SoundPool: pointer = 0xa0028000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 16:51:11.029  1029  1423 D WifiNative-wlan0: SET ps 1: returned true
08-31 16:51:11.030  1029  1423 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 16:51:11.030  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 16:51:11.030  1029  1423 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 16:51:11.031  1029  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-31 16:51:11.031  1029  1532 D ConnectivityService: ignoring duplicate network state non-change
,08-31 16:51:11.033  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:11.033  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:11.033  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 16:51:11.034  1029  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 16:51:11.035  1029  1532 D ConnectivityService: Adding iface wlan0 to network 100
,08-31 16:51:11.038  1029  1423 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 16:51:11.039  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:11.039  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:11.039  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:11.041  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:11.041  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:11.041  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 16:51:11.042  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 16:51:11.043  1932  1932 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 16:51:11.044  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:11.044  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:11.044  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 16:51:11.044  1029  1029 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 16:51:11.047  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:11.047  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:11.047  1029  1029 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 16:51:11.048  6239  6239 D BluetoothHeadset: Proxy object connected
08-31 16:51:11.049  6239  6239 D HeadsetProfile: Bluetooth service connected
08-31 16:51:11.050  6239  6239 D BluetoothInputDevice: Proxy object connected
08-31 16:51:11.051  6239  6239 D HidProfile: Bluetooth service connected
08-31 16:51:11.051  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 16:51:11.051  1029  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 16:51:11.051  1029  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-31 16:51:11.052  1029  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-31 16:51:11.052  1029  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-31 16:51:11.053  1029  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 16:51:11.053  1029  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-31 16:51:11.053  1029  1532 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-31 16:51:11.054  1029  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 16:51:11.054  1029  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:11.054  1029  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:11.054  1029  6385 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:11.054  1029  6385 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
,08-31 16:51:11.055  1029  6385 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:11.055  1029  6385 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 16:51:11.057  1029  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-31 16:51:11.057  1029  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:11.058  1029  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:11.058  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:11.058  1594  1594 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:11.058  1029  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 16:51:11.058  1029  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.058  1029  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 16:51:11.058  1029  1532 D ConnectivityService: currentScore = 0, newScore = 20
08-31 16:51:11.059  1029  1532 D ConnectivityService:    accepting network in place of null
08-31 16:51:11.059  1029  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.059  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:11.059  1029  1423 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.059  1029  1423 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:11.059  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 16:51:11.059   317  6479 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 16:51:11.060  1843  1843 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.060  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 16:51:11.061  1029  1532 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-31 16:51:11.062  6239  6239 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:51:11.062  6239  6239 D PanProfile: Bluetooth service connected
08-31 16:51:11.063  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:11.064  6239  6239 D BluetoothMap: Proxy object connected
08-31 16:51:11.064  6239  6239 D MapProfile: Bluetooth service connected
08-31 16:51:11.064  6239  6239 D BluetoothMap: getConnectedDevices()
08-31 16:51:11.065  6208  6232 V BluetoothMapService: getConnectedDevices()
08-31 16:51:11.065  6239  6239 D BluetoothPbap: Proxy object connec,ted
08-31 16:51:11.066  1594  1594 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 16:51:11.066  6239  6239 D PbapServerProfile: Bluetooth service connected
08-31 16:51:11.066  6239  6239 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 16:51:11.066  1029  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 16:51:11.066  1029  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 16:51:11.066  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:11.067  1029  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 16:51:11.067  1029  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:11.067  1029  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 16:51:11.068  1029  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 16:51:11.068  1029  1029 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 16:51:11.068  1029  1029 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 16:51:11.069  1029  1029 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 16:51:11.069  1029  1029 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 16:51:11.069  1029  1029 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-31 16:51:11.070  1029  1532 D ConnectivityService: validation of new default Network = false
08-31 16:51:11.070   317  6480 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 16:51:11.070  1029  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 16:51:11.070  1029  1532 D DSQN    : enableDataServiceNotify 
08-31 16:51:11.070  1029  1532 D DSQN    : start dsqn bin
08-31 16:51:11.070   317  6480 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-31 16:51:11.071   317  6480 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
08-31 16:51:11.071  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:521
08-31 16:51:11.071   317  6482 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 16:51:11.071   317  6482 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-31 16:51:11.071  1029  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 16:51:11.072  1594  1594 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:11.072  1594  1594 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 16:51:11.072  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:11.073  6239  6239 D BluetoothPermissionRequest: onReceive
08-31 16:51:11.079  1029  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:11.079  1029  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.079  1029  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:11.079  1029  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:11.079  6239  6239 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 16:51:11.079  1594  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 16:51:11.073  6483  6483 W dsqn    : type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:11.073  6483  6483 W dsqn    : type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:11.079  6239  6239 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 16:51:11.089  6483  6483 E DSQN    : DSQN ssw
08-31 16:51:11.092  1029  1381 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 16:51:11.095  6239  6239 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 16:51:11.105  6208  6208 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 16:51:11.106  6208  6208 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 16:51:11.108  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:11.111  1594  1594 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 16:51:11.111  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:11.112  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:11.112  6208  6208 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 16:51:11.120   317  6479 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 16:51:11.124  6208  6208 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 16:51:11.124  6208  6208 V BtOppService: onCreate
,08-31 16:51:11.128  6208  6208 V BluetoothOppNotification: send message
08-31 16:51:11.130  6208  6208 V BtOppService: Starting RfcommListener
08-31 16:51:11.131  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 16:51:11.134  6208  6208 D BluetoothOppPreference: Dumping Names:  
08-31 16:51:11.134  6208  6208 D BluetoothOppPreference: {}
08-31 16:51:11.134  6208  6208 D BluetoothOppPreference: Dumping Channels:  
08-31 16:51:11.134  6208  6208 D BluetoothOppPreference: {}
08-31 16:51:11.134  6208  6208 V BtOppService: onStartCommand
08-31 16:51:11.135  6208  6492 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 16:51:11.136  6208  6208 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:11.137  6208  6208 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 16:51:11.137  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:11.137  6208  6492 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 16:51:11.138  6208  6489 V BtOppService: Deleted complete outbound shares, number =  0
08-31 16:51:11.138   317  6482 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
08-31 16:51:11.138  6208  6492 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d115e86 on behalf of 
08-31 16:51:11.139  6208  6492 V BluetoothOppNotification: update too frequent, put in queue
,08-31 16:51:11.140  6208  6489 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 16:51:11.140  6208  6489 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 16:51:11.143  6208  6208 V BluetoothOppNotification: new notify threadi!
08-31 16:51:11.144  6208  6208 V BluetoothOppNotification: send delay message
08-31 16:51:11.144  6208  6208 V BtOppService: start RfcommListener
08-31 16:51:11.146  6208  6208 V BtOppService: RfcommListener started
08-31 16:51:11.146  6208  6208 V BtOppService: ContentObserver received notification
08-31 16:51:11.146  6208  6208 V BtOppService: ContentObserver received notification
08-31 16:51:11.147  6208  6494 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 16:51:11.147  6208  6493 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-31 16:51:11.151  6208  6492 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 16:51:11.151  6208  6492 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 16:51:11.152  1029  1566 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:51:11.153  6208  6492 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cd64347 on behalf of 
08-31 16:51:11.153  6208  6494 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:51:11.153  6208  6493 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fa47774 on behalf of 
08-31 16:51:11.153  6208  6494 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-31 16:51:11.153  6208  6489 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d24649d on behalf of 
08-31 16:51:11.154  6208  6493 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 16:51:11.154  6208  6494 V BtOppRfcommListener: Started RFCOMM listener....
08-31 16:51:11.154  6208  6494 I BtOppRfcommListener: Accept thread started.
08-31 16:51:11.154  6208  6494 V BtOppRfcommListener: Accepting connection...
08-31 16:51:11.155  6208  6493 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 16:51:11.155   317  6479 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-31 16:51:11.155  6208  6493 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d94dd12 on behalf of 
08-31 16:51:11.156  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:11.156  6208  6208 V BluetoothFtpService: Ftp Service onCreate
08-31 16:51:11.156  6208  6208 I BluetoothFtpService: Ftp Service onCreate
08-31 16:51:11.156  6208  6493 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 16:51:11.156  6208  6208 V BluetoothFtpService: Ftp Service onStartCommand
08-31 16:51:11.156  6208  6208 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:11.156  6208  6208 V BluetoothFtpService: Starting Listening on sockets
08-31 16:51:11.156  6208  6208 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 16:51:11.156  6208  6208 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 16:51:11.156  6208  6208 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 16:51:11.156  6208  6208 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:11.156  6208  6208 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 16:51:11.157  6208  6208 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 16:51:11.157  6208  6208 V BluetoothFtpService: Handler(): got msg=1
08-31 16:51:11.159  6208  6208 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 16:51:11.159  6208  6208 V BluetoothFtpService: Ftp Service initSocket
08-31 16:51:11.160  1029  2043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 16:51:11.162  6208  6208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:51:11.163  6208  6208 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-31 16:51:11.163  6208  6208 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 16:51:11.164  6208  6495 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 16:51:11.165  6208  6493 V BluetoothOppNotification: outbound notification was removed.
08-31 16:51:11.165  6208  6493 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 16:51:11.166  6208  6493 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c4b96e0 on behalf of 
08-31 16:51:11.167  6208  6493 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 16:51:11.167  6208  6492 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 16:51:11.173  6208  6208 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e86684c
08-31 16:51:11.173  6208  6208 V BluetoothSapService: Sap Service onCreate
,08-31 16:51:11.177  6208  6493 V BluetoothOppNotification: inbound notification was removed.
08-31 16:51:11.178  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:11.178  6208  6208 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:11.178  6208  6208 V BluetoothSapService: state: 12
08-31 16:51:11.178  6208  6208 V BluetoothSapService: Starting SAP server process
08-31 16:51:11.178  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:11.173  6496  6496 W sapd    : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:11.173  6496  6496 W sapd    : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 16:51:11.179  6208  6208 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 16:51:11.182  6407  6407 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 16:51:11.183   317   886 D LGDataListener: argv[0]=dsqncommand
08-31 16:51:11.183   317   886 D LGDataListener: argv[1]=wlan0
08-31 16:51:11.183   317   886 D LGDataListener: argv[2]=1
08-31 16:51:11.183   317   886 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 16:51:11.183  1029  1109 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 16:51:11.183  1029  1109 D DSQN    : start to monitor internet connection
08-31 16:51:11.184  6208  6497 V BluetoothSapService: Sap Service initRfcommSocket
08-31 16:51:11.186  6496  6496 V BT_SAP  : Event pipe created
08-31 16:51:11.186  6496  6496 V BT_SAP  : create_server_socket qcom.sap.server
08-31 16:51:11.186  6496  6496 V BT_SAP  : created socket fd 6
08-31 16:51:11.188  1029  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:51:11.188  6208  6497 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:51:11.189  6208  6493 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-31 16:51:11.190  6208  6497 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-31 16:51:11.190  6208  6497 V BluetoothSapService: Succeed to create listening socket 
08-31 16:51:11.190  6208  6497 V BluetoothSapService: Accepting socket connection...
08-31 16:51:11.190  6208  6493 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3083410c on behalf of 
08-31 16:51:11.192  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:11.195  1029  6481 D LocSvc_java: NTP server : europe.pool.ntp.org
08-31 16:51:11.196  1029  6481 D LocSvc_java: NTP server returned: 1472655070953 (Wed Aug 31 16:51:10 GMT+02:00 2016) reference: 124537 certainty: 28 system time offset: -242
08-31 16:51:11.196  1029  6481 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-31 16:51:11.196  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:11.206  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
08-31 16:51:11.209  1029  6385 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 14:51:10 GMT], X-Android-Received-Millis=[1472655071209], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472655071183]}
08-31 16:51:11.209  1029  6385 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 16:51:11.209  1029  6385 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 16:51:11.210  1029  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-31 16:51:11.210  1029  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-31 16:51:11.210  1029  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:11.210  1029  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:11.210  1029  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 16:51:11.210  1029  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-31 16:51:11.210  1029  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:11.210  1029  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.210  1029  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:11.210  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:11.210  1029  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-31 16:51:11.210  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:11.210  1029  1532 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.210  1594  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 16:51:11.211  1029  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 16:51:11.211  1029  1423 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.211  6407  6407 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 16:51:11.211  1029  1423 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:11.211  1843  1843 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.211  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-31 16:51:11.214  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 16:51:11.218  6327  6327 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 16:51:11.221  6327  6327 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 16:51:11.223  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:11.226  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:11.229  1594  1594 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 16:51:11.229  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:11.230  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 16:51:11.230  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:11.230  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 16:51:11.231  6407  6407 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 16:51:11.232  6407  6407 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 16:51:11.232  6407  6407 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 16:51:11.246  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 16:51:11.248  6327  6327 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 16:51:11.248  6327  6327 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 16:51:11.251  6239  6239 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 16:51:11.254  6239  6239 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:11.259  6407  6407 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 16:51:11.259  6407  6407 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 16:51:11.260  6407  6407 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 16:51:11.261  6407  6407 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 16:51:11.261  6407  6407 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 16:51:11.308  6110  6110 I UEI.SmartControl: Supports setup maps: true
,08-31 16:51:11.310  6110  6110 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 16:51:11.310  6110  6110 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 16:51:11.310  6110  6110 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 16:51:11.310  6110  6110 I UEI.SmartControl: ### init IR Blaster...
08-31 16:51:11.314  6110  6110 D serial_port: Configuring serial port
08-31 16:51:11.314  6110  6110 E UEI.SmartControl: UEIBLaster setting for 616
08-31 16:51:11.314  6110  6110 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 16:51:11.314  6110  6110 I UEI.SmartControl: configuring settings for MAXQ616
08-31 16:51:11.314  6110  6110 I UEI.SmartControl: Get version...
08-31 16:51:11.317  1029  1423 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 16:51:11.317  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 16:51:11.317  1029  1423 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 16:51:11.317  1029  1423 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 16:51:11.318  1029  1423 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 16:51:11.318  1029  1423 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 16:51:11.318  1029  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
08-31 16:51:11.319  1029  1532 D ConnectivityService: identical MTU - not setting
08-31 16:51:11.319  1029  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 16:51:11.319  1029  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:11.319  1029  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:11.319  1029  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:11.319  1029  1532 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:11.320  1594  2036 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:11.330  6110  6500 D UEI.SmartControl: serial port data available: 21,
08-31 16:51:11.355  6110  6110 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 16:51:11.355  6110  6110 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 16:51:11.355  6110  6110 I UEI.SmartControl: QS saving settings...
08-31 16:51:11.356  6110  6110 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 16:51:11.372  6110  6500 D UEI.SmartControl: serial port data available: 4
,08-31 16:51:11.405  6110  6503 I UEI.SmartControl: Device manager: loading config....
,08-31 16:51:11.406  6110  6503 D UEI.SmartControl: ----------- loading internal config...
08-31 16:51:11.406  6110  6110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 16:51:11.409  6110  6110 E UEI.SmartControl: Services init done
08-31 16:51:11.409  6110  6110 D UEI.SmartControl: QS Service init finished
08-31 16:51:11.411  6110  6110 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 16:51:11.411  6110  6110 D UEI.SmartControl: QS Service version code: 201091
08-31 16:51:11.412  6110  6110 D UEI.SmartControl: Service requested: Control
08-31 16:51:11.414  6110  6503 E UEI.SmartControl: Loading SETTINGS...
08-31 16:51:11.417  6110  6110 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 16:51:11.421  6110  6110 D UEI.SmartControl: Internal service binding...
,08-31 16:51:11.423  6407  6407 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 16:51:11.426  6110  6125 I UEI.SmartControl: ------ IControl API: 11
08-31 16:51:11.426  6110  6125 D UEI.SmartControl: File observer start...
08-31 16:51:11.426  6110  6125 E UEI.SmartControl: IR Port is disabled: false
08-31 16:51:11.426  6110  6125 D UEI.SmartControl: Starting file observer...
08-31 16:51:11.427  6110  6503 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 16:51:11.427  6110  6125 I UEI.SmartControl: Registering callback...
08-31 16:51:11.428  6110  6126 I UEI.SmartControl: ------ IControl API: 19
08-31 16:51:11.428  6110  6126 I UEI.SmartControl: Registering Services Ready callback...
08-31 16:51:11.444  6110  6502 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 16:51:11.444  6110  6502 D UEI.SmartControl: -----service ready thread exits
08-31 16:51:11.445  6407  6423 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 16:51:11.445  6407  6465 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 16:51:11.445  6407  6465 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 16:51:11.447  6407  6407 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 16:51:11.447  6407  6407 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 16:51:11.448  6110  6125 I UEI.SmartControl: ------ IControl API: 8
,08-31 16:51:11.449  6407  6407 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 16:51:11.450  6407  6407 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 16:51:11.450  6407  6407 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 16:51:11.450  6407  6407 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 16:51:11.451  6407  6407 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 16:51:11.451  6407  6407 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 16:51:11.454  6407  6407 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 16:51:11.457  6407  6407 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 16:51:11.458  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 16:51:11.460  6407  6407 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 16:51:11.461  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-31 16:51:11.463  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 16:51:11.464  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 16:51:11.465  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 16:51:11.467  6407  6407 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472655071466]
08-31 16:51:11.470  6407  6407 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 16:51:11.476  1029  1913 I ActivityManager: Killing 5754:com.lge.email/u0a23 (adj 15): empty #17
,08-31 16:51:11.506  6407  6505 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 16:51:11.597  1029  1937 W libprocessgroup: failed to open /acct/uid_10023/pid_5754/cgroup.procs: No such file or directory
,08-31 16:51:11.603  6407  6407 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-31 16:51:11.604  6407  6407 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 16:51:11.609  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 16:51:11.610  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 16:51:11.611  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 16:51:11.612  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-31 16:51:11.614  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 16:51:11.630  6407  6407 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 16:51:12.125  5918  5973 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:51:12.125  5918  5973 I jxcore-log: 
,08-31 16:51:12.148  6208  6208 V BluetoothOppNotification: new notify threadi!
,08-31 16:51:12.156  6208  6208 V BluetoothOppNotification: send delay message
08-31 16:51:12.156  6208  6512 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 16:51:12.166  6208  6512 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fc8a55 on behalf of 
08-31 16:51:12.168  6208  6512 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 16:51:12.170  6208  6512 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 16:51:12.172  6208  6512 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@306afc6a on behalf of 
08-31 16:51:12.173  6208  6512 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-31 16:51:12.180  6208  6512 V BluetoothOppNotification: outbound notification was removed.
08-31 16:51:12.180  6208  6512 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 16:51:12.182  6208  6512 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a71f55b on behalf of 
08-31 16:51:12.183  6208  6512 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 16:51:12.189  6208  6512 V BluetoothOppNotification: inbound notification was removed.
08-31 16:51:12.189  6208  6512 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-31 16:51:12.191  6208  6512 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1aa961f8 on behalf of 
08-31 16:51:12.579  5918  5973 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:51:12.579  5918  5973 I jxcore-log: 
,08-31 16:51:12.605  5918  5973 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 16:51:12.605  5918  5973 I jxcore-log: 
,08-31 16:51:13.093  1029  1423 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-518709435] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 16:51:13.095  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-518709433] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 16:51:13.095  1029  1423 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 16:51:13.111  1594  1594 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 16:51:13.966  5918  5973 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:51:13.966  5918  5973 I jxcore-log: 
,08-31 16:51:14.045  1029  1441 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-31 16:51:14.071  1029  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:14.073  1029  1094 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:14.080  1029  1111 D Tethering: MasterInitialState.processMessage what=3
08-31 16:51:14.086   317  6514 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 16:51:14.086   317  6514 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-31 16:51:14.096  5115  5115 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 16:51:14.101  5115  5144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 16:51:14.104  5918  5918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:14.104  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:14.104  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 16:51:14.104  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:14.104  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:14.104  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 16:51:14.104  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 16:51:14.104  5918  5918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 16:51:14.105  5918  5918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 16:51:14.115  5217  5217 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-31 16:51:14.123   317  6514 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-31 16:51:14.134  1029  1094 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:14.136  1029  1818 D AlarmManagerService: Setting time of day to sec=1472655073
08-31 16:51:13.893  1029  1818 W AlarmManagerService: Unable to set rtc to 1472655073: Invalid argument
,08-31 16:51:13.930  1932  1932 I SecureClockService: Intent.ACTION_TIME_CHANGED 
08-31 16:51:13.932  2696  2696 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
08-31 16:51:13.932  1594  1594 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
08-31 16:51:13.933  2696  2696 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-08-31 16:51:13...... Request
08-31 16:51:13.933  2696  2696 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 72, new day : false...... Request
08-31 16:51:13.933  2696  2696 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 72
08-31 16:51:13.933  2696  2696 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 6
08-31 16:51:13.933  2696  2696 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-08-31 16:51:13
08-31 16:51:13.933  1594  1594 I LgeClockWidgetControlView: time changed, timezoneChanged : false
08-31 16:51:13.934  1594  1594 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 16:51:13.939  1029  1989 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
08-31 16:51:13.940  2025  2025 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=31 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,08-31 16:51:13.942  2025  2025 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 31
08-31 16:51:13.945  2025  2025 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 31
08-31 16:51:13.945  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 16:51:13.962  1808  6526 I CheckinService: active receiver: enabled
,08-31 16:51:13.964  1808  6526 I CheckinService: Preparing to send checkin request
08-31 16:51:13.965  1808  6526 I EventLogService: Accumulating logs since 1472654266134
08-31 16:51:14.011  5918  5973 I jxcore-log: ERROR runTests: 
08-31 16:51:14.011  5918  5973 I jxcore-log: 
,08-31 16:51:14.016  5918  5973 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:14.016  5918  5973 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-31 16:51:14.052  1029  1094 I art     : Explicit concurrent mark sweep GC freed 81574(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.581ms total 114.734ms
08-31 16:51:14.052  5918  5973 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _functionName: 'loadFile',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _lineNumber: '26',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _columnNumber: '11',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:51:14.052  5918  5973 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _functionName: '',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _lineNumber: '38',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _columnNumber: '7',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:51:14.052  5918  5973 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _functionName: '',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _lineNumber: '35',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _columnNumber: '3',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:51:14.052  5918  5973 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _lineNumber: '621',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _columnNumber: '8',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:51:14.052  5918  5973 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _lineNumber: '651',
08-31 16:51:14.052  5918  5973 I jxcore-log:     _columnNumber: '1',
08-31 16:51:14.052  5918  5973 I jxcore-log:    
08-31 16:51:14.052  5918  5973 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:51:14.052  5918  5973 I jxcore-log: 
08-31 16:51:14.052  5918  5973 E jxcore-log: Error: 
08-31 16:51:14.052  5918  5973 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqMan,agerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:14.052  5918  5973 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:51:14.052  5918  5973 E jxcore-log: 
08-31 16:51:14.053  1029  1094 E GpsLocationProvider: No APN found to select.
08-31 16:51:14.054  5918  5973 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 16:51:14.054  5918  5973 I jxcore-log: 
08-31 16:51:14.056  5918  5973 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:51:14.056  5918  5973 I jxcore-log: 
08-31 16:51:14.056  2583  2583 D [Concierge]Service: onStartCommand(). Type : 9
08-31 16:51:14.057  5918  5973 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 16:51:14.057  5918  5973 I jxcore-log: 
08-31 16:51:14.064  2134  2134 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:14.077   317  6533 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 16:51:14.078   317  6533 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-31 16:51:14.115   317  6533 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-31 16:51:14.119  1029  2018 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6534 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-31 16:51:14.129  1808  6526 W EventLogAggregator: Unknown tag: snet_gcore
08-31 16:51:14.129  1808  6526 W EventLogAggregator: Unknown tag: snet_launch_service
,08-31 16:51:14.192  1808  6526 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-31 16:51:14.195  6534  6534 I AppUp4:AppBoxCP: onCreate
,08-31 16:51:14.196  6534  6534 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 16:51:14.198  1029  1524 D WifiService: New client listening to asynchronous messages
08-31 16:51:14.207  6534  6534 I AppUp4:DB:  setFingerPrint start
,08-31 16:51:14.207  6534  6534 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 16:51:14.215  6534  6534 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 16:51:14.215  6534  6534 I AppUp4:DB:  SDK version = 21
08-31 16:51:14.215  6534  6534 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-31 16:51:14.216  6534  6534 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 16:51:14.217  6534  6534 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 16:51:14.217  6534  6534 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:14.219  6534  6534 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 16:51:14.219  6534  6534 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 16:51:14.224  6534  6534 I AppUp4:CustModeStarterReceiver: onReceive
08-31 16:51:14.232  2134  6532 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 16:51:14.249  6534  6534 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:51:14.249  6534  6534 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 16:51:14.260  6534  6534 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@28907f
08-31 16:51:14.260  6534  6534 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 16:51:14.261  6534  6534 D AppUp4:CustFacade: isPhone : true
08-31 16:51:14.262  6534  6534 D AppUp4:CustModeStarterReceiver: begin check event
08-31 16:51:14.262  6534  6534 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-31 16:51:14.262  6534  6534 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-31 16:51:14.268  6534  6555 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 16:51:14.268  6534  6555 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 16:51:14.268  6534  6555 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-31 16:51:14.270  1029  1959 I ActivityManager: Killing 5795:com.android.gallery3d/u0a27 (adj 15): empty #17
08-31 16:51:14.314  6550  6550 D AndroidRuntime: 
08-31 16:51:14.314  6550  6550 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 16:51:14.318  6550  6550 D AndroidRuntime: CheckJNI is OFF
,08-31 16:51:14.324  1029  1937 W libprocessgroup: failed to open /acct/uid_10027/pid_5795/cgroup.procs: No such file or directory
08-31 16:51:14.328  3217  3217 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:14.329  3217  3217 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 16:51:14.332  3217  3217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 16:51:14.337  3217  3217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 16:51:14.347  3421  3421 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:14.350  3421  3421 V DownloadManager: DownloadService onCreate
08-31 16:51:14.351  3421  6562 I DownloadManager: in removeSpuriousFiles
08-31 16:51:14.352  3421  6562 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-31 16:51:14.353  3217  6561 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 16:51:14.354  3421  6562 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@7a72d75 on behalf of 3421
08-31 16:51:14.355  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-31 16:51:14.355  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-31 16:51:14.355  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-31 16:51:14.355  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-31 16:51:14.355  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-31 16:51:14.355  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-31 16:51:14.356  3217  6561 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-31 16:51:14.358  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-31 16:51:14.358  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-31 16:51:14.358  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-31 16:51:14.358  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-31 16:51:14.358  3421  6562 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-31 16:51:14.359  3217  6564 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:14.360  3217  6564 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 16:51:14.362  3421  6562 I DownloadManager: in trimDatabase
08-31 16:51:14.363  3421  6562 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-31 16:51:14.364  3421  6562 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@f86310a on behalf of 3421
08-31 16:51:14.365  2134  6558 D GCM     : Connected
,08-31 16:51:14.408  1029  2043 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6577 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 16:51:14.410  3421  3421 V DownloadManager: DownloadService onStartCommand
08-31 16:51:14.410  3421  6563 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-31 16:51:14.412  3421  6563 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1eca2bf1 on behalf of 3421
08-31 16:51:14.414  3217  6561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-31 16:51:14.416  3421  6563 V DownloadManager: processing inserted download 1
08-31 16:51:14.420  3421  6563 V DownloadManager: processing inserted download 4
,08-31 16:51:14.422  3421  6563 V DownloadManager: processing inserted download 7
08-31 16:51:14.423  3421  6563 V DownloadManager: processing inserted download 8
08-31 16:51:14.424  3421  6563 V DownloadManager: processing inserted download 9
08-31 16:51:14.425  3421  6563 V DownloadManager: processing inserted download 10
08-31 16:51:14.427  3421  6563 V DownloadManager: processing inserted download 11
08-31 16:51:14.428  3421  6563 V DownloadManager: processing inserted download 12
08-31 16:51:14.429  3421  6563 V DownloadManager: processing inserted download 13
08-31 16:51:14.430  3421  6563 V DownloadManager: processing inserted download 14
08-31 16:51:14.431  3421  6563 V DownloadManager: processing inserted download 16
08-31 16:51:14.453  1029  1983 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6594 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-31 16:51:14.461  3421  3421 V DownloadManager: DownloadService onDestroy
08-31 16:51:14.462  3217  3217 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-31 16:51:14.463  3217  3217 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-31 16:51:14.463  3217  3217 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-31 16:51:14.464  3217  3217 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-31 16:51:14.468  2134  6558 D GCM     : Message class com.google.e.a.a.q
08-31 16:51:14.479  3217  3217 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-31 16:51:14.489  6577  6577 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:14.490  6577  6577 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 16:51:14.491  6577  6577 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 16:51:14.491  6577  6577 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 16:51:14.498  6550  6550 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-31 16:51:14.507  1029  1097 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-31 16:51:14.508  1029  1097 I ActivityManager: Killing 5918:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-31 16:51:14.512  6594  6594 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 16:51:14.513  6594  6594 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-31 16:51:14.550  1029  1959 I WindowState: WIN DEATH: Window{15945414 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:51:14.550  1029  1524 D WifiService: Client connection lost with reason: 4
,08-31 16:51:14.556  1029  1959 D InputDispatcher: Window went away: Window{15945414 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:51:14.608  6594  6594 I MultiDex: VM with version 2.1.0 has multidex support
08-31 16:51:14.608  6594  6594 I MultiDex: install
08-31 16:51:14.608  6594  6594 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 16:51:14.727  1029  1097 I ActivityManager:   Force finishing activity ActivityRecord{3d160d9 u0 com.test.thalitest/.MainActivity t6}
,08-31 16:51:14.755   347   361 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 16:51:14.756  1029  2043 W ActivityManager: Spurious death for ProcessRecord{2a7dae9f 5918:com.test.thalitest/u0a118}, curProc for 5918: null
08-31 16:51:14.758  6577  6577 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-31 16:51:14.764  1932  3788 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-31 16:51:14.765  1932  3788 D SplitWindowPolicy: topRunningActivity=ActivityInfo{26fe5e9 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 16:51:14.767  1932  1949 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 16:51:14.767  1029  1117 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-31 16:51:14.768  1932  1949 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ce8126e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 16:51:14.779  1029  1117 I ActivityManager:   Force finishing activity ActivityRecord{3d160d9 u0 com.test.thalitest/.MainActivity t6 f}
08-31 16:51:14.780  1029  1117 W ActivityManager: Duplicate finish request for ActivityRecord{3d160d9 u0 com.test.thalitest/.MainActivity t6 f}
,08-31 16:51:14.794  6577  6577 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-31 16:51:14.813  2025  2025 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 16:51:14.814  1594  1594 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-31 16:51:14.814  1594  1594 I [SystemUI]LGPowerUI: On Skip Timer : true
08-31 16:51:14.815  2025  2025 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-31 16:51:14.816  1029  1524 D WifiController: battery changed pluggedType: 2
,08-31 16:51:14.816  1594  1594 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
08-31 16:51:14.817  1594  1594 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-31 16:51:14.818  1932  2112 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-31 16:51:14.818  1932  2112 D LEDHandler: Battery Level Remaining: 100%
08-31 16:51:14.818  1932  2112 D LEDHandler: Battery Temp: 303, mChargingStatus=5, mChargingStop=false
08-31 16:51:14.818  1594  1594 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-31 16:51:14.820  1029  1029 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:14.820  1029  1029 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 16:51:14.821  6208  6265 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 16:51:14.821  6061  6061 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 16:51:14.826  1594  1594 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-31 16:51:14.835  1987  1987 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 16:51:14.835  2696  2696 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-31 16:51:14.839  6208  6208 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 16:51:14.839  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 16:51:14.846  1029  1372 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 16:51:14.849  4367  4367 I art     : Explicit concurrent mark sweep GC freed 554(36KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 431us total 59.355ms
08-31 16:51:14.851  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 16:51:14.852  2025  2115 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-31 16:51:14.852  6594  6594 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-31 16:51:14.863  2445  2593 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:51:14.864  4264  4264 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 16:51:14.864  4264  4264 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 16:51:14.864  4264  4264 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 16:51:14.865  4264  4264 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 16:51:14.865  4264  4264 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 16:51:14.865  4264  4264 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 16:51:14.865  4264  4264 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:51:14.865  4264  4264 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 16:51:14.865  4264  4264 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:14.865  4264  4264 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:14.865  4264  4264 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 16:51:14.866  4264  4264 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 16:51:14.881  1029  1094 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-31 16:51:14.884  6577  6577 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 16:51:14.898  1029  2043 V SIM_STK : Menu title from STK is T-Mobile
08-31 16:51:14.934  1029  1029 D administrator: Handling package changes for user 0
,08-31 16:51:14.945  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-31 16:51:14.946  1896  1896 D ActionManagerService: notifyUserLog: 1000003
08-31 16:51:14.947  1594  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 16:51:14.947  1594  1644 D KeyguardModel: createShortcutInfo...
08-31 16:51:14.948  2025  2025 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-31 16:51:14.949  2696  4201 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 16:51:14.965  2025  2025 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-31 16:51:14.967  2025  2025 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 16:51:14.968  1594  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 16:51:14.968  1594  1644 D KeyguardModel: createShortcutInfo...
,08-31 16:51:14.969  1594  1594 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-31 16:51:14.975  1594  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 16:51:14.976  1594  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:14.976  1594  1644 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 16:51:14.978  1594  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 16:51:14.978  1896  1896 D ActionManagerService: notifyUserLog: 1000004
08-31 16:51:14.979  2696  4201 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-31 16:51:14.980  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-31 16:51:14.981  2696  2752 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 16:51:14.988  1594  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:14.988  1594  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 16:51:14.996  1029  2018 V SIM_STK : Menu title from STK is T-Mobile
08-31 16:51:14.997  1029  2018 V SIM_STK : Menu title from STK is T-Mobile
08-31 16:51:15.000  6577  6577 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:51:15.001  6577  6577 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , display: false
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , animation: false }
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , display: false
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , animation: false }
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , display: false
08-31 16:51:15.002  2025  2025 I GBoardWebViewUtils: , animation: false }
08-31 16:51:15.003  1594  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 16:51:15.003  1594  1644 D KeyguardModel: createShortcutInfo...
,08-31 16:51:15.012  1594  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 16:51:15.012  1860  1860 D SplitUIManager: split_name #11 / not available #0
08-31 16:51:15.012  1860  1860 D SplitUIService: removed split : 
08-31 16:51:15.013   317  6616 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 16:51:15.013   317  6616 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-31 16:51:15.016  1594  1644 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 16:51:15.019  1594  1594 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 16:51:15.019  1594  1594 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 16:51:15.019  1594  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:15.019  1594  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 16:51:15.020  1594  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 16:51:15.020  1594  1644 D KeyguardModel: createShortcutInfo...
08-31 16:51:15.021  2025  6615 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 16:51:15.028  1594  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:15.028  1594  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 16:51:15.030  1594  1644 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 16:51:15.030  1594  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 16:51:15.030  1594  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:15.030  1594  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 16:51:15.031  1594  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 16:51:15.031  1594  1644 D KeyguardModel: createShortcutInfo...
08-31 16:51:15.041  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 16:51:15.042  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 16:51:15.047   317  6616 D libc-netbsd: res_queryN name = www.google.com succeed
08-31 16:51:15.085   317  6622 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 16:51:15.085   317  6622 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 16:51:15.085   317  6622 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 16:51:15.086  1594  1594 D KeyguardModel: handleShortcutListChanged...
08-31 16:51:15.086  1594  1594 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 16:51:15.092  1029  1760 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 16:51:15.093  6208  6208 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 16:51:15.094  1594  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 16:51:15.094  1594  1644 D KeyguardModel: createShortcutInfo...
08-31 16:51:15.096  1594  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 16:51:15.096  1594  1644 D KeyguardModel: createShortcutInfo...
08-31 16:51:15.097  1594  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:15.097  1594  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 16:51:15.098  1594  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 16:51:15.098  1594  1644 D KeyguardModel: createShortcutInfo...
08-31 16:51:15.099  1594  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:15.099  1594  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 16:51:15.099  1029  1989 V SIM_STK : Menu title from STK is T-Mobile
08-31 16:51:15.104  1860  1860 D SplitUIManager: split_name #11 / not available #0
08-31 16:51:15.104  1860  1860 I SplitUIService: split app #11
,08-31 16:51:15.113  1594  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 16:51:15.113  1594  1644 D KeyguardModel: createShortcutInfo...
08-31 16:51:15.117  1594  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:15.117  1594  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 16:51:15.118  1594  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 16:51:15.118  1594  1644 D KeyguardModel: createShortcutInfo...
08-31 16:51:15.122  2025  2040 I art     : Background sticky concurrent mark sweep GC freed 3231(171KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 7.704ms total 19.880ms
,08-31 16:51:15.125  2025  2025 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-31 16:51:15.150  1029  1442 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-31 16:51:15.154  1594  1594 D KeyguardModel: handleShortcutListChanged...
08-31 16:51:15.154  1594  1594 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 16:51:15.159  1029  1029 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-31 16:51:15.159  1029  1029 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 16:51:15.160  1029  1029 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 16:51:15.162  1029  1569 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-31 16:51:15.236  6577  6577 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 16:51:15.253  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-31 16:51:15.256  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 16:51:15.258  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 16:51:15.259  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 16:51:15.260  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 16:51:15.261  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-31 16:51:15.272  6577  6577 I HubEmail: JNI_OnLoad()
08-31 16:51:15.272  6577  6577 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 16:51:15.272  6577  6577 I HubEmail: registerNatives()
08-31 16:51:15.272  6577  6577 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 16:51:15.272  6577  6577 I HubEmail: registerNativeMethods()
08-31 16:51:15.272  6577  6577 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 16:51:15.272  6577  6577 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-31 16:51:15.276  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-31 16:51:15.276  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 16:51:15.277  1029  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{328a7064 u0 com.lge.launcher2/.Launcher t5} time:128875
08-31 16:51:15.282  6577  6627 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:15.286  2025  2795 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 16:51:15.286  2025  2795 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-31 16:51:15.293  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 16:51:15.294  3351  3351 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 16:51:15.294  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 16:51:15.294  3351  3351 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:15.294  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 16:51:15.296  3351  3351 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 16:51:15.296  3351  3351 D PhoneState: setPdpRejectCasuse : false
08-31 16:51:15.302  2025  2025 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-31 16:51:15.311   317  6633 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 16:51:15.311   317  6633 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-31 16:51:15.326  1029  1942 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6634 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-31 16:51:15.329  2025  2025 D [Concierge]WidgetView: change position of spinner
08-31 16:51:15.330  2583  2583 D [Concierge]Service: onStartCommand(). Type : 8
08-31 16:51:15.330  2583  2583 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-31 16:51:15.332  2583  2583 D [Concierge]Service: Update widget ID : 11
08-31 16:51:15.332  2583  2583 D [Concierge]Service: onStartCommand(). Type : 0
08-31 16:51:15.333  2025  2025 I [Concierge]WidgetView: initWebView(). Time : 1472655075333
08-31 16:51:15.338  6594  6609 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:51:15.338  6594  6609 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 16:51:15.353  1029  1094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:15.353  2025  2025 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 401255170
08-31 16:51:15.354  2025  2025 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 16:51:15.354  2025  2025 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 16:51:15.357  1029  1094 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 16:51:15.359  2025  2025 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3f6f5ce9
08-31 16:51:15.359  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-31 16:51:15.360   317  6633 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
08-31 16:51:15.361  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 16:51:15.361  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 16:51:15.366  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 16:51:15.367  2025  2025 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 16:51:15.367  2025  2025 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-31 16:51:15.368  2025  2025 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472654974983, New one : 1472655075333
08-31 16:51:15.368  2025  2025 D [Concierge]WidgetView: Unregister all receivers
08-31 16:51:15.368  2025  2025 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 16:51:15.368  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 16:51:15.370  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 16:51:15.372  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 16:51:15.374  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 16:51:15.376  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 16:51:15.378  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 16:51:15.380  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 16:51:15.384  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 16:51:15.385  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 16:51:15.386  1029  1117 I art     : Explicit concurrent mark sweep GC freed 26690(1826KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.826ms total 401.665ms
,08-31 16:51:15.409  6634  6634 D LgDataFeature: LgDataFeature() Constructor: none
08-31 16:51:15.409  6634  6634 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 16:51:15.411  6634  6634 D PhoneMonitor: Register our PhoneStateListener
,08-31 16:51:15.415  6550  6550 D AndroidRuntime: Shutting down VM
08-31 16:51:15.429  2025  2025 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-31 16:51:15.437  2025  2025 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 16:51:15.437  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-31 16:51:15.438  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 16:51:15.451  6267  6629 V FormManager: There are no updated forms. The schedule will be deleted.
,08-31 16:51:15.458  2025  2025 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@109ecb2f time:129056
08-31 16:51:15.458  6267  6629 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-31 16:51:15.488  1029  1117 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6651 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 16:51:15.497  6634  6634 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 16:51:15.502  6634  6634 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 16:51:15.528  6634  6634 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-31 16:51:15.528  6634  6634 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-31 16:51:15.529  6634  6634 D TelephonyAutoProfiling: [parse] Load xml
08-31 16:51:15.530  6634  6634 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
,08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 16:51:15.530  6634  6634 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 16:51:15.530  6634  6634 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-31 16:51:15.537  6634  6634 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-31 16:51:15.539  1029  1566 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6671 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:15.541  1029  1566 I ActivityManager: Killing 2116:com.lge.music/u0a34 (adj 15): empty #17
08-31 16:51:15.543  6667  6667 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-31 16:51:15.546   351   351 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 499us total 11.802ms
08-31 16:51:15.551   324  2144 V AudioFlinger: 2116 died, releasing its sessions
08-31 16:51:15.551   324  2144 V AudioFlinger:  pid 1843 @ 0
08-31 16:51:15.551   324  2144 V AudioFlinger:  pid 3351 @ 1
08-31 16:51:15.551   324  2144 V AudioFlinger:  pid 3351 @ 2
,08-31 16:51:15.567   351   351 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 20.143ms
,08-31 16:51:15.587   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 403us total 18.953ms
,08-31 16:51:15.589  6667  6667 I dex2oat : dex2oat took 45.750ms (threads: 4)
,08-31 16:51:15.598  6594  6609 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 16:51:15.598  6594  6609 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 16:51:15.598  6594  6609 I Adreno-EGL: Build Date: 12/12/14 금
08-31 16:51:15.598  6594  6609 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 16:51:15.598  6594  6609 I Adreno-EGL: Remote Branch: 
08-31 16:51:15.598  6594  6609 I Adreno-EGL: Local Patches: 
08-31 16:51:15.598  6594  6609 I Adreno-EGL: Reconstruct Branch: 
08-31 16:51:15.619  2025  2025 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-31 16:51:15.658  2025  2842 I GBoardtInterface: onReloaded()
08-31 16:51:15.660  1029  1760 W libprocessgroup: failed to open /acct/uid_10034/pid_2116/cgroup.procs: No such file or directory
08-31 16:51:15.660  2025  2025 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-31 16:51:15.671  6594  6609 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 16:51:15.671  6594  6609 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 16:51:15.671  6594  6609 I Adreno-EGL: Build Date: 12/12/14 금
08-31 16:51:15.671  6594  6609 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 16:51:15.671  6594  6609 I Adreno-EGL: Remote Branch: 
08-31 16:51:15.671  6594  6609 I Adreno-EGL: Local Patches: 
08-31 16:51:15.671  6594  6609 I Adreno-EGL: Reconstruct Branch: 
08-31 16:51:15.679  1029  1913 I ActivityManager: Killing 5868:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-31 16:51:15.717  6594  6609 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 16:51:15.717  6594  6609 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 16:51:15.717  6594  6609 I Adreno-EGL: Build Date: 12/12/14 금
08-31 16:51:15.717  6594  6609 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 16:51:15.717  6594  6609 I Adreno-EGL: Remote Branch: 
08-31 16:51:15.717  6594  6609 I Adreno-EGL: Local Patches: 
08-31 16:51:15.717  6594  6609 I Adreno-EGL: Reconstruct Branch: 
,08-31 16:51:15.845  2696  2752 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-31 16:51:15.846  1029  1044 W libprocessgroup: failed to open /acct/uid_10061/pid_5868/cgroup.procs: No such file or directory
,08-31 16:51:15.857  1029  1913 I ActivityManager: Killing 6003:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-31 16:51:15.877  1029  1423 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:2759] from screen [on:0 period:-518706651] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 16:51:15.878  1029  1423 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-518706650] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 16:51:15.878  1029  1423 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-31 16:51:15.953  1029  1045 W libprocessgroup: failed to open /acct/uid_10097/pid_6003/cgroup.procs: No such file or directory

```
