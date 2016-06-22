#### Test 721454317367600_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
06-22 07:44:08.180  5677  5677 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
06-22 07:44:08.264  5677  5677 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:08.264  5677  5677 D LgDataFeature: LgDataFeature() Constructor Done, null
06-22 07:44:08.326  5677  5677 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
06-22 07:44:08.352  5677  5677 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:44:08.355  5677  5677 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:44:08.373  5677  5677 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
06-22 07:44:08.373  5677  5677 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
06-22 07:44:08.388  1028  1971 I ActivityManager: Killing 5122:com.google.android.setupwizard/u0a46 (adj 15): empty #17
06-22 07:44:08.426  1028  1917 W libprocessgroup: failed to open /acct/uid_10046/pid_5122/cgroup.procs: No such file or directory
06-22 07:44:08.440  2812  2829 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
06-22 07:44:08.445  4336  5719 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-22 07:44:08.444  2812  2829 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2d254cbc on behalf of 5677
06-22 07:44:08.490  1028  1989 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5720 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:08.517  1028  2027 V SIM_STK : Menu title from STK is T-Mobile
06-22 07:44:08.531  5677  5677 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
06-22 07:44:08.558  5677  5677 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
06-22 07:44:08.592  4336  5719 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
06-22 07:44:08.643  5720  5720 D DocsApplication: Installing DEX configuration.
06-22 07:44:08.661  5720  5720 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
06-22 07:44:08.665  5720  5720 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{4e65e73 com.google.android.apps.docs}
06-22 07:44:08.681  5720  5720 D TAG     : onCreate()
06-22 07:44:08.699  5720  5720 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,06-22 07:44:09.257  5758  5758 D AndroidRuntime: 
06-22 07:44:09.257  5758  5758 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-22 07:44:09.260  5758  5758 D AndroidRuntime: CheckJNI is OFF
06-22 07:44:09.283  2766  2766 I MusicWidget: mDelayedStopHandler : unbind
06-22 07:44:09.293  2128  2128 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
06-22 07:44:09.293  2128  2128 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
06-22 07:44:09.293  2128  2128 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
06-22 07:44:09.294  2128  2128 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
06-22 07:44:09.294  2128  2128 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
06-22 07:44:09.294  2128  2128 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
06-22 07:44:09.295  2128  2128 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
06-22 07:44:09.295  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
06-22 07:44:09.296  1028  1970 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2bfe22dbcom.lge.music.MediaPlaybackService$5@3a35c178
06-22 07:44:09.296  2128  2128 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
06-22 07:44:09.297  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.298  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.299  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.299  2128  2128 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@8653ce1
06-22 07:44:09.299  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.303  2128  2128 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
06-22 07:44:09.303  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.303  2128  2128 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
06-22 07:44:09.303  2128  2128 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
06-22 07:44:09.303  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.304  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.304  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.304  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.305  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
06-22 07:44:09.305  2128  2128 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
06-22 07:44:09.306  2128  2128 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
06-22 07:44:09.307  2128  2128 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
06-22 07:44:09.307  2128  2128 V MediaPlayer[Native]: reset
06-22 07:44:09.312  2128  2128 V MediaPlayer[Native]: setListener
06-22 07:44:09.312  2128  2128 V MediaPlayer[Native]: disconnect
06-22 07:44:09.312  2128  2128 V MediaPlayer[Native]: destructor
06-22 07:44:09.312   318  1381 V AudioFlinger: releasing 18 from 2128 for -1
06-22 07:44:09.312   318  1381 V AudioFlinger:  decremented refcount to 0
06-22 07:44:09.312   318  1381 V AudioFlinger: purging stale effects
06-22 07:44:09.314  2128  2128 V MediaPlayer[Native]: disconnect
06-22 07:44:09.317  2128  2128 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
06-22 07:44:09.324  2128  2128 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
06-22 07:44:09.327  2128  2128 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
06-22 07:44:09.328  2128  2128 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
06-22 07:44:09.329  2128  2128 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
06-22 07:44:09.329  2128  2128 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
06-22 07:44:09.329  2128  2128 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 77996113
06-22 07:44:09.329  2128  2128 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 77996113
06-22 07:44:09.336  2128  2128 I SmartShareClient: [SmartShareManagerClient] terminate service: 2128/MediaPlaybackService/322858703
06-22 07:44:09.338  2128  2128 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
06-22 07:44:09.338  2128  2128 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@283aa0b6
06-22 07:44:09.343  2128  2128 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
06-22 07:44:09.344  2128  2128 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
06-22 07:44:09.344  2128  2128 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
06-22 07:44:09.344  2128  2128 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
06-22 07:44:09.346  1028  1044 I ActivityManager: Killing 5155:com.lge.clock/u0a10 (adj 15): empty #17
06-22 07:44:09.363  2128  2128 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29982
06-22 07:44:09.397  5758  5758 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-22 07:44:09.444  1028  1724 W libprocessgroup: failed to open /acct/uid_10010/pid_5155/cgroup.procs: No such file or directory
06-22 07:44:09.446  1028  1043 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-22 07:44:09.479  1935  1950 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
06-22 07:44:09.484  1028  1043 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
06-22 07:44:09.485  1028  1043 D ActivityManager: setTaskToReturnTo : TaskRecord{3a74065 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-22 07:44:09.485  1028  1043 D ActivityManager: setTaskToReturnTo : TaskRecord{3a74065 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-22 07:44:09.486  1028  1043 D WindowStateEx: AppWindowTokenEx init.. 
06-22 07:44:09.487   340   351 E GBMv2   : DFP En is all cleared set to be enabled
06-22 07:44:09.543  1028  1043 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5778 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-22 07:44:09.544  5758  5758 D AndroidRuntime: Shutting down VM
06-22 07:44:09.587  1935  1950 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
06-22 07:44:09.588  1935  1950 D SplitWindowPolicy: topRunningActivity=ActivityInfo{31379814 co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
06-22 07:44:09.589  1935  2561 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
06-22 07:44:09.589  1935  2561 D SplitWindowPolicy: topRunningActivity=ActivityInfo{187a08bd co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
06-22 07:44:09.593  1811  4405 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
06-22 07:44:09.647  5778  5778 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-22 07:44:09.660  1811  4405 D Icing   : Loaded CLD2 Version V2.0 - 20140131
06-22 07:44:09.719  5778  5778 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
06-22 07:44:09.732  5778  5778 I LibraryLoader: Loading: webviewchromium
06-22 07:44:09.734  5778  5778 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4108-4111)
06-22 07:44:09.735  5778  5778 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:09.747  1811  4405 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
06-22 07:44:09.754  5778  5778 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {41e0f65}
06-22 07:44:09.755  5778  5778 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:09.756  5778  5778 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
06-22 07:44:09.763  5778  5778 I BrowserStartupController: Initializing chromium process, renderers=0
06-22 07:44:09.764  5778  5778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:09.768  5778  5803 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
06-22 07:44:09.772  5778  5778 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
06-22 07:44:09.772  5778  5778 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
06-22 07:44:09.773  5778  5778 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
06-22 07:44:09.773   318  1380 V AudioPolicyService: registerClient() client 0xb04106e0, uid 10118
06-22 07:44:09.785  1028  1090 D BluetoothManagerService: Message: 20
06-22 07:44:09.785  1028  1090 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c7b11c7:true
06-22 07:44:09.788  5778  5807 D BluetoothAdapter: 916161594: getState() :  mService = null. Returning STATE_OFF
06-22 07:44:09.803  5778  5778 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:09.803  5778  5778 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:09.803  5778  5778 I Adreno-EGL: Build Date: 12/12/14 금
06-22 07:44:09.803  5778  5778 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-22 07:44:09.803  5778  5778 I Adreno-EGL: Remote Branch: 
06-22 07:44:09.803  5778  5778 I Adreno-EGL: Local Patches: 
06-22 07:44:09.803  5778  5778 I Adreno-EGL: Reconstruct Branch: 
06-22 07:44:09.890  5778  5813 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
06-22 07:44:09.891  5778  5778 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
06-22 07:44:09.907  5778  5778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:09.912  5778  5778 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-22 07:44:09.916  5778  5778 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-22 07:44:09.919  5778  5778 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-22 07:44:09.919  5778  5778 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-22 07:44:09.930  5778  5778 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
06-22 07:44:09.936  5778  5778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:09.936  5778  5778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:09.956  5778  5826 D OpenGLRenderer: Render dirty regions requested: true
06-22 07:44:09.956  5778  5826 I OpenGLRenderer: Initialized EGL, version 1.4
06-22 07:44:09.961  5778  5826 D OpenGLRenderer: Enabling debug mode 0
06-22 07:44:09.972  5778  5778 D Atlas   : Validating map...
06-22 07:44:09.977  1028  2027 D SplitWindow: check instance of lgWin Window{ce82989 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 07:44:10.012  5778  5824 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:10.012  5778  5824 D LgDataFeature: LgDataFeature() Constructor Done, null
06-22 07:44:10.081  5720  5720 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:10.082  5720  5720 D LgDataFeature: LgDataFeature() Constructor Done, null
06-22 07:44:10.107  1028  1091 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +521ms (total +620ms)
06-22 07:44:10.107  1028  1091 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36f3613a u0 com.test.thalitest/.MainActivity t12} time:104484
06-22 07:44:10.107  1028  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=899732805, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
06-22 07:44:10.112  5778  5778 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4a62051 time:104489
06-22 07:44:10.135  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
06-22 07:44:10.199  5778  5778 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-22 07:44:10.226  5778  5778 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
06-22 07:44:10.226  5778  5778 I chromium: 
06-22 07:44:10.236  5778  5824 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
06-22 07:44:10.236  5778  5824 I chromium: 
06-22 07:44:10.285  5720  5720 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
06-22 07:44:10.303  5778  5840 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435127680
06-22 07:44:10.308  5778  5840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:44:10.308  5778  5840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:44:10.308  5778  5840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:44:10.308  5778  5840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:44:10.308  5778  5840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:44:10.309  5778  5840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bab2445 added. We now have 1 listener(s)
06-22 07:44:10.322  1028  1569 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5846 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
06-22 07:44:10.324  1028  1724 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:10.326  5778  5840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
06-22 07:44:10.327  5778  5840 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
06-22 07:44:10.328  5778  5840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-22 07:44:10.328  5778  5840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:44:10.331  5778  5840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5878a8 added. We now have 1 listener(s)
06-22 07:44:10.331  5778  5840 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-22 07:44:10.334  1028  1538 D WifiService: New client listening to asynchronous messages
06-22 07:44:10.334  5778  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:10.335  5778  5840 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-22 07:44:10.337  5778  5840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-22 07:44:10.337  5778  5840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-22 07:44:10.337  5778  5840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:44:10.337  5778  5840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-22 07:44:10.338  5778  5840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-22 07:44:10.339  1028  1916 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:10.339  5778  5840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
06-22 07:44:10.341  5778  5840 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:10.341  5778  5840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:44:10.341  5778  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:10.341  5778  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:10.341  5778  5840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:44:10.341  5778  5840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:10.341  5778  5840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:10.341  5778  5840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:10.341  5778  5840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:10.341  5778  5840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:44:10.341  5778  5840 D io.jxcore.node.ConnectivityMonitor: start: OK
06-22 07:44:10.342  5778  5840 I io.jxcore.node.LifeCycleMonitor: start: OK
06-22 07:44:10.369  5778  5778 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-22 07:44:10.372  5846  5846 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
06-22 07:44:10.379  5846  5846 I LockScreenSettings: New app installed broadcast received ..
06-22 07:44:10.382  5846  5846 I LockScreenSettings: Number of installed packages  1
06-22 07:44:10.412  1028  2027 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5865 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
06-22 07:44:10.413  1028  2027 I ActivityManager: Killing 4869:com.lge.bnr/1000 (adj 15): empty #17
06-22 07:44:10.500  1028  1569 W libprocessgroup: failed to open /acct/uid_1000/pid_4869/cgroup.procs: No such file or directory
06-22 07:44:10.536  5865  5865 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:44:10.670  1028  1917 I ActivityManager: Killing 4761:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,06-22 07:44:10.753  1028  1780 W libprocessgroup: failed to open /acct/uid_10085/pid_4761/cgroup.procs: No such file or directory
,06-22 07:44:11.041  5778  5864 W jxcore-log: Initializing JXcore engine
06-22 07:44:11.041  5778  5864 W jxcore-log: JXcore engine is ready
,06-22 07:44:11.088  1028  1971 V SIM_STK : Menu title from STK is T-Mobile
,06-22 07:44:11.101  5864  5864 W Thread-641: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10258]" dev="sockfs" ino=10258 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,06-22 07:44:11.101  5864  5864 W Thread-641: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
06-22 07:44:11.101  5864  5864 W Thread-641: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10358]" dev="sockfs" ino=10358 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
06-22 07:44:11.101  5864  5864 W Thread-641: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
06-22 07:44:11.101  5864  5864 W Thread-641: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[28961]" dev="sockfs" ino=28961 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
06-22 07:44:11.119  5778  5864 W jxcore-log: Starting JXcore engine
,06-22 07:44:11.140  1028  2027 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5902 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-22 07:44:11.189  5902  5902 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
06-22 07:44:11.189  5902  5902 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,06-22 07:44:11.210  1028  1952 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5920 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,06-22 07:44:11.211  5778  5864 W jxcore-log: Platform android
06-22 07:44:11.211  5778  5864 W jxcore-log: 
06-22 07:44:11.212  5778  5864 W jxcore-log: Process ARCH arm
06-22 07:44:11.212  5778  5864 W jxcore-log: 
06-22 07:44:11.212  1028  1952 I ActivityManager: Killing 5224:com.google.android.gm/u0a64 (adj 15): empty #17
06-22 07:44:11.304  1028  1917 W libprocessgroup: failed to open /acct/uid_10064/pid_5224/cgroup.procs: No such file or directory
,06-22 07:44:11.404  5778  5864 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:44:11.404  5778  5864 I jxcore-log: 
06-22 07:44:11.404  5778  5864 W jxcore-log: JXcore engine is started
,06-22 07:44:11.415  5778  5840 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-22 07:44:11.422  5778  5778 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
06-22 07:44:11.452   340   353 E GBMv2   : DFP En is all cleared set to be enabled
06-22 07:44:11.453   340   353 E GBMv2   : Set value is all cleared set the max
06-22 07:44:11.453   340   353 I GBMv2   : DFP Enabled. Ignore VFP set
,06-22 07:44:11.472  1028  1724 I art     : Explicit concurrent mark sweep GC freed 26542(1312KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 42MB/64MB, paused 1.640ms total 136.129ms
,06-22 07:44:11.545  5920  5920 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,06-22 07:44:11.572  1028  1569 I ActivityManager: Killing 5270:com.google.android.talk/u0a72 (adj 15): empty #17
,06-22 07:44:11.574  5920  5920 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-22 07:44:11.602  4248  5938 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,06-22 07:44:11.675  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=899732805 [*alarm*], flags=0x0
,06-22 07:44:11.680  1028  1916 W libprocessgroup: failed to open /acct/uid_10072/pid_5270/cgroup.procs: No such file or directory
06-22 07:44:14.207  5720  5720 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,06-22 07:44:14.208  1028  1916 I ActivityManager: Killing 5004:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
06-22 07:44:14.226  4983  4983 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
06-22 07:44:14.227  4983  4983 W System.err: android.os.DeadObjectException
06-22 07:44:14.227  4983  4983 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-22 07:44:14.227  4983  4983 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-22 07:44:14.227  4983  4983 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
06-22 07:44:14.227  4983  4983 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
06-22 07:44:14.227  4983  4983 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
06-22 07:44:14.227  4983  4983 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
06-22 07:44:14.227  4983  4983 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:44:14.227  4983  4983 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:44:14.227  4983  4983 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:14.227  4983  4983 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-22 07:44:14.227  4983  4983 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:14.227  4983  4983 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:14.227  4983  4983 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-22 07:44:14.227  4983  4983 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-22 07:44:14.228  4983  4983 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
06-22 07:44:14.228  4983  4983 W System.err: android.os.DeadObjectException
06-22 07:44:14.228  4983  4983 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-22 07:44:14.228  4983  4983 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-22 07:44:14.228  4983  4983 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
06-22 07:44:14.228  4983  4983 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
06-22 07:44:14.228  4983  4983 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
06-22 07:44:14.228  4983  4983 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
06-22 07:44:14.228  4983  4983 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:44:14.228  4983  4983 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:44:14.228  4983  4983 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:14.228  4983  4983 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-22 07:44:14.228  4983  4983 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:14.228  4983  4983 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:14.228  4983  4983 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-22 07:44:14.229  4983  4983 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-22 07:44:14.229  4983  4983 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
06-22 07:44:14.229  4983  4983 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,06-22 07:44:14.473  1028  1952 W libprocessgroup: failed to open /acct/uid_1000/pid_5004/cgroup.procs: No such file or directory
06-22 07:44:14.474  1028  1952 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,06-22 07:44:14.485  4983  4983 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
06-22 07:44:14.485  4983  4983 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
06-22 07:44:14.529  1028  1043 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=5954 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-22 07:44:14.531  4983  4983 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,06-22 07:44:14.614  5954  5954 D UEI.SmartControl: Quickset Services start...
06-22 07:44:14.616  5954  5954 I UEI.SmartControl: Manufacture = LGE
06-22 07:44:14.616  5954  5954 D UEI.SmartControl: Id = LGNevo
06-22 07:44:14.617  5954  5954 D UEI.SmartControl: File observer start...
06-22 07:44:14.618  5954  5954 E UEI.SmartControl: IR Port is disabled: false
06-22 07:44:14.618  5954  5954 D UEI.SmartControl: Starting file observer...
06-22 07:44:14.618  5954  5954 D UEI.SmartControl: Extracting JNI libs...
06-22 07:44:14.618  5954  5954 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,06-22 07:44:14.709  5954  5954 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,06-22 07:44:14.710  5954  5954 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-22 07:44:14.710  5954  5954 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,06-22 07:44:14.744  5954  5954 I UEI.SmartControl: --- Selecting new region: 6
,06-22 07:44:14.747  5954  5954 I UEI.SmartControl: Model = LG-D855
06-22 07:44:14.749  5954  5954 D UEI.SmartControl: QS Service created
06-22 07:44:14.764  5954  5954 I UEI.SmartControl: Service initServices...
06-22 07:44:14.768  5954  5954 D UEI.SmartControl: QS start get config
,06-22 07:44:14.805  5954  5954 D UEI.SmartControl: Loading JNI Libs...
,06-22 07:44:15.035  5954  5954 I UEI.SmartControl: Supports setup maps: true
,06-22 07:44:15.037  5954  5954 D UEI.SmartControl: QS start statue = true Error code = 0
06-22 07:44:15.038  5954  5954 I UEI.SmartControl: QS version = v2.7.10.1_RC1
06-22 07:44:15.038  5954  5954 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-22 07:44:15.038  5954  5954 I UEI.SmartControl: ### init IR Blaster...
,06-22 07:44:15.042  5954  5954 D serial_port: Configuring serial port
06-22 07:44:15.046  5954  5954 E UEI.SmartControl: UEIBLaster setting for 616
06-22 07:44:15.046  5954  5954 I UEI.SmartControl: Setting serial record hearder size = 2
06-22 07:44:15.046  5954  5954 I UEI.SmartControl: configuring settings for MAXQ616
06-22 07:44:15.046  5954  5954 I UEI.SmartControl: Get version...
06-22 07:44:15.062  5954  5978 D UEI.SmartControl: serial port data available: 21
,06-22 07:44:15.091  5954  5954 D UEI.SmartControl: MAXQ616 A2-X4 software.
06-22 07:44:15.091  5954  5954 I UEI.SmartControl: IR Blaster version: 256702256704300002
06-22 07:44:15.092  5954  5954 I UEI.SmartControl: QS saving settings...
,06-22 07:44:15.094  5954  5954 D UEI.SmartControl: IR Blaster version: 25672567
,06-22 07:44:15.112  5954  5978 D UEI.SmartControl: serial port data available: 4
,06-22 07:44:15.146  5954  5954 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
06-22 07:44:15.147  5954  5954 E UEI.SmartControl: Services init done
06-22 07:44:15.148  5954  5954 D UEI.SmartControl: QS Service init finished
06-22 07:44:15.148  5954  5954 D UEI.SmartControl: QS Service version name: 2.1.91
06-22 07:44:15.148  5954  5954 D UEI.SmartControl: QS Service version code: 201091
06-22 07:44:15.149  5954  5954 D UEI.SmartControl: Service requested: Control
06-22 07:44:15.152  5954  5982 I UEI.SmartControl: Device manager: loading config....
,06-22 07:44:15.152  5954  5982 D UEI.SmartControl: ----------- loading internal config...
06-22 07:44:15.158  5954  5982 E UEI.SmartControl: Loading SETTINGS...
06-22 07:44:15.160  5954  5954 D UEI.SmartControl: Request IControl service: devices are loaded...
06-22 07:44:15.161  1028  1043 I ActivityManager: Killing 4983:com.lge.qremote/u0a112 (adj 15): empty #17
06-22 07:44:15.176  5720  5833 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,06-22 07:44:15.176  5954  5982 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
06-22 07:44:15.185  5954  5981 I UEI.SmartControl: Notify AllClients services are ready: 0
06-22 07:44:15.185  5954  5981 D UEI.SmartControl: -----service ready thread exits
,06-22 07:44:15.254  1028  1970 W libprocessgroup: failed to open /acct/uid_10112/pid_4983/cgroup.procs: No such file or directory
,06-22 07:44:15.258  5954  5954 D UEI.SmartControl: Internal service binding...
06-22 07:44:16.112  1028  1970 I ActivityManager: Killing 4918:com.android.calendar/u0a13 (adj 15): empty #17
,06-22 07:44:16.213  1028  1724 W libprocessgroup: failed to open /acct/uid_10013/pid_4918/cgroup.procs: No such file or directory
,06-22 07:44:19.374  2128  2128 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19972
,06-22 07:44:20.128  5954  5979 D serial_port: close(fd = 25)
,06-22 07:44:20.136  5954  5979 I UEI.SmartControl: Serial port is closed.
,06-22 07:44:20.153  5954  5983 D UEI.SmartControl: Internal timer expired: 1
06-22 07:44:20.153  5954  5983 D UEI.SmartControl: unbind internal service
,06-22 07:44:20.174  5954  5954 D UEI.SmartControl: Service.onUnbind: IControl
06-22 07:44:20.175  5954  5954 D UEI.SmartControl: Service.onDestroy
,06-22 07:44:20.179  5954  5954 D UEI.SmartControl: Lock is in USE false
,06-22 07:44:20.179  5954  5954 D UEI.SmartControl: unbind internal service
,06-22 07:44:20.179  5954  5954 I UEI.SmartControl: Serial port is closed.
,06-22 07:44:20.179  5954  5954 I UEI.SmartControl: Serial port is closed.
,06-22 07:44:20.180  5954  5954 D UEI.SmartControl: Blaster closed
06-22 07:44:20.180  5954  5954 D UEI.SmartControl: Shut down QS...
,06-22 07:44:20.180  5954  5954 D UEI.SmartControl: Stopping QS lib,
06-22 07:44:20.181  5954  5954 D UEI.SmartControl: QS lib stop result = true
06-22 07:44:20.181  5954  5954 D UEI.SmartControl: Stopped QS lib,
06-22 07:44:20.182  5954  5954 D UEI.SmartControl: Stopped file observer...
,06-22 07:44:20.183  5954  5954 D UEI.SmartControl: QS shutdown complete
,06-22 07:44:21.352  1028  1086 I ActivityManager: Waited long enough for: ServiceRecord{31fca56e u0 com.google.android.gms/.wearable.service.WearableService}
,06-22 07:44:21.968  5778  5864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-22 07:44:21.968  5778  5864 I jxcore-log: 
06-22 07:44:21.970  5778  5864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-22 07:44:21.970  5778  5864 I jxcore-log: 
,06-22 07:44:21.973  5778  5864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:21.973  5778  5864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:44:21.973  5778  5864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:21.973  5778  5864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:21.973  5778  5864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:44:21.973  5778  5864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:21.973  5778  5864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:21.973  5778  5864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:21.973  5778  5864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:21.973  5778  5864 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:21.973  5778  5864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-22 07:44:21.976  5778  5864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-22 07:44:21.976  5778  5864 I jxcore-log: 
06-22 07:44:21.977  5778  5864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-22 07:44:21.977  5778  5864 I jxcore-log: 
06-22 07:44:22.298  5778  5864 I jxcore-log: Unit Test app is loaded
06-22 07:44:22.298  5778  5864 I jxcore-log: 
,06-22 07:44:22.307  5778  5864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-22 07:44:22.307  5778  5864 I jxcore-log: 
06-22 07:44:22.314  1028  1952 D WifiServiceImplEx: setWifiEnabled: true pid=5778, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
06-22 07:44:22.315  1028  1952 D WifiService: setWifiEnabled: true pid=5778, uid=10118
,06-22 07:44:22.316  1028  1952 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
06-22 07:44:22.318  5778  5778 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-22 07:44:22.338  1028  1569 D WifiServiceImplEx: disconnect pid=5778, uid=10118, packageName=com.test.thalitest
06-22 07:44:22.338  1028  1532 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
06-22 07:44:22.338  1028  1532 I LGFTMITEM: [GET_FTM][id=6], offset=12288
06-22 07:44:22.338  1028  1917 D WifiServiceImplEx: reconnect pid=5778, uid=10118, packageName=com.test.thalitest
06-22 07:44:22.341  1028  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:22.341  1028  2027 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
06-22 07:44:22.342  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-22 07:44:22.343  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-22 07:44:22.343  1028  1028 D Ulp_jni : JNI:system_update. Event-4
06-22 07:44:22.344  1028  1532 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
06-22 07:44:22.344  1028  1532 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
06-22 07:44:22.344  1028  1532 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
06-22 07:44:22.344  1028  1532 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
06-22 07:44:22.344  1028  1532 I WifiUtil: Intf0MacAddress=C49A027FFB5D
06-22 07:44:22.344  1028  1532 E WifiHW  : unknown target_country: EU , set to default
06-22 07:44:22.344  1028  1532 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
06-22 07:44:22.344  1028  1532 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
06-22 07:44:22.344  1028  1532 I WifiUtil: gEnableBmps=1
,06-22 07:44:22.375  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-22 07:44:22.375  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-22 07:44:22.375  1028  1028 D Ulp_jni : JNI:system_update. Event-4
06-22 07:44:22.377  1028  1090 D BluetoothManagerService: Message: 1
06-22 07:44:22.377  1028  1090 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-22 07:44:22.385  5778  5864 I jxcore-log: My device name is: LGE-LG-D855
06-22 07:44:22.385  5778  5864 I jxcore-log: 
06-22 07:44:22.388  5778  5864 I jxcore-log: WARN testUtils: myNameCallback not set!
06-22 07:44:22.388  5778  5864 I jxcore-log: 
,06-22 07:44:22.399  1028  1090 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5996 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,06-22 07:44:22.477  5996  5996 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
06-22 07:44:22.477  5996  5996 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:44:22.477  5996  5996 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
06-22 07:44:22.478  5996  5996 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-22 07:44:22.543  5996  5996 D BluetoothAdapterApp: Loading JNI Library
,06-22 07:44:22.546   313   888 D SoftapController: Softap fwReload - Ok
06-22 07:44:22.547  1028  1090 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-22 07:44:22.550   313   888 D CommandListener: Setting iface cfg
06-22 07:44:22.551   313   888 D CommandListener: Trying to bring down wlan0
06-22 07:44:22.551  1028  1090 D Tethering: InitialState.processMessage what=4
06-22 07:44:22.552   313   888 D CommandListener: Clearing all IP addresses on wlan0
06-22 07:44:22.552   313  6019 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
06-22 07:44:22.556  1028  1088 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-22 07:44:22.569  1028  1532 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,06-22 07:44:22.573  1028  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-22 07:44:22.573  1028  1532 E WifiStateMachine: useWiFiOffloading() : false
06-22 07:44:22.573  1028  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-22 07:44:22.589  1028  1086 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6022 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-22 07:44:22.590  1028  1090 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-22 07:44:22.596  1028  1532 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
06-22 07:44:22.596  1028  1532 D WifiMonitor: connecting to supplicant
06-22 07:44:22.600  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
06-22 07:44:22.603  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-22 07:44:22.606  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
06-22 07:44:22.607  5778  5778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-22 07:44:22.621  6021  6021 W wpa_supplicant: type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,06-22 07:44:22.621  6021  6021 W wpa_supplicant: type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:22.650  6021  6021 I wpa_supplicant: Successfully initialized wpa_supplicant
,06-22 07:44:22.675  5996  5996 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@4e65e73 Instance Count = 1
06-22 07:44:22.675  6021  6021 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-22 07:44:22.675  6021  6021 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
06-22 07:44:22.683  5996  5996 D BluetoothAdapterApp: onCreate
,06-22 07:44:22.699  6022  6022 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:22.699  6022  6022 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
06-22 07:44:22.699  6022  6022 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:44:22.700  6022  6022 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
06-22 07:44:22.700  6022  6022 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-22 07:44:22.701  6022  6022 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-22 07:44:22.701  5996  5996 D ProfileConfigQcom: [BTUI] HeadsetService is supported
06-22 07:44:22.701  5996  5996 D ProfileConfigQcom: Adding HeadsetService
06-22 07:44:22.702  5996  5996 D ProfileConfigQcom: [BTUI] A2dpService is supported
06-22 07:44:22.702  5996  5996 D ProfileConfigQcom: Adding A2dpService
06-22 07:44:22.702  5996  5996 D ProfileConfigQcom: [BTUI] HidService is supported
,06-22 07:44:22.702  5996  5996 D ProfileConfigQcom: Adding HidService
06-22 07:44:22.702  5996  5996 D ProfileConfigQcom: [BTUI] HealthService is supported
06-22 07:44:22.702  5996  5996 D ProfileConfigQcom: Adding HealthService
06-22 07:44:22.702  5996  5996 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
06-22 07:44:22.703  5996  5996 D ProfileConfigQcom: [BTUI] PanService is supported
06-22 07:44:22.703  5996  5996 D ProfileConfigQcom: Adding PanService
06-22 07:44:22.704  5996  5996 D ProfileConfigQcom: [BTUI] GattService is supported
06-22 07:44:22.704  5996  5996 D ProfileConfigQcom: Adding GattService
06-22 07:44:22.704  5996  5996 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
06-22 07:44:22.704  5996  5996 D ProfileConfigQcom: Adding BluetoothMapService
06-22 07:44:22.704  5996  5996 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
06-22 07:44:22.724  1028  1090 D BluetoothManagerService: Message: 20
06-22 07:44:22.725  1028  1090 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40d79c6:true
,06-22 07:44:22.725  5996  5996 D BluetoothAdapterState: make
,06-22 07:44:22.729  5996  5996 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
06-22 07:44:22.729  5996  5996 I bluedroid-qcom: init
06-22 07:44:22.729  5996  6045 I BluetoothAdapterState: Entering OffState
06-22 07:44:22.733  5996  5996 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
06-22 07:44:22.733  5996  5996 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
06-22 07:44:22.733  5996  5996 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
06-22 07:44:22.733  5996  5996 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
06-22 07:44:22.733  5996  5996 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
06-22 07:44:22.734  5996  5996 I bluedroid-qcom: get_profile_interface socket
06-22 07:44:22.734  5996  6049 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
06-22 07:44:22.731  6048  6048 W bdaddr_loader: type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:22.731  6048  6048 W bdaddr_loader: type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:22.736  5996  5996 I bluedroid-qcom: get_profile_interface map_client
,06-22 07:44:22.737  5996  6049 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
06-22 07:44:22.737  5996  6049 D BluetoothAdapterProperties: Name is: G3
06-22 07:44:22.738  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
06-22 07:44:22.738  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
06-22 07:44:22.739  6048  6048 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
06-22 07:44:22.739  6048  6048 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
06-22 07:44:22.739  6048  6048 I LGFTMITEM: [GET_FTM][id=8], offset=16384
06-22 07:44:22.739  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
06-22 07:44:22.740  1028  1090 D BluetoothManagerService: Message: 40
06-22 07:44:22.740  1028  1090 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
06-22 07:44:22.741  5996  6012 I bluedroid-qcom: config_hci_snoop_log
06-22 07:44:22.742  1028  1090 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
06-22 07:44:22.742  1028  1090 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
06-22 07:44:22.743  6048  6048 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
06-22 07:44:22.747  6048  6048 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
06-22 07:44:22.747  6048  6048 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,06-22 07:44:22.749  5996  6011 V LGMDMManagerInternal: Create singleton instance
06-22 07:44:22.770  6021  6021 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-22 07:44:22.797  5996  6045 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-22 07:44:22.797  5996  6045 D BluetoothAdapterProperties: Setting state to 11
06-22 07:44:22.797  5996  6045 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,06-22 07:44:22.798  1028  1090 D BluetoothManagerService: Message: 60
06-22 07:44:22.798  1028  1090 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
06-22 07:44:22.798  1028  1090 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
06-22 07:44:22.799  5996  6045 I LGBluetoothServiceJni: classInitNative: succeeds
06-22 07:44:22.799  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:22.800  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-22 07:44:22.803  5996  6045 D BluetoothBondStateMachine: make
06-22 07:44:22.806  5996  6045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:22.806  5996  6045 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
06-22 07:44:22.806  5996  6045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:22.806  5996  6045 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
06-22 07:44:22.806  5996  6045 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
06-22 07:44:22.808  5996  6050 I BluetoothBondStateMachine: StableState(): Entering Off State
,06-22 07:44:22.814  5996  6045 E BluetoothAdapterService: File transfer profiles supported!!
06-22 07:44:22.819  1028  1028 D BluetoothHeadset: Proxy object connected
06-22 07:44:22.820  1846  1846 D BluetoothHeadset: Proxy object connected
06-22 07:44:22.820  1846  1846 D BluetoothHeadset: Proxy object connected
06-22 07:44:22.820  1846  1846 D BluetoothHeadset: Proxy object connected
,06-22 07:44:22.821  5996  5996 D HeadsetService: Received start request. Starting profile...
06-22 07:44:22.821  5996  5996 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
06-22 07:44:22.821  5996  5996 D LGBluetoothHfpAdapter: Version 1.6
06-22 07:44:22.823  5996  5996 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-22 07:44:22.824  5996  5996 I BluetoothHeadsetServiceJni: classInitNative: succeeds
06-22 07:44:22.824  5996  5996 D HeadsetStateMachine: make
06-22 07:44:22.824  5996  6045 E BluetoothAdapterService: File transfer profiles supported!!
06-22 07:44:22.828  5996  6045 E BluetoothAdapterService: File transfer profiles supported!!
06-22 07:44:22.831  5996  6045 E BluetoothAdapterService: File transfer profiles supported!!
06-22 07:44:22.831  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-22 07:44:22.831  6022  6022 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-22 07:44:22.831  6022  6022 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-22 07:44:22.831  6022  6022 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,06-22 07:44:22.832  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-22 07:44:22.835  5996  6045 E BluetoothAdapterService: File transfer profiles supported!!
06-22 07:44:22.838  5996  6045 E BluetoothAdapterService: File transfer profiles supported!!
06-22 07:44:22.841  5996  6045 E BluetoothAdapterService: File transfer profiles supported!!
06-22 07:44:22.844  5996  5996 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:22.845  5996  5996 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-22 07:44:22.848  5996  5996 D HeadsetStateMachine: max_hf_connections = 1
06-22 07:44:22.848  5996  5996 I bluedroid-qcom: get_profile_interface handsfree
06-22 07:44:22.849  5996  5996 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
06-22 07:44:22.850   318  2158 V AudioPolicyService: registerClient() client 0xb0410360, uid 1002
06-22 07:44:22.850   318  1380 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
06-22 07:44:22.850   318  1380 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-22 07:44:22.850   318  1380 V AudioPolicyManagerEx: getOutput() returns output 2
06-22 07:44:22.850  5996  5996 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-22 07:44:22.850   318   318 V AudioFlinger: registerClient() client 0xb55815b0, pid 5996
06-22 07:44:22.850   318  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:22.851   318  1376 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:22.851  1028  2026 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:22.851  1028  2026 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:22.851  5996  5996 V ToneGenerator: Create Track: 0xb4928a80
06-22 07:44:22.851  5996  5996 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
06-22 07:44:22.851  5996  5996 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
06-22 07:44:22.851  6022  6022 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-22 07:44:22.851  1846  1862 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:22.851  1846  1862 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:22.851   318  1380 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-22 07:44:22.851   318  1380 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
06-22 07:44:22.851  5996  6012 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:22.851   318  1380 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-22 07:44:22.851   318  1380 V AudioPolicyManagerEx: getOutput() returns output 2
06-22 07:44:22.851  5996  6012 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
06-22 07:44:22.851  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-22 07:44:22.851   318  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:22.851   318  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:22.851  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-22 07:44:22.851  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-22 07:44:22.851  6022  6022 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-22 07:44:22.851  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-22 07:44:22.851  1028  1569 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:22.851  1028  1569 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:22.852  1846  2448 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:22.852  1846  2448 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:22.852  5996  5996 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-22 07:44:22.852  5996  6012 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:22.852  5996  6012 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
06-22 07:44:22.852  6022  6022 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-22 07:44:22,.852   318   318 I AudioFlinger: isAudioPlaybackHookOn() false
06-22 07:44:22.852   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-22 07:44:22.852   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
06-22 07:44:22.852   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-22 07:44:22.852   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
06-22 07:44:22.852  5996  5996 V AudioSystem: getLatency() output 2, latency 50
06-22 07:44:22.852  5996  5996 V AudioSystem: getFrameCount() output 2, frameCount 960
06-22 07:44:22.852  5996  5996 V AudioTrack: createTrack_l() output 2 afLatency 50
06-22 07:44:22.852   318  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
06-22 07:44:22.852   318  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
06-22 07:44:22.852   318  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
06-22 07:44:22.852   318  1380 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
06-22 07:44:22.852   318  1380 V AudioFlinger: createTrack() lSessionId: 21
06-22 07:44:22.853  3389  3404 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:22.853  3389  3404 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:22.853  3389  3404 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:22.853  3389  3404 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:22.853  2128  2144 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:22.853  2128  2144 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:22.853  2128  2144 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:22.853  2128  2144 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:22.853  1596  4037 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:22.853  1596  4037 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:22.853  1596  4037 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:22.853  1596  4037 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:22.853  1028  1780 I ActivityManager: Killing 4671:com.android.providers.calendar/u0a14 (adj 15): empty #17
06-22 07:44:22.853  5996  5996 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
06-22 07:44:22.853   318   318 V AudioFlinger: acquiring 21 from 5996, for 5996
06-22 07:44:22.853   318   318 V AudioFlinger:  added new entry for 21
06-22 07:44:22.853  5996  5996 V ToneGenerator: ToneGenerator INIT OK, time: 117230
06-22 07:44:22.853  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:22.854  5996  6051 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-22 07:44:22.854  5996  6051 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-22 07:44:22.854  5996  6051 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-22 07:44:22.854  5996  6051 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
06-22 07:44:22.855   318  1380 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 5996
06-22 07:44:22.855   318  1380 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
06-22 07:44:22.855   318  1380 V voice   : voice_set_parameters: enter: bt_samplerate=8000
06-22 07:44:22.855   318  1380 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
06-22 07:44:22.855   318  1380 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-22 07:44:22.855   318  1380 V voice   : voice_set_parameters: exit with code(0)
06-22 07:44:22.855   318  1380 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
06-22 07:44:22.855   318  1380 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
06-22 07:44:22.855  5996  6045 V LGMDMManager: Create singleton instance
06-22 07:44:22.856   318  1380 V msm8974_platform: platform_set_parameters: exit with code(0)
06-22 07:44:22.856   318  1380 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-22 07:44:22.856   318  1380 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-22 07:44:22.856   318  1380 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
06-22 07:44:22.856  5996  6051 V ToneGenerator: ToneGenerator destructor
06-22 07:44:22.856  5996  6051 V ToneGenerator: stopTone
06-22 07:44:22.856  5996  6051 V ToneGenerator: Delete Track: 0xb4928a80
06-22 07:44:22.857  5996  6051 V AudioTrack: ~AudioTrack, releasing session id from 5996 on behalf of 5996
06-22 07:44:22.857   318  2158 V AudioPolicyService: AudioCommandThread() adding release output 2
06-22 07:44:22.857   318  2158 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
06-22 07:44:22.857   318  1253 V AudioPolicyService: AudioCommandThread() waking up
06-22 07:44:22.857  5996  6045 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-22 07:44:22.857   318  1253 V AudioPolicyService: AudioCommandThread() processing release output 2
06-22 07:44:22.857   318  1380 V AudioFlinger: releasing 21 from 5996 for 5996
06-22 07:44:22.857   318  1253 V AudioPolicyManager: releaseOutput() 2
06-22 07:44:22.857   318  1253 V AudioPolicyService: AudioCommandThread() going to sleep
06-22 07:44:22.857   318  1380 V AudioFlinger:  decremented refcount to 0
06-22 07:44:22.857   318  1380 V AudioFlinger: purging stale effects
06-22 07:44:22.857   318  2158 V AudioFlinger: PlaybackThread::Track destructor
06-22 07:44:22.857   318  2158 V AudioFlinger: removeClient_l() pid 5996, calling pid 318
06-22 07:44:22.861  1028  1952 W Process : Unable to open /proc/6053/status
06-22 07:44:22.884  6021  6021 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,06-22 07:44:22.886  6021  6021 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
06-22 07:44:22.886  6021  6021 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
06-22 07:44:22.889  1028  1532 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
06-22 07:44:22.889  1028  1532 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
06-22 07:44:22.889  1028  6055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
06-22 07:44:22.889  1028  1532 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
06-22 07:44:22.890  1028  6055 D WifiMonitor: Dropping event because (p2p0) is stopped
06-22 07:44:22.890  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
06-22 07:44:22.890  1028  1532 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
06-22 07:44:22.890  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
06-22 07:44:22.890  1028  1532 E WifiStateMachine:  SupplicantStartingState CMD_DISCONNECT 0 0
06-22 07:44:22.890  1028  6055 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
06-22 07:44:22.890  1028  6055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
06-22 07:44:22.890  1028  1532 E WifiStateMachine:  DefaultState CMD_DISCONNECT 0 0
06-22 07:44:22.891  1028  1532 E WifiStateMachine:  SupplicantStartingState CMD_RECONNECT 0 0
06-22 07:44:22.891  1028  1532 E WifiStateMachine:  DefaultState CMD_RECONNECT 0 0
06-22 07:44:22.891  1028  1532 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:22.891  1028  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:22.892  1028  1532 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:22.892  1028  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:22.892  1028  1532 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
06-22 07:44:22.892  1028  1532 D WifiNative-wlan0: doString: [DRIVER MACADDR]
06-22 07:44:22.893  1028  1532 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
06-22 07:44:22.893  1028  1532 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
06-22 07:44:22.893  1028  1532 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
06-22 07:44:22.936  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
,06-22 07:44:22.940  1028  1569 W libprocessgroup: failed to open /acct/uid_10014/pid_4671/cgroup.procs: No such file or directory
06-22 07:44:22.941  1028  1028 D BluetoothA2dp: Proxy object connected
06-22 07:44:22.942  5996  5996 D A2dpService: Received start request. Starting profile...
06-22 07:44:22.942  1028  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-22 07:44:22.942  1028  1532 E WifiStateMachine: useWiFiOffloading() : false
06-22 07:44:22.942  1028  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-22 07:44:22.943  5996  5996 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-22 07:44:22.945  1028  1532 D WifiNative-wlan0: doBoolean: SET update_config 1
06-22 07:44:22.945  5996  5996 V Avrcp   : make
06-22 07:44:22.946  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:22.946  5996  5996 D Avrcp   : [BTUI] Use Native AVRCP : init jni
06-22 07:44:22.946  5996  5996 I bluedroid-qcom: get_profile_interface avrcp
06-22 07:44:22.946  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:22.947  1935  1935 D WfdService: Waiting for WifiP2p enabling
06-22 07:44:22.948  1028  1532 D WifiNative-wlan0: SET update_config 1: returned true
06-22 07:44:22.948  1028  1532 D WifiConfigStore: Loading config and enabling all networks 
06-22 07:44:22.948  1028  1532 D WifiNative-wlan0: doString: [LIST_NETWORKS]
06-22 07:44:22.949  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-22 07:44:22.951  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-22 07:44:22.953  1028  1532 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
06-22 07:44:22.956  1028  1536 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
06-22 07:44:22.960  5778  5778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:22.960  5778  5778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-22 07:44:22.960  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:22.960  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:22.960  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-22 07:44:22.960  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:22.960  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:22.960  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:22.960  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:22.961  5778  5778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:22.961  5778  5778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-22 07:44:22.966  1028  1532 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-22 07:44:22.972  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-22 07:44:22.972  6022  6022 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-22 07:44:22.972  6022  6022 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-22 07:44:22.972  6022  6022 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-22 07:44:22.972  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,06-22 07:44:22.975  1028  1532 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
06-22 07:44:22.975  1028  1532 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
06-22 07:44:22.975  6022  6022 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-22 07:44:22.976  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
06-22 07:44:22.976  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-22 07:44:22.976  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-22 07:44:22.976  6022  6022 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-22 07:44:22.976  6022  6022 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-22 07:44:22.978  5996  5996 V AudioManager: registerRemoteController: size of Media player list: 0
06-22 07:44:22.978  1028  1532 D WifiStateMachine: enableVerboseLogging : level 2
06-22 07:44:22.978  1028  1532 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
06-22 07:44:22.978  1028  1532 D WifiNative-wlan0: SET device_name g3_global_com: returned true
06-22 07:44:22.979  1028  1532 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
06-22 07:44:22.979  1028  1532 D WifiNative-wlan0: SET manufacturer LGE: returned true
06-22 07:44:22.979  1028  1532 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
06-22 07:44:22.979  1028  1532 D WifiNative-wlan0: SET model_name LG-D855: returned true
06-22 07:44:22.979  1028  1532 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
06-22 07:44:22.980  1028  1532 D WifiNative-wlan0: SET model_number LG-D855: returned true
06-22 07:44:22.980  1028  1532 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
06-22 07:44:22.980  1028  1532 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
06-22 07:44:22.981  1028  1532 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
06-22 07:44:22.981  1028  1532 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
06-22 07:44:22.981  1028  1532 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
06-22 07:44:22.982  1028  1532 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
06-22 07:44:22.984  5996  5996 E AudioManager: No RCC entry present to update
06-22 07:44:22.984  5996  5996 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,06-22 07:44:22.986  5996  5996 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,06-22 07:44:22.987  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
06-22 07:44:22.987  5996  5996 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
06-22 07:44:23.023  1028  1044 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6058 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,06-22 07:44:23.026  1028  1532 D WifiStateMachine: Setting OUI to DA-A1-19
06-22 07:44:23.026  1028  1532 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
06-22 07:44:23.026  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
06-22 07:44:23.027  1935  1935 D WfdsService: Supplicant Connection state is changed : true
06-22 07:44:23.028  1935  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
06-22 07:44:23.028  1935  2306 D WfdsService: Set the WFDS Monitor: true
06-22 07:44:23.028  1028  1532 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
06-22 07:44:23.029  1028  1532 D WifiNative-HAL: Setting external_sim to 1
06-22 07:44:23.029  1028  1532 D WifiNative-wlan0: doBoolean: SET external_sim 1
06-22 07:44:23.029  1935  2306 D WfdsMonitor: WfdsMonitorThread create
06-22 07:44:23.029  1935  2306 D WfdsMonitor: WFDS Monitor is created and started
06-22 07:44:23.029  1935  2306 D WfdsService: WiFi: Supplicant connection re-established
06-22 07:44:23.029  1028  1532 D WifiNative-wlan0: SET external_sim 1: returned true
06-22 07:44:23.029  1028  1532 I WifiNative-HAL: startHal
06-22 07:44:23.030  1028  1532 E wifi    : getStaticLongField sWifiHalHandle 0x987ba8dc
06-22 07:44:23.030  1028  1532 E WifiHAL : Could not connect handle
06-22 07:44:23.030  1028  1532 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301f26
06-22 07:44:23.030  1028  1532 I WifiNative-HAL: Could not start hal
06-22 07:44:23.030  1028  1532 D WifiStateMachine: Setting OUI to DA-A1-19
06-22 07:44:23.030  1028  1532 I WifiNative-HAL: startHal
06-22 07:44:23.030  1028  1532 E wifi    : getStaticLongField sWifiHalHandle 0x987ba85c
06-22 07:44:23.030  1028  1532 E WifiHAL : Could not connect handle
06-22 07:44:23.030  1028  1532 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301f22
06-22 07:44:23.030  1028  1532 I WifiNative-HAL: Could not start hal
06-22 07:44:23.030  1028  1532 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
06-22 07:44:23.030  1028  1532 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
06-22 07:44:23.030  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
06-22 07:44:23.031  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
06-22 07:44:23.031  1028  1532 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
06-22 07:44:23.044  1935  6072 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
06-22 07:44:23.044  1935  6072 E CtrlSupplicant: Succeed to open control connection
06-22 07:44:23.044  1935  6072 E CtrlSupplicant: Succeed to open monitor connection
06-22 07:44:23.045  1935  6072 D WfdsMonitor: Supplicant connection established
06-22 07:44:23.045  1935  2306 D WfdsService: Connected to the supplicant for wfds
06-22 07:44:23.050   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 471us total 31.614ms
,06-22 07:44:23.068  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
06-22 07:44:23.068  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
06-22 07:44:23.068  1028  1532 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
06-22 07:44:23.068  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
06-22 07:44:23.068  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
06-22 07:44:23.068  1028  1532 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
06-22 07:44:23.068  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
06-22 07:44:23.068  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
06-22 07:44:23.069  1028  1532 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
06-22 07:44:23.069  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
06-22 07:44:23.069  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,06-22 07:44:23.070   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 398us total 19.038ms
06-22 07:44:23.070  1028  1532 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
06-22 07:44:23.070  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
06-22 07:44:23.070  6021  6021 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
06-22 07:44:23.070  1028  1532 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
06-22 07:44:23.070  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
06-22 07:44:23.071  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
06-22 07:44:23.071  1028  1532 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
06-22 07:44:23.072  1028  1532 E WifiNative: : [117,435,999 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
06-22 07:44:23.072  1028  1532 D WifiNative-wlan0: doBoolean: RECONNECT
06-22 07:44:23.072  1028  1532 D WifiNative-wlan0: RECONNECT: returned true
06-22 07:44:23.072  1028  1532 D WifiNative-wlan0: doString: [STATUS]
06-22 07:44:23.072  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
06-22 07:44:23.072  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
06-22 07:44:23.073  1028  1532 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
06-22 07:44:23.073  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
06-22 07:44:23.074  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
06-22 07:44:23.074  1028  1532 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
06-22 07:44:23.074  1028  1532 D WifiNative-wlan0: doBoolean: SET ps 1
06-22 07:44:23.074  1028  1532 D WifiNative-wlan0: SET ps 1: returned true
06-22 07:44:23.074  1028  1028 D WifiHS20: hidePasspointNotification off =false
06-22 07:44:23.075  1028  1531 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.076   313   888 D CommandListener: Setting iface cfg
06-22 07:44:23.076   313   888 D CommandListener: Trying to bring up p2p0
06-22 07:44:23.076  1028  1531 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-22 07:44:23.076  1028  1531 D LGWifiP2pService: P2pEnablingState
06-22 07:44:23.076  1028  1531 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.076  1028  1531 D LGWifiP2pService: P2p socket connection successful
06-22 07:44:23.076  1028  1531 D LGWifiP2pService: P2pEnabledState
06-22 07:44:23.078  1028  1531 D LGWifiP2pService: sending p2p connection changed broadcast
06-22 07:44:23.079  1028  1531 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
06-22 07:44:23.079  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:23.079  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:23.080  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.080  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.080  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-22 07:44:23.080  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:23.088   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 356us total 17.428ms
06-22 07:44:23.091  1935  1935 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
06-22 07:44:23.092  1028  1531 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
06-22 07:44:23.092  1028  1531 D WifiNative-p2p0: doBoolean: SET device_name G3
06-22 07:44:23.093  1028  1531 D WifiNative-p2p0: SET device_name G3: returned true
06-22 07:44:23.093  1028  1531 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
06-22 07:44:23.093  1028  1531 D LGWifiP2pService: before postfix = G3
06-22 07:44:23.093  1028  1531 D WifiServerServiceExt: postfix byte check : 2
06-22 07:44:23.093  1028  1531 D LGWifiP2pService: after postfix = G3
06-22 07:44:23.093  1028  1531 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,06-22 07:44:23.094  1028  1531 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
06-22 07:44:23.094  1028  1531 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
06-22 07:44:23.095  1028  1531 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
06-22 07:44:23.095  1028  1531 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
06-22 07:44:23.095  1028  1531 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
06-22 07:44:23.095  1028  1531 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
06-22 07:44:23.096  1028  1531 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
06-22 07:44:23.096  1028  1531 D WifiNative-HAL: p2pGetDeviceAddress
06-22 07:44:23.096  1028  1531 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
06-22 07:44:23.097  1028  1531 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
06-22 07:44:23.097  1028  1531 D WifiNative-p2p0: doBoolean: P2P_FLUSH
06-22 07:44:23.098  1028  1531 D WifiNative-p2p0: P2P_FLUSH: returned true
06-22 07:44:23.098  1028  1531 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
06-22 07:44:23.098  1028  1531 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
06-22 07:44:23.098  1028  1531 D WifiNative-p2p0: doString: [LIST_NETWORKS]
06-22 07:44:23.098  1028  1531 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
06-22 07:44:23.098  1028  1531 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
06-22 07:44:23.102  1028  1538 D WifiService: New client listening to asynchronous messages
06-22 07:44:23.103  1935  1935 D WfdsService: WifiP2pState is changed : true
06-22 07:44:23.103  1935  2306 D WfdsService: Receive the WFDS_ENABLE Method
06-22 07:44:23.103  1935  2306 D WfdsService: Set the WFDS Monitor: true
06-22 07:44:23.103  1935  2306 D WfdsService: Connected to the supplicant for wfds
06-22 07:44:23.103  1935  2306 D WfdsJNI : doCommand: WFDS_SET TRUE
06-22 07:44:23.105  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 3
06-22 07:44:23.105  1028  1028 D RttService: SCAN_AVAILABLE : 3
,06-22 07:44:23.105  1028  1550 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.105  1028  1550 I WifiNative-HAL: startHal
06-22 07:44:23.105  1028  1551 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.105  1028  1532 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
06-22 07:44:23.106  1028  1532 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
06-22 07:44:23.106  6021  6021 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
06-22 07:44:23.106  1935  2306 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
06-22 07:44:23.106  1028  1532 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
06-22 07:44:23.106  1028  1531 D WifiNative-p2p0: SAVE_CONFIG: returned true
06-22 07:44:23.106  6021  6021 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
06-22 07:44:23.106  1028  1550 E wifi    : getStaticLongField sWifiHalHandle 0x94b8799c
06-22 07:44:23.106  1028  1531 D LGWifiP2pService: sending p2p persistent groups changed broadcast
06-22 07:44:23.106  1028  1550 E WifiHAL : Could not connect handle
06-22 07:44:23.106  1028  1550 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301e5e
06-22 07:44:23.106  1028  1550 I WifiNative-HAL: Could not start hal
06-22 07:44:23.107  1028  1532 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
06-22 07:44:23.107  1028  1531 D LGWifiP2pService: InactiveState
06-22 07:44:23.107  1028  1550 E WifiScanningService: could not start HAL
06-22 07:44:23.107  1028  1531 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.107  1028  1531 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.107  1028  1531 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
06-22 07:44:23.107  1028  1532 E WifiStateMachine:  DisconnectedState what:132106 1 0
06-22 07:44:23.107  1935  2306 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
06-22 07:44:23.107  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
06-22 07:44:23.107  1028  1532 E WifiStateMachine:  ConnectModeState what:132106 1 0
06-22 07:44:23.107  6021  6021 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-22 07:44:23.108  1028  1532 E WifiStateMachine:  DriverStartedState what:132106 1 0
06-22 07:44:23.108  1028  1532 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
06-22 07:44:23.108  6021  6021 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
06-22 07:44:23.108  6021  6021 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.108  1028  1532 E WifiStateMachine:  DisconnectedState what:132096 -100 0
06-22 07:44:23.108  6021  6021 E wpa_supplicant: nWIFIDualbandAPConnection: 1
06-22 07:44:23.108  6021  6021 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.109  1028  1532 E WifiStateMachine:  ConnectModeState what:132096 -100 0
06-22 07:44:23.109  1028  1532 E WifiStateMachine:  DriverStartedState what:132096 -100 0
06-22 07:44:23.109  1028  1532 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
06-22 07:44:23.109  1935  6072 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,06-22 07:44:23.109  6021  6021 E wpa_supplicant: disconnect_rssi_lvl: -100
06-22 07:44:23.109  1028  6055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
06-22 07:44:23.109  1028  6055 E WifiMonitor: WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-22 07:44:23.109  1028  6055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-22 07:44:23.109  1028  6055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-22 07:44:23.109  1028  6055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-22 07:44:23.109  1028  6055 E WifiMonitor: WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.109  1028  1532 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
06-22 07:44:23.110  1028  1531 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
06-22 07:44:23.110  1028  1531 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.110  1028  1531 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.110  1028  1531 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.110  1028  1532 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
06-22 07:44:23.110  1028  1531 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.110  1028  1531 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.110  1028  1531 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.110  1935  2306 D WfdsService: selectPreferredScanChannel [36]
06-22 07:44:23.110  1935  2306 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
06-22 07:44:23.110  1028  1532 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
06-22 07:44:23.110  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
06-22 07:44:23.111  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
06-22 07:44:23.111  1935  6072 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-22 07:44:23.111  1935  6072 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-22 07:44:23.111  6021  6021 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-22 07:44:23.111  1935  1935 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
06-22 07:44:23.111  6021  6021 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
06-22 07:44:23.112  6021  6021 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.112  1935  1935 D WfdsService: isConnected: false
06-22 07:44:23.112  6021  6021 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1935  6072 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-22 07:44:23.113  1935  6072 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-22 07:44:23.113  1028  6055 E WifiMonitor: WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
06-22 07:44:23.113  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-22 07:44:23.113  1028  6055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-22 07:44:23.113  1028  6055 E WifiMonitor: WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-22 07:44:23.113  1028  6055 E WifiMonitor: WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.113  1028  6055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-22 07:44:23.114  1028  1531 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.114  1028  1028 E WifiServerServiceExt: No p2p device connected
06-22 07:44:23.114  1028  1531 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.114  1028  1531 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.114  1028  1531 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.114  1028  1531 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.114  1028  1531 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.114  1028  1532 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
06-22 07:44:23.114  1028  1531 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.115  1028  1531 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.115  1028  1532 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
06-22 07:44:23.115  1028  1532 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
06-22 07:44:23.116  1028  1532 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
06-22 07:44:23.116  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
06-22 07:44:23.116  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
06-22 07:44:23.116  6021  6021 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-22 07:44:23.116  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
06-22 07:44:23.117  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-22 07:44:23.117  1028  6055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-22 07:44:23.117  1028  6055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-22 07:44:23.117  1028  1532 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
06-22 07:44:23.117  1028  1532 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
06-22 07:44:23.117  1028  1532 D WifiNative-wlan0: BSS_FLUSH 0: returned true
06-22 07:44:23.118  1028  1532 D WifiNative-wlan0: doBoolean: SCAN
06-22 07:44:23.118  1028  1532 D WifiNative-wlan0: SCAN: returned false
06-22 07:44:23.119  1028  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=117483  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,06-22 07:44:23.120  1028  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=117484  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-22 07:44:23.120  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:23.120  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:23.120  1028  1532 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:44:23.121  1028  1532 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:44:23.123  1028  1569 V SIM_STK : Menu title from STK is T-Mobile
06-22 07:44:23.123  1028  1569 V SIM_STK : Menu title from STK is T-Mobile
06-22 07:44:23.125  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.125  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.125  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-22 07:44:23.126  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:23.127  1028  1532 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:44:23.127  1028  1532 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:44:23.128  1028  1532 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:44:23.129  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:23.129  1028  1028 D WifiServerServiceExt: setSupplicantStateSCANNING
06-22 07:44:23.133  1935  1935 I WfdStateTracker: handleP2pThisDeviceChanged
06-22 07:44:23.133  1935  1935 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,06-22 07:44:23.134  1935  1935 D WfdsService: Update P2p Interface State: 3
06-22 07:44:23.135  1935  2306 W WfdsService: DefaultState - msg [9441285] is not handled
06-22 07:44:23.166  1028  1569 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6081 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-22 07:44:23.173  1028  1917 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
06-22 07:44:23.174  6058  6079 W FormManager: Network not available. Please check & try again.
06-22 07:44:23.177  6058  6080 V FormManager: Network unavailable.
,06-22 07:44:23.179  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
06-22 07:44:23.180  6058  6080 V FormManager: Network unavailable.
06-22 07:44:23.182  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-22 07:44:23.183  5996  5996 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
06-22 07:44:23.183  5996  5996 I BluetoothA2dpServiceJni: classInitNative
06-22 07:44:23.183  5996  5996 I BluetoothA2dpServiceJni: classInitNative: succeeds
06-22 07:44:23.183  5996  5996 D A2dpStateMachine: make
06-22 07:44:23.184  5996  5996 I bluedroid-qcom: get_profile_interface a2dp
06-22 07:44:23.184  5996  6100 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-22 07:44:23.186  5996  5996 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,06-22 07:44:23.186  5996  5996 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,06-22 07:44:23.187  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:23.187  5996  5996 I BluetoothHidServiceJni: classInitNative: succeeds
06-22 07:44:23.189  5996  5996 D HidService: Received start request. Starting profile...
06-22 07:44:23.189  5996  5996 I bluedroid-qcom: get_profile_interface hidhost
06-22 07:44:23.189  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:23.189  5996  5996 I BluetoothHealthServiceJni: classInitNative: succeeds
06-22 07:44:23.191  5996  5996 D HealthService: Received start request. Starting profile...
06-22 07:44:23.191  5996  6098 D A2dpStateMachine: Enter Disconnected: -2
06-22 07:44:23.192  5996  5996 I bluedroid-qcom: get_profile_interface health
06-22 07:44:23.192  5996  5996 I LGBluetoothHealthServiceJni: classInitNative: succeeds
06-22 07:44:23.192  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:23.193  5996  5996 I BluetoothPanServiceJni: classInitNative(L105): succeeds
06-22 07:44:23.194  1028  1971 I ActivityManager: Killing 5543:com.google.android.partnersetup/u0a8 (adj 15): empty #17
06-22 07:44:23.194  5996  5996 D PanService: Received start request. Starting profile...
06-22 07:44:23.194  5996  5996 D BluetoothPanServiceJni: initializeNative(L110): pan
06-22 07:44:23.194  5996  5996 I bluedroid-qcom: get_profile_interface pan
06-22 07:44:23.265  1028  1724 W libprocessgroup: failed to open /acct/uid_10008/pid_5543/cgroup.procs: No such file or directory
,06-22 07:44:23.267  5996  5996 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
06-22 07:44:23.267  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:23.270  5996  5996 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
06-22 07:44:23.286  5996  5996 D BtGatt.DebugUtils: handleDebugAction() action=null
06-22 07:44:23.287  5996  5996 D BtGatt.GattService: Received start request. Starting profile...
06-22 07:44:23.287  5996  5996 D BtGatt.GattService: start()
06-22 07:44:23.287  5996  5996 I bluedroid-qcom: get_profile_interface gatt
,06-22 07:44:23.288  5996  5996 D BtGatt.AdvertiseManager: advertise manager created
,06-22 07:44:23.307  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
,06-22 07:44:23.311  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:23.312  5996  5996 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
06-22 07:44:23.314  5996  5996 V BluetoothMapService: BluetoothMapBinder()
06-22 07:44:23.314  5996  5996 D BluetoothMapService: Received start request. Starting profile...
06-22 07:44:23.314  5996  5996 D BluetoothMapService: start()
06-22 07:44:23.316  6081  6081 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:23.317  5996  5996 D BluetoothMapEmailSettingsLoader: Found 0 applications
06-22 07:44:23.317  5996  5996 D BluetoothMapEmailAppObserver: createReceiver()
06-22 07:44:23.319  5996  5996 D BluetoothMapEmailAppObserver: initObservers()
06-22 07:44:23.319  5996  5996 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,06-22 07:44:23.328  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:23.329  5996  5996 D HeadsetStateMachine: Proxy object connected
06-22 07:44:23.329  5996  5996 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
06-22 07:44:23.329  5996  5996 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
06-22 07:44:23.330  1846  1846 D BluetoothPhoneService.BluetoothLTECall:  call mBluetoothHeadset.phoneStateChanged()
06-22 07:44:23.331  5996  5996 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-22 07:44:23.331  1846  1846 W BluetoothHeadset: Proxy not attached to service
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: java.lang.Throwable
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-22 07:44:23.331  1846  1846 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-22 07:44:23.332  5996  5996 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:23.332  5996  5996 V BluetoothPbapReceiver: ***********state = 11
,06-22 07:44:23.334  2202  2202 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-22 07:44:23.335  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-22 07:44:23.336  5996  5996 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-22 07:44:23.336  5996  6051 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:44:23.337  5996  6051 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-22 07:44:23.338  5996  6051 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-22 07:44:23.339  1028  1538 D WifiService: New client listening to asynchronous messages
06-22 07:44:23.340  5996  5996 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-22 07:44:23.342  5996  5996 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-22 07:44:23.344  5996  5996 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,06-22 07:44:23.346  5996  5996 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-22 07:44:23.347  5996  5996 V PanService: [BTUI] SIM Extra State :ABSENT
06-22 07:44:23.348  5996  5996 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
06-22 07:44:23.349  5996  5996 V BluetoothMapService: Handler(): got msg=1
06-22 07:44:23.349  5996  6045 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-22 07:44:23.349  5996  6045 I bluedroid-qcom: enable
06-22 07:44:23.349  5996  6111 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
06-22 07:44:23.349  5996  6045 I bt_hci_bdroid: init
06-22 07:44:23.349  5996  6111 I bt-btu  : btu_task pending for preload complete event
06-22 07:44:23.359  5996  6045 I bt_vendor: bt-vendor : init
,06-22 07:44:23.359  5996  6045 I bt_vendor: bt-vendor : get_bt_soc_type
06-22 07:44:23.359  5996  6045 E bt_vendor: get_bt_soc_type: Failed to get soc type
06-22 07:44:23.359  5996  6045 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
06-22 07:44:23.359  5996  6045 D bt_userial_mct: userial_init
06-22 07:44:23.360  5996  6045 D bt_hci_bdroid: set_power 1
06-22 07:44:23.360  5996  6045 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
06-22 07:44:23.360  5996  6045 I bt_vendor: Starting hciattach daemon
06-22 07:44:23.360  5996  6045 I bt_vendor: try to set true
,06-22 07:44:23.351  6114  6114 W sh      : type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:23.351  6114  6114 W sh      : type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:23.371  1028  1916 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6115 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
06-22 07:44:23.372  6118  6118 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,06-22 07:44:23.376  6022  6022 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:23.376  6022  6022 D LgDataFeature: LgDataFeature() Constructor Done, null
06-22 07:44:23.384  6022  6022 D WiFiOffLoadUpdatePriority: remove : truetruetrue
,06-22 07:44:23.394  1028  1532 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
06-22 07:44:23.394  1028  1532 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,06-22 07:44:23.399  1028  1532 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
06-22 07:44:23.399  1028  1532 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
06-22 07:44:23.399  1028  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-22 07:44:23.412  1028  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
,06-22 07:44:23.413  6022  6022 D WiFiOffLoadUpdatePriority: remove1
06-22 07:44:23.413  6022  6022 V WiFiOffLoadSharedPrefsUtils: save remove
06-22 07:44:23.420  6022  6022 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
06-22 07:44:23.420  6022  6022 D WiFiOffLoadBroadcast: S: false, R: false
06-22 07:44:23.421  1028  1532 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
06-22 07:44:23.422  1028  1532 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
06-22 07:44:23.423  6022  6022 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
06-22 07:44:23.423  6022  6022 D WiFiOffLoadUpdatePriority: connected SSID: null
06-22 07:44:23.423  6022  6022 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
06-22 07:44:23.425  1028  1044 D WifiServiceImplEx: addOrUpdateNetwork pid=6022, uid=1000, packageName=android.uid.system:1000
06-22 07:44:23.426  1028  1044 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
06-22 07:44:23.426  1028  1532 E WifiStateMachine:  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
06-22 07:44:23.427  1028  1532 E WifiStateMachine:  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
,06-22 07:44:23.427  1028  1532 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
06-22 07:44:23.427  1028  1532 D WifiServerServiceExt: addOrUpdateNetwork: mThisIsFirstEnableing = false
06-22 07:44:23.427  1028  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 ssid 4e47373030
06-22 07:44:23.427  6139  6139 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
06-22 07:44:23.433  6140  6140 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
06-22 07:44:23.444  6142  6142 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,06-22 07:44:23.449  6143  6143 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
06-22 07:44:23.453  1028  1532 D WifiNative-wlan0: SET_NETWORK 0 ssid 4e47373030: returned true
06-22 07:44:23.453  1028  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
06-22 07:44:23.453  1028  1532 D WifiNative-wlan0: SET_NETWORK 0 key_mgmt WPA-PSK: returned true
06-22 07:44:23.453  1028  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 proto WPA RSN
06-22 07:44:23.453  1028  1532 D WifiNative-wlan0: SET_NETWORK 0 proto WPA RSN: returned true
06-22 07:44:23.454  1028  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
06-22 07:44:23.454  1028  1532 D WifiNative-wlan0: SET_NETWORK 0 pairwise TKIP CCMP: returned true
06-22 07:44:23.454  1028  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
06-22 07:44:23.454  1028  1532 D WifiNative-wlan0: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
06-22 07:44:23.454  1028  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 priority 300
06-22 07:44:23.455  1028  1532 D WifiNative-wlan0: SET_NETWORK 0 priority 300: returned true
06-22 07:44:23.455  6145  6145 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
06-22 07:44:23.455  1028  1532 E WifiConfigStore: will read network variables netId=0
06-22 07:44:23.458  6115  6115 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
06-22 07:44:23.458  6115  6115 W LG Account v2.2: No ProfileInfo entries
06-22 07:44:23.458  6115  6115 I LG Account v2.2: isEnabled: false
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]ver: 4.21.112(40211120)
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Country: EU
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Operator: OPEN
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Ranking support: false
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Comfort support: false
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Accessory: true
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Health device: true
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Extra Pedometer: false
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Blood glucose device: false
06-22 07:44:23.458  6115  6115 I Feature : [Lifetracker]Device Number: 3
06-22 07:44:23.459  1028  1532 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
06-22 07:44:23.459  1028  1532 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
,06-22 07:44:23.460  6022  6022 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
06-22 07:44:23.461  6022  6022 D WiFiOffLoadUpdatePriority: configuration updated: 0
06-22 07:44:23.461  1028  1532 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
06-22 07:44:23.461  1028  1532 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
06-22 07:44:23.461  1028  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-22 07:44:23.462  6147  6147 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
06-22 07:44:23.462  1028  1569 I ActivityManager: Killing 5576:com.lge.appbox.client/u0a11 (adj 15): empty #17
06-22 07:44:23.479  1028  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
06-22 07:44:23.479  6022  6022 D WiFiOffLoadUpdatePriority: configuration saved: true
06-22 07:44:23.480  6149  6149 I libmdmdetect: ESOC framework not supported
06-22 07:44:23.480  6149  6149 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,06-22 07:44:23.484  6149  6149 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
06-22 07:44:23.484  6149  6149 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
06-22 07:44:23.484  6149  6149 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
06-22 07:44:23.484  6149  6149 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
06-22 07:44:23.484  6149  6149 D bthci_qcomm_common: [BTUI]     LE: Class 2
06-22 07:44:23.484  6149  6149 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
06-22 07:44:23.484  6149  6149 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
06-22 07:44:23.506  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
06-22 07:44:23.506  6021  6021 E wpa_supplicant: USIM:  scard_init function
06-22 07:44:23.506  1028  6055 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
06-22 07:44:23.506  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
06-22 07:44:23.506  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
06-22 07:44:23.507  6021  6021 I wpa_supplicant: Trying to associate with SSID 'NG700'
06-22 07:44:23.507  1028  6055 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
06-22 07:44:23.507  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
06-22 07:44:23.507  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
06-22 07:44:23.507  1028  1532 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
,06-22 07:44:23.507  1028  1532 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-22 07:44:23.508  1028  1532 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-22 07:44:23.508  1028  1532 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-22 07:44:23.508  1028  1532 I WifiNative-HAL: startHal
06-22 07:44:23.508  1028  1532 E wifi    : getStaticLongField sWifiHalHandle 0x987ba8cc
06-22 07:44:23.509  1028  1532 E WifiHAL : Could not connect handle
06-22 07:44:23.509  1028  1532 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501cca
06-22 07:44:23.509  1028  1532 I WifiNative-HAL: Could not start hal
06-22 07:44:23.509  1028  1532 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
06-22 07:44:23.564  1028  1881 W libprocessgroup: failed to open /acct/uid_10011/pid_5576/cgroup.procs: No such file or directory
,06-22 07:44:23.573  1028  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=117937  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
06-22 07:44:23.584  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-22 07:44:23.584  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:23.584  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.585  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.585  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-22 07:44:23.588  1028  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=117953  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
06-22 07:44:23.588  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:23.591  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.591  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.591  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-22 07:44:23.591  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:23.591  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATING
06-22 07:44:23.601  6022  6022 D BluetoothPermissionRequest: onReceive
06-22 07:44:23.601  6022  6022 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,06-22 07:44:23.612  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:23.612  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:23.616  6021  6021 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,06-22 07:44:23.616  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
06-22 07:44:23.616  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
06-22 07:44:23.616  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
06-22 07:44:23.616  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with f4:f2:6d:22:99:3e
06-22 07:44:23.616  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-22 07:44:23.616  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:44:23.617  1028  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=117981  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
06-22 07:44:23.617  1028  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=117982  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
06-22 07:44:23.618  1028  1532 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=117983
06-22 07:44:23.619  1028  1532 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=117983
06-22 07:44:23.619  1028  1532 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=117984
06-22 07:44:23.619  1028  1532 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=117984
06-22 07:44:23.620  1028  1532 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=117984
06-22 07:44:23.620  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:23.620  1028  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=117985  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
06-22 07:44:23.623  1028  1090 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-22 07:44:23.623  6021  6021 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-22 07:44:23.623  6021  6021 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-22 07:44:23.624  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-22 07:44:23.624  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:44:23.624  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,06-22 07:44:23.624  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-22 07:44:23.624  1028  6055 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-22 07:44:23.624  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
06-22 07:44:23.624  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-22 07:44:23.624  1028  6055 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-22 07:44:23.625  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-22 07:44:23.625  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:44:23.627  1028  1090 D BluetoothManagerService: Message: 20
06-22 07:44:23.627  1028  1090 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e6645ae:true
,06-22 07:44:23.633  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.633  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.633  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,06-22 07:44:23.636  1028  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=118000  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
06-22 07:44:23.638  1028  2026 I ActivityManager: Killing 5593:com.android.contacts/u0a19 (adj 15): empty #17
06-22 07:44:23.642  6022  6022 D LGBluetoothResetSettingReceiver: return without doing reset settings.
06-22 07:44:23.642  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:23.642  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-22 07:44:23.646  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:23.777  1028  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=118141  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
06-22 07:44:23.778  5996  5996 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,06-22 07:44:23.780  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:23.780  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-22 07:44:23.782  1028  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=118146  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
06-22 07:44:23.784  1028  1532 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=118148
06-22 07:44:23.785  1028  1532 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=118149
06-22 07:44:23.785  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.785  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.785  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
06-22 07:44:23.786  1028  1532 D WifiNative-wlan0: doString: [STATUS]
06-22 07:44:23.787  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:23.788  1028  6055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-22 07:44:23.788  1028  6055 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:44:23.789  1028  1532 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
06-22 07:44:23.789  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:23.789  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATED
06-22 07:44:23.791  1028  1780 W libprocessgroup: failed to open /acct/uid_10019/pid_5593/cgroup.procs: No such file or directory
,06-22 07:44:23.801  1028  1532 I WifiServiceExtension: setVHTCapabilityType  : false
06-22 07:44:23.812  5996  5996 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,06-22 07:44:23.816  5996  5996 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-22 07:44:23.817  5996  5996 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-22 07:44:23.817  5996  5996 V BluetoothSapReceiver: SapReceiver onReceive 
06-22 07:44:23.818  5996  5996 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:23.818  5996  5996 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,06-22 07:44:23.892  1028  1724 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6156 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-22 07:44:23.899  1028  1532 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
06-22 07:44:23.899  1028  1532 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
06-22 07:44:23.903  6081  6081 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:23.904  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:23.904  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:23.905  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:23.905  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.905  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.905  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
06-22 07:44:23.909  6058  6154 W FormManager: Network not available. Please check & try again.
,06-22 07:44:23.915  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.915  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:23.915  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
06-22 07:44:23.925  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:23.925  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-22 07:44:23.926  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-22 07:44:23.927  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-22 07:44:23.934  1028  1532 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
06-22 07:44:23.934  1028  1539 D ConnectivityService: Got NetworkAgent Messenger
06-22 07:44:23.935  1028  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
06-22 07:44:23.935  1028  1539 D ConnectivityService: NetworkAgent connected
06-22 07:44:23.935  1028  1532 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-22 07:44:23.935  1028  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
06-22 07:44:23.936  1028  1532 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
06-22 07:44:23.936  1028  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,06-22 07:44:23.937  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:23.944  1028  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
06-22 07:44:23.944  1028  1532 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-22 07:44:23.944  1028  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
06-22 07:44:23.947  1028  1532 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
06-22 07:44:23.947  1028  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-22 07:44:23.949  6058  6155 V FormManager: Network unavailable.
,06-22 07:44:23.952  3224  3224 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-22 07:44:23.952  3224  3224 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-22 07:44:23.953  1028  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
06-22 07:44:23.954  6058  6155 V FormManager: Network unavailable.
06-22 07:44:23.954   313   888 D CommandListener: Setting iface cfg
06-22 07:44:23.954  3224  3224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,06-22 07:44:23.957  3224  3224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-22 07:44:23.961  1028  1532 E WifiStateMachine: Start Dhcp Watchdog 1
06-22 07:44:23.961  1028  6174 D DhcpStateMachine: StoppedState
,06-22 07:44:23.961  1028  6174 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.961  1028  6174 D DhcpStateMachine: WaitBeforeStartState
06-22 07:44:23.961  1028  1532 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=118326  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-22 07:44:23.962  1028  1532 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=118326  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-22 07:44:23.962  1028  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=118326  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-22 07:44:23.962  1028  1532 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:23.962  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:23.963  1028  1532 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:23.963  1028  1532 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:23.963  1028  1532 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:23.963  1028  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:44:23.964  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:23.964  1028  1028 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
06-22 07:44:23.965  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:23.965  6156  6156 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:44:23.965  1028  1532 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=118329  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-22 07:44:23.965  1028  1028 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
06-22 07:44:23.965  1028  1532 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=118330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-22 07:44:23.965  1028  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=118330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-22 07:44:23.966  1028  1532 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1990416030] from screen [on:0 period:1990416030]
06-22 07:44:23.967  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1990416031]
06-22 07:44:23.967  1028  1532 I WifiNative-HAL: startHal
06-22 07:44:23.967  1028  1532 E wifi    : getStaticLongField sWifiHalHandle 0x987ba8bc
06-22 07:44:23.967  1028  1532 E WifiHAL : Could not connect handle
06-22 07:44:23.967  1028  1532 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0xa01aea
06-22 07:44:23.967  1028  1532 I WifiNative-HAL: Could not start hal
06-22 07:44:23.967  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:44:23.968  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:23.968  3224  6175 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-22 07:44:23.970  3224  6176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-22 07:44:23.970  3224  6176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-22 07:44:23.972  1028  1532 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:23.973  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:23,.973  1028  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:23.973  1028  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:23.973  1028  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,06-22 07:44:23.973  1028  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:23.973  1028  1539 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
06-22 07:44:23.974  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-22 07:44:23.974  1028  1532 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
06-22 07:44:23.974  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
06-22 07:44:23.974  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
06-22 07:44:23.975  1028  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-22 07:44:23.977  6081  6081 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-22 07:44:23.979  6081  6081 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-22 07:44:23.979  6081  6081 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:23.982  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:23.993  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
06-22 07:44:23.993  1028  1532 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
06-22 07:44:23.993  1028  1532 D WifiNative-wlan0: doBoolean: SET ps 0
06-22 07:44:23.993  1028  1532 D WifiNative-wlan0: SET ps 0: returned true
06-22 07:44:23.993  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
06-22 07:44:23.993  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
06-22 07:44:23.993  1028  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
06-22 07:44:23.994  1028  1532 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
06-22 07:44:23.994  1028  1532 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-22 07:44:23.994  1028  1532 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-22 07:44:23.994  1028  1532 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
06-22 07:44:23.994  1028  1531 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34c553a4 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.994  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:23.994  1028  1531 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34c553a4 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.994  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
06-22 07:44:23.994  1028  6174 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:23.995  1028  6174 D DhcpStateMachine: DHCP Start wake lock is acquired.
06-22 07:44:23.996  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:23.996  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
06-22 07:44:23.996  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.032  1028  1952 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6178 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,06-22 07:44:24.033  1028  1952 I ActivityManager: Killing 5620:com.lge.email/u0a23 (adj 15): empty #17
06-22 07:44:24.104  1028  2027 W libprocessgroup: failed to open /acct/uid_10023/pid_5620/cgroup.procs: No such file or directory
,06-22 07:44:24.149  6178  6178 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-22 07:44:24.175  6178  6178 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,06-22 07:44:24.198  1028  6174 D DhcpStateMachine: DHCPV4 request on wlan0
,06-22 07:44:24.199  1028  6174 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
06-22 07:44:24.200  1028  6174 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
06-22 07:44:24.207  6178  6178 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
06-22 07:44:24.208  6178  6178 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
06-22 07:44:24.208  6178  6178 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
06-22 07:44:24.208  6178  6178 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
06-22 07:44:24.209  6178  6178 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
06-22 07:44:24.211  6178  6178 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,06-22 07:44:24.216  6178  6178 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
06-22 07:44:24.222  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.221  6195  6195 W dhcpcd  : type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,06-22 07:44:24.221  6195  6195 W dhcpcd  : type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:24.225  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.236  6195  6195 I dhcpcd  : version 5.5.6 starting
,06-22 07:44:24.237  6195  6195 E dhcpcd  : get_duid: m
06-22 07:44:24.237  6195  6195 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
06-22 07:44:24.237  6195  6195 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
06-22 07:44:24.239  6178  6178 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-22 07:44:24.241  6178  6178 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
06-22 07:44:24.243  5920  5920 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-22 07:44:24.243  5920  5920 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
06-22 07:44:24.247  6178  6178 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
06-22 07:44:24.250  5920  5920 V [BNRBootReceiver]: Boot Receiver Return
,06-22 07:44:24.254  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.268  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:24.278  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.284  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,06-22 07:44:24.284  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.285  6178  6178 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-22 07:44:24.288  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
06-22 07:44:24.290  6022  6022 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
06-22 07:44:24.292  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.297  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:24.302  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.306  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.307  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.308  6178  6178 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-22 07:44:24.310  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,06-22 07:44:24.316  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:24.318  6195  6195 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
06-22 07:44:24.319  6195  6195 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
06-22 07:44:24.319  6195  6195 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
06-22 07:44:24.320  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.325  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.325  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.325  6178  6178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,06-22 07:44:24.326  6195  6195 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
06-22 07:44:24.326  6195  6195 D dhcpcd  : wlan0: sending REQUEST (xid 0x70a098e0), next in 3.74 seconds
06-22 07:44:24.327  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-22 07:44:24.327  6022  6022 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-22 07:44:24.327  6022  6022 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-22 07:44:24.327  6022  6022 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-22 07:44:24.327  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-22 07:44:24.328  6022  6022 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-22 07:44:24.328  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-22 07:44:24.328  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-22 07:44:24.328  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-22 07:44:24.328  6022  6022 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-22 07:44:24.328  6022  6022 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-22 07:44:24.328  6022  6022 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-22 07:44:24.330  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.335  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:24.341  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.346  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.347  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.347  6178  6178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-22 07:44:24.349  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,06-22 07:44:24.354  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:24.358  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.363  6195  6195 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,06-22 07:44:24.364  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.364  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.364  6178  6178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-22 07:44:24.367  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.371  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:24.377  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.384  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.385  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.385  6178  6178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,06-22 07:44:24.387  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.391  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:24.395  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.400  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.400  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.400  6178  6178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,06-22 07:44:24.403  6195  6195 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
06-22 07:44:24.403  6195  6195 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
06-22 07:44:24.403  6195  6195 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
06-22 07:44:24.403  6195  6195 D dhcpcd  : wlan0: adding default route via 192.168.1.1
06-22 07:44:24.403  6178  6178 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
06-22 07:44:24.403  6195  6195 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
06-22 07:44:24.403  6195  6195 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
06-22 07:44:24.404  6195  6195 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
06-22 07:44:24.404  6195  6195 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
06-22 07:44:24.405  1028  1532 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:24.405  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:24.406  1028  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:24.406  1028  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:24.407  1028  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:24.407  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
06-22 07:44:24.407  1028  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:44:24.407  1028  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-22 07:44:24.408  6178  6178 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
06-22 07:44:24.451  6178  6178 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:24.451  6178  6178 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-22 07:44:24.458  6178  6178 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
06-22 07:44:24.459  6178  6178 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
06-22 07:44:24.459  6178  6178 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
06-22 07:44:24.459  6178  6178 V SoundPool: doLoad: loading sample sampleID=1
06-22 07:44:24.459  6178  6178 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
06-22 07:44:24.463  5954  5954 D UEI.SmartControl: QS Service created
06-22 07:44:24.463  6178  6178 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
06-22 07:44:24.465  6178  6178 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-22 07:44:24.465  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
06-22 07:44:24.466  6178  6217 V SoundPool: Start decode
06-22 07:44:24.466  6178  6217 V MediaPlayer[Native]: decode(31, 10857164, 17813)
06-22 07:44:24.467   318  1381 V MediaPlayerService: decode(23, 10857164, 17813)
06-22 07:44:24.467   318  1381 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
06-22 07:44:24.467   318  1381 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
06-22 07:44:24.467   318  1381 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
06-22 07:44:24.467   318  1381 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
06-22 07:44:24.467   318  1381 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
06-22 07:44:24.467   318  1381 V MediaPlayerService: player type = 3
06-22 07:44:24.467   318  1381 V AwesomePlayer: AwesomePlayer create()
06-22 07:44:24.467   318  1381 V AwesomePlayer: reset_l() 
06-22 07:44:24.467   318  1381 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:24.467   318  1381 V AwesomePlayer: setAudioSink() 
06-22 07:44:24.467   318  1381 V AwesomePlayer: reset_l() 
06-22 07:44:24.467   318  1381 V AudioCache: notify(0xb10121c0, 8, 0, 0)
06-22 07:44:24.467   318  1381 V AudioCache: ignored
06-22 07:44:24.467   318  1381 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:24.467   318  1381 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
06-22 07:44:24.467   318  1381 V AwesomePlayer: setDataSource_l dataSource
06-22 07:44:24.467   318  1381 V LGParserOSAL: SniffLGParser start
06-22 07:44:24.467   318  1381 V LGParserOSAL: MainType:5, SubType=0
06-22 07:44:24.467   318  1381 V LGParserOSAL: #### check Mime : application/ogg
06-22 07:44:24.467   318  1381 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
06-22 07:44:24.467   318  1381 E MediaExtractor: Use LGExtractor :application/ogg 
06-22 07:44:24.470  5954  5954 I UEI.SmartControl: Service initServices...
06-22 07:44:24.470  5954  5954 D UEI.SmartControl: QS start get config
,06-22 07:44:24.500  6149  6150 E QC-QMI  : qmi_client [6149] 13: failed to locate client data
06-22 07:44:24.501   471   471 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
06-22 07:44:24.501   471   471 E QC-QMI  : QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,06-22 07:44:24.511   318  1381 V LGParserOSAL: supported mime: application/ogg
06-22 07:44:24.511   318  1381 V AwesomePlayer: setDataSource_l() extractor countTracks=1
06-22 07:44:24.511   318  1381 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
06-22 07:44:24.511   318  1381 V AwesomePlayer: mBitrate = -1 bits/sec
06-22 07:44:24.511   318  1381 V AwesomePlayer: AudioTrack Setting
06-22 07:44:24.511   318  1381 V AwesomePlayer: AudioTrack Setting channelCount = 2
06-22 07:44:24.511   318  1381 V AwesomePlayer: setAudioSource() 
06-22 07:44:24.511   318  1381 V MediaPlayerService: prepare
06-22 07:44:24.511   318  1381 V AwesomePlayer: prepareAsync_l() 
06-22 07:44:24.511   318  1381 V MediaPlayerService: wait for prepare
06-22 07:44:24.512   318  6224 V AwesomePlayer: onPrepareAsyncEvent() 
06-22 07:44:24.512   318  6224 V AwesomePlayer: initAudioDecoder() 
06-22 07:44:24.512   318  6224 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,06-22 07:44:24.512   318  6224 V AudioSystem: isOffloadSupported()
06-22 07:44:24.512   318  6224 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
06-22 07:44:24.512   318  6224 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-22 07:44:24.512   318  6224 I AudioFlinger: isAudioPlaybackHookOn() false
06-22 07:44:24.512   318  6224 V AwesomePlayer: getUseOffload() = 0 
06-22 07:44:24.512   318  6224 V OMXCodec: OMXCodec::Create
06-22 07:44:24.512   318  6224 V OMXCodec: findMatchingCodecs()
06-22 07:44:24.512   318  6224 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
06-22 07:44:24.513   318  6224 V OMXCodec: matchingCodecs.size()=1
06-22 07:44:24.513   318  6224 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
06-22 07:44:24.516   318  6224 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
06-22 07:44:24.516   318  6224 V LGCodecAdapter: LG Codec Adapter start
06-22 07:44:24.516   318  6224 V OMXCodec: OMXCodec Createtor
06-22 07:44:24.516   318  6224 V OMXCodec: setComponentRole
06-22 07:44:24.516   318  6224 V OMXCodec: configureCodec protected=0
06-22 07:44:24.516   318  6224 V LGCodecAdapter: called getLGCodecSpecificData
06-22 07:44:24.516   318  6224 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
06-22 07:44:24.516   318  6224 V LGCodecOSAL: Called LGconfigureCodecMETA
06-22 07:44:24.516   318  6224 V LGCodecOSAL: Called LGconfigureCodecMSG
06-22 07:44:24.516   318  6224 V LGCodecOSAL: Not support LGCodec
06-22 07:44:24.516   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
06-22 07:44:24.516   318  6224 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
06-22 07:44:24.516   318  6224 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
06-22 07:44:24.516   318  6224 I AwesomePlayer: Could not offload audio decode, try pcm offload
06-22 07:44:24.516   318  6224 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
06-22 07:44:24.516   318  6224 V AudioSystem: isOffloadSupported()
06-22 07:44:24.516   318  6224 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
06-22 07:44:24.516   318  6224 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-22 07:44:24.516   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
06-22 07:44:24.516   318  6224 V OMXCodec: init()
06-22 07:44:24.516   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
06-22 07:44:24.516   318  6224 V OMXCodec: allocateBuffers
06-22 07:44:24.516   318  6224 V OMXCodec: allocateBuffersOnPort portIndex=0
06-22 07:44:24.516   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
06-22 07:44:24.516   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
06-22 07:44:24.516   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
06-22 07:44:24.517   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
06-22 07:44:24.517   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
06-22 07:44:24.517   318  6224 V OMXCodec: allocateBuffersOnPort portIndex=1
06-22 07:44:24.517   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
06-22 07:44:24.517   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
06-22 07:44:24.517   318  6224 V OMXCodec: [OMX.google.vorbis.decod,er] allocated buffer 0xb040fab0 on output port
06-22 07:44:24.517   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
06-22 07:44:24.517   318  6224 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fe70 on output port
06-22 07:44:24.517   318  6224 V OMXCodec: init() mAsyncCompletion wait!!! 
06-22 07:44:24.517   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
06-22 07:44:24.517   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
06-22 07:44:24.518   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
06-22 07:44:24.518   318  6224 V OMXCodec: init() mAsyncCompletion wait!!! 
06-22 07:44:24.518   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
06-22 07:44:24.518   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
06-22 07:44:24.518   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
06-22 07:44:24.518   318  6224 V OMXCodec: init() mAsyncCompletion wait free! 
06-22 07:44:24.518   318  6224 V AwesomePlayer: finishAsyncPrepare_l() 
06-22 07:44:24.518   318  6224 V AudioCache: notify(0xb10121c0, 5, 0, 0)
06-22 07:44:24.518   318  6224 V AudioCache: ignored
06-22 07:44:24.518   318  6224 V AudioCache: notify(0xb10121c0, 1, 0, 0)
06-22 07:44:24.518   318  6224 V AudioCache: prepared
06-22 07:44:24.518   318  1381 V AudioCache: wait - success
06-22 07:44:24.518   318  1381 V MediaPlayerService: start
06-22 07:44:24.518   318  1381 V AwesomePlayer: play_l() 
06-22 07:44:24.518   318  1381 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
06-22 07:44:24.518   318  1381 V AwesomePlayer: createAudioPlayer_l
06-22 07:44:24.518   318  1381 V AwesomePlayer: seekAudioIfNecessary_l() 
06-22 07:44:24.518   318  1381 V AwesomePlayer: startAudioPlayer_l() 
06-22 07:44:24.518   318  1381 D AudioPlayer: start of Playback, useOffload 0
06-22 07:44:24.518   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
06-22 07:44:24.518   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:24.520   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
06-22 07:44:24.521   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:24.521  6178  6178 V LGMDMManager: Create singleton instance
,06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049456
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
06-22 07:44:24.523   318  6227 V OMXCodec: allocateBuffersOnPort portIndex=1
,06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb16dd100 on output port
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
06-22 07:44:24.523   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
06-22 07:44:24.525   318  1381 V AudioCache: open(48000, 2, 0x0, 1, 4)
06-22 07:44:24.525   318  1381 V AudioCache: notify(0xb10121c0, 6, 0, 0)
06-22 07:44:24.525   318  1381 V AudioCache: ignored
,06-22 07:44:24.526   318  1381 V MediaPlayerService: wait for playback complete
,06-22 07:44:24.526   318  6229 V AudioCache: write(0xb57c8000, 4096)
,06-22 07:44:24.526   318  6229 V AudioCache: memcpy(0xac006000, 0xb57c8000, 4096)
06-22 07:44:24.527   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.527   318  6229 V AudioCache: memcpy(0xac007000, 0xb57c8000, 4096)
06-22 07:44:24.527   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.527   318  6229 V AudioCache: memcpy(0xac008000, 0xb57c8000, 4096)
06-22 07:44:24.528   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.528   318  6229 V AudioCache: memcpy(0xac009000, 0xb57c8000, 4096)
06-22 07:44:24.528   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.528   318  6229 V AudioCache: memcpy(0xac00a000, 0xb57c8000, 4096)
,06-22 07:44:24.528   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.528   318  6229 V AudioCache: memcpy(0xac00b000, 0xb57c8000, 4096)
06-22 07:44:24.529   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.529   318  6229 V AudioCache: memcpy(0xac00c000, 0xb57c8000, 4096)
06-22 07:44:24.529   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.529   318  6229 V AudioCache: memcpy(0xac00d000, 0xb57c8000, 4096)
06-22 07:44:24.529   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.529   318  6229 V AudioCache: memcpy(0xac00e000, 0xb57c8000, 4096)
06-22 07:44:24.530   318  6229 V AudioCache: write(0xb57c8000, 4096)
,06-22 07:44:24.530   318  6229 V AudioCache: memcpy(0xac00f000, 0xb57c8000, 4096)
06-22 07:44:24.530   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.530   318  6229 V AudioCache: memcpy(0xac010000, 0xb57c8000, 4096)
06-22 07:44:24.531   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.531   318  6229 V AudioCache: memcpy(0xac011000, 0xb57c8000, 4096)
06-22 07:44:24.531   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.531   318  6229 V AudioCache: memcpy(0xac012000, 0xb57c8000, 4096)
06-22 07:44:24.532   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.532   318  6229 V AudioCache: memcpy(0xac013000, 0xb57c8000, 4096)
,06-22 07:44:24.532   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.532   318  6229 V AudioCache: memcpy(0xac014000, 0xb57c8000, 4096)
06-22 07:44:24.533   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.533   318  6229 V AudioCache: memcpy(0xac015000, 0xb57c8000, 4096)
06-22 07:44:24.533   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.533   318  6229 V AudioCache: memcpy(0xac016000, 0xb57c8000, 4096)
06-22 07:44:24.534   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.534   318  6229 V AudioCache: memcpy(0xac017000, 0xb57c8000, 4096)
06-22 07:44:24.534   318  6229 V AudioCache: write(0xb57c8000, 4096)
,06-22 07:44:24.534   318  6229 V AudioCache: memcpy(0xac018000, 0xb57c8000, 4096)
06-22 07:44:24.535   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.535   318  6229 V AudioCache: memcpy(0xac019000, 0xb57c8000, 4096)
06-22 07:44:24.535   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.535   318  6229 V AudioCache: memcpy(0xac01a000, 0xb57c8000, 4096)
06-22 07:44:24.536   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.536   318  6229 V AudioCache: memcpy(0xac01b000, 0xb57c8000, 4096)
06-22 07:44:24.536   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.536   318  6229 V AudioCache: memcpy(0xac01c000, 0xb57c8000, 4096)
06-22 07:44:24.537   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.537   318  6229 V AudioCache: memcpy(0xac01d000, 0xb57c8000, 4096)
06-22 07:44:24.537   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.537   318  6229 V AudioCache: memcpy(0xac01e000, 0xb57c8000, 4096)
,06-22 07:44:24.538   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.538   318  6229 V AudioCache: memcpy(0xac01f000, 0xb57c8000, 4096)
06-22 07:44:24.538   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.538   318  6229 V AudioCache: memcpy(0xac020000, 0xb57c8000, 4096)
06-22 07:44:24.539   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.539   318  6229 V AudioCache: memcpy(0xac021000, 0xb57c8000, 4096)
06-22 07:44:24.539   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.539   318  6229 V AudioCache: memcpy(0xac022000, 0xb57c8000, 4096)
06-22 07:44:24.540   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.540   318  6229 V AudioCache: memcpy(0xac023000, 0xb57c8000, 4096)
06-22 07:44:24.540   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.540   318  6229 V AudioCache: memcpy(0xac024000, 0xb57c8000, 4096)
06-22 07:44:24.541   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.541   318  6229 V AudioCache: memcpy(0xac025000, 0xb57c8000, 4096)
06-22 07:44:24.543   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.543   318  6229 V AudioCache: memcpy(0xac026000, 0xb57c8000, 4096)
06-22 07:44:24.543   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.543   318  6229 V AudioCache: memcpy(0xac027000, 0xb57c8000, 4096)
06-22 07:44:24.543   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.543   318  6229 V AudioCache: memcpy(0xac028000, 0xb57c8000, 4096)
06-22 07:44:24.544   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.544   318  6229 V AudioCache: memcpy(0xac029000, 0xb57c8000, 4096)
06-22 07:44:24.545   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.545   318  6229 V AudioCache: memcpy(0xac02a000, 0xb57c8000, 4096)
06-22 07:44:24.546   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.546   318  6229 V AudioCache: memcpy(0xac02b000, 0xb57c8000, 4096)
06-22 07:44:24.546   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.546   318  6229 V AudioCache: memcpy(0xac02c000, 0xb57c8000, 4096)
06-22 07:44:24.547   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.547   318  6229 V AudioCache: memcpy(0xac02d000, 0xb57c8000, 4096)
06-22 07:44:24.548   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.548   318  6229 V AudioCache: memcpy(0xac02e000, 0xb57c8000, 4096)
06-22 07:44:24.548   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.548   318  6229 V AudioCache: memcpy(0xac02f000, 0xb57c8000, 4096)
,06-22 07:44:24.552   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.552   318  6229 V AudioCache: memcpy(0xac030000, 0xb57c8000, 4096)
06-22 07:44:24.552   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.553   318  6229 V AudioCache: memcpy(0xac031000, 0xb57c8000, 4096)
06-22 07:44:24.553   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.553   318  6229 V AudioCache: memcpy(0xac032000, 0xb57c8000, 4096)
06-22 07:44:24.554   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.554   318  6229 V AudioCache: memcpy(0xac033000, 0xb57c8000, 4096)
06-22 07:44:24.555   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.555   318  6229 V AudioCache: memcpy(0xac034000, 0xb57c8000, 4096)
06-22 07:44:24.555   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.555   318  6229 V AudioCache: memcpy(0xac035000, 0xb57c8000, 4096)
06-22 07:44:24.555   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.555   318  6229 V AudioCache: memcpy(0xac036000, 0xb57c8000, 4096)
06-22 07:44:24.555   318  6229 V AudioCache: write(0xb57c8000, 4096)
06-22 07:44:24.555   318  6229 V AudioCache: memcpy(0xac037000, 0xb57c8000, 4096)
06-22 07:44:24.555   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
06-22 07:44:24.556   318  6229 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
06-22 07:44:24.556   318  6229 V AwesomePlayer: postAudioEOS() 
06-22 07:44:24.556   318  6229 V AudioCache: write(0xb57c8000, 280)
06-22 07:44:24.556   318  6229 V AudioCache: memcpy(0xac038000, 0xb57c8000, 280)
06-22 07:44:24.557   318  6224 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
06-22 07:44:24.557   318  6224 V AwesomePlayer: onStreamDone
06-22 07:44:24.557   318  6224 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
06-22 07:44:24.557   318  6224 V AudioCache: notify(0xb10121c0, 2, 0, 0)
06-22 07:44:24.557   318  6224 V AudioCache: playback complete
06-22 07:44:24.557   318  6224 V AwesomePlayer: pause_l() 
06-22 07:44:24.557   318  6224 V AudioCache: notify(0xb10121c0, 7, 0, 0)
06-22 07:44:24.557   318  6224 V AudioCache: ignored
06-22 07:44:24.557   318  6224 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:24.557   318  1381 V AudioCache: wait - success
06-22 07:44:24.557   318  1381 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
06-22 07:44:24.557   318  6224 D AudioPlayer: Pause Playback at 1068125
06-22 07:44:24.558   318  1381 V AwesomePlayer: reset_l() 
06-22 07:44:24.558   318  1381 V AudioCache: notify(0xb10121c0, 8, 0, 0)
06-22 07:44:24.558   318  1381 V AudioCache: ignored
06-22 07:44:24.558   318  1381 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:24.558   318  1381 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
06-22 07:44:24.558   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
06-22 07:44:24.558   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
06-22 07:44:24.558   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
06-22 07:44:24.558   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
06-22 07:44:24.560   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
06-22 07:44:24.560   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb16dd100 on port 1
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:24.564   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
06-22 07:44:24.565   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
06-22 07:44:24.565   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
06-22 07:44:24.565   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
06-22 07:44:24.565   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
06-22 07:44:24.565   318  6227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
06-22 07:44:24.565   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
06-22 07:44:24.565   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
06-22 07:44:24.566   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
06-22 07:44:24.566   318  1381 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
06-22 07:44:24.566   318  1381 D AudioPlayer: AudioPlayer releasing audio source
06-22 07:44:24.567   318  1381 D AudioPlayer: AudioPlayer done releasing audio source
06-22 07:44:24.567   318  1381 V AwesomePlayer: reset_l() 
06-22 07:44:24.567   318  1381 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:24.567   318  1381 V AwesomePlayer: ~AwesomePlayer call
06-22 07:44:24.567   318  1381 V AwesomePlayer: reset_l() 
06-22 07:44:24.567   318  1381 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:24.567  6178  6217 V SoundPool: close(31)
06-22 07:44:24.567  6178  6217 V SoundPool: pointer = 0x9fe6d000, size = 205080, sampleRate = 48000, numChannels = 2
06-22 07:44:24.580  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
06-22 07:44:24.580  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,06-22 07:44:24.584  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6690
,06-22 07:44:24.584  6233  6233 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
06-22 07:44:24.592  6234  6234 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,06-22 07:44:24.608  1028  6174 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,06-22 07:44:24.610  1028  6174 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
06-22 07:44:24.610  1028  6174 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-22 07:44:24.610  1028  6174 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
06-22 07:44:24.610  1028  6174 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
06-22 07:44:24.610  1028  6174 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-22 07:44:24.610  1028  6174 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
06-22 07:44:24.610  1028  6174 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
06-22 07:44:24.611  1028  1532 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
06-22 07:44:24.611  1028  6174 D DhcpStateMachine: RunningState
06-22 07:44:24.611  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
06-22 07:44:24.611  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
06-22 07:44:24.612  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
06-22 07:44:24.611  1028  1531 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:24.612  1028  1531 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:24.612  1028  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
06-22 07:44:24.612  1028  1532 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
06-22 07:44:24.612  6021  6021 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
06-22 07:44:24.613  1028  1532 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
06-22 07:44:24.613  1028  1532 D WifiNative-wlan0: doBoolean: SET ps 1
06-22 07:44:24.620  5996  6045 I bt_vendor: bluetooth satus is on
06-22 07:44:24.620  5996  6045 D bt_hci_bdroid: preload
06-22 07:44:24.620  5996  6113 D bt_userial_mct: userial_open(port:0)
06-22 07:44:24.620  5996  6113 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
06-22 07:44:24.621  5996  6113 I bt_vendor: Done intiailizing UART
06-22 07:44:24.621  5996  6113 I bt_vendor: Done intiailizing UART
06-22 07:44:24.621  5996  6113 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
06-22 07:44:24.621  5996  6113 I bt_vendor: Bluetooth Firmware and transport layer are initialized
06-22 07:44:24.621  5996  6236 D bt_userial_mct: Entering userial_read_thread()
06-22 07:44:24.621  5996  6111 I bt-btu  : btu_task received preload complete event
,06-22 07:44:24.621  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
06-22 07:44:24.621  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
06-22 07:44:24.622  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_HCI
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_L2CAP
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_RFCOMM
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_AVDT
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_AVRC
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_A2D
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_BNEP
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_BTM
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_HID_HOST
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_GAP
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_PAN
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_SDP
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_GATT
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_SMP
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_BTAPP
06-22 07:44:24.624  5996  6111 I         : BTE_InitTraceLevels -- TRC_BTIF
06-22 07:44:24.643  1028  1532 D WifiNative-wlan0: SET ps 1: returned true
,06-22 07:44:24.643  1028  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-22 07:44:24.644  1028  1532 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
06-22 07:44:24.645  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
06-22 07:44:24.645  1028  1532 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
06-22 07:44:24.645  5996  6111 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
06-22 07:44:24.645  5996  6111 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0179061 
06-22 07:44:24.645  5996  6111 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0179061 
06-22 07:44:24.645  1028  1539 D ConnectivityService: ignoring duplicate network state non-change
06-22 07:44:24.649  5996  6049 E bt-btif : Calling BTA_HhEnable
06-22 07:44:24.649  5996  6049 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
06-22 07:44:24.649  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
06-22 07:44:24.649  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
06-22 07:44:24.649  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
06-22 07:44:24.649  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
06-22 07:44:24.649  5996  6049 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
06-22 07:44:24.649  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
06-22 07:44:24.650  5996  6049 D BluetoothAdapterProperties: Name is: G3
06-22 07:44:24.651  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:24.651  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:24.651  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-22 07:44:24.651  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
06-22 07:44:24.651  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
06-22 07:44:24.651  5996  6049 D BluetoothAdapterProperties: Scan Mode:20
06-22 07:44:24.651  5996  6049 D BluetoothAdapterProperties: Discoverable Timeout:120
06-22 07:44:24.652  5996  6049 D bt_hci_bdroid: postload
06-22 07:44:24.652  5996  6113 D bt_hci_bdroid: Used up Tx Cmd credits
06-22 07:44:24.652  5996  6111 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
06-22 07:44:24.655  5996  6111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-22 07:44:24.655  5996  6111 W bt-smp  : Plain text(LSB ~ MSB) = 2b e5 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-22 07:44:24.655  5996  6111 W bt-smp  : Encrypted text(LSB ~ MSB) = ed a6 a2 38 7a 20 15 65 24 7d bb 86 7e f4 d7 70 
06-22 07:44:24.655  5996  6111 W bt-btm  : Stopping oneshot timer
06-22 07:44:24.656  5996  6113 D bt_hci_bdroid: Used up Tx Cmd credits
06-22 07:44:24.656  5996  6113 D bt_hci_bdroid: Used up Tx Cmd credits
06-22 07:44:24.656  5996  6113 D bt_hci_bdroid: Used up Tx Cmd credits
06-22 07:44:24.656  5778  5778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-22 07:44:24.656  5996  6113 D bt_hci_bdroid: Used up Tx Cmd credits
06-22 07:44:24.656  5996  6236 E bt_mct  : hci lib postload completed
06-22 07:44:24.656  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:24.656  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:24.657  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast actio,n 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.659  1028  1539 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
06-22 07:44:24.659  5996  6049 D bte_conf: Device ID record 1 : primary
06-22 07:44:24.659  5996  6049 D bte_conf:   vendorId            = 00c4
06-22 07:44:24.659  5996  6049 D bte_conf:   vendorIdSource      = 0001
06-22 07:44:24.659  5996  6049 D bte_conf:   product             = 13a1
06-22 07:44:24.659  5996  6049 D bte_conf:   version             = 1000
06-22 07:44:24.659  5996  6049 D bte_conf:   clientExecutableURL = 
,06-22 07:44:24.659  5996  6049 D bte_conf:   serviceDescription  = 
06-22 07:44:24.659  5996  6049 D bte_conf:   documentationURL    = 
06-22 07:44:24.659  5996  6049 D bte_conf: bte_load_did_conf no section named DID2.
06-22 07:44:24.659  1028  1539 D ConnectivityService: Adding iface wlan0 to network 100
06-22 07:44:24.661  6239  6239 W sh      : type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:24.661  6239  6239 W sh      : type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:24.664  5996  6049 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-22 07:44:24.665  5996  6045 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-22 07:44:24.665  5996  6045 D BluetoothAdapterProperties: ScanMode =  20
06-22 07:44:24.665  5996  6045 D BluetoothAdapterProperties: State =  11
06-22 07:44:24.665  5996  6045 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
06-22 07:44:24.665  5996  6045 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
06-22 07:44:24.665  5996  6045 D BluetoothAdapterProperties: Setting state to 12
06-22 07:44:24.665  5996  6045 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-22 07:44:24.666  1028  1090 D BluetoothManagerService: Message: 60
06-22 07:44:24.666  1028  1090 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-22 07:44:24.666  1028  1090 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 5 receivers.
06-22 07:44:24.666  1028  1090 D BluetoothA2dp: onBluetoothStateChange: up=true
06-22 07:44:24.666  1028  1090 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:44:24.666  5996  6045 I BluetoothAdapterState: Entering On State
06-22 07:44:24.667  5996  6049 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
06-22 07:44:24.668  5996  6111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-22 07:44:24.668  5996  6111 W bt-smp  : Plain text(LSB ~ MSB) = 23 26 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-22 07:44:24.668  5996  6111 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 18 4b ca 14 f9 5f 61 85 6a 3b ba 3c fc 3c 0f 
06-22 07:44:24.668  5996  6111 W bt-btm  : Stopping oneshot timer
06-22 07:44:24.671  1846  1861 D BluetoothHeadset: onBluetoothStateChange: up=true
,06-22 07:44:24.673  1846  3468 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:44:24.675  1846  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:44:24.680  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:24.680  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:24.680  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-22 07:44:24.682  1028  1090 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
06-22 07:44:24.682  1028  1090 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
06-22 07:44:24.683  5996  6045 D LGBluetoothServiceAdapter: [BTUI] OnState
06-22 07:44:24.683  5996  6045 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
06-22 07:44:24.683  5996  6045 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
06-22 07:44:24.683  1935  1935 V WfdStateTracker: handleWifiStateChangedEvent: 1
06-22 07:44:24.684  5996  6045 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,06-22 07:44:24.686  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:24.687  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-22 07:44:24.687  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:24.687  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:24.687  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-22 07:44:24.689  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
06-22 07:44:24.690  1028  1090 D BluetoothManagerService: Message: 40
06-22 07:44:24.690  1028  1090 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
06-22 07:44:24.691  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-22 07:44:24.693  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:24.693  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:24.694  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-22 07:44:24.695  1935  1935 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:24.695  1935  2114 D LGBluetoothAPIService: Message: 1
06-22 07:44:24.695  1935  2114 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
06-22 07:44:24.697  6246  6246 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
06-22 07:44:24.697  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-22 07:44:24.698  1596  1596 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:24.699  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:24.700  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:24.700  5996  6111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-22 07:44:24.700  5996  6111 W bt-smp  : Plain text(LSB ~ MSB) = 14 c7 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-22 07:44:24.700  5996  6111 W bt-smp  : Encrypted text(LSB ~ MSB) = d2 ab 99 6b 55 a2 7a f4 4a 44 b7 17 b6 59 fb 11 
06-22 07:44:24.700  5996  6111 W bt-btm  : Stopping oneshot timer
,06-22 07:44:24.705  1596  1596 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-22 07:44:24.705  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:24.706  5996  5996 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:24.706  5996  5996 D BluetoothMapService: STATE_ON
06-22 07:44:24.706  1028  1532 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
06-22 07:44:24.707  5996  5996 D LGBluetoothAPIServer: [BTUI] onCreate()
06-22 07:44:24.707  5996  5996 D LGBluetoothAPIServer: [BTUI] onBind()
06-22 07:44:24.708  1935  2114 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
06-22 07:44:24.708  5996  6111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-22 07:44:24.708  5996  6111 W bt-smp  : Plain text(LSB ~ MSB) = 8b 08 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-22 07:44:24.708  5996  6111 W bt-smp  : Encrypted text(LSB ~ MSB) = 9c 55 d1 bb 3b 87 eb 98 07 79 8b 7c 18 ed 69 cc 
06-22 07:44:24.708  5996  6111 W bt-btm  : Stopping oneshot timer
06-22 07:44:24.709  1935  1935 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
06-22 07:44:24.710  1935  2114 D LGBluetoothAPIService: Message: 100
06-22 07:44:24.710  1935  2114 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
06-22 07:44:24.715  5996  6111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-22 07:44:24.715  5996  6111 W bt-smp  : Plain text(LSB ~ MSB) = 35 3d 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-22 07:44:24.715  5996  6111 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 3e 1e 5a 0b 01 b2 13 77 2a 74 07 33 9d 05 2c 
06-22 07:44:24.715  5996  6111 W bt-btm  : Stopping oneshot timer
,06-22 07:44:24.717  5996  6045 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
06-22 07:44:24.719  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:24.719  5996  5996 V BluetoothPbapService: Pbap Service onCreate
06-22 07:44:24.719  5996  5996 V BluetoothPbapService: Starting PBAP service
06-22 07:44:24.720  5996  5996 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-22 07:44:24.720  5996  5996 V BluetoothMapService: Handler(): got msg=1
06-22 07:44:24.720  5996  5996 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
06-22 07:44:24.721  5996  5996 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:24.721  5996  5996 V BluetoothPbapService: state: 12
06-22 07:44:24.721  5996  5996 V BluetoothPbapService: Handler(): got msg=1
06-22 07:44:24.721  5996  5996 V BluetoothPbapService: Pbap Service startRfcommSocketListener
06-22 07:44:24.722  5996  6247 D BluetoothMapMasInstance: MAS initSocket()
06-22 07:44:24.722  5996  6247 D BluetoothMapMasInstance:   masId = 00
06-22 07:44:24.722  5996  6247 D BluetoothMapMasInstance:   msgTypes = 0e
06-22 07:44:24.722  5996  6247 D BluetoothMapMasInstance:   masName = SMS/MMS
06-22 07:44:24.722  5996  6247 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
06-22 07:44:24.722  5996  6248 V BluetoothPbapService: Pbap Service initSocket
06-22 07:44:24.723  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:24.724  5996  6248 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:44:24.725  1028  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:24.725  5996  6248 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
06-22 07:44:24.725  5996  6248 V BluetoothPbapService: Succeed to create listening socket 
06-22 07:44:24.725  5996  6248 V BluetoothPbapService: Accepting socket connection...
,06-22 07:44:24.725  5996  6247 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:44:24.726  6022  6022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-22 07:44:24.726  5996  6247 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
06-22 07:44:24.726  5996  6247 V BluetoothMapMasInstance: Succeed to create listening socket 
06-22 07:44:24.726  5996  6247 D BluetoothMapMasInstance: Accepting socket connection...
06-22 07:44:24.727  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:24.728  5996  5996 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-22 07:44:24.728  5996  5996 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:24.728  5996  5996 V BluetoothPbapReceiver: ***********state = 12
06-22 07:44:24.731  2202  2202 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-22 07:44:24.731  2202  2202 D c       : Getting all permits...
06-22 07:44:24.731  2202  2202 D a       : Opening database...
06-22 07:44:24.733  2202  2202 D a       : Opening database auth.proximity.permit_store...
06-22 07:44:24.734  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.734  2202  2202 D a       : Closing database...
06-22 07:44:24.740  1596  1596 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:24.740  1596  1596 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-22 07:44:24.741  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:24.742  1596  1596 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,06-22 07:44:24.791  6022  6022 D LocalBluetoothProfileManager: Adding local A2DP profile
,06-22 07:44:24.794  1028  1090 D BluetoothManagerService: Message: 30
06-22 07:44:24.796  1028  1539 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-22 07:44:24.797  1028  1539 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
06-22 07:44:24.797  6022  6022 D LocalBluetoothProfileManager: Adding local HEADSET profile
06-22 07:44:24.798  1028  1539 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
06-22 07:44:24.799  1028  1539 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
06-22 07:44:24.799  1028  1539 D ConnectivityService: addLocalRoutetoDefaultNetwork
06-22 07:44:24.799  1028  1539 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
06-22 07:44:24.799  1028  1539 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
06-22 07:44:24.803  1028  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-22 07:44:24.803  1028  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:24.803  1028  1539 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:24.803  1028  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-22 07:44:24.803  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:24.803  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
06-22 07:44:24.803  1028  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:24.804  1028  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:24.804  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,06-22 07:44:24.805  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-22 07:44:24.807  1028  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-22 07:44:24.808  1028  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.808  1028  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
06-22 07:44:24.808  1028  1539 D ConnectivityService: currentScore = 0, newScore = 20
06-22 07:44:24.808  1028  1539 D ConnectivityService:    accepting network in place of null
06-22 07:44:24.808  1028  1539 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.809   313  6250 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
06-22 07:44:24.809  1028  1532 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.809  1028  1532 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:24.809  1846  1846 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.809  1028  1539 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
06-22 07:44:24.809  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,06-22 07:44:24.812  1028  1090 D BluetoothManagerService: Message: 30
06-22 07:44:24.813  1028  1539 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
06-22 07:44:24.813  1028  1539 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
06-22 07:44:24.814  1028  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-22 07:44:24.814  1028  1539 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:24.815  1028  1539 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
06-22 07:44:24.815   313  6251 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:24.815   313  6251 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
06-22 07:44:24.815   313  6251 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
06-22 07:44:24.816  1028  1539 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
06-22 07:44:24.816  1028  1028 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
06-22 07:44:24.816  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-22 07:44:24.816  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-22 07:44:24.816  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-22 07:44:24.816  1028  1028 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
06-22 07:44:24.817  1028  1090 D BluetoothManagerService: Message: 30
06-22 07:44:24.817  1028  1088 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-22 07:44:24.819  1028  1539 D ConnectivityService: validation of new default Network = false
06-22 07:44:24.819  1028  1539 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
06-22 07:44:24.819  1028  1539 D DSQN    : enableDataServiceNotify 
06-22 07:44:24.819  1028  1539 D DSQN    : start dsqn bin
06-22 07:44:24.824   313  6253 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:24.824   313  6253 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
06-22 07:44:24.821  6254  6254 W dsqn    : type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:24.821  6254  6254 W dsqn    : type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:24.825  1028  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:24.825  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.825  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:24.825  1028  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:24.826  1596  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-22 07:44:24.829  1028  1090 D BluetoothManagerService: Message: 30
06-22 07:44:24.830  1028  1530 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,06-22 07:44:24.835  6022  6022 D LocalBluetoothProfileManager: Adding local MAP profile
06-22 07:44:24.836  6022  6022 D BluetoothMap: Create BluetoothMap proxy object
06-22 07:44:24.837  1028  1090 D BluetoothManagerService: Message: 30
06-22 07:44:24.837  6254  6254 E DSQN    : DSQN ssw
06-22 07:44:24.838  5996  6049 D BluetoothAdapterProperties: Discoverable Timeout:120
06-22 07:44:24.838  5996  6049 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
06-22 07:44:24.839  5996  6049 D BluetoothAdapterProperties: Scan Mode:21
06-22 07:44:24.839  5996  6049 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
06-22 07:44:24.840  1028  1090 D BluetoothManagerService: Message: 30
06-22 07:44:24.841  5778  5778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-22 07:44:24.841  6022  6022 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-22 07:44:24.842  5996  5996 V BluetoothPbapService: Pbap Service onBind
06-22 07:44:24.843  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-22 07:44:24.845  5778  5778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-22 07:44:24.845  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:24.845  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-22 07:44:24.845  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-22 07:44:24.845  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-22 07:44:24.845  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-22 07:44:24.845  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-22 07:44:24.845  5778  5778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-22 07:44:24.846  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:24.846  5778  5778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-22 07:44:24.846  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:24.847  6022  6022 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,06-22 07:44:24.849  6022  6022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
06-22 07:44:24.853  6022  6022 D DockEventReceiver: finishStartingService: stopping service
06-22 07:44:24.857  6022  6022 D BluetoothA2dp: Proxy object connected
06-22 07:44:24.857  6022  6022 D A2dpProfile: Bluetooth service connected
06-22 07:44:24.860  6022  6022 D BluetoothHeadset: Proxy object connected
06-22 07:44:24.860  6022  6022 D HeadsetProfile: Bluetooth service connected
06-22 07:44:24.861   313  6253 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
06-22 07:44:24.862  6022  6022 D BluetoothInputDevice: Proxy object connected
06-22 07:44:24.862  6022  6022 D HidProfile: Bluetooth service connected
06-22 07:44:24.863  6022  6022 D BluetoothPan: BluetoothPAN Proxy object connected
06-22 07:44:24.864  6022  6022 D PanProfile: Bluetooth service connected
06-22 07:44:24.865   313  6250 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
06-22 07:44:24.865  6022  6022 D BluetoothMap: Proxy object connected
06-22 07:44:24.866  6022  6022 D MapProfile: Bluetooth service connected
06-22 07:44:24.866  6022  6022 D BluetoothMap: getConnectedDevices()
06-22 07:44:24.866  5996  6011 V BluetoothMapService: getConnectedDevices()
06-22 07:44:24.867  6022  6022 D BluetoothPbap: Proxy object connected
06-22 07:44:24.867  6022  6022 D PbapServerProfile: Bluetooth service connected
06-22 07:44:24.867  6022  6022 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-22 07:44:24.868  6022  6022 D BluetoothPermissionRequest: onReceive
06-22 07:44:24.870  6022  6022 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,06-22 07:44:24.871  6022  6022 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-22 07:44:24.872  5996  5996 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,06-22 07:44:24.873  6022  6022 D LGBluetoothResetSettingReceiver: return without doing reset settings.
06-22 07:44:24.875  5996  5996 I LGBluetoothOppAdapter: [BTUI] startOppService()
06-22 07:44:24.875  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.875  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.879  6178  6178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-22 07:44:24.880  5996  5996 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
06-22 07:44:24.883  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.888  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:24.890  5996  5996 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-22 07:44:24.890  5996  5996 V BtOppService: onCreate
06-22 07:44:24.891  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.892  5996  5996 V BluetoothOppNotification: send message
06-22 07:44:24.895  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.896  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,06-22 07:44:24.896  6178  6178 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-22 07:44:24.896  1028  6252 D LocSvc_java: NTP server : europe.pool.ntp.org
06-22 07:44:24.897  1028  6252 D LocSvc_java: NTP server returned: 1466574264904 (Wed Jun 22 07:44:24 GMT+02:00 2016) reference: 119261 certainty: 17 system time offset: 8
06-22 07:44:24.897  1028  6252 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
06-22 07:44:24.897  5996  5996 V BtOppService: Starting RfcommListener
06-22 07:44:24.901   313  6250 D libc-netbsd: res_queryN name = clients3.google.com succeed
06-22 07:44:24.902  5996  6265 V BtOppService: Deleted complete outbound shares, number =  0
06-22 07:44:24.903   327   412 I ThermalEngine: Thermal-Server: Thermal received msg from  override
06-22 07:44:24.903  3149  6268 I Thermal-Lib: Thermal-Lib-Client: Client request sent
06-22 07:44:24.903  5996  6265 V BtOppService: Deleted complete inbound failed shares, number = 0
06-22 07:44:24.904  5996  6265 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
06-22 07:44:24.904  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.905  5996  6265 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@332ab797 on behalf of 
06-22 07:44:24.905  5996  5996 D BluetoothOppPreference: Dumping Names:  
06-22 07:44:24.905  5996  5996 D BluetoothOppPreference: {}
06-22 07:44:24.905  5996  5996 D BluetoothOppPreference: Dumping Channels:  
06-22 07:44:24.905  5996  5996 D BluetoothOppPreference: {}
,06-22 07:44:24.907  5996  5996 V BtOppService: onStartCommand
06-22 07:44:24.907  5996  6269 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
06-22 07:44:24.908   313   887 D LGDataListener: argv[0]=dsqncommand
06-22 07:44:24.908   313   887 D LGDataListener: argv[1]=wlan0
06-22 07:44:24.908   313   887 D LGDataListener: argv[2]=1
06-22 07:44:24.908   313   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
06-22 07:44:24.908  1028  1088 D DSQN    : DSQM DsqnNotification wlan0  1
06-22 07:44:24.908  1028  1088 D DSQN    : start to monitor internet connection
06-22 07:44:24.908  5996  6269 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-22 07:44:24.909  5996  5996 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:24.909  5996  6269 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e60396d on behalf of 
06-22 07:44:24.909  5996  5996 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
06-22 07:44:24.911  5996  5996 V BluetoothOppNotification: new notify threadi!
06-22 07:44:24.913  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 22 Jun 2016 05:44:24 GMT], X-Android-Received-Millis=[1466574264913], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1466574264907]}
06-22 07:44:24.913  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-22 07:44:24.914  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
06-22 07:44:24.914  1028  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-22 07:44:24.914  1028  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-22 07:44:24.914  1028  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:24.914  1028  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:24.914  1028  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-22 07:44:24.914  1028  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-22 07:44:24.914  1028  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:24.914  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.914  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:24.914  1028  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:24.915  1028  1539 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.915  1596  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-22 07:44:24.915  1028  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-22 07:44:24.915  1028  1532 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.915  1028  1532 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:24.915  6081  6081 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
06-22 07:44:24.916  1846  1846 D TelephonyNetworkFactory-1: new s,core 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:24.916  1846  1846 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
06-22 07:44:24.916  5996  5996 V BluetoothOppNotification: send delay message
06-22 07:44:24.917  5996  5996 V BtOppService: start RfcommListener
06-22 07:44:24.918  5996  6272 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,06-22 07:44:24.921  5996  5996 V BtOppService: RfcommListener started
06-22 07:44:24.921  5996  5996 V BtOppService: ContentObserver received notification
06-22 07:44:24.921  5996  5996 V BtOppService: ContentObserver received notification
06-22 07:44:24.921  5996  6273 V BtOppRfcommListener: Starting RFCOMM listener....
06-22 07:44:24.922  6081  6081 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:24.923  5996  6269 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
06-22 07:44:24.923  5996  6269 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-22 07:44:24.923  5996  6272 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17c5d9a2 on behalf of 
06-22 07:44:24.924  5996  6272 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-22 07:44:24.924  5996  6272 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-22 07:44:24.925  5996  6269 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cd93633 on behalf of 
06-22 07:44:24.928  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:24.928  1028  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:24.929  5996  6273 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:44:24.930  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:24.930  5996  6273 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
06-22 07:44:24.930  5996  5996 V BluetoothFtpService: Ftp Service onCreate
06-22 07:44:24.930  5996  5996 I BluetoothFtpService: Ftp Service onCreate
06-22 07:44:24.930  5996  6273 V BtOppRfcommListener: Started RFCOMM listener....
06-22 07:44:24.930  5996  6273 I BtOppRfcommListener: Accept thread started.
06-22 07:44:24.930  5996  6273 V BtOppRfcommListener: Accepting connection...
06-22 07:44:24.930  5996  5996 V BluetoothFtpService: Ftp Service onStartCommand
06-22 07:44:24.930  5996  5996 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:24.930  5996  5996 V BluetoothFtpService: Starting Listening on sockets
06-22 07:44:24.930  5996  6269 V BluetoothOppNotification: update too frequent, put in queue
06-22 07:44:24.931  5996  5996 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-22 07:44:24.931  5996  5996 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-22 07:44:24.931  5996  5996 V BluetoothSapReceiver: SapReceiver onReceive 
06-22 07:44:24.931  5996  5996 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:24.931  5996  5996 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
06-22 07:44:24.931  5996  5996 V BluetoothSapReceiver: Calling SAP service start service with action = null
06-22 07:44:24.931  5996  6272 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5d3ff69 on behalf of 
06-22 07:44:24.932  5996  6272 V BluetoothOppNotification: outbound: succ-0  fail-0
06-22 07:44:24.932  5996  5996 V BluetoothFtpService: Handler(): got msg=1
06-22 07:44:24.933  5996  5996 V BluetoothFtpService: Ftp Service startRfcommSocketListener
06-22 07:44:24.933  5996  5996 V BluetoothFtpService: Ftp Service initSocket
06-22 07:44:24.935  1028  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:24.941  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.941  5996  6269 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true,
06-22 07:44:24.942  5996  5996 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-22 07:44:24.943  5996  5996 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
06-22 07:44:24.943  5996  5996 V BluetoothFtpService: Succeed to create listening socket on channel 20
06-22 07:44:24.944  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.945  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.945  6178  6178 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
06-22 07:44:24.945  5996  6274 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
06-22 07:44:24.946  5996  6272 V BluetoothOppNotification: outbound notification was removed.
06-22 07:44:24.946  6178  6178 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
06-22 07:44:24.946  5996  6272 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-22 07:44:24.946  6178  6178 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
06-22 07:44:24.949  1596  1596 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-22 07:44:24.950  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:24.950  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:24.951  5996  5996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369b843a
06-22 07:44:24.951  5996  5996 V BluetoothSapService: Sap Service onCreate
06-22 07:44:24.952  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-22 07:44:24.952  5996  5996 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:24.952  5996  5996 V BluetoothSapService: state: 12
06-22 07:44:24.952  5996  5996 V BluetoothSapService: Starting SAP server process
06-22 07:44:24.953  5996  6272 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fa42925 on behalf of 
06-22 07:44:24.953  5996  5996 V BluetoothSapService: SAP Service startRfcommListenerThread
06-22 07:44:24.953  5996  6272 V BluetoothOppNotification: inbound: succ-0  fail-0
06-22 07:44:24.954  5996  6276 V BluetoothSapService: Sap Service initRfcommSocket
06-22 07:44:24.951  6275  6275 W sapd    : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:24.954  1028  1724 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:24.955  6081  6081 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
06-22 07:44:24.951  6275  6275 W sapd    : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-22 07:44:24.955  5996  6276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:44:24.956  6081  6081 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:24.956  5996  6276 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
06-22 07:44:24.956  5996  6276 V BluetoothSapService: Succeed to create listening socket 
06-22 07:44:24.957  5996  6276 V BluetoothSapService: Accepting socket connection...
,06-22 07:44:24.957  6022  6022 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:24.961  6022  6022 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:24.962  6275  6275 V BT_SAP  : Event pipe created
06-22 07:44:24.962  6275  6275 V BT_SAP  : create_server_socket qcom.sap.server
06-22 07:44:24.962  6275  6275 V BT_SAP  : created socket fd 6
06-22 07:44:24.963  5996  6272 V BluetoothOppNotification: inbound notification was removed.
06-22 07:44:24.963  5996  6272 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-22 07:44:24.965  5996  6272 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@150cfafa on behalf of 
06-22 07:44:24.965  6178  6178 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-22 07:44:24.965  6178  6178 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-22 07:44:24.966  6178  6178 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
06-22 07:44:24.966  6178  6178 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
06-22 07:44:24.966  6178  6178 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,06-22 07:44:24.972  5954  5954 I UEI.SmartControl: Supports setup maps: true
,06-22 07:44:24.974  5954  5954 D UEI.SmartControl: QS start statue = true Error code = 0
06-22 07:44:24.974  5954  5954 I UEI.SmartControl: QS version = v2.7.10.1_RC1
06-22 07:44:24.974  5954  5954 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-22 07:44:24.974  5954  5954 I UEI.SmartControl: ### init IR Blaster...
06-22 07:44:24.977  5954  5954 D serial_port: Configuring serial port
06-22 07:44:24.977  5954  5954 E UEI.SmartControl: UEIBLaster setting for 616
06-22 07:44:24.977  5954  5954 I UEI.SmartControl: Setting serial record hearder size = 2
06-22 07:44:24.977  5954  5954 I UEI.SmartControl: configuring settings for MAXQ616
06-22 07:44:24.977  5954  5954 I UEI.SmartControl: Get version...
06-22 07:44:24.993  5954  6277 D UEI.SmartControl: serial port data available: 21
,06-22 07:44:25.018  5954  5954 D UEI.SmartControl: MAXQ616 A2-X4 software.
06-22 07:44:25.018  5954  5954 I UEI.SmartControl: IR Blaster version: 256702256704300002
06-22 07:44:25.018  5954  5954 I UEI.SmartControl: QS saving settings...
06-22 07:44:25.019  5954  5954 D UEI.SmartControl: IR Blaster version: 25672567
,06-22 07:44:25.034  5954  6277 D UEI.SmartControl: serial port data available: 4
,06-22 07:44:25.060  5954  6280 I UEI.SmartControl: Device manager: loading config....
06-22 07:44:25.061  5954  5954 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,06-22 07:44:25.062  5954  6280 D UEI.SmartControl: ----------- loading internal config...
,06-22 07:44:25.062  5954  5954 E UEI.SmartControl: Services init done
06-22 07:44:25.062  5954  5954 D UEI.SmartControl: QS Service init finished
06-22 07:44:25.062  5954  5954 D UEI.SmartControl: QS Service version name: 2.1.91
06-22 07:44:25.062  5954  5954 D UEI.SmartControl: QS Service version code: 201091
06-22 07:44:25.062  5954  5954 D UEI.SmartControl: Service requested: Control
06-22 07:44:25.064  5954  6280 E UEI.SmartControl: Loading SETTINGS...
06-22 07:44:25.066  5954  6280 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
06-22 07:44:25.067  5954  5954 D UEI.SmartControl: Request IControl service: devices are loaded...
06-22 07:44:25.068  5954  5954 D UEI.SmartControl: Internal service binding...
06-22 07:44:25.069  6178  6178 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
06-22 07:44:25.069  5954  5969 I UEI.SmartControl: ------ IControl API: 11
06-22 07:44:25.069  5954  5969 D UEI.SmartControl: File observer start...
06-22 07:44:25.069  5954  5969 E UEI.SmartControl: IR Port is disabled: false
06-22 07:44:25.069  5954  5969 D UEI.SmartControl: Starting file observer...
06-22 07:44:25.070  5954  5969 I UEI.SmartControl: Registering callback...
06-22 07:44:25.070  5954  5970 I UEI.SmartControl: ------ IControl API: 19
06-22 07:44:25.071  5954  5970 I UEI.SmartControl: Registering Services Ready callback...
06-22 07:44:25.071  5954  5970 I UEI.SmartControl: Notify client services are ready...
06-22 07:44:25.071  6178  6193 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
06-22 07:44:25.072  6178  6214 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
06-22 07:44:25.072  6178  6214 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
06-22 07:44:25.072  6178  6178 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
06-22 07:44:25.072  6178  6178 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
06-22 07:44:25.073  5954  5969 I UEI.SmartControl: ------ IControl API: 8
,06-22 07:44:25.074  6178  6178 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,06-22 07:44:25.074  6178  6178 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
06-22 07:44:25.074  6178  6178 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
06-22 07:44:25.074  6178  6178 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
06-22 07:44:25.075  6178  6178 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
06-22 07:44:25.075  6178  6178 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
06-22 07:44:25.075  6178  6178 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
06-22 07:44:25.077  6178  6178 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
06-22 07:44:25.077  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
06-22 07:44:25.078  6178  6178 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-22 07:44:25.078  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
06-22 07:44:25.078  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
06-22 07:44:25.079  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
06-22 07:44:25.079  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
06-22 07:44:25.080  6178  6178 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1466574265079]
06-22 07:44:25.080  5954  6279 I UEI.SmartControl: Notify AllClients services are ready: 0
06-22 07:44:25.080  6178  6178 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
06-22 07:44:25.080  6178  6194 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
06-22 07:44:25.081  5954  6279 D UEI.SmartControl: -----service ready thread exits
06-22 07:44:25.081  6178  6214 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
06-22 07:44:25.081  6178  6214 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
06-22 07:44:25.081  6178  6178 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
06-22 07:44:25.082  1028  1724 I ActivityManager: Killing 5654:com.android.gallery3d/u0a27 (adj 15): empty #17
06-22 07:44:25.091  6178  6282 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,06-22 07:44:25.093  1028  1532 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:44:25.094  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:44:25.094  1028  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:44:25.094  1028  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:44:25.094  1028  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:44:25.094  1028  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:44:25.095  1028  1539 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
06-22 07:44:25.095  1028  1539 D ConnectivityService: identical MTU - not setting
06-22 07:44:25.095  1028  1539 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-22 07:44:25.095  1028  1539 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:25.095  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:25.095  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:25.095  1028  1539 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:25.096  1596  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-22 07:44:25.173  1028  1989 W libprocessgroup: failed to open /acct/uid_10027/pid_5654/cgroup.procs: No such file or directory
,06-22 07:44:25.176  6178  6178 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
06-22 07:44:25.177  6178  6178 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-22 07:44:25.177  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
06-22 07:44:25.177  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
06-22 07:44:25.177  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
06-22 07:44:25.177  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
06-22 07:44:25.178  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
06-22 07:44:25.182  6178  6178 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
06-22 07:44:25.832  1028  1374 V AlarmManager: RTC_WAKEUP set : Alarm{132e3b1b type 0 when 1466574263379 com.android.vending} when 1466574263379
,06-22 07:44:25.890  1028  1989 V SIM_STK : Menu title from STK is T-Mobile
,06-22 07:44:25.923  5996  5996 V BluetoothOppNotification: new notify threadi!
06-22 07:44:25.923  5996  5996 V BluetoothOppNotification: send delay message
06-22 07:44:25.924  5996  6293 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,06-22 07:44:25.933  5996  6293 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25b38ab on behalf of 
06-22 07:44:25.933  5996  6293 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-22 07:44:25.935  5996  6293 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-22 07:44:25.936  5996  6293 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b5d6b08 on behalf of 
06-22 07:44:25.937  5996  6293 V BluetoothOppNotification: outbound: succ-0  fail-0
,06-22 07:44:25.939  5996  6293 V BluetoothOppNotification: outbound notification was removed.
06-22 07:44:25.939  5996  6293 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-22 07:44:25.941  5996  6293 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d9332a1 on behalf of 
06-22 07:44:25.941  5996  6293 V BluetoothOppNotification: inbound: succ-0  fail-0
06-22 07:44:25.944  5996  6293 V BluetoothOppNotification: inbound notification was removed.
06-22 07:44:25.944  5996  6293 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-22 07:44:25.945  5996  6293 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a9fccc6 on behalf of 
06-22 07:44:26.004  5677  5677 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,06-22 07:44:26.377   327   412 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,06-22 07:44:26.385  3149  6300 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,06-22 07:44:26.976  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990419040] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:44:26.979  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990419043] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:44:26.979  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:44:26.996  1596  1596 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-22 07:44:27.025  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-22 07:44:27.025  5778  5864 I jxcore-log: 
,06-22 07:44:27.410  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-22 07:44:27.410  5778  5864 I jxcore-log: 
,06-22 07:44:27.437  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-22 07:44:27.437  5778  5864 I jxcore-log: 
,06-22 07:44:27.442  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-22 07:44:27.442  5778  5864 I jxcore-log: 
06-22 07:44:27.458  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-22 07:44:27.458  5778  5864 I jxcore-log: 
06-22 07:44:27.461  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-22 07:44:27.461  5778  5864 I jxcore-log: 
,06-22 07:44:27.690  1028  1533 V WifiInternetCheck: Single check msg out of sync, ignoring.
,06-22 07:44:27.818  1028  1539 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-22 07:44:27.827  1028  1090 D Tethering: MasterInitialState.processMessage what=3
06-22 07:44:27.839   313  6301 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:27.840   313  6301 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,06-22 07:44:27.849  5778  5778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-22 07:44:27.850  1028  1085 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:27.851  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
06-22 07:44:27.857  5177  5177 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-22 07:44:27.885   313  6301 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
,06-22 07:44:27.904  1028  1822 D AlarmManagerService: Setting time of day to sec=1466574267
06-22 07:44:27.910  1028  1822 W AlarmManagerService: Unable to set rtc to 1466574267: Invalid argument
,06-22 07:44:27.934  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:44:27.935  5075  5102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
06-22 07:44:27.936  1935  1935 I SecureClockService: Intent.ACTION_TIME_CHANGED 
06-22 07:44:27.936  1596  1596 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
06-22 07:44:27.938  2729  2729 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
06-22 07:44:27.939  2729  2729 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-06-22 07:44:27...... Request
06-22 07:44:27.939  2729  2729 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 2, new day : false...... Request
06-22 07:44:27.939  2729  2729 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 2
06-22 07:44:27.939  2729  2729 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 2
06-22 07:44:27.939  2729  2729 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-06-22 07:44:27
06-22 07:44:27.942  1596  1596 I LgeClockWidgetControlView: time changed, timezoneChanged : false
06-22 07:44:27.944  1028  1880 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
06-22 07:44:27.947  1811  6307 I CheckinService: active receiver: enabled
06-22 07:44:27.948  2028  2028 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=22 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,06-22 07:44:27.951  2028  2028 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 22
06-22 07:44:27.951  2202  2202 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:27.955  1811  6307 I CheckinService: Preparing to send checkin request
06-22 07:44:27.955  2028  2028 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 22
06-22 07:44:27.955  1811  6307 I EventLogService: Accumulating logs since 1466573634287
06-22 07:44:27.956  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-22 07:44:27.961   313  6318 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:27.961   313  6318 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,06-22 07:44:27.962  1028  1970 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
06-22 07:44:27.963  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.963  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.963  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-22 07:44:27.963  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.963  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-22 07:44:27.976  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 22 Jun 2016 05:44:27 GMT], X-Android-Received-Millis=[1466574267975], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1466574267963]}
06-22 07:44:27.976  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-22 07:44:27.976  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
06-22 07:44:27.976  1028  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-22 07:44:27.976  1028  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-22 07:44:27.976  1028  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:27.976  1028  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:27.976  1028  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-22 07:44:27.976  1028  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-22 07:44:27.977  1028  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:27.977  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:27.977  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:27.977  1028  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:27.978  1596  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-22 07:44:27.987  1028  1043 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6319 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-22 07:44:27.996  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,06-22 07:44:28.031   313  6318 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,06-22 07:44:28.043  1028  1085 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:28.050  1811  6307 W EventLogAggregator: Unknown tag: snet_gcore
06-22 07:44:28.050  1811  6307 W EventLogAggregator: Unknown tag: snet_launch_service
,06-22 07:44:28.094  1028  1970 I art     : Explicit concurrent mark sweep GC freed 80553(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.395ms total 71.359ms
,06-22 07:44:28.104  1028  1085 E GpsLocationProvider: No APN found to select.
06-22 07:44:28.108  1811  6307 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-22 07:44:28.116  1028  1538 D WifiService: New client listening to asynchronous messages
06-22 07:44:28.120  6319  6319 I AppUp4:AppBoxCP: onCreate
,06-22 07:44:28.120  6319  6319 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-22 07:44:28.125  6319  6319 I AppUp4:DB:  setFingerPrint start
06-22 07:44:28.125  6319  6319 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
06-22 07:44:28.130  6319  6319 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
06-22 07:44:28.130  6319  6319 I AppUp4:DB:  SDK version = 21
06-22 07:44:28.130  6319  6319 I AppUp4:DB:  beforefinger == newfinger no write in DB
,06-22 07:44:28.132  6319  6319 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-22 07:44:28.132  6319  6319 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,06-22 07:44:28.132  6319  6319 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:28.134  6319  6319 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
06-22 07:44:28.134  6319  6319 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
06-22 07:44:28.137  2202  6317 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-22 07:44:28.139  6319  6319 I AppUp4:CustModeStarterReceiver: onReceive
06-22 07:44:28.160  6319  6319 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:28.160  6319  6319 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-22 07:44:28.165  6319  6319 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@41e0f65
06-22 07:44:28.165  6319  6319 D AppUp4:CustFacade: isCustomizationCompleted : false
06-22 07:44:28.165  6319  6319 D AppUp4:CustFacade: isPhone : true
06-22 07:44:28.165  6319  6319 D AppUp4:CustModeStarterReceiver: begin check event
06-22 07:44:28.166  6319  6319 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-22 07:44:28.166  6319  6319 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
06-22 07:44:28.238  6319  6341 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,06-22 07:44:28.239  6319  6341 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-22 07:44:28.239  6319  6341 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
06-22 07:44:28.243  1028  1724 I ActivityManager: Killing 2128:com.lge.music/u0a34 (adj 15): empty #17
06-22 07:44:28.259   318  2158 V AudioFlinger: 2128 died, releasing its sessions
06-22 07:44:28.259   318  2158 V AudioFlinger:  pid 1846 @ 0
06-22 07:44:28.259   318  2158 V AudioFlinger:  pid 3389 @ 1
06-22 07:44:28.260   318  2158 V AudioFlinger:  pid 3389 @ 2
,06-22 07:44:28.411  1028  2026 W libprocessgroup: failed to open /acct/uid_10034/pid_2128/cgroup.procs: No such file or directory
,06-22 07:44:28.415  3224  3224 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:28.416  3224  3224 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-22 07:44:28.420  3224  3224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-22 07:44:28.467  1028  1043 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6350 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,06-22 07:44:28.471  3224  3224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-22 07:44:28.477  2812  2812 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:28.480  2812  2812 V DownloadManager: DownloadService onCreate
,06-22 07:44:28.482  3224  6363 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-22 07:44:28.482  2812  6364 I DownloadManager: in removeSpuriousFiles
06-22 07:44:28.483  2812  6364 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
06-22 07:44:28.483  2812  6364 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e8978cb on behalf of 2812
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
06-22 07:44:28.484  2812  6364 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
06-22 07:44:28.485  2812  6364 I DownloadManager: in trimDatabase
06-22 07:44:28.485  2812  6364 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
06-22 07:44:28.486  2812  6364 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2b5878a8 on behalf of 2812
06-22 07:44:28.488  3224  6367 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:28.488  3224  6367 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-22 07:44:28.503  3224  6363 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,06-22 07:44:28.510  1028  1880 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6373 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-22 07:44:28.523  2812  2812 V DownloadManager: DownloadService onStartCommand
,06-22 07:44:28.533  6350  6350 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-22 07:44:28.533  6350  6350 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-22 07:44:28.534  2812  6365 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
06-22 07:44:28.543  3224  6363 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
06-22 07:44:28.544  2812  6365 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f34d6a7 on behalf of 2812
,06-22 07:44:28.547  3224  3224 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
06-22 07:44:28.550  2812  6365 V DownloadManager: processing inserted download 1
06-22 07:44:28.551  2812  6365 V DownloadManager: processing inserted download 4
06-22 07:44:28.552  2812  6365 V DownloadManager: processing inserted download 7
06-22 07:44:28.553  2812  6365 V DownloadManager: processing inserted download 8
06-22 07:44:28.554  2812  6365 V DownloadManager: processing inserted download 9
06-22 07:44:28.555  2812  6365 V DownloadManager: processing inserted download 10
,06-22 07:44:28.556  2812  6365 V DownloadManager: processing inserted download 11
06-22 07:44:28.557  2812  6365 V DownloadManager: processing inserted download 12
,06-22 07:44:28.558  2812  6365 V DownloadManager: processing inserted download 13
06-22 07:44:28.560  3224  3224 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
06-22 07:44:28.560  2812  6365 V DownloadManager: processing inserted download 14
,06-22 07:44:28.560  3224  3224 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
06-22 07:44:28.563  3224  3224 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
06-22 07:44:28.565  6350  6350 I MultiDex: VM with version 2.1.0 has multidex support
06-22 07:44:28.565  6350  6350 I MultiDex: install
06-22 07:44:28.565  6350  6350 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-22 07:44:28.567  3224  3224 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,06-22 07:44:28.571  6373  6373 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:28.571  6373  6373 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:44:28.572  6373  6373 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-22 07:44:28.572  6373  6373 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-22 07:44:28.575  2812  2812 V DownloadManager: DownloadService onDestroy
06-22 07:44:28.577  6350  6350 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
06-22 07:44:28.632  6373  6373 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,06-22 07:44:28.639  6350  6372 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
06-22 07:44:28.649  6373  6373 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,06-22 07:44:28.653   313  6399 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:28.654   313  6399 D libc-netbsd: res_queryN name = www.googleapis.com, class = 1, type = 1
,06-22 07:44:28.679  6373  6373 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-22 07:44:28.699   313  6399 D libc-netbsd: res_queryN name = www.googleapis.com succeed
,06-22 07:44:28.711  6373  6373 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:28.711  6373  6373 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-22 07:44:28.817  6373  6373 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,06-22 07:44:28.847  3389  3389 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,06-22 07:44:28.847  3389  3389 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:28.853  6373  6373 I HubEmail: JNI_OnLoad()
06-22 07:44:28.853  6373  6373 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-22 07:44:28.853  6373  6373 I HubEmail: registerNatives()
06-22 07:44:28.853  6373  6373 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-22 07:44:28.853  6373  6373 I HubEmail: registerNativeMethods()
06-22 07:44:28.853  6373  6373 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-22 07:44:28.853  6373  6373 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
06-22 07:44:28.856  3389  3389 I LgeMiscReceiver: networkInfo.isConnected() = true
06-22 07:44:28.857  3389  3389 D PhoneState: setPdpRejectCasuse : false
06-22 07:44:28.892  1028  1916 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6409 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,06-22 07:44:28.897  6373  6408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:44:28.905   313  6424 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:28.905   313  6424 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,06-22 07:44:28.945   313  6424 D libc-netbsd: res_queryN name = www.google.com succeed
,06-22 07:44:28.949   313  6428 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:28.949   313  6428 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
06-22 07:44:28.949   313  6428 D libc-netbsd: res_queryN name = clients3.google.com succeed
06-22 07:44:28.967  6409  6409 D LgDataFeature: LgDataFeature() Constructor: none
,06-22 07:44:28.968  6409  6409 D LgDataFeature: LgDataFeature() Constructor Done, null
06-22 07:44:28.973  6409  6409 D PhoneMonitor: Register our PhoneStateListener
06-22 07:44:28.974  1028  1534 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
06-22 07:44:28.974   313  6430 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:28.974   313  6430 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
06-22 07:44:28.980  6409  6409 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,06-22 07:44:28.981  6409  6409 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
06-22 07:44:28.988  6409  6409 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
06-22 07:44:28.989  6409  6409 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
06-22 07:44:28.989  6409  6409 D TelephonyAutoProfiling: [parse] Load xml
06-22 07:44:28.990  6409  6409 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
06-22 07:44:28.990  6409  6409 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
06-22 07:44:28.990  6409  6409 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
06-22 07:44:28.994  6409  6409 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
06-22 07:44:29.012  1028  1917 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6433 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:29.013  1028  1917 I ActivityManager: Killing 5720:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,06-22 07:44:29.031   313  6430 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,06-22 07:44:29.131  6058  6407 V FormManager: There are no updated forms. The schedule will be deleted.
,06-22 07:44:29.140  6058  6407 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
06-22 07:44:29.146  1028  1989 W libprocessgroup: failed to open /acct/uid_10061/pid_5720/cgroup.procs: No such file or directory
,06-22 07:44:29.194  1811  1811 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
06-22 07:44:29.196  2202  2202 I ConfigService: onCreate
06-22 07:44:29.196  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,06-22 07:44:29.198  1811  6451 I ConfigFetchService: running network task: configservice_periodic
06-22 07:44:29.202  2202  2202 I ConfigService: onBind returning update interface
06-22 07:44:29.204  1811  1811 I ConfigFetchService: service connected
06-22 07:44:29.205  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-22 07:44:29.205  2202  2202 I ConfigService: onBind returning config service
06-22 07:44:29.205  1811  6451 I ConfigFetchService: launchTask
06-22 07:44:29.206  1811  1811 I ConfigClient: service connected
06-22 07:44:29.209  1028  2026 I ActivityManager: Killing 5846:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,06-22 07:44:29.339  1028  1880 W libprocessgroup: failed to open /acct/uid_10080/pid_5846/cgroup.procs: No such file or directory
,06-22 07:44:29.409  1028  1043 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6454 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
06-22 07:44:29.409  1028  1043 I ActivityManager: Killing 5494:com.android.defcontainer/u0a4 (adj 15): empty #17
,06-22 07:44:29.441  1811  6452 I art     : Explicit concurrent mark sweep GC freed 13921(905KB) AllocSpace objects, 7(112KB) LOS objects, 51% free, 29MB/61MB, paused 1.193ms total 64.895ms
,06-22 07:44:29.446  1028  1044 V SIM_STK : Menu title from STK is T-Mobile
06-22 07:44:29.469  6350  6372 D LgDataFeature: LgDataFeature() Constructor: none
,06-22 07:44:29.469  6350  6372 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-22 07:44:29.509  1028  1952 W libprocessgroup: failed to open /acct/uid_10004/pid_5494/cgroup.procs: No such file or directory
,06-22 07:44:29.513  1811  6452 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
06-22 07:44:29.520   313  6472 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:29.521   313  6472 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-22 07:44:29.554  6454  6454 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
06-22 07:44:29.556  6454  6454 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,06-22 07:44:29.561  6454  6454 V DrmService: Service onCreate
,06-22 07:44:29.561  6454  6454 D DrmService: Received new request = 2
06-22 07:44:29.566   313  6472 D libc-netbsd: res_queryN name = android.clients.google.com succeed
06-22 07:44:29.566  6454  6473 I DrmSntpClient: Start Sync process
06-22 07:44:29.566  6454  6473 D DrmSntpClient: Server : 0
06-22 07:44:29.570   313  6474 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:29.571   313  6474 D libc-netbsd: res_queryN name = pool.ntp.org, class = 1, type = 1
06-22 07:44:29.597  1028  2027 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6475 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:29.608   344   344 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 258us total 13.295ms
,06-22 07:44:29.610   313  6474 D libc-netbsd: res_queryN name = pool.ntp.org succeed
06-22 07:44:29.621   344   344 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 223us total 12.817ms
06-22 07:44:29.623  6454  6473 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
06-22 07:44:29.623   323   899 V ILGDrmService: eDRM_SetDRMTime +++
06-22 07:44:29.623   323   899 I LGDRM   : [DRM] SET TIME : YR=2016, MON=6, DAY=22
06-22 07:44:29.623   323   899 I LGDRM   : [DRM] SET TIME : HR=5, MIN=44, SEC=28
,06-22 07:44:29.629   323   899 V ILGDrmService: eDRM_SetDRMTime ---
06-22 07:44:29.633   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 225us total 10.901ms
06-22 07:44:29.634  6454  6473 I DrmSntpClient: Synched
06-22 07:44:29.636  6454  6454 D DrmService: Completed !! request = 2
06-22 07:44:29.636  6454  6454 D DrmService: Request count = 0
06-22 07:44:29.637  6454  6454 V DrmService: Service onDestroy
06-22 07:44:29.637  1028  1044 I ActivityManager: Killing 5865:com.google.android.apps.plus/u0a97 (adj 15): empty #17
06-22 07:44:29.697  6492  6492 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-22 07:44:29.719  1028  1989 W libprocessgroup: failed to open /acct/uid_10097/pid_5865/cgroup.procs: No such file or directory
,06-22 07:44:29.734  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-22 07:44:29.734  5778  5864 I jxcore-log: 
,06-22 07:44:29.745  6492  6492 I dex2oat : dex2oat took 47.491ms (threads: 4)
06-22 07:44:29.746  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-22 07:44:29.746  5778  5864 I jxcore-log: 
06-22 07:44:29.746  6475  6475 I art     : Almond Protected OAT
06-22 07:44:29.753  6350  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:29.753  6350  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:29.753  6350  6372 I Adreno-EGL: Build Date: 12/12/14 금
06-22 07:44:29.753  6350  6372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-22 07:44:29.753  6350  6372 I Adreno-EGL: Remote Branch: 
06-22 07:44:29.753  6350  6372 I Adreno-EGL: Local Patches: 
06-22 07:44:29.753  6350  6372 I Adreno-EGL: Reconstruct Branch: 
06-22 07:44:29.754  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-22 07:44:29.754  5778  5864 I jxcore-log: 
,06-22 07:44:29.792  6475  6475 D WeatherApplication: removeAccount
,06-22 07:44:29.793  6475  6475 D WeatherApplication: Account.length = 0
06-22 07:44:29.793  6475  6475 E WeatherApplication: OPERATOR:OPEN
06-22 07:44:29.796  6475  6475 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:44:29
06-22 07:44:29.803  6475  6475 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-22 07:44:29.803  6475  6475 D Weather.Utils: 2 : All the weather widget is gone.
,06-22 07:44:29.805  6475  6475 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-22 07:44:29.807  6475  6475 D WeatherAncestor: connectivity changed - connection : true
06-22 07:44:29.807  6475  6475 D WeatherService: 2 : isServiceAlived():false forecastCache:null
06-22 07:44:29.814  6475  6475 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
06-22 07:44:29.814  6475  6475 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
06-22 07:44:29.815  6475  6475 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,06-22 07:44:29.832  6475  6475 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-22 07:44:29.832  6475  6475 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:44:29
,06-22 07:44:29.861  6350  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:29.861  6350  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:29.861  6350  6372 I Adreno-EGL: Build Date: 12/12/14 금
06-22 07:44:29.861  6350  6372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-22 07:44:29.861  6350  6372 I Adreno-EGL: Remote Branch: 
06-22 07:44:29.861  6350  6372 I Adreno-EGL: Local Patches: 
06-22 07:44:29.861  6350  6372 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:29.870  1028  1916 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6500 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:29.872  1028  1916 I ActivityManager: Killing 5902:com.lge.eula/1000 (adj 15): empty #17
06-22 07:44:29.902  6350  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:29.902  6350  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:29.902  6350  6372 I Adreno-EGL: Build Date: 12/12/14 금
06-22 07:44:29.902  6350  6372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-22 07:44:29.902  6350  6372 I Adreno-EGL: Remote Branch: 
06-22 07:44:29.902  6350  6372 I Adreno-EGL: Local Patches: 
06-22 07:44:29.902  6350  6372 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:29.918  1811  6452 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-22 07:44:29.924  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-22 07:44:29.924  5778  5864 I jxcore-log: 
06-22 07:44:30.004  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-22 07:44:30.004  5778  5864 I jxcore-log: 
,06-22 07:44:30.010  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3011] from screen [on:0 period:1990422074] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:44:30.011  1028  1970 W libprocessgroup: failed to open /acct/uid_1000/pid_5902/cgroup.procs: No such file or directory
06-22 07:44:30.013  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990422077] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-22 07:44:30.013  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:44:30.024  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
06-22 07:44:30.026  1811  1811 I ConfigFetchService: stopping self
06-22 07:44:30.063  2202  2202 I ConfigService: onDestroy
,06-22 07:44:30.068  5954  6281 D UEI.SmartControl: Internal timer expired: 2
,06-22 07:44:30.068  5954  6281 D UEI.SmartControl: unbind internal service
06-22 07:44:30.114  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-22 07:44:30.114  5778  5864 I jxcore-log: 
,06-22 07:44:30.122  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-22 07:44:30.122  5778  5864 I jxcore-log: 
06-22 07:44:30.123   279   415 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:30.123   279   415 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-22 07:44:30.123   279   415 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:30.124  6500  6518 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
06-22 07:44:30.125   279   415 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,06-22 07:44:30.125   279   415 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-22 07:44:30.125   279   415 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:30.125  6500  6518 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-22 07:44:30.142   279   415 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:30.142   279   415 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-22 07:44:30.142   279   415 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:30.143  6500  6520 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
06-22 07:44:30.148   279   415 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:30.148   279   415 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-22 07:44:30.149   279   415 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:30.149  6500  6520 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-22 07:44:30.190  5954  6278 D serial_port: close(fd = 24)
,06-22 07:44:30.193  5954  6278 I UEI.SmartControl: Serial port is closed.
06-22 07:44:30.196  1811  6307 I CheckinTask: Sending checkin request (7664 bytes)
06-22 07:44:30.325  1811  6307 I CheckinResponseProcessor: From server: 5 gservices updates and 0 deletes
,06-22 07:44:30.329  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-22 07:44:30.329  5778  5864 I jxcore-log: 
06-22 07:44:30.353  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-22 07:44:30.353  5778  5864 I jxcore-log: 
,06-22 07:44:30.357  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-22 07:44:30.357  5778  5864 I jxcore-log: 
06-22 07:44:30.362  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-22 07:44:30.362  5778  5864 I jxcore-log: 
06-22 07:44:30.376  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-22 07:44:30.376  5778  5864 I jxcore-log: 
,06-22 07:44:30.395  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-22 07:44:30.395  5778  5864 I jxcore-log: 
,06-22 07:44:30.406  6500  6500 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,06-22 07:44:30.418  6500  6500 I LibraryLoader: Loading: webviewchromium
,06-22 07:44:30.421  6500  6500 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4789-4792)
06-22 07:44:30.421  6500  6500 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:30.429  6500  6500 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37c17d24}
06-22 07:44:30.433  6500  6500 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:30.434  6500  6500 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,06-22 07:44:30.448  6500  6500 I BrowserStartupController: Initializing chromium process, renderers=0
06-22 07:44:30.449  6500  6500 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:44:30.459   318  1381 V AudioPolicyService: registerClient() client 0xb0410380, uid 10093
,06-22 07:44:30.459  6500  6500 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
06-22 07:44:30.460  6500  6542 W AudioManagerAndroid: Requires BLUETOOTH permission
06-22 07:44:30.460  6500  6500 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,06-22 07:44:30.460  6500  6500 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
06-22 07:44:30.472  6500  6500 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:30.472  6500  6500 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:30.472  6500  6500 I Adreno-EGL: Build Date: 12/12/14 금
06-22 07:44:30.472  6500  6500 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-22 07:44:30.472  6500  6500 I Adreno-EGL: Remote Branch: 
06-22 07:44:30.472  6500  6500 I Adreno-EGL: Local Patches: 
06-22 07:44:30.472  6500  6500 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:30.483  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-22 07:44:30.483  5778  5864 I jxcore-log: 
,06-22 07:44:30.488  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-22 07:44:30.488  5778  5864 I jxcore-log: 
,06-22 07:44:30.515  5778  5864 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-22 07:44:30.515  5778  5864 I jxcore-log: 
06-22 07:44:30.522  1028  6550 I CertBlacklister: Certificate blacklist changed, updating...
,06-22 07:44:30.524  5778  5864 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
06-22 07:44:30.525  5778  5864 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-22 07:44:30.525  5778  5864 I jxcore-log: 
06-22 07:44:30.527  1028  6550 I CertBlacklister: Certificate blacklist updated
06-22 07:44:30.541  2202  2333 I GservicesProvider: main difference update completed
,06-22 07:44:30.558  6500  6500 I NSApplication: Starting up...
06-22 07:44:30.575  5778  5864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-22 07:44:30.575  5778  5864 I jxcore-log: 
,06-22 07:44:30.576  5778  5864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-22 07:44:30.576  5778  5864 I jxcore-log: 
06-22 07:44:30.612  1028  1971 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6556 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:30.613  1028  1971 I ActivityManager: Killing 5920:com.lge.bnr/1000 (adj 15): empty #17
06-22 07:44:30.661  1028  1780 W libprocessgroup: failed to open /acct/uid_1000/pid_5920/cgroup.procs: No such file or directory
,06-22 07:44:30.698  6556  6556 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:44:30.729  1811  6307 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-22 07:44:30.755  1811  6307 I CheckinService: active receiver: disabled
,06-22 07:44:30.781  1811  6573 I CheckinService: active receiver: disabled
06-22 07:44:30.984  5075  5075 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,06-22 07:44:31.018  1811  6582 I CheckinService: active receiver: disabled
06-22 07:44:31.081  1028  1970 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6587 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-22 07:44:31.204  6587  6605 D ALBootInit: ====action==>android.intent.action.TIME_SET
,06-22 07:44:31.208  6587  6605 D ALBootInit: Alarm ALBootInit: TIME_SET
06-22 07:44:31.211  6587  6605 D Alarms  : [setNextAlert] start
,06-22 07:44:31.240  1028  1971 I art     : Explicit concurrent mark sweep GC freed 21472(1130KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.589ms total 137.207ms
,06-22 07:44:31.246  6587  6605 D Alarms  : [setNextAlert] (1)
06-22 07:44:31.250  6587  6605 D Alarms  :  minTime  = 0
06-22 07:44:31.252  6587  6605 D Alarms  :  -- OK multi -- 0
06-22 07:44:31.253  6587  6605 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
06-22 07:44:31.253  6587  6605 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
06-22 07:44:31.271  6587  6605 I CommonUtil: BUILD Country: EU
,06-22 07:44:31.275  6587  6605 D Alarms  : broadcastToWidgetProvider : false
06-22 07:44:31.283  6587  6605 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
,06-22 07:44:31.291  1028  1043 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
06-22 07:44:31.295  6587  6587 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
,06-22 07:44:31.296  6587  6587 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@369b843a
06-22 07:44:31.298  6587  6587 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@369b843a
06-22 07:44:31.302  6587  6587 D QuickCoverProvider: onReceiver
06-22 07:44:31.311  1552  1552 I indal   : SmartCoverWidgetContext createApplicationContext
06-22 07:44:31.311  1552  1552 I indal   : SmartCoverWidgetContext createApplicationContext
,06-22 07:44:31.322  6475  6475 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 7:44:31
,06-22 07:44:31.324  6475  6475 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-22 07:44:31.324  6475  6475 D Weather.Utils: 2 : All the weather widget is gone.
06-22 07:44:31.325  6475  6475 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-22 07:44:31.327  6475  6475 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@215d28eb
06-22 07:44:31.327  6475  6475 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
06-22 07:44:31.327  6475  6475 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
06-22 07:44:31.328  6475  6475 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
06-22 07:44:31.330  6475  6475 D Weather_cast: 2 : set auto-update time : 6/22 10:44
06-22 07:44:31.334  6475  6475 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 7:44:31
,06-22 07:44:31.411  1028  2026 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6613 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-22 07:44:31.414  1028  2026 I ActivityManager: Killing 6156:com.lge.settings.easy/1000 (adj 15): empty #17
,06-22 07:44:31.469  1028  1880 W libprocessgroup: failed to open /acct/uid_1000/pid_6156/cgroup.procs: No such file or directory
,06-22 07:44:31.527  6613  6613 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1466574271527
06-22 07:44:31.528  6613  6613 D         : TimeServiceNative: User Time to be set is 1466574271527
,06-22 07:44:31.528  6613  6613 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
06-22 07:44:31.528  6613  6613 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
06-22 07:44:31.528  6613  6613 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1466574271527
06-22 07:44:31.529   390  1027 D QC-time-services: Daemon: Connection accepted:time_genoff
06-22 07:44:31.529  6613  6613 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
06-22 07:44:31.529   390  6630 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1466574271527
06-22 07:44:31.529   390  6630 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1466574271527, operation = 0
06-22 07:44:31.530   390  6630 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/2/70 0:12:30
06-22 07:44:31.530   390  6630 D QC-time-services: Daemon:Value read from RTC seconds = 87150000
06-22 07:44:31.530   390  6630 D QC-time-services: Daemon:new time 1466574271527 
06-22 07:44:31.530   390  6630 D QC-time-services: Daemon: delta 1466487121527 genoff 1466487121527 
06-22 07:44:31.531   390  6630 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487121527 to memory
06-22 07:44:31.531   390  6630 D QC-time-services: Daemon:Opening File: /data/time/ats_2
06-22 07:44:31.531   390  6630 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
06-22 07:44:31.547   390  6630 D QC-time-services: Updating the TOD offset
06-22 07:44:31.547   390  6630 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487121527 to memory
06-22 07:44:31.547   390  6630 D QC-time-services: Daemon:Opening File: /data/time/ats_1
06-22 07:44:31.547   390  6630 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-22 07:44:31.552   390  6630 E QC-time-services: Daemon:Update to modem bit set
06-22 07:44:31.552   390  6630 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
06-22 07:44:31.552   390  6630 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522321527
06-22 07:44:31.552  6613  6613 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
06-22 07:44:31.555   390  1025 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
06-22 07:44:31.555   390  1027 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
06-22 07:44:31.619  1028  1780 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6634 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
06-22 07:44:31.620  1028  1780 I ActivityManager: Killing 6081:com.lge.sync/1000 (adj 15): empty #17
,06-22 07:44:31.692  1028  2026 W libprocessgroup: failed to open /acct/uid_1000/pid_6081/cgroup.procs: No such file or directory
,06-22 07:44:31.762  6634  6634 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,06-22 07:44:31.771  6634  6634 V [BNRBootReceiver]: Boot Receiver Return
06-22 07:44:31.772  6634  6634 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-22 07:44:31.814  1028  2027 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6652 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,06-22 07:44:31.819  1028  2027 I ActivityManager: Killing 6022:com.android.settings/1000 (adj 15): empty #17
06-22 07:44:31.843  1028  1538 D WifiService: Client connection lost with reason: 4
,06-22 07:44:31.859  1028  2026 W libprocessgroup: failed to open /acct/uid_1000/pid_6022/cgroup.procs: No such file or directory
,06-22 07:44:31.899  6652  6652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:44:31.929  6652  6652 D CalendarApplication: CalendarApplication.onCreate()
,06-22 07:44:31.939  6652  6652 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
06-22 07:44:31.940  6652  6652 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@15f001a9, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2968632e, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@133e6ecf, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3a72705c, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@41e0f65, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@369b843a, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@215d28eb, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@27e43648, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@8653ce1, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@22adaa06, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@346368c7, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@292a6ef4, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3997c61d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1b6a6092, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@18a3ca63, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@10f98660, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@f6fa719, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2dc9f3de, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2fea9bf, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@26e0a88c, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@294a9bd5, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2bfd6fea, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2bfe22db, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3a35c178, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@4a62051, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@283aa0b6, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@b211b7, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@37c17d24, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1f5b708d, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@10481242, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@54c1253, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2e2b4790, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@19b8889, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@35c9108e, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@57b80af, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2d254cbc, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2bab2445, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@f49a79a, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2e8978cb, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2b5878a8, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Prefe,renceKey$KeyData@235ebfc1, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3e0aa366,
06-22 07:44:31.944  6652  6652 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,06-22 07:44:31.952  6652  6652 D Config  : [init]
,06-22 07:44:31.953  6652  6652 I Config  : LGCalendar ver.4.40.16
06-22 07:44:31.954  6652  6652 I Config  : start check model
06-22 07:44:31.954  6652  6652 I Config  : start check native_ca
06-22 07:44:31.955  6652  6652 I Config  : Config Operator=OPEN, Country=EU
,06-22 07:44:31.955  6652  6652 D Config  : [setDefaultValuesToPref]
06-22 07:44:31.955  6652  6652 D Config  : [parseProfiles]
06-22 07:44:31.961  6652  6652 D ProfilesParser: [debug_displayParseInfos] profile.country = null
06-22 07:44:31.961  6652  6652 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
06-22 07:44:31.961  6652  6652 D Config  : [updateProfiletoCountryInfo]
06-22 07:44:31.962  6652  6652 D GeneralPreference: [checkAndMigrateOldPreference]
,06-22 07:44:31.974  6652  6652 E AgendaWidgetManager: [updateWidgets] 
,06-22 07:44:31.980  6652  6671 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
06-22 07:44:31.989  6652  6671 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,06-22 07:44:32.005  6652  6671 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,06-22 07:44:32.010  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
06-22 07:44:32.014  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
06-22 07:44:32.018  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
06-22 07:44:32.022  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,06-22 07:44:32.026  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
06-22 07:44:32.030  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
06-22 07:44:32.034  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,06-22 07:44:32.038  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
06-22 07:44:32.041  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
06-22 07:44:32.046  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
06-22 07:44:32.049  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,06-22 07:44:32.053  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
06-22 07:44:32.056  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
06-22 07:44:32.061  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,06-22 07:44:32.064  6652  6671 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
06-22 07:44:32.064  6652  6671 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
06-22 07:44:32.067  6652  6671 I AlertUtils: set default noti to content://media/internal/audio/media/41
06-22 07:44:32.075  6652  6671 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,06-22 07:44:32.146  6652  6678 W HolidayIntentService: onHandleIntent
,06-22 07:44:32.148  6652  6652 D MonthWidgetProvider: [onReceive]
,06-22 07:44:32.149  6652  6652 D CalendarWidgetProvider: [onReceive]
06-22 07:44:32.149  6652  6652 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,06-22 07:44:32.150  6652  6678 D HolidayDataLoader: readJsonAsset : holiday.json
,06-22 07:44:32.162  6652  6652 D CalendarTypeController: [onUpdateAndInitCalendarTime],
06-22 07:44:32.171  6652  6652 D WeekWidgetProvider: [onReceive]
06-22 07:44:32.171  6652  6652 D CalendarWidgetProvider: [onReceive]
,06-22 07:44:32.171  6652  6652 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
06-22 07:44:32.172  6652  6652 D CalendarTypeController: [onUpdateAndInitCalendarTime]
06-22 07:44:32.176  2202  2202 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,06-22 07:44:32.197  2202  2202 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-22 07:44:32.199  2202  2202 D c       : Getting all permits...
06-22 07:44:32.199  2202  2202 D a       : Opening database...
06-22 07:44:32.203  2202  2202 D a       : Opening database auth.proximity.permit_store...
06-22 07:44:32.204  2202  2202 D a       : Closing database...
,06-22 07:44:32.255  1811  1811 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver },
,06-22 07:44:32.265  1811  1811 D SystemUpdateService: onCreate
06-22 07:44:32.269  1811  1811 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
06-22 07:44:32.278  6652  6678 E HolidayIntentService: onHandleIntent:holiday data empty
,06-22 07:44:32.285  1028  1569 I ActivityManager: Killing 5954:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
06-22 07:44:32.288  2202  2336 I art     : Explicit concurrent mark sweep GC freed 11463(635KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 1.253ms total 45.573ms
06-22 07:44:32.288  2202  2202 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
06-22 07:44:32.308  2202  2202 I GCM     : GCM config loaded
,06-22 07:44:32.309  6178  6178 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
06-22 07:44:32.309  6178  6178 W System.err: android.os.DeadObjectException
06-22 07:44:32.309  6178  6178 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-22 07:44:32.309  6178  6178 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-22 07:44:32.309  6178  6178 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
06-22 07:44:32.309  6178  6178 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
06-22 07:44:32.309  6178  6178 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
06-22 07:44:32.310  6178  6178 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
06-22 07:44:32.310  6178  6178 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:44:32.310  6178  6178 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:44:32.310  6178  6178 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:32.310  6178  6178 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-22 07:44:32.310  6178  6178 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:32.310  6178  6178 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:32.310  6178  6178 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-22 07:44:32.310  6178  6178 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-22 07:44:32.310  6178  6178 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
06-22 07:44:32.310  6178  6178 W System.err: android.os.DeadObjectException
06-22 07:44:32.311  6178  6178 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-22 07:44:32.311  6178  6178 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-22 07:44:32.312  6178  6178 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
06-22 07:44:32.312  6178  6178 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
06-22 07:44:32.312  6178  6178 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
06-22 07:44:32.312  6178  6178 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
06-22 07:44:32.312  6178  6178 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:44:32.312  6178  6178 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:44:32.312  6178  6178 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:32.312  6178  6178 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-22 07:44:32.312  6178  6178 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:32.312  6178  6178 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:32.312  6178  6178 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-22 07:44:32.312  6178  6178 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-22 07:44:32.312  6178  6178 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
06-22 07:44:32.313  6178  6178 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
06-22 07:44:32.316   313  6689 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:32.316   313  6689 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
06-22 07:44:32.317   313  6689 D libc-netbsd: res_queryN name = mtalk.google.com succeed
06-22 07:44:32.350  1028  1724 W libp,rocessgroup: failed to open /acct/uid_1000/pid_5954/cgroup.procs: No such file or directory
06-22 07:44:32.350  1811  6684 I CheckinService: active receiver: disabled
06-22 07:44:32.350  1028  1724 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,06-22 07:44:32.363  1811  6682 V GA-SERVICE: Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
,06-22 07:44:32.378  6178  6178 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,06-22 07:44:32.383  6178  6178 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
06-22 07:44:32.425  1028  1971 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6690 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-22 07:44:32.426  6178  6178 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,06-22 07:44:32.428  1811  6685 I SystemUpdateService: cancelUpdate (empty URL)
06-22 07:44:32.428  1811  6685 I SystemUpdateService: active receiver: disabled
06-22 07:44:32.461  1811  1811 D SystemUpdateService: onDestroy
,06-22 07:44:32.485  1811  1811 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,06-22 07:44:32.495  1811  1811 I OcrUtils: Updating ocr activity enabled=false
,06-22 07:44:32.504  2463  2463 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
06-22 07:44:32.526  6690  6690 D UEI.SmartControl: Quickset Services start...
,06-22 07:44:32.530  6690  6690 I UEI.SmartControl: Manufacture = LGE
06-22 07:44:32.531  6690  6690 D UEI.SmartControl: Id = LGNevo
06-22 07:44:32.532  6690  6690 D UEI.SmartControl: File observer start...
06-22 07:44:32.533  6690  6690 E UEI.SmartControl: IR Port is disabled: false
06-22 07:44:32.534  6690  6690 D UEI.SmartControl: Starting file observer...
06-22 07:44:32.534  6690  6690 D UEI.SmartControl: Extracting JNI libs...
,06-22 07:44:32.535  6690  6690 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
06-22 07:44:32.565  1028  1881 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6710 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
,06-22 07:44:32.570  2463  2560 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
06-22 07:44:32.590  2202  6707 D GCM     : Connected
,06-22 07:44:32.654  2202  6707 D GCM     : Message class com.google.e.a.a.q
,06-22 07:44:32.702  6690  6690 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
06-22 07:44:32.702  6690  6690 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-22 07:44:32.702  6690  6690 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,06-22 07:44:32.713  2463  2560 I GCoreUlr: No GCM registration ID
06-22 07:44:32.743  2463  2560 I GCoreUlr: Ensuring that reporting is stopped because of reasons: (no Google accounts)
,06-22 07:44:32.744  4336  4368 I ContactAccountLoggerTas: canRun() : Opted Out
06-22 07:44:32.761  6690  6690 I UEI.SmartControl: --- Selecting new region: 6
,06-22 07:44:32.764  6690  6690 I UEI.SmartControl: Model = LG-D855
06-22 07:44:32.766  6690  6690 D UEI.SmartControl: QS Service created
06-22 07:44:32.768  6710  6736 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:32.768  6710  6736 D LgDataFeature: LgDataFeature() Constructor Done, null
06-22 07:44:32.785  1028  1044 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6743 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
,06-22 07:44:32.794  4336  4369 I Search.GservicesUpdateTask: Updating Gservices keys
06-22 07:44:32.795  2463  2562 D GCoreFlp: Unknown pending intent to remove.
,06-22 07:44:32.809  2463  2560 I GCoreUlr: Unbound from all location providers
06-22 07:44:32.809  6690  6690 I UEI.SmartControl: Service initServices...
06-22 07:44:32.812  2463  2560 I BleScanCompatLib: Scan : No clients left, canceling alarm.
,06-22 07:44:32.813  6690  6690 D UEI.SmartControl: QS start get config
06-22 07:44:32.863  4336  4368 I ContactAccountLoggerTas: canRun() : Opted Out
06-22 07:44:32.864  4336  6753 I ContactAccountLoggerTas: canRun() : Opted Out
,06-22 07:44:32.868  4336  6753 I ContactAccountLoggerTas: canRun() : Opted Out
06-22 07:44:32.872  6690  6690 D UEI.SmartControl: Loading JNI Libs...
06-22 07:44:32.878  6743  6743 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-22 07:44:32.882  4336  6753 I ContactAccountLoggerTas: canRun() : Opted Out
06-22 07:44:32.885   313  6770 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-22 07:44:32.885   313  6770 D libc-netbsd: res_queryN name = www.gstatic.com, class = 1, type = 1
06-22 07:44:32.895  6743  6743 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-22 07:44:32.898  6743  6743 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-22 07:44:32.900  6743  6743 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
06-22 07:44:32.901  1028  1989 I ActivityManager: Killing 6115:com.lge.lifetracker/u0a37 (adj 15): empty #17
06-22 07:44:32.923   313  6770 D libc-netbsd: res_queryN name = www.gstatic.com succeed
,06-22 07:44:33.022  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=36.0, 0.0, 0.0  rx=39.0 bcn=0 [on:0 tx:0 rx:0 period:2994] from screen [on:0 period:1990425086] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:44:33.023  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=36.0, 0.0, 0.0  rx=39.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1990425087] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-22 07:44:33.023  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:44:33.032  1028  1044 W libprocessgroup: failed to open /acct/uid_10037/pid_6115/cgroup.procs: No such file or directory
06-22 07:44:33.053  1028  1043 I ActivityManager: Killing 6178:com.lge.qremote/u0a112 (adj 15): empty #17
,06-22 07:44:33.122  6690  6690 I UEI.SmartControl: Supports setup maps: true
,06-22 07:44:33.124  6690  6690 D UEI.SmartControl: QS start statue = true Error code = 0
06-22 07:44:33.125  6690  6690 I UEI.SmartControl: QS version = v2.7.10.1_RC1
06-22 07:44:33.125  6690  6690 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-22 07:44:33.125  6690  6690 I UEI.SmartControl: ### init IR Blaster...
06-22 07:44:33.127  1028  1917 W libprocessgroup: failed to open /acct/uid_10112/pid_6178/cgroup.procs: No such file or directory
06-22 07:44:33.129  6690  6690 D serial_port: Configuring serial port
06-22 07:44:33.134  2202  2202 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-22 07:44:33.135  6690  6690 E UEI.SmartControl: UEIBLaster setting for 616
06-22 07:44:33.135  6690  6690 I UEI.SmartControl: Setting serial record hearder size = 2
06-22 07:44:33.136  6690  6690 I UEI.SmartControl: configuring settings for MAXQ616
06-22 07:44:33.136  6690  6690 I UEI.SmartControl: Get version...
06-22 07:44:33.145  2202  2202 I GCM     : GCM config loaded
06-22 07:44:33.153  6690  6780 D UEI.SmartControl: serial port data available: 21
,06-22 07:44:33.164  6409  6409 V SetupWizard: Connected to Gservices successfully
06-22 07:44:33.168  2202  2202 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-22 07:44:33.178  6587  6587 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,06-22 07:44:33.180  6690  6690 D UEI.SmartControl: MAXQ616 A2-X4 software.
06-22 07:44:33.180  6690  6690 I UEI.SmartControl: IR Blaster version: 256702256704300002
06-22 07:44:33.180  6690  6690 I UEI.SmartControl: QS saving settings...
06-22 07:44:33.181  6690  6690 D UEI.SmartControl: IR Blaster version: 25672567
,06-22 07:44:33.184  6475  6475 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 7:44:33
,06-22 07:44:33.185  6475  6475 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-22 07:44:33.185  6475  6475 D Weather.Utils: 2 : All the weather widget is gone.
06-22 07:44:33.186  6475  6475 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-22 07:44:33.186  6475  6475 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
06-22 07:44:33.187  6475  6475 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 7:44:33
06-22 07:44:33.189  2202  2202 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
06-22 07:44:33.197  6690  6780 D UEI.SmartControl: serial port data available: 4
,06-22 07:44:33.227  6690  6785 I UEI.SmartControl: Device manager: loading config....
,06-22 07:44:33.227  6690  6785 D UEI.SmartControl: ----------- loading internal config...
,06-22 07:44:33.228  6690  6690 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,06-22 07:44:33.231  6690  6690 E UEI.SmartControl: Services init done
06-22 07:44:33.232  6690  6690 D UEI.SmartControl: QS Service init finished
06-22 07:44:33.233  6690  6690 D UEI.SmartControl: QS Service version name: 2.1.91
06-22 07:44:33.233  6690  6690 D UEI.SmartControl: QS Service version code: 201091
06-22 07:44:33.234  6690  6690 D UEI.SmartControl: Service requested: Control
06-22 07:44:33.235  6690  6785 E UEI.SmartControl: Loading SETTINGS...
06-22 07:44:33.239  6690  6690 D UEI.SmartControl: Request IControl service: devices are loaded...
,06-22 07:44:33.240  6690  6690 D UEI.SmartControl: Service.onUnbind: IControl
06-22 07:44:33.241  6690  6690 D UEI.SmartControl: Service.onDestroy
06-22 07:44:33.241  6690  6690 D UEI.SmartControl: Lock is in USE false
06-22 07:44:33.241  6690  6690 D UEI.SmartControl: unbind internal service
06-22 07:44:33.242  6690  6690 D serial_port: close(fd = 25)
06-22 07:44:33.243  6690  6785 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
06-22 07:44:33.246  6690  6690 I UEI.SmartControl: Serial port is closed.
06-22 07:44:33.247  6690  6690 I UEI.SmartControl: Serial port is closed.
06-22 07:44:33.247  6690  6784 I UEI.SmartControl: Notify AllClients services are ready: 0
06-22 07:44:33.247  6690  6690 D UEI.SmartControl: Blaster closed
06-22 07:44:33.247  6690  6784 D UEI.SmartControl: -----service ready thread exits
06-22 07:44:33.248  6690  6690 D UEI.SmartControl: Shut down QS...
06-22 07:44:33.248  6690  6690 D UEI.SmartControl: Stopping QS lib
06-22 07:44:33.248  6690  6690 D UEI.SmartControl: QS lib stop result = true
06-22 07:44:33.248  6690  6690 D UEI.SmartControl: Stopped QS lib
06-22 07:44:33.249  6690  6690 D UEI.SmartControl: Stopped file observer...
06-22 07:44:33.249  6690  6690 D UEI.SmartControl: QS shutdown complete
06-22 07:44:33.250  6690  6690 D UEI.SmartControl: QS Service created
,06-22 07:44:33.269  6690  6690 I UEI.SmartControl: Service initServices...
,06-22 07:44:33.269  6690  6690 D UEI.SmartControl: QS start get config
06-22 07:44:33.626  6690  6690 I UEI.SmartControl: Supports setup maps: true
,06-22 07:44:33.632  6690  6690 D UEI.SmartControl: QS start statue = true Error code = 0
,06-22 07:44:33.632  6690  6690 I UEI.SmartControl: QS version = v2.7.10.1_RC1
06-22 07:44:33.632  6690  6690 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-22 07:44:33.632  6690  6690 I UEI.SmartControl: ### init IR Blaster...
06-22 07:44:33.636  6690  6690 D serial_port: Configuring serial port
06-22 07:44:33.636  6690  6690 E UEI.SmartControl: UEIBLaster setting for 616
06-22 07:44:33.636  6690  6690 I UEI.SmartControl: Setting serial record hearder size = 2
06-22 07:44:33.636  6690  6690 I UEI.SmartControl: configuring settings for MAXQ616
06-22 07:44:33.636  6690  6690 I UEI.SmartControl: Get version...
06-22 07:44:33.653  6690  6795 D UEI.SmartControl: serial port data available: 21
,06-22 07:44:33.680  6690  6690 D UEI.SmartControl: MAXQ616 A2-X4 software.
,06-22 07:44:33.680  6690  6690 I UEI.SmartControl: IR Blaster version: 256702256704300002
06-22 07:44:33.681  6690  6690 I UEI.SmartControl: QS saving settings...
06-22 07:44:33.683  6690  6690 D UEI.SmartControl: IR Blaster version: 25672567
,06-22 07:44:33.701  6690  6795 D UEI.SmartControl: serial port data available: 4
,06-22 07:44:33.735  6690  6690 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,06-22 07:44:33.741  6690  6690 E UEI.SmartControl: Services init done
,06-22 07:44:33.741  6690  6690 D UEI.SmartControl: QS Service init finished
06-22 07:44:33.743  6690  6690 D UEI.SmartControl: QS Service version name: 2.1.91
06-22 07:44:33.744  6690  6690 D UEI.SmartControl: QS Service version code: 201091
06-22 07:44:33.744  6690  6690 D UEI.SmartControl: Service requested: Control
06-22 07:44:33.749  6690  6798 I UEI.SmartControl: Device manager: loading config....
,06-22 07:44:33.753  1028  1044 I ActivityManager: Killing 5677:com.android.vending/u0a44 (adj 15): empty #17
06-22 07:44:33.754  6690  6798 D UEI.SmartControl: ----------- loading internal config...
06-22 07:44:33.763  6690  6798 E UEI.SmartControl: Loading SETTINGS...
,06-22 07:44:33.769  6690  6798 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
06-22 07:44:33.794  6690  6797 I UEI.SmartControl: Notify AllClients services are ready: 0
06-22 07:44:33.794  6690  6797 D UEI.SmartControl: -----service ready thread exits
,06-22 07:44:33.799  1028  1970 W libprocessgroup: failed to open /acct/uid_10044/pid_5677/cgroup.procs: No such file or directory
06-22 07:44:33.803  6690  6690 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@8653ce1 that was originally bound here
06-22 07:44:33.803  6690  6690 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@8653ce1 that was originally bound here
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-22 07:44:33.803  6690  6690 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-22 07:44:33.804  6690  6690 D UEI.SmartControl: Internal service binding...
06-22 07:44:34.241  6690  6787 D UEI.SmartControl: Internal timer expired: 2
,06-22 07:44:35.059  1028  1724 I ActivityManager: Killing 6319:com.lge.appbox.client/u0a11 (adj 15): empty #17
,06-22 07:44:35.121  1028  1971 W libprocessgroup: failed to open /acct/uid_10011/pid_6319/cgroup.procs: No such file or directory
,06-22 07:44:35.296  1028  1780 I art     : Explicit concurrent mark sweep GC freed 11275(560KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.962ms total 152.864ms
,06-22 07:44:35.309  6500  6521 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,06-22 07:44:36.002  1028  2026 I ActivityManager: Killing 6058:com.lge.formmanager/u0a26 (adj 15): empty #17
,06-22 07:44:36.032  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=30.0, 0.0, 0.0  rx=29.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990428096] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:44:36.036  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=30.0, 0.0, 0.0  rx=29.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990428099] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-22 07:44:36.036  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:44:36.038  1028  1724 W libprocessgroup: failed to open /acct/uid_10026/pid_6058/cgroup.procs: No such file or directory
06-22 07:44:37.537  6690  6701 E UEI.SmartControl: file observer is disposed!
,06-22 07:44:38.140  6556  6778 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,06-22 07:44:38.736  6690  6799 D UEI.SmartControl: Internal timer expired: 3
,06-22 07:44:38.737  6690  6799 D UEI.SmartControl: unbind internal service
,06-22 07:44:38.760  6690  6690 D UEI.SmartControl: Service.onUnbind: IControl
,06-22 07:44:38.763  6690  6690 D UEI.SmartControl: Service.onDestroy
,06-22 07:44:38.763  6690  6690 D UEI.SmartControl: Lock is in USE false
,06-22 07:44:38.763  6690  6690 D UEI.SmartControl: unbind internal service
06-22 07:44:38.765  6690  6690 D serial_port: close(fd = 24)
,06-22 07:44:38.768  6690  6690 I UEI.SmartControl: Serial port is closed.
,06-22 07:44:38.768  6690  6690 I UEI.SmartControl: Serial port is closed.
06-22 07:44:38.768  6690  6690 D UEI.SmartControl: Blaster closed
06-22 07:44:38.768  6690  6690 D UEI.SmartControl: Shut down QS...
06-22 07:44:38.768  6690  6690 D UEI.SmartControl: Stopping QS lib
06-22 07:44:38.769  6690  6690 D UEI.SmartControl: QS lib stop result = true
06-22 07:44:38.769  6690  6690 D UEI.SmartControl: Stopped QS lib
06-22 07:44:38.769  6690  6690 D UEI.SmartControl: QS shutdown complete
06-22 07:44:39.044  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=23.5, 0.0, 0.0  rx=21.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990431107] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-22 07:44:39.047  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=23.5, 0.0, 0.0  rx=21.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990431111] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
06-22 07:44:39.047  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:44:40.850  1596  1596 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,06-22 07:44:40.896  1028  1422 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-22 07:44:40.916  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-22 07:44:40.921   344   344 I art     : Background concurrent mark sweep GC freed 785(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 10.644ms total 43.243ms
06-22 07:44:40.951  1028  1086 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6823 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-22 07:44:40.957  1596  1596 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
06-22 07:44:40.961  1596  1596 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
06-22 07:44:40.996  1028  1028 D administrator: Handling package changes for user 0
,06-22 07:44:41.008  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,06-22 07:44:41.047  6823  6823 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-22 07:44:41.115  1028  1028 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
06-22 07:44:41.115  1028  1028 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-22 07:44:41.120  6823  6823 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:41.120  6823  6823 D LgDataFeature: LgDataFeature() Constructor Done, null
06-22 07:44:41.174  1028  1085 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:44:41.181  1028  1085 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
06-22 07:44:41.191  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
06-22 07:44:41.192  2463  2463 V GmsNetworkLocationProvi: DISABLE
,06-22 07:44:41.237  2463  2463 E GCoreFlp: Bound FusedProviderService with LocationManager
,06-22 07:44:41.244  6823  6869 I Babel   : MmsConfig: mnc/mcc: 0/0
06-22 07:44:41.244  6823  6869 I Babel   : MmsConfig.loadMmsSettings
06-22 07:44:41.259  6823  6869 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
06-22 07:44:41.259  6823  6869 I Babel   : MmsConfig.loadFromDatabase
,06-22 07:44:41.269  6823  6869 E Babel   : canonicalizeMccMnc: invalid mccmnc 
06-22 07:44:41.269  6823  6869 I Babel   : MmsConfig.loadFromResources
06-22 07:44:41.270  6823  6869 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
06-22 07:44:41.271  6823  6869 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,06-22 07:44:41.273  6823  6823 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:44:41.292  6823  6867 W AudioCapabilities: Unsupported mime audio/evrc
06-22 07:44:41.293  6823  6867 W AudioCapabilities: Unsupported mime audio/qcelp
06-22 07:44:41.293  1811  6871 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
06-22 07:44:41.293  1811  6871 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
06-22 07:44:41.294  6823  6867 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:44:41.299  6823  6867 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
06-22 07:44:41.301  6823  6867 W AudioCapabilities: Unsupported mime audio/qcelp
06-22 07:44:41.301  6823  6867 W AudioCapabilities: Unsupported mime audio/evrc
06-22 07:44:41.320  6823  6867 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-22 07:44:41.323  1028  1970 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6873 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-22 07:44:41.332  1028  1044 I ActivityManager: Killing 6433:com.android.chrome/u0a57 (adj 15): empty #17
,06-22 07:44:41.336  6823  6867 W VideoCapabilities: Unsupported mime video/divx
,06-22 07:44:41.338  6823  6867 W VideoCapabilities: Unsupported mime video/divx311
06-22 07:44:41.342   344   344 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 307us total 18.391ms
06-22 07:44:41.346  1811  4405 I Icing   : updateResources: need to parse e{com.google.android.gms}
06-22 07:44:41.346  6823  6867 W VideoCapabilities: Unsupported mime video/divx4
,06-22 07:44:41.351  6823  6867 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-22 07:44:41.356   344   344 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 281us total 13.514ms
06-22 07:44:41.363  6823  6867 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-22 07:44:41.366  6823  6867 W AudioCapabilities: Unsupported mime audio/eac3
,06-22 07:44:41.366  6823  6867 W AudioCapabilities: Unsupported mime audio/ac3
06-22 07:44:41.367  6823  6867 W AudioCapabilities: Unsupported mime audio/g726
06-22 07:44:41.368  6823  6867 W AudioCapabilities: Unsupported mime audio/wma-voice
06-22 07:44:41.368   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 12.398ms
06-22 07:44:41.369  6823  6867 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-22 07:44:41.369  6823  6867 W AudioCapabilities: Unsupported mime audio/adpcm
06-22 07:44:41.370  6823  6867 W VideoCapabilities: Unsupported mime video/theora
06-22 07:44:41.371  6823  6867 W VideoCapabilities: Unsupported mime video/mjpg
,06-22 07:44:41.490  1028  1989 W libprocessgroup: failed to open /acct/uid_10057/pid_6433/cgroup.procs: No such file or directory
,06-22 07:44:41.513  1028  1085 D LocationProviderProxy: applying state to connected service
,06-22 07:44:41.551  6873  6873 I AppUp4:AppBoxCP: onCreate
06-22 07:44:41.552  6873  6873 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,06-22 07:44:41.562  6873  6873 I AppUp4:DB:  setFingerPrint start
06-22 07:44:41.562  6873  6873 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
06-22 07:44:41.571  6873  6873 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
06-22 07:44:41.571  6873  6873 I AppUp4:DB:  SDK version = 21
06-22 07:44:41.571  6873  6873 I AppUp4:DB:  beforefinger == newfinger no write in DB
,06-22 07:44:41.573  6873  6873 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-22 07:44:41.581  6873  6873 I AppUp4:CustModeStarterReceiver: onReceive
06-22 07:44:41.623  6873  6873 D LgDataFeature: LgDataFeature() Constructor: none
06-22 07:44:41.624  6873  6873 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-22 07:44:41.630  6873  6873 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2968632e
06-22 07:44:41.630  6873  6873 D AppUp4:CustFacade: isCustomizationCompleted : false
06-22 07:44:41.630  6873  6873 D AppUp4:CustFacade: isPhone : true
06-22 07:44:41.631  6873  6873 D AppUp4:CustModeStarterReceiver: begin check event
06-22 07:44:41.631  6873  6873 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
06-22 07:44:41.698  1028  1780 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6894 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
06-22 07:44:41.700  1028  1780 I ActivityManager: Killing 6454:com.lge.drmservice/u0a62 (adj 15): empty #17
,06-22 07:44:41.769  1028  1724 W libprocessgroup: failed to open /acct/uid_10062/pid_6454/cgroup.procs: No such file or directory
,06-22 07:44:41.779  1596  1596 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:44:41.780  1596  1596 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:44:41.780  1028  1538 D WifiController: battery changed pluggedType: 2
06-22 07:44:41.781  1596  1596 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
06-22 07:44:41.781  1596  1596 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:44:41.782  1935  2064 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:44:41.782  1935  2064 D LEDHandler: Battery Level Remaining: 100%
06-22 07:44:41.782  1935  2064 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
,06-22 07:44:41.782  1596  1596 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-22 07:44:41.786  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:41.786  5996  6051 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:44:41.786  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:41.787  6634  6634 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-22 07:44:41.802  6894  6894 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:41.803  6894  6894 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:44:41.803  6894  6894 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,06-22 07:44:41.804  6894  6894 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
06-22 07:44:41.804  6894  6894 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-22 07:44:41.878  6894  6894 I SystemConfig: BUILD Country: EU
06-22 07:44:41.878  6894  6894 I SystemConfig: BUILD Operator: OPEN
,06-22 07:44:41.935  1028  1569 I ActivityManager: Killing 6500:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,06-22 07:44:42.002  1028  1916 W libprocessgroup: failed to open /acct/uid_10093/pid_6500/cgroup.procs: No such file or directory
,06-22 07:44:42.015  6894  6914 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
06-22 07:44:42.015  6894  6914 I SystemConfig: existFile = false
,06-22 07:44:42.016  6894  6914 I SystemConfig: canReadFile = false
06-22 07:44:42.016  6894  6914 I SystemConfig: systemFeature RCS result false
06-22 07:44:42.016  6894  6914 D SystemConfig: refreshRcsSupport() :false
06-22 07:44:42.071  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=12.2, 0.0, 0.0  rx=11.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990434135] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:44:42.076  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=12.2, 0.0, 0.0  rx=11.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990434139] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:44:42.076  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:44:42.088  1028  1952 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6916 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,06-22 07:44:42.148  6916  6916 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:42.149  6916  6916 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-22 07:44:42.149  6916  6916 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
06-22 07:44:42.149  6916  6916 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-22 07:44:42.261  6916  6916 I AppConfig: Total System Memory = 2995761152
,06-22 07:44:42.277  6916  6916 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,06-22 07:44:42.365  1028  1780 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6938 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:42.366  1028  1780 I ActivityManager: Killing 6373:com.lge.email/u0a23 (adj 15): empty #17
06-22 07:44:42.464  1028  1970 W libprocessgroup: failed to open /acct/uid_10023/pid_6373/cgroup.procs: No such file or directory
,06-22 07:44:42.685  6938  6938 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,06-22 07:44:42.892  6938  6938 D LgDataFeature: LgDataFeature() Constructor: none
,06-22 07:44:42.892  6938  6938 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-22 07:44:42.941  6938  6938 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,06-22 07:44:42.963  6938  6938 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:44:42.965  6938  6938 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-22 07:44:42.985  6938  6938 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
06-22 07:44:42.986  6938  6938 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,06-22 07:44:43.018  1028  1989 I ActivityManager: Killing 5075:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,06-22 07:44:43.050  1028  1952 W libprocessgroup: failed to open /acct/uid_1000/pid_5075/cgroup.procs: No such file or directory
,06-22 07:44:43.053  2812  2896 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,06-22 07:44:43.054  2812  2896 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@248d8ff2 on behalf of 6938
06-22 07:44:43.061  4336  6984 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
06-22 07:44:43.112  1028  1780 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6985 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:43.149  6938  6938 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,06-22 07:44:43.181  6938  6938 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,06-22 07:44:43.220  6985  6985 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,06-22 07:44:43.251  6985  6985 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
06-22 07:44:43.251  6985  6985 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
06-22 07:44:43.251  6985  6985 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
06-22 07:44:43.251  6985  6985 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
06-22 07:44:43.252  6985  6985 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
06-22 07:44:43.252  6985  6985 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,06-22 07:44:43.281  1028  1880 I ActivityManager: Killing 6613:com.qualcomm.timeservice/1000 (adj 15): empty #17
,06-22 07:44:43.321  1028  1724 W libprocessgroup: failed to open /acct/uid_1000/pid_6613/cgroup.procs: No such file or directory
,06-22 07:44:43.608  1028  1917 V SIM_STK : Menu title from STK is T-Mobile
,06-22 07:44:43.642  4336  6984 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 580 ms] updated apps [took 580 ms] 
,06-22 07:44:45.094  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990437157] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:44:45.097  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990437160] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:44:45.097  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:44:48.122  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990440186] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:44:48.125  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990440189] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:44:48.125  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:44:48.199  1028  1970 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,06-22 07:44:48.202  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:48.202  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:48.202  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-22 07:44:48.202  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:48.202  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-22 07:44:48.211  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 22 Jun 2016 05:44:48 GMT], X-Android-Received-Millis=[1466574288211], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1466574288206]}
06-22 07:44:48.211  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-22 07:44:48.211  1028  6173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,06-22 07:44:48.214  1028  1539 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
,06-22 07:44:48.215  1028  1539 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
,06-22 07:44:48.215  1028  1539 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:48.215  1028  1539 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,06-22 07:44:48.215  1028  1539 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,06-22 07:44:48.215  1028  1539 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-22 07:44:48.215  1028  1539 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,06-22 07:44:48.215  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:48.215  1028  1539 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:48.219  1028  1539 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ],
06-22 07:44:48.220  1596  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-22 07:44:51.189  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1990443253] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:44:51.192  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990443256] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:44:51.193  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:44:54.215  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990446279] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:44:54.225  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1990446288] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:44:54.226  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:44:57.246  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990449310] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:44:57.258  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990449322] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:44:57.258  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:44:57.463  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{28080a46 type 2 when 151806 com.google.android.gms} when 151806
,06-22 07:44:57.499   313  7035 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-22 07:44:57.502   313  7035 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
06-22 07:44:57.503   313  7035 D libc-netbsd: res_queryN name = mtalk.google.com succeed
06-22 07:44:57.533  1028  1086 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7036 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,06-22 07:44:57.650  7036  7036 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-22 07:44:57.685  7036  7036 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,06-22 07:44:57.710  7036  7036 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
06-22 07:44:57.711  7036  7036 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
06-22 07:44:57.711  7036  7036 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,06-22 07:44:57.713  7036  7036 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
06-22 07:44:57.713  7036  7036 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
06-22 07:44:57.715  7036  7036 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
06-22 07:44:57.718  7036  7036 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
06-22 07:44:57.724  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,06-22 07:44:57.726  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6690
06-22 07:44:57.729  7036  7036 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
06-22 07:44:57.731  7036  7036 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
06-22 07:44:57.732  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
06-22 07:44:57.733  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
06-22 07:44:57.733  7036  7036 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
06-22 07:44:57.756  7036  7036 D LgDataFeature: LgDataFeature() Constructor: none
,06-22 07:44:57.758  7036  7036 D LgDataFeature: LgDataFeature() Constructor Done, null
06-22 07:44:57.763  7036  7036 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
06-22 07:44:57.763  7036  7036 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
06-22 07:44:57.763  7036  7036 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
06-22 07:44:57.763  7036  7036 V SoundPool: doLoad: loading sample sampleID=1
06-22 07:44:57.764  7036  7036 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
06-22 07:44:57.767  6690  6690 D UEI.SmartControl: QS Service created
06-22 07:44:57.769  7036  7036 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,06-22 07:44:57.773  7036  7036 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-22 07:44:57.773  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
06-22 07:44:57.776  7036  7057 V SoundPool: Start decode
06-22 07:44:57.777  7036  7057 V MediaPlayer[Native]: decode(31, 10857164, 17813)
06-22 07:44:57.777   318  2158 V MediaPlayerService: decode(23, 10857164, 17813)
06-22 07:44:57.777   318  2158 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
06-22 07:44:57.777   318  2158 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
06-22 07:44:57.777   318  2158 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
06-22 07:44:57.777   318  2158 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
06-22 07:44:57.777   318  2158 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
06-22 07:44:57.777   318  2158 V MediaPlayerService: player type = 3
06-22 07:44:57.777   318  2158 V AwesomePlayer: AwesomePlayer create()
06-22 07:44:57.778   318  2158 V AwesomePlayer: reset_l() 
06-22 07:44:57.778   318  2158 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:57.778   318  2158 V AwesomePlayer: setAudioSink() 
06-22 07:44:57.778   318  2158 V AwesomePlayer: reset_l() 
06-22 07:44:57.778   318  2158 V AudioCache: notify(0xb1012300, 8, 0, 0)
06-22 07:44:57.778   318  2158 V AudioCache: ignored
06-22 07:44:57.778   318  2158 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:57.778   318  2158 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
06-22 07:44:57.778   318  2158 V AwesomePlayer: setDataSource_l dataSource
06-22 07:44:57.778   318  2158 V LGParserOSAL: SniffLGParser start
06-22 07:44:57.778   318  2158 V LGParserOSAL: MainType:5, SubType=0
06-22 07:44:57.778   318  2158 V LGParserOSAL: #### check Mime : application/ogg
06-22 07:44:57.778   318  2158 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
06-22 07:44:57.778   318  2158 E MediaExtractor: Use LGExtractor :application/ogg 
06-22 07:44:57.804   318  2158 V LGParserOSAL: supported mime: application/ogg
06-22 07:44:57.804   318  2158 V AwesomePlayer: setDataSource_l() extractor countTracks=1
06-22 07:44:57.804   318  2158 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
06-22 07:44:57.804   318  2158 V AwesomePlayer: mBitrate = -1 bits/sec
06-22 07:44:57.804   318  2158 V AwesomePlayer: AudioTrack Setting
06-22 07:44:57.804   318  2158 V AwesomePlayer: AudioTrack Setting channelCount = 2
06-22 07:44:57.804   318  2158 V AwesomePlayer: setAudioSource() 
06-22 07:44:57.804   318  2158 V MediaPlayerService: prepare
06-22 07:44:57.804   318  2158 V AwesomePlayer: prepareAsync_l() 
,06-22 07:44:57.807   318  2158 V MediaPlayerService: wait for prepare
06-22 07:44:57.808   318  7058 V AwesomePlayer: onPrepareAsyncEvent() 
06-22 07:44:57.808   318  7058 V AwesomePlayer: initAudioDecoder() 
06-22 07:44:57.808   318  7058 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
06-22 07:44:57.808   318  7058 V AudioSystem: isOffloadSupported()
06-22 07:44:57.808   318  7058 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
06-22 07:44:57.808   318  7058 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-22 07:44:57.808   318  7058 I AudioFlinger: isAudioPlaybackHookOn() false
06-22 07:44:57.808   318  7058 V AwesomePlayer: getUseOffload() = 0 
06-22 07:44:57.808   318  7058 V OMXCodec: OMXCodec::Create
06-22 07:44:57.808   318  7058 V OMXCodec: findMatchingCodecs()
06-22 07:44:57.808   318  7058 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
06-22 07:44:57.808   318  7058 V OMXCodec: matchingCodecs.size()=1
06-22 07:44:57.808   318  7058 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
06-22 07:44:57.809   318  7058 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
06-22 07:44:57.809   318  7058 V LGCodecAdapter: LG Codec Adapter start
06-22 07:44:57.810   318  7058 V OMXCodec: OMXCodec Createtor
06-22 07:44:57.810   318  7058 V OMXCodec: setComponentRole
06-22 07:44:57.810   318  7058 V OMXCodec: configureCodec protected=0
06-22 07:44:57.810   318  7058 V LGCodecAdapter: called getLGCodecSpecificData
06-22 07:44:57.810   318  7058 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
06-22 07:44:57.810   318  7058 V LGCodecOSAL: Called LGconfigureCodecMETA
06-22 07:44:57.810   318  7058 V LGCodecOSAL: Called LGconfigureCodecMSG
06-22 07:44:57.810   318  7058 V LGCodecOSAL: Not support LGCodec
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
06-22 07:44:57.810   318  7058 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
06-22 07:44:57.810   318  7058 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
06-22 07:44:57.810   318  7058 I AwesomePlayer: Could not offload audio decode, try pcm offload
06-22 07:44:57.810   318  7058 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
06-22 07:44:57.810   318  7058 V AudioSystem: isOffloadSupported()
06-22 07:44:57.810   318  7058 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
06-22 07:44:57.810   318  7058 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
06-22 07:44:57.810   318  7058 V OMXCodec: init()
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
06-22 07:44:57.810   318  7058 V OMXCodec: allocateBuffers
06-22 07:44:57.810   318  7058 V OMXCodec: allocateBuffersOnPort portIndex=0
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.deco,der] allocated buffer 0xb040f9c0 on input port
06-22 07:44:57.810   318  7058 V OMXCodec: allocateBuffersOnPort portIndex=1
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
06-22 07:44:57.810   318  7058 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040ffb0 on output port
06-22 07:44:57.810   318  7058 V OMXCodec: init() mAsyncCompletion wait!!! 
06-22 07:44:57.811   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
06-22 07:44:57.811   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
06-22 07:44:57.811   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
06-22 07:44:57.811   318  7058 V OMXCodec: init() mAsyncCompletion wait!!! 
06-22 07:44:57.812   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
06-22 07:44:57.812   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
06-22 07:44:57.812   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
06-22 07:44:57.812   318  7058 V OMXCodec: init() mAsyncCompletion wait free! 
06-22 07:44:57.812   318  7058 V AwesomePlayer: finishAsyncPrepare_l() 
06-22 07:44:57.812   318  7058 V AudioCache: notify(0xb1012300, 5, 0, 0)
06-22 07:44:57.812   318  7058 V AudioCache: ignored
06-22 07:44:57.812   318  7058 V AudioCache: notify(0xb1012300, 1, 0, 0)
06-22 07:44:57.812   318  7058 V AudioCache: prepared
06-22 07:44:57.812   318  2158 V AudioCache: wait - success
06-22 07:44:57.812   318  2158 V MediaPlayerService: start
06-22 07:44:57.812   318  2158 V AwesomePlayer: play_l() 
06-22 07:44:57.812   318  2158 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
06-22 07:44:57.812   318  2158 V AwesomePlayer: createAudioPlayer_l
06-22 07:44:57.812   318  2158 V AwesomePlayer: seekAudioIfNecessary_l() 
06-22 07:44:57.812   318  2158 V AwesomePlayer: startAudioPlayer_l() 
06-22 07:44:57.812   318  2158 D AudioPlayer: start of Playback, useOffload 0
06-22 07:44:57.812   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
06-22 07:44:57.812   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
06-22 07:44:57.814   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
06-22 07:44:57.814   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
06-22 07:44:57.814   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
06-22 07:44:57.814   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
06-22 07:44:57.814   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
06-22 07:44:57.815  2202  7053 D GCM     : Connected
,06-22 07:44:57.826   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049776
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
06-22 07:44:57.827   318  7060 V OMXCodec: allocateBuffersOnPort portIndex=1
06-22 07:44:57.827   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
06-22 07:44:57.828   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
06-22 07:44:57.828   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
06-22 07:44:57.828   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
06-22 07:44:57.828   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb16dd150 on output port
06-22 07:44:57.829   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
06-22 07:44:57.829   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
06-22 07:44:57.829   318  2158 V AudioCache: open(48000, 2, 0x0, 1, 4)
06-22 07:44:57.830   318  2158 V AudioCache: notify(0xb1012300, 6, 0, 0)
06-22 07:44:57.830   318  2158 V AudioCache: ignored
06-22 07:44:57.831   318  2158 V MediaPlayerService: wait for playback complete
06-22 07:44:57.832   318  7061 V AudioCache: write(0xb57bd000, 4096)
,06-22 07:44:57.833   318  7061 V AudioCache: memcpy(0xaf004000, 0xb57bd000, 4096)
06-22 07:44:57.834   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.835   318  7061 V AudioCache: memcpy(0xaf005000, 0xb57bd000, 4096)
06-22 07:44:57.835   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.835   318  7061 V AudioCache: memcpy(0xaf006000, 0xb57bd000, 4096)
06-22 07:44:57.835   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.835   318  7061 V AudioCache: memcpy(0xaf007000, 0xb57bd000, 4096)
06-22 07:44:57.836   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.836   318  7061 V AudioCache: memcpy(0xaf008000, 0xb57bd000, 4096)
06-22 07:44:57.836   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.836   318  7061 V AudioCache: memcpy(0xaf009000, 0xb57bd000, 4096)
06-22 07:44:57.836   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.836   318  7061 V AudioCache: memcpy(0xaf00a000, 0xb57bd000, 4096)
06-22 07:44:57.836   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.836   318  7061 V AudioCache: memcpy(0xaf00b000, 0xb57bd000, 4096)
06-22 07:44:57.837   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.837   318  7061 V AudioCache: memcpy(0xaf00c000, 0xb57bd000, 4096)
06-22 07:44:57.838   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.838   318  7061 V AudioCache: memcpy(0xaf00d000, 0xb57bd000, 4096)
06-22 07:44:57.838   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.838   318  7061 V AudioCache: memcpy(0xaf00e000, 0xb57bd000, 4096)
06-22 07:44:57.838   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.838   318  7061 V AudioCache: memcpy(0xaf00f000, 0xb57bd000, 4096)
06-22 07:44:57.839   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.839   318  7061 V AudioCache: memcpy(0xaf010000, 0xb57bd000, 4096)
06-22 07:44:57.839   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.839   318  7061 V AudioCache: memcpy(0xaf011000, 0xb57bd000, 4096)
06-22 07:44:57.839   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.839   318  7061 V AudioCache: memcpy(0xaf012000, 0xb57bd000, 4096)
06-22 07:44:57.841  2202  7053 D GCM     : Message class com.google.e.a.a.q
06-22 07:44:57.861   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.862   318  7061 V AudioCache: memcpy(0xaf013000, 0xb57bd000, 4096)
,06-22 07:44:57.864   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.864   318  7061 V AudioCache: memcpy(0xaf014000, 0xb57bd000, 4096)
06-22 07:44:57.864   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.864   318  7061 V AudioCache: memcpy(0xaf015000, 0xb57bd000, 4096)
06-22 07:44:57.866   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.866   318  7061 V AudioCache: memcpy(0xaf016000, 0xb57bd000, 4096)
06-22 07:44:57.867   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.867   318  7061 V AudioCache: memcpy(0xaf017000, 0xb57bd000, 4096)
06-22 07:44:57.868   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.868   318  7061 V AudioCache: memcpy(0xaf018000, 0xb57bd000, 4096)
06-22 07:44:57.869  7036  7036 V LGMDMManager: Create singleton instance
06-22 07:44:57.871   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.871   318  7061 V AudioCache: memcpy(0xaf019000, 0xb57bd000, 4096)
06-22 07:44:57.873   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.873   318  7061 V AudioCache: memcpy(0xaf01a000, 0xb57bd000, 4096)
06-22 07:44:57.873   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.873   318  7061 V AudioCache: memcpy(0xaf01b000, 0xb57bd000, 4096)
06-22 07:44:57.873   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.873   318  7061 V AudioCache: memcpy(0xaf01c000, 0xb57bd000, 4096)
06-22 07:44:57.873   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.873   318  7061 V AudioCache: memcpy(0xaf01d000, 0xb57bd000, 4096)
06-22 07:44:57.875   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.875   318  7061 V AudioCache: memcpy(0xaf01e000, 0xb57bd000, 4096)
06-22 07:44:57.875   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.875   318  7061 V AudioCache: memcpy(0xaf01f000, 0xb57bd000, 4096)
06-22 07:44:57.875   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.875   318  7061 V AudioCache: memcpy(0xaf020000, 0xb57bd000, 4096)
06-22 07:44:57.875   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.875   318  7061 V AudioCache: memcpy(0xaf021000, 0xb57bd000, 4096)
06-22 07:44:57.876   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.877   318  7061 V AudioCache: memcpy(0xaf022000, 0xb57bd000, 4096)
06-22 07:44:57.877   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.877   318  7061 V AudioCache: memcpy(0xaf023000, 0xb57bd000, 4096)
06-22 07:44:57.877   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.877   318  7061 V AudioCache: memcpy(0xaf024000, 0xb57bd000, 4096)
06-22 07:44:57.877   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.877   318  7061 V AudioCache: memcpy(0xaf025000, 0xb57bd000, 4096)
,06-22 07:44:57.880   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.880   318  7061 V AudioCache: memcpy(0xaf026000, 0xb57bd000, 4096)
06-22 07:44:57.880   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.880   318  7061 V AudioCache: memcpy(0xaf027000, 0xb57bd000, 4096)
06-22 07:44:57.880   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.880   318  7061 V AudioCache: memcpy(0xaf028000, 0xb57bd000, 4096)
06-22 07:44:57.880   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.880   318  7061 V AudioCache: memcpy(0xaf029000, 0xb57bd000, 4096)
06-22 07:44:57.882   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.882   318  7061 V AudioCache: memcpy(0xaf02a000, 0xb57bd000, 4096)
06-22 07:44:57.882   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.882   318  7061 V AudioCache: memcpy(0xaf02b000, 0xb57bd000, 4096)
06-22 07:44:57.882   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.882   318  7061 V AudioCache: memcpy(0xaf02c000, 0xb57bd000, 4096)
06-22 07:44:57.882   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.882   318  7061 V AudioCache: memcpy(0xaf02d000, 0xb57bd000, 4096)
06-22 07:44:57.883  6690  6690 I UEI.SmartControl: Service initServices...
06-22 07:44:57.883  6690  6690 D UEI.SmartControl: QS start get config
06-22 07:44:57.883   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.883   318  7061 V AudioCache: memcpy(0xaf02e000, 0xb57bd000, 4096)
06-22 07:44:57.884   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.884   318  7061 V AudioCache: memcpy(0xaf02f000, 0xb57bd000, 4096)
06-22 07:44:57.885   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.885   318  7061 V AudioCache: memcpy(0xaf030000, 0xb57bd000, 4096)
06-22 07:44:57.885   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.885   318  7061 V AudioCache: memcpy(0xaf031000, 0xb57bd000, 4096)
06-22 07:44:57.886   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.886   318  7061 V AudioCache: memcpy(0xaf032000, 0xb57bd000, 4096)
06-22 07:44:57.886   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.886   318  7061 V AudioCache: memcpy(0xaf033000, 0xb57bd000, 4096)
06-22 07:44:57.887   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.887   318  7061 V AudioCache: memcpy(0xaf034000, 0xb57bd000, 4096)
06-22 07:44:57.888   318  7061 V AudioCache: write(0xb57bd000, 4096)
06-22 07:44:57.888   318  7061 V AudioCache: memcpy(0xaf035000, 0xb57bd000, 4096)
,06-22 07:44:57.888   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
06-22 07:44:57.888   318  7061 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
06-22 07:44:57.888   318  7061 V AwesomePlayer: postAudioEOS() 
06-22 07:44:57.888   318  7061 V AudioCache: write(0xb57bd000, 280)
06-22 07:44:57.888   318  7061 V AudioCache: memcpy(0xaf036000, 0xb57bd000, 280)
06-22 07:44:57.890   318  7058 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
06-22 07:44:57.890   318  7058 V AwesomePlayer: onStreamDone
06-22 07:44:57.890   318  7058 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
06-22 07:44:57.890   318  7058 V AudioCache: notify(0xb1012300, 2, 0, 0)
06-22 07:44:57.890   318  7058 V AudioCache: playback complete
06-22 07:44:57.890   318  2158 V AudioCache: wait - success
06-22 07:44:57.890   318  2158 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
06-22 07:44:57.890   318  7058 V AwesomePlayer: pause_l() 
06-22 07:44:57.890   318  7058 V AudioCache: notify(0xb1012300, 7, 0, 0)
06-22 07:44:57.890   318  7058 V AudioCache: ignored
06-22 07:44:57.890   318  7058 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:57.890   318  7058 D AudioPlayer: Pause Playback at 1068125
06-22 07:44:57.890   318  2158 V AwesomePlayer: reset_l() 
06-22 07:44:57.890   318  2158 V AudioCache: notify(0xb1012300, 8, 0, 0)
06-22 07:44:57.890   318  2158 V AudioCache: ignored
06-22 07:44:57.890   318  2158 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:57.890   318  2158 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
06-22 07:44:57.890   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
06-22 07:44:57.890   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
06-22 07:44:57.891   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
06-22 07:44:57.891   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
06-22 07:44:57.892   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
06-22 07:44:57.892   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
06-22 07:44:57.892   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
06-22 07:44:57.892   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
06-22 07:44:57.892   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
06-22 07:44:57.893   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
06-22 07:44:57.893   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb16dd150 on port 1
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-22 07:44:57.894   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
06-22 07:44:57.894   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
06-22 07:44:57.894   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
06-22 07:44:57.895   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
06-22 07:44:57.895   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
06-22 07:44:57.895   318  7060 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
06-22 07:44:57.895   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
06-22 07:44:57.895   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
06-22 07:44:57.895   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
06-22 07:44:57.896   318  2158 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
06-22 07:44:57.896   318  2158 D AudioPlayer: AudioPlayer releasing audio source
06-22 07:44:57.896   318  2158 D AudioPlayer: AudioPlayer done releasing audio source
06-22 07:44:57.896   318  2158 V AwesomePlayer: reset_l() 
06-22 07:44:57.896   318  2158 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:57.896   318  2158 V AwesomePlayer: ~AwesomePlayer call
06-22 07:44:57.896   318  2158 V AwesomePlayer: reset_l() 
06-22 07:44:57.896   318  2158 V AwesomePlayer: cancelPlayerEvents
06-22 07:44:57.896  7036  7057 V SoundPool: close(31)
06-22 07:44:57.896  7036  7057 V SoundPool: pointer = 0x9fe6d000, size = 205080, sampleRate = 48000, numChannels = 2
06-22 07:44:57.912  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,06-22 07:44:57.913  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
06-22 07:44:57.915  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8607
06-22 07:44:58.221  6690  6690 I UEI.SmartControl: Supports setup maps: true
,06-22 07:44:58.227  6690  6690 D UEI.SmartControl: QS start statue = true Error code = 0
,06-22 07:44:58.227  6690  6690 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,06-22 07:44:58.227  6690  6690 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-22 07:44:58.227  6690  6690 I UEI.SmartControl: ### init IR Blaster...
06-22 07:44:58.231  6690  6690 D serial_port: Configuring serial port
06-22 07:44:58.232  6690  6690 E UEI.SmartControl: UEIBLaster setting for 616
06-22 07:44:58.232  6690  6690 I UEI.SmartControl: Setting serial record hearder size = 2
06-22 07:44:58.232  6690  6690 I UEI.SmartControl: configuring settings for MAXQ616
,06-22 07:44:58.232  6690  6690 I UEI.SmartControl: Get version...
06-22 07:44:58.246  6690  7084 D UEI.SmartControl: serial port data available: 21
,06-22 07:44:58.273  6690  6690 D UEI.SmartControl: MAXQ616 A2-X4 software.
,06-22 07:44:58.274  6690  6690 I UEI.SmartControl: IR Blaster version: 256702256704300002
,06-22 07:44:58.278  6690  6690 I UEI.SmartControl: QS saving settings...
06-22 07:44:58.281  6690  6690 D UEI.SmartControl: IR Blaster version: 25672567
,06-22 07:44:58.298  6690  7084 D UEI.SmartControl: serial port data available: 4
,06-22 07:44:58.336  6690  6690 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,06-22 07:44:58.346  6690  6690 E UEI.SmartControl: Services init done
06-22 07:44:58.346  6690  6690 D UEI.SmartControl: QS Service init finished
06-22 07:44:58.347  6690  7090 I UEI.SmartControl: Device manager: loading config....
06-22 07:44:58.347  6690  7090 D UEI.SmartControl: ----------- loading internal config...
06-22 07:44:58.349  6690  6690 D UEI.SmartControl: QS Service version name: 2.1.91
06-22 07:44:58.349  6690  6690 D UEI.SmartControl: QS Service version code: 201091
06-22 07:44:58.349  6690  6690 D UEI.SmartControl: Service requested: Control
06-22 07:44:58.353  6690  7090 E UEI.SmartControl: Loading SETTINGS...
,06-22 07:44:58.357  6690  6690 D UEI.SmartControl: Request IControl service: devices are loaded...
06-22 07:44:58.360  7036  7036 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
06-22 07:44:58.361  6690  6708 I UEI.SmartControl: ------ IControl API: 11
06-22 07:44:58.361  6690  6708 D UEI.SmartControl: File observer start...
06-22 07:44:58.362  6690  6708 E UEI.SmartControl: IR Port is disabled: false
06-22 07:44:58.362  6690  6708 D UEI.SmartControl: Starting file observer...
06-22 07:44:58.363  6690  6708 I UEI.SmartControl: Registering callback...
06-22 07:44:58.364  6690  6690 D UEI.SmartControl: Internal service binding...
06-22 07:44:58.364  6690  6706 I UEI.SmartControl: ------ IControl API: 19
06-22 07:44:58.365  6690  6706 I UEI.SmartControl: Registering Services Ready callback...
06-22 07:44:58.370  6690  7090 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,06-22 07:44:58.386  6690  7089 I UEI.SmartControl: Notify AllClients services are ready: 0
,06-22 07:44:58.388  7036  7052 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
06-22 07:44:58.389  7036  7055 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
06-22 07:44:58.389  7036  7055 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
06-22 07:44:58.390  7036  7036 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
06-22 07:44:58.390  6690  7089 D UEI.SmartControl: -----service ready thread exits
06-22 07:44:58.391  7036  7036 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
06-22 07:44:58.391  6690  6708 I UEI.SmartControl: ------ IControl API: 8
06-22 07:44:58.393  7036  7036 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
06-22 07:44:58.393  7036  7036 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
06-22 07:44:58.394  7036  7036 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
06-22 07:44:58.394  7036  7036 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
06-22 07:44:58.395  7036  7036 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
06-22 07:44:58.395  7036  7036 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
06-22 07:44:58.400  7036  7036 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,06-22 07:44:58.407  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
06-22 07:44:58.408  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
06-22 07:44:58.409  7036  7036 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-22 07:44:58.409  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
06-22 07:44:58.411  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
06-22 07:44:58.412  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
06-22 07:44:58.413  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,06-22 07:44:58.416  7036  7036 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1466574298416]
06-22 07:44:58.422  7036  7036 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
06-22 07:44:58.425  1028  1970 I ActivityManager: Killing 6634:com.lge.bnr/1000 (adj 15): empty #17
,06-22 07:44:58.469  1028  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_6634/cgroup.procs: No such file or directory
,06-22 07:44:58.477  7036  7092 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
06-22 07:44:58.483  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,06-22 07:44:58.486  7036  7036 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-22 07:44:58.486  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
06-22 07:44:58.487  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
06-22 07:44:58.487  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
06-22 07:44:58.487  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
06-22 07:44:58.488  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
06-22 07:44:58.498  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,06-22 07:45:00.045  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:45:00.045  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:45:00.046  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:45:00.046  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:45:00.063  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:45:00.063  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:45:00.069  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:45:00.077  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:45:00.279  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990452343] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:00.282  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990452346] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:00.283  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:01.301  1028  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=899732805, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,06-22 07:45:01.323  6587  6587 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-22 07:45:01.329  6587  6587 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@369b843a
06-22 07:45:01.354  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,06-22 07:45:01.383  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=899732805 [*alarm*], flags=0x0
,06-22 07:45:03.304  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990455368] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:03.307  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990455371] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:03.308  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:03.332  6690  7091 D UEI.SmartControl: Internal timer expired: 4
06-22 07:45:03.332  6690  7091 D UEI.SmartControl: unbind internal service
,06-22 07:45:03.352  6690  7085 D serial_port: close(fd = 24)
,06-22 07:45:03.360  6690  7085 I UEI.SmartControl: Serial port is closed.
,06-22 07:45:03.969  1028  1532 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
06-22 07:45:03.971  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
06-22 07:45:03.972  1028  1532 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,06-22 07:45:03.973  1028  1532 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
06-22 07:45:03.974  1028  1532 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,06-22 07:45:03.975  1028  1532 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,06-22 07:45:06.332  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990458396] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:06.335  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990458399] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:06.335  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:09.363  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1990461427] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:09.374  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990461438] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:09.374  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:45:12.394  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990464458] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:12.397  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990464461] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:12.397  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:15.425  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990467489] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:15.434  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990467492] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:15.434  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:18.454  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990470518] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:18.457  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990470521] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:18.458  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:21.483  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990473547] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:21.486  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990473550] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:21.487  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:24.512  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990476576] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:24.515  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990476579] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:24.516  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:27.539  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990479602] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:27.542  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990479605] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:27.542  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:27.867  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{318c1115 type 2 when 182206 com.google.android.gms} when 182206
,06-22 07:45:27.892  7036  7036 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,06-22 07:45:27.896  7036  7036 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8607
06-22 07:45:27.925  1811  1811 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-22 07:45:27.931  2202  2202 I ConfigService: onCreate
06-22 07:45:27.932  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-22 07:45:27.934  1811  7093 I ConfigFetchService: running network task: configservice_periodic
06-22 07:45:27.937  1811  7093 I ConfigFetchService: launchTask
,06-22 07:45:27.945  2202  2202 I ConfigService: onBind returning update interface
06-22 07:45:27.947  1811  1811 I ConfigFetchService: service connected
06-22 07:45:27.947  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-22 07:45:27.947  2202  2202 I ConfigService: onBind returning config service
06-22 07:45:27.949  1811  1811 I ConfigClient: service connected
,06-22 07:45:28.020  1028  2026 V SIM_STK : Menu title from STK is T-Mobile
,06-22 07:45:28.042  1811  2379 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-22 07:45:28.078   313  7100 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-22 07:45:28.080   313  7100 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-22 07:45:28.080   313  7100 D libc-netbsd: res_queryN name = android.clients.google.com succeed
06-22 07:45:28.273  1811  2379 W ConfigFetchTask: bad response from server: 401 Unauthorized
06-22 07:45:28.276  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
,06-22 07:45:28.281  1811  1811 I ConfigFetchService: stopping self
06-22 07:45:28.319  2202  2202 I ConfigService: onDestroy
,06-22 07:45:30.566  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990482630] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:30.576  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990482640] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:30.577  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:45:33.597  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990485661] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:45:33.611  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1990485674] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:45:33.611  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:36.631  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990488695] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:36.634  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990488698] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:36.634  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:39.662  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990491725] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:39.665  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990491728] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:39.665  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:42.687  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1990494750] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:42.698  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990494762] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:42.699  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:45.719  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990497782] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:45.722  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990497785] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:45.722  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:48.744  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990500808] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:48.747  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990500811] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:48.747  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:51.766  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990503830] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:51.775  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1990503839] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:51.775  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:45:54.798  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990506861] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:54.812  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1990506875] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:54.812  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:45:57.831  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990509895] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:45:57.835  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990509898] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:45:57.835  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:00.065  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:46:00.065  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:46:00.065  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-22 07:46:00.066  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:46:00.080  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:46:00.081  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:46:00.083  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:46:00.085  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:46:00.857  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990512921] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:00.873  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:1990512937] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:00.873  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:03.891  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990515955] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:46:03.894  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990515958] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:03.894  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:06.919  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990518982] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:06.922  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990518986] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:06.922  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:09.947  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1990522010] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:09.957  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990522021] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:09.957  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:12.979  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990525042] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:46:12.982  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990525046] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:12.982  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:16.007  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990528071] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:16.017  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990528081] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:16.018  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:46:19.044  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990531108] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:19.047  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990531111] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:46:19.048  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:20.297  1028  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=899732805, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,06-22 07:46:20.307  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e3f5efc type 2 when 223202 android} when 223202
06-22 07:46:20.352  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,06-22 07:46:20.376  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=899732805 [*alarm*], flags=0x0,
,06-22 07:46:22.072  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990534136] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:22.075  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990534139] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:22.075  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:25.096  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990537159] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:25.106  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990537169] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:25.106  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:46:28.127  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990540191] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:28.140  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990540203] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:28.140  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:46:28.301  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{22d46985 type 2 when 242651 com.google.android.gms} when 242651
,06-22 07:46:28.360  1811  1811 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-22 07:46:28.367  2202  2202 I ConfigService: onCreate
06-22 07:46:28.368  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-22 07:46:28.371  1811  7104 I ConfigFetchService: running network task: configservice_periodic
06-22 07:46:28.374  1811  7104 I ConfigFetchService: launchTask
,06-22 07:46:28.383  2202  2202 I ConfigService: onBind returning update interface
06-22 07:46:28.386  1811  1811 I ConfigFetchService: service connected
,06-22 07:46:28.388  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,06-22 07:46:28.388  2202  2202 I ConfigService: onBind returning config service
06-22 07:46:28.391  1811  1811 I ConfigClient: service connected
06-22 07:46:28.441  1028  1569 V SIM_STK : Menu title from STK is T-Mobile
,06-22 07:46:28.457  1811  2392 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-22 07:46:28.463   313  7107 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-22 07:46:28.463   313  7107 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-22 07:46:28.463   313  7107 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-22 07:46:28.706  1811  2392 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-22 07:46:28.721  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
,06-22 07:46:28.724  1811  1811 I ConfigFetchService: stopping self
06-22 07:46:28.770  2202  2202 I ConfigService: onDestroy
,06-22 07:46:31.162  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990543225] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:31.165  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990543228] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:31.165  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:34.148  1596  1596 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-22 07:46:34.149  1596  1596 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 07:46:34.162  1028  1538 D WifiController: battery changed pluggedType: 2
,06-22 07:46:34.166  1935  2064 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:46:34.166  1935  2064 D LEDHandler: Battery Level Remaining: 100%
06-22 07:46:34.166  1935  2064 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
06-22 07:46:34.169  1596  1596 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
06-22 07:46:34.169  1596  1596 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:46:34.171  5996  6051 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:46:34.172  1596  1596 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:46:34.174  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:46:34.174  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:46:34.182  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990546246] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:46:34.187  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:1990546251] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:46:34.187  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:37.205  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1990549269] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:37.228  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:23] from screen [on:0 period:1990549292] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:46:37.228  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:40.246  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990552310] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:40.257  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990552321] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:40.257  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:46:43.280  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990555344] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:43.283  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990555347] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:46:43.283  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:46.307  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990558371] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:46.318  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990558381] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:46.319  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:46:49.341  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990561404] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:49.344  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990561408] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:46:49.344  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:52.369  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990564432] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:52.372  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990564436] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:46:52.372  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:55.399  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990567463] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:55.402  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990567466] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:55.402  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:46:58.428  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990570492] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:58.431  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990570495] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:46:58.431  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:00.054  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:47:00.054  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:47:00.054  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:47:00.055  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:47:00.069  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:47:00.070  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:47:00.072  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:47:00.074  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:47:01.455  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990573519] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:01.458  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990573522] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:01.469  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:04.490  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990576554] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:04.493  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990576557] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:04.494  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:07.517  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990579581] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:07.528  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990579592] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:07.528  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:47:10.549  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990582613] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:10.552  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1990582615] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:10.552  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:13.577  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990585641] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:13.588  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990585652] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:13.589  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:16.610  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990588673] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:16.613  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990588676] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:16.613  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:19.639  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990591703] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:19.642  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990591706] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:19.642  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:22.669  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990594733] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:22.672  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990594736] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:22.672  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:25.696  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990597760] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:25.711  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1990597774] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:25.711  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:28.729  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990600793] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:28.732  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990600796] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:28.732  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:31.756  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990603819] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:31.766  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990603829] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:31.766  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:47:34.786  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990606850] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:34.799  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990606862] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:34.799  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:37.820  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990609884] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:37.823  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990609887] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:37.823  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:40.844  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990612908] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:40.847  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990612911] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:40.847  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:43.873  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990615936] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:43.876  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990615940] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:43.876  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:46.900  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990618964] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:46.903  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990618967] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:46.904  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:49.931  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990621994] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,06-22 07:47:49.934  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990621997] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:47:49.934  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:52.960  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990625024] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:52.963  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990625027] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:52.963  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:55.985  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990628049] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:55.988  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990628052] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:55.995  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:47:59.016  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990631079] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:59.027  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990631091] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:47:59.028  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:48:00.053  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:48:00.054  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:48:00.054  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-22 07:48:00.054  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:48:00.071  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:48:00.071  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:48:00.073  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:48:00.075  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:48:00.300  1028  3471 I LocationManagerService: remove 2db799f6
,06-22 07:48:00.313  1028  3471 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
06-22 07:48:00.313  1028  3471 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-22 07:48:00.316  1028  3471 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-22 07:48:00.320  1028  3471 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-22 07:48:00.320  1028  3471 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-22 07:48:02.049  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990634113] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:02.052  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990634116] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:48:02.053  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:05.079  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990637143] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:05.082  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990637146] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:05.082  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:08.107  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990640171] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:08.118  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990640182] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:08.119  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:10.114  1028  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=899732805, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,06-22 07:48:10.170  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,06-22 07:48:10.209  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=899732805 [*alarm*], flags=0x0
,06-22 07:48:10.357  1028  1971 I art     : Explicit concurrent mark sweep GC freed 85287(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.358ms total 202.324ms
,06-22 07:48:11.140  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990643203] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:11.143  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990643207] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:11.143  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:14.165  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1990646228] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:14.175  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990646232] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:14.175  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:48:17.195  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990649259] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:17.208  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1990649272] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:17.208  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:20.230  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990652293] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:48:20.233  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990652297] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:20.233  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:23.260  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990655324] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:23.264  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990655328] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:48:23.264  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:26.291  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990658355] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:26.294  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990658358] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:48:26.295  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:28.767  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f967f2c type 2 when 363101 com.google.android.gms} when 363101
,06-22 07:48:28.814  1811  1811 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-22 07:48:28.820  2202  2202 I ConfigService: onCreate
06-22 07:48:28.821  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-22 07:48:28.822  1811  7130 I ConfigFetchService: running network task: configservice_periodic
06-22 07:48:28.824  1811  7130 I ConfigFetchService: launchTask
06-22 07:48:28.831  2202  2202 I ConfigService: onBind returning update interface
,06-22 07:48:28.835  1811  1811 I ConfigFetchService: service connected
06-22 07:48:28.836  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-22 07:48:28.836  2202  2202 I ConfigService: onBind returning config service
,06-22 07:48:28.837  1811  1811 I ConfigClient: service connected
06-22 07:48:28.913  1028  2026 V SIM_STK : Menu title from STK is T-Mobile
,06-22 07:48:28.931  1811  3806 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-22 07:48:28.936   313  7144 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-22 07:48:28.937   313  7144 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-22 07:48:28.937   313  7144 D libc-netbsd: res_queryN name = android.clients.google.com succeed
06-22 07:48:29.173  1811  3806 W ConfigFetchTask: bad response from server: 401 Unauthorized
06-22 07:48:29.175  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
06-22 07:48:29.178  1811  1811 I ConfigFetchService: stopping self
,06-22 07:48:29.226  2202  2202 I ConfigService: onDestroy
,06-22 07:48:29.322  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990661386] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:29.325  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990661389] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:48:29.325  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:32.336  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990664400] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:48:32.347  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990664411] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:48:32.347  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:35.369  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990667433] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:48:35.372  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990667436] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:35.372  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:38.399  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990670463] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:38.402  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990670466] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:38.402  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:41.431  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990673494] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:41.434  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990673497] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:48:41.434  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:44.460  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990676524] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:44.463  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990676527] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:44.464  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:47.486  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990679550] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:47.496  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990679560] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:47.496  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:50.517  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990682581] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:50.530  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1990682594] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:50.530  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:48:53.550  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990685614] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:53.553  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990685617] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:48:53.553  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:48:56.577  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990688640] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:56.587  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990688651] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:56.587  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:48:59.608  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990691671] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:59.621  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1990691685] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:48:59.622  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:49:00.055  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:49:00.056  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:49:00.056  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:49:00.056  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:49:00.072  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:49:00.072  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:49:00.074  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:49:00.076  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:49:02.644  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990694708] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:02.647  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990694711] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:02.647  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:05.668  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990697731] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:05.678  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990697742] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:05.679  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:08.703  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1990700767] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:08.721  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:18] from screen [on:0 period:1990700785] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:08.721  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:49:11.737  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990703801] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:11.749  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990703813] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:11.749  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:14.772  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990706835] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:49:14.775  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990706838] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:14.775  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:17.798  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990709861] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:17.808  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990709871] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:17.808  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:20.829  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990712893] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:49:20.832  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990712896] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:20.832  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:23.860  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990715924] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:23.863  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990715927] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:23.863  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:26.887  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990718951] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:26.897  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990718961] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:26.897  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:29.919  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990721983] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:49:29.922  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990721986] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:29.923  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:32.947  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990725011] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:32.957  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990725021] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:32.957  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:49:35.978  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990728041] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:35.990  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990728053] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:35.990  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:49:39.010  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990731074] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:39.013  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990731077] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:49:39.014  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:42.041  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990734105] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:42.044  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990734108] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:49:42.044  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:45.071  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990737134] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:45.074  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990737138] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:49:45.074  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:48.101  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990740165] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:48.104  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990740168] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:49:48.104  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:51.129  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990743193] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:51.132  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990743196] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:51.132  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:54.161  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990746224] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:54.163  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990746227] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:54.164  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:49:57.183  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990749247] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:49:57.186  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990749250] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:49:57.187  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:00.055  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:50:00.056  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:50:00.056  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:50:00.056  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:50:00.071  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:50:00.072  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:50:00.074  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:50:00.076  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:50:00.211  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990752275] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:00.214  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990752278] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-22 07:50:00.214  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:03.238  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990755301] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:03.248  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990755311] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:03.248  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:06.269  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990758333] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:06.272  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990758336] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:06.272  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:09.295  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990761359] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:09.304  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990761362] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:09.306  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:50:12.326  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990764390] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:12.338  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990764402] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:12.339  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:50:15.360  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990767424] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:15.363  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990767427] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:15.363  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:18.384  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990770448] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:18.388  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990770451] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:18.388  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:21.412  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990773476] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:21.415  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990773479] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:21.416  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:24.439  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990776503] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:24.442  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990776506] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:24.442  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:27.469  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990779532] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:27.472  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990779535] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:27.472  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:30.496  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990782559] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:30.506  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990782570] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:30.506  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:50:33.527  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990785591] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:33.539  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990785602] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:33.539  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:50:36.561  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990788624] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:36.564  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990788628] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:36.564  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:39.587  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990791651] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:39.598  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990791662] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:39.599  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:50:42.629  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990794693] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:42.632  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990794696] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:42.632  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:45.660  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990797724] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:45.663  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990797727] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:45.663  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:48.692  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1990800756] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:48.695  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990800759] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:48.695  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:51.721  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990803785] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:51.724  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990803788] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:51.725  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:54.747  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990806811] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:54.757  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990806821] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:54.758  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:50:57.782  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990809846] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:50:57.785  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990809849] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:50:57.785  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:00.054  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:51:00.054  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:51:00.054  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:51:00.055  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:51:00.070  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:51:00.070  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:51:00.072  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:51:00.079  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:51:00.809  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1990812873] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:00.812  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990812876] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:00.812  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:03.835  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1990815899] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:03.836  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1990815900] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:03.836  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:06.854  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990818918] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:06.857  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990818921] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:06.858  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:09.883  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1990821947] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:09.886  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990821950] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:09.886  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:12.906  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990824970] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:12.916  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990824980] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:12.917  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:51:15.936  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990828000] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:15.949  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990828012] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:15.949  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:18.970  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990831033] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:18.973  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990831036] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:18.973  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:22.000  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990834064] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:22.003  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990834067] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:22.003  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:25.030  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990837094] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:25.033  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990837097] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:25.034  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:28.057  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990840120] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:28.067  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990840131] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:28.067  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:51:31.088  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990843151] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:31.101  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1990843165] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:31.101  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:34.122  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990846186] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:34.125  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990846189] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:34.125  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:37.146  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990849209] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:37.156  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990849219] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:37.156  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:51:40.176  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990852240] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:40.188  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990852251] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:40.188  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:43.209  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990855273] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:43.212  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990855276] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:43.212  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:46.236  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990858300] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:46.246  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990858310] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:46.246  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:51:49.267  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990861331] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:49.280  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1990861344] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:49.280  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:51:52.302  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990864365] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:52.305  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990864368] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:52.305  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:55.329  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990867392] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:55.332  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990867396] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:55.332  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:51:58.359  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990870422] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:51:58.362  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990870426] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:51:58.362  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:00.059  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:52:00.059  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:52:00.059  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:52:00.060  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:52:00.073  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:52:00.073  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:52:00.076  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:52:00.078  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:52:01.388  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990873451] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:01.399  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990873462] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:01.399  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:04.419  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990876482] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:52:04.422  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990876486] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:52:04.422  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:07.447  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990879511] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:07.457  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990879521] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:52:07.457  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:52:10.480  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990882543] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:10.495  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:1990882559] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:10.496  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:52:13.514  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990885577] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:13.517  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990885580] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:52:13.517  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:16.542  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990888606] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:16.546  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990888609] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:16.546  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:19.566  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990891630] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:19.577  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990891640] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:19.577  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:52:22.596  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990894660] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:22.607  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990894671] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:22.608  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:25.629  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990897693] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:52:25.632  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990897696] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:25.632  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:28.655  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990900719] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:28.666  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990900729] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:28.666  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:52:29.196  1028  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=899732805, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,06-22 07:52:29.221  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{11ab95cf type 2 when 603552 com.google.android.gms} when 603552
,06-22 07:52:29.289  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,06-22 07:52:29.313  1811  1811 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-22 07:52:29.320  2202  2202 I ConfigService: onCreate
06-22 07:52:29.320  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-22 07:52:29.322  1811  7154 I ConfigFetchService: running network task: configservice_periodic
06-22 07:52:29.340  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=899732805 [*alarm*], flags=0x0
,06-22 07:52:29.344  1811  7154 I ConfigFetchService: launchTask
,06-22 07:52:29.345  2202  2202 I ConfigService: onBind returning update interface
06-22 07:52:29.346  1811  1811 I ConfigFetchService: service connected
06-22 07:52:29.346  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-22 07:52:29.346  2202  2202 I ConfigService: onBind returning config service
06-22 07:52:29.348  1811  1811 I ConfigClient: service connected
06-22 07:52:29.420  1028  1569 V SIM_STK : Menu title from STK is T-Mobile
,06-22 07:52:29.444  1811  5541 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-22 07:52:29.451   313  7174 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-22 07:52:29.452   313  7174 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-22 07:52:29.493   313  7174 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-22 07:52:29.737  1811  5541 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-22 07:52:29.741  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
06-22 07:52:29.744  1811  1811 I ConfigFetchService: stopping self
06-22 07:52:29.784  2202  2202 I ConfigService: onDestroy
,06-22 07:52:31.687  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990903751] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:31.697  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990903761] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:31.697  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:34.718  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=8.5, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990906782] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-22 07:52:34.721  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=8.5, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990906785] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 07:52:34.721  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:37.745  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990909808] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:37.748  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990909812] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:37.754  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:52:40.775  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1990912838] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:52:40.778  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990912842] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:40.778  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:43.807  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990915871] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:43.819  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1990915882] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:43.819  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:52:46.839  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990918903] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:46.853  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1990918916] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:46.853  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:49.874  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990921937] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:52:49.877  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990921941] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:49.877  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:52:52.896  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990924959] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:52.906  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990924969] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:52.906  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:52:55.926  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990927990] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:55.938  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990928002] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:55.939  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:52:58.957  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990931021] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:58.969  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990931033] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:52:58.970  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:53:00.053  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:53:00.053  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:53:00.053  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:53:00.054  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:53:00.070  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:53:00.070  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:53:00.073  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:53:00.075  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:53:01.992  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990934056] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:53:01.995  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990934059] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:01.995  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:05.019  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990937083] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:05.022  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990937086] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:05.022  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:08.050  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990940114] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:08.053  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990940117] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:53:08.054  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:10.120  1028  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=899732805, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,06-22 07:53:10.166  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,06-22 07:53:10.198  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=899732805 [*alarm*], flags=0x0
,06-22 07:53:11.072  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990943135] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:11.075  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990943139] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:11.075  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:14.096  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990946159] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:14.106  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990946169] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:14.106  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:53:17.128  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990949191] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:17.140  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1990949203] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:17.142  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:20.162  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990952225] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:53:20.165  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990952228] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:20.165  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:23.187  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990955251] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:23.198  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990955261] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:23.198  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:53:26.216  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990958280] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:26.229  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1990958293] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:26.229  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:53:29.251  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990961315] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:53:29.254  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990961318] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:29.255  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:32.276  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1990964340] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:32.286  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990964350] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:32.286  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:35.299  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990967362] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:35.302  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990967366] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:53:35.302  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:38.326  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1990970389] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:38.336  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990970399] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:38.336  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:53:41.355  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1990973418] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:41.358  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990973422] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:41.367  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:44.389  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990976453] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:44.392  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1990976455] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:53:44.392  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:47.417  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990979481] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:47.427  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990979491] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:47.428  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:53:50.451  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990982514] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:50.454  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1990982518] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:53:50.454  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:53.478  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990985541] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:53.487  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1990985551] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:53.487  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:56.509  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990988573] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:53:56.512  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990988576] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:56.512  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:53:59.536  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1990991600] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:59.546  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1990991609] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:53:59.546  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:54:00.055  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:54:00.056  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:54:00.056  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:54:00.056  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:54:00.072  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:54:00.072  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:54:00.074  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:54:00.076  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:54:02.566  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990994630] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:02.580  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1990994644] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:02.581  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:05.602  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1990997666] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:54:05.605  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990997669] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:05.606  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:08.628  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991000692] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:08.637  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991000701] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:54:08.638  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:54:11.659  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991003722] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:54:11.662  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991003726] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:54:11.662  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:14.690  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991006754] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:14.693  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991006757] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:14.693  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:17.719  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991009783] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:17.722  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991009786] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:17.723  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:20.750  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991012814] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:20.753  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991012817] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:20.753  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:23.777  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991015841] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:23.786  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991015850] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:23.787  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:54:26.807  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991018871] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:26.820  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991018884] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:26.820  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:29.842  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991021905] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:54:29.845  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991021908] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:29.845  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:32.868  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991024931] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:32.878  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991024942] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:32.879  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:54:35.909  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3012] from screen [on:0 period:1991027973] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:35.921  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991027984] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:35.921  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:54:38.116  1028  1569 I ActivityManager: Killing 6652:com.android.calendar/u0a13 (adj 15): empty #17
,06-22 07:54:38.183  1028  1724 W libprocessgroup: failed to open /acct/uid_10013/pid_6652/cgroup.procs: No such file or directory
,06-22 07:54:38.940  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991031004] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:38.943  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991031007] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:38.943  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:41.964  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991034027] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:41.967  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991034031] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:41.967  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:44.992  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991037056] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:44.994  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1991037058] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:44.994  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:48.016  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991040080] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:48.027  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991040091] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:48.028  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:54:51.047  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991043110] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:51.059  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991043123] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:51.059  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:54.081  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991046145] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:54:54.085  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991046148] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:54:54.085  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:54:57.107  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991049171] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:54:57.118  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991049181] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:54:57.118  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:55:00.073  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:55:00.073  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:55:00.073  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:55:00.073  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:55:00.079  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:55:00.079  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:55:00.080  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:55:00.081  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:55:00.139  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991052203] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:00.141  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1991052205] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:00.141  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:03.153  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991055217] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:03.156  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991055220] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:03.157  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:06.182  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991058246] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:06.185  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991058249] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:06.185  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:09.207  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991061271] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:09.217  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991061280] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:09.217  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:55:12.237  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991064301] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:12.249  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991064313] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:12.250  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:55:15.270  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991067334] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:15.273  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991067337] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:15.273  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:18.296  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991070360] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:18.306  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991070369] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:18.306  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:55:21.327  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991073391] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:21.339  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991073403] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:21.339  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:24.362  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991076425] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:24.365  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991076428] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:24.365  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:27.387  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991079451] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:27.397  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991079461] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:27.398  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:30.421  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991082484] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:30.424  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991082487] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:30.424  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:33.446  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991085510] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:33.460  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1991085524] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:33.460  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:36.481  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991088545] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:36.485  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991088548] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:36.485  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:39.507  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991091570] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:39.516  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991091580] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:39.516  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:55:42.537  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991094600] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:42.549  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991094613] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:42.550  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:45.572  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991097636] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:45.575  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991097639] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:45.575  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:48.595  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991100658] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:48.598  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991100662] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:48.605  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:51.626  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991103689] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:51.637  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991103701] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:51.637  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:54.659  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991106722] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:54.662  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991106725] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:55:54.662  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:55:57.687  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991109751] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:57.698  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991109761] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:55:57.698  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:56:00.042  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:56:00.042  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:56:00.042  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:56:00.043  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:56:00.057  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:56:00.058  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:56:00.061  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:56:00.063  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:56:00.720  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991112784] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:00.723  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991112787] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:00.723  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:03.750  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991115814] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:03.753  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991115817] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:03.754  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:06.780  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991118844] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:06.783  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991118847] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:06.784  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:09.807  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991121870] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:09.815  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:1991121878] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:09.815  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:12.832  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991124895] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:12.835  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991124898] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:12.835  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:15.855  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991127918] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:15.858  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991127921] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:15.858  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:18.882  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991130945] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:18.885  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991130948] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:18.885  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:21.909  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991133973] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:21.912  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991133976] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:21.912  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:24.939  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991137003] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:24.942  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991137006] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:24.942  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:27.967  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991140031] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:27.972  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:1991140036] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:27.972  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:30.990  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1991143054] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:30.993  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991143057] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:30.993  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:34.017  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991146080] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:34.027  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991146091] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:34.027  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:37.049  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991149112] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:37.052  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991149116] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:37.052  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:40.080  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991152143] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:40.083  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991152147] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:40.083  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:43.109  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991155173] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:43.112  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991155176] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:43.112  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:46.137  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991158201] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:46.147  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991158211] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:46.148  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:56:49.169  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991161233] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:49.172  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991161236] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:49.172  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:52.198  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991164262] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:52.209  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991164272] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:52.209  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:56:55.230  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991167294] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:55.233  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991167297] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:56:55.233  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:56:58.260  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991170324] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:58.263  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991170327] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:56:58.264  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:00.055  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:57:00.055  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:57:00.056  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-22 07:57:00.056  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:57:00.071  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:57:00.071  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:57:00.073  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:57:00.075  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:57:01.287  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991173351] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:01.301  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1991173365] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:01.302  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:57:04.322  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991176385] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:57:04.325  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991176388] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:57:04.325  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:07.351  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991179415] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:07.354  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991179418] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:07.354  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:10.378  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991182441] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:10.387  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991182451] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:10.387  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:57:13.406  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991185470] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:13.418  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991185481] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:13.418  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:57:16.440  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991188504] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:16.443  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991188507] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:57:16.443  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:19.470  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991191534] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:19.473  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991191537] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:57:19.473  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:22.499  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991194563] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:22.503  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991194566] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:22.503  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:25.528  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991197592] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:25.532  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991197595] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:57:25.532  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:28.559  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991200623] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:28.562  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991200626] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:28.562  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:31.590  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991203654] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:31.593  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991203657] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:31.593  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:34.616  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991206680] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:34.627  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991206690] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:34.627  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:57:37.648  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991209712] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:37.660  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991209724] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:37.660  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:57:40.682  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991212745] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:40.685  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991212749] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:57:40.685  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:43.710  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991215774] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:43.713  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991215777] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:43.714  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:46.740  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991218804] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:46.743  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991218807] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:46.744  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:49.782  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991221845] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:49.785  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991221849] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:57:49.785  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:52.811  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991224874] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:52.814  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991224878] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:52.814  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:55.835  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991227899] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:55.845  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991227908] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:55.845  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:57:58.862  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991230926] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:57:58.865  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991230929] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:57:58.866  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:00.054  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:58:00.054  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:58:00.055  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:58:00.055  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:58:00.069  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:58:00.070  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:58:00.072  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:58:00.074  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:58:01.889  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991233953] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:01.892  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991233956] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-22 07:58:01.893  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:04.915  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991236978] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:04.918  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991236982] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:04.924  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:58:07.945  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991240009] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:07.970  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:25] from screen [on:0 period:1991240034] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:07.970  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:10.987  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991243051] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:10.997  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991243061] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:10.998  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:14.020  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991246084] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:14.023  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991246087] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:14.024  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:17.051  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991249115] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:17.054  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991249118] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:17.054  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:20.079  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991252143] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:20.083  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991252146] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:20.083  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:23.108  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991255171] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:23.118  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991255182] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:23.119  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:26.139  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991258203] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:26.142  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991258206] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:26.143  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:29.169  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991261233] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:29.172  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991261236] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:29.172  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:32.195  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991264259] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:32.205  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991264268] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:32.206  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:58:35.225  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991267288] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:35.236  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991267292] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:35.236  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:58:38.258  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991270322] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:38.261  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991270325] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:38.262  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:41.287  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991273351] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:41.297  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991273361] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:41.297  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:58:44.313  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991276377] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:44.316  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991276380] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:44.316  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:47.339  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991279403] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:47.343  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991279406] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:47.343  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:50.369  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991282433] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:50.372  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991282436] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:50.372  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:53.395  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991285459] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:53.398  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991285462] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:53.404  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:56.423  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991288486] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:58:56.426  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991288490] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:56.426  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:58:59.452  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991291516] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:59.455  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991291519] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:58:59.455  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:00.061  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 07:59:00.062  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:59:00.062  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 07:59:00.062  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:59:00.076  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 07:59:00.076  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:59:00.079  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:59:00.085  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:59:02.479  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991294542] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:02.482  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991294546] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:02.482  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:05.508  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991297571] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:05.517  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991297581] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:05.517  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:08.538  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991300602] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:59:08.542  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991300605] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:08.542  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:11.565  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991303629] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:11.576  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991303639] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:11.576  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:14.597  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991306661] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:14.612  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1991306675] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:14.612  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:17.632  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991309696] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:59:17.635  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991309699] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:17.636  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:20.655  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991312719] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:20.664  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:1991312727] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:20.665  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:59:23.685  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991315748] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:23.696  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991315752] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:23.696  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:59:24.633  1028  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=899732805, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,06-22 07:59:24.654  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{304616de type 2 when 1018990 com.android.bluetooth} when 1018990
,06-22 07:59:24.661  5996  6111 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-22 07:59:24.661  5996  6111 W bt-smp  : Plain text(LSB ~ MSB) = 62 f4 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-22 07:59:24.661  5996  6111 W bt-smp  : Encrypted text(LSB ~ MSB) = fa 12 ed 68 f4 cc 67 5e f8 a0 d8 36 46 2a 25 bb 
06-22 07:59:24.661  5996  6111 W bt-btm  : Stopping oneshot timer
06-22 07:59:24.690  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,06-22 07:59:24.719  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=899732805 [*alarm*], flags=0x0
,06-22 07:59:26.719  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991318783] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:26.722  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991318786] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:26.722  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:29.744  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1991321808] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:59:29.745  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1991321809] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:59:29.745  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:32.765  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991324829] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:32.776  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991324839] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:32.776  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:59:35.796  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991327859] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:35.807  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991327871] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:35.807  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:59:38.827  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991330891] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:38.839  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991330903] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:38.839  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 07:59:41.861  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991333925] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:41.865  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991333928] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:59:41.865  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:44.892  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991336955] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:44.895  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991336959] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:59:44.895  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:47.922  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991339985] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:47.925  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991339988] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:59:47.925  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:50.951  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991343015] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:50.955  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991343018] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:59:50.955  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:53.980  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991346044] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:53.983  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991346047] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:53.983  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 07:59:57.011  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991349074] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:57.014  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991349077] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:59:57.014  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:00.037  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991352101] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:00.047  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991352111] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:00.047  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:00:00.058  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 08:00:00.058  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 08:00:00.066  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-22 08:00:00.068  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
06-22 08:00:00.076  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:00:00.076  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:00:00.084  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 08:00:00.092  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 08:00:01.340  1028  1374 D PowerManagerServiceEx: acquireWakeLockInternal: lock=899732805, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
,06-22 08:00:01.356  6587  6587 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-22 08:00:01.361  6587  6587 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@369b843a
06-22 08:00:01.386  2595  2595 D [Concierge]Service: onStartCommand(). Type : 9
,06-22 08:00:01.414  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=899732805 [*alarm*], flags=0x0
,06-22 08:00:03.088  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2997] from screen [on:0 period:1991355152] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:03.092  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991355155] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:03.092  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:06.117  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991358180] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:06.126  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991358190] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:06.126  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:09.144  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991361207] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:00:09.147  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991361211] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:09.147  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:12.172  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991364236] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:12.175  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991364239] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:12.175  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:15.196  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991367259] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:15.206  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991367270] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:15.206  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:00:18.232  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991370296] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:18.235  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991370299] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:00:18.235  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:21.259  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991373322] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:21.262  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991373326] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:21.262  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:24.287  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991376351] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:24.298  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991376361] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:24.298  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:27.323  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991379387] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:27.327  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991379390] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:27.327  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:29.762  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{368390bf type 2 when 1084113 com.google.android.gms} when 1084113
,06-22 08:00:29.826  1811  1811 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-22 08:00:29.833  2202  2202 I ConfigService: onCreate
06-22 08:00:29.834  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-22 08:00:29.837  1811  7196 I ConfigFetchService: running network task: configservice_periodic
06-22 08:00:29.841  1811  7196 I ConfigFetchService: launchTask
,06-22 08:00:29.851  2202  2202 I ConfigService: onBind returning update interface
06-22 08:00:29.853  1811  1811 I ConfigFetchService: service connected
,06-22 08:00:29.855  2202  2202 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-22 08:00:29.855  2202  2202 I ConfigService: onBind returning config service
06-22 08:00:29.857  1811  1811 I ConfigClient: service connected
06-22 08:00:29.911  1028  1971 V SIM_STK : Menu title from STK is T-Mobile
,06-22 08:00:29.923  1811  6452 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-22 08:00:29.929   313  7199 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-22 08:00:29.929   313  7199 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,06-22 08:00:29.973   313  7199 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-22 08:00:30.293  1811  6452 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-22 08:00:30.304  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
06-22 08:00:30.307  1811  1811 I ConfigFetchService: stopping self
06-22 08:00:30.345  1028  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d13f38e type 2 when 1052205 com.google.android.gms} when 1052205
06-22 08:00:30.345  1028  1374 V AlarmManager: RTC_WAKEUP set : Alarm{38827af type 0 when 1466575200001 com.lge.ia.task.informant} when 1466575200001
,06-22 08:00:30.350  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991382414] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:00:30.351  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1991382414] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:00:30.351  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:00:30.357  2202  2202 I ConfigService: onDestroy
,06-22 08:00:30.375  2729  2729 D LIA_Informant_FavoriteNumScheduler: FavoriteNumScheduler onReceive! request messageGenerator
06-22 08:00:30.376  2729  2729 D LIA_Informant_FavoriteNumScheduler: curentDate : 20160622
06-22 08:00:30.384  2729  4206 D LIA_Informant_FavoriteNumScheduler: request
06-22 08:00:30.384  2729  4206 D LIA_Informant_FavoriteNumScheduler: generateCards
06-22 08:00:30.384  2729  4206 D LIA_Informant_FavoriteNumScheduler: connectIntimacyEngine
,06-22 08:00:30.436  1028  1044 V SIM_STK : Menu title from STK is T-Mobile
,06-22 08:00:30.450  2202  7053 D GCM     : Message class com.google.e.a.a.h
,06-22 08:00:30.510  1028  1952 V SIM_STK : Menu title from STK is T-Mobile
,06-22 08:00:30.521  2729  4206 I LIA_Informant_LGIntelligentAgent: [LG Intelligent Agent Info] ----------------------
,06-22 08:00:30.521  2729  4206 I LIA_Informant_LGIntelligentAgent:  - LIA SDK Version Name : 0.8.20
06-22 08:00:30.521  2729  4206 I LIA_Informant_LGIntelligentAgent:  - LIA SDK Release Date : 2014.09.05
06-22 08:00:30.521  2729  4206 I LIA_Informant_LGIntelligentAgent:  - LIA Service Version Name : 0.8.20.2
06-22 08:00:30.521  2729  4206 I LIA_Informant_LGIntelligentAgent:  - This APK(com.lge.ia.task.informant) Version Name : 4.21.14
06-22 08:00:30.521  2729  4206 I LIA_Informant_LGIntelligentAgent: --------------------------------------------------
06-22 08:00:30.523  2729  4206 I LIA_Informant_LGIntelligentAgent: connectLIAService - task name : S4URecommender
06-22 08:00:30.523  2729  4206 I LIA_Informant_LGIntelligentAgent: tryConnecting ...
06-22 08:00:30.523  2729  4206 I LIA_Informant_LIATaskLoader: getTaskSdkClassName : com.lge.ia.LIAS4URecommender
06-22 08:00:30.523  1990  1990 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia }
06-22 08:00:30.524  2729  4206 D LIA_Informant_LIATaskLoader: classLoad - TargetClass : com.lge.ia.LIAS4URecommender
,06-22 08:00:30.527  2729  4206 I LIA_Informant_LIATaskLoader: createLIAService - Success
,06-22 08:00:30.528  2729  4206 I LIA_Informant_ConnectionProxyHandler: open() : S4URecommender opened.
06-22 08:00:30.528  2729  4206 I LIA_Informant_LGIntelligentAgent: tryConnecting : map put - 1
06-22 08:00:30.528  2729  4206 I LIA_Informant_ConnectionProxyHandler: tryConnecting...
06-22 08:00:30.530  2729  4206 I LIA_Informant_ConnectionProxy: startService(com.lge.ia.task.s4urecommender) : Success
06-22 08:00:30.530  2729  2729 D LIA_S4URecommender_LIARemoteService: onStartCommand() : LIARemoteService started! - (Id :4), Intent { act=com.lge.ia.task.s4urecommender pkg=com.lge.ia.task.s4urecommender (has extras) }
06-22 08:00:30.532  2729  4206 I LIA_Informant_ConnectionProxy: bindService(com.lge.ia.task.s4urecommender) : Success
06-22 08:00:30.532  2729  2729 D LIA_Informant_ConnectionProxy: onServiceConnected() : com.lge.ia.task.s4urecommender
06-22 08:00:30.532  2729  2729 D LIA_S4URecommender_LIARemoteManager: getProperties()
06-22 08:00:30.532  2729  2729 D LIA_S4URecommender_TaskLauncher: getTaskPropertyList() - main launcher : false
06-22 08:00:30.533  2729  2729 I LIA_Informant_ConnectionProxy: Checking activation option of S4URecommender
06-22 08:00:30.533  2729  2729 I LIA_Informant_ConnectionProxy: Task Property : S4URecommender, true
06-22 08:00:30.533  2729  2729 I LIA_Informant_ConnectionProxy: Task activation property : S4URecommender, true
06-22 08:00:30.533  2729  2729 I LIA_Informant_ConnectionProxyHandler: ConnectionProxyListener - onConnected : 
06-22 08:00:30.533  2729  2729 V LIA_Informant_ConnectionProxyHandler: S4URecommender Task Property: Activation:true, AutoExecution:true
06-22 08:00:30.533  2729  2729 D LIA_Informant_ConnectionProxy: getTaskConnector(S4URecommender / com.lge.ia.task.s4urecommender) : Thread(1)
06-22 08:00:30.533  2729  2729 D LIA_S4URecommender_LIARemoteManager: getTask() : S4URecommender
06-22 08:00:30.533  2729  2729 D LIA_S4URecommender_TaskLauncher: getTask() : S4URecommender (main launcher : false)
06-22 08:00:30.534  2729  2729 I LIA_S4URecommender_TaskContext: getNewAppSession() : App session is added - com.lge.ia.manager.session.AppSession@3310d3fe
06-22 08:00:30.534  2729  2729 I LIA_Informant_ConnectionProxyHandler: setTaskConnectorIntoTask - Success
06-22 08:00:30.534  2729  2729 I LIA_Informant_ConnectionProxyHandler: stopTimeoutTimer
06-22 08:00:30.535  2729  7216 I LIA_Informant_LGIntelligentAgent: tryConnecting : onTryConnectionSuccess - com.lge.ia.LIAS4URecommender@1335d75f
06-22 08:00:30.535  2729  7216 I LIA_Informant_LGIntelligentAgent: tryConnecting onTryConnectionSuccess : map remove - 1
06-22 08:00:30.536  2729  7216 D LIA_Informant_FavoriteNumScheduler: IntimacyEngine onConnected!
06-22 08:00:30.536  2729  4206 D LIA_Informant_LIAS4URecommender: [youngjung][getFavoriteReminders] processing....
06-22 08:00:30.537  2729  4206 D LIA_S4URecommender_TaskSession: sendMessageSync() - enable state : true, thread id : 225, thread name : pool-3-thread-1
06-22 08:00:30.537  2729  4217 D LIA_S4URecommender_S4URecommenderTask: process entered : 112
06-22 08:00:30.570  2729  4206 D LIA_Informant_FavoriteNumScheduler: FavoriteRemindersResult size = 0
06-22 08:00:30.571  2729  4206 D LIA_S4URecommender_AppSession: Notifying to appsession that a session is finished.
06-22 08:00:30.572  2729  4206 I LIA_S4URecommender_TaskContext: onAppSessionFinished : S4URecommender(size: 2)
06-22 08:00:30.572  2729  4206 I LIA_S4URecommender_TaskContext: Current app session(s) : 
06-22 08:00:30.573  2729  4206 I LIA_S4URecommender_TaskContext: com.lge.ia.manager.session.AppSession@187a08bd
06-22 08:00:30.573  2729  4206 D LIA_Informant_ConnectionProxy: tryUnbindService(com.lge.ia.task.s4urecommender) - Thread(225)
,06-22 08:00:30.578  2729  4206 I LIA_Informant_ConnectionProxyHandler: isContainAutoExecutionTask() : true, S4URecommender
06-22 08:00:30.579  2729  4206 D LIA_Informant_ConnectionProxyHandler: close() : AutoExecution Or Activation task in remote service. Not try to stop the service.
06-22 08:00:30.579  2729  4206 I LIA_Informant_ConnectionProxyHandler: close() : S4URecommender closed.
06-22 08:00:30.579  2729  4206 D InformantAlarmUtil: getFirstAlarm
06-22 08:00:30.580  2729  4206 D LIA_Informant_InformantCalendarUtil: getDay()
06-22 08:00:30.580  2729  4206 D InformantAlarmUtil: getAlarmListOfDay: day = 5
06-22 08:00:30.606  2729  4206 D LIA_Informant_FavoriteNumScheduler: setAlarm
,06-22 08:00:30.608  2729  4206 D LIA_Informant_FavoriteNumScheduler: Date : Wed Jun 22 08:00:00 GMT+02:00 2016
,06-22 08:00:33.359  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991385422] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 08:00:33.362  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991385426] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-22 08:00:33.362  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:36.387  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991388451] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:36.397  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991388461] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:36.398  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:39.417  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991391481] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:39.430  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991391494] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:39.430  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:42.451  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991394515] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:42.454  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991394518] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:42.454  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:45.480  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991397544] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:45.483  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991397547] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:45.484  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:48.512  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991400576] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:48.515  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991400579] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:48.515  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:51.537  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991403601] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:51.546  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991403610] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:51.547  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:54.566  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991406630] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:54.579  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991406643] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:54.580  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:00:57.601  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991409665] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:57.615  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1991409679] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:00:57.615  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:01:00.067  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:01:00.067  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 08:01:00.068  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-22 08:01:00.077  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:01:00.085  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:01:00.085  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:01:00.087  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:01:00.092  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 08:01:00.632  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991412696] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:00.635  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991412699] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:00.635  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:03.661  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991415725] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:03.664  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991415728] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:03.664  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:06.687  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991418750] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:06.697  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991418760] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:06.697  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:01:09.717  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991421781] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:09.729  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991421793] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:09.730  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:12.752  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991424815] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:12.755  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991424818] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:12.755  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:15.779  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991427843] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:15.782  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991427846] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:15.783  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:18.809  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991430873] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:18.812  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991430876] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:18.812  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:21.839  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991433902] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:21.842  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991433905] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:21.842  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:24.872  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991436936] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:24.875  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991436939] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:24.875  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:27.899  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991439963] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:27.902  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991439966] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:27.903  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:30.926  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991442989] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:30.935  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991442999] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:30.936  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:01:33.957  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991446021] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:33.969  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991446033] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:33.970  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:01:36.991  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991449055] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:36.995  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991449058] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:36.995  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:40.020  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991452084] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:40.024  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991452087] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:40.024  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:43.051  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991455115] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:43.054  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991455118] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:43.054  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:46.078  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991458141] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:46.086  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991458150] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:46.086  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:01:49.106  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991461170] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:49.119  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991461182] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:49.119  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:01:52.137  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991464201] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:52.148  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991464212] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:52.148  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:01:55.171  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991467235] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:55.174  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991467238] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:55.174  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:01:58.204  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991470268] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:01:58.207  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991470271] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:01:58.207  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:00.059  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 08:02:00.059  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:02:00.059  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-22 08:02:00.060  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:02:00.074  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:02:00.074  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:02:00.076  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:02:00.080  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 08:02:01.232  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991473296] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:01.235  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991473299] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:01.236  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:04.259  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991476323] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:04.262  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991476326] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:04.262  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:07.289  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991479353] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:07.292  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991479356] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:07.292  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:10.319  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991482383] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:10.322  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991482386] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:10.322  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:13.346  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991485410] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:13.356  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991485420] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:13.356  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:02:16.376  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991488440] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:16.388  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991488452] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:16.388  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:19.411  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991491474] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:19.414  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991491477] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:19.414  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:22.441  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991494505] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:22.444  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991494508] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:22.445  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:25.466  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991497530] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:25.476  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991497540] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:25.477  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:02:28.497  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991500561] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:28.510  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991500574] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:28.510  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:02:31.532  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991503596] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:31.535  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991503599] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:31.535  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:34.562  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991506626] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:34.565  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991506629] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:34.565  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:37.589  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991509653] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:37.592  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991509656] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:37.592  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:40.617  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991512681] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:40.627  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991512691] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:40.627  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:02:43.647  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991515710] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:43.660  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1991515724] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:43.660  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:02:45.704  1028  1085 I UsageStatsService: User[0] Flushing usage stats to disk
,06-22 08:02:46.681  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991518745] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:46.684  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991518748] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:46.684  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:49.712  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991521775] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:49.715  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991521779] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:49.715  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:52.736  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991524800] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:52.748  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991524811] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:52.748  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:55.772  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991527836] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:02:55.775  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991527839] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:55.775  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:02:58.802  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991530866] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:58.805  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991530869] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:02:58.805  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:00.054  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 08:03:00.054  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 08:03:00.055  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 08:03:00.055  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:03:00.069  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 08:03:00.069  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:03:00.072  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:03:00.074  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 08:03:01.826  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991533889] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:01.839  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1991533903] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:01.839  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:03:04.861  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991536925] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:03:04.865  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991536928] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:04.865  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:07.884  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991539948] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:07.888  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991539951] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:07.895  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:10.914  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991542978] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:10.917  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991542981] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:03:10.918  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:13.946  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991546010] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:13.957  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991546021] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:13.957  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:03:16.975  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991549038] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:16.978  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991549041] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:16.987  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:20.008  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991552071] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:20.020  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991552083] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:20.020  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:23.042  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991555106] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:03:23.045  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991555109] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:23.045  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:26.069  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991558132] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:26.072  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991558135] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:26.072  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:29.092  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991561156] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:29.095  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991561159] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:29.095  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:32.123  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991564187] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:32.126  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991564190] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:03:32.126  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:35.152  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991567216] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:35.155  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991567219] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:03:35.155  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:38.182  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991570246] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:38.185  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991570249] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:38.185  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:41.208  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991573272] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:41.217  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991573281] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:41.217  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:03:44.237  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991576301] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:44.250  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991576313] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:44.250  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:47.272  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991579336] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:03:47.275  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991579339] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:47.275  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:50.302  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991582365] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:50.305  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991582369] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:50.305  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:53.325  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991585389] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:53.336  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991585399] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:53.336  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:03:56.356  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991588420] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:56.368  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991588432] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:56.368  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:03:59.391  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991591454] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:03:59.394  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991591458] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:03:59.394  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:00.100  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:04:00.100  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:04:00.101  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 08:04:00.101  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:04:00.106  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 08:04:00.106  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 08:04:00.107  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:04:00.108  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 08:04:02.421  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991594485] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:02.424  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991594488] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:02.424  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:05.448  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991597511] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:05.458  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991597521] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:05.458  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:08.480  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991600544] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:08.483  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991600547] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:08.483  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:11.504  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991603568] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:11.507  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991603571] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:11.507  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:14.531  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991606595] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:14.534  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991606598] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:14.535  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:17.557  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991609621] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:17.567  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991609631] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:17.567  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:20.589  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991612652] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:20.592  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991612656] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:20.592  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:23.616  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991615680] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:23.626  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991615690] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:23.627  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:26.648  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991618712] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:26.651  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991618715] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:26.652  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:29.679  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991621743] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:29.682  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991621746] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:29.682  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:32.704  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991624768] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:32.707  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991624771] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:32.707  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:35.732  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991627796] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:35.735  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991627799] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:35.735  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:38.757  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991630820] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:38.767  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991630831] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:38.767  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:04:41.787  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991633851] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:41.798  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991633862] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:41.798  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:44.819  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991636882] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:44.822  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991636886] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:44.822  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:47.844  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991639908] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:47.847  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991639911] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:47.847  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:50.873  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991642936] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:50.876  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991642939] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:50.876  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:53.901  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991645965] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:53.904  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991645968] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:04:53.904  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:56.930  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991648994] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:56.933  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991648997] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:56.934  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:04:59.963  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991652027] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:59.966  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991652030] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:04:59.966  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:00.042  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 08:05:00.042  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:05:00.042  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 08:05:00.043  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:05:00.055  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 08:05:00.056  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:05:00.058  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:05:00.062  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 08:05:02.986  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991655050] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:02.996  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991655060] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:02.997  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:05:06.017  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991658081] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:06.030  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991658094] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:06.030  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:09.052  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991661116] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:05:09.056  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991661119] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:09.056  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:12.080  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991664144] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:12.083  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991664147] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:05:12.083  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:15.109  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991667173] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:15.112  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991667176] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:15.112  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:18.137  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991670201] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:18.147  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991670211] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:18.148  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:21.169  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991673233] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:21.172  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991673236] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:21.172  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:24.195  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991676259] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:24.204  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991676262] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:24.204  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:05:27.224  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991679288] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:27.227  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991679291] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:05:27.227  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:30.253  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991682316] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:05:30.256  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991682319] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:05:30.256  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:33.277  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991685340] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:33.287  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991685350] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:33.287  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:05:36.304  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991688368] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:05:36.307  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991688371] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:36.307  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:39.329  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991691393] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:39.333  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991691396] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:39.333  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:42.357  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991694421] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:42.366  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1991694430] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:42.366  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:05:45.387  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991697451] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:45.400  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991697464] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:45.400  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:48.423  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991700486] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:05:48.426  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991700489] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:48.426  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:51.446  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991703510] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:51.456  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991703520] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:51.456  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:05:54.476  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991706540] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:54.489  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991706553] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:54.489  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:05:57.510  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991709573] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:05:57.513  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1991709577] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:05:57.513  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:00.100  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 08:06:00.100  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 08:06:00.101  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-22 08:06:00.101  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:06:00.116  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:06:00.116  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:06:00.120  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:06:00.122  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 08:06:00.539  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991712603] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:00.542  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991712606] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:00.542  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:03.568  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991715631] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:03.577  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991715641] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:03.577  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:06:06.597  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991718661] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:06.611  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991718674] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:06.611  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:09.632  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991721696] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:09.635  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991721699] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:09.645  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:12.665  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991724729] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:12.681  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:1991724745] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:12.686  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:15.707  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991727771] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:15.720  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991727784] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:15.720  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:06:18.740  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:1991730804] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:18.753  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1991730817] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:18.753  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:06:21.771  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991733834] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:21.774  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991733837] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:21.774  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:24.801  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991736865] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:24.804  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991736868] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:24.805  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:27.826  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991739890] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:27.836  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991739900] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:27.836  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:06:30.856  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991742920] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:30.868  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991742931] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:30.868  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:06:33.889  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991745953] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:33.892  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991745956] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:33.892  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:06:36.909  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991748973] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:36.913  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991748976] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:36.913  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:39.937  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991752001] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:39.947  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991752011] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:39.948  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:06:42.969  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991755033] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:42.972  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991755036] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:42.972  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:45.999  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991758063] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:46.002  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991758066] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:46.002  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:49.027  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991761091] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:49.039  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1991761102] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:49.039  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:52.060  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991764124] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:52.063  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991764127] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:52.063  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:55.089  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991767153] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:55.092  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991767156] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:06:55.092  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:06:58.119  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1991770183] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:58.122  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991770186] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:06:58.122  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:00.055  1596  1596 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-22 08:07:00.055  1596  1596 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:07:00.055  1596  1596 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-22 08:07:00.056  1596  1596 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:07:00.070  1596  1596 I LgeClockWidgetControlView: called onTimeUpdated()
,06-22 08:07:00.070  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:07:00.073  1596  1596 I [SystemUI]DateView: called onTimeUpdated()
,06-22 08:07:00.075  1596  1596 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:07:01.149  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991773212] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:07:01.152  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991773215] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:07:01.152  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:04.178  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991776242] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:04.182  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991776245] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:04.182  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:07.204  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991779268] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:07.207  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991779271] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:07:07.207  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:10.232  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991782296] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:10.235  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991782299] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:10.236  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:13.260  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991785324] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:13.263  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991785327] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:07:13.263  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:16.289  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991788353] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:16.292  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991788356] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:16.292  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:19.315  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1991791379] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:19.325  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991791382] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:19.325  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:07:22.345  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991794409] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:22.355  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991794412] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:22.356  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:07:25.378  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991797442] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:25.382  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991797445] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:07:25.382  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:28.407  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991800470] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:28.417  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1991800480] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:28.417  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:07:31.436  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1991803500] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:31.449  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1991803512] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:31.449  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-22 08:07:34.471  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1991806535] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:34.474  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991806538] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:07:34.474  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:37.501  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991809565] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:37.504  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991809568] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:37.504  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-22 08:07:40.530  1028  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1991812594] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 08:07:40.533  1028  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1991812597] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 08:07:40.533  1028  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,TIME-OUT KILL (timeout was 1400000ms)
```
