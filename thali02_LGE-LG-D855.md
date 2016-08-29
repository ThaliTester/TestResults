#### Test 814185776bb1ff3_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-29 09:53:42.778  5833  5833 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-29 09:53:42.883  5833  5833 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:53:42.883  5833  5833 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 09:53:42.937  5833  5833 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-29 09:53:42.958  5833  5833 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 09:53:42.959  5833  5833 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 09:53:42.978  5833  5833 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 09:53:42.978  5833  5833 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
--------- beginning of system
08-29 09:53:42.991  1036  2033 I ActivityManager: Killing 5269:com.lge.clock/u0a10 (adj 15): empty #17
08-29 09:53:43.052  1036  1923 W libprocessgroup: failed to open /acct/uid_10010/pid_5269/cgroup.procs: No such file or directory
08-29 09:53:43.065  2846  2862 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-29 09:53:43.068  2846  2862 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@b461da on behalf of 5833
08-29 09:53:43.069  4505  5875 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 09:53:43.117  1036  2051 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5876 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 09:53:43.148  5833  5833 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-29 09:53:43.177  5833  5833 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-29 09:53:43.276  5876  5876 D DocsApplication: Installing DEX configuration.
08-29 09:53:43.292  5876  5876 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-29 09:53:43.296  5876  5876 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{18b668e9 com.google.android.apps.docs}
08-29 09:53:43.311  5876  5876 D TAG     : onCreate()
08-29 09:53:43.329  5876  5876 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-29 09:53:43.472  1036  1923 V SIM_STK : Menu title from STK is T-Mobile
08-29 09:53:43.523  4505  5875 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 452 ms] updated apps [took 452 ms] 
,08-29 09:53:43.831  5903  5903 D AndroidRuntime: 
08-29 09:53:43.831  5903  5903 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 09:53:43.834  5903  5903 D AndroidRuntime: CheckJNI is OFF
08-29 09:53:43.997  5903  5903 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 09:53:44.002  1036  1923 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 09:53:44.017  1943  2781 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 09:53:44.020  1036  1923 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 09:53:44.023  1036  1923 D ActivityManager: setTaskToReturnTo : TaskRecord{2e8c40bb #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 09:53:44.023  1036  1923 D ActivityManager: setTaskToReturnTo : TaskRecord{2e8c40bb #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 09:53:44.024  1036  1923 D WindowStateEx: AppWindowTokenEx init.. 
08-29 09:53:44.025   346   350 E GBMv2   : DFP En is all cleared set to be enabled
08-29 09:53:44.060  1036  1923 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5921 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 09:53:44.063  5903  5903 D AndroidRuntime: Shutting down VM
08-29 09:53:44.109  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 09:53:44.109  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{454609f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 09:53:44.110  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 09:53:44.110  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2757c5ec co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 09:53:44.133  2789  2789 I MusicWidget: mDelayedStopHandler : unbind
08-29 09:53:44.141  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 09:53:44.141  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 09:53:44.141  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 09:53:44.143  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 09:53:44.143  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 09:53:44.143  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-29 09:53:44.144  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-29 09:53:44.145  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-29 09:53:44.148  1036  2017 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2c7f91com.lge.music.MediaPlaybackService$5@1cf6aef6
08-29 09:53:44.148  2130  2130 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 09:53:44.148  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.149  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.149  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.150  2130  2130 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@157a2a07
08-29 09:53:44.150  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.150  2130  2130 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 09:53:44.150  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.151  2130  2130 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 09:53:44.151  2130  2130 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 09:53:44.151  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.151  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.152  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.152  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.152  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 09:53:44.153  2130  2130 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-29 09:53:44.154  2130  2130 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 09:53:44.154  2130  2130 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 09:53:44.154  2130  2130 V MediaPlayer[Native]: reset
08-29 09:53:44.164  2130  2130 V MediaPlayer[Native]: setListener
08-29 09:53:44.164  2130  2130 V MediaPlayer[Native]: disconnect
08-29 09:53:44.164  2130  2130 V MediaPlayer[Native]: destructor
08-29 09:53:44.164   324   324 V AudioFlinger: releasing 18 from 2130 for -1
08-29 09:53:44.164   324   324 V AudioFlinger:  decremented refcount to 0
08-29 09:53:44.164   324   324 V AudioFlinger: purging stale effects
08-29 09:53:44.164  2130  2130 V MediaPlayer[Native]: disconnect
08-29 09:53:44.174  2130  2130 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-29 09:53:44.186  2130  2130 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 09:53:44.187  2130  2130 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 09:53:44.188  5921  5921 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 09:53:44.188  2130  2130 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 09:53:44.188  2130  2130 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 09:53:44.188  2130  2130 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 09:53:44.188  2130  2130 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 110863095
08-29 09:53:44.188  2130  2130 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 110863095
08-29 09:53:44.195  2130  2130 I SmartShareClient: [SmartShareManagerClient] terminate service: 2130/MediaPlaybackService/201566885
08-29 09:53:44.197  2130  2130 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 09:53:44.197  2130  2130 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3df5d564
08-29 09:53:44.206  2130  2130 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 09:53:44.206  2130  2130 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 09:53:44.207  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 09:53:44.207  2130  2130 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 09:53:44.209  1036  1960 I ActivityManager: Killing 4906:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 09:53:44.217  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
08-29 09:53:44.247  5921  5921 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 09:53:44.306  1036  1924 W libprocessgroup: failed to open /acct/uid_10085/pid_4906/cgroup.procs: No such file or directory
,08-29 09:53:44.316  5921  5921 I LibraryLoader: Loading: webviewchromium
08-29 09:53:44.319  5921  5921 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5100-5104)
08-29 09:53:44.320  5921  5921 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 09:53:44.351  5921  5921 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c6e562b}
08-29 09:53:44.352  5921  5921 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 09:53:44.353  5921  5921 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 09:53:44.364  5921  5921 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 09:53:44.365  5921  5921 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 09:53:44.370  5921  5946 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,08-29 09:53:44.376  5921  5921 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 09:53:44.377  5921  5921 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 09:53:44.377  5921  5921 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 09:53:44.380   324  2129 V AudioPolicyService: registerClient() client 0xb1020d00, uid 10118
08-29 09:53:44.385  1036  1118 D BluetoothManagerService: Message: 20
,08-29 09:53:44.385  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@343d9f6d:true
08-29 09:53:44.392  5921  5921 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 09:53:44.392  5921  5921 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 09:53:44.392  5921  5921 I Adreno-EGL: Build Date: 12/12/14 금
08-29 09:53:44.392  5921  5921 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 09:53:44.392  5921  5921 I Adreno-EGL: Remote Branch: 
08-29 09:53:44.392  5921  5921 I Adreno-EGL: Local Patches: 
08-29 09:53:44.392  5921  5921 I Adreno-EGL: Reconstruct Branch: 
08-29 09:53:44.473  5921  5956 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 09:53:44.479  5921  5921 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 09:53:44.500  5921  5921 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 09:53:44.505  5921  5921 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 09:53:44.508  5921  5921 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 09:53:44.512  5921  5921 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 09:53:44.512  5921  5921 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-29 09:53:44.524  1818  4658 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-29 09:53:44.528  5921  5921 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-29 09:53:44.536  5921  5921 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 09:53:44.536  5921  5921 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 09:53:44.563  5921  5968 D OpenGLRenderer: Render dirty regions requested: true
08-29 09:53:44.563  5921  5968 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 09:53:44.568  5921  5968 D OpenGLRenderer: Enabling debug mode 0
08-29 09:53:44.580  1818  4658 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-29 09:53:44.586  5921  5921 D Atlas   : Validating map...
08-29 09:53:44.590  1036  1052 D SplitWindow: check instance of lgWin Window{1bcf637f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 09:53:44.633  5921  5966 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:53:44.633  5921  5966 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 09:53:44.692  1818  4658 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-29 09:53:44.740  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +632ms (total +715ms)
08-29 09:53:44.741  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1912b9d8 u0 com.test.thalitest/.MainActivity t6} time:105525
08-29 09:53:44.741  5921  5921 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1cf6aef6 time:105526
,08-29 09:53:44.866  5921  5921 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 09:53:44.866  5921  5921 I chromium: 
,08-29 09:53:44.893  5921  5921 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 09:53:44.953  5876  5876 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:53:44.953  5876  5876 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 09:53:44.955  5921  5966 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 09:53:44.955  5921  5966 I chromium: 
08-29 09:53:45.077  5921  5990 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435027968
,08-29 09:53:45.088  5921  5990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 09:53:45.088  5921  5990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 09:53:45.088  5921  5990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 09:53:45.088  5921  5990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 09:53:45.088  5921  5990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 09:53:45.088  5921  5990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b461da added. We now have 1 listener(s)
,08-29 09:53:45.092  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:53:45.094  5921  5990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 09:53:45.096  5921  5990 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:53:45.105  5921  5990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 09:53:45.106  5921  5990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 09:53:45.112  5921  5990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25db6f01 added. We now have 1 listener(s)
08-29 09:53:45.112  5921  5990 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:53:45.117  1036  1544 D WifiService: New client listening to asynchronous messages
08-29 09:53:45.120  5921  5990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:53:45.120  5921  5990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 09:53:45.120  5921  5990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 09:53:45.120  5921  5990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 09:53:45.120  5921  5990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 09:53:45.123  5921  5990 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:53:45.127  1036  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:53:45.129  5921  5990 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 09:53:45.136  5921  5990 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 09:53:45.136  5921  5990 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:45.136  5921  5990 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:45.136  5921  5990 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:53:45.136  5921  5990 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:45.136  5921  5990 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:45.136  5921  5990 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:45.136  5921  5990 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:45.136  5921  5990 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:53:45.136  5921  5990 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 09:53:45.136  5921  5990 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:53:45.137  5921  5990 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 09:53:45.142  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:45.170  5921  5921 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 09:53:45.210  1036  1923 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5996 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-29 09:53:45.211  1036  1923 I ActivityManager: Killing 5038:com.lge.bnr/1000 (adj 15): empty #17
08-29 09:53:45.214   346   352 E GBMv2   : DFP En is all cleared set to be enabled
08-29 09:53:45.214   346   352 E GBMv2   : Set value is all cleared set the max
08-29 09:53:45.214   346   352 I GBMv2   : DFP Enabled. Ignore VFP set
08-29 09:53:45.289  1036  1960 W libprocessgroup: failed to open /acct/uid_1000/pid_5038/cgroup.procs: No such file or directory
,08-29 09:53:45.316  5876  5876 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-29 09:53:45.328  5996  5996 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-29 09:53:45.346  5996  5996 I LockScreenSettings: New app installed broadcast received ..
,08-29 09:53:45.351  5996  5996 I LockScreenSettings: Number of installed packages  1
08-29 09:53:45.398  1036  1923 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6017 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 09:53:45.414   362   362 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 14.988ms
08-29 09:53:45.426   362   362 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 11.785ms
,08-29 09:53:45.438   362   362 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 11.585ms
,08-29 09:53:45.494  6017  6017 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 09:53:46.053  1036  2033 V SIM_STK : Menu title from STK is T-Mobile
,08-29 09:53:46.136  1036  1905 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6051 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 09:53:46.233  5921  5994 W jxcore-log: Initializing JXcore engine
08-29 09:53:46.233  5921  5994 W jxcore-log: JXcore engine is ready
,08-29 09:53:46.274  5994  5994 W Thread-672: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7471]" dev="sockfs" ino=7471 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 09:53:46.274  5994  5994 W Thread-672: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 09:53:46.274  5994  5994 W Thread-672: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9979]" dev="sockfs" ino=9979 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 09:53:46.274  5994  5994 W Thread-672: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 09:53:46.274  5994  5994 W Thread-672: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[27642]" dev="sockfs" ino=27642 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-29 09:53:46.288  5921  5994 W jxcore-log: Starting JXcore engine
,08-29 09:53:46.337  1036  1942 I art     : Explicit concurrent mark sweep GC freed 24620(1212KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 42MB/64MB, paused 1.426ms total 103.976ms
,08-29 09:53:46.339  6051  6051 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 09:53:46.339  6051  6051 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-29 09:53:46.366  5921  5994 W jxcore-log: Platform android
08-29 09:53:46.366  5921  5994 W jxcore-log: 
08-29 09:53:46.366  5921  5994 W jxcore-log: Process ARCH arm
08-29 09:53:46.366  5921  5994 W jxcore-log: 
,08-29 09:53:46.369  1036  1924 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6070 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 09:53:46.370  1036  1924 I ActivityManager: Killing 5160:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 09:53:46.390  5139  5139 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-29 09:53:46.391  5139  5139 W System.err: android.os.DeadObjectException
08-29 09:53:46.391  5139  5139 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 09:53:46.391  5139  5139 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 09:53:46.391  5139  5139 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 09:53:46.391  5139  5139 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 09:53:46.392  5139  5139 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 09:53:46.392  5139  5139 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 09:53:46.392  5139  5139 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 09:53:46.392  5139  5139 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 09:53:46.392  5139  5139 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 09:53:46.392  5139  5139 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 09:53:46.392  5139  5139 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:46.392  5139  5139 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:46.392  5139  5139 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 09:53:46.392  5139  5139 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 09:53:46.392  5139  5139 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 09:53:46.393  5139  5139 W System.err: android.os.DeadObjectException
08-29 09:53:46.393  5139  5139 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 09:53:46.393  5139  5139 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 09:53:46.393  5139  5139 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 09:53:46.393  5139  5139 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 09:53:46.393  5139  5139 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 09:53:46.393  5139  5139 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 09:53:46.393  5139  5139 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 09:53:46.393  5139  5139 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 09:53:46.393  5139  5139 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 09:53:46.393  5139  5139 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 09:53:46.393  5139  5139 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:46.393  5139  5139 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:46.393  5139  5139 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 09:53:46.393  5139  5139 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 09:53:46.393  5139  5139 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 09:53:46.394  5139  5139 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 09:53:46.581  5921  5994 I jxcore-log: JXcore Cordova bridge is ready!
08-29 09:53:46.581  5921  5994 I jxcore-log: 
08-29 09:53:46.582  5921  5994 W jxcore-log: JXcore engine is started
,08-29 09:53:46.588  5921  5990 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 09:53:46.590  5921  5921 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-29 09:53:46.617  1036  2051 W libprocessgroup: failed to open /acct/uid_1000/pid_5160/cgroup.procs: No such file or directory
08-29 09:53:46.618  1036  2051 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 09:53:46.627  5139  5139 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 09:53:46.627  5139  5139 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 09:53:46.694  1036  1051 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6090 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 09:53:46.694  5139  5139 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 09:53:46.750  6070  6070 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-29 09:53:46.777  1036  2051 I ActivityManager: Killing 5367:com.google.android.gm/u0a64 (adj 15): empty #17
,08-29 09:53:46.778  6070  6070 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 09:53:46.787  6090  6090 D UEI.SmartControl: Quickset Services start...
08-29 09:53:46.789  6090  6090 I UEI.SmartControl: Manufacture = LGE
08-29 09:53:46.789  6090  6090 D UEI.SmartControl: Id = LGNevo
08-29 09:53:46.791  6090  6090 D UEI.SmartControl: File observer start...
08-29 09:53:46.792  6090  6090 E UEI.SmartControl: IR Port is disabled: false
08-29 09:53:46.792  6090  6090 D UEI.SmartControl: Starting file observer...
08-29 09:53:46.793  6090  6090 D UEI.SmartControl: Extracting JNI libs...
08-29 09:53:46.793  6090  6090 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-29 09:53:46.867  1036  1987 W libprocessgroup: failed to open /acct/uid_10064/pid_5367/cgroup.procs: No such file or directory
,08-29 09:53:46.878  6090  6090 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 09:53:46.878  6090  6090 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 09:53:46.878  6090  6090 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-29 09:53:46.914  6090  6090 I UEI.SmartControl: --- Selecting new region: 6
,08-29 09:53:46.917  6090  6090 I UEI.SmartControl: Model = LG-D855
08-29 09:53:46.919  6090  6090 D UEI.SmartControl: QS Service created
08-29 09:53:46.936  6090  6090 I UEI.SmartControl: Service initServices...
,08-29 09:53:46.942  6090  6090 D UEI.SmartControl: QS start get config
08-29 09:53:46.998  6090  6090 D UEI.SmartControl: Loading JNI Libs...
,08-29 09:53:47.399  6090  6090 I UEI.SmartControl: Supports setup maps: true
08-29 09:53:47.404  6090  6090 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 09:53:47.404  6090  6090 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 09:53:47.405  6090  6090 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 09:53:47.405  6090  6090 I UEI.SmartControl: ### init IR Blaster...
,08-29 09:53:47.412  6090  6090 D serial_port: Configuring serial port
08-29 09:53:47.416  6090  6090 E UEI.SmartControl: UEIBLaster setting for 616
08-29 09:53:47.417  6090  6090 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 09:53:47.417  6090  6090 I UEI.SmartControl: configuring settings for MAXQ616
08-29 09:53:47.417  6090  6090 I UEI.SmartControl: Get version...
08-29 09:53:47.432  6090  6120 D UEI.SmartControl: serial port data available: 21
,08-29 09:53:47.459  6090  6090 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 09:53:47.459  6090  6090 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 09:53:47.459  6090  6090 I UEI.SmartControl: QS saving settings...
08-29 09:53:47.460  6090  6090 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 09:53:47.477  6090  6120 D UEI.SmartControl: serial port data available: 4
,08-29 09:53:47.511  6090  6090 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 09:53:47.527  6090  6123 I UEI.SmartControl: Device manager: loading config....
08-29 09:53:47.528  6090  6123 D UEI.SmartControl: ----------- loading internal config...
,08-29 09:53:47.538  6090  6090 E UEI.SmartControl: Services init done
08-29 09:53:47.538  6090  6090 D UEI.SmartControl: QS Service init finished
08-29 09:53:47.539  6090  6090 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 09:53:47.539  6090  6090 D UEI.SmartControl: QS Service version code: 201091
08-29 09:53:47.540  6090  6090 D UEI.SmartControl: Service requested: Control
08-29 09:53:47.543  6090  6123 E UEI.SmartControl: Loading SETTINGS...
08-29 09:53:47.545  6090  6090 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 09:53:47.548  1036  1642 I ActivityManager: Killing 5139:com.lge.qremote/u0a112 (adj 15): empty #17
,08-29 09:53:47.568  6090  6123 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-29 09:53:47.583  6090  6122 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 09:53:47.584  6090  6122 D UEI.SmartControl: -----service ready thread exits
,08-29 09:53:47.636  1036  1924 W libprocessgroup: failed to open /acct/uid_10112/pid_5139/cgroup.procs: No such file or directory
,08-29 09:53:47.640  6090  6090 D UEI.SmartControl: Internal service binding...
08-29 09:53:49.087  5876  5876 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 09:53:49.097  1036  1996 I ActivityManager: Killing 5411:com.google.android.talk/u0a72 (adj 15): empty #17
08-29 09:53:49.226  1036  2051 W libprocessgroup: failed to open /acct/uid_10072/pid_5411/cgroup.procs: No such file or directory
,08-29 09:53:50.034  5876  5988 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 09:53:51.025  1036  2051 I ActivityManager: Killing 5086:com.android.calendar/u0a13 (adj 15): empty #17
,08-29 09:53:51.117  1036  1923 W libprocessgroup: failed to open /acct/uid_10013/pid_5086/cgroup.procs: No such file or directory
,08-29 09:53:52.496  6090  6121 D serial_port: close(fd = 25)
,08-29 09:53:52.505  6090  6121 I UEI.SmartControl: Serial port is closed.
08-29 09:53:52.511  6090  6124 D UEI.SmartControl: Internal timer expired: 1
08-29 09:53:52.511  6090  6124 D UEI.SmartControl: unbind internal service
,08-29 09:53:52.522  6090  6090 D UEI.SmartControl: Service.onUnbind: IControl
08-29 09:53:52.523  6090  6090 D UEI.SmartControl: Service.onDestroy
,08-29 09:53:52.526  6090  6090 D UEI.SmartControl: Lock is in USE false
,08-29 09:53:52.527  6090  6090 D UEI.SmartControl: unbind internal service
08-29 09:53:52.527  6090  6090 I UEI.SmartControl: Serial port is closed.
08-29 09:53:52.527  6090  6090 I UEI.SmartControl: Serial port is closed.
08-29 09:53:52.527  6090  6090 D UEI.SmartControl: Blaster closed
08-29 09:53:52.527  6090  6090 D UEI.SmartControl: Shut down QS...
08-29 09:53:52.528  6090  6090 D UEI.SmartControl: Stopping QS lib
08-29 09:53:52.528  6090  6090 D UEI.SmartControl: QS lib stop result = true
,08-29 09:53:52.528  6090  6090 D UEI.SmartControl: Stopped QS lib,
08-29 09:53:52.529  6090  6090 D UEI.SmartControl: Stopped file observer...
08-29 09:53:52.530  6090  6090 D UEI.SmartControl: QS shutdown complete
,08-29 09:53:54.217  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19992
,08-29 09:53:55.870  1036  1114 I ActivityManager: Waited long enough for: ServiceRecord{3fd5beda u0 com.google.android.gms/.wearable.service.WearableService}
,08-29 09:53:56.366  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 09:53:56.366  5921  5994 I jxcore-log: 
,08-29 09:53:56.369  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 09:53:56.369  5921  5994 I jxcore-log: 
08-29 09:53:56.373  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:56.373  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:56.373  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:53:56.373  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:56.373  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:56.373  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:56.373  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:56.373  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:53:56.376  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:53:56.378  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 09:53:56.378  5921  5994 I jxcore-log: 
08-29 09:53:56.379  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 09:53:56.379  5921  5994 I jxcore-log: 
,08-29 09:53:56.887  5921  5994 D executeNativeTests: Running unit tests
,08-29 09:53:56.969  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:53:56.969  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc added. We now have 2 listener(s)
,08-29 09:53:56.970  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 09:53:56.972  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-29 09:53:56.972  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 09:53:56.972  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:53:56.972  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 09:53:56.972  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 added. We now have 2 listener(s),
08-29 09:53:56.972  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:53:56.973  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:53:56.974  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:53:56.976  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 09:53:56.976  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:56.976  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:53:56.976  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:56.976  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:56.976  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:56.976  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:56.976  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:53:56.977  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:56.977  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:53:56.980  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:53:56.980  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:53:56.980  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 09:53:56.981  5921  5994 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 09:53:56.982  5921  5994 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:53:56.982  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:53:56.982  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:53:56.982  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:53:56.983  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:56.983  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:56.983  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:56.984  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:56.984  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:56.984  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:56.984  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:53:56.984  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc removed from the list
08-29 09:53:56.984  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:56.984  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 removed from the list
08-29 09:53:56.984  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:56.984  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:56.985  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:56.985  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:56.986  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:56.986  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:56.986  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:56.987  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:56.989  5921  5994 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 09:53:56.989  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:56.989  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:56.989  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operatio,n, skipping...
08-29 09:53:56.989  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:56.989  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:56.989  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:56.989  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:56.989  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:56.989  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:56.989  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:53:56.989  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:53:56.989  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:56.989  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:53:56.989  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:56.990  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:56.990  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:56.990  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:53:56.990  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:53:56.995  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:53:56.996  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:56.996  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-29 09:53:56.996  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:56.996  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:56.996  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:56.997  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:56.997  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list,
08-29 09:53:56.997  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:56.997  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:56.997  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:56.997  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:56.997  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 09:53:56.997  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:56.997  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:56.998  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 09:53:56.998  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:56.998  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:56.998  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:56.999  5921  5994 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 09:53:57.001  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:57.002  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:57.002  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:57.002  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:53:57.002  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:57.002  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:57.002  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:57.002  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:57.002  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:57.003  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:53:57.003  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:53:57.004  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.004  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 09:53:57.004  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:53:57.004  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:53:57.004  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:57.004  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 09:53:57.007  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-29 09:53:57.007  1036  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:53:57.011  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:53:57.014  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:53:57.016  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-29 09:53:57.016  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 09:53:57.017  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:57.018  5921  5994 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 09:53:57.018  5921  5994 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:53:57.020  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.020  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.020  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.020  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.020  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.020  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:57.020  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.020  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.021  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.021  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.021  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.021  5921  5994 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:53:57.022  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:57.023  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:57.023  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:57.023  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:53:57.023  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:57.023  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:57.023  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:57.023  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:57.023  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:53:57.024  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:53:57.024  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:53:57.025  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.025  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:53:57.025  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:53:57.025  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, star,t advertiser: false
08-29 09:53:57.025  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:57.025  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:53:57.028  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:53:57.029  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:57.030  5921  5994 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 09:53:57.030  5921  5994 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:53:57.031  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.031  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.031  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.031  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.031  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.031  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:57.031  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.031  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.031  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.031  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.031  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.031  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.031  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.032  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.032  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.033  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.033  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.033  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.033  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.034  5921  5994 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:53:57.035  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:57.036  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:57.036  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:57.036  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:53:57.036  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:57.036  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:57.036  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:57.036  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:57.036  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:53:57.037  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:53:57.037  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:53:57.037  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:53:57.037  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:53:57.037  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:53:57.037  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:57.037  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:53:57.039  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.040  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:53:57.041  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:57.042  5921  5994 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 09:53:57.042  5921  5994 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:53:57.042  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.042  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.042  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.043  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.043  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.043  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.043  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.043  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.043  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:57.043  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.043  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.043  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.043  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.043  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.044  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.044  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.044  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.044  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.045  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.045  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.045  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.045  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.045  5921  5994 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 09:53:57.045  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.045  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.045  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.046  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.046  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.046  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.046  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.046  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.046  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.046  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.046  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.046  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.046  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.046  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.047  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.047  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.047  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.047  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.047  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.047  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.048  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 09:53:57.048  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.048  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.048  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.048  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.048  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.048  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.048  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.048  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.048  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.048  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.048  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.048  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.048  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.048  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.049  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.049  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.049  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.049  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.049  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.049  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.050  5921  5994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 09:53:57.050  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.050  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.050  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.050  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.050  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.050  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.051  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.051  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.051  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.051  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.051  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.051  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.051  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.051  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.051  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.051  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.053  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.053  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.053  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.053  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.053  5921  5994 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 09:53:57.053  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.053  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.053  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.054  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.054  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.054  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.054  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.054  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.054  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.054  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.054  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.054  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.054  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.054  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.054  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.055  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.055  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.055  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.055  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.055  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.055  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:53:57.055  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:53:57.055  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:53:57.055  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:53:57.056  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:53:57.056  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:53:57.056  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.056  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.056  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.056  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.056  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 09:53:57.056  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.056  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.056  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.056  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.056  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.056  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.056  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.056  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.056  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.057  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.057  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.057  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.057  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.057  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.057  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.058  5921  5994 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:53:57.058  5921  5994 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:53:57.058  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 09:53:57.060  5921  5994 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:53:57.060  5921  5994 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:53:57.060  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:53:57.060  5921  5994 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 09:53:57.060  5921  5994 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:53:57.061  5921  5994 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 09:53:57.061  5921  5994 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:53:57.061  5921  5994 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:53:57.061  5921  5994 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 09:53:57.061  5921  5994 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:53:57.061  5921  5994 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:53:57.061  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 09:53:57.063  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 09:53:57.063  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 09:53:57.063  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 09:53:57.064  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 09:53:57.064  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 09:53:57.064  5921  5994 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 09:53:57.064  5921  5994 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:53:57.064  5921  5994 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 09:53:57.064  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.064  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.065  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.065  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.065  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.065  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.065  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 09:53:57.065  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.065  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.065  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.065  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.065  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.065  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.065  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.065  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.066  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.066  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.066  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.066  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.066  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.066  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.067  5921  5994 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 09:53:57.067  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.067  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.067  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.068  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.068  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.068  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.068  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.068  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.068  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.068  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.068  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.068  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.068  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.068  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.068  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.068  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.069  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.069  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.069  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.069  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.081  5921  5994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 09:53:57.083  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.083  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.083  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.083  5921  6128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 736)
08-29 09:53:57.083  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.083  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.084  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.084  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.084  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.084  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.084  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.084  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.084  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.084  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.084  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.085  5921  6129 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 736
08-29 09:53:57.086  5921  6129 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 736)
08-29 09:53:57.086  5921  6129 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 736)
08-29 09:53:57.087  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.087  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.088  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.088  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.088  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.088  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.090  5921  5994 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 09:53:57.090  5921  5994 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 09:53:57.090  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:53:57.091  5921  5994 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 09:53:57.091  5921  5994 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:53:57.091  5921  5994 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 09:53:57.091  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:53:57.091  5921  5994 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 09:53:57.091  5921  5994 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:53:57.091  5921  5994 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:53:57.091  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:53:57.091  5921  5994 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 09:53:57.091  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.091  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.092  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.092  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.092  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.092  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.092  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.092  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.092  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.092  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.092  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.092  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.092  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.092  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.095  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.095  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.096  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.096  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.096  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.096  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.096  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.097  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.097  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.097  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.097  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.097  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.097  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.097  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.097  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.097  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.097  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.097  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.097  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.097  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.097  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.097  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.097  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.097  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.098  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.098  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.098  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.098  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.098  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.098  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: List,ener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.098  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.098  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.098  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.098  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.098  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.099  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.099  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.099  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.099  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.099  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.099  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.100  5921  5994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 09:53:57.100  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:57.101  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 09:53:57.101  5921  5994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 09:53:57.101  5921  5994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 09:53:57.102  5921  5921 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 09:53:57.102  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 09:53:57.102  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:53:57.103  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.103  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 09:53:57.103  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 09:53:57.103  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 09:53:57.103  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.103  5921  5994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 09:53:57.103  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:53:57.103  5921  5921 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 09:53:57.103  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.103  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.103  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:53:57.103  5921  5994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:53:57.103  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:53:57.104  5921  6136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:53:57.104  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:53:57.105  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:53:57.105  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:53:57.105  5921  5994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:53:57.105  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.105  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.105  3780  3885 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-29 09:53:57.106  5921  5994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:53:57.106  5921  6136 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 09:53:57.106  5921  6136 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 09:53:57.106  5921  6136 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 09:53:57.106  5921  5921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:57.106  5921  5921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:57.106  5921  5921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:53:57.106  5921  5921 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 09:53:57.106  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.106  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.106  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.106  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.107  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.107  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.107  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.107  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.107  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.107  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.107  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.107  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.107  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.107  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.107  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.108  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.108  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.108  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.108  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.109  5921  5994 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 09:53:57.109  5921  5994 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:53:57.109  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:53:57.110  5921  5994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:53:57.111  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.111  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.111  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.111  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.111  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.111  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.111  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.111  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.111  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.111  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.111  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.111  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.111  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.111  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.114  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.114  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.115  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.115  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.116  1036  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:53:57.116  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:53:57.117  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:53:57.117  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.117  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.117  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.117  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.117  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.117  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.118  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.118  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.118  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.118  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.118  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.118  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.118  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.118  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.118  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.118  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.118  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.118  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.119  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:57.119  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:57.119  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:57.120  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:57.120  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.120  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.120  5921  5994 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e580ccc not in the list
08-29 09:53:57.120  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.120  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.120  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:57.120  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.120  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.120  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:57.120  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:57.121  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:57.121  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:57.121  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:57.121  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212bcb15 not in the list
08-29 09:53:57.122  5921  5994 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 09:53:57.122  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:53:57.123  5921  5994 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 09:53:57.123  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:53:57.123  5921  5994 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 09:53:57.123  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:53:57.124  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 09:53:57.124  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 09:53:57.125  5921  5994 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 09:53:57.125  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:53:57.125  5921  5994 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 09:53:57.125  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:53:57.125  5921  5994 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 09:53:57.125  5921  5994 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 09:53:57.125  5921  5994 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 09:53:57.125  5921  5994 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 09:53:57.126  5921  5994 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 09:53:57.126  5921  5994 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 09:53:57.126  5921  5994 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 09:53:57.126  5921  5994 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 09:53:57.127  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:53:57.127  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cfc3882 added. We now have 2 listener(s)
08-29 09:53:57.127  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:53:57.128  5921  5994 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 09:53:57.129  1036  1783 D WifiServiceImplEx: setWifiEnabled: true pid=5921, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 09:53:57.129  1036  1783 D WifiService: setWifiEnabled: true pid=5921, uid=10118
08-29 09:53:57.129  1036  1783 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 09:53:57.130  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:53:57.130  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@727db93 added. We now have 3 listener(s)
08-29 09:53:57.130  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:53:57.133  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:53:57.133  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@179177d0 added. We now have 4 listener(s)
08-29 09:53:57.133  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:53:57.135  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:53:57.135  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@165193c9 added. We now have 5 listener(s)
08-29 09:53:57.135  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:53:57.138  1036  1783 D WifiServiceImplEx: setWifiEnabled: false pid=5921, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 09:53:57.138  1036  1783 D WifiService: setWifiEnabled: false pid=5921, uid=10118
08-29 09:53:57.138  1036  1783 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:53:57.147  1036  1539 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-29 09:53:57.147  1036  1712 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 09:53:57.148  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 09:53:57.148  1036  1712 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@ab428e5 mBinding = false
08-29 09:53:57.148  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 09:53:57.148  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 09:53:57.149  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 09:53:57.150  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 09:53:57.150  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-29 09:53:57.150  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 09:53:57.150  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-29 09:53:57.150  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:57.151  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:57.151  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:57.151  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:57.151  1036  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@39845ac1
08-29 09:53:57.151  1036  1537 D LGWifiP2pService: P2pDisablingState
08-29 09:53:57.152  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:57.152  1036  1537 D LGWifiP2pService: p2p socket connection lost
08-29 09:53:57.152  1036  1537 D LGWifiP2pService: P2pDisabledState
08-29 09:53:57.152  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 09:53:57.152  1943  1943 D WfdsService: WifiP2pState is changed : false
08-29 09:53:57.152  1943  2329 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 09:53:57.153  1943  2329 D WfdsService: Set the WFDS Monitor: false
08-29 09:53:57.153  1943  2329 D WfdsMonitor: WFDS Monitor is stopped
08-29 09:53:57.153  1943  2329 D WfdsService: STATE : WfdsDisabledState - enter
08-29 09:53:57.153  1943  2840 D CtrlSupplicant: Received on exit socket, terminate
08-29 09:53:57.153  1943  2840 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 09:53:57.153  1943  2840 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 09:53:57.153  1943  2840 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 09:53:57.154  1943  2331 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 09:53:57.154  1943  2329 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 09:53:57.155  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 09:53:57.155   319   894 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:53:57.157  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 09:53:57.157  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 09:53:57.157  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-29 09:53:57.160  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-29 09:53:57.160  1036  1118 D BluetoothManagerService: Message: 2
08-29 09:53:57.161  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 09:53:57.161  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:53:57.161  1036  1118 D BluetoothManagerService: Sending off request.
08-29 09:53:57.161  3780  3798 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 09:53:57.162  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:53:57.163  3780  3852 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 09:53:57.163  3780  3852 D BluetoothAdapterProperties: Setting state to 13
08-29 09:53:57.163  3780  3852 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 09:53:57.163  1036  1118 D BluetoothManagerService: Message: 60
08-29 09:53:57.163  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 09:53:57.163  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 09:53:57.163  3780  3852 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 09:53:57.164  3780  3852 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 09:53:57.164  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:53:57.164  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:53:57.164  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 09:53:57.168  1036  1539 D WifiNative-p2p0: doBoolean: TERMINATE
,08-29 09:53:57.169  1036  1539 D WifiNative-p2p0: TERMINATE: returned true
08-29 09:53:57.169  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 09:53:57.169  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-29 09:53:57.169  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 09:53:57.170  3780  3857 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:53:57.170  3780  3852 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 09:53:57.171  3780  3852 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 09:53:57.171  3780  4115 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:53:57.172  3780  4158 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:53:57.172  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-29 09:53:57.172  3780  4146 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:53:57.173  3780  4161 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:53:57.174  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 09:53:57.174  3780  3924 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 09:53:57.174  3780  4114 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 09:53:57.174  3780  4114 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:53:57.174  3780  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 09:53:57.174  3780  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 09:53:57.174  3780  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 09:53:57.174  3780  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 09:53:57.174  3780  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 09:53:57.174  3780  4114 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:53:57.178  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 09:53:57.179  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 09:53:57.180  3780  3924 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 09:53:57.181  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:53:57.182  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:53:57.182  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:53:57.182  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 09:53:57.184  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:57.185  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:57.188  3780  3780 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:57.188  3780  3780 D BluetoothMapService: STATE_TURNING_OFF
08-29 09:53:57.188  3780  3780 V BluetoothMapService: Handler(): got msg=4
08-29 09:53:57.188  3780  3780 D BluetoothMapService: MAP Service closeService in
08-29 09:53:57.188  3780  3780 D BluetoothMapMasInstance: MAP Service shutdown
08-29 09:53:57.188  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:57.188  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:57.188  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:57.188  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:53:57.188  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:53:57.188  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:57.188  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:57.188  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:57.188  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:53:57.188  3780  3780 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 09:53:57.188  3780  3780 V BluetoothMapService: MAP Service closeService out
08-29 09:53:57.188  3780  3780 V BtOppService: Receiver DISABLED_ACTION 
08-29 09:53:57.189  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:57.189  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular,: DO_NOT_CARE, BSSID name: null
08-29 09:53:57.189  3780  3780 I BtOppRfcommListener: stopping Accept Thread
08-29 09:53:57.189  3780  3780 V BtOppRfcommListener: close mBtServerSocket
08-29 09:53:57.189  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:53:57.189  3780  3780 V BtOppRfcommListener: waiting for thread to terminate
,08-29 09:53:57.189  3780  4146 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 09:53:57.190  3780  3780 V BtOppRfcommListener: done waiting for thread to terminate
08-29 09:53:57.190  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.191  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:57.191  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:57.191  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:57.191  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:53:57.191  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:53:57.191  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:57.191  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:57.191  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:57.191  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:53:57.192  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:57.192  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:53:57.193  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.195  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.196  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.197  5921  6128 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-29 09:53:57.198  5921  6128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 736)
08-29 09:53:57.214  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 09:53:57.214  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 09:53:57.215  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:53:57.218  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 09:53:57.228  1036  1114 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6144 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 09:53:57.233  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 09:53:57.234  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.235  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.247  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:53:57.266  2688  2688 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 09:53:57.266  2688  2688 I wpa_supplicant: monitor socket send errors count : 1
08-29 09:53:57.266  2688  2688 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
,08-29 09:53:57.267  1036  2837 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 09:53:57.267  1036  2837 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 09:53:57.276  1036  2017 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6162 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 09:53:57.282  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 09:53:57.282  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:53:57.282  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 09:53:57.282  3780  3780 V BtOppService: onDestroy
08-29 09:53:57.284  3780  3780 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 09:53:57.297  6144  6144 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 09:53:57.297  6144  6144 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-29 09:53:57.297  6144  6144 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 09:53:57.297  6144  6144 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 09:53:57.299  6144  6144 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 09:53:57.299  6144  6144 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 09:53:57.314  2688  2688 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 09:53:57.315  1036  2837 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 09:53:57.315  1036  2837 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 09:53:57.315  1036  2837 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 09:53:57.315  2688  2688 W wpa_supplicant: USIM:  scard_deinit function
08-29 09:53:57.315  1036  2837 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 09:53:57.316  1036  2837 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:53:57.316  1036  2837 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 09:53:57.316  1036  1118 D Tethering: InitialState.processMessage what=4
08-29 09:53:57.316  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 09:53:57.318  1036  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118086
08-29 09:53:57.318  1036  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118086
08-29 09:53:57.319  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=118086  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 09:53:57.319  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=118087  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 09:53:57.319   319  6179 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 09:53:57.320  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:53:57.320  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:53:57.321  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 09:53:57.335  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 09:53:57.338  6162  6162 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 09:53:57.339  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:53:57.340  1036  1642 I ActivityManager: Killing 4818:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 09:53:57.356  2688  2688 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 09:53:57.356  1036  2837 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 09:53:57.356  1036  2837 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 09:53:57.356  1036  2837 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 09:53:57.357  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
,08-29 09:53:57.367  1036  1712 W libprocessgroup: failed to open /acct/uid_10014/pid_4818/cgroup.procs: No such file or directory
08-29 09:53:57.427  6144  6144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 09:53:57.435  3780  3780 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 09:53:57.436  3780  3780 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:57.436  3780  3780 V BluetoothPbapReceiver: ***********state = 13
08-29 09:53:57.438  3780  3780 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-29 09:53:57.441  3780  3780 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:57.441  3780  3780 V BluetoothPbapService: state: 13
08-29 09:53:57.441  3780  3780 V BluetoothPbapService: Pbap Service closeService in
08-29 09:53:57.442  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:53:57.442  3780  3780 V BluetoothPbapService: successfully stopped pbap service
08-29 09:53:57.442  3780  3780 V BluetoothPbapService: Pbap Service closeService out
08-29 09:53:57.442  3780  3780 V BluetoothPbapService: Pbap Service onDestroy
08-29 09:53:57.442  3780  3780 V BluetoothPbapService: Pbap Service closeService in
08-29 09:53:57.442  3780  3780 V BluetoothPbapService: Pbap Service closeService out
08-29 09:53:57.443  3780  3780 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 09:53:57.461  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:53:57.486  1036  1924 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6184 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-29 09:53:57.488  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-29 09:53:57.488  1036  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 09:53:57.489  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 09:53:57.489  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-29 09:53:57.489  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 09:53:57.490  1943  2329 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 09:53:57.490  1943  2329 D WfdsService: Set the WFDS Monitor: false
08-29 09:53:57.490  1943  2329 D WfdsMonitor: WFDS Monitor is stopped
08-29 09:53:57.492  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:53:57.493  2511  2511 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:53:57.494  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 09:53:57.496  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 09:53:57.496  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:57.496  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 09:53:57.497  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 09:53:57.498  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:57.534  6144  6144 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 09:53:57.535  6144  6144 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 09:53:57.544  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:53:57.565  1036  1118 D BluetoothManagerService: Message: 20
08-29 09:53:57.565  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@90cb647:true
,08-29 09:53:57.578  1036  1118 D BluetoothManagerService: Message: 30
,08-29 09:53:57.583  1036  1118 D BluetoothManagerService: Message: 30
08-29 09:53:57.587  6144  6144 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 09:53:57.588  6144  6144 D BluetoothMap: Create BluetoothMap proxy object
08-29 09:53:57.589  1036  1118 D BluetoothManagerService: Message: 30
,08-29 09:53:57.595  6184  6184 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 09:53:57.595  1036  1118 D BluetoothManagerService: Message: 30
08-29 09:53:57.596  6184  6184 W LG Account v2.2: No ProfileInfo entries
08-29 09:53:57.596  6184  6184 I LG Account v2.2: isEnabled: false
08-29 09:53:57.596  6184  6184 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 09:53:57.596  6184  6184 I Feature : [Lifetracker]Country: EU
08-29 09:53:57.596  6184  6184 I Feature : [Lifetracker]Operator: OPEN
08-29 09:53:57.596  6184  6184 I Feature : [Lifetracker]Ranking support: false
08-29 09:53:57.596  6184  6184 I Feature : [Lifetracker]Comfort support: false
08-29 09:53:57.596  6184  6184 I Feature : [Lifetracker]Accessory: true
08-29 09:53:57.596  6184  6184 I Feature : [Lifetracker]Health device: true
08-29 09:53:57.596  6184  6184 I Feature : [Lifetracker]Extra Pedometer: false
08-29 09:53:57.597  6184  6184 I Feature : [Lifetracker]Blood glucose device: false
08-29 09:53:57.597  6184  6184 I Feature : [Lifetracker]Device Number: 3
08-29 09:53:57.598  6144  6144 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 09:53:57.599  6144  6144 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 09:53:57.600  1036  1642 I ActivityManager: Killing 5571:com.android.defcontainer/u0a4 (adj 15): empty #17
08-29 09:53:57.607  5921  5921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:53:57.631  1036  2033 W libprocessgroup: failed to open /acct/uid_10004/pid_5571/cgroup.procs: No such file or directory
,08-29 09:53:57.632  6144  6144 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-29 09:53:57.637  6144  6144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-29 09:53:57.646  6144  6144 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:53:57.663  6144  6144 D BluetoothInputDevice: Proxy object connected
,08-29 09:53:57.665  6144  6144 D HidProfile: Bluetooth service connected
08-29 09:53:57.666  6144  6144 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:53:57.667  6144  6144 D PanProfile: Bluetooth service connected
08-29 09:53:57.668  6144  6144 D BluetoothMap: Proxy object connected
08-29 09:53:57.668  6144  6144 D MapProfile: Bluetooth service connected
08-29 09:53:57.668  6144  6144 D BluetoothMap: getConnectedDevices()
08-29 09:53:57.669  6144  6144 D BluetoothMap: Bluetooth is Not enabled
08-29 09:53:57.670  6144  6144 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 09:53:57.673  6144  6144 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 09:53:57.679  6144  6144 D BluetoothPermissionRequest: onReceive
08-29 09:53:57.681  6144  6144 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 09:53:57.691  1036  2033 I ActivityManager: Killing 5696:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-29 09:53:57.694  6144  6144 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 09:53:57.750  3780  3780 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 09:53:57.750  3780  3780 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 09:53:57.751  3780  3780 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 09:53:57.751  1036  1576 W libprocessgroup: failed to open /acct/uid_10008/pid_5696/cgroup.procs: No such file or directory
,08-29 09:53:57.857  1036  2033 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6213 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-29 09:53:57.866  3780  3780 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:57.866  3780  3780 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 09:53:57.868  3780  3780 V BluetoothFtpService: Ftp Service onStartCommand
08-29 09:53:57.868  3780  3780 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:57.868  3780  3780 V BluetoothFtpService: Ftp Service closeService
08-29 09:53:57.868  3780  3780 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-29 09:53:57.871  3780  3780 V BluetoothFtpService: successfully stopped ftp service
08-29 09:53:57.871  3780  3780 V BluetoothFtpService: Ftp Service onDestroy
08-29 09:53:57.871  3780  3780 V BluetoothFtpService: Ftp Service closeService
08-29 09:53:57.874  3780  3780 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 09:53:57.874  3780  3780 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 09:53:57.874  3780  3780 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 09:53:57.874  3780  3780 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:57.874  3780  3780 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 09:53:57.875  3780  3780 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 09:53:57.876  3780  3780 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:57.876  3780  3780 V BluetoothSapService: state: 13
08-29 09:53:57.877  3780  3780 V BluetoothSapService: Stopping SAP server process
08-29 09:53:57.878  3780  3780 V BluetoothSapService: Sap Service closeSapService in
08-29 09:53:57.878  3780  3780 V BluetoothSapService: Close listen Socket : 
08-29 09:53:57.878  3780  3780 V BluetoothSapService: Close rfcomm Socket : 
08-29 09:53:57.878  3780  3780 V BluetoothSapService: Close sapd  Socket : 
08-29 09:53:57.879  3780  3780 V BluetoothSapService: Sap Service closeSapService out
08-29 09:53:57.880  3780  3780 V BluetoothSapService: Sap Service onDestroy
08-29 09:53:57.880  3780  3780 V BluetoothSapService: Sap Service closeSapService in
08-29 09:53:57.880  3780  3780 V BluetoothSapService: Close listen Socket : 
,08-29 09:53:57.880  3780  3780 V BluetoothSapService: Close rfcomm Socket : 
08-29 09:53:57.880  3780  3780 V BluetoothSapService: Close sapd  Socket : 
08-29 09:53:57.883  3780  3780 V BluetoothSapService: Sap Service closeSapService out
08-29 09:53:57.934  1036  2033 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6233 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 09:53:57.972  6213  6213 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 09:53:58.003  6233  6233 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 09:53:58.007  6213  6213 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-29 09:53:58.022  1036  1923 I ActivityManager: Killing 5730:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 09:53:58.039  6213  6213 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-29 09:53:58.040  6213  6213 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 09:53:58.040  6213  6213 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 09:53:58.041  6213  6213 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 09:53:58.041  6213  6213 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 09:53:58.045  6213  6213 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 09:53:58.050  6213  6213 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 09:53:58.077  1036  1924 W libprocessgroup: failed to open /acct/uid_10011/pid_5730/cgroup.procs: No such file or directory
,08-29 09:53:58.085  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:53:58.088  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:53:58.102  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 09:53:58.104  6213  6213 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 09:53:58.106  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:53:58.107  6213  6213 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 09:53:58.112  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 09:53:58.112  6162  6162 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 09:53:58.112  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:53:58.119  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:53:58.125  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:53:58.137  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 09:53:58.138  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:53:58.141  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 09:53:58.183  3780  3857 D bt_hci_bdroid: cleanup
,08-29 09:53:58.183  3780  3924 W bt-btif : ag scb idx 1 not allocated
08-29 09:53:58.183  3780  3924 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 09:53:58.183  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 09:53:58.183  3780  3924 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:53:58.183  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:53:58.183  3780  3924 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:53:58.183  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:53:58.183  3780  3924 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:53:58.183  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:53:58.184  3780  3924 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:53:58.184  3780  3924 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 09:53:58.184  3780  3926 I bt_lpm  : LPM is already off!!!
08-29 09:53:58.184  3780  4086 I bt_userial_mct: exiting userial_read_thread
08-29 09:53:58.184  3780  4086 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 09:53:58.185  3780  3857 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 09:53:58.185  3780  3926 I bt_vendor: hw_epilog_process
,08-29 09:53:58.186  3780  3857 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 09:53:58.186  3780  3857 D bt_userial_mct: userial_close
08-29 09:53:58.186  3780  3857 E bt_userial_mct: pthread_join() FAILED result:3
08-29 09:53:58.186  3780  3857 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 09:53:58.214  1036  2033 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6260 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-29 09:53:58.265  3780  3857 D bt_hci_bdroid: set_power 0
08-29 09:53:58.265  3780  3857 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 09:53:58.265  3780  3857 I bt_vendor: bluetooth satus is on
08-29 09:53:58.265  3780  3857 I bt_vendor: bt-vendor : resetting BT status
08-29 09:53:58.265  3780  3857 I bt_vendor: Starting hciattach daemon
08-29 09:53:58.265  3780  3857 I bt_vendor: try to set false
08-29 09:53:58.266  3780  3857 I bt_vendor: Starting hciattach daemon
08-29 09:53:58.266  3780  3857 I bt_vendor: try to set false
08-29 09:53:58.267  3780  3857 I bt_vendor: cleanup
,08-29 09:53:58.267  3780  3924 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 09:53:58.268  3780  3857 I GKI_LINUX: GKI_exit_task 0 done
08-29 09:53:58.268  3780  3857 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 09:53:58.270  3780  3852 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 09:53:58.279  3780  3780 D HeadsetService: Received stop request...Stopping profile...
,08-29 09:53:58.281  3780  3780 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 09:53:58.281  3780  3780 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:53:58.281  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297dfa88
08-29 09:53:58.282  3780  3884 D HeadsetStateMachine: Exit Disconnected: -1
08-29 09:53:58.284  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-29 09:53:58.284  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-29 09:53:58.285  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-29 09:53:58.285  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 09:53:58.285  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-29 09:53:58.287  3780  3780 D A2dpService: Received stop request...Stopping profile...
08-29 09:53:58.287  3780  3914 D A2dpStateMachine: Exit Disconnected: -1
08-29 09:53:58.288  3780  3780 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 09:53:58.290  3780  3780 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 09:53:58.290  3780  3780 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:53:58.290  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297dfa88
08-29 09:53:58.290  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-29 09:53:58.291  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 09:53:58.291  3780  3780 D HeadsetStateMachine: Unbinding service...
08-29 09:53:58.292  3780  3780 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 09:53:58.292  3780  3780 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 09:53:58.292  3780  3780 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 09:53:58.292  3780  3780 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 09:53:58.292  3780  3780 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 09:53:58.292  3780  3780 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 09:53:58.292  3780  3780 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 09:53:58.294  3780  3852 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-29 09:53:58.295  3780  3780 D HidService: Received stop request...Stopping profile...
08-29 09:53:58.295  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297dfa88
08-29 09:53:58.296  6144  6144 D BluetoothInputDevice: Proxy object disconnected
08-29 09:53:58.296  6144  6144 D HidProfile: Bluetooth service disconnected
08-29 09:53:58.297  3780  3780 D HealthService: Received stop request...Stopping profile...
08-29 09:53:58.297  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297dfa88
08-29 09:53:58.298  3780  3780 D PanService: Received stop request...Stopping profile...
08-29 09:53:58.298  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297dfa88
08-29 09:53:58.300  6144  6144 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:53:58.300  6144  6144 D PanProfile: Bluetooth service disconnected
08-29 09:53:58.300  3780  3780 I BluetoothA2dpServiceJni: cleanupNative
08-29 09:53:58.300  3780  3915 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 09:53:58.300  3780  3780 I GKI_LINUX: GKI_exit_task 2 done
08-29 09:53:58.300  3780  3780 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 09:53:58.300  3780  3780 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 09:53:58.301  3780  3780 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 09:53:58.301  3780  3780 D BtGatt.GattService: stop()
08-29 09:53:58.301  3780  3780 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 09:53:58.302  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297dfa88
08-29 09:53:58.303  3780  3780 D BluetoothMapService: Received stop request...Stopping profile...
08-29 09:53:58.303  3780  3780 D BluetoothMapService: stop()
08-29 09:53:58.304  3780  3780 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 09:53:58.304  3780  3780 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 09:53:58.305  3780  3780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297dfa88
,08-29 09:53:58.306  3780  3780 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 09:53:58.306  3780  3780 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 09:53:58.307  3780  3780 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:53:58.307  3780  3780 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:53:58.307  3780  3780 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:53:58.307  3780  3780 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:53:58.307  3780  3780 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 09:53:58.308  6144  6144 D BluetoothMap: Proxy object disconnected
08-29 09:53:58.308  6144  6144 D MapProfile: Bluetooth service disconnected
08-29 09:53:58.309  3780  3780 V BluetoothMapService: Handler(): got msg=4
08-29 09:53:58.309  3780  3780 D BluetoothMapService: MAP Service closeService in
08-29 09:53:58.309  3780  3780 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 09:53:58.309  3780  3780 V BluetoothMapService: MAP Service closeService out
08-29 09:53:58.309  3780  3780 D BluetoothMapService: cleanup()
08-29 09:53:58.309  3780  3780 D BluetoothMapService: MAP Service closeService in
08-29 09:53:58.310  3780  3780 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 09:53:58.310  3780  3780 V BluetoothMapService: MAP Service closeService out
08-29 09:53:58.310  3780  3852 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 09:53:58.310  3780  3852 D BluetoothAdapterProperties: Setting state to 10
08-29 09:53:58.310  3780  3852 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 09:53:58.310  3780  3852 I BluetoothAdapterState: Entering OffState
08-29 09:53:58.311  1036  1118 D BluetoothManagerService: Message: 60
08-29 09:53:58.311  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 09:53:58.311  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 09:53:58.311  6144  6159 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:53:58.312  6144  6160 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:53:58.312  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:53:58.312  6144  6159 D BluetoothMap: onBluetoothStateChange: up=false
08-29 09:53:58.313  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:53:58.313  6144  6160 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 09:53:58.314  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:53:58.314  1854  4323 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:53:58.315  1854  4319 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:53:58.316  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 09:53:58.316  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 09:53:58.319  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 09:53:58.319  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
,08-29 09:53:58.319  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@ab428e5 mBinding = false
08-29 09:53:58.320  1036  1118 D BluetoothManagerService: Sending unbind request.
08-29 09:53:58.321  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 09:53:58.326  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:58.327  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:58.327  6144  6144 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 09:53:58.328  6144  6144 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 09:53:58.328  6144  6144 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 09:53:58.328  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:58.328  1943  2133 D LGBluetoothAPIService: Message: 2
08-29 09:53:58.329  1943  2133 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3f355db5 mBinding = false
08-29 09:53:58.329  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 09:53:58.329  1943  2133 D LGBluetoothAPIService: Sending unbind request.
08-29 09:53:58.330  6144  6144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 09:53:58.333  1603  1603 D BluetoothAdapter: 55090976: getState() :  mService = null. Returning STATE_OFF
08-29 09:53:58.334  1603  1603 D BluetoothAdapter: 55090976: getState() :  mService = null. Returning STATE_OFF
08-29 09:53:58.340  3780  3857 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 09:53:58.341  3780  3780 I GKI_LINUX: GKI_exit_task 1 done
08-29 09:53:58.341  3780  3780 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 09:53:58.341  3780  3780 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 09:53:58.341  3780  3780 I art     : --- WEIRD: removing null entry 246
08-29 09:53:58.342  3780  3780 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 09:53:58.342  3780  3780 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 09:53:58.343  3780  3780 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 09:53:58.344  6144  6144 D DockEventReceiver: finishStartingService: stopping service
08-29 09:53:58.345  3780  3780 I art     : System.exit called, status: 0
08-29 09:53:58.345  3780  3780 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 09:53:58.354  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 09:53:58.357  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:58.363  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:53:58.367   324   324 V AudioFlinger: 3780 died, releasing its sessions
,08-29 09:53:58.367   324   324 V AudioFlinger:  pid 1854 @ 0
08-29 09:53:58.367   324   324 V AudioFlinger:  pid 3292 @ 1
,08-29 09:53:58.367   324   324 V AudioFlinger:  pid 3292 @ 2
08-29 09:53:58.368  6144  6144 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 09:53:58.385  1036  1987 I ActivityManager: Process com.android.bluetooth (pid 3780) has died
08-29 09:53:58.385  1036  1987 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-29 09:53:58.391  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:53:58.397  6260  6281 W FormManager: Network not available. Please check & try again.
,08-29 09:53:58.408  6144  6144 D BluetoothPermissionRequest: onReceive
08-29 09:53:58.410  6260  6282 V FormManager: Network unavailable.
,08-29 09:53:58.412  6144  6144 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 09:53:58.412  6144  6144 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 09:53:58.418  6144  6144 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 09:53:58.420  6260  6282 V FormManager: Network unavailable.
08-29 09:53:58.465  1036  1942 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6284 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 09:53:58.469  1036  1712 I ActivityManager: Killing 5748:com.android.contacts/u0a19 (adj 15): empty #17
08-29 09:53:58.518  1036  1905 W libprocessgroup: failed to open /acct/uid_10019/pid_5748/cgroup.procs: No such file or directory
,08-29 09:53:58.546  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 09:53:58.546  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 09:53:58.547  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 09:53:58.547  6144  6144 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 09:53:58.548  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 09:53:58.555  6284  6284 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 09:53:58.556  6284  6284 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 09:53:58.556  6284  6284 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 09:53:58.557  6284  6284 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 09:53:58.560  6144  6144 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-29 09:53:58.561  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 09:53:58.561  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 09:53:58.561  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 09:53:58.561  6144  6144 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 09:53:58.561  6144  6144 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-29 09:53:58.567  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 09:53:58.567  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 09:53:58.570  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:53:58.574  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:53:58.576  6284  6284 D BluetoothAdapterApp: Loading JNI Library
,08-29 09:53:58.584  6162  6162 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 09:53:58.584  6162  6162 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 09:53:58.584  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:53:58.587  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:58.591  4228  6303 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 09:53:58.597  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:53:58.608  4228  6307 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 09:53:58.610  4228  6307 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 09:53:58.611  6260  6305 W FormManager: Network not available. Please check & try again.
08-29 09:53:58.615  6260  6306 V FormManager: Network unavailable.
08-29 09:53:58.617  6260  6306 V FormManager: Network unavailable.
08-29 09:53:58.618  6213  6213 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 09:53:58.619  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 09:53:58.619  6213  6213 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-29 09:53:58.621  6284  6284 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@18b668e9 Instance Count = 1
08-29 09:53:58.626  6284  6284 D BluetoothAdapterApp: onCreate
08-29 09:53:58.652  6284  6284 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 09:53:58.652  6284  6284 D ProfileConfigQcom: Adding HeadsetService
08-29 09:53:58.653  6284  6284 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 09:53:58.653  6284  6284 D ProfileConfigQcom: Adding A2dpService
08-29 09:53:58.653  6284  6284 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 09:53:58.653  6284  6284 D ProfileConfigQcom: Adding HidService
08-29 09:53:58.653  6284  6284 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 09:53:58.654  6284  6284 D ProfileConfigQcom: Adding HealthService
08-29 09:53:58.654  6284  6284 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-29 09:53:58.656  6284  6284 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 09:53:58.656  6284  6284 D ProfileConfigQcom: Adding PanService
08-29 09:53:58.656  6284  6284 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 09:53:58.656  6284  6284 D ProfileConfigQcom: Adding GattService
08-29 09:53:58.657  6284  6284 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 09:53:58.657  6284  6284 D ProfileConfigQcom: Adding BluetoothMapService
08-29 09:53:58.657  6284  6284 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 09:53:58.659  6284  6284 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 09:53:58.662  6213  6213 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:53:58.662  6213  6213 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 09:53:58.663  6144  6144 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 09:53:58.665  6284  6284 V LGMDMManagerInternal: Create singleton instance
08-29 09:53:58.670  6213  6213 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 09:53:58.671  6213  6213 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 09:53:58.671  6213  6213 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-29 09:53:58.671  6213  6213 V SoundPool: doLoad: loading sample sampleID=1
08-29 09:53:58.671  6213  6213 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 09:53:58.675  6090  6090 D UEI.SmartControl: QS Service created
08-29 09:53:58.676  6213  6213 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 09:53:58.677  6213  6315 V SoundPool: Start decode
08-29 09:53:58.677  6213  6315 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-29 09:53:58.679   324  2128 V MediaPlayerService: decode(22, 10857164, 17813)
08-29 09:53:58.679   324  2128 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 09:53:58.679   324  2128 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 09:53:58.679   324  2128 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 09:53:58.679   324  2128 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 09:53:58.679   324  2128 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 09:53:58.679   324  2128 V MediaPlayerService: player type = 3
08-29 09:53:58.679   324  2128 V AwesomePlayer: AwesomePlayer create()
08-29 09:53:58.679   324  2128 V AwesomePlayer: reset_l() 
08-29 09:53:58.679   324  2128 V AwesomePlayer: cancelPlayerEvents
08-29 09:53:58.679   324  2128 V AwesomePlayer: setAudioSink() 
08-29 09:53:58.679   324  2128 V AwesomePlayer: reset_l() 
08-29 09:53:58.679   324  2128 V AudioCache: notify(0xb5474780, 8, 0, 0)
08-29 09:53:58.679   324  2128 V AudioCache: ignored
08-29 09:53:58.679   324  2128 V AwesomePlayer: cancelPlayerEvents
08-29 09:53:58.679   324  2128 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 09:53:58.679   324  2128 V AwesomePlayer: setDataSource_l dataSource
08-29 09:53:58.679   324  2128 V LGParserOSAL: SniffLGParser start
08-29 09:53:58.680   324  2128 V LGParserOSAL: MainType:5, SubType=0
08-29 09:53:58.680   324  2128 V LGParserOSAL: #### check Mime : application/ogg
08-29 09:53:58.680   324  2128 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 09:53:58.680   324  2128 E MediaExtractor: Use LGExtractor :application/ogg 
,08-29 09:53:58.680  6213  6213 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 09:53:58.680  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 09:53:58.693  6090  6090 I UEI.SmartControl: Service initServices...
08-29 09:53:58.693  6090  6090 D UEI.SmartControl: QS start get config
08-29 09:53:58.693  6213  6213 V LGMDMManager: Create singleton instance
08-29 09:53:58.740   324  2128 V LGParserOSAL: supported mime: application/ogg
08-29 09:53:58.740   324  2128 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 09:53:58.740   324  2128 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 09:53:58.740   324  2128 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 09:53:58.740   324  2128 V AwesomePlayer: AudioTrack Setting
08-29 09:53:58.741   324  2128 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 09:53:58.741   324  2128 V AwesomePlayer: setAudioSource() 
08-29 09:53:58.741   324  2128 V MediaPlayerService: prepare
08-29 09:53:58.741   324  2128 V AwesomePlayer: prepareAsync_l() 
08-29 09:53:58.741   324  2128 V MediaPlayerService: wait for prepare
08-29 09:53:58.741   324  6318 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 09:53:58.741   324  6318 V AwesomePlayer: initAudioDecoder() 
08-29 09:53:58.741   324  6318 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 09:53:58.741   324  6318 V AudioSystem: isOffloadSupported()
08-29 09:53:58.741   324  6318 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 09:53:58.741   324  6318 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 09:53:58.741   324  6318 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 09:53:58.741   324  6318 V AwesomePlayer: getUseOffload() = 0 
08-29 09:53:58.741   324  6318 V OMXCodec: OMXCodec::Create
08-29 09:53:58.741   324  6318 V OMXCodec: findMatchingCodecs()
08-29 09:53:58.741   324  6318 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 09:53:58.741   324  6318 V OMXCodec: matchingCodecs.size()=1
,08-29 09:53:58.741   324  6318 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 09:53:58.743   324  6318 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 09:53:58.743   324  6318 V LGCodecAdapter: LG Codec Adapter start
08-29 09:53:58.743   324  6318 V OMXCodec: OMXCodec Createtor
08-29 09:53:58.743   324  6318 V OMXCodec: setComponentRole
08-29 09:53:58.743   324  6318 V OMXCodec: configureCodec protected=0
08-29 09:53:58.743   324  6318 V LGCodecAdapter: called getLGCodecSpecificData
08-29 09:53:58.743   324  6318 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 09:53:58.743   324  6318 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 09:53:58.743   324  6318 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 09:53:58.743   324  6318 V LGCodecOSAL: Not support LGCodec
08-29 09:53:58.743   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 09:53:58.743   324  6318 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 09:53:58.743   324  6318 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 09:53:58.743   324  6318 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 09:53:58.743   324  6318 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 09:53:58.743   324  6318 V AudioSystem: isOffloadSupported()
08-29 09:53:58.743   324  6318 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 09:53:58.743   324  6318 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 09:53:58.743   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 09:53:58.743   324  6318 V OMXCodec: init()
08-29 09:53:58.743   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 09:53:58.743   324  6318 V OMXCodec: allocateBuffers
08-29 09:53:58.743   324  6318 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 09:53:58.743   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-29 09:53:58.744   324  6318 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-29 09:53:58.744   324  6318 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-29 09:53:58.744   324  6318 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 09:53:58.744   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 09:53:58.744   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 09:53:58.744   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 09:53:58.744   324  6318 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 09:53:58.744   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 ,09:53:58.744   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 09:53:58.744   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 09:53:58.744   324  6318 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 09:53:58.744   324  6318 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 09:53:58.744   324  6318 V AudioCache: notify(0xb5474780, 5, 0, 0)
08-29 09:53:58.744   324  6318 V AudioCache: ignored
08-29 09:53:58.744   324  6318 V AudioCache: notify(0xb5474780, 1, 0, 0)
08-29 09:53:58.744   324  6318 V AudioCache: prepared
08-29 09:53:58.744   324  2128 V AudioCache: wait - success
08-29 09:53:58.744   324  2128 V MediaPlayerService: start
08-29 09:53:58.744   324  2128 V AwesomePlayer: play_l() 
08-29 09:53:58.744   324  2128 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 09:53:58.744   324  2128 V AwesomePlayer: createAudioPlayer_l
08-29 09:53:58.744   324  2128 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 09:53:58.744   324  2128 V AwesomePlayer: startAudioPlayer_l() 
08-29 09:53:58.744   324  2128 D AudioPlayer: start of Playback, useOffload 0
08-29 09:53:58.744   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 09:53:58.745   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
,08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 09:53:58.747   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 09:53:58.748   324  6320 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 09:53:58.748   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 09:53:58.748   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-29 09:53:58.748   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-29 09:53:58.748   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-29 09:53:58.748   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on output port
08-29 09:53:58.748   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 09:53:58.748   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 09:53:58.749   324  2128 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 09:53:58.750   324  2128 V AudioCache: notify(0xb5474780, 6, 0, 0)
08-29 09:53:58.750   324  2128 V AudioCache: ignored
08-29 09:53:58.750   324  2128 V MediaPlayerService: wait for playback complete
08-29 09:53:58.750   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.750   324  6321 V AudioCache: memcpy(0xaf104000, 0xb178e000, 4096)
08-29 09:53:58.752   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.752   324  6321 V AudioCache: memcpy(0xaf105000, 0xb178e000, 4096)
08-29 09:53:58.753   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.753   324  6321 V AudioCache: memcpy(0xaf106000, 0xb178e000, 4096)
08-29 09:53:58.753   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.753   324  6321 V AudioCache: memcpy(0xaf107000, 0xb178e000, 4096)
08-29 09:53:58.754   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.754   324  6321 V AudioCache: memcpy(0xaf108000, 0xb178e000, 4096)
08-29 09:53:58.754   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.754   324  6321 V AudioCache: memcpy(0xaf109000, 0xb178e000, 4096)
08-29 09:53:58.755   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.755   324  6321 V AudioCache: memcpy(0xaf10a000, 0xb178e000, 4096)
08-29 09:53:58.756   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.756   324  6321 V AudioCache: memcpy(0xaf10b000, 0xb178e000, 4096)
08-29 09:53:58.756   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.756   324  6321 V AudioCache: memcpy(0xaf10c000, 0xb178e000, 4096)
08-29 09:53:58.757   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.757   324  6321 V AudioCache: memcpy(0xaf10d000, 0xb178e000, 4096)
08-29 09:53:58.757   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.757   324  6321 V AudioCache: memcpy(0xaf10e000, 0xb178e000, 4096)
08-29 09:,53:58.758   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.758   324  6321 V AudioCache: memcpy(0xaf10f000, 0xb178e000, 4096)
08-29 09:53:58.758   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.758   324  6321 V AudioCache: memcpy(0xaf110000, 0xb178e000, 4096)
08-29 09:53:58.759   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.759   324  6321 V AudioCache: memcpy(0xaf111000, 0xb178e000, 4096)
08-29 09:53:58.759   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.759   324  6321 V AudioCache: memcpy(0xaf112000, 0xb178e000, 4096)
08-29 09:53:58.760   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.760   324  6321 V AudioCache: memcpy(0xaf113000, 0xb178e000, 4096)
08-29 09:53:58.760   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.760   324  6321 V AudioCache: memcpy(0xaf114000, 0xb178e000, 4096)
08-29 09:53:58.761   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.761   324  6321 V AudioCache: memcpy(0xaf115000, 0xb178e000, 4096)
08-29 09:53:58.761   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.761   324  6321 V AudioCache: memcpy(0xaf116000, 0xb178e000, 4096)
08-29 09:53:58.762   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.762   324  6321 V AudioCache: memcpy(0xaf117000, 0xb178e000, 4096)
08-29 09:53:58.762   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.762   324  6321 V AudioCache: memcpy(0xaf118000, 0xb178e000, 4096)
08-29 09:53:58.763   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.763   324  6321 V AudioCache: memcpy(0xaf119000, 0xb178e000, 4096)
08-29 09:53:58.763   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.763   324  6321 V AudioCache: memcpy(0xaf11a000, 0xb178e000, 4096)
08-29 09:53:58.764   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.764   324  6321 V AudioCache: memcpy(0xaf11b000, 0xb178e000, 4096)
08-29 09:53:58.764   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.764   324  6321 V AudioCache: memcpy(0xaf11c000, 0xb178e000, 4096)
08-29 09:53:58.764   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.764   324  6321 V AudioCache: memcpy(0xaf11d000, 0xb178e000, 4096)
08-29 09:53:58.764  6284  6284 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:58.765   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.765   324  6321 V AudioCache: memcpy(0xaf11e000, 0xb178e000, 4096)
08-29 09:53:58.765   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.765   324  6321 V AudioCache: memcpy(0xaf11f000, 0xb178e000, 4096)
08-29 09:53:58.765   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.765   324  6321 V AudioCache: memcpy(0xaf120000, 0xb178e000, 4096)
08-29 09:53:58.766   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.766   324  6321 V AudioCache: memcpy(0xaf121000, 0xb178e000, 4096)
,08-29 09:53:58.767   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.767   324  6321 V AudioCache: memcpy(0xaf122000, 0xb178e000, 4096)
08-29 09:53:58.767   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.767   324  6321 V AudioCache: memcpy(0xaf123000, 0xb178e000, 4096)
08-29 09:53:58.767   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.767   324  6321 V AudioCache: memcpy(0xaf124000, 0xb178e000, 4096)
08-29 09:53:58.767   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.767   324  6321 V AudioCache: memcpy(0xaf125000, 0xb178e000, 4096)
08-29 09:53:58.768  6284  6284 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 09:53:58.768  6284  6284 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 09:53:58.768  6284  6284 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 09:53:58.768   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.768   324  6321 V AudioCache: memcpy(0xaf126000, 0xb178e000, 4096)
08-29 09:53:58.769   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.769   324  6321 V AudioCache: memcpy(0xaf127000, 0xb178e000, 4096)
08-29 09:53:58.769   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.769   324  6321 V AudioCache: memcpy(0xaf128000, 0xb178e000, 4096)
08-29 09:53:58.769   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.769   324  6321 V AudioCache: memcpy(0xaf129000, 0xb178e000, 4096)
08-29 09:53:58.769   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.769   324  6321 V AudioCache: memcpy(0xaf12a000, 0xb178e000, 4096)
08-29 09:53:58.769  6284  6284 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:58.770  6284  6284 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 09:53:58.770   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.770   324  6321 V AudioCache: memcpy(0xaf12b000, 0xb178e000, 4096)
08-29 09:53:58.770   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.770   324  6321 V AudioCache: memcpy(0xaf12c000, 0xb178e000, 4096)
08-29 09:53:58.771   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.771   324  6321 V AudioCache: memcpy(0xaf12d000, 0xb178e000, 4096)
08-29 09:53:58.771   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.771   324  6321 V AudioCache: memcpy(0xaf12e000, 0xb178e000, 4096)
08-29 09:53:58.772   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.772   324  6321 V AudioCache: memcpy(0xaf12f000, 0xb178e000, 4096)
08-29 09:53:58.772   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.772   324  6321 V AudioCache: memcpy(0xaf130000, 0xb178e000, 4096)
08-29 09:53:58.773   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.773   324  6321 V AudioCache: memcpy(0xaf131000, 0xb178e000, 4096)
08-29 09:53:58.773   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.773   324  6321 V AudioCache: memcpy(0xaf132000, 0xb178e000, 4096)
08-29 09:53:58.774   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.774   324  6321 V AudioCache: memcpy(0xaf133000, 0xb178e000, 4096)
08-29 09:53:58.774   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.774   324  6321 V AudioCache: memcpy(0xaf134000, 0xb178e000, 4096)
08-29 09:53:58.775   324  6321 V AudioCache: write(0xb178e000, 4096)
08-29 09:53:58.775   324  6321 V AudioCache: memcpy(0xaf135000, 0xb178e000, 4096)
08-29 09:53:58.775   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 09:53:58.775   324  6321 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 09:53:58.775   324  6321 V AwesomePlayer: postAudioEOS() 
08-29 09:53:58.775   324  6321 V AudioCache: write(0xb178e000, 280)
08-29 09:53:58.775   324  6321 V AudioCache: memcpy(0xaf136000, 0xb178e000, 280)
08-29 09:53:58.777  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 09:53:58.,778  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 09:53:58.779  6233  6233 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 09:53:58.782   324  6318 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 09:53:58.782   324  6318 V AwesomePlayer: onStreamDone
08-29 09:53:58.782   324  6318 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 09:53:58.782   324  6318 V AudioCache: notify(0xb5474780, 2, 0, 0)
08-29 09:53:58.782   324  6318 V AudioCache: playback complete
08-29 09:53:58.782   324  6318 V AwesomePlayer: pause_l() 
08-29 09:53:58.782   324  6318 V AudioCache: notify(0xb5474780, 7, 0, 0)
08-29 09:53:58.782   324  6318 V AudioCache: ignored
08-29 09:53:58.782   324  6318 V AwesomePlayer: cancelPlayerEvents
08-29 09:53:58.782   324  2128 V AudioCache: wait - success
08-29 09:53:58.782   324  2128 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 09:53:58.783   324  6318 D AudioPlayer: Pause Playback at 1068125
08-29 09:53:58.783   324  2128 V AwesomePlayer: reset_l() 
08-29 09:53:58.783   324  2128 V AudioCache: notify(0xb5474780, 8, 0, 0)
08-29 09:53:58.783   324  2128 V AudioCache: ignored
08-29 09:53:58.783   324  2128 V AwesomePlayer: cancelPlayerEvents
08-29 09:53:58.783   324  2128 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 09:53:58.783   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 09:53:58.783   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 09:53:58.783   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 09:53:58.783   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 1
08-29 09:53:58.783   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 09:53:58.784   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 09:53:58.784  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3443
08-29 09:53:58.784   324  2128 V OMXCodec: [OMX.google.vorbis.,decoder] mAsyncCompletion wait lock!!
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 09:53:58.784   324  6320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 09:53:58.784   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 09:53:58.784   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 09:53:58.784   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 09:53:58.785   324  2128 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 09:53:58.785   324  2128 D AudioPlayer: AudioPlayer releasing audio source
08-29 09:53:58.785   324  2128 D AudioPlayer: AudioPlayer done releasing audio source
08-29 09:53:58.785   324  2128 V AwesomePlayer: reset_l() 
08-29 09:53:58.785   324  2128 V AwesomePlayer: cancelPlayerEvents
08-29 09:53:58.785   324  2128 V AwesomePlayer: ~AwesomePlayer call
08-29 09:53:58.785   324  2128 V AwesomePlayer: reset_l() 
08-29 09:53:58.785   324  2128 V AwesomePlayer: cancelPlayerEvents
08-29 09:53:58.785  6213  6315 V SoundPool: close(32)
08-29 09:53:58.785  6213  6315 V SoundPool: pointer = 0x9ffe6000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 09:53:58.970  6090  6090 I UEI.SmartControl: Supports setup maps: true
08-29 09:53:58.973  6090  6090 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 09:53:58.973  6090  6090 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 09:53:58.973  6090  6090 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 09:53:58.973  6090  6090 I UEI.SmartControl: ### init IR Blaster...
,08-29 09:53:58.976  6090  6090 D serial_port: Configuring serial port
08-29 09:53:58.976  6090  6090 E UEI.SmartControl: UEIBLaster setting for 616
08-29 09:53:58.976  6090  6090 I UEI.SmartControl: Setting serial record hearder size = 2
,08-29 09:53:58.976  6090  6090 I UEI.SmartControl: configuring settings for MAXQ616
08-29 09:53:58.976  6090  6090 I UEI.SmartControl: Get version...
08-29 09:53:58.995  6090  6323 D UEI.SmartControl: serial port data available: 21
,08-29 09:53:59.022  6090  6090 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-29 09:53:59.022  6090  6090 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-29 09:53:59.022  6090  6090 I UEI.SmartControl: QS saving settings...
08-29 09:53:59.024  6090  6090 D UEI.SmartControl: IR Blaster version: 25672567
08-29 09:53:59.040  6090  6323 D UEI.SmartControl: serial port data available: 4
,08-29 09:53:59.074  6090  6329 I UEI.SmartControl: Device manager: loading config....,
,08-29 09:53:59.076  6090  6090 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 09:53:59.080  6090  6090 E UEI.SmartControl: Services init done
08-29 09:53:59.081  6090  6090 D UEI.SmartControl: QS Service init finished
08-29 09:53:59.081  6090  6329 D UEI.SmartControl: ----------- loading internal config...
08-29 09:53:59.082  6090  6090 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 09:53:59.082  6090  6090 D UEI.SmartControl: QS Service version code: 201091
,08-29 09:53:59.083  6090  6090 D UEI.SmartControl: Service requested: Control
08-29 09:53:59.093  6090  6329 E UEI.SmartControl: Loading SETTINGS...
08-29 09:53:59.094  6090  6090 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-29 09:53:59.098  6090  6090 D UEI.SmartControl: Internal service binding...
08-29 09:53:59.100  6213  6213 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 09:53:59.103  6090  6106 I UEI.SmartControl: ------ IControl API: 11
08-29 09:53:59.103  6090  6106 D UEI.SmartControl: File observer start...
08-29 09:53:59.104  6090  6106 E UEI.SmartControl: IR Port is disabled: false
08-29 09:53:59.104  6090  6106 D UEI.SmartControl: Starting file observer...
08-29 09:53:59.105  6090  6106 I UEI.SmartControl: Registering callback...
08-29 09:53:59.106  6090  6329 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 09:53:59.106  6090  6105 I UEI.SmartControl: ------ IControl API: 19
08-29 09:53:59.107  6090  6105 I UEI.SmartControl: Registering Services Ready callback...
,08-29 09:53:59.131  6090  6328 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-29 09:53:59.132  6090  6328 D UEI.SmartControl: -----service ready thread exits
08-29 09:53:59.133  6213  6231 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-29 09:53:59.134  6213  6313 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 09:53:59.135  6213  6313 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 09:53:59.136  6213  6213 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 09:53:59.136  6213  6213 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 09:53:59.136  6090  6106 I UEI.SmartControl: ------ IControl API: 8
08-29 09:53:59.138  6213  6213 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 09:53:59.138  6213  6213 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 09:53:59.139  6213  6213 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 09:53:59.139  6213  6213 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 09:53:59.140  6213  6213 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 09:53:59.141  6213  6213 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-29 09:53:59.142  6213  6213 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 09:53:59.149  6213  6213 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-29 09:53:59.152  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 09:53:59.153  6213  6213 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 09:53:59.154  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 09:53:59.155  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 09:53:59.157  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 09:53:59.158  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 09:53:59.159  6213  6213 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472457239158]
08-29 09:53:59.163  6213  6213 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-29 09:53:59.166  1036  1987 I ActivityManager: Killing 5809:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-29 09:53:59.201  6213  6331 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 09:53:59.206  1036  1987 I ActivityManager: Killing 5774:com.lge.email/u0a23 (adj 15): empty #18
08-29 09:53:59.237  1036  1642 W libprocessgroup: failed to open /acct/uid_10027/pid_5809/cgroup.procs: No such file or directory
,08-29 09:53:59.249  1036  1051 W libprocessgroup: failed to open /acct/uid_10023/pid_5774/cgroup.procs: No such file or directory
08-29 09:53:59.251  6213  6213 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-29 09:53:59.253  6213  6213 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 09:53:59.255  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 09:53:59.256  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 09:53:59.257  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 09:53:59.257  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 09:53:59.258  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 09:53:59.267  6213  6213 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 09:54:00.038  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-29 09:54:00.038  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-29 09:54:00.038  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-29 09:54:00.039  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-29 09:54:00.051  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-29 09:54:00.052  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-29 09:54:00.054  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-29 09:54:00.057  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 09:54:00.194  1036  1996 D WifiServiceImplEx: setWifiEnabled: true pid=5921, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 09:54:00.200  1036  1996 D WifiService: setWifiEnabled: true pid=5921, uid=10118
08-29 09:54:00.200  1036  1996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:00.222  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 09:54:00.222  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 09:54:00.222  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-29 09:54:00.224  1036  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 09:54:00.224  1036  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 09:54:00.227  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 09:54:00.227  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 09:54:00.227  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 09:54:00.227  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 09:54:00.227  1036  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 09:54:00.227  1036  1539 E WifiHW  : unknown target_country: EU , set to default
08-29 09:54:00.227  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 09:54:00.227  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 09:54:00.227  1036  1539 I WifiUtil: gEnableBmps=1
08-29 09:54:00.821   319   894 D SoftapController: Softap fwReload - Ok
,08-29 09:54:00.826  1036  1539 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (592ms)
08-29 09:54:00.827   319   894 D CommandListener: Setting iface cfg
08-29 09:54:00.827   319   894 D CommandListener: Trying to bring down wlan0
08-29 09:54:00.829  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 09:54:00.841   319  6346 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 09:54:00.855  1036  1118 D Tethering: InitialState.processMessage what=4
08-29 09:54:00.856  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 09:54:00.859   319   894 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:54:00.861  1036  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 09:54:00.861  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 09:54:00.864  6347  6347 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 09:54:00.871  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 09:54:00.871  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-29 09:54:00.871  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 09:54:00.864  6347  6347 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:00.885  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:54:00.896  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 09:54:00.900  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:00.906  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:00.906  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 09:54:00.906  1036  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 09:54:00.906  1036  1539 D WifiMonitor: connecting to supplicant
08-29 09:54:00.931  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:00.931  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 09:54:00.932  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 09:54:00.932  6144  6144 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 09:54:00.939  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 09:54:00.940  6144  6144 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 09:54:00.941  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 09:54:00.941  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 09:54:00.941  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-29 09:54:00.941  6144  6144 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 09:54:00.941  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 09:54:00.942  6144  6144 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 09:54:00.944  6347  6347 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 09:54:00.951  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:00.951  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 09:54:00.951  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 09:54:00.951  6144  6144 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 09:54:00.952  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 09:54:00.953  6144  6144 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 09:54:00.953  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 09:54:00.953  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 09:54:00.953  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 09:54:00.953  6144  6144 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 09:54:00.953  6144  6144 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 09:54:00.969  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 09:54:00.978  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:00.980  6347  6347 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 09:54:00.980  6347  6347 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-29 09:54:00.984  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:00.992  6260  6368 V FormManager: Network unavailable.
,08-29 09:54:00.998  6260  6368 V FormManager: Network unavailable.
08-29 09:54:00.993  6260  6367 W FormManager: Network not available. Please check & try again.
,08-29 09:54:01.081  6347  6347 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:54:01.102  6347  6347 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 09:54:01.110  6347  6347 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-29 09:54:01.112  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-29 09:54:01.113  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 09:54:01.113  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 09:54:01.114  1036  6369 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 09:54:01.114  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 09:54:01.114  1036  6369 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 09:54:01.114  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:01.115  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:01.115  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:01.116  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:01.116  1036  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 09:54:01.116  1036  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-29 09:54:01.117  1036  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 09:54:01.117  1036  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 09:54:01.117  1036  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 09:54:01.118  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 09:54:01.118  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-29 09:54:01.118  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 09:54:01.118  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.118  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.118  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.119  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.119  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 09:54:01.123  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-29 09:54:01.124  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:54:01.125  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:01.125  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:01.125  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:01.125  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:01.125  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:01.125  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:01.125  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:01.125  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:01.125  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:01.125  1036  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 09:54:01.125  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:01.125  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:01.127  6347  6347 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 09:54:01.127  1036  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-29 09:54:01.127  1036  1539 D WifiConfigStore: Loading config and enabling all networks 
08-29 09:54:01.127  1036  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 09:54:01.128  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:01.128  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 09:54:01.128  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:01.128  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:01.128  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:01.128  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:01.128  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:01.128  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:01.128  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:01.128  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:01.128  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 09:54:01.128  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:01.128  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:01.129  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 09:54:01.129  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 09:54:01.129  1036  6369 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 09:54:01.129  1036  6369 E WifiMonitor: han,dleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 09:54:01.130  1036  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 09:54:01.131  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 09:54:01.132  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-29 09:54:01.137  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 09:54:01.140  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 09:54:01.144  1036  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 09:54:01.148  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:01.155  1036  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 09:54:01.155  1036  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 09:54:01.157  1036  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-29 09:54:01.157  1036  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 09:54:01.157  1036  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 09:54:01.157  1036  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 09:54:01.158  1036  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 09:54:01.158  1036  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 09:54:01.158  1036  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 09:54:01.159  1036  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 09:54:01.159  6260  6371 W FormManager: Network not available. Please check & try again.
08-29 09:54:01.159  1036  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 09:54:01.159  1036  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 09:54:01.160  1036  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 09:54:01.160  1036  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 09:54:01.160  1036  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 09:54:01.160  1036  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 09:54:01.160  6260  6372 V FormManager: Network unavailable.
08-29 09:54:01.161  1036  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 09:54:01.162  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:54:01.162  1036  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 09:54:01.162  1036  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 09:54:01.162  1036  1539 D WifiNative-HAL: Setting external_sim to 1
08-29 09:54:01.162  1036  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 09:54:01.163  1036  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 09:54:01.163  1036  1539 I WifiNative-HAL: startHal
08-29 09:54:01.163  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-29 09:54:01.163  1036  1539 D wifi    : setting scan oui 0xaf73de00
08-29 09:54:01.163  1943  2329 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 09:54:01.163  1943  2329 D WfdsService: Set the WFDS Monitor: true
08-29 09:54:01.163  1943  2329 D WfdsMonitor: WfdsMonitorThread create
08-29 09:54:01.163  1943  2329 D WfdsMonitor: WFDS Monitor is created and started
08-29 09:54:01.163  1943  2329 D WfdsService: WiFi: Supplicant connection re-established
08-29 09:54:01.163  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:54:01.163  1036  1539 I WifiNative-HAL: startHal
08-29 09:54:01.163  1036  1539 D wifi    : setting scan oui 0xaf73de00
08-29 09:54:01.163  1036  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 09:54:01.164  1036  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 09:54:01.164  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 09:54:01.164  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 09:54:01.164  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 09:54:01.164  1943  6373 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 09:54:01.165  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 09:54:01.165  1943  6373 E CtrlSupplicant: Succeed to open control connection
08-29 09:54:01.165  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 09:54:01.165  1943  6373 E CtrlSupplicant: Succeed to open monitor connection
08-29 09:54:01.166  1943  6373 D WfdsMonitor: Supplicant connection established
08-29 09:54:01.166  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 09:54:01.166  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 09:54:01.166  6347  6347 I wpa_supplicant,: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 09:54:01.166  1943  2329 D WfdsService: Connected to the supplicant for wfds
08-29 09:54:01.166  6260  6372 V FormManager: Network unavailable.
,08-29 09:54:01.166  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 09:54:01.166  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 09:54:01.166  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 09:54:01.167  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 09:54:01.167  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 09:54:01.167  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 09:54:01.167  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 09:54:01.167  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 09:54:01.167  6347  6347 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 09:54:01.167  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 09:54:01.167  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 09:54:01.168  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 09:54:01.168  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 09:54:01.169  1036  1539 E WifiNative: : [121,935,921 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 09:54:01.169  1036  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 09:54:01.169  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 09:54:01.169  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 09:54:01.169  1036  1539 D WifiNative-wlan0: RECONNECT: returned true
08-29 09:54:01.169  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-29 09:54:01.170  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 09:54:01.170  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 09:54:01.170  1036  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 09:54:01.170  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
,08-29 09:54:01.171  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-29 09:54:01.171  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.172  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 09:54:01.172  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-29 09:54:01.172  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.172  1036  1557 I WifiNative-HAL: startHal
08-29 09:54:01.173  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf73de00
08-29 09:54:01.173  1036  1557 D wifi    : failed to get capabilities : -3
08-29 09:54:01.173  1036  1557 E WifiScanningService: could not get scan capabilities
08-29 09:54:01.173  1036  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.173  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 09:54:01.174  1036  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 09:54:01.174   319   894 D CommandListener: Setting iface cfg
08-29 09:54:01.174   319   894 D CommandListener: Trying to bring up p2p0
08-29 09:54:01.174  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:54:01.175  1036  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 09:54:01.175  1036  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 09:54:01.175  1036  1537 D LGWifiP2pService: P2pEnablingState
08-29 09:54:01.175  1036  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.175  1036  1537 D LGWifiP2pService: P2p socket connection successful
08-29 09:54:01.175  1036  1537 D LGWifiP2pService: P2pEnabledState
08-29 09:54:01.175  1036  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 09:54:01.176  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=121943  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 09:54:01.179  1036  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 09:54:01.179  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:54:01.180  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 09:54:01.180  1943  1943 D WfdsService: WifiP2pState is changed : true
08-29 09:54:01.180  1943  2329 D WfdsService: Receive the WFDS_ENABLE Method
08-29 09:54:01.180  1943  2329 D WfdsService: Set the WFDS Monitor: true
08-29 09:54:01.180  1943  2329 D WfdsService: Connected to the supplicant for wfds
08-29 09:54:01.180  1943  2329 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 09:54:01.180  6347  6347 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 09:54:01.180  1036  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 09:54:01.181  1943  2329 D WfdsService: selectPreferredScanChannel [36]
08-29 09:54:01.181  1036  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 09:54:01.181  1943  2329 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 09:54:01.181  1036  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
,08-29 09:54:01.181  1036  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-29 09:54:01.182  1036  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 09:54:01.182  1036  1537 D LGWifiP2pService: before postfix = G3
08-29 09:54:01.182  1036  1537 D WifiServerServiceExt: postfix byte check : 2
08-29 09:54:01.182  1036  1537 D LGWifiP2pService: after postfix = G3
08-29 09:54:01.182  1036  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 09:54:01.182  1036  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 09:54:01.182  1036  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 09:54:01.182  1036  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 09:54:01.183  1036  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 09:54:01.183  1036  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 09:54:01.183  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 09:54:01.183  1036  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 09:54:01.183  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-29 09:54:01.184  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 09:54:01.184  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:01.184  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:01.184  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=121952  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 09:54:01.185  1036  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 09:54:01.185  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.185  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.185  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 09:54:01.185  1036  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 09:54:01.186  1036  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 09:54:01.186  1036  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 09:54:01.186  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:01.186  6347  6347 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 09:54:01.186  1036  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 09:54:01.187  1036  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 09:54:01.187  1036  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 09:54:01.187  1036  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 09:54:01.187  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 09:54:01.188  1036  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 09:54:01.188  1036  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 09:54:01.188  1036  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 09:54:01.188  1036  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 09:54:01.188  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 09:54:01.189  1036  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 09:54:01.189  1943  1943 D WfdsService: isConnected: false
08-29 09:54:01.189  1036  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 09:54:01.189  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 09:54:01.189  1036,  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 09:54:01.189  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 09:54:01.189  1943  1943 D WfdsService: Update P2p Interface State: 3
08-29 09:54:01.191  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:01.193  4228  6374 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 09:54:01.198  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 09:54:01.199  6347  6347 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 09:54:01.199  1036  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 09:54:01.199  1036  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 09:54:01.199  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 09:54:01.199  1036  1537 D LGWifiP2pService: InactiveState
08-29 09:54:01.199  1036  1537 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.200  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.200  1036  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 09:54:01.200  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 09:54:01.200  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 09:54:01.200  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 09:54:01.200  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 09:54:01.201  4228  6375 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 09:54:01.201  6347  6347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:01.201  1036  6369 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 09:54:01.201  1036  6369 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:01.201  1036  6369 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:01.201  1036  6369 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:01.201  6347  6347 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 09:54:01.202  6347  6347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.202  1943  6373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 09:54:01.202  1943  6373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:01.202  1036  6369 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:01.202  1036  6369 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.202  1036  6369 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.202  1036  6369 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.202  6347  6347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.203  1943  6373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:01.203  1036  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 09:54:01.203  1036  6369 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:01.204  1036  6369 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.204  1036  6369 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.204  1036  6369 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.204  1036  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.204  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.204  6347  6347 I wpa_supplicant,: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 09:54:01.204  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.204  1036  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.204  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.204  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.204  6347  6347 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:01.205  6347  6347 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,08-29 09:54:01.205  6347  6347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.205  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 09:54:01.206  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:01.206  1036  6369 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:01.206  1036  6369 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:01.206  1036  6369 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:01.206  1036  6369 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.206  1036  6369 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.206  1036  6369 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-29 09:54:01.206  6347  6347 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.206  1036  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 09:54:01.207  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 09:54:01.207  1943  6373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:01.208  1943  6373 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:01.208  1036  6369 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:01.208  1036  6369 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.208  1036  6369 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.208  1036  6369 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:01.208  1036  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.208  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.208  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.208  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 09:54:01.208  1036  1537 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.208  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.208  1036  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.208  1036  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.208  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:01.209  1036  1036 E WifiServerServiceExt: No p2p device connected
08-29 09:54:01.209  4228  6375 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 09:54:01.209  1943  2329 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 09:54:01.210  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 09:54:01.210  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 09:54:01.210  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 09:54:01.210  6347  6347 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 09:54:01.210  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 09:54:01.210  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 09:54:01.210  1036  6369 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 09:54:01.210  1036  6369 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 09:54:01.211  1036  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 09:54:01.211  1036  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 09:54:01.211  1036  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 09:54:01.211  1036  1539 D WifiNative-wlan0: doBoolean: SCAN
08-29 09:54:01.212  1036  1539 D WifiNative-wlan0: SCAN: returned false
08-29 09:54:01.212  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:01.212  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=121980  SSID:  BSSID: 00:00:00:00:,00:00 nid: -1 state: SCANNING
08-29 09:54:01.215  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=121983  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 09:54:01.215  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:01.215  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:01.216  1036  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:01.216  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.216  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.216  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 09:54:01.216  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:01.217  1036  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:01.218  1036  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:01.219  1036  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:01.219  1036  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:01.220  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:01.220  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 09:54:01.220  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:01.220  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-29 09:54:01.221  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:01.222  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:01.223  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 09:54:01.228  6070  6070 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 09:54:01.228  6070  6070 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-29 09:54:01.232  6070  6070 V [BNRBootReceiver]: Boot Receiver Return
,08-29 09:54:01.235  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:01.241  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:01.247  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:01.254  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 09:54:01.254  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:54:01.257  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 09:54:01.751  6347  6347 E wpa_supplicant: USIM:  scard_init function
08-29 09:54:01.752  6347  6347 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-29 09:54:01.760  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 09:54:01.761  1036  6369 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 09:54:01.761  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 09:54:01.761  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
08-29 09:54:01.761  1036  6369 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 09:54:01.764  1036  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 09:54:01.768  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 09:54:01.768  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 09:54:01.769  1036  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 09:54:01.769  1036  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 09:54:01.770  1036  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 09:54:01.770  1036  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-29 09:54:01.791  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=122558  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 09:54:01.799  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:01.799  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:01.800  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:01.803  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.803  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.803  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-29 09:54:01.809  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=122577  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 09:54:01.810  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:01.810  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 09:54:01.815  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-29 09:54:01.827  6144  6144 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-29 09:54:01.834  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:01.843  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:01.850  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:01.864  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 09:54:01.866  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:01.867  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:01.879  6347  6347 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 09:54:01.885  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 09:54:01.885  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 09:54:01.886  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 09:54:01.886  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 09:54:01.886  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:01.886  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 09:54:01.889  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=122657  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 09:54:01.891  6347  6347 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 09:54:01.891  6347  6347 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 09:54:01.894  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:01.894  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 09:54:01.894  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 09:54:01.894  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 09:54:01.894  1036  6369 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 09:54:01.894  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 09:54:01.894  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 09:54:01.894  1036  6369 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 09:54:01.894  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:01.894  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 09:54:01.898  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=122660  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 09:54:01.899  1036  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122666
08-29 09:54:01.899  1036  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122667
08-29 09:54:01.901  1036  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122669
08-29 09:54:01.902  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122669
08-29 09:54:01.904  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 09:54:01.914  1036  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122682
08-29 09:54:01.915  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=122682  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 09:54:01.919  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.919  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.919  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 09:54:01.921  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:01.921  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 09:54:01.930  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:01.934  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-29 09:54:01.934  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 09:54:01.934  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 09:54:01.934  6144  6144 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 09:54:01.937  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=122704  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 09:54:01.938  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.939  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.939  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 09:54:01.939  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=122707  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 09:54:01.940  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 09:54:01.940  6144  6144 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 09:54:01.941  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 09:54:01.941  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 09:54:01.941  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 09:54:01.941  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=122708  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 09:54:01.941  6144  6144 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 09:54:01.941  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 09:54:01.942  6144  6144 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 09:54:01.943  1036  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122710
08-29 09:54:01.944  1036  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122711
08-29 09:54:01.946  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-29 09:54:01.946  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:01.947  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 09:54:01.947  1036  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-29 09:54:01.949  1036  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 09:54:01.951  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:01.953  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:01.953  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:01.954  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:01.957  1036  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 09:54:01.957  1036  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 09:54:01.965  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:01.965  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.968  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 09:54:01.968  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 09:54:01.977  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:01.977  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 09:54:01.979  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:01.980  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.981  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:01.981  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 09:54:01.981  1036  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=764196606, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-29 09:54:01.981  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:01.981  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:01.983  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:01.986  1036  1378 V AlarmManager: RTC_WAKEUP set : Alarm{24aef659 type 0 when 1472457237983 com.android.vending} when 1472457237983
08-29 09:54:01.987  1036  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 09:54:01.987  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:54:01.987  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 09:54:01.988  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 09:54:01.988  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 09:54:01.990  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 09:54:01.992  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 09:54:01.993  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:54:01.993  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 09:54:01.993  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 09:54:01.993  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 09:54:01.995  1036  1545 D ConnectivityService: Got NetworkAgent Messenger
08-29 09:54:01.996  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 09:54:01.996  1036  1545 D ConnectivityService: NetworkAgent connected
08-29 09:54:01.998  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 09:54:02.002   319   894 D CommandListener: Setting iface cfg
,08-29 09:54:02.008  1036  1539 E WifiStateMachine: Start Dhcp Watchdog 1
,08-29 09:54:02.009  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122776  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:02.010  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122777  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:02.010  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122777  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:02.011  1036  6403 D DhcpStateMachine: StoppedState
08-29 09:54:02.011  1036  6403 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:02.011  1036  6403 D DhcpStateMachine: WaitBeforeStartState
08-29 09:54:02.011  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:02.012  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 09:54:02.012  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:02.012  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:02.013  1036  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:02.013  1036  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-29 09:54:02.014  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:02.014  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:02.015  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:02.015  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:02.016  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:02.016  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:02.016  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 09:54:02.019  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122787  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:02.020  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122787  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:02.020  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122788  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:02.022  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-716540506] from screen [on:0 period:-716540506]
08-29 09:54:02.022  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:02.022  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-29 09:54:02.023  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:02.023  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-716540505]
08-29 09:54:02.023  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 09:54:02.029  1036  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-29 09:54:02.029  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.029  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.030  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.030  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.030  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.031  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.032  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-29 09:54:02.032  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-29 09:54:02.032  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 09:54:02.032  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 09:54:02.033  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 09:54:02.033  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 09:54:02.033  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 0
,08-29 09:54:02.034  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:02.034  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 09:54:02.034  1036  1539 D WifiNative-wlan0: SET ps 0: returned true
08-29 09:54:02.034  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 09:54:02.034  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 09:54:02.034  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 09:54:02.035  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1139fc82 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:02.035  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1139fc82 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:02.035  1036  6403 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:02.035  1036  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 09:54:02.035  1036  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 09:54:02.035  1036  6403 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 09:54:02.035  2608  2608 D [Concierge]Service: onStartCommand(). Type : 9
08-29 09:54:02.035  1036  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 09:54:02.036  1036  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-29 09:54:02.036  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:02.036  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 09:54:02.039  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:02.046  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:02.052  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:02.055  1036  1987 V SIM_STK : Menu title from STK is T-Mobile
08-29 09:54:02.058  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:02.059  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:54:02.059  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:02.062  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:02.067  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:02.072  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:02.076  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:02.076  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:02.077  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:02.079  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:02.083  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:02.088  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:02.092  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:02.092  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:02.093  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:02.095  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=764196606 [*alarm*], flags=0x0
,08-29 09:54:02.117  4390  6406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 09:54:02.152  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:02.152  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:02.152  1036  1537 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:54:02.170  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 09:54:02.170  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 09:54:02.170  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 09:54:02.171  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 09:54:02.171  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 09:54:02.172  1036  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-29 09:54:02.230  5833  5833 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-29 09:54:02.237  1036  6403 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 09:54:02.238  1036  6403 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 09:54:02.238  1036  6403 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 09:54:02.234  6414  6414 W dhcpcd  : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 09:54:02.234  6414  6414 W dhcpcd  : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:02.251  6414  6414 I dhcpcd  : version 5.5.6 starting
,08-29 09:54:02.253  6414  6414 E dhcpcd  : get_duid: m
08-29 09:54:02.253  6414  6414 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 09:54:02.253  6414  6414 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 09:54:02.322  6414  6414 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 09:54:02.323  6414  6414 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 09:54:02.323  6414  6414 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-29 09:54:02.325  6414  6414 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-29 09:54:02.326  6414  6414 D dhcpcd  : wlan0: sending REQUEST (xid 0xfc05bedb), next in 3.00 seconds
08-29 09:54:02.337  6414  6414 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 09:54:02.345  6414  6414 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 09:54:02.345  6414  6414 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-29 09:54:02.346  6414  6414 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 09:54:02.346  6414  6414 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-29 09:54:02.346  6414  6414 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 09:54:02.346  6414  6414 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 09:54:02.346  6414  6414 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 09:54:02.346  6414  6414 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 09:54:02.347  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.348  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.348  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.349  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.350  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 09:54:02.351  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:02.351  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 09:54:02.841  1036  6403 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-29 09:54:02.852  1036  6403 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-29 09:54:02.853  1036  6403 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 09:54:02.853  1036  6403 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 09:54:02.854  1036  6403 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 09:54:02.854  1036  6403 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 09:54:02.854  1036  6403 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-29 09:54:02.858  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 09:54:02.859  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 09:54:02.860  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:02.860  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:54:02.867  1036  6403 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 09:54:02.867  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 09:54:02.868  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 09:54:02.869  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 09:54:02.869  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 09:54:02.869  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 09:54:02.870  1036  6403 D DhcpStateMachine: RunningState
08-29 09:54:02.870  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 09:54:02.871  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 09:54:02.886  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-29 09:54:02.890  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-29 09:54:02.891  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 09:54:02.891  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 09:54:02.892  1036  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 09:54:02.893  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
08-29 09:54:02.904  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:02.904  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 09:54:02.922  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:02.922  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:02.922  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 09:54:02.928  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 09:54:02.930  1036  1545 D ConnectivityService: Adding iface wlan0 to network 100
08-29 09:54:02.934  1036  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 09:54:02.967  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:02.967  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:02.967  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 09:54:02.972  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:02.986  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 09:54:03.008  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:03.008  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 09:54:03.022  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 09:54:03.030  1036  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 09:54:03.030  1036  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-29 09:54:03.036  1036  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-29 09:54:03.040  1036  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-29 09:54:03.042  1036  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 09:54:03.043  1036  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-29 09:54:03.043  1036  1545 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-29 09:54:03.047  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.047  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.047  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 09:54:03.049  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 09:54:03.053  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.053  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:03.053  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 09:54:03.054  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 09:54:03.054  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 09:54:03.054  1036  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-29 09:54:03.055  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-29 09:54:03.055  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:03.055  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:03.055  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 09:54:03.055  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.055  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 09:54:03.056  1036  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-29 09:54:03.056  1036  1545 D ConnectivityService:    accepting network in place of null
08-29 09:54:03.056  1036  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.059  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 09:54:03.059  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-5ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.059  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 09:54:03.060  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.060  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.060  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 09:54:03.065  1036  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.065  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:03.066  1036  1545 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-29 09:54:03.067  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:03.070  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.070  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 09:54:03.070  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 09:54:03.070  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:54:03.072   319  6466 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 09:54:03.076  1036  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 09:54:03.076  1036  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 09:54:03.077  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 09:54:03.080  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 09:54:03.081  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 09:54:03.081  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-29 09:54:03.081  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 09:54:03.081  1036  1036 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-29 09:54:03.084  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:03.084  1036  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 09:54:03.086  1036  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 09:54:03.087   319  6468 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-29 09:54:03.088   319  6468 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-29 09:54:03.088  1036  1545 D ConnectivityService: validation of new default Network = false
08-29 09:54:03.088  1036  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 09:54:03.088  1036  1545 D DSQN    : enableDataServiceNotify 
08-29 09:54:03.088  1036  1545 D DSQN    : start dsqn bin
08-29 09:54:03.088   319  6468 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
08-29 09:54:03.089   319  6471 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 09:54:03.089   319  6471 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-29 09:54:03.090   319  6471 D libc-netbsd: res_queryN name = europe.pool.ntp.org., class = 1, type = 1
08-29 09:54:03.091  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 09:54:03.091  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 09:54:03.091  1036  6467 D LocSvc_java: requestTime failed
08-29 09:54:03.091  1036  6467 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-29 09:54:03.096  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-29 09:54:03.096  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.096  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:03.096  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:03.096  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 09:54:03.096  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:03.096  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.097  1603  1835 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 09:54:03.098  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:03.103  1036  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 09:54:03.094  6473  6473 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:03.094  6473  6473 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 09:54:03.114  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:03.114  6473  6473 E DSQN    : DSQN ssw
08-29 09:54:03.128  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:03.128   319  6466 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 09:54:03.128  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:54:03.132  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:03.136  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:03.136  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 09:54:03.137  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.137  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.141  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:03.145  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 09:54:03.150  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:03.150  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:03.151  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:03.154  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 09:54:03.157  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 09:54:03.161  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:03.162   319  6466 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-29 09:54:03.164  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:03.169  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:03.175  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:03.175  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:03.176  6213  6213 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 09:54:03.177  6213  6213 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 09:54:03.177  6213  6213 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-29 09:54:03.181  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 09:54:03.185  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 09:54:03.185  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:03.193  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:03.198   319   893 D LGDataListener: argv[0]=dsqncommand
08-29 09:54:03.198   319   893 D LGDataListener: argv[1]=wlan0
08-29 09:54:03.198   319   893 D LGDataListener: argv[2]=1
08-29 09:54:03.199   319   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 09:54:03.200  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 09:54:03.200  1036  1116 D DSQN    : start to monitor internet connection
,08-29 09:54:03.210  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:03.223  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:03.223  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:03.225  6213  6213 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-29 09:54:03.227  6213  6213 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 09:54:03.228  1036  2051 D WifiServiceImplEx: setWifiEnabled: false pid=5921, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 09:54:03.228  6213  6213 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 09:54:03.228  1036  2051 D WifiService: setWifiEnabled: false pid=5921, uid=10118
08-29 09:54:03.228  1036  2051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 09:54:03.233  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 07:54:03 GMT], X-Android-Received-Millis=[1472457243231], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472457243198]}
08-29 09:54:03.233  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 09:54:03.234  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 09:54:03.234  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-29 09:54:03.235  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-29 09:54:03.235  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:03.235  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:03.235  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 09:54:03.236  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-29 09:54:03.236  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-29 09:54:03.237  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.237  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 09:54:03.238  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:03.239  1603  1835 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 09:54:03.241  1036  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.242  1036  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.242  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:03.243  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 09:54:03.244  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.245  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 09:54:03.250  1036  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 09:54:03.250  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 09:54:03.251  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 09:54:03.251  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 09:54:03.251  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-29 09:54:03.252  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 09:54:03.252  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 09:54:03.253  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 09:54:03.253  1036  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 09:54:03.253  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:54:03.254  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 09:54:03.254  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 09:54:03.255  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 09:54:03.263  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 09:54:03.263  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 09:54:03.263  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.263  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.263  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 09:54:03.264  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 09:54:03.264  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 09:54:03.265  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-29 09:54:03.266  1036  6403 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:54:03.275   319   894 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:54:03.289  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 09:54:03.292  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:54:03.296  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.309  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 09:54:03.309  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
08-29 09:54:03.309  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-29 09:54:03.312  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 09:54:03.312  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:03.312  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 09:54:03.313  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-29 09:54:03.315  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.318  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.318  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.318  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 09:54:03.324  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:03.325  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.325  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.326  1036  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@39845ac1
08-29 09:54:03.326  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:03.326  1036  1537 D LGWifiP2pService: P2pDisablingState
08-29 09:54:03.327  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.327  1036  1537 D LGWifiP2pService: p2p socket connection lost
08-29 09:54:03.327  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:03.327  1036  1537 D LGWifiP2pService: P2pDisabledState
08-29 09:54:03.327  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:03.328  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 09:54:03.328  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:03.329  1036  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 09:54:03.330  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 09:54:03.330  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 09:54:03.330  6347  6347 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 09:54:03.330  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.331  1036  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.333  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:03.334  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-29 09:54:03.334  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.334  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.334  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 09:54:03.334  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 09:54:03.334  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-29 09:54:03.335  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.335  1036  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.336  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 09:54:03.336  1943  1943 D WfdsService: WifiP2pState is changed : false
08-29 09:54:03.336  1943  2329 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 09:54:03.336  1943  2329 D WfdsService: Set the WFDS Monitor: false
08-29 09:54:03.338  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 09:54:03.338  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 09:54:03.338  1943  2329 D WfdsMonitor: WFDS Monitor is stopped
08-29 09:54:03.339  1943  2329 D WfdsService: STATE : WfdsDisabledState - enter
08-29 09:54:03.339  1943  6373 D CtrlSupplicant: Received on exit socket, terminate
08-29 09:54:03.339  1943  6373 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 09:54:03.339  1943  6373 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 09:54:03.339  1943  6373 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 09:54:03.339  1943  2329 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 09:54:03.339  1943  2331 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 09:54:03.340  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 09:54:03.340  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 09:54:03.341  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.341  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-29 09:54:03.344  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 09:54:03.344  6162  6162 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 09:54:03.344  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:03.348  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 09:54:03.352  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:03.363  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:03.363  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:54:03.366  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 09:54:03.367   319   894 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:54:03.368  1036  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 09:54:03.368  1036  1545 D DSQN    : disableDataServiceNotify
08-29 09:54:03.368  1036  1545 D DSQN    : stop dsqn bin
08-29 09:54:03.369  1036  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 09:54:03.369  1036  1539 D WifiNative-p2p0: TERMINATE: returned true
08-29 09:54:03.369  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 09:54:03.369  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-29 09:54:03.369  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 09:54:03.370  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:03.370  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 09:54:03.370  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:03.370  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-29 09:54:03.370  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.370  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.371  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 09:54:03.371  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 09:54:03.372  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.373  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:03.374  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:03.374  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:03.374  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:03.374  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:03.374  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:03.374  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:03.374  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:03.374  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:03.374  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:03.374  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:03.374  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.375  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:03.375  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:03.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:03.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:03.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:03.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:03.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:03.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:03.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:03.375  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:03.375  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:03.378  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 09:54:03.378  6162  6162 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 09:54:03.378  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:03.378  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 09:54:03.378  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:03.379  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 09:54:03.381  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 09:54:03.384  1036  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 09:54:03.384  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.384  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:03.385  1036  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:03.385  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 09:54:03.385  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 09:54:03.386  1036  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 09:54:03.386  1036  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 09:54:03.386  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 09:54:03.386  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.386  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.386  1036  6402 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 09:54:03.386  1603  1835 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 09:54:03.389  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:03.390  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 09:54:03.390  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 09:54:03.390  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 09:54:03.390  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 09:54:03.390  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 09:54:03.390  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 09:54:03.391  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:03.391  1036  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.391  1036  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.391  1036  1545 D NetworkManagementService: Removing idletimer
08-29 09:54:03.391  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 09:54:03.392  1036  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.392  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:03.392  1036  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.392  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:03.393  1854  1854 D TelephonyNetworkFactory-1:   ,my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 09:54:03.393  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 09:54:03.394  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 09:54:03.394  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 09:54:03.394  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 09:54:03.398  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:03.398  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:54:03.401  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 09:54:03.406  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:03.410  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 09:54:03.410  6162  6162 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 09:54:03.410  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 09:54:03.419  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:03.426  6347  6347 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 09:54:03.426  6347  6347 I wpa_supplicant: monitor socket send errors count : 1
08-29 09:54:03.426  6347  6347 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-29 09:54:03.427  1036  6369 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 09:54:03.427  1036  6369 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 09:54:03.428  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:03.431  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 09:54:03.432  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.433  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.434  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:03.435  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:54:03.437  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 09:54:03.446  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 09:54:03.452  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:03.455  6260  6487 W FormManager: Network not available. Please check & try again.
08-29 09:54:03.458  6260  6488 V FormManager: Network unavailable.
,08-29 09:54:03.461  6260  6488 V FormManager: Network unavailable.
08-29 09:54:03.462  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 09:54:03.476  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 09:54:03.478  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:54:03.479  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.479  6347  6347 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 09:54:03.479  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 09:54:03.480  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 09:54:03.480  1036  6369 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 09:54:03.480  1036  6369 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 09:54:03.481  6347  6347 W wpa_supplicant: USIM:  scard_deinit function
08-29 09:54:03.482  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:03.482  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 09:54:03.482  1036  1118 D Tethering: InitialState.processMessage what=4
08-29 09:54:03.483  1036  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124248
08-29 09:54:03.483  1036  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124251
08-29 09:54:03.484  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124251  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 09:54:03.484  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124252  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 09:54:03.486  1036  6403 D DhcpStateMachine: StoppedState
08-29 09:54:03.486  1036  6403 D DhcpStateMachine: StoppedState{ when=-144ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:03.487  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 09:54:03.488  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:03.489  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 09:54:03.493  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 09:54:03.494  1036  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 09:54:03.495  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:03.495  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 09:54:03.495  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-29 09:54:03.495  6144  6144 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 09:54:03.496  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 09:54:03.496  6144  6144 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 09:54:03.497  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 09:54:03.497  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 09:54:03.497  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 09:54:03.497  6144  6144 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 09:54:03.497  6144  6144 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 09:54:03.517  6347  6347 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 09:54:03.517  1036  6369 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 09:54:03.517  1036  6369 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 09:54:03.517  1036  6369 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 09:54:03.519  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
,08-29 09:54:03.624  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-29 09:54:03.624  1943  2329 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 09:54:03.624  1943  2329 D WfdsService: Set the WFDS Monitor: false
08-29 09:54:03.624  1943  2329 D WfdsMonitor: WFDS Monitor is stopped
,08-29 09:54:03.630  1036  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 09:54:03.630  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 09:54:03.630  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-29 09:54:03.630  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 09:54:03.633  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 09:54:03.633  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 09:54:03.635  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 09:54:03.635  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:03.638  2511  2511 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:03.640  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 09:54:03.642  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:03.642  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:03.642  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:03.642  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:03.642  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:03.642  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:03.642  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:03.642  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:03.642  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:03.643  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:03.643  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:03.643  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:03.643  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:03.643  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:03.643  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:03.643  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:03.643  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:03.643  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:03.644  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 09:54:03.644  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 09:54:03.644  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 09:54:03.647  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:54:03.659  6162  6162 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 09:54:03.659  6162  6162 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 09:54:03.659  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:03.660  4228  6489 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 09:54:03.663  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:03.668  4228  6491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 09:54:03.669  4228  6491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 09:54:03.672  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:03.679  6260  6492 W FormManager: Network not available. Please check & try again.
,08-29 09:54:03.684  6260  6493 V FormManager: Network unavailable.
08-29 09:54:03.691  6260  6493 V FormManager: Network unavailable.
,08-29 09:54:04.076  6090  6330 D UEI.SmartControl: Internal timer expired: 2
,08-29 09:54:04.076  6090  6330 D UEI.SmartControl: unbind internal service
,08-29 09:54:04.312  6090  6324 D serial_port: close(fd = 24)
,08-29 09:54:04.319  6090  6324 I UEI.SmartControl: Serial port is closed.
,08-29 09:54:05.032  1036  1539 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-716537496] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-29 09:54:05.034  1036  1539 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-716537494] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-29 09:54:06.087  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:06.100  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-29 09:54:06.111  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:06.116  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:06.119  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:06.124  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 09:54:06.129  3672  3706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 09:54:06.142  5324  5324 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 09:54:06.200  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 09:54:06.214  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:06.295  1036  1996 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6515 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 09:54:06.297  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 09:54:06.297  1036  1052 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-29 09:54:06.299  1036  1113 E GpsLocationProvider: No APN found to select.
08-29 09:54:06.312   362   362 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 22.447ms
,08-29 09:54:06.325  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 09:54:06.325  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 09:54:06.325  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-29 09:54:06.326  1036  1118 D BluetoothManagerService: Message: 1
08-29 09:54:06.326  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-29 09:54:06.334   362   362 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 20.482ms
,08-29 09:54:06.363   362   362 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 27.166ms
08-29 09:54:06.372  1036  1118 D BluetoothManagerService: Message: 20
08-29 09:54:06.372  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38ebd794:true
,08-29 09:54:06.373  6284  6284 D BluetoothAdapterState: make
08-29 09:54:06.378  6284  6284 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 09:54:06.378  6284  6284 I bluedroid-qcom: init
08-29 09:54:06.378  6284  6540 I BluetoothAdapterState: Entering OffState
08-29 09:54:06.379  6284  6284 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 09:54:06.380  6284  6284 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 09:54:06.380  6284  6284 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 09:54:06.380  6284  6284 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 09:54:06.380  6284  6284 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 09:54:06.380  6284  6284 I bluedroid-qcom: get_profile_interface socket
08-29 09:54:06.380  6284  6284 I bluedroid-qcom: get_profile_interface map_client
,08-29 09:54:06.382  6284  6543 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 09:54:06.374  6544  6544 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:06.374  6544  6544 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:06.386  6284  6543 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 09:54:06.387  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 09:54:06.388  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 09:54:06.388  6284  6543 D BluetoothAdapterProperties: Name is: G3
,08-29 09:54:06.389  6544  6544 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 09:54:06.389  6544  6544 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 09:54:06.389  6544  6544 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 09:54:06.389  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:06.389  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 09:54:06.389  1036  1118 D BluetoothManagerService: Message: 40
08-29 09:54:06.389  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,08-29 09:54:06.390  6284  6299 I bluedroid-qcom: config_hci_snoop_log
08-29 09:54:06.390  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:06.391  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:06.391  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 09:54:06.391  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 09:54:06.394  6544  6544 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 09:54:06.398  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:06.399  6284  6540 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 09:54:06.400  6284  6540 D BluetoothAdapterProperties: Setting state to 11
08-29 09:54:06.400  6284  6540 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 09:54:06.401  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:06.401  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:06.401  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:06.402  6544  6544 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 09:54:06.402  6544  6544 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 09:54:06.402  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:06.404  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:06.404  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-29 09:54:06.404  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-29 09:54:06.404  1036  1118 D BluetoothManagerService: Message: 60
08-29 09:54:06.404  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 09:54:06.404  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-29 09:54:06.406  6284  6540 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 09:54:06.407  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:06.408  6515  6515 I AppUp4:AppBoxCP: onCreate
08-29 09:54:06.408  5324  5324 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 09:54:06.409  6515  6515 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 09:54:06.409  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:06.410  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 09:54:06.411  6144  6144 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 09:54:06.414  6284  6540 D BluetoothBondStateMachine: make
08-29 09:54:06.415  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:06.416  5324  5324 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 09:54:06.416  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:06.420  6284  6540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.420  6284  6540 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 09:54:06.420  6284  6540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.420  6284  6540 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 09:54:06.421  6284  6284 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 09:54:06.421  6284  6540 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 09:54:06.422  6284  6547 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 09:54:06.422  6284  6284 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:06.422  6284  6284 V BluetoothPbapReceiver: ***********state = 11
08-29 09:54:06.425  6284  6540 E BluetoothAdapterService: File transfer profiles supported!!
08-29 09:54:06.426  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:54:06.428  6515  6515 I AppUp4:DB:  setFingerPrint start
08-29 09:54:06.428  6515  6515 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-29 09:54:06.437  6515  6515 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 09:54:06.437  6515  6515 I AppUp4:DB:  SDK version = 21
08-29 09:54:06.437  6515  6515 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-29 09:54:06.437  6284  6540 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 09:54:06.439  6284  6284 D HeadsetService: Received start request. Starting profile...
08-29 09:54:06.440  6284  6284 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 09:54:06.440  6284  6284 D LGBluetoothHfpAdapter: Version 1.6
08-29 09:54:06.440  6515  6515 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 09:54:06.441  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 09:54:06.441  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:06.442  6284  6540 E BluetoothAdapterService: File transfer profiles supported!!
08-29 09:54:06.443  6284  6284 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 09:54:06.443  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 09:54:06.443  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 09:54:06.444  6284  6284 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 09:54:06.444  6284  6284 D HeadsetStateMachine: make
08-29 09:54:06.446  6284  6540 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 09:54:06.448  6144  6144 D BluetoothPermissionRequest: onReceive
08-29 09:54:06.451  6284  6540 E BluetoothAdapterService: File transfer profiles supported!!
08-29 09:54:06.455  6144  6144 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 09:54:06.456  6284  6540 E BluetoothAdapterService: File transfer profiles supported!!
08-29 09:54:06.459  6515  6515 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 09:54:06.461  6284  6540 E BluetoothAdapterService: File transfer profiles supported!!
08-29 09:54:06.475  6284  6540 V LGMDMManager: Create singleton instance
,08-29 09:54:06.479  6284  6284 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:54:06.479  6284  6284 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 09:54:06.482  6284  6540 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 09:54:06.482  6515  6515 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:54:06.482  6515  6515 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 09:54:06.483  6284  6284 D HeadsetStateMachine: max_hf_connections = 1
08-29 09:54:06.483  6284  6284 I bluedroid-qcom: get_profile_interface handsfree
08-29 09:54:06.484  6284  6284 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 09:54:06.485   324  1385 V AudioPolicyService: registerClient() client 0xb558a640, uid 1002
08-29 09:54:06.485   324  2129 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 09:54:06.485   324  2129 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 09:54:06.485   324  2129 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 09:54:06.485  6284  6284 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 09:54:06.485   324   324 V AudioFlinger: registerClient() client 0xb1433178, pid 6284
08-29 09:54:06.486   324  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:06.486   324  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:06.486  1603  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:06.486  1603  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:06.486  1854  2445 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:06.486  1854  2445 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:06.486  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:06.486  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:06.486  2130  4343 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:06.486  2130  4343 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:06.486  3292  3318 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:06.486  3292  3318 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:06.486  6284  6546 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:06.487   324  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:06.487   324  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-29 09:54:06.487  1036  2017 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:06.487  1036  2017 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:06.487  1603  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:06.487  1603  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:06.487  1854  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:06.487  1854  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:06.487  2130  2148 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:06.487  2130  2148 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:06.487  6284  6284 V ToneGenerator: Create Track: 0xb4928a80
08-29 09:54:06.487  6284  6284 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 09:54:06.487  6284  6284 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 09:54:06.487   324  2128 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 09:54:06.487   324  2128 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 09:54:06.487   324  2128 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 09:54:06.487  3292  3317 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:06.487   324  2128 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 09:54:06.487  3292  3317 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:06.487  6284  6284 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 09:54:06.487  6284  6546 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 09:54:06.488   324  2129 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 09:54:06.488  6284  6546 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:06.488   324   324 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 09:54:06.488  6284  6546 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 09:54:06.488   324   324 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 09:54:06.488   324   324 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 09:54:06.488   324   324 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 09:54:06.488  6284  6284 V AudioSystem: getLatency() output 2, latency 50
08-29 09:54:06.488  6284  6284 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 09:54:06.488  6284  6284 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 09:54:06.489   324  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 09:54:06.489   324  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 09:54:06.489   324  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 09:54:06.489   324  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 09:54:06.489   324  1384 V AudioFlinger: createTrack() lSessionId: 22
08-29 09:54:06.489  6284  6284 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 09:54:06.490   324  1384 V AudioFlinger: acquiring 22 from 6284, for 6284
08-29 09:54:06.490   324  1384 V AudioFlinger:  added new entry for 22
08-29 09:54:06.490  6284  6284 V ToneGenerator: ToneGenerator INIT OK, time: 127275
08-29 09:54:06.490  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.490  6284  6548 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 ,09:54:06.490  6284  6548 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 09:54:06.491  6284  6548 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 09:54:06.491  6284  6548 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 09:54:06.491   324  2128 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6284
08-29 09:54:06.491  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.491   324  2128 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 09:54:06.491   324  2128 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 09:54:06.491   324  2128 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 09:54:06.491   324  2128 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 09:54:06.492   324  2128 V voice   : voice_set_parameters: exit with code(0)
08-29 09:54:06.492   324  2128 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 09:54:06.492   324  2128 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 09:54:06.492   324  2128 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 09:54:06.492   324  2128 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 09:54:06.492   324  2128 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 09:54:06.492   324  2128 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 09:54:06.492  6284  6548 V ToneGenerator: ToneGenerator destructor
08-29 09:54:06.492  6284  6284 D A2dpService: Received start request. Starting profile...
08-29 09:54:06.492  6284  6548 V ToneGenerator: stopTone
08-29 09:54:06.492  6284  6548 V ToneGenerator: Delete Track: 0xb4928a80
08-29 09:54:06.493  6284  6548 V AudioTrack: ~AudioTrack, releasing session id from 6284 on behalf of 6284
08-29 09:54:06.493  6284  6284 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 09:54:06.493   324  1385 V AudioFlinger: releasing 22 from 6284 for 6284
08-29 09:54:06.493   324  1385 V AudioFlinger:  decremented refcount to 0
08-29 09:54:06.493   324  1385 V AudioFlinger: purging stale effects
08-29 09:54:06.493   324  1385 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 09:54:06.493   324  1385 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 09:54:06.493   324  1385 V AudioFlinger: PlaybackThread::Track destructor
08-29 09:54:06.493   324  1273 V AudioPolicyService: AudioCommandThread() waking up
08-29 09:54:06.493   324  1385 V AudioFlinger: removeClient_l() pid 6284, calling pid 324
08-29 09:54:06.493   324  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 09:54:06.493   324  1273 V AudioPolicyManager: releaseOutput() 2
,08-29 09:54:06.493   324  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 09:54:06.493  6284  6284 V Avrcp   : make
08-29 09:54:06.494  6284  6284 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 09:54:06.494  6284  6284 I bluedroid-qcom: get_profile_interface avrcp
08-29 09:54:06.496  6515  6515 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3c6e562b
08-29 09:54:06.496  6515  6515 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 09:54:06.496  6515  6515 D AppUp4:CustFacade: isPhone : true
08-29 09:54:06.496  6515  6515 D AppUp4:CustModeStarterReceiver: begin check event
08-29 09:54:06.497  1036  1996 W Process : Unable to open /proc/6552/status
,08-29 09:54:06.497  6515  6515 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 09:54:06.497  6515  6515 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-29 09:54:06.500  6284  6284 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 09:54:06.503  6284  6284 E AudioManager: No RCC entry present to update
08-29 09:54:06.503  6284  6284 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 09:54:06.505  6284  6284 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 09:54:06.506  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 09:54:06.506  6284  6284 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 09:54:06.509  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 09:54:06.515  6515  6549 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-29 09:54:06.516  6515  6549 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 09:54:06.516  6515  6549 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 09:54:06.549  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:06.550  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 09:54:06.554  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 09:54:06.562  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:54:06.572  4228  6555 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 09:54:06.577  4228  6556 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:06.578  4228  6556 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 09:54:06.611  1036  2051 V SIM_STK : Menu title from STK is T-Mobile
,08-29 09:54:06.611  1036  2051 V SIM_STK : Menu title from STK is T-Mobile
08-29 09:54:06.620  1036  2017 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6557 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 09:54:06.664  1036  1642 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 09:54:06.670  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-29 09:54:06.673  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 09:54:06.673  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 09:54:06.674  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 09:54:06.674  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 09:54:06.674  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 09:54:06.674  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 09:54:06.674  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 09:54:06.674  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 09:54:06.674  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 09:54:06.674  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 09:54:06.674  6284  6284 I BluetoothA2dpServiceJni: classInitNative
08-29 09:54:06.674  6284  6284 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:54:06.674  6284  6284 D A2dpStateMachine: make
,08-29 09:54:06.676  6284  6284 I bluedroid-qcom: get_profile_interface a2dp
08-29 09:54:06.676  6284  6575 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 09:54:06.677  6557  6557 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:54:06.678  6557  6557 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 09:54:06.678  6284  6284 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:54:06.679  6284  6284 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 09:54:06.679  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.680  6557  6557 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 09:54:06.679  6284  6574 D A2dpStateMachine: Enter Disconnected: -2
08-29 09:54:06.680  6284  6284 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 09:54:06.680  6557  6557 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 09:54:06.681  6284  6284 D HidService: Received start request. Starting profile...
08-29 09:54:06.681  6284  6284 I bluedroid-qcom: get_profile_interface hidhost
08-29 09:54:06.681  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.682  6284  6284 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 09:54:06.683  6284  6284 D HealthService: Received start request. Starting profile...
,08-29 09:54:06.685  6284  6284 I bluedroid-qcom: get_profile_interface health
08-29 09:54:06.685  6284  6284 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 09:54:06.685  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.685  6284  6284 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 09:54:06.687  6284  6284 D PanService: Received start request. Starting profile...
08-29 09:54:06.687  6284  6284 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 09:54:06.687  6284  6284 I bluedroid-qcom: get_profile_interface pan
08-29 09:54:06.695  6284  6284 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 09:54:06.695  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
,08-29 09:54:06.696  6284  6284 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 09:54:06.701  6284  6284 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 09:54:06.702  6284  6284 D BtGatt.GattService: Received start request. Starting profile...
08-29 09:54:06.702  6284  6284 D BtGatt.GattService: start()
08-29 09:54:06.702  6284  6284 I bluedroid-qcom: get_profile_interface gatt
08-29 09:54:06.702  6284  6284 D BtGatt.AdvertiseManager: advertise manager created
08-29 09:54:06.709  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
,08-29 09:54:06.711  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.711  6284  6284 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 09:54:06.713  6284  6284 V BluetoothMapService: BluetoothMapBinder()
08-29 09:54:06.713  6284  6284 D BluetoothMapService: Received start request. Starting profile...
08-29 09:54:06.714  6284  6284 D BluetoothMapService: start()
08-29 09:54:06.717  6284  6284 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 09:54:06.717  6284  6284 D BluetoothMapEmailAppObserver: createReceiver()
08-29 09:54:06.718  6284  6284 D BluetoothMapEmailAppObserver: initObservers()
,08-29 09:54:06.719  6284  6284 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 09:54:06.727  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:06.728  6284  6284 D HeadsetStateMachine: Proxy object connected
08-29 09:54:06.728  6284  6284 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 09:54:06.729  6284  6284 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 09:54:06.730  6284  6548 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 09:54:06.730  6284  6548 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 09:54:06.730  6284  6548 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 09:54:06.734  6284  6284 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 09:54:06.737  6284  6284 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 09:54:06.740  6284  6284 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 09:54:06.743  6284  6284 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 09:54:06.746  6284  6284 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 09:54:06.747  6284  6284 V PanService: [BTUI] SIM Extra State :ABSENT
,08-29 09:54:06.751  6284  6284 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:06.758  6284  6284 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 09:54:06.758  6284  6284 V BluetoothMapService: Handler(): got msg=1
08-29 09:54:06.759  6284  6540 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 09:54:06.759  6284  6540 I bluedroid-qcom: enable
,08-29 09:54:06.759  6284  6284 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 09:54:06.759  6284  6284 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 09:54:06.759  6284  6284 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 09:54:06.759  6284  6540 I bt_hci_bdroid: init
08-29 09:54:06.759  6284  6284 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:06.759  6284  6582 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 09:54:06.760  6284  6582 I bt-btu  : btu_task pending for preload complete event
08-29 09:54:06.760  6284  6284 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 09:54:06.760  6284  6540 I bt_vendor: bt-vendor : init
08-29 09:54:06.760  6284  6540 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 09:54:06.760  6284  6540 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 09:54:06.760  6284  6540 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 09:54:06.760  6284  6540 D bt_userial_mct: userial_init
08-29 09:54:06.761  6284  6540 D bt_hci_bdroid: set_power 1
08-29 09:54:06.761  6284  6540 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 09:54:06.761  6284  6540 I bt_vendor: Starting hciattach daemon
08-29 09:54:06.761  6284  6540 I bt_vendor: try to set true
08-29 09:54:06.764  6557  6557 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-29 09:54:06.754  6585  6585 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:06.754  6585  6585 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:06.778  6557  6557 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 09:54:06.793  6587  6587 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 09:54:06.820  6557  6557 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 09:54:06.855  6593  6593 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 09:54:06.860  6557  6557 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 09:54:06.860  6557  6557 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 09:54:06.869  6594  6594 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 09:54:06.897  6597  6597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 09:54:06.908  6600  6600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-29 09:54:06.921  6601  6601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 09:54:06.935  6602  6602 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 09:54:06.955  6604  6604 I libmdmdetect: ESOC framework not supported
08-29 09:54:06.956  6604  6604 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 09:54:06.964  6604  6604 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 09:54:06.964  6604  6604 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 09:54:06.964  6604  6604 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 09:54:06.964  6604  6604 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 09:54:06.964  6604  6604 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 09:54:06.964  6604  6604 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 09:54:06.964  6604  6604 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 09:54:06.976  6557  6557 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 09:54:07.007  6557  6557 I HubEmail: JNI_OnLoad()
08-29 09:54:07.007  6557  6557 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-29 09:54:07.007  6557  6557 I HubEmail: registerNatives()
,08-29 09:54:07.007  6557  6557 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 09:54:07.007  6557  6557 I HubEmail: registerNativeMethods()
08-29 09:54:07.007  6557  6557 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 09:54:07.007  6557  6557 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-29 09:54:07.016  6604  6605 E QC-QMI  : qmi_client [6604] 14: failed to locate client data
08-29 09:54:07.016   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[11:Try again]
08-29 09:54:07.017   483   483 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-29 09:54:07.018  3292  3292 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 09:54:07.018  6557  6609 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:07.019  3292  3292 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:07.025  6260  6607 W FormManager: Network not available. Please check & try again.
08-29 09:54:07.025  3292  3292 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 09:54:07.026  3292  3292 D PhoneState: setPdpRejectCasuse : false
,08-29 09:54:07.102  1036  1052 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6611 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 09:54:07.111  6260  6608 V FormManager: Network unavailable.
08-29 09:54:07.114  6260  6608 V FormManager: Network unavailable.
08-29 09:54:07.120  1036  1924 I ActivityManager: Killing 2130:com.lge.music/u0a34 (adj 15): empty #17
,08-29 09:54:07.127  6616  6616 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
08-29 09:54:07.137  6626  6626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 09:54:07.151   324  2128 V AudioFlinger: 2130 died, releasing its sessions
08-29 09:54:07.151   324  2128 V AudioFlinger:  pid 1854 @ 0
08-29 09:54:07.151   324  2128 V AudioFlinger:  pid 3292 @ 1
08-29 09:54:07.151   324  2128 V AudioFlinger:  pid 3292 @ 2
,08-29 09:54:07.163  6284  6540 I bt_vendor: bluetooth satus is on
08-29 09:54:07.163  6284  6540 D bt_hci_bdroid: preload
08-29 09:54:07.163  6284  6584 D bt_userial_mct: userial_open(port:0)
,08-29 09:54:07.163  6284  6584 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 09:54:07.169  6284  6584 I bt_vendor: Done intiailizing UART
08-29 09:54:07.169  6284  6584 I bt_vendor: Done intiailizing UART
08-29 09:54:07.169  6284  6584 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 09:54:07.170  6284  6584 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 09:54:07.170  6284  6582 I bt-btu  : btu_task received preload complete event
08-29 09:54:07.170  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 09:54:07.170  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 09:54:07.172  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 09:54:07.174  6284  6632 D bt_userial_mct: Entering userial_read_thread()
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 09:54:07.175  6284  6582 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 09:54:07.187  1036  1996 W libprocessgroup: failed to open /acct/uid_10034/pid_2130/cgroup.procs: No such file or directory
,08-29 09:54:07.229  6284  6582 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 09:54:07.229  6284  6582 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f4061 
08-29 09:54:07.229  6284  6582 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f4061 
,08-29 09:54:07.254  6284  6543 E bt-btif : Calling BTA_HhEnable
08-29 09:54:07.254  6284  6543 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x0019:0x2140040
,08-29 09:54:07.254  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 09:54:07.254  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 09:54:07.254  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 09:54:07.254  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 09:54:07.254  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-29 09:54:07.254  6284  6543 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 09:54:07.269  6284  6582 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 09:54:07.269  6284  6582 W bt-smp  : Plain text(LSB ~ MSB) = fe ed 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 09:54:07.269  6284  6582 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 cb 26 62 eb 2d 11 5c 25 9d 8b 36 a2 97 7b 72 
08-29 09:54:07.269  6284  6582 W bt-btm  : Stopping oneshot timer
,08-29 09:54:07.420  1036  1642 I art     : Explicit concurrent mark sweep GC freed 131625(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.107ms total 210.966ms
,08-29 09:54:07.421  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 09:54:07.421  6284  6543 D BluetoothAdapterProperties: Name is: G3
08-29 09:54:07.423  6284  6543 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:54:07.423  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 09:54:07.423  6284  6543 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:54:07.423  6284  6543 D bt_hci_bdroid: postload
08-29 09:54:07.424  6284  6543 D bte_conf: Device ID record 1 : primary
08-29 09:54:07.424  6284  6543 D bte_conf:   vendorId            = 00c4
08-29 09:54:07.424  6284  6543 D bte_conf:   vendorIdSource      = 0001
08-29 09:54:07.424  6284  6543 D bte_conf:   product             = 13a1
08-29 09:54:07.424  6284  6543 D bte_conf:   version             = 1000
08-29 09:54:07.424  6284  6543 D bte_conf:   clientExecutableURL = 
08-29 09:54:07.424  6284  6543 D bte_conf:   serviceDescription  = 
08-29 09:54:07.424  6284  6543 D bte_conf:   documentationURL    = 
08-29 09:54:07.424  6284  6584 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 09:54:07.424  6284  6543 D bte_conf: bte_load_did_conf no section named DID2.
08-29 09:54:07.424  6284  6582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 09:54:07.427  6284  6540 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 09:54:07.427  6284  6584 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 09:54:07.427  6284  6584 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 09:54:07.427  6284  6540 D BluetoothAdapterProperties: ScanMode =  20
08-29 09:54:07.427  6284  6540 D BluetoothAdapterProperties: State =  11
08-29 09:54:07.428  6284  6584 D bt_hci_bdroid: Used up Tx Cmd credits
,08-29 09:54:07.428  6284  6584 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 09:54:07.428  6284  6540 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 09:54:07.428  6284  6632 E bt_mct  : hci lib postload completed
08-29 09:54:07.424  6637  6637 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:07.430  6284  6540 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 09:54:07.430  6284  6540 D BluetoothAdapterProperties: Setting state to 12
08-29 09:54:07.424  6637  6637 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:07.430  6284  6540 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 09:54:07.431  6284  6543 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 09:54:07.432  6284  6543 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 09:54:07.433  1036  1118 D BluetoothManagerService: Message: 60
08-29 09:54:07.433  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 09:54:07.433  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-29 09:54:07.435  6284  6540 I BluetoothAdapterState: Entering On State
08-29 09:54:07.438  6284  6540 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 09:54:07.438  6284  6540 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 09:54:07.438  6284  6540 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 09:54:07.439  6284  6540 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 09:54:07.440  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:07.440  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:07.440  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:07.440  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:07.440  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:07.440  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:07.440  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:07.440  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:07.442  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:07.446  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:07.446  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:07.446  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:07.446  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:07.446  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:07.446  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:07.446  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:07.446  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:07.447  6144  6159 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:54:07.448  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:07.450  6144  6160 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:54:07.450  6144  6160 D BluetoothPan: onBluetoothStateChange call bindService
08-29 09:54:07.454  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:07.457  6144  6160 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 09:54:07.458  1036  1036 D BluetoothA2dp: Proxy object connected
08-29 09:54:07.462  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:07.463  6144  6639 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:54:07.464  1036  1036 D BluetoothHeadset: Proxy object connected
08-29 09:54:07.466  6284  6543 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:54:07.466  6284  6543 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 09:54:07.468  1854  2640 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:07.474  6144  6144 D BluetoothInputDevice: Proxy object connected
08-29 09:54:07.474  6144  6144 D HidProfile: Bluetooth service connected
08-29 09:54:07.474  1854  1854 D BluetoothHeadset: Proxy object connected
,08-29 09:54:07.478  1854  2445 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:07.481  1854  1854 D BluetoothHeadset: Proxy object connected
08-29 09:54:07.481  1854  4323 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:07.483  1854  1854 D BluetoothHeadset: Proxy object connected
08-29 09:54:07.483  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 09:54:07.483  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 09:54:07.484  6144  6144 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:54:07.484  6144  6144 D PanProfile: Bluetooth service connected
08-29 09:54:07.485  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 09:54:07.486  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.486  6284  6540 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-29 09:54:07.490  1943  2133 D LGBluetoothAPIService: Message: 1
08-29 09:54:07.490  1943  2133 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-29 09:54:07.494  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 09:54:07.497  6284  6284 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.497  6284  6284 D BluetoothMapService: STATE_ON
08-29 09:54:07.498  1036  1118 D BluetoothManagerService: Message: 40
08-29 09:54:07.498  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 09:54:07.502  6643  6643 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 09:54:07.503  6144  6144 D BluetoothMap: Proxy object connected
08-29 09:54:07.503  6144  6144 D MapProfile: Bluetooth service connected
08-29 09:54:07.503  6144  6144 D BluetoothMap: getConnectedDevices()
,08-29 09:54:07.506  5921  5921 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 09:54:07.508  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:07.510  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:07.510  6284  6284 V BluetoothPbapService: Pbap Service onCreate
08-29 09:54:07.510  6284  6284 V BluetoothPbapService: Starting PBAP service
08-29 09:54:07.511  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:07.511  6284  6284 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 09:54:07.511  6284  6284 V BluetoothMapService: Handler(): got msg=1
08-29 09:54:07.511  6284  6300 V BluetoothMapService: getConnectedDevices()
08-29 09:54:07.511  6284  6284 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 09:54:07.512  6284  6284 V BluetoothPbapService: Pbap Service onBind
08-29 09:54:07.512  1943  2133 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 09:54:07.512  6284  6284 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.512  6284  6284 V BluetoothPbapService: state: 12
08-29 09:54:07.513  6284  6284 V BluetoothPbapService: Handler(): got msg=1
08-29 09:54:07.513  6284  6648 D BluetoothMapMasInstance: MAS initSocket()
08-29 09:54:07.513  6284  6284 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 09:54:07.514  6284  6648 D BluetoothMapMasInstance:   masId = 00
08-29 09:54:07.514  6284  6648 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 09:54:07.514  6284  6648 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 09:54:07.514  6284  6648 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 09:54:07.514  6284  6284 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 09:54:07.515  6284  6284 D LGBluetoothAPIServer: [BTUI] onBind()
,08-29 09:54:07.516  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:07.516  6144  6144 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 09:54:07.517  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 09:54:07.517  1943  2133 D LGBluetoothAPIService: Message: 100
08-29 09:54:07.517  1943  2133 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 09:54:07.518  6284  6648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:07.518  6284  6649 V BluetoothPbapService: Pbap Service initSocket
08-29 09:54:07.518  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:07.519  6284  6648 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 09:54:07.520  6284  6648 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 09:54:07.520  6284  6648 D BluetoothMapMasInstance: Accepting socket connection...
08-29 09:54:07.520  6284  6543 D BluetoothAdapterProperties: Scan Mode:21
08-29 09:54:07.520  6284  6543 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 09:54:07.521  6144  6144 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 09:54:07.521  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:07.522  1036  1118 D BluetoothManagerService: Message: 30
08-29 09:54:07.523  1036  1118 D BluetoothManagerService: Message: 30
08-29 09:54:07.524  6284  6649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:07.525  6284  6649 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 09:54:07.525  6284  6649 V BluetoothPbapService: Succeed to create listening socket 
08-29 09:54:07.525  6284  6649 V BluetoothPbapService: Accepting socket connection...
08-29 09:54:07.526  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:07.529  6144  6144 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 09:54:07.531  6144  6144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 09:54:07.534  6144  6144 D BluetoothPbap: Proxy object connected
08-29 09:54:07.535  6284  6284 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 09:54:07.535  6284  6284 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.535  6284  6284 V BluetoothPbapReceiver: ***********state = 12
08-29 09:54:07.536  6144  6144 D PbapServerProfile: Bluetooth service connected
08-29 09:54:07.536  6144  6144 D BluetoothA2dp: Proxy object connected
08-29 09:54:07.536  6144  6144 D A2dpProfile: Bluetooth service connected
08-29 09:54:07.540  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:54:07.541  2214  2214 D c       : Getting all permits...
08-29 09:54:07.541  2214  2214 D a       : Opening database...
,08-29 09:54:07.542  6144  6144 D BluetoothHeadset: Proxy object connected
08-29 09:54:07.543  6144  6144 D HeadsetProfile: Bluetooth service connected
08-29 09:54:07.546  2214  2214 D a       : Opening database auth.proximity.permit_store...
08-29 09:54:07.547  2214  2214 D a       : Closing database...
08-29 09:54:07.548  6144  6144 D DockEventReceiver: finishStartingService: stopping service
08-29 09:54:07.557  6144  6144 D BluetoothPermissionRequest: onReceive
,08-29 09:54:07.559  6144  6144 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 09:54:07.561  6144  6144 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 09:54:07.563  6284  6284 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 09:54:07.565  6284  6284 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 09:54:07.570  6284  6284 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 09:54:07.587  6611  6611 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:54:07.587  6611  6611 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 09:54:07.589  6284  6284 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 09:54:07.589  6284  6284 V BtOppService: onCreate
08-29 09:54:07.591  6611  6611 D PhoneMonitor: Register our PhoneStateListener
08-29 09:54:07.593  6284  6284 V BluetoothOppNotification: send message
08-29 09:54:07.596  6284  6284 V BtOppService: Starting RfcommListener
08-29 09:54:07.602  6284  6284 D BluetoothOppPreference: Dumping Names:  
08-29 09:54:07.602  6284  6284 D BluetoothOppPreference: {}
08-29 09:54:07.602  6284  6284 D BluetoothOppPreference: Dumping Channels:  
08-29 09:54:07.602  6284  6284 D BluetoothOppPreference: {}
08-29 09:54:07.602  6284  6284 V BtOppService: onStartCommand
,08-29 09:54:07.605  6284  6658 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 09:54:07.607  6611  6611 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 09:54:07.607  6284  6284 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.608  6284  6284 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 09:54:07.609  6284  6658 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 09:54:07.609  6611  6611 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 09:54:07.609  6284  6655 V BtOppService: Deleted complete outbound shares, number =  0
08-29 09:54:07.614  6284  6655 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-29 09:54:07.616  6284  6284 V BluetoothOppNotification: new notify threadi!
08-29 09:54:07.617  6284  6284 V BluetoothOppNotification: send delay message
08-29 09:54:07.618  6284  6655 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 09:54:07.619  6284  6660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 09:54:07.619  6284  6655 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e063b73 on behalf of 
08-29 09:54:07.619  6284  6284 V BtOppService: start RfcommListener
08-29 09:54:07.619  6284  6658 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d9aabe2 on behalf of 
08-29 09:54:07.622  6284  6284 V BtOppService: RfcommListener started
08-29 09:54:07.622  6284  6284 V BtOppService: ContentObserver received notification
08-29 09:54:07.624  6284  6661 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 09:54:07.624  6611  6611 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 09:54:07.625  6611  6611 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 09:54:07.625  6284  6658 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 09:54:07.625  6284  6658 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 09:54:07.625  6611  6611 D TelephonyAutoProfiling: [parse] Load xml
,08-29 09:54:07.628  6284  6658 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cb68a30 on behalf of 
08-29 09:54:07.629  6284  6658 V BluetoothOppNotification: update too frequent, put in queue
08-29 09:54:07.629  6284  6660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28f3a6a9 on behalf of 
08-29 09:54:07.630  6284  6660 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 09:54:07.631  6284  6658 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 09:54:07.632  6284  6660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 09:54:07.633  6284  6660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c3ba42e on behalf of 
,08-29 09:54:07.634  6284  6660 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 09:54:07.636  6284  6660 V BluetoothOppNotification: outbound notification was removed.
08-29 09:54:07.636  6284  6660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 09:54:07.636  6611  6611 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-29 09:54:07.636  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-29 09:54:07.636  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 09:54:07.636  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 09:54:07.637  6611  6611 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 09:54:07.637  6611  6611 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-29 09:54:07.638  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:07.638  6284  6284 V BluetoothFtpService: Ftp Service onCreate
08-29 09:54:07.638  6284  6284 I BluetoothFtpService: Ftp Service onCreate
08-29 09:54:07.639  6284  6660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a32195c on behalf of 
,08-29 09:54:07.640  6284  6284 V BluetoothFtpService: Ftp Service onStartCommand
08-29 09:54:07.640  6284  6284 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.641  6284  6284 V BluetoothFtpService: Starting Listening on sockets
,08-29 09:54:07.641  6284  6284 V BtOppService: ContentObserver received notification
08-29 09:54:07.641  6284  6284 V BluetoothFtpService: Handler(): got msg=1
,08-29 09:54:07.642  6284  6284 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 09:54:07.642  6284  6284 V BluetoothFtpService: Ftp Service initSocket
,08-29 09:54:07.643  6284  6660 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 09:54:07.645  6284  6663 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 09:54:07.645  6284  6663 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 09:54:07.645  6284  6660 V BluetoothOppNotification: inbound notification was removed.
08-29 09:54:07.645  6284  6660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 09:54:07.646  6284  6663 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34370465 on behalf of 
08-29 09:54:07.646  6284  6660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9e1d53a on behalf of 
08-29 09:54:07.647  6284  6663 V BluetoothOppNotification: update too frequent, put in queue
08-29 09:54:07.647  6611  6611 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-29 09:54:07.647  6284  6663 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 09:54:07.654  1036  2017 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6664 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 09:54:07.654  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:07.655  1036  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:07.655  6284  6284 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:07.656  6284  6661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:07.656  1036  2017 I ActivityManager: Killing 5876:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 09:54:07.686  1036  1942 W libprocessgroup: failed to open /acct/uid_10061/pid_5876/cgroup.procs: No such file or directory
,08-29 09:54:07.687  6284  6661 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-29 09:54:07.688  6284  6661 V BtOppRfcommListener: Started RFCOMM listener....
08-29 09:54:07.688  6284  6661 I BtOppRfcommListener: Accept thread started.
08-29 09:54:07.688  6284  6661 V BtOppRfcommListener: Accepting connection...
,08-29 09:54:07.688  6284  6284 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-29 09:54:07.689  6284  6284 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 09:54:07.690  6284  6681 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 09:54:07.694  6284  6284 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 09:54:07.694  6284  6284 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 09:54:07.694  6284  6284 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 09:54:07.694  6284  6284 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.694  6284  6284 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 09:54:07.694  6284  6284 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 09:54:07.710  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:07.710  6284  6284 V BluetoothSapService: Sap Service onCreate
,08-29 09:54:07.712  6284  6284 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.712  6284  6284 V BluetoothSapService: state: 12
08-29 09:54:07.712  6284  6284 V BluetoothSapService: Starting SAP server process
08-29 09:54:07.714  6284  6284 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-29 09:54:07.715  6284  6683 V BluetoothSapService: Sap Service initRfcommSocket
08-29 09:54:07.716  1036  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:07.714  6682  6682 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:07.714  6682  6682 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:07.716  6284  6683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:07.719  6284  6683 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 09:54:07.719  6284  6683 V BluetoothSapService: Succeed to create listening socket 
08-29 09:54:07.719  6284  6683 V BluetoothSapService: Accepting socket connection...
08-29 09:54:07.728  6682  6682 V BT_SAP  : Event pipe created
08-29 09:54:07.728  6682  6682 V BT_SAP  : create_server_socket qcom.sap.server
08-29 09:54:07.728  6682  6682 V BT_SAP  : created socket fd 6
,08-29 09:54:08.080  1036  1923 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6691 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 09:54:08.086  1036  1923 I ActivityManager: Killing 5996:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-29 09:54:08.146  1036  1987 W libprocessgroup: failed to open /acct/uid_10080/pid_5996/cgroup.procs: No such file or directory
,08-29 09:54:08.186  6691  6691 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,08-29 09:54:08.189  6691  6691 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,08-29 09:54:08.205  6691  6691 V DrmService: Service onCreate
08-29 09:54:08.205  6691  6691 D DrmService: Received new request = 2
,08-29 09:54:08.210  6691  6708 I DrmSntpClient: Start Sync process
08-29 09:54:08.210  6691  6708 D DrmSntpClient: Server : 0
08-29 09:54:08.241  1036  1942 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6709 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:54:08.245  6691  6708 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-29 09:54:08.246  6691  6691 D DrmService: Completed !! request = 2
08-29 09:54:08.246  6691  6691 D DrmService: Request count = 0
08-29 09:54:08.250  6691  6691 V DrmService: Service onDestroy
08-29 09:54:08.252  1036  1051 I ActivityManager: Killing 6017:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-29 09:54:08.307  1036  1924 W libprocessgroup: failed to open /acct/uid_10097/pid_6017/cgroup.procs: No such file or directory
,08-29 09:54:08.331  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:54:08.331  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:08.343  6709  6709 I art     : Almond Protected OAT
,08-29 09:54:08.373  1036  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 09:54:08.374  1036  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 09:54:08.401  6709  6709 D WeatherApplication: removeAccount
,08-29 09:54:08.402  6709  6709 D WeatherApplication: Account.length = 0
08-29 09:54:08.403  6709  6709 E WeatherApplication: OPERATOR:OPEN
,08-29 09:54:08.409  6709  6709 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:8
,08-29 09:54:08.413  6709  6709 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 09:54:08.413  6709  6709 D Weather.Utils: 2 : All the weather widget is gone.
08-29 09:54:08.415  6709  6709 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 09:54:08.418  6709  6709 D WeatherAncestor: connectivity changed - connection : true
08-29 09:54:08.419  6709  6709 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-29 09:54:08.431  6709  6709 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 09:54:08.431  6709  6709 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-29 09:54:08.431  6709  6709 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-29 09:54:08.453  6709  6709 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 09:54:08.453  6709  6709 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:8
,08-29 09:54:08.504  1036  1576 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6727 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 09:54:08.504  1036  1576 I ActivityManager: Killing 6051:com.lge.eula/1000 (adj 15): empty #17
,08-29 09:54:08.554  1036  2017 W libprocessgroup: failed to open /acct/uid_1000/pid_6051/cgroup.procs: No such file or directory
,08-29 09:54:08.619  6284  6284 V BluetoothOppNotification: new notify threadi!
08-29 09:54:08.619  6284  6284 V BluetoothOppNotification: send delay message
,08-29 09:54:08.622  6284  6744 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 09:54:08.624  6284  6744 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32880b06 on behalf of 
08-29 09:54:08.626  6284  6744 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 09:54:08.628  6284  6744 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 09:54:08.630  6284  6744 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ecb5c7 on behalf of 
08-29 09:54:08.632  6284  6744 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-29 09:54:08.635  6284  6744 V BluetoothOppNotification: outbound notification was removed.
08-29 09:54:08.635  6284  6744 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 09:54:08.637  6284  6744 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a1637f4 on behalf of 
08-29 09:54:08.638  6284  6744 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 09:54:08.640  6284  6744 V BluetoothOppNotification: inbound notification was removed.
08-29 09:54:08.641  6284  6744 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 09:54:08.643  6284  6744 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b3a5b1d on behalf of 
,08-29 09:54:08.665   282   415 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 09:54:08.665   282   415 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 09:54:08.665   282   415 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 09:54:08.668  6727  6746 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 09:54:08.678   282   415 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 09:54:08.678   282   415 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 09:54:08.678   282   415 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 09:54:08.680  6727  6746 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 09:54:08.688   282   415 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 09:54:08.689   282   415 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 09:54:08.689   282   415 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 09:54:08.689  6727  6750 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 09:54:08.691   282   415 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 09:54:08.691   282   415 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 09:54:08.691   282   415 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 09:54:08.694  6727  6750 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 09:54:08.918  6727  6727 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-29 09:54:08.930  6727  6727 I LibraryLoader: Loading: webviewchromium
,08-29 09:54:08.934  6727  6727 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9714-9718)
08-29 09:54:08.934  6727  6727 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 09:54:08.941  6727  6727 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3df5d564}
08-29 09:54:08.943  6727  6727 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 09:54:08.945  6727  6727 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 09:54:08.969  6727  6727 I BrowserStartupController: Initializing chromium process, renderers=0
,08-29 09:54:08.970  6727  6727 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 09:54:08.983  6727  6727 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 09:54:08.984  6727  6727 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
08-29 09:54:08.984  6727  6727 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
,08-29 09:54:08.991   324  1385 V AudioPolicyService: registerClient() client 0xb1020ec0, uid 10093
08-29 09:54:08.992  6727  6770 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 09:54:09.012  6727  6727 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 09:54:09.012  6727  6727 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 09:54:09.012  6727  6727 I Adreno-EGL: Build Date: 12/12/14 금
08-29 09:54:09.012  6727  6727 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 09:54:09.012  6727  6727 I Adreno-EGL: Remote Branch: 
08-29 09:54:09.012  6727  6727 I Adreno-EGL: Local Patches: 
08-29 09:54:09.012  6727  6727 I Adreno-EGL: Reconstruct Branch: 
,08-29 09:54:09.119  6727  6727 I NSApplication: Starting up...
,08-29 09:54:09.188  1036  1942 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6783 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 09:54:09.192  1036  1923 I ActivityManager: Killing 6070:com.lge.bnr/1000 (adj 15): empty #17
08-29 09:54:09.238  1036  1783 W libprocessgroup: failed to open /acct/uid_1000/pid_6070/cgroup.procs: No such file or directory
,08-29 09:54:09.271  6783  6783 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 09:54:09.327  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 09:54:09.327  1036  1642 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1f0a70b9 mBinding = false
,08-29 09:54:09.347  1036  1118 D BluetoothManagerService: Message: 2
08-29 09:54:09.347  1036  1118 D BluetoothManagerService: Sending off request.
,08-29 09:54:09.348  6284  6299 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 09:54:09.348  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 09:54:09.349  6284  6540 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 09:54:09.349  6284  6540 D BluetoothAdapterProperties: Setting state to 13
08-29 09:54:09.349  6284  6540 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 09:54:09.349  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 09:54:09.349  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-29 09:54:09.349  6284  6540 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 09:54:09.349  6284  6540 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 09:54:09.351  6284  6543 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:54:09.352  6284  6540 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 09:54:09.354  6284  6649 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:54:09.356  6284  6661 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 09:54:09.356  6284  6681 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:54:09.357  6284  6683 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 09:54:09.358  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 09:54:09.358  6284  6582 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 09:54:09.359  6284  6648 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 09:54:09.359  6284  6648 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:54:09.359  6284  6648 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 09:54:09.359  6284  6648 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 09:54:09.359  6284  6648 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 09:54:09.359  6284  6648 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 09:54:09.359  6284  6648 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 09:54:09.359  6284  6648 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 09:54:09.360  6284  6540 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 09:54:09.366  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 09:54:09.367  6284  6582 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 09:54:09.369  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:09.369  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:09.369  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:09.369  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:09.369  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:09.369  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:09.369  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:09.369  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:09.369  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:09.371  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:09.371  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:09.373  1036  1118 D BluetoothManagerService: Message: 60
08-29 09:54:09.373  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 09:54:09.373  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 09:54:09.375  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:09.375  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:09.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:09.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:09.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:09.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:09.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:09.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:09.375  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:09.376  5921  5921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:54:09.376  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:09.377  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:09.381  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 09:54:09.383  6284  6284 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:09.383  6284  6284 D BluetoothMapService: STATE_TURNING_OFF
08-29 09:54:09.383  6284  6284 V BluetoothMapService: Handler(): got msg=4
08-29 09:54:09.384  6284  6284 D BluetoothMapService: MAP Service closeService in
08-29 09:54:09.384  6284  6284 D BluetoothMapMasInstance: MAP Service shutdown
08-29 09:54:09.384  6284  6284 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 09:54:09.384  6284  6284 V BluetoothMapService: MAP Service closeService out
08-29 09:54:09.387  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:09.388  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:09.388  6284  6284 V BtOppService: Receiver DISABLED_ACTION 
08-29 09:54:09.389  6284  6284 I BtOppRfcommListener: stopping Accept Thread
08-29 09:54:09.389  6284  6284 V BtOppRfcommListener: close mBtServerSocket
08-29 09:54:09.390  6284  6661 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 09:54:09.390  6284  6284 V BtOppRfcommListener: waiting for thread to terminate
08-29 09:54:09.390  6284  6284 V BtOppRfcommListener: done waiting for thread to terminate
08-29 09:54:09.393  6284  6284 V BtOppService: onDestroy
,08-29 09:54:09.396  6284  6284 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 09:54:09.397  6144  6144 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 09:54:09.399  6144  6144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 09:54:09.408  6284  6284 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 09:54:09.409  6284  6284 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:09.409  6284  6284 V BluetoothPbapReceiver: ***********state = 13
,08-29 09:54:09.412  6284  6284 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 09:54:09.413  6284  6284 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:09.413  6284  6284 V BluetoothPbapService: state: 13
08-29 09:54:09.413  6284  6284 V BluetoothPbapService: Pbap Service closeService in
08-29 09:54:09.416  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:54:09.417  6144  6144 D DockEventReceiver: finishStartingService: stopping service
08-29 09:54:09.419  6144  6144 D BluetoothPbap: Proxy object disconnected
08-29 09:54:09.419  6144  6144 D PbapServerProfile: Bluetooth service disconnected
08-29 09:54:09.420  6284  6284 V BluetoothPbapService: successfully stopped pbap service
08-29 09:54:09.420  6284  6284 V BluetoothPbapService: Pbap Service closeService out
08-29 09:54:09.421  6284  6284 V BluetoothPbapService: Pbap Service onDestroy
08-29 09:54:09.421  6284  6284 V BluetoothPbapService: Pbap Service closeService in
08-29 09:54:09.421  6284  6284 V BluetoothPbapService: Pbap Service closeService out
08-29 09:54:09.421  6284  6284 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-29 09:54:09.444  6144  6144 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 09:54:09.452  6144  6144 D BluetoothPermissionRequest: onReceive
08-29 09:54:09.452  6144  6144 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 09:54:09.459  6144  6144 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 09:54:09.469  6284  6284 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 09:54:09.469  6284  6284 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 09:54:09.470  6284  6284 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 09:54:09.474  6284  6284 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:09.474  6284  6284 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-29 09:54:09.475  6284  6284 V BluetoothFtpService: Ftp Service onStartCommand
08-29 09:54:09.476  6284  6284 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:09.476  6284  6284 V BluetoothFtpService: Ftp Service closeService
08-29 09:54:09.476  6284  6284 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 09:54:09.479  6284  6284 V BluetoothFtpService: successfully stopped ftp service
08-29 09:54:09.479  6284  6284 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 09:54:09.479  6284  6284 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 09:54:09.479  6284  6284 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 09:54:09.479  6284  6284 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:09.480  6284  6284 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 09:54:09.480  6284  6284 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 09:54:09.481  6284  6284 V BluetoothFtpService: Ftp Service onDestroy
08-29 09:54:09.481  6284  6284 V BluetoothFtpService: Ftp Service closeService
08-29 09:54:09.485  6284  6284 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:09.486  6284  6284 V BluetoothSapService: state: 13
08-29 09:54:09.486  6284  6284 V BluetoothSapService: Stopping SAP server process
08-29 09:54:09.487  6284  6284 V BluetoothSapService: Sap Service closeSapService in
08-29 09:54:09.487  6284  6284 V BluetoothSapService: Close listen Socket : 
08-29 09:54:09.487  6284  6284 V BluetoothSapService: Close rfcomm Socket : 
08-29 09:54:09.487  6284  6284 V BluetoothSapService: Close sapd  Socket : 
,08-29 09:54:09.490  6284  6284 V BluetoothSapService: Sap Service closeSapService out
08-29 09:54:09.490  6284  6284 V BluetoothSapService: Sap Service onDestroy
08-29 09:54:09.490  6284  6284 V BluetoothSapService: Sap Service closeSapService in
08-29 09:54:09.490  6284  6284 V BluetoothSapService: Close listen Socket : 
08-29 09:54:09.490  6284  6284 V BluetoothSapService: Close rfcomm Socket : 
08-29 09:54:09.490  6284  6284 V BluetoothSapService: Close sapd  Socket : 
08-29 09:54:09.491  6284  6284 V BluetoothSapService: Sap Service closeSapService out
08-29 09:54:09.621  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 09:54:09.624  3672  3706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 09:54:09.644  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:09.656  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-29 09:54:09.656  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:09.656  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 09:54:09.656  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 09:54:09.657  6515  6515 I AppUp4:CustModeStarterReceiver: onReceive
08-29 09:54:09.661  6515  6515 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3c6e562b
08-29 09:54:09.662  6515  6515 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 09:54:09.662  6515  6515 D AppUp4:CustFacade: isPhone : true
08-29 09:54:09.662  6515  6515 D AppUp4:CustModeStarterReceiver: begin check event
08-29 09:54:09.662  6515  6515 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 09:54:09.666  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:09.666  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 09:54:09.667  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 09:54:09.669  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:54:09.676  4228  6824 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 09:54:09.680  6557  6557 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 09:54:09.682  4228  6825 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:09.682  4228  6825 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 09:54:09.714  3292  3292 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 09:54:09.714  3292  3292 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:09.715  3292  3292 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-29 09:54:09.717  6557  6829 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:09.722  6260  6831 W FormManager: Network not available. Please check & try again.
08-29 09:54:09.723  6611  6611 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 09:54:09.723  6611  6611 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 09:54:09.725  6260  6832 V FormManager: Network unavailable.
08-29 09:54:09.734  6709  6709 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:9
,08-29 09:54:09.735  6260  6832 V FormManager: Network unavailable.
08-29 09:54:09.737  6709  6709 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 09:54:09.737  6709  6709 D Weather.Utils: 2 : All the weather widget is gone.
08-29 09:54:09.737  6709  6709 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 09:54:09.738  6709  6709 D WeatherAncestor: connectivity changed - connection : true
08-29 09:54:09.738  6709  6709 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1a294c21
08-29 09:54:09.739  6709  6709 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 09:54:09.739  6709  6709 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 09:54:09.739  6709  6709 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 09:54:09.739  6709  6709 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 09:54:09.739  6709  6709 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:9
08-29 09:54:09.767  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 09:54:09.770  3672  3706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 09:54:09.789  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:09.797  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 09:54:09.797  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:09.798  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 09:54:09.798  6515  6515 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 09:54:09.800  6515  6515 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 09:54:09.804  6515  6515 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3c6e562b
,08-29 09:54:09.804  6515  6515 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 09:54:09.804  6515  6515 D AppUp4:CustFacade: isPhone : true
08-29 09:54:09.804  6515  6515 D AppUp4:CustModeStarterReceiver: begin check event
08-29 09:54:09.805  6515  6515 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 09:54:09.809  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:09.809  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 09:54:09.811  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:54:09.813  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 09:54:09.820  4228  6834 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 09:54:09.820  6557  6557 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 09:54:09.826  4228  6835 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:09.826  4228  6835 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 09:54:09.842  6557  6836 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:09.847  3292  3292 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-29 09:54:09.847  3292  3292 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:09.847  3292  3292 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 09:54:09.854  6611  6611 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-29 09:54:09.855  6260  6839 W FormManager: Network not available. Please check & try again.
08-29 09:54:09.855  6611  6611 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 09:54:09.874  6260  6840 V FormManager: Network unavailable.
,08-29 09:54:09.879  6709  6709 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:9
,08-29 09:54:09.879  6260  6840 V FormManager: Network unavailable.
,08-29 09:54:09.882  6709  6709 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-29 09:54:09.882  6709  6709 D Weather.Utils: 2 : All the weather widget is gone.
,08-29 09:54:09.883  6709  6709 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-29 09:54:09.883  6709  6709 D WeatherAncestor: connectivity changed - connection : true,
08-29 09:54:09.883  6709  6709 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1a294c21
08-29 09:54:09.885  6709  6709 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-29 09:54:09.885  6709  6709 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4,
08-29 09:54:09.885  6709  6709 D ForecastDataCache: 2 : Cache is up-to-date, count: 0,
,08-29 09:54:09.885  6709  6709 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false,
08-29 09:54:09.886  6709  6709 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:9,
,08-29 09:54:10.264  6284  6543 D bt_hci_bdroid: cleanup
,08-29 09:54:10.286  6284  6584 I bt_lpm  : LPM is already off!!!
08-29 09:54:10.287  6284  6582 W bt-btif : ag scb idx 1 not allocated
08-29 09:54:10.287  6284  6582 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 09:54:10.287  6284  6582 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:54:10.288  6284  6582 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 09:54:10.289  6284  6632 I bt_userial_mct: exiting userial_read_thread
08-29 09:54:10.289  6284  6632 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-29 09:54:10.289  6284  6543 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0,
08-29 09:54:10.290  6284  6584 I bt_vendor: hw_epilog_process
08-29 09:54:10.290  6284  6543 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 09:54:10.290  6284  6543 D bt_userial_mct: userial_close
08-29 09:54:10.290  6284  6543 E bt_userial_mct: pthread_join() FAILED result:3
08-29 09:54:10.290  6284  6543 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 09:54:10.296  6284  6543 D bt_hci_bdroid: set_power 0
08-29 09:54:10.296  6284  6543 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 09:54:10.296  6284  6543 I bt_vendor: bluetooth satus is on
08-29 09:54:10.296  6284  6543 I bt_vendor: bt-vendor : resetting BT status
08-29 09:54:10.296  6284  6543 I bt_vendor: Starting hciattach daemon,
08-29 09:54:10.296  6284  6543 I bt_vendor: try to set false
,08-29 09:54:10.305  6284  6543 I bt_vendor: Starting hciattach daemon
08-29 09:54:10.305  6284  6543 I bt_vendor: try to set false
08-29 09:54:10.307  6284  6543 I bt_vendor: cleanup
08-29 09:54:10.308  6284  6582 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 09:54:10.308  6284  6543 I GKI_LINUX: GKI_exit_task 0 done
08-29 09:54:10.308  6284  6543 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 09:54:10.310  6284  6540 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 09:54:10.314  6284  6284 D HeadsetService: Received stop request...Stopping profile...
,08-29 09:54:10.319  6284  6284 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 09:54:10.319  6284  6284 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:54:10.319  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:10.320  6284  6548 D HeadsetStateMachine: Exit Disconnected: -1
08-29 09:54:10.327  6284  6540 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-29 09:54:10.329  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:10.329  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 09:54:10.325  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:10.330  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:10.331  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-29 09:54:10.332  6284  6284 D A2dpService: Received stop request...Stopping profile...
08-29 09:54:10.333  6284  6574 D A2dpStateMachine: Exit Disconnected: -1
08-29 09:54:10.334  6284  6284 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 09:54:10.336  6284  6284 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 09:54:10.336  6284  6284 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:54:10.336  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:10.337  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-29 09:54:10.337  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 09:54:10.338  6284  6284 D HidService: Received stop request...Stopping profile...
08-29 09:54:10.338  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:10.340  6284  6284 D HealthService: Received stop request...Stopping profile...
08-29 09:54:10.340  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
,08-29 09:54:10.344  6284  6284 D HeadsetStateMachine: Unbinding service...
08-29 09:54:10.348  6284  6284 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 09:54:10.348  6284  6284 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 09:54:10.348  6284  6284 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 09:54:10.348  6284  6284 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 09:54:10.348  6284  6284 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 09:54:10.348  6284  6284 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:54:10.348  6284  6284 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 09:54:10.349  6284  6284 D PanService: Received stop request...Stopping profile...
08-29 09:54:10.350  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:10.350  6284  6284 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 09:54:10.351  6284  6284 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 09:54:10.351  6284  6284 D BtGatt.GattService: stop()
08-29 09:54:10.351  6284  6284 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 09:54:10.353  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
,08-29 09:54:10.356  6284  6284 D BluetoothMapService: Received stop request...Stopping profile...
08-29 09:54:10.356  6284  6284 D BluetoothMapService: stop()
08-29 09:54:10.358  6284  6284 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 09:54:10.358  6284  6284 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 09:54:10.358  6284  6284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a294c21
08-29 09:54:10.360  6284  6284 I BluetoothA2dpServiceJni: cleanupNative
08-29 09:54:10.360  6284  6575 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 09:54:10.362  6284  6284 I GKI_LINUX: GKI_exit_task 2 done
08-29 09:54:10.363  6284  6284 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 09:54:10.363  6284  6284 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 09:54:10.363  6284  6284 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 09:54:10.363  6284  6284 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:54:10.363  6284  6284 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:54:10.364  6284  6284 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:54:10.364  6284  6284 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:54:10.364  6284  6284 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 09:54:10.366  6284  6284 V BluetoothMapService: Handler(): got msg=4
08-29 09:54:10.366  6284  6284 D BluetoothMapService: MAP Service closeService in
08-29 09:54:10.366  6284  6284 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 09:54:10.366  6284  6284 V BluetoothMapService: MAP Service closeService out
,08-29 09:54:10.369  6284  6540 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 09:54:10.369  6284  6540 D BluetoothAdapterProperties: Setting state to 10
08-29 09:54:10.369  6284  6540 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 09:54:10.371  1036  1118 D BluetoothManagerService: Message: 60
08-29 09:54:10.371  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 09:54:10.371  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 09:54:10.371  6284  6540 I BluetoothAdapterState: Entering OffState
08-29 09:54:10.372  6144  6159 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:54:10.373  6284  6284 D BluetoothMapService: cleanup()
08-29 09:54:10.373  6284  6284 D BluetoothMapService: MAP Service closeService in
08-29 09:54:10.373  6284  6284 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 09:54:10.373  6284  6284 V BluetoothMapService: MAP Service closeService out
08-29 09:54:10.374  6144  6159 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:54:10.375  6144  6159 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:54:10.376  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:54:10.376  6144  6159 D BluetoothMap: onBluetoothStateChange: up=false
08-29 09:54:10.377  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:54:10.377  6144  6159 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 09:54:10.377  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:54:10.381  1854  2640 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:54:10.382  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:54:10.382  6144  6159 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:54:10.383  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 09:54:10.384  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 09:54:10.385  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 09:54:10.385  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 09:54:10.386  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1f0a70b9 mBinding = false
08-29 09:54:10.386  1036  1118 D BluetoothManagerService: Sending unbind request.
08-29 09:54:10.391  6284  6543 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 09:54:10.393  6284  6284 I GKI_LINUX: GKI_exit_task 1 done
,08-29 09:54:10.393  6284  6284 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 09:54:10.394  6284  6284 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 09:54:10.394  6284  6284 I art     : --- WEIRD: removing null entry 248
08-29 09:54:10.394  6284  6284 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 09:54:10.395  6284  6284 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 09:54:10.395  6284  6284 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 09:54:10.397  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 09:54:10.399  6284  6284 I art     : System.exit called, status: 0
08-29 09:54:10.399  6284  6284 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 09:54:10.427   324  2128 V AudioFlinger: 6284 died, releasing its sessions
08-29 09:54:10.427   324  2128 V AudioFlinger:  pid 1854 @ 0
08-29 09:54:10.427   324  2128 V AudioFlinger:  pid 3292 @ 1
08-29 09:54:10.427   324  2128 V AudioFlinger:  pid 3292 @ 2
08-29 09:54:10.431  6144  6144 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-29 09:54:10.433  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-29 09:54:10.433  1943  2133 D LGBluetoothAPIService: Message: 101
08-29 09:54:10.434  1943  2133 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-29 09:54:10.434  1943  2133 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-29 09:54:10.434  1943  2133 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-29 09:54:10.534  1036  1924 I ActivityManager: Process com.android.bluetooth (pid 6284) has died
08-29 09:54:10.534  1036  1924 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-29 09:54:10.534  1036  1924 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-29 09:54:10.544  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 09:54:10.545  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:10.547  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:10.547  6144  6144 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 09:54:10.548  6144  6144 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 09:54:10.548  1943  2133 D LGBluetoothAPIService: Message: 2
08-29 09:54:10.548  1943  2133 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-29 09:54:10.550  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:10.556  6144  6144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 09:54:10.561  1603  1603 D BluetoothAdapter: 55090976: getState() :  mService = null. Returning STATE_OFF
08-29 09:54:10.561  1603  1603 D BluetoothAdapter: 55090976: getState() :  mService = null. Returning STATE_OFF
,08-29 09:54:10.610  1036  1783 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6871 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 09:54:10.612  6144  6144 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:10.689  6871  6871 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 09:54:10.690  6871  6871 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 09:54:10.690  6871  6871 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-29 09:54:10.691  6871  6871 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 09:54:10.712  6871  6871 D BluetoothAdapterApp: Loading JNI Library
,08-29 09:54:10.749  6871  6871 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@18b668e9 Instance Count = 1
,08-29 09:54:10.756  6871  6871 D BluetoothAdapterApp: onCreate
,08-29 09:54:10.783  6871  6871 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-29 09:54:10.783  6871  6871 D ProfileConfigQcom: Adding HeadsetService
08-29 09:54:10.783  6871  6871 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 09:54:10.783  6871  6871 D ProfileConfigQcom: Adding A2dpService
08-29 09:54:10.784  6871  6871 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 09:54:10.784  6871  6871 D ProfileConfigQcom: Adding HidService
08-29 09:54:10.784  6871  6871 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-29 09:54:10.784  6871  6871 D ProfileConfigQcom: Adding HealthService
08-29 09:54:10.785  6871  6871 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 09:54:10.786  6871  6871 D ProfileConfigQcom: [BTUI] PanService is supported
,08-29 09:54:10.786  6871  6871 D ProfileConfigQcom: Adding PanService
08-29 09:54:10.786  6871  6871 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 09:54:10.787  6871  6871 D ProfileConfigQcom: Adding GattService
,08-29 09:54:10.787  6871  6871 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 09:54:10.787  6871  6871 D ProfileConfigQcom: Adding BluetoothMapService
08-29 09:54:10.787  6871  6871 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-29 09:54:10.788  6871  6871 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 09:54:10.790  6871  6871 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:10.790  6871  6871 V BluetoothPbapReceiver: ***********state = 10
,08-29 09:54:10.792  6871  6871 V LGMDMManagerInternal: Create singleton instance
,08-29 09:54:10.889  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:10.902  6144  6144 D BluetoothPermissionRequest: onReceive
08-29 09:54:10.904  6144  6144 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 09:54:10.905  6871  6871 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-29 09:54:10.905  6871  6871 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 09:54:10.906  6144  6144 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 09:54:10.906  6144  6144 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 09:54:10.907  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 09:54:10.907  1943  2133 D LGBluetoothAPIService: Message: 100
08-29 09:54:10.907  1943  2133 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-29 09:54:10.910  6144  6144 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 09:54:10.914  6871  6871 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 09:54:10.918  6871  6871 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:10.921  6871  6871 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 09:54:10.921  6871  6871 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-29 09:54:10.922  6871  6871 V BluetoothSapReceiver: SapReceiver onReceive 
,08-29 09:54:10.923  6871  6871 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:10.923  6871  6871 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-29 09:54:10.925  6233  6233 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 09:54:12.347  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 09:54:12.347  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-29 09:54:13.397  1036  1545 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-29 09:54:13.694  6727  6748 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-29 09:54:14.641  1036  1642 I ActivityManager: Killing 5833:com.android.vending/u0a44 (adj 15): empty #17
,08-29 09:54:14.676  1036  1923 W libprocessgroup: failed to open /acct/uid_10044/pid_5833/cgroup.procs: No such file or directory
,08-29 09:54:15.372  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:15.372  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ed6a385 added. We now have 6 listener(s)
,08-29 09:54:15.372  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:15.387  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:15.387  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@51455da added. We now have 7 listener(s)
08-29 09:54:15.387  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:15.388  5921  5994 I System.out: IsBluetoothEnabled
08-29 09:54:15.389  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:15.389  1036  1051 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 09:54:15.391  1036  1118 D BluetoothManagerService: Message: 2
08-29 09:54:15.394  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:15.396  1036  1712 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:15.396  1036  1712 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 09:54:15.410  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 09:54:15.411  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 09:54:15.411  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-29 09:54:15.411  1036  1118 D BluetoothManagerService: Message: 1
08-29 09:54:15.412  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 09:54:15.436  1036  1118 D BluetoothManagerService: Message: 20
08-29 09:54:15.436  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e42f174:true
,08-29 09:54:15.440  6871  6871 D BluetoothAdapterState: make
08-29 09:54:15.445  6871  6871 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 09:54:15.446  6871  6871 I bluedroid-qcom: init
08-29 09:54:15.447  6871  6903 I BluetoothAdapterState: Entering OffState
08-29 09:54:15.447  6871  6871 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 09:54:15.447  6871  6871 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 09:54:15.447  6871  6871 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 09:54:15.447  6871  6871 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 09:54:15.447  6871  6871 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 09:54:15.449  6871  6871 I bluedroid-qcom: get_profile_interface socket
08-29 09:54:15.449  6871  6871 I bluedroid-qcom: get_profile_interface map_client
,08-29 09:54:15.454  6871  6907 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 09:54:15.454  6906  6906 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:15.454  6906  6906 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:15.463  6906  6906 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 09:54:15.463  6906  6906 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 09:54:15.463  6906  6906 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-29 09:54:15.469  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 09:54:15.470  1036  1118 D BluetoothManagerService: Message: 40
08-29 09:54:15.470  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 09:54:15.471  6871  6886 I bluedroid-qcom: config_hci_snoop_log
08-29 09:54:15.472  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 09:54:15.472  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 09:54:15.475  6906  6906 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-29 09:54:15.482  6871  6903 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 09:54:15.482  6871  6903 D BluetoothAdapterProperties: Setting state to 11
08-29 09:54:15.485  6906  6906 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 09:54:15.485  6906  6906 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 09:54:15.487  6871  6903 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 09:54:15.489  1036  1118 D BluetoothManagerService: Message: 60
08-29 09:54:15.489  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 09:54:15.489  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 09:54:15.491  6871  6907 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 09:54:15.492  6871  6903 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 09:54:15.499  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:15.503  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:15.502  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 09:54:15.506  6871  6907 D BluetoothAdapterProperties: Name is: G3
08-29 09:54:15.507  6144  6144 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 09:54:15.515  6871  6871 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 09:54:15.515  6871  6871 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:15.515  6871  6871 V BluetoothPbapReceiver: ***********state = 11
,08-29 09:54:15.532  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:15.537  6871  6903 D BluetoothBondStateMachine: make
,08-29 09:54:15.538  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 09:54:15.539  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 09:54:15.548  6871  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
08-29 09:54:15.548  6871  6903 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 09:54:15.548  6871  6903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
08-29 09:54:15.549  6871  6903 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 09:54:15.550  6871  6903 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-29 09:54:15.552  6871  6917 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 09:54:15.557  6871  6903 E BluetoothAdapterService: File transfer profiles supported!!
08-29 09:54:15.563  6871  6903 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 09:54:15.564  6144  6144 D BluetoothPermissionRequest: onReceive
08-29 09:54:15.570  6871  6903 E BluetoothAdapterService: File transfer profiles supported!!
08-29 09:54:15.571  6871  6871 D HeadsetService: Received start request. Starting profile...
08-29 09:54:15.572  6871  6871 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 09:54:15.573  6871  6871 D LGBluetoothHfpAdapter: Version 1.6
08-29 09:54:15.574  6144  6144 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 09:54:15.578  6871  6903 E BluetoothAdapterService: File transfer profiles supported!!
08-29 09:54:15.581  6871  6871 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 09:54:15.584  6871  6871 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 09:54:15.585  6871  6871 D HeadsetStateMachine: make
08-29 09:54:15.587  6871  6903 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 09:54:15.593  6871  6903 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 09:54:15.599  6871  6903 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 09:54:15.629  6871  6871 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:54:15.629  6871  6871 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 09:54:15.636  6871  6903 V LGMDMManager: Create singleton instance
08-29 09:54:15.638  6871  6903 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 09:54:15.639  6871  6871 D HeadsetStateMachine: max_hf_connections = 1
08-29 09:54:15.639  6871  6871 I bluedroid-qcom: get_profile_interface handsfree
08-29 09:54:15.641  6871  6871 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-29 09:54:15.642   324  2129 V AudioPolicyService: registerClient() client 0xb1020e60, uid 1002
08-29 09:54:15.643   324  2129 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-29 09:54:15.643   324  2129 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 09:54:15.643   324  2129 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 09:54:15.643  6871  6871 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 09:54:15.644   324  1385 V AudioFlinger: registerClient() client 0xb101fb68, pid 6871
08-29 09:54:15.644   324  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:15.644   324  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:15.645  1603  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-29 09:54:15.645  1603  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:15.645  3292  3317 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:15.645  3292  3317 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:15.645  1854  2640 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:15.645   324  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:15.645  1854  2640 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:15.645   324  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:15.645  6871  6887 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:15.645  1036  1923 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 09:54:15.645  1036  1923 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 09:54:15.645  1036  1923 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:15.645  1036  1923 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:15.645  1603  2101 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:15.645  1603  2101 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:15.646  6871  6887 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,08-29 09:54:15.646  6871  6887 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:15.646  6871  6887 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 09:54:15.647  6871  6871 V ToneGenerator: Create Track: 0xb4928080
08-29 09:54:15.647  6871  6871 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 09:54:15.647  6871  6871 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 09:54:15.647  3292  3318 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:15.647  3292  3318 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:15.647  1854  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 09:54:15.647  1854  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 09:54:15.648   324  2128 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 09:54:15.648   324  2128 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 09:54:15.648   324  2128 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 09:54:15.648   324  2128 V AudioPolicyManagerEx: getOutput() returns output 2
,08-29 09:54:15.655   324  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 09:54:15.656   324  2129 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 09:54:15.656   324  2129 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 09:54:15.656   324  2129 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 09:54:15.656   324  2129 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 09:54:15.657  6871  6871 V AudioSystem: getLatency() output 2, latency 50
08-29 09:54:15.657  6871  6871 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 09:54:15.657  6871  6871 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 09:54:15.657   324  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 09:54:15.657   324  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 09:54:15.657   324  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 09:54:15.657   324  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 09:54:15.657   324  1385 V AudioFlinger: createTrack() lSessionId: 23
08-29 09:54:15.658  6871  6871 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 09:54:15.659   324  2129 V AudioFlinger: acquiring 23 from 6871, for 6871
08-29 09:54:15.659   324  2129 V AudioFlinger:  added new entry for 23
,08-29 09:54:15.664  6871  6871 V ToneGenerator: ToneGenerator INIT OK, time: 136449
08-29 09:54:15.665  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
08-29 09:54:15.667  6871  6925 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 09:54:15.667  6871  6925 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 09:54:15.667  6871  6925 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 09:54:15.667  6871  6925 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 09:54:15.669   324  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6871
08-29 09:54:15.669  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
08-29 09:54:15.669   324  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 09:54:15.669   324  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 09:54:15.669   324  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 09:54:15.669   324  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 09:54:15.669   324  1384 V voice   : voice_set_parameters: exit with code(0)
08-29 09:54:15.669   324  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 09:54:15.669   324  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 09:54:15.669   324  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 09:54:15.669   324  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 09:54:15.669   324  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 09:54:15.669   324  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 09:54:15.669  6871  6925 V ToneGenerator: ToneGenerator destructor
08-29 09:54:15.669  6871  6925 V ToneGenerator: stopTone
08-29 09:54:15.670  6871  6925 V ToneGenerator: Delete Track: 0xb4928080
08-29 09:54:15.676  6871  6925 V AudioTrack: ~AudioTrack, releasing session id from 6871 on behalf of 6871
08-29 09:54:15.676   324  1385 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 09:54:15.676   324   324 V AudioFlinger: releasing 23 from 6871 for 6871
08-29 09:54:15.676   324  1385 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
,08-29 09:54:15.676   324   324 V AudioFlinger:  decremented refcount to 0
08-29 09:54:15.676   324   324 V AudioFlinger: purging stale effects
08-29 09:54:15.676   324  1273 V AudioPolicyService: AudioCommandThread() waking up
08-29 09:54:15.676   324  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 09:54:15.676   324  1273 V AudioPolicyManager: releaseOutput() 2
,08-29 09:54:15.676   324  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 09:54:15.677   324  1385 V AudioFlinger: PlaybackThread::Track destructor
,08-29 09:54:15.677   324  1385 V AudioFlinger: removeClient_l() pid 6871, calling pid 324
08-29 09:54:15.677  6871  6871 D A2dpService: Received start request. Starting profile...
08-29 09:54:15.677  6871  6871 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 09:54:15.678  6871  6871 V Avrcp   : make
08-29 09:54:15.679  6871  6871 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 09:54:15.679  6871  6871 I bluedroid-qcom: get_profile_interface avrcp
,08-29 09:54:15.692  6871  6871 V AudioManager: registerRemoteController: size of Media player list: 0
,08-29 09:54:15.694  6871  6871 E AudioManager: No RCC entry present to update
,08-29 09:54:15.694  6871  6871 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 09:54:15.699  6871  6871 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 09:54:15.701  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 09:54:15.701  6871  6871 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 09:54:15.705  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 09:54:15.775  1036  1642 I art     : Explicit concurrent mark sweep GC freed 33427(1621KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.509ms total 125.182ms
,08-29 09:54:15.830  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
08-29 09:54:15.830  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
,08-29 09:54:15.973  1036  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 09:54:15.986  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 09:54:15.992  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 09:54:15.993  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 09:54:15.994  6871  6871 I BluetoothA2dpServiceJni: classInitNative
08-29 09:54:15.994  6871  6871 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:54:15.994  6871  6871 D A2dpStateMachine: make
08-29 09:54:15.996  6871  6871 I bluedroid-qcom: get_profile_interface a2dp
08-29 09:54:15.996  6871  6935 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 09:54:16.000  6871  6871 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:54:16.000  6871  6871 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 09:54:16.001  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
08-29 09:54:16.002  6871  6871 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 09:54:16.002  6871  6934 D A2dpStateMachine: Enter Disconnected: -2
08-29 09:54:16.004  6871  6871 D HidService: Received start request. Starting profile...
08-29 09:54:16.005  6871  6871 I bluedroid-qcom: get_profile_interface hidhost
08-29 09:54:16.005  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
,08-29 09:54:16.007  6871  6871 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 09:54:16.009  6871  6871 D HealthService: Received start request. Starting profile...
08-29 09:54:16.013  6871  6871 I bluedroid-qcom: get_profile_interface health
08-29 09:54:16.013  6871  6871 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 09:54:16.013  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
08-29 09:54:16.014  6871  6871 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 09:54:16.016  6871  6871 D PanService: Received start request. Starting profile...
08-29 09:54:16.016  6871  6871 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 09:54:16.016  6871  6871 I bluedroid-qcom: get_profile_interface pan
,08-29 09:54:16.026  6871  6871 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 09:54:16.026  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
08-29 09:54:16.027  6871  6871 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 09:54:16.033  6871  6871 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:54:16.034  6871  6871 D BtGatt.GattService: Received start request. Starting profile...
08-29 09:54:16.034  6871  6871 D BtGatt.GattService: start()
08-29 09:54:16.034  6871  6871 I bluedroid-qcom: get_profile_interface gatt
08-29 09:54:16.035  6871  6871 D BtGatt.AdvertiseManager: advertise manager created
08-29 09:54:16.048  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
,08-29 09:54:16.052  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
,08-29 09:54:16.053  6871  6871 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 09:54:16.056  6871  6871 V BluetoothMapService: BluetoothMapBinder()
08-29 09:54:16.058  6871  6871 D BluetoothMapService: Received start request. Starting profile...
08-29 09:54:16.058  6871  6871 D BluetoothMapService: start()
08-29 09:54:16.064  6871  6871 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-29 09:54:16.065  6871  6871 D BluetoothMapEmailAppObserver: createReceiver()
08-29 09:54:16.067  6871  6871 D BluetoothMapEmailAppObserver: initObservers()
08-29 09:54:16.068  6871  6871 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 09:54:16.089  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
,08-29 09:54:16.090  6871  6871 D HeadsetStateMachine: Proxy object connected
,08-29 09:54:16.091  6871  6871 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 09:54:16.091  6871  6871 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 09:54:16.098  6871  6871 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 09:54:16.099  6871  6925 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 09:54:16.099  6871  6925 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 09:54:16.100  6871  6925 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 09:54:16.105  6871  6871 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 09:54:16.109  6871  6871 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 09:54:16.111  6871  6871 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:16.119  6871  6871 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 09:54:16.125  6871  6871 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 09:54:16.125  6871  6871 V PanService: [BTUI] SIM Extra State :ABSENT
,08-29 09:54:16.130  6871  6871 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 09:54:16.130  6871  6871 V BluetoothMapService: Handler(): got msg=1
08-29 09:54:16.131  6871  6871 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 09:54:16.131  6871  6871 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 09:54:16.131  6871  6871 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 09:54:16.131  6871  6871 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:16.131  6871  6903 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-29 09:54:16.131  6871  6871 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 09:54:16.131  6871  6903 I bluedroid-qcom: enable
,08-29 09:54:16.135  6871  6903 I bt_hci_bdroid: init
08-29 09:54:16.136  6871  6942 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 09:54:16.136  6871  6942 I bt-btu  : btu_task pending for preload complete event
08-29 09:54:16.138  6871  6903 I bt_vendor: bt-vendor : init
08-29 09:54:16.138  6871  6903 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 09:54:16.138  6871  6903 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 09:54:16.138  6871  6903 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 09:54:16.138  6871  6903 D bt_userial_mct: userial_init
08-29 09:54:16.139  6871  6903 D bt_hci_bdroid: set_power 1
08-29 09:54:16.139  6871  6903 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 09:54:16.139  6871  6903 I bt_vendor: Starting hciattach daemon
08-29 09:54:16.139  6871  6903 I bt_vendor: try to set true
08-29 09:54:16.134  6945  6945 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:16.134  6945  6945 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:16.191  6946  6946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 09:54:16.301  6952  6952 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 09:54:16.314  6953  6953 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 09:54:16.349  6955  6955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 09:54:16.366  6956  6956 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 09:54:16.390  6957  6957 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 09:54:16.402  6961  6961 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-29 09:54:16.436  6963  6963 I libmdmdetect: ESOC framework not supported
08-29 09:54:16.437  6963  6963 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 09:54:16.446  6963  6963 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 09:54:16.446  6963  6963 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-29 09:54:16.446  6963  6963 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 09:54:16.446  6963  6963 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 09:54:16.446  6963  6963 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 09:54:16.446  6963  6963 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 09:54:16.446  6963  6963 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 09:54:16.483  6963  6964 E QC-QMI  : qmi_client [6963] 15: failed to locate client data
08-29 09:54:16.484   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[11:Try again]
08-29 09:54:16.484   483   483 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-29 09:54:16.521  6968  6968 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 09:54:16.536  6969  6969 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 09:54:16.553  6871  6903 I bt_vendor: bluetooth satus is on
08-29 09:54:16.554  6871  6903 D bt_hci_bdroid: preload
,08-29 09:54:16.556  6871  6944 D bt_userial_mct: userial_open(port:0)
08-29 09:54:16.556  6871  6944 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 09:54:16.560  6871  6944 I bt_vendor: Done intiailizing UART
08-29 09:54:16.561  6871  6944 I bt_vendor: Done intiailizing UART
08-29 09:54:16.561  6871  6944 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 09:54:16.561  6871  6944 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 09:54:16.562  6871  6942 I bt-btu  : btu_task received preload complete event
08-29 09:54:16.562  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 09:54:16.562  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 09:54:16.565  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 09:54:16.567  6871  6971 D bt_userial_mct: Entering userial_read_thread()
,08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 09:54:16.571  6871  6942 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 09:54:16.572  6871  6942 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 09:54:16.572  6871  6942 I         : BTE_InitTraceLevels -- TRC_SDP,
,08-29 09:54:16.572  6871  6942 I         : BTE_InitTraceLevels -- TRC_GATT,
,08-29 09:54:16.572  6871  6942 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 09:54:16.572  6871  6942 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 09:54:16.572  6871  6942 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 09:54:16.644  6871  6942 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 09:54:16.644  6871  6942 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f4061 ,
08-29 09:54:16.644  6871  6942 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f4061 
,08-29 09:54:16.680  6871  6907 E bt-btif : Calling BTA_HhEnable
08-29 09:54:16.680  6871  6907 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 09:54:16.681  6871  6907 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 09:54:16.683  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 09:54:16.683  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 09:54:16.683  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 09:54:16.685  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 09:54:16.685  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 09:54:16.685  6871  6907 D BluetoothAdapterProperties: Name is: G3
08-29 09:54:16.686  6871  6907 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:54:16.687  6871  6907 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:54:16.687  6871  6907 D bt_hci_bdroid: postload
08-29 09:54:16.687  6871  6944 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 09:54:16.688  6871  6907 D bte_conf: Device ID record 1 : primary
08-29 09:54:16.688  6871  6907 D bte_conf:   vendorId            = 00c4
08-29 09:54:16.688  6871  6907 D bte_conf:   vendorIdSource      = 0001
08-29 09:54:16.688  6871  6907 D bte_conf:   product             = 13a1
08-29 09:54:16.688  6871  6907 D bte_conf:   version             = 1000
08-29 09:54:16.688  6871  6907 D bte_conf:   clientExecutableURL = 
08-29 09:54:16.688  6871  6907 D bte_conf:   serviceDescription  = 
08-29 09:54:16.688  6871  6907 D bte_conf:   documentationURL    = 
08-29 09:54:16.688  6871  6907 D bte_conf: bte_load_did_conf no section named DID2.
08-29 09:54:16.689  6871  6942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 09:54:16.689  6871  6944 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 09:54:16.690  6871  6944 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 09:54:16.691  6871  6944 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 09:54:16.693  6871  6971 E bt_mct  : hci lib postload completed
,08-29 09:54:16.702  6871  6942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 09:54:16.702  6871  6942 W bt-smp  : Plain text(LSB ~ MSB) = 53 c0 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 09:54:16.702  6871  6942 W bt-smp  : Encrypted text(LSB ~ MSB) = a3 10 10 30 6f ab 9d 25 d9 69 bc 94 13 97 1c ad 
08-29 09:54:16.702  6871  6942 W bt-btm  : Stopping oneshot timer
08-29 09:54:16.703  6871  6903 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 09:54:16.703  6871  6903 D BluetoothAdapterProperties: ScanMode =  20
08-29 09:54:16.703  6871  6903 D BluetoothAdapterProperties: State =  11
08-29 09:54:16.703  6871  6903 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 09:54:16.703  6871  6903 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 09:54:16.704  6871  6903 D BluetoothAdapterProperties: Setting state to 12
08-29 09:54:16.704  6871  6903 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 09:54:16.704  6973  6973 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 09:54:16.704  6973  6973 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:16.710  6871  6907 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 09:54:16.714  1036  1118 D BluetoothManagerService: Message: 60
08-29 09:54:16.715  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 09:54:16.716  6871  6903 I BluetoothAdapterState: Entering On State
08-29 09:54:16.717  6871  6907 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 09:54:16.684  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 09:54:16.721  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 09:54:16.740  6871  6942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 09:54:16.740  6871  6942 W bt-smp  : Plain text(LSB ~ MSB) = 8b 43 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 09:54:16.741  6871  6942 W bt-smp  : Encrypted text(LSB ~ MSB) = de 9b 3a 44 b9 ed 16 9b 53 a0 36 f4 51 de 08 81 
,08-29 09:54:16.743  6871  6942 W bt-btm  : Stopping oneshot timer
08-29 09:54:16.746  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-29 09:54:16.757  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:16.757  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:16.757  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:16.757  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:16.757  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:16.757  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:16.757  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:16.757  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:16.760  6871  6907 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:54:16.761  6871  6907 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 09:54:16.764  6871  6942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 09:54:16.765  6871  6942 W bt-smp  : Plain text(LSB ~ MSB) = be 94 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 09:54:16.765  6871  6942 W bt-smp  : Encrypted text(LSB ~ MSB) = 2d 2a aa a6 9e 64 8f c7 78 77 c8 62 9e 52 3f aa 
08-29 09:54:16.765  6871  6942 W bt-btm  : Stopping oneshot timer
08-29 09:54:16.765  6871  6903 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 09:54:16.765  6871  6903 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 09:54:16.766  6871  6903 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 09:54:16.766  6144  6159 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:54:16.769  6871  6903 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-29 09:54:16.769  6871  6903 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-29 09:54:16.781  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:16.784  6871  6942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 09:54:16.784  6871  6942 W bt-smp  : Plain text(LSB ~ MSB) = f5 2b 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 09:54:16.784  6871  6942 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f 24 26 07 9b 73 5d c9 d2 08 fb 98 fb f6 e5 0c 
08-29 09:54:16.784  6871  6942 W bt-btm  : Stopping oneshot timer
08-29 09:54:16.792  6144  6159 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:54:16.802  6871  6942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 09:54:16.802  6871  6942 W bt-smp  : Plain text(LSB ~ MSB) = 5e 2c 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 09:54:16.802  6871  6942 W bt-smp  : Encrypted text(LSB ~ MSB) = ed f8 c7 02 de 12 2f 6e c5 b9 c5 19 78 af b4 3b 
,08-29 09:54:16.805  6871  6942 W bt-btm  : Stopping oneshot timer
08-29 09:54:16.806  6144  6159 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:54:16.806  6144  6159 D BluetoothPan: onBluetoothStateChange call bindService
08-29 09:54:16.826  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:16.838  6978  6978 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-29 09:54:16.843  1036  1036 D BluetoothA2dp: Proxy object connected
08-29 09:54:16.849  6144  6159 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:54:16.856  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:54:16.860  6144  6639 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:54:16.861  6144  6144 D BluetoothA2dp: Proxy object connected
08-29 09:54:16.861  6144  6144 D A2dpProfile: Bluetooth service connected
08-29 09:54:16.863  1036  1036 D BluetoothHeadset: Proxy object connected
08-29 09:54:16.866  6144  6144 D BluetoothInputDevice: Proxy object connected
08-29 09:54:16.866  6144  6144 D HidProfile: Bluetooth service connected
08-29 09:54:16.869  1854  2640 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:16.870  6144  6144 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:54:16.870  6144  6144 D PanProfile: Bluetooth service connected
,08-29 09:54:16.874  6144  6144 D BluetoothMap: Proxy object connected
08-29 09:54:16.874  6144  6144 D MapProfile: Bluetooth service connected
08-29 09:54:16.874  6144  6144 D BluetoothMap: getConnectedDevices()
08-29 09:54:16.875  6871  6886 V BluetoothMapService: getConnectedDevices()
08-29 09:54:16.875  1854  1854 D BluetoothHeadset: Proxy object connected
08-29 09:54:16.876  1854  4323 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:16.877  1854  1854 D BluetoothHeadset: Proxy object connected
08-29 09:54:16.878  1854  2445 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:16.879  1854  1854 D BluetoothHeadset: Proxy object connected
08-29 09:54:16.880  6144  6160 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:54:16.881  6144  6144 D BluetoothHeadset: Proxy object connected
08-29 09:54:16.881  6144  6144 D HeadsetProfile: Bluetooth service connected
,08-29 09:54:16.883  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 09:54:16.883  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 09:54:16.885  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 09:54:16.887  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:16.887  1943  2133 D LGBluetoothAPIService: Message: 1
08-29 09:54:16.887  1943  2133 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 09:54:16.887  1943  2133 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-29 09:54:16.887  1943  2133 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 09:54:16.889  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 09:54:16.894  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:16.894  1036  1118 D BluetoothManagerService: Message: 40
08-29 09:54:16.894  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-29 09:54:16.897  6871  6871 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:16.897  6871  6871 D BluetoothMapService: STATE_ON
08-29 09:54:16.897  6871  6871 V BluetoothMapService: Handler(): got msg=1
08-29 09:54:16.898  6871  6871 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 09:54:16.900  6871  6995 D BluetoothMapMasInstance: MAS initSocket()
08-29 09:54:16.900  6871  6995 D BluetoothMapMasInstance:   masId = 00
08-29 09:54:16.900  6871  6995 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 09:54:16.900  6871  6995 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 09:54:16.900  6871  6995 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 09:54:16.901  6144  6144 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 09:54:16.902  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:16.903  6144  6144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 09:54:16.904  6871  6995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:16.906  6871  6995 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 09:54:16.906  6871  6907 D BluetoothAdapterProperties: Scan Mode:21
08-29 09:54:16.907  6871  6907 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-29 09:54:16.909  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:16.913  6871  6995 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 09:54:16.914  6871  6995 D BluetoothMapMasInstance: Accepting socket connection...
08-29 09:54:16.914  6144  6144 D DockEventReceiver: finishStartingService: stopping service
08-29 09:54:16.917  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
,08-29 09:54:16.917  6871  6871 V BluetoothPbapService: Pbap Service onCreate
08-29 09:54:16.917  6871  6871 V BluetoothPbapService: Starting PBAP service
08-29 09:54:16.918  6871  6871 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 09:54:16.919  6871  6871 V BluetoothPbapService: Pbap Service onBind
08-29 09:54:16.921  6871  6871 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:16.922  6871  6871 V BluetoothPbapService: state: 12
08-29 09:54:16.922  6871  6871 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 09:54:16.922  6871  6871 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:16.922  6871  6871 V BluetoothPbapReceiver: ***********state = 12
08-29 09:54:16.922  6144  6144 D BluetoothPbap: Proxy object connected
08-29 09:54:16.922  6144  6144 D PbapServerProfile: Bluetooth service connected
08-29 09:54:16.924  6871  6871 V BluetoothPbapService: Handler(): got msg=1
08-29 09:54:16.925  6871  6871 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 09:54:16.926  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:54:16.926  6871  6998 V BluetoothPbapService: Pbap Service initSocket
08-29 09:54:16.927  2214  2214 D c       : Getting all permits...
08-29 09:54:16.927  2214  2214 D a       : Opening database...
08-29 09:54:16.927  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:16.928  6871  6998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:16.929  6871  6998 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 09:54:16.929  6871  6998 V BluetoothPbapService: Succeed to create listening socket 
08-29 09:54:16.929  6871  6998 V BluetoothPbapService: Accepting socket connection...
08-29 09:54:16.931  2214  2214 D a       : Opening database auth.proximity.permit_store...
08-29 09:54:16.931  2214  2214 D a       : Closing database...
08-29 09:54:16.942  6144  6144 D BluetoothPermissionRequest: onReceive
,08-29 09:54:16.944  6144  6144 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-29 09:54:16.947  6144  6144 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 09:54:16.950  6871  6871 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 09:54:16.952  6871  6871 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 09:54:16.958  6871  6871 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 09:54:16.978  6871  6871 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 09:54:16.978  6871  6871 V BtOppService: onCreate
,08-29 09:54:16.982  6871  6871 V BluetoothOppNotification: send message
08-29 09:54:16.985  6871  6871 V BtOppService: Starting RfcommListener
08-29 09:54:17.002  6871  6871 D BluetoothOppPreference: Dumping Names:  
08-29 09:54:17.002  6871  6871 D BluetoothOppPreference: {}
08-29 09:54:17.002  6871  6871 D BluetoothOppPreference: Dumping Channels:  
08-29 09:54:17.002  6871  6871 D BluetoothOppPreference: {}
,08-29 09:54:17.007  6871  6871 V BtOppService: onStartCommand
08-29 09:54:17.011  6871  7002 V BtOppService: Deleted complete outbound shares, number =  0
08-29 09:54:17.012  6871  7005 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 09:54:17.013  6871  7005 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-29 09:54:17.014  6871  6871 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:17.015  6871  7002 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 09:54:17.015  6871  6871 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 09:54:17.016  6871  7002 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 09:54:17.018  6871  7002 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d9aabe2 on behalf of 
08-29 09:54:17.021  6871  7005 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e063b73 on behalf of 
08-29 09:54:17.023  6871  6871 V BluetoothOppNotification: new notify threadi!
08-29 09:54:17.025  6871  6871 V BluetoothOppNotification: send delay message
08-29 09:54:17.026  6871  7005 V BluetoothOppNotification: update too frequent, put in queue
08-29 09:54:17.027  6871  6871 V BtOppService: start RfcommListener
08-29 09:54:17.027  6871  7006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 09:54:17.029  6871  7006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cb68a30 on behalf of 
08-29 09:54:17.029  6871  7006 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 09:54:17.031  6871  7006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-29 09:54:17.032  6871  7006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28f3a6a9 on behalf of 
08-29 09:54:17.033  6871  6871 V BtOppService: RfcommListener started
08-29 09:54:17.037  6871  6871 V BtOppService: ContentObserver received notification
08-29 09:54:17.037  6871  6871 V BtOppService: ContentObserver received notification
08-29 09:54:17.038  6871  7007 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 09:54:17.039  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:17.045  6871  7005 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 09:54:17.045  6871  7007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:17.045  6871  7005 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 09:54:17.046  6871  7006 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 09:54:17.048  6871  7007 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-29 09:54:17.048  6871  7007 V BtOppRfcommListener: Started RFCOMM listener....
08-29 09:54:17.049  6871  7007 I BtOppRfcommListener: Accept thread started.
08-29 09:54:17.049  6871  7007 V BtOppRfcommListener: Accepting connection...
08-29 09:54:17.049  6871  7005 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c3ba42e on behalf of 
08-29 09:54:17.049  6871  7006 V BluetoothOppNotification: outbound notification was removed.
08-29 09:54:17.049  6871  7006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-29 09:54:17.051  6871  7005 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 09:54:17.052  6871  7006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aff1bcf on behalf of 
08-29 09:54:17.057  6871  7006 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 09:54:17.060  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
08-29 09:54:17.060  6871  7006 V BluetoothOppNotification: inbound notification was removed.
08-29 09:54:17.060  6871  6871 V BluetoothFtpService: Ftp Service onCreate
08-29 09:54:17.060  6871  6871 I BluetoothFtpService: Ftp Service onCreate
08-29 09:54:17.060  6871  7006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 09:54:17.060  6871  6871 V BluetoothFtpService: Ftp Service onStartCommand
08-29 09:54:17.060  6871  6871 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:17.061  6871  6871 V BluetoothFtpService: Starting Listening on sockets
08-29 09:54:17.061  6871  6871 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 09:54:17.061  6871  6871 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 09:54:17.061  6871  6871 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 09:54:17.062  6871  6871 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:17.062  6871  6871 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 09:54:17.062  6871  6871 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 09:54:17.063  6871  7006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34370465 on behalf of 
08-29 09:54:17.065  6871  6871 V BluetoothFtpService: Handler(): got msg=1
08-29 09:54:17.066  6871  6871 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 09:54:17.067  6871  6871 V BluetoothFtpService: Ftp Service initSocket
08-29 09:54:17.073  1036  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:17.074  6871  6871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:17.075  6871  6871 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-29 09:54:17.076  6871  6871 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-29 09:54:17.077  6871  7009 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-29 09:54:17.096  6871  6871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b4da846
,08-29 09:54:17.097  6871  6871 V BluetoothSapService: Sap Service onCreate
08-29 09:54:17.100  6871  6871 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:17.100  6871  6871 V BluetoothSapService: state: 12
08-29 09:54:17.100  6871  6871 V BluetoothSapService: Starting SAP server process
08-29 09:54:17.102  6871  6871 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 09:54:17.094  7010  7010 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:17.094  7010  7010 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:17.105  6871  7011 V BluetoothSapService: Sap Service initRfcommSocket
08-29 09:54:17.106  1036  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:17.108  6871  7011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:54:17.112  6871  7011 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 09:54:17.112  6871  7011 V BluetoothSapService: Succeed to create listening socket 
08-29 09:54:17.112  6871  7011 V BluetoothSapService: Accepting socket connection...
,08-29 09:54:17.127  7010  7010 V BT_SAP  : Event pipe created
,08-29 09:54:17.127  7010  7010 V BT_SAP  : create_server_socket qcom.sap.server
08-29 09:54:17.127  7010  7010 V BT_SAP  : created socket fd 6
,08-29 09:54:17.440  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:17.440  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:17.440  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:17.440  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:17.440  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:17.440  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:17.440  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:17.440  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:17.449  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:17.452  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:17.452  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c6d2a0b added. We now have 8 listener(s)
08-29 09:54:17.452  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:17.459  1036  1924 D WifiServiceImplEx: setWifiEnabled: false pid=5921, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 09:54:17.459  1036  1924 D WifiService: setWifiEnabled: false pid=5921, uid=10118
08-29 09:54:17.459  1036  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:17.466  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:17.468  1036  1576 D WifiServiceImplEx: setWifiEnabled: true pid=5921, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 09:54:17.469  1036  1576 D WifiService: setWifiEnabled: true pid=5921, uid=10118
08-29 09:54:17.469  1036  1576 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:54:17.486  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 09:54:17.486  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 09:54:17.487  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-29 09:54:17.488  1036  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 09:54:17.488  1036  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-29 09:54:17.491  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 09:54:17.491  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-29 09:54:17.491  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 09:54:17.491  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 09:54:17.491  1036  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-29 09:54:17.491  1036  1539 E WifiHW  : unknown target_country: EU , set to default
08-29 09:54:17.491  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 09:54:17.491  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 09:54:17.491  1036  1539 I WifiUtil: gEnableBmps=1
08-29 09:54:18.033  6871  6871 V BluetoothOppNotification: new notify threadi!
,08-29 09:54:18.043  6871  6871 V BluetoothOppNotification: send delay message
08-29 09:54:18.066   319   894 D SoftapController: Softap fwReload - Ok
,08-29 09:54:18.085  1036  1539 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (590ms)
,08-29 09:54:18.090  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 09:54:18.090  1036  1118 D Tethering: InitialState.processMessage what=4
08-29 09:54:18.100   319   894 D CommandListener: Setting iface cfg
08-29 09:54:18.100   319   894 D CommandListener: Trying to bring down wlan0
,08-29 09:54:18.111   319  7032 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 09:54:18.119   319   894 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:54:18.123  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 09:54:18.130  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 09:54:18.131  1036  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 09:54:18.134  7033  7033 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 09:54:18.144  7033  7033 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:18.165  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 09:54:18.165  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-29 09:54:18.165  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 09:54:18.181  1036  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 09:54:18.181  1036  1539 D WifiMonitor: connecting to supplicant
08-29 09:54:18.183  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:18.184  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:18.184  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 09:54:18.184  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 09:54:18.184  6144  6144 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 09:54:18.186  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 09:54:18.192  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-29 09:54:18.194  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 09:54:18.196  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:18.207  6871  7030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 09:54:18.208  7033  7033 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 09:54:18.209  6144  6144 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 09:54:18.210  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 09:54:18.210  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 09:54:18.210  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 09:54:18.210  6144  6144 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 09:54:18.210  6144  6144 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-29 09:54:18.212  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:18.212  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 09:54:18.212  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 09:54:18.212  6144  6144 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 09:54:18.213  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 09:54:18.213  6871  7030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@199881e1 on behalf of 
08-29 09:54:18.213  6144  6144 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 09:54:18.213  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 09:54:18.213  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 09:54:18.213  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 09:54:18.213  6144  6144 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 09:54:18.214  6144  6144 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 09:54:18.214  6871  7030 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 09:54:18.216  6871  7030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 09:54:18.218  6871  7030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32880b06 on behalf of 
08-29 09:54:18.218  6871  7030 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 09:54:18.220  6871  7030 V BluetoothOppNotification: outbound notification was removed.
08-29 09:54:18.220  6871  7030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 09:54:18.222  6871  7030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ecb5c7 on behalf of 
08-29 09:54:18.222  6871  7030 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 09:54:18.226  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:18.229  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:18.238  6260  7051 W FormManager: Network not available. Please check & try again.
,08-29 09:54:18.238  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:18.240  6871  7030 V BluetoothOppNotification: inbound notification was removed.
08-29 09:54:18.240  6871  7030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 09:54:18.242  6260  7052 V FormManager: Network unavailable.
08-29 09:54:18.242  7033  7033 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 09:54:18.243  7033  7033 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-29 09:54:18.246  6871  7030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a1637f4 on behalf of 
08-29 09:54:18.248  6260  7052 V FormManager: Network unavailable.
,08-29 09:54:18.313  7033  7033 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:54:18.339  7033  7033 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 09:54:18.346  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 09:54:18.347  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 09:54:18.348  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 09:54:18.348  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-29 09:54:18.349  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:18.349  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:18.349  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:18.350  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:18.350  1036  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 09:54:18.351  1036  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 09:54:18.351  1036  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 09:54:18.351  1036  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 09:54:18.351  1036  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 09:54:18.352  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 09:54:18.352  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-29 09:54:18.352  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-29 09:54:18.355  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:18.355  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:18.355  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:54:18.355  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:18.355  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:18.355  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 09:54:18.358  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 09:54:18.359  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-29 09:54:18.359  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 09:54:18.360  1036  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 09:54:18.360  1036  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-29 09:54:18.360  1036  1539 D WifiConfigStore: Loading config and enabling all networks 
08-29 09:54:18.360  1036  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 09:54:18.361  1036  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 09:54:18.366  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 09:54:18.366  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 09:54:18.366  7033  7033 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 09:54:18.366  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 09:54:18.366  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 09:54:18.367  1036  7055 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 09:54:18.367  1036  7055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-29 09:54:18.368  1036  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 09:54:18.373  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:18.373  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:18.373  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:18.373  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:18.373  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:18.373  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:18.373  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:18.373  5921  5921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:18.378  1036  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-29 09:54:18.379  5921  5921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:18.379  1036  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 09:54:18.380  1036  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-29 09:54:18.380  1036  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 09:54:18.381  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:18.382  1036  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 09:54:18.382  1036  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 09:54:18.383  1036  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 09:54:18.383  1036  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 09:54:18.383  1036  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 09:54:18.384  1036  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 09:54:18.384  1036  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 09:54:18.384  1036  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 09:54:18.385  1036  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 09:54:18.385  1036  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 09:54:18.386  1036  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 09:54:18.386  1036  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 09:54:18.386  1036  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 09:54:18.388  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:54:18.388  1036  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 09:54:18.389  1036  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 09:54:18.389  1036  1539 D WifiNative-HAL: Setting external_sim to 1
08-29 09:54:18.389  1036  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 09:54:18.390  1036  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 09:54:18.390  1036  1539 I WifiNative-HAL: startHal
08-29 09:54:18.390  1036  1539 D wifi    : setting scan oui 0xaf73de00
08-29 09:54:18.390  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:18.390  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:54:18.390  1036  1539 I WifiNative-HAL: startHal
08-29 09:54:18.390  1036  1539 D wifi    : setting scan oui 0xaf73de00
08-29 09:54:18.391  1036  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 09:54:18.391  1036  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 09:54:18.391  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 09:54:18.391  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-29 09:54:18.391  1943  2329 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 09:54:18.391  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 09:54:18.391  1943  2329 D WfdsService: Set the WFDS Monitor: true
08-29 09:54:18.391  1943  2329 D WfdsMonitor: WfdsMonitorThread create
08-29 09:54:18.392  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 09:54:18.392  1943  2329 D WfdsMonitor: WFDS Monitor is created and started
08-29 09:54:18.392  1943  2329 D WfdsService: WiFi: Supplicant connection re-established
08-29 09:54:18.392  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 09:54:18.392  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 09:54:18.392  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 09:54:18.392  1036,  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 09:54:18.392  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 09:54:18.393  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 09:54:18.393  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 09:54:18.393  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 09:54:18.393  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 09:54:18.393  1943  7059 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 09:54:18.393  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 09:54:18.393  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 09:54:18.393  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 09:54:18.393  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 09:54:18.394  1943  7059 E CtrlSupplicant: Succeed to open control connection
08-29 09:54:18.394  7033  7033 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 09:54:18.394  1943  7059 E CtrlSupplicant: Succeed to open monitor connection
08-29 09:54:18.394  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 09:54:18.394  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 09:54:18.394  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 09:54:18.394  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-29 09:54:18.395  1943  7059 D WfdsMonitor: Supplicant connection established
08-29 09:54:18.395  1943  2329 D WfdsService: Connected to the supplicant for wfds
08-29 09:54:18.396  1036  1539 E WifiNative: : [139,162,540 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 09:54:18.396  1036  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 09:54:18.396  1036  1539 D WifiNative-wlan0: RECONNECT: returned true
08-29 09:54:18.396  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-29 09:54:18.397  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 09:54:18.397  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 09:54:18.397  1036  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 09:54:18.397  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 09:54:18.397  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-29 09:54:18.398  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.399  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 09:54:18.399  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 09:54:18.399  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-29 09:54:18.399  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.399  1036  1557 I WifiNative-HAL: startHal
08-29 09:54:18.399  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf73de00
08-29 09:54:18.399  1036  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 09:54:18.399  1036  1557 D wifi    : failed to get capabilities : -3
08-29 09:54:18.399  1036  1557 E WifiScanningService: could not get scan capabilities
08-29 09:54:18.399  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.399  1036  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 09:54:18.400  1036  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 09:54:18.400   319   894 D CommandListener: Setting iface cfg
08-29 09:54:18.400   319   894 D CommandListener: Trying to bring up p2p0
08-29 09:54:18.400  1036  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 09:54:18.400  1036  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 09:54:18.400  1036  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 09:54:18.401  1036  1537 D LGWifiP2pService: P2pEnablingState
08-29 09:54:18.401  1036  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.401  1036  1537 D LGWifiP2pService: P2p socket connection successful
08-29 09:54:18.401  1036  1537 D LGWifiP2pService: P2pEnabledState
08-29 09:54:18.401  1036  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 09:54:18.401  1036  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 09:54:18.401  7033  7033 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 09:54:18.401  1036  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 09:54:18.402  1036  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 09:54:18.403  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:18.403  1036  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 09:54:18.403  1036  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 09:54:18.403  1036  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 09:54:18.403  7033  7033 E wpa_supplicant: disconnect_rssi_lvl: -100
08-2,9 09:54:18.404  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=139172  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 09:54:18.404  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 09:54:18.404  1943  1943 D WfdsService: WifiP2pState is changed : true
08-29 09:54:18.405  1943  2329 D WfdsService: Receive the WFDS_ENABLE Method
,08-29 09:54:18.405  1943  2329 D WfdsService: Set the WFDS Monitor: true
08-29 09:54:18.405  1943  2329 D WfdsService: Connected to the supplicant for wfds
,08-29 09:54:18.405  1943  2329 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 09:54:18.405  7033  7033 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 09:54:18.406  1943  2329 D WfdsService: selectPreferredScanChannel [36]
,08-29 09:54:18.406  1943  2329 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 09:54:18.406  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 09:54:18.407  1943  1943 D WfdsService: isConnected: false
08-29 09:54:18.407  1036  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,08-29 09:54:18.407  1036  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 09:54:18.408  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=139175  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 09:54:18.408  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 09:54:18.408  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
,08-29 09:54:18.409  1036  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 09:54:18.409  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-29 09:54:18.409  1036  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-29 09:54:18.409  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 09:54:18.409  1036  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 09:54:18.409  1036  1537 D LGWifiP2pService: before postfix = G3
,08-29 09:54:18.409  1036  1537 D WifiServerServiceExt: postfix byte check : 2
08-29 09:54:18.409  1036  1537 D LGWifiP2pService: after postfix = G3
08-29 09:54:18.409  1036  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 09:54:18.409  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 09:54:18.410  7033  7033 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ,
08-29 09:54:18.410  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:18.410  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:18.411  7033  7033 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 09:54:18.411  1036  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
,08-29 09:54:18.411  7033  7033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.411  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 09:54:18.411  7033  7033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.412  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:18.412  1036  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true,
08-29 09:54:18.412  1036  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 09:54:18.412  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 09:54:18.412  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 09:54:18.412  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-29 09:54:18.412  1036  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 09:54:18.412  1036  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 09:54:18.412  1036  7055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:18.413  1943  7059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-29 09:54:18.413  1036  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 09:54:18.413  1943  7059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:18.413  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-29 09:54:18.413  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 09:54:18.413  1036  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 09:54:18.413  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 09:54:18.413  1036  7055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:18.413  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 09:54:18.413  1036  7055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:18.413  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-29 09:54:18.413  1036  7055 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.413  1036  7055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.413  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 09:54:18.413  7033  7033 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-29 09:54:18.414  1036  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true,
08-29 09:54:18.414  1036  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 09:54:18.413  1036  7055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.414  1036  7055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD],
08-29 09:54:18.419  1036  7055 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.419  1036  7055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-29 09:54:18.419  1036  7055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.419  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 09:54:18.419  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 09:54:18.419  1036  7055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-29 09:54:18.419  1036  7055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 09:54:18.419  1036  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 09:54:18.419  1036  1539 D WifiNative-wlan0: doBoolean: SCAN
,08-29 09:54:18.420  1036  1539 D WifiNative-wlan0: SCAN: returned false
08-29 09:54:18.420  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=139188  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 09:54:18.420  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:18.420  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:18.421  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 09:54:18.421  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=139189  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-29 09:54:18.422  1036  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:18.423  1036  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 09:54:18.423  1036  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-29 09:54:18.423  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:18.423  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:18.423  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 09:54:18.424  1036  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 09:54:18.424  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 09:54:18.425  1036  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-29 09:54:18.425  1036  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 09:54:18.425  1036  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,08-29 09:54:18.425  1036  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 09:54:18.425  6260  7057 W FormManager: Network not available. Please check & try again.
,08-29 09:54:18.427  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 09:54:18.427  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 09:54:18.428  1036  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:18.428  1943  1943 D WfdsService: Update P2p Interface State: 3
08-29 09:54:18.428  1036  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:18.428  1036  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:18.428  1036  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 09:54:18.430  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:18.430  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 09:54:18.433  1036  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 09:54:18.433  1036  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 09:54:18.433  1036  1537 D LGWifiP2pService: InactiveState
08-29 09:54:18.433  1036  1537 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.433  6260  7058 V FormManager: Network unavailable.
08-29 09:54:18.433  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.433  1036  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 09:54:18.434  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 09:54:18.434  7033  7033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:18.435  1943  7059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 09:54:18.435  7033  7033 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 09:54:18.435  7033  7033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.435  1943  7059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:18.436  7033  7033 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.436  1943  7059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:18.437  1036  7055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-29 09:54:18.437  1036  7055 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:18.437  1036  7055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:18.437  1036  7055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 09:54:18.437  1036  7055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-29 09:54:18.437  1036  7055 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.437  1036  7055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-29 09:54:18.437  1036  7055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.437  1036  7055 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 09:54:18.437  1036  7055 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.437  1036  7055 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.437  1036  7055 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 09:54:18.438  1036  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.438  1036  1537 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:18.439  1036  1036 E WifiServerServiceExt: No p2p device connected
08-29 09:54:18.439  1943  2329 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 09:54:18.439  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:18.440  6260  7058 V FormManager: Network unavailable.
08-29 09:54:18.441  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 09:54:18.441  4228  4228 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 09:54:18.445  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:54:18.447  4228  4228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 09:54:18.451  4228  7060 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 09:54:18.451  4228  7061 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 09:54:18.452  4228  7061 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 09:54:18.488  1036  1942 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7062 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 09:54:18.501  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:18.501  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:18.501  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:18.501  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:18.501  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:18.501  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:18.501  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:18.501  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:18.503  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:18.507  5921  5994 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 09:54:18.508  5921  5994 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 09:54:18.509  5921  5994 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c6d8715 Bundle[{}]
08-29 09:54:18.510  5921  5994 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 09:54:18.510  5921  5994 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 09:54:18.511  5921  5994 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 09:54:18.511  5921  5994 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 09:54:18.512  5921  5994 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 09:54:18.512  5921  5994 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 09:54:18.517  5921  5994 I System.out: Running OutgoingSocketThread
,08-29 09:54:18.521  5921  7077 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 766)
08-29 09:54:18.524  5921  7077 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 51637
08-29 09:54:18.524  5921  7077 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 09:54:18.638  7062  7062 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 09:54:18.638  7062  7062 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-29 09:54:18.652  7062  7062 V [BNRBootReceiver]: Boot Receiver Return
,08-29 09:54:18.653  7062  7062 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 09:54:18.660  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:18.676  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:18.697  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:18.704  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:18.704  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:54:18.707  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 09:54:18.711  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:18.719  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:18.726  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:18.733  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:18.733  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 09:54:18.735  6213  6213 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 09:54:18.738  1036  1960 I ActivityManager: Killing 6515:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-29 09:54:18.768  1036  1996 W libprocessgroup: failed to open /acct/uid_10011/pid_6515/cgroup.procs: No such file or directory
,08-29 09:54:19.030  7033  7033 E wpa_supplicant: USIM:  scard_init function
,08-29 09:54:19.037  7033  7033 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 09:54:19.039  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 09:54:19.039  1036  7055 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 09:54:19.039  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 09:54:19.039  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: WPS-AP-AVAILABLE 
08-29 09:54:19.039  1036  7055 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 09:54:19.039  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 09:54:19.039  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 09:54:19.040  1036  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 09:54:19.041  1036  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 09:54:19.041  1036  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 09:54:19.042  1036  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 09:54:19.042  1036  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 09:54:19.062  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=139830  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 09:54:19.069  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=139836  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 09:54:19.069  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 09:54:19.073  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.073  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.073  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 09:54:19.076  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:19.076  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-29 09:54:19.080  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.080  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:19.082  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:54:19.095  6144  6144 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 09:54:19.106  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 09:54:19.119  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:19.128  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:19.135  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:19.136  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.136  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 09:54:19.158  7033  7033 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 09:54:19.165  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 09:54:19.165  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 09:54:19.168  7033  7033 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 09:54:19.168  7033  7033 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 09:54:19.171  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 09:54:19.171  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 09:54:19.172  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:19.172  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 09:54:19.172  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:19.172  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 09:54:19.172  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 09:54:19.172  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 09:54:19.172  1036  7055 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 09:54:19.173  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=139941  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 09:54:19.174  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=139941  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 09:54:19.174  1036  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139942
,08-29 09:54:19.181  1036  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139948
08-29 09:54:19.182  1036  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139950
08-29 09:54:19.183  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139951
08-29 09:54:19.184  1036  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 51 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139952
08-29 09:54:19.188  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=139956  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 09:54:19.172  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 09:54:19.191  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 09:54:19.191  1036  7055 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 09:54:19.191  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:19.191  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 09:54:19.194  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 09:54:19.199  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.200  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:19.203  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.203  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.203  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 09:54:19.208  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.210  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.210  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:19.211  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.211  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.211  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-29 09:54:19.213  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.214  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=139982  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 09:54:19.215  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:19.215  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=139982  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 09:54:19.216  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=139983  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 09:54:19.217  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:19.217  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 09:54:19.221  1036  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139989
08-29 09:54:19.222  1036  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139990
,08-29 09:54:19.222  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-29 09:54:19.223  1036  7055 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 09:54:19.223  1036  7055 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 09:54:19.223  1036  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 09:54:19.225  1036  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 09:54:19.229  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:19.230  1036  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 09:54:19.230  1036  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 09:54:19.237  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.237  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.237  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 09:54:19.240  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:19.240  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.240  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 09:54:19.241  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:19.252  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.252  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:19.253  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.254  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:19.254  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.255  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:19.255  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.255  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 09:54:19.257  1036  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 09:54:19.257  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:54:19.257  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 09:54:19.258  1036  1545 D ConnectivityService: Got NetworkAgent Messenger
08-29 09:54:19.258  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 09:54:19.258  1036  1545 D ConnectivityService: NetworkAgent connected
08-29 09:54:19.258  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.258  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 09:54:19.258  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 09:54:19.260  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:19.260  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 09:54:19.260  6144  6144 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 09:54:19.260  6144  6144 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 09:54:19.260  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 09:54:19.261  6144  6144 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 09:54:19.261  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 09:54:19.261  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 09:54:19.261  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 09:54:19.261  6144  6144 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 09:54:19.261  6144  6144 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 09:54:19.261  6144  6144 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 09:54:19.263  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 09:54:19.263  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:54:19.264  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 09:54:19.264  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 09:54:19.264  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 09:54:19.266  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 09:54:19.270  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 09:54:19.272   319   894 D CommandListener: Setting iface cfg
08-29 09:54:19.277  1036  7107 D DhcpStateMachine: StoppedState
08-29 09:54:19.277  1036  1539 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 09:54:19.277  1036  7107 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:19.277  1036  7107 D DhcpStateMachine: WaitBeforeStartState
08-29 09:54:19.278  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140045  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:19.278  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140046  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:19.279  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140046  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:19.279  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:19.280  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:19.280  1036  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:19.280  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 09:54:19.280  1036  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:19.281  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:19.281  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 09:54:19.282  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:19.282  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 09:54:19.282  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140050  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:19.283  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140050  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:19.283  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=140051  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 09:54:19.284  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14240] from screen [on:0 period:-716523244] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 09:54:19.286  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-716523242] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-29 09:54:19.286  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 09:54:19.287  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:19.291  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 09:54:19.292  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.293  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.293  1036  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-29 09:54:19.293  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.294  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:19.294  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.294  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.294  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:19.294  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.294  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.295  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 09:54:19.296  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=9,0,0
08-29 09:54:19.296  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=9,0,0
08-29 09:54:19.296  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 09:54:19.296  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 09:54:19.297  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 09:54:19.297  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 09:54:19.297  1036  1539 D WifiNative-wlan0: SET ps 0: returned true
08-29 09:54:19.297  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 09:54:19.297  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 09:54:19.298  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 09:54:19.298  1036  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 09:54:19.298  1036  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 09:54:19.298  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34860365 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:19.298  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34860365 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:19.298  1036  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 09:54:19.298  1036  7107 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:19.298  1036  7107 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 09:54:19.299  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:19.300   319   894 D CommandListener: Setting iface cfg
08-29 09:54:19.300   319   894 D CommandListener: Trying to bring up wlan0
08-29 09:54:19.301  1036  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 09:54:19.304  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-29 09:54:19.304  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 09:54:19.308  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 09:54:19.310  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.311  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 09:54:19.311  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 09:54:19.312  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.312  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:19.312  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.312  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.313  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.313  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 09:54:19.313  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 09:54:19.314  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 09:54:19.314  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 09:54:19.314  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 09:54:19.314  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:19.314  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:19.314  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 09:54:19.315  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 09:54:19.315  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 09:54:19.315  7033  7033 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 09:54:19.315  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 09:54:19.316  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
,08-29 09:54:19.320  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:19.320  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.320  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:19.322  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:19.327  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:19.331  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-29 09:54:19.332  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:19.332  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 09:54:19.333  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 09:54:19.333  1036  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 09:54:19.334  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 09:54:19.334  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
08-29 09:54:19.335  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.335  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:19.336  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.336  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.336  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.336  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 09:54:19.339  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 09:54:19.340  1036  1545 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 09:54:19.343  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.343  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.343  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-29 09:54:19.343  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 09:54:19.345  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 09:54:19.345  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.345  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.345  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 09:54:19.348  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:19.348  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.348  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:19.348  1036  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 09:54:19.349  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 09:54:19.352  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.352  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:54:19.352  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 09:54:19.355  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 09:54:19.357  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.357  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 09:54:19.358  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.361  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 09:54:19.362  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.362  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 09:54:19.363  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.364  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:54:19.364  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 09:54:19.364  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.366  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:19.372  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 09:54:19.372  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.373  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:19.376  1036  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 09:54:19.376  1036  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-29 09:54:19.377  1036  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 09:54:19.377  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:19.378   319   894 E Netd    : netlink response contains error (File exists)
08-29 09:54:19.378  1036  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 09:54:19.378  1036  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 09:54:19.379  1036  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 09:54:19.379  1036  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-29 09:54:19.380  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 09:54:19.380  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 09:54:19.380  1036  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 09:54:19.381  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 09:54:19.381  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:19.381  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:19.381  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-29 09:54:19.381  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.381  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 09:54:19.381  1036  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-29 09:54:19.381  1036  1545 D ConnectivityService:    accepting network in place of null
08-29 09:54:19.381  1036  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.381  1036  7104 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:19.381  1036  7104 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 09:54:19.381  1036  7104 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:19.381  1036  7104 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 09:54:19.382  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.382  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 09:54:19.383  1036  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 09:54:19.383  1036  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 09:54:19.383  1036  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.383  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:19.383  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 09:54:19.384  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 09:54:19.385   319  7113 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-29 09:54:19.387   319  7114 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 09:54:19.385  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 09:54:19.388  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 09:54:19.388  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 09:54:19.388  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:19.388  1036  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 09:54:19.389  1036  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 09:54:19.389  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 09:54:19.391  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 09:54:19.392  1036  1545 D ConnectivityService: validation of new default Network = false
08-29 09:54:19.392  1036  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 09:54:19.392  1036  1545 D DSQN    : enableDataServiceNotify 
08-29 09:54:19.392  1036  1545 D DSQN    : start dsqn bin
,08-29 09:54:19.399  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 09:54:19.394  7115  7115 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:19.394  7115  7115 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 09:54:19.400  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.400  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:19.400  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:19.400  1603  1835 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 09:54:19.401  1036  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 09:54:19.401  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:19.411  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:19.411  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.412  6213  6213 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 09:54:19.412  7115  7115 E DSQN    : DSQN ssw
,08-29 09:54:19.417  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:19.421  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 09:54:19.422  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:19.425  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:19.426  1818  7119 I CheckinService: active receiver: enabled
08-29 09:54:19.429  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 09:54:19.435  1818  7119 I CheckinService: Preparing to send checkin request
08-29 09:54:19.436  1818  7119 I EventLogService: Accumulating logs since 1472455616635
08-29 09:54:19.437   319  7113 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-29 09:54:19.440  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:19.441  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.441  6213  6213 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 09:54:19.442  6213  6213 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 09:54:19.442  6213  6213 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 09:54:19.444  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 09:54:19.445  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 09:54:19.446  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.446  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.448  6162  6162 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 09:54:19.448  6162  6162 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 09:54:19.451  6144  6144 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 09:54:19.455  6144  6144 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 09:54:19.460  6213  6213 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 09:54:19.460  6213  6213 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 09:54:19.461  6213  6213 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 09:54:19.461  6213  6213 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 09:54:19.461  6213  6213 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 09:54:19.469   319  7113 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 09:54:19.483  1818  7119 W EventLogAggregator: Unknown tag: snet_gcore
,08-29 09:54:19.483  1818  7119 W EventLogAggregator: Unknown tag: snet_launch_service
08-29 09:54:19.499  1036  7107 D DhcpStateMachine: DHCPV4 request on wlan0
,08-29 09:54:19.501  1036  7107 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-29 09:54:19.501  1036  7107 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 09:54:19.503   319   893 D LGDataListener: argv[0]=dsqncommand
08-29 09:54:19.503   319   893 D LGDataListener: argv[1]=wlan0
08-29 09:54:19.503   319   893 D LGDataListener: argv[2]=1
08-29 09:54:19.503   319   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-29 09:54:19.504  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-29 09:54:19.504  1036  1116 D DSQN    : start to monitor internet connection
08-29 09:54:19.504  7123  7123 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:19.504  7123  7123 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 09:54:19.516  7123  7123 I dhcpcd  : version 5.5.6 starting
08-29 09:54:19.518  7123  7123 E dhcpcd  : get_duid: m
08-29 09:54:19.518  7123  7123 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 09:54:19.518  5921  5994 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 767)
08-29 09:54:19.518  7123  7123 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 09:54:19.518  5921  5994 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 767)
,08-29 09:54:19.521  5921  5994 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 772)
08-29 09:54:19.522  5921  5994 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 09:54:19.522  5921  5994 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 773)
08-29 09:54:19.526  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.526  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ccc70e8 added. We now have 2 listener(s)
08-29 09:54:19.527  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.529  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.529  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.529  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.529  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.529  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18e2f301 added. We now have 9 listener(s)
08-29 09:54:19.529  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.529  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:19.533  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:19.534  1036  7104 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 07:54:19 GMT], X-Android-Received-Millis=[1472457259534], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472457259503]}
08-29 09:54:19.534  1818  7119 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-29 09:54:19.534  1036  7104 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 09:54:19.534  1036  7104 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-29 09:54:19.535  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-29 09:54:19.535  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 09:54:19.535  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:19.535  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:19.535  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 09:54:19.535  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-29 09:54:19.535  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 09:54:19.535  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.535  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:19.536  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:19.536  1036  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.536  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 09:54:19.536  1036  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.536  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:19.537  1603  1835 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 09:54:19.538  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:19.538  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 09:54:19.543  1036  1544 D WifiService: New client listening to asynchronous messages
08-29 09:54:19.544  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:19.544  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:19.544  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:19.544  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:19.544  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:19.544  5921  5994 V io.jxcore.node.Connect,ivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.544  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:19.544  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:19.546  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.547  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:19.547  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.547  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17c25be7 added. We now have 3 listener(s)
08-29 09:54:19.547  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.551  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.551  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.552  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.552  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.552  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.552  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@116bb394 added. We now have 10 listener(s)
08-29 09:54:19.552  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.552  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:19.552  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:19.552  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:19.552  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.552  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.552  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:19.552  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.552  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ccc70e8 removed from the list
08-29 09:54:19.552  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.553  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18e2f301 removed from the list
08-29 09:54:19.554  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.554  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:19.554  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.556  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.556  5921  5994 D org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:19.558  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.558  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.558  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.558  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18e2f301 not in the list
08-29 09:54:19.558  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.558  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.560  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.560  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.560  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.560  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@116bb394 removed from the list
08-29 09:54:19.560  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.560  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.560  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.560  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.560  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17c25be7 removed from the list
08-29 09:54:19.561  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 09:54:19.561  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.561  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@340abe3d added. We now have 2 listener(s)
08-29 09:54:19.561  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.562  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.562  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.562  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.562  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 09:54:19.562  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.563  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.563  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb7c632 added. We now have 9 listener(s)
08-29 09:54:19.563  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.563  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryMana,gerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:54:19.564  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:19.567  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:19.567  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:19.567  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:19.567  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:19.567  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:19.567  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.567  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:19.567  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:19.568  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.568  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:19.568  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.568  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1a7500 added. We now have 3 listener(s)
08-29 09:54:19.569  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 09:54:19.570  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.571  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.571  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.571  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.571  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aea0139 added. We now have 10 listener(s)
08-29 09:54:19.571  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.571  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:19.571  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:19.571  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:19.571  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:19.571  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:19.573  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.575  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.575  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:54:19.575  1036  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.579  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:19.580  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:54:19.581  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:19.581  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:54:19.582  5921  5994 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 09:54:19.582  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:19.582  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:19.584  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:19.584  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:19.584  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:19.584  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.584  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.584  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:19.584  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.584  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@340abe3d removed from the list
08-29 09:54:19.584  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.584  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb7c632 removed from the list
08-29 09:54:19.584  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:19.584  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.585  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.585  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.585  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.586  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.586  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.586  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb7c632 not in the list
08-29 09:54:19.586  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.586  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.586  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.587  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:54:19.587  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:19.587  7123  7123 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 09:54:19.587  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.587  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManag,er: dispose
08-29 09:54:19.587  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aea0139 removed from the list
08-29 09:54:19.587  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.587  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.587  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.587  7123  7123 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 09:54:19.587  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.587  7123  7123 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 09:54:19.587  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1a7500 removed from the list
08-29 09:54:19.587  7123  7123 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 09:54:19.587  7123  7123 D dhcpcd  : wlan0: sending REQUEST (xid 0x7b038605), next in 3.46 seconds
08-29 09:54:19.588  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.588  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1031e12c added. We now have 2 listener(s)
08-29 09:54:19.588  1036  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.590  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.590  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.590  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.590  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.590  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be077f5 added. We now have 9 listener(s)
08-29 09:54:19.590  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.591  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:19.594  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:19.597  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:19.597  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:19.597  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:19.597  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:19.597  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:19.597  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.597  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:19.597  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:19.599  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.599  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:19.599  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.599  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e20abfb added. We now have 3 listener(s)
08-29 09:54:19.600  1036  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.601  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.602  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.603  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.603  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.603  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.603  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.603  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1771e418 added. We now have 10 listener(s)
08-29 09:54:19.603  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.603  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:19.604  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:19.604  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:19.604  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:19.604  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:19.604  5921  59,94 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 09:54:19.607  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:54:19.607  1036  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.611  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:19.611  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:54:19.612  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:19.613  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:19.614  5921  5994 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 09:54:19.614  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:19.614  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:19.614  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:19.614  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.614  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.614  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:19.614  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.614  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1031e12c removed from the list
08-29 09:54:19.614  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.614  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be077f5 removed from the list
08-29 09:54:19.614  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:19.614  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.614  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.615  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.615  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.615  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.615  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.615  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be077f5 not in the list
08-29 09:54:19.615  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.615  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.616  5921  5994 I org.thalipro,ject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.616  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:54:19.616  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:19.617  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.617  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.617  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1771e418 removed from the list
08-29 09:54:19.617  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.617  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.617  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.617  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.617  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e20abfb removed from the list
08-29 09:54:19.617  7123  7123 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-29 09:54:19.617  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.618  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc40cd7 added. We now have 2 listener(s)
08-29 09:54:19.618  1036  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 09:54:19.620  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.620  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.620  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.620  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.620  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad29c4 added. We now have 9 listener(s)
08-29 09:54:19.620  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.621  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:54:19.623  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:19.626  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:19.626  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:19.626  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:19.626  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:19.626  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:19.626  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.626  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:19.626  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:19.627  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.628  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:19.628  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.628  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@110a1fe2 added. We now have 3 listener(s)
08-29 09:54:19.629  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.630  1036  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 09:54:19.631  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.632  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.632  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.632  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.632  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.633  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d29f73 added. We now have 10 listener(s)
08-29 09:54:19.633  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.633  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:19.633  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:19.633  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:19.633  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:19.633  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:19.635  7123  7123 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 09:54:19.635  7123  7123 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 09:54:19.635  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:54:19.635  7123  7123 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 09:54:19.635  7123  7123 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 09:54:19.635  1036  1712 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.635  7123  7123 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 09:54:19.636  7123  7123 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 09:54:19.636  7123  7123 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 09:54:19.636  7123  7123 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 09:54:19.639  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:19.640  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:54:19.642  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:19.642  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:19.644  5921  5994 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-29 09:54:19.646  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:19.646  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:19.646  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:19.646  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.646  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.646  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:19.646  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.646  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dc40cd7 removed from the list
08-29 09:54:19.646  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.647  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad29c4 removed from the list
08-29 09:54:19.647  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:19.647  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.648  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.648  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.649  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.649  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.649  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.649  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad29c4 not in the list
08-29 09:54:19.649  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.649  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.652  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.652  5921  5994 D BluetoothLeScanner: could not find callback wrapper
08-29 09:54:19.652  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:19.652  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.652  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.652  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d29f73 removed from the list
08-29 09:54:19.652  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.652  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.653  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09,:54:19.653  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.653  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@110a1fe2 removed from the list
08-29 09:54:19.653  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.653  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192e582e added. We now have 2 listener(s)
08-29 09:54:19.654  1036  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 09:54:19.658  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.658  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.659  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.659  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:19.659  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@392dbfcf added. We now have 9 listener(s)
08-29 09:54:19.659  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.660  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:54:19.664  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:19.669  5921  5994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:19.669  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:19.669  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 09:54:19.669  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:19.669  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:19.669  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.669  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:19.669  5921  5994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:19.670  5921  5994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:19.671  5921  5994 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:19.671  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:19.671  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c004865 added. We now have 3 listener(s)
08-29 09:54:19.671  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 09:54:19.673  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.675  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 09:54:19.675  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:19.675  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:19.675  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:19.675  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154bc93a added. We now have 10 listener(s)
08-29 09:54:19.675  5921  5994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:19.676  5921  5994 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:19.676  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:19.676  5921  5994 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:19.676  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.676  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.676  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:19.676  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.676  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192e582e removed from the list
08-29 09:54:19.676  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.676  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@392dbfcf removed from the list
08-29 09:54:19.680  5921  5921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:19.681  5921  5994 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:19.681  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.681  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.681  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.682  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.682  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.682  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.682  5921  5994 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@392dbfcf not in the list
08-29 09:54:19.682  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given liste,ner does not exist in the list - probably already removed
08-29 09:54:19.682  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.683  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:19.684  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:19.684  5921  5994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:19.684  5921  5994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154bc93a removed from the list
08-29 09:54:19.684  5921  5994 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:19.684  5921  5994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:19.684  5921  5994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:19.684  5921  5994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:19.684  5921  5994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c004865 removed from the list
,08-29 09:54:19.687  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 09:54:19.687  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 09:54:19.687  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 09:54:19.687  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:19.688  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 09:54:19.688  5921  5994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:19.699  5921  7138 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 780, name: My test thread name)
08-29 09:54:19.700  5921  7138 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 780, thread name: My test thread name)
08-29 09:54:19.700  5921  7138 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 780, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 09:54:19.702  5921  7139 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 782, name: My test thread name)
08-29 09:54:19.703  5921  7139 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 782, thread name: My test thread name)
08-29 09:54:19.703  5921  7139 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 782, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 09:54:19.706  5921  5994 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 09:54:19.706  5921  5994 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 09:54:19.706  5921  5994 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 09:54:19.706  5921  5994 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 09:54:19.706  5921  5994 D com.test.thalitest.ThaliTestRunner: Total duration: 22739 ms
08-29 09:54:19.712  5921  5994 I jxcore-log: Total number of executed tests:  80
08-29 09:54:19.712  5921  5994 I jxcore-log: 
08-29 09:54:19.712  5921  5994 I jxcore-log: Number of passed tests:  80
08-29 09:54:19.712  5921  5994 I jxcore-log: 
08-29 09:54:19.712  5921  5994 I jxcore-log: Number of failed tests:  0
08-29 09:54:19.712  5921  5994 I jxcore-log: 
08-29 09:54:19.712  5921  5994 I jxcore-log: Number of ignored tests:  0
08-29 09:54:19.712  5921  5994 I jxcore-log: 
08-29 09:54:19.712  5921  5994 I jxcore-log: Total duration:  22739
08-29 09:54:19.712  5921  5994 I jxcore-log: 
08-29 09:54:19.713  5921  5994 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 09:54:19.713  5921  5994 I jxcore-log: 
08-29 09:54:19.718  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.718  5921  5994 I jxcore-log: 
08-29 09:54:19.722  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.722  5921  5994 I jxcore-log: 
08-29 09:54:19.724  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.724  5921  5994 I jxcore-log: 
,08-29 09:54:19.727  5921  5921 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 09:54:19.728  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.728  5921  5994 I jxcore-log: 
08-29 09:54:19.730  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.730  5921  5994 I jxcore-log: 
08-29 09:54:19.732  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.732  5921  5994 I jxcore-log: 
08-29 09:54:19.737  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.737  5921  5994 I jxcore-log: 
,08-29 09:54:19.740  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:54:19.740  5921  5994 I jxcore-log: 
08-29 09:54:19.742  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.742  5921  5994 I jxcore-log: 
08-29 09:54:19.743  1036  1642 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7144 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-29 09:54:19.743  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.743  5921  5994 I jxcore-log: 
08-29 09:54:19.744  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.744  5921  5994 I jxcore-log: 
08-29 09:54:19.746  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.746  5921  5994 I jxcore-log: 
08-29 09:54:19.747  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.747  5921  5994 I jxcore-log: 
,08-29 09:54:19.748  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.748  5921  5994 I jxcore-log: 
08-29 09:54:19.749  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.749  5921  5994 I jxcore-log: 
08-29 09:54:19.750  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.750  5921  5994 I jxcore-log: 
08-29 09:54:19.751  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.751  5921  5994 I jxcore-log: 
08-29 09:54:19.751  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:19.751  5921  5994 I jxcore-log: 
08-29 09:54:19.752  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.752  5921  5994 I jxcore-log: 
08-29 09:54:19.753  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:19.753  5921  5994 I jxcore-log: 
08-29 09:54:19.754  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:19.754  5921  5994 I jxcore-log: 
08-29 09:54:19.755  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:19.755  5921  5994 I jxcore-log: 
08-29 09:54:19.756  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:19.756  5921  5994 I jxcore-log: 
08-29 09:54:19.757  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:19.757  5921  5994 I jxcore-log: 
08-29 09:54:19.757  5921  5994 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:19.757  5921  5994 I jxcore-log: 
,08-29 09:54:19.791  7144  7144 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 09:54:19.791  7144  7144 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 09:54:19.835  7144  7144 I MultiDex: VM with version 2.1.0 has multidex support
08-29 09:54:19.835  7144  7144 I MultiDex: install
08-29 09:54:19.835  7144  7144 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 09:54:19.847  7144  7144 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-29 09:54:19.851  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-29 09:54:19.859  2214  2214 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-29 09:54:19.860  2214  2214 D c       : Getting all permits...
08-29 09:54:19.860  2214  2214 D a       : Opening database...
,08-29 09:54:19.866  2214  2214 D a       : Opening database auth.proximity.permit_store...
,08-29 09:54:19.867  2214  2214 D a       : Closing database...
08-29 09:54:19.905  1036  7107 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 09:54:19.906  1036  7107 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 09:54:19.907  1036  7107 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 09:54:19.907  1036  7107 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 09:54:19.907  1036  7107 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 09:54:19.907  1036  7107 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 09:54:19.907  1036  7107 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 09:54:19.907  1036  7107 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-29 09:54:19.908  1036  7107 D DhcpStateMachine: RunningState
,08-29 09:54:19.991  7167  7167 D AndroidRuntime: 
08-29 09:54:19.991  7167  7167 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 09:54:19.993  7167  7167 D AndroidRuntime: CheckJNI is OFF
,08-29 09:54:20.176  7167  7167 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-29 09:54:20.193  1036  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-29 09:54:20.193  1036  1114 I ActivityManager: Killing 5921:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-29 09:54:20.264  1036  1783 I WindowState: WIN DEATH: Window{1bcf637f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 09:54:20.264  1036  1544 D WifiService: Client connection lost with reason: 4
,08-29 09:54:20.272  1036  1783 D InputDispatcher: Window went away: Window{1bcf637f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 09:54:20.403  1036  1114 E libprocessgroup: failed to kill 1 processes for processgroup 5921
,08-29 09:54:20.407  1036  1114 I ActivityManager:   Force finishing activity ActivityRecord{1912b9d8 u0 com.test.thalitest/.MainActivity t6}
,08-29 09:54:20.431   346   350 E GBMv2   : DFP En is all cleared set to be enabled
08-29 09:54:20.432  1036  2017 W ActivityManager: Spurious death for ProcessRecord{2f268b9a 5921:com.test.thalitest/u0a118}, curProc for 5921: null
08-29 09:54:20.433  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 09:54:20.434  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b443c4a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 09:54:20.434  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 09:54:20.435  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{11a867bb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 09:54:20.435  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-29 09:54:20.436  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{1912b9d8 u0 com.test.thalitest/.MainActivity t6 f}
08-29 09:54:20.436  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{1912b9d8 u0 com.test.thalitest/.MainActivity t6 f}
,08-29 09:54:20.448  7144  7162 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:54:20.448  7144  7162 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 09:54:20.465  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-29 09:54:20.468  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-29 09:54:20.469  3644  3644 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 09:54:20.473  6871  6871 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 09:54:20.473  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 09:54:20.479  2511  2669 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 09:54:20.481  4390  4390 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 09:54:20.481  4390  4390 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 09:54:20.481  4390  4390 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 09:54:20.481  4390  4390 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 09:54:20.481  4390  4390 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 09:54:20.481  4390  4390 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 09:54:20.481  4390  4390 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 09:54:20.481  4390  4390 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 09:54:20.481  4390  4390 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:20.481  4390  4390 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-29 09:54:20.481  4390  4390 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 09:54:20.481  1036  1428 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 09:54:20.481  4390  4390 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-29 09:54:20.509  1036  1905 V SIM_STK : Menu title from STK is T-Mobile
,08-29 09:54:20.520  4505  4505 I art     : Explicit concurrent mark sweep GC freed 763(44KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 649us total 66.331ms
08-29 09:54:20.540  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-29 09:54:20.542  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-29 09:54:20.543  3672  3672 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 09:54:20.544  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 09:54:20.545  2034  2149 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-29 09:54:20.549  1036  1036 D administrator: Handling package changes for user 0
08-29 09:54:20.585  1036  1113 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-29 09:54:20.605  1036  1783 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7189 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 09:54:20.610  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-29 09:54:20.612   362   362 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 302us total 13.789ms
08-29 09:54:20.614  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 09:54:20.615  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-29 09:54:20.616  3644  4382 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-29 09:54:20.627  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-29 09:54:20.636  1036  1960 V SIM_STK : Menu title from STK is T-Mobile
08-29 09:54:20.636  1036  1960 V SIM_STK : Menu title from STK is T-Mobile
,08-29 09:54:20.637   362   362 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 21.428ms
08-29 09:54:20.645  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-29 09:54:20.645  1871  1871 D SplitUIService: removed split : 
08-29 09:54:20.657   362   362 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 19.389ms
,08-29 09:54:20.662  2214  2214 I ConfigService: onCreate
08-29 09:54:20.662  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 09:54:20.664  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 09:54:20.665  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 09:54:20.666  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 09:54:20.669  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-29 09:54:20.669  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 09:54:20.670  3644  4382 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-29 09:54:20.671  3644  4367 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 09:54:20.673  2214  2214 I ConfigService: onBind returning update interface
08-29 09:54:20.686  1036  1996 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , display: false
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , animation: false }
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 09:54:20.687  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 09:54:20.687  6871  6871 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , display: false
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , animation: false }
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , display: false
08-29 09:54:20.687  2034  2034 I GBoardWebViewUtils: , animation: false }
08-29 09:54:20.688  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms, } action com.google.android.gms.config.START
08-29 09:54:20.688  2214  2214 I ConfigService: onBind returning config service
,08-29 09:54:20.690  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 09:54:20.690  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 09:54:20.694  2034  7208 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 09:54:20.696  1818  1818 I ConfigFetchService: service connected
08-29 09:54:20.705  2214  2214 I ConfigService: onDestroy
08-29 09:54:20.705  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-29 09:54:20.705  1871  1871 I SplitUIService: split app #11
,08-29 09:54:20.707  1818  7210 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 09:54:20.708  7189  7189 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-29 09:54:20.723  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 09:54:20.724  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-29 09:54:20.729  1036  1712 V SIM_STK : Menu title from STK is T-Mobile
,08-29 09:54:20.744  7212  7212 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-29 09:54:20.748  1036  1642 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7216 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 09:54:20.796  1603  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 09:54:20.796  1603  1652 D KeyguardModel: createShortcutInfo...
08-29 09:54:20.800  1603  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 09:54:20.800  1603  1652 D KeyguardModel: createShortcutInfo...
08-29 09:54:20.803  7212  7212 I dex2oat : dex2oat took 59.201ms (threads: 4)
08-29 09:54:20.803  1603  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 09:54:20.804  1603  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:54:20.804  1603  1652 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-29 09:54:20.806  1603  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 09:54:20.806  1603  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 09:54:20.806  1603  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 09:54:20.807  1603  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 09:54:20.807  1603  1652 D KeyguardModel: createShortcutInfo...
08-29 09:54:20.810  1603  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 09:54:20.810  1603  1652 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 09:54:20.811  1603  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 09:54:20.811  1603  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 09:54:20.816  1603  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 09:54:20.816  1603  1652 D KeyguardModel: createShortcutInfo...
,08-29 09:54:20.820  7144  7162 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 09:54:20.820  7144  7162 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 09:54:20.820  7144  7162 I Adreno-EGL: Build Date: 12/12/14 금
08-29 09:54:20.820  7144  7162 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 09:54:20.820  7144  7162 I Adreno-EGL: Remote Branch: 
08-29 09:54:20.820  7144  7162 I Adreno-EGL: Local Patches: 
08-29 09:54:20.820  7144  7162 I Adreno-EGL: Reconstruct Branch: 
08-29 09:54:20.821  1603  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:54:20.821  1603  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 09:54:20.821  1603  1652 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 09:54:20.821  1603  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 09:54:20.822  1603  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 09:54:20.822  1603  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 09:54:20.835  1603  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 09:54:20.835  1603  1652 D KeyguardModel: createShortcutInfo...
,08-29 09:54:20.836  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 09:54:20.837  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 09:54:20.837  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 09:54:20.839  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-29 09:54:20.846  5490  7239 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-29 09:54:20.850  1036  1923 I ActivityManager: Killing 6557:com.lge.email/u0a23 (adj 15): empty #17
,08-29 09:54:20.857  1818  7241 I PeopleContactsSync: CP2 sync disabled
08-29 09:54:20.884   339   425 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 09:54:20.884  3222  7242 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-29 09:54:20.886  7216  7216 I AppUp4:AppBoxCP: onCreate
08-29 09:54:20.886  7216  7216 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-29 09:54:20.891  7216  7216 I AppUp4:DB:  setFingerPrint start
08-29 09:54:20.891  7216  7216 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 09:54:20.897  7216  7216 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 09:54:20.897  7216  7216 I AppUp4:DB:  SDK version = 21
08-29 09:54:20.897  7216  7216 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-29 09:54:20.900  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-29 09:54:20.902  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 09:54:20.904  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 09:54:20.905  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 09:54:20.906  7144  7162 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 09:54:20.906  7144  7162 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 09:54:20.906  7144  7162 I Adreno-EGL: Build Date: 12/12/14 금
08-29 09:54:20.906  7144  7162 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 09:54:20.906  7144  7162 I Adreno-EGL: Remote Branch: 
08-29 09:54:20.906  7144  7162 I Adreno-EGL: Local Patches: 
08-29 09:54:20.906  7144  7162 I Adreno-EGL: Reconstruct Branch: 
08-29 09:54:20.906  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 09:54:20.907  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-29 09:54:20.923  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-29 09:54:20.923  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 09:54:20.924  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 09:54:20.924  2034  2813 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 09:54:20.924  2034  2813 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-29 09:54:20.939  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-29 09:54:20.940  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-29 09:54:20.940  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 09:54:20.947  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 09:54:20.952  7144  7162 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 09:54:20.952  7144  7162 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 09:54:20.952  7144  7162 I Adreno-EGL: Build Date: 12/12/14 금
08-29 09:54:20.952  7144  7162 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 09:54:20.952  7144  7162 I Adreno-EGL: Remote Branch: 
08-29 09:54:20.952  7144  7162 I Adreno-EGL: Local Patches: 
08-29 09:54:20.952  7144  7162 I Adreno-EGL: Reconstruct Branch: 
,08-29 09:54:20.956  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-29 09:54:20.956  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 09:54:20.959  1036  1783 W libprocessgroup: failed to open /acct/uid_10023/pid_6557/cgroup.procs: No such file or directory
08-29 09:54:20.964  1818  4658 I Icing   : doRemovePackageData com.test.thalitest
,08-29 09:54:20.965  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3efc5e76 u0 com.lge.launcher2/.Launcher t5} time:141749
08-29 09:54:20.967  2034  2034 D [Concierge]WidgetView: change position of spinner
08-29 09:54:20.968  7216  7216 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-29 09:54:20.968  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472457260968
08-29 09:54:20.968  2608  2608 D [Concierge]Service: onStartCommand(). Type : 8
08-29 09:54:20.968  2608  2608 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-29 09:54:20.970  1603  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 09:54:20.970  1603  1652 D KeyguardModel: createShortcutInfo...
08-29 09:54:20.971  2608  2608 D [Concierge]Service: Update widget ID : 11
08-29 09:54:20.971  2608  2608 D [Concierge]Service: onStartCommand(). Type : 0
08-29 09:54:20.972  1603  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 09:54:20.972  1603  1652 D KeyguardModel: createShortcutInfo...
08-29 09:54:20.973  1603  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 09:54:20.974  1603  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-29 09:54:20.982  1603  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 09:54:20.982  1603  1652 D KeyguardModel: createShortcutInfo...
08-29 09:54:20.984  1603  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 09:54:20.984  1603  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 09:54:20.986  1036  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 09:54:20.986  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 09:54:20.986  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 09:54:20.986  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 09:54:20.987  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 09:54:20.987  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 09:54:20.987  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-29 09:54:20.988  1036  1545 D ConnectivityService: identical MTU - not setting
08-29 09:54:20.988  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 09:54:20.988  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 09:54:20.988  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:20.988  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:20.988  1036  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 09:54:20.989  1603  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 09:54:20.989  1603  1652 D KeyguardModel: createShortcutInfo...
08-29 09:54:20.989  1603  1835 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 09:54:20.990  1603  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 09:54:20.990  1603  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 09:54:20.991  1603  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 09:54:20.991  1603  1652 D KeyguardModel: createShortcutInfo...
08-29 09:54:20.999  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-29 09:54:20.999  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-29 09:54:21.005  1036  1124 I art     : Explicit concurrent mark sweep GC freed 85527(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 2.127ms total 392.246ms
,08-29 09:54:21.037  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 09:54:21.050  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-29 09:54:21.051  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 744195182
08-29 09:54:21.052  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 09:54:21.052  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 09:54:21.052  7216  7216 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-29 09:54:21.055  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1ea0d74a
08-29 09:54:21.055  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-29 09:54:21.058  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 09:54:21.058  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 09:54:21.063  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 09:54:21.064  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 09:54:21.074  1818  7213 I art     : Explicit concurrent mark sweep GC freed 20731(1439KB) AllocSpace objects, 19(304KB) LOS objects, 51% free, 29MB/61MB, paused 704us total 93.615ms
,08-29 09:54:21.077   362   362 I art     : Background concurrent mark sweep GC freed 789(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 10.762ms total 19.857ms
08-29 09:54:21.080  1818  1830 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-29 09:54:21.080  1818  1830 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-29 09:54:21.080  1818  1830 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-29 09:54:21.085  1036  1052 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7247 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-29 09:54:21.085  1036  1052 I ActivityManager: Killing 6611:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-29 09:54:21.121  7167  7167 D AndroidRuntime: Shutting down VM
,08-29 09:54:21.145  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472457147378, New one : 1472457260968
08-29 09:54:21.146  2034  2034 D [Concierge]WidgetView: Unregister all receivers
,08-29 09:54:21.146  1036  1576 W libprocessgroup: failed to open /acct/uid_10046/pid_6611/cgroup.procs: No such file or directory
08-29 09:54:21.146  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 09:54:21.161  7247  7247 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:54:21.161  7247  7247 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 09:54:21.161  7247  7247 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 09:54:21.165  7247  7247 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 09:54:21.165  7247  7247 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-29 09:54:21.182  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7264 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 09:54:21.184  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 09:54:21.184  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 09:54:21.186  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 09:54:21.188  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-29 09:54:21.189  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 09:54:21.190  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 09:54:21.191  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 09:54:21.192  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 09:54:21.196  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 09:54:21.196  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 09:54:21.196  1818  7238 W GmsApplication: Using Auth Proxy for data requests.
,08-29 09:54:21.200  1818  7238 W GmsApplication: Using Auth Proxy for data requests.
08-29 09:54:21.231  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-29 09:54:21.240  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-29 09:54:21.240  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-29 09:54:21.241  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 09:54:21.255  7247  7247 I SystemConfig: BUILD Country: EU
08-29 09:54:21.255  7247  7247 I SystemConfig: BUILD Operator: OPEN
,08-29 09:54:21.264  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ab5dfdb time:142049
08-29 09:54:21.270  1036  1960 I ActivityManager: Killing 6664:com.android.chrome/u0a57 (adj 15): empty #17
,08-29 09:54:21.285   319  7283 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-29 09:54:21.286   319  7283 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-29 09:54:21.334   319  7283 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-29 09:54:21.356  1036  1987 W libprocessgroup: failed to open /acct/uid_10057/pid_6664/cgroup.procs: No such file or directory
,08-29 09:54:21.360  1036  2051 I ActivityManager: Killing 6691:com.lge.drmservice/u0a62 (adj 15): empty #17
08-29 09:54:21.372  2214  2234 I art     : Explicit concurrent mark sweep GC freed 4323(242KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 28MB/60MB, paused 591us total 15.932ms
,08-29 09:54:21.398  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-29 09:54:21.427  1036  1052 W libprocessgroup: failed to open /acct/uid_10062/pid_6691/cgroup.procs: No such file or directory
,08-29 09:54:21.428  7247  7284 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-29 09:54:21.428  7247  7284 I SystemConfig: existFile = false
08-29 09:54:21.428  7247  7284 I SystemConfig: canReadFile = false
08-29 09:54:21.428  7247  7284 I SystemConfig: systemFeature RCS result false
08-29 09:54:21.428  7247  7284 D SystemConfig: refreshRcsSupport() :false
08-29 09:54:21.437  2352  7288 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 09:54:21.439  2034  2863 I GBoardtInterface: onReloaded()
,08-29 09:54:21.441  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-29 09:54:21.461  1036  1783 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7289 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 09:54:21.463  3644  4367 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 09:54:21.465  3644  3660 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 09:54:21.472  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-29 09:54:21.474  3644  4382 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 09:54:21.474  3644  4382 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-29 09:54:21.477  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-29 09:54:21.478  3644  4382 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 09:54:21.478  3644  4382 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 09:54:21.478  3644  4382 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-29 09:54:21.478  3644  4382 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-29 09:54:21.478  3644  4367 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 09:54:21.481  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-29 09:54:21.481  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-29 09:54:21.483  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-29 09:54:21.483  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 09:54:21.486  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-29 09:54:21.486  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-29 09:54:21.498  7289  7289 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:54:21.498  7289  7289 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 09:54:21.499  7289  7289 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 09:54:21.499  7289  7289 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 09:54:21.553  7289  7289 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 09:54:21.560  7289  7289 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-29 09:54:21.569  1818  7119 W System.err: FileClientSessionCache: Error writing session data for android.clients.google.com to /data/data/com.google.android.gms/app_sslcache/android.clients.google.com.443.
08-29 09:54:21.569  1818  7119 W System.err: java.io.FileNotFoundException: /data/data/com.google.android.gms/app_sslcache/android.clients.google.com.443: open failed: EROFS (Read-only file system)
,08-29 09:54:21.570  1818  7119 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 09:54:21.570  1818  7119 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:21.570  1818  7119 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:21.570  1818  7119 W System.err: 	at com.android.org.conscrypt.FileClientSessionCache$Impl.putSessionData(FileClientSessionCache.java:204)
08-29 09:54:21.570  1818  7119 W System.err: 	at com.android.org.conscrypt.ClientSessionContext.putSession(ClientSessionContext.java:120)
08-29 09:54:21.570  1818  7119 W System.err: 	at com.android.org.conscrypt.SSLParametersImpl.setupSession(SSLParametersImpl.java:585)
08-29 09:54:21.570  1818  7119 W System.err: 	at com.android.org.conscrypt.OpenSSLSocketImpl.startHandshake(OpenSSLSocketImpl.java:344)
08-29 09:54:21.570  1818  7119 W System.err: 	at android.net.SSLCertificateSocketFactory.verifyHostname(SSLCertificateSocketFactory.java:190)
08-29 09:54:21.570  1818  7119 W System.err: 	at android.net.SSLCertificateSocketFactory.createSocket(SSLCertificateSocketFactory.java:435)
08-29 09:54:21.570  1818  7119 W System.err: 	at com.android.okhttp.Connection.upgradeToTls(Connection.java:171)
08-29 09:54:21.570  1818  7119 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:151)
08-29 09:54:21.570  1818  7119 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:276)
08-29 09:54:21.570  1818  7119 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:208)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.google.android.gms.checkin.f.a(SourceFile:302)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.google.android.gms.checkin.f.a(SourceFile:210)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.google.android.gms.checkin.c.a(SourceFile:375)
08-29 09:54:21.571  1818  7119 W System.err: 	at com.google.android.gms.checkin.c.doInBackground(SourceFile:365)
08-29 09:54:21.571  1818  7119 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
08-29 09:54:21.571  1818  7119 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 09:54:21.571  1818  7119 W System.err: 	at java.lang.Thread.run(Thread.java:818)
08-29 09:54:21.571  1818  7119 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:21.572  1818  7119 W System.err: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:21.572  1818  7119 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:21.572  1818  7119 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 09:54:21.572  1818  7119 W System.err: 	... 24 more
08-29 09:54:21.582  7289  7289 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 09:54:21.595  1818  7119 I CheckinTask: Sending checkin request (7936 bytes)
08-29 09:54:21.606  7289  7289 D LgDataFeature: LgDataFeature() Constructor: none
08-29 09:54:21.606  7289  7289 D LgDataFeature: LgDataFeature() Constructor Done, null

```
